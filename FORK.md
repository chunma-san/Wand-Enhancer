# chunma edition

This is an unofficial fork of [k1tbyte/Wand-Enhancer](https://github.com/k1tbyte/Wand-Enhancer), maintained by [chunma-san](https://github.com/chunma-san). Original authorship and the Apache-2.0 license are preserved.

## Changes

- A dark blue desktop palette and a clearly identified fork window title.
- A personalized English README with the maintainer's Discord profile card.
- Automated upstream merges every six hours, followed by Windows builds and the upstream test suite.
- Releases contain an unsigned EXE, a ZIP with license and source provenance, and SHA-256 checksums. Every successful new source commit gets a unique release tag.

## Maintenance

The upstream stable branch is `master`. Updates are merged, never force-pushed. Conflicts stop the workflow for manual resolution. GitHub may reject an automated push that changes workflow files; those updates need a maintainer to merge with workflow-authorized credentials. Failed builds never publish a release. Scheduled workflows can be delayed or disabled by GitHub after inactivity; they can also be started manually from Actions.

Automation runs on GitHub, so a home server does not need to stay online. No personal server addresses, bot tokens or webhook secrets are required.

The default binary excludes optional update-checking network code. This fork does not promise compatibility with every Wand version. The remote panel retains upstream's trusted LAN/VPN-only behavior; do not expose its port to the public internet.
