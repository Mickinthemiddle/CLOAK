# Changelog

All notable changes to the **CLOAK dataset** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## June 2026

### Added

#### Techniques (TE)

| ID | Name | Tactic | Category |
|----|------|--------|----------|
| TE-124 | Operational patience | Secure behavior | Behavioral |
| TE-125 | Physical and social footprint minimisation | Secure behavior | Behavioral |
| TE-126 | Privacy-preserving cryptocurrency selection | Anonymous cryptocurrency | Technical |
| TE-127 | Pre-emptive data minimisation | Reduce attack surface | Behavioral |
| TE-128 | Periodic OPSEC review and adaptation | Secure behavior | Behavioral |
| TE-129 | BGP-level network infrastructure security | Anonymous hosting | Technical |

#### Subtechniques (ST)

| ID | Name | Parent | Category |
|----|------|--------|----------|
| ST-2762 | Software dead man's switch | TE-92 Selfdestruction | Technical |
| ST-2763 | Client-side cloud encryption | TE-52 Encryption | Technical |
| ST-2764 | Hash-based software integrity verification | TE-100 Tamper-evident software | Technical |
| ST-2765 | Air-gapped cryptographic key management | TE-52 Encryption | Technical |
| ST-2766 | I2P eepsite hosting | TE-9 Anonymous internet connection | Technical |
| ST-2767 | Awareness of network payload inspection capabilities | TE-103 Threat modeling | Behavioral |
| ST-2768 | Awareness of HTTP traffic logging capabilities | TE-103 Threat modeling | Behavioral |
| ST-2772 | Reduce comparison corpus | TE-29 Avoid stylometry | Behavioral |
| ST-2773 | Image steganography | TE-97 Steganography | Technical |
| ST-2774 | Audio steganography | TE-97 Steganography | Technical |
| ST-2775 | Video steganography | TE-97 Steganography | Technical |
| ST-2776 | Network/Protocol steganography | TE-97 Steganography | Technical |
| ST-2777 | Text steganography | TE-97 Steganography | Technical |
| ST-2778 | Awareness of law enforcement interrogation deception tactics | TE-95 Silence | Behavioral |
| ST-2779 | Know and invoke legal rights during detention | TE-95 Silence | Behavioral |
| ST-2780 | Verify clipboard contents before sending | TE-124 Operational patience | Behavioral |
| ST-2781 | Resist counterparty time pressure | TE-124 Operational patience | Behavioral |
| ST-2782 | Avoid physically distinguishing vehicle or property markers | TE-125 Physical and social footprint minimisation | Behavioral |
| ST-2783 | Vet social circle for law enforcement proximity | TE-125 Physical and social footprint minimisation | Behavioral |
| ST-2784 | Avoid timezone-revealing greetings in anonymous communications | TE-125 Physical and social footprint minimisation | Behavioral |
| ST-2785 | Avoid bragging or status display | TE-125 Physical and social footprint minimisation | Behavioral |
| ST-2786 | Active disinformation feeding (red herring) | TE-46 Deception | Behavioral |
| ST-2787 | Avoid SMR (Shingled Magnetic Recording) drives for hidden volumes | TE-56 Hidden volume | Technical |
| ST-2788 | Awareness of spin-stand microscopy as physical forensic threat | TE-56 Hidden volume | Technical |
| ST-2789 | Prefer mandatory-privacy cryptocurrencies | TE-126 Privacy-preserving cryptocurrency selection | Technical |
| ST-2790 | Evaluate cryptographic privacy mechanism | TE-126 Privacy-preserving cryptocurrency selection | Technical |
| ST-2791 | Avoid unnecessary service registrations | TE-127 Pre-emptive data minimisation | Behavioral |
| ST-2792 | Use ephemeral communication services | TE-127 Pre-emptive data minimisation | Technical |
| ST-2793 | Scheduled cryptographic key rotation | TE-128 Periodic OPSEC review and adaptation | Technical |
| ST-2794 | Awareness of law enforcement cryptocurrency lure technique | TE-96 Situational awareness | Behavioral |
| ST-2795 | Protocol hiding vs. network circumvention distinction | TE-19 Anti-censorship | Technical |
| ST-2797 | Awareness of Raptor / BGP correlation attacks against Tor | TE-129 BGP-level network infrastructure security | Technical |
| ST-2798 | Verify physical vs. virtual server location | TE-129 BGP-level network infrastructure security | Technical |
| ST-2799 | RPKI validation for server infrastructure | TE-129 BGP-level network infrastructure security | Technical |
| ST-2800 | Rotating server infrastructure to prevent traffic correlation | TE-129 BGP-level network infrastructure security | Technical |
| ST-2801 | TLS fingerprint impersonation (uTLS / ClientHello spoofing) | TE-19 Anti-censorship | Technical |
| ST-2803 | Maintained normalcy cover profile | TE-118 Compartmentalization | Behavioral |

#### Procedures (PR)

| ID | Name | Parent | Category |
|----|------|--------|----------|
| TTP-1458 | DeadManSwitch | ST-2762 Software dead man's switch | Technical |
| TTP-1459 | gokill | ST-2762 Software dead man's switch | Technical |
| TTP-1460 | Cryptomator | ST-2763 Client-side cloud encryption | Technical |
| TTP-1461 | Duplicity | ST-307 Encrypted backups | Technical |
| TTP-1462 | GtkHash | ST-2764 Hash-based software integrity verification | Technical |
| TTP-1463 | PrivateKeyVault | ST-2765 Air-gapped cryptographic key management | Technical |
| TTP-1464 | i2pd | ST-374 Invisible Internet Project (I2P) | Technical |
| TTP-1465 | Remmina | TE-80 Remote Desktop Protocol (RDP) | Technical |
| TTP-1466 | RealVNC viewer | TE-80 Remote Desktop Protocol (RDP) | Technical |
| TTP-1470 | Cryptsetup | ST-312 Encrypted Logical Volume Manager (LVM) | Technical |
| TTP-1472 | Steghide | ST-2773 Image steganography | Technical |
| TTP-1473 | Stegosuite | ST-2773 Image steganography | Technical |
| TTP-1474 | Xiao steganography | ST-2773 Image steganography | Technical |
| TTP-1475 | OpenPuff | ST-2773 Image steganography | Technical |
| TTP-1476 | SSuite Picsel | ST-2775 Video steganography | Technical |
| TTP-1477 | Wayback Machine onion service as JS-free clearnet proxy | TE-36 Bypass human verification | Technical |
| TTP-1478 | Xray Core | TE-19 Anti-censorship | Technical |
| TTP-1479 | VLESS+XTLS | TE-19 Anti-censorship | Technical |
| TTP-1480 | VLESS+REALITY | TE-19 Anti-censorship | Technical |
| TTP-2796 | OBFS4 IAT-MODE timing obfuscation | ST-433 Obfuscated bridges | Technical |

#### Website

- Website dark mode toggle is available

### Changed

- Updated description of TE-80 Remote Desktop Protocol (RDP)
- Website visual design adapted from MITRE ATT&CK website

### Removed

- **TTP-299 CannaHome** — darknet market listing removed from dataset.


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