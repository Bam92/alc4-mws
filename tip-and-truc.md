## Merge 2 git repos
If you want to merge project-a into project-b:

cd path/to/project-b
git remote add project-a path/to/project-a
git fetch project-a --tags
git merge --allow-unrelated-histories project-a/master # or whichever branch you want to merge
git remote remove project-a

Source: https://stackoverflow.com/questions/1425892/how-do-you-merge-two-git-repositories

## https://beta.frontendmentor.io/challenges
