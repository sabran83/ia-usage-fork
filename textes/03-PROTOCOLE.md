# PROTOCOLE D’ÉVALUATION OPEN-OBJET (Procédure pratique)

**Durée :** 7 semaines  
**Objectif :** produire un rapport public, vérifiable et reproductible.  
**Format final :** JSON-LD publié sur IPFS (stockage décentralisé).

> Ce document décrit **la procédure pratique** pour réaliser une évaluation OPEN-OBJET en 7 semaines.  
> Ce **n’est pas** la grille des critères (cette dernière reste séparée). Ici : le mode d’emploi étape par étape.

---

## 🟠 Semaine 1 — Documentation

**But :** rassembler toute la documentation existante et vérifier son accessibilité.

**Actions**
- Collecter : code source, schémas, documents techniques, manuels.
- Vérifier l’accessibilité : lecture à voix haute à un non-expert pour tester la compréhensibilité.

**Livrable**
- Inventaire documentaire complet (PDF/ODT) listant tous les fichiers et leur état.

---

## 🟡 Semaines 2–3 — Tests d’utilisation réelle

**But :** observer l’expérience utilisateur réelle.

**Actions**
- Sélectionner 3 utilisateurs représentatifs.
- Faire des sessions filmées (écran + voix).
- Mesurer :
  - temps d’apprentissage,
  - erreurs,
  - frustration (échelle NASA-TLX).

**Livrables**
- Vidéos brutes des sessions.
- Rapport d’analyse qualitative (difficultés, points bloquants, suggestions).

---

## 🔵 Semaine 4 — Audit technique

**But :** tester robustesse et comportement face à scénarios variés.

**Actions**
- Reproduire l’environnement technique (serveur, données, paramètres).
- Exécuter scénarios de test (contrefactuels / stress) tels que :
  - que se passe-t-il si un utilisateur envoie une valeur anormale ?
  - que se passe-t-il si la connexion Internet coupe 2 secondes ?
  - que se passe-t-il avec un profil extrême ou malicieux ?
- Observer les effets et les points de rupture.

**Livrable**
- Rapport d’audit comportemental (tests, logs, résultats).

---

## 🟩 Semaine 5 — Réparabilité

**But :** mesurer la facilité de diagnostic et de réparation.

**Actions**
- Introduire 3 pannes types :
  - panne logicielle,
  - panne matérielle,
  - erreur utilisateur.
- Mesurer :
  - temps d’identification,
  - temps de réparation,
  - outils nécessaires,
  - coût estimé.

**Livrable**
- Benchmark réparabilité (tableau temps/outils/coûts).

---

## 🟣 Semaine 6 — Contestabilité (recours & sortie)

**But :** vérifier si l’utilisateur peut contester, sortir ou migrer.

**Actions & tests**
1. **Sortie / migration**
   - Peut-on exporter ses données ?
   - Peut-on migrer vers une alternative ?
2. **Recours**
   - Soumettre 5 plaintes (réelles ou simulées) via les canaux disponibles.
   - Mesurer délai et qualité de la réponse.

**Livrable**
- Rapport contestabilité (export, migration, délais de réponse, qualité du recours).

---

## 🔵 Semaine 7 — Publication

**But :** rendre le travail public, vérifiable et infalsifiable.

**Actions**
- Compiler toutes les preuves, vidéos, rapports et mesures.
- Générer un fichier **JSON-LD** conforme au schéma `open-objet.jsonld`.
- Publier le JSON-LD (et les livrables associés) sur **IPFS**.
- Récupérer le **hash IPFS** (empreinte immuable).

**Livrables**
- Rapport final complet.
- Fichier JSON-LD (schéma `open-objet.jsonld`).
- Lien IPFS (hash).
- Score total (0–100) et sommaire des preuves.

---

## 🧩 Exemple de JSON-LD (résumé machine-lisible)

> Le JSON-LD est un **résumé technique** destiné aux outils / chercheurs : il récapitule l’objet, le score, l’évaluateur et le lien IPFS.

```json
{
  "@context": "https://ia-usage-fork.github.io/open-objet.jsonld",
  "@type": "Evaluation",
  "objectName": "YouTube Recommendation",
  "scoreTotal": 0,
  "evaluator": "Citoyen-12345",
  "ipfsHash": "QmT123..."
}

}
