Ejercicio 1
git config --global user.name "Sergio Moreno Sanchez"
git config --global user.email "sergio.m20@myyahoo.com"
git config --global color.ui auto.
git config --list

Ejercicio 2
mkdir libro
cd libro
git in it


Ejercicio 3
  
  git satatus
  
  echo capitulo 1: introduccion a git > indice.txt
  echo capitulo 2: flujo de trabajo basico >> indice.txt
  echo capitulo 3: repositorios remotos >> indice.txt
  
  git status
  
  git add indice.txt
  
  git status

Ejercicio 4
 git conmit -m "Añadido indice del libro"
 git push

 
 Ejercicio 5

git rm indice.txt -f
echo capitulo 1:  introduccion a git > indice.txt
  echo capitulo 2: flujo de trabajo basico >> indice.txt
  echo capitulo 3: gestion de rama >> indice.txt
  echo capitulo 4: repositorios remotos >> indice.txt
git add indice.txt

git diff

git conmit -m "Añadido capitulo 3 sobre gestion de ramas"
git push


Ejercicio 6

git show

git conmit --amend -m "Añadido capitulo 2 sobre gestion de rama"

git status
