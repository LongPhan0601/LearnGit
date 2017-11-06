# GIT WORKFLOW
1. Initial (clone == copy)
2. Fetch & merge (pull)
3. Branching, tagging
4. Modify (implement features, fix bugs)
5. Commit to local repository
6. Push changes on origin

# USEFUL REFERENCES
1. https://git-scm.com/book/vi/v1
2. https://backlog.com/git-tutorial/vn/intro/intro1_1.html
3. http://nvie.com/posts/a-successful-git-branching-model/

# BASIC GIT COMMANDS
- Creating a repository
``git init .``

- Cloning an existing repository
``git clone <URL>``

- Add new file
``git add README.txt``

- Remove file
``git rm README.txt``

- Commit changes
``git commit -am "Some comments"``

- Show log
``git log``

- Show commit
``git show``

- Show difference
``git diff``

- Undo changes
``git checkout -- README.txt``

- Revert to specific commit
``git revert <commit hash number>``

- Create new branch
``git branch <branch name>``

- Create & checkout new branch
``git checkout -b <branch name>``

- Switch to another branch
``git checkout <branch name>``

- Delete branch
``git branch -d <branch name>``

- Show all branches
``git branch -a``

- Create new Annotated Tag
``git tag -a <tag name>``

- Show all tags
``git tag``

- Delete a tag
``git tag -d <tag name>``

- Push changes to remote
``git push origin <banch name>``

- Apply new change & merge
``git pull``

- Get new update only (not merge)
``git fetch``

- Merge changes
``git merge origin master``
