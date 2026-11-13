Lab 1: Starting a Git Repository

Name: Aryan Gangwar

Roll Number: 2410303583


Course: BCS554 - HTML and CSS Development Lab

University: Invertis University, Bareilly (B.Tech CSE)

Aim:

To create a Git repository, set the author name and email, make two commits and read the history with git log.

Theory:

1. Git is a version control system. It remembers every saved version (commit) of a project, so you can go back or compare.
2. A repository is a project folder that Git tracks. The command git init creates a hidden .git folder inside it.
3. The commands git config --local user.name and user.email set the author for this repository only. Running the same command without a value prints the saved value.
4. Git has three areas: the working directory (your files), the staging area (files chosen for the next commit) and the repository (saved commits).
5. git status shows the state of each file: untracked (new), modified or staged.
6. git add file moves a file to the staging area. git commit -m with a message saves a snapshot.
7. git log --oneline shows the history, one line per commit, newest first.

Tasks done:

1. Task 1: Created the folder html-lab, ran git init, set user.name and user.email with git config --local and printed both values.
2. Task 2: Created index.html with an h1 heading, checked git status, ran git add and committed with the message Add home page.
3. Task 3: Added an h2 heading, committed again with the message Add next meeting heading and viewed the history with git log --oneline.

Files in this folder:

1. index.html: the page with the work of this lab.
2. style.css: the stylesheet of the page.
3. images/screenshot.png: screenshot of the output.

How to run:

The commands are given in the screenshot. Run them in a terminal inside the folder git-practice.
