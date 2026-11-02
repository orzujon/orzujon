# Orzujon Ahrorov

### Platform Engineer · SRE · Building AI Infrastructure

I work on **platform reliability, infrastructure automation and safe operations** for complex systems. My professional background is in financial-services platforms—Kubernetes/OpenShift, Cloud Foundry, CI/CD and incident response. Outside work, I'm building a GPU-backed AI incident investigation platform and a reproducible Kubernetes lab.

**Interested in:** AI Platform Engineer · Senior Platform Engineer · Site Reliability Engineer roles (UK and international).

> **What I bring:** experience operating enterprise platforms, the ability to build and test automation, and a preference for evidence over assumptions. I care about what happens when deployments fail—not just when demos work.

## Start here: engineering evidence

| Project | The engineering problem | Inspect the work |
| --- | --- | --- |
| **[Sentinel AI Platform](https://github.com/orzujon/sentinel-ai-platform)** | How can an AI-assisted incident workflow retrieve relevant operational knowledge **without treating model output as verified fact**? Local GPU inference, a FastAPI service, retrieval, mechanical checks and synthetic evaluations. | [Architecture and decisions](https://github.com/orzujon/sentinel-ai-platform/blob/main/docs/portfolio-case-study.md) · [Evaluation failure analysis](https://github.com/orzujon/sentinel-ai-platform/blob/main/evaluations/2026-10-24-four-case-baseline.md) |
| **[Sentinel infrastructure](https://github.com/orzujon/sentinel-ai-platform/tree/main/infrastructure)** | How do you provision and validate an isolated Kubernetes environment without touching protected VMs? PowerShell/Hyper-V, Ubuntu, Ansible, kubeadm, network checks and approval-gated reconciliation. | [Provisioning stages](https://github.com/orzujon/sentinel-ai-platform/blob/main/infrastructure/level1/README.md) · [Validation playbook](https://github.com/orzujon/sentinel-ai-platform/blob/main/infrastructure/ansible/playbooks/150-active-network.yml) |
| **[KubeMedic](https://github.com/orzujon/kubemedic)** | How can a support engineer diagnose Kubernetes pod failures **without making changes**? A Python CLI that produces deterministic findings and next investigation steps. | [Diagnostic rules](https://github.com/orzujon/kubemedic/blob/main/src/kubemedic/checks/pods.py) · [Unit tests](https://github.com/orzujon/kubemedic/tree/main/tests) |
| **[GKE / Terraform](https://github.com/orzujon/DevOps-GKE)** | How do you deploy workloads using infrastructure as code and workload identity rather than static cloud credentials? | [Implementation levels](https://github.com/orzujon/DevOps-GKE/tree/main/learning) · [GitHub Actions](https://github.com/orzujon/DevOps-GKE/tree/main/.github/workflows) |
| **[OpsField](https://github.com/orzujon/platform-troubleshooting-hub)** | How can engineers systematically investigate Linux, networking and Kubernetes incidents? A static interactive workbench with decision trees, runbooks and scenario practice. | **[Try the live workbench](https://orzujon.github.io/platform-troubleshooting-hub/)** |

Also: [Branch Protection Checker](https://github.com/orzujon/repository-audit) — a Python proof of concept for GitHub governance auditing, with documented fix/reset limitations.

## Experience beyond public GitHub

Most enterprise platform code cannot be published, so here is the work behind the repositories:

- **Platform migrations and operations:** worked across OpenShift/Kubernetes and Cloud Foundry environments, including an OpenShift 3-to-4 migration programme and controlled workload/namespace retirement.
- **Operational automation:** built Ruby-based automation integrating ticket-driven requests with Concourse tasks, including unit tests and code-quality checks. The implementation is employer-internal; the public repos demonstrate similar design principles without disclosing internal code.
- **Production diagnosis:** investigated application and routing issues using logs, deployment state and monitoring rather than assuming a healthy pod or process means a healthy service.
- **Engineering guidance:** act as a technical first point of contact for junior engineers, helping with objectives, safe operational practices and knowledge sharing.

**Core toolkit:** Kubernetes · OpenShift · Cloud Foundry · GKE · Linux · networking · Terraform · Ansible · Helm · Python · PowerShell · Ruby · Bash · GitHub Actions · Concourse · Jenkins · Prometheus/Thanos · Datadog

**Certification:** Certified Kubernetes Administrator (CKA).

## A principle I try to engineer into every tool

```text
Observe -> collect evidence -> check assumptions -> propose a change
        -> require approval -> apply only to owned resources -> verify
```

I favour reproducible test cases, explicit failure states, safe defaults and audit records. My labs are **independent experimental projects**, not production services or claims of enterprise-scale AI deployment. Their READMEs and case studies separate implemented behaviour, measured evidence and unfinished milestones.

## Get in touch

[LinkedIn](https://www.linkedin.com/in/orzujona/) · [Email](mailto:ahrorovor@gmail.com) · [Repositories](https://github.com/orzujon?tab=repositories)

**Open to discussing roles focused on secure, reliable platform infrastructure and the systems needed to operate AI workloads.**
