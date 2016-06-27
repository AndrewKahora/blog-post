---
layout: post
posts: Github commits part 2
---

commiting
---------

1. git status - checks the current status of the repository. This tells you a lot of things; at the moment, it’s telling you that you don’t any uncommitted changes in your repository.
2. touch README.md - create a README file. The .md suffix is indicative that the file will be formatted in Markdown, which is widely used for formatting on the GitHub website.
3. git status - same command, second time. This time, you can see that there’s a new file, but it’s “untracked”. That means it won’t be included in the commit. You’ll need to add it, first.
4. git add . - add all untracked files to the repository (at least, those untracked files which are not omitted by the .gitignore file). You can, of course, add files individually by replacing the . with the file name.
5. git status - now the README.md file is showing as a new file to be committed.
6. git commit -m “Add README.md” - commit the recent changes. The -m switch allows you to enter a short double-quoted commit message. Omitting that switch will cause git to open a text editor so you can enter a longer message; save and close the text editor when you’re done.
