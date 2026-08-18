# Awesome MCP Servers for DevOps with stars

> A curated list of Model Context Protocol servers for DevOps workflows — infrastructure, CI/CD, monitoring, security, and cloud operations.

**Curated by [Wagner](https://www.trywagner.dev)** — The first AI DevOps teammate

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=WagnerAgent/awesome-mcp-servers-devops\&type=date\&legend=top-left)](https://www.star-history.com/#WagnerAgent/awesome-mcp-servers-devops\&type=date\&legend=top-left)

## Contents

* [Source Control](#-source-control)
* [Infrastructure as Code](#%EF%B8%8F-infrastructure-as-code)
* [Kubernetes and Containers](#%EF%B8%8F-kubernetes-and-containers)
* [Command Line and Local Ops](#%EF%B8%8F-command-line-and-local-ops)
* [Browser Automation](#-browser-automation)
* [Code Execution](#%EF%B8%8F-code-execution)
* [Coding Agents](#-coding-agents)
* [Aggregators](#-aggregators)
* [CI/CD](#-cicd)
* [Cloud Platforms](#%EF%B8%8F-cloud-platforms)
* [Observability](#-observability)
* [Security](#-security)
* [Collaboration](#-collaboration)
* [Getting Started](#-getting-started)

## 🔀 Source Control

### GitHub

The official GitHub MCP server — battle-tested and feature-complete.

|                      |                                                                                                                      |
| -------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Repo**             | [github/github-mcp-server](https://github.com/github/github-mcp-server) ⭐ 32,319 \| 🐛 380 \| 🌐 Go \| 📅 2026-08-17 |
| **Maintainer**       | 🏷️ GitHub (Official)                                                                                                |
| **What it does**     | Repository operations, issues, PRs, code search, GitHub Actions workflows.                                           |
| **Standout feature** | 🛡️ Lockdown mode for public repos to prevent prompt injection.                                                      |

**Community options**

| Repo                                                                                                                           | Notes                                 |
| ------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------- |
| [ddukbg/github-enterprise-mcp](https://github.com/ddukbg/github-enterprise-mcp) ⭐ 29 \| 🐛 1 \| 🌐 TypeScript \| 📅 2025-09-14 | GitHub Enterprise API integration.    |
| [adhikasp/mcp-git-ingest](https://github.com/adhikasp/mcp-git-ingest) ⭐ 313 \| 🐛 10 \| 🌐 Python \| 📅 2025-01-26             | Read and analyze GitHub repositories. |

### GitLab

Native GitLab integration via their Duo platform.

|                  |                                                                                                               |
| ---------------- | ------------------------------------------------------------------------------------------------------------- |
| **Docs**         | [GitLab MCP Server Documentation](https://docs.gitlab.com/user/gitlab_duo/model_context_protocol/mcp_server/) |
| **Maintainer**   | 🏷️ GitLab (Official)                                                                                         |
| **What it does** | Issues, merge requests, pipelines, commits, cross-project search.                                             |
| **Note**         | ⚠️ Requires GitLab 18.6+ for HTTP transport.                                                                  |

**Community options**

| Repo                                                                                                                                                               | Notes                                   |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------- |
| [kopfrechner/gitlab-mr-mcp](https://github.com/kopfrechner/gitlab-mr-mcp) ⭐ 94 \| 🐛 4 \| 🌐 JavaScript \| 📅 2026-07-27                                           | Merge requests + issues for GitLab.     |
| [modelcontextprotocol/server-gitlab](https://github.com/modelcontextprotocol/servers/tree/main/server-gitlab) ⭐ 89,644 \| 🐛 527 \| 🌐 TypeScript \| 📅 2026-08-10 | Reference GitLab server implementation. |

### Azure DevOps

|                  |                                                                                                   |
| ---------------- | ------------------------------------------------------------------------------------------------- |
| **Repo**         | [tiberriver256/azure-devops-mcp-server](https://github.com/tiberriver256/azure-devops-mcp-server) |
| **Maintainer**   | 👥 Community                                                                                      |
| **What it does** | Repos, work items, pipelines, boards.                                                             |

**Community options**

| Repo                                                                                                                                               | Notes                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| [Tiberriver256/mcp-server-azure-devops](https://github.com/Tiberriver256/mcp-server-azure-devops) ⭐ 381 \| 🐛 39 \| 🌐 TypeScript \| 📅 2026-07-07 | Azure DevOps integration via MCP.            |
| [stefanskiasan/azure-devops-mcp-server](https://github.com/stefanskiasan/azure-devops-mcp-server) ⭐ 33 \| 🐛 1 \| 🌐 TypeScript \| 📅 2025-02-15   | Azure DevOps server for Cline.               |
| [Vortiago/mcp-azure-devops](https://github.com/Vortiago/mcp-azure-devops) ⭐ 79 \| 🐛 15 \| 🌐 Python \| 📅 2025-10-29                              | Azure DevOps via Python SDK.                 |
| [aaronsb/ado-mcp](https://github.com/aaronsb/ado-mcp) ⭐ 17 \| 🐛 2 \| 🌐 TypeScript \| 📅 2025-03-24                                               | Azure DevOps tools for pipelines/work items. |

### Gitea & Gitee

| Repo                                                                                                                                                         | Notes                                      |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------ |
| [gitea/gitea-mcp](https://gitea.com/gitea/gitea-mcp)                                                                                                         | MCP server for Gitea instances.            |
| [oschina/gitee](https://github.com/oschina/gitee)                                                                                                            | Gitee API integration.                     |
| [modelcontextprotocol/server-git](https://github.com/modelcontextprotocol/servers/tree/main/server-git) ⭐ 89,644 \| 🐛 527 \| 🌐 TypeScript \| 📅 2026-08-10 | Reference local Git server implementation. |

## 🏗️ Infrastructure as Code

### Terraform

HashiCorp's official MCP server for Terraform workflows.

|                  |                                                                                                                                |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| **Repo**         | [hashicorp/terraform-mcp-server](https://github.com/hashicorp/terraform-mcp-server) ⭐ 1,506 \| 🐛 46 \| 🌐 Go \| 📅 2026-08-18 |
| **Docs**         | [HashiCorp Developer](https://developer.hashicorp.com/terraform/mcp-server)                                                    |
| **Maintainer**   | 🏷️ HashiCorp (Official)                                                                                                       |
| **What it does** | Registry search, workspace management, plan/apply operations, state inspection.                                                |
| **Status**       | 🧪 Beta.                                                                                                                       |

**Community implementations**

| Repo                                                                                                                                              | Notes                                 |
| ------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| [dulltz/mcp-server-hcp-terraform](https://github.com/dulltz/mcp-server-hcp-terraform) ⚠️ Archived                                                 | Terraform Cloud/HCP focused.          |
| [guilhermeyoshida/mcp-terraform-assistant](https://github.com/guilhermeyoshida/mcp-terraform-assistant) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-08 | Local Terraform operations.           |
| [jashkahar/Terraform-MCP-Server](https://github.com/jashkahar/Terraform-MCP-Server) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2025-03-31                     | Exposes Terraform operations via MCP. |
| [nwiizo/tfmcp](https://github.com/nwiizo/tfmcp) ⭐ 371 \| 🐛 0 \| 🌐 Rust \| 📅 2026-08-13                                                         | Rust-based Terraform MCP server.      |
| [severity1/terraform-cloud-mcp](https://github.com/severity1/terraform-cloud-mcp) ⭐ 23 \| 🐛 3 \| 🌐 Python \| 📅 2025-11-02                      | Terraform Cloud API integration.      |
| [thrash888/terraform-mcp-server](https://github.com/thrash888/terraform-mcp-server)                                                               | Terraform Registry MCP server.        |
| [westonplatter/mcp-terraform-python](https://github.com/westonplatter/mcp-terraform-python) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-04             | Terraform operations in Python.       |

### Vault

Secrets management via MCP.

|                  |                                                                                                                     |
| ---------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [hashicorp/vault-mcp-server](https://github.com/hashicorp/vault-mcp-server) ⭐ 58 \| 🐛 21 \| 🌐 Go \| 📅 2026-08-17 |
| **Docs**         | [HashiCorp Developer](https://developer.hashicorp.com/vault/docs/mcp-server/overview)                               |
| **Maintainer**   | 🏷️ HashiCorp (Official)                                                                                            |
| **What it does** | Mount management, KV operations, secrets access.                                                                    |
| **Status**       | 🧪 Beta — ⚠️ secrets exposure requires trusted clients.                                                             |

### Pulumi

|                     |                                                                                      |
| ------------------- | ------------------------------------------------------------------------------------ |
| **Repo**            | [pulumi/mcp-server](https://github.com/pulumi/mcp-server)                            |
| **Docs**            | [Pulumi MCP Docs](https://www.pulumi.com/docs/iac/guides/ai-integration/mcp-server/) |
| **Maintainer**      | 🏷️ Pulumi (Official)                                                                |
| **What it does**    | Stack queries, resource search, Pulumi Cloud integration.                            |
| **Remote endpoint** | 🌐 `https://mcp.ai.pulumi.com/mcp`                                                   |

### OpenTofu

The open-source Terraform alternative has its own MCP server.

|                     |                                                                                                                                 |
| ------------------- | ------------------------------------------------------------------------------------------------------------------------------- |
| **Repo**            | [opentofu/opentofu-mcp-server](https://github.com/opentofu/opentofu-mcp-server) ⭐ 107 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-07-15 |
| **Maintainer**      | 🏷️ OpenTofu (Official)                                                                                                         |
| **What it does**    | Registry search, provider/module documentation, resource docs.                                                                  |
| **Remote endpoint** | 🌐 `mcp.opentofu.org`                                                                                                           |

### Multi-IaC

|                  |                                                                                              |
| ---------------- | -------------------------------------------------------------------------------------------- |
| **Repo**         | [stakpak/mcp](https://github.com/stakpak/mcp) ⭐ 18 \| 🐛 1 \| 🌐 JavaScript \| 📅 2026-07-04 |
| **What it does** | Terraform, Kubernetes, GitHub Actions, Dockerfile workflows.                                 |

## ☸️ Kubernetes and Containers

### Kubernetes

Several solid options exist — pick based on your needs.

#### containers/kubernetes-mcp-server

Native Go implementation, no kubectl dependency.

|                   |                                                                                                                                    |
| ----------------- | ---------------------------------------------------------------------------------------------------------------------------------- |
| **Repo**          | [containers/kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server) ⭐ 1,975 \| 🐛 95 \| 🌐 Go \| 📅 2026-08-18 |
| **Why choose it** | ⚡ Single binary, direct K8s API access, multi-cluster support.                                                                     |

#### Azure/mcp-kubernetes

Microsoft's implementation.

|                   |                                                                                                        |
| ----------------- | ------------------------------------------------------------------------------------------------------ |
| **Repo**          | [Azure/mcp-kubernetes](https://github.com/Azure/mcp-kubernetes) ⭐ 60 \| 🐛 7 \| 🌐 Go \| 📅 2026-08-11 |
| **Why choose it** | 🎯 Unified kubectl tool interface, minimal context consumption.                                        |

#### Flux159/mcp-server-kubernetes

Popular community option.

|                   |                                                                                                                                     |
| ----------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Repo**          | [Flux159/mcp-server-kubernetes](https://github.com/Flux159/mcp-server-kubernetes) ⭐ 1,569 \| 🐛 6 \| 🌐 TypeScript \| 📅 2026-08-08 |
| **Why choose it** | 🛡️ Non-destructive mode, secrets masking, easy Claude Code integration.                                                            |

#### alexei-led/k8s-mcp-server

Multi-tool support.

|                   |                                                                                                                       |
| ----------------- | --------------------------------------------------------------------------------------------------------------------- |
| **Repo**          | [alexei-led/k8s-mcp-server](https://github.com/alexei-led/k8s-mcp-server) ⭐ 213 \| 🐛 2 \| 🌐 Python \| 📅 2026-02-27 |
| **Why choose it** | 🧰 kubectl + helm + istioctl + argocd in one server.                                                                  |

#### Community Kubernetes servers

| Repo                                                                                                                          | Notes                                                                                                |
| ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------- |
| [rohitg00/kubectl-mcp-server](https://github.com/rohitg00/kubectl-mcp-server) ⭐ 952 \| 🐛 6 \| 🌐 Python \| 📅 2026-04-08     | Kubernetes CLI via MCP (read/write).                                                                 |
| [aadarshjain/kubectl-mcp-server](https://github.com/aadarshjain/kubectl-mcp-server) ⭐ 2 \| 🐛 1 \| 🌐 Python \| 📅 2025-09-06 | Local kubectl server (read-only by default).                                                         |
| [manusa/kubernetes-mcp-server](https://github.com/manusa/kubernetes-mcp-server) ⭐ 1,975 \| 🐛 95 \| 🌐 Go \| 📅 2026-08-18    | Kubernetes + OpenShift support.                                                                      |
| [strowk/mcp-k8s-go](https://github.com/strowk/mcp-k8s-go) ⭐ 386 \| 🐛 11 \| 🌐 Go \| 📅 2025-12-22                            | Go-based Kubernetes operations.                                                                      |
| [weibaohui/k8m](https://github.com/weibaohui/k8m) ⭐ 871 \| 🐛 25 \| 🌐 Go \| 📅 2026-08-14                                    | Multi-cluster management + UI.                                                                       |
| [weibaohui/kom](https://github.com/weibaohui/kom) ⭐ 149 \| 🐛 5 \| 🌐 Go \| 📅 2026-08-14                                     | SDK + multi-cluster operations.                                                                      |
| [wenhuwang/mcp-k8s-eye](https://github.com/wenhuwang/mcp-k8s-eye) ⭐ 28 \| 🐛 3 \| 🌐 Go \| 📅 2025-05-16                      | Cluster health analysis and ops.                                                                     |
| [kubestellar/console](https://github.com/kubestellar/console) ⭐ 128 \| 🐛 41 \| 🌐 TypeScript \| 📅 2026-08-18                | AI-powered multi-cluster management dashboard with MCP server (kc-agent) for AI-assisted operations. |

### Tilt

|                  |                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------- |
| **Repo**         | [rrmistry/tilt-mcp](https://github.com/rrmistry/tilt-mcp) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2026-03-08 |
| **What it does** | Tilt resources, logs, and dev workflow control.                                                     |

### Nomad

|                  |                                                                                                    |
| ---------------- | -------------------------------------------------------------------------------------------------- |
| **Repo**         | [kocierik/mcp-nomad](https://github.com/kocierik/mcp-nomad) ⭐ 58 \| 🐛 0 \| 🌐 Go \| 📅 2026-08-16 |
| **What it does** | Nomad cluster management and analysis.                                                             |

### Docker Hub

|                  |                                                                                                     |
| ---------------- | --------------------------------------------------------------------------------------------------- |
| **Repo**         | [docker/hub-mcp](https://github.com/docker/hub-mcp) ⭐ 159 \| 🐛 3 \| 🌐 TypeScript \| 📅 2026-07-30 |
| **Docs**         | [Docker Hub MCP](https://docs.docker.com/ai/mcp-catalog-and-toolkit/hub-mcp/)                       |
| **Maintainer**   | 🏷️ Docker (Official)                                                                               |
| **What it does** | 🐳 Image discovery, repository management, tag inspection.                                          |

### Portainer

|                  |                                                                                                                   |
| ---------------- | ----------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [portainer/portainer-mcp](https://github.com/portainer/portainer-mcp) ⭐ 214 \| 🐛 5 \| 🌐 Python \| 📅 2026-08-13 |
| **Maintainer**   | 🏷️ Portainer (Official)                                                                                          |
| **What it does** | Container management, deployments, environment operations.                                                        |
| **Note**         | 🛡️ Read-only mode available for safety.                                                                          |

### Qovery

|                   |                                                                            |
| ----------------- | -------------------------------------------------------------------------- |
| **Documentation** | [Qovery MCP configuration](https://www.qovery.com/docs/copilot/mcp-server) |
| **Maintainer**    | 🏷️ Qovery (Official)                                                      |
| **What it does**  | Cluster management, app deployments, security, self-service.               |
| **Note**          | Guardrails and permissions management included.                            |

## 🖥️ Command Line & Local Ops

Tools for executing commands or interacting with local environments safely.

| Repo                                                                                                                                                         | Notes                                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------------------ |
| [MladenSU/cli-mcp-server](https://github.com/MladenSU/cli-mcp-server) ⭐ 177 \| 🐛 10 \| 🌐 Python \| 📅 2025-07-04                                           | Secure CLI execution with policies.                                                                          |
| [g0t4/mcp-server-commands](https://github.com/g0t4/mcp-server-commands) ⭐ 231 \| 🐛 8 \| 🌐 TypeScript \| 📅 2026-07-29                                      | Run commands and scripts via MCP.                                                                            |
| [Harsh-2002/SSH-MCP](https://github.com/Harsh-2002/SSH-MCP) ⭐ 4 \| 🐛 0 \| 🌐 Go \| 📅 2026-02-17                                                            | Remote SSH/SFTP with 43 tools: Docker, monitoring, databases, file ops, VoIP diagnostics, jump host support. |
| [tumf/mcp-shell-server](https://github.com/tumf/mcp-shell-server) ⭐ 186 \| 🐛 0 \| 🌐 Python \| 📅 2026-08-15                                                | Shell command execution server.                                                                              |
| [ferrislucas/iterm-mcp](https://github.com/ferrislucas/iterm-mcp) ⭐ 567 \| 🐛 8 \| 🌐 TypeScript \| 📅 2025-09-20                                            | iTerm integration for macOS.                                                                                 |
| [OthmaneBlial/term\_mcp\_deepseek](https://github.com/OthmaneBlial/term_mcp_deepseek) ⭐ 17 \| 🐛 0 \| 🌐 Python \| 📅 2025-09-21                             | Terminal server for DeepSeek.                                                                                |
| [maxim-saplin/mcp\_safe\_local\_python\_executor](https://github.com/maxim-saplin/mcp_safe_local_python_executor) ⭐ 46 \| 🐛 1 \| 🌐 Python \| 📅 2025-07-17 | Safe local Python execution.                                                                                 |
| [wonderwhy-er/DesktopCommanderMCP](https://github.com/wonderwhy-er/DesktopCommanderMCP) ⭐ 9,336 \| 🐛 199 \| 🌐 TypeScript \| 📅 2026-08-14                  | Local file/process control.                                                                                  |
| [automateyournetwork/pyATS\_MCP](https://github.com/automateyournetwork/pyATS_MCP) ⭐ 79 \| 🐛 0 \| 🌐 Python \| 📅 2026-07-10                                | Cisco pyATS network automation.                                                                              |

## 🌐 Browser Automation

| Repo                                                                                                                                                     | Notes                                                                                                                         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- |
| [aircodelabs/grasp](https://github.com/aircodelabs/grasp) ⭐ 4 \| 🐛 0 \| 🌐 TypeScript \| 📅 2025-06-20                                                  | Self-hosted browser agent.                                                                                                    |
| [browserbase/mcp-server-browserbase](https://github.com/browserbase/mcp-server-browserbase) ⚠️ Archived                                                  | Cloud browser automation.                                                                                                     |
| [browsermcp/mcp](https://github.com/browsermcp/mcp) ⭐ 6,980 \| 🐛 147 \| 🌐 TypeScript \| 📅 2025-04-24                                                  | Local Chrome control.                                                                                                         |
| [Automata-Labs-team/MCP-Server-Playwright](https://github.com/Automata-Labs-team/MCP-Server-Playwright) ⭐ 298 \| 🐛 10 \| 🌐 JavaScript \| 📅 2025-06-05 | Playwright automation.                                                                                                        |
| [blackwhite084/playwright-plus-python-mcp](https://github.com/blackwhite084/playwright-plus-python-mcp) ⭐ 189 \| 🐛 5 \| 🌐 Python \| 📅 2025-01-07      | Playwright + Python.                                                                                                          |
| [executeautomation/playwright-mcp-server](https://github.com/executeautomation/playwright-mcp-server)                                                    | Playwright MCP server.                                                                                                        |
| [microsoft/playwright-mcp](https://github.com/microsoft/playwright-mcp) ⭐ 36,218 \| 🐛 1 \| 🌐 TypeScript \| 📅 2026-08-17                               | Official Playwright MCP.                                                                                                      |
| [co-browser/browser-use-mcp-server](https://github.com/co-browser/browser-use-mcp-server) ⭐ 842 \| 🐛 19 \| 🌐 Python \| 📅 2026-05-20                   | browser-use with SSE transport.                                                                                               |
| [eyalzh/browser-control-mcp](https://github.com/eyalzh/browser-control-mcp) ⭐ 315 \| 🐛 21 \| 🌐 TypeScript \| 📅 2026-07-24                             | Browser control MCP.                                                                                                          |
| [ndthanhdev/mcp-browser-kit](https://github.com/ndthanhdev/mcp-browser-kit) ⭐ 54 \| 🐛 8 \| 🌐 TypeScript \| 📅 2026-08-16                               | Browser automation toolkit.                                                                                                   |
| [kimtth/mcp-aoai-web-browsing](https://github.com/kimtth/mcp-aoai-web-browsing) ⭐ 34 \| 🐛 0 \| 🌐 Python \| 📅 2026-07-16                               | Web browsing MCP server.                                                                                                      |
| [scrapeless-ai/scrapeless-mcp-server](https://github.com/scrapeless-ai/scrapeless-mcp-server) ⭐ 168 \| 🐛 1 \| 🌐 TypeScript \| 📅 2025-09-23            | SERP and web data access.                                                                                                     |
| [getrupt/ashra-mcp](https://github.com/getrupt/ashra-mcp)                                                                                                | Browser automation server.                                                                                                    |
| [autonomous-testing/wopee-mcp](https://www.npmjs.com/package/wopee-mcp)                                                                                  | AI testing agents for web apps — dispatch test runs, analysis crawls, and AI agent tests, fetch artifacts and project status. |

## ⚙️ Code Execution

| Repo                                                                                                                                                                | Notes                           |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------- |
| [pydantic/pydantic-ai (mcp-run-python)](https://github.com/pydantic/pydantic-ai/tree/main/packages/mcp-run-python) ⭐ 19,357 \| 🐛 719 \| 🌐 Python \| 📅 2026-08-18 | Run Python in a sandbox.        |
| [yepcode/mcp-server-js](https://github.com/yepcode/mcp-server-js) ⭐ 46 \| 🐛 1 \| 🌐 TypeScript \| 📅 2026-03-17                                                    | Secure JS/Python sandbox.       |
| [alfonsograziano/node-code-sandbox-mcp](https://github.com/alfonsograziano/node-code-sandbox-mcp) ⭐ 157 \| 🐛 14 \| 🌐 TypeScript \| 📅 2025-11-24                  | Node.js Docker sandbox.         |
| [ckanthony/openapi-mcp](https://github.com/ckanthony/openapi-mcp) ⭐ 194 \| 🐛 8 \| 🌐 Go \| 📅 2026-03-21                                                           | Access APIs from OpenAPI specs. |

## 🤖 Coding Agents

| Repo                                                                                                                            | Notes                                                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------- |
| [bgauryy/octocode-mcp](https://github.com/bgauryy/octocode-mcp) ⭐ 913 \| 🐛 3 \| 🌐 TypeScript \| 📅 2026-08-12                 | GitHub research + analysis agent.                                                                                                |
| [oraios/serena](https://github.com/oraios/serena) ⭐ 28,149 \| 🐛 110 \| 🌐 Python \| 📅 2026-08-16                              | LSP-based coding agent.                                                                                                          |
| [ezyang/codemcp](https://github.com/ezyang/codemcp) ⭐ 1,607 \| 🐛 78 \| 🌐 Python \| 📅 2025-12-25                              | Simple coding agent MCP.                                                                                                         |
| [Wolfe-Jam/claude-faf-mcp](https://github.com/Wolfe-Jam/claude-faf-mcp) ⭐ 22 \| 🐛 1 \| 🌐 TypeScript \| 📅 2026-08-18          | Persistent project context tools.                                                                                                |
| [juehang/vscode-mcp-server](https://github.com/juehang/vscode-mcp-server) ⭐ 389 \| 🐛 13 \| 🌐 TypeScript \| 📅 2026-01-07      | VS Code workspace tooling.                                                                                                       |
| [doggybee/mcp-server-leetcode](https://github.com/doggybee/mcp-server-leetcode) ⭐ 44 \| 🐛 4 \| 🌐 TypeScript \| 📅 2025-04-02  | LeetCode problem access.                                                                                                         |
| [jinzcdev/leetcode-mcp-server](https://github.com/jinzcdev/leetcode-mcp-server) ⭐ 139 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-07-12 | LeetCode (global/China) access.                                                                                                  |
| [willibrandon/CursorMCPMonitor](https://github.com/willibrandon/CursorMCPMonitor) ⭐ 12 \| 🐛 0 \| 🌐 C# \| 📅 2025-03-12        | MCP monitoring for Cursor.                                                                                                       |
| [SKULLFIRE07/cortex-memory](https://github.com/SKULLFIRE07/cortex-memory) ⭐ 7 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-03-25         | Persistent AI memory for coding assistants. Auto-captures decisions, patterns, and context. VSCode extension + CLI + MCP server. |
| [claw-army/claude-node](https://github.com/claw-army/claude-node) ⭐ 6 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-04                     | Python subprocess bridge for Claude Code CLI.                                                                                    |
| [HendryAvila/Hoofy](https://github.com/HendryAvila/Hoofy) ⭐ 15 \| 🐛 0 \| 🌐 Go \| 📅 2026-03-12                                | Spec-driven dev companion with persistent memory, adaptive change pipeline, and Clarity Gate. 32 tools, single Go binary.        |

## 🔗 Aggregators

| Repo                                                                                                                                                     | Notes                                                                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [askbudi/roundtable](https://github.com/askbudi/roundtable) ⭐ 121 \| 🐛 7 \| 🌐 Python \| 📅 2025-10-06                                                  | Multi-assistant MCP hub.                                                                                                                                                     |
| [composiohq/rube](https://github.com/composiohq/rube)                                                                                                    | 500+ app integrations.                                                                                                                                                       |
| [julien040/anyquery](https://github.com/julien040/anyquery) ⭐ 1,759 \| 🐛 5 \| 🌐 Go \| 📅 2026-08-16                                                    | SQL over 40+ apps.                                                                                                                                                           |
| [metatool-ai/metatool-app](https://github.com/metatool-ai/metatool-app) ⭐ 2,609 \| 🐛 105 \| 🌐 TypeScript \| 📅 2026-06-22                              | MetaMCP with GUI.                                                                                                                                                            |
| [mindsdb/mindsdb](https://github.com/mindsdb/mindsdb) ⭐ 39,601 \| 🐛 2 \| 🌐 Makefile \| 📅 2026-08-13                                                   | Data unification + MCP.                                                                                                                                                      |
| [glenngillen/mcpmcp-server](https://github.com/glenngillen/mcpmcp-server) ⭐ 35 \| 🐛 3 \| 📅 2025-04-24                                                  | MCP server registry.                                                                                                                                                         |
| [wegotdocs/open-mcp](https://github.com/wegotdocs/open-mcp) ⭐ 368 \| 🐛 1 \| 🌐 Shell \| 📅 2026-08-17                                                   | Turn web APIs into MCP.                                                                                                                                                      |
| [PipedreamHQ/pipedream](https://github.com/PipedreamHQ/pipedream/tree/master/packages/mcp-server) ⭐ 11,627 \| 🐛 4,298 \| 🌐 JavaScript \| 📅 2026-08-17 | 2,500+ API integrations.                                                                                                                                                     |
| [VeriTeknik/pluggedin-mcp-proxy](https://github.com/VeriTeknik/pluggedin-mcp-proxy) ⭐ 134 \| 🐛 1 \| 🌐 TypeScript \| 📅 2026-05-10                      | Proxy + discovery layer.                                                                                                                                                     |
| [tigranbs/mcgravity](https://github.com/tigranbs/mcgravity) ⭐ 102 \| 🐛 1 \| 🌐 Rust \| 📅 2026-02-15                                                    | MCP load balancing.                                                                                                                                                          |
| [waystation-ai/mcp](https://github.com/waystation-ai/mcp) ⭐ 60 \| 🐛 1 \| 🌐 JavaScript \| 📅 2025-09-10                                                 | Connect MCP hosts to apps.                                                                                                                                                   |
| [sxhxliang/mcp-access-point](https://github.com/sxhxliang/mcp-access-point) ⭐ 183 \| 🐛 2 \| 🌐 Rust \| 📅 2026-03-11                                    | One-click MCP wrapper.                                                                                                                                                       |
| [Arch Tools](https://archtools.dev)                                                                                                                      | 53 production-ready AI tools via MCP with x402 USDC payments.                                                                                                                |
| [Not Human Search](https://nothumansearch.ai/mcp)                                                                                                        | Search engine indexing 1,900+ agent-first tools (MCP servers, OpenAPI, llms.txt). Tools for `search_sites`, `verify_mcp` (live JSON-RPC probe), `list_categories`, and more. |
| [The Stall](https://the-stall.intuitek.ai/mcp)                                                                                                           | 208 pay-per-call data capabilities via x402 USDC micropayments — market intel, crypto/DeFi analytics, infrastructure probes, financial data, and more. No API keys.          |

## 🚀 CI/CD

### Argo CD

GitOps deployment management via AI.

|                  |                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------- |
| **Repo**         | [akuity/argocd-mcp](https://github.com/akuity/argocd-mcp) ⭐ 557 \| 🐛 66 \| 🌐 TypeScript \| 📅 2026-08-11 |
| **Maintainer**   | 🏷️ Akuity (Official — Argo CD creators)                                                                   |
| **What it does** | Application listing, sync operations, resource trees, logs.                                                |
| **Transports**   | 📡 stdio, HTTP stream.                                                                                     |

### Jenkins

|                  |                                                                                                                          |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------ |
| **Repo**         | [jenkinsci/mcp-server-plugin](https://github.com/jenkinsci/mcp-server-plugin) ⭐ 105 \| 🐛 24 \| 🌐 Java \| 📅 2026-08-14 |
| **Plugin page**  | [Jenkins Plugin Index](https://plugins.jenkins.io/mcp-server/)                                                           |
| **Maintainer**   | 👥 Jenkins Community                                                                                                     |
| **What it does** | Build status, job triggers, console logs.                                                                                |
| **Requires**     | ⚠️ Jenkins 2.479+.                                                                                                       |

### GitHub Actions

|                  |                                                                                                       |
| ---------------- | ----------------------------------------------------------------------------------------------------- |
| **Repo**         | [Tiberriver256/mcp-server-github-actions](https://github.com/Tiberriver256/mcp-server-github-actions) |
| **Maintainer**   | 👥 Community                                                                                          |
| **What it does** | Workflow runs, logs, and pipeline management.                                                         |

### Codemagic (Mobile CI/CD)

|                  |                                                                                                                              |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [stefanoamorelli/codemagic-mcp](https://github.com/stefanoamorelli/codemagic-mcp) ⭐ 12 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-28 |
| **Maintainer**   | 👥 Community                                                                                                                 |
| **What it does** | Mobile CI/CD pipeline control.                                                                                               |

### DevOps Visibility

| Repo                                                                                                                 | Notes                                      |
| -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------ |
| [SBDI/mcp-devps-hub](https://github.com/SBDI/mcp-devps-hub) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-03                | End-to-end DevOps visibility.              |
| [gofireflyio/firefly-mcp](https://github.com/gofireflyio/firefly-mcp) ⭐ 16 \| 🐛 4 \| 🌐 TypeScript \| 📅 2026-04-13 | Cloud resource discovery and codification. |

### CI/CD Helpers

| Repo                                                                                                                 | Notes                          |
| -------------------------------------------------------------------------------------------------------------------- | ------------------------------ |
| [Acid-base/FastMCP-Proper](https://github.com/Acid-base/FastMCP-Proper) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-25    | MCP server with CI/CD tooling. |
| [lobehub/mcp-hello-world](https://github.com/lobehub/mcp-hello-world) ⭐ 22 \| 🐛 1 \| 🌐 JavaScript \| 📅 2025-06-20 | CI/CD test server.             |

### Build Tools

| Repo                                                                                                                 | Notes                                                                                                                        |
| -------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| [arvindand/maven-tools-mcp](https://github.com/arvindand/maven-tools-mcp) ⭐ 30 \| 🐛 2 \| 🌐 Java \| 📅 2026-07-13   | Maven and build tooling.                                                                                                     |
| [nowork-studio/toprank](https://github.com/nowork-studio/toprank) ⭐ 3,370 \| 🐛 11 \| 🌐 TypeScript \| 📅 2026-08-14 | NotFair Google Ads MCP server. Diagnose campaigns, recommend optimizations, execute approved changes via the Google Ads API. |

## ☁️ Cloud Platforms

### AWS

AWS provides a collection of MCP servers for their services.

|                |                                                                                               |
| -------------- | --------------------------------------------------------------------------------------------- |
| **Repo**       | [awslabs/mcp](https://github.com/awslabs/mcp) ⭐ 9,611 \| 🐛 268 \| 🌐 Python \| 📅 2026-08-17 |
| **Docs**       | [AWS MCP Servers](https://awslabs.github.io/mcp/)                                             |
| **Maintainer** | 🏷️ AWS (Official)                                                                            |
| **Includes**   | 📦 AWS API server, Documentation server, Knowledge server, Prometheus server.                 |

**Community options**

| Repo                                                                                                                  | Notes                     |
| --------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| [alexei-led/aws-mcp-server](https://github.com/alexei-led/aws-mcp-server) ⭐ 185 \| 🐛 1 \| 🌐 Python \| 📅 2026-02-27 | AWS CLI-based MCP server. |

### Azure

| Repo                                                                                                                                                     | Notes                         |
| -------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------- |
| [jdubois/azure-cli-mcp](https://github.com/jdubois/azure-cli-mcp)                                                                                        | Azure CLI wrapper.            |
| [hardik-id/azure-resource-graph-mcp-server](https://github.com/hardik-id/azure-resource-graph-mcp-server) ⭐ 18 \| 🐛 1 \| 🌐 TypeScript \| 📅 2025-05-06 | Azure Resource Graph queries. |
| [erikhoward/adls-mcp-server](https://github.com/erikhoward/adls-mcp-server) ⭐ 6 \| 🐛 3 \| 🌐 Python \| 📅 2025-05-31                                    | Azure Data Lake Storage.      |

### Cloudflare

Comprehensive coverage of Cloudflare's platform.

|                  |                                                                                                                                            |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------ |
| **Repo**         | [cloudflare/mcp-server-cloudflare](https://github.com/cloudflare/mcp-server-cloudflare) ⭐ 4,088 \| 🐛 59 \| 🌐 TypeScript \| 📅 2026-08-11 |
| **Docs**         | [Cloudflare Agents Docs](https://developers.cloudflare.com/agents/model-context-protocol/mcp-servers-for-cloudflare/)                      |
| **Maintainer**   | 🏷️ Cloudflare (Official)                                                                                                                  |
| **What it does** | ⚡ Workers, KV, R2, D1, observability.                                                                                                      |
| **Count**        | 📦 13 specialized MCP servers.                                                                                                             |

### Alibaba Cloud

|                    |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Repo**           | [aliyun/alibaba-cloud-ops-mcp-server](https://github.com/aliyun/alibaba-cloud-ops-mcp-server) ⭐ 126 \| 🐛 4 \| 🌐 Python \| 📅 2026-03-16                                                                                                                                                                                                                                                                                                                                             |
| **Maintainer**     | 🏷️ Alibaba Cloud (Official)                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **What it does**   | ECS, Cloud Monitor, OOS operations.                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Also available** | 📦 [ACK (Kubernetes)](https://github.com/aliyun/alibabacloud-ack-mcp-server) ⭐ 116 \| 🐛 8 \| 🌐 Python \| 📅 2026-07-31, [DataWorks](https://github.com/aliyun/alibabacloud-dataworks-mcp-server) ⭐ 50 \| 🐛 11 \| 🌐 TypeScript \| 📅 2026-06-16, [DMS](https://github.com/aliyun/alibabacloud-dms-mcp-server) ⭐ 52 \| 🐛 16 \| 🌐 Python \| 📅 2026-07-29, [Function Compute](https://github.com/aliyun/alibabacloud-fc-mcp-server) ⭐ 8 \| 🐛 8 \| 🌐 JavaScript \| 📅 2026-02-14. |

### Other Platforms

| Repo                                                                                                                   | Notes                              |
| ---------------------------------------------------------------------------------------------------------------------- | ---------------------------------- |
| [bright8192/esxi-mcp-server](https://github.com/bright8192/esxi-mcp-server) ⭐ 64 \| 🐛 6 \| 🌐 Python \| 📅 2025-07-01 | VMware ESXi/vCenter management.    |
| [thunderboltsid/mcp-nutanix](https://github.com/thunderboltsid/mcp-nutanix) ⭐ 14 \| 🐛 1 \| 🌐 Go \| 📅 2026-01-29     | Nutanix Prism Central integration. |

## 📊 Observability

### Grafana

|                  |                                                                                                                                                                    |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Repo**         | [grafana/mcp-grafana](https://github.com/grafana/mcp-grafana) ⭐ 3,367 \| 🐛 128 \| 🌐 Go \| 📅 2026-08-17                                                          |
| **Maintainer**   | 🏷️ Grafana Labs (Official)                                                                                                                                        |
| **What it does** | 📈 Dashboard queries, alerts, datasource info, incident management.                                                                                                |
| **Requires**     | ⚠️ Grafana 9.0+.                                                                                                                                                   |
| **Related**      | 📦 [Loki MCP](https://github.com/grafana/loki-mcp) ⭐ 165 \| 🐛 27 \| 🌐 Go \| 📅 2026-08-17, [Tempo MCP](https://github.com/grafana/tempo-mcp-server) ⚠️ Archived. |

### Datadog

|                  |                                                                                                                              |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [TANTIOPE/datadog-mcp-server](https://github.com/TANTIOPE/datadog-mcp-server) ⭐ 5 \| 🐛 15 \| 🌐 TypeScript \| 📅 2026-08-17 |
| **Maintainer**   | 👥 Community                                                                                                                 |
| **What it does** | 📊 Logs search, APM trace filtering, metrics queries, dashboards, monitors, incidents, SLOs, synthetics, and more.           |
| **Note**         | 📦 Available via `npx datadog-mcp` or Docker. Supports stdio + HTTP transports, read-only mode.                              |

### Prometheus

Several community implementations available.

| Repo                                                                                                                                   | Lang       | Notes                                |
| -------------------------------------------------------------------------------------------------------------------------------------- | ---------- | ------------------------------------ |
| [pab1it0/prometheus-mcp-server](https://github.com/pab1it0/prometheus-mcp-server) ⭐ 511 \| 🐛 8 \| 🌐 Python \| 📅 2026-08-05          | 🐍 Python  | ⭐ 177 stars, well-documented.        |
| [yshngg/prometheus-mcp-server](https://github.com/yshngg/prometheus-mcp-server) ⭐ 4 \| 🐛 1 \| 🌐 Go \| 📅 2026-08-04                  | 🏎️ Go     | ✅ 100% Prometheus API compatibility. |
| [idanfishman/prometheus-mcp](https://github.com/idanfishman/prometheus-mcp) ⭐ 27 \| 🐛 4 \| 🌐 TypeScript \| 📅 2026-02-09             | 📇 Node.js | 📡 stdio + HTTP transports.          |
| [etruong42/prometheus-mcp](https://github.com/etruong42/prometheus-mcp) ⭐ 1 \| 🐛 0 \| 🌐 Python \| 📅 2025-04-24                      | 🐍 Python  | Community implementation.            |
| [loginmqv/mcp-server-prometheus](https://github.com/loginmqv/mcp-server-prometheus)                                                    | 📇 Node.js | Prometheus MCP server.               |
| [CaesarYangs/prometheus\_mcp\_server](https://github.com/CaesarYangs/prometheus_mcp_server) ⭐ 34 \| 🐛 3 \| 🌐 Python \| 📅 2025-04-05 | 🐍 Python  | Prometheus MCP server.               |

AWS also provides a [Prometheus MCP Server](https://awslabs.github.io/mcp/servers/prometheus-mcp-server) for Amazon Managed Prometheus with SigV4 auth.

### VictoriaMetrics

|                  |                                                                                                                                                            |
| ---------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [VictoriaMetrics-Community/mcp-victoriametrics](https://github.com/VictoriaMetrics-Community/mcp-victoriametrics) ⭐ 214 \| 🐛 20 \| 🌐 Go \| 📅 2026-07-19 |
| **What it does** | VictoriaMetrics query + metrics access.                                                                                                                    |

### Alertmanager

|                  |                                                                                                                      |
| ---------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [kaznak/alertmanager-mcp](https://github.com/kaznak/alertmanager-mcp) ⭐ 10 \| 🐛 0 \| 🌐 TypeScript \| 📅 2025-03-28 |
| **What it does** | Alertmanager alerts and silences.                                                                                    |

### APM & Monitoring

| Repo                                                                                                                          | Notes                                                                                         |
| ----------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| [dynatrace-oss/dynatrace-mcp](https://github.com/dynatrace-oss/dynatrace-mcp) ⭐ 134 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-07-24 | Dynatrace monitoring integration.                                                             |
| [last9/last9-mcp-server](https://github.com/last9/last9-mcp-server) ⭐ 59 \| 🐛 13 \| 🌐 Go \| 📅 2026-08-17                   | Last9 observability.                                                                          |
| [Uptrack-App/uptrack-mcp](https://github.com/Uptrack-App/uptrack-mcp) ⭐ 0 \| 🐛 0 \| 🌐 JavaScript \| 📅 2026-05-06           | Uptime monitoring — 10 tools for monitor/incident management. Remote MCP (OAuth 2.0) + stdio. |

## 🔒 Security

### Snyk

Vulnerability scanning directly from your AI assistant.

|                  |                                                                                                                                                         |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Docs**         | [Snyk MCP Documentation](https://docs.snyk.io/cli-ide-and-ci-cd-integrations/snyk-cli/developer-guardrails-for-agentic-workflows/snyk-mcp-early-access) |
| **Maintainer**   | 🏷️ Snyk (Official)                                                                                                                                     |
| **What it does** | 🔍 Code scanning, dependency checks, container scanning, IaC analysis, SBOM generation.                                                                 |
| **Access**       | 💻 Via `snyk mcp` CLI command (v1.1296.2+).                                                                                                             |

### Semgrep

|                  |                                                            |
| ---------------- | ---------------------------------------------------------- |
| **Repo**         | [semgrep/mcp](https://github.com/semgrep/mcp) ⚠️ Archived  |
| **Docs**         | [Semgrep MCP Docs](https://semgrep.dev/docs/mcp)           |
| **Maintainer**   | 🏷️ Semgrep (Official)                                     |
| **What it does** | 🔍 Static analysis, OWASP scanning, custom rule execution. |
| **Remote**       | 🌐 `https://mcp.semgrep.ai` (no auth required).            |

### Community Security Servers

| Repo                                                                                                                                 | Notes                                                                                                           |
| ------------------------------------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------- |
| [LaurieWired/GhidraMCP](https://github.com/LaurieWired/GhidraMCP) ⭐ 9,813 \| 🐛 82 \| 🌐 Java \| 📅 2025-06-23                       | Ghidra reverse engineering.                                                                                     |
| [13bm/GhidraMCP](https://github.com/13bm/GhidraMCP) ⭐ 134 \| 🐛 3 \| 🌐 Java \| 📅 2026-06-06                                        | Ghidra analysis tools.                                                                                          |
| [BurtTheCoder/mcp-shodan](https://github.com/BurtTheCoder/mcp-shodan) ⭐ 157 \| 🐛 5 \| 🌐 TypeScript \| 📅 2026-03-31                | Shodan search + CVE data.                                                                                       |
| [BurtTheCoder/mcp-virustotal](https://github.com/BurtTheCoder/mcp-virustotal) ⭐ 145 \| 🐛 6 \| 🌐 TypeScript \| 📅 2026-05-24        | VirusTotal scanning.                                                                                            |
| [fr0gger/MCP\_Security](https://github.com/fr0gger/MCP_Security) ⭐ 51 \| 🐛 2 \| 🌐 Python \| 📅 2025-01-22                          | ORKL threat intelligence.                                                                                       |
| [girste/mcp-cybersec-watchdog](https://github.com/girste/mcp-cybersec-watchdog) ⭐ 53 \| 🐛 6 \| 🌐 Go \| 📅 2026-02-07               | Linux security audit.                                                                                           |
| [qianniuspace/mcp-security-audit](https://github.com/qianniuspace/mcp-security-audit) ⭐ 56 \| 🐛 1 \| 🌐 TypeScript \| 📅 2025-07-18 | npm dependency audits.                                                                                          |
| [rad-security/mcp-server](https://github.com/rad-security/mcp-server) ⭐ 6 \| 🐛 0 \| 🌐 TypeScript \| 📅 2026-08-14                  | Kubernetes security insights.                                                                                   |
| [roadwy/cve-search\_mcp](https://github.com/roadwy/cve-search_mcp) ⭐ 103 \| 🐛 1 \| 🌐 Python \| 📅 2025-07-26                       | CVE-Search API.                                                                                                 |
| [operantlabs/operant-mcp](https://github.com/operantlabs/operant-mcp) ⭐ 23 \| 🐛 1 \| 🌐 TypeScript \| 📅 2026-04-01                 | 51 security testing tools for pentesting, vulnerability scanning, and security auditing.                        |
| [securityfortech/secops-mcp](https://github.com/securityfortech/secops-mcp) ⭐ 207 \| 🐛 4 \| 🌐 Python \| 📅 2025-09-17              | Security testing toolbox.                                                                                       |
| [slouchd/cyberchef-api-mcp-server](https://github.com/slouchd/cyberchef-api-mcp-server) ⭐ 44 \| 🐛 0 \| 🌐 Python \| 📅 2026-04-03   | CyberChef API access.                                                                                           |
| [nickpending/mcp-recon](https://github.com/nickpending/mcp-recon) ⭐ 30 \| 🐛 0 \| 🌐 Go \| 📅 2025-04-22                             | Recon + domain analysis.                                                                                        |
| [Agnuxo1/EnigmAgent](https://github.com/Agnuxo1/EnigmAgent) ⭐ 4 \| 🐛 0 \| 🌐 Python \| 📅 2026-06-05                                | AES-256-GCM + Argon2id encrypted vault. Resolves `{{PLACEHOLDER}}` secrets so API keys never appear in prompts. |

## 📝 Collaboration

### Atlassian (Jira + Confluence)

|                  |                                                                                                                                      |
| ---------------- | ------------------------------------------------------------------------------------------------------------------------------------ |
| **Repo**         | [atlassian/atlassian-mcp-server](https://github.com/atlassian/atlassian-mcp-server) ⭐ 971 \| 🐛 82 \| 🌐 JavaScript \| 📅 2026-07-27 |
| **Docs**         | [Atlassian Remote MCP](https://www.atlassian.com/platform/remote-mcp-server)                                                         |
| **Maintainer**   | 🏷️ Atlassian (Official)                                                                                                             |
| **What it does** | 📋 Jira issues, Confluence pages, Compass integration, cross-product workflows.                                                      |
| **Security**     | 🔐 OAuth 2.0, respects existing permissions.                                                                                         |

Community alternative with Server/Data Center support: [sooperset/mcp-atlassian](https://github.com/sooperset/mcp-atlassian) ⭐ 5,756 | 🐛 186 | 🌐 Python | 📅 2026-08-18.

### Jira (Community)

|                  |                                                                                                                |
| ---------------- | -------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [nguyenvanduocit/jira-mcp](https://github.com/nguyenvanduocit/jira-mcp) ⭐ 96 \| 🐛 3 \| 🌐 Go \| 📅 2026-04-18 |
| **What it does** | Jira issue queries and updates.                                                                                |

### Project Management

|                  |                                                                                                                         |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [MervinPraison/praisonai-mcp](https://github.com/MervinPraison/praisonai-mcp) ⭐ 1 \| 🐛 1 \| 🌐 Python \| 📅 2026-01-13 |
| **What it does** | Project workflows via PraisonAI.                                                                                        |

### Service Desks

| Repo                                                                                                             | Notes                  |
| ---------------------------------------------------------------------------------------------------------------- | ---------------------- |
| [effytech/freshdesk\_mcp](https://github.com/effytech/freshdesk_mcp) ⭐ 66 \| 🐛 12 \| 🌐 Python \| 📅 2026-07-30 | Freshdesk integration. |
| [dbsanfte/topdesk-mcp](https://github.com/dbsanfte/topdesk-mcp) ⭐ 3 \| 🐛 0 \| 🌐 Python \| 📅 2025-07-02        | TOPdesk integration.   |

### Notion

|                  |                                                                                                                                     |
| ---------------- | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Repo**         | [makenotion/notion-mcp-server](https://github.com/makenotion/notion-mcp-server) ⭐ 4,593 \| 🐛 185 \| 🌐 TypeScript \| 📅 2026-07-25 |
| **Docs**         | [Notion MCP](https://developers.notion.com/docs/mcp)                                                                                |
| **Maintainer**   | 🏷️ Notion (Official)                                                                                                               |
| **What it does** | 📄 Page/database queries, content creation, workspace navigation.                                                                   |
| **Options**      | 🌐 Hosted server or 🏠 self-host via npm/Docker.                                                                                    |

## ⚡ Getting Started

### Basic Setup Pattern

Most MCP servers follow this configuration pattern for Claude Desktop or similar clients:

```json
{
  "mcpServers": {
    "server-name": {
      "command": "npx",
      "args": ["-y", "@org/mcp-server-package"]
    }
  }
}
```

For remote/hosted servers:

```json
{
  "mcpServers": {
    "server-name": {
      "type": "http",
      "url": "https://server-endpoint.example.com/mcp"
    }
  }
}
```

### 🛡️ Safety First

|     | Recommendation                                                                                        |
| --- | ----------------------------------------------------------------------------------------------------- |
| 1️⃣ | **Start read-only** — Most servers support read-only modes. Use them until you trust the integration. |
| 2️⃣ | **Scope permissions** — Use dedicated API tokens with minimal required access.                        |
| 3️⃣ | **Audit actions** — Log what your AI assistant does, especially for write operations.                 |
| 4️⃣ | **Test in staging** — Don't let AI touch production until you've validated behavior.                  |

## Contributing

Have a DevOps MCP server that should be here? See [contributing.md](contributing.md).

Requirements:

* ✅ Must have a working public repository or documentation.
* ✅ Must be relevant to DevOps workflows.
* ✅ Must include verified links.

## Resources

* [awesome](https://github.com/sindresorhus/awesome) ⭐ 497,054 | 🐛 102 | 📅 2026-06-30
* [awesome-mcp-servers](https://github.com/punkpeye/awesome-mcp-servers) ⭐ 92,495 | 🐛 3,104 | 📅 2026-08-17
* [MCP Reference Servers](https://github.com/modelcontextprotocol/servers) ⭐ 89,644 | 🐛 527 | 🌐 TypeScript | 📅 2026-08-10
* [FastMCP (jlowin)](https://github.com/jlowin/fastmcp) ⭐ 27,255 | 🐛 269 | 🌐 Python | 📅 2026-08-18
* [awesome-mcp-clients](https://github.com/punkpeye/awesome-mcp-clients) ⭐ 6,548 | 🐛 74 | 📅 2026-06-07
* [FastMCP (punkpeye)](https://github.com/punkpeye/fastmcp) ⭐ 3,249 | 🐛 18 | 🌐 TypeScript | 📅 2026-08-17
* [MCP Specification](https://modelcontextprotocol.io/)
* [Anthropic MCP Documentation](https://docs.anthropic.com/en/docs/agents-and-tools/mcp)

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Wagner](https://www.trywagner.dev) has waived all copyright and related rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
