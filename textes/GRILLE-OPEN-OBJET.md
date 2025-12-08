# GRILLE OPEN-OBJET v1.0
## Protocole d'évaluation des objets techniques, sociaux et algorithmiques

### **Critère U – Utilité réelle (0-2 pts)**

| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| **Besoin documenté** | Enquête utilisateurs (n≥50) | &gt;70% confirment un besoin pré-existant | 40-70% | &lt;40% |
| **Absence d'induction** | A/B test vs placebo | &lt;10% d'usage induit | 10-30% | &gt;30% |
| **Autonomie gagnée** | Mesure temps/effort économisé | &gt;20% gain d'autonomie | 5-20% | &lt;5% ou perte |

---

### **Critère C – Complexité encapsulée (0-2 pts)**

| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| **Documentation accessible** | Test lecture par 5 profils (enfant, senior, non-expert) | 4/5 comprennent le schéma | 2-3/5 | &lt;2/5 |
| **Audit technique possible** | Temps pour reproduire une panne | &lt;1h avec docs | 1-8h | &gt;8h ou impossible |
| **Modularité** | Nombre de composants indépendants | &gt;5 modules | 2-5 | Monolithique |

---

### **Critère T – Transparence auditable (0-2 pts)**

| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| **Code ouvert** | Licence OSI + repo public | Oui, +200 commits/an | Oui, peu actif | Non |
| **Explication des décisions** | SHAP/LIME/counterfactual | &gt;80% des décisions explicables | 50-80% | &lt;50% |
| **Traçabilité des données** | Datasheet (Gebru) | Dataset + métadonnées complets | Partiel | Aucun |

---

### **Critère R – Réparabilité (0-2 pts)**

| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| **Pièces disponibles** | Nombre de fournisseurs | ≥3 indépendants | 1-2 | 0 |
| **Documentation de réparation** | Manuel + tutoriels vidéo | &gt;10 tutos communauté | 1-10 | Aucun |
| **Temps de réparation** | Benchmark par 3 réparateurs | &lt;1h pour panne commune | 1-4h | &gt;4h ou impossible |

---

### **Critère C – Contestabilité (0-2 pts)**

| Indicateur | Méthode | Seuil 2 pts | Seuil 1 pt | Seuil 0 pt |
|------------|---------|-------------|------------|------------|
| **Exit possible** | Standards ouverts | Oui, migration &lt;1 jour | Oui, difficile | Non (verrouillage) |
| **Recours humain** | Délai réponse | &lt;24h | 24h-7j | &gt;7j ou aucun |
| **Communauté critique** | Nombre de forks/issues | &gt;100 forks/an | 10-100 | &lt;10 |

---

### **Calcul du score global**

- **Score total** : Somme des 5 critères (0-10)
- **Label communautaire** :
  - 🟢 **Bon objet** : ≥7/10
  - 🟠 **Objet limite** : 4-6/10
  - 🔴 **Mauvais objet** : ≤3/10

### **Règles de révision**

- **Validité** : 2 ans, puis ré-évaluation obligatoire
- **Contestabilité** : Quiconque peut **forker** une évaluation et la contester avec nouvelles preuves

---

### **Exemple d'application rapide : YouTube Recommendation**

| Critère | Score | Justification |
|---------|-------|---------------|
| **Utilité** | 0/2 | 85% des vues induites (A/B test vs placebo) |
| **Complexité** | 0/2 | Code fermé, infrastructure opaque |
| **Transparence** | 0/2 | &lt;5% décisions explicables (SHAP impossible) |
| **Réparabilité** | 0/2 | Aucune pièce, aucun manuel |
| **Contestabilité** | 0/2 | Exit impossible (verrou écosystème) |
| **TOTAL** | **0/10** | **🔴 MAUVAIS OBJET** |

---

### **Comment utiliser cette grille ?**

1. **Clonez** le repo : `git clone https://github.com/sabran83/ia-usage-fork`
2. **Testez** un objet de votre choix en suivant le protocole des 7 semaines
3. **Ouvrez une Issue** pour débattre de votre évaluation
4. **Forkez** pour créer votre version adaptée

**Cette grille est un artefact vivant. Usez-la, cassez-la, améliorez-la.**
