# Purple Team SSH Brute-Force Detection Lab

Purple Team lab simulating SSH brute-force detection, network monitoring, SIEM analysis, and mitigation using Kali Linux, Nmap, tcpdump, Splunk, and fail2ban.

## View the project

**Live project site:** https://mandozone.github.io/Purple-Team-SSH-Detection-Lab/

If you are viewing this repository on GitHub, start with the live site above. The `site/` folder contains the rendered portfolio page files, so opening `site/index.html` inside GitHub will show source code rather than the website.

## TL;DR for recruiters

| | |
|---|---|
| **Scenario** | Simulated SSH brute-force activity against an isolated Linux lab host. |
| **What I built** | A detection workflow using packet capture, log evidence, Splunk SPL searches, MITRE ATT&CK mapping, and fail2ban mitigation. |
| **Evidence** | Nmap scan, tcpdump captures, Splunk event analysis, IOC table, authentication-failure spike, and containment verification. |
| **Security value** | Shows practical SOC-style detection work: observe activity, collect evidence, classify behavior, tune detection logic, and document response. |

## Skills demonstrated

`Linux Administration` · `SSH Security` · `Nmap` · `tcpdump` · `Splunk` · `SPL Queries` · `MITRE ATT&CK` · `Brute-Force Detection` · `fail2ban` · `Incident Response Documentation`

## Repository structure

| Path | Purpose |
|---|---|
| `README.md` | Recruiter-friendly project summary |
| `site/` | Rendered portfolio website and supporting screenshots |
| `site/assets/purple-team-ssh-detection-lab.pdf` | Bundled full lab report |

## What recruiters should notice

- This is a hands-on detection lab, not a theoretical write-up.
- The workflow includes reconnaissance, traffic capture, SIEM analysis, detection logic, MITRE mapping, and mitigation.
- The screenshots are used as evidence for the technical steps performed.
