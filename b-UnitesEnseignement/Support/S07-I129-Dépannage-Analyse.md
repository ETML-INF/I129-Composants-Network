---
marp: true
theme: default
paginate: true
footer: "ETML - Module I129 - AGR"
---

# S07-I129-Dépannage et analyse réseau

**Module :** ETML – Module 129  
**Auteur :** Alexis Gugler  
**Création :** 05.08.2025  
**Version :** 1 du 05.08.2025  
**Durée estimée de lecture :** XX minutes

---

# Table des matières

1. Introduction
2. Outils de diagnostic réseau
   - ping
   - traceroute
   - show
   - debug
3. Méthodologie de recherche d’erreurs (modèle OSI)
4. Exercice pratique : dépannage sur Packet Tracer

---

# 1. Introduction

Cette séquence présente les outils et méthodes pour diagnostiquer et corriger les problèmes réseau. Vous apprendrez à utiliser les commandes de base, à raisonner selon le modèle OSI et à dépanner un réseau sur Packet Tracer.

---

# 2. Outils de diagnostic réseau

## 2.1 ping
- Permet de tester la connectivité entre deux équipements réseau.
- Utilise le protocole ICMP pour envoyer des paquets de test (echo request/reply).
- Exemple :
```shell
PC> ping 192.168.1.1
```

---

## 2.2 traceroute
- Permet de visualiser le chemin suivi par les paquets jusqu’à une destination.
- Affiche chaque routeur traversé et le temps de réponse.
- Exemple :
```shell
PC> traceroute 8.8.8.8
```

---

## 2.3 show
- Commande Cisco pour afficher l’état des interfaces, la table de routage, les VLANs, etc.
- Exemples :
```shell
Router# show ip interface brief
Router# show running-config
Router# show vlan
```

---

## 2.4 debug
- Commande Cisco pour activer des messages de diagnostic détaillés en temps réel.
- À utiliser avec précaution (peut surcharger l’équipement).
- Exemple :
```shell
Router# debug ip icmp
```

---

# 3. Méthodologie de recherche d’erreurs (modèle OSI)

- Suivre les couches du modèle OSI pour isoler la source du problème :
  1. **Physique** : câbles, alimentation, voyants
  2. **Liaison de données** : adresses MAC, switchs, VLANs
  3. **Réseau** : adresses IP, routage
  4. **Transport** : ports TCP/UDP
  5. **Session** : connexions, authentification
  6. **Présentation** : format des données
  7. **Application** : services, applications réseau
- Procéder par élimination, du bas vers le haut.
- Utiliser les outils adaptés à chaque couche.

---

## Questions de réflexion

- Pourquoi est-il important de raisonner selon le modèle OSI lors d’un dépannage ?
- Quels sont les risques d’utiliser la commande `debug` sans précaution ?
- Quelle commande utiliser pour vérifier rapidement l’état des interfaces sur un routeur Cisco ?

---

*Sources : Cisco, supports ETML, documentation Packet Tracer*
