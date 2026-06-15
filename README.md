# Hi, I'm Kamran Akhlaq 👋

### Infrastructure & Operations Engineer · Linux · Networking · Cloud · VoIP · DevOps

When a server goes down, a network starts dropping packets, or a phone system stops taking calls, I find what actually broke and fix it for good.

## 👨‍💻 About Me

I'm an infrastructure and operations engineer with 11+ years across IT, telecom, and product-driven companies. I do two things well: keep mission-critical systems running, and find what broke at the root so it stays fixed.

I currently lead a 14-person team operating roughly 100 servers and 350 VMs behind telecom platforms that serve 20M+ subscribers at 99.9% uptime. My work runs from packet-level network troubleshooting and Linux administration up to building Production and Disaster-Recovery data centers, Kubernetes clusters, PostgreSQL high availability, and the monitoring and automation around all of it.

## 🛠️ What I Do

- **Infrastructure & data centers:** design and build Production and DR environments, hardware-to-production, on open-source stacks: Kubernetes, PostgreSQL HA, distributed storage, load balancing, and DR drills.
- **Network troubleshooting & security:** packet-level diagnosis (Wireshark, tcpdump) of TCP/IP, TLS, DNS, routing, and firewall faults across Cisco, Fortinet, MikroTik, and UniFi; VLANs, NAT, IPsec/SSL VPN.
- **Linux & systems administration:** Ubuntu, Debian, RHEL/CentOS, services, logs, permissions, backups, patching, hardening, and performance tuning.
- **Cloud & DevOps:** AWS and Azure (compute, networking, storage, identity), Docker and Kubernetes, CI/CD with Jenkins and Git, and Python/Bash/Ansible automation.
- **Databases:** PostgreSQL (HA, replication, DR, tuning), MySQL/MariaDB and Percona, plus Nginx, HAProxy, and Apache in front.
- **Production support & incident management:** incidents, problems, change, root-cause analysis, SLA tracking, and 24/7 operations (Zammad, Zendesk, Jira).
- **Monitoring & observability:** Nagios, Prometheus, Grafana, PRTG, Wazuh, and Alertmanager for coverage, alerting, and early detection.
- **VoIP & telephony:** Asterisk, FreePBX, and Vicidial, SIP trunks, IVR, call routing, CDRs, and call-quality troubleshooting.

## 🔧 Selected Work

