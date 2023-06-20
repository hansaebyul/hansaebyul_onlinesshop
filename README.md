git init
git add -A
git commit -m "onlineshop"

git remote add origin https://github.com/hansaebyul/onlineshop.git
git push -u origin master

git remote -v
#origin 삭제 명령어
git remote remove origin
#origin 다시 등록
git remote add origin https://github.com/hansaebyul/onlineshop.git
