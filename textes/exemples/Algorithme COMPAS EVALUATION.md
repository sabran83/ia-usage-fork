# ÉVALUATION OPEN-OBJET : Algorithme COMPAS
**Objet** : Logiciel d’évaluation du risque de récidive  
**Date** : 08/12/2025  
**Évaluateur** : Citoyen-24680 (public)  

## Score par critère détaillé (sur 20 points)

| Critère / Score | Score | Détail / Justification | Preuve / Exemple |
|-----------------|-------|----------------------|----------------|
| **U – Utilité réelle (4)** | 2/4 🟡 | Aide à la décision judiciaire mais biais documentés : l’outil n’améliore pas objectivement la justice et peut induire des erreurs. | Études ProPublica |
| **CE – Complexité Encapsulée (4 sous-critères ×1 = 4)** | 0/4 🔴 | **1. Documentation technique** : absente → 0<br>**2. Modularité / ouverture** : code fermé, pas modulaire → 0<br>**3. Auditabilité** : impossible de tester sans risquer d’erreur → 0<br>**4. Politisation / encapsulation cachée** : CE=0 immédiat car code opaque et logique cachée. | Code propriétaire, NDA |
| **TA – Transparence Auditable (4)** | 0/4 🔴 | Décisions non explicables, documentation insuffisante pour un public ou collectif non expert. | Rapports critiques |
| **R – Réparabilité (4)** | 0/4 🔴 | Pas de manuel public, pas d’accès au code, impossibilité de corriger ou d’adapter l’outil. | N/A |
| **CO – Contestabilité (4)** | 0/4 🔴 | Contestation impossible sans accès interne ; l’utilisateur / juge ne peut pas remettre en cause l’algorithme. | Cas judiciaires |
| **TOTAL (20)** | 2/20 🔴 | Objet très opaque, non gouvernable, dépendance forte → MAUVAIS OBJET |  |

---

💡 **Notes :**  
- CE est détaillé en 4 sous-critères pour rendre plus visible la répartition : documentation, modularité, auditabilité et politisation.  
- Politisation / encapsulation cachée = CE=0 immédiat, même si d’autres sous-critères semblaient partiellement bons.  
- Les autres critères (U, TA, R, CO) sont sur 4 points pour un total de 20, plus intuitif pour le public.
