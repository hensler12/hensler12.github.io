CREATING GITHUB PAGES REPOSITORY

create directory <mkdir>

initialize directory as a local repository <git init>

add index.html file to repo

send index.html to git staging area <git add .>

check status of staging area <git status>

commit index.html to local repo <git commit -m “what did you just do.”>

create GitHub Pages remote repo (create repo in GitHub named username.github.io)

link remote and local repos <git remote add origin (copy and paste github link)>

push local repo to remote <git push -u origin master> (only need to use “-u” the first time)

UPDATING PAGES

make edits to index.html

send updates to git staging area <git add .>

check status of staging area <git status>

commit edits to local repo <git commit -m “what did you do.”>

push edits to remote repo <git push origin master>
