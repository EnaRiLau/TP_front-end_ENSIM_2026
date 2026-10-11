# Corrections des TP - Programmation front end


## TP 2.1 : Styliser votre site vitrine

1. Créer un fichier .css et importez le dans vos 3 pages HTML

2. Barre de navigation - À utiliser dans chaque page : 
   * Style générique pour la barre de navigation
   * Style pour "le lien actif" (repérer en un coup d'œil la page active)
   * Appliquez la propriété `list-style-type: none;` sur la liste des liens

3. Modifier le style de tous les titres de niveau 1 : Utiliser la police "Impact, fantasy" et modifier la taille du texte à "2.5rem"

4. Encadrer l'image de la page "Mes informations" (avec un padding de "15px")

5. Mettre en gras le texte des colonnes "Nom du projet" de la page "Experiences"

6. Écrire en taille de police "0.7rem" le texte du footer de la page "Experience"

7. Mettre un fond d'une couleur de votre choix au formulaire de la page "Mes informations"
   


## TP 1.4 : Ajouter un formulaire de contact

1. Sur la page "Mes informations", ajouter un formulaire tel que : 
   * La balise **`form`** contienne 2 attributs :
     * **`action`** avec comme valeur : "**mailto:**_VotreEmail_" (Remplacer _"VotreEmail"_ par votre adresse mail 😉)
     * **`method`** avec comme valeur : **`GET`**
   * Il contienne : 
     * Un **`input`** **requis** avec un attribut **type** valant **`email`**
     * Un **`textarea`** avec un attribut **name** valant **`body`** (qui permette à l'utilisateur de "pré-remplir" son message)
     * Un **bouton** de type **`submit`**
     * Un **bouton** de type **`reset`**
   * Tous les champs du formulaires doivent être dans un même `fieldset`
   * Chaque champ / groupe de champs doit avoir un `label` / `legend` associé

## TP 1.3 : Initiez la page de vos experiences 

1. Créer une nouvelle page "Experiences" contenant au minimum : 
   * Un **tableau** de vos projets personnels, étudiants et professionels : 
     * En ligne, chacun de vos projets
     * 2 colonnes : nom du projet  &   technologies / outils / bonne pratiques utilisées
   * Un footer qui rappelle votre nom / prénom et qui indique votre année de promotion

2. Mettre à jour les `nav` de toutes les pages

## TP 1.2 : Ajouter une image

1. Ajoutez une image de votre choix sur la page "Mes informations"

## TP 1.1 : Initier votre site vitrine

1. Créer une page HTML "Mes informations" qui contienne au minimum : 
   * Un titre de niveau 1 qui contienne votre nom / prénom
   * Une liste à puces non ordonnées de différents hobbies / passions que vous avez


2. Créer une page HTML "Accueil" qui contienne au minimum : 
   * Un titre de niveau 1 "Bienvenue sur mon site vitrine !"
   * Un paragraphe contenant un texte de votre choix ([lorem Ipsum ?](https://fr.lipsum.com/))

3. Créer une barre de navigation dans ces 2 pages qui permet de naviguer entre ces 2 pages