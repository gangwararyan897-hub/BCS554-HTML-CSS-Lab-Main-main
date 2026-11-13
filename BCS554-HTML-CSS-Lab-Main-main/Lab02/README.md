Lab 2: Pushing and Starting Cloning a Repository

Name: Aryan Gangwar

Roll Number: 2410303583


Course: BCS554 - HTML and CSS Development Lab

University: Invertis University, Bareilly (B.Tech CSE)

Aim:

To create a bare remote repository, push the commits of the html-lab repository to it and clone it into a new folder.

Theory:

1. A remote is a copy of a repository stored somewhere else, such as another folder, GitHub or a server.
2. A bare repository (git init --bare) has no working files, only the history. It is used as a central shared repository.
3. git remote add origin followed by a path or URL gives the remote a short name. origin is the usual name. git remote -v lists the remotes with their addresses.
4. git push origin main uploads the commits to the remote branch. The branch may be called main or master, so check it with git status first.
5. git clone copies a whole repository with its complete history and sets origin automatically.
6. After cloning, git log --oneline shows the same commits as the original repository.

Tasks done:

1. Task 1: Created a bare repository html-remote, added it as origin in html-lab and listed it with git remote -v.
2. Task 2: Pushed the main branch of html-lab to origin.
3. Task 3: Cloned html-remote into a new folder html-copy and viewed its history with git log --oneline.

Files in this folder:

1. index.html: the page with the work of this lab.
2. style.css: the stylesheet of the page.
3. images/screenshot.png: screenshot of the output.

How to run:

The commands are given in the screenshot. Run them in a terminal inside the folder git-practice.
