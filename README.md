# Introduction

* [howdns.works](https://howdns.works/episodes/)
* [A warm welcome to DNS](https://powerdns.org/hello-dns/)
* [35C3 - Domain Name System - Hannes Mehnert](https://www.youtube.com/watch?v=I7060fqa-B8)
* [Let's hand write DNS messages | James Routley](https://routley.io/tech/2017/12/28/hand-writing-dns-messages.html)

# Authoritative Nameservers

* [nsd](https://github.com/NLnetLabs/nsd)
* [PowerDNS](https://github.com/PowerDNS/pdns)
* [Knot DNS](https://gitlab.labs.nic.cz/knot/knot-dns)
* [Bind](https://gitlab.isc.org/isc-projects/bind9)
* [tinydns](https://cr.yp.to/djbdns/tinydns.html)
* [coredns](https://github.com/coredns/coredns)
* [tenta-dns](https://github.com/tenta-browser/tenta-dns)
* [shaman](https://github.com/nanopack/shaman)
* [robdns](https://github.com/robertdavidgraham/robdns)

# Relevant Projects

* [zonemaster](https://github.com/dotse/zonemaster/)
* [dnssec-monitor](https://github.com/dotse/dnssec-monitor)
* [dnstwist](https://github.com/elceef/dnstwist/)
* [octodns](https://github.com/github/octodns/)
* [opendnssec](https://github.com/opendnssec/opendnssec)
* [DNSCurve: Usable security for DNS](https://dnscurve.org/)
* [denominator](https://github.com/Netflix/denominator)
* [nmap dns-fuzz](https://nmap.org/nsedoc/scripts/dns-fuzz.html)
* [Yeti DNS](https://yeti-dns.org/)
* [NicTool](https://github.com/msimerson/NicTool)
* [cullum/dank-selfhosted](https://github.com/cullum/dank-selfhosted/tree/master/roles/nsd)

# Monitoring

* [DNS query/response logging with dnstap - Jan-Piet Mens](https://jpmens.net/2017/09/11/dns-query-response-logging-with-dnstap/)
* [How Cloudflare analyzes 1M DNS queries per second](https://blog.cloudflare.com/how-cloudflare-analyzes-1m-dns-queries-per-second/)
* [On the surprising connection between the magic HyperLoglog and DNSSEC NSEC3](https://ds9a.nl/hypernsec3/)

## Passive DNS

* [ISC Passive DNS Architecture](https://www.farsightsecurity.com/assets/media/download/passive-dns-architecture.pdf)
* [Farsight DNSDB API Documentation](https://api.dnsdb.info/)
* [Passive observations of a large DNS service - Wouter de Vries](https://blog.apnic.net/2018/08/14/passive-observations-of-a-large-dns-service/)
* [Passive DNS Replication - enyo.de](http://www.enyo.de/fw/software/dnslogger/)
* [Alternatives to Passive DNS Replication - enyo.de](http://www.enyo.de/fw/software/dnslogger/alternatives.html)
* [Passive DNS Replication WHOIS Server - enyo.de](http://www.enyo.de/fw/software/dnslogger/whois.html)

# Benchmarking

* [knot - dns benchmarking](https://gitlab.labs.nic.cz/knot/dns-benchmarking)

# Provisioning

* [Automatic provisioning of slave DNS servers - Jan-Piet Mens](https://jpmens.net/2013/02/13/automatic-provisioning-of-slave-dns-servers/)
* [How the AXFR protocol works](https://cr.yp.to/djbdns/axfr-notes.html)
* [Managing DNS Zones Using Git - Ondřej Caletka](https://labs.ripe.net/Members/ondrej_caletka/managing-dns-zones-using-git)

# Security

* [DomainChroma: Building actionable threat intelligence from malicious domain names](https://www.sciencedirect.com/science/article/pii/S0167404818302967)
* [The Modality of Mortality in Domain Names](https://www.farsightsecurity.com/assets/media/download/VB2018-study.pdf)
* [Esoteric sub-domain enumeration techniques](https://github.com/appsecco/bugcrowd-levelup-subdomain-enumeration)
* [OpenBSD as an authoritative DNS nameserver](https://cryogenix.net/openbsd_nameserver.html)
* [Bitsquatting: DNS Hijacking without Exploitation - Artem Dinaburg](http://media.blackhat.com/bh-us-11/Dinaburg/BH_US_11_Dinaburg_Bitsquatting_WP.pdf)
* [Observations on checksum errors in DNS queries to verisign's name servers - Duane Wessels](https://www.verisign.com/assets/VRSN_Bitsquatting_TR_20120320.pdf)
* [DNS Response Policy Zones](https://ftp.isc.org/isc/dnsrpz/isc-tn-2010-1.txt)
* [DNS over TLS: Encrypting DNS end-to-end - Facebook Code](https://code.fb.com/security/dns-over-tls/)

## DNSSEC

* [OpenDNSSEC Lab & Training](https://github.com/opendnssec/odslab)
* [How To Set Up DNSSEC on an NSD Nameserver on Ubuntu 14.04](https://www.digitalocean.com/community/tutorials/how-to-set-up-dnssec-on-an-nsd-nameserver-on-ubuntu-14-04)
* [DNSSEC Signer Migration](https://labs.ripe.net/Members/anandb/dnssec-signer-migration)
* [Resilient OpenDNSSEC](https://www.nlnetlabs.nl/downloads/publications/Aleksandar-Kasabov-OpenDNSSEC.pdf)
* [Against DNSSEC - Quarrelsome](https://sockpuppet.org/blog/2015/01/15/against-dnssec/)
* [DNSSEC-bis for complete beginners (like me)](https://ds9a.nl/dnssec/)
* [The role of DNS and DNSSEC in information security](https://ds9a.nl/secure-dns.html)
* [DNSSEC - The Good The Bad and The Very Bad](http://conference.hackinthebox.org/hitbsecconf2011ams/materials/D2T3%20-%20Bert%20Hubert%20-%20DNSSEC%20-%20The%20Good%20The%20Bad%20and%20The%20Very%20Bad.pdf)
* [14 DNS Nerds Don't Control The Internet - Quarrelsome](https://sockpuppet.org/blog/2016/10/27/14-dns-nerds-dont-control-the-internet/)
* [Parents, children, CDS/CDNSKEY records, and dnssec-cds](https://jpmens.net/2017/09/21/parents-children-cds-cdnskey-records-and-dnssec-cds/)

## Reports

* [The .io Error - Taking Control of All .io Domains With a Targeted Registration | The Hacker Blog](https://thehackerblog.com/the-io-error-taking-control-of-all-io-domains-with-a-targeted-registration/index.html)
* [The Journey to Hijacking a Country's TLD - The Hidden Risks of Domain Extensions | The Hacker Blog](https://thehackerblog.com/the-journey-to-hijacking-a-countrys-tld-the-hidden-risks-of-domain-extensions/index.html)
* [Hacking Guatemala’s DNS – Spying on Active Directory Users By Exploiting a TLD Misconfiguration | The Hacker Blog](https://thehackerblog.com/hacking-guatemalas-dns-spying-on-active-directory-users-by-exploiting-a-tld-misconfiguration/index.html)
* [Respect My Authority – Hijacking Broken Nameservers to Compromise Your Target | The Hacker Blog](https://thehackerblog.com/respect-my-authority-hijacking-broken-nameservers-to-compromise-your-target/index.html)
* [Floating Domains – Taking Over 20K DigitalOcean Domains via a Lax Domain Import System | The Hacker Blog](https://thehackerblog.com/floating-domains-taking-over-20k-digitalocean-domains-via-a-lax-domain-import-system/index.html)
* [The Orphaned Internet – Taking Over 120K Domains via a DNS Vulnerability in AWS, Google Cloud, Rackspace and Digital Ocean | The Hacker Blog](https://thehackerblog.com/the-orphaned-internet-taking-over-120k-domains-via-a-dns-vulnerability-in-aws-google-cloud-rackspace-and-digital-ocean/index-2.html)
* [The International Incident – Gaining Control of a .int Domain Name With DNS Trickery | The Hacker Blog](https://thehackerblog.com/the-international-incident-gaining-control-of-a-int-domain-name-with-dns-trickery/index.html)
 * [Microsoft Azure data deleted because of DNS outage](https://nakedsecurity.sophos.com/2019/02/01/dns-outage-turns-tables-on-azure-database-users/)
 * [DNSpionage Campaign Targets Middle East  - Talos](https://blog.talosintelligence.com/2018/11/dnspionage-campaign-targets-middle-east.html)
 * [A Deep Dive on the Recent Widespread DNS Hijacking Attacks - Krebs on Security](https://krebsonsecurity.com/2019/02/a-deep-dive-on-the-recent-widespread-dns-hijacking-attacks/)


# Development

* [“The DNS Camel”, or, the rise in DNS complexity - Bert Hubert](https://blog.powerdns.com/2018/03/22/the-dns-camel-or-the-rise-in-dns-complexit/)
* [How we made our DNS stack 3x faster](https://blog.cloudflare.com/how-we-made-our-dns-stack-3x-faster/)

# Blogs

* [Jan-Piet Mens](https://jpmens.net/)
* [APNIC Blog](https://blog.apnic.net/tag/dns/)
* [PowerDNS Blog](https://blog.powerdns.com/)
* [DNS - CircleID](http://www.circleid.com/topics/dns)
* [DNS - The Cloudflare Blog](https://blog.cloudflare.com/tag/dns/)

# Conferences

* [DNS-OARC](https://indico.dns-oarc.net/)

# Talks

* [DEF CON 16 - Dan Kaminsky: Black Ops 2008](https://www.youtube.com/watch?v=7Pp72gUYx00)
* [High-speed high-security cryptography: encrypting and authenticating the whole Internet - Daniel J. Bernstein](https://media.ccc.de/v/27c3-4295-en-high_speed_high_security_cryptography)
* [Bert Hubert “DNS is the Gateway to Good & Bad: How OX helps to secure the Internet”](https://vimeo.com/241165925)
* [Bert Hubert "HyperLogLog inspired three-minute scan of DNSSEC delegations worldwide"](https://indico.dns-oarc.net/event/26/contributions/437/attachments/395/671/hyperloglog_1.pdf)

# Books

* [DNS Security: In-depth Vulnerability Analysis and Mitigation Solutions](https://www.goodreads.com/book/show/19251179-dns-security)
* [DNSSEC Mastery: Securing the Domain Name Service with BIND](https://www.tiltedwindmillpress.com/product/dnssec-mastery-securing-the-domain-name-service-with-bind-ebook/)
* [Managing Mission - Critical Domains and DNS](https://www.packtpub.com/networking-and-servers/managing-mission-critical-domains-and-dns)

## Free

* [Alternative DNS servers the book - Jan-Piet Mens](https://jpmens.net/2010/10/29/alternative-dns-servers-the-book-as-pdf/)
* [DNS for Rocket Scientists](http://www.zytrax.com/books/dns/)

# RFCs

* https://www.isc.org/community/rfcs/dns/

# Papers/Publications

* [Federated Domain Name Service Using DNS Metazones - Paul Vixie](https://jpmens.net/drop/metazones.pdf)
* [Secure Domain Name System (DNS) Deployment Guide](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-81-2.pdf)
* [Passive Observations of a Large DNS Service: 2.5 Years in the Life of Google](http://tma.ifip.org/2018/wp-content/uploads/sites/3/2018/06/tma2018_paper30.pdf)
* [Nameserver Predelegation Check (German) - denic](https://www.denic.de/fileadmin/public/documentation/DENIC-23p.pdf)
* [Beobachtungsmöglichkeiten im Domain Name System: Angriffe auf die Privatsphäre und Techniken zum Selbstdatenschutz - Dominik Herrmann (German)](https://svs.informatik.uni-hamburg.de/publications/2015/2015-12-01-Herrmann-GI-Disspreis-Beobachtungsmoeglichkeiten-im-DNS.pdf)
* [DNSSEC HOWTO - Olaf Kolkman](https://www.dns-school.org/Documentation/dnssec_howto.pdf)
* [Erkennung von Angriffsmustern in Passiv-DNS-Daten - Bachelorarbeit Nick Diedrich](http://edoc.sub.uni-hamburg.de/haw/volltexte/2017/4012/pdf/Bachelorarbeit_Nick_Diedrich.pdf)
