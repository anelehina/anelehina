## Hi, I'm Anele 👋

**Cloud Platform & Infrastructure Engineer** in Johannesburg, South Africa. 5+ years designing, securing and running cloud, network and data-centre infrastructure, now going deep on DevOps and SRE: infrastructure as code, CI/CD, Kubernetes and observability.

I believe infrastructure should be **secure by default, reproducible from Git, and boring to operate**.

---

### 🏠 Currently building: [ikhaya-platform](https://github.com/anelehina/ikhaya-platform)

A single home server run like a small production platform. Nothing listens on the router: admin access goes through a Tailscale mesh VPN, monitoring data is pushed out to Grafana Cloud, and public sites will arrive through an outbound Cloudflare Tunnel.

| Phase | Theme | Status |
|---|---|---|
| 0 | Hardened Ubuntu host, Tailscale, PR-based Git workflow, Docker, self-hosted password manager | ✅ Done |
| 1 | Host as code with Ansible, DNS filtering, encrypted backups with tested restores | 🔨 In progress |
| 2 | k3s and a public edge through Cloudflare Tunnel, managed with Terraform | 📋 Planned |
| 3 | CI/CD and GitOps: GitHub Actions, image scanning, Argo CD | 📋 Planned |
| 4 | Observability: Grafana Cloud with Alloy, Prometheus and Loki, dead-man alerting | 🟢 Foundation live |
| 5 | Disaster recovery drills on AWS | 📋 Planned |

Every change lands through a reviewed pull request on a protected `main`. See the [architecture](https://github.com/anelehina/ikhaya-platform/blob/main/docs/architecture.md), the [decision records](https://github.com/anelehina/ikhaya-platform/tree/main/docs/adr) and the [first postmortem](https://github.com/anelehina/ikhaya-platform/blob/main/docs/postmortems/2026-10-19-wifi-outage.md).

---

### 🧰 What I work with

| Area | Tools |
|---|---|
| Cloud | AWS (EC2, ECS Fargate, Lambda, RDS/Aurora, S3, VPC, Route 53, CloudWatch, IAM, WAF, Network Firewall, MSK, SQS), GCP |
| Infrastructure as code | CloudFormation, Terraform, Ansible |
| Containers | Docker, Docker Compose, ECS, Kubernetes (k3s) |
| Networking | TCP/IP, DNS, routing, VPNs, VPC design, load balancing, Wireshark |
| Security | IAM, WAF, TLS, secrets management, vulnerability management, zero-trust access |
| Operations | Linux, VMware vSphere, monitoring, incident response, root-cause analysis |

### 📜 Certifications

![AWS Solutions Architect Associate](https://img.shields.io/badge/AWS-Solutions_Architect_Associate-232F3E?logo=amazonwebservices&logoColor=white)
![CCNP](https://img.shields.io/badge/Cisco-CCNP-1BA0D7?logo=cisco&logoColor=white)
![CCNA](https://img.shields.io/badge/Cisco-CCNA-1BA0D7?logo=cisco&logoColor=white)

**Next up:** HashiCorp Terraform Associate, then CKA.

---

### 🤝 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-anelehina-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anelehina)
