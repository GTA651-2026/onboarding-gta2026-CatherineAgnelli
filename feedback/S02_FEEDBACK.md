# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-28T17:19:48+00:00 -- Run `20260528T171846Z-876e9e4f`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le bref présente une comparaison structurée entre PME et grande entreprise avec une grille de critères et des recommandations contextuelles. Il gagnerait à enrichir les justifications par des chiffres/assomptions vérifiables et à fournir la déclaration d'usage d'IA manquante.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le document présente clairement deux scénarios (PME 50 employés et 500+ employés) et donne des recommandations distinctes pour chaque contexte.
- Piste d'amélioration : Préciser le secteur d'activité et un ordre de grandeur de budget pour chaque scénario afin de mieux justifier les différences de recommandation.

**Justification criteres**
- Observation : La grille liste impact, faisabilité, coût et risque pour chaque agent et offre des justifications concises (par ex. «si la suite 365 est déjà utilisée, la faisabilité est à 5/5»).
- Piste d'amélioration : Développer les justifications avec chiffres ou hypothèses vérifiables (coûts estimés chiffrés, métriques d'impact) et combler les justifications vagues.

**Role specialise identifie**
- Observation : Les rôles sont nommés en termes métier: «Gestion financière automatisée», «Agent CRM de vente et service client», «Assistant généralisé».
- Piste d'amélioration : Ajouter un exemple concret par rôle montrant une tâche métier réalisée et la valeur mesurable (ex. réduction du délai de clôture, taux de conversion).

**Recommandation argumentee**
- Observation : Il y a une recommandation claire par contexte (Copilot pour la PME; Salesforce Einstein pour la grande entreprise) avec raisons liées à intégration et impact.
- Piste d'amélioration : Expliciter le compromis entre options (parquoi une option est écartée) et articuler les risques et gains quantifiés pour convaincre un comité de direction.

**Ai disclosure**
- Observation : Aucun fichier ai-usage.md mentionné ni renseigné dans le brief.
- Piste d'amélioration : Fournir un ai-usage.md indiquant les outils IA utilisés (ou «aucun»), l'étape d'utilisation, la validation humaine et les limites identifiées.

## 3. Déclaration d'utilisation de l'IA

> La déclaration indique l'outil utilisé et précise la tâche où l'IA a aidé, ainsi que la vérification des chiffres. En revanche, il manque la version/modèle exact de l'outil et aucune limite ou erreur observée n'est décrite.

**Sujets bien couverts dans votre déclaration :**

- outils utilisés (nom + version/modèle)
- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260528T171846Z-876e9e4f`
- **Devoir :** `S02`
- **Étudiant·e :** `CatherineAgnelli`
- **Commit analysé :** `1e568b4`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T171846Z-876e9e4f/CatherineAgnelli/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
