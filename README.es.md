# Automatización de Load Balancers

🇺🇸 [English](README.md)

Proyectos de automatización multi-vendor enfocados en **Load Balancers, Application Delivery Controllers (ADC) y prácticas NetDevOps**.

Este repositorio está orientado a desarrollar y documentar flujos de automatización para la administración, configuración, validación y operación de infraestructura de balanceo de carga de diferentes fabricantes.

## 🎯 Objetivo del proyecto

El objetivo de este repositorio es construir soluciones de automatización reutilizables para tareas operativas comunes de Load Balancers y ADC, reduciendo trabajo manual repetitivo, mejorando la consistencia de configuración e introduciendo prácticas NetDevOps en la infraestructura de entrega de aplicaciones.

## 🌐 Fabricantes

El proyecto está diseñado para cubrir progresivamente:

- **F5 Networks BIG-IP**
- **A10 Networks Thunder ADC**
- **Citrix NetScaler ADC**

Se podrán incorporar plataformas adicionales a medida que evolucione el repositorio.

## 🔧 Enfoque tecnológico

La automatización utilizará principalmente tecnologías como:

- Python
- Ansible
- APIs REST
- APIs y SDKs de fabricantes
- JSON / YAML
- Git
- CI/CD
- Automatización de infraestructura
- Prácticas NetDevOps

Dependiendo de la plataforma, también se utilizarán APIs específicas del fabricante como **F5 iControl REST**.

## 🚀 Áreas de automatización

El repositorio incorporará progresivamente automatización relacionada con:

- Información de dispositivos y health checks
- Administración de Virtual Servers / Virtual IPs
- Pools y Service Groups
- Pool Members / Servers
- Nodes
- Health Monitors
- Objetos SSL/TLS
- Backups de configuración
- Validación de configuración
- Verificaciones operativas
- Inventario y reportes
- Administración basada en APIs
- Despliegue de configuración
- Validaciones pre-check y post-check
- Flujos de rollback automatizado
- Operaciones multi-dispositivo
- Integración CI/CD

## ⚙️ Enfoque NetDevOps

El objetivo a largo plazo no es solamente crear scripts o playbooks individuales, sino aplicar una **metodología NetDevOps a la infraestructura de Load Balancers**.

El repositorio explorará progresivamente flujos como:

```text
Git
 │
 ▼
Validación
 │
 ▼
Automatización
 │
 ▼
Load Balancer / ADC
 │
 ▼
Post-check
 │
 ▼
Reporte / Rollback
```

Esto permite administrar la infraestructura de balanceo mediante flujos repetibles, versionados y auditables.

## 📂 Estructura del repositorio

A medida que crezca el proyecto, la automatización se organizará por fabricante y tecnología.

```text
loadbalancers_automation/
│
├── f5/
├── a10/
├── citrix-netscaler/
├── ansible/
├── python/
├── docs/
├── README.md
└── README.es.md
```

> La estructura evolucionará a medida que se agreguen nuevos laboratorios y proyectos de automatización.

## 🧪 Entorno de laboratorio

Toda automatización desarrollada en este repositorio debe probarse primero en laboratorios o entornos controlados antes de adaptarse a infraestructura de producción.

## 📊 Estado del repositorio

> 🚧 **Work in Progress**

Este repositorio hace parte de mi desarrollo continuo en:

**Load Balancer Automation | Network Automation | NetDevOps | DevNet | Infrastructure Automation**

Se agregarán progresivamente nuevos laboratorios, scripts, playbooks e integraciones.

## 📄 Licencia

Este proyecto está licenciado bajo la [Licencia MIT](LICENSE).

## 👨‍💻 Autor

**Anderson Martinez Virviescas**

Network Administrator | Network Automation | NetDevOps | DevNet | Linux | Cybersecurity

GitHub: [@andersonmavi30](https://github.com/andersonmavi30)

---

> Parte de mi portafolio de Network Automation y NetDevOps.
