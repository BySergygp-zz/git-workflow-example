# Prueba de Github Workflow v1.0 (DEV1.0)

1. First commit
2. Second commit

## Commits 
git add .
git commit -m "message commit"
git push

3. Create branch development

## Create Branch 

- to create only : 
git branch name_branch

- to create & change : 
git checkout -b name_branch

4. Create feature_branch development

## Create Feature Branch

git checkout -b feature_branch development

- to link local branch to remote branch 
git push --set-upstream origin feature_branch

5. Merges

## Do merge

git merge branch_to_merge

- if do you have problems
    Open file and modify
- Recommit
    git add file.xx
    git commit
    git push

6. Finish Branch

## Delete branch

- delete remote
git push origin :feature_branch

- delete local
git branch -d feature_branch

