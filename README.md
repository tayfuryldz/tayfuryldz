# Tayfur Yıldız

Security-focused developer working on open-source software, developer tooling, and practical security research.

I like problems that need a reproducible answer: trace the behavior, isolate the failure, make the smallest useful change, and leave a regression test behind.

[LinkedIn](https://www.linkedin.com/in/tayfur-y%C4%B1ld%C4%B1z-3b7820391/) · [HackerOne](https://hackerone.com/tayfuryldzz?type=user) · [Bugcrowd](https://bugcrowd.com/h/tayfuryldz) · [Intigriti](https://app.intigriti.com/researcher/profile/tayfuryldz) · [YesWeHack](https://yeswehack.com/hunters/tayfuryldz#latest-hacktivity)

## Open source

Most of my recent work has been upstream: debugging existing systems, writing focused fixes, adding regression coverage, and working through maintainer review. I have **140+ merged pull requests in repositories I don't own** in the last 12 months.

A few representative contributions:

| Project | Contribution |
| --- | --- |
| [TheAlgorithms/Python](https://github.com/TheAlgorithms/Python) | [Constrained TimSort inputs to comparable values](https://github.com/TheAlgorithms/Python/pull/15432), tightening the implementation and its typing contract. |
| [RustDesk](https://github.com/rustdesk/rustdesk) | [Fixed Windows foreground activation for an existing session](https://github.com/rustdesk/rustdesk/pull/16349). |
| [OpenLayers](https://github.com/openlayers/openlayers) | [Fixed `MouseWheelZoom` target cleanup](https://github.com/openlayers/openlayers/pull/17640), including lifecycle and interaction-state handling. |
| [sktime](https://github.com/sktime/sktime) | [Made `SubLOF` compatible with pandas 3](https://github.com/sktime/sktime/pull/11141). |
| [OpenTelemetry PHP](https://github.com/open-telemetry/opentelemetry-php) | [Fixed SDK global attribute-limit fallbacks](https://github.com/open-telemetry/opentelemetry-php/pull/2058) with regression coverage across the affected limits. |
| [Nextcloud Mail](https://github.com/nextcloud/mail) | [Fixed detection of `application/octet-stream` ICS attachments](https://github.com/nextcloud/mail/pull/13732). |
| [GitHub Advisory Database](https://github.com/github/advisory-database) | Contributed advisory metadata fixes, including [PickleScan](https://github.com/github/advisory-database/pull/9765) and [Gitea](https://github.com/github/advisory-database/pull/9733) fix references. |
| [planning-with-files](https://github.com/OthmanAdi/planning-with-files) | Contributed a series of reliability fixes across project attestation, PowerShell pointer replacement, OpenCode replay handling, and active-plan state; for example [#297](https://github.com/OthmanAdi/planning-with-files/pull/297) and [#287](https://github.com/OthmanAdi/planning-with-files/pull/287). |

## HeaderProof

[**HeaderProof**](https://github.com/tayfuryldz/headerproof) is the security project I maintain. It is built around evidence rather than noisy heuristics: probe HTTP behavior, preserve the response that supports a finding, and keep conclusions reproducible.

The current work covers CORS and CSRF behavior, response/header injection, cache-related issues, content reflection and other HTTP security checks, with profiles for controlling scan behavior and output intended to be useful during authorized testing.

Related repositories: [headerproof-action](https://github.com/tayfuryldz/headerproof-action) · [headerproof-templates](https://github.com/tayfuryldz/headerproof-templates)

## Working set

<p>
  <img src="https://cdn.simpleicons.org/python" width="28" height="28" alt="Python" title="Python" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/rust" width="28" height="28" alt="Rust" title="Rust" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/typescript" width="28" height="28" alt="TypeScript" title="TypeScript" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/javascript" width="28" height="28" alt="JavaScript" title="JavaScript" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/php" width="28" height="28" alt="PHP" title="PHP" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/linux" width="28" height="28" alt="Linux" title="Linux" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/git" width="28" height="28" alt="Git" title="Git" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/github" width="28" height="28" alt="GitHub" title="GitHub" />&nbsp;&nbsp;
  <img src="https://cdn.simpleicons.org/docker" width="28" height="28" alt="Docker" title="Docker" />
</p>

Security research: HTTP behavior, web application security, bug bounty, attack-surface analysis, validation, and low-noise automation. Daily environment includes Linux/WSL, Burp Suite, Nuclei, Nmap, and ProjectDiscovery tooling.

---

<sub>Security work is performed in authorized environments and within the applicable program or project scope.</sub>
