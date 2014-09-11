filebox
=======

Contains various files and notes.


#config
git config --global user.name "turgay"
git config --global user.email "turgaykivrak@gmail.com"
git remote set-url origin git@github.com:turgay/<repo-name>.git

#to fix commits
git filter-branch -f --env-filter "GIT_AUTHOR_NAME='turgay'; GIT_AUTHOR_EMAIL='turgaykivrak@gmail.com'; GIT_COMMITTER_NAME='turgay'; GIT_COMMITTER_EMAIL='turgaykivrak@gmail.com';" HEAD

