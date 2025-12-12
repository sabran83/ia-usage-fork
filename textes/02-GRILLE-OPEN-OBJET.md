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

# ÉVALUATION "OPEN"-OBJET : Algorithme de recommandation YouTube
**Objet** : Algorithme de recommandation vidéo  
**Date** : 08/12/2025  
**Évaluateur** : Citoyen-12345 (public)  

## Score par critère détaillé (25 sous-critères, total 100 points)

| Critère / Sous-critère | Score /4 | Détail / Justification |
|------------------------|----------|----------------------|
| **U – Utilité réelle (Total 20)** | **0/20 🔴** | |
| 1. Pertinence fonctionnelle | 0/4 🔴 | Recommande majoritairement des vidéos addictives, non pertinentes pour l’éducation ou l’information. |
| 2. Impact réel | 0/4 🔴 | 85% des vues induites selon tests A/B (ProPublica) ; influence disproportionnée sur consommation et opinions. |
| 3. Usage effectif | 0/4 🔴 | Usage massif mais orienté vers la captation de l’attention, pas vers un bénéfice utilisateur réel. |
| 4. Accessibilité | 0/4 🔴 | Code fermé, aucune documentation accessible au public. |
| 5. Documentation | 0/4 🔴 | Aucun manuel ou guide explicatif public. |
| **CE – Complexité Encapsulée (Total 20)** | **0/20 🔴** | |
| 1. Documentation technique | 0/4 🔴 | Code fermé, infrastructure opaque. |
| 2. Modularité / ouverture | 0/4 🔴 | Impossible d’adapter ou modifier l’algorithme pour l’utilisateur ou la communauté. |
| 3. Auditabilité | 0/4 🔴 | Aucune possibilité de vérifier ou auditer le fonctionnement réel. |
| 4. Politisation / encapsulation cachée | 0/4 🔴 | Algorithme opaque, décisions internes non auditable, biais potentiellement cachés. |
| 5. Robustesse / simplicité | 0/4 🔴 | Extrêmement complexe, non documenté, impossible à comprendre pour le citoyen. |
| **TA – Transparence Auditable (Total 20)** | **0/20 🔴** | |
| 1. Documentation claire | 0/4 🔴 | Aucune documentation publique. |
| 2. Normes ou standards | 0/4 🔴 | Aucun standard externe accessible ou applicable. |
| 3. Lisibilité des décisions | 0/4 🔴 | Moins de 5% des décisions explicables ; SHAP impossible. |
| 4. Communication externe | 0/4 🔴 | Aucune communication sur le fonctionnement réel de l’algorithme. |
| 5. Accessibilité collective | 0/4 🔴 | Aucun accès collectif pour contrôle citoyen ou recherche indépendante. |
| **R – Réparabilité (Total 20)** | **0/20 🔴** | |
| 1. Correctibilité | 0/4 🔴 | Aucune possibilité de corriger ou ajuster l’algorithme. |
| 2. Adaptabilité | 0/4 🔴 | Infrastructure propriétaire, impossible d’adaptation par tiers. |
| 3. Documentation aide | 0/4 🔴 | Aucun guide pour comprendre ou modifier le système. |
| 4. Communauté / support | 0/4 🔴 | Pas de communauté de support pour réparation ou adaptation. |
| 5. Continuité / maintenance | 0/4 🔴 | Maintenance uniquement interne, non transparente, inaccessible au public. |
| **CO – Contestabilité (Total 20)** | **0/20 🔴** | |
| 1. Remise en cause par experts | 0/4 🔴 | Impossible de contester le fonctionnement exact de l’algorithme. |
| 2. Possibilité d’appel / recours | 0/4 🔴 | Aucun recours pour influencer les recommandations ou décisions. |
| 3. Transparence des résultats | 0/4 🔴 | Décisions internes non publiées, données et modèles opaques. |
| 4. Participation citoyenne | 0/4 🔴 | Aucune participation possible ; utilisateurs entièrement dépendants. |
| 5. Alternatives / substituts | 0/4 🔴 | Impossible de substituer l’algorithme pour les utilisateurs individuels. |

| **TOTAL (100)** | **0/100 🔴** | Algorithme opaque, non transparent, non contestable, utilisation largement nocive et manipulatrice. 

## Recommandation
Retrait immédiat du marché jusqu’à audit complet et publication d’une documentation exhaustive.  
Développer des alternatives transparentes, modulables et explicables pour utilisateurs et chercheurs.

