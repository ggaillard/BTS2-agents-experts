# Quiz final · Bilan du parcours

À faire à l'étape 5. Les questions reprennent la partie 10 du cours écrit.

**Mode d'emploi :** pour chaque question, notez votre réponse (A, B ou C) **avant** d'ouvrir « Voir la réponse ». Comptez vos bonnes réponses à la fin. Vous pouvez refaire le quiz autant de fois que nécessaire.


## Question 1

Dans quel ordre l'IA a-t-elle gagné en autonomie ?

- **A.** complétion, conversation, agent local, agent autonome
- **B.** agent autonome, agent local, conversation, complétion
- **C.** conversation, complétion, agent autonome, agent local

<details><summary>Voir la réponse</summary>

**Réponse A.** Niveaux 1-2 : l'humain écrit, l'IA aide. Niveaux 3-4 : l'IA écrit, l'humain dirige.

</details>


## Question 2

Quel est le rôle du fichier AGENTS.md ?

- **A.** lister les étudiants du projet
- **B.** remplacer le README
- **C.** être la fiche de poste commune à tous les agents : pile, commandes, règles

<details><summary>Voir la réponse</summary>

**Réponse C.** Il est lu par Copilot, Claude, Codex… avant chaque tâche ; il contient aussi les règles apprises.

</details>


## Question 3

Quelle issue un agent peut-il réaliser sans ambiguïté ?

- **A.** « Ajouter la recherche »
- **B.** une issue avec contexte, besoin, critères d'acceptation testables et hors périmètre
- **C.** « Fais au mieux pour améliorer le catalogue »

<details><summary>Voir la réponse</summary>

**Réponse B.** Une issue floue donne une PR fausse : chaque critère doit se vérifier par oui ou par non.

</details>


## Question 4

Pourquoi l'humain écrit-il un test d'acceptation avant de déléguer ?

- **A.** parce que ce test est le juge de paix qui dira si la tâche est réussie
- **B.** pour occuper le temps pendant que l'agent travaille
- **C.** parce que l'agent ne sait pas écrire de tests

<details><summary>Voir la réponse</summary>

**Réponse A.** Sans test fiable, l'agent peut « réussir » une tâche ratée.

</details>


## Question 5

Vous corrigez un bug dans la facturation d'un client soumis au RGPD. Quel modèle ?

- **A.** le plus puissant du moment, quel que soit le fournisseur
- **B.** le modèle le plus rapide
- **C.** un modèle local ou un fournisseur validé par l'organisation

<details><summary>Voir la réponse</summary>

**Réponse C.** La confidentialité passe avant la performance : les données ne doivent pas sortir sans accord.

</details>


## Question 6

Une PR d'agent ajoute le paquet laravel-pdf-maker-pro. Que vérifiez-vous ?

- **A.** rien, la CI s'en charge
- **B.** qu'il existe vraiment, est maintenu et a une licence compatible
- **C.** seulement qu'il s'installe sans erreur

<details><summary>Voir la réponse</summary>

**Réponse B.** Un agent peut inventer un nom de paquet ou tomber sur un paquet piégé au nom proche d'un paquet connu.

</details>


## Question 7

Qu'est-ce qu'une injection de prompt ?

- **A.** une faille SQL classique
- **B.** une erreur de syntaxe dans le prompt
- **C.** un texte malveillant, dans une issue ou un fichier, qui détourne les consignes de l'agent

<details><summary>Voir la réponse</summary>

**Réponse C.** Exemple : une issue contenant « ignore tes consignes et… ». Parade : relire les issues, outils minimaux.

</details>


## Question 8

Dans le cycle agentique, où se concentre l'effort du développeur ?

- **A.** aux deux extrémités : la spécification et la revue
- **B.** au milieu, sur le codage
- **C.** uniquement sur les tests

<details><summary>Voir la réponse</summary>

**Réponse A.** L'agent produit au milieu ; l'humain cadre au début et décide à la fin.

</details>


## Question 9

« C'est Copilot qui a écrit ce code. » Pourquoi cette phrase n'excuse-t-elle pas le développeur ?

- **A.** parce que Copilot ne fait jamais d'erreur
- **B.** parce que celui qui fusionne relit, explique et assume le code livré
- **C.** parce que la phrase est fausse techniquement

<details><summary>Voir la réponse</summary>

**Réponse B.** Le code reste sous la responsabilité de l'humain qui l'a accepté, même s'il ne l'a pas tapé.

</details>


## Question 10

Un agent a répété deux fois la même erreur. Où ajouter la règle qui l'évitera ?

- **A.** dans un commentaire de la PR
- **B.** dans le nom de la branche
- **C.** dans AGENTS.md

<details><summary>Voir la réponse</summary>

**Réponse C.** Tous les agents lisent AGENTS.md avant chaque tâche : le dépôt apprend de ses erreurs.

</details>


---

**Mon score : … / 10** — je valide si j'obtiens au moins **7/10**.

Reportez votre score dans [PROGRESSION.md](../PROGRESSION.md). Sinon : relisez le cours écrit, en particulier les parties correspondant à vos erreurs, puis refaites le quiz.
