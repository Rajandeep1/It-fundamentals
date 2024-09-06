# [Project Name]

## Description

MODULE 1

## Author

Rajandeep Kaur
Changes to a new branch
## Assignment

Assignment - 1

## Purpose of the Following Git Commands

- **`git init`**:
  - **Purpose:** Initializes a new Git repository in the current directory.
  - **Usage Example:** 
    ```bash
    git init
    ```

- **`git status`**:
  - **Purpose:** Shows the status of changes in the working directory and staging area.
  - **Usage Example:**
    ```bash
    git status
    ```

- **`git add`**:
  - **Purpose:** Stages changes in the working directory for the next commit.
  - **Usage Example:**
    ```bash
    git add filename
    ```
    Use `.` to add all changes:
    ```bash
    git add .
    ```

- **`git commit`**:
  - **Purpose:** Commits the staged changes to the repository with a descriptive message.
  - **Usage Example:**
    ```bash
    git commit -m "Commit message"
    ```

- **`git push`**:
  - **Purpose:** Uploads local commits to the remote repository.
  - **Usage Example:**
    ```bash
    git push origin branch-name
    ```

- **`git pull`**:
  - **Purpose:** Fetches and integrates changes from the remote repository into the local repository.
  - **Usage Example:**
    ```bash
    git pull origin branch-name
    ```

- **`git log`**:
  - **Purpose:** Displays the commit history for the repository.
  - **Usage Example:**
    ```bash
    git log
    ```

- **`git branch`**:
  - **Purpose:** Lists, creates, or deletes branches.
  - **Usage Example:**
    ```bash
    git branch
    ```
    Create a new branch:
    ```bash
    git branch new-branch-name
    ```

- **`git merge`**:
  - **Purpose:** Merges changes from one branch into another.
  - **Usage Example:**
    ```bash
    git merge branch-name
    ```

- **`git checkout`**:
  - **Purpose:** Switches branches or restores working directory files.
  - **Usage Example:**
    ```bash
    git checkout branch-name
    ```
    Create and switch to a new branch:
    ```bash
    git checkout -b new-branch-name
    ```

## First Git Status Output:
*Include the output of `git status` before making changes here.*

## Second Git Status Output:
*Include the output of `git status` after making changes here.*

## Steps to Update `README.md`:

1. **Open `README.md`:**
   - Open the `README.md` file in Visual Studio Code or another text editor.

2. **Add the Information:**
   - Copy and paste the above content into your `README.md` file, or modify it to fit your needs.

3. **Save the File:**
   - Save your changes to the `README.md` file (usually by pressing `Ctrl + S` or `Cmd + S`).

4. **Commit Changes (if using Git):**
   - Stage and commit the changes if you’re using Git for version control:
     ```bash
     git add README.md
     git commit -m "Add purpose of common Git commands to README.md"
     git push
     ```
