# Hi, I'm Parambir Singh 👋

**VoIP / Telecom Systems Engineer** — architecting, securing, and scaling cloud-based telecom platforms.

[![Live Resume](https://img.shields.io/badge/Live%20Resume-param--cloudtelecom.github.io-2dd4bf?style=for-the-badge)](https://param-cloudtelecom.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/parambir-singh-3b9a80bb/)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=Param-Cloudtelecom&show_icons=true&theme=tokyonight&hide_border=true&count_private=false)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Param-Cloudtelecom&layout=compact&theme=tokyonight&hide_border=true)

I work across the full voice stack: from raw SIP/RTP packets to multi-tenant Cloud PBX
orchestration. My focus is building telecom systems that are secure, observable, and built
to survive carrier-grade traffic.

```
SIP Signaling → SBC / NAT Traversal → TLS/SRTP → FreeSWITCH / Asterisk Core → CDR / Billing
                          ↑
                  PCAP / Wireshark / sngrep / Homer (HEP) — full call-flow visibility
```

## What I do

- **SIP & media engineering** — SIP signaling, RTP media flow design, TLS/SRTP encryption,
  NAT traversal, SBC logic, SIP trunking, multi-tenant Cloud PBX architecture
- **Platform engineering** — building and tuning FreeSWITCH and Asterisk deployments for
  enterprise and carrier-grade call volume, REST API integration, CDR pipelines into
  relational databases
- **Diagnostics** — PCAP analysis, Wireshark/tshark, sngrep, Homer/HEP, SIP ladder
  diagrams, end-to-end failure investigation across distributed, high-availability voice
  infrastructure
- **Automation & development** — C programming, performance tuning, telecom automation
  tooling, Docker-based service deployment, Linux systems administration
- **DevOps & IaC** — Terraform modules for AWS (VPC/ECS Fargate/RDS), GitHub Actions
  CI/CD with OIDC-federated deploys, Kubernetes/Helm with autoscaling and
  PodDisruptionBudgets

## Featured projects

| Project | What it shows |
|---|---|
| 🌍 [**terraform-aws-infra-modules**](https://github.com/Param-Cloudtelecom/terraform-aws-infra-modules) | Reusable Terraform modules for a VPC + ECS Fargate service + RDS Postgres stack — least-privilege security groups, autoscaling, secrets in Secrets Manager |
| 🔁 [**cicd-pipeline-aws-ecs**](https://github.com/Param-Cloudtelecom/cicd-pipeline-aws-ecs) | GitHub Actions pipeline: lint → test → build/push to ECR → deploy to ECS Fargate via OIDC, with automatic rollback on a failed deploy |
| ⎈ [**k8s-helm-service-deploy**](https://github.com/Param-Cloudtelecom/k8s-helm-service-deploy) | Production-shaped Helm chart — Deployment, HPA, PodDisruptionBudget, Ingress, locked-down non-root securityContext |
| 🔀 [**kamailio-sbc-router**](https://github.com/Param-Cloudtelecom/kamailio-sbc-router) | A Kamailio-based SIP Session Border Controller: multi-tenant routing, NAT traversal (rtpengine), TLS/SRTP termination, carrier failover via dispatcher module |
| ☎️ [**freeswitch-cloud-pbx**](https://github.com/Param-Cloudtelecom/freeswitch-cloud-pbx) | Multi-tenant FreeSWITCH dialplan + ESL automation layer with a REST API for call origination and a CDR pipeline into PostgreSQL |
| 📞 [**pjsip-sip-diagnostics**](https://github.com/Param-Cloudtelecom/pjsip-sip-diagnostics) | A pjsua2-based SIP test/diagnostic client for validating registration, call setup, and RTP quality against an SBC or trunk — built for the same kind of packet-level troubleshooting Wireshark/sngrep covers |
| 🤖 [**ai-voice-agent**](https://github.com/Param-Cloudtelecom/ai-voice-agent) | Real-time conversational AI agent that auto-answers FreeSWITCH calls — speech-to-text → LLM → text-to-speech streamed live into the call |
| 👥 [**teams-sip-bridge**](https://github.com/Param-Cloudtelecom/teams-sip-bridge) | Bridges Microsoft Teams Direct Routing to an on-prem SIP/FreeSWITCH Cloud PBX core |
| 🛡️ [**fortinet-voip-firewall**](https://github.com/Param-Cloudtelecom/fortinet-voip-firewall) | FortiGate config for SIP/RTP — the SIP ALG problem, firewall policy, and voice QoS prioritization |
| 📊 [**sip-pcap-analyzer**](https://github.com/Param-Cloudtelecom/sip-pcap-analyzer) | Parses SIP pcap captures into a per-call summary table — Call-ID, status, setup time, duration |
| 🐳 [**telecom-stack-docker**](https://github.com/Param-Cloudtelecom/telecom-stack-docker) | Containerized telecom stack: Kamailio + FreeSWITCH + PostgreSQL + Homer (HEP) monitoring, spun up with one compose file |
| 🚨 [**ghost-call-defense**](https://github.com/Param-Cloudtelecom/ghost-call-defense) | Detection and mitigation for nuisance/ghost SIP calls and scanning traffic at the SBC layer |
| 🔐 [**cloudflare-tunnel-voip-access**](https://github.com/Param-Cloudtelecom/cloudflare-tunnel-voip-access) | Secure Cloud PBX admin access via named Cloudflare Tunnel + Access (Zero Trust) — no exposed admin ports |
| ☁️ [**aws-mobile-call-api**](https://github.com/Param-Cloudtelecom/aws-mobile-call-api) | Serverless API Gateway + Lambda + DynamoDB backend for a mobile Cloud PBX app |
| 🐍 [**kazoo-crossbar-client**](https://github.com/Param-Cloudtelecom/kazoo-crossbar-client) | Python client for 2600Hz's KAZOO platform Crossbar REST API |
| 🧰 [**linux-voip-ops-toolkit**](https://github.com/Param-Cloudtelecom/linux-voip-ops-toolkit) | Trunk health checks, rotating SIP packet capture, system health reports, automated CDR backups |
| 📟 [**yealink-remote-phonebook**](https://github.com/Param-Cloudtelecom/yealink-remote-phonebook) | Live, server-generated company directory for Yealink desk phones via Remote Phone Book |
| 📖 [**voip-troubleshooting-playbook**](https://github.com/Param-Cloudtelecom/voip-troubleshooting-playbook) | A structured runbook for diagnosing one-way audio, jitter, registration failures, and dropped calls |
| 🔓 [**voip-phone-unlock-guide**](https://github.com/Param-Cloudtelecom/voip-phone-unlock-guide) | Vendor-lock removal guide for repurposing owned/decommissioned desk phones across PBX platforms |
| 📢 [**multicast-paging-system**](https://github.com/Param-Cloudtelecom/multicast-paging-system) | SIP multicast overhead paging across Yealink, Snom, Grandstream, and Cisco desk phones |
| 🅿️ [**voip-call-parking-announce**](https://github.com/Param-Cloudtelecom/voip-call-parking-announce) | FreeSWITCH call parking with automatic spoken slot announcement over overhead paging |
| ⚙️ [**voip-phone-provisioning-guides**](https://github.com/Param-Cloudtelecom/voip-phone-provisioning-guides) | Auto-provisioning guides for Yealink, Cisco, Grandstream, Avaya, and Snom |

See [all 22 repos →](https://github.com/Param-Cloudtelecom?tab=repositories)

## Certifications

- 🛡️ **Fortinet NSE 7 — Enterprise Firewall, 7.6 Administrator** — [verify on Credly](https://www.credly.com/badges/e05c5dac-0b35-4c0c-86ab-f686a7f9a02e/linked_in_profile)
- ☁️ **AWS Certified Cloud Practitioner** — [verify on Credly](https://www.credly.com/badges/0c2037ca-8781-428c-8499-b1e4c5fd1e36/linked_in_profile)
- 🌐 **CompTIA Network+ ce Certification** — [verify on Credly](https://www.credly.com/badges/e9627e55-c843-4fdd-8759-5e979d6a0117/linked_in_profile)

## Background

- **VoIP Engineer / Telecommunications Technician** — Cloud telecom & UCaaS services
  provider, Canada (2021 – Present). SIP trunking, multi-tenant Cloud PBX support,
  FreeSWITCH/Asterisk platform engineering, packet-level troubleshooting for
  carrier-grade voice traffic.
- **IT Support Specialist** — BECCOS India (2020 – 2021). C programming, TCP/IP
  networking fundamentals.
- **B.E., Electrical and Electronics Engineering** — Sant Longowal Institute of
  Engineering and Technology (2014 – 2018).

## Tools & technologies

`FreeSWITCH` `Asterisk` `Kamailio` `pjsip` `SIP/RTP` `TLS/SRTP` `Wireshark` `tshark`
`sngrep` `Homer (HEP)` `Docker` `Linux` `PostgreSQL` `C` `Python` `REST APIs` `Cloudflare`
`rtpengine` `KAZOO / Crossbar API` `AWS (Lambda, API Gateway, DynamoDB, ECS Fargate, RDS)` `FortiGate / FortiOS`
`Zero Trust (Cloudflare Access)` `Bash` `Git` `Nginx` `DNS`
`SIP Multicast Paging` `Auto-Provisioning (Yealink/Cisco/Grandstream/Avaya/Snom)`
`CDR / Billing Pipelines` `sngrep` `TCP/IP` `Windows/Linux Interop`
`Terraform` `Kubernetes` `Helm` `GitHub Actions` `OIDC` `HorizontalPodAutoscaler`

---

📫 Open to VoIP/network engineering roles where deep protocol-level skill actually matters.
