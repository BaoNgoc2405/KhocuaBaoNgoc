# KhocuaBaoNgoc
git config --global user.name BaoNgoc2405
git config --global user.email baongocc24052006@gmail.com

mkdir hello
cd hello
cp ~/hello.sh

git init
git add hello.sh
git commit -m "Them file hello.sh vao github"
git remote add origin https://github.com/BaoNgoc2405/KhocuaBaoNgoc.git
git push -u origin master
