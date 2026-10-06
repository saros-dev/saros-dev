<div align="center">

# Saros

### DevOps · DevSecOps · SRE · Observability · Open Source

**Building systems that are observable, secure, automated, and reliable.**

<br />

[![GitHub](https://img.shields.io/badge/GitHub-saros--dev-181717?style=flat-square\&logo=github)](https://github.com/saros-dev)
[![Open Source](https://img.shields.io/badge/Open%20Source-Projects-2ea44f?style=flat-square\&logo=opensourceinitiative\&logoColor=white)](https://github.com/saros-dev)
[![Security](https://img.shields.io/badge/Security-Minded-8B0000?style=flat-square\&logo=hackthebox\&logoColor=white)](https://github.com/saros-dev)

</div>

---

```text
$ whoami

Saros

DevOps / DevSecOps / SRE engineer
Open-source builder
Observability & infrastructure enthusiast
Security-minded engineer

$ mission

Build       → systems that work
Secure      → systems that can be trusted
Observe     → systems that can be understood
Automate    → systems that can be operated
Improve     → systems that can evolve
```

## What I Build

I work at the intersection of **infrastructure, observability, security, and software engineering**.

My interests range from Linux and networking to containers, CI/CD, Kubernetes, distributed tracing, application performance, and security engineering.

I prefer learning by building complete systems:

> **Build it → instrument it → break it → investigate it → secure it → automate it.**

---

# 🚀 SarosObserv

### Open-source observability platform

**SarosObserv** is my most important open-source project.

The long-term goal is to build an independent, OpenTelemetry-native observability platform that can grow from a focused engineering project into a **large-scale open-source observability ecosystem**.

The ambition is not to build another dashboard.

It is to build the platform underneath the dashboard.

**SarosObserv aims to make it possible to:**

* ingest telemetry through OpenTelemetry / OTLP
* discover applications, services, endpoints, and dependencies
* explore distributed traces
* understand latency across service boundaries
* correlate telemetry signals
* query telemetry efficiently
* visualize system behavior
* progressively introduce metrics and logs
* provide developers and operators with useful application intelligence
* remain open, extensible, self-hostable, and community-driven

### Current architecture

```text
                    APPLICATIONS
                         │
                         │ OpenTelemetry
                         ▼
              ┌─────────────────────┐
              │  OpenTelemetry      │
              │     Collector       │
              └──────────┬──────────┘
                         │ OTLP
                         ▼
              ┌─────────────────────┐
              │    SarosObserv      │
              │     Go Backend      │
              └──────────┬──────────┘
                         │
                         ▼
                  ┌─────────────┐
                  │ ClickHouse  │
                  │    Storage  │
                  └──────┬──────┘
                         │
                         ▼
                  ┌─────────────┐
                  │  REST API   │
                  └──────┬──────┘
                         │
                         ▼
                  ┌─────────────┐
                  │ React / TS  │
                  │     UI      │
                  └─────────────┘
```

### Current engineering focus

**Backend**

`Go` · `OTLP` · `REST API` · `ClickHouse`

**Frontend**

`React` · `TypeScript`

**Infrastructure**

`Docker` · `Docker Compose`

**Observability**

`OpenTelemetry` · `Distributed Tracing`

### Long-term direction

```text
Traces
  │
  ├── Metrics
  │
  ├── Logs
  │
  ├── Service Discovery
  │
  ├── Dependency Mapping
  │
  ├── Performance Analysis
  │
  ├── Incident Detection
  │
  └── Root Cause Analysis
             │
             ▼
       Application Intelligence
```

The vision is to build something that can eventually serve the same broad class of engineering needs as platforms such as Grafana, while taking a different architectural path and developing its own identity.

**Repository:**
https://github.com/saros-dev/sarosobserv

---

# 🔬 DevOps Shop

A production-style application laboratory used to experiment with:

`Go` · `PostgreSQL` · `Docker` · `OpenTelemetry` · `Prometheus` · `Grafana` · `Tempo`

DevOps Shop is also one of the environments I use to develop and validate **SarosObserv**.

```text
DevOps Shop
     │
     ▼
OpenTelemetry
     │
     ▼
SarosObserv
     │
     ▼
Trace → Analyze → Understand
```

https://github.com/saros-dev/devops-shop

---

# 🛡️ Security & Red Team

Security is an important part of how I think about infrastructure.

I'm particularly interested in the **adversarial side of engineering**:

```text
Recon
  ↓
Enumeration
  ↓
Attack Surface
  ↓
Threat Modeling
  ↓
Controlled Testing
  ↓
Detection
  ↓
Remediation
  ↓
Hardening
```

Areas I'm exploring:

* Linux security and hardening
* Network security
* Web application security
* OWASP methodology
* Reconnaissance and enumeration
* Vulnerability assessment
* Container security
* Kubernetes security
* Identity and access control
* Secrets management
* DevSecOps
* Detection engineering
* Incident investigation

The objective isn't simply to learn how to exploit a system.

It's to understand **why the vulnerability exists, how it can be detected, how it can be remediated, and how the system can be made harder to compromise.**

All offensive-security work is performed only in systems I own or am explicitly authorized to assess.

---

# 🧰 Engineering Stack

### Systems

`Linux` · `Bash` · `Git` · `Networking`

### Development

`Go` · `Python`

### Infrastructure

`Docker` · `Kubernetes` · `Terraform` · `Ansible`

### CI/CD

`GitHub Actions` · `GitLab CI` · `Jenkins`

### Observability

`OpenTelemetry` · `Prometheus` · `Grafana` · `Tempo` · `Loki`

### Data

`PostgreSQL` · `ClickHouse`

### Security

`OWASP` · `Nmap` · `Wireshark` · Linux hardening · Container security · DevSecOps

---

# 📌 Selected Projects

### [SarosObserv](https://github.com/saros-dev/sarosobserv)

**Open-source observability platform**

Go · React · TypeScript · OpenTelemetry · ClickHouse

---

### [DevOps Shop](https://github.com/saros-dev/devops-shop)

**Application and observability laboratory**

Go · PostgreSQL · Docker · OpenTelemetry

---

### [DevOps Lab](https://github.com/saros-dev/devops-lab)

**Hands-on infrastructure and DevOps experiments**

Linux · Docker · CI/CD · Kubernetes · Observability

---

### [Linux Engineering Handbook](https://github.com/saros-dev/linux-engineering-handbook)

**Practical Linux engineering and troubleshooting knowledge base**

Linux · Networking · Bash · System Administration

---

### [GitHub Telegram Notify](https://github.com/saros-dev/github-telegram-notify)

**Event-driven GitHub automation**

GitHub · Python · Telegram

---

### [DevOps Task Manager](https://github.com/saros-dev/devops-task-manager)

**Application engineering and DevOps practice**

Go · Docker · CI/CD

---

# 🧠 How I Think About Engineering

```text
                         ┌───────────────┐
                         │    SYSTEM     │
                         └───────┬───────┘
                                 │
              ┌──────────────────┼──────────────────┐
              │                  │                  │
              ▼                  ▼                  ▼
           BUILD              SECURE             OBSERVE
              │                  │                  │
              └──────────────────┼──────────────────┘
                                 │
                                 ▼
                              OPERATE
                                 │
                                 ▼
                            INVESTIGATE
                                 │
                                 ▼
                              IMPROVE
```

I care less about collecting technology names and more about understanding:

* what a system is doing
* why it behaves that way
* where it can fail
* how it can be attacked
* how failures can be detected
* how operations can be automated
* how the system can be improved

---

# 🌱 Current Direction

```text
Linux & Networking
        ↓
Containers
        ↓
CI/CD
        ↓
Infrastructure Automation
        ↓
Kubernetes
        ↓
Security / DevSecOps
        ↓
OpenTelemetry
        ↓
Distributed Observability
        ↓
SRE
        ↓
Building SarosObserv
```

My current priority is going deeper rather than simply expanding the list.

---

# 🌍 Open Source

SarosObserv is intended to become a serious open-source project.

The long-term vision includes:

* a strong developer experience
* clear architecture
* reliable APIs
* comprehensive documentation
* automated testing
* secure defaults
* self-hosted deployments
* Docker and Kubernetes support
* extensibility
* community contributions
* an ecosystem around the platform

I want the project to grow through **engineering quality and community contribution**, not simply through a collection of features.

---

# 📫 Connect

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-saros--dev-181717?style=for-the-badge\&logo=github)](https://github.com/saros-dev)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Saros%20Shojaii-0A66C2?style=for-the-badge\&logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/saros-shojaiji/)

</div>

---

<div align="center">

### BUILD · SECURE · OBSERVE · AUTOMATE · IMPROVE

<sub>Open source • Infrastructure • Security • Observability</sub>

</div>
