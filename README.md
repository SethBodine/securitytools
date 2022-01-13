![](https://avatars0.githubusercontent.com/u/2897191?s=95&v=4)
# securitytools
this repository hosts an array of GitHub projects leveraged across the security community, indexed as submodules.
```shell
docker pull ghcr.io/thetanz/securitytools:latest
```

### adding submodules
git projects can be added to this repository by navigating to an applicable folder and replacing `git clone` with `git submodule add`
### removing submodules
1. delete the relevant section from `.gitmodules`.
2. stage the `.gitmodules` changes with `git add .gitmodules`
3. delete the relevant section from `.git/config`
4. run `git rm --cached path_to_submodule` (no trailing slash).
5. run `rm -rf .git/modules/path_to_submodule` (no trailing slash).
6. commit changes `git commit -m "submodule removal"`
7. delete submodule files `rm -rf path_to_submodule`
# projects
[![report generator](https://github.com/thetanz/securitytools/actions/workflows/reporter.yml/badge.svg)](https://github.com/thetanz/securitytools/actions/workflows/reporter.yml)

this readme is dynamically generated based upon the contents of the submodules
## vendor
* [vendor/rtr](https://github.com/bk-cs/rtr)
	_Real-time Response scripts_

## forensics
* [forensics/ArtifactCollectionMatrix](https://github.com/swisscom/ArtifactCollectionMatrix)
	_Forensic Artifact Collection Tool Matrix_

## incidents
* [incidents/Aurora-Incident-Response](https://github.com/cyb3rfox/Aurora-Incident-Response)
	_Incident Response Documentation made easy. Developed by Incident Responders for Incident Responders_

## discovery
* [discovery/httprobe](https://github.com/tomnomnom/httprobe)
	_Take a list of domains and probe for working HTTP and HTTPS servers_

## websites
* [websites/dirsearch](https://github.com/maurosoria/dirsearch)
	_Web path scanner_

* [websites/ffuf](https://github.com/ffuf/ffuf)
	_Fast web fuzzer written in Go_

* [websites/weird_proxies](https://github.com/GrrrDog/weird_proxies)
	_Reverse proxies cheatsheet_

* [websites/CMSeeK](https://github.com/Tuhinshubhra/CMSeeK)
	_CMS Detection and Exploitation suite - Scan WordPress, Joomla, Drupal and over 180 other CMSs_

## osint
* [osint/spiderfoot](https://github.com/smicallef/spiderfoot)
	_SpiderFoot automates OSINT for threat intelligence and mapping your attack surface._

* [osint/sherlock](https://github.com/sherlock-project/sherlock)
	_🔎 Hunt down social media accounts by username across social networks_

* [osint/dorkScanner](https://github.com/madhavmehndiratta/dorkScanner)
	_A typical search engine dork scanner scrapes search engines with dorks that you provide in order to find vulnerable URLs._

* [osint/uDork](https://github.com/m3n0sd0n4ld/uDork)
	_uDork is a script written in Bash Scripting that uses advanced Google search techniques to obtain sensitive information in files or directories, find IoT devices, detect versions of web applications, and so on._

* [osint/CrossLinked](https://github.com/m8r0wn/CrossLinked)
	_LinkedIn enumeration tool to extract valid employee names from an organization through search engine scraping_

* [osint/holehe](https://github.com/megadose/holehe)
	_holehe allows you to check if the mail is used on different sites like twitter, instagram and will retrieve information on sites with the forgotten password function._

* [osint/reconspider](https://github.com/bhavsec/reconspider)
	_🔎 Most Advanced Open Source Intelligence (OSINT) Framework for scanning IP Address, Emails, Websites, Organizations._

* [osint/waybackpack](https://github.com/jsvine/waybackpack)
	_Download the entire Wayback Machine archive for a given URL._

## email
* [email/espoofer](https://github.com/chenjj/espoofer)
	_An email spoofing testing tool that aims to bypass SPF/DKIM/DMARC and forge DKIM signatures.🍻_

* [email/checkdmarc](https://github.com/domainaware/checkdmarc)
	_A parser for SPF and DMARC DNS records_

## authentication
* [authentication/SAML2Spray](https://github.com/LuemmelSec/SAML2Spray)
	_Python Script for SAML2 Authentication Passwordspray_

## networking
* [networking/CloudFlair](https://github.com/christophetd/CloudFlair)
	_🔎 Find origin servers of websites behind CloudFlare by using Internet-wide scan data from Censys._

* [networking/mitmengine](https://github.com/cloudflare/mitmengine)
	_A MITM (monster-in-the-middle) detection tool. Used to build MALCOLM:_

* [networking/AutoRecon](https://github.com/Tib3rius/AutoRecon)
	_AutoRecon is a multi-threaded network reconnaissance tool which performs automated enumeration of services._

* [networking/Responder](https://github.com/lgandx/Responder)
	_Responder is a LLMNR, NBT-NS and MDNS poisoner, with built-in HTTP/SMB/MSSQL/FTP/LDAP rogue authentication server supporting NTLMv1/NTLMv2/LMv2, Extended Security NTLMSSP and Basic HTTP authentication._

* [networking/wifijammer](https://github.com/DanMcInerney/wifijammer)
	_Continuously jam all wifi clients/routers_

* [networking/Tunna](https://github.com/SECFORCE/Tunna)
	_Tunna is a set of tools which will wrap and tunnel any TCP communication over HTTP. It can be used to bypass network restrictions in fully firewalled environments._

* [networking/cloud-ranges](https://github.com/pry0cc/cloud-ranges)
	_A list of cloud ranges from different providers._

* [networking/bettercap](https://github.com/bettercap/bettercap)
	_The Swiss Army knife for 802.11, BLE, IPv4 and IPv6 networks reconnaissance and MITM attacks._

## vuln-identification
* [vuln-identification/flan](https://github.com/cloudflare/flan)
	_A pretty sweet vulnerability scanner_

* [vuln-identification/nmap-vulners](https://github.com/vulnersCom/nmap-vulners)
	_NSE script based on Vulners.com API_

* [vuln-identification/tsunami-security-scanner](https://github.com/google/tsunami-security-scanner)
	_Tsunami is a general purpose network security scanner with an extensible plugin system for detecting high severity vulnerabilities with high confidence._

## indicators
* [indicators/jarm](https://github.com/salesforce/jarm)

* [indicators/yara](https://github.com/VirusTotal/yara)
	_The pattern matching swiss knife_

* [indicators/intel](https://github.com/thetanz/securitytools)
	_quality community projects  👨‍👩‍👧‍👦📓🔎_

* [indicators/ja3](https://github.com/salesforce/ja3)
	_JA3 is a standard for creating SSL client fingerprints in an easy to produce and shareable way._

## testing
* [testing/atomic-red-team](https://github.com/redcanaryco/atomic-red-team)
	_Small and highly portable detection tests based on MITRE's ATT&CK._

* [testing/PEASS-ng](https://github.com/carlospolop/PEASS-ng)
	_PEASS - Privilege Escalation Awesome Scripts SUITE (with colors)_

* [testing/all-about-apikey](https://github.com/daffainfo/all-about-apikey)
	_Detailed information about API key / OAuth token (Description, Request, Response, Regex, Example)_

* [testing/DeTTECT](https://github.com/rabobank-cdc/DeTTECT)
	_Detect Tactics, Techniques & Combat Threats_

* [testing/caldera](https://github.com/mitre/caldera)
	_Automated Adversary Emulation Platform_

* [testing/joystick](https://github.com/mitre-attack/joystick)
	_Joystick is a tool that gives you the ability to transform the ATT&CK Evaluations data into concise views that brings forward the nuances in the results._

## analysis
* [analysis/munin](https://github.com/Neo23x0/munin)
	_Online hash checker for Virustotal and other services_

* [analysis/malwoverview](https://github.com/alexandreborges/malwoverview)
	_Malwoverview is a first response tool used for threat hunting and offers intel information from Virus Total, Hybrid Analysis, URLHaus, Polyswarm, Malshare, Alien Vault, Malpedia, ThreatCrowd, Valhalla, Malware Bazaar, ThreatFox, Triage and it is able to scan Android devices against VT and HA._

* [analysis/DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI)

* [analysis/hstsparser](https://github.com/thebeanogamer/hstsparser)
	_A tool to parse Firefox and Chrome HSTS databases into forensic artifacts!_

## activedirectory
* [activedirectory/ADFSpoof](https://github.com/fireeye/ADFSpoof)

* [activedirectory/BloodHound](https://github.com/BloodHoundAD/BloodHound)
	_Six Degrees of Domain Admin_

* [activedirectory/SharpHound3](https://github.com/BloodHoundAD/SharpHound3)
	_C# Data Collector for the BloodHound Project, Version 3_

## reconnaisance
* [reconnaisance/fierce](https://github.com/mschwager/fierce)
	_A DNS reconnaissance tool for locating non-contiguous IP space._

* [reconnaisance/gau](https://github.com/lc/gau)
	_Fetch known URLs from AlienVault's Open Threat Exchange, the Wayback Machine, and Common Crawl._

* [reconnaisance/cloud_enum](https://github.com/initstring/cloud_enum)
	_Multi-cloud OSINT tool. Enumerate public resources in AWS, Azure, and Google Cloud._

* [reconnaisance/HostHunter](https://github.com/SpiderLabs/HostHunter)
	_HostHunter a recon tool for discovering hostnames using OSINT techniques._

* [reconnaisance/opensquat](https://github.com/atenreiro/opensquat)
	_Detection of phishing domains and domain squatting. Supports permutations such as homograph attack, typosquatting and bitsquatting._

* [reconnaisance/SubDomainizer](https://github.com/nsonaniya2010/SubDomainizer)
	_A tool to find subdomains and interesting things hidden inside, external Javascript files of page, folder, and Github._

* [reconnaisance/Sudomy](https://github.com/Screetsec/Sudomy)
	_Sudomy is a subdomain enumeration tool to collect subdomains and analyzing domains performing automated reconnaissance (recon) for bug hunting / pentesting_

* [reconnaisance/AttackSurfaceMapper](https://github.com/superhedgy/AttackSurfaceMapper)
	_AttackSurfaceMapper is a tool that aims to automate the reconnaissance process._

* [reconnaisance/fav-up](https://github.com/pielco11/fav-up)
	_IP lookup by favicon using Shodan_

* [reconnaisance/dnsrecon](https://github.com/darkoperator/dnsrecon)
	_DNS Enumeration Script_

* [reconnaisance/recon-ng](https://github.com/lanmaster53/recon-ng)
	_Open Source Intelligence gathering tool aimed at reducing the time spent harvesting information from open sources._

## internet-scale-research
* [internet-scale-research/nuclei](https://github.com/projectdiscovery/nuclei)
	_Fast and customizable vulnerability scanner based on simple YAML based DSL._

* [internet-scale-research/Hunting-New-Registered-Domains](https://github.com/gfek/Hunting-New-Registered-Domains)
	_Hunting Newly Registered Domains_

* [internet-scale-research/phishing_catcher](https://github.com/x0rz/phishing_catcher)
	_Phishing catcher using Certstream_

* [internet-scale-research/EyeWitness](https://github.com/FortyNorthSecurity/EyeWitness)
	_EyeWitness is designed to take screenshots of websites, provide some server header info, and identify default credentials if possible._

## windows
* [windows/SharpNoPSExec](https://github.com/juliourena/SharpNoPSExec)
	_Get file less command execution for lateral movement._

* [windows/Certipy](https://github.com/ly4k/Certipy)
	_Python implementation for Active Directory certificate abuse_

* [windows/ForgeCert](https://github.com/GhostPack/ForgeCert)
	_"Golden" certificates_

* [windows/RDPassSpray](https://github.com/xFreed0m/RDPassSpray)
	_Python3 tool to perform password spraying using RDP_

## microsoft&azure
* [microsoft&azure/Azure-Network-Security](https://github.com/Azure/Azure-Network-Security)
	_Resources for improving Customer Experience with Azure Network Security_

* [microsoft&azure/CRT](https://github.com/CrowdStrike/CRT)
	_Contact: CRT@crowdstrike.com_

* [microsoft&azure/BlobHunter](https://github.com/cyberark/BlobHunter)
	_Find exposed data in Azure with this public blob scanner_

* [microsoft&azure/azucar](https://github.com/nccgroup/azucar)
	_Security auditing tool for Azure environments_

* [microsoft&azure/o365recon](https://github.com/nyxgeek/o365recon)
	_retrieve information via O365 and AzureAD with a valid cred_

* [microsoft&azure/Cloud-Katana](https://github.com/Azure/Cloud-Katana)
	_Unlocking Serverless Computing to Assess Security Controls_

* [microsoft&azure/o365-attack-toolkit](https://github.com/mdsecactivebreach/o365-attack-toolkit)
	_A toolkit to attack Office365_

* [microsoft&azure/MicroBurst](https://github.com/NetSPI/MicroBurst)
	_A collection of scripts for assessing Microsoft Azure security_

* [microsoft&azure/SkyArk](https://github.com/cyberark/SkyArk)
	_SkyArk helps to discover, assess and secure the most privileged entities in Azure and AWS_

* [microsoft&azure/Stormspotter](https://github.com/Azure/Stormspotter)
	_Azure Red Team tool for graphing Azure and Azure Active Directory objects_

* [microsoft&azure/o365creeper](https://github.com/LMGsec/o365creeper)
	_Python script that performs email address validation against Office 365 without submitting login attempts._

* [microsoft&azure/Sparrow](https://github.com/cisagov/Sparrow)
	_Sparrow.ps1 was created by CISA's Cloud Forensics team to help detect possible compromised accounts and applications in the Azure/m365 environment._

* [microsoft&azure/msmailprobe](https://github.com/busterb/msmailprobe)
	_Office 365 and Exchange Enumeration_

* [microsoft&azure/cs-suite](https://github.com/SecurityFTW/cs-suite)
	_Cloud Security Suite - One stop tool for auditing the security posture of AWS/GCP/Azure infrastructure._

* [microsoft&azure/AzurePenTestScope](https://github.com/swiftsolves-msft/AzurePenTestScope)
	_The following scripts and programs are to help security professionals scope their organizations Azure footprint prior to penetration testing._

* [microsoft&azure/Mandiant-Azure-AD-Investigator](https://github.com/fireeye/Mandiant-Azure-AD-Investigator)

## scanners
* [scanners/masscan](https://github.com/robertdavidgraham/masscan)
	_TCP port scanner, spews SYN packets asynchronously, scanning entire Internet in under 5 minutes._

* [scanners/RustScan](https://github.com/RustScan/RustScan)
	_🤖 The Modern Port Scanner 🤖_

* [scanners/Striker](https://github.com/s0md3v/Striker)
	_Striker is an offensive information and vulnerability scanner._

