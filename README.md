# 2023-01-17: DSCI 310 Git Demo
Intro Git Demo

Week 2 Lecture: January 17, 2023

- `git clone <URL>`: takes what's on github and does a one time download to your computer
- `git status`: tells the status of git
- `git add <FILE>`: add the <FILE>s to the staging area
- `git commit`: create the commit (aka snapshot)
    - `git commit -m "MESSAGE"`: create the git message directly in the command line
- `git push <where> <what>`: take local commits on `<what>`, and send it to `<where>`
- `git pull <where> <what>`: take remote commits on `<what>`, and pull from `<where>`
    - e.g., `git pull origin main`