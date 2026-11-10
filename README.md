<div align="center">

# Marzena Kupniewska

**DevOps & Platform Engineering · Kubernetes · Infrastructure as Code · GitOps**

From virtual machines to declaratively managed Kubernetes platforms.

[GitHub](https://github.com/Marzena-Olga) · [Selected projects](#selected-projects) · [Beyond infrastructure](#beyond-infrastructure)

</div>

---

## About me

I build and operate on-premises Kubernetes platforms and automate infrastructure and application delivery. My work connects Linux administration, virtualization, networking, storage, and GitOps across development, staging, and production environments.

I use Terraform, Ansible, Helm, Argo CD, and GitLab CI/CD to make infrastructure and deployments repeatable. I work across the platform lifecycle: provisioning virtual machines, configuring clusters, integrating platform services, troubleshooting failures, and planning migrations and upgrades.

I also lead two development teams and share practical Kubernetes knowledge through internal workshops and documentation.

## Selected projects

### Infrastructure as Code

**[terraform-iac](https://github.com/Marzena-Olga/terraform-iac)**

Provisioning virtual machines for Kubernetes on Proxmox, including CPU, memory, disks, networking, and SSH access. The configuration also covers retrieving the Proxmox token from Passbolt.

`Terraform` · `Proxmox` · `Linux` · `Passbolt`

### GitOps platform bootstrap

**[argocd-bootstrap](https://github.com/Marzena-Olga/argocd-bootstrap)**

A Kubernetes platform bootstrap configuration in which Ansible performs the initial setup and Argo CD takes over ongoing management through a root Application and ApplicationSets. It brings monitoring, storage, database operators, certificates, and platform services into a declarative workflow.

`Argo CD` · `ApplicationSet` · `Ansible` · `Kubernetes` · `GitOps`

### ThingsBoard on Kubernetes

**[thingsboard-ce](https://github.com/Marzena-Olga/thingsboard-ce)**

A Helm chart for deploying ThingsBoard Community Edition through GitOps. It integrates with existing PostgreSQL, Cassandra, Redis, and Kafka services, secrets delivered from Passbolt through External Secrets Operator, Gateway API routing, and Prometheus monitoring.

`Helm` · `ThingsBoard CE` · `External Secrets Operator` · `Gateway API` · `Prometheus`

### Application delivery across environments

**[applicationset-generator](https://github.com/Marzena-Olga/applicationset-generator)**

ApplicationSet generation and deployment configuration for development, staging, and production. Shared Helm values and environment-specific overrides help keep application configuration consistent without duplicating entire charts.

`Argo CD` · `ApplicationSet` · `Helm` · `GitOps`

## Hands-on experience

| Area | Technologies and practical work |
| --- | --- |
| Infrastructure and automation | Debian / Linux, Proxmox, VMware, Terraform, Ansible |
| Kubernetes and delivery | kubeadm, containerd, Helm, Argo CD, ApplicationSets, GitLab CI/CD |
| Networking and traffic | Cilium, Envoy Gateway, Gateway API, HAProxy, Keepalived |
| Storage | Ceph, Longhorn, NFS CSI |
| Databases and messaging | PostgreSQL / CloudNativePG, PgBouncer, Kafka / Strimzi, Cassandra / K8ssandra, Redis / Valkey |
| Secrets and identity | Passbolt, External Secrets Operator, cert-manager, Keycloak |
| Observability | Prometheus, Grafana, Alertmanager, Loki, Hubble |

## How I work

- Keep infrastructure and deployment configuration in version control.
- Automate repeatable tasks and document operational decisions.
- Investigate issues across application, cluster, network, and storage layers.
- Validate upgrades and migrations before applying them to production.
- Build platform services that help development teams deploy and troubleshoot applications.

## Beyond infrastructure

I enjoy working on motorcycles and documenting practical solutions. This repository also includes my notes on adapting the lighting of a US-spec 2022 Indian Scout.

**[Indian Scout lighting guide — in Polish](https://Marzena-Olga.github.io/scout/)** · [Guide source](scout/index.html)

---

For repository structure, local preview, and editing instructions, see [DEVELOPMENT.md](DEVELOPMENT.md).
