<!--
  im0xfay — profile README
  Animated elements are third-party generated SVGs rendered as images:
    capsule-render  : gradient divider bars
    readme-typing-svg : typing animation for the handle
    komarev         : visitor counter
    shields.io      : badges
  Nothing here is a GitHub feature — it is all markdown <img> pointing at renderers.
-->

<div align="center">

![header](https://capsule-render.vercel.app/api?type=rect&color=0:0a0007,50:6A0572,100:0a0007&height=3&width=1000)

<!-- animated handle -->
[![im0xfay](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=800&size=56&duration=480&pause=2200&color=FF00FF&center=true&vCenter=true&width=900&height=90&lines=im0xfay)](https://github.com/im0xfay)

<!-- rotating tagline -->
[![roles](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=2600&pause=1100&color=B48EAD&center=true&vCenter=true&width=920&height=44&lines=CVE+Research+%2F%2F+Exploit+Development;Root+cause+first%2C+then+the+tool;Lab-verified+or+it+does+not+ship;The+bug+is+the+source%2C+not+the+banner)](https://github.com/im0xfay)

![footer](https://capsule-render.vercel.app/api?type=rect&color=0:0a0007,50:6A0572,100:0a0007&height=3&width=1000)

[![Profile Views](https://komarev.com/ghpvc/?username=im0xfay&label=Profile%20Views&color=6A0572&style=flat-square)](https://github.com/im0xfay)
[![Followers](https://img.shields.io/github/followers/im0xfay?label=Followers&style=flat-square&color=6A0572&logo=github&logoColor=white)](https://github.com/im0xfay?tab=followers)
[![Repos](https://img.shields.io/badge/Repos-10-6A0572?style=flat-square&logo=github&logoColor=white)](https://github.com/im0xfay?tab=repositories)
[![Region](https://img.shields.io/badge/Region-Tokyo-6A0572?style=flat-square)](https://github.com/im0xfay)

`find the root cause · prove it in the lab · ship what survives`

</div>

---

## `// ABOUT`

Offensive security researcher working on **web application exploitation**, **CVE research**,
and **exploit development**. I take a CVE from advisory to a working, reproducible tool:
source and root-cause analysis, sink-coverage audit, faithful lab reconstruction,
hostile-condition hardening, then an operator-grade PoC.

I work against real deployments as well as labs — which is why the tools report **honest
status** instead of wishful `VULN` lines. A signature match is a lead; only observed,
repeatable impact is a finding.

- **Focus** — CMS and web-app exploitation (WordPress, Joomla, custom), unauth RCE chains,
  file-upload / auth-bypass / path-traversal classes
- **Method** — root cause → sink coverage → lab → hostile variants → verified PoC
- **Principle** — no false positives; every claim backed by observed evidence

---

## `// FOCUS`

```
0x01  Vulnerability Research
0x02  CVE Hunting
0x03  Exploit Development
0x04  Source-Code Auditing
0x05  CMS Security          (WordPress · Joomla)
0x06  Web Application Security
```

---

## `// METHOD`

```
  Intel        Root Cause      Lab            Exploit        Productionize
  ─────   →    ──────────  →  ──────   →    ─────────  →  ─────────────
  KEV/EPSS     semgrep         multi-         chain           menu tool,
  + advisory   + manual        variant,       candidates,     fallback
  + gap        trace,          dirty by       lab-raced,      layering,
  analysis     sink audit      default        verified        honest tags
```

Every published tool is **menu-driven**, **starts with no arguments**, **auto-discovers
endpoints (never hardcoded lab paths)**, **self-attacked before release**, and reaches a
controlled outcome rather than merely triggering a bug.

Verdict policy: `SKIP → CLEAN → INFO → UNKNOWN → VULN → PWN`. A vulnerable version alone is
never `VULN` — that line requires a real response from the target.

---

## `// ARSENAL`

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-121011?style=flat-square&logo=gnubash&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=flat-square&logo=burpsuite&logoColor=white)
![Semgrep](https://img.shields.io/badge/Semgrep-1B2A32?style=flat-square&logo=semgrep&logoColor=white)
![sqlmap](https://img.shields.io/badge/sqlmap-1B2A32?style=flat-square&logo=databricks&logoColor=white)
![Nuclei](https://img.shields.io/badge/Nuclei-1B2A32?style=flat-square&logo=protondb&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-1B2A32?style=flat-square&logo=gnu&logoColor=white)

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

</div>

---

## `// WORK`

<table>
<tr>
<td width="50%" valign="top">

**[im0xfay/MEGAPACK](https://github.com/im0xfay/MEGAPACK)**<br>
Unified multi-CVE scanner and exploiter — **65 modules** across Joomla Core, Joomla
extensions and WordPress plugins. Menu-first, honest verdicts, per-CVE documentation.

`56 verified · 7 documented · 2 unsupported`

</td>
<td width="50%" valign="top">

**[im0xfay/CWP2SHELL](https://github.com/im0xfay/CWP2SHELL)**<br>
Control Web Panel < 1.29 — 10-CVE chain from unauthenticated module dispatch to
hosting-user RCE, then a loopback user API to root.

`lab-verified end-to-end`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[CVE-2026-89324](https://github.com/im0xfay/CVE-2026-89324)**<br>
Basel Post Types ≤ 1.18 — unauthenticated auth bypass via a forged Opauth callback,
landing on an admin takeover.

`lab-verified · WC pinned 9.5.2`

</td>
<td width="50%" valign="top">

**[CVE-2026-126537](https://github.com/im0xfay/CVE-2026-126537)**<br>
Ninja Forms File Uploads ≤ 3.3.36 — unauthenticated upload path to code execution.

`lab-verified`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[CVE-2026-118423](https://github.com/im0xfay/CVE-2026-118423)**<br>
WP Libre Form ≤ 1.5.0.1 — unauthenticated arbitrary file upload → RCE.

`lab-verified`

</td>
<td width="50%" valign="top">

**[CVE-2026-110468 / 110469](https://github.com/im0xfay/CVE-2026-110468-110469-WIDZIALNI)**<br>
WidzialniCMS < 2.5 — unauthenticated file upload → RCE, with a field note on a
detection signature that false-positives in the wild.

`lab-verified`

</td>
</tr>
</table>

> Each public repo ships the **tool, the lab, the research notes and the report** — not just a PoC.

---

## `// NOTES`

Selected findings where the honest answer was *not* the advisory's answer:

| CVE | Advisory claim | What the source showed |
|---|---|---|
| CVE-2026-56290 | unauth upload → RCE | Write is real, code execution is not: `pathinfo(..., PATHINFO_FILENAME) . '.css'` forces the `.css` suffix, so `fbi.php` lands as `fbi.css` |
| CVE-2026-48939 | unauth upload → RCE | `InputFilter::isSafeFile()` rejects the forbidden extension list, `<?php` and `<?` in content, and the phar stub — every upload path is neutralised |
| CVE-2026-35222 | com_tags SQL injection, CVSS 9.8 | `TagModel.php` unchanged across six tags; `filter_fields` is a closed list and `filter_order_Dir` accepts only `ASC`/`DESC`/empty |

Reporting a negative result is still reporting. "It cannot be exploited" is a finding.

---

## `// CONTACT`

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-im0xfay-6A0572?style=for-the-badge&logo=github&logoColor=white)](https://github.com/im0xfay)
[![Telegram](https://img.shields.io/badge/Telegram-@im0xfay-6A0572?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/im0xfay)

</div>

---

<div align="center">

![footer](https://capsule-render.vercel.app/api?type=rect&color=0:0a0007,50:6A0572,100:0a0007&height=3&width=1000)

*All research is conducted under authorisation — own systems, isolated labs, or written
engagement scope. Published tooling is for authorised security testing only.*

> *not everyone deserves a seat at my table. Some are better on the floor*

</div>
