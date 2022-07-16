# Introduction

* [howdns.works](https://howdns.works/episodes/)
* [A warm welcome to DNS](https://powerdns.org/hello-dns/)
* [35C3 - Domain Name System - Hannes Mehnert](https://www.youtube.com/watch?v=I7060fqa-B8)
* [Let's hand write DNS messages | James Routley](https://routley.io/posts/hand-writing-dns-messages/)
* [DNS Wars](https://www.potaroo.net/ispcol/2019-11/dnswars.html)
* [DKIM demystified](https://www.20i.com/blog/dkim-demystified/)
* [DNS for Rocket Scientists](http://www.zytrax.com/books/dns/ch1/)
* [An interview with Paul Mockapetris, the creator of the DNS](https://www.welcometothejungle.com/en/collections/behind-the-code/coder-stories/articles/btc-interview-paul-mockapetris)
* [Why updating DNS takes time](https://wizardzines.com/comics/updating-dns/)
* [(All) DNS Resource Records - netmeister.org](https://www.netmeister.org/blog/dns-rrs.html)
* [How to use dig](https://jvns.ca/blog/2021/12/04/how-to-use-dig/)
* [Mess with DNS](https://messwithdns.net/)
* [Life of a DNS query](https://wizardzines.com/comics/life-of-a-dns-query/)
* [The multiple meanings of "nameserver" and "DNS resolver"](https://jvns.ca/blog/2022/02/14/some-dns-terminology/)

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
* [texnomic/securedns](https://github.com/Texnomic/SecureDNS)

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
* [atomiadns](https://github.com/atomia/atomiadns)
* [dnsjava](https://github.com/dnsjava/dnsjava)
* [dog](https://github.com/ogham/dog)

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
* [Exposure: a Passive DNS Analysis Service to Detect and Report malicious Domains](https://sites.cs.ucsb.edu/~chris/research/doc/tissec14_exposure.pdf)

# Benchmarking

* [knot - dns benchmarking](https://gitlab.labs.nic.cz/knot/dns-benchmarking)

# Provisioning

* [Automatic provisioning of slave DNS servers - Jan-Piet Mens](https://jpmens.net/2013/02/13/automatic-provisioning-of-slave-dns-servers/)
* [How the AXFR protocol works](https://cr.yp.to/djbdns/axfr-notes.html)
* [Managing DNS Zones Using Git - Ondřej Caletka](https://labs.ripe.net/Members/ondrej_caletka/managing-dns-zones-using-git)
* [Posh Security: Managing DNS with DNSControl, CloudFlare, DNSimple, Github, VSTS, Key Vault, and Docker!](https://poshsecurity.com/blog/managing-dns-with-dnscontrol-cloudflare-dnsimple-github-vsts-key-vault-and-docker)

# Security

* [DomainChroma: Building actionable threat intelligence from malicious domain names](https://www.sciencedirect.com/science/article/pii/S0167404818302967)
* [The Modality of Mortality in Domain Names](https://www.farsightsecurity.com/assets/media/download/VB2018-study.pdf)
* [Esoteric sub-domain enumeration techniques](https://github.com/appsecco/bugcrowd-levelup-subdomain-enumeration)
* [OpenBSD as an authoritative DNS nameserver](https://cryogenix.net/openbsd_nameserver.html)
* [Bitsquatting: DNS Hijacking without Exploitation - Artem Dinaburg](http://media.blackhat.com/bh-us-11/Dinaburg/BH_US_11_Dinaburg_Bitsquatting_WP.pdf)
* [Observations on checksum errors in DNS queries to verisign's name servers - Duane Wessels](https://www.verisign.com/assets/VRSN_Bitsquatting_TR_20120320.pdf)
* [DNS Response Policy Zones](https://ftp.isc.org/isc/dnsrpz/isc-tn-2010-1.txt)
* [DNS over TLS: Encrypting DNS end-to-end - Facebook Code](https://code.fb.com/security/dns-over-tls/)
* [Posh Security: Advice on Mitigating DNS Infrastructure Tampering](https://poshsecurity.com/blog/advice-on-mitigating-dns-infrastructure-tampering)
* [DNS Security: Threat Modeling DNSSEC, DoT, and DoH](https://www.netmeister.org/blog/doh-dot-dnssec.html)
* [New Adventures in DNSSEC and DANE](https://www.netmeister.org/blog/dnssec-dane.html)
* [Bitsquatting: DNS Hijacking without exploitation](http://dinaburg.org/bitsquatting.html)
* [Hijacking of abandoned subdomains part 2](https://labs.detectify.com/2014/12/08/hijacking-of-abandoned-subdomains-part-2/)
* [A security researcher commandeered a country’s expired top-level domain to save it from hackers](https://techcrunch.com/2021/01/15/congo-comandeered/)
* [Bitsquatting microsoft.com](https://remyhax.xyz/posts/bitsquatting-windows/)
* [The Duct Tape Holding the Internet Together](https://medium.com/thisiscala/the-duct-tape-holding-the-internet-together-12118be60ff1)
* [Sinkholed](https://susam.in/blog/sinkholed/)
* [The Hijacking of perl.com](https://www.perl.com/article/the-hijacking-of-perl-com/)
* [How MarkMonitor left > 60,000 domains for the taking](https://ian.sh/markmonitor)
* [Deep inside a DNS amplification DDOS Attack](https://blog.cloudflare.com/deep-inside-a-dns-amplification-ddos-attack/)
* [DNS Cache Poisoning Attack: Resurrections with Side Channels](https://www.cs.ucr.edu/~zhiyunq/pub/ccs21_dns_poisoning.pdf)
* [Does Your Domain Have a Registry Lock?](https://krebsonsecurity.com/2020/01/does-your-domain-have-a-registry-lock/)

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
* [DNSSEC provisioning automation with CDS/CDNSKEY in the real world - Jan-Piet Mens](https://jpmens.net/2021/10/05/dnssec-cds-cdnskey-in-the-real-world/)
* [For DNSSEC - easyDNS](https://easydns.com/blog/2015/08/06/for-dnssec/)
* [Major DNSSEC Outages and Validation Failures](https://ianix.com/pub/dnssec-outages.html)

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
 * [Buying a single character domain – and 3 character FQDN – for £15](https://shkspr.mobi/blog/2020/08/buying-a-single-character-domain-and-3-character-fqdn-for-15/)
* [DNSSEC issues take Fiji domains offline](https://blog.cloudflare.com/dnssec-issues-fiji/)
* [A lock with many keys: Spoofing DNSSEC-signed domains in 8.8.8.8](https://www.sidnlabs.nl/en/news-and-blogs/a-lock-with-many-keys-spoofing-dnssec-signed-domains-in-8-8-8-8)
* [Detecting DNS Root Manipulation](https://labs.ripe.net/author/qasim-lone/detecting-dns-root-manipulation/)

# Infrastructure

## Anycast

* [Anycast DNS — Resilient Scalability for Critical Network Infrastructure Software, Part 2 — Implementation](https://medium.com/@tom.bowles/anycast-dns-part-2-4acc51e4d64f)

## TLDs

* [TLD Graveyard](https://dzdb.caida.org/tlds/graveyard)

# Development

* [“The DNS Camel”, or, the rise in DNS complexity - Bert Hubert](https://blog.powerdns.com/2018/03/22/the-dns-camel-or-the-rise-in-dns-complexit/)
* [How we made our DNS stack 3x faster](https://blog.cloudflare.com/how-we-made-our-dns-stack-3x-faster/)
* [Why We Built Our Own DNS Infrastructure - Replit](https://blog.replit.com/dns)

# Blogs

* [Jan-Piet Mens](https://jpmens.net/)
* [APNIC Blog](https://blog.apnic.net/tag/dns/)
* [PowerDNS Blog](https://blog.powerdns.com/)
* [DNS - CircleID](http://www.circleid.com/topics/dns)
* [DNS - The Cloudflare Blog](https://blog.cloudflare.com/tag/dns/)

## Articles

* [Please do not put IP addresses into DNS MX records](https://blog.hboeck.de/archives/904-Please-do-not-put-IP-addresses-into-DNS-MX-records.html)
* [The Perils of an .xyz Domain](https://www.spotvirtual.com/blog/the-perils-of-an-xyz-domain/)
* [Tackling Email Spoofing and Phishing](https://blog.cloudflare.com/tackling-email-spoofing/)
* [Understanding How Facebook Disappeared from the Internet](https://blog.cloudflare.com/october-2021-facebook-outage/)
* [What's in a hostname?](https://www.netmeister.org/blog/hostnames.html)
* [DNS Openness - RIPE Labs](https://labs.ripe.net/author/gih/dns-openness/)
* [Fun with the DNS SOA expire field](https://jpmens.net/2022/01/14/fun-with-the-dns-soa-expire-field/)
* [What happens to TLDs when their country stops existing?](https://astrid.tech/2022/04/05/1/dead-tlds/)
* [DNS Esoterica - Why you can't dig Switzerland](https://shkspr.mobi/blog/2022/07/dns-esoterica-why-you-cant-dig-switzerland/)
* [Breaking DKIM - on Purpose and by Chance](https://noxxi.de/research/breaking-dkim-on-purpose-and-by-chance.html)

## Social Media

* [Rule 53: if you can think of it, someone's done it in the DNS - Peter Lowe](https://twitter.com/pgl/status/1405614755000295427)

# Conferences

* [DNS-OARC](https://indico.dns-oarc.net/)

# Talks

* [DEF CON 16 - Dan Kaminsky: Black Ops 2008](https://www.youtube.com/watch?v=7Pp72gUYx00)
* [High-speed high-security cryptography: encrypting and authenticating the whole Internet - Daniel J. Bernstein](https://media.ccc.de/v/27c3-4295-en-high_speed_high_security_cryptography)
* [Bert Hubert “DNS is the Gateway to Good & Bad: How OX helps to secure the Internet”](https://vimeo.com/241165925)
* [Bert Hubert "HyperLogLog inspired three-minute scan of DNSSEC delegations worldwide"](https://indico.dns-oarc.net/event/26/contributions/437/attachments/395/671/hyperloglog_1.pdf)
* [Detecting and Preventing Malicious Domain Registrations in the .eu TLD - Lieven Desmet](https://www.youtube.com/watch?v=TpzhM3VFyJc)
* [Paul Vixie talks about DNS over HTTPS](https://www.youtube.com/watch?v=ZxTdEEuyxHU)
* [36C3 - Email authentication for penetration testers](https://www.youtube.com/watch?v=elxL8BU4vH8)
* [#rC3 - Encrypted DNS, Episode II](https://www.youtube.com/watch?v=ILG4WLFmN7A)
* [You have No Idea Who Sent that Email: 18 Attacks on Email Sender Authentication](https://www.youtube.com/watch?v=ar_lVqkWcHk)
* [gpn20 - Breaking things with emoji](https://www.youtube.com/watch?v=_DvzVf4f-fI)

# Podcasts

* [Network Collective - History of networking - Paul Mockapetris - Origins of DNS](https://networkcollective.com/2018/01/hon-dns-origins/)

# Books

* [DNS Security: In-depth Vulnerability Analysis and Mitigation Solutions](https://www.goodreads.com/book/show/19251179-dns-security)
* [DNSSEC Mastery: Securing the Domain Name Service with BIND](https://www.tiltedwindmillpress.com/product/dnssec-mastery-securing-the-domain-name-service-with-bind-ebook/)
* [Managing Mission - Critical Domains and DNS](https://www.packtpub.com/networking-and-servers/managing-mission-critical-domains-and-dns)

## Free

* [Alternative DNS servers the book - Jan-Piet Mens](https://jpmens.net/2010/10/29/alternative-dns-servers-the-book-as-pdf/)
* [DNS for Rocket Scientists](http://www.zytrax.com/books/dns/)

# RFCs

* https://www.isc.org/community/rfcs/dns/
* [DNS Terminology](https://tools.ietf.org/html/rfc8499)

# Tools

* [DNSViz](https://dnsviz.net/)
* [Dig web interface - online dns lookup tool](https://www.digwebinterface.com/)
* [Nameserver Predelegation Check Webinterface](https://www.denic.de/service/tools/nast/)
* [DNS Toys](https://www.dns.toys/)

# Papers/Publications

* [Federated Domain Name Service Using DNS Metazones - Paul Vixie](https://jpmens.net/drop/metazones.pdf)
* [Secure Domain Name System (DNS) Deployment Guide](http://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-81-2.pdf)
* [Passive Observations of a Large DNS Service: 2.5 Years in the Life of Google](http://tma.ifip.org/2018/wp-content/uploads/sites/3/2018/06/tma2018_paper30.pdf)
* [Nameserver Predelegation Check (German) - denic](https://www.denic.de/fileadmin/public/documentation/DENIC-23p.pdf)
* [Beobachtungsmöglichkeiten im Domain Name System: Angriffe auf die Privatsphäre und Techniken zum Selbstdatenschutz - Dominik Herrmann (German)](https://svs.informatik.uni-hamburg.de/publications/2015/2015-12-01-Herrmann-GI-Disspreis-Beobachtungsmoeglichkeiten-im-DNS.pdf)
* [DNSSEC HOWTO - Olaf Kolkman](https://www.dns-school.org/Documentation/dnssec_howto.pdf)
* [Erkennung von Angriffsmustern in Passiv-DNS-Daten - Bachelorarbeit Nick Diedrich](http://edoc.sub.uni-hamburg.de/haw/volltexte/2017/4012/pdf/Bachelorarbeit_Nick_Diedrich.pdf)
* [Counterfighting Counterfeit: detecting andtaking down fraudulent webshops at a ccTLD](https://www.sidnlabs.nl/downloads/6tIo0U3dqydRSP781LYgDP/3c1bea3394648c44e5ea155f7e3f0887/Counterfighting_Counterfeit_detecting_and_taking_down_fraudulent_webshops_at_a_ccTLD.pdf)
* [Development of the Domain Name System - Paul V. Mockapetris, Kevin J. Dunlap](https://cseweb.ucsd.edu/classes/wi01/cse222/papers/mockapetris-dns-sigcomm88.pdf)
