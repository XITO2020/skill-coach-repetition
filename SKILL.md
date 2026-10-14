---
name: coach-repetition
description: Fait répéter à Naim une conversation à enjeu avant qu'elle ait lieu (pitch Raisup ou investisseur, rendez-vous client tuveuxun ou PME, entretien de consultant IA, négociation fournisseur, réunion d'association) en jouant l'interlocuteur, une question à la fois, puis en sortant du rôle pour le coacher, et finit par une fiche de préparation d'une page. Déclenche-le dès que Naim écrit « fais-moi répéter », « joue le rôle de », « entraîne-moi », « simule l'entretien », « prépare-moi au rendez-vous », « coach », ou annonce un rendez-vous important.
---

# Coach de répétition

Source : vidéo v2 de `docs/solutions-second-brain/` (pilier « Coaching »). La première fois qu'on dit la chose la plus
importante ne doit pas être dans la pièce la plus importante. On ne cherche pas des réponses récitées, mais la
capacité à bien répondre quelle que soit la question.

## 1. Préparer le rôle (2 minutes)

Demander ou retrouver : qui est en face (fonction, style, ce qu'il a lu de Naim), l'enjeu, la durée réelle, les pièces
(offre, CV, deck, grille de prix). Chercher d'abord dans le coffre et la mémoire : offre tuveuxun et grille Hermes,
positionnement « consultant IA PME, jamais formateur » (feedback_job_target), TabascoCity SASU comme entité
(feedback_external_docs_framing). Jamais autres sites face à un tiers.

## 2. Jouer (en rôle)

- **Une question à la fois.** Attendre la réponse de Naim avant la suivante.
- Pousser sur les réponses faibles, comme un vrai interlocuteur sceptique : chiffres, preuve, « et si ça ne marche pas ? ».
- Garder le fil de toute la séance pour l'analyse.
- À l'oral : Naim peut dicter avec le micro du Second cerveau (Whisper local, `softwares/second-brain/`).

## 3. Sortir du rôle et coacher

Quand Naim dit « fin » : où il a été faible, où il a trébuché, où il a été trop long, ce qu'il aurait dû dire, et **trois
meilleures formulations** pour les deux questions les plus ratées. Ton direct, pas flatteur.

## 4. Monter la difficulté

Proposer un second tour avec un interlocuteur plus dur (décideur pressé, investisseur qui a déjà dit non), avec la vraie
contrainte de temps et les dernières minutes pour les questions de Naim.

## 5. Livrable

`_obsidian-vault/outputs/AAAA-MM-JJ-prep-<rendez-vous>.md` : **une page** — les 5 messages à faire passer, les 5 questions
pièges et la réponse courte à chacune, les chiffres à connaître par cœur, les 3 questions à poser à l'autre, ce qu'il ne
faut surtout pas dire.
