1.
2.
/Users/mac/.zshrc:65: bad pattern: /Users/mac/.oh-my-zsh/oh-my-zsh.sh[[
mac@Amanyis ~ % pwd
/Users/mac
mac@Amanyis ~ % cd Downloads/
mac@Amanyis Downloads % mkdir gitrep && cd gitrep
mac@Amanyis gitrep % git init
Initialized empty Git repository in /Users/mac/Downloads/gitrep/.git/
mac@Amanyis gitrep % git clone https://github.com/DanielAmanyi/actions-1.git
Cloning into 'actions-1'...
remote: Enumerating objects: 61, done.
remote: Counting objects: 100% (61/61), done.
remote: Compressing objects: 100% (41/41), done.
remote: Total 61 (delta 6), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (61/61), 18.39 KiB | 64.00 KiB/s, done.
Resolving deltas: 100% (6/6), done.
mac@Amanyis gitrep % ls
actions-1
mac@Amanyis gitrep % cd actions-1/
mac@Amanyis actions-1 % ls
