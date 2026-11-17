<!-- Header banner -->
<p align="center">
  <img alt="Donna Nyagah, Lead DevSecOps Engineer" src="https://capsule-render.vercel.app/api?type=waving&height=200&color=0:0f2027,50:203a43,100:2c5364&text=Donna%20Nyagah&fontColor=ffffff&fontSize=60&fontAlignY=38&desc=Lead%20DevSecOps%20Engineer&descSize=22&descAlignY=60&section=header" />
</p>

<p align="center">
  <img alt="Location" src="https://img.shields.io/badge/Based%20in-Nairobi%2C%20Kenya-2c5364?style=flat-square" />
  <img alt="Availability" src="https://img.shields.io/badge/Open%20to-consulting%20%26%20roles-2ea44f?style=flat-square" />
</p>

I build secure delivery pipelines and container platforms, mostly on Azure and Kubernetes, and I lead a small DevOps team that supports several client platforms.

## What I work with

<p align="center">
  <img alt="Azure, AWS, Kubernetes, Docker, Terraform, GitLab, GitHub Actions" src="https://skillicons.dev/icons?i=azure,aws,kubernetes,docker,terraform,gitlab,githubactions&perline=7" />
</p>

<p align="center">
  <img alt="Azure DevOps" src="https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white" />
  <img alt="Helm" src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" />
  <img alt="Trivy" src="https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white" />
  <img alt="Docker Compose" src="https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="ingress-nginx" src="https://img.shields.io/badge/ingress--nginx-009639?style=flat-square" />
  <img alt="cert-manager" src="https://img.shields.io/badge/cert--manager-326CE5?style=flat-square" />
</p>

<details>
<summary>Full stack by area</summary>

| Area | Tools |
|---|---|
| Cloud | Azure (AKS, Azure DevOps, ACR, Entra ID), AWS (EC2, SSM, S3, Secrets Manager) |
| CI/CD | Azure DevOps, GitLab CI, GitHub Actions |
| Containers | Docker, Docker Compose, Kubernetes, Helm |
| Infrastructure as code | Terraform |
| Security | Trivy image scanning, least-privilege access, runtime secrets management, hardened container defaults |
| Documentation | High-level and low-level architecture documents, design decision records, runbooks |

</details>

## Selected work

Both projects are reference versions of patterns I built for a multi-service SaaS platform. Names, addresses and other specifics are placeholders.

<table>
<tr>
<td width="50%" valign="top">

### [GitLab CI/CD secure container pipeline](https://github.com/<your-username>/Gitlab-CI-CD-secure-container-pipeline)

Builds 11 images in parallel, scans each with Trivy, blocks the release on fixable HIGH or CRITICAL findings, and deploys to AWS through SSM with no SSH keys.

![GitLab CI](https://img.shields.io/badge/GitLab%20CI-FC6D26?style=flat-square&logo=gitlab&logoColor=white)
![Trivy](https://img.shields.io/badge/Trivy-1904DA?style=flat-square&logo=aqua&logoColor=white)
![AWS SSM](https://img.shields.io/badge/AWS%20SSM-232F3E?style=flat-square)

</td>
<td width="50%" valign="top">

### [Hardened Docker and Compose stack](https://github.com/<your-username>/<docker-stack-repo>)

Distroless non-root images, a read-only runtime with all capabilities dropped, and per-service NATS and Postgres credentials.

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Compose](https://img.shields.io/badge/Compose-2496ED?style=flat-square&logo=docker&logoColor=white)
![NATS](https://img.shields.io/badge/NATS%20JetStream-27AAE1?style=flat-square)

</td>
</tr>
</table>

## How I work

```mermaid
flowchart LR
    A[Assess<br/>current build and run setup] --> B[Codify<br/>infrastructure and pipelines as code]
    B --> C[Secure<br/>scan, restrict, rotate]
    C --> D[Document<br/>architecture and runbooks]
    D --> E[Hand over<br/>to the team that runs it]
```

## Leadership

I lead a DevOps team of two engineers across several client platforms. Client details stay private, so what you see here is rebuilt from scratch.

## Work with me

I'm open to consulting engagements and full-time roles.

<p align="center">
  <a href="mailto:nyacurunyagah@gmail.com"><img alt="Email me" src="https://img.shields.io/badge/Email-Get%20in%20touch-0b5fff?style=for-the-badge" /></a>
  <a href="www.linkedin.com/in/donna-nyagah"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-Connect-0a66c2?style=for-the-badge" /></a>
</p>

<p align="center">
  <img alt="" src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0f2027,50:203a43,100:2c5364&section=footer" />
</p>
