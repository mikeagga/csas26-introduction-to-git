---
title: "Introduction to Git Supplementary Homework assignment"
author: "Michael Agosino"
date: today
---

---

# Git Fundamentals - Homework Assignment

---

## Instructions

Complete each section in order. For each task, you will include the required Git
commands and terminal output as evidence of your work. You may submit your
answers in a markdown file committed to a Git repository (how fitting).

---

## Part 1: Setup 

1. Create a new directory called `git_homework` and initialize a Git repository
   inside it.
2. Configure your global `user.name` and `user.email` if they are not already
   set.
3. Run `git config --list` and paste the relevant output showing your name,
   email, and default branch.

**Submit:** The commands you ran and the relevant output from `git config
--list`.

---

## Part 2: Your First Commits

1. Create a file called `about.md`. Inside it, write a short paragraph about
   yourself.
2. Check the status of the repository. What state is `about.md` in? Why?
3. Stage `about.md` and check the status again. What changed and why?
4. Commit the file with an appropriate commit message.
5. Create a second file called `goals.md`. Write three things you hope to learn
   this semester. Stage and commit it.
6. Run `git log` and paste the output.

**Submit:** The commands you ran and the output of `git log`.

---

## Part 3: Inspecting Git Objects

Using `git cat-file -p`, inspect the internals of your most recent commit.

1. Run `git log` and copy your latest commit hash.
2. Use `git cat-file -p` on the commit hash. Paste the output. Identify and
label the following:
   - The **tree hash**
   - The **parent hash** (if one exists)
   - The **commit message**
3. Use `git cat-file -p` on the tree hash. Paste the output. What does each line
represent?
4. Use `git cat-file -p` on one of the blob hashes. What is the output?
5. In your own words, explain the relationship between a commit, a tree, and a
blob.

**Submit:** Your commands, their outputs, and your written explanation.

---

## Part 4: Branching and Merging

1. Create a new branch called `feature` and switch to it.
2. Create a file called `feature_notes.md` and write a few sentences describing
a feature you would add to an imaginary app. Commit it to the `feature` branch.
3. Switch back to `main` and create a file called `main_notes.md` with any
content. Commit it to `main`.
4. Run the following and paste the output: ```bash git log --oneline --graph
--all --decorate --parents ```
5. **Without merging yet**, explain in your own words why a fast-forward merge
is not possible at this point.
6. Rebase `feature` onto `main`. Paste the output of `git log --oneline --graph
--all --decorate --parents` after rebasing.
7. Switch back to `main` and perform a fast-forward merge of `feature`.
8. Delete the `feature` branch.
9. Paste the final output of `git log --oneline --graph --all --decorate
--parents`.

**Submit:** Your commands, their outputs, and your written explanation from step
5.

---

## Part 5: Resetting

1. Create a file called `oops.md` with any content. Stage and commit it with the
message `"oops commit"`.
2. Run `git log --oneline` and paste the output.
3. Perform a **soft reset** to undo the commit.
   - What does `git status` show after the reset? Why?
   - Re-commit the file with a corrected message: `"intentional commit"`.
4. Create another file called `mistake.md` with any content. Commit it.
5. Perform a **hard reset** to undo this commit.
   - Run `ls`. Is `mistake.md` still there?
   - Run `git reflog` and paste the output.
6. Use `git reflog` to restore your repository to the state just before the hard
reset.
   - Run `ls` to confirm `mistake.md` is back.

**Submit:** Your commands, their outputs, and your answers to the questions
above.

---

## Part 6: Short Answer

Answer each question in 2-4 sentences:

1. What is the difference between a **soft reset** and a **hard reset**? When
would you use each?
2. What is the difference between **rebasing** and **merging**? Why might you
prefer one over the other?
3. Why should you **never rebase** a branch that someone else is actively
working on?
4. What is the purpose of the `.git/` directory? What happens if you delete it?

---

## Submission

Submit a single markdown file called `homework.md` containing:

- All commands you ran for each part.
- All terminal output (use fenced code blocks).
- Your written answers to any questions.

Commit this file to your `git_homework` repository and submit either a zipped
copy of the repository or a link to it on GitHub.

---

*Good luck! Remember: there is very little downside to committing often.*

---
