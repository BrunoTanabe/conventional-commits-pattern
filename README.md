# Conventional Commits Patterns 📊

---

## Table of Contents 📚
1. [Introduction 📖](#1-introduction-📖)
2. [Importance of Standardizing Commits 🔧](#2-importance-of-standardizing-commits-🔧)
3. [How to Use Conventional Commits 📐](#3-how-to-use-conventional-commits-📐)
4. [Commit Types 🗂️](#4-commit-types-🗂️)
5. [Examples 💡](#5-examples-💡)
6. [Contribution Guidelines 🤝](#6-contribution-guidelines-🤝)
7. [License 📜](#7-license-📜)
8. [Contact 📧](#8-contact-📧)

---

## 1. Introduction 📖
Conventional Commits is a specification for writing consistent commit messages. It defines a set of rules for creating an explicit commit history, which makes it easier to write automated tools on top of. These patterns are meant to improve the readability and structure of commit messages, thereby facilitating better collaboration and project management.

---

## 2. Importance of Standardizing Commits 🔧
Standardizing commits provides several benefits:
- **Improves readability 🧾:** Consistent commit messages make it easier to understand the changes made to the project.
- **Facilitates collaboration 🤝:** Team members can quickly grasp the context of changes.
- **Automates tasks 🔄:** Tools can generate changelogs, release notes, and version numbers automatically.
- **Enhances project management 📈:** Clear commit messages help in tracking progress and identifying issues.

---

## 3. How to Use Conventional Commits? 📐
To use Conventional Commits Patterns:
- **Adopt a consistent format 📏:** Follow the structure defined by Conventional Commits.
- **Use meaningful messages 📝:** Write commit messages that clearly describe the changes made.
- **Leverage tools 🛠️:** Utilize tools that enforce or validate Conventional Commit messages, such as commitlint.

Format your commit messages like this:
```
<type>[optional scope]: <description>
[optional body]
[optional footer(s)]
```
- **Type**: This denotes the kind of change that this commit is providing.
- **Scope** (optional): A scope may be included to provide additional contextual information and is contained within parentheses, following the type.
- **Description**: A short description of the change.
- **Body** (optional): A longer description of the change.
- **Footer** (optional): One or more footers that may include "BREAKING CHANGE" notices or references to issue tracker IDs.

---

## 4. Commit Types 🗂️
Conventional Commits Patterns include several types, each serving a specific purpose:

- **fix 🐛**: Patches a bug in your codebase.
- **feat ✨**: Introduces a new feature to the codebase.
- **docs 📝**: Documentation only changes.
- **style 💅**: Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc).
- **refactor 🔨**: A code change that neither fixes a bug nor adds a feature.
- **perf ⚡**: Improves performance.
- **test 🧪**: Adds missing tests or corrects existing tests.
- **build 📦**: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm).
- **ci 🚀**: Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs).
- **chore 🧹**: Other changes that don't modify src or test files.
- **wip 🚧**: Work in progress; not yet ready for production.

---

## 5. Examples 💡
Each commit message example includes a Bash command to demonstrate how to create the commit using Git.

### fix 🐛
```bash
git commit -m "fix(order): correct minor typos in code

see the issue for details on the typos fixed"
```
### feat ✨
```bash
git commit -m "feat(blog): add comment section

Users can now leave comments on articles. This was a highly requested feature from our user feedback."
```
### docs 📝
```bash
git commit -m "docs(changelog): update changelog to 0.3.0"
```
### style 💅
```bash
git commit -m "style(navbar): correct indentation"
```
### refactor 🔨
```bash
git commit -m "refactor(auth): simplify validation logic"
```
### perf ⚡
```bash
git commit -m "perf(rendering): cache SVG assets"
```
### test 🧪
```bash
git commit -m "test(login): add unit tests for password reset"
```
### build 📦
```bash
git commit -m "build(packer): update dependencies"
```
### ci 🚀
```bash
git commit -m "ci(travis): force install dependencies"
```
### chore 🧹
```bash
git commit -m "chore(release): bump version to 1.0.3"
```
### wip 🚧
```bash
git commit -m "wip(feature-x): temporary commit - to be squashed"
```

---

## 6. Contribution Guidelines 🤝
Contributions are welcome! If you have a new project type to add or improvements to the existing scripts, feel free to fork the repository and submit a pull request. Please follow the guidelines below:
- Fork the repository.
- Create a new branch (`git checkout -b feature-branch`).
- Make your changes.
- Commit your changes (`git commit -m "feat: add new feature"`).
- Push to the branch (`git push origin feature-branch`).
- Open a pull request.

---

## 7. License 📜
This project is licensed under the MIT License. See the [LICENSE](https://github.com/BrunoTanabe/conventional-commits-pattern/blob/main/LICENSE) file for more details.

---

## 8. Contact 📧
For any questions or suggestions, please open an issue on GitHub or contact the repository owner at [tanabebruno@gmail.com](mailto:tanabebruno@gmail.com).