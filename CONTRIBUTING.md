# Contributing to VibeCoder Blueprint

Thank you for your interest in contributing to **VibeCoder Blueprint**! We welcome and appreciate all forms of contributions, from reporting bugs to submitting new features and improving documentation. Your efforts help make this open-source utility more robust and valuable for the community.

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

### Table of Contents

1.  [How Can I Contribute?](#how-can-i-contribute)
    * [Reporting Bugs](#reporting-bugs)
    * [Suggesting Enhancements](#suggesting-enhancements)
    * [Code Contributions](#code-contributions)
        * [Setting Up Your Development Environment](#setting-up-your-development-environment)
        * [Making Changes](#making-changes)
        * [Submitting Your Pull Request (PR)](#submitting-your-pull-request-pr)
    * [Documentation Contributions](#documentation-contributions)
2.  [Code Style and Guidelines](#code-style-and-guidelines)
3.  [Commit Message Guidelines](#commit-message-guidelines)
4.  [Review Process](#review-process)
5.  [Project Roadmap & Future Directions](#project-roadmap--future-directions)

---

### 1. How Can I Contribute?

There are many ways to contribute to VibeCoder Blueprint, regardless of your technical expertise.

#### Reporting Bugs

If you find a bug, please help us by reporting it!

* **Before reporting:** Search existing [GitHub Issues](https://github.com/AKS01-github/VibeCoder-Blueprint/issues) to ensure the bug hasn't already been reported.
* **How to report:** Open a new issue and provide as much detail as possible.
    * A clear and concise title.
    * Steps to reproduce the bug.
    * Expected behavior.
    * Actual behavior.
    * Screenshots or animated GIFs (if applicable).
    * Your operating system and browser version.

#### Suggesting Enhancements

Have an idea for a new feature, a UI/UX improvement, or a better way to structure prompts? We'd love to hear it!

* **Before suggesting:** Check existing [GitHub Issues](https://github.com/AKS01-github/VibeCoder-Blueprint/issues) and [GitHub Discussions](https://github.com/AKS01-github/VibeCoder-Blueprint/discussions) to see if your idea has already been discussed.
* **How to suggest:** Open a new issue or start a discussion, clearly outlining:
    * The proposed enhancement.
    * The problem it solves or the benefit it provides.
    * Any examples or mock-ups (if applicable).

#### Code Contributions

We welcome contributions to the codebase. This includes bug fixes, new features, and refactoring efforts.

##### Setting Up Your Development Environment

VibeCoder Blueprint is currently a static HTML/CSS/JavaScript application, making setup straightforward.

1.  **Fork the repository:** Click the "Fork" button at the top right of the [VibeCoder Blueprint GitHub repository](https://github.com/AKS01-github/VibeCoder-Blueprint).
2.  **Clone your forked repository:**
    ```bash
    git clone https://github.com/AKS01-github/VibeCoder-Blueprint
    
    ```
3.  **Navigate to the project directory:**
    ```bash
    cd vibecoder-blueprint
    ```
4.  **Open `index.html` in your web browser:** You can directly open `index.html` from your file system to run the planner locally. This allows you to test your changes live.

##### Making Changes

1.  **Create a new branch:** Before making changes, create a new branch from `main` (or `master`) for your feature or bug fix. Choose a descriptive name.
    ```bash
    git checkout -b feature/your-feature-name
    # Or for bug fixes: git checkout -b bugfix/issue-description
    ```
2.  **Implement your changes:** Write your code, ensuring it aligns with the project's goals of simplifying prompt planning for AI/low-code/no-code tools.
3.  **Test your changes:** Thoroughly test your modifications to ensure they work as expected and don't introduce new issues.

##### Submitting Your Pull Request (PR)

Once you've made your changes and tested them, submit a Pull Request.

1.  **Commit your changes:**
    ```bash
    git add .
    git commit -m "feat: Add new prompt planning section for [topic]"
    # Follow the Commit Message Guidelines below.
    ```
2.  **Push to your branch:**
    ```bash
    git push origin feature/your-feature-name
    ```
3.  **Open a Pull Request:** Go to your forked repository on GitHub and click the "Compare & pull request" button.
    * **Provide a detailed description:** Clearly explain the purpose of your PR, what changes you've made, what problem it solves, and any relevant details.
    * **Link to issues:** If your PR addresses an existing issue, link to it (e.g., `Closes #123`).
    * **Screenshots/GIFs:** For UI/UX changes, include screenshots or GIFs to demonstrate the new functionality.

#### Documentation Contributions

High-quality documentation is vital for any open-source project. We appreciate contributions that improve our `README.md`, `CONTRIBUTING.md`, or any other project documentation.

* Correct typos or grammatical errors.
* Clarify existing explanations.
* Add new sections or examples.

---

### 2. Code Style and Guidelines

While VibeCoder Blueprint is currently a static HTML/CSS/JS project, maintaining consistency is key for future scalability and maintainability, especially as we consider refactoring to a modern JavaScript framework.

* **HTML:** Ensure well-structured, semantic HTML.
* **CSS:** Keep CSS rules organized and aim for clarity. Avoid overly specific selectors where possible.
* **JavaScript:** Write readable, well-commented JavaScript. Adhere to basic best practices.
* **Comments:** Use comments to explain complex logic or non-obvious design choices.
* **Consistency:** Try to match the existing coding style in the project.

---

### 3. Commit Message Guidelines

We encourage using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) for clear and consistent commit history.

Examples:

* `feat: Add new module for prompt validation`
* `fix: Correct markdown output for JTBD section`
* `docs: Update README with new features`
* `style: Adjust button spacing in navigation`
* `refactor: Simplify local storage handling`
* `chore: Update .gitignore`

---

### 4. Review Process

All pull requests will be reviewed by the project maintainer.

* We aim to provide timely and constructive feedback.
* Reviews will focus on:
    * **Functionality:** Does the change work as intended and solve the stated problem?
    * **Code Quality:** Is the code clean, readable, maintainable, and consistent with the project's style?
    * **Adherence to Guidelines:** Does the PR follow the contribution guidelines and Code of Conduct?
    * **Impact:** Does the change align with the project's goal of enhancing AI/low-code/no-code prompt planning?
* You may be asked to make revisions based on feedback.
* Once approved, your changes will be merged into the `main` branch.

---

### 5. Project Roadmap & Future Directions

While the current focus is on refining the core static utility, future considerations for VibeCoder Blueprint include:

* **Refactoring to a Modern JavaScript Framework:** Exploring frameworks like React, Vue, or Svelte to enhance modularity, scalability, and developer experience.
* **Advanced Features:** Potential future features could include more sophisticated prompt templating, integration with specific low-code/no-code platforms (conceptual), or enhanced output options.
* **Community-Driven Enhancements:** Many future directions will be influenced by community feedback and contributions.

Your input helps shape the future of VibeCoder Blueprint!

---