# Getting Started with Git: A Beginner’s Guide

Hello! If you’re curious about Git and want to learn how to use it for your coding projects, you’re in the right place. When I started with programming, Git seemed mysterious, but it quickly became one of my most valuable tools. Here’s how you can get started, step by step.

---

## What is Git?

Git is a tool that helps you keep track of changes to your files. Imagine writing a story and being able to go back to any previous version whenever you want. That’s what Git does for your code! You can also work with friends and never worry about losing your work.

For more details, check out the [official Git tutorial](https://git-scm.com/docs/gittutorial).

---

## Step 1: Install Git

1. Go to [git-scm.com](https://git-scm.com/) and download Git for your computer.
2. Follow the instructions to install it. The default settings are fine for most beginners.

---

## Step 2: Set Up Your Identity

After installing Git, open your terminal (Command Prompt, Terminal, or Git Bash) and enter:

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

This tells Git who you are, so your work is recognized.

---

## Step 3: Create Your First Project

Let’s start a new project folder and turn it into a Git repository.

```bash
mkdir my-first-git-project
cd my-first-git-project
git init
```

You’ll see a message that Git has initialized your folder. Now Git is watching for changes!

---

## Step 4: Add a File and Save Your Work

Make a simple text file:

```bash
echo "Hello, Git!" > hello.txt
```

Now, add the file to Git and commit (save) your changes:

```bash
git add hello.txt
git commit -m "Add hello.txt with a greeting"
```

- `git add` tells Git to track the file.
- `git commit` saves a snapshot of your work.

---

## Step 5: Check the Status and History

To see what’s going on, use these commands:

```bash
git status
git log
```

- `git status` shows which files are being tracked or changed.
- `git log` lists your past commits.

---

## Step 6: Fix Mistakes

If you ever mess up, don’t worry! Git can help you go back.

```bash
git checkout hello.txt
```

This will restore the file to the last commit.

---

## Final Thoughts

That’s it! You’ve just learned the basics of Git. The best way to learn is to practice—try making changes, adding new files, and committing your work. If you want to dive deeper, the [official Git tutorial](https://git-scm.com/docs/gittutorial) is a great resource.

Git might feel strange at first, but soon it will become second nature. Happy coding!

---
"Move git.md to blog folder"
