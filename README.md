# Learning Git via WSL

Welcome to the Git learning repository! This guide will help you get started with Git using Windows Subsystem for Linux (WSL).

## Prerequisites

1. **Install WSL**: Ensure WSL is installed and configured on your Windows machine.
2. **Install Git**: Use the following command to install Git on your WSL:
    ```bash
    sudo apt update
    sudo apt install git
    ```
3. **Set Up Git**: Configure your Git username and email:
    ```bash
    git config --global user.name "Your Name"
    git config --global user.email "youremail@example.com"
    ```

## Topics Covered

- Setting up a Git repository
- Basic Git commands
- Branching and merging
- Working with remote repositories
- Resolving merge conflicts

## Getting Started

1. **Initialize a Repository**:
    ```bash
    git init
    ```
2. **Clone a Repository**:
    ```bash
    git clone <repository-url>
    ```
3. **Add and Commit Changes**:
    ```bash
    git add .
    git commit -m "Your commit message"
    ```

## Resources

- [Git Documentation](https://git-scm.com/doc)
- [WSL Documentation](https://learn.microsoft.com/en-us/windows/wsl/)

Happy learning!