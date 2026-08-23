# Changelog

All notable changes to the **CLOAK dataset** will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

---

## August 2026

### Added

#### Website

- Search now also indexes procedures (ID, name, description), with a dedicated "Procedures" result group in the search dropdown that jumps straight to the (sub)technique the procedure belongs to.
- Search and category filters remain usable on every view, not just the Matrix — previously they were hidden on tactic and technique pages.
- New **About** page featuring the CLOAK logo.
- Total procedure count added next to the tactic/technique/subtechnique counts shown above the Matrix.
- Updated CLOAK wordmark logo across the site.

#### Techniques (TE)

| ID | Name | Tactic | Category |
|----|------|--------|----------|
| TE-130 | Negotiation channel security | Secure behavior | Technical |
| TE-131 | Resilience | Anonymous hosting | Technical |
| TE-132 | Payment verification | Anonymous transactions | Technical |
| TE-133 | Financial intermediaries | Anonymous transactions | Behavioral |
| TE-134 | Denial | Plausible deniability | Behavioral |
| TE-135 | Organizational role separation | Plausible deniability | Behavioral |
| TE-136 | Use victim infrastructure | Reduce attack surface | Technical |
| TE-137 | Counterparty vetting | Risk management | Behavioral |

#### Subtechniques (ST)

| ID | Name | Parent | Category |
|----|------|--------|----------|
| ST-2900 | Decentralized instant messaging | TE-8 Anonymous instant messaging | Technical |
| ST-2901 | Virtual phone numbers | TE-11 Anonymous phone number | Technical |
| ST-2902 | Reverse tunneling | TE-77 Proxy | Technical |
| ST-2903 | Proxy chaining | TE-77 Proxy | Technical |
| ST-2904 | Address format considerations | TE-126 Privacy-preserving cryptocurrency selection | Technical |
| ST-2905 | Peer-to-peer encrypted messenger | TE-8 Anonymous instant messaging | Technical |

#### Procedures (PR)

