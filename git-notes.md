# Git Notes 📝

## What is Git?

Git is a **Version Control System (VCS)** that helps track changes in code, similar to how a bank account tracks debit, credit, and balance information.  
It maintains a history of project developments, making it a crucial tool for collaborative work and version management.

---

## Why is Git Popular?

Git is widely used globally, both in small and large projects, due to its:

- 🟢 **Open-source nature**: Freely available and community-driven
- ⚡ **Speed and scalability**: Efficient and adaptable to projects of all sizes
- 🌍 **Industry adoption**: Widely used in companies and organizations

---

## Benefits of Using Git

- ✅ Tracks changes and maintains project history
- 🤝 Facilitates collaboration and version management
- 🚀 Fast, scalable, and reliable

## 🔧 Primary Purposes of Git

Git is used for two primary purposes:

---

### 1. 🕓 Tracking Project History

Git helps us keep a record of changes made to our codebase over time.

For example:
- You can track the addition of new features like a **sign-up page** or **specific buttons** on a website.
- If you ever need to revisit a particular stage or figure out where a certain piece of code came from, Git's version control system makes that easy.

---

### 2. 🤝 Collaboration

Git enables multiple people to work on a single project at the same time, which is especially helpful in companies with large teams.

- It tracks who made what change.
- Prevents overwriting each other’s code.
- Ensures a smooth and conflict-free collaboration process.

## 🔗 Git vs GitHub

Git and GitHub are related but distinct concepts:

- **Git** is a **version control tool** that helps developers track changes in their codebase.
- **GitHub** is a **web-based platform** that allows developers to store and manage their Git repositories online.

---

## 💼 GitHub & Your Developer Profile

On a resume, it's common to include a link to your **GitHub profile** to showcase your:

- Projects
- Code quality
- Contributions

This allows recruiters and collaborators to view your work and assess your skills.

---

## 📁 What Are GitHub Repositories?

On GitHub, projects are stored in containers called **Repositories** (think of them like folders).  
Each repository contains:

- Project files (HTML, CSS, JS, etc.)
- Version history
- ReadMe, documentation, and other metadata

By sharing your repositories, you make your work **visible to others** — including potential employers!

## 📘 Git and GitHub Basics

- A **Repository (Repo)** can be either:
  - **Public**: Anyone can view/access it.
  - **Private**: Only selected users can access it.

---

### 🔄 Committing Changes

- A **commit** is like saving a snapshot of your changes.
- When you commit, you're saying: _"These changes are final now."_

Typical Git workflow:

1. Make changes to your code or files
2. **Add** the changes to the staging area (`git add`)
3. **Commit** the changes (`git commit`) – now they're saved in the version history

---

## ☁️ GitHub-Specific Notes

- On **GitHub**, commits are made directly to the repository and become part of the project's history.
- When editing files (like `README.md`) on GitHub, you can use:
  - **Markdown**: A lightweight language for formatting
  - Some basic **HTML elements**

---

### ✍️ Markdown Formatting Tips

- Use `#` for headings
- `-` or `*` for bullet points
- `**bold**` or `_italic_` for text styling
- New lines can be made with 2 spaces at the end of a line or by pressing enter twice

---

### 📄 Importance of the `README.md` File

The `README.md` file is a key part of any GitHub repository. It usually includes:

- 📝 **Project introduction**
- 🧩 **Instructions** for setup or usage
- 📎 **Other relevant details** (links, credits, etc.)

It helps others quickly understand what your project is and how to use it.

## 🛠️ Setting Up Git

- **GitHub** is a web-based platform, but to use **Git**, you need to set it up on your **local computer system**.

---

### 💻 Tools You’ll Use

To work with Git, you’ll typically use a **terminal** or a **code editor**:

