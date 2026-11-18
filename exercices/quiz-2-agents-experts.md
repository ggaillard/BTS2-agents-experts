# Quiz 2 · Les agents experts

À faire à la fin de l'étape 2, après la vidéo « Partie 2 » et les diapositives 8 à 18.

**Mode d'emploi :** pour chaque question, notez votre réponse (A, B ou C) **avant** d'ouvrir « Voir la réponse ». Comptez vos bonnes réponses à la fin. Vous pouvez refaire le quiz autant de fois que nécessaire.


## Question 1

Quel agent propose un plan technique sans écrire de code ?

- **A.** le développeur
- **B.** l'architecte
- **C.** le testeur

<details><summary>Voir la réponse</summary>

**Réponse B.** L'architecte a des outils en lecture seule : il analyse le code et propose un plan, l'humain le valide.

</details>


## Question 2

Quel est le seul agent qui modifie le code de l'application et lance des commandes ?

- **A.** le développeur
- **B.** le testeur
- **C.** le documentaliste

<details><summary>Voir la réponse</summary>

**Réponse A.** Le développeur (coding agent) a les outils edit et terminal ; il travaille dans un environnement isolé et ouvre une PR.

</details>


## Question 3

Le relecteur sécurité trouve une faille. Que fait-il ?

- **A.** il la corrige lui-même
- **B.** il ferme la pull request
- **C.** il la signale et passe la main au développeur

<details><summary>Voir la réponse</summary>

**Réponse C.** Il est en lecture seule : il signale (bloquant ou mineur) et le passage de main envoie la correction au développeur.

</details>


## Question 4

Le testeur a le droit d'écrire, mais seulement :

- **A.** dans le dossier des tests
- **B.** dans le dossier app/
- **C.** dans AGENTS.md

<details><summary>Voir la réponse</summary>

**Réponse A.** Ses consignes le limitent aux tests, et lui interdisent de modifier un test existant pour le faire passer.

</details>


## Question 5

À quoi sert l'agent documentaliste ?

- **A.** écrire le code des nouvelles fonctionnalités
- **B.** tester l'interface graphique
- **C.** transformer les erreurs des agents en règles dans AGENTS.md

<details><summary>Voir la réponse</summary>

**Réponse C.** C'est la boucle longue du cycle : chaque erreur repérée devient une règle que tous les agents liront ensuite.

</details>


---

**Mon score : … / 5** — je valide si j'obtiens au moins **4/5**.

Reportez votre score dans [PROGRESSION.md](../PROGRESSION.md). Sinon : revoyez la vidéo « Partie 2 » et les diapositives des agents, puis refaites le quiz.
