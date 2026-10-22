<div align="center">
  <img src="assets/hero.svg" alt="Meet Soni — I make infrastructure behave like a product." width="100%" />

  <p>
    <a href="https://meet-soni.pages.dev/"><img src="https://img.shields.io/badge/PORTFOLIO-visit-0e7490?style=for-the-badge&labelColor=0b1422" alt="Portfolio" /></a>
    <a href="https://linkedin.com/in/meets0ni"><img src="https://img.shields.io/badge/LINKEDIN-connect-2563eb?style=for-the-badge&labelColor=0b1422" alt="LinkedIn" /></a>
    <a href="https://github.com/meetsoni-dev"><img src="https://img.shields.io/badge/GITHUB-explore-a3e635?style=for-the-badge&labelColor=0b1422" alt="GitHub" /></a>
  </p>
</div>

<img src="assets/divider.svg" alt="" width="100%" />

## `01 / THE WORK`

I'm a DevOps / Platform Engineer working where **software delivery meets production reality**.

I like the unglamorous, high-leverage work: removing friction from releases, making infrastructure repeatable, figuring out why a system is failing, and making the next incident less mysterious than the last.

I don't collect tools for the sake of it. I use them to make systems easier to ship, understand, secure, and afford.

## `02 / SIGNAL, NOT NOISE`

<table>
  <tr>
    <td width="33%" valign="top">
      <img src="https://img.shields.io/badge/01-CLOUD_COST-0e7490?style=flat-square" alt="Cloud cost" /><br/>
      <strong>−70% monthly AWS spend</strong><br/>
      <sub>One environment went from roughly $10k to $3k/month after workload and managed-service cost analysis.</sub>
    </td>
    <td width="33%" valign="top">
      <img src="https://img.shields.io/badge/02-DELIVERY-65a30d?style=flat-square" alt="Delivery" /><br/>
      <strong>10+ hours → 3–4 hours</strong><br/>
      <sub>Reduced CI/CD setup effort per service through reusable workflows and shared deployment patterns.</sub>
    </td>
    <td width="33%" valign="top">
      <img src="https://img.shields.io/badge/03-RECOVERY-0891b2?style=flat-square" alt="Recovery" /><br/>
      <strong>Database restored. No data lost.</strong><br/>
      <sub>Worked through a Kubernetes/PostgreSQL storage incident by protecting and recovering the surviving data.</sub>
    </td>
  </tr>
</table>

<img src="assets/divider.svg" alt="" width="100%" />

## `03 / HOW I THINK ABOUT DELIVERY`

<div align="center">
  <img src="assets/delivery-map.svg" alt="Delivery system: commit, verify, package, promote, observe, improve, with security policy and telemetry feedback." width="100%" />
</div>

A pipeline is not just a sequence of YAML steps. It's a system of controls and feedback:

- **Commit → verify:** repeatable builds, tests, and security checks.
- **Package → promote:** traceable artifacts, environment boundaries, and GitOps.
- **Observe → improve:** useful telemetry, actionable alerts, and evidence-led incident response.

## `04 / THE TOOLBOX`

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,azure,gcp,kubernetes,docker,terraform,jenkins,githubactions,git,prometheus,grafana,python,bash,go&perline=7" alt="Icons for AWS, Azure, GCP, Kubernetes, Docker, Terraform, Jenkins, GitHub Actions, Git, Prometheus, Grafana, Python, Bash, and Go" />
</p>

| SYSTEM | THINGS I BUILD WITH |
|:--|:--|
| **Cloud & compute** | AWS · Azure · GCP · EKS · AKS · GKE |
| **Infrastructure** | Terraform · Helm · Kustomize · Karpenter |
| **Delivery & GitOps** | GitHub Actions · Jenkins · Azure DevOps · Argo CD · Argo Rollouts |
| **Observability** | Prometheus · Grafana · Loki · ELK · PagerDuty |
| **Security** | Trivy · SonarQube · Fortify · IAM/RBAC · secret management |
| **Traffic & data** | Gateway API · Istio · NGINX · PostgreSQL · Redis · Kafka |
| **Automation & AIOps** | Python · Bash · Go · n8n · AWS Bedrock |

<img src="assets/divider.svg" alt="" width="100%" />

## `05 / SELECTED WORK`

### [Kubernetes CI pipeline ↗](https://github.com/Meet-S0ni/kubernetescode)
**Build lane.** Jenkins pipeline for building and packaging a containerized Python application.

`Jenkins` `Docker` `Git`

### [Kubernetes GitOps manifests ↗](https://github.com/Meet-S0ni/kubernetesmanifest)
**Deploy lane.** Kubernetes manifests managed through Argo CD, separating application delivery from the build pipeline.

`Kubernetes` `Argo CD` `GitOps`

### [Azure Kubernetes infrastructure ↗](https://github.com/PredictiveResearchPtyLtd/milana-infra-as-code)
**Infrastructure lane.** Open-source Terraform work covering AKS, ACR, ingress, and Grafana monitoring.

`Azure` `Terraform` `AKS`

### More than happy-path engineering

Some of the most useful work happens when reality disagrees with the diagram:

- **A network path that looked open but wasn't:** traced private-to-public service connectivity to the actual translated source address.
- **A noisy incident becomes a useful signal:** built an event-driven diagnostic workflow that gathers Kubernetes context and produces structured RCA output.
- **A platform grows without every service becoming a snowflake:** standardized reusable delivery patterns across 25+ services and 15+ repositories.

*These are sanitized summaries. Client names, private architecture details, and sensitive incident specifics are intentionally omitted.*

## `06 / OPERATING PRINCIPLES`

<details>
  <summary><strong>What I optimize for</strong></summary>

  - **Boring releases.** A deployment should be repeatable, observable, and reversible.
  - **Evidence before intervention.** Metrics, logs, events, and dependency paths before a blind restart.
  - **Guardrails over heroics.** Good defaults, least privilege, automated checks, and clear ownership.
  - **Cost with context.** Optimize the workload and its actual usage—not just the invoice.
  - **Learning that compounds.** Turn incidents into runbooks, automation, and better system design.
</details>

## `07 / FIND ME ELSEWHERE`

<p align="center">
  <a href="https://meet-soni.pages.dev/"><img src="https://img.shields.io/badge/↗_PORTFOLIO-0e7490?style=for-the-badge" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/meets0ni"><img src="https://img.shields.io/badge/↗_LINKEDIN-2563eb?style=for-the-badge" alt="LinkedIn" /></a>
  <a href="https://www.credly.com/users/meet-soni"><img src="https://img.shields.io/badge/↗_CREDENTIALS-7c3aed?style=for-the-badge" alt="Credly" /></a>
  <a href="https://stackoverflow.com/users/17133721"><img src="https://img.shields.io/badge/↗_STACK_OVERFLOW-f97316?style=for-the-badge" alt="Stack Overflow" /></a>
</p>

<div align="center">
  <sub>Infrastructure is a product. Production is the user.</sub>
</div>
