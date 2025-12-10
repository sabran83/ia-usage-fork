# ÉVALUATION 'OPEN'-OBJET : Algorithme COMPAS
**Objet** : Logiciel d’évaluation du risque de récidive  
**Date** : 08/12/2025  
**Évaluateur** : Citoyen-24680 (public)  

## Score par critère détaillé (25 sous-critères, total 100 points)

| Critère / Sous-critère | Score /4 | Détail / Justification |
|------------------------|----------|----------------------|
| **U – Utilité réelle** |          |                        |
| 1. Pertinence sociale  | 1/4 🟡   | Aide à la décision judiciaire mais biais documentés |
| 2. Impact réel         | 0/4 🔴   | Ne garantit pas une amélioration objective de la justice |
| 3. Usage effectif      | 1/4 🟡   | Utilisé par certains tribunaux, mais adoption limitée |
| 4. Accessibilité       | 0/4 🔴   | Non accessible au public, opaque pour citoyens et juges |
| 5. Documentation       | 0/4 🔴   | Documentation externe insuffisante pour compréhension complète |
| **CE – Complexité Encapsulée** |          |                        |
| 1. Documentation technique | 0/4 🔴 | Code fermé, aucune documentation technique disponible |
| 2. Modularité / ouverture | 0/4 🔴 | Pas de modularité, tout est monolithique |
| 3. Auditabilité           | 0/4 🔴 | Impossible de tester ou auditer sans risque de brick ou erreur |
| 4. Politisation / encapsulation cachée | 0/4 🔴 | Code opaque, logique cachée → CE=0 immédiat |
| 5. Robustesse logique     | 0/4 🔴 | Aucune vérification indépendante possible, décisions non traçables |
| **TA – Transparence Auditable** |          |                        |
| 1. Documentation claire  | 0/4 🔴 | Rapports non accessibles au grand public |
| 2. Normes ou standards   | 0/4 🔴 | Pas de standard ouvert ni RFC disponible |
| 3. Lisibilité des décisions | 0/4 🔴 | Décisions non explicables pour un collectif |
| 4. Communication externe | 0/4 🔴 | Pas de description claire du fonctionnement externe |
| 5. Accessibilité collective | 0/4 🔴 | Pas de possibilité pour le public de comprendre ou vérifier |
| **R – Réparabilité**     |          |                        |
| 1. Correctibilité       | 0/4 🔴 | Impossibilité de corriger ou modifier le logiciel |
| 2. Adaptabilité         | 0/4 🔴 | Ne peut pas être adapté à différents contextes ou juridictions |
| 3. Documentation aide   | 0/4 🔴 | Aucun guide de réparation ou adaptation fourni |
| 4. Communauté / support | 0/4 🔴 | Pas de communauté ou support public pour ajustements |
| 5. Continuité / maintenance | 0/4 🔴 | Maintenance impossible sans accès au code source |
| **CO – Contestabilité**  |          |                        |
| 1. Remise en cause par experts | 0/4 🔴 | Experts externes ne peuvent pas tester ou vérifier l’outil |
| 2. Possibilité d’appel / recours | 0/4 🔴 | Contestation limitée à des voies judiciaires complexes |
| 3. Transparence des résultats | 0/4 🔴 | Résultats non publics ou traçables |
| 4. Participation citoyenne | 0/4 🔴 | Aucun mécanisme pour l’utilisateur ou le public de contester |
| 5. Alternatives / substituts | 0/4 🔴 | Pas d’alternative ouverte ou auditée disponible |

| **TOTAL** | 2/100 🟥 | Objet très opaque, non gouvernable, dépendance forte → **MAUVAIS OBJET** |

---

💡 **Notes :**  
- Tous les critères principaux sont notés sur **5 sous-critères ×4 points = 20 par critère**  
- Total global = **100 points** pour un score intuitif  
- Couleurs : 🟢 = 3‑4, 🟡 = 1‑2, 🔴 = 0  
- Politisation / encapsulation cachée = CE=0 immédiat → toutes les sous-parties CE bloquées  
- COMPAS est très opaque : aucune transparence, auditabilité ou contestabilité disponible
