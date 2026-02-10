# Introduction to Git and GitHub

A beginner-friendly guide to help you use GitHub effectively in your learning journey — no prior programming experience required.

---

## What is Git?

**Git** is a version control system — it tracks every change you make to your files so you can go back to any previous version. Think of it as an "undo history" for your entire project.

Created by Linus Torvalds in 2005, Git lets you:

- Save snapshots of your work at any point (called **commits**).
- Experiment on separate **branches** without breaking your main project.
- Collaborate with others by **merging** everyone's changes together.

## What is GitHub?

**GitHub** is a website that hosts your Git projects online. It adds collaboration tools on top of Git — you can share code, review each other's work, track tasks, and more.

**Why it matters for your learning:**
- Your projects are backed up and accessible from anywhere.
- You build a public portfolio that shows your work.
- You learn the same workflow used by professional developers and AI teams worldwide.

---

## Getting Set Up

### 1. Create a GitHub account

Go to [github.com](https://github.com/) and sign up for a free account.

> If you are a student, apply for the [GitHub Student Developer Pack](https://github.com/education/students) — it gives you free access to premium tools including GitHub Copilot.

### 2. Install Git on your computer

- **Windows:** Download from [git-scm.com/downloads](https://git-scm.com/downloads) and run the installer.
- **Mac:** Open Terminal and run `git --version`. If Git is not installed, you will be prompted to install it.
- **Linux:** Run `sudo apt install git` (Ubuntu/Debian) or `sudo dnf install git` (Fedora).

### 3. Configure Git with your identity

Open your terminal (Command Prompt, PowerShell, or Terminal) and run:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Use the same email you used for your GitHub account.

---

## Key Concepts

| Term | What it means |
|------|---------------|
| **Repository (Repo)** | A folder tracked by Git. Contains your project files and their full history. |
| **Commit** | A saved snapshot of your changes. Each commit has a message describing what changed. |
| **Branch** | A separate line of work. The default branch is called `main`. |
| **Merge** | Combining changes from one branch into another. |
| **Clone** | Downloading a copy of a remote repository to your computer. |
| **Fork** | Creating your own copy of someone else's repository on GitHub. |
| **Pull Request (PR)** | A request to merge your changes into another branch or repository. This is where code review happens. |
| **Push** | Uploading your local commits to GitHub. |
| **Pull** | Downloading the latest changes from GitHub to your computer. |

---

## Your First Workflow

This is the basic cycle you will use every time you work on a project.

### Using the terminal (command line)

```bash
# 1. Clone a repository from GitHub to your computer
git clone https://github.com/your-username/your-repo.git

# 2. Move into the project folder
cd your-repo

# 3. Make your changes (edit files, add files, etc.)

# 4. See what has changed
git status

# 5. Stage your changes (tell Git what to include in the next commit)
git add .

# 6. Commit your changes with a descriptive message
git commit -m "Add my introduction to the README"

# 7. Push your changes to GitHub
git push
```

### Using GitHub in the browser (no terminal needed)

You can also edit files directly on GitHub:

1. Navigate to a file in your repository.
2. Click the **pencil icon** to edit.
3. Make your changes.
4. Scroll down, write a commit message, and click **Commit changes**.

This is a perfectly valid way to work, especially when starting out.

---

## Tasks

Work through these tasks in order. Each folder contains its own instructions and any starter files you need.

| Task | Folder | What you will learn |
|------|--------|---------------------|
| 1. Create Your GitHub Profile README | [01-profile-readme](./01-profile-readme/) | Repo creation, commits, basic Markdown |
| 2. Host a Personal Site with GitHub Pages | [02-github-pages](./02-github-pages/) | Push-to-deploy, seeing real results from Git |
| 3. Learn Markdown | [03-markdown-basics](./03-markdown-basics/) | The formatting language used everywhere on GitHub |
| 4. Collaborate as a Team | [04-team-collaboration](./04-team-collaboration/) | Forking, branching, pull requests, teamwork |
| 5. Track Work with Issues and Projects | [05-issues-and-projects](./05-issues-and-projects/) | Project management the way real teams do it |

---

## Learning Resources

These official resources will deepen your understanding. Review them alongside the tasks.

### Interactive Courses (learn by doing)

| Resource | Description |
|----------|-------------|
| [GitHub Skills](https://skills.github.com/) | Free hands-on courses that run inside GitHub repositories. Start with **"Introduction to GitHub"**. |
| [Learn Git Branching](https://learngitbranching.js.org/) | Interactive visual tool for understanding how branches work. |

### Official Documentation

| Resource | Description |
|----------|-------------|
| [GitHub Docs - Get Started](https://docs.github.com/en/get-started) | Structured guides from account creation to advanced workflows. |
| [Hello World - GitHub Docs](https://docs.github.com/en/get-started/start-your-journey/hello-world) | GitHub's own beginner tutorial for the pull request workflow. |
| [Writing on GitHub (Markdown)](https://docs.github.com/en/get-started/writing-on-github) | Learn Markdown — the formatting language used in READMEs, issues, and PRs. |

### For Students

| Resource | Description |
|----------|-------------|
| [GitHub Student Developer Pack](https://github.com/education/students) | Free access to premium developer tools including GitHub Copilot. |
| [GitHub Education](https://github.com/education) | Programs, resources, and community for students and educators. |

### Deep Dives (when you are ready)

| Resource | Description |
|----------|-------------|
| [Pro Git Book (free)](https://git-scm.com/book) | The complete reference for understanding Git in depth. |
| [Git and GitHub Learning Resources](https://docs.github.com/en/get-started/start-your-journey/git-and-github-learning-resources) | GitHub's curated list of additional learning materials. |

---

## Common Mistakes and How to Fix Them

| Problem | Solution |
|---------|----------|
| `fatal: not a git repository` | You are not inside a Git project folder. Use `cd` to navigate into your cloned repo. |
| `error: failed to push some refs` | Someone else (or you on another device) made changes. Run `git pull` first, then `git push`. |
| You committed to the wrong branch | Run `git log` to find your commit, then use `git cherry-pick <commit-id>` on the correct branch. |
| You made a typo in your commit message | If you have not pushed yet: `git commit --amend -m "Corrected message"` |
| You accidentally staged a file | Run `git reset HEAD filename` to unstage it. |
| Your fork is behind the original repo | On your fork on GitHub, click **"Sync fork"** to pull in the latest changes. |

---

## What to Submit (for students)

When you have completed all the tasks, submit the following links to your instructor:

| Task | What to submit |
|------|---------------|
| Task 1 | Your GitHub profile link (e.g., `https://github.com/janedoe`) |
| Task 2 | Your live GitHub Pages link (e.g., `https://janedoe.github.io`) |
| Task 3 | Link to your `markdown-practice.md` file (e.g., `https://github.com/janedoe/janedoe/blob/main/markdown-practice.md`) |
| Task 4 | Your team repository link + list of all team members' GitHub usernames |
| Task 5 | Same team repository link (instructor will check Issues, PRs, and Projects tabs) |

Each task folder has a detailed **"What to Submit"** section with the exact checklist your instructor will use for grading.

---

## What Next?

Once you have completed the tasks above, you can:

- Explore repositories on topics you are interested in using [GitHub Explore](https://github.com/explore).
- Look for beginner-friendly issues labeled `good first issue` in projects you like.
- Start uploading your own class projects and assignments to build your portfolio.
- Take more [GitHub Skills](https://skills.github.com/) courses to learn about Actions, security, and advanced workflows.

The best way to learn GitHub is to use it every day. Push your work, track your tasks with issues, and collaborate with your classmates. Your GitHub profile will become a living portfolio of everything you learn.
