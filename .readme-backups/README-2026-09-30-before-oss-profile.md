# Tayfur Yıldız

Security-focused developer and open-source contributor. I work on application security, reliability, developer tooling, and the small correctness bugs that tend to hide at system boundaries.

I prefer reproducible failures, narrow fixes, and regression tests over speculative changes. Over the last year, I have authored **140+ merged pull requests in repositories I do not own**.

[LinkedIn](https://www.linkedin.com/in/tayfur-y%C4%B1ld%C4%B1z-3b7820391/) · [HackerOne](https://hackerone.com/tayfuryldzz?type=user) · [Bugcrowd](https://bugcrowd.com/h/tayfuryldz) · [Intigriti](https://app.intigriti.com/researcher/profile/tayfuryldz) · [YesWeHack](https://yeswehack.com/hunters/tayfuryldz#latest-hacktivity)

## Current work

### [HeaderProof](https://github.com/tayfuryldz/headerproof)

An evidence-oriented HTTP security scanner built to keep findings reproducible and low-noise. The project focuses on request/response behavior around CORS, CSRF, header injection, cache poisoning, content reflection, and related web security signals.

I also maintain [HeaderProof Action](https://github.com/tayfuryldz/headerproof-action) and [HeaderProof Templates](https://github.com/tayfuryldz/headerproof-templates) for CI use and reusable checks.

## Selected open-source work

- **[OpenTelemetry PHP](https://github.com/open-telemetry/opentelemetry-php/pull/2058)** — fixed SDK attribute-limit fallback behavior across tracing and logging, with unit coverage for the global-limit paths.
- **[OpenLayers](https://github.com/openlayers/openlayers/pull/17640)** — fixed map target cleanup affecting mouse-wheel zoom and moved the lifecycle handling into the map/browser-event layer with regression coverage.
- **[sktime](https://github.com/sktime/sktime/pull/11141)** — made `SubLOF` compatible with pandas 3 while preserving coverage for older pandas versions.
- **[planning-with-files](https://github.com/OthmanAdi/planning-with-files/pull/287)** — hardened concurrent PowerShell active-plan replacement with bounded retries and deterministic regression coverage.
- **[LibreSign](https://github.com/LibreSign/libresign/pull/8730)** — corrected visible-element URL handling so downloaded bytes are validated before persistence, adapting the fix through an upstream service refactor.
- **[The Algorithms · Python](https://github.com/TheAlgorithms/Python/pull/15432)** — tightened TimSort typing around comparable values and added regression coverage.
- **[Headroom](https://github.com/headroomlabs-ai/headroom/pull/3655)** — made memory handling fail closed when tool references cannot be resolved, with project-isolation regression coverage.
- **[react-native-better-maps](https://github.com/gmi-software/react-native-better-maps/pull/143)** — hardened overlay collection against invalid coordinates and split validation into focused, tested paths.

Most of my upstream work is in bug fixes, edge-case handling, regression tests, and reliability improvements. The full history is available in my [pull requests](https://github.com/pulls?q=is%3Apr+author%3Atayfuryldz).

## Tools & languages

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" width="28" height="28" alt="Python" title="Python" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/rust/rust-original.svg" width="28" height="28" alt="Rust" title="Rust" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/php/php-original.svg" width="28" height="28" alt="PHP" title="PHP" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" width="28" height="28" alt="JavaScript" title="JavaScript" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/bash/bash-original.svg" width="28" height="28" alt="Bash" title="Bash" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" width="28" height="28" alt="Linux" title="Linux" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" width="28" height="28" alt="Git" title="Git" />&nbsp;&nbsp;
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" width="28" height="28" alt="Docker" title="Docker" />
</p>

Security work is performed only in authorized environments and open-source projects.
