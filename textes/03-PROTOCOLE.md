# PROTOCOLE D'ÉVALUATION OPEN-OBJET
## Durée : 7 semaines | Format : JSON-LD | Livrable : Rapport public sur IPFS

### **Principe 3 : Protocole de test standardisé**

**Semaine 1 – Documentation**
- Récupérer code source, schémas, manuels
- Tester accessibilité : lecture à voix haute à un non-expert
- **Livrable** : Inventaire documentaire (format PDF/ODT)

**Semaine 2-3 – Utilisation**
- 3 utilisateurs réels filment leurs interactions (écran + voix)
- Mesure du temps d'apprentissage, erreurs, frustration (échelle NASA-TLX)
- **Livrable** : Vidéos brutes + analyse qualitative

**Semaine 4 – Audit technique**
- Tenter de reproduire l'environnement de test
- Counterfactual testing : 100 scénarios de bord (ex: "Que se passe-t-il si...")
- Adversarial testing : robustesse aux entrées anormales
- **Livrable** : Rapport d'audit comportemental

**Semaine 5 – Réparation**
- Introduire 3 pannes standards (panne logicielle, matérielle, erreur utilisateur)
- Mesurer temps d'identification et de correction avec documentation
- **Livrable** : Benchmark réparabilité (temps, outils, coût)

**Semaine 6 – Contestation**
- Tester exit : exporter données, migrer vers alternative
- Tester recours : soumettre 5 plaintes, mesurer délai de réponse
- **Livrable** : Rapport contestabilité

**Semaine 7 – Publication**
- Rédiger évaluation au format JSON-LD (schéma open-objet.json)
- Publier sur dépôt public (IPFS) avec hash unique
- **Livrable** : Rapport final + lien IPFS

### **Format JSON-LD (exemple)**
```json
{
  "@context": "https://ia-usage-fork.github.io/open-objet.jsonld",
  "@type": "Evaluation",
  "objectName": "YouTube Recommendation",
  "scoreTotal": 0,
  "evaluator": "Citoyen-12345",
  "ipfsHash": "QmT123..."
}
