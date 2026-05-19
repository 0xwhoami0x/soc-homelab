# docs/splunk/
 
## What This Folder Contains
All documentation related to the Splunk SIEM deployment in this lab.
Guides, references, workflows, runbooks, and post-incident writeups.
 
## Contents
 
### Setup and Architecture
- `setup-guide.md` — full Splunk installation walkthrough on Proxmox LXC
- `architecture.md` — lab topology, data flow diagram, component overview
 
### Reference
- `spl-reference.md` — SPL command reference and common search patterns
- `frameworks.md` — MITRE ATT&CK, Kill Chain, Diamond Model mapped to detections
- `rba-model.md` — Risk-Based Alerting scoring model and documentation
 
### Operations
- `soc-workflow.md` — triage process, investigation checklist, disposition guide
- `runbooks/` — step-by-step response procedures per alert type
- `incident-reports/` — post-incident writeups from lab exercises
 
### Assets
- `dashboards/` — exported Splunk dashboard XML files (importable directly)
 
## How to Use
Start with `setup-guide.md` if building the lab from scratch.
Use `spl-reference.md` during investigations as a search cheat sheet.
Open `soc-workflow.md` when working an alert to follow the triage process.
Each runbook in `runbooks/` corresponds to a detection rule in `rules/sigma/`.
