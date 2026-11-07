---
description: Jenkins LTS upgrade guides written by starting version, with rehearsal results for 38 LTS lines. In English and Chinese.
---

# Jenkins LTS upgrade guides

For each Jenkins LTS release, one guide: what changed that matters for upgrades, and **what happens when you upgrade from the version you run today**.

The official upgrade guide tells you what changed in a release. It does not tell you that the same release is a simple war swap from one version and a three-step migration from another. Each guide here starts with that table, based on rehearsals of 38 LTS lines with the most installed plugins.

| LTS | Released | Guide | Key points |
| --- | --- | --- | --- |
| 2.580.x | 2026-09-30 / 2026-10-28 | [2.580](2-580.md) | Java 21 or 25 required; from 2.355 or older a direct upgrade can fail to start; 2.580.2 fixes 15 security issues |

## How these guides are made {#how}

- Based on the official upgrade guide, changelog and security advisories. Drafted with AI and checked against the sources.
- Where my reading differs from the official text, the guide says so and gives the reason.
- Rehearsal data comes from the [upgrade matrix](https://github.com/keelinfra/jenkins-upgrade-check/tree/matrix) of [jenkins-upgrade-check](https://github.com/keelinfra/jenkins-upgrade-check), which runs every week.
- Found a mistake, or hit a problem that is not covered? [Open an issue](https://github.com/shenxianpeng/jenkins-lts/issues).

Text is licensed [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), the same as jenkins.io.
