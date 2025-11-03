# 🧭 Roadmap - SOC HomeLab

### Phase 1 : Base réseau & supervision
- [ ] Installation Proxmox + création VLANs
- [ ] Déploiement pfSense (firewall / VLAN / NAT)
- [ ] VM management + accès SSH

### Phase 2 : Stack SIEM
- [ ] Installation ELK (Elastic + Kibana)
- [ ] Ajout Filebeat et Logstash
- [ ] Premier dashboard de logs système

### Phase 3 : IDS / Suricata
- [ ] Déploiement Suricata en mode IDS
- [ ] Envoi des alertes vers Logstash
- [ ] Tests d’alertes (scan nmap, exploit, etc.)

### Phase 4 : Endpoint Security
- [ ] Installation Wazuh Manager
- [ ] Installation d’un agent Windows/Linux
- [ ] Visualisation des événements sur le SIEM

### Phase 5 : Threat Intel & IR
- [ ] Déploiement TheHive + Cortex + MISP
- [ ] Liaison avec Wazuh ou Suricata
- [ ] Premier cas d’incident simulé

### Phase 6 : Honeypots & démos
- [ ] Déploiement Cowrie SSH/Telnet
- [ ] Intégration des logs dans ELK
- [ ] Génération d’attaques réelles (bruteforce)

### Phase 7 : Documentation & automatisation
- [ ] Diagrammes réseau et dataflow
- [ ] Playbooks Ansible
- [ ] Rapport final et vidéo de démonstration
