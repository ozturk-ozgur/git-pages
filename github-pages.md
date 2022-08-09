projeyi github ta yayinlamak icin (deployen)
nur frontend bei gitHub nur static 

git master dan main e gecmek icin önce git add ve commit yapilmali sonra main e gec.

git branch -D gh-pages -- silmek icin

branch lari yeni vs code icinde acinca farkli görüyoruz farkli repo oldugu icin

linki kopyala about kismina yapistir ya da readme icerisine 


# NPM

npm init -y
package.json olusturuldu
hangi library bizde kurulu oldugunu gösteririr
projenin tarifi gibi

npm install en basta yapilmasi lazim, json a bakar orda kayitli olanlari install yapar

npm i gh-pages --save-dev   -> node_modules kuruldu

"scripts": {
    "deploy": "gh-pages -d ./"

npm run deploy









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