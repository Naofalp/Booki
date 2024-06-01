<img src="images/logo/Booki.png" alt="Logo de Booki" width="100">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

# Booki

Ce projet vise à créer une interface utilisateur pour rechercher des hébergements et des activités. Cette version initiale se concentre sur la validation de l'interface et ne comporte pas de fonctionnalité opérationnelle.


[Site web responsive](https://naofalp.github.io/Booki/) ⎜ [Maquette Figma](https://www.figma.com/design/r9YJyUkpVdrxzBBKGH7reY/Maquettes-Booki-(desktop%2C-mobile%2C-tablette)?node-id=3-0) ⎜ [English](#English)

## Description

Je débute mon alternance en tant que développeur web au sein de la start-up Booki. 

L’entreprise souhaite développer un site Internet qui permette aux usagers de trouver des hébergements et des activités dans la ville de leur choix. Je suis chargé d'intégrer l'interface du site avec du code HTML et CSS. Pour cela, je travaille en étroite collaboration avec Sarah, la CTO, et Loïc, l’UI designer.

## Table des matières

- [Spécifications fonctionnelles](#spécifications-fonctionnelles)
- [Spécifications techniques](#spécifications-techniques)

## Spécifications fonctionnelles

### Fonction recherche
- Les usagers pourront rechercher des hébergements dans la ville de leur choix.
- Le champ de recherche est un champ de saisie, le texte doit donc pouvoir être édité par l’utilisateur.
- Il faut englober ce champ dans un formulaire. La partie Recherche ne doit pas être fonctionnelle - il s’agit d’une première version pour valider l’interface.

### Liens “Hébergements” et “Activités”
- Les textes “Hébergements” et “Activités”, situés dans l’en-tête, sont des liens. Ils doivent mener respectivement vers la section “Hébergements à Marseille” et “Activités à Marseille”.

### Cartes hébergements et activités
- Chaque carte d’hébergement ou d’activité devra être cliquable dans son intégralité (pas uniquement le titre).
- Pour l’instant, les liens sont vides. On peut utiliser un attribut `href=”#”` pour simuler la présence d’un lien.

### Filtres de recherche
- Les hébergements peuvent être filtrés par thématique, comme le budget ou l’ambiance.
- Les filtres doivent changer de couleur au survol de la souris.
- Les filtres ne doivent pas être fonctionnels - il s’agit juste d’une première version pour valider l’interface.



## Spécifications techniques

### Breakpoints
- Nous avons convenu avec le designer UI d’utiliser 1024 px et 768 px :
  - >1024 px pour les écrans d’ordinateurs ;
  - >=768 px pour les tablettes ;
  - Tout ce qui est en dessous de 768 px pour les téléphones portables.

### Largeur min - max
- Pour éviter d’étirer la page web sur la largeur de façon excessive, il va falloir déterminer une largeur maximum de 1440 px. Au-delà, une marge blanche doit apparaître sur les côtés et le contenu doit se limiter à 1440 px de large.
- La largeur minimum est fixée à 320 px. En-deçà de cette largeur, le comportement n’est pas garanti.

### Desktop first
- Il faut d’abord réaliser l’intégration pour les ordinateurs (autrement dit, en desktop first), puis les tablettes et enfin les téléphones.

### Bibliothèque d’icônes
- Les icônes proviennent de la bibliothèque Font Awesome.

### Couleurs
- Les couleurs de la charte sont le bleu (#0065FC), le bleu clair (#DEEBFF) et le gris pour le fond (#F2F2F2).

### Police
- La police du site est Raleway.

### Balises sémantiques
- Il est important d’utiliser les balises sémantiques.

### Validité du code
- Aucun IDE ou éditeur de code particulier n’est imposé pour le développement.
- Le code doit être valide aux validateurs W3C HTML et CSS.
- Le code HTML ne doit pas contenir de propriété CSS.
- Lors du passage du desktop au mobile et à la tablette, ne pas dupliquer le code HTML (exception faite dans le formulaire avec le mot “Rechercher” et l’icône de la loupe).
- Privilégier l’utilisation des classes CSS pour cibler un élément, plutôt que d’utiliser le nom de l’élément lui-même.
- Ne pas dupliquer des classes CSS inutilement.

### Compatibilité navigateurs
- La maquette doit être compatible avec les dernières versions de Google Chrome et de Mozilla Firefox. Il faudra tester la page web sur ces deux navigateurs.

### Restrictions
- Aucun framework CSS (type BootStrap ou Tailwind CSS) ou préprocesseur CSS (type Sass ou Less) ne doit être utilisé.
- Aucun autre langage ne doit être utilisé (comme JavaScript, par exemple).



## English

## Description

I am starting my alternance as a web developer at the start-up Booki.

The company wants to develop a website that allows users to find accommodations and activities in the city of their choice. I am responsible for integrating the user interface using HTML and CSS. For this, I work closely with Sarah, the CTO, and Loïc, the UI designer.

## Table of contents

- [Functional Specifications](#functional-specifications)
- [Technical Specifications](#technical-specifications)

## Functional Specifications


### Search Function
- Users will be able to search for accommodations in the city of their choice.
- The search field is an input field, so the text must be editable by the user.
- This field must be wrapped in a form. The search feature does not need to be functional - this is an initial version to validate the interface.

### Links “Accommodations” and “Activities”
- The texts “Accommodations” and “Activities” in the header are links. They should lead to the sections “Accommodations in Marseille” and “Activities in Marseille” respectively.

### Accommodation and Activity Cards
- Each accommodation or activity card should be clickable in its entirety (not just the title).
- For now, the links are empty. You can use an attribute `href="#"` to simulate the presence of a link.

### Search Filters
- Accommodations can be filtered by themes, such as budget or ambiance.
- Filters should change color when hovered over with the mouse.
- The filters do not need to be functional - this is just an initial version to validate the interface.



## Technical Specifications

### Breakpoints
- We agreed with the UI designer to use 1024 px and 768 px:
  - >1024 px for computer screens;
  - >=768 px for tablets;
  - Anything below 768 px for mobile phones.

### Min - Max Width
- To avoid excessive stretching of the web page, a maximum width of 1440 px must be set. Beyond this, a white margin should appear on the sides and the content should be limited to 1440 px wide.
- The minimum width is set to 320 px. Below this width, the behavior is not guaranteed.

### Desktop First
- Integration should be done first for computers (desktop first), then tablets, and finally phones.

### Icon Library
- Icons are from the Font Awesome library.

### Colors
- The colors of the design are blue (#0065FC), light blue (#DEEBFF), and gray for the background (#F2F2F2).

### Font
- The site font is Raleway.

### Semantic Tags
- It is important to use semantic tags.

### Code Validity
- No specific IDE or code editor is required for development.
- The code must be valid with W3C HTML and CSS validators.
- HTML code must not contain CSS properties.
- When transitioning from desktop to mobile and tablet, do not duplicate HTML code (exception made in the form with the word “Search” and the magnifying glass icon).
- Prefer the use of CSS classes to target an element, rather than using the element’s name itself.
- Do not duplicate CSS classes unnecessarily.

### Browser Compatibility
- The design must be compatible with the latest versions of Google Chrome and Mozilla Firefox. The web page should be tested on these two browsers.

### Restrictions
- No CSS frameworks (such as Bootstrap or Tailwind CSS) or CSS preprocessors (such as Sass or Less) should be used.
- No other language should be used (such as JavaScript, for example).

