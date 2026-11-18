# Quiz 3 · Choisir et paramétrer

À faire à la fin de l'étape 3, après la vidéo « Partie 3 » et l'écriture de vos fichiers .agent.md.

**Mode d'emploi :** pour chaque question, notez votre réponse (A, B ou C) **avant** d'ouvrir « Voir la réponse ». Comptez vos bonnes réponses à la fin. Vous pouvez refaire le quiz autant de fois que nécessaire.


## Question 1

Quelle est la première question à se poser avant de déléguer une tâche ?

- **A.** Quel est le modèle le plus récent ?
- **B.** Combien la tâche va-t-elle coûter ?
- **C.** Le code ou les données peuvent-ils sortir de l'organisation ?

<details><summary>Voir la réponse</summary>

**Réponse C.** C'est la question bloquante (RGPD, secret industriel). Si la réponse est non : modèle local (Ollama) ou fournisseur validé par l'organisation.

</details>


## Question 2

Quelle famille de modèle choisir pour l'agent architecte ?

- **A.** rapide
- **B.** raisonnement
- **C.** polyvalent

<details><summary>Voir la réponse</summary>

**Réponse B.** Concevoir une architecture demande une analyse longue ; une erreur à cette étape coûte cher plus tard.

</details>


## Question 3

Pourquoi le relecteur sécurité n'a-t-il pas l'outil d'écriture ?

- **A.** par moindre privilège : il signale, il ne corrige pas
- **B.** parce qu'il coûterait plus cher
- **C.** parce que c'est techniquement impossible

<details><summary>Voir la réponse</summary>

**Réponse A.** Un agent n'a que les outils strictement nécessaires à son rôle : il ne peut pas faire ce qu'on ne lui a pas confié.

</details>


## Question 4

À quoi sert le champ handoffs d'un fichier .agent.md ?

- **A.** choisir le modèle
- **B.** limiter les outils
- **C.** passer la main à l'agent suivant

<details><summary>Voir la réponse</summary>

**Réponse C.** Il ajoute un bouton qui transmet le travail à un autre agent, sans avoir à tout réexpliquer.

</details>


## Question 5

Où se trouvent les garde-fous les plus solides ?

- **A.** dans les consignes de l'agent
- **B.** côté GitHub : branche protégée, revue obligatoire, secrets hors du code
- **C.** dans le choix du modèle

<details><summary>Voir la réponse</summary>

**Réponse B.** Un agent peut mal suivre une consigne ; il ne peut pas contourner une règle de protection de branche.

</details>


---

**Mon score : … / 5** — je valide si j'obtiens au moins **4/5**.

Reportez votre score dans [PROGRESSION.md](../PROGRESSION.md). Sinon : revoyez la vidéo « Partie 3 » et la partie 4 du cours, puis refaites le quiz.
