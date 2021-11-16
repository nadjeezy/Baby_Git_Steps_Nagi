# Baby_Git_Steps

## Présentation du projet

### Ressources

- [Learngitbranching](https://learngitbranching.js.org/?locale=fr_FR)
- [git-scm](https://git-scm.com/)

### Sous-titre : Objectif

1. apprendre Git
2. apprendre MArkdown

## Présentation du codeur

### Présentation

- Bonjour, Je suis développeur !!

| Entreprise | poste | année |
| :---------------: |:---------------:| :-----:|
| Acteam-it  | Stage dev | 2021 |

##Témoignage

Best DevOps I've ever seen ! I wish I be like they.

## Changelog

### first commit
Premier commit
```git
git commit -m "initial commit"
```

---------------
### Code compteur d'action
Changement du code de __script__.py
Vérification des différences
```git
git diff __script__.py
```
Commit
```git
git commit -m "Code compteur d'action"
```

----------------
### Fix
Renommage du commit
```git
git commit --amend -m "fix"
```

----------------
### poneys.txt
Création du fichier poneys.txt
Commit
```git
git commit -m "poneys.txt"
```
----------------
### unicornmode
Ajout d'une ligne dans __script__.py
```git
git commit -m "unicornmode"
```

---
### Merge
Fusion de dev avec master
```git
git merge dev
```

---
### maPremiereFusion
Passage de la valeur à 1.
```git
git commit -m "maPremiereFusion"
```
---
### v1.0.0
création d'un tag
```git
git tag v1.0.0
```
---
### liaison github
Liaison du dossier local au dossier git
```git
git remote add origin https://github.com/nadjeezy/Baby_Git_Steps_Nagi
git push origin master 
```
---
### clone repo autre
```git
git clone https://github.com/.../... 
```

### temoignage chez romy
Creation d'une branche sur le repository de l'autre
Push de ma branche vers origin
```git
git checkout -b devnagi
git commit -am "..."
git push origin devnagi 
```
Puis création d'une pull request