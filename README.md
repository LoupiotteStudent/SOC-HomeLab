# 🛰️ SOC HomeLab

Projet personnel de **laboratoire SOC complet**, déployé sur un **serveur Proxmox**, afin de démontrer mes compétences en **cybersécurité défensive** (Blue Team).

---

## 🎯 Objectifs
- Mettre en place un environnement SOC réaliste.
- Collecter, corréler et visualiser les logs réseau et hôte.
- Détecter des attaques réelles ou simulées.
- Gérer la réponse aux incidents et la threat intelligence.

---

## 🧱 Architecture

| Composant | Rôle principal | Technologies |
|------------|----------------|--------------|
| **pfSense/OPNsense** | Firewall, VLAN, NAT | pfSense |
| **Sensor** | IDS/IPS, analyse réseau | Suricata, Zeek |
| **SIEM** | Indexation et visualisation | Elasticsearch, Logstash, Kibana |
| **Endpoint Monitoring** | Logs et détection hôte | Wazuh, osquery |
| **Incident Response** | Gestion des alertes | TheHive, Cortex |
| **Honeypots** | Capture d'attaques | Cowrie, T-Pot |
| **Threat Intel** | Enrichissement des IOC | MISP |

---

## 🌐 Schéma d’infrastructure

![Architecture SOC HomeLab](diagrams/architecture_v3.drawio.png)

---

## 📚 Documentation
Les guides détaillés se trouvent dans le dossier [`docs/`](docs/).

---

## 🧭 Roadmap
Consulte la [roadmap du projet](docs/roadmap.md) pour suivre les étapes de déploiement.

