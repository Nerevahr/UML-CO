# Package

* 🔖 **Définition**
* 🔖 **Responsabilité**

___

## 📑 Définition

D'une manière générale, le mot paquetage désigne un ensemble de plusieurs entités regroupées en une seule. C'est un élément commun à plusieurs diagrammes pour leur organisation.

![image](https://raw.githubusercontent.com/POEC-20-05/UML-CO/master/wiki/resources/04/01-Package.jpg)

___

## 📑 Responsabilité

> En programmation votre code source sera organisé en paquetage. Chaque paquet aura une responsabilité précise et je vous invite à réfléchir sur cette notion.


### 🏷️ **MVC**

Le motif MVC possède une organisation type de paquetage, si vous êtes dans l'utilisation d'un cadre applicatif, les responsabilités sont claires et documentées, la prise de décision est minimisée. Sans framework, je vous conseil de vous inspirer des règles établies par différents cadres pour vous cadrer vous même.

🔗 [Spring best practices](https://medium.com/the-resonant-web/spring-boot-2-0-project-structure-and-best-practices-part-2-7137bdcba7d3)

___

👨🏻‍💻 Manipulation

Créer un diagramme de package pour votre projet orienté back ou synthétisant l'organisation d'un projet sur Spring si votre projet est front uniquement, **utilisez les notes et commentaires pour expliquer la responsabilité de chaque paquet**.

___

### 🏷️ **CBA**

Le motif CBA possède une organisation orientée vue, très différente de l'organisation MVC. Chaque composant d'affichage est une classe qui possède son dossier. Si un composant en possède un autre ce sera un sous dossier

🔗 [Angular structural gidelines](https://angular.io/guide/styleguide#style-04-06)

* app
  * heroes
    * hero
    * hero-list
    * shared
  * ...

![image](https://raw.githubusercontent.com/POEC-20-05/UML-CO/master/wiki/resources/04/angular.jpg)

___

👨🏻‍💻 Manipulation

Créer un diagramme de package pour votre projet front orienté composant, **utilisez les notes et commentaires pour expliquer la responsabilité de chaque paquet**.

___

Le diagramme de package n'appartient pas à la vue développement pour rien, c'est un outil important d'analyse et de prise de décision avant création de classes.

___

👨🏻‍💻 Manipulation

Mettez vos classes dans le package correspondant et complétez votre diagramme de classe: ajouter une ou des classes sans opérations dans chaque package sur votre diagramme de classe principal. Différencier les classes par une couleur et mettez en place les relations.

___
