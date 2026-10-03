 <!--
-->

<div align="center">

<a href="https://github.com/saros-dev">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:0F172A,50:164E63,100:0891B2&text=SAROS&fontColor=FFFFFF&fontSize=68&fontAlignY=38&desc=DEVOPS%20%7C%20SRE%20%7C%20OBSERVABILITY&descAlignY=58&descSize=17&animation=fadeIn" width="100%" alt="Saros — DevOps, SRE and Observability"/>
</a>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&width=650&lines=Build+reliable+systems.;Instrument+every+critical+path.;Trace+requests.+Understand+latency.;Automate+the+repeatable.;Learn+by+building%2C+break+to+understand." alt="Animated engineering principles"/>
</a>

<br/>

<a href="https://github.com/saros-dev?tab=repositories">
  <img src="https://img.shields.io/badge/FOCUS-Engineering%20%26%20Automation-0F172A?style=for-the-badge" alt="Engineering and automation"/>
</a>
<a href="https://github.com/saros-dev/devops-shop">
  <img src="https://img.shields.io/badge/FLAGSHIP-DevOps%20Shop-0891B2?style=for-the-badge" alt="Flagship project"/>
</a>

</div>

---

## `$ whoami`

I'm Saros, an engineer focused on **DevOps, Site Reliability Engineering, and Observability**.

I enjoy understanding how systems work beneath the surface: how applications communicate, how infrastructure fails, where latency originates, and how automation makes deployments more repeatable.

My approach is hands-on:

* Build applications and infrastructure labs.
* Automate development and delivery workflows.
* Instrument applications to collect metrics and distributed traces.
* Investigate performance issues and system failures.
* Document findings so experiments become reusable engineering knowledge.

**My engineering philosophy:** Don't just make it work. Understand why it works, how it fails, and how to prove what's happening.

## `// currently_building`

### DevOps Shop

An evolving, hands-on DevOps and observability project built around a Go application, PostgreSQL, and an OpenTelemetry-based telemetry pipeline.

<div align="center">

<a href="https://github.com/saros-dev/devops-shop">
  <img src="https://img.shields.io/badge/Explore-DevOps%20Shop-0891B2?style=for-the-badge&logo=github&logoColor=white" alt="Explore DevOps Shop"/>
</a>

</div>

**Application layer**

* Go and REST API endpoints
* PostgreSQL integration
* Request handling and database interactions

**Observability layer**

* OpenTelemetry instrumentation and Collector
* Prometheus metrics
* Grafana dashboards
* Tempo distributed tracing

**Engineering objectives**

* Follow requests across application and database boundaries.
* Investigate latency using trace spans and database timing.
* Connect telemetry signals to make troubleshooting more effective.
* Build repeatable testing, delivery, and deployment workflows.

The goal is to move beyond *"the application is slow"* and identify which operation is slow, how much time it takes, and what the available telemetry can prove about the cause.

## `// system_architecture`

<div align="center">

```mermaid
flowchart TB
    U["Client / HTTP Request"] --> API["Go REST API"]
    API <--> DB[("PostgreSQL")]
    API -. "Traces and metrics" .-> OTEL["OpenTelemetry Collector"]
    DB -. "DB telemetry when instrumented" .-> OTEL
    OTEL --> P["Prometheus"]
    OTEL --> T["Tempo"]
    OTEL --> L["Loki (when configured)"]
    P --> G["Grafana"]
    T --> G
    L --> G

    classDef app fill:#164E63,stroke:#22D3EE,color:#FFFFFF
    classDef store fill:#1E293B,stroke:#64748B,color:#FFFFFF
    classDef observe fill:#312E81,stroke:#A5B4FC,color:#FFFFFF

    class API,OTEL app
    class DB store
    class P,T,L,G observe
```

<sub>Target architecture overview. Telemetry paths and log collection depend on the current implementation and configuration.</sub>

</div>

## `// technology_stack`

**Systems & development**

