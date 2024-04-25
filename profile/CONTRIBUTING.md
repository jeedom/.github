# Github contribution :

Merci beaucoup pour votre volonté de contribuer à ce projet! Veuillez suivre ces
directives pour garantir une collaboration harmonieuse avec l’ensemble de la
communauté.

## Corrections de bogues et fautes de frappe

Pour les corrections de bogues et de fautes de frappe, veuillez suivre ces étapes :

1. Faites vos modifications directement sur la branche beta.
2. Effectuez un commit en suivant la spécification Conventional Commits en
utilisant le type "fix" et en incluant une description claire du correctif, par
exemple : "fix: résoudre le plantage dû à une méthode obsolète". Ou un PR
depuis votre fork.

## Fonctionnalités / Features

Pour l'ajout de nouvelles fonctionnalités, veuillez suivre ces étapes :

1. Créez une issue décrivant la fonctionnalité que vous souhaitez ajouter.
2. Utilisez le bouton "Créer une branche" directement inclus dans l'issue pour
créer une nouvelle branche basée sur la branche beta. (Si vous n'avez pas les
droits pour créer une branche sur ce dépôt, créez une branche localement sur
votre fork du dépôt. Et faire un lien dans l’issue).
3. Implémentez la fonctionnalité.
4. Effectuez les commits en suivant la spécification Conventional Commits en
utilisant le type "feat" et en incluant une description claire de la nouvelle
fonctionnalité, par exemple : "feat: ajouter une nouvelle méthode duplicate
a la class eqLogic.
5. Si votre fonctionnalité inclut des changements dans la documentation, ajoutez
un commit supplémentaire avec le type "docs" et une description appropriée,
par exemple : "docs: mettre à jour la documentation pour inclure la nouvelle
méthode".
6. Si votre fonctionnalité inclut des changements qui affectent les utilisateurs et
méritent d'être mentionnés dans le changelog, ajoutez un commit
supplémentaire avec le type "chore" et une description appropriée, par
exemple : "chore: mettre à jour le changelog pour la version x.x.x".
7. Soumettez une pull request vers la branche beta.
8. Attendez la validation.
   
## Refactor, Docs, Test, Chore

Pour les commits de type "refactor", "docs", "test" et "chore", veuillez suivre les
mêmes étapes que pour les fonctionnalités, en remplaçant le type de commit par
celui approprié et en fournissant une description adaptée à la nature du
changement, comme décrit ci-dessous :

* refactor: refactorisation du code, par exemple : ```refactor: migrer des
composants de classe vers les hooks```.
* docs: modifications dans la documentation, par exemple : ```docs: ajouter un
exemple d'utilisation pour le module```.
* test: ajouter ou mettre à jour des tests, par exemple : ```test: ajouter des
tests d'intégration utilisant detox```.
* chore: changements dans le changelog, par exemple : ```chore: changement
du changelog```.
