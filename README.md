<div align="center">

# Marzena Kupniewska

**DevOps / SRE · Kubernetes · Infrastructure as Code · GitOps**

Od maszyn wirtualnych do deklaratywnie zarządzanej platformy Kubernetes.

[Profil GitHub](https://github.com/Marzena-Olga) · [Projekty](#wybrane-projekty) · [Po godzinach](#po-godzinach)

</div>

---

## O mnie

Zajmuję się budową i utrzymaniem platform Kubernetes on-premises oraz automatyzacją infrastruktury i wdrożeń. Łączę Terraform, Ansible, Helm, Argo CD i GitLab CI/CD, aby zarządzać środowiskami DEV, STAGE i PROD w powtarzalny sposób.

Najbliższe są mi praktyczne zadania: przygotowanie infrastruktury, uruchomienie usług platformowych, zarządzanie sekretami, monitoring i niezawodność środowisk.

## Wybrane projekty

### 01 · Infrastruktura jako kod

**[terraform-iac](https://github.com/Marzena-Olga/terraform-iac)**

Automatyzacja przygotowania maszyn wirtualnych pod Kubernetes na Proxmox: tworzenie VM z szablonów, konfiguracja CPU, pamięci, dysków i sieci oraz kont użytkowników z kluczami SSH. Konfiguracja obejmuje również pobieranie tokena Proxmox z Passbolt.

`Terraform` · `Proxmox` · `Kubernetes` · `Passbolt`

### 02 · Platforma zarządzana przez GitOps

**[argocd-bootstrap](https://github.com/Marzena-Olga/argocd-bootstrap)**

Konfiguracja startowa platformy Kubernetes. Po inicjalizacji przez Ansible zarządzanie przejmuje Argo CD, wykorzystując root Application i ApplicationSets. Repozytorium obejmuje między innymi monitoring, storage, operatory baz danych, certyfikaty oraz usługi platformowe.

`Argo CD` · `ApplicationSet` · `Ansible` · `Kubernetes` · `GitOps`

### 03 · ThingsBoard na Kubernetes

**[thingsboard-ce](https://github.com/Marzena-Olga/thingsboard-ce)**

Chart Helm do wdrażania ThingsBoard Community Edition w modelu GitOps. Integruje aplikację z istniejącymi usługami PostgreSQL, Cassandra, Redis i Kafka, sekretami z Passbolt przez External Secrets Operator, Gateway API oraz monitoringiem Prometheus.

`Helm` · `ThingsBoard CE` · `External Secrets` · `Gateway API` · `Prometheus`

### 04 · Konfiguracja wdrożeń dla wielu środowisk

**[applicationset-generator](https://github.com/Marzena-Olga/applicationset-generator)**

Projekt związany z generowaniem ApplicationSets i organizacją wdrożeń aplikacji dla DEV, STAGE i PROD. Dokumentacja opisuje wspólne wartości chartu Helm oraz osobne nadpisania dla środowisk, dzięki którym nie trzeba powielać całej konfiguracji aplikacji.

`Argo CD` · `ApplicationSet` · `Helm` · `DEV / STAGE / PROD`

## Obszary pracy

| Obszar | Technologie |
| --- | --- |
| Infrastruktura i automatyzacja | Proxmox, Terraform, Ansible, Linux |
| Platforma i wdrożenia | Kubernetes, Helm, Argo CD, GitLab CI/CD |
| Dane i storage | PostgreSQL / CloudNativePG, Kafka / Strimzi, Cassandra, Redis, Rook / Ceph |
| Sekrety i obserwowalność | Passbolt, External Secrets Operator, Prometheus, Grafana |

## Po godzinach

Lubię pracę przy motocyklu i dokumentowanie praktycznych rozwiązań. W tym repozytorium znajdziesz także moje notatki z adaptacji oświetlenia Indian Scouta 2022 w wersji amerykańskiej.

**[Przeczytaj instrukcję: Światła Indian Scout](https://Marzena-Olga.github.io/scout/)** · [Kod instrukcji](scout/index.html)

---

Informacje o strukturze strony, podglądzie lokalnym i edycji znajdziesz w [DEVELOPMENT.md](DEVELOPMENT.md).
