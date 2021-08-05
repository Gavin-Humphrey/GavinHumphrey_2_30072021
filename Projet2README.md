# Projet-2-Reservia
J'ai d'abord commencé par découper la maquette en éléments html. 
Je l'ai divisé en sections : la première section, <header>, qui comprend le logo Reservia et la navigation que j'ai taguée "navbar".
Ensuite, je suis allé à la "section Search", c'est la section qui contient la barre de recherche, les filtres et l'icône d'information. 
Je suis ensuite allé à la "accomodations section". Ceci est divisé en la "main section" que j'ai placée dans "flex row", et la "aside", que j'ai placée en "flex column". 
Je suis ensuite passé à la "section activities" qui est un mélange de boxes aux plusiers dimensions; que j'ai divisé en sous-sections en utilisant les <div> et "class".
Et enfin, le "footer". J'ai utilisé beaucoup de <div>, "class" et <span> pour définir et séparer le contenu. Côté image, j'ai opté pour les petites image afin d'avoir un site beaucoup plus dynamique qui sera plus rapide à charger. J'ai rendu les images cliquables et agrandissables. Et toutes les icônes proviennent de "Font Awesome".
Puis au CSS. 
J'ai choisi la Flexbox plutôt que la Grid, même si, pour moi, cela me semble un peut plus complexe car c'est  unidimensionele par a port a Grid qui a deux dimensionele. 
Je l'ai pratiquement utilisé du "header" (logo Reservia) jusqu'à la fin (footer). 
J'ai utilisé le "flex-row" pour la section et "flex-column" pour  "aside" et un mélange des deux pour la "activities section". 
J'ai utilisé la font "Raleway", sans-serif, en bold. Et toutes les icônes proviennent de "Font Awesome", j'ai utilisé #F2F2F2 pour background color et RGB pour color value. 
J'ai fait les filtres et les images à transformer avec une "scale" de 1,05 au survol, avec un pointeur de curseur.
En ce qui concerne le "responsive", j'ai utilisé trois breakpoints, 1200px, 992px et 576px; pour ordinateurs portables, tablettes et smartphones. 
J'ai inversé le "order" de "containergauche" qui est la "accomodations section" et "àside", à partir de 992px, et les ai tous placés en "column" à partir d'un "breakpoint" de 576px.
