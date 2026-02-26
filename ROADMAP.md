# Course Roadmap

## Visual Overview

```mermaid
graph TD
    M00[00 Pre-Course<br>Web Fundamentals] --> M01[01 Foundations<br>DevOps Philosophy]
    M01 --> M02[02 Linux<br>Command Line]
    M01 --> M03[03 Networking<br>TCP/IP & DNS]
    M02 --> M04[04 Python Basics<br>Scripting]
    M02 --> M05[05 Git & GitHub<br>Version Control]
    M04 --> M06[06 Python Advanced<br>OOP & APIs]
    M03 --> M07[07 AWS<br>Cloud Services]
    M05 --> M07
    M06 --> M08[08 Docker<br>Containers]
    M07 --> M08
    M05 --> M09[09 CI/CD<br>Pipelines]
    M08 --> M09
    M08 --> M10[10 Kubernetes<br>Orchestration]
    M10 --> M11[11 Helm<br>K8s Packaging]
    M07 --> M12[12 Terraform<br>IaC]
    M10 --> M13[13 ArgoCD<br>GitOps]
    M09 --> M13
    M02 --> M14[14 Ansible<br>Config Management]
    M09 --> M15[15 Jenkins<br>Build Automation]
    M10 --> M16[16 Grafana<br>Monitoring]

    style M00 fill:#2d6a4f,color:#fff
    style M01 fill:#2d6a4f,color:#fff
    style M02 fill:#404040,color:#fff
    style M03 fill:#404040,color:#fff
    style M04 fill:#404040,color:#fff
    style M05 fill:#404040,color:#fff
    style M06 fill:#404040,color:#fff
    style M07 fill:#404040,color:#fff
    style M08 fill:#404040,color:#fff
    style M09 fill:#404040,color:#fff
    style M10 fill:#404040,color:#fff
    style M11 fill:#404040,color:#fff
    style M12 fill:#404040,color:#fff
    style M13 fill:#404040,color:#fff
    style M14 fill:#404040,color:#fff
    style M15 fill:#404040,color:#fff
    style M16 fill:#404040,color:#fff
```

Green = Complete | Gray = Upcoming

## Module Descriptions

| Module | What You Learn | Prerequisites |
|--------|---------------|---------------|
| **00 Pre-Course** | HTML, CSS, JavaScript basics via SoloLearn | None |
| **01 Foundations** | What DevOps actually is, SDLC, team dynamics, production mindset | 00 |
| **02 Linux** | Terminal, filesystem, permissions, shell scripting | 01 |
| **03 Networking** | TCP/IP stack, DNS, HTTP, ports, firewalls | 01 |
| **04 Python Basics** | Variables, loops, functions, file I/O, scripting | 02 |
| **05 Git & GitHub** | Branches, merges, PRs, collaboration workflows | 02 |
| **06 Python Advanced** | OOP, REST APIs, automation, testing | 04 |
| **07 AWS** | EC2, S3, VPC, IAM, core cloud patterns | 03, 05 |
| **08 Docker** | Images, containers, Compose, networking | 06, 07 |
| **09 CI/CD** | Pipeline design, GitHub Actions, deployment strategies | 05, 08 |
| **10 Kubernetes** | Pods, services, deployments, ConfigMaps | 08 |
| **11 Helm** | Charts, values, templating, releases | 10 |
| **12 Terraform** | Providers, resources, state, modules | 07 |
| **13 ArgoCD** | GitOps principles, app-of-apps, sync strategies | 09, 10 |
| **14 Ansible** | Inventory, playbooks, roles, idempotency | 02 |
| **15 Jenkins** | Jenkinsfile, agents, shared libraries | 09 |
| **16 Grafana** | Prometheus, dashboards, alerts, SLOs | 10 |

## Learning Path Tracks

**Core Path**: 00 -> 01 -> 02 -> 04 -> 05 -> 08 -> 09 -> 10

**Cloud Track**: 03 -> 07 -> 12

**GitOps Track**: 09 -> 13

**Monitoring Track**: 10 -> 16
