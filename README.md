# The Gym Git && Github exercise

## Welcome! 👋

This is a solution to the Gym Traning. The Gym challenge help us to improve our coding skills by building realistic projects.
In this exercise, we will use git and Github command.

## Content

- [the-gym-git-github-exercise](#the-gym-git-github-exercice)
- [Welcome! 👋](#welcome)
- [The challenge](#the-challenge)
- [My process](#my-process)
- [Author](#author)
- [Connect Us:](#connect-us)

### The challenge

Users should be able to:

- Before starting these exercises, please create one github repository that you will use to paste your terminal history into after each exercise,
- Call it “Gym Git Exercise Solutions” or similar. Make sure it has a readme file,
- The process for solving the exercises is as follows:
- First try to solve the exercise on your own (without peaking into the solution!). You are allowed google git commands, if you don’t remember them or if you need to read up on them.
- Next watch the solution video for the exercise you just completed.
- If you feel you may have done some things wrong, do the exercise again. But while you are doing it again, don’t peak at the video. Do it from memory.
- Now you can watch the video again (possibly at double speed, or skipping to the bits that you have doubts about) to double check if you did everything right this time.
- If you feel you still had mistakes, do the exercise again. Again, do it from memory, don’t peak at the video. And then afterwards check the video again etc. etc.
- Once you are confident that you have got the right solution, copy the terminal commands you used in your last try and past them in the readme file of the “Gym Git Exercise Solutions” repository you have created. All Solutions to all exercises should be pasted into the readme file of this repository. Even when an exercise requires you to create a github repository for the purposes of solving the exercise, nevertheless always use the “Gym Git Exercise Solutions” readme file to paste your terminal history into.

## My process

# Bundle 1

## Exercise 1

```bash

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice
$ git init
Initialized empty Git repository in C:/Users/TheGym/Documents/TheGym-Tasks/Git-Exercice/.git/

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (master)
$ git branch -M main

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ touch README.md

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ git add README.md

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ git commit -m "feat: initialize readme of gym git exercise"
[main (root-commit) 095f6ea] feat: initialize readme of gym git exercise
 1 file changed, 50 insertions(+)
 create mode 100644 README.md

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ git remote add origin https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions.git

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 1.42 KiB | 728.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions.git
 * [new branch]      main -> main

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ git branch dev

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (main)
$ git checkout dev
Switched to branch 'dev'

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions/pull/new/dev
remote:
To https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions.git
 * [new branch]      dev -> dev

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$ git branch test

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$ git checkout test
Switched to branch 'test'

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions/pull/new/test
remote:
To https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions.git
 * [new branch]      test -> test

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (test)
$ git checkout dev
Switched to branch 'dev'

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$ git branch -d test
Deleted branch test (was 095f6ea).

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$ git push origin dev
Everything up-to-date

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$ git push origin --delete test
To https://github.com/IbrahimBagalwa/the-gym-git-exercise-solutions.git
 - [deleted]         test

TheGym@DESKTOP-8H0OS24 MINGW64 ~/Documents/TheGym-Tasks/Git-Exercice (dev)
$
```

## Author

- Twitter - [@ibrahim_Bagalwa](https://twitter.com/ibrahim_Bagalwa)
- LinkedIn - [ibrahim-bagalwa](https://www.linkedin.com/in/IbrahimBagalwa)

## Connect Us:

<p align="left">

[![Follow on Twitter](https://img.shields.io/badge/--twitter?label=Twitter&logo=Twitter&style=social)](https://twitter.com/ibrahim_Bagalwa) [![Connect on LinkedIn](https://img.shields.io/badge/--linkedin?label=LinkedIn&logo=LinkedIn&style=social)](https://www.linkedin.com/in/IbrahimBagalwa) [![Send me email](https://img.shields.io/badge/--gmail?label=Gmail&logo=Gmail&style=social)](mailto:bagmurhulaibrahim@gmail.com) [![Send me whatsapp message ](https://img.shields.io/badge/--whatsapp?label=Whatsapp&logo=Whatsapp&style=social)](+243971004914)

---

</p>
