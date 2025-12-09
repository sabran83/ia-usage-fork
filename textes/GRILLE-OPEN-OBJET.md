# PROTOCOLE OPEN-OBJET (Open Evaluation Protocol for Normative Objects)

## Objectif
Rendre l’évaluation des objets (physiques, sociaux, algorithmiques) participative, transparente, itérative et vérifiable par n’importe quel collectif.

---

## Principe 1 : Évaluation distribuée (peer-to-peer)
- **Pas d’instance unique** : chaque communauté (Repair Café, université, association, entreprise) peut mener une évaluation OPEN-OBJET.
- **Interopérabilité** : les évaluations sont publiées au format standard (JSON-LD) sur un dépôt décentralisé (IPFS + Git).
- **Réputation des évaluateurs** : les évaluateurs sont notés par la communauté selon compétence technique, indépendance, diversité (équipe ≥ 3 disciplines).

---

## Principe 2 : Grille détaillée (version 2.0)

### **Critère U – Utilité réelle (0-2 pts)**
| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| Besoin documenté | Enquête utilisateurs (n≥50) | &gt;70% confirment un besoin pré-existant | 40-70% | &lt;40% |
| Absence d'induction | A/B test vs placebo | &lt;10% d'usage induit | 10-30% | &gt;30% |
| Autonomie gagnée | Mesure temps/effort économisé | &gt;20% gain d'autonomie | 5-20% | &lt;5% ou perte |

### **Critère C – Complexité encapsulée (0-2 pts)**
| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| Documentation accessible | Test lecture par 5 profils (enfant, senior, non-expert) | 4/5 comprennent le schéma | 2-3/5 | &lt;2/5 |
| Audit technique possible | Temps pour reproduire une panne | &lt;1h avec docs | 1-8h | &gt;8h ou impossible |
| Modularité | Nombre de composants indépendants | &gt;5 modules | 2-5 | Monolithique |

### **Critère T – Transparence auditable (0-2 pts)**
| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| Code ouvert | Licence OSI + repo public | Oui, +200 commits/an | Oui, peu actif | Non |
| Explication des décisions | SHAP/LIME/counterfactual | &gt;80% des décisions explicables | 50-80% | &lt;50% |
| Traçabilité des données | Datasheet (Gebru) | Dataset + métadonnées complets | Partiel | Aucun |

### **Critère R – Réparabilité (0-2 pts)**
| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| Pièces disponibles | Nombre de fournisseurs | ≥3 indépendants | 1-2 | 0 |
| Documentation de réparation | Manuel + tutoriels vidéo | &gt;10 tutos communauté | 1-10 | Aucun |
| Temps de réparation | Benchmark par 3 réparateurs | &lt;1h pour panne commune | 1-4h | &gt;4h ou impossible |

### **Critère C – Contestabilité (0-2 pts)**
| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| Exit possible | Standards ouverts | Oui, migration &lt;1 jour | Oui, difficile | Non (verrouillage) |
| Recours humain | Délai réponse | &lt;24h | 24h-7j | &gt;7j ou aucun |
| Communauté critique | Nombre de forks/issues | &gt;100 forks/an | 10-100 | &lt;10 |

---

## Principe 3 : Protocole de test standardisé

**Semaine 1 – Documentation**
- Récupérer code source, schémas, manuels.
- Tester accessibilité : lecture à voix haute à un non-expert.

**Semaine 2-3 – Utilisation**
- 3 utilisateurs réels filment leurs interactions.
- Mesure du temps d’apprentissage, erreurs, frustration (NASA-TLX).

**Semaine 4 – Audit technique**
- Tenter de reproduire l'environnement de test.
- Counterfactual testing : 100 scénarios de bord.
- Adversarial testing : robustesse aux inputs anormaux.

**Semaine 5 – Réparation**
- Introduire 3 pannes standards (logiciel, matériel, erreur utilisateur).
- Mesurer temps d'identification et de correction avec documentation.

**Semaine 6 – Contestation**
- Tester exit : exporter données, migrer vers alternative.
- Tester recours : soumettre 5 plaintes, mesurer délai réponse.

**Semaine 7 – Publication**
- Rédiger évaluation au format JSON-LD (schéma open-objet.jsonld).
- Publier sur dépôt public (IPFS) avec hash unique.

---

## Principe 4 : Calcul du score et label

- **Score total** : somme des 5 critères (0-10)
- **Label communautaire** :
  - 🟢 **Bon objet** : ≥7/10
  - 🟠 **Objet limite** : 4-6/10
  - 🔴 **Mauvais objet** : ≤3/10
- **Validité** : 2 ans, puis ré-évaluation obligatoire
- **Contestabilité** : quiconque peut forker une évaluation et la contester

---

## Principe 5 : Gouvernance du protocole

- **Comité d’évolution** : 12 personnes (4 citoyens tirés au sort, 4 experts, 4 réparateurs)
- **Mandat** : 2 ans, renouvelable 1 fois
- **Mission** : amender la grille par consensus (vote majoritaire qualifiée 75%)

---

## Exemple d'application : évaluation YouTube Recommendation

| Critère | Score | Justification |
|---------|-------|---------------|
| **Utilité** | 0/2 | 85% des vues induites (A/B test ProPublica) |
| **Complexité** | 0/2 | Code fermé, infrastructure opaque |
| **Transparence** | 0/2 | &lt;5% décisions explicables (SHAP impossible) |
| **Réparabilité** | 0/2 | Aucune pièce, aucun manuel public |
| **Contestabilité** | 0/2 | Exit impossible (verrou écosystème) |
| **TOTAL** | **0/10** | **🔴 MAUVAIS OBJET** |

---

**Engagez-vous directement dans le principal**
