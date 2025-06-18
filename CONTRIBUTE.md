# Contributing to Leno AI

Thank you for your interest in contributing to Leno AI! We welcome pull requests, bug reports, and feature suggestions from the community. This guide will help you get started as a contributor.

---

## 📝 How to Contribute

1. **Fork the Repository**
   - Visit [https://github.com/tmalone1250/lenoai](https://github.com/tmalone1250/lenoai) and click the **Fork** button.

2. **Clone Your Fork**
   - Copy your fork URL and run:
     ```sh
     git clone https://github.com/<your-github-username>/lenoai.git
     cd lenoai
     ```

3. **Create a Feature Branch**
   - Always work on a branch (not `main`):
     ```sh
     git checkout -b my-feature-branch
     ```
   - Use a descriptive name (e.g., `add-stock-agent`, `fix-login-bug`).

4. **Make and Commit Changes**
   - Edit files, add features, or fix bugs.
   - Stage and commit your changes:
     ```sh
     git add .
     git commit -m "Describe your change here"
     ```

5. **Push and Open a Pull Request (PR)**
   - Push your branch:
     ```sh
     git push origin my-feature-branch
     ```
   - Go to your fork on GitHub and click "Compare & pull request".
   - Fill out the PR template and submit.

6. **Submit Issues**
   - For bugs or feature requests, go to the [Issues](https://github.com/tmalone1250/lenoai/issues) tab and click "New issue".

7. **Sync with Upstream**
   - Add the upstream repo:
     ```sh
     git remote add upstream https://github.com/tmalone1250/lenoai.git
     ```
   - Fetch and merge changes:
     ```sh
     git fetch upstream
     git checkout main
     git merge upstream/main
     git push origin main
     ```
   - Rebase your feature branch if needed:
     ```sh
     git checkout my-feature-branch
     git rebase main
     ```

---

## 🧑‍💻 Coding Standards
- Write clear, concise code and comments.
- Use docstrings for all functions and classes.
- Follow Python, JavaScript, and Markdown best practices.
- Keep tools atomic and stateless when possible.
- Use environment variables for all credentials and secrets.
- Add or update documentation for any new features or changes.

## 🧪 Testing
- Test your changes locally before submitting a PR.
- If possible, add or update automated tests.

## 📄 Documentation
- Update the README.md or relevant docs for any user-facing or architectural changes.
- Add usage examples or instructions as needed.

## 🤝 Code of Conduct
- Be respectful and inclusive.
- Provide constructive feedback in code reviews and discussions.
- Help others and ask for help when needed.

---

Thank you for helping make Leno AI better for everyone!
