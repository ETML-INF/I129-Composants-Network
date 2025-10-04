# E-129-Ex02 – VLANs et STP sur Cisco Packet Tracer

**Module :** ETML – Module 129

**Exercice :** 02

**Auteur :** Alexis Gugler

**Création :** 31.07.2025

**Version :** 3 du 31.07.2025

**Durée estimée :** 45 minutes

---

## 🧑‍🎓 Informations de l’élève

* **Nom :** `__________________________`
* **Prénom :** `__________________________`
* **Date :** `__________________________`

---

## 📌 Consignes générales

* **Nom du fichier à rendre :** `E-129-Ex02-nom-prenom.pkt`
* **Lieu de dépôt :** Canal MS Teams, section **Fichiers** du cours.
* **Format accepté :** `.pkt` (Packet Tracer)
* **Date limite de rendu :** Selon les consignes de l’enseignant

---

## 🎯 Objectif

- Créer un réseau avec trois VLANs et six PC répartis sur trois switchs interconnectés en triangle.
- Vérifier que le Spanning Tree Protocol (STP) est activé et comprendre son rôle.

---

## 🛠️ Directives de travail

### 1. Créer le réseau

* Placez trois switchs Cisco (ex : 2960) et six PC sur Packet Tracer.
* Reliez les trois switchs entre eux en triangle (chaque switch connecté aux deux autres).
* Connectez deux PC sur chaque switch (un port par PC).

---

### 2. Configurer les VLANs

* Créez trois VLANs (VLAN 10, VLAN 20, VLAN 30).
* Affectez deux PC à chaque VLAN (ex : PC1 et PC2 dans VLAN 10, PC3 et PC4 dans VLAN 20, PC5 et PC6 dans VLAN 30).
* Configurez les ports trunk entre les switchs pour transporter les VLANs.

---

### 3. Vérifier la configuration

* Utilisez la commande `show vlan brief` pour vérifier l'affectation des ports.
* Utilisez la commande `show interfaces trunk` pour vérifier les trunks.

---

### 4. Vérifier le STP

* Utilisez la commande `show spanning-tree` sur chaque switch.
* Identifiez le Root Bridge et observez l'état des ports (forwarding/blocking).
* Débranchez un des câbles entre deux switchs et observez le changement d'état des ports.

---

## ❓ Questions

* À quoi sert le STP dans ce contexte ?
* Que se passe-t-il si vous supprimez un des liens entre deux switchs ?
* Pourquoi configure-t-on des trunks entre les switchs ?

---

