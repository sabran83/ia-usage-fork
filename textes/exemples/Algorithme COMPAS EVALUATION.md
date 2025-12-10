# ÉVALUATION OPEN-OBJET : Algorithme COMPAS
**Objet** : Logiciel d’évaluation du risque de récidive  
**Date** : 08/12/2025  
**Évaluateur** : Citoyen-24680 (public)  

## Score par critère détaillé

| Critère / Score | Score | Détail / Justification | Preuve / Exemple |
|-----------------|-------|----------------------|----------------|
| **U – Utilité réelle (2)** | 1/2 🟡 | Aide à la décision judiciaire mais biais documentés : l’outil n’améliore pas objectivement la justice et peut induire des erreurs. | Études ProPublica |
| **CE – Complexité Encapsulée (6)** | 0/6 🔴 | Code fermé, logique opaque, pas de documentation, pas d’audit possible → encapsulation masquée → CE=0. Politisation de l’encapsulation : l’utilisateur / juge ne peut pas comprendre ni contrôler l’algorithme. | Code propriétaire, NDA |
| **TA – Transparence Auditable (2)** | 0/2 🔴 | Décisions non explicables, documentation insuffisante pour un public ou collectif non expert. | Rapports critiques |
| **R – Réparabilité (2)** | 0/2 🔴 | Pas de manuel public, pas d’accès au code, impossibilité de corriger ou d’adapter l’outil. | N/A |
| **CO – Contestabilité (2)** | 0/2 🔴 | Contestation impossible sans accès interne ; l’utilisateur / juge ne peut pas remettre en cause l’algorithme. | Cas judiciaires |
| **TOTAL (14)** | 1/14 🔴 | Objet très opaque, non gouvernable, dépendance forte → MAUVAIS OBJET |  |

---

💡 **Notes :**  
- CE est noté sur 6, car il intègre documentation, modularité et auditabilité.  
- U, TA, R, CO restent sur 2.  
- Politisation / encapsulation cachée = CE=0, même si d’autres critères semblent partiellement bons.  
