# LAB1_SEC_ANDROID


https://github.com/user-attachments/assets/19da70a3-07d5-4a63-9cfa-0a624b05df98




## 🔹 Mobexler
**Mobexler** est une machine virtuelle dédiée au **pentesting mobile (Android)**.

### Fonctionnalités
- Environnement prêt pour le test de sécurité
- Outils intégrés :
  - ADB
  - Burp Suite
  - Frida
  - Apktool
  - JADX
  - Wireshark

### Utilisation
- Analyse d’applications Android (APK)
- Reverse engineering
- Interception du trafic réseau
- Tests OWASP Mobile

### Avantages
- Prêt à l’emploi
- Gain de temps
- Idéal pour apprendre le pentest mobile

---

## 🔹 Genymotion
**Genymotion** est un émulateur Android rapide.

### Fonctionnalités
- Simulation d’appareils Android
- Basé sur VirtualBox
- Support ADB
- Simulation (GPS, réseau, batterie)

### Utilisation
- Tester des applications Android
- Développement mobile
- Environnement de test sans téléphone réel

### Avantages
- Rapide et fluide
- Léger
- Facile à configurer

---

## 🔗 Relation entre Mobexler et Genymotion

- **Mobexler** → outil de pentest (attaquant / analyse)
- **Genymotion** → appareil Android virtuel (cible)

### 🔄 Fonctionnement ensemble
1. Lancer Genymotion (appareil Android)
2. Connecter avec ADB :
   ```bash
   adb connect <IP>:5555
