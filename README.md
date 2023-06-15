# git 사용법

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ cd ..

grace@quellegnade MINGW64 /c/dev/frontend/frontend4 (master)
$ cd c_class

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git init
Initialized empty Git repository in C:/dev/frontend/frontend4/c_class/.git/

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git config --global user.name "eunsaem-git"

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git config --global user.email "eunsaem9603@gmail.com"

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git add README.md

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git commit -m "시리얼번호 생성"
[master (root-commit) f8c62a1] 시리얼번호 생성
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git branch -M master

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git remote add origin https://github.com/eunsaem-git/c_class.git

grace@quellegnade MINGW64 /c/dev/frontend/frontend4/c_class (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 253 bytes | 253.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/eunsaem-git/c_class.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.