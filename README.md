# How-To-Repo
A text file describing some of the more important how-tos when setting up my personal Github

## How to connect local files to Github repo
**Adapted from "Adding locally hosted code to GitHub" on docs.github.com"**

1. Create new repository on Github.com
2. Open Git Bash
3. Change current working directory to your local project file
4. Initialise local directory as Git Repo 
    - $ git init -b main
5. Add the files in your new local repository. This stages them for the first commit.
    - $ git add .
6. Commit the files
    - $ git commit -m "First commit"
7. Copy the https link and paste in the Gitbash command prompt
    - $ git remote add origin  <https remote url>
    - $ git remove -v #to verify the new remote URL
8. Push changes in local folder to Github.com
    - $ git push origin main
