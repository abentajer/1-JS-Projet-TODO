
# TODO Application with JS

Le but de ce mini-projet est la réalisation d’une application de gestion des tâches. En se basant sur le fichier index.html fournit, écrire le code JS permettant :
1. D’ajouter une tâche saisie dans le formulaire (add a new todo)
2. Pour chaque tâche ajoutée utiliser le template string fournit pour ajouter la nouvelle tâche
dans la liste :
```
`<li class="list-group-item d-flex justify-content-between align-items-center">
<span>${todo}</span>
<i class="far fa-trash-alt delete"></i> </li>`
```

3. Le formulaire en haut servira pour filtrer la liste des tâches en fonction de ce que l’utilisateur va entrer comme valeur. La liste doit être filtré au fur et à mesure que l’utilisateur saisie des caractères dans le formulaire de filtre

# Rendre le projet
Dans un premier cloner le dossier du projet avec la commande : 

```
git clone  https://github.com/abentajer/1-JS-Projet-TODO.git
```
Par la suite créez votre propre branche afin d'y mettre votre propre solution à l'aide de : 
```
git checkout -b todoapp/votre_nom_prenom
```
Une fois que vous avez terminé de coder votre solution, tapez : 
```
git add -A
```
Puis : 
```
git commit -m "Solution projet todo"
```
Vous pouvez adapter le message du commit.
Finalement 
```
git push --set-upstream origin todoapp/votre_nom_prenom
```
