<!-- MASTER-HEADER-START -->
<div align="center">

<a href="https://0xcyberlitech.com/">
  <img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/headers/header-0xcyberlitech.svg" alt="0XCYBERLITECH // ARCHITECTURE SOUVERAINE" width="100%" />
</a>

<p align="center">
  <a href="https://0xcyberlitech.com/"><img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-portal.svg" alt="Portail 0xCyberLiTech.com" width="24%" /></a>
  <a href="https://0xcyberlitech.com/soc-rd.html"><img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-soc-rd.svg" alt="Livre Blanc SOC Cockpit" width="24%" /></a>
  <a href="https://0xcyberlitech.com/jarvis-rd.html"><img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-jarvis-rd.svg" alt="Livre Blanc JARVIS IA" width="24%" /></a>
  <a href="https://github.com/0xCyberLiTech?tab=repositories"><img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-github.svg" alt="Catalogue des 24 Dépôts" width="24%" /></a>
</p>
<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/divider-hud.svg" alt="" width="100%" />
</div>
<!-- MASTER-HEADER-END -->

<div align="center">

<a href="https://0xcyberlitech.com/">
  <img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/hero-sanctuary-3d.svg" alt="Synoptique 3D du Double Sanctuaire 0xCyberLiTech — SOC Cockpit v5.5 & JARVIS Stark Mark-VII" width="100%" />
</a>

</div>

---

## <img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/icons/wire-plan.svg" width="18" height="18" align="absmiddle" alt="" /> 01 // LE DOUBLE SANCTUAIRE R&D (PRODUCTION 24/7)
<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/glow-section-cyan.svg" width="100%" alt="" />

> *"On n'apprend pas la cybersécurité en lisant. On l'apprend en défendant une infrastructure réelle exposée 24h/24 aux attaques d'Internet."*

