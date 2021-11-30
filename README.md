# TEST
echo "# TEST" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:MITSU-GIT01/TEST.git
git push -u origin master