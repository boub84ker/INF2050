# Maven vs Ant+Ivy

## Identification

- Cours      : Outils et pratiques de développement logiciel
- Sigle      : `INF2050`
- Session    : `Hiver 2020`
- Groupe     : `30`
- Enseignant : `François-Xavier Guillemette`
- Auteur     : `Zineb Ben Larabi` (`BENZ21519706`)
- Auteur     : `Andrei Bucsa ` (`BUCA15038505 `)
- Auteur     : `Ahmed Lakkati ` (`LAKA09038700 `)
- Auteur     : `Boubker Kabbaj` (`KABB23038404 `)





## MAVEN



### Description

Maven est un système de build fait exclusivement par les langages de la JVM et les fichiers de configurations de Maven sont écrits en XML. C'est un système qui permet de décrire le build d'un projet JAVA. Au niveau Maven, tout le cycle de build soit la compilation, le téléchargement de dépendances, exécution des tests, productions de la distribution, etc. est déjà établi. Le programme n'a qu'à définir les dépendances et l'identifiant. Maven est un framework de build plutôt qu'une librairie qui décrie un build.

Il est souvent utilisé pour automatiser quelques tâches telles que les tests unitaires et déploiements des applications qui composent le projet. Il permet de gérer des dépendances et des documentations.








## ANT+IVY



### Description


ANT a comme principal objectif de régler la portabilité complète en JAVA. Il fournit un panel de fonctionnalités qui aura le même comportement sur tous les systèmes si l'on souhaite déplié une application sur plusieurs plates-formes. Alors qu'avec MAKE, pour effectuer une tâche les actions sont spécifiées comme étant des commandes SHELL qui sont propres à l'exécution.

IVY est alors une librairie complémentaire qui permet de déclarer et de télécharger des modules dépendants.

ANT+IVY utilise un langage déclaratif et un système de téléchargement d'archives JAVA (JAR). À partir d'un fichier de déclaration de dépendances, IVY télécharge les bonnes versions des dépendances directes et transitives du projet puis les rend disponibles pour le script ANT.






## Critères d'évaluations



### Ses critères permettront de choisir le meilleur outil


- **Niveau de complexité :**  la question qu'il faut se poser est la suivante, à quel point est-il complexe de créer et maintenir un script build? Beaucoup d'aspects peuvent s'ajouter dans la complexité d'un script build, particulièrement d'un point de vue extérieur, par exemple, un autre membre de l'équipe. Donc, lorsqu'on analyse cet aspect, il faut vérifier le long terme ; sois est-il facile pour un nouveau développeur de lire et comprendre le script un an après l'avoir écrit ? Est-ce que le build est complexe ? Est-il intuitif ? Facile à comprendre et à suivre ? Est-il explicite ou implicite ?


- **Documentation et communauté de l'outil :** un critère important de l'adoption de l'outil est la documentation, car elle vous décrit et explique les nécessités pour atteindre un but précis, soit un projet par exemple, avec l'outil en question. La communauté qui utilise l'outil en question est tout aussi importante, car on y retrouve beaucoup d'aide, considérons que la plupart d'entre eux ont passé à travers les mêmes situations, donc ils sont de bon conseil.


- **Intégration avec IDE :** l'environnement de développement varie, selon un développeur à un autre, donc il est primordial que les outils JAVA build supportent et s'intègre avec les autres outils et produits dont les développeurs utilisent régulièrement dont les IDE( Environnement de Développement Intégrer). Bref, le support IDE est l'intégration la plus cruciale avec les outils build.



## Quels outils est le meilleur ?

- **Niveau de complexité :** l'outil le moins complexe entre ANT+IVY et MAVEN est MAVEN. Ce dernier est très déclaratif, c'est-à-dire que la plupart des développeurs auront plus de facilités à comprendre comment fonctionne un projet build. Ils n'ont pas besoin de deviner quel fichier sera dans le "JAR». Alors qu'il est plus compliqué pour les autres membres d'une équipe de travaillés sur un projet déjà existant sur IVY à cause du large éventail de façons de construire un projet sur ANT, car ce dernier nous offre une très grande liberté et contrôle sur nos build, donc il faut toujours refaire la structure pour tous les nouveaux projets. (Chaque projet à un descripteur build différent.)


- **Documentation et communauté de l'outil :** l'outil qui possède la meilleure documentation est MAVEN. Il est plus facile de retrouver le matériel qu'on recherche. Des guides d'introductions sont disponibles pour les développeurs sur plusieurs sujets variés tels que les projets multi module, les configurations, les extensions, etc. Étant donné que MAVEN est plus vieux la communauté est moins active par contre, elle est nettement mieux que celle de ANT+IVY puisque celui-ci est pratiquement insuffisant limite inexistante.


- **Intégration avec IDE :** l'outil qui possède la meilleure intégration avec les environnements de développements intégrer est MAVEN. La plupart des IDE JAVA ont un support spécifique pour MAVEN à travers des Plugins disponibles aux téléchargements. Les systèmes sont entièrement intégrés, aucun autres outil ou configuration n’est nécessaire, alors qu'avec ANT+IVY l'intégration avec les IDE est plus difficile.


### En bref, MAVEN est le meilleur outil selon les critères de complexité, de documentation/communauté et d'intégration(IDE).



