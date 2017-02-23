AVPWN
=====

List of real-world threats against endpoint protection software - For future reference. The list is based on public information and thus is obviously incomplete. 

The list should include:
  * Non-public 0-day exploits at the time of reference
  * Public incidents where attackers exploited endpoint protection software 
  * Supporting public evidence should be provided for all records

The list doesn't include: 
  * Exploits intentionally disclosed to the vendor in any way (including full uncoordinated disclosure)
  * Detection bypasses, because I don't want to fill up the storage space of GitHub
  * Attacks or exploits against perimeter products, because I'm lazy

The List
--------

| Name                                                                        | Link                                                   | Internal ID | Server Side | Client Side | Known Incident |
|-----------------------------------------------------------------------------|--------------------------------------------------------|-------------|-------------|-------------|----------------|
| avast! Local Information Disclosure                                         | https://wikileaks.org/hackingteam/emails/emailid/45441 | 13-005      |           0 |           1 |       Brokered |
| avast! Local Privilege Escalation                                           | https://wikileaks.org/hackingteam/emails/emailid/45441 | 13-010      |           0 |           1 |       Brokered |
| McAfee ePolicy Orchestrator Privileged Remote Code Execution                | https://wikileaks.org/hackingteam/emails/emailid/45441 | 13-019      |           1 |           0 |       Brokered |
| McAfee ePolicy Orchestrator Post-Auth Privileged Remote Code Execution      | https://wikileaks.org/hackingteam/emails/emailid/45441 | 13-023      |           1 |           0 |       Brokered |
| McAfee ePolicy Orchestrator Post-Auth Privileged Remote Code Execution      | https://wikileaks.org/hackingteam/emails/emailid/45441 | 13-024      |           1 |           0 |       Brokered |
| ESET NOD32 Antivirus and ESET Smart Security Remote Pre-auth Code Execution | https://wikileaks.org/hackingteam/emails/emailid/45441 | 2010-0021   |           0 |           1 | Brokered, Sold |
| Symantec AntiVirus Remote Stack Buffer Overflow  | http://www.securityfocus.com/news/11426 | CVE-2006-2630   |           0 |           1 | Exploited ItW |

### Honorable mentions

* As of November 2016. Zerodium (a prominent vulnerability broker) [is offering](https://web.archive.org/web/20161108134847/http://zerodium.com/program.html) up to $40.000 for Antivirus LPE/RCE
* In 2014. Kaspersky [reported](https://kasperskycontenthub.com/wp-content/uploads/sites/43/vlpdfs/unveilingthemask_v1.0.pdf) that the Careto malware was attempting to exploit a vulnerability in their products _"to make the malware 'invisible' in the system"_. The targeted vulnerability was fixed in 2008.
* In 2015. Kaspersky [reported](https://blog.kaspersky.co.uk/kaspersky-statement-duqu-attack/5858/) a compromise of their own systems. According to the report _"neither [Kaspersky's] products nor services have been compromised"_, and attackers were after information about _"ongoing investigations [...] detection methods and analysis capabilities"_.
