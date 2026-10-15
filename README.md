<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:001E2B,50:00684A,100:00ED64&height=190&section=header&text=Mohammed%20Suhail%20Zamani&fontSize=44&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineer%20%C2%B7%20MongoDB&descSize=18&descAlignY=58&animation=fadeIn" width="100%" alt="banner"/>

<a href="https://www.mongodb.com"><img src="https://img.shields.io/badge/MongoDB-Application%20Modernization-00ED64?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=001E2B" alt="MongoDB"/></a>
<a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=001E2B" alt="LinkedIn"/></a>
<a href="mailto:msuhail.zamani@mongodb.com"><img src="https://img.shields.io/badge/Email-say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=001E2B" alt="Email"/></a>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3200&pause=900&color=00ED64&center=true&vCenter=true&width=640&lines=I+build+the+CLI+that+ships+a+platform+into+customer+environments.;Python+%C2%B7+Java+%C2%B7+Go+%C2%B7+Docker+%C2%B7+GitHub+Actions;Signed+bundles%2C+safe+updates%2C+boring+rollouts.;Teaching+Claude+Code+to+do+the+repetitive+parts." alt="typing intro"/>

</div>

## 👋 About me

I'm a software engineer on MongoDB's **Application Modernization Platform (AMP)** team. We help enterprises move legacy applications onto modern architectures, and I work on the part that makes that *installable*: the packaging, the CLI, and the release machinery that put a suite of containerized analysis tools onto a customer's host and keep them up to date.

- 🧰 **I own developer-facing surfaces.** CLIs, release pipelines, shared libraries, and the docs that go with them.
- 🔐 **I care about trust in the supply chain.** Signed release bundles, image digests verified at load *and* at runtime, and provenance you can print.
- 🔁 **I like lifecycles more than features.** Install → preflight → status → update → reset, with every step idempotent and reversible.
- 🤖 **I build the tooling that builds the tooling.** Claude Code skills, plugins, and a local usage dashboard for the team.

## 🚀 What I'm building

<table>
<tr>
<td width="50%" valign="top">

### `amp` — a single-binary platform CLI
A Python CLI frozen per OS/arch that installs and operates a platform of Docker Compose services from a signed release bundle.

- One install workflow, plus `status`, `shutdown`, `restart`, `reset`
- `update`: check → present → approve → stage → apply, with audit trail
- `preflight` that runs the bundle's own checks before anything touches the host
- `provenance`: bundle digest, release signature, per-image load-time IDs

</td>
<td width="50%" valign="top">

### Release & update engine
The packaging layer the CLI consumes: `bundle.yaml` manifests, dual-digest signing, multi-project installs, and a config store the tools read at startup.

- Several projects per install, each tool mounting the active one
- Config schema with required-at-init and secret fields
- Versioned shared packages for telemetry and config validation
- Reusable GitHub Actions workflows adopted across the team's repos

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Claude Code skills & plugins
An internal skills marketplace that turns the team's recurring engineering work into repeatable, reviewable skills.

- Telemetry and config-library migrations as guided skills
- CI migration to shared reusable workflows
- Multi-agent PR review, Jira hygiene, and release checklists

</td>
<td width="50%" valign="top">

### AMP Pulse
A local-only dashboard of Claude Code usage: spend vs. budget, business value delivered, token-saving tips, a 30-day forecast, and a printable report.

- Python backend, vanilla web UI, zero external services
- Shipped as a Claude Code plugin with a CI-built release

</td>
</tr>
</table>

> Most of this lives in private repositories, so you won't see it in the activity graph. Happy to talk about any of it.

## 🧑‍🔧 Toolbox

<div align="center">

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java"/>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go"/>
  <img src="https://img.shields.io/badge/Shell-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MongoDB-00ED64?style=for-the-badge&logo=mongodb&logoColor=white&labelColor=001E2B" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker"/>
  <img src="https://img.shields.io/badge/Compose-1D63ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions"/>
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PyInstaller-single%20binary-3776AB?style=for-the-badge" alt="PyInstaller"/>
  <img src="https://img.shields.io/badge/Signed%20releases-cosign%20%2F%20digests-7C3AED?style=for-the-badge" alt="Sigstore"/>
  <img src="https://img.shields.io/badge/Claude%20Code-skills%20%26%20plugins-D97757?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude Code"/>
  <img src="https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="pytest"/>
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira"/>
</p>

</div>

## 🧭 How I work

| Principle | What it looks like in practice |
|---|---|
| **Small, named PRs** | One ticket, one PR, conventional commits, version bump in the same commit. |
| **Review is half the job** | I review more PRs than I open. Comments cite the line and propose the fix. |
| **Make it boring to operate** | Every CLI step is idempotent, prints what it will do, and asks before it changes state. |
| **Verify, then verify in prod shape** | Unit tests, then the real frozen binary against a real Compose stack in CI. |
| **Write it down** | Design doc before code, PRD for the CLI surface, ADR when we change our minds. |

## 📬 Reach me

<div align="center">

<p align="center">
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN-HANDLE"><img src="https://img.shields.io/badge/LinkedIn-YOUR--HANDLE-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"/></a>
  <a href="mailto:msuhail.zamani@mongodb.com"><img src="https://img.shields.io/badge/Email-msuhail.zamani%40mongodb.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://github.com/msuhailz"><img src="https://img.shields.io/badge/GitHub-msuhailz-181717?style=flat-square&logo=github" alt="GitHub"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00ED64,50:00684A,100:001E2B&height=100&section=footer" width="100%" alt="footer"/>

</div>