| ID | Name | Parent | Category |
|----|------|--------|----------|
| TTP-2900 | Proton Mail | TE-7 Anonymous email | Technical |
| TTP-2901 | Gmail | TE-7 Anonymous email | Technical |
| TTP-2902 | Qaz.im | ST-152 Burner email | Technical |
| TTP-2904 | Rocket.chat | TE-8 Anonymous instant messaging | Technical |
| TTP-2905 | Exploit.im | ST-326 Extensible Messaging and Presence Protocol (XMPP) | Technical |
| TTP-2906 | Cloudflare ZeroTrust tunnel | ST-2902 Reverse tunneling | Technical |
| TTP-2907 | Fast Reverse Proxy (FRP) | ST-2902 Reverse tunneling | Technical |
| TTP-2908 | 1ty.me | TE-114 Anonymous file sharing | Technical |
| TTP-2909 | Anonfiles.app | TE-114 Anonymous file sharing | Technical |
| TTP-2910 | Bashupload | TE-114 Anonymous file sharing | Technical |
| TTP-2911 | Dropfiles | TE-114 Anonymous file sharing | Technical |
| TTP-2912 | Dropmefiles.com | TE-114 Anonymous file sharing | Technical |
| TTP-2913 | File.io | TE-114 Anonymous file sharing | Technical |
| TTP-2914 | FileTransfer.io | TE-114 Anonymous file sharing | Technical |
| TTP-2915 | Gofile.io | TE-114 Anonymous file sharing | Technical |
| TTP-2916 | ImgBB | TE-114 Anonymous file sharing | Technical |
| TTP-2917 | Limewire.com | TE-114 Anonymous file sharing | Technical |
| TTP-2918 | Mega.nz | TE-114 Anonymous file sharing | Technical |
| TTP-2919 | Sendspace.com | TE-114 Anonymous file sharing | Technical |
| TTP-2920 | Tempsend.com | TE-114 Anonymous file sharing | Technical |
| TTP-2921 | Transfer.sh | TE-114 Anonymous file sharing | Technical |
| TTP-2922 | Ufile.io | TE-114 Anonymous file sharing | Technical |
| TTP-2923 | Up1 | TE-114 Anonymous file sharing | Technical |
| TTP-2924 | Wetransfer | TE-114 Anonymous file sharing | Technical |
| TTP-2925 | temp.sh | TE-114 Anonymous file sharing | Technical |
| TTP-2926 | Prnt.sc | TE-114 Anonymous file sharing | Technical |
| TTP-2927 | Avoid CIS countires | TE-96 Situational awareness | Behavioral |
| TTP-2928 | Avoid email communication | TE-96 Situational awareness | Behavioral |
| TTP-2929 | Avoid insecure channels | TE-96 Situational awareness | Behavioral |
| TTP-2930 | Git repository | TE-113 Open Source Software (OSS) | Technical |
| TTP-2931 | Erase shared evidence to defeat third-party monitoring | TE-130 Negotiation channel security | Behavioral |
| TTP-2932 | Password-protect negotiation chat | TE-130 Negotiation channel security | Technical |
| TTP-2933 | Refuse to click victim-provided links | TE-130 Negotiation channel security | Technical |
| TTP-2934 | Rotate to fresh chat link for sensitive phase | TE-130 Negotiation channel security | Technical |
| TTP-2935 | Backup communication platform | TE-130 Negotiation channel security | Technical |
| TTP-2936 | Private communication server | TE-130 Negotiation channel security | Technical |
| TTP-2937 | Preferred communication language | TE-130 Negotiation channel security | Behavioral |
| TTP-2938 | Password protected chat | TE-130 Negotiation channel security | Technical |
| TTP-2939 | Password protected panel | TE-130 Negotiation channel security | Technical |
| TTP-2940 | Mirror site for takedown resistance | TE-131 Resilience | Technical |
| TTP-2941 | File upload restriction | TE-87 Secure hosting | Technical |
| TTP-2942 | 4vps.su | ST-633 Virtual Private Server (VPS) | Technical |
| TTP-2943 | JustHost | ST-633 Virtual Private Server (VPS) | Technical |
| TTP-2944 | Amnezia VPN | ST-545 Selfhosted VPN | Technical |
| TTP-2945 | Chain-hopping | TE-38 Cleaning coins | Technical |
| TTP-2946 | Bech32 address | ST-2904 Address format considerations | Technical |
| TTP-2947 | SegWit address | ST-2904 Address format considerations | Technical |
| TTP-2948 | Non-segwit wallet | ST-2904 Address format considerations | Technical |
| TTP-2949 | Disguise payment purpose from bank/exchange | TE-16 Anonymously buy cryptocurrency | Behavioral |
| TTP-2950 | Recommend non-custodial wallets | TE-16 Anonymously buy cryptocurrency | Technical |
| TTP-2951 | Small test transaction before full payment | TE-132 Payment verification | Technical |
| TTP-2952 | Money mule | TE-133 Financial intermediaries | Physical |
| TTP-2953 | Fake business | TE-133 Financial intermediaries | Behavioral |
| TTP-2954 | Fake business bank accounts | TE-133 Financial intermediaries | Behavioral |
| TTP-2955 | Offshore bank accounts | TE-133 Financial intermediaries | Behavioral |
| TTP-2956 | Safety deposit boxes | TE-133 Financial intermediaries | Physical |
| TTP-2957 | PayPal | TE-133 Financial intermediaries | Technical |
| TTP-2958 | Fraud | TE-133 Financial intermediaries | Behavioral |
| TTP-2959 | Disguised copy | ST-472 Physical concealment | Physical |
| TTP-2960 | Deny data exfiltration to limit legal exposure | TE-134 Denial | Behavioral |
| TTP-2961 | Blame-shifting to autonomous affiliate | TE-135 Organizational role separation | Behavioral |
| TTP-2962 | Remote access via victim's legitimate tools | TE-136 Use victim infrastructure | Technical |
| TTP-2963 | Counter Anti-Virus (CAV) | TL-13 Tactic-level TTPs & Procedures | Technical |
| TTP-2964 | Verify negotiator authority | TE-137 Counterparty vetting | Behavioral |
| TTP-2965 | Tox | ST-2905 Peer-to-peer encrypted messenger | Technical |


### Changed

- Subtechniques on a technique's detail page are now shown as expandable cards with their own procedures nested directly underneath them, instead of all procedures being pooled into a single flat list at the bottom of the page.
- Top navigation now shows only the CLOAK wordmark logo.

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
