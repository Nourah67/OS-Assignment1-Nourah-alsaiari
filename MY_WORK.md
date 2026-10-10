# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Nourah Hassan Omar ALsaiari] |
| **Student ID** | [445052639] |
| **University Email** | [445052639@std.psau.edu.sa] |
| **GitHub Username** | [Nourah67] |
| **Repository Link** | [https://github.com/Nourah67/OS-Assignment1-Nourah-alsaiari] |
 
---

## 🎥 Video Link

**Video Link**: [https://drive.google.com/file/d/1vqyUaCG-6Cqm6QNSBMgCp5fPgRYXaHGj/view?usp=sharing]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [October 8, 2026]
**What I did**: Started working on the Operating Systems assignment.

**Details**:
- Read the assignment instructions in README.md.
- Opened SchedulerSimulation.java and reviewed the existing code
- Ran the original program and observed its output.
- Started understanding how the Round-Robin scheduling algorithm works.
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**:  Understanding how the scheduler manages processes and threads.

**Solution**: Read the code carefully and observed the program output to understand the execution flow.

**Time spent**: 1 hour and 30 minutes

---

## Your Development Log

### Entry 1 - [October 9, 2026]
**What I did**:Worked on implementing Feature 1: Process Priority.

**Details**:1-Reviewed the Process class and the scheduler logic.
2-Worked on adding priority information to processes.
3-Tested the code several times to check the changes.
4-Compared the output before and after the modification.

**Challenges**:This feature took me longer than expected because I needed time to understand the existing code and make the changes correctly.

**Solution**:  I reviewed the code step by step and tested the program after making changes.

**Time spent**: 3 hour

---

### Entry 2 - [October 9, 2026]
**What I did**: Worked on Feature 2: Context Switch Counter.

**Details**:1-Reviewed the scheduler loop to understand when context switches occur.
2-Worked on adding a counter to track context switches.
3-Checked where the counter should be updated.
4-Ran the program and reviewed the output

**Challenges**: Identifying the correct place to count context switches without counting them incorrectly.

**Solution**: Reviewed the scheduler logic and tested the program to check the counter.

**Time spent**: 1 hour

---

### Entry 3 - [October 10, 2026]
**What I did**:Worked on Feature 3: Waiting Time Tracking.

**Details**: 1-Reviewed the scheduling code to understand how waiting time is calculated.
2-Worked on tracking the waiting time for each process.
3-Checked how the results should appear in the output table.
4-Ran the program and reviewed the results.

**Challenges**:Understanding how to calculate waiting time correctly and display it in the final summary.

**Solution**: Reviewed the scheduling logic and tested the program to check the calculated values.

**Time spent**: 2 hours

---

### Entry 4 - [October 10, 2026]
**What I did**:Tested the program after adding the new features.

**Details**:1-Ran the program to check that it worked correctly.
2-Reviewed the output for the three features.
3-Checked the results and looked for errors.

**Challenges**: Making sure all the features worked correctly together.

**Solution**: Ran the program and reviewed the output to identify any problems.

**Time spent**: 45 menuts

---

### Entry 5 - [October 10, 2026]
**What I did**:Reviewed my Git commit history,
and Checked that my changes were saved in the repository,
Organized my work to make sure each feature had its own commit.

**Details**:Reviewed the saved commits and checked the changes made during the assignment.

**Challenges**:Making sure the commits clearly showed the work completed for each feature.

**Solution**:Reviewed the commit history and checked the saved changes.

**Time spent**: 30 menuts

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [10 hours]

**Most challenging part**:The most challenging part was implementing the features and understanding how they worked with the existing code.

**Most interesting learning**:I learned how process priority, context switches, and waiting time work in a scheduling simulation.

**What I would do differently next time**:I would start earlier, divide the work into smaller tasks, and test each change step by step.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned that multithreading allows a program to perform multiple tasks concurrently. Each thread has its own execution path, but threads may share resources. I also learned that the CPU scheduler manages how processes or threads get CPU time. Context switching allows the CPU to switch between tasks. Different scheduling methods can affect performance and fairness. This assignment helped me understand scheduling concepts better through coding and testing.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part was implementing the new features without affecting the original code. I had difficulty understanding how to add process priority correctly. I also needed to understand how to count context switches and calculate waiting time. Sometimes, I had to check the output more than once. Testing the program helped me find and understand problems. This experience taught me to be patient and check my code carefully.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by reviewing the code and understanding each part step by step. I tested the program after adding each feature. When the output was not correct, I checked my changes and tried again. I also reviewed the scheduling logic to understand how the features worked. Testing helped me find problems and improve my code. In the end, I learned the importance of patience and debugging.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is useful in many real-world applications. For example, an operating system uses scheduling to share CPU time between different running programs. Round-Robin scheduling gives each process a time quantum to run. Another example is a web browser, which can perform different tasks while keeping the user interface responsive. Threads can help applications handle multiple tasks efficiently. Context switching allows the CPU to move between tasks. These concepts help me understand how applications manage their work.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is a program that is running, while a thread is a unit of execution within a process. A process has its own memory space, while threads in the same process can share memory and resources. In my assignment, each process in the simulation is represented by a thread. The Thread.start() method starts the thread's execution, while Thread.join() waits for it to finish.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[The ready queue stores processes waiting for CPU time. In my assignment, the Round-Robin scheduler uses a FIFO order to select processes. Each process gets a turn to run for a limited time called the time quantum. If a process does not finish, it goes back to the end of the queue. The priority feature displays a priority value, but it does not change the queue order.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is in the New state when a new Thread object is created in the addProcessToQueue() method. At this point, the thread has been created but has not started running yet.]

2. **Runnable**: [P1 enters the Runnable state when the scheduler calls currentThread.start(). This makes the thread eligible to run when the CPU scheduler gives it a chance.]

3. **Running**: [P1 is Running when the CPU executes its run() method. During this state, P1 performs its assigned work according to the time quantum.]

4. **Waiting**: [P1's thread can enter the Timed Waiting state when Thread.sleep() pauses it for a specified time. Meanwhile, the main scheduler thread waits for P1 to finish its turn when it calls currentThread.join().]

5. **Terminated**: [P1 enters the Terminated state when its run() method finishes execution. Once a Java thread is terminated, it cannot be started again, so the program must create a new Thread object if the process needs another turn.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [CPU Scheduling]

**Description**:
[An operating system manages multiple programs that need CPU time. Round-Robin gives each process a limited time quantum to execute. If a process does not finish, it returns to the end of the ready queue.]

**Why Round-Robin works well here**:
[Round-Robin provides fairness because each process gets a turn. It also improves responsiveness by allowing other processes to run instead of letting one process use the CPU continuously.]

### Example 2: [Web Browser]

**Description**:
[A web browser can perform multiple tasks, such as loading webpages and responding to user actions. Threads help the application manage different tasks.]

**Why Round-Robin works well here**:
[Round-Robin can share CPU time between tasks that are ready to run. This helps prevent one task from monopolizing CPU time and can improve responsiveness.]

## Summary

**Key concepts I understood through these questions:**
1.The difference between a process and a thread.
2.How Round-Robin scheduling and the ready queue work.
3.How thread states change during execution.

**Concepts I need to study more:**
1.Calculating waiting time and turnaround time accurately.
2.Understanding thread synchronization and context switching in more detail.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [✅ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [✅ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ✅] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [✅ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ✅] Code compiles and runs with no errors
- [✅ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [✅ ] Each feature has clear comments

**Commits**
- [ ✅] **At least 3 meaningful commits, ideally 6 or more**
- [✅ ] **One commit per feature**
- [✅ ] Commits are spread over **different dates** (not all in the last hour)
- [✅ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ✅] Full name and student ID filled in at the top
- [✅ ] Development log has **5+ entries** on different dates
- [ ✅] Reflection: 4 questions, 5-7 sentences each
- [✅ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [✅ ] No `[...]` placeholders left
- [✅ ] No section headers deleted

**Video**
- [ ✅] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ✅] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ✅] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ✅] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
