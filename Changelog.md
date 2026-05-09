# Changelog

All notable changes to the **CLOAK dataset** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---


## May 2026

### Added
- Added 10 sub-techniques

Technical sub-techniques (5):

| ID | Name | Parent technique | Tactic |
|---|---|---|---|
| ST-2800 | Keystroke biometric obfuscation | Unlinked Subtechniques | Reduce attack surface |
| ST-2801 | Protocol mimicry via camouflage web server | Anonymous internet connection | Anonymous browsing |
| ST-2802 | Probabilistic log anonymization (Bloom filter) | Anti-forensics | Plausible deniability |
| ST-2803 | Sensor-triggered automated kill switch | Selfdestruction | Plausible deniability |
| ST-2804 | SSD cryptographic key erasure | Anti-forensics | Plausible deniability |

Behavioral sub-techniques (2):

| ID | Name | Parent technique | Tactic |
|---|---|---|---|
| ST-2805 | Automated stylometric spoofing | Avoid stylometry | Secure behavior |
| ST-2806 | Dark persona compartmentalization | Avoid cross-contamination | Secure behavior |

Physical sub-techniques (3):

| ID | Name | Parent technique | Tactic |
|---|---|---|---|
| ST-2807 | Thermal label printing for forensically safe dispatch | Avoid cross-contamination | Secure behavior |
| ST-2808 | RF/Wi-Fi motion detection countermeasure | Wired-only | Reduce attack surface |
| ST-2809 | Tactical physical entry delay | Situational awareness | Secure behavior |

### Updated
- Changelog


## March 2026

### Added
- Changelog.md 

### Updated
- Updated index.html
- Removed changelog from README.md

## [February 2026]

### Added
- Search functionality to improve navigation within the dataset.
- Short introduction describing the purpose and structure of the dataset.
- Total number of TTPs displayed in the dataset.
- **60 new TTPs** based on remaining documentation sources.

### Updated
- `README.md` updated to reflect the latest dataset structure and additions.
- Dataset coverage expanded to ensure correct rendering and inclusion of all documented TTPs.

### New TTPs

| Technique | Sub-technique | Procedure / Tool |
|---|---|---|
| Avoid leaving DNA | Random hostnames | dark.fail |
| Compartmentalization | Add cryptocurrency to darknet market account | tor.taxi |
| Self-education | Avoid package tracking via official USPS website | DNSCrypt |
| Anonymous traveling | Third-party package tracking | dnscrypt-proxy 2 |
| Avoid exchanges | — | ADHOC S2 |
| Fake or hollow walls and floors | — | ADHOC S3 |
| Open package in public place | — | FoxyProxy |
| Avoid bookmarked darknet markets | — | Greasemonkey |
| Act if car GPS is being tracked | — | Dash |
| Remove car microphone | — | SOCKSchain |
| Keep evidence minimal | — | Cryptostorm VPN |
| Avoid saving customer addresses | — | Fedora |
| Alter browser habits | — | ThinkPad X1 Carbon (5th generation) |
| Encrypt DNS | — | ThinkPad T560P |
| Avoid roads with tolls | — | ThinkPad 450S |
| Only travel with burner devices | — | CanvasBlocker |
| Avoid cars with RF communications | — | KeePassX |
| Avoid Tor over Tor | — | Wickr |
| Avoid using anonymously bought devices within CCTV storage window | — | — |
| Offline notes | — | — |
| Offline spell checker | — | — |
| Multiple translations | — | — |
| Generate PGP keys regularly | — | — |
| Carry external media with you | — | — |
| Carry transmitting devices with you | — | — |
| Limit number of installed applications | — | — |
| Set homepage to Google | — | — |
| Change download folder to encrypted location | — | — |
| Disable search history | — | — |
| Private browsing mode | — | — |
| Close and clean | — | — |
| Avoid advertisements | — | — |
| Avoid ignoring warnings | — | — |
| Avoid downloading from untrusted sources | — | — |
| Show punycode | — | — |
| Disable browser PDF reader | — | — |
| Certificate pinning | — | — |
| Disable beaconing | — | — |
| Disable prefetching | — | — |
| Disable browser pings | — | — |
| Password policies | — | — |
| Avoid digital and online diceware simulators | — | — |

---

## Notes

More TTPs will be added as additional research and documentation progresses.

If you notice inconsistencies or have suggestions for improvement, please open an issue or contact:

cloak@opsectechniques.com