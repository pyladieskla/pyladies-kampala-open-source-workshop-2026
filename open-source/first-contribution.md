# PyLadies Kampala Open Source Workshop 2026

## First Open Source Contribution

This practical session introduces participants to the process of contributing to an open-source project. Participants will learn how to find a project, understand its contribution guidelines, make a small change, and submit their first Pull Request.

---

## Exercise 1: What Is Open Source?

Before making a contribution, discuss:

- What does open source mean?
- Why do people contribute to open-source projects?
- What can someone contribute besides code?
- How can open-source contributions help with learning and career development?

Think about open-source projects you already use.

Examples include:

- Python
- Django
- NumPy
- Pandas
- Mozilla Firefox
- VS Code

---

## Exercise 2: Find an Open Source Project

Choose an open-source project on GitHub.

Look for a project that:

- Is actively maintained.
- Has clear contribution guidelines.
- Has issues that beginners can understand.
- Welcomes new contributors.

Search GitHub for issues labelled:

- `good first issue`
- `beginner`
- `first contribution`
- `help wanted`

Read the project's README before choosing an issue.

---

## Exercise 3: Understand the Repository

Open the repository and look through its files.

Try to identify:

- The README file
- Contribution guidelines
- Code of Conduct
- Documentation
- Source code
- Tests
- Issue tracker

Read the contribution guidelines carefully.

### Questions

Before contributing, answer:

1. What does the project do?
2. Who maintains it?
3. How can someone contribute?
4. What rules do contributors need to follow?
5. How should issues and Pull Requests be created?

---

## Exercise 4: Choose an Issue

Find an issue that is appropriate for a beginner.

Read the entire issue carefully.

Identify:

- What problem needs to be solved?
- What change is being requested?
- Has someone already started working on it?
- What files might need to be changed?

If necessary, leave a comment on the issue explaining that you would like to work on it.

---

## Exercise 5: Fork the Repository

Fork the project repository to your own GitHub account.

After creating the fork, copy its URL.

Clone your fork to your computer:

    git clone YOUR_FORK_URL

Move into the project directory:

    cd project-name

Check the repository:

    git status

---

## Exercise 6: Create a Branch

Create a new branch for your contribution.

For example:

    git checkout -b first-contribution

Make sure you are working on your own branch and not directly on `main`.

---

## Exercise 7: Make a Small Contribution

Make the change required by the issue.

Depending on the project, your first contribution might involve:

- Fixing a documentation error.
- Improving an example.
- Correcting a typo.
- Adding a small feature.
- Improving documentation.
- Fixing a simple bug.
- Adding or improving a test.

Do not make unrelated changes.

Keep your contribution focused on the issue you selected.

---

## Exercise 8: Test Your Changes

Before submitting your contribution, test your changes.

Depending on the project, this might include:

- Running the project.
- Running automated tests.
- Checking documentation.
- Checking that links work.
- Checking that your code follows the project's style guidelines.

If the project provides specific testing instructions, follow them.

---

## Exercise 9: Commit Your Changes

Check what has changed:

    git status

Review your changes:

    git diff

Stage your changes:

    git add .

Create a clear commit:

    git commit -m "Fix documentation example"

Use a commit message that briefly explains what you changed.

---

## Exercise 10: Push Your Contribution

Push your branch to your GitHub fork:

    git push -u origin first-contribution

Open your GitHub repository and confirm that your branch has been pushed successfully.

---

## Exercise 11: Create a Pull Request

Open the original project on GitHub.

Create a Pull Request from your branch.

Your Pull Request should clearly explain:

- What you changed.
- Why you made the change.
- Which issue it addresses.
- How you tested the change.

If the project asks contributors to use a specific Pull Request format, follow it.

---

## Exercise 12: Respond to Feedback

A maintainer may review your Pull Request and request changes.

Read their feedback carefully.

If changes are requested:

1. Make the requested changes locally.
2. Test the changes.
3. Commit them.
4. Push them to the same branch.

The Pull Request will automatically update.

Remember that code review is part of the normal open-source contribution process.

---

# Group Challenge

Work in small groups to identify an open-source project that participants could continue contributing to after the workshop.

As a group:

1. Find the project.
2. Read its contribution guidelines.
3. Identify beginner-friendly issues.
4. Discuss possible contributions.
5. Choose one small contribution.
6. Prepare a Pull Request.

---

# Reflection

After completing the exercise, answer the following questions:

1. What was the easiest part of making your first contribution?
2. What was the most difficult part?
3. What did you learn about working with other developers?
4. Would you contribute to an open-source project again?
5. What project would you like to contribute to in the future?

---

# Learning Outcomes

By the end of this session, participants should be able to:

- Explain what open source means.
- Find open-source projects on GitHub.
- Understand project documentation and contribution guidelines.
- Find beginner-friendly issues.
- Fork and clone repositories.
- Create branches for contributions.
- Make and test changes.
- Create meaningful commits.
- Push changes to GitHub.
- Create Pull Requests.
- Respond to maintainer feedback.
- Understand the basic open-source contribution workflow.

---

# After the Workshop

Participants are encouraged to continue contributing to open-source projects after the workshop.

PyLadies Kampala will continue to share beginner-friendly open-source opportunities, mentorship resources, and community activities to help participants build confidence and make further contributions.
