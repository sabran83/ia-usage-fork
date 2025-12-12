# PROTOCOLE OPEN-OBJET (Open Evaluation Protocol for Normative Objects)

## Objectif
Rendre l’évaluation des objets (physiques, sociaux, algorithmiques) participative, transparente, itérative et vérifiable par n’importe quel collectif.

---

## Principe 1 : Évaluation distribuée (peer-to-peer)
- **Pas d’instance unique** : chaque communauté (Repair Café, université, association, entreprise) peut mener une évaluation OPEN-OBJET.
- **Interopérabilité** : les évaluations sont publiées au format standard (JSON-LD) sur un dépôt décentralisé (IPFS + Git).
- **Réputation des évaluateurs** : les évaluateurs sont notés par la communauté selon compétence technique, indépendance, diversité (équipe ≥ 3 disciplines).

---

# Protocole OPEN-OBJET – Version 3.0 

## 🎯 Objectif
Accréditer un objet, un service ou un corpus (ex. : Code fiscal américain) selon les 5 critères OPEN-OBJET et 25 sous-critères détaillés, pour obtenir un score sur 100 points.

---

## Principe 1 : Évaluation citoyenne
Chaque objet est évalué par au moins un citoyen, avec justification factuelle. Les scores reflètent l’accessibilité, l’utilité et la gouvernabilité de l’objet.

---

## Principe 2 : Grille détaillée (version 3.0 – 25 sous-critères / 100 points)

### **Critère U – Utilité réelle (0-20 pts, 5 sous-critères × 4 pts)**
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Pertinence fonctionnelle | Analyse fonctionnelle | L’objet répond à un besoin fondamental et documenté | Besoin partiellement documenté | Usage artificiel ou inutile |
| Impact réel | Observation / données | Bénéfices tangibles et mesurables | Bénéfices partiels ou indirects | Aucun bénéfice réel |
| Usage effectif | Statistiques / enquêtes | Utilisé régulièrement par le public cible | Usage irrégulier ou limité | Non utilisé ou usage imposé |
| Accessibilité | Test utilisateurs | Facile à comprendre et à utiliser par un non-expert | Compréhension partielle | Trop complexe ou inaccessible |
| Documentation | Guides, manuels, jurisprudence | Documentation complète, compréhensible et à jour | Documentation partielle ou partiellement lisible | Documentation absente ou incompréhensible |

### **Critère CE – Complexité Encapsulée (0-20 pts, 5 sous-critères × 4 pts)**
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Documentation technique | Lecture et tests par profils variés | Documentation complète et compréhensible | Partiellement accessible | Incompréhensible ou inexistante |
| Modularité / ouverture | Analyse composants | >5 composants indépendants et modifiables | 2-5 composants modifiables | Monolithique, non modifiable |
| Auditabilité | Test de reproduction / contrôle | Audit complet possible en <1h par expert | Audit possible mais long (1-8h) | Impossible à auditer |
| Politisation / encapsulation cachée | Observation / analyse | Pas de règles cachées, transparence totale | Transparence partielle | Verrouillage opaque ou règles cachées |
| Robustesse / simplicité | Test usage / stress | Objet stable, fiable et cohérent | Stable mais complexe | Instable ou incohérent |

### **Critère TA – Transparence Auditable (0-20 pts, 5 sous-critères × 4 pts)**
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Documentation claire | Guides, schémas, exemples | Documentation simple et compréhensible | Partiellement claire | Incompréhensible |
| Normes ou standards | Vérification légale ou technique | Conformes et publiés | Partiellement respectés | Non conformes ou absents |
| Lisibilité des décisions | Analyse décisions / rapports | Décisions accessibles et compréhensibles | Décisions partiellement lisibles | Décisions opaques |
| Communication externe | Sites, rapports, publications | Exposition claire et régulière | Communication irrégulière | Non communiqué |
| Accessibilité collective | Statistiques usage / diffusion | Large diffusion et enseignement | Diffusion limitée | Diffusion quasi nulle |

### **Critère R – Réparabilité (0-20 pts, 5 sous-critères × 4 pts)**
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Correctibilité | Possibilité d’amendement ou réparation | Réparable facilement et rapidement | Réparable avec délai ou expert | Non réparable |
| Adaptabilité | Flexibilité / options | Adaptable à différents contextes | Adaptabilité limitée | Non adaptable |
| Documentation de réparation | Guides, tutoriels, support | >10 tutos ou guides complets | 1-10 guides disponibles | Aucun guide |
| Communauté / support | Forums, experts, pairs | Communauté active et accessible | Support limité | Aucun support |
| Continuité / maintenance | Suivi / mise à jour | Maintenance régulière et planifiée | Mise à jour irrégulière | Pas de maintenance |

### **Critère CO – Contestabilité (0-20 pts, 5 sous-critères × 4 pts)**
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Exit possible | Possibilité de quitter / remplacer l’objet | Migration ou sortie simple <1 jour | Sortie possible mais complexe | Verrouillage complet |
| Recours humain | Délais de réponse et recours | <24h ou procédure simple | 24h-7j | >7j ou inexistant |
| Communauté critique | Feedback, forks, issues | >100 contributions/an | 10-100 | <10 ou aucun |
| Participation citoyenne | Actions directes | Participation directe possible | Participation indirecte ou limitée | Participation impossible |
| Alternatives / substituts | Possibilité de substituer | Alternatives multiples et accessibles | Alternatives limitées | Aucune alternative |

---

## Principe 3 : Notation et couleurs
- Chaque sous-critère est noté sur 0-4 pts  
- Couleurs pour visualisation rapide :  
  - 🟢 = 3-4 pts  
  - 🟡 = 1-2 pts  
  - 🔴 = 0 pts  
- Score total = somme des 25 sous-critères (0-100)

---

## Principe 4 : Preuves et justification
Chaque score doit être accompagné d’une **preuve ou justification** factuelle (ex. publications officielles, guides, tutoriels, observations).  
Les notes sont publiques pour garantir transparence.

---

## Principe 5 : Recommandations
Après évaluation, formuler des recommandations concrètes pour :
- Augmenter l’utilité et l’autonomie citoyenne  
- Améliorer la transparence et l’auditabilité  
- Renforcer la réparabilité et la contestabilité

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
