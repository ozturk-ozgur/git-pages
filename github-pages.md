projeyi github ta yayinlamak icin (deployen)
nur frontend bei gitHub nur static 

git master dan main e gecmek icin önce git add ve commit yapilmali sonra main e gec.



git checkout -b gh-pages (new branch)
git push --set-upstream origin gh-pages










echo "# git-pages" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:ozturk-ozgur/git-pages.git
git push -u origin main


git remote add origin git@github.com:ozturk-ozgur/git-pages.git
git branch -M main
git push -u origin main

