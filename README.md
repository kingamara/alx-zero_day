My first readme
root@eea9e6d5a322:/alx-zero_day/0x03-git# git branch
  master
* update_script
root@eea9e6d5a322:/alx-zero_day/0x03-git# git chechout master
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout
root@eea9e6d5a322:/alx-zero_day/0x03-git# git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.
root@eea9e6d5a322:/alx-zero_day/0x03-git# ls
bash  c  js  README.md
root@eea9e6d5a322:/alx-zero_day/0x03-git# rm -r js
root@eea9e6d5a322:/alx-zero_day/0x03-git# git add .
root@eea9e6d5a322:/alx-zero_day/0x03-git# git commit -m 'Hot fix'
[master 998bf6c] Hot fix
 2 files changed, 0 insertions(+), 0 deletions(-)
 delete mode 100644 0x03-git/js/index.js
 delete mode 100644 0x03-git/js/main.js
root@eea9e6d5a322:/alx-zero_day/0x03-git# git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 2 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/kingamara/alx-zero_day.git
   cbecf45..998bf6c  master -> master
root@eea9e6d5a322:/alx-zero_day/0x03-git# ls
bash  c  README.md
root@eea9e6d5a322:/alx-zero_day/0x03-git# cat README.md
I love programming
root@eea9e6d5a322:/alx-zero_day/0x03-git# cd ..
root@eea9e6d5a322:/alx-zero_day# cat README.md
My first readme
root@eea9e6d5a322:/alx-zero_day# up_to_date
