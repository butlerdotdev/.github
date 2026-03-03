<p align="center">
  <a href="https://butlerlabs.dev"><img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/bl.png" alt="Butler Labs" width="100"/></a>
</p>

<h1 align="center">Butler Labs</h1>

<p align="center">
  <strong>Ship developer platforms in weeks, not years.</strong><br/>
  Open source tools for Kubernetes fleet management, hosted control planes, and internal developer platforms.
</p>

<p align="center">
  <a href="https://butlerlabs.dev">Website</a> &middot;
  <a href="https://docs.butlerlabs.dev">Docs</a> &middot;
  <a href="https://github.com/butlerdotdev/butler/discussions">Discussions</a> &middot;
  <a href="https://discord.gg/cAzWG9qz3K">Discord</a>
</p>

---

### What We Build

We build open source infrastructure tools that compress 12-18 month platform buildouts into weeks. Everything is Apache 2.0. No vendor lock-in, no surprise paywalls.

<table>
<tr>
<td align="center" width="33%">
<a href="https://github.com/butlerdotdev/butler"><img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/butler.png" alt="Butler" width="120"/></a><br/>
<strong><a href="https://github.com/butlerdotdev/butler">Butler</a></strong><br/>
Multi-cluster Kubernetes management. One CRD creates a complete tenant cluster with networking, storage, and addons across any infrastructure provider.
</td>
<td align="center" width="33%">
<a href="https://github.com/butlerdotdev/steward"><img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/steward.png" alt="Steward" width="120"/></a><br/>
<strong><a href="https://github.com/butlerdotdev/steward">Steward</a></strong><br/>
Hosted Kubernetes control planes. Run API servers as pods instead of dedicated VMs. Targeting CNCF Sandbox.
</td>
<td align="center" width="33%">
<a href="https://github.com/butlerdotdev/butler-portal"><img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/portal.png" alt="Butler Portal" width="120"/></a><br/>
<strong><a href="https://github.com/butlerdotdev/butler-portal">Butler Portal</a></strong><br/>
Internal Developer Platform built on Backstage. Service catalogs, golden paths, and self-service environments.
</td>
</tr>
</table>

### Repositories

| | Repository | What it does |
|---|------------|-------------|
| **Platform** | [butler](https://github.com/butlerdotdev/butler) | Project overview, architecture, governance |
| | [butler-controller](https://github.com/butlerdotdev/butler-controller) | Cluster lifecycle, IPAM, addon management |
| | [butler-api](https://github.com/butlerdotdev/butler-api) | CRD type definitions (the API contract) |
| | [butler-server](https://github.com/butlerdotdev/butler-server) | REST/WebSocket API backend |
| | [butler-console](https://github.com/butlerdotdev/butler-console) | Web UI for cluster management |
| | [butler-cli](https://github.com/butlerdotdev/butler-cli) | `butleradm` + `butlerctl` CLI tools |
| | [butler-charts](https://github.com/butlerdotdev/butler-charts) | Helm charts for all components |
| | [butler-bootstrap](https://github.com/butlerdotdev/butler-bootstrap) | Management cluster provisioning |
| **Control Plane** | [steward](https://github.com/butlerdotdev/steward) | Hosted control plane operator |
| | [capi-steward](https://github.com/butlerdotdev/cluster-api-control-plane-provider-steward) | Cluster API provider for Steward |
| **Ecosystem** | [butler-portal](https://github.com/butlerdotdev/butler-portal) | Backstage-based IDP |
| | [butler-image-factory](https://github.com/butlerdotdev/butler-image-factory) | OS image build and hosting service |

### Portal Ecosystem

Butler Portal ships with purpose-built plugins for the full platform engineering lifecycle.

<table>
<tr>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/chambers.png" alt="Chambers" width="80"/><br/>
<strong>Chambers</strong><br/>
Private dev environments. SSH access, editor deep links, dotfiles. No local setup required.
</td>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/keeper.svg" alt="Keeper" width="80"/><br/>
<strong>Keeper</strong><br/>
IaC registry and governance. Terraform modules, Helm charts, OPA policies, approval workflows.
</td>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/herald.svg" alt="Herald" width="80"/><br/>
<strong>Herald</strong><br/>
Telemetry routing at fleet scale. Visual pipeline builder for logs, metrics, and traces.
</td>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/alfred.svg" alt="Alfred" width="80"/><br/>
<strong>Alfred</strong><br/>
Answers from your infrastructure knowledge. Indexes docs, runbooks, and incident history.
</td>
<td align="center" width="20%">
<img src="https://raw.githubusercontent.com/butlerdotdev/.github/main/profile/assets/jeeves.svg" alt="Jeeves" width="80"/><br/>
<strong>Jeeves</strong><br/>
Proactive drift remediation. Declares desired state, detects drift, auto-remediates.
</td>
</tr>
</table>

### Infrastructure Providers

**Stable:** Harvester HCI, Nutanix AHV | **In Progress:** Proxmox VE, AWS, Azure, GCP

### Get Involved

- **[Getting Started](https://docs.butlerlabs.dev/butler/getting-started)** to deploy your first cluster
- **[Contributing Guide](https://github.com/butlerdotdev/butler/blob/main/CONTRIBUTING.md)** to start building with us
- **[GitHub Discussions](https://github.com/butlerdotdev/butler/discussions)** for questions and ideas
- **[Discord](https://discord.gg/cAzWG9qz3K)** for real-time conversation
