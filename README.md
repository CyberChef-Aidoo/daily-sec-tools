# Daily Sec Tools
A daily log of cybersecurity tools our team learns and documents one tool, one write-up, one day at a time.

## About
This repository is a shared learning journal. Each day, a team member picks a new cybersecurity tool, spends time exploring it, and documents what they learned in a short, structured write-up. Over time this becomes a searchable reference library built entirely by the team, for the team.

**Goals:**
- Build hands-on familiarity with a wide range of security tools (recon, scanning, exploitation, forensics, defense, etc.)
- Create a lightweight, reusable knowledge base for future projects and interviews
- Hold each other accountable with a consistent daily/weekly cadence
- Practice clear technical writing

## How it works

1. Pick a tool that hasn't been covered yet (check `tools/` or the [Tool Index](#tool-index) below).
2. Install/run it in a **safe, isolated environment** (a VM, container, or a lab you own — never against systems you don't have explicit permission to test).
3. Create a new write-up using the [template](#write-up-template) below.
4. Save it under `tools/<category>/<tool-name>.md`.
5. Open a pull request. A teammate reviews it, then it's merged.
6. Update the [Tool Index](#tool-index) table with the new entry.

## Repository structure

```
daily-sec-tools/
├── README.md
├── template.md
├── tools/
│   ├── recon/
│   ├── scanning/
│   ├── exploitation/
│   ├── forensics/
│   ├── web-security/
│   ├── network-security/
│   └── defense-blue-team/
└── resources/
    └── links.md
```

## Write-up template

```markdown
# Tool Name

**Category:** e.g. Reconnaissance / Scanning / Exploitation / Forensics / Defense
**Date covered:** YYYY-MM-DD
**Author:** @github-handle

## What it is
Brief description of the tool and what problem it solves.

## Installation
How to install it (OS/package manager/Docker, etc.)

## Basic usage
Core commands or workflow with example output.

## Use case walkthrough
A short practical example — what you ran and what it revealed.

## Key takeaways
- Bullet points on what's genuinely useful
- Gotchas, limitations, or things that surprised you

## References
- Official docs / relevant links
```

## Tool index

| Tool | Category | Covered by | Date |
|------|----------|-----------|------|
| _example: Nmap_ | Scanning | @handle | 2026-08-01 |

*(Update this table as new write-ups are added.)*

## Ground rules

- ⚠️ **Only test tools against systems you own or are explicitly authorized to test** (your own lab, intentionally vulnerable VMs like DVWA/Metasploitable, or platforms like HTB/TryHackMe).
- Keep write-ups concise and practical — future-you (and teammates) should be able to skim it in under 5 minutes.
- Cite official documentation and credible sources.
- No credentials, private IPs, or client-identifiable data in any write-up or screenshot.

## Contributing

1. Fork or branch from `main`.
2. Add your write-up following the template above.
3. Open a PR with a short summary of the tool.
4. Get one review before merging.

## License

This repository is for internal team learning. Add a license (e.g. MIT) if you plan to make it public.
