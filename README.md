# Highly Resistant Censorship Evasion Using Multi-Stage Trojan Technology
Multi-stage Trojan technology aims to enhance censorship resistance by reusing existing Trojans.
Its greatest advantage over existing Tor and VPNs is its high censorship resistance.
Tor is good for anonymity and privacy protection, but it is easily blocked and difficult to use for censorship evasion.
VPNs have long been used to access sites from censored countries, but recently they have become more prone to blocking and their high fees have become a drawback.
This multi-stage Trojan technology simply bypasses HTTPS, making it less susceptible to censorship and less expensive to maintain.
1. The core technology is the chain construction of Trojan servers.
When a Trojan accesses server S1, the information is immediately forwarded to server S2. S2 then moves to server S3, which ultimately accesses the target site.
This makes physical access tracking difficult. By using multiple routes, it appears to be a normal HTTPS redirect, enabling censorship evasion.

# Core Technology I: Massively Distributed Server Architecture
This architecture relies on individual servers rather than large-scale servers.
Large-scale servers increase stability, but also increase the likelihood of exploitation and maintenance costs.
Of course, this is run by volunteers. If you're interested, please join us!

## Core Technology II: Dynamic Defense (MTD)
By changing IP addresses irregularly, we prevent the creation of censorship lists and make constant access impossible through IP address changes alone.
Furthermore, irregular changes also prevent periodic access bans.

# Core Technology III: Automatic Listing

This requires a lot of effort, but is absolutely essential.
Approved servers are listed and made accessible to users.
Manual listing is possible, but automating it reduces the burden and enables faster provisioning.

# Proof of Concept (PoC) Phase Goals

1. Core Protocol: Implement a Trojan module for HTTPS spoofing.
2. MTD System: Create a PoC for automatic IP changing and discarding code.
3. Node Management: Implement a prototype for automatic removal of censored servers and node detection.

# Ethics and Licensing

All MSTS code will be released under the GPL v3. This prevents technology monopolies and ensures contributions to the community.