Chaque brique présentée sur ce profil tourne en **production réelle 24h/24 et 7j/7** sur une dorsale **Proxmox VE 9** souveraine, sans aucun cloud tiers, gouvernée par une discipline d'**ingénierie déterministe (Dette Technique Zéro)**. Les dossiers d'architecture complets et blueprints matériels sont publiés sur le portail officiel **[0xcyberlitech.com](https://0xcyberlitech.com/)**.

| Sanctuaire | Architecture & Spécifications Clés | Portail R&D (`0xcyberlitech.com`) | Dépôt & Tuto GitHub |
|:---|:---|:---:|:---:|
| [**SOC COCKPIT**](https://github.com/0xCyberLiTech/SOC)<br/>*Extreme HUD v5.5* | **38 tuiles télémétriques temps réel** sur 5 pages · **Suricata IDS** (90k+ sig.) · **CrowdSec WAF** · **Wazuh SIEM** · Riposte noyau `< 1 s` · **Studio Back-Office** · **19 Gardiens CI/CD** | [**Livre Blanc SOC →**](https://0xcyberlitech.com/soc-rd.html) | [**Dépôt GitHub SOC →**](https://github.com/0xCyberLiTech/SOC)<br/>[<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer SOC sur GitHub" />](https://github.com/0xCyberLiTech/SOC) |
| [**JARVIS MARK-VII**](https://github.com/0xCyberLiTech/JARVIS)<br/>*Orchestrateur IA Local* | **Qwen 3.5 9B** sur **RTX 5080 16 Go Blackwell** · **Fast-Path déterministe `< 200 ms`** · Voix neurale **Antoine HD** & **Faster-Whisper** · Mémoire **Hermès SQLite WAL & RAG** · **Pont MCP (22 outils)** | [**Livre Blanc JARVIS →**](https://0xcyberlitech.com/jarvis-rd.html)<br/>[**Blueprint RTX 5080 →**](https://0xcyberlitech.com/blueprint-jarvis.html) | [**Dépôt GitHub JARVIS →**](https://github.com/0xCyberLiTech/JARVIS)<br/>[<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer JARVIS sur GitHub" />](https://github.com/0xCyberLiTech/JARVIS) |

---


<details>
<summary><b>[SYNOPTIQUE INTERACTIF] Ouvrir le Graphe d'Architecture (Technologie GitHub Mermaid Zoom/Pan)</b></summary>

```mermaid
%%{init: {'theme': 'dark', 'themeVariables': { 'primaryColor': '#091326', 'primaryTextColor': '#f8fafc', 'primaryBorderColor': '#00d9ff', 'lineColor': '#00d9ff', 'secondaryColor': '#060b16', 'tertiaryColor': '#0b1528'}}}%%
flowchart LR
    WAN["[WAN] Flux Internet Hostiles 24/7"] --> FW["[DEFENSE] Filtrage Perimetrique<br/>Suricata IDS · CrowdSec WAF"]
    FW --> PVE["[HYPERVISEUR] Dorsale Proxmox VE 9<br/>Isolation VLAN & VMs Dediees"]
    PVE --> SOC["[SOC] Cockpit Extreme HUD v5.5<br/>38 Tuiles · Wazuh SIEM · Studio"]
    PVE --> JARVIS["[IA] JARVIS Stark Mark-VII FUI<br/>Qwen 3.5 9B · RTX 5080 16GB"]
    SOC <-->|"Bus Telemetrique Read-Only < 200ms"| JARVIS
    JARVIS --> VOICE["[AUDIO] Boucle Vocale Souveraine<br/>Faster-Whisper STT · Antoine HD TTS"]
    SOC --> PORTAL["[PORTAIL] Portail R&D Officiel<br/>https://0xcyberlitech.com"]
    JARVIS --> PORTAL
```

</details>

---

## <img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/icons/wire-plan.svg" width="18" height="18" align="absmiddle" alt="" /> 02 // CARTOGRAPHIE 3D DES CONTRIBUTIONS & TÉLÉMÉTRIE D'INGÉNIERIE
<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/glow-section-cyan.svg" width="100%" alt="" />

<div align="center">

<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/github-metrics.svg" alt="Cartographie isométrique 3D des contributions et télémétrie GitHub 0xCyberLiTech" width="58%" />

<br/><br/>

<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/telemetry-activity-hud.svg" alt="Télémétrie d'ingénierie et courbe d'activité souveraine 0xCyberLiTech" width="100%" />

<br/><br/>

<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/radar-mastery-hud.svg" alt="Radar polygonal de maîtrise technologique et répartition des 138 tutoriels et 203 pages" width="100%" />

</div>

---

## <img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/icons/wire-plan.svg" width="18" height="18" align="absmiddle" alt="" /> 03 // CATALOGUE DES ATELIERS TECHNIQUES & RUNBOOKS (DEBIAN 12 · 13 · 14)
<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/glow-section-cyan.svg" width="100%" alt="" />

L'ensemble des procédures d'infrastructure, de durcissement et de supervision ci-dessous est maintenu selon le principe de **Vérité Vraie** (`Debian 12 Bookworm · Debian 13 Trixie · Debian 14 Forky`, `Docker Compose v2`, `systemd`, `nftables`/`ufw`).

| Domaine | Atelier Technique | Périmètre Opérationnel & Technologies | Dossiers | Accès Direct |
|:---|:---|:---|:---:|:---:|
| **SANCTUAIRE R&D** | [**JARVIS Mark-VII**](https://github.com/0xCyberLiTech/JARVIS) | Orchestrateur IA souverain Qwen 3.5 9B (RTX 5080 Blackwell), Fast-Path `< 200 ms`, Voix & RAG | `Vitrine` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer JARVIS" />](https://github.com/0xCyberLiTech/JARVIS) |
| **SANCTUAIRE R&D** | [**SOC Cockpit v5.5**](https://github.com/0xCyberLiTech/SOC) | Poste de commandement Cyberdéfense 38 tuiles, Suricata IDS, CrowdSec WAF, Wazuh SIEM | `Vitrine` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer SOC" />](https://github.com/0xCyberLiTech/SOC) |
| **CYBERDÉFENSE** | [**Cybersécurité**](https://github.com/0xCyberLiTech/Cybersecurite) | Durcissement Debian 12, 13 & 14, Suricata 7 IDS/IPS, CrowdSec ipset noyau, sécurisation | `18` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Cybersécurité" />](https://github.com/0xCyberLiTech/Cybersecurite) |
| **CYBERDÉFENSE** | [**Firewall**](https://github.com/0xCyberLiTech/Firewall) | Filtrage réseau Netfilter, `nftables` Zero-Trust, `ufw`, `iptables`, cloisonnement DMZ/VLAN | `4` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Firewall" />](https://github.com/0xCyberLiTech/Firewall) |
| **CYBERDÉFENSE** | [**Proxy**](https://github.com/0xCyberLiTech/Proxy) | Filtrage HTTP/HTTPS avec Squid Proxy, SSL Bump, HAProxy sous Debian 12, 13 & 14 | `9` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Proxy" />](https://github.com/0xCyberLiTech/Proxy) |
| **CYBERDÉFENSE** | [**OpenVAS**](https://github.com/0xCyberLiTech/OpenVAS) | Scanner de vulnérabilités Greenbone (GVM), audit CVE & remédiation | `7` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer OpenVAS" />](https://github.com/0xCyberLiTech/OpenVAS) |
| **CYBERDÉFENSE** | [**SSH**](https://github.com/0xCyberLiTech/SSH) | Bastion OpenSSH, authentification par clés Ed25519, tunnels sécurisés | `3` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer SSH" />](https://github.com/0xCyberLiTech/SSH) |
| **CYBERDÉFENSE** | [**Cryptographie**](https://github.com/0xCyberLiTech/Cryptographie) | Chiffrement symétrique/asymétrique, PKI X.509, certificats TLS OpenSSL | `2` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Cryptographie" />](https://github.com/0xCyberLiTech/Cryptographie) |
| **SIEM & NOC** | [**Graylog**](https://github.com/0xCyberLiTech/Graylog) | Centralisation SIEM des journaux Linux/Windows, pipelines et dashboards | `13` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Graylog" />](https://github.com/0xCyberLiTech/Graylog) |
| **SIEM & NOC** | [**Zabbix**](https://github.com/0xCyberLiTech/Zabbix) | Supervision d'infrastructure Zabbix Server & Agents, triggers et alertes | `10` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Zabbix" />](https://github.com/0xCyberLiTech/Zabbix) |
| **SIEM & NOC** | [**Checkmk**](https://github.com/0xCyberLiTech/Checkmk) | Monitoring multi-nœuds haute précision, agents Linux/Windows et règles | `2` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Checkmk" />](https://github.com/0xCyberLiTech/Checkmk) |
| **SIEM & NOC** | [**Nagios**](https://github.com/0xCyberLiTech/Nagios) | Supervision réseau Nagios Core, plugins NRPE et contrôles de services | `10` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Nagios" />](https://github.com/0xCyberLiTech/Nagios) |
| **SIEM & NOC** | [**Smokeping**](https://github.com/0xCyberLiTech/Smokeping) | Métrologie WAN, mesure de latence/jitter ICMP et graphes RRD | `1` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Smokeping" />](https://github.com/0xCyberLiTech/Smokeping) |
| **SIEM & NOC** | [**Supervision**](https://github.com/0xCyberLiTech/Supervision) | Fondamentaux d'observabilité NOC/SOC, protocoles SNMP et architecture | `1` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Supervision" />](https://github.com/0xCyberLiTech/Supervision) |
| **INFRA & VIRTUALISATION** | [**Proxmox VE 8 & 9**](https://github.com/0xCyberLiTech/Proxmox) | Montage Bare-Metal BIOS/UEFI, ZFS, LVM-Thin, KVM (`qm`), LXC (`pct`), Pare-feu PVE, Sauvegardes PRA (`vzdump`/PBS) & Cluster HA | `10` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Proxmox" />](https://github.com/0xCyberLiTech/Proxmox) |
| **INFRA & CONTENEURS** | [**Docker**](https://github.com/0xCyberLiTech/Docker) | Conteneurisation Docker Engine, `docker compose` v2, Portainer, réseaux/volumes | `23` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Docker" />](https://github.com/0xCyberLiTech/Docker) |
| **INFRA & RÉSEAU** | [**DNS (BIND9)**](https://github.com/0xCyberLiTech/DNS) | Serveurs DNS Maître/Esclave BIND9, zones directes/inverses Debian 12, 13 & 14 | `4` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer DNS" />](https://github.com/0xCyberLiTech/DNS) |
| **INFRA & RÉSEAU** | [**DHCP**](https://github.com/0xCyberLiTech/DHCP) | Attribution dynamique IP, réservations MAC et segmentation sous Debian | `4` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer DHCP" />](https://github.com/0xCyberLiTech/DHCP) |
| **INFRA & RÉSEAU** | [**NTPsec**](https://github.com/0xCyberLiTech/NTPsec) | Synchronisation horaire atomique sécurisée pour corrélation forensique | `1` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer NTPsec" />](https://github.com/0xCyberLiTech/NTPsec) |
| **WEB & DATA** | [**Apache2 / LAMP**](https://github.com/0xCyberLiTech/Apache2) | Stack Web Debian (Apache2, PHP, MariaDB), VirtualHosts SSL/TLS | `7` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Apache2" />](https://github.com/0xCyberLiTech/Apache2) |
| **WEB & DATA** | [**MySQL / MariaDB**](https://github.com/0xCyberLiTech/MySQL) | Administration SGBD relationnel, durcissement des accès et sauvegardes | `1` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer MySQL" />](https://github.com/0xCyberLiTech/MySQL) |
| **IA & SYSTÈME** | [**IA Souveraine**](https://github.com/0xCyberLiTech/IA) | Ollama GPU Blackwell, Qwen 3.5 9B, RAG SQLite-vec, Whisper CUDA TTS & architectures GPU/NPU | `11` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer IA" />](https://github.com/0xCyberLiTech/IA) |
| **IA & SYSTÈME** | [**Astuces Linux**](https://github.com/0xCyberLiTech/Astuces) | Runbooks d'administration système, diagnostic CLI et automatisation | `7` | [<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/btn-explore.svg" alt="Explorer Astuces" />](https://github.com/0xCyberLiTech/Astuces) |

<!-- MASTER-FOOTER-START -->
<div align="center">
<img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/divider-hud.svg" alt="" width="100%" />

<a href="https://0xcyberlitech.com/">
  <img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/footer-master.svg" alt="0xCyberLiTech — Architecture Cyberdéfense, Ingénierie Déterministe & IA Souveraine" width="100%" />
</a>

<p align="center"><a href="https://0xcyberlitech.com/"><img src="https://raw.githubusercontent.com/0xCyberLiTech/0xcyberlitech/main/assets/badge-antigravity.svg" alt="Architecturé par Marc & Antigravity (Google DeepMind)" width="520" /></a></p>

<sub><b>Architecturé &amp; Forgé par Marc &amp; Antigravity (Google DeepMind)</b> &nbsp;·&nbsp; <a href="https://0xcyberlitech.com/"><b>0xcyberlitech.com</b></a> &nbsp;·&nbsp; <a href="https://0xcyberlitech.com/soc-rd.html">Architecture SOC Cockpit v5.5</a> &nbsp;·&nbsp; <a href="https://0xcyberlitech.com/jarvis-rd.html">Architecture JARVIS Mark-VII</a> &nbsp;·&nbsp; <a href="https://0xcyberlitech.com/blueprint-jarvis.html">Blueprint Matériel RTX 5080</a></sub>

</div>
<!-- MASTER-FOOTER-END -->