<a href="https://www.linux.org/"><img src="https://img.shields.io/badge/Linux-111827?style=flat-square&logo=linux&logoColor=FCC624" alt="Linux"/></a> <a href="https://git-scm.com/"><img src="https://img.shields.io/badge/Git-111827?style=flat-square&logo=git&logoColor=F05032" alt="Git"/></a> <a href="https://www.gnu.org/software/bash/"><img src="https://img.shields.io/badge/Bash-111827?style=flat-square&logo=gnubash&logoColor=4EAA25" alt="Bash"/></a> <a href="https://go.dev/"><img src="https://img.shields.io/badge/Go-111827?style=flat-square&logo=go&logoColor=00ADD8" alt="Go"/></a> <a href="https://www.python.org/"><img src="https://img.shields.io/badge/Python-111827?style=flat-square&logo=python&logoColor=3776AB" alt="Python"/></a>

**Containers & delivery**

<a href="https://www.docker.com/"><img src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker"/></a> <a href="https://docs.github.com/en/actions"><img src="https://img.shields.io/badge/GitHub%20Actions-111827?style=flat-square&logo=githubactions&logoColor=2088FF" alt="GitHub Actions"/></a> <a href="https://about.gitlab.com/topics/ci-cd/"><img src="https://img.shields.io/badge/GitLab%20CI-111827?style=flat-square&logo=gitlab&logoColor=FC6D26" alt="GitLab CI"/></a>

**Observability**

<a href="https://opentelemetry.io/"><img src="https://img.shields.io/badge/OpenTelemetry-111827?style=flat-square&logo=opentelemetry&logoColor=F5F5F5" alt="OpenTelemetry"/></a> <a href="https://prometheus.io/"><img src="https://img.shields.io/badge/Prometheus-111827?style=flat-square&logo=prometheus&logoColor=E6522C" alt="Prometheus"/></a> <a href="https://grafana.com/"><img src="https://img.shields.io/badge/Grafana-111827?style=flat-square&logo=grafana&logoColor=F46800" alt="Grafana"/></a> <a href="https://grafana.com/oss/tempo/"><img src="https://img.shields.io/badge/Tempo-111827?style=flat-square&logo=grafana&logoColor=F46800" alt="Grafana Tempo"/></a> <a href="https://www.postgresql.org/"><img src="https://img.shields.io/badge/PostgreSQL-111827?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL"/></a>

<sub>Technologies shown here reflect my hands-on work and current learning focus; they do not imply equal proficiency in every tool.</sub>

## `// featured_repositories`

| Project                                                                               | What you'll find                                          |
| ------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| [DevOps Shop](https://github.com/saros-dev/devops-shop)                               | Application engineering, PostgreSQL, and observability    |
| [DevOps Lab](https://github.com/saros-dev/devops-lab)                                 | Practical infrastructure and DevOps experiments           |
| [Linux Engineering Handbook](https://github.com/saros-dev/linux-engineering-handbook) | Linux administration, commands, and troubleshooting notes |
| [GitHub Telegram Notify](https://github.com/saros-dev/github-telegram-notify)         | GitHub event automation and notifications                 |
| [DevOps Task Manager](https://github.com/saros-dev/devops-task-manager)               | Application development and engineering practice          |

## `// engineering_principles`

```text
BUILD       → Create something that works.
INSTRUMENT  → Make its behavior observable.
TEST        → Verify expected behavior.
BREAK       → Reproduce realistic failure modes.
INVESTIGATE → Follow evidence, not assumptions.
AUTOMATE    → Make repeatable work reproducible.
DOCUMENT    → Turn findings into engineering knowledge.
```

## `// current_learning_path`

* Linux internals, networking, and troubleshooting
* Docker, container networking, and deployment workflows
* CI/CD with GitHub Actions and GitLab CI
* Infrastructure automation with Ansible and Terraform
* Kubernetes architecture, networking, and operations
* OpenTelemetry, distributed tracing, metrics, and logs
* SRE fundamentals, reliability, and incident investigation

## `// connect`

<div align="center">

<a href="https://github.com/saros-dev">
  <img src="https://img.shields.io/badge/GitHub-saros--dev-111827?style=for-the-badge&logo=github" alt="GitHub profile"/>
</a>

<br/><br/>

<sub>BUILD · OBSERVE · AUTOMATE · INVESTIGATE · REPEAT</sub>

</div>

<a href="https://capsule-render.vercel.app/">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0891B2,100:0F172A&height=100&section=footer" width="100%" alt="Decorative footer"/>
</a>
