---
marp: true
theme: default
paginate: true
footer: "ETML - Module I129 - AGR"
---

# S08-I129-Documentation et remise du réseau

**Module :** ETML – Module 129  
**Auteur :** Alexis Gugler  
**Création :** 05.08.2025  
**Version :** 1 du 05.08.2025  
**Durée estimée de lecture :** XX minutes

---

# Table des matières

1. Introduction
2. Éléments d’une documentation réseau
   - Schéma réseau
   - Configurations
   - Choix techniques
3. Rédaction de la documentation
4. Remise au client

---

# 1. Introduction

Cette séquence aborde la finalisation d’un projet réseau : comment documenter le travail réalisé et préparer la remise au client. Vous apprendrez à structurer une documentation professionnelle et à présenter votre projet.

---

# 2. Éléments d’une documentation réseau

## 2.1 Schéma réseau
- Représentation graphique de l’architecture du réseau (équipements, connexions, VLANs, etc.).
- Doit être clair, lisible et à jour.

## 2.2 Configurations
- Inclure les configurations des équipements principaux (switchs, routeurs).
- Exemples : hostname, interfaces, VLANs, routage, sécurité.
- Présenter les extraits de configuration ou les fichiers complets en annexe.

---

## 2.3 Choix techniques
- Expliquer les choix faits lors de la conception (topologie, adressage, sécurité, matériel).
- Justifier les décisions importantes (ex : choix du routage statique, segmentation en VLANs, etc.).

## 2.4 Documentation IP fixes
- Il est important de maintenir une documentation des adresses IP fixes attribuées aux équipements.
- Par exemple un fichier excel avec toutes les adresses IP fixes libres et utilisées que l'on met à jour régulièrement.

---

# 3. Rédaction de la documentation

- Structurer la documentation : introduction, objectifs, schéma, configurations, choix techniques, annexes.
- Utiliser un langage clair, des schémas et des tableaux si besoin.
- Vérifier l’exactitude et la cohérence des informations.
- Exemple de plan :
  1. Introduction et objectifs
  2. Schéma réseau
  3. Configurations détaillées
  4. Choix techniques et justification
  5. Annexes (captures d’écran, fichiers de config, etc.)

---

# 3.1 La documentation : un artefact vivant

- La documentation réseau n’est pas un document figé : elle doit évoluer avec le réseau.
- Toute modification (ajout d’un équipement, changement d’IP, migration, etc.) doit être répercutée dans la documentation.
- Une documentation à jour facilite la maintenance, le dépannage et l’évolution du réseau.
- Elle permet aussi d’assurer la continuité de service en cas de changement d’équipe ou d’intervenant.

---

# 3.2 Outils modernes pour la documentation réseau

- Il existe aujourd’hui des outils dédiés à la gestion et à la mise à jour de la documentation technique. Ces outils permettent de centraliser, versionner et partager la documentation avec toute l’équipe.
- Exemples d’outils :
  - **Confluence** (Atlassian) : solution collaborative très utilisée en entreprise (souvent couplée à Jira).
  - **DokuWiki** : wiki open source simple à déployer pour la documentation technique.
  - **NetBox** : outil open source spécialisé pour la documentation d’infrastructure réseau (IPAM, gestion d’équipements, etc.).
  - **Notion** : plateforme collaborative polyvalente (notes, bases de données, documentation).
- L’utilisation d’un outil adapté permet d’éviter les pertes d’information et d’assurer la pérennité de la documentation.

---

# 4. Remise au client

- Préparer une présentation orale pour expliquer le projet.
- Fournir la documentation complète au client (format PDF / imprimé et source).

---

## Questions de réflexion

- Pourquoi la documentation est-elle essentielle dans un projet réseau ?
- Quels sont les risques d’une documentation incomplète ou obsolète ?
- Comment adapter la présentation selon le public (client technique ou non technique) ?

---

*Sources : Cisco, supports ETML, documentation Packet Tracer*
