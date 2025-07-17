# 📄 CHANGELOG - 0xcyberlitech

Toutes les modifications notables de ce projet seront consignées ici, selon la norme [Keep a Changelog](https://keepachangelog.com/fr/1.0.0/).

---

## [v1.0.0] - 2025-07-17

### 🚀 Version initiale

- Ajout des scripts de sécurité et audit réseau :
  - `script_nmap.sh` : scanner réseau avec gestion des résultats et FAQ
  - `script_clamav.sh` : gestion de l’antivirus ClamAV (scan, mise à jour)
  - `script_chkrootkit.sh` : analyse rootkits avec gestion complète des résultats
  - `script_rkhunter.sh` : audit rootkits avec menu dédié et FAQ
  - `script_lynis.sh` : audit système Lynis avec installation et scan local/distant
  - `lansubnet.sh` : scan de sous-réseaux avec Nmap, MAC, vendeurs, gestion résultats
- Méta-script `0xcyberlitech.sh` intégrant tous les modules avec menu principal
- Système de journalisation centralisée (`journal.log`)
- Gestion des dépendances et vérifications automatiques
- Interface interactive et moderne avec menus et sous-menus
- Documentation intégrée via FAQ pour chaque outil
- Scripts compatibles Debian 12, Bash, Git Bash Windows

---

## 📌 À venir (prochaines versions)

- Ajout d’outils complémentaires de sécurité et monitoring
- Automatisation des alertes et reporting
- Intégration avec plateformes CI/CD
- Optimisation UX/UI des menus interactifs
- Support multi-utilisateurs et gestion des accès

---

## 🛠 Historique du projet

- Début du développement : 2025-06-01  
- Première release officielle : 2025-07-17
