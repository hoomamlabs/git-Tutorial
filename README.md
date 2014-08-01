git-Tutorial
============

##git config location 
```sh
$HOME/.gitconfig
```
or 
```sh
$ git config --global user.name "Nadia Afakrouch"
$ git config --global user.email nadia.afa@gmail.com
```
=============================
###Basic -Repository
```sh
mkdir nom_depot
cd nom_depot
git init
```

or 

```sh
git clone git://<repository>
```
=============
##Repo Status
```sh
git diff
git diff <commit1> <commit2>
git status
git log
```
=========
##File management

```sh
git add <nom_fichier_ou_dossier>
git add *
git rm <nom_fichier>
git mv <nom_fichier> <nouvelle_destination>
```
================
##Commits management

```sh
git pull
git commit <fichier1> <fichier2>
git commit -a
```
### Push master origine
/*

```sh
git remote rm origin  #Removes old origin
git remote add origin https://username@bitbucket.org/your.new.repo  #Adds new origin pointing to BitBucket
git push -u origin  #Pushes commits to new repo => first time  to upstream (match) local master with remote master
```
*/
```sh
git push origin master
```
=========

almaraji3

- [http://doc.ubuntu-fr.org/git](http://doc.ubuntu-fr.org/git)
- [http://andersonleeb.com/blog/changing-git-remote-origin](http://andersonleeb.com/blog/changing-git-remote-origin)
- [https://www.atlassian.com/fr/git/tutorial/git-basics](https://www.atlassian.com/fr/git/tutorial/git-basics)
- [https://try.github.io/levels/1/challenges/1](https://try.github.io/levels/1/challenges/1)
- [http://git-scm.com/docs/gittutorial](http://git-scm.com/docs/gittutorial)




