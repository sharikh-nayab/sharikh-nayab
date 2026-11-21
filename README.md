<h1 align="center">Sharikh Nayab</h1>
<p align="center">DevOps · Site Reliability · Observability</p>

<p align="center">
  <a href="https://linkedin.com/in/sharikh-nayab-0633921b1"><img src="https://img.shields.io/badge/LinkedIn-sharikh--nayab-0A66C2?logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:sharikhn545@gmail.com"><img src="https://img.shields.io/badge/Email-sharikhn545%40gmail.com-D14836?logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Pune,%20India-UTC%2B5:30-555555" alt="Location">
  <img src="https://img.shields.io/badge/Open%20to-remote%20%7C%20relocation-2EA043" alt="Open to work">
</p>

Four years running production Kubernetes on Azure and AWS, most of it on the
observability side: Dynatrace, Prometheus, Grafana, and the alerting and
on-call practice around them. I like platforms where the alert that pages you
has a runbook, the dashboard matches the alert, and the whole thing is in git.

```js
const sharikh = {
  role:      "DevOps / Site Reliability Engineer",
  location:  "Pune, India (IST, UTC+5:30)",
  cloud:     ["Azure", "AWS"],
  platform:  ["Kubernetes", "AKS", "EKS", "OpenShift", "Helm", "ArgoCD"],
  iac:       ["Terraform", "Ansible", "ARM"],
  cicd:      ["Azure DevOps", "GitHub Actions", "GitLab CI", "Jenkins"],
  observability: {
    dynatrace: ["OneAgent", "DQL", "PurePath", "RUM", "Synthetic", "Davis AI"],
    oss:       ["Prometheus", "Grafana", "OpenTelemetry", "Alertmanager", "Tempo"],
    logs:      ["Splunk", "ELK", "Kibana"],
  },
  scripting: ["Python", "Bash", "PowerShell"],
  certs:     ["CKA", "AZ-400", "AZ-104", "HashiCorp Terraform Associate"],
};
```

<p align="center">
  <img src="https://skillicons.dev/icons?i=azure,aws,kubernetes,terraform,docker,prometheus,grafana,githubactions,jenkins,ansible,python,bash,linux,git&perline=14" alt="tools" />
</p>

## Projects

| | |
|---|---|
| **[aks-observability-platform](https://github.com/sharikh-nayab/aks-observability-platform)** | AKS with Terraform, Dynatrace (cloudNativeFullStack) and kube-prometheus-stack. Alert rules with a runbook for each, a golden-signals dashboard, and a load generator that proves the alerts fire. The setup I've converged on at work, written down. |
| **[otel-slo-lab](https://github.com/sharikh-nayab/otel-slo-lab)** | Kubernetes observability lab on kind: OpenTelemetry tail sampling, Sloth-generated multi-window burn-rate SLO alerts, in-process fault injection, and an incident walkthrough from pager to root cause. Five ADRs on the non-obvious choices. |
| **[StockFlow](https://github.com/sharikh-nayab/StockFlow)** | Inventory API in FastAPI + SQLAlchemy + Alembic. Where I practise the application side so I understand what I'm operating. |

## What I've been doing

- Built and run an Azure platform (AKS, Web Apps, Functions) provisioned with
  Terraform and instrumented end to end with Dynatrace: custom metrics,
  tagging rules, management zones, log processing, DQL workflows and
  role-specific dashboards.
- Cut deployment time by 40% and delivered zero-downtime Java releases on AKS
  by rebuilding Azure DevOps pipelines.
- Caught 85% of performance regressions before users saw them, mostly through
  Davis AI anomaly detection, PurePath tracing and Prometheus alerting with
  real runbooks behind it.
- Automated the boring parts of ops in Python and PowerShell (VM lifecycle,
  snapshots, vCenter provisioning), cutting manual work by around 60%.

## Certifications

<p>
  <img src="https://img.shields.io/badge/CKA-Certified%20Kubernetes%20Administrator-326CE5?logo=kubernetes&logoColor=white" alt="CKA">
  <img src="https://img.shields.io/badge/AZ--400-Azure%20DevOps%20Engineer%20Expert-0078D4?logo=microsoftazure&logoColor=white" alt="AZ-400">
  <img src="https://img.shields.io/badge/AZ--104-Azure%20Administrator%20Associate-0078D4?logo=microsoftazure&logoColor=white" alt="AZ-104">
  <img src="https://img.shields.io/badge/HashiCorp-Terraform%20Associate%20(003)-7B42BC?logo=terraform&logoColor=white" alt="Terraform Associate">
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=sharikh-nayab&show_icons=true&hide_border=true&theme=github_dark&hide_title=true&include_all_commits=true" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sharikh-nayab&layout=compact&hide_border=true&theme=github_dark&hide=jupyter%20notebook,html,css,javascript" height="150" alt="languages" />
</p>
