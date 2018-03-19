# Prise en main d'outils pour le développement



### 1. Mise en place d’un projet Maven

Rendez-vous **[ici](https://github.com/iblasquez/Back2Basics_Developpement/blob/master/CreerProjetMavenEclipse.md)** dans le dépôt [Back2Basics_Developpement](https://github.com/iblasquez/Back2Basics_Developpement).  
Dans l'`artifactId`, au lieu d'appeler votre projet `MonApplication`, vous l'appelerez **`refactoringexemple`**.


### 2. Mise en place du projet Maven spaceinvaders

En reprenant ce que vous avez fait précédemment, créez un nouveau projet Maven nommé **`spaceinvaders`** avec un `pom.xml` correctement configuré et updaté (version Java et JUnit).  
Supprimez les fichiers créés par défaut `App.java` et `AppTest.java` pour disposer d’un projet vide que nous utiliserons un peu plus tard dans le cadre du mini-projet.



### 3. Prise en main d'[ObjectAid UMLExplorer](http://www.objectaid.com/)

Revenir sur le projet créé à l'exercice 1 (normalement nommé `refactoringexemple`).  

Rendez-vous **[ici](https://github.com/iblasquez/tuto_ModelisationUML/tree/master/ObjectAid)** dans le dépôt [tuto_ModelisationUML](https://github.com/iblasquez/tuto_ModelisationUML). 

Votre projet étant déjà créé, il ne vous reste plus qu'à installer le plug-in [ObjectAid UMLExplorer](http://www.objectaid.com/), récupérer les 3 classes et continuer le tutoriel...  
Vous ne devez réaliser pour ce TP que la partie du tutoriel concernant le diagramme de classes. 
(pas le diagramme de séquence)


### 4. Prise en main d'[EclEmma](http://www.eclemma.org) (pour connaître la couverture de code)

Rester sur le projet `refactoringexemple` avec ses 3 classes : `Customer`, `Movie` et `Rental`.  

Rendez-vous **[ici](https://github.com/iblasquez/Refactoring_PremierExempleFowler/blob/master/refactoring_Step0_miseEnPlaceTests.md)** dans le dépôt [Refactoring_PremierExempleFowler](https://github.com/iblasquez/Refactoring_PremierExempleFowler).    
 
Ce qui nous intéresse dans ce tutoriel est la mise en place des tests et la prise en main de l'outil Java de couverture du code par les tests ([EclEmma](http://www.eclemma.org/)).  
Au passage, n'hésitez pas à installer [Infinitest](https://infinitest.github.io/), très pratique pour lancer les tests de manière continue :simple_smile:  
Pour le cadre de ce TP, ne faites que la page sur laquelle vous vous trouvez c'est-à-dire : Pas de refactoring sans test !, puis passez à l'exercice suivant...


### 5. Prise en main de [SonarLint](http://www.sonarlint.org/) (une aide à la qualité de code)

Rendez-vous **[ici](https://github.com/iblasquez/tutoriel_SonarQube/blob/master/Analyse_SonarLintEclipse.md)** dans le dépôt [Back2Basics_Developpement](https://github.com/iblasquez/Back2Basics_Developpement)  


### 6. Génération d'un nuage de mots du code source (pour un focus sur l'intention du code)

A l'aide de **Source Code Word Cloud Generator** disponible [ici](https://sourcecodecloud.codeplex.com) et du contenu du fichier `JavaBlacklist.txt` disponible [là]( https://github.com/iblasquez/enseignement-iut-m2104/tree/master/ressources/JavaBlacklist.txt) dans ressources du dépôt [enseignement-iut-m2104](https://github.com/iblasquez/enseignement-iut-m2104), vous pouvez facilement générer le nuage de mots du code source de votre projet.  

Pour cela, une fois l'application du [Source Code Word Cloud Generator](https://sourcecodecloud.codeplex.com) lancée, placez-vous dans l'explorateur sur le répertoire de votre workspace portant le nom du projet à analyser, dans votre cas ce devrait être **`refactoringexemple`** pour commencer et cliquez sur le bouton **`Generate`**.
Vous venez de générer le nuage de mots relatif au projet `refactoringexemple`.

Créez un projet **`refactoringtennis`** avec les fichier `TennisGame.java`, `TennisGame3.java` et `TennisTest.java` récupérés sur [https://github.com/emilybache/Tennis-Refactoring-Kata](https://github.com/emilybache/Tennis-Refactoring-Kata).  
Générez le nuage de mots de ce projet.   
Quid du métier et de l’intention du code dans ce projet ?  


Remarque : Une solution alternative à **Source Code WorldCloud Generator** est le projet Kumo qui est disponible sur github à l'adresse suivante : [https://github.com/kennycason/kumo](https://github.com/kennycason/kumo). C'est une API Java qui permet de créer et personnaliser son propre World Cloud. Pour savoir comment l'utiliser, consulter les nombreux exemples donnés dans le README de ce dépôt.




## Commentaires, remarques et suggestions
Pour les discussions, c'est par là : https://github.com/iblasquez/enseignement-iut-m2104/issues  
Pour les propositions de contenu, de modification par ici : https://github.com/iblasquez/enseignement-iut-m2104/pulls

Et bien sûr, n'hésitez pas à personnaliser vos messages avec des [emojis](http://www.webpagefx.com/tools/emoji-cheat-sheet/) :smile:



## Licence


Tous les documents de ce dépôt sont placés sous licence CC BY-NC-SA :  [Creative Commons
Attribution - Pas d'Utilisation Commerciale - Partage dans les Mêmes Conditions](https://creativecommons.org/licenses/by-nc-sa/4.0/)

<img src="https://licensebuttons.net/l/by-nc-sa/3.0/88x31.png" width="100">

En savoir plus sur [les licences Creative Commons](https://creativecommons.org/licenses/?lang=fr-FR) ...

Toutefois, toute personne enseignant au département Informatique de l'IUT du Limousin doit demander une autorisation préalable si elle souhaite utiliser ce document.





