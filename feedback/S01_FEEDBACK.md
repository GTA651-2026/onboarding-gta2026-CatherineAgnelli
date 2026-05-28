# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T20:46:40+00:00 -- Run `20260528T204526Z-4170164e`_

Ce document est produit par un pipeline reproductible (validation automatique du livrable + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Rétroaction pédagogique sur le brief

> Le brief identifie clairement le problème d'efficacité du service client et fournit des chiffres convaincants sur la valeur créée. Cependant il manque une différenciation organisationnelle, une grille de justification détaillée et des conditions/indicateurs mesurables pour appuyer la recommandation devant un comité de direction.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief ne précise ni la taille, ni le secteur, ni le budget et n'offre aucune différenciation PME vs grande entreprise.
- Piste d'amélioration : Ajouter deux profils distincts (PME et grande entreprise) avec taille, secteur et budget estimés, puis expliquer comment la recommandation diffère pour chacun.

**Justification criteres**
- Observation : La grille de critères (impact, faisabilité, risque, coût) et les justifications pour chaque agent sont absentes du document.
- Piste d'amélioration : Compléter une grille pour les trois agents en justifiant chaque cellule par une donnée chiffrée ou une hypothèse vérifiable pour les quatre critères.

**Role specialise identifie**
- Observation : Le document identifie clairement 'Agent de service client' comme rôle orchestré, en langage métier.
- Piste d'amélioration : Préciser au moins un exemple concret illustrant la distinction entre cet agent spécialisé et un agent généraliste (ex. : types de tâches prises en charge).

**Recommandation argumentee**
- Observation : Le texte suggère de ne pas éliminer le service humain pour les cas de haute valeur mais n'expose pas formellement un compromis ni pourquoi d'autres options sont écartées.
- Piste d'amélioration : Formuler une recommandation explicite par contexte (PME vs grande entreprise) et expliquer pourquoi les autres options ont été rejetées en termes de valeur et risque.

**Role specialise**
- Observation : Le rôle est nommé 'Agent de service client' mais l'auteur n'explique quel expert humain il remplace ou augmente ni pourquoi ce rôle est stratégique.
- Piste d'amélioration : Décrire quel poste humain est remplacé/augmenté (ex. : opérateur support niveau 1) et argumenter pourquoi ce rôle est stratégique pour l'organisation.

**Probleme affaires**
- Observation : Le problème identifié est le temps de traitement des demandes de service client trop élevés et le besoin de répondre à plus de demandes efficacement.
- Piste d'amélioration : Ajouter un ancrage chiffré (volume de demandes, SLA manquants, coût horaire) pour rendre le problème directement mesurable par la direction.

**Valeur creee**
- Observation : La valeur est quantifiée: équivalent à 700 employés, temps par demande réduit de 11 à 2 minutes (~81%) et erreurs réduites de 25%.
- Piste d'amélioration : Citer la source publique de ces chiffres et préciser la période/condition de mesure pour rendre la valeur vérifiable.

**Risque mitigation**
- Observation : Le risque principal identifié est la dégradation de la qualité; la mitigation proposée est de rediriger vers le personnel humain les cas à forte valeur.
- Piste d'amélioration : Ajouter des mesures concrètes de suivi (indicateurs, seuils d'alerte, audits périodiques) et une procédure d'escalade formalisée.

**Condition succes**
- Observation : La condition énoncée est de ne pas éliminer le service humain et d'utiliser l'agent pour cas rapides et de moindre valeur, sans indicateur mesurable.
- Piste d'amélioration : Formuler une condition observable (ex. : taux d'escalade < X%, adoption > Y% en 6 mois, réduction du temps moyen de traitement de Z%).

**Ai disclosure**
- Observation : Le brief inclut un rappel de mettre à jour ai-usage.md mais ne fournit pas d'information sur la présence ou le contenu de ce fichier.
- Piste d'amélioration : Ajouter un fichier ai-usage.md indiquant les outils utilisés (ou 'aucun'), l'étape d'utilisation, la validation humaine et les limites observées.

## 2. Déclaration d'utilisation de l'IA

> La déclaration indique l'outil utilisé et la tâche aidée, et vous signalez des vérifications humaines des chiffres. Il manque toutefois une mention explicite des limites ou des erreurs observées, et l'outil n'est pas précisé avec une version/modèle.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)
- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- limites ou erreurs observées

## 3. Pistes d'action pour la prochaine itération

- Compléter i-usage.md en y ajoutant : limites ou erreurs observées.

---

## 4. Traçabilité

- **Run ID :** `20260528T204526Z-4170164e`
- **Devoir :** `S01`
- **Étudiant·e :** `CatherineAgnelli`
- **Commit analysé :** `4412cbb`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T204526Z-4170164e/CatherineAgnelli/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