**[Built Production + Disaster-Recovery data centers from bare metal (65 servers)](https://github.com/kamran-akhlaq/Project-Datacenter-ABIS/blob/main/README.md)**
Led the end-to-end build of Production and DR sites on an open-source stack: multi-master Kubernetes, PostgreSQL high availability (replication and connection pooling), Rook-Ceph distributed and object storage, Keycloak identity, and HAProxy with VIP failover. Designed the segmented network, hardened the OS, ran DR drills, and documented it to ISO/IEC 22237 and 27001 readiness.

**Restored analytics traffic blocked at the network level (40% → 100% delivery)**
Analytics events were silently failing to reach a cloud endpoint. I captured and analyzed the traffic, isolated the cause to injected TCP RST packets and dropped TLS handshakes on the international path, and routed around the interference to bring delivery back to 100%.

**Stabilized a 50-node Kubernetes cluster (300+ days uptime since)**
Brought an unstable multi-master cluster to a healthy state by working through Flannel CNI crash loops, PodCIDR mismatches, containerd and CoreDNS faults, and registry pulls blocked behind a corporate proxy. It has run 300+ days without recurrence.

**[Modernized enterprise monitoring (coverage 23% → 95%+, detection ~10% → ~90%)](https://github.com/kamran-akhlaq/Project-Monitoring-Modernization/blob/main/README.md)**
Rebuilt an underperforming monitoring platform with deep Linux and ESXi coverage and custom checks, raising service-check coverage from ~23% to over 95% and proactive fault detection from ~8-15% to 85-90%, while cutting monitoring-server load by ~87%.

**Eliminated recurring production incidents (10-15/month → 0)**
The same issues kept coming back. I ran root-cause analysis on the worst offenders, put in permanent fixes instead of band-aids, added preventive monitoring, and documented everything so it stayed fixed.

**Stabilized a VoIP/Asterisk platform handling ~150K calls/day (~90% fewer complaints)**
A call platform was generating constant dropped-call and audio complaints. I traced it to SIP trunk, call-routing, and codec/NAT issues, fixed them, and tuned service performance.

**Automated routine operations (50 tasks, ~16 hours/week saved)**
Replaced manual, repetitive work with Python, Bash, and Ansible, server build and hardening, monitoring, backups, and ETL, removing 50 recurring tasks and freeing roughly 16 hours a week.

## 💻 Tech Stack

**Cloud Platforms**

![Microsoft Azure](https://img.shields.io/badge/Microsoft%20Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Google Cloud](https://img.shields.io/badge/GoogleCloud-%234285F4.svg?style=for-the-badge&logo=google-cloud&logoColor=white)

**Virtualization**

![VMware](https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=vmware&logoColor=white)
![Proxmox](https://img.shields.io/badge/Proxmox-%234C8BF5.svg?style=for-the-badge&logo=proxmox&logoColor=white)
![VirtualBox](https://img.shields.io/badge/VirtualBox-%230074FF.svg?style=for-the-badge&logo=virtualbox&logoColor=white)

**Operating Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Microsoft Windows](https://img.shields.io/badge/Microsoft%20Windows-0078D4?style=for-the-badge&logo=microsoft-windows&logoColor=white)
![Microsoft Servers](https://img.shields.io/badge/Microsoft%20Servers-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)

**Networking**

![Cisco](https://img.shields.io/badge/Cisco-004B87?style=for-the-badge&logo=cisco&logoColor=white)
![Fortinet](https://img.shields.io/badge/Fortinet-%23C6C6C6.svg?style=for-the-badge&logo=fortinet&logoColor=white)
![Huawei](https://img.shields.io/badge/Huawei-EE1D23?style=for-the-badge&logo=huawei&logoColor=white)
![MikroTik](https://img.shields.io/badge/MikroTik-293239?style=for-the-badge&logo=mikrotik&logoColor=white)
![Ubiquiti](https://img.shields.io/badge/Ubiquiti%20UniFi-0559C9?style=for-the-badge&logo=ubiquiti&logoColor=white)

**DevOps & CI/CD**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=for-the-badge&logo=ansible&logoColor=white)

**Monitoring**

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white)
![Nagios](https://img.shields.io/badge/Nagios-000000?style=for-the-badge&logo=nagios&logoColor=white)
![Wazuh](https://img.shields.io/badge/Wazuh-3C97D3?style=for-the-badge&logo=wazuh&logoColor=white)

**Databases**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

**Web & Proxy**

![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![Apache](https://img.shields.io/badge/Apache-D22128?style=for-the-badge&logo=apache&logoColor=white)
![HAProxy](https://img.shields.io/badge/HAProxy-106DA9?style=for-the-badge&logo=haproxy&logoColor=white)

**VoIP & Telephony**

![Asterisk](https://img.shields.io/badge/Asterisk-FF5800?style=for-the-badge&logo=asterisk&logoColor=white)
![FreePBX](https://img.shields.io/badge/FreePBX-FF5800?style=for-the-badge)
![Vicidial](https://img.shields.io/badge/Vicidial-1E6FB8?style=for-the-badge)

**Languages & Automation**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

## 📜 Certifications

- CCNA Security
- CCNA Routing & Switching
- CCNA Cyber Ops
- HCNA Routing & Switching
- Palo Alto ACE (Accredited Configuration Engineer)
- Fortinet NSE 1 & 2
- Microsoft Certified: Azure AI Fundamentals (AI-900)

## 📫 Work With Me

I'm available for freelance and contract work in infrastructure, operations, networking, and support, from urgent fixes to long-term engagements.

<!-- Replace YOUR_PROFILE_LINK with your real Upwork profile URL before publishing. -->
[![Upwork](https://img.shields.io/badge/Hire%20me%20on-Upwork-6FDA44?style=for-the-badge&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/~010ed25fc87ec3fe85?mp_source=share)
