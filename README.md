# Mon Projet Web

## 1. 🎨 Présentation du projet

### Concept
- Thème choisi : site fictif de la société de vente de papier Dunder Mifflin (tiré de la série The Office).
- Public cible : fans de la série, amateurs et amatrices de blagues internes à la série.
- Objectifs du site : mettre en avant les différents personnages et la série en général, en faisant un site à l'humour décalé.

### Fonctionnalités prévues
- Navigation : 
  - Menu principal accessible depuis toutes les pages en cliquant sur le logo du site.
  - Navigation pensée mobile-first, affichée en colonne sur petits écrans puis en ligne sur tablette/desktop.
  - Mise en évidence de la page active via une classe .active.
  
- Sections principales : 
  - Page d’accueil : présentation générale, section promotionnelle “Golden Ticket”, employé du mois, best-sellers de la marque.
  - Our Company : texte de présentation, fondateurs, galerie d’images des bureaux de Dunder Mifflin.
  - Our Products : navigation par catégories, présentation des produits sous forme de cartes.
  - Our Team : introduction à l’équipe et cartes des employés classées par départements.
  - News : page “Coming soon” avec un message centralisé.
  
- Contenus proposés :
  - Textes inspirés de l’univers de The Office.
  - Images locales (produits, bureaux, employés), optimisées pour l’affichage responsive.
  - Cartes interactives avec ombres, hover et transitions visuelles.
  - Mise en page en Flexbox et Grid pour organiser les sections de manière claire et moderne.
  - Palette de couleurs personnalisée basée sur l’identité visuelle Dunder Mifflin.

---

## 2. 📚 Parcours d'apprentissage

### Ressources utilisées
- Plateforme utilisée :
  -    OpenClassrooms, cours "Créez votre site web avec HTML5 et CSS3"
- Vidéos / tutoriels suivis
  -   Flexbox Froggy, jeu interactif pour maîtriser Flexbox

### Progression
- Semaines 3–4 : choix du thème du site web, définition de la palette de couleurs, réflexion sur l’identité visuelle, premiers croquis / idées de structure
- Semaines 5–6 : début du projet site web, création du dépôt GitHub, clonage du projet dans WebStorm, première page HTML simple
- Semaines 7–8 : mise en place de l’arborescence du projet, création des pages HTML principales, structure HTML sémantique, navigation fonctionnelle entre les pages
- Semaines 9–10 : intégration complète des contenus textuels, ajout des images, attributs alt et title, début de la feuille de style CSS
- Semaines 11–12 : CSS global (couleurs, typographies, espacements), mise en page avec Flexbox et Grid, menu horizontal, début du responsive design
- Semaines 13–14 : responsive design complet, adaptation mobile / tablette / desktop, amélioration de l’expérience utilisateur, harmonisation graphique sur toutes les pages
- Semaine 15 – Rendu final: optimisation du CSS, validation HTML et CSS, mise à jour du README

Publication finale du site
---

## 3. 🛠️ Outils et méthodologie

### Environnement de travail
- IDE : WebStorm
- Navigateurs de test : Firefox, Chrome, Safari
- Versioning : Git + GitHub
- Validation : Validator W3C, PageSpeed Insights, Wave

### Méthodologie
- Approche mobile-first
- Commits réguliers et messages clairs
- Tests sur plusieurs navigateurs et appareils

### Choix de design
- Palette de couleurs :  
  - Couleur principale : `#b57b41` – Brun doré, chaleureux, rappelle le papier et les teintes vintage de la série.
  - Couleur secondaire : `#1f57e6` – Bleu Dunder Mifflin, dynamique, couleur du logo original.
  - Couleur d’accent claire / de fond : `#eff4fb` – Blanc bleuté, doux et idéal pour les fonds de page.
  - Couleur de texte : `#272226` – Gris très foncé, lisible, élégant, pas un noir pur.
  - Couleur d'accent lumineuse : `#fff9b1` – Jaune pâle, pour les touches humoristiques (ex: Golden Ticket).
  - Lien vers palette générée : https://coolors.co/b57b41-1f57e6-eff4fb-272226-fff9b1
###
- Typographies :  
  - Titres : Oswald
    - Importée en local via @font-face
    - Fichier utilisé : /fonts/oswald-v57-latin-regular.woff2
    - Appliquée aux éléments h1, h2, h3, h4 pour créer une hiérarchie visuelle claire et dynamique.
###
  - Texte : Open Sans
    - Importée en local via @font-face
    - Fichier utilisé : /fonts/open-sans-v44-latin-regular.woff2
    - Utilisée comme police principale pour tout le corps du texte (body), lisible et adaptée à un site moderne.
---

## 4. ✅ Tests et validation

### Validation technique
- HTML Validator : résultat …
- CSS Validator : résultat …
- PageSpeed Insights :  
  - Performance : …/100  
  - Accessibilité : …/100  
  - Bonnes pratiques : …/100  
  - SEO : …/100  

