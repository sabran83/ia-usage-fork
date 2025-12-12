# PROTOCOLE OPEN-OBJET (Open Evaluation Protocol for Normative Objects)

## Objectif
Rendre l’évaluation des objets (physiques, sociaux, algorithmiques) participative, transparente, itérative et vérifiable par n’importe quel collectif.

---

## Principe 1 : Évaluation distribuée
- **Pas d’instance unique** : chaque communauté (Repair Café, université, association, entreprise) peut mener une évaluation OPEN-OBJET.
- **Interopérabilité** : les évaluations sont publiées au format standard (JSON-LD) sur un dépôt décentralisé (IPFS + Git).
- **Réputation des évaluateurs** : les évaluateurs sont notés par la communauté selon compétence technique, indépendance et diversité (équipe ≥ 3 disciplines).

---

## Principe 2 : Évaluation citoyenne
Chaque objet est évalué par au moins un citoyen, avec justification factuelle. Les scores reflètent l’accessibilité, l’utilité et la gouvernabilité de l’objet.

---

## Principe 3 : Grille détaillée (25 sous-critères / 100 points)

### Critère U – Utilité réelle (0-20 pts)
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Pertinence fonctionnelle | Analyse fonctionnelle | Répond à un besoin fondamental et documenté | Besoin partiellement documenté | Usage artificiel ou inutile |
| Impact réel | Observation / données | Bénéfices tangibles et mesurables | Bénéfices partiels ou indirects | Aucun bénéfice réel |
| Usage effectif | Statistiques / enquêtes | Utilisé régulièrement par le public cible | Usage irrégulier ou limité | Non utilisé ou usage imposé |
| Accessibilité | Test utilisateurs | Facile à comprendre et à utiliser par un non-expert | Compréhension partielle | Trop complexe ou inaccessible |
| Documentation | Guides, manuels, jurisprudence | Documentation complète et à jour | Documentation partielle | Documentation absente ou incompréhensible |

### Critère CE – Complexité Encapsulée (0-20 pts)
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Documentation technique | Lecture et tests | Documentation complète et compréhensible | Partiellement accessible | Incompréhensible ou inexistante |
| Modularité / ouverture | Analyse composants | >5 composants indépendants et modifiables | 2-5 composants modifiables | Monolithique, non modifiable |
| Auditabilité | Test de reproduction / contrôle | Audit complet possible par expert | Audit possible mais long | Impossible à auditer |
| Politisation / encapsulation cachée | Observation / analyse | Transparence totale | Transparence partielle | Verrouillage opaque ou règles cachées |
| Robustesse / simplicité | Test usage / stress | Objet stable et cohérent | Stable mais complexe | Instable ou incohérent |

### Critère TA – Transparence Auditable (0-20 pts)
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Documentation claire | Guides, schémas, exemples | Simple et compréhensible | Partiellement claire | Incompréhensible |
| Normes ou standards | Vérification légale ou technique | Conformes et publiés | Partiellement respectés | Non conformes ou absents |
| Lisibilité des décisions | Analyse décisions / rapports | Décisions accessibles | Partiellement lisibles | Opaques |
| Communication externe | Sites, rapports, publications | Exposition claire et régulière | Communication irrégulière | Non communiqué |
| Accessibilité collective | Statistiques usage / diffusion | Large diffusion | Diffusion limitée | Diffusion quasi nulle |

### Critère R – Réparabilité (0-20 pts)
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Correctibilité | Amendement ou réparation | Réparable facilement | Réparable avec délai ou expert | Non réparable |
| Adaptabilité | Flexibilité / options | Adaptable à différents contextes | Adaptabilité limitée | Non adaptable |
| Documentation de réparation | Guides, tutoriels, support | >10 guides complets | 1-10 guides | Aucun guide |
| Communauté / support | Forums, experts, pairs | Communauté active | Support limité | Aucun support |
| Continuité / maintenance | Suivi / mise à jour | Maintenance régulière | Mise à jour irrégulière | Pas de maintenance |

### Critère CO – Contestabilité (0-20 pts)
| Sous-critère | Méthode / Preuve | Seuil 4 pts | Seuil 2 pts | Seuil 0 pts |
|-------------|-----------------|------------|------------|------------|
| Exit possible | Quitter / remplacer l’objet | Sortie simple <1 jour | Sortie possible mais complexe | Verrouillage complet |
| Recours humain | Délais de réponse et recours | <24h ou procédure simple | 24h-7j | >7j ou inexistant |
| Communauté critique | Feedback, forks, issues | >100 contributions/an | 10-100 | <10 ou aucun |
| Participation citoyenne | Actions directes | Participation directe possible | Participation indirecte | Participation impossible |
| Alternatives / substituts | Possibilité de substituer | Alternatives multiples et accessibles | Alternatives limitées | Aucune alternative |

---

## Principe 4 : Notation et couleurs
- Chaque sous-critère est noté sur 0-4 pts  
- Couleurs pour visualisation rapide :  
  - 🟢 = 3-4 pts  
  - 🟡 = 1-2 pts  
  - 🔴 = 0 pts  
- **Score total = somme des 25 sous-critères (0-100 pts)**

---

## Principe 5 : Preuves et justification
Chaque score doit être accompagné d’une **preuve ou justification** factuelle (publications officielles, guides, tutoriels, observations).  
Les notes sont publiques pour garantir la transparence.

---

## Principe 6 : Recommandations
Après évaluation, formuler des recommandations concrètes pour :  
- Augmenter l’utilité et l’autonomie citoyenne  
- Améliorer la transparence et l’auditabilité  
- Renforcer la réparabilité et la contestabilité

---

## ÉVALUATION OPEN-OBJET : Algorithme de recommandation YouTube
**Objet** : Algorithme de recommandation vidéo  
**Date** : 08/12/2025  
**Évaluateur** : Citoyen-12345 (public)  

| Critère / Sous-critère | Score /4 | Détail / Justification |
|------------------------|----------|----------------------|
| **U – Utilité réelle** | **0/20 🔴** | Usage addictif, peu pertinent pour éducation ou information. |
| **CE – Complexité Encapsulée** | **0/20 🔴** | Code opaque, impossible à auditer ou modifier. |
| **TA – Transparence Auditable** | **0/20 🔴** | Documentation inexistante, décisions opaques. |
| **R – Réparabilité** | **0/20 🔴** | Non réparable ou adaptable par le public. |
| **CO – Contestabilité** | **0/20 🔴** | Impossible à contester ou substituer. |

| **TOTAL (100)** | **0/100 🔴** | Algorithme opaque, non transparent et non contestable. |




