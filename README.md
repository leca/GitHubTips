# GitHubTips

echo "# GitHubTips" >> README.md
git init



## to include a readme.md 
git add README.md

## to include deletions:
git add --all

git commit -m "first commit"

git remote add origin https://github.com/leca/GitHubTips.git

git push -u origin master

## or push an existing repository from the command line

git remote add origin https://github.com/leca/GitHubTips.git

git push -u origin master

## to clone a repo (after fork!)

git clone repo_url

## to clone with a new directory name
git clone repo_url new_dir
