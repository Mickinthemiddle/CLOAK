![Alt text](https://github.com/Mickinthemiddle/CLOAK/blob/main/CLOAK.png)
# Concealment Layers for Online Anonymity and Knowledge (CLOAK)
CLOAK is the first publicly available knowledge base on cybercriminal concealment measures. CLOAK is the result of qualitative scientific research and has been inspired by the famous [MITRE ATT&CK™](https://attack.mitre.org) framework. CLOAK has been developed by analyzing over 200 Operational Security (OpSec) guides from both the clear- and darkweb. CLOAK's main objective is to contribute to combating cybercrime better and has been made publicly available to allow improvements to be made together with the cybersecurity community. CLOAK's initial version (January 2025) already identified 13 tactics, 109 techniques, 679 sub-techniques, and 586 procedures. Which comes down to a total of 1.459 unique TTP's! For an interactive version of CLOAK please see https://opsectechniques.com. 

## The problem
Cybercrime is a global growing problem and concealment measures make attribution of cybercrime hard or impossible, because they provide threat actors anonymity. We tend to focus on tactics, techniques, and procedures (TTPs) with respect to cyberattacks, but focus very little on adversarial concealment measures which preserve their anonymity through and in cyberspace. Concealment measures allow cybercriminals to get away with their crimes and continue them for a longer period of time. It is therefore necessary to conduct more scientific research on this underexposed topic to combat cybercrime better. 

Three types of cybercrime are distinguished: cyber-dependent crime (type I), cyber-enabled crime (type II), and crimes in the machine (type III). We mainly focus on cyber-dependent (type I) crimes, as one can notice by looking at MITRE ATT&CK. CLOAK’s focus on cybercrime broadens our current view on cybercrime by also focussing on the other types of cybercrime as well, and including the ‘before’ and ‘after’ phases. By doing so, it opens the door for other approaches in combating cybercrime. For example the ability to identify gaps in countermeasures and detection capabilities, or the ability to fingerprint threat actors based on the concealment measures they apply, instead of their deployed TTPs during cyberattacks.

## The science
The findings of the qualitative scientific research showed that concealment measures are taken in three levels: technical, behavioral, and physical. To achieve the best possible level of anonymity, cybercriminals must take measures in all three levels. The role each level plays with respect to concealment and the most mentioned measures have been briefly described below. For more information about concealment measures and how they are interconnected, please see [CLOAK](https://opsectechniques.com). A scientific article about CLOAK is expected to be published later this year. 

### Technical
The technical measures are the most important for _becoming_ anonymous. The most important technical measures are The Onion Router (TOR), Virtual Private Networks (VPN), encryption, isolation, anti-fingerprinting, wiping traces, and hardening.

### Behavioral
The behavioral measures are the most important for _staying_ anonymous. The most important behavioral measures are remaining silent about illicit activities, avoidance of sharing personal details, compartmentalization, threat modeling, risk management, unique credentials, public Wi-Fi, and applying deception.

### Physical
The physical measures are necessary in conjunction with technical and behavioral measures for _continuity, detection and evasion_ of law enforcement agencies. The most important physical measures are faraday cages, physical destruction of hardware, tamper detection, paper wallets, data leak prevention, and removing or covering unnecessary components.

## Use cases
### Understanding cybercriminal behavior
CLOAK provides oversight of and insight into cybercriminal concealment measures from a technical, behavioral, and physical perspective, and thus provides a better understanding of cybercriminal behavior and how those measures are interconnected. CLOAK is therefore suitable to raise awareness about cybercriminal behavior. 

### Aid criminal investigations
CLOAK could be leveraged by law enforcement agencies and security and intelligence services to determine their next course of action in cybercriminal investigations, and identify gaps in their countermeasure arsenal.

### Unified referencing TTPs
CLOAK could be leveraged to reference to cybercriminal concealment TTPs in a unified manner, for example in indictments and technical write-ups. This allows to speak the same language globally with respect to cybercriminal concealment techniques.

### Identify gaps
CLOAK could be leveraged to identify gaps with respect to countermeasures and detection capabilities, and thus contributes to the development or improvement of countermeasures and detection capabilities.

### Circumvent censorship
Some measures can be applied by individuals living in strict regimes to circumvent censorship.  

There probably are even more practical use cases which are not mentioned here. 

## Remarks
CLOAK in it's current form is far from perfect, but it's a start. By making CLOAK open source we can hopefully together enhance it further and improve its practical value. Possible enhancements are for example:

* adding countermeasures
* adding detection capabilities
* improving the TTP descriptions
* adding more TTPs which are missing
* merging/removing outdated/ineffective TTPs
* adding effectiveness of TTPs

## The author
[Mick Deben](https://www.linkedin.com/in/mick-deben/) holds a Master of Science (MSc) in cybersecurity and has over a decade of experience in information security and cybersecurity. CLOAK was originally developed for his master’s thesis at Leiden University titled: “Hiding through and in cyberspace: Modeling cybercriminal concealment techniques” (under embargo). Feel free to reach out to cloak@opsectechniques.com. 

## License
This project is licensed under GNU General Public License, version 2.  
