# Load Balancers Automation

🇨🇴 [Español](README.es.md)

Multi-vendor automation projects focused on **Load Balancers, Application Delivery Controllers (ADC) and NetDevOps practices**.

This repository is intended to develop and document automation workflows for the administration, configuration, validation and operation of load-balancing infrastructure from different vendors.

## 🎯 Project Objective

The goal of this repository is to build reusable automation solutions for common Load Balancer and ADC operational tasks, reducing repetitive manual work, improving configuration consistency and introducing NetDevOps practices into application delivery infrastructure.

## 🌐 Vendors

The project is designed to progressively cover:

- **F5 Networks BIG-IP**
- **A10 Networks Thunder ADC**
- **Citrix NetScaler ADC**

Additional platforms may be incorporated as the repository evolves.

## 🔧 Technology Focus

Automation will primarily use technologies such as:

- Python
- Ansible
- REST APIs
- Vendor APIs and SDKs
- JSON / YAML
- Git
- CI/CD
- Infrastructure Automation
- NetDevOps practices

Depending on the platform, vendor-specific APIs such as **F5 iControl REST** will also be used.

## 🚀 Automation Areas

The repository will progressively include automation related to:

- Device information and health checks
- Virtual Server / Virtual IP management
- Pools and Service Groups
- Pool Members / Servers
- Nodes
- Health Monitors
- SSL/TLS objects
- Configuration backups
- Configuration validation
- Operational checks
- Inventory and reporting
- API-based administration
- Configuration deployment
- Pre-check and post-check validation
- Automated rollback workflows
- Multi-device operations
- CI/CD integration

## ⚙️ NetDevOps Approach

The long-term objective is not only to create individual scripts or playbooks, but to apply a **NetDevOps methodology to Load Balancer infrastructure**.

The repository will progressively explore workflows such as:

```text
Git
 │
 ▼
Validation
 │
 ▼
Automation
 │
 ▼
Load Balancer / ADC
 │
 ▼
Post-check
 │
 ▼
Reporting / Rollback
```

This allows load-balancing infrastructure to be managed using repeatable, version-controlled and auditable automation workflows.

## 📂 Repository Structure

As the project grows, automation will be organized by vendor and technology.

```text
loadbalancers_automation/
│
├── f5/
├── a10/
├── citrix-netscaler/
├── ansible/
├── python/
├── docs/
└── README.md
```

> The structure will evolve as new labs and automation projects are added.

## 🧪 Lab Environment

All automation developed in this repository should first be tested in laboratory or controlled environments before being adapted for production infrastructure.

## 📊 Repository Status

> 🚧 **Work in Progress**

This repository is part of my continuous development in:

**Load Balancer Automation | Network Automation | NetDevOps | DevNet | Infrastructure Automation**

New labs, scripts, playbooks and integrations will be added progressively.

## 👨‍💻 Author

**Anderson Martinez Virviescas**

Network Administrator | Network Automation | NetDevOps | DevNet | Linux | Cybersecurity

GitHub: [@andersonmavi30](https://github.com/andersonmavi30)

---

> Part of my Network Automation and NetDevOps portfolio.
