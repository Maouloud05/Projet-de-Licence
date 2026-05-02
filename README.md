# AdCheck : Audit de confidentialité des applications mobiles

## Présentation du projet
AdCheck est une solution hybride (Web/Mobile) conçue pour évaluer le niveau de protection des données personnelles au sein de l'écosystème applicatif d'un smartphone. L'outil analyse les déclarations de permissions et identifie la présence de librairies tierces orientées marketing ou tracking.

## Objectifs techniques
* **Analyse statique :** Extraction et lecture des manifestes d'applications pour lister les accès sensibles.
* **Identification de trackers :** Confrontation des signatures logicielles avec les bases de données de référence (ex: Exodus Privacy).
* **Indicateur de risque :** Modélisation d'un score de confiance basé sur le nombre et la criticité des permissions accordées.
* **Interface de monitoring :** Visualisation synthétique des résultats sur mobile et historique des audits sur une interface web dédiée.

## Spécifications logicielles
* **Environnement Mobile :** [Ta techno, ex: React Native / Flutter]
* **Architecture Backend :** API REST développée sous [Ta techno, ex: Node.js]
* **Persistance des données :** [Ta techno, ex: PostgreSQL / MongoDB]

## État d'avancement
- [x] Définition du cahier des charges
- [ ] Développement du moteur d'analyse
- [ ] Conception de l'interface utilisateur
- [ ] Tests et déploiement

---
*Réalisé par [Ton Nom] — Licence Informatique — 2026*
