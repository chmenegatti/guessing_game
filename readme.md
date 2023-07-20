
<div align="center">
<h1 align="center">
<img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/folder-markdown-open.svg" width="100" />
<br>guessing_game
</h1>
<h3>◦ Guess right, code tight</h3>
<h3>◦ Developed with the software and tools listed below.</h3>

<p align="center">
<img src="https://img.shields.io/badge/Rust-000000.svg?style&logo=Rust&logoColor=white" alt="Rust" />
</p>
<img src="https://img.shields.io/github/languages/top/chmenegatti/guessing_game.git?style&color=5D6D7E" alt="GitHub top language" />
<img src="https://img.shields.io/github/languages/code-size/chmenegatti/guessing_game.git?style&color=5D6D7E" alt="GitHub code size in bytes" />
<img src="https://img.shields.io/github/commit-activity/m/chmenegatti/guessing_game.git?style&color=5D6D7E" alt="GitHub commit activity" />
<img src="https://img.shields.io/github/license/chmenegatti/guessing_game.git?style&color=5D6D7E" alt="GitHub license" />
</div>

---

## 📒 Table of Contents
- [📒 Table of Contents](#-table-of-contents)
- [📍 Overview](#-overview)
- [⚙️ Features](#-features)
- [📂 Project Structure](#project-structure)
- [🧩 Modules](#modules)
- [🚀 Getting Started](#-getting-started)
- [🗺 Roadmap](#-roadmap)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)
- [👏 Acknowledgments](#-acknowledgments)

---


## 📍 Overview

The project is a simple guessing game where the user has to guess a randomly generated secret number. The program provides feedback if the guess is too small or too big and continues to loop until the correct guess is made. The value proposition of this project is to provide a fun and interactive way for users to test their guessing skills.

---

## ⚙️ Features

| Feature                | Description                           |
| ---------------------- | ------------------------------------- |
| **⚙️ Architecture**     | The codebase follows a simple procedural architecture. It consists of a single source file `main.rs` which contains the main logic for the guessing game. The architecture is straightforward and easy to understand. It generates a random secret number, prompts the user for guesses, and provides feedback until the correct guess is made. The codebase does not employ any specific design patterns or architectural decisions beyond the basic procedural structure. Overall, the architecture is suitable for the simple nature of the project.    |
| **📖 Documentation**   | The documentation for the project is minimal. There is only a brief summary of the functionality provided in the README file of the repository. While the code itself is relatively easy to understand, more comprehensive documentation would be beneficial for developers who are new to the project or unfamiliar with Rust. It would help provide context, explain the choices made, and guide users in contributing to the codebase. It is recommended to enhance the documentation to improve clarity and assist developers.    |
| **🔗 Dependencies**    | The codebase does not have any external dependencies. It relies solely on the standard Rust libraries and does not require any additional systems or libraries to be installed. This makes it easy to set up and run the application without any external dependencies.    |
| **🧩 Modularity**      | The project does not have a strong emphasis on modularity. The entire logic of the guessing game is contained within a single source file `main.rs`. While the code is well-structured and split into multiple functions, there is no clear separation of concerns or modularization of different components. This lack of modularity limits code reusability and maintainability. It would be beneficial to refactor the codebase to extract logical units into separate modules or files, promoting better modularity and separation of concerns.    |
| **✔️ Testing**          | The codebase does not include any automated tests. Lack of testing is a significant drawback as it makes it difficult to verify the correctness of the code and detect potential bugs. The addition of unit tests would greatly improve the stability and reliability of the application. It is recommended to adopt a testing framework, such as Rust's built-in testing capabilities using the `#[test]` attribute, to write tests for the various functions and ensure the accuracy of the game's behavior.    |
| **⚡️ Performance**      | The performance of the guessing game code is satisfactory for its purpose. The execution time depends on the number of guesses made by the user. Since the number range is relatively small (1 to 101), the game's performance is not a major concern. The codebase does not have any performance optimizations or specific considerations for speed or efficiency. However, given the simplicity of the project, the current implementation is acceptable in terms of performance and resource usage.    |
| **🔐

---


## 📂 Project Structure




---

## 🧩 Modules

<details closed><summary>Src</summary>

| File                                                                              | Summary                                                                                                                                                                                                                |
| ---                                                                               | ---                                                                                                                                                                                                                    |
| [main.rs](https://github.com/chmenegatti/guessing_game.git/blob/main/src/main.rs) | The code generates a random secret number between 1 and 101. It prompts the user to guess the number and provides feedback if the guess is too small or too big. It continues to loop until the correct guess is made. |

</details>

---

## 🚀 Getting Started

### ✔️ Prerequisites

Before you begin, ensure that you have the following prerequisites installed:
> - `ℹ️ Requirement 1`
> - `ℹ️ Requirement 2`
> - `ℹ️ ...`

### 📦 Installation

1. Clone the guessing_game repository:
```sh
git clone https://github.com/chmenegatti/guessing_game.git
```

2. Change to the project directory:
```sh
cd guessing_game
```

3. Install the dependencies:
```sh
cargo build
```

### 🎮 Using guessing_game

```sh
cargo run
```

### 🧪 Running Tests
```sh
cargo test
```

---


## 🗺 Roadmap

> - [X] `ℹ️  Task 1: Implement X`
> - [ ] `ℹ️  Task 2: Refactor Y`
> - [ ] `ℹ️ ...`


---

## 🤝 Contributing

Contributions are always welcome! Please follow these steps:
1. Fork the project repository. This creates a copy of the project on your account that you can modify without affecting the original project.
2. Clone the forked repository to your local machine using a Git client like Git or GitHub Desktop.
3. Create a new branch with a descriptive name (e.g., `new-feature-branch` or `bugfix-issue-123`).
```sh
git checkout -b new-feature-branch
```
4. Make changes to the project's codebase.
5. Commit your changes to your local branch with a clear commit message that explains the changes you've made.
```sh
git commit -m 'Implemented new feature.'
```
6. Push your changes to your forked repository on GitHub using the following command
```sh
git push origin new-feature-branch
```
7. Create a new pull request to the original project repository. In the pull request, describe the changes you've made and why they're necessary.
The project maintainers will review your changes and provide feedback or merge them into the main branch.

---

## 📄 License

This project is licensed under the `ℹ️  INSERT-LICENSE-TYPE` License. See the [LICENSE](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/adding-a-license-to-a-repository) file for additional info.

---

## 👏 Acknowledgments

> - `ℹ️  List any resources, contributors, inspiration, etc.`

---
