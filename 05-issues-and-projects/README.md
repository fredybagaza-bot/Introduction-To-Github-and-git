# Task 5: Track Work with Issues and Projects

GitHub Issues and Projects help you plan, organize, and track tasks — just like professional development teams do. In this task, you will use them on your **team repository from Task 4**.

---

## What are Issues?

An **issue** is a task, bug report, feature request, or any unit of work you want to track. Each issue has:

- A title and description.
- Labels (e.g., `bug`, `enhancement`, `documentation`).
- An assignee (who is responsible).
- A link to a pull request that resolves it.

## What are Projects?

A **project** is a board (like a Kanban board) that organizes your issues into columns. A typical setup:

| Todo | In Progress | Done |
|------|-------------|------|
| Task A | Task B | Task C |
| Task D | | Task E |

---

## Part 1: Create Issues

Do this in your **team repository from Task 4**.

1. Go to the team repository on GitHub.
2. Click the **Issues** tab.
3. Click **New issue**.
4. Each team member should create **at least 2 issues** describing improvements or additions to the team project. Examples:
   - "Add images to the VS Code section"
   - "Fix formatting in the Table of Contents"
   - "Add a Resources section at the bottom of the README"
   - "Add a section about [new tool/topic]"
   - "Proofread and fix typos in all sections"
5. For each issue, fill in:
   - **Title:** A short, clear description of the task.
   - **Description:** Write 1-2 sentences explaining what needs to be done and why.
   - **Assignee:** Click **Assignees** on the right and assign it to yourself or a teammate.
   - **Label:** Click **Labels** on the right and pick one (e.g., `enhancement`, `documentation`, `bug`). If no labels exist yet, the repo owner should click **Labels** > **New label** to create some.

---

## Part 2: Create a Project Board

**The repo owner does this:**

1. Go to the team repository on GitHub.
2. Click the **Projects** tab.
3. Click **Link a project** > **New project**.
4. Choose the **Board** layout.
5. Name it **"Team Sprint Board"**.
6. Click **Create**.
7. Add the issues your team created:
   - Click **+ Add item** at the bottom of the "Todo" column.
   - Type `#` and select issues from the list, or paste the issue number.
   - Add all issues to the board.

**All team members:**

8. As you work on issues, drag them from **Todo** to **In Progress** to **Done**.

---

## Part 3: Resolve an Issue with a Pull Request

Each team member should **resolve at least one issue** by making a pull request:

1. Pick an issue assigned to you from the project board. Move it to **In Progress**.
2. In your terminal, pull the latest changes and create a branch:

```bash
git checkout main
git pull
git checkout -b fix-issue-3
```

> Name the branch after the issue (e.g., `fix-issue-3`, `add-resources-section`).

3. Make the changes described in the issue.
4. Stage, commit, and push:

```bash
git add .
git commit -m "Add resources section (closes #3)"
git push origin fix-issue-3
```

> Writing `closes #3` in the commit message (using the actual issue number) will automatically close the issue when the PR is merged.

5. On GitHub, click **"Compare & pull request"**.
6. In the PR description, write `Closes #3` (with the actual issue number). This links the PR to the issue.
7. Submit the pull request. The repo owner reviews and merges it.
8. Once merged, the issue closes automatically and moves to **Done** on the project board.

---

## Part 4: Use Issues for Team Discussion

Try this as a team:

1. One person creates an issue titled **"What should we add to our project next?"**.
2. Each team member comments on the issue with a suggestion.
3. Use emoji reactions (thumbs up/down) to vote on suggestions.
4. Once the team decides, the issue creator edits the issue description to record the decision, then closes the issue.

---

## What to Submit

Your instructor will check the **team repository from Task 4** for:

- [ ] The repository has **at least 6 issues** created (at least 2 per team member).
- [ ] Each issue has a **title, description, assignee, and label**.
- [ ] A **project board** named "Team Sprint Board" exists with issues organized into columns.
- [ ] At least one issue was **closed via a pull request** using `Closes #` in the PR description.
- [ ] The Issues tab shows a mix of **open and closed** issues.

**Submit:** The same team repository link from Task 4. Your instructor will check the Issues tab, Pull requests tab, and Projects tab.

---

## Reference

- [Quickstart for GitHub Projects](https://docs.github.com/en/issues/planning-and-tracking-with-projects/learning-about-projects/quickstart-for-projects)
- [About issues - GitHub Docs](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-issues)
- [Linking a pull request to an issue](https://docs.github.com/en/issues/tracking-your-work-with-issues/linking-a-pull-request-to-an-issue)
