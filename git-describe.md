## Git vs Git Bash vs GitHub

this file contains all the info I've learnt about Git, Git Bash and GitHub

### What is Git?
Git is a version control system for tracking source code changes during software development

### What is Bash?
Git Bash is an application for Microsoft Windows environments which provides an emulation layer for a Git command line experience

### What is GitHub?
GitHub is a Git repository hosting service, but it adds many of its own features. While Git is a command line tool, GitHub provides a Web-based graphical interface.


### Git syntax
- Where can I go?
  - ls -a
- Where am I?
  - pwd
- Go somewhere
  - cd <location>
- Create something?
  - touch <file name>
- remove something?
  - rm <file>, rm -rf <directory name>
- Make directory?
  - mkdir <directory name>
- Delete directory
  - rm -rf <directory name>
- Initialise master timeline?
  - git init
- Get status?
  - git status
- Add a file to be commited to GitHub?
  - git add <file name>
- How to commit a file?
  - git commit -m <'Include a comment so its easier to track your code'>
- Show the log?
  - git log
- The git checkout command lets you navigate between the branches created by git branch . Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.
  - git checkout <>
- What is git ignore?
  - use it to hide files you dont want pushed to GitHub
  - Place the name of the file(s) you want hidden in the touch .gitignore
  - .gitignore
- How to add a remote repository to git hub?
  - Create a repsitory on your GitHub home page.
  - Follow the instructions to add the remote to git bash.
  - git add remote <repository location on GitHub>
- How to push the file to GitHub?
  - git push origin master
