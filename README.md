mkdir -p ~/github-essentials
cd $_
echo "# github-essentials" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:<username>/<repository>.git
git push -u origin master
