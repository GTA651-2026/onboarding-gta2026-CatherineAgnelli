# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T20:11:39+00:00 -- Run `20260528T200936Z-acdfcf6a`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief identifie clairement le problème d'affaires et fournit des chiffres chiffrés convaincants sur la valeur créée. Il manque cependant des éléments organisationnels (taille/secteur/budget), une grille de justification par critère et des recommandations différenciées et mesurables par contexte.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief mentionne seulement le cas choisi (Klarna) sans préciser taille, secteur, budget ni différencier PME vs grande entreprise.
- Piste d'amélioration : Ajouter une description chiffrée du contexte (taille, secteur, budget) et expliquer comment la recommandation divergerait pour une PME vs une grande entreprise.

**Justification criteres**
- Observation : Aucune grille de sélection ni justification pour les critères impact, faisabilité, risque et coût n'est fournie pour les agents.
- Piste d'amélioration : Présenter une matrice avec les trois agents et donner pour chaque cellule une justification factuelle ou une hypothèse vérifiable couvrant impact, faisabilité, risque et coût.

**Role specialise identifie**
- Observation : Le rôle est nommé clairement comme « Agent de service client » et lié à la fonction du service à la clientèle.
- Piste d'amélioration : Préciser en langage métier un exemple concret (ex. : « répond aux demandes de remboursement rapides ») et distinguer explicitement un agent spécialisé d'un agent généraliste.

**Recommandation argumentee**
- Observation : Le texte suggère de conserver l'intervention humaine pour les cas à plus forte valeur mais ne formule pas une recommandation claire par contexte ni n'expose les compromis avec les options rejetées.
- Piste d'amélioration : Formuler une recommandation finale distincte pour PME vs grande entreprise, en expliquant pourquoi les autres options ont été écartées (compromis valeur/risque/coût).

**Role specialise**
- Observation : Le brief indique que l'agent est équivalent à 700 employés humains, impliquant qu'il remplace/augmente des agents du service client.
- Piste d'amélioration : Décrire précisément quelles tâches humaines sont remplacées ou augmentées, et expliquer pourquoi ce rôle est stratégique pour l'organisation (ex. : réduction du temps de réponse, maintien de la satisfaction client).

**Probleme affaires**
- Observation : Le problème est formulé clairement: « temps de traitement des demandes de service à la clientèle trop élevés » et besoin d'augmenter le nombre de demandes traitées efficacement.
- Piste d'amélioration : Condenser en 1–2 phrases et ajouter, si possible, un indicateur de départ (ex. : volume de demandes/jour ou SLA actuel) pour mieux cadrer l'enjeu.

**Valeur creee**
- Observation : Le brief fournit des chiffres concrets: équivalent à 700 employés, temps moyen par demande réduit de 11 à 2 minutes (≈81 %) et réduction des erreurs de 25 %.
- Piste d'amélioration : Citer la source publique pour ces chiffres et relier la valeur à métriques business (ex. : économies annuelles ou amélioration du taux de satisfaction client).

**Risque mitigation**
- Observation : Le risque principal identifié est la dégradation de la qualité du service et la mitigation proposée est le renvoi partiel vers le personnel humain pour les cas à forte valeur.
- Piste d'amélioration : Rendre la mitigation plus concrète (ex. : définir un seuil d'escalade, procédures d'audit qualité trimestriel et indicateurs de surveillance).

**Condition succes**
- Observation : La condition indiquée est de conserver l'assistance humaine pour les cas de haute valeur et n'utiliser l'agent que pour les cas rapides et moins critiques.
- Piste d'amélioration : Formuler une condition de succès mesurable et temporelle (ex. : adoption ≥ 70 % sur les requêtes < 5 min en 6 mois, ou réduction des escalades de X %).

**Ai disclosure**
- Observation : Le document rappelle de mettre à jour ai-usage.md mais ne confirme ni son contenu ni les outils utilisés.
- Piste d'amélioration : Inclure un fichier ai-usage.md mentionnant les outils utilisés (ou « aucun »), l'étape d'utilisation, la validation humaine et les limites observées.

## 3. Déclaration d'utilisation de l'IA

> La déclaration nomme l'outil et décrit précisément l'étape où l'IA a aidé ainsi que la vérification humaine effectuée. Il manque toutefois la version/modèle de l'outil et aucune limite ou erreur constatée n'est documentée.

**Sujets bien couverts dans votre déclaration :**

- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- outils utilisés (nom + version/modèle)
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Compléter `ai-usage.md` en y ajoutant : outils utilisés (nom + version/modèle).
- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260528T200936Z-acdfcf6a`
- **Devoir :** `S01`
- **Étudiant·e :** `CatherineAgnelli`
- **Commit analysé :** `be82ea1`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T200936Z-acdfcf6a/CatherineAgnelli/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
