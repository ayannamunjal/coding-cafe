Question 1
--global makes the Git configuration apply to all repositories for the current user on the computer. Without --global, the configuration applies only to the current repository.

Question 2
ls -a shows hidden files and folders inside the repository. The .git folder contains Git's internal information, including configuration, objects, references, and logs used to track the repository and its history.

Question 3
The approximate number of untracked files depends on the files created in the repository. git status identifies untracked files by listing them under "Untracked files."

Question 4
After creating .gitignore, files and folders matching its rules no longer appear as untracked files in git status. The .gitignore file itself appears as an untracked file because it has not yet been committed.

Question 5
.gitignore should be committed because it tells everyone working on the repository which files Git should ignore. This keeps the same ignore rules when the repository is shared or cloned.

Question 6
README.md moves through three states:
Untracked - Git sees the file but is not tracking it.
Staged - after git add README.md, it is prepared for the next commit.
Committed - after git commit, it becomes part of the repository's history.

Question 7
git commit produces a message showing the new commit's hash and summary of the changes, including the number of files changed. In this lab, the first commit changed 3 files: .gitignore, README.md, and lab4/notes.md.

Question 8
The first seven characters of a commit hash are an abbreviated commit ID (SHA-1 hash). They uniquely identify a commit within the repository and can be used to refer to that commit.
