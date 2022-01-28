1. How do you see the files changed within each commit from git log?
A: by entering the command: git log --stat
2. How do you see the contents of what changed within each file from the git log?
A: by entering the command: git log --patch
3. What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)
A: HEAD reffers to the most recent commit in history. I.E. when using --diff it displays changes made to a file since the last commit only.