- 🧠 **Popular Code Editor**:  
  - [Visual Studio Code (VS Code)](https://code.visualstudio.com/)  
  - Supports all programming languages and integrates well with Git

- 🪟 **For Windows**:  
  - Use **Git Bash** or **Command Prompt**

- 🍎 **For Mac**:  
  - Use the built-in **Terminal**

---

### ⚙️ Once Git is Installed

You can run Git commands in your terminal or directly from your code editor to:

- Manage your repositories
- Track changes in your code
- Collaborate with others more efficiently

## 🧪 Common Git Bash Commands

Use these commands to check if Git is properly set up and to navigate your system via the terminal:

- ```git --version```  
  ✅ Check the version of Git installed on your system

- ```ls```  
  📂 List all files and folders in the current directory

- ```clear```  
  🧼 Clear the terminal screen

- ```pwd```  
  📍 Print the current working directory


## ⚙️ Configuring Git

When working with Git, you need to configure your **identity** — your **name** and **email address**.  
This information is used to track who made changes to the repository.

---

### 🧭 Global vs Local Configuration

You can configure Git using the `git config` command with different scopes:

---

#### 🌍 Global Configuration
Sets identity for **all repositories** on your system:


git config --global user.name "Your Name"

git config --global user.email "your_email@example.com"

#### 📁 Local Configuration
Sets identity for **a specific repository** (omit `--global`):


git config user.name "Project-Specific Name"
git config user.email "project_email@example.com"

By setting your **global configuration**, you'll use the same identity across **all Git projects**.  
Use **local configuration** when working with **multiple GitHub accounts** or **collaborative/team-specific projects**.

### 🔍 View Current Configuration

To check your Git config settings, use:

_git config --list_


## 📥 Cloning a Repository Using Git

Follow these steps to clone a repository to your local machine:

---

### 🔗 Cloning a Repository

1. **Go to GitHub**:  
   Find and open the project you want to clone.

2. **Get the Repository URL**:  
   Click the **"Code"** button (top-right of the repo), choose **HTTPS**, and copy the link.

3. **Open Terminal**:  
   Use your terminal, Git Bash, or any command line tool.

4. **Navigate to the Desired Folder**:  
   Use the `cd` command to go to the folder where you want to clone the project.

5. **Clone the Repository**:  
   Run the following command (replace with the actual URL you copied):

   ```bash
   git clone https://github.com/username/repository_name.git

This will copy the entire repository to your local system.

### 📌 Checking Status

After cloning (or making changes), use this command to check the status of your repository:


```git status```

It shows:

🆕 Untracked files — files that are not yet being tracked by Git

📝 Modified files — files that have been changed but not staged

✅ Changes staged for commit — files added to the staging area, ready to be committed


## 📂 Terminal Basics: Navigating & Listing Files

These basic commands are essential for navigating and managing files in your terminal or Git Bash:

---

### 📁 Navigating Directories

- `cd` : **Change Directory** — used to move into a specific folder

  **Example:**

  ```bash
  cd directory_name

(Note: If your folder name has spaces, use quotes or backslash escape)

⌨️ Autocomplete Tip:
Press the Tab key while typing a folder name to autocomplete it

📄 Listing Files

```ls``` : List files and directories in the current directory
ls -a : List all files, including hidden files (those starting with a dot .)

## 📂 File States in Git

Files in Git can be in one of the following four states:

---

### 1. 🆕 **Untracked (U)**

- New files that Git doesn't yet track.
- You can start tracking them with:

  ```bash
  git add <filename>

### 2. 📝 **Modified (M)**

- Files that have been **changed** but not yet staged for commit.
- To stage them for commit, use:

  ```bash
  git add <filename>

### 3. ✅ **Staged**

- Files that are **ready** to be committed (they appear under "Changes to be committed" when you run `git status`).

- You can now commit these changes with:

  ```bash
  git commit -m "Your commit message"

 ### 4. ✔️ **Unmodified (or Committed)**

- Files that are **unchanged** since the last commit, or have already been committed.
- These files are up-to-date with the latest commit.
 

## 📌 Adding and Committing Files

### 1. 🔹 Adding Files

To track new and modified files, add them to the Git staging area using:


```git add <filename>```

Or to add **all files** in the working directory, use:


```git add .```
> The `.` command adds **all files** in the current directory.
Once added, files are marked with an **"A"** sign, indicating they’ve been added to the staging area.

### 2. 🔹 Committing Changes

A commit is a snapshot of your staged changes. Use:


```git commit -m "meaningful message"```

✅ Your message should clearly describe the changes made (e.g., `"fix new bug"`, `"add feature"`).

After committing:

- `git status` will show: `"nothing to commit, working tree clean"`
- Git may also say: `"Your branch is ahead of 'origin/main' by 1 commit."`

### 3. 🔹 Pushing Changes

To upload local commits to the remote repository, use:


```git push origin main```
- `origin` is the name of the **remote repository** (default name when you clone a repo).
- `main` is the name of the **branch** you’re pushing to (you’ll learn more about branches later).

### 🕓 Git Tracks History Through Commits

Each commit represents a version of your project.  
By viewing the commit history, you can trace the evolution of your codebase and understand what changed, when, and why.


# 🛠️ Managing Git with a Local Project

## 📁 Creating a New Git Repository

1. **Create a new folder**: You can create a new folder in VS Code or use the command line:
    ```bash
    mkdir <folder_name>
    # Example:
    mkdir LocalRepo
    ```

2. **Navigate to the folder**: Use the `cd` command to enter the folder:
    ```bash
    cd <folder_name>
    # Example:
    cd LocalRepo
    ```

3. **Initialize Git**: Run the following command to create a new Git repository in the folder:
    ```bash
    git init
    ```

---

## 🔄 Working with Git

1. **Create files**: Add files to your project folder as needed.

2. **Stage changes**:
    - To stage all changes:
        ```bash
        git add .
        ```
    - To stage a specific file:
        ```bash
        git add <file_name>
        ```

3. **Commit changes**: Use the following command to commit changes with a message:
    ```bash
    git commit -m "<meaningful_message>"
    ```

---

## 📂 Navigating Directories

- `cd <directory_name>`: Takes you inside a directory.
- `cd ..`: Takes you back to the parent directory.

---

By following these steps, you can manage your project with Git and track changes using commits.


# 🔗 Linking Local Repository to GitHub

## 📂 Create a New Repository on GitHub
1. **Create a new repository on GitHub**: Go to your GitHub profile and create a new repository.

## 📋 Copy the HTTPS Link
2. **Copy the HTTPS link**: Copy the HTTPS link of your new repository.

## 🔧 Set the Remote Origin
3. **Set the remote origin**: In VS Code, run the following command to link your local repository to GitHub:
    ```bash
    git remote add origin <HTTPS_link>
    ```
    - `origin` is the name given to the remote repository (you can use any name, but `origin` is conventional).

## ✅ Verify the Remote
4. **Verify the remote**: Run the following command to verify the remote origin:
    ```bash
    git remote -v
    ```

---

## 🌿 Working with Branches

1. **Check the current branch**: Run `git branch` to check which branch you're on.

2. **Rename the branch (optional)**: If you're using a branch named "master" and want to rename it to "main", run:
    ```bash
    git branch -M main
    ```

---

## 🚀 Pushing Changes to GitHub

1. **Push changes**: Run the following command to push your changes to GitHub:
    ```bash
    git push origin main
    ```

2. **Set upstream (optional)**: To set the upstream tracking information (so you can push without specifying remote/branch), run:
    ```bash
    git push -u origin main
    ```
## ✔️ After Setting Upstream
- You can now use `git push` without specifying the remote and branch.
- Make changes, add, commit, and push using `git push`.


# 🌿 Git Branches in detail  :

## What are Git Branches?

Git branches are separate lines of development in a repository. They allow multiple developers to work on different features or tasks independently without affecting the main codebase.

## Benefits of Git Branches

1. **Parallel Development**: Multiple developers can work on different features simultaneously without conflicts.
2. **Isolation**: Changes made in one branch don't affect other branches.
3. **Flexibility**: Branches can be created, merged, or deleted as needed.

## Common Branching Workflow

1. **Main Branch (e.g., `main`/`master`)**: The primary branch that reflects the production-ready state of the code.
2. **Feature Branches**: Created for specific features or tasks. These branches are merged into the main branch once the work is complete.
3. **Merge**: When a feature branch is complete, it's merged into the main branch, incorporating the changes.

## Example Scenario

1. **Developer 1** creates a branch for **Feature 1** and starts working on it.
2. **Developer 2** creates a branch for **Feature 2** and starts working on it, without waiting for Developer 1 to finish.
3. Both developers can work independently, committing changes to their respective branches.
4. Once a feature is complete, the corresponding branch is merged into the **main** branch.

By using Git branches, teams can collaborate efficiently, manage multiple features, and maintain a stable codebase.

# 🌿 Git Branch Commands & Workflow

## 🔧 Git Branch Commands

1. `git branch`  
   → List all branches in your repository.

2. `git branch -M main`  
   → Rename the current branch to `main`.

3. `git checkout <branch_name>`  
   → Switch to a different branch.

4. `git checkout -b <new_branch_name>`  
   → Create a new branch and switch to it immediately.

5. `git branch -d <branch_name>`  
   → Delete a branch (must be on a different branch to delete).

---

## 🔄 Working with Branches

- When you create a new branch and make changes, those changes exist **only** in that branch.
- If you switch to another branch (e.g., `main`), changes in the other branch will **not** appear.
- To bring those changes into another branch, you must **merge** them using:

     ```git merge <branch_name>```

## ☁️ Pushing Changes to GitHub

To push changes from a new branch to GitHub, use the command:


```git push origin <branch_name>```

This will upload the contents of the branch to your remote GitHub repository, making it accessible to collaborators or for use in pull requests.

(By using Git branches, you can manage different versions of your codebase and collaborate with others efficiently. Branching allows for safer experimentation, independent development, and cleaner workflows.)


## 🔀 Merging Code and Managing Pull Requests

### ✅ 2 Ways of Merging Code

1. **Local Merge**
   - Use the following command to merge branches locally:
     ```
     git merge <branch_name>
     ```
     Example: If you're on a new branch and want to merge it with the `main` branch:
     ```
     git merge main
     ```

   - **Comparing Branches**
     You can compare branches using:
     ```
     git diff <branch_name>
     ```
     Example: To compare your new branch with the `main` branch:
     ```
     git diff main
     ```

2. **Using GitHub to Merge Code**
   - **Create a Pull Request (PR)**: A PR lets you tell others about changes you've pushed to a branch.
   - **Code Review**: Senior developers can review and comment on your code before it's merged into the `main` branch.
   - **Merging a PR**: Once a PR is approved, the code can be merged into `main`.

### ⚠️ Resolving Conflicts

- If your new branch and main have conflicts, GitHub won’t auto-merge.
- Conflicts must be resolved manually before the merge.

### 🧠 Best Practices

- Create a new pull request for each new branch or set of changes.
- Provide clear descriptions in PRs explaining the changes made.
- Use PRs to collaborate, get feedback, and ensure high-quality code.

## 🔄 Keeping Your Local Repository Updated

When changes have been made in the remote repository (e.g., GitHub) but aren't reflected in your local repository (e.g., VS Code), use the `git pull` command.

### 📥 Git Pull Command


```git pull origin main```

This command fetches changes from the remote repository named origin and merges them into your local main branch.

By running this command, you'll synchronize your local codebase with the latest updates from GitHub, ensuring everything is up to date.

# 🔧 Resolving Merge Conflicts in Git

## ❓ What are Merge Conflicts?

- Merge conflicts occur when Git is unable to automatically merge changes from two different commits.
- This happens when changes are made to the same file and line in different branches.

---

## 📌 Example Scenario

- You make changes to a file in the `main` branch.
- You create a new branch (`feature1`) and make different changes to the same file and line.
- When you try to merge `feature1` into `main` using:

  
  ```git merge feature1```

## 🛠️ Resolving Merge Conflicts

### 🔍 Using VS Code

VS Code provides a smart editor with the following options when a merge conflict occurs:

- **Accept Current Change** – Keeps the changes in the current branch.
- **Accept Incoming Change** – Keeps the changes from the branch being merged in.
- **Accept Both Changes** – Includes both sets of changes in the file.
- **Compare Changes** – Lets you view a side-by-side diff to decide how to resolve the conflict.

---

### ✍️ Manual Resolution

You can also resolve merge conflicts manually by following these steps:

1. Open the conflicted file and locate the conflict markers:
   ```bash
   <<<<<<< HEAD
   // current branch changes
   =======
   // incoming branch changes
   >>>>>>> feature1

2. Decide which version of the code to keep: current branch, incoming branch, or a combination.

3. Remove the conflict markers (<<<<<<<, =======, >>>>>>>), and edit the code as needed.

4. Save the file.

5. Stage the resolved file. 

6. Commit the resolution. 

Now your conflict is resolved and the merge can proceed successfully.


## 🔄 Undoing Changes in Git

### 🧩 Case 1: Unstaging Changes

- If you've staged changes using `git add` but haven't committed them yet, you can unstage them with:
  
  ```git reset <filename>```

This removes the file from the staging area. The changes remain in the working directory and are marked as modified.

### 🧩 Case 2: Undoing the Last Commit

To undo the most recent commit but keep the changes in your working directory:

```git reset HEAD~1```

This moves the HEAD pointer back by one commit and unstages the changes.

[🔁 Understanding HEAD

HEAD points to your current commit.

HEAD~1 moves back one commit.

HEAD~2, HEAD~3, etc. move back multiple commits.]

### 🧩 Case 3: Undoing Multiple Commits

Use the following command to reset to a specific previous commit:

```git reset <commit_hash>```

This removes the commits from history but keeps the changes in your working directory.
This will remove the commits from the log, but the changes will remain in your working directory.

(You can find the commit hash using ```git log``` )

🧹 Removing Changes Completely :
To remove all changes and reset your working directory to a specific commit:
git reset --hard <commit_hash>

⚠️ Warning: This will permanently discard changes not committed.

By using these commands, you can effectively undo changes, clean up your repository, and manage your Git history.

# Great we have finished our Git and Github Tutorial
# Thankyou 😄