# Idée projet : outil pour organiser les tâches ménagères dans une coloc

**User story**
En tant qu'utilisatrice/utilisateur, je peux : 
- Créer un compte
- Créer une Colocation
- Rejoindre une Colocation
- Créer des tâches dans une Colocation rejointe
- Voir les tâches
- M'attribuer des tâches
- Marquer des tâches comme accomplies
- Gagner des points selon les tâches accomplies
- Voir mon profil et mes points
- Voir le profil et les points des autres colocs
- Basculer l'affichage en dark mode
- Réinitialiser mon mot de passe
- ...

**Classes/Objets**

Profil :
- e-mail*
- password*
- nom*
- photo

Colocation :
- nom*
- adresse*
- mot de passe*

Tâche :
- ID*
- nom*
- description
- temps requis*: long/moyen/court (on gagne plus de points avec une tâche longue qu'avec une courte)
- date de création*
- attribution (nom du coloc qui s'est attribué la tâche)
- date de réalisation (quand tâche marquée comme accomplie)
- délai ?
- certaines tâches hebdomadaires ? répétition ?

**Pages**
 - Page "Ma coloc", avec les tâches ouvertes, en cours
 - Page "Profil", avec les points, les tâches attribuées, la photo, etc.
 - Page "Création de tâche"
 - Page "login"
 - Page calendrier ?

**Idées ressources / outils** 
- [Tutorial pour créer une todo (Meteor + React simple)](https://react-tutorial.meteor.com/simple-todos/)
- [Tailwind CSS](https://tailwindcss.com/) ou [Primer Design System](https://primer.style/) ou [Bootstrap](https://getbootstrap.com/) mais bof
- [Figma](https://www.figma.com/)
- ...

**Questions**
 - Est-ce que les utilisateurs peuvent attribuer des tâches aux autres ?
 - Que fait-on avec les points ? Ca pourrait être une règle définie à l'avance par les colocs : au bout de "XX" points, on paie une bouffe ou on fait un kdo.
 - Est-ce qu'il y a une notion de date, de calendrier ou de délai ?
 - Comment rejoint-on une coloc ? (lien unique, mot de passe, etc)
 - ...
