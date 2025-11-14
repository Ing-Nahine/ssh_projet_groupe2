# Connexion à distance via SSH (Réseau Local)

## 📋 Description
Projet d'exposé sur la mise en œuvre de connexions SSH dans un réseau local.

**Groupe 2**
- GBABLI MATHIEU Nahine
- GNACADJA Jean de Dieu
- AHOKOU Melvine

**Date** : 17/11/2025

---

## 🎯 Objectifs
- Installer un serveur SSH sous Linux
- Établir des connexions SSH depuis Linux et Windows
- Transférer des fichiers via SCP

---

## 📚 Documents

- 📄 [Rapport complet (PDF)](./rapport.pdf)
- 🎨 [Présentation PowerPoint (PDF)](./presentation.pdf)

---

## 🖼️ Captures d'écran

### Installation du serveur SSH
![Installation SSH](./captures/01-installation-ssh.png)

### Connexion Linux vers Linux
![Connexion Linux](./captures/02-connexion-linux.png)

### Connexion Windows (PuTTY)
![PuTTY](./captures/03-putty-windows.png)

### Transfert de fichiers SCP
![SCP](./captures/04-transfert-scp.png)

---

## 💻 Commandes principales

### Installation
```bash
sudo apt update
sudo apt install openssh-server
sudo systemctl start ssh
```

### Connexion
```bash
ssh utilisateur@adresse_ip
```

### Transfert de fichiers
```bash
# Local vers distant
scp fichier.txt user@ip:/chemin/

# Distant vers local
scp user@ip:/fichier.txt ./
```

---

## 🔧 Prérequis
- 2 postes Linux (Ubuntu/Debian)
- 1 poste Windows avec PuTTY
- Réseau local configuré

---

## 📖 Ressources
- [Documentation OpenSSH](https://www.openssh.com/)
- [PuTTY](https://www.putty.org/)
- Chapitres 7 et 14 EdX

---

## 📞 Contact
Pour toute question : combarinahine@gmail.com
