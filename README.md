<h1 align="center">Gustavo Norymberg</h1>
<h3 align="center">Cloud Solutions Architect · AI Platform · Azure</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3500&pause=1000&color=0078D4&center=true&vCenter=true&width=640&lines=Enforcement+layer+for+AI+agents;Agent+governance+%C2%B7+least+privilege+%C2%B7+audit;Fifteen+years+of+network+security+before+agents;Zero-Trust+landing+zones+%C2%B7+everything+as+code" alt="tagline"/>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/gustavonorymberg/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:rhinom@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://gustavo.rhinojedi.dev"><img src="https://img.shields.io/badge/Website-gustavo.rhinojedi.dev-0E7490?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website"/></a>
  <img src="https://img.shields.io/badge/Israel-555555?style=for-the-badge&logo=googlemaps&logoColor=white" alt="Israel"/>
  <img src="https://img.shields.io/badge/Open_to-Principal_%2F_Staff_AI_roles-2ea44f?style=for-the-badge" alt="Open to work"/>
</p>

---

### 👋 About

Cloud solutions architect for AI platforms on Azure. I build **enforcement points for AI agents**: a gateway on Azure API Management that fails closed and logs every deny, and MCP servers with default-deny capabilities and audit. Before agents, **fifteen years in network security and operations**: DDoS defense and firewalls at national carriers, including a year inside a security vendor's R&D. Then cloud platforms, designed and taken to production. More at **[gustavo.rhinojedi.dev](https://gustavo.rhinojedi.dev)**.

### 🚀 What I build

- 🛡️ **Agent governance & AI security:** deny-by-default enforcement in front of agents · per-agent identity · fail-closed validation · every deny logged · human confirmation on writes
- 🤖 **Agentic systems:** MCP servers with per-agent default deny · agent tooling in daily use (MCP servers, skills and agents) · evaluation harnesses · a gate where reviewer agents must challenge every deliverable before release

### 📐 What I design and deliver

- 🧠 **LLM platforms:** high-level design for self-hosted open-weight LLM serving on AKS GPU (vLLM), with API Management as the model gateway and single audit point, and safety checks around agent orchestration
- ☁️ **Enterprise Azure:** Zero-Trust landing zones in production · hub-spoke networking · IaC (Terraform / AVM / ALZ) · CI/CD
- 🧭 **Delivery & leadership:** pre-sales → architecture → production · team leadership

### 🔐 Security roots

- 🌐 **Fifteen years of network security and operations:** DDoS defense and firewalls at national carriers · beta and field trials of security appliances inside a vendor's R&D, on customers' mirrored traffic · datacenter hosting and service assurance for enterprise customers

### 🧰 Toolbox

![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![AKS](https://img.shields.io/badge/AKS-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Azure DevOps](https://img.shields.io/badge/Azure_DevOps-0078D7?style=flat-square&logo=azuredevops&logoColor=white)

![MCP](https://img.shields.io/badge/MCP-000000?style=flat-square)
![RAG](https://img.shields.io/badge/RAG_%2F_vector-4B8BBE?style=flat-square)
![vLLM](https://img.shields.io/badge/vLLM-FF6F61?style=flat-square)
![Anthropic](https://img.shields.io/badge/Anthropic_API-D4A27F?style=flat-square)
![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white)
![Entra ID](https://img.shields.io/badge/Entra_ID_%2F_Zero--Trust-0078D4?style=flat-square)

![Network security](https://img.shields.io/badge/Network_security-7F1D1D?style=flat-square)
![DDoS defense](https://img.shields.io/badge/DDoS_defense-991B1B?style=flat-square)
![Firewalls](https://img.shields.io/badge/Firewalls-9A3412?style=flat-square)
![OPA / Rego](https://img.shields.io/badge/OPA_%2F_Rego-566366?style=flat-square)

### 📂 Featured

| | |
|---|---|
| 🚪 **[agent-gateway-apim](https://github.com/rhinolands/agent-gateway-apim)** | The enforcement point for AI agents on **Azure API Management**: Terraform/AVM, Entra **app-only identity**, validate-JWT, managed identity to the backend, rate-limit & audit. **CI-validated.** |
| 🤝 **[agent-gateway-a2a](https://github.com/rhinolands/agent-gateway-a2a)** | The **HLD/LLD + threat model** the gateway work is built on: single governed action surface, **per-agent app-only identity**, deny by default, an optional confirm step for dangerous tools, gateway-level audit. |
| 🤖 **[mcp-agent-starter](https://github.com/rhinolands/mcp-agent-starter)** | A minimal **MCP server** with the security model production agents need: capability checks with deny by default, audit log, two-step **propose and confirm** on writes. |
| 📐 **[azure-ai-platform-reference-architecture](https://github.com/rhinolands/azure-ai-platform-reference-architecture)** | A reference pattern for **production agentic AI on Azure**: self-hosted LLM serving (vLLM/AKS), MCP orchestration, model gateway, RAG, Zero-Trust. Now with a reproducible **[RAG security-trimming lab](https://github.com/rhinolands/azure-ai-platform-reference-architecture/tree/main/labs/rag-security-trimming)** on Microsoft's reference retrieval stack: document-level security trimming under the user's Entra identity on Azure AI Search. One ACL value changed flips a document between cited and trimmed. |
| 🧠 **[agent-knowledge-base](https://github.com/rhinolands/agent-knowledge-base)** | An **agent-readable KB** (concept/reference/log buckets) + a stdlib indexer that lints, chunks for RAG, and emits a capability map. Context engineering as code. |
| 🛡️ **[content-mask](https://github.com/rhinolands/content-mask)** | A **default-deny privacy gate** for AI-generated content: masks known names, blocks IPs, emails and phone numbers by default, plus any patterns in its map. |

---

<p align="center">
  <i>📍 Israel · open to <b>Principal / Staff AI architect</b> roles · let's build clouds that think.</i>
</p>
