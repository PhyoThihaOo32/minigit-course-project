# Homework 2 — Part 2 Submission

Student name: Phyo T. Oo

GitHub username: PhyoThihaOo32

## 1. Git Command Observations

| Command or workflow  | What did you observe?                                                                                                   | What was the user trying to accomplish?                                                                                                   | What problem or risk did it address?                                                                                                                                                                                         |
| -------------------- | ----------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1. git status        | It showed which branch I was on and whether there were modified, staged, or untracked files.                            | The user wanted to understand the current state of the project before taking the next action.                                             | It helped confirm the correct branch and showed which files had changes and which files needed to be committed.                                                                                                              |
| 2. git diff          | It showed the detailed changes (including file names and line numbers) in my working tree that had not been staged yet. | The user wanted to review exactly what had changed before selecting the changes for the next saved version.                               | It helped find mistakes or unwanted changes before moving forward.                                                                                                                                                           |
| 3. git add <file>    | The selected file was added to the staging area, which is the place between the working tree and local repository.      | The user wanted to choose specific changes, organize them, and put them in one place before adding them to the final local repository.    | This additional layer helps us undo decisions, double-check the files and changes made in the files, put them back into the working tree, and re-edit them before taking a snapshot and adding them to the local repository. |
| 4. git diff --staged | It showed the detailed changes that were already added to the staging area and ready for the next commit.               | The user wanted to review and double-check the selected changes before taking the final snapshot and adding them to the local repository. | It helped make sure only the correct and intended changes were staged and gave the user another chance to catch mistakes before committing.                                                                                  |

## 2. User Needs

### UN-GIT-01 — Check Current Project State

> A developer needs a way to check the current state of the project because they want to make sure they understand and keep track of anything important before taking further action.

### UN-GIT-02 — Select and Organize Intended Changes

> A developer needs a way to put updated files in a temporary place between the actual working area and the archive because they want to review and organize the files before finally adding them to the archive.

### UN-GIT-03 — Verify and Preserve Changes

> A developer needs a way to double-check which files and changes are finally going to be added to the archive (local repository) because they do not want broken or incomplete work to be added, which could damage the whole project.

## 3. User Requirements

| ID and short title                        | User requirement                                                                                                                                          | Source user need        | Rationale                                                                                                                                                                        |
| ----------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| UR-GIT-01 — Check Project State           | A developer shall be able to see the current state of the project, including the current working places and changed files, before taking the next action. | UN-GIT-01               | This helps the developer to clarify if he is at the right working place, understand what is happening in the project, and avoid taking action without knowing its current state. |
| UR-GIT-02 — Select and Organize the Files | A developer shall be able to select updated files and place them in a temporary area before permanently saving them to the local repository.              | UN-GIT-02               | This gives the developer a place to organize and review selected files before adding them to the project history.                                                                |
| UR-GIT-03 — Double-Check Selected Changes | A developer shall be able to review the files and changes selected for the next saved version before finally adding them to his local project (archive).  | UN-GIT-03               | This helps prevent broken, incomplete, or unwanted work from being added to the project history.                                                                                 |
| UR-GIT-04 — Create a Snapshot             | A developer shall be able to create a snapshot of the selected and verified changes and save it permanently in the local repository.                      | [Not specified in DOCX] | This allows the developer to use a commit to preserve the correct version of the project in the local repository after all selected changes have been reviewed.                  |
