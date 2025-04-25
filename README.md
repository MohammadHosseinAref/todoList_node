1.Install git scm
	check by ( git -v )
2.Create repository

3. open Git Bash

4. git add .

5.git commit -m "  "

6. git push

7. git status

8- git log - git log -1

9. git diff

10. git checkout .... / git checkout master

11. for reName -> add new file - remove old file - commit - push

12. remove change from working directory
    git checkout -- fileName
    ___________
    remove change after add file
    git reset HEAD fileName

13. git reset --hard logId

14. create folder: mkdir folderName

15. .gitignore
    folder : forderName/
    file : fileName.--- or *.--- soft !namefile.--- exampl *.cmd !status.cmd
     https://www.toptal.com/developers/gitignore
     https://github.com/github/gitignore

16. git log --since=" date or time"
    git log --until=" date or time"
    git log --oneline
    git --author=""
    git --grap="" (search in commite)
    git log -p logId
    git log --oneline
______
17. create branch:
    Create: git branch  name
    list of branch: git branch
    change branch: git checkout branch name
    delete branck: git branch -D branch name
    create and swich branch: git checkout -b branch name
    rename branch: git branch -m new name
    show diff in branch: git diff branch1..branch2
________
18. merge:
    fast-forward: all commit to branch
    git merge branch name
    no fast-forward: all commit change one commit
    git merge branch name --no--ff --message=" ... "
    git log --oneline --graph --decorate
________
19. stach:
    git stach save "..."
    git stash list
    git stach show id stash
    OUT OF STAGE: git stash pop id stash (delete stash when out of stash)
    OUT OF STAGE: git stash apply id stash 
    Delete stage: git stash drop id stage
    Delete All stage: git stash clear
__________
20. remote to server:
    1.Create repository
    2. git clone adress
    3. git commit and push
    git branch -r list branch in server    
    git branch list branch in local
    git fatch
    git merge origin/master (merge server to current branch in local )
    git pull (fach and merch)
___________
21. git remote (list git)
    git remote add name ...(link git)
    git remote show remot name

22. git push remoteName branchName
    git remote remove remoteName
