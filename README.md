<div align="center">

<img src="https://readme-typing-svg.demolab.com?lines=Linux+sysadmin+%C2%B7+8+years+in+web+hosting;cPanel%2FWHM+at+fleet+scale;OpenResty+%2F+Nginx+edge+automation;Python+eBPF+and+XDP;CVE+mitigation+%2B+monitoring&font=Fira+Code&size=24&duration=3200&pause=900&center=true&vCenter=true&width=520&height=150&color=7AA2F7" alt="Linux sysadmin, 8 years in web hosting; cPanel/WHM at fleet scale; OpenResty/Nginx edge automation; Python eBPF and XDP; CVE mitigation and monitoring" />

**Nizar Akbar Meilani** — Yogyakarta, Indonesia

[![LinkedIn](https://img.shields.io/badge/LinkedIn-nizarakbarm-0a66c2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/nizarakbarm)
[![Email](https://img.shields.io/badge/email-nizarakbarm04%40gmail.com-333333?style=flat&logo=gmail&logoColor=white)](mailto:nizarakbarm04@gmail.com)

</div>

## 💻 What I do

Sysadmin at DomaiNesia, 8 years in web hosting operations — 4 of them running large-scale cPanel/WHM fleets. I automate OpenResty/Nginx edge and provisioning config, and write the security and monitoring tooling that runs on top: Icinga plugins, ModSecurity rule scoping, malware remediation, Cloudflare onboarding.

## 🔭 Currently

- Python eBPF tracing — benchmarking BCC C-string runtime against Python-BPF AST AOT on the same tracepoint. Two decks shipped: [PyCon HK 2026 HTML deck](https://github.com/nizarakbarm/pycon-hk-2026-bcc-vs-pythonbpf) and the [PyCon Taiwan 2026 Slidev deck](https://github.com/nizarakbarm/pycon-tw-2026-slidev) with its harness and measured dataset
- Patching [Python-BPF](https://github.com/nizarakbarm/Python-BPF) (fork) — closing defects the benchmark exposed. First fix: a `kprobe` + `kretprobe` pair annotating the same `ctx` struct crashed the debug-info generator with `RecursionError` (shared `DILocalVariable` metadata cycle), forcing the split-file workaround. One node per function + regression tests; verifier CI suite revived on the fork
- Agent tooling in Rust — [HackerOne API as an MCP server](https://github.com/nizarakbarm/hackerone_mcp_rust)
- Nginx/WordPress provisioning and hardening, fleet-wide CVE exposure assessment

## 💬 Talks

- **Kernel-Enforced Sandboxing for AI Agent Supply Chains with nono.sh** — openSUSE Asia Summit 2026
- **Python eBPF: BCC C-String Runtime vs Python-BPF AST AOT** — PyCon Taiwan 2026 ([Slidev deck + dataset](https://github.com/nizarakbarm/pycon-tw-2026-slidev)), PyCon Hong Kong 2026 ([HTML deck](https://nizarakbarm.github.io/pycon-hk-2026-bcc-vs-pythonbpf/))
- **IPList to BPFRule: A Python DDoS Mitigation Framework via XDP Hook of bpfilter** — PyCon Hong Kong 2025

## 📦 Selected work

| Repo | What it is |
|---|---|
| [`pycon-hk-2026-bcc-vs-pythonbpf`](https://github.com/nizarakbarm/pycon-hk-2026-bcc-vs-pythonbpf) | HTML deck — BCC vs Python-BPF, `sys_enter_execve`, 2M events, 3 instrumentation passes |
| [`pycon-tw-2026-slidev`](https://github.com/nizarakbarm/pycon-tw-2026-slidev) | Slidev deck + benchmark harness + measured dataset + limitation inventory |
| [`Python-BPF`](https://github.com/nizarakbarm/Python-BPF) | Fork — compiler fixes: two-section shared-`ctx` debug-info crash, verifier CI |
| [`hackerone_mcp_rust`](https://github.com/nizarakbarm/hackerone_mcp_rust) | HackerOne API surface as an MCP server, Rust |
| [`lve_error_monitoring_plugin`](https://github.com/nizarakbarm/lve_error_monitoring_plugin) | Icinga check for CloudLinux LVE error counts |
| [`Nginx-Wordpress-Provision`](https://github.com/nizarakbarm/Nginx-Wordpress-Provision) | Nginx + WordPress provisioning template |
| [`ModSecExcluder`](https://github.com/nizarakbarm/ModSecExcluder) | Per-user/domain ModSecurity rule-ID exclusion for WHM/cPanel |
| [`Cloudflareddos`](https://github.com/nizarakbarm/Cloudflareddos) | Cloudflare domain onboarding + under-attack mode from Python |

<details>
<summary>🧰 Stack</summary>

![Linux](https://img.shields.io/badge/-Linux-0d1117?style=flat&logo=linux&logoColor=white)
![Bash](https://img.shields.io/badge/-Bash-0d1117?style=flat&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/-Python-0d1117?style=flat&logo=python&logoColor=white)
![Ansible](https://img.shields.io/badge/-Ansible-0d1117?style=flat&logo=ansible&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-0d1117?style=flat&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-0d1117?style=flat&logo=nginx&logoColor=white)
![OpenResty](https://img.shields.io/badge/-OpenResty-0d1117?style=flat&logo=openresty&logoColor=white)
![Rust](https://img.shields.io/badge/-Rust-0d1117?style=flat&logo=rust&logoColor=white)
![Terraform](https://img.shields.io/badge/-Terraform-0d1117?style=flat&logo=terraform&logoColor=white)
![Cloudflare](https://img.shields.io/badge/-Cloudflare-0d1117?style=flat&logo=cloudflare&logoColor=white)
![eBPF](https://img.shields.io/badge/-eBPF-0d1117?style=flat&logo=ebpf&logoColor=white)

</details>

<details>
<summary>📈 GitHub, at a glance</summary>

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=nizarakbarm&theme=tokyonight" alt="GitHub profile summary" />

</details>
