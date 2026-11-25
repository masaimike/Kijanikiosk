(Working Directory vs Staging vs History)
1.Working Directory
- contains files currently stored on my computer . 
-changes are not yest tracked as part of a commit 
-git simply recognized files have been modified
-[git status]allow us to see what git detects

2.Staging Area
-where developers prepare exact set of changes they want included in the next commit
-files are added using [git add <filename>]

3.Repository History
-contains all committed snapshots of the project
- we use the command [ git commit -m "committ message]

(Branching Rules)
A branch is a pointer to a specific commit in the Repository History.It enables developers
to work efiiciently on multiple tasks simultaneously.Once a feature is complete ,it can be merged into a shared branch . Teams can review work before it becomes part ofth e system
 
Pull REquest Expectations
They provide a structuredd process for integrating those changes back into the shared repository.
It displays files that were modified,exact lines of code that changed,the commit message explaining the change.
