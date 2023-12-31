# ndli-front-2023

# Projet React sur le Changement Climatique

Ce projet React vise à sensibiliser les utilisateurs aux questions liées au changement climatique. Il offre une expérience interactive permettant aux utilisateurs de tester leurs connaissances sur ce sujet crucial.

## Fonctionnalités

### 1. Composant Header :
- Options d'accessibilité : Monochromie, Dichromie, Trichromie, Dyslexie.
- Basculement de police : Police Dyslexie pour une meilleure lisibilité.
- Design réactif : Le header inclut une icône d'engrenage révélant des options d'accessibilité.

### 2. Composant Home :
- Affichage de la liste des idées reçues traitées et de leurs explications.

### 3. Composant HomeMainContainer :
- Présente un lien vers une section "Testez vos connaissances".
- Rend une liste de questions avec des explications associées.

### 4. Composant QuestionPage :
- Gère l'état des réponses sélectionnées, l'affichage des explications et l'index de la question actuelle.
- Rend de manière dynamique les questions, les options de réponse et les explications.
- Permet aux utilisateurs de sélectionner des réponses et de voir des explications.
- Prend en charge l'interaction au clavier pour la sélection des réponses.
- Utilise une fonction de réinitialisation pour passer à la question suivante.
- Récupère les données des questions à partir d'un fichier JSON externe.
- Rend les images associées à chaque question.

### 5. JSON de données :
- Contient une liste de questions avec des réponses, des explications et des images associées.


## Approche de conception - Numérique Durable

- **Éco-conception Responsable**: Notre application web priorise une approche éco-conception, réduisant l'impact environnemental.

- **Optimisation des Ressources**: Hébergement responsable, utilisation de "linters" pour des calculs efficients, et minimisation des actualisations côté client.

- **Réduction des Données Transférées**: Conception minimale du site, lazy loading, utilisation d'images vectorielles (`svg`), et minification du code serveur.

- **Méthodologie Documentée**: Une stratégie basée sur une recherche approfondie, avec des métriques pour évaluer l'impact environnemental.

- **Sensibilisation Environnementale**: En tant que plateforme informative, notre site va au-delà en sensibilisant les utilisateurs à la transition écologique.

- **Accessibilité pour Tous**: Notre application est conçue pour être utilisable par toutes les personnes, y compris celles en situation de handicap.

