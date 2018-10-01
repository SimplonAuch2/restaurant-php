# Restauration


Un restaurant propose des menus. Un menu à un nom et est composé de plats.

Il existe trois types de menus : standard, végétarien, enfant.

Le menu standard est composé d'une entrée, d'un plat de viande, d'un plat de légumes et d'un dessert.

Le menu végétarien est composé d'une entrée, d'un plat de poisson, d'un plat de légumes et d'un dessert.

Le menu enfant est composé d'une entrée et d'un dessert.

Un menu est composé de plats. Un plat a un nom et est caractérisé par un temps de préparation et un prix.

Il existe plusieurs espèces de plat : entrée, viande, poisson, légume, dessert.

Chaque espèce de plat possède des précisions qui lui sont propres :

* Entrée : chaude ou froide.
* Poisson : son origine : eau douce ou eau de mer…
* Viande : type de cuisson : saignant, à point, bien cuit…
* Légume : sa saison de récolte : printemps, été, automne, hiver.
* Dessert : son parfum : vanille, fraise, chocolat …

Réalisation :

On définira une classe Plat et ses classes héritées : Entrée, Viande, …

Les classes doivent comporter des méthodes permettant de:

* Connaître le nom du plat ("salade de tomate", "gigot d'agneau", "tarte" …)
* Connaître son type (chaud ou froid, saignant, à point, bien cuit …)
* Connaître son temps de préparation.
* Connaître son prix
* Afficher toutes les caractéristiques du plat ( nom, type, temps de préparation, prix)



On définira une classe Menu et ses classes héritées : MenuVegetarien, MenuStandard, …

Les classes doivent comporter des méthodes permettant de:

* Connaître le nom d'un menu
* Connaître le temps de préparation nécessaire à sa réalisation.
* Connaître son prix.
* Afficher le menu : son nom, ses plats avec leurs descriptions.
* Comparer le prix de deux menus. On doit pouvoir comparer des menus de même nature (ex. 2 menus enfant) mais aussi des menus de nature différente (ex. un menu végétarien et un menu standard etc. )


Travail à réaliser :

Réaliser un diagramme de classe (UML) et un MCD

Écrire la déclaration de chacune des classes (en php)

Écrire un programme principal permettant de déclarer, d'initialiser des instances de classes et de menu, de répondre à l'attente d'un client : possibilité de connaître, pour un menu donné, sa description (son nom, ses plats), son temps de préparation, son prix, pouvoir comparer des menus et connaître le moins cher..


Obligations :

Le code doit être correctement indenté.
Le code sera documenté et clair (nom de variable et de classes claires)
Tout ceci en anglais
