//HTTPS SSH  https://github.com/tamak-io/tamak-io.git

//Create new repository in commandline

echo "# tamak-io" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M 'main'
git remote add origin https://github.com/tamak-io/tamak-io.git
git push -u origin 'main'

//push an existing repository from the command line

git remote add origin https://github.com/tamak-io/tamak-io.git
git branch -M 'main'
git push -u origin 'main'
