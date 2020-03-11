# gestibrew
Application de gestion de brasserie artisanale


Développée en Nativescript + VueJS 
https://docs.nativescript.org/vuejs/nativescript-vuejs

j'ai fait la maquette de gestibrew sur inVision. Tout n'est pas maquetté parfaitement, mais le gros y est. Il manque quelques trucs de gestions comme des alertes, des confirmations d'enregistrement ou d'annulation... et puis l'édition des paramètres, l'ajout d'indisponibilité, et le planning des fermenteurs (que je ne sais pas encore comment faire). J'ai atteint ce que je pouvais maquetter avec la version gratuite de moqups (200 éléments c'est pas beaucoup)
https://invis.io/HCW6NRMZKTB#/407051589_ACCUEIL


Pour l'ordre de réalisation des fonctionnalités, voici les besoins :
MVP : accueil avec alerte des stocks, gestion et édition des stocks, liste et création de brassins, calcul des coûts, paramètres. Un truc qui n'apparait pas bien dans la maquette, c'est que les stocks par défaut affichent le stock réel (les brassins dont la date est passée), mais il faudra aussi pouvoir afficher le stock prévisionnel (en fonction des brassins prévus mais pas encore fait)... à voir comment on fera ça.
V1 : ajout de l'édition du pdf d'un brassin, qui contient nom + n°, coûts détaillés, volume final, coût total au litre, date de conditionnement
V2 : ajout de la partie planning, des indisponibilités, et maj de l'accueil avec l'affichage de la prochaine étape. C'est la partie un peu marrante, car il faut calculer les dates en fonctions des disponibilités, des dates habituelles des étapes, sachant que tout peut être réédité
V3 : ajout du planning des fermenteurs
V4 : ajout d'une gestion des accès (dans un but de distribution/commercialisation)
V5 : ajout de la gestion du parc de fûts ? ou autre...