### Compatibilité
- Navigateurs testés : Chrome …, Firefox ✅, Safari …
- Appareils testés : mobile, tablette, desktop

### Accessibilité
- Attributs alt : ✅
- Hiérarchie des titres : ✅
- Contraste couleurs : conforme WCAG
- Navigation clavier : testée
- Zoom 200% : lisible

---

## 5. 🤖 Usage de l’IA (si applicable)

### IA utilisée
- Nom et version : ChatGPT 5
- Contexte : génération de code / debug / recherche / rédaction

### Utilisation détaillée
- Contenu généré avec l’IA : 
  - j'ai généré la majorité du contenu des textes en anglais pour mon HTML, mais je m'en suis servie majoritairement comme outil de correction et de conseil pour cette partie HTML. En CSS, je me suis appuyée sur l’IA pour comprendre la mise en page, les sélecteurs et le responsive, puis j’ai adapté le code à mon projet.
- Explication et adaptation personnelle du code généré
  - pour le HTML, l’intelligence artificielle m’a principalement servi à vérifier la validité et la cohérence de mon code, ainsi qu’à générer et reformuler les contenus textuels en anglais. La structure des pages, l’organisation sémantique et l’intégration des éléments ont été réalisées par moi-même, avec l’IA utilisée comme outil de contrôle et d’aide à la rédaction.
  - pour le CSS, l’IA m’a aidée à comprendre certaines logiques de mise en page et de responsive design, notamment avec flexbox, grid et les media queries. Les propositions ont ensuite été adaptées, simplifiées ou modifiées afin de correspondre à l’identité visuelle du site et à mes choix personnels.
  - l’utilisation de l’IA s’inscrit donc dans une démarche d’apprentissage et de compréhension des concepts, et non comme une solution clé en main.

### Proportion
- Structure HTML : 80% personnel / 20% aidé
- CSS : 40% personnel / 60% aidé
- Responsive : 50% personnel
- Tests et validation : 100% personnel

---

## 6. 🎯 Bilan personnel

### Ce que j’ai appris
- Compétences techniques acquises : 
  - bases du HTML5 et du CSS3, structuration sémantique d’une page web, mise en page avec Flexbox et Grid, gestion des images, liens et navigation, publication d’un site avec GitHub Pages  
- Découvertes surprenantes : 
  - l’importance de la structure HTML avant le design, le rôle central du CSS dans la lisibilité et l’ergonomie, l’impact du poids des images sur les performances d’un site, l’utilité des attributs alt et title pour l’accessibilité 
- Concepts difficiles maîtrisés : 
  - compréhension de la relation HTML / CSS, sélecteurs CSS et hiérarchie des styles, responsive design et media queries, organisation du code et de l’arborescence du projet   

### Difficultés rencontrées
- Problèmes techniques et solutions trouvées : 
  - gestion de git et des branches, avec une première organisation par page qui s’est révélée peu adaptée, puis adoption d’une organisation par version et utilisation de la branche main pour le développement principal.
- Moments de blocage et dépassement  
  - blocages lors de la compréhension du lien entre html et css, notamment pour les sélecteurs, la mise en page et le responsive design, dépassés par des essais progressifs et une meilleure structuration du code.
- Aide reçue et sources : 
  - aide reçue principalement via l’intelligence artificielle (chatgpt), complétée par mes prises de notes des cours OpenClassrooms et de l'aide demandée à des camarades de classe.

### Réussites et fiertés
- Aspects du projet dont je suis fière :
  - satisfaction d’avoir conçu un site web complet et fonctionnel en partant de zéro, avec une structure claire, une navigation cohérente et une identité visuelle aboutie.
- Progrès constatés depuis le début :  
  - progression marquée depuis le début du module, avec une meilleure compréhension du html, du css, de la logique de mise en page et de l’organisation globale d’un projet web.
- Envies de développement futur :  
  - envie de continuer à développer mes compétences en web, notamment en approfondissant le css, les animations, l’accessibilité et, à terme, l’ajout de fonctionnalités interactives avec javascript.

### Améliorations possibles
- Ce que j’ajouterais avec plus de temps : 
  - avec plus de temps, j’ajouterais davantage de contenu interactif, une mise en page encore plus aboutie et des animations légères pour enrichir l’expérience utilisateur. Je terminerais la page "News"
- Fonctionnalités bonus envisagées : 
  - des fonctionnalités bonus pourraient inclure des effets de survol plus avancés, des transitions animées, ainsi qu’une navigation plus dynamique entre les sections.
- Compétences à approfondir :
  - les compétences à approfondir concernent principalement le css avancé, l’accessibilité web, le responsive design plus fin et l’introduction progressive de javascript pour rendre le site plus interactif.
