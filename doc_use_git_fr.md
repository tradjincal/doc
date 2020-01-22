# Propulser une contribution avec git

**Index**  
 - [Création d'un compte sur github.com](#CreationCompteGithub)  
 - [Forker la documentation de YunoHost dans votre dépôt](#ForkerDocumentationYunoHost)  
 - [Modifier les fichiers et ajouter vos contributions](#ModifAjoutContrib)  
 - [Envoyer vos contributions avec une Pull Request](#EnvoyerPR)  
 - [Suivre votre contribution et prendre en compte les retours des contributeurs·trices](#SuivreContributions)  
 - [Faire remonter des erreurs et des souhaits en créant une issue](#RemonterIssues)  
 - [Corriger et inspecter les contributions](#ReviewContrib)
 - [Aller plus loin avec git et contribuer sur son poste de travail](#PlusLoinGitOrdi)  
    - [Quelques ressources sur le web](#LiensWeb)  

Il est bien sûr possible de contribuer directement sur la documentation de Yunohost, mais ce n'est pas la manière la plus pratique de le faire tant pour le/la contributeur·trice que pour la personne qui va injecter votre contribution dans la documentation. Un tutoriel pour comprendre et créer une contribution à la documentation de Yunohost en utilisant l'outil [git (en)](https://git-scm.com/) et [github.com](http://github.com/) qui est un service de forge git internet qui héberge et stocke le code source de Yunohost et sa documentation.

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts" src="https://framatube.org/videos/embed/9db9f3f1-9b54-44ed-9e91-461d262d2205" frameborder="0" allowfullscreen></iframe>


## Création d'un compte sur github.com <a name="CreationCompteGithub"></a>

Pour pouvoir envoyer vos contributions via GitHub, vous devez avoir un compte sur github, pour créer le compte vous aurez besoin d'une adresse email valide à laquelle vous avez accès. Github est un outil puissant qui propose de nombreuses fonctionnalités, l'interface peut être un peu effrayant au début.  
Vous n'êtes pas obligé·ée de donner vos noms et prénoms, vous pouvez utiliser un pseudonyme (lors de l'inscription `Username`).  

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts" src="https://tube.metadocs.cc/videos/embed/7288bf53-6942-4af1-a713-61e3b37ec11b" frameborder="0" allowfullscreen></iframe>


## Forker le dépot de la documentation de YunoHost dans dépot <a name="ForkerDocumentationYunoHost"></a>

Forker le code source permet de créer une nouvelle branche de développement d'un code source de logiciel ou dans le cas présent, le code source de la documentation. En créant une nouvelle branche, cela vous permet de modifier le code et d'ajouter vos contributions sans altérer le code de la branche `master` qui est le rendu public de la documentation. Ce qui vous permet de ne pas devoir tout marquer mais le faire en plusieurs étapes. (Notamment pour les contributions demandant plus de temps de travail).

Forker un projet sur github est extrêmement simple, il suffit ce cliquer sur le bouton Fork, cela créera un nouveau dépôt sur votre espace de github.
![Capture d'écran bouton fork github](/images/dug_fork.png)  
Dans le titre du nouveau dépôt, vous verrez de quelle provenance vient le dépôt, dans le cas présent `YunoHost/doc`  
![Capture d'écran titre et sous-titre du dépot](/images/dug_fork_source.png)

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts" src="https://tube.metadocs.cc/videos/embed/20730c3e-a918-41fc-b843-4378a85b0233" frameborder="0" allowfullscreen></iframe>


> **Point de vigilance !**  
> Si vous forkez le dépôt d'un autre contributeur que yunohost, vous aurez les mêmes fichiers. Sauf que quand vous enverrez vos modifications, elles seront envoyées au contributeur et non au dépôt yunohost. L'avantage est que ça vous permet de développer une autre branche créee par le contributeur et ainsi travailler avec une autre personne à une amélioration avant proposition au dépôt principal.  
> Il n'est pas possible de forker le forke et le dépôt d'origine au même moment dans vos dépôts.

## Modifier et ajouter votre contribution <a name="ModifAjoutContrib"></a>

Une fois le dépôt forker (copié), il vous faudra créer une nouvelle branche de développement au sein de votre dépôt. C'est à travers cette branche que vous allez modifier les fichiers et ainsi proposer des améliorations de la documentation. Le fait que ce soit une nouvelle branche vous permettra par la suite de faire une Pull Request, c'est à dire une demande d'ajout de vos contributions au sein de la branche `master` qui est la branche principale.

<iframe width="560" height="315" sandbox="allow-same-origin allow-scripts" src="https://tube.metadocs.cc/videos/embed/d48f2d7e-c501-472d-b5da-871ab0d7ea0c" frameborder="0" allowfullscreen></iframe>

## Envoyer votre contribution par une Pull Request <a name="EnvoyerPR"></a>

## Suivre votre contribution et prendre en compte les retours des contributeurs·trices <a name="SuivreContributions"></a>

Lorsque vous avez déjà fait une PR (Pull Request), les modifications de votre branche de développement sur le dépôt git se rajouteront automatiquement à la PR. Cela ne nécessite aucune action supplémentaire. Vous pouvez aussi intégrer les propositions de modifications de contributeurs, qui lorsqu'ils/elles auditeront le code, peuvent trouver des erreurs ou de nouvelles formulations plus adaptées.  

## Faire remonter des erreurs et des souhaits par des issues <a name="RemonterIssues"></a>

## Corriger et inspecter les contributions <a name"ReviewContrib"></a>

## Aller plus loin avec git et travailler sur son poste de travail <a name="PlusLoinGitOrdi"></a>

Utiliser la puissance de git et ainsi travailler sur son son ordinateur personnel, permet entre autres de ne pas avoir à créer de `commit` à chaque enregistrement intermediaire des pages de documentations modifiées. Cela permet aussi d'utiliser des outils et logiciels qui permettent une distinction plus facile des codes utilisés dans une page de documentation.

### Quelques ressources ailleurs sur le net pour aller plus loin <a name="LiensWeb"></a>

 - [Gérer son code avec git et github - openclassrooms.com](https://openclassrooms.com/fr/courses/2342361-gerez-votre-code-avec-git-et-github)
 - [Interface utilisateurs·trices de git - git-scm.com](https://git-scm.com/download/gui/linux)