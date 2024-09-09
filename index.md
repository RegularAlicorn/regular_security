# 2024
## September
* [Kibana ](https://securityonline.info/critical-kibana-flaws-cve-2024-37288-cve-2024-37285-expose-systems-to-arbitrary-code-execution/)
     * yaml deserialization error in amazon bedrock connector
     * yaml deserialization vulnerability allowing RCE. Requires some pre-owned privileges
* DoS attack and possible unauthenticated resource access for [Sonic Firewalls](https://psirt.global.sonicwall.com/vuln-detail/SNWLID-2024-0015). **Go update!**
* [These findings by RAND](https://www.rand.org/pubs/research_reports/RRA2680-1.html) also apply to companies selling you their AI (which includes security companies). The general issue "human factor" remains unsolved.

> Five leading root causes of the failure of AI projects were identified
> * First, industry stakeholders often misunderstand — or miscommunicate — what problem needs to be solved using AI.
> * Second, many AI projects fail because the organization lacks the necessary data to adequately train an effective AI model.
> * Third, in some cases, AI projects fail because the organization focuses more on using the latest and greatest technology than on solving real problems for their intended users.
> * Fourth, organizations might not have adequate infrastructure to manage their data and deploy completed AI models, which increases the likelihood of project failure.
> * Finally, in some cases, AI projects fail because the technology is applied to problems that are too difficult for AI to solve.

## August
* [RCE in SolarWinds Web Helpdesk](https://nvd.nist.gov/vuln/detail/CVE-2024-28986). They "couldn't reproduce unauthenticated access". Sure, let's believe them.
* !: [Windows TCP/IP v6 remote exploitation](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-38063). Wormable.
* Another heavy Ivanti Issue, this time in [Virtual Traffic Manager](https://forums.ivanti.com/s/article/Security-Advisory-Ivanti-Virtual-Traffic-Manager-vTM-CVE-2024-7593?language=en_US)  
Apparently you can modify with at least sudo privileges on Unix-OS level from outside.
* [Hacker leaked american SSNs of virtually every US citizen](https://www.bleepingcomputer.com/news/security/hackers-leak-27-billion-data-records-with-social-security-numbers/) (330 mil. population vs. 2.7 billion records leaked. Dublicated entries explain this)
    * the SSN is tied to a person from birth and can not be changed. It's used to loans, credits and more
    * if you are affected, make sure to watch your finances and consider e.g. freezing credit
    * [Troy Hunt](https://www.troyhunt.com/inside-the-3-billion-people-national-public-data-breach/) suggests, this breach contains mostly bad webscraping data, already dead peoples data nad other unfitting contents. This paints the whole breach more of a "not-so-important"-color. Still, take care and monitor your credits. Treat this "unverified" for now.
* [The Guardian](https://www.theguardian.com/world/2023/feb/15/revealed-disinformation-team-jorge-claim-meddling-elections-tal-hanan) reported about an isreali group allegedly meddling with 33 pressidental elections around the world
* [Zero-Click, unauthenticated RCE in IPv6 implementation of Windows](https://www.cybermaxx.com/resources/cve-2024-38063/)
    * [Heavy classification from MS](https://msrc.microsoft.com/update-guide/en-US/advisory/CVE-2024-38063)


## Remember for 2024
* [Windows Recall](https://doublepulsar.com/recall-stealing-everything-youve-ever-typed-or-viewed-on-your-own-windows-pc-is-now-possible-da3e12e9465e)
  * Multiple security issues (unsecured database with information, screenshots every 5 seconds)
  * Lies about how secure the product is
