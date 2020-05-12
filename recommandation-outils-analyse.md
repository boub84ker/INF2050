# SonarQube vs PMD

## Identification

- Cours      :  Outils et pratiques de développement logiciel
- Sigle      : `INF2050`
- Session    : `Hiver 2020`
- Groupe     : `30`
- Enseignant : `François-Xavier Guillemette`
- Auteur     :  `Zineb Ben Larabi (BENZ21519706)`
- Auteur     : `Ahmed Lakkati (LAKA09038700)`
- Auteur     : `Boubker Kabbaj (KABB23038404)`




## SonarQube

### Description

SonarQube est un logiciel libre qui mesure et gère la qualité du code source. Il peut analyser une site internet et meme une application mobile ou Java. 
Sonar a été développé dans l'objectif de rendre la gestion de la qualité du code accessible au plus grand nombre sans être le développeur. Cette analyse va permettre aux équipes de développement de se répartir les tâches de traitements et d'analyses du code source.

Il fournit des analyseurs de code, des outils de génération de rapports, des modules de recherche de défauts et TimeMachine comme fonctionnalité principale. Il utilise aussi des plugin pour la mise en place des fonctionnalités. Il est alors un outil pour les développeurs et les gestionnaires pour analyser la qualité du code source.



## PMD


### Description 
PMD est un outil d’analyse de code static qui est en mesure de detecter automatiquement un large éventail de défauts potentiels et de code dangereux ou non optimisé souvent de mauvaise pratiques par exemple, attraper un exception sans la traiter, trop de méthode complexe, etc.

Contrairement au autre outil, PMD se concentre sur la détection préventive des défauts dans le code en veillant à ce que les bonnes pratiques soient suivies.

PMD vient avec des règles qui peuvent être configurées afin de les utiliser sur un projet donné. Par exemple, des try/catchs vide, utiliser .equals() au lieu de ‘==‘, mauvaise utilisation de la convention des noms de variables.

De plus, PMD vient avec un CPD « copy-paste detector » c’est-à-dire qu’il détecte les code copie-coller 




## Critères d'évaluations


### Ses critères permettront de choisir le meilleur outil

* **Qualité:** Est-ce que l’outil est en mesure de nous donné une report sur la qualité du code source? Est-il en mesure de nous donner des suggestion sur le code a améliorer ? Est-il en mesure de detecter les bugs? Il est important de detecter les bugs afin d’y remédier et afin d’optimiser le code. Est-ce que l’outil est en mesure de verifier si le code respecte les conventions d’écriture de code source ? Ce sont des questions primordiales qui nous permettent de savoir si l’outil est en mesure de gérer la qualité du code source.

* **Documentation et communauté de l'outil:**  un critère important de l'adoption de l'outil est la documentation, car elle vous décrit et explique les nécessités pour atteindre un but précis, soit un projet par exemple, avec l'outil en question. La communauté qui utilise l'outil en question est tout aussi importante, car on y retrouve beaucoup d'aide, considérons que la plupart d'entre eux ont passé à travers les mêmes situations, donc ils sont de bon conseil.

* **Intégration avec IDE :** l'environnement de développement varie, selon un développeur à un autre, donc il est primordial que les outils d’analyse statique pour Java supportent et s'intègre avec les autres outils et produits dont les développeurs utilisent régulièrement dont les IDE( Environnement de Développement Intégrer).
## Quels outils est le meilleur ?


* **Qualité:** L’outil qui est mesure de gérer le mieux la qualité du code source est SonarQube, car celui-ci détecte les bugs, mais aussi les duplication, les conventions de codage et d’écriture, il couvre les tests. Il peut aussi indiquer grace aux indicateur de qualité se qui peut a l’avenir arriver de mauvais au code. Il offre aussi des outils de gestion de la qualité pour vous aider a corriger les erreurs. Alors que PMD, lui est un outil qui sert a detecter les mauvaises pratiques du code conventionnel  
  


* **Documentation et communauté de l'outil:** l'outil qui possède la meilleure documentation est SonarQube. Il est plus facile de retrouver le matériel qu'on recherche. Des guides d'introductions sont disponibles pour les développeurs sur plusieurs sujets variés. Selon une étude 20% des développeurs utilisent SonarQube alors que 12% utilisent PMD, cette difference nous permet de réaliser que la communauté PMD est plus petite de SonarQube.


* **Intégration avec IDE :**  Les deux outils possèdent une intégration avec les environnements de développements intégrer et le langage Java 8. Par contre, PMD est aussi compatible avec JavaScript, PLSQL.

