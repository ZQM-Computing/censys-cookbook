# Censys Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **Censys cookbook** — internet scanning data from the command line. Second-tier OSINT tool in the wave-8 set. Live use needs the owner's free Censys API key, which stays out of repos. Patterns are planned from the design, not yet from fleet runs. It is intended for Security researchers who query internet-wide scan data. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** Censys patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Security researchers who query internet-wide scan data.

## Prerequisites

- Censys CLI in the fleet tooling
- A free Censys API key, kept out of repos
- Bash or PowerShell

## Patterns (planned)

**Nothing below exists yet.**

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-first-search` | A first hosts search and its output |
| 02 | `02-certificates` | Certificate search patterns |
| 03 | `03-output` | Exporting results for triage |

## Repository layout

```text
censys-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [shodan-cookbook](https://github.com/ZQM-Computing/shodan-cookbook) — Internet-device search from the command line
- [amass-cookbook](https://github.com/ZQM-Computing/amass-cookbook) — Passive subdomain enumeration and graph output
- [spiderfoot-cookbook](https://github.com/ZQM-Computing/spiderfoot-cookbook) — Passive OSINT automation as a service
