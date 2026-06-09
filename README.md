# 🧑‍💻 GitHub Collaboration — Team Project

Welcome. This repo is your hands-on introduction to working with Git and GitHub in a team.
You will fork, branch, commit, push, review, and merge — the same way real developers do.

Follow the files in order:

| Step | File | What it covers |
|------|------|----------------|
| 1 | `README.md` ← you are here | Fork the repo, add collaborators, set up Kanban |
| 2 | `CONVENTIONS.md` | How to name branches, commits, and PRs |
| 3 | `TASKS.md` | Your actual Kanban tasks for this project |

---

## 📚 Resources

Read at least one of these before you start:

1. [**GitHub Skills**](https://skills.github.com/) — Interactive exercises directly inside GitHub. Start here.
2. [**Atlassian Git Tutorials**](https://www.atlassian.com/git/tutorials) — Visual explanations of branching, merging, and rebasing.
3. [**Pro Git Book**](https://git-scm.com/book/en/v2) — The full official reference. Chapters 1–3 are enough.
4. [**Oh My Git!**](https://ohmygit.org/) — A game that teaches Git visually. Surprisingly good.

---

## Part 1 — Fork the Repository

1. Open the repository page on GitHub.
2. Click **Fork** in the top-right corner.
3. Select your personal account as the destination.
4. Open your terminal.
5. Run `git clone https://github.com/YOUR_USERNAME/REPO_NAME.git`
6. Run `cd REPO_NAME`
7. Run `git remote add upstream https://github.com/ORIGINAL_OWNER/REPO_NAME.git`
8. Run `git remote -v` and confirm you see both `origin` and `upstream`.

---

## Part 2 — Add Collaborators

> Only the repository owner does this part.

1. Go to your repository on GitHub.
2. Click **Settings**.
3. Click **Collaborators** in the left sidebar.
4. Click **Add people**.
5. Search for your teammate's GitHub username.
6. Click **Add [username] to this repository**.
7. Repeat steps 4–6 for each teammate.
8. Tell your teammates to check their email and **accept the invitation**.

---

## Part 3 — Set Up the Kanban Board

1. Go to your repository on GitHub.
2. Click the **Projects** tab.
3. Click **New project**.
4. Select the **Board** template.
5. Name the board (e.g. `Team Project — Sprint 1`).
6. Click **Create project**.
7. Rename the default columns to: `Backlog`, `To Do`, `In Progress`, `In Review`, `Done`.
8. Go to `TASKS.md` in this repo.
9. Create a GitHub Issue for each task listed there.
10. Open your board and add each Issue as a card under **Backlog**.
11. Assign each card to a team member.

---

> Once everyone has accepted their invitation and the board is set up, move to `CONVENTIONS.md`.
