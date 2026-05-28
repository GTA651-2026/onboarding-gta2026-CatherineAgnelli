# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-28T17:27:59+00:00 -- Run `20260528T172647Z-afdf4262`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief distingue clairement deux tailles d'organisation et propose des recommandations cohérentes avec la grille de critères, mais les justifications restent souvent générales. Pour être défendable en comité, ajoutez des données chiffrées, un budget/secteur par scénario et un ai-usage.md complet.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief présente deux scénarios («Scénario 1: PME 50 employés» et «Scénario 2: 500+ employés») et adapte la recommandation selon la taille.
- Piste d'amélioration : Préciser pour chaque scénario le secteur d'activité et une estimation de budget pour justifier plus finement les différences de recommandation.

**Justification criteres**
- Observation : La grille donne des scores pour Impact, Faisabilité, Coût et Risque pour chaque agent avec courtes justifications (ex. «4 sur 5, étant donné le manque probable de CFO dans la PME»).
- Piste d'amélioration : Renforcer les justifications par données chiffrées ou hypothèses vérifiables (ex. estimation de coûts, délai d'implantation, indicateurs d'impact) et combler les éléments vagues.

**Role specialise identifie**
- Observation : Les rôles sont nommés en termes métier: «Gestion financière automatisée», «Agent CRM de vente et service client», «Assistant généralisé».
- Piste d'amélioration : Illustrer pour chaque rôle une valeur métier concrète (ex. 'réduction du DSO de X jours', 'augmentation du taux de conversion de Y%').

**Recommandation argumentee**
- Observation : La recommandation finale différencie les contextes: Copilot 365 pour PME <50 et Salesforce Einstein pour entreprise >500, avec brèves raisons liées à intégration et impact.
- Piste d'amélioration : Présenter explicitement le compromis entre options (pourquoi une option est écartée) et résumer les risques et gains attendus pour le comité de direction.

**Ai disclosure**
- Observation : ai-usage.md absent (aucune mention d'utilisation d'IA dans le document).
- Piste d'amélioration : Fournir un fichier ai-usage.md indiquant les outils (ou 'aucun'), les étapes d'utilisation, la validation humaine et les limites observées.

## 3. Déclaration d'utilisation de l'IA

> La déclaration précise l'étape d'utilisation et la vérification des chiffres par l'étudiant·e, mais elle omet une information importante sur l'outil (version/modèle) et ne signale pas de limites ou d'erreurs observées. Veuillez ajouter la version/modèle de ChatGPT utilisé et décrire explicitement les limites ou erreurs rencontrées.

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

- **Run ID :** `20260528T172647Z-afdf4262`
- **Devoir :** `S02`
- **Étudiant·e :** `CatherineAgnelli`
- **Commit analysé :** `bfb7367`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T172647Z-afdf4262/CatherineAgnelli/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
