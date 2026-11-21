# Sharikh Nayab

DevOps / SRE engineer in Pune, India. Four years running production Kubernetes
on Azure and AWS, with most of that time spent on the observability side:
Dynatrace, Prometheus, Grafana, and the alerting and on-call practice around
them.

```js
const sharikh = {
  role:      "DevOps / Site Reliability Engineer",
  location:  "Pune, India (IST, UTC+5:30)",
  cloud:     ["Azure", "AWS"],
  platform:  ["Kubernetes", "AKS", "EKS", "OpenShift", "Helm", "ArgoCD"],
  iac:       ["Terraform", "Ansible", "ARM"],
  cicd:      ["Azure DevOps", "GitHub Actions", "GitLab CI", "Jenkins"],
  observability: {
    dynatrace:  ["OneAgent", "DQL", "PurePath", "RUM", "Synthetic", "Davis AI"],
    oss:        ["Prometheus", "Grafana", "OpenTelemetry", "Alertmanager", "Tempo"],
    logs:       ["Splunk", "ELK", "Kibana"],
  },
  scripting: ["Python", "Bash", "PowerShell"],
  certs:     ["CKA", "AZ-400", "AZ-104", "HashiCorp Terraform Associate"],
  openTo:    ["remote (EU / Gulf / US overlap)", "relocation"],
};
```

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

## Projects

| | |
|---|---|
| [aks-observability-platform](https://github.com/sharikh-nayab/aks-observability-platform) | AKS with Terraform, Dynatrace (cloudNativeFullStack) and kube-prometheus-stack. Alert rules with a runbook for each, a golden-signals dashboard, and a load generator that proves the alerts fire. The setup I've converged on at work, written down. |
| [otel-slo-lab](https://github.com/sharikh-nayab/otel-slo-lab) | Kubernetes observability lab on kind: OpenTelemetry tail sampling, Sloth-generated multi-window burn-rate SLO alerts, in-process fault injection, and an incident walkthrough from pager to root cause. Five ADRs on the non-obvious choices. |
| [StockFlow](https://github.com/sharikh-nayab/StockFlow) | Inventory API in FastAPI + SQLAlchemy + Alembic. Where I practise the application side so I understand what I'm operating. |

## Certifications

- Certified Kubernetes Administrator (CKA), The Linux Foundation
- Microsoft Certified: Azure DevOps Engineer Expert (AZ-400)
- Microsoft Certified: Azure Administrator Associate (AZ-104)
- HashiCorp Certified: Terraform Associate (003)

## Contact

[LinkedIn](https://linkedin.com/in/sharikh-nayab-0633921b1) · sharikhn545@gmail.com

---

<p>
  <img src="https://github-readme-stats.vercel.app/api?username=sharikh-nayab&show_icons=true&hide_border=true&theme=github_dark&hide_title=true" height="150" alt="stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sharikh-nayab&layout=compact&hide_border=true&theme=github_dark&hide=jupyter%20notebook,html,css" height="150" alt="languages" />
</p>
