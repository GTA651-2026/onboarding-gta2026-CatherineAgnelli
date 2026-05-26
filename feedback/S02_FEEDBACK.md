# Rétroaction automatisée -- S02 (Sélectionner des solutions IA : décision, opérations, productivité)

_Générée le 2026-05-26T14:09:19+00:00 -- Run `20260526T140803Z-ec457158`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief propose des recommandations claires pour deux tailles d'entreprise et compare des options par critères. Cependant il manque complètement le modèle dimensionnel, les vérifications techniques et la traçabilité requises pour production.

### Observations par dimension

**Model quality**
- Observation : Le document contient des recommandations produit mais aucun schéma dimensionnel, grain, ni tables déclarées.
- Piste d'amélioration : Fournir un schéma dimensionnel (schéma étoile/constellation), préciser le grain et lister les dimensions et faits clés.

**Validation quality**
- Observation : Aucune requête SQL ou script de vérification n'est présenté pour valider les résultats ou traiter les cas limites.
- Piste d'amélioration : Ajouter des requêtes de validation reproductibles qui montrent que la question CEO est répondue et traitent les NULLs et cas limites.

**Executive justification**
- Observation : Recommandation: Pour une PME de moins de 50 employés, je crois que Copilot 365 est une bonne option... Pour une grande entreprise de plus de 500 employés, je crois que Salesforce Einstein est la meilleure option.
- Piste d'amélioration : Formuler une recommandation décisionnelle concise (p.ex. 'Choisir X pour <cas>, budget attendu et KPI d'impact') et ajouter chiffres synthétiques d'impact et de coût.

**Process trace**
- Observation : Aucune mention d'historique git, ni note d'utilisation d'IA ou journal de décision visible dans le brief.
- Piste d'amélioration : Inclure un log de commits significatifs, une note IA décrivant outils et validations humaines, et un decision log lié au choix final.

**Reproducibility**
- Observation : Aucun artefact, script ou instruction reproduisible (README, DuckDB, chemins) n'est fourni.
- Piste d'amélioration : Fournir un dépôt clonable avec scripts/jeux d'exemple et instructions claires pour reproduire l'analyse en moins de 5 minutes.

## 3. Déclaration d'utilisation de l'IA

> La déclaration indique l'outil utilisé et décrit l'étape où l'IA a aidé, ainsi que la vérification des chiffres par l'étudiant. Il manque toutefois la mention précise du modèle/version de l'outil et aucune limite ou erreur observée n'est décrite.

**Sujets bien couverts dans votre déclaration :**

- à quelle étape l'IA a été utilisée
- comment la sortie a été validée par l'humain

**Sujets à ajouter ou expliciter pour la prochaine itération :**

- outils utilisés (nom + version/modèle)
- limites ou erreurs observées

## 4. Pistes d'action pour la prochaine itération

- Compléter `ai-usage.md` en y ajoutant : limites ou erreurs observées.

---

## 5. Traçabilité

- **Run ID :** `20260526T140803Z-ec457158`
- **Devoir :** `S02`
- **Étudiant·e :** `CatherineAgnelli`
- **Commit analysé :** `9bd5956`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260526T140803Z-ec457158/CatherineAgnelli/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
