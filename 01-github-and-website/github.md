# Part 1: GitHub

[Workshop 1](README.md) · Fri, Nov 6, 2026 · Instructor: Hua

By the end of this part you will have:

- [ ] a GitHub account
- [ ] your own repository
- [ ] your first commit
- [ ] a copy of the club's `workshops` repository (this one!)

Everything in Parts 1–4 happens in your web browser, so it works on any laptop,
including Chromebooks.

## Words to know

| Word | What it means |
|------|---------------|
| **Git** | A tool that saves snapshots of your project, so you can see every change and go back if something breaks. |
| **GitHub** | A website that stores Git projects online, so you can share them and work from any computer. |
| **Repository (repo)** | A project folder that Git keeps track of. |
| **Commit** | A saved snapshot of your files, with a short message saying what changed. |
| **Clone** | Download a copy of a repository to your computer. |
| **Push** | Send your new commits from your computer up to GitHub. |
| **Pull** | Get the newest commits from GitHub down to your computer. |

## Part 1: Make a GitHub account

1. Go to [github.com/signup](https://github.com/signup).
2. Enter your email, a password, and a **username**.
   - Choose a username you'd be happy for a teacher or college to see. It will be part of your website address in Part 2.
   - Use your first name or a nickname, not your full name.
3. Check your email for the verification code and enter it.
4. If GitHub asks questions about how you'll use it, you can skip them.

> GitHub accounts are for people **13 and older**. If you're 12, tell an instructor and pair up with a mentor today.

## Part 2: Create your first repository

1. In the top-right corner of GitHub, click **+** → **New repository**.
2. **Repository name:** `my-first-repo`
3. Choose **Public**.
4. Check **Add a README file**.
5. Click **Create repository**.

You now have a repository with one file, `README.md`. A README is the front page of a project:
GitHub shows it below the file list.

## Part 3: Make your first commit

1. Click `README.md`, then click the **pencil icon** (Edit this file).
2. Replace what's there with an introduction to yourself. You can start from
   [this template](about-me-README.md): open it, click **Raw**, select all, copy it
   into your README, and fill in the blanks.
3. Click **Preview** to see how it looks. `#` makes a heading and `-` makes a bullet point.
4. Click **Commit changes…**
5. Write a short **commit message** that says what you changed, for example `Add an introduction about me`.
6. Click **Commit changes**.

That's your first commit.

**Good commit messages** say *what* changed, in a few words:

| 👍 Good | 👎 Not helpful |
|---------|----------------|
| `Add an introduction about me` | `update` |
| `Fix typo in hobbies list` | `asdf` |
| `Add photo of my robot` | `changes` |

## Part 4: Look at your history

On your repository's main page, click **Commits** (or the clock icon) near the top of the file list.
You'll see every commit: the first one GitHub made when it created the repo, and yours.
Click a commit to see exactly which lines changed (green = added, red = removed).

**Try it:** make one more small change to your README and commit it. Check that the history now shows 3 commits.

## Part 5: Clone the club's repository

Now get your own copy of the club's lessons. Pick **one** option.

### Option A: GitHub Codespaces (works on any computer, including Chromebooks)

A codespace is a computer in the cloud that you use from your browser. Git is already installed.

1. Go to **your** `my-first-repo` on GitHub.
2. Click the green **Code** button → **Codespaces** tab → **Create codespace on main**.
3. Wait for it to load. You'll see an editor with a **terminal** at the bottom.
4. In the terminal, type these commands one at a time and press Enter after each:

   ```bash
   cd /workspaces
   git clone https://github.com/valley-ai-club/workshops.git
   ls workshops
   ```

   You should see the workshop folders (`01-github-and-website`, …).

Personal GitHub accounts get free codespace time every month, which is plenty for this club.
When you're done, close the tab; the codespace stops on its own.

### Option B: your own laptop (Mac or Windows)

1. Open a terminal:
   - **Mac:** open the **Terminal** app. Type `git --version` and press Enter. If your Mac offers to install developer tools, click **Install** and wait.
   - **Windows:** install **Git for Windows** from [git-scm.com](https://git-scm.com/downloads), then open **Git Bash**.
2. Go to a folder where you keep schoolwork, then clone:

   ```bash
   cd Documents
   git clone https://github.com/valley-ai-club/workshops.git
   ls workshops
   ```

### Keep it up to date

Before each future workshop, get the newest lessons:

```bash
cd workshops
git pull
```

Remember the rule: **don't edit files inside `workshops`.** Copy anything you want to change into your own repository.

## Part 6 (stretch): commit from the terminal

Finished early? Make a commit without the website. This is how most programmers use Git.
These steps use the codespace from Option A, where you're already signed in to GitHub.

```bash
cd /workspaces/my-first-repo
```

1. Open `README.md` in the editor on the left and add a line, for example a new hobby. Save with Ctrl+S (Cmd+S on a Mac).
2. Ask Git what changed:

   ```bash
   git status
   git diff
   ```

3. Choose the file to include in your next commit (this is called *staging*):

   ```bash
   git add README.md
   ```

4. Make the commit:

   ```bash
   git commit -m "Add another hobby"
   ```

5. Send it to GitHub:

   ```bash
   git push
   ```

6. Refresh your repository on GitHub. Your new commit is in the history.

> On your own laptop, Git needs your name and a way to sign in to GitHub before you can push.
> Ask a mentor during office hours, or stick with Codespaces for now.

## Cheat sheet

| Command | What it does |
|---------|--------------|
| `git clone <url>` | Download a copy of a repository |
| `git status` | Show which files changed |
| `git diff` | Show exactly which lines changed |
| `git add <file>` | Choose a file for the next commit |
| `git commit -m "message"` | Save a snapshot with a message |
| `git push` | Send your commits to GitHub |
| `git pull` | Get the newest commits from GitHub |
| `git log --oneline` | List past commits, one per line |

## Stuck?

| Problem | Try this |
|---------|----------|
| The verification email never arrived | Check your spam folder, then ask GitHub to resend it. |
| `repository not found` | Check the URL for typos. Copy it from the green **Code** button instead of typing it. |
| `git: command not found` | Git isn't installed on this computer. Use Codespaces (Option A). |
| `Permission denied` or `403` when pushing to `workshops` | That's expected: the club's repository is read-only. Push to your own repository instead. |
| `git pull` says your changes would be overwritten | You edited a file inside `workshops`. Ask a mentor; we'll help you save your work and fix it. |

## Next: build your website

In office hours, move on to [Part 2: Your website](website.md) and put your own page on the web.
