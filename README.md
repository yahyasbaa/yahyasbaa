<h1 align="center">Hi, I'm Yahya 👋</h1>

<p align="center">
  <b>Security engineering · SOC &amp; detection engineering · Network security · Secure cloud infrastructure</b>
</p>

<p align="center">
  <a href="https://github.com/yahyasbaa/soc-siem-lab"><img alt="SOC & SIEM lab" src="https://img.shields.io/badge/SOC%20%26%20SIEM-Wazuh%20%7C%20MITRE%20ATT%26CK-1f6feb?style=for-the-badge"></a>
  <a href="https://github.com/yahyasbaa/enterprise-network-security-lab"><img alt="Network security lab" src="https://img.shields.io/badge/Network%20Security-nftables%20%7C%20Suricata-2ea043?style=for-the-badge"></a>
  <a href="https://github.com/yahyasbaa/secure-cloud-infrastructure"><img alt="Secure cloud" src="https://img.shields.io/badge/Secure%20Cloud-Terraform%20%7C%20AWS-8250df?style=for-the-badge"></a>
</p>

---

### 🛡️ About me

I build **reproducible, tested security environments**. They are labs where every control, detection and
configuration comes with an automated test that proves it works, and fails loudly when it stops working.

- 🔎 **Blue team / SOC**: log collection, detection engineering, ATT&CK mapping, incident-response playbooks
- 🌐 **Network security**: segmentation, default-deny firewalling, inline IDS/IPS, centralised logging
- ☁️ **Cloud security**: least-privilege IaC, encryption everywhere, policy-as-code, CI/CD with OIDC
- 🧪 **Everything as code, everything tested**: Docker, Makefiles, pytest, one-command workflows

---

### 🚀 Featured projects

| Project | What it is | Highlights |
|---|---|---|
| 🛰️ **[soc-siem-lab](https://github.com/yahyasbaa/soc-siem-lab)** | Local SOC with Wazuh (manager · OpenSearch indexer · dashboards) monitoring Linux, Windows, web and IDS hosts | 36 detections across 26 MITRE ATT&CK techniques · end-to-end detection tests (272 passing) · analyst dashboard · evidence bundles · 7 IR playbooks |
| 🧱 **[enterprise-network-security-lab](https://github.com/yahyasbaa/enterprise-network-security-lab)** | Small-enterprise network with five VLAN-equivalent segments in Docker | stateful default-deny nftables firewall · inline Suricata IDS/IPS (fail closed) · DMZ, servers, management and security zones · live security regression tests |
| ☁️ **[secure-cloud-infrastructure](https://github.com/yahyasbaa/secure-cloud-infrastructure)** | Security-first three-tier AWS architecture in Terraform | WAF + ALB → private EC2 → encrypted RDS · KMS, Secrets Manager, CloudTrail, 24 CloudWatch alarms · checkov / tfsec / trivy / gitleaks · GitHub Actions with OIDC · STRIDE threat model |
| 🩺 **[MedPredict](https://github.com/yahyasbaa/MedPredict)** | Full-stack medical-practice management app with an AI diagnosis-assistance microservice | React + Vite · Django REST + JWT · Flask + scikit-learn (Random Forest) · PostgreSQL · Docker Compose microservices |

---

### 🧰 Tech I work with

**Security**
<br>
<img alt="Wazuh" src="https://img.shields.io/badge/Wazuh-005571?style=flat-square">
<img alt="OpenSearch" src="https://img.shields.io/badge/OpenSearch-005EB8?style=flat-square&logo=opensearch&logoColor=white">
<img alt="Suricata" src="https://img.shields.io/badge/Suricata-EF5B25?style=flat-square">
<img alt="nftables" src="https://img.shields.io/badge/nftables-333333?style=flat-square&logo=linux&logoColor=white">
<img alt="MITRE ATT&CK" src="https://img.shields.io/badge/MITRE%20ATT%26CK-C8102E?style=flat-square">
<img alt="Sysmon" src="https://img.shields.io/badge/Sysmon-0078D4?style=flat-square">
<img alt="checkov" src="https://img.shields.io/badge/checkov-7B42BC?style=flat-square">
<img alt="tfsec" src="https://img.shields.io/badge/tfsec-2E3440?style=flat-square">
<img alt="Trivy" src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aquasecurity&logoColor=white">
<img alt="gitleaks" src="https://img.shields.io/badge/gitleaks-D9381E?style=flat-square">

**Cloud &amp; infrastructure**
<br>
<img alt="AWS" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
<img alt="Terraform" src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white">
<img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
<img alt="GitHub Actions" src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white">
<img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black">
<img alt="Nginx" src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white">
<img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white">

**Languages &amp; frameworks**
<br>
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
<img alt="Bash" src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white">
<img alt="pytest" src="https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white">
<img alt="Django" src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white">
<img alt="Flask" src="https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white">
<img alt="React" src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB">
<img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white">

---

### 📐 How I build things

```text
design  ->  implement as code  ->  automate the setup  ->  test the security control itself
        ->  break it on purpose to prove the test fails  ->  document what was verified and what wasn't
```

<p align="center"><i>All labs are local and isolated. Offensive scenarios are simulated or contained, and never aimed at real systems.</i></p>
