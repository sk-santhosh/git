# Git Basics for Beginners

Welcome to the world of version control with Git! Whether you're a developer, designer, or just someone looking to collaborate on projects, understanding these basic Git commands is essential. This guide will walk you through the fundamental Git commands to help you get started.

## Table of Contents
- [Git Basics for Beginners](#git-basics-for-beginners)
  - [Table of Contents](#table-of-contents)
  - [1. Installation](#1-installation)
  - [2. Configuration](#2-configuration)
  - [3. Initialization](#3-initialization)
  - [4. Cloning a Repository](#4-cloning-a-repository)
  - [5. Making Changes](#5-making-changes)
    - [5.1. Checking the Status](#51-checking-the-status)
    - [5.2. Adding Changes](#52-adding-changes)
    - [5.3. Committing Changes](#53-committing-changes)
  - [6. Branching](#6-branching)
    - [6.1. Creating a New Branch](#61-creating-a-new-branch)
    - [6.2. Switching Branches](#62-switching-branches)
    - [6.3. Merging Branches](#63-merging-branches)
  - [7. Remote Repositories](#7-remote-repositories)
    - [7.1. Pushing Changes](#71-pushing-changes)
    - [7.2. Pulling Changes](#72-pulling-changes)
  - [8. Version Tags](#8-version-tags)
  - [9. Release Workflow](#9-release-workflow)
    - [9.1. Development Branch](#91-development-branch)
    - [9.2. Staging Branch](#92-staging-branch)
    - [9.3. Live (Master) Branch](#93-live-master-branch)
  - [10. Conclusion](#10-conclusion)

## 1. Installation

First things first, make sure Git is installed on your machine. You can download it from [git-scm.com](https://git-scm.com/).

## 2. Configuration

Set up your Git user information using the following commands:

```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

## 3. Initialization

Initialize a new Git repository in your project directory:

```bash
git init
```

## 4. Cloning a Repository

Clone an existing repository to your local machine:

```bash
git clone <repository_url>
```

## 5. Making Changes

### 5.1. Checking the Status

Check the status of your working directory:

```bash
git status
```

### 5.2. Adding Changes

Stage changes for commit:

```bash
git add <file_name>
```

### 5.3. Committing Changes

Commit your changes with a descriptive message:

```bash
git commit -m "Your commit message here"
```

## 6. Branching

### 6.1. Creating a New Branch

Create a new branch for your work:

```bash
git branch <branch_name>
```

### 6.2. Switching Branches

Switch to a different branch:

```bash
git checkout <branch_name>
```

### 6.3. Merging Branches

Merge changes from one branch into another:

```bash
git merge <branch_name>
```

## 7. Remote Repositories

### 7.1. Pushing Changes

Push your changes to a remote repository:

```bash
git push origin <branch_name>
```

### 7.2. Pulling Changes

Pull changes from a remote repository:

```bash
git pull origin <branch_name>
```

## 8. Version Tags

Tag specific commits for versioning:

```bash
git tag -a v1.0 -m "Version 1.0"
```

## 9. Release Workflow

### 9.1. Development Branch

Create and work on a development branch:

```bash
git checkout -b dev
```

### 9.2. Staging Branch

Merge development changes into the staging branch:

```bash
git checkout stage
git merge dev
```

### 9.3. Live (Master) Branch

Merge staging changes into the live (master) branch for release:

```bash
git checkout master
git merge stage
```

## 10. Conclusion

Congratulations! You now have a basic understanding of essential Git commands. Remember to practice and explore advanced Git features to enhance your version control skills. Happy coding!
