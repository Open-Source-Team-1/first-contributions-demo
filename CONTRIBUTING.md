# Contributing to Our Project

First of all, thank you for your interest in contributing! 🎉

This repository is a beginner-friendly space for learning how open-source contributions work. Whether you are making your first contribution or already have experience with Git and GitHub, you are welcome here.

Our goal is to learn, collaborate, and help each other grow as developers.

## 📌 Before You Start

- Be respectful and supportive of other contributors.
- Keep your contributions small, clear, and meaningful.
- Read the existing `README.md` before making changes.
- If you are unsure about something, ask questions or open an issue.

## 🚀 How to Contribute

### Step 1: Fork the Repository

Visit the original repository:

https://github.com/Open-Source-Team-1/first-contributions-demo

Click the **Fork** button in the top-right corner to create a copy of the repository under your GitHub account.

### Step 2: Clone Your Fork

Open your terminal and run the following command, replacing `<your-username>` with your GitHub username.

```bash
git clone https://github.com/<your-username>/first-contributions-demo.git
```

Move into the project directory:

```bash
cd first-contributions-demo
```

### Step 3: Add the Original Repository as Upstream

This helps you keep your fork synchronized with the original repository.

```bash
git remote add upstream https://github.com/Open-Source-Team-1/first-contributions-demo.git
```

### Step 4: Create a New Branch

Always create a separate branch for your contribution.

```bash
git switch -c docs/add-your-name
```

You can replace `docs/add-your-name` with a short, descriptive branch name related to your change.

### Step 5: Make Your Contribution

Make a small, meaningful change to the repository.

For your first contribution, you can:
- Add your name to the designated contributors file, if the repository provides one.
- Improve documentation or fix a typo.
- Suggest a useful improvement to the project.

**Important:** Only edit files relevant to your contribution. Do not modify unrelated files.

### Step 6: Review Your Changes

Check which files you modified:

```bash
git status
```

Review the changes before committing:

```bash
git diff
```

Make sure your changes are intentional and do not contain unrelated edits.

### Step 7: Commit Your Changes

Stage the files you want to contribute:

```bash
git add <file-name>
```

Commit your changes with a clear message:

```bash
git commit -m "docs: add contributor information"
```

Replace the example commit message with one that accurately describes your contribution.

### Step 8: Push Your Branch

Push your branch to your fork on GitHub:

```bash
git push -u origin docs/add-your-name
```

If you used a different branch name, replace `docs/add-your-name` accordingly.

### Step 9: Open a Pull Request

1. Visit your fork on GitHub.
2. Click **Compare & pull request**, or open a new pull request.
3. Make sure the base repository is `Open-Source-Team-1/first-contributions-demo`.
4. Select the appropriate base branch, usually `main` if that is the repository's default branch.
5. Add a clear title and explain what you changed and why.
6. Submit your pull request.

Your pull request will be reviewed by the maintainers. They may ask for changes before it can be merged.

## 📝 Pull Request Guidelines

Before submitting a pull request, make sure:

- [ ] Your changes serve a clear purpose.
- [ ] You have reviewed your changes.
- [ ] Your commit messages describe your work.
- [ ] You have not included unrelated changes.
- [ ] Your pull request explains what you changed.
- [ ] You have followed the existing project structure and guidelines.

## 🤝 Community Expectations

We expect all contributors to:

- Treat everyone with respect.
- Be open to constructive feedback.
- Ask questions when they need help.
- Give other contributors time to review their work.
- Help maintain a welcoming learning environment.

## ❓ Need Help?

If you get stuck, open an issue in the repository and explain the problem you encountered. Include relevant error messages or steps to reproduce the issue when possible.

We are all here to learn. Your first contribution does not need to be perfect.

**Thank you for contributing and being part of our open-source journey!** 💚