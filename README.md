# Introduction to Code Sharing

If you're a developer who writes code that other developers will use or modify, you should get comfortable with a version control system. The most popular system is Git, and this tutorial explains how to get started with Git using GitHub.

## Code sharing requirements

- Developers need an easy way to share files
- Code changes should be tracked
- It should be possible to experiment with changes without breaking it for others

## Code sharing solutions

- Git
- Mercurial
- Subversion
- Microsoft Team Foundation Server

This tutorial will focus on Git since it is the most widely-used code-management tool. [`source`](https://en.wikipedia.org/wiki/Git#Adoption)

## Introduction to Git

Git allows developers to take "snapshots" of their code. This makes it easy to refer to previous code versions when something breaks, and to test new experimental changes without breaking the existing stable code. 

Here is a summary of how this works:

1. Create a repository with `git init [project-name]` or clone an existing repository with `git clone [url]`
2. Add files to the staging area with `git add [file] or git add *`
3. Commit staged files to the repository with `git commit -m “[message]”` (This requires repository write-access)

To learn more about setting up and using Git, visit https://help.github.com/articles/set-up-git

## Introduction to GitHub

GitHub is the most widely-used implementation of Git. Interactions with code repositories can all be done via the web browser, and additional functionality is provided by desktop clients compatible with GitHub.

GitHub provides [an excellent "Hello World" tutorial](https://guides.github.com/activities/hello-world/) that teaches you how to use their platform, but I'll summarize the basics below.

**Before you begin:** [Create a free account](http://github.com/) at GitHub

### 1. Create a repository

![image](https://user-images.githubusercontent.com/1199572/42891884-65055ba6-8a7e-11e8-837d-48319882bc64.png)

![image](https://user-images.githubusercontent.com/1199572/42891795-36127b80-8a7e-11e8-8b47-40f379ad4b55.png)

### 2. Create a branch

![image](https://user-images.githubusercontent.com/1199572/42899552-703ffc22-8a94-11e8-9458-0a9994d358b7.png)

### 3. Change files and commit the changes to the new branch

![image](https://user-images.githubusercontent.com/1199572/42899678-c782aeda-8a94-11e8-8ecf-7e0b88a27483.png)

### 4. Open a pull request

![image](https://user-images.githubusercontent.com/1199572/42899747-fe4ebcb0-8a94-11e8-9c0f-6608c77d85e4.png)

### 5. Merge and close the pull request

![image](https://user-images.githubusercontent.com/1199572/42899820-319fa796-8a95-11e8-8936-8bec01c44d63.png)

## Git Clients

Although the GitHub website provides a basic demonstration of Git functionality, it is more practical to install a desktop client if you plan to use Git as part of your daily programming workflow. Here is a partial list of Git-compatible clients:

- [Sourcetree](https://www.sourcetreeapp.com/) (Currently my favorite) | Windows, Mac | Free
- [GitHub Desktop](https://desktop.github.com/) | Windows, Mac | Free
- [SmartGit](https://www.syntevo.com/smartgit/) | Windows, Mac, Linux | $79/user / Free for non-commercial use
- [More clients](https://git-scm.com/download/gui/windows)

## Learn More

This tutorial barely scratches the surface of Git, its GitHub implementation and other version control systems. Here are some additional resources to help you understand code sharing.

- [Git Website](https://git-scm.com/)
- [GitHub Website](https://github.com/)
- [GitHub Guides](https://guides.github.com/)
- [GitHub Explore](https://github.com/explore)
- [GitHub On Demand Training](https://services.github.com/on-demand/)
