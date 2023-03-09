# Openclassrooms Projet 3 : "Portfolio-architecte-sophie-bluel"

L'objectif est d'ajouter des fonctionalités à l'aide de `Javascript` portfolio de "__Sophie Bluel__" (voir l'image ci-dessous).

<div align="center">
  <img src="https://github.com/JonathanCornic/ProjetsOpenClassrooms/blob/main/projet%203/Maquette%20Portfolio%20Sophie%20Bluel/Maquette/Capture%20d'%C3%A9cran%202023-03-06%20170010.png" />
  
  <img src="https://github.com/JonathanCornic/ProjetsOpenClassrooms/blob/main/projet%203/Maquette%20Portfolio%20Sophie%20Bluel/Maquette/Capture%20d'%C3%A9cran%202023-03-06%20170109.png" />
</div>

# Spécifications fonctionnelles
* Creer __dynamiquement__ la galerie photo du portfolio.
* Pouvoir filtrer les travaux par categorie.
* Les boutons de __filtres__ doivent changer seulement d’apparence l'orsqu'ils sont actifs.
* Creer une page __Login__ et son __Formulaire__.
* Rendre __fonctionnel__ le log in et rediriger l'utilisateur vers la page index ou apparaîtra une fenetre modale.
* Configurer le bouton "Modifer" pour qu' il fasse apparaître une nouvelle modale qui contiendra la preview de la galerie ainsi qu'un icon __delete__.
* Configurer le bouton d'__ajout__ pour pouvoir y ajouter un nouveau projet.
* Parametrer une "preview" à l'image ajouter.

# Spécifications techniques
* Le site ne doit pas se rafraichir lorsque l'on ajoute ou supprime un projet.
* Il faut pouvoir `authentifier` l'utilisateur et trouver le moyen de conserver son `Token`.
* Un message __d'erreur__ doit apparaître si les champs sont mal renseignés.
* Une seule __Modale__ à la fois doit être présente dans le code source.
* La __Modale__ doit se fermer à l'aide du bouton `X`, ou bien en cliquant en dehors de celle-ci.
* Lors de l'envoie de nouveaux projet un __Message d'erreur__ doit apparaître si les champs sont mal rensseignés.
* Lors de __l'ajout__ de travaux, la galerie doit etre mis à jour et également la galerie Preview de la modale.

# Pour lancer le backend suivez les instructions du Readme à l'interieur du dossier backend.
Il est imprtant d'utiliser un serveur local type liveserveur pour faire fonctionner le tout.

Je vous met le lien MDN ici pour se qui concerne les erreurs de type CORS :
[lien](https://developer.mozilla.org/fr/docs/Web/HTTP/CORS/Errors/CORSRequestNotHttp)
