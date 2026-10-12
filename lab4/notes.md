# Lab 4: Git & GitHub — Answers

## Question 1
The `--global` option saves my name and email for all Git repositories belonging to my user account. Without it, the settings would apply only to the current repository if I used `--local`, or Git might use another available configuration.

## Question 2
The `ls -a` command showed a hidden folder called `.git` that did not appear in a normal `ls` listing. It contains Git's internal data, including repository history, configuration, and information needed to track changes.

## Question 3
Git showed the files and folders in my project that had not yet been tracked. The `.venv` folder may contain many files from external Python packages that I did not write myself.

## Question 4
After creating `.gitignore`, Git stopped listing files such as `.DS_Store`, `.pyc` files, and files inside `.venv/` as untracked. These files are now ignored according to the rules in `.gitignore`.

## Question 5
The `.gitignore` file should be committed because it tells Git which files to ignore. Keeping it in the repository helps everyone working on the project follow the same rules.

## Question 6
`README.md` moved from the untracked files section to the changes to be committed section after I ran `git add README.md`. This means the file moved from the working directory into the staging area.

## Question 7
After the commit, Git displayed a summary containing the commit information, the number of files changed, and any insertions or deletions. The exact number of changed files depends on the output of my commit.

## Question 8
The first seven characters are the short form of the commit hash, a unique identifier for a commit. They help me identify and refer to a particular version of my project.

## Question 9
The four steps are edit, stage, commit, and repeat. Editing changes the files, staging selects the changes, and committing saves them in the repository history.

## Question 10
`README.md` is a standard file name that GitHub automatically displays on the repository's front page. It gives readers an introduction to the project and explains its contents.

## Question 11
`gh auth login` authenticated me with GitHub and saved the necessary authentication credentials. This allows GitHub CLI and Git to authenticate future operations without repeatedly asking for my account password.

## Question 12
The GitHub repository's front page displays `README.md` as formatted text. GitHub automatically renders this file because it is a standard place for project information.

## Question 13
Pushing did not change my local commit history. It uploaded my existing commits to GitHub so that the remote repository could have the same history.

## Question 14
A private repository exists on GitHub but can only be accessed by its owner and people who have been granted permission. If a repository does not exist on GitHub, there is no remote repository there to access or collaborate on.