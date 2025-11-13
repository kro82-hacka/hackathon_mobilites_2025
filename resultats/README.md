## Comment déposer vos résultats, code et présentations ?

[Github commands cheat sheet](https://git-scm.com/cheat-sheet)

- Cloner le repository Hackathon Mobilités 2025 avec la commande suivante :

``` shell
git clone https://github.com/hackathons-mobilites/hackathon_mobilites_2025.git
```

- Créer une nouvelle branche avec le nom de votre équipe :

``` shell
git checkout equipe-2
```

- Se déplacer dans le sous-dossier /resultats/repository :

``` shell
cd resultats/repository
```

- Développer votre solution et ajouter les tous les fichiers nécessaires
- Ajouter votre présentation dans le dossier resultats/presentation
- Pour déposer la version finale de votre projet ou bien simplement sauvegarder une version de votre code intermédiaire :

``` shell
git add .
git commit -m "{votre message de commit}"
git push
```

## Les pépites du Hackathon IA Mobilités 2024

Retrouvez aussi les meilleurs projets de l'année dernière en suivant ce [lien](https://github.com/hackathons-mobilites/hackathon_ia_mobilites_2024/blob/main/resultats/Readme.md).


## Note de dévélopment

> Note pour l'équipe

Principe d'opération: On centralise sur un seul repo (master) sur le quel on va chacun faire un fork et merge depuis:

1. Aller sur le repo:

```shell
git clone -b equipe-2 https://github.com/aladinoster/hackathon_mobilites_2025.git
```

2. Fork le repo

3. Cloner votre repo

```shell
git clone -b equipe-2 https://github.com/<user>/hackathon_mobilites_2025.git
```

4. Commit toutes les experiences/ explorations sur notebooks. On reserve le prototype finale sur resultats

5. Integrer le code via un [Pull request](https://github.com/aladinoster/hackathon_mobilites_2025/compare)