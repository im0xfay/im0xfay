<div align="center">

<pre>
 ___ __  __  ___  __  __ ___    _   __   __
|_ _|  \/  |/ _ \ \ \/ /| __|  /_\  \ \ / /
 | || |\/| | (_) | >  < | _|  / _ \  \ V / 
|___|_|  |_|\___/ /_/\_\|_|  /_/ \_\  |_|  
</pre>

### Vulnerability Research & Exploit Development

*Find the root cause. Reproduce it in the lab. Ship a tool that survives hostile conditions.*

[![CVE Research](https://img.shields.io/badge/Focus-CVE_Research-6A0572?style=flat-square)](#-selected-work)
[![Exploit Dev](https://img.shields.io/badge/Focus-Exploit_Dev-6A0572?style=flat-square)](#-selected-work)
[![Lab Verified](https://img.shields.io/badge/Method-Lab--Verified-brightgreen?style=flat-square)](#-method)
[![Repos](https://img.shields.io/badge/Repos-4-6A0572?style=flat-square)](https://github.com/im0xfay?tab=repositories)

</div>

---

## About

Security researcher focused on **web application penetration testing** and **exploit
development**. I take a CVE from advisory to a working, reproducible tool: source/root-cause
analysis, sink-coverage audit, faithful lab reconstruction, hostile-condition hardening, and
an operator-grade PoC.

I work on real deployments as well as labs — which is why my tools report **honest status**
instead of wishful "VULN" lines. A signature match is a lead; only observed, repeatable
impact is a finding.

- **Focus** — CMS & web-app exploitation (WordPress, Joomla, custom), unauth RCE chains,
  file-upload / auth-bypass / path-traversal classes
- **Method** — root-cause → sink coverage → lab → hostile variants → verified PoC
- **Principle** — no false positives; every claim backed by observed evidence

---

## Method

```
  Intel        Root Cause      Lab            Exploit        Productionize
  ─────   →    ──────────  →  ──────   →    ─────────  →  ─────────────
  KEV/EPSS     semgrep         multi-         chain           menu tool,
  + advisory   + manual        variant,       candidates,     fallback
  + gap        trace,          dirty by       lab-raced,      layering,
  analysis     sink audit      default        verified        honest tags
```

Every published tool: **menu-driven**, **no-arg start**, **auto-discovery (never hardcoded
lab paths)**, **self-attacked before release**, and gated behind an explicit `--exploit`
flag (default is detect-only).

---

## Selected Work

| Repository | Class | Status |
|---|---|---|
| [CVE-2026-110468 / 110469 — WidzialniCMS < 2.5](https://github.com/im0xfay/CVE-2026-110468-110469-WIDZIALNI) | Unauth file upload → RCE (`CWE-434`) | Lab-verified · [field note](https://github.com/im0xfay/CVE-2026-110468-110469-WIDZIALNI#-field-note--the-detection-signature-is-a-false-positive-in-the-wild) |
| [CVE-2026-118423 — WP Libre Form ≤ 1.5.0.1](https://github.com/im0xfay/CVE-2026-118423) | Unauth arbitrary file upload → RCE | Lab-verified |
| CVE-2026-86596 — s2Member ≤ 260927 | Unauth template-injection RCE | Private |
| CVE-2026-65555 — Uncanny Toolkit (LearnDash) | Verification bypass | Private |

> Each public repo ships the **tool + lab + full research + report** — not just a PoC.

---

## Tooling

<div align="center">

**Analysis**

![Semgrep](https://img.shields.io/badge/Semgrep-1B2A32?style=flat-square&logo=semgrep&logoColor=white)
![CodeQL](https://img.shields.io/badge/CodeQL-1B2A32?style=flat-square&logo=github&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-1B2A32?style=flat-square&logo=gnu&logoColor=white)

**Web / Exploit**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![SQLMap](https://img.shields.io/badge/sqlmap-1B2A32?style=flat-square&logo=databricks&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-1B2A32?style=flat-square&logo=protondb&logoColor=white)

**Runtime**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)

</div>

---

## Contact

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-im0xfay-6A0572?style=for-the-badge&logo=github&logoColor=white)](https://github.com/im0xfay)
[![Telegram](https://img.shields.io/badge/Telegram-@im0xfay-6A0572?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/im0xfay)

</div>

---

<div align="center">

*All research is conducted under authorisation — own systems, isolated labs, or written
engagement scope. Published tooling is for authorised security testing only.*

> *not everyone deserves a seat at my table. Some are better on the floor*

</div>
