# Rétroaction automatisée -- S01 (L'IA générative et l'ère agentique : orchestrer des experts sans en être un)

_Générée le 2026-05-28T18:01:52+00:00 -- Run `20260528T180023Z-d01c8d01`_

Ce document est produit par un pipeline reproductible (vérification SQL déterministe + analyse LLM du brief et de la déclaration IA). Une revue humaine précède toujours sa publication. **À ce stade expérimental, aucune note ni étiquette de niveau n'est diffusée : l'objectif est purement formatif.**

---

## 1. Vérification automatique de la requête SQL

La vérification automatique n'a pas pu être réalisée (gate non applicable (type=text_artifact, must_run=False)).


## 2. Rétroaction pédagogique sur le brief

> Le brief identifie clairement le problème d'affaires et présente des chiffres quantifiés de valeur créee, ainsi qu'une mitigation pragmatique (retour humain pour cas sensibles). Cependant il manque le contexte organisationnel différencié, une grille de justification complète et des recommandations formalisées liées aux scores.

### Observations par dimension

**Contexte organisationnel**
- Observation : Le brief ne précise ni taille, ni budget, ni secteur de Klarna pour différencier PME vs grande entreprise.
- Piste d'amélioration : Ajouter une description chiffrée du contexte (taille, secteur, budget) et fournir une recommandation distincte pour PME et grande entreprise.

**Justification criteres**
- Observation : Aucune grille avec impact, faisabilité, risque et coût pour les agents n'est fournie dans le document.
- Piste d'amélioration : Fournir une matrice pour les trois agents avec une justification factuelle ou une hypothèse vérifiable pour chaque critère.

**Role specialise identifie**
- Observation : Le rôle est nommé « Agent de service client », ce qui est exprimé en langage métier.
- Piste d'amélioration : Illustrer la distinction spécialisé vs généraliste par un exemple concret (ex. tâches précises prises en charge) et préciser la valeur métier créée.

**Recommandation argumentee**
- Observation : L'auteur indique qu'il est « idéal de ne pas éliminer complètement le service humain » mais n'expose pas clairement le compromis entre options.
- Piste d'amélioration : Formuler une recommandation distincte par contexte, liée aux scores de la grille, et expliquer pourquoi les autres options ont été écartées.

**Role specialise**
- Observation : Le rôle est identifié comme « Agent de service client » et il est suggéré de renvoyer certains cas au personnel humain.
- Piste d'amélioration : Préciser quel expert humain est remplacé ou augmenté (ex. : agents de support niveau 1) et pourquoi ce remplacement est stratégique pour l'organisation.

**Probleme affaires**
- Observation : Le problème est formulé : « temps de traitement des demandes de service à la clientèle trop élevés » et besoin de répondre à plus de demandes efficacement.
- Piste d'amélioration : Ajouter un ancrage chiffré ou un KPI (ex. nombre de requêtes/jour, délai moyen cible) pour rendre le problème mesurable pour un comité exécutif.

**Valeur creee**
- Observation : Le brief indique l'équivalent de 700 employés, un temps moyen passant de 11 à 2 minutes (~81% de réduction) et une baisse des erreurs de 25%.
- Piste d'amélioration : Citer la source publique pour ces chiffres et expliquer brièvement comment ces gains se traduisent en économies ou en revenus pour l'organisation.

**Risque mitigation**
- Observation : Le risque principal identifié est la dégradation de la qualité du service et la mitigation proposée est un retour partiel au personnel humain pour les cas à forte valeur.
- Piste d'amélioration : Rendre la mitigation actionnable en précisant les seuils déclencheurs, les métriques de qualité à surveiller et la gouvernance de bascule vers l'humain.

**Condition succes**
- Observation : La condition de succès indiquée est de ne pas éliminer complètement le service humain et d'utiliser l'agent pour les cas de moindre valeur.
- Piste d'amélioration : Définir un indicateur observable et un horizon (ex. : taux d'escalade < 10% et adoption utilisateur > 80% en 6 mois).

**Ai disclosure**
- Observation : Le document rappelle : « mettez a jour ai-usage.md » mais ne précise si des outils IA ont été utilisés ni les éléments requis.
- Piste d'amélioration : Inclure ou attacher un ai-usage.md indiquant les outils utilisés (ou « aucun »), l'étape d'utilisation, la validation humaine et les limites observées.

## 3. Déclaration d'utilisation de l'IA

> La déclaration précise l'outil utilisé et l'étape où l'IA a aidé, et indique comment les chiffres ont été vérifiés. Il manque toutefois une mention des limites ou erreurs observées, et le modèle/la version de l'outil n'est pas fournie.

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

- **Run ID :** `20260528T180023Z-d01c8d01`
- **Devoir :** `S01`
- **Étudiant·e :** `CatherineAgnelli`
- **Commit analysé :** `b009361`
- **Audit (côté instructeur) :** `tools/instructor/feedback_pipeline/audit/20260528T180023Z-d01c8d01/CatherineAgnelli/`
- **Prompts (SHA-256) :**
  - `rubric_grader_system` : `505f32d1d8319d66...`
  - `ai_usage_grader_system` : `81cb7fdf89bda55a...`
- **Fournisseur (rubrique) :** `openai`
- **Fournisseur (IA-usage) :** `openai` (gpt-5-mini-2025-08-07)

_Ce feedback a été produit par un pipeline automatisé et **revu par l'équipe pédagogique avant publication**. Aucun chiffre ni étiquette de niveau n'est diffusé à ce stade expérimental : l'objectif est uniquement formatif. Ouvrez une issue dans ce dépôt pour toute question._
