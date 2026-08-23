# PyLadies Kampala Open Source Workshop 2026

## Git and GitHub Practical Exercises

These exercises introduce participants to Git and GitHub and help them understand how developers manage code, track changes, and collaborate on projects.

---

## Exercise 1: Configure Git

Check whether Git is installed on your computer.

Run:

    git --version

Configure your Git username:

    git config --global user.name "Your Name"

Configure your email:

    git config --global user.email "your-email@example.com"

Check your configuration:

    git config --list

---

## Exercise 2: Create a Git Repository

Create a new folder for a simple project.

For example:

    mkdir my-first-project

Move into the project folder:

    cd my-first-project

Initialize Git:

    git init

Check the status of the repository:

    git status

---

## Exercise 3: Create and Track a File

Create a file called `README.md`.

Add some information about your project.

Check the Git status:

    git status

Add the file to the staging area:

    git add README.md

Check the status again.

Then create your first commit:

    git commit -m "Add project README"

Check the commit history:

    git log

---

## Exercise 4: Make Changes and Commit Them

Open your `README.md` file and add more information about your project.

Check the changes:

    git status

View the exact changes:

    git diff

Stage the changes:

    git add README.md

Commit them:

    git commit -m "Update project README"

View the commit history again:

    git log

---

## Exercise 5: Create a .gitignore File

Create a file called `.gitignore`.

Add files or folders that should not be committed to Git.

For example:

    .venv/
    __pycache__/
    .env

Check your Git status and make sure the files listed in `.gitignore` are not being tracked.

### Challenge

Research why files such as `.env` should not normally be committed to a public repository.

---

## Exercise 6: Create a GitHub Repository

Create a new repository on GitHub.

Give the repository a meaningful name.

For example:

    my-first-project

Add a short description.

Choose whether the repository should be public or private.

---

## Exercise 7: Connect Your Local Repository to GitHub

Copy the GitHub repository URL.

Connect your local repository to GitHub:

    git remote add origin YOUR_REPOSITORY_URL

Check the remote:

    git remote -v

Rename the current branch to `main`:

    git branch -M main

Push your project to GitHub:

    git push -u origin main

Open the repository on GitHub and confirm that your files are visible.

---

## Exercise 8: Clone a Repository

Find a public GitHub repository.

Copy its repository URL.

Clone the repository:

    git clone REPOSITORY_URL

Move into the repository:

    cd repository-name

View the files:

    ls

Check the Git status:

    git status

---

## Exercise 9: Create a Branch

Create a new branch for a change.

For example:

    git checkout -b add-about-page

Make a change to the project.

Add and commit the change:

    git add .
    git commit -m "Add about page"

View your branches:

    git branch

---

## Exercise 10: Push a Branch to GitHub

Push your new branch to GitHub:

    git push -u origin add-about-page

Open the GitHub repository.

You should now see your new branch.

---

## Exercise 11: Create a Pull Request

Open your GitHub repository.

Create a Pull Request from your branch into the `main` branch.

In the Pull Request description, explain:

- What you changed
- Why you made the change
- How you tested it

Ask another participant to review your Pull Request.

---

## Exercise 12: Review Someone Else's Pull Request

Work with a partner.

Open their Pull Request and review their changes.

Check:

- Is the code understandable?
- Does the change solve the intended problem?
- Are there obvious errors?
- Is anything missing?

Leave a constructive comment.

If everything looks good, approve the Pull Request.

---

## Exercise 13: Merge a Pull Request

After the Pull Request has been reviewed and approved, merge it into the `main` branch.

Then update your local repository:

    git checkout main

    git pull origin main

Check that the changes are now available locally.

---

## Exercise 14: Working With Git History

View the commit history:

    git log

View a shorter version:

    git log --oneline

Find out what changed in a previous commit.

### Challenge

Use Git history to identify:

- Who made a change
- When the change was made
- What the commit message was

---

# Mini Project: Collaborative GitHub Project

Work in small groups.

Choose a simple project such as:

- A community website
- A Python application
- A personal portfolio
- A student resource website
- A simple information page

Create a GitHub repository for the project.

Each participant should:

1. Clone the repository.
2. Create a branch.
3. Make a change.
4. Commit the change.
5. Push the branch to GitHub.
6. Create a Pull Request.
7. Review another participant's Pull Request.
8. Merge approved changes.

The goal is to experience the basic workflow used by developers when collaborating on real projects.

---

# Learning Outcomes

By the end of these exercises, participants should be able to:

- Understand what Git is and why developers use it.
- Create and initialize Git repositories.
- Track changes using Git.
- Create meaningful commits.
- Create and use branches.
- Connect local repositories to GitHub.
- Push and pull changes.
- Clone existing repositories.
- Create Pull Requests.
- Review other people's contributions.
- Collaborate on a shared project using GitHub.
- Understand the basic workflow of contributing to open-source projects.
