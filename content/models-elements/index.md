---
title: "Tous les modèles de présentation"
subtitle: "Tous les modèles de présentation Sligo"
type: presentation
description: |-
  Démonstration légère des compositions Sligo Alpha.
authors:
  - Sligo
noindex: true
theme:
  background: "#f7f6f2"
  ink: "#151d34"
  blue: "#164791"
  violet: "#4631d4"
  red: "#c61818"

slides:
  content:

    - part: "Le vocabulaire"

    - title: "Une page normale"
      texte: |-
        Sligo laisse le Markdown faire son travail.

        - Une liste reste une liste
        - Les fragments sont ajoutés après le rendu
        - Le contenu reste lisible sans CSS spécifique

    - title: "Une citation"
      texte: |-
        Une slide normale peut contenir du Markdown riche.

        > La simplicité d'écriture est une fonctionnalité.
    - part: "Explication"
    - title: "Un rappel"
      texte: |-
        Le texte normal est centré, avec une largeur confortable.
      focus: |-
        ## À retenir

        Pas besoin de classes pour obtenir cette composition.

    - title: "Deux regards"
      compare:
        - color: blue
          title: "WebPerf"
          texte: |-
            - Tests automatisés
            - Front & Back
            - Tâtonnage
            - Expérimentation
        - color: violet
          title: "Accessibilité"
          texte: |-
            - Tests manuels
            - Front
            - Normatif
            - Légal

    - title: "Illustrer un propos"
      aside:
        - image: example-diagram.svg
        - color: violet
          texte: |-
            **Contexte :** l'image occupe l'espace principal.

            La zone secondaire sert à expliquer, préciser ou rappeler.

    - title: "Étapes"
      steps:
        - "Observer"
        - "Mesurer"
        - "Comprendre"
        - "Agir"

    - steps:
        - title: "Observer"
          texte: "Voir le comportement réel"
        - title: "Mesurer"
          texte: "Obtenir des données"
        - title: "Comprendre"
          texte: "Identifier les causes"
        - title: "Agir"
          texte: "Modifier ce qui compte"

    - title: "Trois chiffres"
      stats:
        - value: "42%"
          label: "utilisateurs"
        - value: "1,8 s"
          label: "chargement"
        - value: "−35%"
          label: "poids transféré"

    - statement:
        eyebrow: "À retenir"
        texte: "La performance perçue est une expérience utilisateur."
        note: "Une seule idée. Beaucoup d'espace."

    - title: "Les idées arrivent"
      cards:
        - title: "Tests automatisés"
          texte: "Front & Back"
        - title: "Tâtonnage"
          texte: "Expérimentation"
        - title: "Mesure"
          texte: "Données réelles"

    - title: "Un chiffre"
      stat:
        eyebrow: "Indicateur clé"
        value: "42%"
        label: "des utilisateurs"
        note: "Animation volontairement discrète."

    - title: "Un raccourci"
      keyboard: "Naviguer|←,→"

    - title: "Un SVG"
      svg: example-diagram.svg

    - title: "Du code"
      code:
        language: javascript
        content: |-
          const result = await fetch(url);
          const data = await result.json();
          console.log(data);

    - title: "Un quiz"
      quiz:
        question: "Quelle syntaxe reste la plus simple ?"
        choices:
          - text: "Du Markdown normal"
            correct: true
          - text: "Des classes CSS partout"
            correct: false
          - text: "Des balises HTML dans chaque slide"
            correct: false
          - text: "Des options de layout partout"
            correct: false
    - title: "Quiz"
      quiz:
        question: "Quelle composition utiliser pour une progression ?"
        choices:
          - text: "steps"
            correct: true
            explanation: "Une progression est une intention de type steps."
          - text: "compare"
            correct: false
          - text: "statement"
            correct: false
          - text: "stat"
            correct: false

    - statement:
        eyebrow: "Fin"
        texte: "Décrire ce que l'on veut raconter."
---