# Bug-Bounty Companion updates

This public repository is the update-only AltStore Classic channel for the
native Bug-Bounty iPhone companion.

- Add the source once: <https://axisman3r.github.io/bug-bounty-ios-updates/>
- Feed URL: <https://axisman3r.github.io/bug-bounty-ios-updates/source.json>
- Compiled IPA files are unsigned. AltStore and AltServer perform personal-device signing.
- Each feed version records the exact IPA SHA-256 and declares every privacy permission.

This repository intentionally contains no private Swift source, provider keys,
reports, guidelines, pairing tokens, certificates, workspace paths or Apple
credentials. The compiled app can be downloaded and inspected by anyone who
finds this public repository.

AltStore still requires the user to approve an update. A free Apple provisioning
profile must be refreshed within seven days, normally by AltStore while AltServer
is available on the same trusted Wi-Fi.
