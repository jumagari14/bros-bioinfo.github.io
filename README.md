# Bienvenue sur Bros-Bionfo

Ici on va publier les cours du M1 de Bordeaux. Enjoy !

------
## Les Cours

### Algorithmique, Programmation et Utilisation des Systèmes Informatiques

###### /cours/Algo_sys_prog/

- [Fichier du cours: APU-USI](https://bros-bioinfo.github.io/cours/Algo_sys_prog/APU-USI)
- [Fichier du cours: APU-PROG (à créer)](https://bros-bioinfo.github.io/cours/Algo_sys_prog/APU-PROG)




### Omics and Bioinformatics

###### /cours/Omics_and_Bioinformatics/

- [Fichier du cours: OBI](https://bros-bioinfo.github.io/cours/Omics_and_Bioinformatics/OBI)




### Traitements des données environnementales

###### /cours/Stats/


------
## Partie Technique

##### Les commandes git:

**Pour commencer**, il faut:
- installer git;
- se faire un compte github (et se faire ajouter en contributeur)
- se placer dans le répertoire où on veut mettre le dossier avec cd
- cloner le dossier github localement:
  ```shell
  git clone https://github.com/bros-bioinfo/bros-bioinfo.github.io.git
  ```



**Avant d'éditer le fichier**: il faut se mettre dans la racine du projet et:
```shell
git pull
```
(Cela permet de récupérer les modifications éventuels réalisées par d'autres depuis internet).


**Après l'édition du fichier**:
```shell
git add --all ; git commit -m "updates des cours" ; git push --all
```
S'il y a des problèmes, faites chaques commandes séparément.
- git add: permet d'ajouter les fichiers modifiés à la liste d'envoi;
- git commit: message de changement;
- git push: upload


**Convention pour nommer les fichiers (et en déduire l'url):**

Exemple:
- Fichier Markdown du TD de stat n°1: stats/td1/td1.md
