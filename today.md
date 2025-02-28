# 2025-02-28
## CVE-2025-22964
 DDSN Interactive cm3 Acora CMS version 10.1.1 has an unauthenticated time-based blind SQL Injection vulnerability caused by insufficient input sanitization and validation in the "table" parameter. This flaw allows attackers to inject malicious SQL queries by directly incorporating user-supplied input into database queries without proper escaping or validation. Exploiting this issue enables unauthorized access, manipulation of data, or exposure of sensitive information, posing significant risks to the integrity and confidentiality of the application.

- [https://github.com/padayali-JD/CVE-2025-22964](https://github.com/padayali-JD/CVE-2025-22964) :  
![starts](https://img.shields.io/github/stars/padayali-JD/CVE-2025-22964.svg) 
![forks](https://img.shields.io/github/forks/padayali-JD/CVE-2025-22964.svg) 
2025-02-28T04:33:03Z

## CVE-2024-49138
 Windows Common Log File System Driver Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2024-49138-POC](https://github.com/MrAle98/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2024-49138-POC.svg) 
2025-02-14T22:04:41Z

- [https://github.com/aspire20x/CVE-2024-49138-POC](https://github.com/aspire20x/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/aspire20x/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/aspire20x/CVE-2024-49138-POC.svg) 
2025-02-28T12:41:09Z

- [https://github.com/bananoname/CVE-2024-49138-POC](https://github.com/bananoname/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/bananoname/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/bananoname/CVE-2024-49138-POC.svg) 
2025-01-21T02:06:00Z

## CVE-2024-47051
 This advisory addresses two critical security vulnerabilities present in Mautic versions before 5.2.3. These vulnerabilities could be exploited by authenticated users.  *  Remote Code Execution (RCE) via Asset Upload:A Remote Code Execution vulnerability has been identified in the asset upload functionality. Insufficient enforcement of allowed file extensions allows an attacker to bypass restrictions and upload executable files, such as PHP scripts.  *  Path Traversal File Deletion:A Path Traversal vulnerability exists in the upload validation process. Due to improper handling of path components, an authenticated user can manipulate the file deletion process to delete arbitrary files on the host system.

- [https://github.com/mallo-m/CVE-2024-47051](https://github.com/mallo-m/CVE-2024-47051) :  
![starts](https://img.shields.io/github/stars/mallo-m/CVE-2024-47051.svg) 
![forks](https://img.shields.io/github/forks/mallo-m/CVE-2024-47051.svg) 
2025-02-28T05:36:08Z

## CVE-2024-38819
 Applications serving static resources through the functional web frameworks WebMvc.fn or WebFlux.fn are vulnerable to path traversal attacks. An attacker can craft malicious HTTP requests and obtain any file on the file system that is also accessible to the process in which the Spring application is running.

- [https://github.com/masa42/CVE-2024-38819-POC](https://github.com/masa42/CVE-2024-38819-POC) :  
![starts](https://img.shields.io/github/stars/masa42/CVE-2024-38819-POC.svg) 
![forks](https://img.shields.io/github/forks/masa42/CVE-2024-38819-POC.svg) 
2024-12-14T10:13:45Z

- [https://github.com/GhostS3c/CVE-2024-38819](https://github.com/GhostS3c/CVE-2024-38819) :  
![starts](https://img.shields.io/github/stars/GhostS3c/CVE-2024-38819.svg) 
![forks](https://img.shields.io/github/forks/GhostS3c/CVE-2024-38819.svg) 
2024-12-16T08:49:02Z

- [https://github.com/skrkcb2/cve-2024-38819](https://github.com/skrkcb2/cve-2024-38819) :  
![starts](https://img.shields.io/github/stars/skrkcb2/cve-2024-38819.svg) 
![forks](https://img.shields.io/github/forks/skrkcb2/cve-2024-38819.svg) 
2025-02-28T02:29:44Z

# 2025-02-27
## CVE-2025-21333
 Windows Hyper-V NT Kernel Integration VSP Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2025-21333-POC](https://github.com/MrAle98/CVE-2025-21333-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2025-21333-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2025-21333-POC.svg) 
2025-02-27T14:37:39Z

## CVE-2025-1094
 Improper neutralization of quoting syntax in PostgreSQL libpq functions PQescapeLiteral(), PQescapeIdentifier(), PQescapeString(), and PQescapeStringConn() allows a database input provider to achieve SQL injection in certain usage patterns.  Specifically, SQL injection requires the application to use the function result to construct input to psql, the PostgreSQL interactive terminal.  Similarly, improper neutralization of quoting syntax in PostgreSQL command line utility programs allows a source of command line arguments to achieve SQL injection when client_encoding is BIG5 and server_encoding is one of EUC_TW or MULE_INTERNAL.  Versions before PostgreSQL 17.3, 16.7, 15.11, 14.16, and 13.19 are affected.

- [https://github.com/soltanali0/CVE-2025-1094-Exploit](https://github.com/soltanali0/CVE-2025-1094-Exploit) :  
![starts](https://img.shields.io/github/stars/soltanali0/CVE-2025-1094-Exploit.svg) 
![forks](https://img.shields.io/github/forks/soltanali0/CVE-2025-1094-Exploit.svg) 
2025-02-27T11:12:44Z

## CVE-2025-0364
 BigAntSoft BigAnt Server, up to and including version 5.6.06, is vulnerable to unauthenticated remote code execution via account registration. An unauthenticated remote attacker can create an administrative user through the default exposed SaaS registration mechanism. Once an administrator, the attacker can upload and execute arbitrary PHP code using the "Cloud Storage Addin," leading to unauthenticated code execution.

- [https://github.com/vulncheck-oss/cve-2025-0364](https://github.com/vulncheck-oss/cve-2025-0364) :  
![starts](https://img.shields.io/github/stars/vulncheck-oss/cve-2025-0364.svg) 
![forks](https://img.shields.io/github/forks/vulncheck-oss/cve-2025-0364.svg) 
2025-02-27T18:38:03Z

## CVE-2024-56264
 Unrestricted Upload of File with Dangerous Type vulnerability in Beee ACF City Selector allows Upload a Web Shell to a Web Server.This issue affects ACF City Selector: from n/a through 1.14.0.

- [https://github.com/Nxploited/CVE-2024-56264](https://github.com/Nxploited/CVE-2024-56264) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-56264.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-56264.svg) 
2025-02-24T20:11:57Z

- [https://github.com/dpakmrya/CVE-2024-56264](https://github.com/dpakmrya/CVE-2024-56264) :  
![starts](https://img.shields.io/github/stars/dpakmrya/CVE-2024-56264.svg) 
![forks](https://img.shields.io/github/forks/dpakmrya/CVE-2024-56264.svg) 
2025-02-27T18:06:44Z

## CVE-2024-36401
 GeoServer is an open source server that allows users to share and edit geospatial data. Prior to versions 2.23.6, 2.24.4, and 2.25.2, multiple OGC request parameters allow Remote Code Execution (RCE) by unauthenticated users through specially crafted input against a default GeoServer installation due to unsafely evaluating property names as XPath expressions.The GeoTools library API that GeoServer calls evaluates property/attribute names for feature types in a way that unsafely passes them to the commons-jxpath library which can execute arbitrary code when evaluating XPath expressions. This XPath evaluation is intended to be used only by complex feature types (i.e., Application Schema data stores) but is incorrectly being applied to simple feature types as well which makes this vulnerability apply to **ALL** GeoServer instances. No public PoC is provided but this vulnerability has been confirmed to be exploitable through WFS GetFeature, WFS GetPropertyValue, WMS GetMap, WMS GetFeatureInfo, WMS GetLegendGraphic and WPS Execute requests. This vulnerability can lead to executing arbitrary code.Versions 2.23.6, 2.24.4, and 2.25.2 contain a patch for the issue. A workaround exists by removing the `gt-complex-x.y.jar` file from the GeoServer where `x.y` is the GeoTools version (e.g., `gt-complex-31.1.jar` if running GeoServer 2.25.1). This will remove the vulnerable code from GeoServer but may break some GeoServer functionality or prevent GeoServer from deploying if the gt-complex module is needed.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/Chocapikk/CVE-2024-36401](https://github.com/Chocapikk/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-36401.svg) 
2024-08-02T14:57:26Z

- [https://github.com/whitebear-ch/GeoServerExploit](https://github.com/whitebear-ch/GeoServerExploit) :  
![starts](https://img.shields.io/github/stars/whitebear-ch/GeoServerExploit.svg) 
![forks](https://img.shields.io/github/forks/whitebear-ch/GeoServerExploit.svg) 
2025-01-17T08:36:48Z

- [https://github.com/Mr-xn/CVE-2024-36401](https://github.com/Mr-xn/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/Mr-xn/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/Mr-xn/CVE-2024-36401.svg) 
2024-07-06T01:57:58Z

- [https://github.com/netuseradministrator/CVE-2024-36401](https://github.com/netuseradministrator/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/netuseradministrator/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/netuseradministrator/CVE-2024-36401.svg) 
2024-10-08T03:16:26Z

- [https://github.com/bigb0x/CVE-2024-36401](https://github.com/bigb0x/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/bigb0x/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/bigb0x/CVE-2024-36401.svg) 
2024-07-04T19:18:04Z

- [https://github.com/ahisec/geoserver-](https://github.com/ahisec/geoserver-) :  
![starts](https://img.shields.io/github/stars/ahisec/geoserver-.svg) 
![forks](https://img.shields.io/github/forks/ahisec/geoserver-.svg) 
2024-07-24T15:33:03Z

- [https://github.com/thestar0/CVE-2024-36401-WoodpeckerPlugin](https://github.com/thestar0/CVE-2024-36401-WoodpeckerPlugin) :  
![starts](https://img.shields.io/github/stars/thestar0/CVE-2024-36401-WoodpeckerPlugin.svg) 
![forks](https://img.shields.io/github/forks/thestar0/CVE-2024-36401-WoodpeckerPlugin.svg) 
2024-11-23T08:24:26Z

- [https://github.com/XiaomingX/cve-2024-36401-poc](https://github.com/XiaomingX/cve-2024-36401-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-36401-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-36401-poc.svg) 
2024-11-22T14:22:57Z

- [https://github.com/Niuwoo/CVE-2024-36401](https://github.com/Niuwoo/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/Niuwoo/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/Niuwoo/CVE-2024-36401.svg) 
2024-07-05T03:05:39Z

- [https://github.com/justin-p/geoexplorer](https://github.com/justin-p/geoexplorer) :  
![starts](https://img.shields.io/github/stars/justin-p/geoexplorer.svg) 
![forks](https://img.shields.io/github/forks/justin-p/geoexplorer.svg) 
2024-08-27T16:16:15Z

- [https://github.com/daniellowrie/CVE-2024-36401-PoC](https://github.com/daniellowrie/CVE-2024-36401-PoC) :  
![starts](https://img.shields.io/github/stars/daniellowrie/CVE-2024-36401-PoC.svg) 
![forks](https://img.shields.io/github/forks/daniellowrie/CVE-2024-36401-PoC.svg) 
2024-09-26T13:20:32Z

- [https://github.com/0x0d3ad/CVE-2024-36401](https://github.com/0x0d3ad/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/0x0d3ad/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/0x0d3ad/CVE-2024-36401.svg) 
2024-11-30T19:28:14Z

- [https://github.com/RevoltSecurities/CVE-2024-36401](https://github.com/RevoltSecurities/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/RevoltSecurities/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/RevoltSecurities/CVE-2024-36401.svg) 
2024-07-05T15:33:09Z

- [https://github.com/punitdarji/GeoServer-CVE-2024-36401](https://github.com/punitdarji/GeoServer-CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/punitdarji/GeoServer-CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/punitdarji/GeoServer-CVE-2024-36401.svg) 
2024-09-28T14:58:44Z

- [https://github.com/wingedmicroph/CVE-2024-36401](https://github.com/wingedmicroph/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/wingedmicroph/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/wingedmicroph/CVE-2024-36401.svg) 
2025-02-27T12:58:19Z

- [https://github.com/unlinedvol/CVE-2024-36401](https://github.com/unlinedvol/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/unlinedvol/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/unlinedvol/CVE-2024-36401.svg) 
2025-02-14T16:58:43Z

- [https://github.com/kkhackz0013/CVE-2024-36401](https://github.com/kkhackz0013/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/kkhackz0013/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/kkhackz0013/CVE-2024-36401.svg) 
2024-10-14T17:16:03Z

- [https://github.com/yisas93/CVE-2024-36401-PoC](https://github.com/yisas93/CVE-2024-36401-PoC) :  
![starts](https://img.shields.io/github/stars/yisas93/CVE-2024-36401-PoC.svg) 
![forks](https://img.shields.io/github/forks/yisas93/CVE-2024-36401-PoC.svg) 
2024-08-01T21:30:04Z

- [https://github.com/jakabakos/CVE-2024-36401-GeoServer-RCE](https://github.com/jakabakos/CVE-2024-36401-GeoServer-RCE) :  
![starts](https://img.shields.io/github/stars/jakabakos/CVE-2024-36401-GeoServer-RCE.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/CVE-2024-36401-GeoServer-RCE.svg) 
2024-07-12T07:07:14Z

## CVE-2024-20671
 Microsoft Defender Security Feature Bypass Vulnerability

- [https://github.com/ig-labs/EDR-ALPC-Block-POC](https://github.com/ig-labs/EDR-ALPC-Block-POC) :  
![starts](https://img.shields.io/github/stars/ig-labs/EDR-ALPC-Block-POC.svg) 
![forks](https://img.shields.io/github/forks/ig-labs/EDR-ALPC-Block-POC.svg) 
2025-02-27T11:22:35Z

## CVE-2024-5909
 A problem with a protection mechanism in the Palo Alto Networks Cortex XDR agent on Windows devices allows a low privileged local Windows user to disable the agent. This issue may be leveraged by malware to disable the Cortex XDR agent and then to perform malicious activity.

- [https://github.com/ig-labs/EDR-ALPC-Block-POC](https://github.com/ig-labs/EDR-ALPC-Block-POC) :  
![starts](https://img.shields.io/github/stars/ig-labs/EDR-ALPC-Block-POC.svg) 
![forks](https://img.shields.io/github/forks/ig-labs/EDR-ALPC-Block-POC.svg) 
2025-02-27T11:22:35Z

## CVE-2024-4577
 In PHP versions8.1.* before 8.1.29, 8.2.* before 8.2.20, 8.3.* before 8.3.8, when using Apache and PHP-CGI on Windows, if the system is set up to use certain code pages, Windows may use "Best-Fit" behavior to replace characters in command line given toWin32 API functions. PHP CGI module may misinterpret those characters as PHP options, which may allow a malicious user to pass options to PHP binary being run, and thus reveal the source code of scripts, run arbitrary PHP code on the server, etc.

- [https://github.com/watchtowrlabs/CVE-2024-4577](https://github.com/watchtowrlabs/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/CVE-2024-4577.svg) 
2024-06-22T15:13:52Z

- [https://github.com/xcanwin/CVE-2024-4577-PHP-RCE](https://github.com/xcanwin/CVE-2024-4577-PHP-RCE) :  
![starts](https://img.shields.io/github/stars/xcanwin/CVE-2024-4577-PHP-RCE.svg) 
![forks](https://img.shields.io/github/forks/xcanwin/CVE-2024-4577-PHP-RCE.svg) 
2024-07-21T20:27:03Z

- [https://github.com/TAM-K592/CVE-2024-4577](https://github.com/TAM-K592/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/TAM-K592/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/TAM-K592/CVE-2024-4577.svg) 
2024-06-11T04:46:42Z

- [https://github.com/11whoami99/CVE-2024-4577](https://github.com/11whoami99/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/11whoami99/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/11whoami99/CVE-2024-4577.svg) 
2024-06-09T16:16:30Z

- [https://github.com/Chocapikk/CVE-2024-4577](https://github.com/Chocapikk/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-4577.svg) 
2024-06-09T14:20:36Z

- [https://github.com/ZephrFish/CVE-2024-4577-PHP-RCE](https://github.com/ZephrFish/CVE-2024-4577-PHP-RCE) :  
![starts](https://img.shields.io/github/stars/ZephrFish/CVE-2024-4577-PHP-RCE.svg) 
![forks](https://img.shields.io/github/forks/ZephrFish/CVE-2024-4577-PHP-RCE.svg) 
2024-06-19T16:19:57Z

- [https://github.com/BTtea/CVE-2024-4577-RCE-PoC](https://github.com/BTtea/CVE-2024-4577-RCE-PoC) :  
![starts](https://img.shields.io/github/stars/BTtea/CVE-2024-4577-RCE-PoC.svg) 
![forks](https://img.shields.io/github/forks/BTtea/CVE-2024-4577-RCE-PoC.svg) 
2024-11-20T06:24:59Z

- [https://github.com/gh-ost00/CVE-2024-4577-RCE](https://github.com/gh-ost00/CVE-2024-4577-RCE) :  
![starts](https://img.shields.io/github/stars/gh-ost00/CVE-2024-4577-RCE.svg) 
![forks](https://img.shields.io/github/forks/gh-ost00/CVE-2024-4577-RCE.svg) 
2024-08-20T03:28:28Z

- [https://github.com/huseyinstif/CVE-2024-4577-Nuclei-Template](https://github.com/huseyinstif/CVE-2024-4577-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/huseyinstif/CVE-2024-4577-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/huseyinstif/CVE-2024-4577-Nuclei-Template.svg) 
2024-06-24T11:54:58Z

- [https://github.com/gotr00t0day/CVE-2024-4577](https://github.com/gotr00t0day/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/gotr00t0day/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/gotr00t0day/CVE-2024-4577.svg) 
2024-06-15T02:57:48Z

- [https://github.com/K3ysTr0K3R/CVE-2024-4577-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-4577-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-4577-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-4577-EXPLOIT.svg) 
2024-07-12T02:56:25Z

- [https://github.com/manuelinfosec/CVE-2024-4577](https://github.com/manuelinfosec/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/manuelinfosec/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/manuelinfosec/CVE-2024-4577.svg) 
2024-06-08T05:50:27Z

- [https://github.com/l0n3m4n/CVE-2024-4577-RCE](https://github.com/l0n3m4n/CVE-2024-4577-RCE) :  
![starts](https://img.shields.io/github/stars/l0n3m4n/CVE-2024-4577-RCE.svg) 
![forks](https://img.shields.io/github/forks/l0n3m4n/CVE-2024-4577-RCE.svg) 
2024-07-07T15:32:58Z

- [https://github.com/bibo318/CVE-2024-4577-RCE-ATTACK](https://github.com/bibo318/CVE-2024-4577-RCE-ATTACK) :  
![starts](https://img.shields.io/github/stars/bibo318/CVE-2024-4577-RCE-ATTACK.svg) 
![forks](https://img.shields.io/github/forks/bibo318/CVE-2024-4577-RCE-ATTACK.svg) 
2024-07-11T08:37:00Z

- [https://github.com/waived/CVE-2024-4577-PHP-RCE](https://github.com/waived/CVE-2024-4577-PHP-RCE) :  
![starts](https://img.shields.io/github/stars/waived/CVE-2024-4577-PHP-RCE.svg) 
![forks](https://img.shields.io/github/forks/waived/CVE-2024-4577-PHP-RCE.svg) 
2024-09-06T02:10:35Z

- [https://github.com/0x20c/CVE-2024-4577-nuclei](https://github.com/0x20c/CVE-2024-4577-nuclei) :  
![starts](https://img.shields.io/github/stars/0x20c/CVE-2024-4577-nuclei.svg) 
![forks](https://img.shields.io/github/forks/0x20c/CVE-2024-4577-nuclei.svg) 
2024-06-08T04:14:28Z

- [https://github.com/longhoangth18/CVE-2024-4577](https://github.com/longhoangth18/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/longhoangth18/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/longhoangth18/CVE-2024-4577.svg) 
2024-10-14T09:36:45Z

- [https://github.com/Sh0ckFR/CVE-2024-4577](https://github.com/Sh0ckFR/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Sh0ckFR/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Sh0ckFR/CVE-2024-4577.svg) 
2024-06-13T15:17:15Z

- [https://github.com/JeninSutradhar/CVE-2024-4577-checker](https://github.com/JeninSutradhar/CVE-2024-4577-checker) :  
![starts](https://img.shields.io/github/stars/JeninSutradhar/CVE-2024-4577-checker.svg) 
![forks](https://img.shields.io/github/forks/JeninSutradhar/CVE-2024-4577-checker.svg) 
2024-11-13T14:37:33Z

- [https://github.com/Junp0/CVE-2024-4577](https://github.com/Junp0/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Junp0/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Junp0/CVE-2024-4577.svg) 
2024-06-07T09:40:00Z

- [https://github.com/aaddmin1122345/cve-2024-4577](https://github.com/aaddmin1122345/cve-2024-4577) :  
![starts](https://img.shields.io/github/stars/aaddmin1122345/cve-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/aaddmin1122345/cve-2024-4577.svg) 
2024-09-10T01:27:26Z

- [https://github.com/VictorShem/CVE-2024-4577](https://github.com/VictorShem/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/VictorShem/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/VictorShem/CVE-2024-4577.svg) 
2024-07-31T04:13:16Z

- [https://github.com/zomasec/CVE-2024-4577](https://github.com/zomasec/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/zomasec/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/zomasec/CVE-2024-4577.svg) 
2024-06-09T16:47:11Z

- [https://github.com/Wh02m1/CVE-2024-4577](https://github.com/Wh02m1/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Wh02m1/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Wh02m1/CVE-2024-4577.svg) 
2024-06-07T14:29:09Z

- [https://github.com/phirojshah/CVE-2024-4577](https://github.com/phirojshah/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/phirojshah/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/phirojshah/CVE-2024-4577.svg) 
2024-09-12T19:28:53Z

- [https://github.com/taida957789/CVE-2024-4577](https://github.com/taida957789/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/taida957789/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/taida957789/CVE-2024-4577.svg) 
2024-06-07T11:05:57Z

- [https://github.com/AlperenY-cs/CVE-2024-4577](https://github.com/AlperenY-cs/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/AlperenY-cs/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/AlperenY-cs/CVE-2024-4577.svg) 
2024-06-29T10:39:30Z

- [https://github.com/ggfzx/CVE-2024-4577](https://github.com/ggfzx/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ggfzx/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ggfzx/CVE-2024-4577.svg) 
2024-06-26T07:11:46Z

- [https://github.com/nemu1k5ma/CVE-2024-4577](https://github.com/nemu1k5ma/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/nemu1k5ma/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/nemu1k5ma/CVE-2024-4577.svg) 
2024-06-13T01:15:47Z

- [https://github.com/PhinehasNarh/CVE-2024-4577-LetsDefend-walkthrough](https://github.com/PhinehasNarh/CVE-2024-4577-LetsDefend-walkthrough) :  
![starts](https://img.shields.io/github/stars/PhinehasNarh/CVE-2024-4577-LetsDefend-walkthrough.svg) 
![forks](https://img.shields.io/github/forks/PhinehasNarh/CVE-2024-4577-LetsDefend-walkthrough.svg) 
2024-06-24T11:00:16Z

- [https://github.com/XiangDongCJC/CVE-2024-4577-PHP-CGI-RCE](https://github.com/XiangDongCJC/CVE-2024-4577-PHP-CGI-RCE) :  
![starts](https://img.shields.io/github/stars/XiangDongCJC/CVE-2024-4577-PHP-CGI-RCE.svg) 
![forks](https://img.shields.io/github/forks/XiangDongCJC/CVE-2024-4577-PHP-CGI-RCE.svg) 
2024-06-12T12:50:08Z

- [https://github.com/WanLiChangChengWanLiChang/CVE-2024-4577-RCE-EXP](https://github.com/WanLiChangChengWanLiChang/CVE-2024-4577-RCE-EXP) :  
![starts](https://img.shields.io/github/stars/WanLiChangChengWanLiChang/CVE-2024-4577-RCE-EXP.svg) 
![forks](https://img.shields.io/github/forks/WanLiChangChengWanLiChang/CVE-2024-4577-RCE-EXP.svg) 
2024-06-07T17:26:18Z

- [https://github.com/zjhzjhhh/CVE-2024-4577](https://github.com/zjhzjhhh/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/zjhzjhhh/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/zjhzjhhh/CVE-2024-4577.svg) 
2024-06-07T09:53:32Z

- [https://github.com/ohhhh693/CVE-2024-4577](https://github.com/ohhhh693/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ohhhh693/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ohhhh693/CVE-2024-4577.svg) 
2024-06-07T10:29:59Z

- [https://github.com/olebris/CVE-2024-4577](https://github.com/olebris/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/olebris/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/olebris/CVE-2024-4577.svg) 
2024-06-28T10:20:19Z

- [https://github.com/bughuntar/CVE-2024-4577](https://github.com/bughuntar/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bughuntar/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bughuntar/CVE-2024-4577.svg) 
2024-08-17T02:02:26Z

- [https://github.com/charis3306/CVE-2024-4577](https://github.com/charis3306/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/charis3306/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/charis3306/CVE-2024-4577.svg) 
2024-07-03T15:41:42Z

- [https://github.com/Dejavu666/CVE-2024-4577](https://github.com/Dejavu666/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Dejavu666/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Dejavu666/CVE-2024-4577.svg) 
2025-01-08T11:17:23Z

- [https://github.com/chihyeonwon/php-cgi-cve-2024-4577](https://github.com/chihyeonwon/php-cgi-cve-2024-4577) :  
![starts](https://img.shields.io/github/stars/chihyeonwon/php-cgi-cve-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/chihyeonwon/php-cgi-cve-2024-4577.svg) 
2025-02-14T11:16:39Z

- [https://github.com/sug4r-wr41th/CVE-2024-4577](https://github.com/sug4r-wr41th/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/sug4r-wr41th/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/sug4r-wr41th/CVE-2024-4577.svg) 
2025-02-27T21:20:16Z

- [https://github.com/BitMEXResearch/CVE-2024-4577](https://github.com/BitMEXResearch/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/BitMEXResearch/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/BitMEXResearch/CVE-2024-4577.svg) 
2024-06-07T20:35:06Z

- [https://github.com/Sysc4ll3r/CVE-2024-4577](https://github.com/Sysc4ll3r/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Sysc4ll3r/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Sysc4ll3r/CVE-2024-4577.svg) 
2024-06-07T18:41:17Z

- [https://github.com/a-roshbaik/CVE-2024-4577](https://github.com/a-roshbaik/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/a-roshbaik/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/a-roshbaik/CVE-2024-4577.svg) 
2024-07-24T20:23:03Z

- [https://github.com/Jcccccx/CVE-2024-4577](https://github.com/Jcccccx/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Jcccccx/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Jcccccx/CVE-2024-4577.svg) 
2024-07-31T10:37:56Z

- [https://github.com/princew88/CVE-2024-4577](https://github.com/princew88/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/princew88/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/princew88/CVE-2024-4577.svg) 
2024-06-07T09:48:36Z

- [https://github.com/dbyMelina/CVE-2024-4577](https://github.com/dbyMelina/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/dbyMelina/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/dbyMelina/CVE-2024-4577.svg) 
2024-06-09T13:47:59Z

- [https://github.com/ahmetramazank/CVE-2024-4577](https://github.com/ahmetramazank/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ahmetramazank/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ahmetramazank/CVE-2024-4577.svg) 
2024-11-03T16:17:49Z

- [https://github.com/hexedbyte/cve-2024-4577](https://github.com/hexedbyte/cve-2024-4577) :  
![starts](https://img.shields.io/github/stars/hexedbyte/cve-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/hexedbyte/cve-2024-4577.svg) 
2024-06-13T12:43:03Z

- [https://github.com/bl4cksku11/CVE-2024-4577](https://github.com/bl4cksku11/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bl4cksku11/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bl4cksku11/CVE-2024-4577.svg) 
2024-06-11T15:29:21Z

- [https://github.com/Didarul342/CVE-2024-4577](https://github.com/Didarul342/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Didarul342/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Didarul342/CVE-2024-4577.svg) 
2025-02-14T19:44:03Z

- [https://github.com/d3ck4/Shodan-CVE-2024-4577](https://github.com/d3ck4/Shodan-CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/d3ck4/Shodan-CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/d3ck4/Shodan-CVE-2024-4577.svg) 
2024-06-12T07:02:35Z

- [https://github.com/Entropt/CVE-2024-4577_Analysis](https://github.com/Entropt/CVE-2024-4577_Analysis) :  
![starts](https://img.shields.io/github/stars/Entropt/CVE-2024-4577_Analysis.svg) 
![forks](https://img.shields.io/github/forks/Entropt/CVE-2024-4577_Analysis.svg) 
2024-08-14T20:03:28Z

- [https://github.com/a-roshbaik/CVE-2024-4577-PHP-RCE](https://github.com/a-roshbaik/CVE-2024-4577-PHP-RCE) :  
![starts](https://img.shields.io/github/stars/a-roshbaik/CVE-2024-4577-PHP-RCE.svg) 
![forks](https://img.shields.io/github/forks/a-roshbaik/CVE-2024-4577-PHP-RCE.svg) 
2024-07-24T20:29:25Z

- [https://github.com/ywChen-NTUST/PHP-CGI-RCE-Scanner](https://github.com/ywChen-NTUST/PHP-CGI-RCE-Scanner) :  
![starts](https://img.shields.io/github/stars/ywChen-NTUST/PHP-CGI-RCE-Scanner.svg) 
![forks](https://img.shields.io/github/forks/ywChen-NTUST/PHP-CGI-RCE-Scanner.svg) 
2024-09-11T14:17:25Z

- [https://github.com/jakabakos/CVE-2024-4577-PHP-CGI-argument-injection-RCE](https://github.com/jakabakos/CVE-2024-4577-PHP-CGI-argument-injection-RCE) :  
![starts](https://img.shields.io/github/stars/jakabakos/CVE-2024-4577-PHP-CGI-argument-injection-RCE.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/CVE-2024-4577-PHP-CGI-argument-injection-RCE.svg) 
2024-06-18T13:54:15Z

- [https://github.com/AhmedMansour93/Event-ID-268-Rule-Name-SOC292-Possible-PHP-Injection-Detected-CVE-2024-4577-](https://github.com/AhmedMansour93/Event-ID-268-Rule-Name-SOC292-Possible-PHP-Injection-Detected-CVE-2024-4577-) :  
![starts](https://img.shields.io/github/stars/AhmedMansour93/Event-ID-268-Rule-Name-SOC292-Possible-PHP-Injection-Detected-CVE-2024-4577-.svg) 
![forks](https://img.shields.io/github/forks/AhmedMansour93/Event-ID-268-Rule-Name-SOC292-Possible-PHP-Injection-Detected-CVE-2024-4577-.svg) 
2024-09-12T19:13:37Z

# 2025-02-26
## CVE-2025-26264
 GeoVision GV-ASWeb with the version 6.1.2.0 or less, contains a Remote Code Execution (RCE) vulnerability within its Notification Settings feature. An authenticated attacker with "System Settings" privileges in ASWeb can exploit this flaw to execute arbitrary commands on the server, leading to a full system compromise.

- [https://github.com/DRAGOWN/CVE-2025-26264](https://github.com/DRAGOWN/CVE-2025-26264) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2025-26264.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2025-26264.svg) 
2025-02-26T18:38:04Z

## CVE-2025-1302
 Versions of the package jsonpath-plus before 10.3.0 are vulnerable to Remote Code Execution (RCE) due to improper input sanitization. An attacker can execute aribitrary code on the system by exploiting the unsafe default usage of eval='safe' mode.**Note:**This is caused by an incomplete fix for [CVE-2024-21534](https://security.snyk.io/vuln/SNYK-JS-JSONPATHPLUS-7945884).

- [https://github.com/EQSTLab/CVE-2025-1302](https://github.com/EQSTLab/CVE-2025-1302) :  
![starts](https://img.shields.io/github/stars/EQSTLab/CVE-2025-1302.svg) 
![forks](https://img.shields.io/github/forks/EQSTLab/CVE-2025-1302.svg) 
2025-02-26T05:00:18Z

## CVE-2024-56903
 A Cross-Site Request Forgery (CSRF) in Geovision GV-ASWeb with the version 6.1.1.0 or less allows attackers to execute arbitrary operations via supplying a crafted HTTP request.

- [https://github.com/DRAGOWN/CVE-2024-56903](https://github.com/DRAGOWN/CVE-2024-56903) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56903.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56903.svg) 
2025-02-26T17:33:49Z

## CVE-2024-56901
 A Cross-Site Request Forgery (CSRF) in the Account Management component of Geovision GV-ASWeb version 6.1.1.0 or less allows attackers to arbitrarily create Admin accounts via a crafted GET request method.

- [https://github.com/DRAGOWN/CVE-2024-56901](https://github.com/DRAGOWN/CVE-2024-56901) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56901.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56901.svg) 
2025-02-02T22:26:39Z

- [https://github.com/DRAGOWN/CVE-2024-56903](https://github.com/DRAGOWN/CVE-2024-56903) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56903.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56903.svg) 
2025-02-26T17:33:49Z

## CVE-2024-56898
 Incorrect access control in Geovision GV-ASWeb version 6.1.0.0 or less allows unauthorized attackers with low-level privileges to manage and create new user accounts via supplying a crafted HTTP request.

- [https://github.com/DRAGOWN/CVE-2024-56898](https://github.com/DRAGOWN/CVE-2024-56898) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56898.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56898.svg) 
2025-02-04T16:50:13Z

- [https://github.com/DRAGOWN/CVE-2025-26263](https://github.com/DRAGOWN/CVE-2025-26263) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2025-26263.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2025-26263.svg) 
2025-02-26T18:03:50Z

## CVE-2024-24919
 Potentially allowing an attacker to read certain information on Check Point Security Gateways once connected to the internet and enabled with remote Access VPN or Mobile Access Software Blades. A Security fix that mitigates this vulnerability is available.

- [https://github.com/seed1337/CVE-2024-24919-POC](https://github.com/seed1337/CVE-2024-24919-POC) :  
![starts](https://img.shields.io/github/stars/seed1337/CVE-2024-24919-POC.svg) 
![forks](https://img.shields.io/github/forks/seed1337/CVE-2024-24919-POC.svg) 
2024-05-31T22:55:07Z

- [https://github.com/ifconfig-me/CVE-2024-24919-Bulk-Scanner](https://github.com/ifconfig-me/CVE-2024-24919-Bulk-Scanner) :  
![starts](https://img.shields.io/github/stars/ifconfig-me/CVE-2024-24919-Bulk-Scanner.svg) 
![forks](https://img.shields.io/github/forks/ifconfig-me/CVE-2024-24919-Bulk-Scanner.svg) 
2024-06-02T06:36:57Z

- [https://github.com/RevoltSecurities/CVE-2024-24919](https://github.com/RevoltSecurities/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/RevoltSecurities/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/RevoltSecurities/CVE-2024-24919.svg) 
2024-06-05T11:38:12Z

- [https://github.com/GoatSecurity/CVE-2024-24919](https://github.com/GoatSecurity/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/GoatSecurity/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/GoatSecurity/CVE-2024-24919.svg) 
2024-05-31T15:50:57Z

- [https://github.com/un9nplayer/CVE-2024-24919](https://github.com/un9nplayer/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/un9nplayer/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/un9nplayer/CVE-2024-24919.svg) 
2024-06-05T16:13:51Z

- [https://github.com/LucasKatashi/CVE-2024-24919](https://github.com/LucasKatashi/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/LucasKatashi/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/LucasKatashi/CVE-2024-24919.svg) 
2024-05-30T17:08:11Z

- [https://github.com/verylazytech/CVE-2024-24919](https://github.com/verylazytech/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-24919.svg) 
2024-11-26T14:45:44Z

- [https://github.com/geniuszly/CVE-2024-24919](https://github.com/geniuszly/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/geniuszly/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/geniuszly/CVE-2024-24919.svg) 
2024-09-29T08:24:06Z

- [https://github.com/0nin0hanz0/CVE-2024-24919-PoC](https://github.com/0nin0hanz0/CVE-2024-24919-PoC) :  
![starts](https://img.shields.io/github/stars/0nin0hanz0/CVE-2024-24919-PoC.svg) 
![forks](https://img.shields.io/github/forks/0nin0hanz0/CVE-2024-24919-PoC.svg) 
2024-07-27T12:46:44Z

- [https://github.com/c3rrberu5/CVE-2024-24919](https://github.com/c3rrberu5/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/c3rrberu5/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/c3rrberu5/CVE-2024-24919.svg) 
2024-05-30T07:58:10Z

- [https://github.com/GuayoyoCyber/CVE-2024-24919](https://github.com/GuayoyoCyber/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/GuayoyoCyber/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/GuayoyoCyber/CVE-2024-24919.svg) 
2024-06-04T01:38:40Z

- [https://github.com/emanueldosreis/CVE-2024-24919](https://github.com/emanueldosreis/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/emanueldosreis/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/emanueldosreis/CVE-2024-24919.svg) 
2024-05-30T18:56:32Z

- [https://github.com/smackerdodi/CVE-2024-24919-nuclei-templater](https://github.com/smackerdodi/CVE-2024-24919-nuclei-templater) :  
![starts](https://img.shields.io/github/stars/smackerdodi/CVE-2024-24919-nuclei-templater.svg) 
![forks](https://img.shields.io/github/forks/smackerdodi/CVE-2024-24919-nuclei-templater.svg) 
2024-05-31T12:35:30Z

- [https://github.com/Bytenull00/CVE-2024-24919](https://github.com/Bytenull00/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/Bytenull00/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Bytenull00/CVE-2024-24919.svg) 
2024-05-30T21:49:43Z

- [https://github.com/zam89/CVE-2024-24919](https://github.com/zam89/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/zam89/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/zam89/CVE-2024-24919.svg) 
2024-05-31T08:16:57Z

- [https://github.com/GlobalsecureAcademy/CVE-2024-24919](https://github.com/GlobalsecureAcademy/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/GlobalsecureAcademy/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/GlobalsecureAcademy/CVE-2024-24919.svg) 
2024-05-31T17:31:32Z

- [https://github.com/Rug4lo/CVE-2024-24919-Exploit](https://github.com/Rug4lo/CVE-2024-24919-Exploit) :  
![starts](https://img.shields.io/github/stars/Rug4lo/CVE-2024-24919-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Rug4lo/CVE-2024-24919-Exploit.svg) 
2024-06-03T14:09:22Z

- [https://github.com/protonnegativo/CVE-2024-24919](https://github.com/protonnegativo/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/protonnegativo/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/protonnegativo/CVE-2024-24919.svg) 
2024-06-10T01:40:02Z

- [https://github.com/bigb0x/CVE-2024-24919-Sniper](https://github.com/bigb0x/CVE-2024-24919-Sniper) :  
![starts](https://img.shields.io/github/stars/bigb0x/CVE-2024-24919-Sniper.svg) 
![forks](https://img.shields.io/github/forks/bigb0x/CVE-2024-24919-Sniper.svg) 
2024-06-02T23:00:22Z

- [https://github.com/r4p3c4/CVE-2024-24919-Exploit-PoC-Checkpoint-Firewall-VPN](https://github.com/r4p3c4/CVE-2024-24919-Exploit-PoC-Checkpoint-Firewall-VPN) :  
![starts](https://img.shields.io/github/stars/r4p3c4/CVE-2024-24919-Exploit-PoC-Checkpoint-Firewall-VPN.svg) 
![forks](https://img.shields.io/github/forks/r4p3c4/CVE-2024-24919-Exploit-PoC-Checkpoint-Firewall-VPN.svg) 
2024-06-01T12:20:54Z

- [https://github.com/NingXin2002/Check-Point_poc](https://github.com/NingXin2002/Check-Point_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/Check-Point_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/Check-Point_poc.svg) 
2024-12-21T02:43:40Z

- [https://github.com/fernandobortotti/CVE-2024-24919](https://github.com/fernandobortotti/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/fernandobortotti/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/fernandobortotti/CVE-2024-24919.svg) 
2024-06-01T03:44:23Z

- [https://github.com/skyrowalker/CVE-2024-24919](https://github.com/skyrowalker/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/skyrowalker/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/skyrowalker/CVE-2024-24919.svg) 
2024-10-10T13:34:31Z

- [https://github.com/SalehLardhi/CVE-2024-24919](https://github.com/SalehLardhi/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/SalehLardhi/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/SalehLardhi/CVE-2024-24919.svg) 
2024-06-11T03:37:04Z

- [https://github.com/Cappricio-Securities/CVE-2024-24919](https://github.com/Cappricio-Securities/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/Cappricio-Securities/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Cappricio-Securities/CVE-2024-24919.svg) 
2024-06-24T10:02:59Z

- [https://github.com/0xans/CVE-2024-24919](https://github.com/0xans/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/0xans/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/0xans/CVE-2024-24919.svg) 
2024-06-19T16:59:42Z

- [https://github.com/nexblade12/CVE-2024-24919](https://github.com/nexblade12/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/nexblade12/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/nexblade12/CVE-2024-24919.svg) 
2024-05-31T17:51:05Z

- [https://github.com/0xYumeko/CVE-2024-24919](https://github.com/0xYumeko/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/0xYumeko/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/0xYumeko/CVE-2024-24919.svg) 
2024-06-01T12:22:11Z

- [https://github.com/mr-kasim-mehar/CVE-2024-24919-Exploit](https://github.com/mr-kasim-mehar/CVE-2024-24919-Exploit) :  
![starts](https://img.shields.io/github/stars/mr-kasim-mehar/CVE-2024-24919-Exploit.svg) 
![forks](https://img.shields.io/github/forks/mr-kasim-mehar/CVE-2024-24919-Exploit.svg) 
2024-06-02T08:24:32Z

- [https://github.com/starlox0/CVE-2024-24919-POC](https://github.com/starlox0/CVE-2024-24919-POC) :  
![starts](https://img.shields.io/github/stars/starlox0/CVE-2024-24919-POC.svg) 
![forks](https://img.shields.io/github/forks/starlox0/CVE-2024-24919-POC.svg) 
2024-06-06T16:12:42Z

- [https://github.com/birdlex/cve-2024-24919-checker](https://github.com/birdlex/cve-2024-24919-checker) :  
![starts](https://img.shields.io/github/stars/birdlex/cve-2024-24919-checker.svg) 
![forks](https://img.shields.io/github/forks/birdlex/cve-2024-24919-checker.svg) 
2024-06-04T06:54:55Z

- [https://github.com/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check](https://github.com/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check) :  
![starts](https://img.shields.io/github/stars/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check.svg) 
![forks](https://img.shields.io/github/forks/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check.svg) 
2024-06-01T11:56:27Z

- [https://github.com/am-eid/CVE-2024-24919](https://github.com/am-eid/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/am-eid/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/am-eid/CVE-2024-24919.svg) 
2024-05-31T00:06:39Z

- [https://github.com/P3wc0/CVE-2024-24919](https://github.com/P3wc0/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/P3wc0/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/P3wc0/CVE-2024-24919.svg) 
2024-05-31T01:39:02Z

- [https://github.com/hendprw/CVE-2024-24919](https://github.com/hendprw/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/hendprw/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/hendprw/CVE-2024-24919.svg) 
2024-05-30T15:42:23Z

- [https://github.com/nicolvsrlr27/CVE-2024-24919](https://github.com/nicolvsrlr27/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/nicolvsrlr27/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/nicolvsrlr27/CVE-2024-24919.svg) 
2024-06-01T03:05:35Z

- [https://github.com/satriarizka/CVE-2024-24919](https://github.com/satriarizka/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/satriarizka/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/satriarizka/CVE-2024-24919.svg) 
2024-05-31T08:37:35Z

- [https://github.com/Jutrm/cve-2024-24919](https://github.com/Jutrm/cve-2024-24919) :  
![starts](https://img.shields.io/github/stars/Jutrm/cve-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Jutrm/cve-2024-24919.svg) 
2024-07-26T15:23:03Z

- [https://github.com/Vulnpire/CVE-2024-24919](https://github.com/Vulnpire/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/Vulnpire/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Vulnpire/CVE-2024-24919.svg) 
2024-05-31T11:36:26Z

- [https://github.com/Tim-Hoekstra/CVE-2024-24919](https://github.com/Tim-Hoekstra/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/Tim-Hoekstra/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Tim-Hoekstra/CVE-2024-24919.svg) 
2024-06-04T04:58:56Z

- [https://github.com/H3KEY/CVE-2024-24919](https://github.com/H3KEY/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/H3KEY/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/H3KEY/CVE-2024-24919.svg) 
2024-07-22T06:07:45Z

- [https://github.com/0xkalawy/CVE-2024-24919](https://github.com/0xkalawy/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/0xkalawy/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/0xkalawy/CVE-2024-24919.svg) 
2024-05-31T23:39:52Z

- [https://github.com/ShadowByte1/CVE-2024-24919](https://github.com/ShadowByte1/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/ShadowByte1/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/ShadowByte1/CVE-2024-24919.svg) 
2024-07-14T23:33:00Z

- [https://github.com/yagyuufellinluvv/CVE-2024-24919](https://github.com/yagyuufellinluvv/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/yagyuufellinluvv/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/yagyuufellinluvv/CVE-2024-24919.svg) 
2024-06-01T00:09:51Z

- [https://github.com/YN1337/CVE-2024-24919](https://github.com/YN1337/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/YN1337/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/YN1337/CVE-2024-24919.svg) 
2024-06-01T10:07:52Z

- [https://github.com/satchhacker/cve-2024-24919](https://github.com/satchhacker/cve-2024-24919) :  
![starts](https://img.shields.io/github/stars/satchhacker/cve-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/satchhacker/cve-2024-24919.svg) 
2024-06-08T10:26:34Z

- [https://github.com/gurudattch/CVE-2024-24919](https://github.com/gurudattch/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/gurudattch/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/gurudattch/CVE-2024-24919.svg) 
2024-06-01T05:56:54Z

- [https://github.com/spider00009/CVE-2024-24919-POC](https://github.com/spider00009/CVE-2024-24919-POC) :  
![starts](https://img.shields.io/github/stars/spider00009/CVE-2024-24919-POC.svg) 
![forks](https://img.shields.io/github/forks/spider00009/CVE-2024-24919-POC.svg) 
2025-02-26T06:15:27Z

- [https://github.com/J4F9S5D2Q7/CVE-2024-24919-CHECKPOINT](https://github.com/J4F9S5D2Q7/CVE-2024-24919-CHECKPOINT) :  
![starts](https://img.shields.io/github/stars/J4F9S5D2Q7/CVE-2024-24919-CHECKPOINT.svg) 
![forks](https://img.shields.io/github/forks/J4F9S5D2Q7/CVE-2024-24919-CHECKPOINT.svg) 
2024-06-02T07:19:16Z

- [https://github.com/sar-3mar/CVE-2024-24919_POC](https://github.com/sar-3mar/CVE-2024-24919_POC) :  
![starts](https://img.shields.io/github/stars/sar-3mar/CVE-2024-24919_POC.svg) 
![forks](https://img.shields.io/github/forks/sar-3mar/CVE-2024-24919_POC.svg) 
2024-10-28T22:08:28Z

- [https://github.com/nullcult/CVE-2024-24919-Exploit](https://github.com/nullcult/CVE-2024-24919-Exploit) :  
![starts](https://img.shields.io/github/stars/nullcult/CVE-2024-24919-Exploit.svg) 
![forks](https://img.shields.io/github/forks/nullcult/CVE-2024-24919-Exploit.svg) 
2024-06-07T12:25:34Z

- [https://github.com/B1naryo/CVE-2024-24919-POC](https://github.com/B1naryo/CVE-2024-24919-POC) :  
![starts](https://img.shields.io/github/stars/B1naryo/CVE-2024-24919-POC.svg) 
![forks](https://img.shields.io/github/forks/B1naryo/CVE-2024-24919-POC.svg) 
2024-06-02T13:18:24Z

- [https://github.com/Expl0itD0g/CVE-2024-24919---Poc](https://github.com/Expl0itD0g/CVE-2024-24919---Poc) :  
![starts](https://img.shields.io/github/stars/Expl0itD0g/CVE-2024-24919---Poc.svg) 
![forks](https://img.shields.io/github/forks/Expl0itD0g/CVE-2024-24919---Poc.svg) 
2024-06-02T14:00:44Z

- [https://github.com/funixone/CVE-2024-24919---Exploit-Script](https://github.com/funixone/CVE-2024-24919---Exploit-Script) :  
![starts](https://img.shields.io/github/stars/funixone/CVE-2024-24919---Exploit-Script.svg) 
![forks](https://img.shields.io/github/forks/funixone/CVE-2024-24919---Exploit-Script.svg) 
2025-02-21T16:45:37Z

- [https://github.com/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919](https://github.com/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919.svg) 
2024-08-29T14:37:31Z

- [https://github.com/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN](https://github.com/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN) :  
![starts](https://img.shields.io/github/stars/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN.svg) 
![forks](https://img.shields.io/github/forks/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN.svg) 
2024-06-02T12:39:57Z

- [https://github.com/hashdr1ft/SOC_287](https://github.com/hashdr1ft/SOC_287) :  
![starts](https://img.shields.io/github/stars/hashdr1ft/SOC_287.svg) 
![forks](https://img.shields.io/github/forks/hashdr1ft/SOC_287.svg) 
2025-02-05T11:09:37Z

- [https://github.com/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-](https://github.com/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-) :  
![starts](https://img.shields.io/github/stars/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-.svg) 
![forks](https://img.shields.io/github/forks/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-.svg) 
2024-08-31T16:58:20Z

# 2025-02-25
## CVE-2025-25279
 Mattermost versions 10.4.x = 10.4.1, 9.11.x = 9.11.7, 10.3.x = 10.3.2, 10.2.x = 10.2.2 fail to properly validate board blocks when importing boards which allows an attacker could read any arbitrary file on the system via importing and exporting a specially crafted import archive in Boards.

- [https://github.com/numanturle/CVE-2025-25279](https://github.com/numanturle/CVE-2025-25279) :  
![starts](https://img.shields.io/github/stars/numanturle/CVE-2025-25279.svg) 
![forks](https://img.shields.io/github/forks/numanturle/CVE-2025-25279.svg) 
2025-02-25T09:18:34Z

## CVE-2025-24893
 XWiki Platform is a generic wiki platform offering runtime services for applications built on top of it. Any guest can perform arbitrary remote code execution through a request to `SolrSearch`. This impacts the confidentiality, integrity and availability of the whole XWiki installation. To reproduce on an instance, without being logged in, go to `host/xwiki/bin/get/Main/SolrSearch?media=rss&text=%7D%7D%7D%7B%7Basync%20async%3Dfalse%7D%7D%7B%7Bgroovy%7D%7Dprintln%28"Hello%20from"%20%2B%20"%20search%20text%3A"%20%2B%20%2823%20%2B%2019%29%29%7B%7B%2Fgroovy%7D%7D%7B%7B%2Fasync%7D%7D%20`. If there is an output, and the title of the RSS feed contains `Hello from search text:42`, then the instance is vulnerable. This vulnerability has been patched in XWiki 15.10.11, 16.4.1 and 16.5.0RC1. Users are advised to upgrade. Users unable to upgrade may edit `Main.SolrSearchMacros` in `SolrSearchMacros.xml` on line 955 to match the `rawResponse` macro in `macros.vm#L2824` with a content type of `application/xml`, instead of simply outputting the content of the feed.

- [https://github.com/iSee857/CVE-2025-24893-PoC](https://github.com/iSee857/CVE-2025-24893-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2025-24893-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2025-24893-PoC.svg) 
2025-02-25T07:18:51Z

## CVE-2025-24104
 This issue was addressed with improved handling of symlinks. This issue is fixed in iPadOS 17.7.4, iOS 18.3 and iPadOS 18.3. Restoring a maliciously crafted backup file may lead to modification of protected system files.

- [https://github.com/ifpdz/CVE-2025-24104](https://github.com/ifpdz/CVE-2025-24104) :  
![starts](https://img.shields.io/github/stars/ifpdz/CVE-2025-24104.svg) 
![forks](https://img.shields.io/github/forks/ifpdz/CVE-2025-24104.svg) 
2025-02-25T11:03:56Z

## CVE-2025-23942
 Unrestricted Upload of File with Dangerous Type vulnerability in NgocCode WP Load Gallery allows Upload a Web Shell to a Web Server. This issue affects WP Load Gallery: from n/a through 2.1.6.

- [https://github.com/Nxploited/CVE-2025-23942-poc](https://github.com/Nxploited/CVE-2025-23942-poc) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2025-23942-poc.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2025-23942-poc.svg) 
2025-02-25T08:32:49Z

## CVE-2025-21420
 Windows Disk Cleanup Tool Elevation of Privilege Vulnerability

- [https://github.com/Network-Sec/CVE-2025-21420-PoC](https://github.com/Network-Sec/CVE-2025-21420-PoC) :  
![starts](https://img.shields.io/github/stars/Network-Sec/CVE-2025-21420-PoC.svg) 
![forks](https://img.shields.io/github/forks/Network-Sec/CVE-2025-21420-PoC.svg) 
2025-02-25T18:39:01Z

- [https://github.com/toxy4ny/edge-maradeur](https://github.com/toxy4ny/edge-maradeur) :  
![starts](https://img.shields.io/github/stars/toxy4ny/edge-maradeur.svg) 
![forks](https://img.shields.io/github/forks/toxy4ny/edge-maradeur.svg) 
2025-02-20T15:20:50Z

## CVE-2025-0282
 A stack-based buffer overflow in Ivanti Connect Secure before version 22.7R2.5, Ivanti Policy Secure before version 22.7R1.2, and Ivanti Neurons for ZTA gateways before version 22.7R2.3 allows a remote unauthenticated attacker to achieve remote code execution.

- [https://github.com/absholi7ly/CVE-2025-0282-Ivanti-exploit](https://github.com/absholi7ly/CVE-2025-0282-Ivanti-exploit) :  
![starts](https://img.shields.io/github/stars/absholi7ly/CVE-2025-0282-Ivanti-exploit.svg) 
![forks](https://img.shields.io/github/forks/absholi7ly/CVE-2025-0282-Ivanti-exploit.svg) 
2025-01-11T23:54:06Z

- [https://github.com/sfewer-r7/CVE-2025-0282](https://github.com/sfewer-r7/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/sfewer-r7/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/sfewer-r7/CVE-2025-0282.svg) 
2025-01-16T20:09:52Z

- [https://github.com/watchtowrlabs/CVE-2025-0282](https://github.com/watchtowrlabs/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/CVE-2025-0282.svg) 
2025-01-18T16:59:07Z

- [https://github.com/securexploit1/CVE-2025-0282](https://github.com/securexploit1/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/securexploit1/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/securexploit1/CVE-2025-0282.svg) 
2025-01-09T17:36:14Z

- [https://github.com/AnonStorks/CVE-2025-0282-Full-version](https://github.com/AnonStorks/CVE-2025-0282-Full-version) :  
![starts](https://img.shields.io/github/stars/AnonStorks/CVE-2025-0282-Full-version.svg) 
![forks](https://img.shields.io/github/forks/AnonStorks/CVE-2025-0282-Full-version.svg) 
2025-01-12T12:15:44Z

- [https://github.com/AdaniKamal/CVE-2025-0282](https://github.com/AdaniKamal/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/AdaniKamal/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/AdaniKamal/CVE-2025-0282.svg) 
2025-01-28T08:46:44Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

- [https://github.com/44xo/CVE-2025-0282](https://github.com/44xo/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/44xo/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/44xo/CVE-2025-0282.svg) 
2025-02-25T16:45:32Z

- [https://github.com/chiefchainer/CVE-2025-0282](https://github.com/chiefchainer/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/chiefchainer/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/chiefchainer/CVE-2025-0282.svg) 
2025-01-22T08:25:22Z

## CVE-2024-54772
 An issue was discovered in the Winbox service of MikroTik RouterOS long-term release v6.43.13 through v6.49.13 and stable v6.43 through v7.17.2. A patch is available in the stable release v6.49.18. A discrepancy in response size between connection attempts made with a valid username and those with an invalid username allows attackers to enumerate for valid accounts.

- [https://github.com/deauther890/CVE-2024-54772](https://github.com/deauther890/CVE-2024-54772) :  
![starts](https://img.shields.io/github/stars/deauther890/CVE-2024-54772.svg) 
![forks](https://img.shields.io/github/forks/deauther890/CVE-2024-54772.svg) 
2025-02-25T12:43:32Z

## CVE-2024-23346
 Pymatgen (Python Materials Genomics) is an open-source Python library for materials analysis. A critical security vulnerability exists in the `JonesFaithfulTransformation.from_transformation_str()` method within the `pymatgen` library prior to version 2024.2.20. This method insecurely utilizes `eval()` for processing input, enabling execution of arbitrary code when parsing untrusted input. Version 2024.2.20 fixes this issue.

- [https://github.com/9carlo6/CVE-2024-23346](https://github.com/9carlo6/CVE-2024-23346) :  
![starts](https://img.shields.io/github/stars/9carlo6/CVE-2024-23346.svg) 
![forks](https://img.shields.io/github/forks/9carlo6/CVE-2024-23346.svg) 
2024-11-05T14:32:57Z

- [https://github.com/Sanity-Archive/CVE-2024-23346](https://github.com/Sanity-Archive/CVE-2024-23346) :  
![starts](https://img.shields.io/github/stars/Sanity-Archive/CVE-2024-23346.svg) 
![forks](https://img.shields.io/github/forks/Sanity-Archive/CVE-2024-23346.svg) 
2025-02-20T12:23:44Z

- [https://github.com/MAWK0235/CVE-2024-23346](https://github.com/MAWK0235/CVE-2024-23346) :  
![starts](https://img.shields.io/github/stars/MAWK0235/CVE-2024-23346.svg) 
![forks](https://img.shields.io/github/forks/MAWK0235/CVE-2024-23346.svg) 
2024-12-09T22:52:04Z

- [https://github.com/szyth/CVE-2024-23346-rust-exploit](https://github.com/szyth/CVE-2024-23346-rust-exploit) :  
![starts](https://img.shields.io/github/stars/szyth/CVE-2024-23346-rust-exploit.svg) 
![forks](https://img.shields.io/github/forks/szyth/CVE-2024-23346-rust-exploit.svg) 
2025-02-25T16:25:48Z

## CVE-2024-6387
 A security regression (CVE-2006-5051) was discovered in OpenSSH's server (sshd). There is a race condition which can lead sshd to handle some signals in an unsafe manner. An unauthenticated, remote attacker may be able to trigger it by failing to authenticate within a set time period.

- [https://github.com/zgzhang/cve-2024-6387-poc](https://github.com/zgzhang/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/zgzhang/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/zgzhang/cve-2024-6387-poc.svg) 
2024-07-01T10:54:02Z

- [https://github.com/xaitax/CVE-2024-6387_Check](https://github.com/xaitax/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/xaitax/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/xaitax/CVE-2024-6387_Check.svg) 
2025-02-25T09:29:46Z

- [https://github.com/acrono/cve-2024-6387-poc](https://github.com/acrono/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/acrono/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/acrono/cve-2024-6387-poc.svg) 
2024-07-01T12:25:01Z

- [https://github.com/lflare/cve-2024-6387-poc](https://github.com/lflare/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/lflare/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/lflare/cve-2024-6387-poc.svg) 
2024-07-25T04:23:11Z

- [https://github.com/filipi86/CVE-2024-6387-Vulnerability-Checker](https://github.com/filipi86/CVE-2024-6387-Vulnerability-Checker) :  
![starts](https://img.shields.io/github/stars/filipi86/CVE-2024-6387-Vulnerability-Checker.svg) 
![forks](https://img.shields.io/github/forks/filipi86/CVE-2024-6387-Vulnerability-Checker.svg) 
2024-07-10T15:24:08Z

- [https://github.com/Karmakstylez/CVE-2024-6387](https://github.com/Karmakstylez/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/Karmakstylez/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/Karmakstylez/CVE-2024-6387.svg) 
2024-08-22T08:50:25Z

- [https://github.com/l0n3m4n/CVE-2024-6387](https://github.com/l0n3m4n/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/l0n3m4n/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/l0n3m4n/CVE-2024-6387.svg) 
2024-07-05T15:19:28Z

- [https://github.com/theaog/spirit](https://github.com/theaog/spirit) :  
![starts](https://img.shields.io/github/stars/theaog/spirit.svg) 
![forks](https://img.shields.io/github/forks/theaog/spirit.svg) 
2025-01-14T23:16:46Z

- [https://github.com/xonoxitron/regreSSHion](https://github.com/xonoxitron/regreSSHion) :  
![starts](https://img.shields.io/github/stars/xonoxitron/regreSSHion.svg) 
![forks](https://img.shields.io/github/forks/xonoxitron/regreSSHion.svg) 
2024-07-02T15:16:04Z

- [https://github.com/d0rb/CVE-2024-6387](https://github.com/d0rb/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/d0rb/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/d0rb/CVE-2024-6387.svg) 
2024-07-04T20:04:30Z

- [https://github.com/bigb0x/CVE-2024-6387](https://github.com/bigb0x/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/bigb0x/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/bigb0x/CVE-2024-6387.svg) 
2024-07-06T10:47:30Z

- [https://github.com/getdrive/CVE-2024-6387-PoC](https://github.com/getdrive/CVE-2024-6387-PoC) :  
![starts](https://img.shields.io/github/stars/getdrive/CVE-2024-6387-PoC.svg) 
![forks](https://img.shields.io/github/forks/getdrive/CVE-2024-6387-PoC.svg) 
2024-07-01T13:34:47Z

- [https://github.com/thegenetic/CVE-2024-6387-exploit](https://github.com/thegenetic/CVE-2024-6387-exploit) :  
![starts](https://img.shields.io/github/stars/thegenetic/CVE-2024-6387-exploit.svg) 
![forks](https://img.shields.io/github/forks/thegenetic/CVE-2024-6387-exploit.svg) 
2024-07-02T04:45:15Z

- [https://github.com/sxlmnwb/CVE-2024-6387](https://github.com/sxlmnwb/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/sxlmnwb/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/sxlmnwb/CVE-2024-6387.svg) 
2024-07-03T06:47:46Z

- [https://github.com/devarshishimpi/CVE-2024-6387-Check](https://github.com/devarshishimpi/CVE-2024-6387-Check) :  
![starts](https://img.shields.io/github/stars/devarshishimpi/CVE-2024-6387-Check.svg) 
![forks](https://img.shields.io/github/forks/devarshishimpi/CVE-2024-6387-Check.svg) 
2024-07-08T20:39:03Z

- [https://github.com/YassDEV221608/CVE-2024-6387_PoC](https://github.com/YassDEV221608/CVE-2024-6387_PoC) :  
![starts](https://img.shields.io/github/stars/YassDEV221608/CVE-2024-6387_PoC.svg) 
![forks](https://img.shields.io/github/forks/YassDEV221608/CVE-2024-6387_PoC.svg) 
2025-01-04T00:37:14Z

- [https://github.com/AiGptCode/ssh_exploiter_CVE-2024-6387](https://github.com/AiGptCode/ssh_exploiter_CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/AiGptCode/ssh_exploiter_CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/AiGptCode/ssh_exploiter_CVE-2024-6387.svg) 
2024-07-04T01:55:26Z

- [https://github.com/TAM-K592/CVE-2024-6387](https://github.com/TAM-K592/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/TAM-K592/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/TAM-K592/CVE-2024-6387.svg) 
2024-07-02T03:23:00Z

- [https://github.com/l-urk/CVE-2024-6387](https://github.com/l-urk/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/l-urk/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/l-urk/CVE-2024-6387.svg) 
2024-10-19T04:58:22Z

- [https://github.com/0x4D31/cve-2024-6387_hassh](https://github.com/0x4D31/cve-2024-6387_hassh) :  
![starts](https://img.shields.io/github/stars/0x4D31/cve-2024-6387_hassh.svg) 
![forks](https://img.shields.io/github/forks/0x4D31/cve-2024-6387_hassh.svg) 
2024-07-05T03:40:53Z

- [https://github.com/wiggels/regresshion-check](https://github.com/wiggels/regresshion-check) :  
![starts](https://img.shields.io/github/stars/wiggels/regresshion-check.svg) 
![forks](https://img.shields.io/github/forks/wiggels/regresshion-check.svg) 
2024-07-16T20:25:52Z

- [https://github.com/3yujw7njai/CVE-2024-6387](https://github.com/3yujw7njai/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/3yujw7njai/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/3yujw7njai/CVE-2024-6387.svg) 
2024-07-02T01:13:22Z

- [https://github.com/kuffsit/check_cve_2024_6387](https://github.com/kuffsit/check_cve_2024_6387) :  
![starts](https://img.shields.io/github/stars/kuffsit/check_cve_2024_6387.svg) 
![forks](https://img.shields.io/github/forks/kuffsit/check_cve_2024_6387.svg) 
2024-07-22T09:41:11Z

- [https://github.com/th3gokul/CVE-2024-6387](https://github.com/th3gokul/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/th3gokul/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/th3gokul/CVE-2024-6387.svg) 
2024-07-02T17:47:29Z

- [https://github.com/azurejoga/CVE-2024-6387-how-to-fix](https://github.com/azurejoga/CVE-2024-6387-how-to-fix) :  
![starts](https://img.shields.io/github/stars/azurejoga/CVE-2024-6387-how-to-fix.svg) 
![forks](https://img.shields.io/github/forks/azurejoga/CVE-2024-6387-how-to-fix.svg) 
2024-07-05T21:47:44Z

- [https://github.com/xonoxitron/regreSSHion-checker](https://github.com/xonoxitron/regreSSHion-checker) :  
![starts](https://img.shields.io/github/stars/xonoxitron/regreSSHion-checker.svg) 
![forks](https://img.shields.io/github/forks/xonoxitron/regreSSHion-checker.svg) 
2024-07-02T19:06:01Z

- [https://github.com/paradessia/CVE-2024-6387-nmap](https://github.com/paradessia/CVE-2024-6387-nmap) :  
![starts](https://img.shields.io/github/stars/paradessia/CVE-2024-6387-nmap.svg) 
![forks](https://img.shields.io/github/forks/paradessia/CVE-2024-6387-nmap.svg) 
2024-07-02T08:26:46Z

- [https://github.com/awusan125/test_for6387](https://github.com/awusan125/test_for6387) :  
![starts](https://img.shields.io/github/stars/awusan125/test_for6387.svg) 
![forks](https://img.shields.io/github/forks/awusan125/test_for6387.svg) 
2024-12-22T08:24:46Z

- [https://github.com/lala-amber/CVE-2024-6387](https://github.com/lala-amber/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/lala-amber/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/lala-amber/CVE-2024-6387.svg) 
2024-07-04T13:35:57Z

- [https://github.com/BrandonLynch2402/cve-2024-6387-nuclei-template](https://github.com/BrandonLynch2402/cve-2024-6387-nuclei-template) :  
![starts](https://img.shields.io/github/stars/BrandonLynch2402/cve-2024-6387-nuclei-template.svg) 
![forks](https://img.shields.io/github/forks/BrandonLynch2402/cve-2024-6387-nuclei-template.svg) 
2024-07-02T20:28:35Z

- [https://github.com/PrincipalAnthony/CVE-2024-6387-Updated-x64bit](https://github.com/PrincipalAnthony/CVE-2024-6387-Updated-x64bit) :  
![starts](https://img.shields.io/github/stars/PrincipalAnthony/CVE-2024-6387-Updated-x64bit.svg) 
![forks](https://img.shields.io/github/forks/PrincipalAnthony/CVE-2024-6387-Updated-x64bit.svg) 
2024-07-02T09:46:08Z

- [https://github.com/harshinsecurity/sentinelssh](https://github.com/harshinsecurity/sentinelssh) :  
![starts](https://img.shields.io/github/stars/harshinsecurity/sentinelssh.svg) 
![forks](https://img.shields.io/github/forks/harshinsecurity/sentinelssh.svg) 
2024-07-08T07:32:32Z

- [https://github.com/MaulikxLakhani/SSHScout](https://github.com/MaulikxLakhani/SSHScout) :  
![starts](https://img.shields.io/github/stars/MaulikxLakhani/SSHScout.svg) 
![forks](https://img.shields.io/github/forks/MaulikxLakhani/SSHScout.svg) 
2024-07-02T12:29:46Z

- [https://github.com/betancour/OpenSSH-Vulnerability-test](https://github.com/betancour/OpenSSH-Vulnerability-test) :  
![starts](https://img.shields.io/github/stars/betancour/OpenSSH-Vulnerability-test.svg) 
![forks](https://img.shields.io/github/forks/betancour/OpenSSH-Vulnerability-test.svg) 
2024-07-02T01:31:11Z

- [https://github.com/Symbolexe/CVE-2024-6387](https://github.com/Symbolexe/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/Symbolexe/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/Symbolexe/CVE-2024-6387.svg) 
2024-07-04T15:07:21Z

- [https://github.com/prelearn-code/CVE-2024-6387](https://github.com/prelearn-code/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/prelearn-code/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/prelearn-code/CVE-2024-6387.svg) 
2024-07-25T02:37:55Z

- [https://github.com/AzrDll/CVE-2024-6387](https://github.com/AzrDll/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/AzrDll/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/AzrDll/CVE-2024-6387.svg) 
2025-01-20T09:40:27Z

- [https://github.com/ahlfors/CVE-2024-6387](https://github.com/ahlfors/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ahlfors/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ahlfors/CVE-2024-6387.svg) 
2024-07-02T09:57:35Z

- [https://github.com/ThatNotEasy/CVE-2024-6387](https://github.com/ThatNotEasy/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-6387.svg) 
2024-07-15T16:06:41Z

- [https://github.com/muyuanlove/CVE-2024-6387fixshell](https://github.com/muyuanlove/CVE-2024-6387fixshell) :  
![starts](https://img.shields.io/github/stars/muyuanlove/CVE-2024-6387fixshell.svg) 
![forks](https://img.shields.io/github/forks/muyuanlove/CVE-2024-6387fixshell.svg) 
2024-07-02T02:39:40Z

- [https://github.com/ACHUX21/checker-CVE-2024-6387](https://github.com/ACHUX21/checker-CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ACHUX21/checker-CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ACHUX21/checker-CVE-2024-6387.svg) 
2024-07-02T13:18:38Z

- [https://github.com/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker](https://github.com/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker) :  
![starts](https://img.shields.io/github/stars/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker.svg) 
![forks](https://img.shields.io/github/forks/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker.svg) 
2024-08-29T14:52:33Z

- [https://github.com/anhvutuan/CVE-2024-6387-poc-1](https://github.com/anhvutuan/CVE-2024-6387-poc-1) :  
![starts](https://img.shields.io/github/stars/anhvutuan/CVE-2024-6387-poc-1.svg) 
![forks](https://img.shields.io/github/forks/anhvutuan/CVE-2024-6387-poc-1.svg) 
2024-07-11T14:59:20Z

- [https://github.com/MrR0b0t19/CVE-2024-6387-Exploit-POC](https://github.com/MrR0b0t19/CVE-2024-6387-Exploit-POC) :  
![starts](https://img.shields.io/github/stars/MrR0b0t19/CVE-2024-6387-Exploit-POC.svg) 
![forks](https://img.shields.io/github/forks/MrR0b0t19/CVE-2024-6387-Exploit-POC.svg) 
2024-07-02T16:38:33Z

- [https://github.com/Sibijo/mitigate_ssh](https://github.com/Sibijo/mitigate_ssh) :  
![starts](https://img.shields.io/github/stars/Sibijo/mitigate_ssh.svg) 
![forks](https://img.shields.io/github/forks/Sibijo/mitigate_ssh.svg) 
2024-07-11T16:55:52Z

- [https://github.com/rumochnaya/openssh-cve-2024-6387.sh](https://github.com/rumochnaya/openssh-cve-2024-6387.sh) :  
![starts](https://img.shields.io/github/stars/rumochnaya/openssh-cve-2024-6387.sh.svg) 
![forks](https://img.shields.io/github/forks/rumochnaya/openssh-cve-2024-6387.sh.svg) 
2024-07-02T11:23:35Z

- [https://github.com/R4Tw1z/CVE-2024-6387](https://github.com/R4Tw1z/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/R4Tw1z/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/R4Tw1z/CVE-2024-6387.svg) 
2024-07-02T09:01:55Z

- [https://github.com/grupooruss/CVE-2024-6387](https://github.com/grupooruss/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/grupooruss/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/grupooruss/CVE-2024-6387.svg) 
2024-07-02T21:30:12Z

- [https://github.com/shamo0/CVE-2024-6387_PoC](https://github.com/shamo0/CVE-2024-6387_PoC) :  
![starts](https://img.shields.io/github/stars/shamo0/CVE-2024-6387_PoC.svg) 
![forks](https://img.shields.io/github/forks/shamo0/CVE-2024-6387_PoC.svg) 
2024-07-02T08:40:31Z

- [https://github.com/passwa11/cve-2024-6387-poc](https://github.com/passwa11/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/passwa11/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/passwa11/cve-2024-6387-poc.svg) 
2024-07-01T14:10:08Z

- [https://github.com/n1cks0n/Test_CVE-2024-6387](https://github.com/n1cks0n/Test_CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/n1cks0n/Test_CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/n1cks0n/Test_CVE-2024-6387.svg) 
2024-07-02T18:31:41Z

- [https://github.com/identity-threat-labs/Article-RegreSSHion-CVE-2024-6387](https://github.com/identity-threat-labs/Article-RegreSSHion-CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/identity-threat-labs/Article-RegreSSHion-CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/identity-threat-labs/Article-RegreSSHion-CVE-2024-6387.svg) 
2024-08-29T15:06:16Z

- [https://github.com/turbobit/CVE-2024-6387-OpenSSH-Vulnerability-Checker](https://github.com/turbobit/CVE-2024-6387-OpenSSH-Vulnerability-Checker) :  
![starts](https://img.shields.io/github/stars/turbobit/CVE-2024-6387-OpenSSH-Vulnerability-Checker.svg) 
![forks](https://img.shields.io/github/forks/turbobit/CVE-2024-6387-OpenSSH-Vulnerability-Checker.svg) 
2024-07-04T05:13:49Z

- [https://github.com/teamos-hub/regreSSHion](https://github.com/teamos-hub/regreSSHion) :  
![starts](https://img.shields.io/github/stars/teamos-hub/regreSSHion.svg) 
![forks](https://img.shields.io/github/forks/teamos-hub/regreSSHion.svg) 
2024-07-02T02:48:35Z

- [https://github.com/X-Projetion/CVE-2023-4596-OpenSSH-Multi-Checker](https://github.com/X-Projetion/CVE-2023-4596-OpenSSH-Multi-Checker) :  
![starts](https://img.shields.io/github/stars/X-Projetion/CVE-2023-4596-OpenSSH-Multi-Checker.svg) 
![forks](https://img.shields.io/github/forks/X-Projetion/CVE-2023-4596-OpenSSH-Multi-Checker.svg) 
2024-08-06T08:27:32Z

- [https://github.com/password123456/cve-security-response-guidelines](https://github.com/password123456/cve-security-response-guidelines) :  
![starts](https://img.shields.io/github/stars/password123456/cve-security-response-guidelines.svg) 
![forks](https://img.shields.io/github/forks/password123456/cve-security-response-guidelines.svg) 
2024-07-12T04:18:04Z

- [https://github.com/hssmo/cve-2024-6387_AImade](https://github.com/hssmo/cve-2024-6387_AImade) :  
![starts](https://img.shields.io/github/stars/hssmo/cve-2024-6387_AImade.svg) 
![forks](https://img.shields.io/github/forks/hssmo/cve-2024-6387_AImade.svg) 
2024-07-02T12:34:33Z

- [https://github.com/FerasAlrimali/CVE-2024-6387-POC](https://github.com/FerasAlrimali/CVE-2024-6387-POC) :  
![starts](https://img.shields.io/github/stars/FerasAlrimali/CVE-2024-6387-POC.svg) 
![forks](https://img.shields.io/github/forks/FerasAlrimali/CVE-2024-6387-POC.svg) 
2024-07-01T13:42:15Z

- [https://github.com/SiberianHacker/CVE-2024-6387-Finder](https://github.com/SiberianHacker/CVE-2024-6387-Finder) :  
![starts](https://img.shields.io/github/stars/SiberianHacker/CVE-2024-6387-Finder.svg) 
![forks](https://img.shields.io/github/forks/SiberianHacker/CVE-2024-6387-Finder.svg) 
2024-07-05T15:22:25Z

- [https://github.com/jack0we/CVE-2024-6387](https://github.com/jack0we/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/jack0we/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/jack0we/CVE-2024-6387.svg) 
2024-07-01T18:32:41Z

- [https://github.com/sms2056/CVE-2024-6387](https://github.com/sms2056/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/sms2056/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/sms2056/CVE-2024-6387.svg) 
2024-07-04T06:16:19Z

- [https://github.com/no-one-sec/CVE-2024-6387](https://github.com/no-one-sec/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/no-one-sec/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/no-one-sec/CVE-2024-6387.svg) 
2024-07-02T15:13:09Z

- [https://github.com/imv7/CVE-2024-6387](https://github.com/imv7/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/imv7/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/imv7/CVE-2024-6387.svg) 
2024-07-05T11:19:21Z

- [https://github.com/dawnl3ss/CVE-2024-6387](https://github.com/dawnl3ss/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dawnl3ss/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dawnl3ss/CVE-2024-6387.svg) 
2024-07-02T15:14:37Z

- [https://github.com/zql-gif/CVE-2024-6387](https://github.com/zql-gif/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/zql-gif/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/zql-gif/CVE-2024-6387.svg) 
2024-12-19T06:49:52Z

- [https://github.com/mrmtwoj/CVE-2024-6387](https://github.com/mrmtwoj/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/mrmtwoj/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/mrmtwoj/CVE-2024-6387.svg) 
2024-07-09T14:29:30Z

- [https://github.com/YassDEV221608/CVE-2024-6387](https://github.com/YassDEV221608/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/YassDEV221608/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/YassDEV221608/CVE-2024-6387.svg) 
2024-11-24T17:14:29Z

- [https://github.com/dream434/CVE-2024-6387](https://github.com/dream434/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-6387.svg) 
2025-02-22T19:30:02Z

- [https://github.com/DimaMend/cve-2024-6387-poc](https://github.com/DimaMend/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/DimaMend/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/DimaMend/cve-2024-6387-poc.svg) 
2024-07-10T13:33:50Z

- [https://github.com/Mufti22/CVE-2024-6387-checkher](https://github.com/Mufti22/CVE-2024-6387-checkher) :  
![starts](https://img.shields.io/github/stars/Mufti22/CVE-2024-6387-checkher.svg) 
![forks](https://img.shields.io/github/forks/Mufti22/CVE-2024-6387-checkher.svg) 
2024-07-02T03:49:06Z

- [https://github.com/edsonjt81/CVE-2024-6387_Check](https://github.com/edsonjt81/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/edsonjt81/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/edsonjt81/CVE-2024-6387_Check.svg) 
2024-07-02T20:38:06Z

- [https://github.com/CognisysGroup/CVE-2024-6387-Checker](https://github.com/CognisysGroup/CVE-2024-6387-Checker) :  
![starts](https://img.shields.io/github/stars/CognisysGroup/CVE-2024-6387-Checker.svg) 
![forks](https://img.shields.io/github/forks/CognisysGroup/CVE-2024-6387-Checker.svg) 
2024-07-03T12:13:37Z

- [https://github.com/HadesNull123/CVE-2024-6387_Check](https://github.com/HadesNull123/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/HadesNull123/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/HadesNull123/CVE-2024-6387_Check.svg) 
2024-08-26T04:41:02Z

- [https://github.com/sardine-web/CVE-2024-6387-template](https://github.com/sardine-web/CVE-2024-6387-template) :  
![starts](https://img.shields.io/github/stars/sardine-web/CVE-2024-6387-template.svg) 
![forks](https://img.shields.io/github/forks/sardine-web/CVE-2024-6387-template.svg) 
2024-07-06T17:26:21Z

- [https://github.com/shyrwall/cve-2024-6387-poc](https://github.com/shyrwall/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/shyrwall/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/shyrwall/cve-2024-6387-poc.svg) 
2024-07-01T12:50:29Z

- [https://github.com/t3rry327/cve-2024-6387-poc](https://github.com/t3rry327/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/t3rry327/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/t3rry327/cve-2024-6387-poc.svg) 
2024-07-03T13:24:59Z

- [https://github.com/dgourillon/mitigate-CVE-2024-6387](https://github.com/dgourillon/mitigate-CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dgourillon/mitigate-CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dgourillon/mitigate-CVE-2024-6387.svg) 
2024-07-09T16:03:03Z

- [https://github.com/sardine-web/CVE-2024-6387_Check](https://github.com/sardine-web/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/sardine-web/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/sardine-web/CVE-2024-6387_Check.svg) 
2024-07-04T21:31:17Z

- [https://github.com/zenzue/CVE-2024-6387-Mitigation](https://github.com/zenzue/CVE-2024-6387-Mitigation) :  
![starts](https://img.shields.io/github/stars/zenzue/CVE-2024-6387-Mitigation.svg) 
![forks](https://img.shields.io/github/forks/zenzue/CVE-2024-6387-Mitigation.svg) 
2024-07-02T11:17:12Z

- [https://github.com/SkyGodling/CVE-2024-6387-POC](https://github.com/SkyGodling/CVE-2024-6387-POC) :  
![starts](https://img.shields.io/github/stars/SkyGodling/CVE-2024-6387-POC.svg) 
![forks](https://img.shields.io/github/forks/SkyGodling/CVE-2024-6387-POC.svg) 
2025-02-10T06:25:56Z

- [https://github.com/RickGeex/CVE-2024-6387-Checker](https://github.com/RickGeex/CVE-2024-6387-Checker) :  
![starts](https://img.shields.io/github/stars/RickGeex/CVE-2024-6387-Checker.svg) 
![forks](https://img.shields.io/github/forks/RickGeex/CVE-2024-6387-Checker.svg) 
2024-07-02T20:32:48Z

- [https://github.com/jocker2410/CVE-2024-6387_poc](https://github.com/jocker2410/CVE-2024-6387_poc) :  
![starts](https://img.shields.io/github/stars/jocker2410/CVE-2024-6387_poc.svg) 
![forks](https://img.shields.io/github/forks/jocker2410/CVE-2024-6387_poc.svg) 
2024-08-04T10:50:53Z

- [https://github.com/JackSparrowhk/ssh-CVE-2024-6387-poc](https://github.com/JackSparrowhk/ssh-CVE-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/JackSparrowhk/ssh-CVE-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/JackSparrowhk/ssh-CVE-2024-6387-poc.svg) 
2024-07-04T03:51:16Z

- [https://github.com/kubota/CVE-2024-6387-Vulnerability-Checker](https://github.com/kubota/CVE-2024-6387-Vulnerability-Checker) :  
![starts](https://img.shields.io/github/stars/kubota/CVE-2024-6387-Vulnerability-Checker.svg) 
![forks](https://img.shields.io/github/forks/kubota/CVE-2024-6387-Vulnerability-Checker.svg) 
2024-07-09T21:08:19Z

- [https://github.com/4lxprime/regreSSHive](https://github.com/4lxprime/regreSSHive) :  
![starts](https://img.shields.io/github/stars/4lxprime/regreSSHive.svg) 
![forks](https://img.shields.io/github/forks/4lxprime/regreSSHive.svg) 
2024-07-04T14:34:23Z

- [https://github.com/invaderslabs/regreSSHion-CVE-2024-6387-](https://github.com/invaderslabs/regreSSHion-CVE-2024-6387-) :  
![starts](https://img.shields.io/github/stars/invaderslabs/regreSSHion-CVE-2024-6387-.svg) 
![forks](https://img.shields.io/github/forks/invaderslabs/regreSSHion-CVE-2024-6387-.svg) 
2024-07-04T22:22:15Z

- [https://github.com/almogopp/OpenSSH-CVE-2024-6387-Fix](https://github.com/almogopp/OpenSSH-CVE-2024-6387-Fix) :  
![starts](https://img.shields.io/github/stars/almogopp/OpenSSH-CVE-2024-6387-Fix.svg) 
![forks](https://img.shields.io/github/forks/almogopp/OpenSSH-CVE-2024-6387-Fix.svg) 
2024-08-20T09:58:32Z

- [https://github.com/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook](https://github.com/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook) :  
![starts](https://img.shields.io/github/stars/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook.svg) 
![forks](https://img.shields.io/github/forks/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook.svg) 
2024-07-02T11:05:55Z

- [https://github.com/Passyed/regreSSHion-Fix](https://github.com/Passyed/regreSSHion-Fix) :  
![starts](https://img.shields.io/github/stars/Passyed/regreSSHion-Fix.svg) 
![forks](https://img.shields.io/github/forks/Passyed/regreSSHion-Fix.svg) 
2024-07-12T00:06:59Z

- [https://github.com/vkaushik-chef/regreSSHion](https://github.com/vkaushik-chef/regreSSHion) :  
![starts](https://img.shields.io/github/stars/vkaushik-chef/regreSSHion.svg) 
![forks](https://img.shields.io/github/forks/vkaushik-chef/regreSSHion.svg) 
2024-07-08T12:04:33Z

- [https://github.com/CiderAndWhisky/regression-scanner](https://github.com/CiderAndWhisky/regression-scanner) :  
![starts](https://img.shields.io/github/stars/CiderAndWhisky/regression-scanner.svg) 
![forks](https://img.shields.io/github/forks/CiderAndWhisky/regression-scanner.svg) 
2024-07-02T09:06:04Z

- [https://github.com/s1d6point7bugcrowd/CVE-2024-6387-Race-Condition-in-Signal-Handling-for-OpenSSH](https://github.com/s1d6point7bugcrowd/CVE-2024-6387-Race-Condition-in-Signal-Handling-for-OpenSSH) :  
![starts](https://img.shields.io/github/stars/s1d6point7bugcrowd/CVE-2024-6387-Race-Condition-in-Signal-Handling-for-OpenSSH.svg) 
![forks](https://img.shields.io/github/forks/s1d6point7bugcrowd/CVE-2024-6387-Race-Condition-in-Signal-Handling-for-OpenSSH.svg) 
2024-08-19T16:47:14Z

- [https://github.com/alex14324/ssh_poc2024](https://github.com/alex14324/ssh_poc2024) :  
![starts](https://img.shields.io/github/stars/alex14324/ssh_poc2024.svg) 
![forks](https://img.shields.io/github/forks/alex14324/ssh_poc2024.svg) 
2024-07-31T14:19:44Z

- [https://github.com/xristos8574/regreSSHion-nmap-scanner](https://github.com/xristos8574/regreSSHion-nmap-scanner) :  
![starts](https://img.shields.io/github/stars/xristos8574/regreSSHion-nmap-scanner.svg) 
![forks](https://img.shields.io/github/forks/xristos8574/regreSSHion-nmap-scanner.svg) 
2024-07-02T13:52:23Z

# 2025-02-24
## CVE-2024-56897
 Improper access control in the HTTP server in YI Car Dashcam v3.88 allows unrestricted file downloads, uploads, and API commands. API commands can also be made to make unauthorized modifications to the device settings, such as disabling recording, disabling sounds, factory reset.

- [https://github.com/geo-chen/YI-Smart-Dashcam](https://github.com/geo-chen/YI-Smart-Dashcam) :  
![starts](https://img.shields.io/github/stars/geo-chen/YI-Smart-Dashcam.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/YI-Smart-Dashcam.svg) 
2025-02-24T17:02:15Z

## CVE-2024-53677
 File upload logic in Apache Struts is flawed.An attacker can manipulate file upload params to enable paths traversal and under some circumstances this can lead to uploading a malicious file which can be used to perform Remote Code Execution.This issue affects Apache Struts: from 2.0.0 before 6.4.0.Users are recommended to upgrade to version 6.4.0 at least and migrate to the new  file upload mechanism https://struts.apache.org/core-developers/file-upload . If you are not using an old file upload logic based onFileuploadInterceptoryour application is safe.You can find more details in https://cwiki.apache.org/confluence/display/WW/S2-067

- [https://github.com/TAM-K592/CVE-2024-53677-S2-067](https://github.com/TAM-K592/CVE-2024-53677-S2-067) :  
![starts](https://img.shields.io/github/stars/TAM-K592/CVE-2024-53677-S2-067.svg) 
![forks](https://img.shields.io/github/forks/TAM-K592/CVE-2024-53677-S2-067.svg) 
2024-12-20T10:05:15Z

- [https://github.com/cloudwafs/s2-067-CVE-2024-53677](https://github.com/cloudwafs/s2-067-CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/cloudwafs/s2-067-CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/cloudwafs/s2-067-CVE-2024-53677.svg) 
2024-12-17T10:37:17Z

- [https://github.com/XiaomingX/CVE-2024-53677-S2-067](https://github.com/XiaomingX/CVE-2024-53677-S2-067) :  
![starts](https://img.shields.io/github/stars/XiaomingX/CVE-2024-53677-S2-067.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/CVE-2024-53677-S2-067.svg) 
2024-12-18T02:08:09Z

- [https://github.com/EQSTLab/CVE-2024-53677](https://github.com/EQSTLab/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/EQSTLab/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/EQSTLab/CVE-2024-53677.svg) 
2025-01-03T18:51:20Z

- [https://github.com/c4oocO/CVE-2024-53677-Docker](https://github.com/c4oocO/CVE-2024-53677-Docker) :  
![starts](https://img.shields.io/github/stars/c4oocO/CVE-2024-53677-Docker.svg) 
![forks](https://img.shields.io/github/forks/c4oocO/CVE-2024-53677-Docker.svg) 
2024-12-17T07:01:11Z

- [https://github.com/SeanRickerd/CVE-2024-53677](https://github.com/SeanRickerd/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/SeanRickerd/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/SeanRickerd/CVE-2024-53677.svg) 
2025-02-18T13:36:17Z

- [https://github.com/yangyanglo/CVE-2024-53677](https://github.com/yangyanglo/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/yangyanglo/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/yangyanglo/CVE-2024-53677.svg) 
2024-12-17T08:52:36Z

- [https://github.com/dustblessnotdust/CVE-2024-53677-S2-067-thread](https://github.com/dustblessnotdust/CVE-2024-53677-S2-067-thread) :  
![starts](https://img.shields.io/github/stars/dustblessnotdust/CVE-2024-53677-S2-067-thread.svg) 
![forks](https://img.shields.io/github/forks/dustblessnotdust/CVE-2024-53677-S2-067-thread.svg) 
2024-12-18T19:10:48Z

- [https://github.com/punitdarji/Apache-struts-cve-2024-53677](https://github.com/punitdarji/Apache-struts-cve-2024-53677) :  
![starts](https://img.shields.io/github/stars/punitdarji/Apache-struts-cve-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/punitdarji/Apache-struts-cve-2024-53677.svg) 
2025-01-11T11:11:06Z

- [https://github.com/0xdeviner/CVE-2024-53677](https://github.com/0xdeviner/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/0xdeviner/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/0xdeviner/CVE-2024-53677.svg) 
2024-12-23T14:27:51Z

- [https://github.com/shishirghimir/CVE-2024-53677-Exploit](https://github.com/shishirghimir/CVE-2024-53677-Exploit) :  
![starts](https://img.shields.io/github/stars/shishirghimir/CVE-2024-53677-Exploit.svg) 
![forks](https://img.shields.io/github/forks/shishirghimir/CVE-2024-53677-Exploit.svg) 
2025-02-24T13:09:53Z

- [https://github.com/hopsypopsy8/CVE-2024-53677-Exploitation](https://github.com/hopsypopsy8/CVE-2024-53677-Exploitation) :  
![starts](https://img.shields.io/github/stars/hopsypopsy8/CVE-2024-53677-Exploitation.svg) 
![forks](https://img.shields.io/github/forks/hopsypopsy8/CVE-2024-53677-Exploitation.svg) 
2025-02-13T09:10:53Z

- [https://github.com/0xPThree/struts_cve-2024-53677](https://github.com/0xPThree/struts_cve-2024-53677) :  
![starts](https://img.shields.io/github/stars/0xPThree/struts_cve-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/0xPThree/struts_cve-2024-53677.svg) 
2025-01-07T11:39:34Z

## CVE-2024-9698
 The Crafthemes Demo Import plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'process_uploaded_files' function in all versions up to, and including, 3.3. This makes it possible for authenticated attackers, with Administrator-level access and above, to upload arbitrary files on the affected site's server which may make remote code execution possible.

- [https://github.com/Nxploited/CVE-2024-9698](https://github.com/Nxploited/CVE-2024-9698) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-9698.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-9698.svg) 
2025-02-24T14:48:08Z

## CVE-2024-2961
 The iconv() function in the GNU C Library versions 2.39 and older may overflow the output buffer passed to it by up to 4 bytes when converting strings to the ISO-2022-CN-EXT character set, which may be used to crash an application or overwrite a neighbouring variable.

- [https://github.com/ambionics/cnext-exploits](https://github.com/ambionics/cnext-exploits) :  
![starts](https://img.shields.io/github/stars/ambionics/cnext-exploits.svg) 
![forks](https://img.shields.io/github/forks/ambionics/cnext-exploits.svg) 
2024-09-30T08:45:56Z

- [https://github.com/rvizx/CVE-2024-2961](https://github.com/rvizx/CVE-2024-2961) :  
![starts](https://img.shields.io/github/stars/rvizx/CVE-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/rvizx/CVE-2024-2961.svg) 
2024-05-20T07:12:24Z

- [https://github.com/kyotozx/CVE-2024-2961-Remote-File-Read](https://github.com/kyotozx/CVE-2024-2961-Remote-File-Read) :  
![starts](https://img.shields.io/github/stars/kyotozx/CVE-2024-2961-Remote-File-Read.svg) 
![forks](https://img.shields.io/github/forks/kyotozx/CVE-2024-2961-Remote-File-Read.svg) 
2025-01-27T06:22:02Z

- [https://github.com/suce0155/CVE-2024-2961_buddyforms_2.7.7](https://github.com/suce0155/CVE-2024-2961_buddyforms_2.7.7) :  
![starts](https://img.shields.io/github/stars/suce0155/CVE-2024-2961_buddyforms_2.7.7.svg) 
![forks](https://img.shields.io/github/forks/suce0155/CVE-2024-2961_buddyforms_2.7.7.svg) 
2025-02-04T18:51:48Z

- [https://github.com/kjdfklha/CVE-2024-2961_poc](https://github.com/kjdfklha/CVE-2024-2961_poc) :  
![starts](https://img.shields.io/github/stars/kjdfklha/CVE-2024-2961_poc.svg) 
![forks](https://img.shields.io/github/forks/kjdfklha/CVE-2024-2961_poc.svg) 
2024-06-04T10:02:44Z

- [https://github.com/mattaperkins/FIX-CVE-2024-2961](https://github.com/mattaperkins/FIX-CVE-2024-2961) :  
![starts](https://img.shields.io/github/stars/mattaperkins/FIX-CVE-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/mattaperkins/FIX-CVE-2024-2961.svg) 
2024-04-24T07:43:10Z

- [https://github.com/4wayhandshake/CVE-2024-2961](https://github.com/4wayhandshake/CVE-2024-2961) :  
![starts](https://img.shields.io/github/stars/4wayhandshake/CVE-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/4wayhandshake/CVE-2024-2961.svg) 
2025-02-01T10:48:45Z

- [https://github.com/tnishiox/cve-2024-2961](https://github.com/tnishiox/cve-2024-2961) :  
![starts](https://img.shields.io/github/stars/tnishiox/cve-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/tnishiox/cve-2024-2961.svg) 
2024-06-04T09:01:16Z

- [https://github.com/absolutedesignltd/iconvfix](https://github.com/absolutedesignltd/iconvfix) :  
![starts](https://img.shields.io/github/stars/absolutedesignltd/iconvfix.svg) 
![forks](https://img.shields.io/github/forks/absolutedesignltd/iconvfix.svg) 
2024-05-30T13:57:34Z

- [https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961](https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961) :  
![starts](https://img.shields.io/github/stars/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
2025-02-02T11:26:18Z

- [https://github.com/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-](https://github.com/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-) :  
![starts](https://img.shields.io/github/stars/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-.svg) 
![forks](https://img.shields.io/github/forks/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-.svg) 
2025-02-24T04:06:50Z

- [https://github.com/exfil0/test_iconv](https://github.com/exfil0/test_iconv) :  
![starts](https://img.shields.io/github/stars/exfil0/test_iconv.svg) 
![forks](https://img.shields.io/github/forks/exfil0/test_iconv.svg) 
2024-06-04T00:22:13Z

## CVE-2023-1545
 SQL Injection in GitHub repository nilsteampassnet/teampass prior to 3.0.0.23.

- [https://github.com/zer0-dave/CVE-2023-1545-POC](https://github.com/zer0-dave/CVE-2023-1545-POC) :  
![starts](https://img.shields.io/github/stars/zer0-dave/CVE-2023-1545-POC.svg) 
![forks](https://img.shields.io/github/forks/zer0-dave/CVE-2023-1545-POC.svg) 
2025-02-24T18:08:20Z

- [https://github.com/HarshRajSinghania/CVE-2023-1545-Exploit](https://github.com/HarshRajSinghania/CVE-2023-1545-Exploit) :  
![starts](https://img.shields.io/github/stars/HarshRajSinghania/CVE-2023-1545-Exploit.svg) 
![forks](https://img.shields.io/github/forks/HarshRajSinghania/CVE-2023-1545-Exploit.svg) 
2025-02-22T20:17:48Z

# 2025-02-23
## CVE-2025-20029
 Command injection vulnerability exists in iControl REST and BIG-IP TMOS Shell (tmsh) save command, which may allow an authenticated attacker to execute arbitrary system commands. Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated.

- [https://github.com/mbadanoiu/CVE-2025-20029](https://github.com/mbadanoiu/CVE-2025-20029) :  
![starts](https://img.shields.io/github/stars/mbadanoiu/CVE-2025-20029.svg) 
![forks](https://img.shields.io/github/forks/mbadanoiu/CVE-2025-20029.svg) 
2025-02-23T18:53:24Z

## CVE-2025-0924
 The WP Activity Log plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the message parameter in all versions up to, and including, 5.2.2 due to insufficient input sanitization and output escaping. This makes it possible for unauthenticated attackers to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page.

- [https://github.com/skrkcb2/CVE-2025-0924-different](https://github.com/skrkcb2/CVE-2025-0924-different) :  
![starts](https://img.shields.io/github/stars/skrkcb2/CVE-2025-0924-different.svg) 
![forks](https://img.shields.io/github/forks/skrkcb2/CVE-2025-0924-different.svg) 
2025-02-23T00:33:17Z

## CVE-2025-0411
 7-Zip Mark-of-the-Web Bypass Vulnerability. This vulnerability allows remote attackers to bypass the Mark-of-the-Web protection mechanism on affected installations of 7-Zip. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file.The specific flaw exists within the handling of archived files. When extracting files from a crafted archive that bears the Mark-of-the-Web, 7-Zip does not propagate the Mark-of-the-Web to the extracted files. An attacker can leverage this vulnerability to execute arbitrary code in the context of the current user. Was ZDI-CAN-25456.

- [https://github.com/dhmosfunk/7-Zip-CVE-2025-0411-POC](https://github.com/dhmosfunk/7-Zip-CVE-2025-0411-POC) :  
![starts](https://img.shields.io/github/stars/dhmosfunk/7-Zip-CVE-2025-0411-POC.svg) 
![forks](https://img.shields.io/github/forks/dhmosfunk/7-Zip-CVE-2025-0411-POC.svg) 
2025-01-22T15:08:56Z

- [https://github.com/iSee857/CVE-2025-0411-PoC](https://github.com/iSee857/CVE-2025-0411-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2025-0411-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2025-0411-PoC.svg) 
2025-01-27T07:34:46Z

- [https://github.com/cesarbtakeda/7-Zip-CVE-2025-0411-POC](https://github.com/cesarbtakeda/7-Zip-CVE-2025-0411-POC) :  
![starts](https://img.shields.io/github/stars/cesarbtakeda/7-Zip-CVE-2025-0411-POC.svg) 
![forks](https://img.shields.io/github/forks/cesarbtakeda/7-Zip-CVE-2025-0411-POC.svg) 
2025-02-23T03:22:56Z

- [https://github.com/ishwardeepp/CVE-2025-0411-MoTW-PoC](https://github.com/ishwardeepp/CVE-2025-0411-MoTW-PoC) :  
![starts](https://img.shields.io/github/stars/ishwardeepp/CVE-2025-0411-MoTW-PoC.svg) 
![forks](https://img.shields.io/github/forks/ishwardeepp/CVE-2025-0411-MoTW-PoC.svg) 
2025-02-20T14:15:56Z

## CVE-2024-23724
 Ghost through 5.76.0 allows stored XSS, and resultant privilege escalation in which a contributor can take over any account, via an SVG profile picture that contains JavaScript code to interact with the API on localhost TCP port 3001. NOTE: The discoverer reports that "The vendor does not view this as a valid vector."

- [https://github.com/Youssefdds/CVE-2024-23724](https://github.com/Youssefdds/CVE-2024-23724) :  
![starts](https://img.shields.io/github/stars/Youssefdds/CVE-2024-23724.svg) 
![forks](https://img.shields.io/github/forks/Youssefdds/CVE-2024-23724.svg) 
2025-01-19T16:42:17Z

- [https://github.com/gl1tch0x1/Ghost-CMS-Exploit](https://github.com/gl1tch0x1/Ghost-CMS-Exploit) :  
![starts](https://img.shields.io/github/stars/gl1tch0x1/Ghost-CMS-Exploit.svg) 
![forks](https://img.shields.io/github/forks/gl1tch0x1/Ghost-CMS-Exploit.svg) 
2025-02-23T07:29:16Z

## CVE-2024-10924
 The Really Simple Security (Free, Pro, and Pro Multisite) plugins for WordPress are vulnerable to authentication bypass in versions 9.0.0 to 9.1.1.1. This is due to improper user check error handling in the two-factor REST API actions with the 'check_login_and_get_user' function. This makes it possible for unauthenticated attackers to log in as any existing user on the site, such as an administrator, when the "Two-Factor Authentication" setting is enabled (disabled by default).

- [https://github.com/m3ssap0/wordpress-really-simple-security-authn-bypass-exploit](https://github.com/m3ssap0/wordpress-really-simple-security-authn-bypass-exploit) :  
![starts](https://img.shields.io/github/stars/m3ssap0/wordpress-really-simple-security-authn-bypass-exploit.svg) 
![forks](https://img.shields.io/github/forks/m3ssap0/wordpress-really-simple-security-authn-bypass-exploit.svg) 
2024-11-19T12:20:16Z

- [https://github.com/m3ssap0/wordpress-really-simple-security-authn-bypass-vulnerable-application](https://github.com/m3ssap0/wordpress-really-simple-security-authn-bypass-vulnerable-application) :  
![starts](https://img.shields.io/github/stars/m3ssap0/wordpress-really-simple-security-authn-bypass-vulnerable-application.svg) 
![forks](https://img.shields.io/github/forks/m3ssap0/wordpress-really-simple-security-authn-bypass-vulnerable-application.svg) 
2024-11-19T12:19:36Z

- [https://github.com/RandomRobbieBF/CVE-2024-10924](https://github.com/RandomRobbieBF/CVE-2024-10924) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-10924.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-10924.svg) 
2024-11-14T17:00:59Z

- [https://github.com/Maalfer/CVE-2024-10924-PoC](https://github.com/Maalfer/CVE-2024-10924-PoC) :  
![starts](https://img.shields.io/github/stars/Maalfer/CVE-2024-10924-PoC.svg) 
![forks](https://img.shields.io/github/forks/Maalfer/CVE-2024-10924-PoC.svg) 
2024-11-27T14:13:57Z

- [https://github.com/Nxploited/CVE-2024-10924-Exploit](https://github.com/Nxploited/CVE-2024-10924-Exploit) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-10924-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-10924-Exploit.svg) 
2025-02-02T23:26:52Z

- [https://github.com/h8sU/wordpress-cve-2024-10924-exploit](https://github.com/h8sU/wordpress-cve-2024-10924-exploit) :  
![starts](https://img.shields.io/github/stars/h8sU/wordpress-cve-2024-10924-exploit.svg) 
![forks](https://img.shields.io/github/forks/h8sU/wordpress-cve-2024-10924-exploit.svg) 
2025-02-14T13:50:31Z

- [https://github.com/Trackflaw/CVE-2024-10924-Wordpress-Docker](https://github.com/Trackflaw/CVE-2024-10924-Wordpress-Docker) :  
![starts](https://img.shields.io/github/stars/Trackflaw/CVE-2024-10924-Wordpress-Docker.svg) 
![forks](https://img.shields.io/github/forks/Trackflaw/CVE-2024-10924-Wordpress-Docker.svg) 
2024-11-22T09:28:08Z

- [https://github.com/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB](https://github.com/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB) :  
![starts](https://img.shields.io/github/stars/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB.svg) 
![forks](https://img.shields.io/github/forks/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB.svg) 
2024-12-02T08:32:47Z

- [https://github.com/MattJButler/CVE-2024-10924](https://github.com/MattJButler/CVE-2024-10924) :  
![starts](https://img.shields.io/github/stars/MattJButler/CVE-2024-10924.svg) 
![forks](https://img.shields.io/github/forks/MattJButler/CVE-2024-10924.svg) 
2024-11-19T03:08:53Z

- [https://github.com/julesbsz/CVE-2024-10924](https://github.com/julesbsz/CVE-2024-10924) :  
![starts](https://img.shields.io/github/stars/julesbsz/CVE-2024-10924.svg) 
![forks](https://img.shields.io/github/forks/julesbsz/CVE-2024-10924.svg) 
2024-11-20T14:00:11Z

- [https://github.com/cy3erdr4g0n/CVE-2024-10924](https://github.com/cy3erdr4g0n/CVE-2024-10924) :  
![starts](https://img.shields.io/github/stars/cy3erdr4g0n/CVE-2024-10924.svg) 
![forks](https://img.shields.io/github/forks/cy3erdr4g0n/CVE-2024-10924.svg) 
2025-02-05T12:21:49Z

- [https://github.com/sariamubeen/CVE-2024-10924](https://github.com/sariamubeen/CVE-2024-10924) :  
![starts](https://img.shields.io/github/stars/sariamubeen/CVE-2024-10924.svg) 
![forks](https://img.shields.io/github/forks/sariamubeen/CVE-2024-10924.svg) 
2025-02-17T01:55:39Z

- [https://github.com/Hunt3r850/CVE-2024-10924-Wordpress-Docker](https://github.com/Hunt3r850/CVE-2024-10924-Wordpress-Docker) :  
![starts](https://img.shields.io/github/stars/Hunt3r850/CVE-2024-10924-Wordpress-Docker.svg) 
![forks](https://img.shields.io/github/forks/Hunt3r850/CVE-2024-10924-Wordpress-Docker.svg) 
2024-12-03T13:14:06Z

- [https://github.com/MaleeshaUdan/wordpress-CVE-2024-10924--exploit](https://github.com/MaleeshaUdan/wordpress-CVE-2024-10924--exploit) :  
![starts](https://img.shields.io/github/stars/MaleeshaUdan/wordpress-CVE-2024-10924--exploit.svg) 
![forks](https://img.shields.io/github/forks/MaleeshaUdan/wordpress-CVE-2024-10924--exploit.svg) 
2025-02-23T08:50:53Z

- [https://github.com/Hunt3r850/CVE-2024-10924-PoC](https://github.com/Hunt3r850/CVE-2024-10924-PoC) :  
![starts](https://img.shields.io/github/stars/Hunt3r850/CVE-2024-10924-PoC.svg) 
![forks](https://img.shields.io/github/forks/Hunt3r850/CVE-2024-10924-PoC.svg) 
2024-12-03T13:10:44Z

## CVE-2024-1086
 A use-after-free vulnerability in the Linux kernel's netfilter: nf_tables component can be exploited to achieve local privilege escalation.The nft_verdict_init() function allows positive values as drop error within the hook verdict, and hence the nf_hook_slow() function can cause a double free vulnerability when NF_DROP is issued with a drop error which resembles NF_ACCEPT.We recommend upgrading past commit f342de4e2f33e0e39165d8639387aa6c19dff660.

- [https://github.com/Notselwyn/CVE-2024-1086](https://github.com/Notselwyn/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/Notselwyn/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/Notselwyn/CVE-2024-1086.svg) 
2024-04-17T16:09:54Z

- [https://github.com/andigandhi/bitpixie](https://github.com/andigandhi/bitpixie) :  
![starts](https://img.shields.io/github/stars/andigandhi/bitpixie.svg) 
![forks](https://img.shields.io/github/forks/andigandhi/bitpixie.svg) 
2025-02-23T20:51:49Z

- [https://github.com/LLfam/CVE-2024-1086](https://github.com/LLfam/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/LLfam/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/LLfam/CVE-2024-1086.svg) 
2024-12-16T17:38:23Z

- [https://github.com/Alicey0719/docker-POC_CVE-2024-1086](https://github.com/Alicey0719/docker-POC_CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/Alicey0719/docker-POC_CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/Alicey0719/docker-POC_CVE-2024-1086.svg) 
2024-05-19T06:51:46Z

- [https://github.com/kevcooper/CVE-2024-1086-checker](https://github.com/kevcooper/CVE-2024-1086-checker) :  
![starts](https://img.shields.io/github/stars/kevcooper/CVE-2024-1086-checker.svg) 
![forks](https://img.shields.io/github/forks/kevcooper/CVE-2024-1086-checker.svg) 
2024-06-10T17:13:07Z

- [https://github.com/feely666/CVE-2024-1086](https://github.com/feely666/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/feely666/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/feely666/CVE-2024-1086.svg) 
2024-06-10T15:25:12Z

- [https://github.com/CCIEVoice2009/CVE-2024-1086](https://github.com/CCIEVoice2009/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/CCIEVoice2009/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/CCIEVoice2009/CVE-2024-1086.svg) 
2024-04-30T16:13:00Z

- [https://github.com/xzx482/CVE-2024-1086](https://github.com/xzx482/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/xzx482/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/xzx482/CVE-2024-1086.svg) 
2024-07-04T10:54:20Z

## CVE-2021-27365
 An issue was discovered in the Linux kernel through 5.11.3. Certain iSCSI data structures do not have appropriate length constraints or checks, and can exceed the PAGE_SIZE value. An unprivileged user can send a Netlink message that is associated with iSCSI, and has a length up to the maximum length of a Netlink message.

- [https://github.com/coderzawad/Kernel-CVE-2021-27365-hotfix](https://github.com/coderzawad/Kernel-CVE-2021-27365-hotfix) :  
![starts](https://img.shields.io/github/stars/coderzawad/Kernel-CVE-2021-27365-hotfix.svg) 
![forks](https://img.shields.io/github/forks/coderzawad/Kernel-CVE-2021-27365-hotfix.svg) 
2025-02-23T04:49:35Z

## CVE-2021-4034
 A local privilege escalation vulnerability was found on polkit's pkexec utility. The pkexec application is a setuid tool designed to allow unprivileged users to run commands as privileged users according predefined policies. The current version of pkexec doesn't handle the calling parameters count correctly and ends trying to execute environment variables as commands. An attacker can leverage this by crafting environment variables in such a way it'll induce pkexec to execute arbitrary code. When successfully executed the attack can cause a local privilege escalation given unprivileged users administrative rights on the target machine.

- [https://github.com/berdav/CVE-2021-4034](https://github.com/berdav/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/berdav/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/berdav/CVE-2021-4034.svg) 
2022-06-08T04:00:28Z

- [https://github.com/jm33-m0/emp3r0r](https://github.com/jm33-m0/emp3r0r) :  
![starts](https://img.shields.io/github/stars/jm33-m0/emp3r0r.svg) 
![forks](https://img.shields.io/github/forks/jm33-m0/emp3r0r.svg) 
2025-02-23T11:55:34Z

- [https://github.com/ly4k/PwnKit](https://github.com/ly4k/PwnKit) :  
![starts](https://img.shields.io/github/stars/ly4k/PwnKit.svg) 
![forks](https://img.shields.io/github/forks/ly4k/PwnKit.svg) 
2022-06-21T14:52:05Z

- [https://github.com/arthepsy/CVE-2021-4034](https://github.com/arthepsy/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/arthepsy/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/arthepsy/CVE-2021-4034.svg) 
2023-05-04T19:24:39Z

- [https://github.com/Al1ex/LinuxEelvation](https://github.com/Al1ex/LinuxEelvation) :  
![starts](https://img.shields.io/github/stars/Al1ex/LinuxEelvation.svg) 
![forks](https://img.shields.io/github/forks/Al1ex/LinuxEelvation.svg) 
2022-07-29T09:34:03Z

- [https://github.com/PwnFunction/CVE-2021-4034](https://github.com/PwnFunction/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/PwnFunction/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/PwnFunction/CVE-2021-4034.svg) 
2023-01-12T19:23:29Z

- [https://github.com/joeammond/CVE-2021-4034](https://github.com/joeammond/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/joeammond/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/joeammond/CVE-2021-4034.svg) 
2022-01-28T00:29:15Z

- [https://github.com/dzonerzy/poc-cve-2021-4034](https://github.com/dzonerzy/poc-cve-2021-4034) :  
![starts](https://img.shields.io/github/stars/dzonerzy/poc-cve-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/dzonerzy/poc-cve-2021-4034.svg) 
2022-01-27T15:13:51Z

- [https://github.com/Rvn0xsy/CVE-2021-4034](https://github.com/Rvn0xsy/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Rvn0xsy/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Rvn0xsy/CVE-2021-4034.svg) 
2022-01-28T15:37:41Z

- [https://github.com/luijait/PwnKit-Exploit](https://github.com/luijait/PwnKit-Exploit) :  
![starts](https://img.shields.io/github/stars/luijait/PwnKit-Exploit.svg) 
![forks](https://img.shields.io/github/forks/luijait/PwnKit-Exploit.svg) 
2022-02-07T15:42:00Z

- [https://github.com/Ayrx/CVE-2021-4034](https://github.com/Ayrx/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Ayrx/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Ayrx/CVE-2021-4034.svg) 
2022-01-27T11:57:05Z

- [https://github.com/Nickguitar/YAPS](https://github.com/Nickguitar/YAPS) :  
![starts](https://img.shields.io/github/stars/Nickguitar/YAPS.svg) 
![forks](https://img.shields.io/github/forks/Nickguitar/YAPS.svg) 
2022-02-14T01:46:03Z

- [https://github.com/EstamelGG/CVE-2021-4034-NoGCC](https://github.com/EstamelGG/CVE-2021-4034-NoGCC) :  
![starts](https://img.shields.io/github/stars/EstamelGG/CVE-2021-4034-NoGCC.svg) 
![forks](https://img.shields.io/github/forks/EstamelGG/CVE-2021-4034-NoGCC.svg) 
2022-02-09T09:58:59Z

- [https://github.com/ryaagard/CVE-2021-4034](https://github.com/ryaagard/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/ryaagard/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/ryaagard/CVE-2021-4034.svg) 
2022-01-26T01:01:15Z

- [https://github.com/nikaiw/CVE-2021-4034](https://github.com/nikaiw/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/nikaiw/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/nikaiw/CVE-2021-4034.svg) 
2022-01-26T02:27:53Z

- [https://github.com/jm33-m0/go-lpe](https://github.com/jm33-m0/go-lpe) :  
![starts](https://img.shields.io/github/stars/jm33-m0/go-lpe.svg) 
![forks](https://img.shields.io/github/forks/jm33-m0/go-lpe.svg) 
2025-01-23T07:02:35Z

- [https://github.com/zhzyker/CVE-2021-4034](https://github.com/zhzyker/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/zhzyker/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/zhzyker/CVE-2021-4034.svg) 
2022-01-27T06:23:02Z

- [https://github.com/PeterGottesman/pwnkit-exploit](https://github.com/PeterGottesman/pwnkit-exploit) :  
![starts](https://img.shields.io/github/stars/PeterGottesman/pwnkit-exploit.svg) 
![forks](https://img.shields.io/github/forks/PeterGottesman/pwnkit-exploit.svg) 
2022-01-28T00:38:03Z

- [https://github.com/DanaEpp/pwncat_pwnkit](https://github.com/DanaEpp/pwncat_pwnkit) :  
![starts](https://img.shields.io/github/stars/DanaEpp/pwncat_pwnkit.svg) 
![forks](https://img.shields.io/github/forks/DanaEpp/pwncat_pwnkit.svg) 
2022-02-13T00:58:32Z

- [https://github.com/mebeim/CVE-2021-4034](https://github.com/mebeim/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/mebeim/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/mebeim/CVE-2021-4034.svg) 
2022-01-26T16:22:46Z

- [https://github.com/ck00004/CVE-2021-4034](https://github.com/ck00004/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/ck00004/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/ck00004/CVE-2021-4034.svg) 
2022-02-15T02:39:28Z

- [https://github.com/c3c/CVE-2021-4034](https://github.com/c3c/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/c3c/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/c3c/CVE-2021-4034.svg) 
2022-03-30T15:38:20Z

- [https://github.com/c3l3si4n/pwnkit](https://github.com/c3l3si4n/pwnkit) :  
![starts](https://img.shields.io/github/stars/c3l3si4n/pwnkit.svg) 
![forks](https://img.shields.io/github/forks/c3l3si4n/pwnkit.svg) 
2022-01-26T20:17:11Z

- [https://github.com/Almorabea/pkexec-exploit](https://github.com/Almorabea/pkexec-exploit) :  
![starts](https://img.shields.io/github/stars/Almorabea/pkexec-exploit.svg) 
![forks](https://img.shields.io/github/forks/Almorabea/pkexec-exploit.svg) 
2022-01-30T10:44:34Z

- [https://github.com/kimusan/pkwner](https://github.com/kimusan/pkwner) :  
![starts](https://img.shields.io/github/stars/kimusan/pkwner.svg) 
![forks](https://img.shields.io/github/forks/kimusan/pkwner.svg) 
2022-01-27T10:40:14Z

- [https://github.com/evdenis/lsm_bpf_check_argc0](https://github.com/evdenis/lsm_bpf_check_argc0) :  
![starts](https://img.shields.io/github/stars/evdenis/lsm_bpf_check_argc0.svg) 
![forks](https://img.shields.io/github/forks/evdenis/lsm_bpf_check_argc0.svg) 
2022-02-17T16:46:44Z

- [https://github.com/dadvlingd/CVE-2021-4034](https://github.com/dadvlingd/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/dadvlingd/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/dadvlingd/CVE-2021-4034.svg) 
2023-02-19T13:01:42Z

- [https://github.com/NeonWhiteRabbit/CVE-2021-4034](https://github.com/NeonWhiteRabbit/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/NeonWhiteRabbit/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/NeonWhiteRabbit/CVE-2021-4034.svg) 
2022-01-28T18:22:53Z

- [https://github.com/JohnHammond/CVE-2021-4034](https://github.com/JohnHammond/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/JohnHammond/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/JohnHammond/CVE-2021-4034.svg) 
2022-01-26T01:05:56Z

- [https://github.com/chenaotian/CVE-2021-4034](https://github.com/chenaotian/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/chenaotian/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/chenaotian/CVE-2021-4034.svg) 
2022-05-23T02:03:43Z

- [https://github.com/An00bRektn/CVE-2021-4034](https://github.com/An00bRektn/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/An00bRektn/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/An00bRektn/CVE-2021-4034.svg) 
2022-01-27T16:12:20Z

- [https://github.com/wudicainiao/cve-2021-4034](https://github.com/wudicainiao/cve-2021-4034) :  
![starts](https://img.shields.io/github/stars/wudicainiao/cve-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/wudicainiao/cve-2021-4034.svg) 
2022-05-31T11:56:20Z

- [https://github.com/drapl0n/pwnKit](https://github.com/drapl0n/pwnKit) :  
![starts](https://img.shields.io/github/stars/drapl0n/pwnKit.svg) 
![forks](https://img.shields.io/github/forks/drapl0n/pwnKit.svg) 
2022-02-08T04:57:32Z

- [https://github.com/Audiobahn/CVE-2021-4034](https://github.com/Audiobahn/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Audiobahn/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Audiobahn/CVE-2021-4034.svg) 
2022-01-26T01:34:11Z

- [https://github.com/OXDBXKXO/ez-pwnkit](https://github.com/OXDBXKXO/ez-pwnkit) :  
![starts](https://img.shields.io/github/stars/OXDBXKXO/ez-pwnkit.svg) 
![forks](https://img.shields.io/github/forks/OXDBXKXO/ez-pwnkit.svg) 
2022-02-23T21:54:41Z

- [https://github.com/sofire/polkit-0.96-CVE-2021-4034](https://github.com/sofire/polkit-0.96-CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/sofire/polkit-0.96-CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/sofire/polkit-0.96-CVE-2021-4034.svg) 
2022-01-29T08:09:07Z

- [https://github.com/rvizx/CVE-2021-4034](https://github.com/rvizx/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/rvizx/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/rvizx/CVE-2021-4034.svg) 
2022-07-19T12:52:30Z

- [https://github.com/Kirill89/CVE-2021-4034](https://github.com/Kirill89/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Kirill89/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Kirill89/CVE-2021-4034.svg) 
2022-01-28T15:17:47Z

- [https://github.com/clubby789/CVE-2021-4034](https://github.com/clubby789/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/clubby789/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/clubby789/CVE-2021-4034.svg) 
2022-01-26T01:26:26Z

- [https://github.com/jpmcb/pwnkit-go](https://github.com/jpmcb/pwnkit-go) :  
![starts](https://img.shields.io/github/stars/jpmcb/pwnkit-go.svg) 
![forks](https://img.shields.io/github/forks/jpmcb/pwnkit-go.svg) 
2022-01-28T16:23:20Z

- [https://github.com/Yakumwamba/POC-CVE-2021-4034](https://github.com/Yakumwamba/POC-CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Yakumwamba/POC-CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Yakumwamba/POC-CVE-2021-4034.svg) 
2022-01-28T16:10:39Z

- [https://github.com/navisec/CVE-2021-4034-PwnKit](https://github.com/navisec/CVE-2021-4034-PwnKit) :  
![starts](https://img.shields.io/github/stars/navisec/CVE-2021-4034-PwnKit.svg) 
![forks](https://img.shields.io/github/forks/navisec/CVE-2021-4034-PwnKit.svg) 
2022-01-30T04:48:57Z

- [https://github.com/Y3A/CVE-2021-4034](https://github.com/Y3A/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Y3A/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Y3A/CVE-2021-4034.svg) 
2023-07-20T08:59:30Z

- [https://github.com/Al1ex/CVE-2021-4034](https://github.com/Al1ex/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Al1ex/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Al1ex/CVE-2021-4034.svg) 
2022-01-27T02:27:41Z

- [https://github.com/callrbx/pkexec-lpe-poc](https://github.com/callrbx/pkexec-lpe-poc) :  
![starts](https://img.shields.io/github/stars/callrbx/pkexec-lpe-poc.svg) 
![forks](https://img.shields.io/github/forks/callrbx/pkexec-lpe-poc.svg) 
2022-01-28T16:58:49Z

- [https://github.com/TheJoyOfHacking/berdav-CVE-2021-4034](https://github.com/TheJoyOfHacking/berdav-CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/TheJoyOfHacking/berdav-CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/TheJoyOfHacking/berdav-CVE-2021-4034.svg) 
2022-03-23T11:08:33Z

- [https://github.com/tahaafarooq/poppy](https://github.com/tahaafarooq/poppy) :  
![starts](https://img.shields.io/github/stars/tahaafarooq/poppy.svg) 
![forks](https://img.shields.io/github/forks/tahaafarooq/poppy.svg) 
2022-12-20T09:03:26Z

- [https://github.com/FDlucifer/Pwnkit-go](https://github.com/FDlucifer/Pwnkit-go) :  
![starts](https://img.shields.io/github/stars/FDlucifer/Pwnkit-go.svg) 
![forks](https://img.shields.io/github/forks/FDlucifer/Pwnkit-go.svg) 
2022-02-08T03:24:51Z

- [https://github.com/artemis-mike/cve-2021-4034](https://github.com/artemis-mike/cve-2021-4034) :  
![starts](https://img.shields.io/github/stars/artemis-mike/cve-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/artemis-mike/cve-2021-4034.svg) 
2024-04-27T19:02:19Z

- [https://github.com/x04000/CVE-2021-4034](https://github.com/x04000/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/x04000/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/x04000/CVE-2021-4034.svg) 
2022-02-16T19:12:53Z

- [https://github.com/whokilleddb/CVE-2021-4034](https://github.com/whokilleddb/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/whokilleddb/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/whokilleddb/CVE-2021-4034.svg) 
2022-01-27T19:58:45Z

- [https://github.com/codiobert/pwnkit-scanner](https://github.com/codiobert/pwnkit-scanner) :  
![starts](https://img.shields.io/github/stars/codiobert/pwnkit-scanner.svg) 
![forks](https://img.shields.io/github/forks/codiobert/pwnkit-scanner.svg) 
2022-01-30T16:50:08Z

- [https://github.com/gbrsh/CVE-2021-4034](https://github.com/gbrsh/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/gbrsh/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/gbrsh/CVE-2021-4034.svg) 
2022-01-26T00:57:04Z

- [https://github.com/Pixailz/CVE-2021-4034](https://github.com/Pixailz/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Pixailz/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Pixailz/CVE-2021-4034.svg) 
2022-10-11T00:40:47Z

- [https://github.com/Anonymous-Family/CVE-2021-4034](https://github.com/Anonymous-Family/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Anonymous-Family/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Anonymous-Family/CVE-2021-4034.svg) 
2022-01-26T19:31:04Z

- [https://github.com/locksec/CVE-2021-4034](https://github.com/locksec/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/locksec/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/locksec/CVE-2021-4034.svg) 
2022-01-27T16:53:17Z

- [https://github.com/LJP-TW/CVE-2021-4034](https://github.com/LJP-TW/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/LJP-TW/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/LJP-TW/CVE-2021-4034.svg) 
2022-02-18T07:31:30Z

- [https://github.com/deoxykev/CVE-2021-4034-Rust](https://github.com/deoxykev/CVE-2021-4034-Rust) :  
![starts](https://img.shields.io/github/stars/deoxykev/CVE-2021-4034-Rust.svg) 
![forks](https://img.shields.io/github/forks/deoxykev/CVE-2021-4034-Rust.svg) 
2022-02-03T05:17:52Z

- [https://github.com/wechicken456/CVE-2021-4034-CTF-writeup](https://github.com/wechicken456/CVE-2021-4034-CTF-writeup) :  
![starts](https://img.shields.io/github/stars/wechicken456/CVE-2021-4034-CTF-writeup.svg) 
![forks](https://img.shields.io/github/forks/wechicken456/CVE-2021-4034-CTF-writeup.svg) 
2024-05-20T18:33:14Z

- [https://github.com/x04000/AutoPwnkit](https://github.com/x04000/AutoPwnkit) :  
![starts](https://img.shields.io/github/stars/x04000/AutoPwnkit.svg) 
![forks](https://img.shields.io/github/forks/x04000/AutoPwnkit.svg) 
2022-02-13T15:04:06Z

- [https://github.com/hohn/codeql-sample-polkit](https://github.com/hohn/codeql-sample-polkit) :  
![starts](https://img.shields.io/github/stars/hohn/codeql-sample-polkit.svg) 
![forks](https://img.shields.io/github/forks/hohn/codeql-sample-polkit.svg) 
2022-03-15T18:42:24Z

- [https://github.com/Nosferatuvjr/PwnKit](https://github.com/Nosferatuvjr/PwnKit) :  
![starts](https://img.shields.io/github/stars/Nosferatuvjr/PwnKit.svg) 
![forks](https://img.shields.io/github/forks/Nosferatuvjr/PwnKit.svg) 
2022-05-27T19:17:56Z

- [https://github.com/mutur4/Hacking-Scripts](https://github.com/mutur4/Hacking-Scripts) :  
![starts](https://img.shields.io/github/stars/mutur4/Hacking-Scripts.svg) 
![forks](https://img.shields.io/github/forks/mutur4/Hacking-Scripts.svg) 
2023-01-29T19:39:29Z

- [https://github.com/NiS3x/CVE-2021-4034](https://github.com/NiS3x/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/NiS3x/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/NiS3x/CVE-2021-4034.svg) 
2022-01-27T08:40:56Z

- [https://github.com/battleoverflow/CVE-2021-4034](https://github.com/battleoverflow/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/battleoverflow/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/battleoverflow/CVE-2021-4034.svg) 
2024-04-15T05:58:36Z

- [https://github.com/oreosec/pwnkit](https://github.com/oreosec/pwnkit) :  
![starts](https://img.shields.io/github/stars/oreosec/pwnkit.svg) 
![forks](https://img.shields.io/github/forks/oreosec/pwnkit.svg) 
2022-01-28T13:59:31Z

- [https://github.com/moldabekov/CVE-2021-4034](https://github.com/moldabekov/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/moldabekov/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/moldabekov/CVE-2021-4034.svg) 
2022-01-26T11:17:37Z

- [https://github.com/JoyGhoshs/CVE-2021-4034](https://github.com/JoyGhoshs/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/JoyGhoshs/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/JoyGhoshs/CVE-2021-4034.svg) 
2022-01-28T08:12:27Z

- [https://github.com/Immersive-Labs-Sec/CVE-2021-4034](https://github.com/Immersive-Labs-Sec/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Immersive-Labs-Sec/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Immersive-Labs-Sec/CVE-2021-4034.svg) 
2022-01-26T09:37:18Z

- [https://github.com/ayypril/CVE-2021-4034](https://github.com/ayypril/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/ayypril/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/ayypril/CVE-2021-4034.svg) 
2022-01-26T05:42:42Z

- [https://github.com/A1vinSmith/CVE-2021-4034](https://github.com/A1vinSmith/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/A1vinSmith/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/A1vinSmith/CVE-2021-4034.svg) 
2022-11-02T22:24:11Z

- [https://github.com/0x01-sec/CVE-2021-4034-](https://github.com/0x01-sec/CVE-2021-4034-) :  
![starts](https://img.shields.io/github/stars/0x01-sec/CVE-2021-4034-.svg) 
![forks](https://img.shields.io/github/forks/0x01-sec/CVE-2021-4034-.svg) 
2022-01-29T23:29:48Z

- [https://github.com/mutur4/CVE-2021-4034](https://github.com/mutur4/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/mutur4/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/mutur4/CVE-2021-4034.svg) 
2024-04-10T14:48:27Z

- [https://github.com/defhacks/cve-2021-4034](https://github.com/defhacks/cve-2021-4034) :  
![starts](https://img.shields.io/github/stars/defhacks/cve-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/defhacks/cve-2021-4034.svg) 
2022-03-04T05:32:29Z

- [https://github.com/thatstraw/CVE-2021-4034](https://github.com/thatstraw/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/thatstraw/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/thatstraw/CVE-2021-4034.svg) 
2022-01-27T10:27:15Z

- [https://github.com/vilasboasph/CVE-2021-4034](https://github.com/vilasboasph/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/vilasboasph/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/vilasboasph/CVE-2021-4034.svg) 
2022-01-26T19:46:54Z

- [https://github.com/HrishitJoshi/CVE-2021-4034](https://github.com/HrishitJoshi/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/HrishitJoshi/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/HrishitJoshi/CVE-2021-4034.svg) 
2022-02-02T05:37:20Z

- [https://github.com/cd80-ctf/CVE-2021-4034](https://github.com/cd80-ctf/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/cd80-ctf/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/cd80-ctf/CVE-2021-4034.svg) 
2022-01-27T01:23:02Z

- [https://github.com/LukeGix/CVE-2021-4034](https://github.com/LukeGix/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/LukeGix/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/LukeGix/CVE-2021-4034.svg) 
2022-01-26T12:28:31Z

- [https://github.com/Tanmay-N/CVE-2021-4034](https://github.com/Tanmay-N/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Tanmay-N/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Tanmay-N/CVE-2021-4034.svg) 
2022-02-21T17:06:58Z

- [https://github.com/wongwaituck/CVE-2021-4034](https://github.com/wongwaituck/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/wongwaituck/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/wongwaituck/CVE-2021-4034.svg) 
2022-01-26T05:46:34Z

- [https://github.com/hahaleyile/CVE-2021-4034](https://github.com/hahaleyile/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/hahaleyile/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/hahaleyile/CVE-2021-4034.svg) 
2022-02-25T01:30:55Z

- [https://github.com/jehovah2002/CVE-2021-4034-pwnkit](https://github.com/jehovah2002/CVE-2021-4034-pwnkit) :  
![starts](https://img.shields.io/github/stars/jehovah2002/CVE-2021-4034-pwnkit.svg) 
![forks](https://img.shields.io/github/forks/jehovah2002/CVE-2021-4034-pwnkit.svg) 
2022-10-30T18:24:39Z

- [https://github.com/fnknda/CVE-2021-4034_POC](https://github.com/fnknda/CVE-2021-4034_POC) :  
![starts](https://img.shields.io/github/stars/fnknda/CVE-2021-4034_POC.svg) 
![forks](https://img.shields.io/github/forks/fnknda/CVE-2021-4034_POC.svg) 
2022-02-20T17:52:36Z

- [https://github.com/CYB3RK1D/CVE-2021-4034-POC](https://github.com/CYB3RK1D/CVE-2021-4034-POC) :  
![starts](https://img.shields.io/github/stars/CYB3RK1D/CVE-2021-4034-POC.svg) 
![forks](https://img.shields.io/github/forks/CYB3RK1D/CVE-2021-4034-POC.svg) 
2022-04-08T17:26:41Z

- [https://github.com/cdxiaodong/CVE-2021-4034-touch](https://github.com/cdxiaodong/CVE-2021-4034-touch) :  
![starts](https://img.shields.io/github/stars/cdxiaodong/CVE-2021-4034-touch.svg) 
![forks](https://img.shields.io/github/forks/cdxiaodong/CVE-2021-4034-touch.svg) 
2024-01-04T07:43:23Z

- [https://github.com/0xalwayslucky/log4j-polkit-poc](https://github.com/0xalwayslucky/log4j-polkit-poc) :  
![starts](https://img.shields.io/github/stars/0xalwayslucky/log4j-polkit-poc.svg) 
![forks](https://img.shields.io/github/forks/0xalwayslucky/log4j-polkit-poc.svg) 
2022-01-28T15:08:53Z

- [https://github.com/jcatala/f_poc_cve-2021-4034](https://github.com/jcatala/f_poc_cve-2021-4034) :  
![starts](https://img.shields.io/github/stars/jcatala/f_poc_cve-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/jcatala/f_poc_cve-2021-4034.svg) 
2022-03-30T21:12:43Z

- [https://github.com/xcanwin/CVE-2021-4034-UniontechOS](https://github.com/xcanwin/CVE-2021-4034-UniontechOS) :  
![starts](https://img.shields.io/github/stars/xcanwin/CVE-2021-4034-UniontechOS.svg) 
![forks](https://img.shields.io/github/forks/xcanwin/CVE-2021-4034-UniontechOS.svg) 
2022-05-27T18:41:40Z

- [https://github.com/NeonWhiteRabbit/CVE-2021-4034-BASH-One-File-Exploit](https://github.com/NeonWhiteRabbit/CVE-2021-4034-BASH-One-File-Exploit) :  
![starts](https://img.shields.io/github/stars/NeonWhiteRabbit/CVE-2021-4034-BASH-One-File-Exploit.svg) 
![forks](https://img.shields.io/github/forks/NeonWhiteRabbit/CVE-2021-4034-BASH-One-File-Exploit.svg) 
2022-01-28T21:07:04Z

- [https://github.com/Fato07/Pwnkit-exploit](https://github.com/Fato07/Pwnkit-exploit) :  
![starts](https://img.shields.io/github/stars/Fato07/Pwnkit-exploit.svg) 
![forks](https://img.shields.io/github/forks/Fato07/Pwnkit-exploit.svg) 
2022-01-27T18:32:33Z

- [https://github.com/nobelh/CVE-2021-4034](https://github.com/nobelh/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/nobelh/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/nobelh/CVE-2021-4034.svg) 
2022-03-03T21:20:09Z

# 2025-02-22
## CVE-2025-26794
 Exim 4.98 before 4.98.1, when SQLite hints and ETRN serialization are used, allows remote SQL injection.

- [https://github.com/OscarBataille/CVE-2025-26794](https://github.com/OscarBataille/CVE-2025-26794) :  
![starts](https://img.shields.io/github/stars/OscarBataille/CVE-2025-26794.svg) 
![forks](https://img.shields.io/github/forks/OscarBataille/CVE-2025-26794.svg) 
2025-02-22T14:37:36Z

## CVE-2025-25460
 A stored Cross-Site Scripting (XSS) vulnerability was identified in FlatPress 1.3.1 within the "Add Entry" feature. This vulnerability allows authenticated attackers to inject malicious JavaScript payloads into blog posts, which are executed when other users view the posts. The issue arises due to improper input sanitization of the "TextArea" field in the blog entry submission form.

- [https://github.com/RoNiXxCybSeC0101/CVE-2025-25460](https://github.com/RoNiXxCybSeC0101/CVE-2025-25460) :  
![starts](https://img.shields.io/github/stars/RoNiXxCybSeC0101/CVE-2025-25460.svg) 
![forks](https://img.shields.io/github/forks/RoNiXxCybSeC0101/CVE-2025-25460.svg) 
2025-02-22T04:17:05Z

## CVE-2024-56199
 phpMyFAQ is an open source FAQ web application. Starting no later than version 3.2.10 and prior to version 4.0.2, an attacker can inject malicious HTML content into the FAQ editor at `http[:]//localhost/admin/index[.]php?action=editentry`, resulting in a complete disruption of the FAQ page's user interface. By injecting malformed HTML elements styled to cover the entire screen, an attacker can render the page unusable. This injection manipulates the page structure by introducing overlapping buttons, images, and iframes, breaking the intended layout and functionality. Exploiting this issue can lead to Denial of Service for legitimate users, damage to the user experience, and potential abuse in phishing or defacement attacks. Version 4.0.2 contains a patch for the vulnerability.

- [https://github.com/geo-chen/phpMyFAQ](https://github.com/geo-chen/phpMyFAQ) :  
![starts](https://img.shields.io/github/stars/geo-chen/phpMyFAQ.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/phpMyFAQ.svg) 
2025-02-22T06:04:52Z

## CVE-2024-55889
 phpMyFAQ is an open source FAQ web application. Prior to version 3.2.10, a vulnerability exists in the FAQ Record component where a privileged attacker can trigger a file download on a victim's machine upon page visit by embedding it in an iframe element without user interaction or explicit consent. Version 3.2.10 fixes the issue.

- [https://github.com/geo-chen/phpMyFAQ](https://github.com/geo-chen/phpMyFAQ) :  
![starts](https://img.shields.io/github/stars/geo-chen/phpMyFAQ.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/phpMyFAQ.svg) 
2025-02-22T06:04:52Z

## CVE-2024-54820
 XOne Web Monitor v02.10.2024.530 framework 1.0.4.9 was discovered to contain a SQL injection vulnerability in the login page. This vulnerability allows attackers to extract all usernames and passwords via a crafted input.

- [https://github.com/jcarabantes/CVE-2024-54820](https://github.com/jcarabantes/CVE-2024-54820) :  
![starts](https://img.shields.io/github/stars/jcarabantes/CVE-2024-54820.svg) 
![forks](https://img.shields.io/github/forks/jcarabantes/CVE-2024-54820.svg) 
2025-02-22T20:29:16Z

## CVE-2024-54141
 phpMyFAQ is an open source FAQ web application for PHP 8.1+ and MySQL, PostgreSQL and other databases. Prior to 4.0.0, phpMyFAQ exposes the database (ie postgreSQL) server's credential when connection to DB fails. This vulnerability is fixed in 4.0.0.

- [https://github.com/geo-chen/phpMyFAQ](https://github.com/geo-chen/phpMyFAQ) :  
![starts](https://img.shields.io/github/stars/geo-chen/phpMyFAQ.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/phpMyFAQ.svg) 
2025-02-22T06:04:52Z

## CVE-2024-34102
 Adobe Commerce versions 2.4.7, 2.4.6-p5, 2.4.5-p7, 2.4.4-p8 and earlier are affected by an Improper Restriction of XML External Entity Reference ('XXE') vulnerability that could result in arbitrary code execution. An attacker could exploit this vulnerability by sending a crafted XML document that references external entities. Exploitation of this issue does not require user interaction.

- [https://github.com/Chocapikk/CVE-2024-34102](https://github.com/Chocapikk/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-34102.svg) 
2024-09-05T18:38:46Z

- [https://github.com/bigb0x/CVE-2024-34102](https://github.com/bigb0x/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/bigb0x/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/bigb0x/CVE-2024-34102.svg) 
2024-06-29T08:13:05Z

- [https://github.com/th3gokul/CVE-2024-34102](https://github.com/th3gokul/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/th3gokul/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/th3gokul/CVE-2024-34102.svg) 
2025-01-12T15:27:05Z

- [https://github.com/jakabakos/CVE-2024-34102-CosmicSting-XXE-in-Adobe-Commerce-and-Magento](https://github.com/jakabakos/CVE-2024-34102-CosmicSting-XXE-in-Adobe-Commerce-and-Magento) :  
![starts](https://img.shields.io/github/stars/jakabakos/CVE-2024-34102-CosmicSting-XXE-in-Adobe-Commerce-and-Magento.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/CVE-2024-34102-CosmicSting-XXE-in-Adobe-Commerce-and-Magento.svg) 
2024-07-05T09:26:02Z

- [https://github.com/bughuntar/CVE-2024-34102](https://github.com/bughuntar/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/bughuntar/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/bughuntar/CVE-2024-34102.svg) 
2024-07-15T04:16:03Z

- [https://github.com/EQSTLab/CVE-2024-34102](https://github.com/EQSTLab/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/EQSTLab/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/EQSTLab/CVE-2024-34102.svg) 
2025-01-12T11:26:54Z

- [https://github.com/0x0d3ad/CVE-2024-34102](https://github.com/0x0d3ad/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/0x0d3ad/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/0x0d3ad/CVE-2024-34102.svg) 
2024-07-01T17:42:30Z

- [https://github.com/11whoami99/CVE-2024-34102](https://github.com/11whoami99/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/11whoami99/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/11whoami99/CVE-2024-34102.svg) 
2024-07-01T03:20:14Z

- [https://github.com/Phantom-IN/CVE-2024-34102](https://github.com/Phantom-IN/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/Phantom-IN/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/Phantom-IN/CVE-2024-34102.svg) 
2024-07-14T08:42:46Z

- [https://github.com/wubinworks/magento2-cosmic-sting-patch](https://github.com/wubinworks/magento2-cosmic-sting-patch) :  
![starts](https://img.shields.io/github/stars/wubinworks/magento2-cosmic-sting-patch.svg) 
![forks](https://img.shields.io/github/forks/wubinworks/magento2-cosmic-sting-patch.svg) 
2025-02-06T15:59:22Z

- [https://github.com/wubinworks/magento2-jwt-auth-patch](https://github.com/wubinworks/magento2-jwt-auth-patch) :  
![starts](https://img.shields.io/github/stars/wubinworks/magento2-jwt-auth-patch.svg) 
![forks](https://img.shields.io/github/forks/wubinworks/magento2-jwt-auth-patch.svg) 
2024-12-10T05:45:31Z

- [https://github.com/unknownzerobit/poc](https://github.com/unknownzerobit/poc) :  
![starts](https://img.shields.io/github/stars/unknownzerobit/poc.svg) 
![forks](https://img.shields.io/github/forks/unknownzerobit/poc.svg) 
2024-07-08T11:41:53Z

- [https://github.com/mksundaram69/CVE-2024-34102](https://github.com/mksundaram69/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/mksundaram69/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/mksundaram69/CVE-2024-34102.svg) 
2025-01-07T16:47:50Z

- [https://github.com/d0rb/CVE-2024-34102](https://github.com/d0rb/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/d0rb/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/d0rb/CVE-2024-34102.svg) 
2024-06-28T14:52:41Z

- [https://github.com/crynomore/CVE-2024-34102](https://github.com/crynomore/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/crynomore/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/crynomore/CVE-2024-34102.svg) 
2024-07-11T11:54:40Z

- [https://github.com/cmsec423/CVE-2024-34102](https://github.com/cmsec423/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/cmsec423/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/cmsec423/CVE-2024-34102.svg) 
2024-07-01T05:06:42Z

- [https://github.com/dream434/CVE-2024-34102](https://github.com/dream434/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-34102.svg) 
2025-02-22T19:38:04Z

- [https://github.com/ArturArz1/TestCVE-2024-34102](https://github.com/ArturArz1/TestCVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/ArturArz1/TestCVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/ArturArz1/TestCVE-2024-34102.svg) 
2024-06-27T17:07:29Z

- [https://github.com/bughuntar/CVE-2024-34102-Python](https://github.com/bughuntar/CVE-2024-34102-Python) :  
![starts](https://img.shields.io/github/stars/bughuntar/CVE-2024-34102-Python.svg) 
![forks](https://img.shields.io/github/forks/bughuntar/CVE-2024-34102-Python.svg) 
2024-07-15T04:16:35Z

- [https://github.com/cmsec423/Magento-XXE-CVE-2024-34102](https://github.com/cmsec423/Magento-XXE-CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/cmsec423/Magento-XXE-CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/cmsec423/Magento-XXE-CVE-2024-34102.svg) 
2024-07-01T05:08:37Z

- [https://github.com/SamJUK/cosmicsting-validator](https://github.com/SamJUK/cosmicsting-validator) :  
![starts](https://img.shields.io/github/stars/SamJUK/cosmicsting-validator.svg) 
![forks](https://img.shields.io/github/forks/SamJUK/cosmicsting-validator.svg) 
2025-02-14T17:37:41Z

- [https://github.com/bka/magento-cve-2024-34102-exploit-cosmicstring](https://github.com/bka/magento-cve-2024-34102-exploit-cosmicstring) :  
![starts](https://img.shields.io/github/stars/bka/magento-cve-2024-34102-exploit-cosmicstring.svg) 
![forks](https://img.shields.io/github/forks/bka/magento-cve-2024-34102-exploit-cosmicstring.svg) 
2024-10-09T12:33:37Z

- [https://github.com/wubinworks/magento2-encryption-key-manager-cli](https://github.com/wubinworks/magento2-encryption-key-manager-cli) :  
![starts](https://img.shields.io/github/stars/wubinworks/magento2-encryption-key-manager-cli.svg) 
![forks](https://img.shields.io/github/forks/wubinworks/magento2-encryption-key-manager-cli.svg) 
2024-12-04T15:47:48Z

- [https://github.com/wubinworks/magento2-enhanced-xml-security](https://github.com/wubinworks/magento2-enhanced-xml-security) :  
![starts](https://img.shields.io/github/stars/wubinworks/magento2-enhanced-xml-security.svg) 
![forks](https://img.shields.io/github/forks/wubinworks/magento2-enhanced-xml-security.svg) 
2025-01-15T03:33:35Z

## CVE-2024-31819
 An issue in WWBN AVideo v.12.4 through v.14.2 allows a remote attacker to execute arbitrary code via the systemRootPath parameter of the submitIndex.php component.

- [https://github.com/Chocapikk/CVE-2024-31819](https://github.com/Chocapikk/CVE-2024-31819) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-31819.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-31819.svg) 
2024-04-11T20:51:33Z

- [https://github.com/dream434/CVE-2024-31819](https://github.com/dream434/CVE-2024-31819) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-31819.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-31819.svg) 
2025-02-22T19:42:04Z

## CVE-2024-29269
 An issue discovered in Telesquare TLR-2005Ksh 1.0.0 and 1.1.4 allows attackers to run arbitrary system commands via the Cmd parameter.

- [https://github.com/Chocapikk/CVE-2024-29269](https://github.com/Chocapikk/CVE-2024-29269) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-29269.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-29269.svg) 
2024-05-19T19:12:32Z

- [https://github.com/K3ysTr0K3R/CVE-2024-29269-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-29269-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-29269-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-29269-EXPLOIT.svg) 
2024-07-02T00:00:59Z

- [https://github.com/wutalent/CVE-2024-29269](https://github.com/wutalent/CVE-2024-29269) :  
![starts](https://img.shields.io/github/stars/wutalent/CVE-2024-29269.svg) 
![forks](https://img.shields.io/github/forks/wutalent/CVE-2024-29269.svg) 
2024-04-03T02:19:52Z

- [https://github.com/hack-with-rohit/CVE-2024-29269-RCE](https://github.com/hack-with-rohit/CVE-2024-29269-RCE) :  
![starts](https://img.shields.io/github/stars/hack-with-rohit/CVE-2024-29269-RCE.svg) 
![forks](https://img.shields.io/github/forks/hack-with-rohit/CVE-2024-29269-RCE.svg) 
2024-09-08T09:24:25Z

- [https://github.com/YongYe-Security/CVE-2024-29269](https://github.com/YongYe-Security/CVE-2024-29269) :  
![starts](https://img.shields.io/github/stars/YongYe-Security/CVE-2024-29269.svg) 
![forks](https://img.shields.io/github/forks/YongYe-Security/CVE-2024-29269.svg) 
2024-04-12T07:58:16Z

- [https://github.com/Quantum-Hacker/CVE-2024-29269](https://github.com/Quantum-Hacker/CVE-2024-29269) :  
![starts](https://img.shields.io/github/stars/Quantum-Hacker/CVE-2024-29269.svg) 
![forks](https://img.shields.io/github/forks/Quantum-Hacker/CVE-2024-29269.svg) 
2024-09-28T18:22:20Z

- [https://github.com/dream434/CVE-2024-29269](https://github.com/dream434/CVE-2024-29269) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-29269.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-29269.svg) 
2025-02-22T19:33:03Z

## CVE-2024-13209
 A vulnerability was found in Redaxo CMS 5.18.1. It has been classified as problematic. Affected is an unknown function of the file /index.php?page=structure&category_id=1&article_id=1&clang=1&function=edit_art&artstart=0 of the component Structure Management Page. The manipulation of the argument Article Name leads to cross site scripting. It is possible to launch the attack remotely. The exploit has been disclosed to the public and may be used. The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/geo-chen/Redaxo](https://github.com/geo-chen/Redaxo) :  
![starts](https://img.shields.io/github/stars/geo-chen/Redaxo.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/Redaxo.svg) 
2025-02-22T06:12:01Z

## CVE-2024-12884
 A vulnerability was found in Codezips E-Commerce Website 1.0. It has been rated as critical. Affected by this issue is some unknown functionality of the file /login.php. The manipulation of the argument email leads to sql injection. The attack may be launched remotely. The exploit has been disclosed to the public and may be used.

- [https://github.com/geo-chen/E-Commerce](https://github.com/geo-chen/E-Commerce) :  
![starts](https://img.shields.io/github/stars/geo-chen/E-Commerce.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/E-Commerce.svg) 
2025-02-22T06:12:58Z

## CVE-2023-27372
 SPIP before 4.2.1 allows Remote Code Execution via form values in the public area because serialization is mishandled. The fixed versions are 3.2.18, 4.0.10, 4.1.8, and 4.2.1.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/nuts7/CVE-2023-27372](https://github.com/nuts7/CVE-2023-27372) :  
![starts](https://img.shields.io/github/stars/nuts7/CVE-2023-27372.svg) 
![forks](https://img.shields.io/github/forks/nuts7/CVE-2023-27372.svg) 
2024-10-13T21:08:54Z

- [https://github.com/Chocapikk/CVE-2023-27372](https://github.com/Chocapikk/CVE-2023-27372) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2023-27372.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2023-27372.svg) 
2023-09-16T23:13:58Z

- [https://github.com/0SPwn/CVE-2023-27372-PoC](https://github.com/0SPwn/CVE-2023-27372-PoC) :  
![starts](https://img.shields.io/github/stars/0SPwn/CVE-2023-27372-PoC.svg) 
![forks](https://img.shields.io/github/forks/0SPwn/CVE-2023-27372-PoC.svg) 
2023-07-05T14:42:24Z

- [https://github.com/ThatNotEasy/CVE-2023-27372](https://github.com/ThatNotEasy/CVE-2023-27372) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2023-27372.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2023-27372.svg) 
2023-07-31T20:54:36Z

- [https://github.com/izzz0/CVE-2023-27372-POC](https://github.com/izzz0/CVE-2023-27372-POC) :  
![starts](https://img.shields.io/github/stars/izzz0/CVE-2023-27372-POC.svg) 
![forks](https://img.shields.io/github/forks/izzz0/CVE-2023-27372-POC.svg) 
2023-07-12T05:14:11Z

- [https://github.com/1amthebest1/CVE-2023-27372](https://github.com/1amthebest1/CVE-2023-27372) :  
![starts](https://img.shields.io/github/stars/1amthebest1/CVE-2023-27372.svg) 
![forks](https://img.shields.io/github/forks/1amthebest1/CVE-2023-27372.svg) 
2024-08-15T20:39:38Z

- [https://github.com/dream434/CVE-2023-27372](https://github.com/dream434/CVE-2023-27372) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2023-27372.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2023-27372.svg) 
2025-02-22T19:26:22Z

- [https://github.com/redboltsec/CVE-2023-27372-PoC](https://github.com/redboltsec/CVE-2023-27372-PoC) :  
![starts](https://img.shields.io/github/stars/redboltsec/CVE-2023-27372-PoC.svg) 
![forks](https://img.shields.io/github/forks/redboltsec/CVE-2023-27372-PoC.svg) 
2023-09-07T16:20:46Z

## CVE-2023-21563
 BitLocker Security Feature Bypass Vulnerability

- [https://github.com/Wack0/bitlocker-attacks](https://github.com/Wack0/bitlocker-attacks) :  
![starts](https://img.shields.io/github/stars/Wack0/bitlocker-attacks.svg) 
![forks](https://img.shields.io/github/forks/Wack0/bitlocker-attacks.svg) 
2025-02-14T14:42:48Z

- [https://github.com/andigandhi/bitpixie](https://github.com/andigandhi/bitpixie) :  
![starts](https://img.shields.io/github/stars/andigandhi/bitpixie.svg) 
![forks](https://img.shields.io/github/forks/andigandhi/bitpixie.svg) 
2025-02-22T11:06:50Z

## CVE-2023-1698
 In multiple products of WAGO a vulnerability allows an unauthenticated, remote attacker to create new users and change the device configuration which can result in unintended behaviour, Denial of Service and full system compromise.

- [https://github.com/codeb0ss/CVE-2023-1698-PoC](https://github.com/codeb0ss/CVE-2023-1698-PoC) :  
![starts](https://img.shields.io/github/stars/codeb0ss/CVE-2023-1698-PoC.svg) 
![forks](https://img.shields.io/github/forks/codeb0ss/CVE-2023-1698-PoC.svg) 
2023-09-10T01:36:35Z

- [https://github.com/Chocapikk/CVE-2023-1698](https://github.com/Chocapikk/CVE-2023-1698) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2023-1698.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2023-1698.svg) 
2023-09-15T20:07:07Z

- [https://github.com/thedarknessdied/WAGO-CVE-2023-1698](https://github.com/thedarknessdied/WAGO-CVE-2023-1698) :  
![starts](https://img.shields.io/github/stars/thedarknessdied/WAGO-CVE-2023-1698.svg) 
![forks](https://img.shields.io/github/forks/thedarknessdied/WAGO-CVE-2023-1698.svg) 
2023-10-20T12:55:17Z

- [https://github.com/X3RX3SSec/CVE-2023-1698](https://github.com/X3RX3SSec/CVE-2023-1698) :  
![starts](https://img.shields.io/github/stars/X3RX3SSec/CVE-2023-1698.svg) 
![forks](https://img.shields.io/github/forks/X3RX3SSec/CVE-2023-1698.svg) 
2025-02-22T09:14:57Z

- [https://github.com/deIndra/CVE-2023-1698](https://github.com/deIndra/CVE-2023-1698) :  
![starts](https://img.shields.io/github/stars/deIndra/CVE-2023-1698.svg) 
![forks](https://img.shields.io/github/forks/deIndra/CVE-2023-1698.svg) 
2023-10-20T05:44:39Z

## CVE-2022-29581
 Improper Update of Reference Count vulnerability in net/sched of Linux Kernel allows local attacker to cause privilege escalation to root. This issue affects: Linux Kernel versions prior to 5.18; version 4.14 and later versions.

- [https://github.com/Nidhi77777/linux-4.19.72_CVE-2022-29581](https://github.com/Nidhi77777/linux-4.19.72_CVE-2022-29581) :  
![starts](https://img.shields.io/github/stars/Nidhi77777/linux-4.19.72_CVE-2022-29581.svg) 
![forks](https://img.shields.io/github/forks/Nidhi77777/linux-4.19.72_CVE-2022-29581.svg) 
2025-02-22T07:51:56Z

- [https://github.com/nidhihcl/linux-4.19.72_CVE-2022-29581](https://github.com/nidhihcl/linux-4.19.72_CVE-2022-29581) :  
![starts](https://img.shields.io/github/stars/nidhihcl/linux-4.19.72_CVE-2022-29581.svg) 
![forks](https://img.shields.io/github/forks/nidhihcl/linux-4.19.72_CVE-2022-29581.svg) 
2025-02-22T15:44:24Z

## CVE-2022-22659
 A logic issue was addressed with improved state management. This issue is fixed in iOS 15.4 and iPadOS 15.4. An attacker in a privileged network position may be able to leak sensitive user information.

- [https://github.com/geo-chen/iOS](https://github.com/geo-chen/iOS) :  
![starts](https://img.shields.io/github/stars/geo-chen/iOS.svg) 
![forks](https://img.shields.io/github/forks/geo-chen/iOS.svg) 
2025-02-22T06:09:05Z

## CVE-2022-3869
 Code Injection in GitHub repository froxlor/froxlor prior to 0.10.38.2.

- [https://github.com/TomKing062/CVE-2022-38694_unlock_bootloader](https://github.com/TomKing062/CVE-2022-38694_unlock_bootloader) :  
![starts](https://img.shields.io/github/stars/TomKing062/CVE-2022-38694_unlock_bootloader.svg) 
![forks](https://img.shields.io/github/forks/TomKing062/CVE-2022-38694_unlock_bootloader.svg) 
2025-02-21T14:10:58Z

- [https://github.com/TomKing062/CVE-2022-38691_38692](https://github.com/TomKing062/CVE-2022-38691_38692) :  
![starts](https://img.shields.io/github/stars/TomKing062/CVE-2022-38691_38692.svg) 
![forks](https://img.shields.io/github/forks/TomKing062/CVE-2022-38691_38692.svg) 
2025-02-22T01:35:49Z

## CVE-2021-42013
 It was found that the fix for CVE-2021-41773 in Apache HTTP Server 2.4.50 was insufficient. An attacker could use a path traversal attack to map URLs to files outside the directories configured by Alias-like directives. If files outside of these directories are not protected by the usual default configuration "require all denied", these requests can succeed. If CGI scripts are also enabled for these aliased pathes, this could allow for remote code execution. This issue only affects Apache 2.4.49 and Apache 2.4.50 and not earlier versions.

- [https://github.com/inbug-team/CVE-2021-41773_CVE-2021-42013](https://github.com/inbug-team/CVE-2021-41773_CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/inbug-team/CVE-2021-41773_CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/inbug-team/CVE-2021-41773_CVE-2021-42013.svg) 
2021-10-09T03:49:21Z

- [https://github.com/CLincat/vulcat](https://github.com/CLincat/vulcat) :  
![starts](https://img.shields.io/github/stars/CLincat/vulcat.svg) 
![forks](https://img.shields.io/github/forks/CLincat/vulcat.svg) 
2023-12-04T06:43:07Z

- [https://github.com/MrCl0wnLab/SimplesApachePathTraversal](https://github.com/MrCl0wnLab/SimplesApachePathTraversal) :  
![starts](https://img.shields.io/github/stars/MrCl0wnLab/SimplesApachePathTraversal.svg) 
![forks](https://img.shields.io/github/forks/MrCl0wnLab/SimplesApachePathTraversal.svg) 
2024-08-14T14:41:14Z

- [https://github.com/walnutsecurity/cve-2021-42013](https://github.com/walnutsecurity/cve-2021-42013) :  
![starts](https://img.shields.io/github/stars/walnutsecurity/cve-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/walnutsecurity/cve-2021-42013.svg) 
2023-01-23T16:41:56Z

- [https://github.com/im-hanzou/apachrot](https://github.com/im-hanzou/apachrot) :  
![starts](https://img.shields.io/github/stars/im-hanzou/apachrot.svg) 
![forks](https://img.shields.io/github/forks/im-hanzou/apachrot.svg) 
2021-10-12T07:27:09Z

- [https://github.com/Ls4ss/CVE-2021-41773_CVE-2021-42013](https://github.com/Ls4ss/CVE-2021-41773_CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/Ls4ss/CVE-2021-41773_CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/Ls4ss/CVE-2021-41773_CVE-2021-42013.svg) 
2022-09-09T16:09:11Z

- [https://github.com/Vulnmachines/cve-2021-42013](https://github.com/Vulnmachines/cve-2021-42013) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/cve-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/cve-2021-42013.svg) 
2022-08-30T11:59:18Z

- [https://github.com/battleoverflow/apache-traversal](https://github.com/battleoverflow/apache-traversal) :  
![starts](https://img.shields.io/github/stars/battleoverflow/apache-traversal.svg) 
![forks](https://img.shields.io/github/forks/battleoverflow/apache-traversal.svg) 
2024-04-15T06:23:06Z

- [https://github.com/wangfly-me/Apache_Penetration_Tool](https://github.com/wangfly-me/Apache_Penetration_Tool) :  
![starts](https://img.shields.io/github/stars/wangfly-me/Apache_Penetration_Tool.svg) 
![forks](https://img.shields.io/github/forks/wangfly-me/Apache_Penetration_Tool.svg) 
2023-05-22T16:00:49Z

- [https://github.com/Zeop-CyberSec/apache_normalize_path](https://github.com/Zeop-CyberSec/apache_normalize_path) :  
![starts](https://img.shields.io/github/stars/Zeop-CyberSec/apache_normalize_path.svg) 
![forks](https://img.shields.io/github/forks/Zeop-CyberSec/apache_normalize_path.svg) 
2021-10-21T18:51:00Z

- [https://github.com/blackn0te/Apache-HTTP-Server-2.4.49-2.4.50-Path-Traversal-Remote-Code-Execution](https://github.com/blackn0te/Apache-HTTP-Server-2.4.49-2.4.50-Path-Traversal-Remote-Code-Execution) :  
![starts](https://img.shields.io/github/stars/blackn0te/Apache-HTTP-Server-2.4.49-2.4.50-Path-Traversal-Remote-Code-Execution.svg) 
![forks](https://img.shields.io/github/forks/blackn0te/Apache-HTTP-Server-2.4.49-2.4.50-Path-Traversal-Remote-Code-Execution.svg) 
2022-11-22T14:42:10Z

- [https://github.com/asaotomo/CVE-2021-42013-Apache-RCE-Poc-Exp](https://github.com/asaotomo/CVE-2021-42013-Apache-RCE-Poc-Exp) :  
![starts](https://img.shields.io/github/stars/asaotomo/CVE-2021-42013-Apache-RCE-Poc-Exp.svg) 
![forks](https://img.shields.io/github/forks/asaotomo/CVE-2021-42013-Apache-RCE-Poc-Exp.svg) 
2021-12-24T07:38:39Z

- [https://github.com/andrea-mattioli/apache-exploit-CVE-2021-42013](https://github.com/andrea-mattioli/apache-exploit-CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/andrea-mattioli/apache-exploit-CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/andrea-mattioli/apache-exploit-CVE-2021-42013.svg) 
2021-10-08T13:18:55Z

- [https://github.com/CalfCrusher/Path-traversal-RCE-Apache-2.4.49-2.4.50-Exploit](https://github.com/CalfCrusher/Path-traversal-RCE-Apache-2.4.49-2.4.50-Exploit) :  
![starts](https://img.shields.io/github/stars/CalfCrusher/Path-traversal-RCE-Apache-2.4.49-2.4.50-Exploit.svg) 
![forks](https://img.shields.io/github/forks/CalfCrusher/Path-traversal-RCE-Apache-2.4.49-2.4.50-Exploit.svg) 
2022-04-08T09:24:35Z

- [https://github.com/theLSA/apache-httpd-path-traversal-checker](https://github.com/theLSA/apache-httpd-path-traversal-checker) :  
![starts](https://img.shields.io/github/stars/theLSA/apache-httpd-path-traversal-checker.svg) 
![forks](https://img.shields.io/github/forks/theLSA/apache-httpd-path-traversal-checker.svg) 
2021-10-16T10:28:23Z

- [https://github.com/TheLastVvV/CVE-2021-42013_Reverse-Shell](https://github.com/TheLastVvV/CVE-2021-42013_Reverse-Shell) :  
![starts](https://img.shields.io/github/stars/TheLastVvV/CVE-2021-42013_Reverse-Shell.svg) 
![forks](https://img.shields.io/github/forks/TheLastVvV/CVE-2021-42013_Reverse-Shell.svg) 
2021-10-24T13:26:02Z

- [https://github.com/Hydragyrum/CVE-2021-41773-Playground](https://github.com/Hydragyrum/CVE-2021-41773-Playground) :  
![starts](https://img.shields.io/github/stars/Hydragyrum/CVE-2021-41773-Playground.svg) 
![forks](https://img.shields.io/github/forks/Hydragyrum/CVE-2021-41773-Playground.svg) 
2021-11-04T22:56:14Z

- [https://github.com/sergiovks/LFI-RCE-Unauthenticated-Apache-2.4.49-2.4.50](https://github.com/sergiovks/LFI-RCE-Unauthenticated-Apache-2.4.49-2.4.50) :  
![starts](https://img.shields.io/github/stars/sergiovks/LFI-RCE-Unauthenticated-Apache-2.4.49-2.4.50.svg) 
![forks](https://img.shields.io/github/forks/sergiovks/LFI-RCE-Unauthenticated-Apache-2.4.49-2.4.50.svg) 
2023-06-13T12:11:52Z

- [https://github.com/OfriOuzan/CVE-2021-41773_CVE-2021-42013_Exploits](https://github.com/OfriOuzan/CVE-2021-41773_CVE-2021-42013_Exploits) :  
![starts](https://img.shields.io/github/stars/OfriOuzan/CVE-2021-41773_CVE-2021-42013_Exploits.svg) 
![forks](https://img.shields.io/github/forks/OfriOuzan/CVE-2021-41773_CVE-2021-42013_Exploits.svg) 
2023-08-02T09:51:50Z

- [https://github.com/BassoNicolas/CVE-2021-42013](https://github.com/BassoNicolas/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/BassoNicolas/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/BassoNicolas/CVE-2021-42013.svg) 
2024-04-07T17:15:24Z

- [https://github.com/twseptian/cve-2021-42013-docker-lab](https://github.com/twseptian/cve-2021-42013-docker-lab) :  
![starts](https://img.shields.io/github/stars/twseptian/cve-2021-42013-docker-lab.svg) 
![forks](https://img.shields.io/github/forks/twseptian/cve-2021-42013-docker-lab.svg) 
2022-02-09T17:27:53Z

- [https://github.com/5gstudent/cve-2021-41773-and-cve-2021-42013](https://github.com/5gstudent/cve-2021-41773-and-cve-2021-42013) :  
![starts](https://img.shields.io/github/stars/5gstudent/cve-2021-41773-and-cve-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/5gstudent/cve-2021-41773-and-cve-2021-42013.svg) 
2021-10-09T12:14:29Z

- [https://github.com/TheLastVvV/CVE-2021-42013](https://github.com/TheLastVvV/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/TheLastVvV/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/TheLastVvV/CVE-2021-42013.svg) 
2021-10-23T22:00:34Z

- [https://github.com/K3ysTr0K3R/CVE-2021-42013-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2021-42013-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2021-42013-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2021-42013-EXPLOIT.svg) 
2024-01-15T18:01:54Z

- [https://github.com/zerodaywolf/CVE-2021-41773_42013](https://github.com/zerodaywolf/CVE-2021-41773_42013) :  
![starts](https://img.shields.io/github/stars/zerodaywolf/CVE-2021-41773_42013.svg) 
![forks](https://img.shields.io/github/forks/zerodaywolf/CVE-2021-41773_42013.svg) 
2021-10-18T12:47:56Z

- [https://github.com/mauricelambert/CVE-2021-42013](https://github.com/mauricelambert/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/mauricelambert/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/mauricelambert/CVE-2021-42013.svg) 
2022-03-14T07:36:49Z

- [https://github.com/bananoname/cve-2021-42013](https://github.com/bananoname/cve-2021-42013) :  
![starts](https://img.shields.io/github/stars/bananoname/cve-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/bananoname/cve-2021-42013.svg) 
2024-08-01T13:25:24Z

- [https://github.com/robotsense1337/CVE-2021-42013](https://github.com/robotsense1337/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/robotsense1337/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/robotsense1337/CVE-2021-42013.svg) 
2021-11-03T17:41:41Z

- [https://github.com/Hamesawian/CVE-2021-42013](https://github.com/Hamesawian/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/Hamesawian/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/Hamesawian/CVE-2021-42013.svg) 
2023-06-29T16:34:21Z

- [https://github.com/vudala/CVE-2021-42013](https://github.com/vudala/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/vudala/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/vudala/CVE-2021-42013.svg) 
2023-06-22T05:15:16Z

- [https://github.com/cybfar/cve-2021-42013-httpd](https://github.com/cybfar/cve-2021-42013-httpd) :  
![starts](https://img.shields.io/github/stars/cybfar/cve-2021-42013-httpd.svg) 
![forks](https://img.shields.io/github/forks/cybfar/cve-2021-42013-httpd.svg) 
2023-06-08T09:34:09Z

- [https://github.com/jas9reet/CVE-2021-42013-LAB](https://github.com/jas9reet/CVE-2021-42013-LAB) :  
![starts](https://img.shields.io/github/stars/jas9reet/CVE-2021-42013-LAB.svg) 
![forks](https://img.shields.io/github/forks/jas9reet/CVE-2021-42013-LAB.svg) 
2022-06-06T06:09:39Z

- [https://github.com/corelight/CVE-2021-41773](https://github.com/corelight/CVE-2021-41773) :  
![starts](https://img.shields.io/github/stars/corelight/CVE-2021-41773.svg) 
![forks](https://img.shields.io/github/forks/corelight/CVE-2021-41773.svg) 
2021-10-28T05:55:41Z

- [https://github.com/ksanchezcld/httpd-2.4.49](https://github.com/ksanchezcld/httpd-2.4.49) :  
![starts](https://img.shields.io/github/stars/ksanchezcld/httpd-2.4.49.svg) 
![forks](https://img.shields.io/github/forks/ksanchezcld/httpd-2.4.49.svg) 
2021-10-12T22:02:19Z

- [https://github.com/Zyx2440/Apache-HTTP-Server-2.4.50-RCE](https://github.com/Zyx2440/Apache-HTTP-Server-2.4.50-RCE) :  
![starts](https://img.shields.io/github/stars/Zyx2440/Apache-HTTP-Server-2.4.50-RCE.svg) 
![forks](https://img.shields.io/github/forks/Zyx2440/Apache-HTTP-Server-2.4.50-RCE.svg) 
2024-08-26T16:32:21Z

- [https://github.com/IcmpOff/Apache-2.4.49-2.4.50-Traversal-Remote-Code-Execution-Exploit](https://github.com/IcmpOff/Apache-2.4.49-2.4.50-Traversal-Remote-Code-Execution-Exploit) :  
![starts](https://img.shields.io/github/stars/IcmpOff/Apache-2.4.49-2.4.50-Traversal-Remote-Code-Execution-Exploit.svg) 
![forks](https://img.shields.io/github/forks/IcmpOff/Apache-2.4.49-2.4.50-Traversal-Remote-Code-Execution-Exploit.svg) 
2021-11-09T02:39:22Z

- [https://github.com/rnsss/CVE-2021-42013](https://github.com/rnsss/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/rnsss/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/rnsss/CVE-2021-42013.svg) 
2022-01-07T03:12:48Z

- [https://github.com/LayarKacaSiber/CVE-2021-42013](https://github.com/LayarKacaSiber/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/LayarKacaSiber/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/LayarKacaSiber/CVE-2021-42013.svg) 
2021-10-23T13:16:53Z

- [https://github.com/viliuspovilaika/cve-2021-42013](https://github.com/viliuspovilaika/cve-2021-42013) :  
![starts](https://img.shields.io/github/stars/viliuspovilaika/cve-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/viliuspovilaika/cve-2021-42013.svg) 
2022-05-31T04:37:35Z

- [https://github.com/12345qwert123456/CVE-2021-42013](https://github.com/12345qwert123456/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/12345qwert123456/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/12345qwert123456/CVE-2021-42013.svg) 
2022-11-21T17:10:49Z

- [https://github.com/asepsaepdin/CVE-2021-42013](https://github.com/asepsaepdin/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/asepsaepdin/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/asepsaepdin/CVE-2021-42013.svg) 
2025-01-30T16:30:53Z

- [https://github.com/mightysai1997/cve-2021-42013](https://github.com/mightysai1997/cve-2021-42013) :  
![starts](https://img.shields.io/github/stars/mightysai1997/cve-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/mightysai1997/cve-2021-42013.svg) 
2022-09-15T11:28:47Z

- [https://github.com/honypot/CVE-2021-42013](https://github.com/honypot/CVE-2021-42013) :  
![starts](https://img.shields.io/github/stars/honypot/CVE-2021-42013.svg) 
![forks](https://img.shields.io/github/forks/honypot/CVE-2021-42013.svg) 
2022-03-14T04:08:32Z

- [https://github.com/mightysai1997/cve-2021-42013L](https://github.com/mightysai1997/cve-2021-42013L) :  
![starts](https://img.shields.io/github/stars/mightysai1997/cve-2021-42013L.svg) 
![forks](https://img.shields.io/github/forks/mightysai1997/cve-2021-42013L.svg) 
2022-09-15T11:35:11Z

- [https://github.com/mightysai1997/cve-2021-42013.get](https://github.com/mightysai1997/cve-2021-42013.get) :  
![starts](https://img.shields.io/github/stars/mightysai1997/cve-2021-42013.get.svg) 
![forks](https://img.shields.io/github/forks/mightysai1997/cve-2021-42013.get.svg) 
2022-09-15T12:15:14Z

- [https://github.com/dream434/cve-2021-42013-apache](https://github.com/dream434/cve-2021-42013-apache) :  
![starts](https://img.shields.io/github/stars/dream434/cve-2021-42013-apache.svg) 
![forks](https://img.shields.io/github/forks/dream434/cve-2021-42013-apache.svg) 
2025-02-22T19:20:54Z

- [https://github.com/hadrian3689/apache_2.4.50](https://github.com/hadrian3689/apache_2.4.50) :  
![starts](https://img.shields.io/github/stars/hadrian3689/apache_2.4.50.svg) 
![forks](https://img.shields.io/github/forks/hadrian3689/apache_2.4.50.svg) 
2022-09-20T15:30:05Z

- [https://github.com/xMohamed0/CVE-2021-42013-ApacheRCE](https://github.com/xMohamed0/CVE-2021-42013-ApacheRCE) :  
![starts](https://img.shields.io/github/stars/xMohamed0/CVE-2021-42013-ApacheRCE.svg) 
![forks](https://img.shields.io/github/forks/xMohamed0/CVE-2021-42013-ApacheRCE.svg) 
2021-11-14T14:58:58Z

- [https://github.com/pisut4152/Sigma-Rule-for-CVE-2021-41773-and-CVE-2021-42013-exploitation-attempt](https://github.com/pisut4152/Sigma-Rule-for-CVE-2021-41773-and-CVE-2021-42013-exploitation-attempt) :  
![starts](https://img.shields.io/github/stars/pisut4152/Sigma-Rule-for-CVE-2021-41773-and-CVE-2021-42013-exploitation-attempt.svg) 
![forks](https://img.shields.io/github/forks/pisut4152/Sigma-Rule-for-CVE-2021-41773-and-CVE-2021-42013-exploitation-attempt.svg) 
2021-10-08T04:46:08Z

- [https://github.com/0xGabe/Apache-CVEs](https://github.com/0xGabe/Apache-CVEs) :  
![starts](https://img.shields.io/github/stars/0xGabe/Apache-CVEs.svg) 
![forks](https://img.shields.io/github/forks/0xGabe/Apache-CVEs.svg) 
2023-06-03T23:12:48Z

- [https://github.com/pwn3z/CVE-2021-41773-Apache-RCE](https://github.com/pwn3z/CVE-2021-41773-Apache-RCE) :  
![starts](https://img.shields.io/github/stars/pwn3z/CVE-2021-41773-Apache-RCE.svg) 
![forks](https://img.shields.io/github/forks/pwn3z/CVE-2021-41773-Apache-RCE.svg) 
2022-06-17T13:39:38Z

# 2025-02-21
## CVE-2025-26465
 A vulnerability was found in OpenSSH when the VerifyHostKeyDNS option is enabled. A machine-in-the-middle attack can be performed by a malicious machine impersonating a legit server. This issue occurs due to how OpenSSH mishandles error codes in specific conditions when verifying the host key. For an attack to be considered successful, the attacker needs to manage to exhaust the client's memory resource first, turning the attack complexity high.

- [https://github.com/rxerium/CVE-2025-26465](https://github.com/rxerium/CVE-2025-26465) :  
![starts](https://img.shields.io/github/stars/rxerium/CVE-2025-26465.svg) 
![forks](https://img.shields.io/github/forks/rxerium/CVE-2025-26465.svg) 
2025-02-18T16:57:27Z

- [https://github.com/dolutech/patch-manual-CVE-2025-26465-e-CVE-2025-26466](https://github.com/dolutech/patch-manual-CVE-2025-26465-e-CVE-2025-26466) :  
![starts](https://img.shields.io/github/stars/dolutech/patch-manual-CVE-2025-26465-e-CVE-2025-26466.svg) 
![forks](https://img.shields.io/github/forks/dolutech/patch-manual-CVE-2025-26465-e-CVE-2025-26466.svg) 
2025-02-21T14:44:12Z

## CVE-2025-24016
 Wazuh is a free and open source platform used for threat prevention, detection, and response. Starting in version 4.4.0 and prior to version 4.9.1, an unsafe deserialization vulnerability allows for remote code execution on Wazuh servers. DistributedAPI parameters are a serialized as JSON and deserialized using `as_wazuh_object` (in `framework/wazuh/core/cluster/common.py`). If an attacker manages to inject an unsanitized dictionary in DAPI request/response, they can forge an unhandled exception (`__unhandled_exc__`) to evaluate arbitrary python code. The vulnerability can be triggered by anybody with API access (compromised dashboard or Wazuh servers in the cluster) or, in certain configurations, even by a compromised agent. Version 4.9.1 contains a fix.

- [https://github.com/0xjessie21/CVE-2025-24016](https://github.com/0xjessie21/CVE-2025-24016) :  
![starts](https://img.shields.io/github/stars/0xjessie21/CVE-2025-24016.svg) 
![forks](https://img.shields.io/github/forks/0xjessie21/CVE-2025-24016.svg) 
2025-02-19T16:33:45Z

- [https://github.com/MuhammadWaseem29/CVE-2025-24016](https://github.com/MuhammadWaseem29/CVE-2025-24016) :  
![starts](https://img.shields.io/github/stars/MuhammadWaseem29/CVE-2025-24016.svg) 
![forks](https://img.shields.io/github/forks/MuhammadWaseem29/CVE-2025-24016.svg) 
2025-02-21T00:17:42Z

- [https://github.com/huseyinstif/CVE-2025-24016-Nuclei-Template](https://github.com/huseyinstif/CVE-2025-24016-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/huseyinstif/CVE-2025-24016-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/huseyinstif/CVE-2025-24016-Nuclei-Template.svg) 
2025-02-13T06:38:45Z

## CVE-2024-43583
 Winlogon Elevation of Privilege Vulnerability

- [https://github.com/Kvngtheta/CVE-2024-43583-PoC](https://github.com/Kvngtheta/CVE-2024-43583-PoC) :  
![starts](https://img.shields.io/github/stars/Kvngtheta/CVE-2024-43583-PoC.svg) 
![forks](https://img.shields.io/github/forks/Kvngtheta/CVE-2024-43583-PoC.svg) 
2025-02-21T19:50:25Z

## CVE-2024-22243
 Applications that use UriComponentsBuilderto parse an externally provided URL (e.g. through a query parameter) ANDperform validation checks on the host of the parsed URL may be vulnerable to a  open redirect https://cwe.mitre.org/data/definitions/601.html attack or to a SSRF attack if the URL is used after passing validation checks.

- [https://github.com/SeanPesce/CVE-2024-22243](https://github.com/SeanPesce/CVE-2024-22243) :  
![starts](https://img.shields.io/github/stars/SeanPesce/CVE-2024-22243.svg) 
![forks](https://img.shields.io/github/forks/SeanPesce/CVE-2024-22243.svg) 
2024-10-22T16:37:42Z

- [https://github.com/shellfeel/CVE-2024-22243-CVE-2024-22234](https://github.com/shellfeel/CVE-2024-22243-CVE-2024-22234) :  
![starts](https://img.shields.io/github/stars/shellfeel/CVE-2024-22243-CVE-2024-22234.svg) 
![forks](https://img.shields.io/github/forks/shellfeel/CVE-2024-22243-CVE-2024-22234.svg) 
2024-02-28T06:55:26Z

- [https://github.com/Reivap/CVE-2024-22243](https://github.com/Reivap/CVE-2024-22243) :  
![starts](https://img.shields.io/github/stars/Reivap/CVE-2024-22243.svg) 
![forks](https://img.shields.io/github/forks/Reivap/CVE-2024-22243.svg) 
2025-02-21T05:03:01Z

## CVE-2022-47522
 The IEEE 802.11 specifications through 802.11ax allow physically proximate attackers to intercept (possibly cleartext) target-destined frames by spoofing a target's MAC address, sending Power Save frames to the access point, and then sending other frames to the access point (such as authentication frames or re-association frames) to remove the target's original security context. This behavior occurs because the specifications do not require an access point to purge its transmit queue before removing a client's pairwise encryption key.

- [https://github.com/toffeenutt/CVE-2022-47522-PoC](https://github.com/toffeenutt/CVE-2022-47522-PoC) :  
![starts](https://img.shields.io/github/stars/toffeenutt/CVE-2022-47522-PoC.svg) 
![forks](https://img.shields.io/github/forks/toffeenutt/CVE-2022-47522-PoC.svg) 
2025-02-21T05:47:00Z

## CVE-2022-42889
 Apache Commons Text performs variable interpolation, allowing properties to be dynamically evaluated and expanded. The standard format for interpolation is "${prefix:name}", where "prefix" is used to locate an instance of org.apache.commons.text.lookup.StringLookup that performs the interpolation. Starting with version 1.5 and continuing through 1.9, the set of default Lookup instances included interpolators that could result in arbitrary code execution or contact with remote servers. These lookups are: - "script" - execute expressions using the JVM script execution engine (javax.script) - "dns" - resolve dns records - "url" - load values from urls, including from remote servers Applications using the interpolation defaults in the affected versions may be vulnerable to remote code execution or unintentional contact with remote servers if untrusted configuration values are used. Users are recommended to upgrade to Apache Commons Text 1.10.0, which disables the problematic interpolators by default.

- [https://github.com/karthikuj/cve-2022-42889-text4shell-docker](https://github.com/karthikuj/cve-2022-42889-text4shell-docker) :  
![starts](https://img.shields.io/github/stars/karthikuj/cve-2022-42889-text4shell-docker.svg) 
![forks](https://img.shields.io/github/forks/karthikuj/cve-2022-42889-text4shell-docker.svg) 
2022-11-14T17:12:41Z

- [https://github.com/kljunowsky/CVE-2022-42889-text4shell](https://github.com/kljunowsky/CVE-2022-42889-text4shell) :  
![starts](https://img.shields.io/github/stars/kljunowsky/CVE-2022-42889-text4shell.svg) 
![forks](https://img.shields.io/github/forks/kljunowsky/CVE-2022-42889-text4shell.svg) 
2023-12-29T14:57:34Z

- [https://github.com/securekomodo/text4shell-scan](https://github.com/securekomodo/text4shell-scan) :  
![starts](https://img.shields.io/github/stars/securekomodo/text4shell-scan.svg) 
![forks](https://img.shields.io/github/forks/securekomodo/text4shell-scan.svg) 
2022-10-20T12:51:08Z

- [https://github.com/ClickCyber/cve-2022-42889](https://github.com/ClickCyber/cve-2022-42889) :  
![starts](https://img.shields.io/github/stars/ClickCyber/cve-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/ClickCyber/cve-2022-42889.svg) 
2022-10-18T14:10:07Z

- [https://github.com/SeanWrightSec/CVE-2022-42889-PoC](https://github.com/SeanWrightSec/CVE-2022-42889-PoC) :  
![starts](https://img.shields.io/github/stars/SeanWrightSec/CVE-2022-42889-PoC.svg) 
![forks](https://img.shields.io/github/forks/SeanWrightSec/CVE-2022-42889-PoC.svg) 
2022-10-20T11:56:13Z

- [https://github.com/HKirito/CVE-2022-33980](https://github.com/HKirito/CVE-2022-33980) :  
![starts](https://img.shields.io/github/stars/HKirito/CVE-2022-33980.svg) 
![forks](https://img.shields.io/github/forks/HKirito/CVE-2022-33980.svg) 
2022-10-20T09:00:26Z

- [https://github.com/f0ng/text4shellburpscanner](https://github.com/f0ng/text4shellburpscanner) :  
![starts](https://img.shields.io/github/stars/f0ng/text4shellburpscanner.svg) 
![forks](https://img.shields.io/github/forks/f0ng/text4shellburpscanner.svg) 
2022-12-09T09:08:13Z

- [https://github.com/cxzero/CVE-2022-42889-text4shell](https://github.com/cxzero/CVE-2022-42889-text4shell) :  
![starts](https://img.shields.io/github/stars/cxzero/CVE-2022-42889-text4shell.svg) 
![forks](https://img.shields.io/github/forks/cxzero/CVE-2022-42889-text4shell.svg) 
2023-03-17T16:15:41Z

- [https://github.com/cryxnet/CVE-2022-42889-RCE](https://github.com/cryxnet/CVE-2022-42889-RCE) :  
![starts](https://img.shields.io/github/stars/cryxnet/CVE-2022-42889-RCE.svg) 
![forks](https://img.shields.io/github/forks/cryxnet/CVE-2022-42889-RCE.svg) 
2022-11-21T10:17:03Z

- [https://github.com/gustanini/CVE-2022-42889-Text4Shell-POC](https://github.com/gustanini/CVE-2022-42889-Text4Shell-POC) :  
![starts](https://img.shields.io/github/stars/gustanini/CVE-2022-42889-Text4Shell-POC.svg) 
![forks](https://img.shields.io/github/forks/gustanini/CVE-2022-42889-Text4Shell-POC.svg) 
2023-06-27T09:01:14Z

- [https://github.com/korteke/CVE-2022-42889-POC](https://github.com/korteke/CVE-2022-42889-POC) :  
![starts](https://img.shields.io/github/stars/korteke/CVE-2022-42889-POC.svg) 
![forks](https://img.shields.io/github/forks/korteke/CVE-2022-42889-POC.svg) 
2022-11-06T16:03:44Z

- [https://github.com/securekomodo/text4shell-poc](https://github.com/securekomodo/text4shell-poc) :  
![starts](https://img.shields.io/github/stars/securekomodo/text4shell-poc.svg) 
![forks](https://img.shields.io/github/forks/securekomodo/text4shell-poc.svg) 
2022-10-31T16:03:56Z

- [https://github.com/QAInsights/cve-2022-42889-jmeter](https://github.com/QAInsights/cve-2022-42889-jmeter) :  
![starts](https://img.shields.io/github/stars/QAInsights/cve-2022-42889-jmeter.svg) 
![forks](https://img.shields.io/github/forks/QAInsights/cve-2022-42889-jmeter.svg) 
2022-11-05T15:27:52Z

- [https://github.com/akshayithape-devops/CVE-2022-42889-POC](https://github.com/akshayithape-devops/CVE-2022-42889-POC) :  
![starts](https://img.shields.io/github/stars/akshayithape-devops/CVE-2022-42889-POC.svg) 
![forks](https://img.shields.io/github/forks/akshayithape-devops/CVE-2022-42889-POC.svg) 
2022-10-23T06:23:03Z

- [https://github.com/smileostrich/Text4Shell-Scanner](https://github.com/smileostrich/Text4Shell-Scanner) :  
![starts](https://img.shields.io/github/stars/smileostrich/Text4Shell-Scanner.svg) 
![forks](https://img.shields.io/github/forks/smileostrich/Text4Shell-Scanner.svg) 
2022-10-24T15:00:53Z

- [https://github.com/pwnb0y/Text4shell-exploit](https://github.com/pwnb0y/Text4shell-exploit) :  
![starts](https://img.shields.io/github/stars/pwnb0y/Text4shell-exploit.svg) 
![forks](https://img.shields.io/github/forks/pwnb0y/Text4shell-exploit.svg) 
2022-11-21T18:17:07Z

- [https://github.com/uk0/cve-2022-42889-intercept](https://github.com/uk0/cve-2022-42889-intercept) :  
![starts](https://img.shields.io/github/stars/uk0/cve-2022-42889-intercept.svg) 
![forks](https://img.shields.io/github/forks/uk0/cve-2022-42889-intercept.svg) 
2022-10-21T03:46:50Z

- [https://github.com/chainguard-dev/text4shell-policy](https://github.com/chainguard-dev/text4shell-policy) :  
![starts](https://img.shields.io/github/stars/chainguard-dev/text4shell-policy.svg) 
![forks](https://img.shields.io/github/forks/chainguard-dev/text4shell-policy.svg) 
2023-06-21T11:06:51Z

- [https://github.com/YulinSec/t4scan](https://github.com/YulinSec/t4scan) :  
![starts](https://img.shields.io/github/stars/YulinSec/t4scan.svg) 
![forks](https://img.shields.io/github/forks/YulinSec/t4scan.svg) 
2022-10-31T04:09:25Z

- [https://github.com/s3l33/CVE-2022-42889](https://github.com/s3l33/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/s3l33/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/s3l33/CVE-2022-42889.svg) 
2022-10-22T02:53:13Z

- [https://github.com/stavrosgns/Text4ShellPayloads](https://github.com/stavrosgns/Text4ShellPayloads) :  
![starts](https://img.shields.io/github/stars/stavrosgns/Text4ShellPayloads.svg) 
![forks](https://img.shields.io/github/forks/stavrosgns/Text4ShellPayloads.svg) 
2022-10-21T19:57:38Z

- [https://github.com/0xmaximus/Apache-Commons-Text-CVE-2022-42889](https://github.com/0xmaximus/Apache-Commons-Text-CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/0xmaximus/Apache-Commons-Text-CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/0xmaximus/Apache-Commons-Text-CVE-2022-42889.svg) 
2022-10-23T09:02:49Z

- [https://github.com/humbss/CVE-2022-42889](https://github.com/humbss/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/humbss/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/humbss/CVE-2022-42889.svg) 
2022-10-21T14:01:47Z

- [https://github.com/devenes/text4shell-cve-2022-42889](https://github.com/devenes/text4shell-cve-2022-42889) :  
![starts](https://img.shields.io/github/stars/devenes/text4shell-cve-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/devenes/text4shell-cve-2022-42889.svg) 
2023-02-28T11:43:41Z

- [https://github.com/sunnyvale-it/CVE-2022-42889-PoC](https://github.com/sunnyvale-it/CVE-2022-42889-PoC) :  
![starts](https://img.shields.io/github/stars/sunnyvale-it/CVE-2022-42889-PoC.svg) 
![forks](https://img.shields.io/github/forks/sunnyvale-it/CVE-2022-42889-PoC.svg) 
2022-11-07T07:57:01Z

- [https://github.com/Vulnmachines/text4shell-CVE-2022-42889](https://github.com/Vulnmachines/text4shell-CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/text4shell-CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/text4shell-CVE-2022-42889.svg) 
2022-10-25T13:15:32Z

- [https://github.com/gokul-ramesh/text4shell-exploit](https://github.com/gokul-ramesh/text4shell-exploit) :  
![starts](https://img.shields.io/github/stars/gokul-ramesh/text4shell-exploit.svg) 
![forks](https://img.shields.io/github/forks/gokul-ramesh/text4shell-exploit.svg) 
2023-03-12T17:06:11Z

- [https://github.com/Gotcha-1G/CVE-2022-42889](https://github.com/Gotcha-1G/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/Gotcha-1G/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/Gotcha-1G/CVE-2022-42889.svg) 
2022-11-02T21:51:15Z

- [https://github.com/rhitikwadhvana/CVE-2022-42889-Text4Shell-Exploit-POC](https://github.com/rhitikwadhvana/CVE-2022-42889-Text4Shell-Exploit-POC) :  
![starts](https://img.shields.io/github/stars/rhitikwadhvana/CVE-2022-42889-Text4Shell-Exploit-POC.svg) 
![forks](https://img.shields.io/github/forks/rhitikwadhvana/CVE-2022-42889-Text4Shell-Exploit-POC.svg) 
2022-10-22T10:31:50Z

- [https://github.com/tulhan/commons-text-goat](https://github.com/tulhan/commons-text-goat) :  
![starts](https://img.shields.io/github/stars/tulhan/commons-text-goat.svg) 
![forks](https://img.shields.io/github/forks/tulhan/commons-text-goat.svg) 
2023-04-18T22:24:14Z

- [https://github.com/Afrouper/MavenDependencyCVE-Scanner](https://github.com/Afrouper/MavenDependencyCVE-Scanner) :  
![starts](https://img.shields.io/github/stars/Afrouper/MavenDependencyCVE-Scanner.svg) 
![forks](https://img.shields.io/github/forks/Afrouper/MavenDependencyCVE-Scanner.svg) 
2025-02-10T04:53:00Z

- [https://github.com/aaronm-sysdig/text4shell-docker](https://github.com/aaronm-sysdig/text4shell-docker) :  
![starts](https://img.shields.io/github/stars/aaronm-sysdig/text4shell-docker.svg) 
![forks](https://img.shields.io/github/forks/aaronm-sysdig/text4shell-docker.svg) 
2024-01-05T10:18:55Z

- [https://github.com/necroteddy/CVE-2022-42889](https://github.com/necroteddy/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/necroteddy/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/necroteddy/CVE-2022-42889.svg) 
2023-04-19T05:53:16Z

- [https://github.com/jayaram-yalla/CVE-2022-42889-POC_TEXT4SHELL](https://github.com/jayaram-yalla/CVE-2022-42889-POC_TEXT4SHELL) :  
![starts](https://img.shields.io/github/stars/jayaram-yalla/CVE-2022-42889-POC_TEXT4SHELL.svg) 
![forks](https://img.shields.io/github/forks/jayaram-yalla/CVE-2022-42889-POC_TEXT4SHELL.svg) 
2022-10-22T14:17:26Z

- [https://github.com/34006133/CVE-2022-42889](https://github.com/34006133/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/34006133/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/34006133/CVE-2022-42889.svg) 
2023-09-10T13:32:05Z

- [https://github.com/neerazz/CVE-2022-42889](https://github.com/neerazz/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/neerazz/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/neerazz/CVE-2022-42889.svg) 
2022-10-19T22:58:32Z

- [https://github.com/Sic4rio/CVE-2022-42889](https://github.com/Sic4rio/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/Sic4rio/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/Sic4rio/CVE-2022-42889.svg) 
2023-09-06T01:15:29Z

- [https://github.com/rockmelodies/CVE-2022-42889](https://github.com/rockmelodies/CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/rockmelodies/CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/rockmelodies/CVE-2022-42889.svg) 
2022-10-17T16:09:23Z

- [https://github.com/eunomie/cve-2022-42889-check](https://github.com/eunomie/cve-2022-42889-check) :  
![starts](https://img.shields.io/github/stars/eunomie/cve-2022-42889-check.svg) 
![forks](https://img.shields.io/github/forks/eunomie/cve-2022-42889-check.svg) 
2022-10-20T12:54:56Z

- [https://github.com/galoget/CVE-2022-42889-Text4Shell-Docker](https://github.com/galoget/CVE-2022-42889-Text4Shell-Docker) :  
![starts](https://img.shields.io/github/stars/galoget/CVE-2022-42889-Text4Shell-Docker.svg) 
![forks](https://img.shields.io/github/forks/galoget/CVE-2022-42889-Text4Shell-Docker.svg) 
2022-10-22T10:03:19Z

- [https://github.com/Dima2021/cve-2022-42889-text4shell](https://github.com/Dima2021/cve-2022-42889-text4shell) :  
![starts](https://img.shields.io/github/stars/Dima2021/cve-2022-42889-text4shell.svg) 
![forks](https://img.shields.io/github/forks/Dima2021/cve-2022-42889-text4shell.svg) 
2023-04-18T15:12:29Z

- [https://github.com/MendDemo-josh/cve-2022-42889-text4shell](https://github.com/MendDemo-josh/cve-2022-42889-text4shell) :  
![starts](https://img.shields.io/github/stars/MendDemo-josh/cve-2022-42889-text4shell.svg) 
![forks](https://img.shields.io/github/forks/MendDemo-josh/cve-2022-42889-text4shell.svg) 
2025-01-23T12:44:43Z

- [https://github.com/DimaMend/cve-2022-42889-text4shell](https://github.com/DimaMend/cve-2022-42889-text4shell) :  
![starts](https://img.shields.io/github/stars/DimaMend/cve-2022-42889-text4shell.svg) 
![forks](https://img.shields.io/github/forks/DimaMend/cve-2022-42889-text4shell.svg) 
2025-02-21T09:44:18Z

- [https://github.com/joshbnewton31080/cve-2022-42889-text4shell](https://github.com/joshbnewton31080/cve-2022-42889-text4shell) :  
![starts](https://img.shields.io/github/stars/joshbnewton31080/cve-2022-42889-text4shell.svg) 
![forks](https://img.shields.io/github/forks/joshbnewton31080/cve-2022-42889-text4shell.svg) 
2024-02-08T20:54:31Z

- [https://github.com/dgor2023/cve-2022-42889-text4shell-docker](https://github.com/dgor2023/cve-2022-42889-text4shell-docker) :  
![starts](https://img.shields.io/github/stars/dgor2023/cve-2022-42889-text4shell-docker.svg) 
![forks](https://img.shields.io/github/forks/dgor2023/cve-2022-42889-text4shell-docker.svg) 
2023-04-12T02:32:57Z

- [https://github.com/ReachabilityOrg/cve-2022-42889-text4shell-docker](https://github.com/ReachabilityOrg/cve-2022-42889-text4shell-docker) :  
![starts](https://img.shields.io/github/stars/ReachabilityOrg/cve-2022-42889-text4shell-docker.svg) 
![forks](https://img.shields.io/github/forks/ReachabilityOrg/cve-2022-42889-text4shell-docker.svg) 
2023-04-11T15:43:44Z

- [https://github.com/adarshpv9746/Text4shell--Automated-exploit---CVE-2022-42889](https://github.com/adarshpv9746/Text4shell--Automated-exploit---CVE-2022-42889) :  
![starts](https://img.shields.io/github/stars/adarshpv9746/Text4shell--Automated-exploit---CVE-2022-42889.svg) 
![forks](https://img.shields.io/github/forks/adarshpv9746/Text4shell--Automated-exploit---CVE-2022-42889.svg) 
2022-11-07T09:44:18Z

- [https://github.com/hotblac/text4shell](https://github.com/hotblac/text4shell) :  
![starts](https://img.shields.io/github/stars/hotblac/text4shell.svg) 
![forks](https://img.shields.io/github/forks/hotblac/text4shell.svg) 
2023-03-12T17:34:46Z

## CVE-2021-44228
 Apache Log4j2 2.0-beta9 through 2.15.0 (excluding security releases 2.12.2, 2.12.3, and 2.3.1) JNDI features used in configuration, log messages, and parameters do not protect against attacker controlled LDAP and other JNDI related endpoints. An attacker who can control log messages or log message parameters can execute arbitrary code loaded from LDAP servers when message lookup substitution is enabled. From log4j 2.15.0, this behavior has been disabled by default. From version 2.16.0 (along with 2.12.2, 2.12.3, and 2.3.1), this functionality has been completely removed. Note that this vulnerability is specific to log4j-core and does not affect log4net, log4cxx, or other Apache Logging Services projects.

- [https://github.com/fullhunt/log4j-scan](https://github.com/fullhunt/log4j-scan) :  
![starts](https://img.shields.io/github/stars/fullhunt/log4j-scan.svg) 
![forks](https://img.shields.io/github/forks/fullhunt/log4j-scan.svg) 
2022-11-23T18:23:24Z

- [https://github.com/NCSC-NL/log4shell](https://github.com/NCSC-NL/log4shell) :  
![starts](https://img.shields.io/github/stars/NCSC-NL/log4shell.svg) 
![forks](https://img.shields.io/github/forks/NCSC-NL/log4shell.svg) 
2022-06-15T23:59:35Z

- [https://github.com/kozmer/log4j-shell-poc](https://github.com/kozmer/log4j-shell-poc) :  
![starts](https://img.shields.io/github/stars/kozmer/log4j-shell-poc.svg) 
![forks](https://img.shields.io/github/forks/kozmer/log4j-shell-poc.svg) 
2024-02-12T22:37:25Z

- [https://github.com/cisagov/log4j-scanner](https://github.com/cisagov/log4j-scanner) :  
![starts](https://img.shields.io/github/stars/cisagov/log4j-scanner.svg) 
![forks](https://img.shields.io/github/forks/cisagov/log4j-scanner.svg) 
2022-12-06T14:38:33Z

- [https://github.com/christophetd/log4shell-vulnerable-app](https://github.com/christophetd/log4shell-vulnerable-app) :  
![starts](https://img.shields.io/github/stars/christophetd/log4shell-vulnerable-app.svg) 
![forks](https://img.shields.io/github/forks/christophetd/log4shell-vulnerable-app.svg) 
2024-04-26T03:16:26Z

- [https://github.com/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words](https://github.com/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words) :  
![starts](https://img.shields.io/github/stars/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words.svg) 
![forks](https://img.shields.io/github/forks/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words.svg) 
2022-01-15T16:18:44Z

- [https://github.com/Puliczek/awesome-list-of-secrets-in-environment-variables](https://github.com/Puliczek/awesome-list-of-secrets-in-environment-variables) :  
![starts](https://img.shields.io/github/stars/Puliczek/awesome-list-of-secrets-in-environment-variables.svg) 
![forks](https://img.shields.io/github/forks/Puliczek/awesome-list-of-secrets-in-environment-variables.svg) 
2022-09-21T12:57:42Z

- [https://github.com/logpresso/CVE-2021-44228-Scanner](https://github.com/logpresso/CVE-2021-44228-Scanner) :  
![starts](https://img.shields.io/github/stars/logpresso/CVE-2021-44228-Scanner.svg) 
![forks](https://img.shields.io/github/forks/logpresso/CVE-2021-44228-Scanner.svg) 
2022-04-07T14:47:03Z

- [https://github.com/f0ng/log4j2burpscanner](https://github.com/f0ng/log4j2burpscanner) :  
![starts](https://img.shields.io/github/stars/f0ng/log4j2burpscanner.svg) 
![forks](https://img.shields.io/github/forks/f0ng/log4j2burpscanner.svg) 
2023-06-13T09:17:54Z

- [https://github.com/mergebase/log4j-detector](https://github.com/mergebase/log4j-detector) :  
![starts](https://img.shields.io/github/stars/mergebase/log4j-detector.svg) 
![forks](https://img.shields.io/github/forks/mergebase/log4j-detector.svg) 
2022-03-10T18:44:50Z

- [https://github.com/corretto/hotpatch-for-apache-log4j2](https://github.com/corretto/hotpatch-for-apache-log4j2) :  
![starts](https://img.shields.io/github/stars/corretto/hotpatch-for-apache-log4j2.svg) 
![forks](https://img.shields.io/github/forks/corretto/hotpatch-for-apache-log4j2.svg) 
2022-10-24T02:25:53Z

- [https://github.com/jas502n/Log4j2-CVE-2021-44228](https://github.com/jas502n/Log4j2-CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/jas502n/Log4j2-CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/jas502n/Log4j2-CVE-2021-44228.svg) 
2022-01-18T12:01:52Z

- [https://github.com/fox-it/log4j-finder](https://github.com/fox-it/log4j-finder) :  
![starts](https://img.shields.io/github/stars/fox-it/log4j-finder.svg) 
![forks](https://img.shields.io/github/forks/fox-it/log4j-finder.svg) 
2022-12-27T17:57:19Z

- [https://github.com/0xInfection/LogMePwn](https://github.com/0xInfection/LogMePwn) :  
![starts](https://img.shields.io/github/stars/0xInfection/LogMePwn.svg) 
![forks](https://img.shields.io/github/forks/0xInfection/LogMePwn.svg) 
2024-12-11T23:04:50Z

- [https://github.com/hillu/local-log4j-vuln-scanner](https://github.com/hillu/local-log4j-vuln-scanner) :  
![starts](https://img.shields.io/github/stars/hillu/local-log4j-vuln-scanner.svg) 
![forks](https://img.shields.io/github/forks/hillu/local-log4j-vuln-scanner.svg) 
2022-08-01T20:17:43Z

- [https://github.com/Diverto/nse-log4shell](https://github.com/Diverto/nse-log4shell) :  
![starts](https://img.shields.io/github/stars/Diverto/nse-log4shell.svg) 
![forks](https://img.shields.io/github/forks/Diverto/nse-log4shell.svg) 
2021-12-20T15:34:21Z

- [https://github.com/CERTCC/CVE-2021-44228_scanner](https://github.com/CERTCC/CVE-2021-44228_scanner) :  
![starts](https://img.shields.io/github/stars/CERTCC/CVE-2021-44228_scanner.svg) 
![forks](https://img.shields.io/github/forks/CERTCC/CVE-2021-44228_scanner.svg) 
2022-03-23T18:12:51Z

- [https://github.com/leonjza/log4jpwn](https://github.com/leonjza/log4jpwn) :  
![starts](https://img.shields.io/github/stars/leonjza/log4jpwn.svg) 
![forks](https://img.shields.io/github/forks/leonjza/log4jpwn.svg) 
2021-12-15T17:18:08Z

- [https://github.com/back2root/log4shell-rex](https://github.com/back2root/log4shell-rex) :  
![starts](https://img.shields.io/github/stars/back2root/log4shell-rex.svg) 
![forks](https://img.shields.io/github/forks/back2root/log4shell-rex.svg) 
2021-12-21T01:24:46Z

- [https://github.com/adilsoybali/Log4j-RCE-Scanner](https://github.com/adilsoybali/Log4j-RCE-Scanner) :  
![starts](https://img.shields.io/github/stars/adilsoybali/Log4j-RCE-Scanner.svg) 
![forks](https://img.shields.io/github/forks/adilsoybali/Log4j-RCE-Scanner.svg) 
2023-08-01T22:05:20Z

- [https://github.com/rubo77/log4j_checker_beta](https://github.com/rubo77/log4j_checker_beta) :  
![starts](https://img.shields.io/github/stars/rubo77/log4j_checker_beta.svg) 
![forks](https://img.shields.io/github/forks/rubo77/log4j_checker_beta.svg) 
2022-01-21T11:43:49Z

- [https://github.com/NS-Sp4ce/Vm4J](https://github.com/NS-Sp4ce/Vm4J) :  
![starts](https://img.shields.io/github/stars/NS-Sp4ce/Vm4J.svg) 
![forks](https://img.shields.io/github/forks/NS-Sp4ce/Vm4J.svg) 
2022-01-24T05:37:34Z

- [https://github.com/HackJava/Log4j2](https://github.com/HackJava/Log4j2) :  
![starts](https://img.shields.io/github/stars/HackJava/Log4j2.svg) 
![forks](https://img.shields.io/github/forks/HackJava/Log4j2.svg) 
2022-12-27T08:38:50Z

- [https://github.com/takito1812/log4j-detect](https://github.com/takito1812/log4j-detect) :  
![starts](https://img.shields.io/github/stars/takito1812/log4j-detect.svg) 
![forks](https://img.shields.io/github/forks/takito1812/log4j-detect.svg) 
2021-12-13T22:27:25Z

- [https://github.com/palantir/log4j-sniffer](https://github.com/palantir/log4j-sniffer) :  
![starts](https://img.shields.io/github/stars/palantir/log4j-sniffer.svg) 
![forks](https://img.shields.io/github/forks/palantir/log4j-sniffer.svg) 
2025-02-21T02:33:44Z

- [https://github.com/curated-intel/Log4Shell-IOCs](https://github.com/curated-intel/Log4Shell-IOCs) :  
![starts](https://img.shields.io/github/stars/curated-intel/Log4Shell-IOCs.svg) 
![forks](https://img.shields.io/github/forks/curated-intel/Log4Shell-IOCs.svg) 
2022-03-04T14:30:46Z

- [https://github.com/HyCraftHD/Log4J-RCE-Proof-Of-Concept](https://github.com/HyCraftHD/Log4J-RCE-Proof-Of-Concept) :  
![starts](https://img.shields.io/github/stars/HyCraftHD/Log4J-RCE-Proof-Of-Concept.svg) 
![forks](https://img.shields.io/github/forks/HyCraftHD/Log4J-RCE-Proof-Of-Concept.svg) 
2021-12-16T01:33:48Z

- [https://github.com/alexandre-lavoie/python-log4rce](https://github.com/alexandre-lavoie/python-log4rce) :  
![starts](https://img.shields.io/github/stars/alexandre-lavoie/python-log4rce.svg) 
![forks](https://img.shields.io/github/forks/alexandre-lavoie/python-log4rce.svg) 
2021-12-16T18:34:46Z

- [https://github.com/yahoo/check-log4j](https://github.com/yahoo/check-log4j) :  
![starts](https://img.shields.io/github/stars/yahoo/check-log4j.svg) 
![forks](https://img.shields.io/github/forks/yahoo/check-log4j.svg) 
2023-03-21T02:57:11Z

- [https://github.com/Qualys/log4jscanwin](https://github.com/Qualys/log4jscanwin) :  
![starts](https://img.shields.io/github/stars/Qualys/log4jscanwin.svg) 
![forks](https://img.shields.io/github/forks/Qualys/log4jscanwin.svg) 
2023-03-22T06:18:58Z

- [https://github.com/mubix/CVE-2021-44228-Log4Shell-Hashes](https://github.com/mubix/CVE-2021-44228-Log4Shell-Hashes) :  
![starts](https://img.shields.io/github/stars/mubix/CVE-2021-44228-Log4Shell-Hashes.svg) 
![forks](https://img.shields.io/github/forks/mubix/CVE-2021-44228-Log4Shell-Hashes.svg) 
2021-12-17T17:02:24Z

- [https://github.com/puzzlepeaches/Log4jUnifi](https://github.com/puzzlepeaches/Log4jUnifi) :  
![starts](https://img.shields.io/github/stars/puzzlepeaches/Log4jUnifi.svg) 
![forks](https://img.shields.io/github/forks/puzzlepeaches/Log4jUnifi.svg) 
2024-01-04T17:12:05Z

- [https://github.com/BinaryDefense/log4j-honeypot-flask](https://github.com/BinaryDefense/log4j-honeypot-flask) :  
![starts](https://img.shields.io/github/stars/BinaryDefense/log4j-honeypot-flask.svg) 
![forks](https://img.shields.io/github/forks/BinaryDefense/log4j-honeypot-flask.svg) 
2021-12-20T14:44:27Z

- [https://github.com/NorthwaveSecurity/log4jcheck](https://github.com/NorthwaveSecurity/log4jcheck) :  
![starts](https://img.shields.io/github/stars/NorthwaveSecurity/log4jcheck.svg) 
![forks](https://img.shields.io/github/forks/NorthwaveSecurity/log4jcheck.svg) 
2021-12-14T15:16:15Z

- [https://github.com/boundaryx/cloudrasp-log4j2](https://github.com/boundaryx/cloudrasp-log4j2) :  
![starts](https://img.shields.io/github/stars/boundaryx/cloudrasp-log4j2.svg) 
![forks](https://img.shields.io/github/forks/boundaryx/cloudrasp-log4j2.svg) 
2021-12-11T02:49:41Z

- [https://github.com/puzzlepeaches/Log4jHorizon](https://github.com/puzzlepeaches/Log4jHorizon) :  
![starts](https://img.shields.io/github/stars/puzzlepeaches/Log4jHorizon.svg) 
![forks](https://img.shields.io/github/forks/puzzlepeaches/Log4jHorizon.svg) 
2022-01-10T19:26:59Z

- [https://github.com/simonis/Log4jPatch](https://github.com/simonis/Log4jPatch) :  
![starts](https://img.shields.io/github/stars/simonis/Log4jPatch.svg) 
![forks](https://img.shields.io/github/forks/simonis/Log4jPatch.svg) 
2021-12-12T10:33:02Z

- [https://github.com/puzzlepeaches/Log4jCenter](https://github.com/puzzlepeaches/Log4jCenter) :  
![starts](https://img.shields.io/github/stars/puzzlepeaches/Log4jCenter.svg) 
![forks](https://img.shields.io/github/forks/puzzlepeaches/Log4jCenter.svg) 
2021-12-22T15:56:21Z

- [https://github.com/Adikso/minecraft-log4j-honeypot](https://github.com/Adikso/minecraft-log4j-honeypot) :  
![starts](https://img.shields.io/github/stars/Adikso/minecraft-log4j-honeypot.svg) 
![forks](https://img.shields.io/github/forks/Adikso/minecraft-log4j-honeypot.svg) 
2021-12-14T13:43:35Z

- [https://github.com/0xDexter0us/Log4J-Scanner](https://github.com/0xDexter0us/Log4J-Scanner) :  
![starts](https://img.shields.io/github/stars/0xDexter0us/Log4J-Scanner.svg) 
![forks](https://img.shields.io/github/forks/0xDexter0us/Log4J-Scanner.svg) 
2021-12-26T09:58:06Z

- [https://github.com/MalwareTech/Log4jTools](https://github.com/MalwareTech/Log4jTools) :  
![starts](https://img.shields.io/github/stars/MalwareTech/Log4jTools.svg) 
![forks](https://img.shields.io/github/forks/MalwareTech/Log4jTools.svg) 
2021-12-23T21:03:08Z

- [https://github.com/thomaspatzke/Log4Pot](https://github.com/thomaspatzke/Log4Pot) :  
![starts](https://img.shields.io/github/stars/thomaspatzke/Log4Pot.svg) 
![forks](https://img.shields.io/github/forks/thomaspatzke/Log4Pot.svg) 
2024-11-29T22:56:57Z

- [https://github.com/alexbakker/log4shell-tools](https://github.com/alexbakker/log4shell-tools) :  
![starts](https://img.shields.io/github/stars/alexbakker/log4shell-tools.svg) 
![forks](https://img.shields.io/github/forks/alexbakker/log4shell-tools.svg) 
2024-04-07T22:45:53Z

- [https://github.com/tangxiaofeng7/CVE-2021-44228-Apache-Log4j-Rce](https://github.com/tangxiaofeng7/CVE-2021-44228-Apache-Log4j-Rce) :  
![starts](https://img.shields.io/github/stars/tangxiaofeng7/CVE-2021-44228-Apache-Log4j-Rce.svg) 
![forks](https://img.shields.io/github/forks/tangxiaofeng7/CVE-2021-44228-Apache-Log4j-Rce.svg) 
2023-05-14T04:54:32Z

- [https://github.com/giterlizzi/nmap-log4shell](https://github.com/giterlizzi/nmap-log4shell) :  
![starts](https://img.shields.io/github/stars/giterlizzi/nmap-log4shell.svg) 
![forks](https://img.shields.io/github/forks/giterlizzi/nmap-log4shell.svg) 
2021-12-17T17:23:57Z

- [https://github.com/aalex954/Log4PowerShell](https://github.com/aalex954/Log4PowerShell) :  
![starts](https://img.shields.io/github/stars/aalex954/Log4PowerShell.svg) 
![forks](https://img.shields.io/github/forks/aalex954/Log4PowerShell.svg) 
2024-03-11T23:52:20Z

- [https://github.com/nccgroup/log4j-jndi-be-gone](https://github.com/nccgroup/log4j-jndi-be-gone) :  
![starts](https://img.shields.io/github/stars/nccgroup/log4j-jndi-be-gone.svg) 
![forks](https://img.shields.io/github/forks/nccgroup/log4j-jndi-be-gone.svg) 
2022-01-04T02:03:58Z

- [https://github.com/zhzyker/logmap](https://github.com/zhzyker/logmap) :  
![starts](https://img.shields.io/github/stars/zhzyker/logmap.svg) 
![forks](https://img.shields.io/github/forks/zhzyker/logmap.svg) 
2021-12-24T09:42:51Z

- [https://github.com/cyberxml/log4j-poc](https://github.com/cyberxml/log4j-poc) :  
![starts](https://img.shields.io/github/stars/cyberxml/log4j-poc.svg) 
![forks](https://img.shields.io/github/forks/cyberxml/log4j-poc.svg) 
2022-12-21T21:11:58Z

- [https://github.com/LiveOverflow/log4shell](https://github.com/LiveOverflow/log4shell) :  
![starts](https://img.shields.io/github/stars/LiveOverflow/log4shell.svg) 
![forks](https://img.shields.io/github/forks/LiveOverflow/log4shell.svg) 
2021-12-24T15:44:53Z

- [https://github.com/bigsizeme/Log4j-check](https://github.com/bigsizeme/Log4j-check) :  
![starts](https://img.shields.io/github/stars/bigsizeme/Log4j-check.svg) 
![forks](https://img.shields.io/github/forks/bigsizeme/Log4j-check.svg) 
2021-12-13T09:18:19Z

- [https://github.com/future-client/CVE-2021-44228](https://github.com/future-client/CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/future-client/CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/future-client/CVE-2021-44228.svg) 
2021-12-12T17:37:11Z

- [https://github.com/lucab85/log4j-cve-2021-44228](https://github.com/lucab85/log4j-cve-2021-44228) :  
![starts](https://img.shields.io/github/stars/lucab85/log4j-cve-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/lucab85/log4j-cve-2021-44228.svg) 
2022-01-10T19:13:04Z

- [https://github.com/For-ACGN/Log4Shell](https://github.com/For-ACGN/Log4Shell) :  
![starts](https://img.shields.io/github/stars/For-ACGN/Log4Shell.svg) 
![forks](https://img.shields.io/github/forks/For-ACGN/Log4Shell.svg) 
2021-12-23T09:01:10Z

- [https://github.com/authomize/log4j-log4shell-affected](https://github.com/authomize/log4j-log4shell-affected) :  
![starts](https://img.shields.io/github/stars/authomize/log4j-log4shell-affected.svg) 
![forks](https://img.shields.io/github/forks/authomize/log4j-log4shell-affected.svg) 
2021-12-19T07:40:25Z

- [https://github.com/CodeShield-Security/Log4JShell-Bytecode-Detector](https://github.com/CodeShield-Security/Log4JShell-Bytecode-Detector) :  
![starts](https://img.shields.io/github/stars/CodeShield-Security/Log4JShell-Bytecode-Detector.svg) 
![forks](https://img.shields.io/github/forks/CodeShield-Security/Log4JShell-Bytecode-Detector.svg) 
2022-02-23T19:10:53Z

- [https://github.com/dtact/divd-2021-00038--log4j-scanner](https://github.com/dtact/divd-2021-00038--log4j-scanner) :  
![starts](https://img.shields.io/github/stars/dtact/divd-2021-00038--log4j-scanner.svg) 
![forks](https://img.shields.io/github/forks/dtact/divd-2021-00038--log4j-scanner.svg) 
2021-12-28T22:21:52Z

- [https://github.com/CreeperHost/Log4jPatcher](https://github.com/CreeperHost/Log4jPatcher) :  
![starts](https://img.shields.io/github/stars/CreeperHost/Log4jPatcher.svg) 
![forks](https://img.shields.io/github/forks/CreeperHost/Log4jPatcher.svg) 
2022-11-10T11:16:17Z

- [https://github.com/RedDrip7/Log4Shell_CVE-2021-44228_related_attacks_IOCs](https://github.com/RedDrip7/Log4Shell_CVE-2021-44228_related_attacks_IOCs) :  
![starts](https://img.shields.io/github/stars/RedDrip7/Log4Shell_CVE-2021-44228_related_attacks_IOCs.svg) 
![forks](https://img.shields.io/github/forks/RedDrip7/Log4Shell_CVE-2021-44228_related_attacks_IOCs.svg) 
2021-12-15T10:19:51Z

- [https://github.com/dwisiswant0/look4jar](https://github.com/dwisiswant0/look4jar) :  
![starts](https://img.shields.io/github/stars/dwisiswant0/look4jar.svg) 
![forks](https://img.shields.io/github/forks/dwisiswant0/look4jar.svg) 
2022-03-02T15:42:36Z

- [https://github.com/1lann/log4shelldetect](https://github.com/1lann/log4shelldetect) :  
![starts](https://img.shields.io/github/stars/1lann/log4shelldetect.svg) 
![forks](https://img.shields.io/github/forks/1lann/log4shelldetect.svg) 
2022-01-05T23:07:50Z

- [https://github.com/redhuntlabs/Log4JHunt](https://github.com/redhuntlabs/Log4JHunt) :  
![starts](https://img.shields.io/github/stars/redhuntlabs/Log4JHunt.svg) 
![forks](https://img.shields.io/github/forks/redhuntlabs/Log4JHunt.svg) 
2025-01-22T10:50:08Z

- [https://github.com/stripe/log4j-remediation-tools](https://github.com/stripe/log4j-remediation-tools) :  
![starts](https://img.shields.io/github/stars/stripe/log4j-remediation-tools.svg) 
![forks](https://img.shields.io/github/forks/stripe/log4j-remediation-tools.svg) 
2023-03-21T09:51:33Z

- [https://github.com/fireeye/CVE-2021-44228](https://github.com/fireeye/CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/fireeye/CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/fireeye/CVE-2021-44228.svg) 
2022-01-07T14:25:33Z

- [https://github.com/infiniroot/nginx-mitigate-log4shell](https://github.com/infiniroot/nginx-mitigate-log4shell) :  
![starts](https://img.shields.io/github/stars/infiniroot/nginx-mitigate-log4shell.svg) 
![forks](https://img.shields.io/github/forks/infiniroot/nginx-mitigate-log4shell.svg) 
2021-12-15T08:14:56Z

- [https://github.com/HynekPetrak/log4shell-finder](https://github.com/HynekPetrak/log4shell-finder) :  
![starts](https://img.shields.io/github/stars/HynekPetrak/log4shell-finder.svg) 
![forks](https://img.shields.io/github/forks/HynekPetrak/log4shell-finder.svg) 
2023-06-21T11:37:03Z

- [https://github.com/Y0-kan/Log4jShell-Scan](https://github.com/Y0-kan/Log4jShell-Scan) :  
![starts](https://img.shields.io/github/stars/Y0-kan/Log4jShell-Scan.svg) 
![forks](https://img.shields.io/github/forks/Y0-kan/Log4jShell-Scan.svg) 
2021-12-21T06:11:58Z

- [https://github.com/hackinghippo/log4shell_ioc_ips](https://github.com/hackinghippo/log4shell_ioc_ips) :  
![starts](https://img.shields.io/github/stars/hackinghippo/log4shell_ioc_ips.svg) 
![forks](https://img.shields.io/github/forks/hackinghippo/log4shell_ioc_ips.svg) 
2022-01-07T17:00:38Z

- [https://github.com/greymd/CVE-2021-44228](https://github.com/greymd/CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/greymd/CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/greymd/CVE-2021-44228.svg) 
2021-12-13T15:16:23Z

- [https://github.com/darkarnium/Log4j-CVE-Detect](https://github.com/darkarnium/Log4j-CVE-Detect) :  
![starts](https://img.shields.io/github/stars/darkarnium/Log4j-CVE-Detect.svg) 
![forks](https://img.shields.io/github/forks/darkarnium/Log4j-CVE-Detect.svg) 
2021-12-18T22:20:25Z

- [https://github.com/sassoftware/loguccino](https://github.com/sassoftware/loguccino) :  
![starts](https://img.shields.io/github/stars/sassoftware/loguccino.svg) 
![forks](https://img.shields.io/github/forks/sassoftware/loguccino.svg) 
2022-01-24T16:43:41Z

- [https://github.com/Jeromeyoung/log4j2burpscanner](https://github.com/Jeromeyoung/log4j2burpscanner) :  
![starts](https://img.shields.io/github/stars/Jeromeyoung/log4j2burpscanner.svg) 
![forks](https://img.shields.io/github/forks/Jeromeyoung/log4j2burpscanner.svg) 
2021-12-11T10:39:41Z

- [https://github.com/julian911015/Log4j-Scanner-Exploit](https://github.com/julian911015/Log4j-Scanner-Exploit) :  
![starts](https://img.shields.io/github/stars/julian911015/Log4j-Scanner-Exploit.svg) 
![forks](https://img.shields.io/github/forks/julian911015/Log4j-Scanner-Exploit.svg) 
2024-09-03T15:22:31Z

- [https://github.com/twseptian/spring-boot-log4j-cve-2021-44228-docker-lab](https://github.com/twseptian/spring-boot-log4j-cve-2021-44228-docker-lab) :  
![starts](https://img.shields.io/github/stars/twseptian/spring-boot-log4j-cve-2021-44228-docker-lab.svg) 
![forks](https://img.shields.io/github/forks/twseptian/spring-boot-log4j-cve-2021-44228-docker-lab.svg) 
2021-12-17T13:59:44Z

- [https://github.com/qingtengyun/cve-2021-44228-qingteng-online-patch](https://github.com/qingtengyun/cve-2021-44228-qingteng-online-patch) :  
![starts](https://img.shields.io/github/stars/qingtengyun/cve-2021-44228-qingteng-online-patch.svg) 
![forks](https://img.shields.io/github/forks/qingtengyun/cve-2021-44228-qingteng-online-patch.svg) 
2022-01-19T09:07:14Z

- [https://github.com/mufeedvh/log4jail](https://github.com/mufeedvh/log4jail) :  
![starts](https://img.shields.io/github/stars/mufeedvh/log4jail.svg) 
![forks](https://img.shields.io/github/forks/mufeedvh/log4jail.svg) 
2021-12-14T21:14:33Z

- [https://github.com/r3kind1e/Log4Shell-obfuscated-payloads-generator](https://github.com/r3kind1e/Log4Shell-obfuscated-payloads-generator) :  
![starts](https://img.shields.io/github/stars/r3kind1e/Log4Shell-obfuscated-payloads-generator.svg) 
![forks](https://img.shields.io/github/forks/r3kind1e/Log4Shell-obfuscated-payloads-generator.svg) 
2022-05-26T03:18:31Z

- [https://github.com/o7-Fire/Log4Shell](https://github.com/o7-Fire/Log4Shell) :  
![starts](https://img.shields.io/github/stars/o7-Fire/Log4Shell.svg) 
![forks](https://img.shields.io/github/forks/o7-Fire/Log4Shell.svg) 
2022-06-28T01:20:20Z

- [https://github.com/toramanemre/log4j-rce-detect-waf-bypass](https://github.com/toramanemre/log4j-rce-detect-waf-bypass) :  
![starts](https://img.shields.io/github/stars/toramanemre/log4j-rce-detect-waf-bypass.svg) 
![forks](https://img.shields.io/github/forks/toramanemre/log4j-rce-detect-waf-bypass.svg) 
2021-12-11T10:19:51Z

- [https://github.com/tippexs/nginx-njs-waf-cve2021-44228](https://github.com/tippexs/nginx-njs-waf-cve2021-44228) :  
![starts](https://img.shields.io/github/stars/tippexs/nginx-njs-waf-cve2021-44228.svg) 
![forks](https://img.shields.io/github/forks/tippexs/nginx-njs-waf-cve2021-44228.svg) 
2021-12-18T11:04:46Z

- [https://github.com/pedrohavay/exploit-CVE-2021-44228](https://github.com/pedrohavay/exploit-CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/pedrohavay/exploit-CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/pedrohavay/exploit-CVE-2021-44228.svg) 
2021-12-13T16:35:58Z

- [https://github.com/corelight/cve-2021-44228](https://github.com/corelight/cve-2021-44228) :  
![starts](https://img.shields.io/github/stars/corelight/cve-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/corelight/cve-2021-44228.svg) 
2024-05-04T18:38:58Z

- [https://github.com/faisalfs10x/Log4j2-CVE-2021-44228-revshell](https://github.com/faisalfs10x/Log4j2-CVE-2021-44228-revshell) :  
![starts](https://img.shields.io/github/stars/faisalfs10x/Log4j2-CVE-2021-44228-revshell.svg) 
![forks](https://img.shields.io/github/forks/faisalfs10x/Log4j2-CVE-2021-44228-revshell.svg) 
2021-12-21T19:48:57Z

- [https://github.com/Glease/Healer](https://github.com/Glease/Healer) :  
![starts](https://img.shields.io/github/stars/Glease/Healer.svg) 
![forks](https://img.shields.io/github/forks/Glease/Healer.svg) 
2023-01-27T17:34:36Z

- [https://github.com/blake-fm/vcenter-log4j](https://github.com/blake-fm/vcenter-log4j) :  
![starts](https://img.shields.io/github/stars/blake-fm/vcenter-log4j.svg) 
![forks](https://img.shields.io/github/forks/blake-fm/vcenter-log4j.svg) 
2021-12-15T12:17:19Z

- [https://github.com/ab0x90/CVE-2021-44228_PoC](https://github.com/ab0x90/CVE-2021-44228_PoC) :  
![starts](https://img.shields.io/github/stars/ab0x90/CVE-2021-44228_PoC.svg) 
![forks](https://img.shields.io/github/forks/ab0x90/CVE-2021-44228_PoC.svg) 
2021-12-15T11:23:38Z

- [https://github.com/lhotari/log4shell-mitigation-tester](https://github.com/lhotari/log4shell-mitigation-tester) :  
![starts](https://img.shields.io/github/stars/lhotari/log4shell-mitigation-tester.svg) 
![forks](https://img.shields.io/github/forks/lhotari/log4shell-mitigation-tester.svg) 
2021-12-13T17:24:37Z

- [https://github.com/Malwar3Ninja/Exploitation-of-Log4j2-CVE-2021-44228](https://github.com/Malwar3Ninja/Exploitation-of-Log4j2-CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/Malwar3Ninja/Exploitation-of-Log4j2-CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/Malwar3Ninja/Exploitation-of-Log4j2-CVE-2021-44228.svg) 
2021-12-19T12:42:02Z

- [https://github.com/ossie-git/log4shell_sentinel](https://github.com/ossie-git/log4shell_sentinel) :  
![starts](https://img.shields.io/github/stars/ossie-git/log4shell_sentinel.svg) 
![forks](https://img.shields.io/github/forks/ossie-git/log4shell_sentinel.svg) 
2021-12-22T08:40:58Z

- [https://github.com/mergebase/log4j-samples](https://github.com/mergebase/log4j-samples) :  
![starts](https://img.shields.io/github/stars/mergebase/log4j-samples.svg) 
![forks](https://img.shields.io/github/forks/mergebase/log4j-samples.svg) 
2021-12-30T05:15:54Z

- [https://github.com/mr-r3b00t/CVE-2021-44228](https://github.com/mr-r3b00t/CVE-2021-44228) :  
![starts](https://img.shields.io/github/stars/mr-r3b00t/CVE-2021-44228.svg) 
![forks](https://img.shields.io/github/forks/mr-r3b00t/CVE-2021-44228.svg) 
2022-01-05T12:37:39Z

- [https://github.com/zsolt-halo/Log4J-Log4Shell-CVE-2021-44228-Spring-Boot-Test-Service](https://github.com/zsolt-halo/Log4J-Log4Shell-CVE-2021-44228-Spring-Boot-Test-Service) :  
![starts](https://img.shields.io/github/stars/zsolt-halo/Log4J-Log4Shell-CVE-2021-44228-Spring-Boot-Test-Service.svg) 
![forks](https://img.shields.io/github/forks/zsolt-halo/Log4J-Log4Shell-CVE-2021-44228-Spring-Boot-Test-Service.svg) 
2021-12-13T13:26:11Z

- [https://github.com/snow0715/log4j-Scan-Burpsuite](https://github.com/snow0715/log4j-Scan-Burpsuite) :  
![starts](https://img.shields.io/github/stars/snow0715/log4j-Scan-Burpsuite.svg) 
![forks](https://img.shields.io/github/forks/snow0715/log4j-Scan-Burpsuite.svg) 
2022-01-26T03:51:30Z

- [https://github.com/xsultan/log4jshield](https://github.com/xsultan/log4jshield) :  
![starts](https://img.shields.io/github/stars/xsultan/log4jshield.svg) 
![forks](https://img.shields.io/github/forks/xsultan/log4jshield.svg) 
2021-12-23T04:50:38Z

- [https://github.com/mitiga/log4shell-cloud-scanner](https://github.com/mitiga/log4shell-cloud-scanner) :  
![starts](https://img.shields.io/github/stars/mitiga/log4shell-cloud-scanner.svg) 
![forks](https://img.shields.io/github/forks/mitiga/log4shell-cloud-scanner.svg) 
2021-12-17T16:00:03Z

- [https://github.com/Nanitor/log4fix](https://github.com/Nanitor/log4fix) :  
![starts](https://img.shields.io/github/stars/Nanitor/log4fix.svg) 
![forks](https://img.shields.io/github/forks/Nanitor/log4fix.svg) 
2021-12-24T13:08:46Z

- [https://github.com/Hydragyrum/evil-rmi-server](https://github.com/Hydragyrum/evil-rmi-server) :  
![starts](https://img.shields.io/github/stars/Hydragyrum/evil-rmi-server.svg) 
![forks](https://img.shields.io/github/forks/Hydragyrum/evil-rmi-server.svg) 
2021-12-12T21:48:06Z

- [https://github.com/hupe1980/scan4log4shell](https://github.com/hupe1980/scan4log4shell) :  
![starts](https://img.shields.io/github/stars/hupe1980/scan4log4shell.svg) 
![forks](https://img.shields.io/github/forks/hupe1980/scan4log4shell.svg) 
2022-02-15T13:04:54Z

# 2025-02-20
## CVE-2025-24971
 DumpDrop is a stupid simple file upload application that provides an interface for dragging and dropping files. An OS Command Injection vulnerability was discovered in the DumbDrop application, `/upload/init` endpoint. This vulnerability could allow an attacker to execute arbitrary code remotely when the **Apprise Notification** enabled. This issue has been addressed in commit `4ff8469d` and all users are advised to patch. There are no known workarounds for this vulnerability.

- [https://github.com/be4zad/CVE-2025-24971](https://github.com/be4zad/CVE-2025-24971) :  
![starts](https://img.shields.io/github/stars/be4zad/CVE-2025-24971.svg) 
![forks](https://img.shields.io/github/forks/be4zad/CVE-2025-24971.svg) 
2025-02-20T17:00:17Z

## CVE-2025-22654
 Unrestricted Upload of File with Dangerous Type vulnerability in kodeshpa Simplified allows Using Malicious Files. This issue affects Simplified: from n/a through 1.0.6.

- [https://github.com/McTavishSue/CVE-2025-22654](https://github.com/McTavishSue/CVE-2025-22654) :  
![starts](https://img.shields.io/github/stars/McTavishSue/CVE-2025-22654.svg) 
![forks](https://img.shields.io/github/forks/McTavishSue/CVE-2025-22654.svg) 
2025-02-20T14:32:46Z

## CVE-2025-21401
 Microsoft Edge (Chromium-based) Security Feature Bypass Vulnerability

- [https://github.com/toxy4ny/edge-maradeur](https://github.com/toxy4ny/edge-maradeur) :  
![starts](https://img.shields.io/github/stars/toxy4ny/edge-maradeur.svg) 
![forks](https://img.shields.io/github/forks/toxy4ny/edge-maradeur.svg) 
2025-02-20T15:20:50Z

## CVE-2025-0108
 An authentication bypass in the Palo Alto Networks PAN-OS software enables an unauthenticated attacker with network access to the management web interface to bypass the authentication otherwise required by the PAN-OS management web interface and invoke certain PHP scripts. While invoking these PHP scripts does not enable remote code execution, it can negatively impact integrity and confidentiality of PAN-OS.You can greatly reduce the risk of this issue by restricting access to the management web interface to only trusted internal IP addresses according to our recommended  best practices deployment guidelines https://live.paloaltonetworks.com/t5/community-blogs/tips-amp-tricks-how-to-secure-the-management-access-of-your-palo/ba-p/464431 .This issue does not affect Cloud NGFW or Prisma Access software.

- [https://github.com/iSee857/CVE-2025-0108-PoC](https://github.com/iSee857/CVE-2025-0108-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2025-0108-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2025-0108-PoC.svg) 
2025-02-13T06:43:21Z

- [https://github.com/FOLKS-iwd/CVE-2025-0108-PoC](https://github.com/FOLKS-iwd/CVE-2025-0108-PoC) :  
![starts](https://img.shields.io/github/stars/FOLKS-iwd/CVE-2025-0108-PoC.svg) 
![forks](https://img.shields.io/github/forks/FOLKS-iwd/CVE-2025-0108-PoC.svg) 
2025-02-14T13:50:44Z

- [https://github.com/fr4nc1stein/CVE-2025-0108-SCAN](https://github.com/fr4nc1stein/CVE-2025-0108-SCAN) :  
![starts](https://img.shields.io/github/stars/fr4nc1stein/CVE-2025-0108-SCAN.svg) 
![forks](https://img.shields.io/github/forks/fr4nc1stein/CVE-2025-0108-SCAN.svg) 
2025-02-18T22:05:23Z

- [https://github.com/becrevex/CVE-2025-0108](https://github.com/becrevex/CVE-2025-0108) :  
![starts](https://img.shields.io/github/stars/becrevex/CVE-2025-0108.svg) 
![forks](https://img.shields.io/github/forks/becrevex/CVE-2025-0108.svg) 
2025-02-19T17:00:11Z

- [https://github.com/sohaibeb/CVE-2025-0108](https://github.com/sohaibeb/CVE-2025-0108) :  
![starts](https://img.shields.io/github/stars/sohaibeb/CVE-2025-0108.svg) 
![forks](https://img.shields.io/github/forks/sohaibeb/CVE-2025-0108.svg) 
2025-02-20T07:48:16Z

- [https://github.com/barcrange/CVE-2025-0108-Authentication-Bypass-checker](https://github.com/barcrange/CVE-2025-0108-Authentication-Bypass-checker) :  
![starts](https://img.shields.io/github/stars/barcrange/CVE-2025-0108-Authentication-Bypass-checker.svg) 
![forks](https://img.shields.io/github/forks/barcrange/CVE-2025-0108-Authentication-Bypass-checker.svg) 
2025-02-19T06:29:56Z

## CVE-2024-43768
 In skia_alloc_func of SkDeflate.cpp, there is a possible out of bounds write due to an integer overflow. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/Mahesh-970/CVE-2024-43768](https://github.com/Mahesh-970/CVE-2024-43768) :  
![starts](https://img.shields.io/github/stars/Mahesh-970/CVE-2024-43768.svg) 
![forks](https://img.shields.io/github/forks/Mahesh-970/CVE-2024-43768.svg) 
2025-02-20T09:44:17Z

## CVE-2024-13489
 The LTL Freight Quotes  Old Dominion Edition plugin for WordPress is vulnerable to SQL Injection via the 'edit_id' and 'dropship_edit_id' parameters in all versions up to, and including, 4.2.10 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13489](https://github.com/RandomRobbieBF/CVE-2024-13489) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13489.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13489.svg) 
2025-02-20T15:46:28Z

## CVE-2024-13488
 The LTL Freight Quotes  Estes Edition plugin for WordPress is vulnerable to SQL Injection via the 'dropship_edit_id' and 'edit_id' parameters in all versions up to, and including, 3.3.7 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13488](https://github.com/RandomRobbieBF/CVE-2024-13488) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13488.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13488.svg) 
2025-02-20T15:36:16Z

## CVE-2024-13485
 The LTL Freight Quotes  ABF Freight Edition plugin for WordPress is vulnerable to SQL Injection via the 'edit_id' and 'dropship_edit_id' parameters in all versions up to, and including, 3.3.7 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13485](https://github.com/RandomRobbieBF/CVE-2024-13485) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13485.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13485.svg) 
2025-02-20T15:48:06Z

## CVE-2024-13483
 The LTL Freight Quotes  SAIA Edition plugin for WordPress is vulnerable to SQL Injection via the 'edit_id' and 'dropship_edit_id' parameters in all versions up to, and including, 2.2.10 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13483](https://github.com/RandomRobbieBF/CVE-2024-13483) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13483.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13483.svg) 
2025-02-20T15:49:11Z

## CVE-2024-13481
 The LTL Freight Quotes  R+L Carriers Edition plugin for WordPress is vulnerable to SQL Injection via the 'edit_id' and 'dropship_edit_id' parameters in all versions up to, and including, 3.3.4 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13481](https://github.com/RandomRobbieBF/CVE-2024-13481) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13481.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13481.svg) 
2025-02-20T15:52:54Z

## CVE-2024-13479
 The LTL Freight Quotes  SEFL Edition plugin for WordPress is vulnerable to SQL Injection via the 'dropship_edit_id' and 'edit_id' parameters in all versions up to, and including, 3.2.4 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13479](https://github.com/RandomRobbieBF/CVE-2024-13479) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13479.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13479.svg) 
2025-02-20T15:51:53Z

## CVE-2024-13478
 The LTL Freight Quotes  TForce Edition plugin for WordPress is vulnerable to SQL Injection via the 'dropship_edit_id' and 'edit_id' parameters in all versions up to, and including, 3.6.4 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-13478](https://github.com/RandomRobbieBF/CVE-2024-13478) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-13478.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-13478.svg) 
2025-02-20T15:50:35Z

## CVE-2024-3273
 ** UNSUPPORTED WHEN ASSIGNED ** A vulnerability, which was classified as critical, was found in D-Link DNS-320L, DNS-325, DNS-327L and DNS-340L up to 20240403. Affected is an unknown function of the file /cgi-bin/nas_sharing.cgi of the component HTTP GET Request Handler. The manipulation of the argument system leads to command injection. It is possible to launch the attack remotely. The exploit has been disclosed to the public and may be used. The identifier of this vulnerability is VDB-259284. NOTE: This vulnerability only affects products that are no longer supported by the maintainer. NOTE: Vendor was contacted early and confirmed immediately that the product is end-of-life. It should be retired and replaced.

- [https://github.com/Chocapikk/CVE-2024-3273](https://github.com/Chocapikk/CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-3273.svg) 
2024-04-07T04:41:26Z

- [https://github.com/adhikara13/CVE-2024-3273](https://github.com/adhikara13/CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/adhikara13/CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/adhikara13/CVE-2024-3273.svg) 
2024-04-07T15:41:42Z

- [https://github.com/ThatNotEasy/CVE-2024-3273](https://github.com/ThatNotEasy/CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-3273.svg) 
2024-04-10T00:36:05Z

- [https://github.com/K3ysTr0K3R/CVE-2024-3273-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-3273-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-3273-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-3273-EXPLOIT.svg) 
2024-04-09T12:51:41Z

- [https://github.com/nickswink/D-Link-NAS-Devices-Unauthenticated-RCE](https://github.com/nickswink/D-Link-NAS-Devices-Unauthenticated-RCE) :  
![starts](https://img.shields.io/github/stars/nickswink/D-Link-NAS-Devices-Unauthenticated-RCE.svg) 
![forks](https://img.shields.io/github/forks/nickswink/D-Link-NAS-Devices-Unauthenticated-RCE.svg) 
2024-04-08T13:57:31Z

- [https://github.com/GSTEINF/CVE-2024-3273](https://github.com/GSTEINF/CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/GSTEINF/CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/GSTEINF/CVE-2024-3273.svg) 
2025-02-20T22:57:03Z

- [https://github.com/LeopoldSkell/CVE-2024-3273](https://github.com/LeopoldSkell/CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/LeopoldSkell/CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/LeopoldSkell/CVE-2024-3273.svg) 
2024-04-16T09:12:58Z

- [https://github.com/mrrobot0o/CVE-2024-3273-](https://github.com/mrrobot0o/CVE-2024-3273-) :  
![starts](https://img.shields.io/github/stars/mrrobot0o/CVE-2024-3273-.svg) 
![forks](https://img.shields.io/github/forks/mrrobot0o/CVE-2024-3273-.svg) 
2024-04-23T06:32:39Z

- [https://github.com/yarienkiva/honeypot-dlink-CVE-2024-3273](https://github.com/yarienkiva/honeypot-dlink-CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/yarienkiva/honeypot-dlink-CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/yarienkiva/honeypot-dlink-CVE-2024-3273.svg) 
2024-04-16T00:00:15Z

- [https://github.com/OIivr/Turvan6rkus-CVE-2024-3273](https://github.com/OIivr/Turvan6rkus-CVE-2024-3273) :  
![starts](https://img.shields.io/github/stars/OIivr/Turvan6rkus-CVE-2024-3273.svg) 
![forks](https://img.shields.io/github/forks/OIivr/Turvan6rkus-CVE-2024-3273.svg) 
2024-05-25T17:27:56Z

- [https://github.com/X-Projetion/CVE-2024-3273-D-Link-Remote-Code-Execution-RCE](https://github.com/X-Projetion/CVE-2024-3273-D-Link-Remote-Code-Execution-RCE) :  
![starts](https://img.shields.io/github/stars/X-Projetion/CVE-2024-3273-D-Link-Remote-Code-Execution-RCE.svg) 
![forks](https://img.shields.io/github/forks/X-Projetion/CVE-2024-3273-D-Link-Remote-Code-Execution-RCE.svg) 
2024-09-21T11:24:47Z

## CVE-2024-1651
 Torrentpier version 2.4.1 allows executing arbitrary commands on the server.This is possible because the application is vulnerable to insecure deserialization.

- [https://github.com/sharpicx/CVE-2024-1651-PoC](https://github.com/sharpicx/CVE-2024-1651-PoC) :  
![starts](https://img.shields.io/github/stars/sharpicx/CVE-2024-1651-PoC.svg) 
![forks](https://img.shields.io/github/forks/sharpicx/CVE-2024-1651-PoC.svg) 
2024-03-07T10:23:52Z

- [https://github.com/hy011121/CVE-2024-1651-exploit-RCE](https://github.com/hy011121/CVE-2024-1651-exploit-RCE) :  
![starts](https://img.shields.io/github/stars/hy011121/CVE-2024-1651-exploit-RCE.svg) 
![forks](https://img.shields.io/github/forks/hy011121/CVE-2024-1651-exploit-RCE.svg) 
2024-02-29T21:09:19Z

- [https://github.com/killukeren/cve-2024-1651](https://github.com/killukeren/cve-2024-1651) :  
![starts](https://img.shields.io/github/stars/killukeren/cve-2024-1651.svg) 
![forks](https://img.shields.io/github/forks/killukeren/cve-2024-1651.svg) 
2025-02-20T07:41:29Z

- [https://github.com/Whiteh4tWolf/CVE-2024-1651-PoC](https://github.com/Whiteh4tWolf/CVE-2024-1651-PoC) :  
![starts](https://img.shields.io/github/stars/Whiteh4tWolf/CVE-2024-1651-PoC.svg) 
![forks](https://img.shields.io/github/forks/Whiteh4tWolf/CVE-2024-1651-PoC.svg) 
2024-04-19T16:20:41Z

## CVE-2023-24932
 Secure Boot Security Feature Bypass Vulnerability

- [https://github.com/Wack0/CVE-2022-21894](https://github.com/Wack0/CVE-2022-21894) :  
![starts](https://img.shields.io/github/stars/Wack0/CVE-2022-21894.svg) 
![forks](https://img.shields.io/github/forks/Wack0/CVE-2022-21894.svg) 
2023-09-27T06:44:27Z

- [https://github.com/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932](https://github.com/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932) :  
![starts](https://img.shields.io/github/stars/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932.svg) 
![forks](https://img.shields.io/github/forks/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932.svg) 
2025-02-20T14:35:22Z

## CVE-2022-40684
 An authentication bypass using an alternate path or channel [CWE-288] in Fortinet FortiOS version 7.2.0 through 7.2.1 and 7.0.0 through 7.0.6, FortiProxy version 7.2.0 and version 7.0.0 through 7.0.6 and FortiSwitchManager version 7.2.0 and 7.0.0 allows an unauthenticated atttacker to perform operations on the administrative interface via specially crafted HTTP or HTTPS requests.

- [https://github.com/horizon3ai/CVE-2022-40684](https://github.com/horizon3ai/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/horizon3ai/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/horizon3ai/CVE-2022-40684.svg) 
2022-10-13T15:25:00Z

- [https://github.com/carlosevieira/CVE-2022-40684](https://github.com/carlosevieira/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/carlosevieira/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/carlosevieira/CVE-2022-40684.svg) 
2022-10-13T20:13:44Z

- [https://github.com/arsolutioner/fortigate-belsen-leak](https://github.com/arsolutioner/fortigate-belsen-leak) :  
![starts](https://img.shields.io/github/stars/arsolutioner/fortigate-belsen-leak.svg) 
![forks](https://img.shields.io/github/forks/arsolutioner/fortigate-belsen-leak.svg) 
2025-01-16T09:56:36Z

- [https://github.com/hackingyseguridad/nmap](https://github.com/hackingyseguridad/nmap) :  
![starts](https://img.shields.io/github/stars/hackingyseguridad/nmap.svg) 
![forks](https://img.shields.io/github/forks/hackingyseguridad/nmap.svg) 
2024-04-17T11:38:44Z

- [https://github.com/Filiplain/Fortinet-PoC-Auth-Bypass](https://github.com/Filiplain/Fortinet-PoC-Auth-Bypass) :  
![starts](https://img.shields.io/github/stars/Filiplain/Fortinet-PoC-Auth-Bypass.svg) 
![forks](https://img.shields.io/github/forks/Filiplain/Fortinet-PoC-Auth-Bypass.svg) 
2023-04-02T12:44:53Z

- [https://github.com/kljunowsky/CVE-2022-40684-POC](https://github.com/kljunowsky/CVE-2022-40684-POC) :  
![starts](https://img.shields.io/github/stars/kljunowsky/CVE-2022-40684-POC.svg) 
![forks](https://img.shields.io/github/forks/kljunowsky/CVE-2022-40684-POC.svg) 
2023-01-21T02:17:48Z

- [https://github.com/TaroballzChen/CVE-2022-40684-metasploit-scanner](https://github.com/TaroballzChen/CVE-2022-40684-metasploit-scanner) :  
![starts](https://img.shields.io/github/stars/TaroballzChen/CVE-2022-40684-metasploit-scanner.svg) 
![forks](https://img.shields.io/github/forks/TaroballzChen/CVE-2022-40684-metasploit-scanner.svg) 
2022-10-27T15:32:53Z

- [https://github.com/hughink/CVE-2022-40684](https://github.com/hughink/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/hughink/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/hughink/CVE-2022-40684.svg) 
2022-10-28T04:07:23Z

- [https://github.com/qingsiweisan/CVE-2022-40684](https://github.com/qingsiweisan/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/qingsiweisan/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/qingsiweisan/CVE-2022-40684.svg) 
2022-10-26T02:16:39Z

- [https://github.com/secunnix/CVE-2022-40684](https://github.com/secunnix/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/secunnix/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/secunnix/CVE-2022-40684.svg) 
2022-10-14T13:28:24Z

- [https://github.com/z-bool/CVE-2022-40684](https://github.com/z-bool/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/z-bool/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/z-bool/CVE-2022-40684.svg) 
2023-02-27T18:10:44Z

- [https://github.com/Chocapikk/CVE-2022-40684](https://github.com/Chocapikk/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2022-40684.svg) 
2022-10-19T16:27:16Z

- [https://github.com/mohamedbenchikh/CVE-2022-40684](https://github.com/mohamedbenchikh/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/mohamedbenchikh/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/mohamedbenchikh/CVE-2022-40684.svg) 
2022-10-15T17:03:29Z

- [https://github.com/und3sc0n0c1d0/CVE-2022-40684](https://github.com/und3sc0n0c1d0/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/und3sc0n0c1d0/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/und3sc0n0c1d0/CVE-2022-40684.svg) 
2022-10-24T17:10:33Z

- [https://github.com/Grapphy/fortipwn](https://github.com/Grapphy/fortipwn) :  
![starts](https://img.shields.io/github/stars/Grapphy/fortipwn.svg) 
![forks](https://img.shields.io/github/forks/Grapphy/fortipwn.svg) 
2022-10-21T19:45:35Z

- [https://github.com/gustavorobertux/gotigate](https://github.com/gustavorobertux/gotigate) :  
![starts](https://img.shields.io/github/stars/gustavorobertux/gotigate.svg) 
![forks](https://img.shields.io/github/forks/gustavorobertux/gotigate.svg) 
2022-10-28T15:26:30Z

- [https://github.com/jsongmax/Fortinet-CVE-2022-40684](https://github.com/jsongmax/Fortinet-CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/jsongmax/Fortinet-CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/jsongmax/Fortinet-CVE-2022-40684.svg) 
2022-10-17T09:44:44Z

- [https://github.com/HAWA771/CVE-2022-40684](https://github.com/HAWA771/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/HAWA771/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/HAWA771/CVE-2022-40684.svg) 
2022-10-15T17:01:37Z

- [https://github.com/Bendalledj/CVE-2022-40684](https://github.com/Bendalledj/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/Bendalledj/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/Bendalledj/CVE-2022-40684.svg) 
2022-10-21T08:09:13Z

- [https://github.com/NeriaBasha/CVE-2022-40684](https://github.com/NeriaBasha/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/NeriaBasha/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/NeriaBasha/CVE-2022-40684.svg) 
2022-10-16T00:25:41Z

- [https://github.com/iveresk/CVE-2022-40684](https://github.com/iveresk/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/iveresk/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/iveresk/CVE-2022-40684.svg) 
2022-10-17T16:42:19Z

- [https://github.com/XalfiE/Fortigate-Belsen-Leak-Dump-CVE-2022-40684-](https://github.com/XalfiE/Fortigate-Belsen-Leak-Dump-CVE-2022-40684-) :  
![starts](https://img.shields.io/github/stars/XalfiE/Fortigate-Belsen-Leak-Dump-CVE-2022-40684-.svg) 
![forks](https://img.shields.io/github/forks/XalfiE/Fortigate-Belsen-Leak-Dump-CVE-2022-40684-.svg) 
2025-02-05T07:51:51Z

- [https://github.com/ClickCyber/cve-2022-40684](https://github.com/ClickCyber/cve-2022-40684) :  
![starts](https://img.shields.io/github/stars/ClickCyber/cve-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/ClickCyber/cve-2022-40684.svg) 
2022-10-15T11:36:12Z

- [https://github.com/puckiestyle/CVE-2022-40684](https://github.com/puckiestyle/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/puckiestyle/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/puckiestyle/CVE-2022-40684.svg) 
2022-10-17T08:49:46Z

- [https://github.com/mhd108/CVE-2022-40684](https://github.com/mhd108/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/mhd108/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/mhd108/CVE-2022-40684.svg) 
2022-10-14T11:01:54Z

- [https://github.com/Anthony1500/CVE-2022-40684](https://github.com/Anthony1500/CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/Anthony1500/CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/Anthony1500/CVE-2022-40684.svg) 
2023-09-14T21:29:24Z

- [https://github.com/notareaperbutDR34P3r/CVE-2022-40684-Rust](https://github.com/notareaperbutDR34P3r/CVE-2022-40684-Rust) :  
![starts](https://img.shields.io/github/stars/notareaperbutDR34P3r/CVE-2022-40684-Rust.svg) 
![forks](https://img.shields.io/github/forks/notareaperbutDR34P3r/CVE-2022-40684-Rust.svg) 
2023-01-17T08:08:35Z

- [https://github.com/Rofell0s/Fortigate-Leak-CVE-2022-40684](https://github.com/Rofell0s/Fortigate-Leak-CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/Rofell0s/Fortigate-Leak-CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/Rofell0s/Fortigate-Leak-CVE-2022-40684.svg) 
2025-01-16T22:44:30Z

- [https://github.com/Yami0x777/Belsen_Group-et-exploitation-de-la-CVE-2022-40684](https://github.com/Yami0x777/Belsen_Group-et-exploitation-de-la-CVE-2022-40684) :  
![starts](https://img.shields.io/github/stars/Yami0x777/Belsen_Group-et-exploitation-de-la-CVE-2022-40684.svg) 
![forks](https://img.shields.io/github/forks/Yami0x777/Belsen_Group-et-exploitation-de-la-CVE-2022-40684.svg) 
2025-02-20T19:17:55Z

- [https://github.com/niklasmato/fortileak-01-2025-Be](https://github.com/niklasmato/fortileak-01-2025-Be) :  
![starts](https://img.shields.io/github/stars/niklasmato/fortileak-01-2025-Be.svg) 
![forks](https://img.shields.io/github/forks/niklasmato/fortileak-01-2025-Be.svg) 
2025-01-24T14:54:56Z

# 2025-02-19
## CVE-2025-25968
 DDSN Interactive cm3 Acora CMS version 10.1.1 contains an improper access control vulnerability. An editor-privileged user can access sensitive information, such as system administrator credentials, by force browsing the endpoint and exploiting the 'file' parameter. By referencing specific files (e.g., cm3.xml), attackers can bypass access controls, leading to account takeover and potential privilege escalation.

- [https://github.com/padayali-JD/CVE-2025-25968](https://github.com/padayali-JD/CVE-2025-25968) :  
![starts](https://img.shields.io/github/stars/padayali-JD/CVE-2025-25968.svg) 
![forks](https://img.shields.io/github/forks/padayali-JD/CVE-2025-25968.svg) 
2025-02-19T05:14:25Z

## CVE-2025-25163
 Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability in Zach Swetz Plugin A/B Image Optimizer allows Path Traversal. This issue affects Plugin A/B Image Optimizer: from n/a through 3.3.

- [https://github.com/RandomRobbieBF/CVE-2025-25163](https://github.com/RandomRobbieBF/CVE-2025-25163) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2025-25163.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2025-25163.svg) 
2025-02-18T10:26:37Z

- [https://github.com/rootharpy/CVE-2025-25163-Nuclei-Template](https://github.com/rootharpy/CVE-2025-25163-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/rootharpy/CVE-2025-25163-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/rootharpy/CVE-2025-25163-Nuclei-Template.svg) 
2025-02-19T04:15:00Z

## CVE-2024-57401
 SQL Injection vulnerability in Uniclare Student portal v.2 and before allows a remote attacker to execute arbitrary code via the Forgot Password function.

- [https://github.com/aksingh82/CVE-2024-57401](https://github.com/aksingh82/CVE-2024-57401) :  
![starts](https://img.shields.io/github/stars/aksingh82/CVE-2024-57401.svg) 
![forks](https://img.shields.io/github/forks/aksingh82/CVE-2024-57401.svg) 
2025-02-19T18:35:27Z

## CVE-2024-57241
 Dedecms 5.71sp1 and earlier is vulnerable to URL redirect. In the web application, a logic error does not judge the input GET request resulting in URL redirection.

- [https://github.com/woshidaheike/CVE-2024-57241](https://github.com/woshidaheike/CVE-2024-57241) :  
![starts](https://img.shields.io/github/stars/woshidaheike/CVE-2024-57241.svg) 
![forks](https://img.shields.io/github/forks/woshidaheike/CVE-2024-57241.svg) 
2025-02-19T10:16:37Z

## CVE-2024-45872
 Bandisoft BandiView 7.05 is vulnerable to Buffer Overflow via sub_0x410d1d. The vulnerability occurs due to insufficient validation of PSD files.

- [https://github.com/bshyuunn/Bandiview-7.05-Vuln-PoC](https://github.com/bshyuunn/Bandiview-7.05-Vuln-PoC) :  
![starts](https://img.shields.io/github/stars/bshyuunn/Bandiview-7.05-Vuln-PoC.svg) 
![forks](https://img.shields.io/github/forks/bshyuunn/Bandiview-7.05-Vuln-PoC.svg) 
2025-02-19T12:50:03Z

## CVE-2024-45871
 Bandisoft BandiView 7.05 is Incorrect Access Control via sub_0x232bd8 resulting in denial of service (DOS).

- [https://github.com/bshyuunn/Bandiview-7.05-Vuln-PoC](https://github.com/bshyuunn/Bandiview-7.05-Vuln-PoC) :  
![starts](https://img.shields.io/github/stars/bshyuunn/Bandiview-7.05-Vuln-PoC.svg) 
![forks](https://img.shields.io/github/forks/bshyuunn/Bandiview-7.05-Vuln-PoC.svg) 
2025-02-19T12:50:03Z

## CVE-2024-45870
 Bandisoft BandiView 7.05 is vulnerable to Incorrect Access Control in sub_0x3d80fc via a crafted POC file.

- [https://github.com/bshyuunn/Bandiview-7.05-Vuln-PoC](https://github.com/bshyuunn/Bandiview-7.05-Vuln-PoC) :  
![starts](https://img.shields.io/github/stars/bshyuunn/Bandiview-7.05-Vuln-PoC.svg) 
![forks](https://img.shields.io/github/forks/bshyuunn/Bandiview-7.05-Vuln-PoC.svg) 
2025-02-19T12:50:03Z

## CVE-2024-43097
 In resizeToAtLeast of SkRegion.cpp, there is a possible out of bounds write due to an integer overflow. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/Mahesh-970/CVE-2024-43097](https://github.com/Mahesh-970/CVE-2024-43097) :  
![starts](https://img.shields.io/github/stars/Mahesh-970/CVE-2024-43097.svg) 
![forks](https://img.shields.io/github/forks/Mahesh-970/CVE-2024-43097.svg) 
2025-02-19T11:14:59Z

## CVE-2024-43090
 In multiple locations, there is a possible cross-user image read due to a missing permission check. This could lead to local information disclosure with User execution privileges needed. User interaction is needed for exploitation.

- [https://github.com/nidhihcl75/frameworks_base_AOSP10_r33_CVE-2024-43090](https://github.com/nidhihcl75/frameworks_base_AOSP10_r33_CVE-2024-43090) :  
![starts](https://img.shields.io/github/stars/nidhihcl75/frameworks_base_AOSP10_r33_CVE-2024-43090.svg) 
![forks](https://img.shields.io/github/forks/nidhihcl75/frameworks_base_AOSP10_r33_CVE-2024-43090.svg) 
2025-02-19T11:23:31Z

## CVE-2024-34716
 PrestaShop is an open source e-commerce web application. A cross-site scripting (XSS) vulnerability that only affects PrestaShops with customer-thread feature flag enabled is present starting from PrestaShop 8.1.0 and prior to PrestaShop 8.1.6. When the customer thread feature flag is enabled through the front-office contact form, a hacker can upload a malicious file containing an XSS that will be executed when an admin opens the attached file in back office. The script injected can access the session and the security token, which allows it to perform any authenticated action in the scope of the administrator's right. This vulnerability is patched in 8.1.6. A workaround is to disable the customer-thread feature-flag.

- [https://github.com/aelmokhtar/CVE-2024-34716](https://github.com/aelmokhtar/CVE-2024-34716) :  
![starts](https://img.shields.io/github/stars/aelmokhtar/CVE-2024-34716.svg) 
![forks](https://img.shields.io/github/forks/aelmokhtar/CVE-2024-34716.svg) 
2024-09-27T10:46:14Z

- [https://github.com/0xDTC/Prestashop-CVE-2024-34716](https://github.com/0xDTC/Prestashop-CVE-2024-34716) :  
![starts](https://img.shields.io/github/stars/0xDTC/Prestashop-CVE-2024-34716.svg) 
![forks](https://img.shields.io/github/forks/0xDTC/Prestashop-CVE-2024-34716.svg) 
2025-01-07T12:51:43Z

- [https://github.com/TU-M/Trickster-HTB](https://github.com/TU-M/Trickster-HTB) :  
![starts](https://img.shields.io/github/stars/TU-M/Trickster-HTB.svg) 
![forks](https://img.shields.io/github/forks/TU-M/Trickster-HTB.svg) 
2025-02-19T17:54:10Z

## CVE-2024-32651
 changedetection.io is an open source web page change detection, website watcher, restock monitor and notification service. There is a Server Side Template Injection (SSTI) in Jinja2 that allows Remote Command Execution on the server host. Attackers can run any system command without any restriction and they could use a reverse shell. The impact is critical as the attacker can completely takeover the server machine. This can be reduced if changedetection is behind a login page, but this isn't required by the application (not by default and not enforced).

- [https://github.com/s0ck3t-s3c/CVE-2024-32651-changedetection-RCE](https://github.com/s0ck3t-s3c/CVE-2024-32651-changedetection-RCE) :  
![starts](https://img.shields.io/github/stars/s0ck3t-s3c/CVE-2024-32651-changedetection-RCE.svg) 
![forks](https://img.shields.io/github/forks/s0ck3t-s3c/CVE-2024-32651-changedetection-RCE.svg) 
2024-09-18T09:16:23Z

- [https://github.com/zcrosman/cve-2024-32651](https://github.com/zcrosman/cve-2024-32651) :  
![starts](https://img.shields.io/github/stars/zcrosman/cve-2024-32651.svg) 
![forks](https://img.shields.io/github/forks/zcrosman/cve-2024-32651.svg) 
2024-05-26T21:42:08Z

- [https://github.com/TU-M/Trickster-HTB](https://github.com/TU-M/Trickster-HTB) :  
![starts](https://img.shields.io/github/stars/TU-M/Trickster-HTB.svg) 
![forks](https://img.shields.io/github/forks/TU-M/Trickster-HTB.svg) 
2025-02-19T17:54:10Z

## CVE-2024-13375
 The Adifier System plugin for WordPress is vulnerable to privilege escalation via account takeover in all versions up to, and including, 3.1.7. This is due to the plugin not properly validating a user's identity prior to updating their details like password through the adifier_recover() function. This makes it possible for unauthenticated attackers to change arbitrary user's passwords, including administrators, and leverage that to gain access to their account.

- [https://github.com/McTavishSue/CVE-2024-13375](https://github.com/McTavishSue/CVE-2024-13375) :  
![starts](https://img.shields.io/github/stars/McTavishSue/CVE-2024-13375.svg) 
![forks](https://img.shields.io/github/forks/McTavishSue/CVE-2024-13375.svg) 
2025-02-19T14:27:23Z

## CVE-2024-13159
 Absolute path traversal in Ivanti EPM before the 2024 January-2025 Security Update and 2022 SU6 January-2025 Security Update allows a remote unauthenticated attacker to leak sensitive information.

- [https://github.com/horizon3ai/Ivanti-EPM-Coercion-Vulnerabilities](https://github.com/horizon3ai/Ivanti-EPM-Coercion-Vulnerabilities) :  
![starts](https://img.shields.io/github/stars/horizon3ai/Ivanti-EPM-Coercion-Vulnerabilities.svg) 
![forks](https://img.shields.io/github/forks/horizon3ai/Ivanti-EPM-Coercion-Vulnerabilities.svg) 
2025-02-19T12:28:04Z

## CVE-2023-44487
 The HTTP/2 protocol allows a denial of service (server resource consumption) because request cancellation can reset many streams quickly, as exploited in the wild in August through October 2023.

- [https://github.com/bcdannyboy/CVE-2023-44487](https://github.com/bcdannyboy/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/bcdannyboy/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/bcdannyboy/CVE-2023-44487.svg) 
2024-01-08T11:12:08Z

- [https://github.com/secengjeff/rapidresetclient](https://github.com/secengjeff/rapidresetclient) :  
![starts](https://img.shields.io/github/stars/secengjeff/rapidresetclient.svg) 
![forks](https://img.shields.io/github/forks/secengjeff/rapidresetclient.svg) 
2023-10-30T20:22:37Z

- [https://github.com/imabee101/CVE-2023-44487](https://github.com/imabee101/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/imabee101/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/imabee101/CVE-2023-44487.svg) 
2023-10-13T11:19:10Z

- [https://github.com/terrorist/HTTP-2-Rapid-Reset-Client](https://github.com/terrorist/HTTP-2-Rapid-Reset-Client) :  
![starts](https://img.shields.io/github/stars/terrorist/HTTP-2-Rapid-Reset-Client.svg) 
![forks](https://img.shields.io/github/forks/terrorist/HTTP-2-Rapid-Reset-Client.svg) 
2023-11-24T20:19:44Z

- [https://github.com/studiogangster/CVE-2023-44487](https://github.com/studiogangster/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/studiogangster/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/studiogangster/CVE-2023-44487.svg) 
2023-10-16T12:32:50Z

- [https://github.com/nxenon/cve-2023-44487](https://github.com/nxenon/cve-2023-44487) :  
![starts](https://img.shields.io/github/stars/nxenon/cve-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/nxenon/cve-2023-44487.svg) 
2023-11-10T08:39:14Z

- [https://github.com/ndrscodes/http2-rst-stream-attacker](https://github.com/ndrscodes/http2-rst-stream-attacker) :  
![starts](https://img.shields.io/github/stars/ndrscodes/http2-rst-stream-attacker.svg) 
![forks](https://img.shields.io/github/forks/ndrscodes/http2-rst-stream-attacker.svg) 
2024-01-11T17:44:09Z

- [https://github.com/ReToCode/golang-CVE-2023-44487](https://github.com/ReToCode/golang-CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/ReToCode/golang-CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/ReToCode/golang-CVE-2023-44487.svg) 
2023-10-26T15:01:38Z

- [https://github.com/threatlabindonesia/CVE-2023-44487-HTTP-2-Rapid-Reset-Exploit-PoC](https://github.com/threatlabindonesia/CVE-2023-44487-HTTP-2-Rapid-Reset-Exploit-PoC) :  
![starts](https://img.shields.io/github/stars/threatlabindonesia/CVE-2023-44487-HTTP-2-Rapid-Reset-Exploit-PoC.svg) 
![forks](https://img.shields.io/github/forks/threatlabindonesia/CVE-2023-44487-HTTP-2-Rapid-Reset-Exploit-PoC.svg) 
2024-12-03T15:03:04Z

- [https://github.com/pabloec20/rapidreset](https://github.com/pabloec20/rapidreset) :  
![starts](https://img.shields.io/github/stars/pabloec20/rapidreset.svg) 
![forks](https://img.shields.io/github/forks/pabloec20/rapidreset.svg) 
2023-10-12T07:11:17Z

- [https://github.com/BMG-Black-Magic/CVE-2023-44487](https://github.com/BMG-Black-Magic/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/BMG-Black-Magic/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/BMG-Black-Magic/CVE-2023-44487.svg) 
2025-02-19T08:16:34Z

- [https://github.com/aulauniversal/CVE-2023-44487](https://github.com/aulauniversal/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/aulauniversal/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/aulauniversal/CVE-2023-44487.svg) 
2025-01-18T11:39:54Z

- [https://github.com/sn130hk/CVE-2023-44487](https://github.com/sn130hk/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/sn130hk/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/sn130hk/CVE-2023-44487.svg) 
2024-05-26T13:01:01Z

- [https://github.com/TYuan0816/cve-2023-44487](https://github.com/TYuan0816/cve-2023-44487) :  
![starts](https://img.shields.io/github/stars/TYuan0816/cve-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/TYuan0816/cve-2023-44487.svg) 
2024-04-22T08:56:39Z

- [https://github.com/sigridou/CVE-2023-44487-](https://github.com/sigridou/CVE-2023-44487-) :  
![starts](https://img.shields.io/github/stars/sigridou/CVE-2023-44487-.svg) 
![forks](https://img.shields.io/github/forks/sigridou/CVE-2023-44487-.svg) 
2023-12-11T23:19:25Z

- [https://github.com/ByteHackr/CVE-2023-44487](https://github.com/ByteHackr/CVE-2023-44487) :  
![starts](https://img.shields.io/github/stars/ByteHackr/CVE-2023-44487.svg) 
![forks](https://img.shields.io/github/forks/ByteHackr/CVE-2023-44487.svg) 
2023-10-12T03:30:35Z

## CVE-2023-20198
 Cisco is providing an update for the ongoing investigation into observed exploitation of the web UI feature in Cisco IOS XE Software. We are updating the list of fixed releases and adding the Software Checker. Our investigation has determined that the actors exploited two previously unknown issues. The attacker first exploited CVE-2023-20198 to gain initial access and issued a privilege 15 command to create a local user and password combination. This allowed the user to log in with normal user access. The attacker then exploited another component of the web UI feature, leveraging the new local user to elevate privilege to root and write the implant to the file system. Cisco has assigned CVE-2023-20273 to this issue. CVE-2023-20198 has been assigned a CVSS Score of 10.0. CVE-2023-20273 has been assigned a CVSS Score of 7.2. Both of these CVEs are being tracked by CSCwh87343.

- [https://github.com/smokeintheshell/CVE-2023-20198](https://github.com/smokeintheshell/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/smokeintheshell/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/smokeintheshell/CVE-2023-20198.svg) 
2023-12-07T22:34:43Z

- [https://github.com/vulncheck-oss/cisco-ios-xe-implant-scanner](https://github.com/vulncheck-oss/cisco-ios-xe-implant-scanner) :  
![starts](https://img.shields.io/github/stars/vulncheck-oss/cisco-ios-xe-implant-scanner.svg) 
![forks](https://img.shields.io/github/forks/vulncheck-oss/cisco-ios-xe-implant-scanner.svg) 
2024-10-28T14:20:11Z

- [https://github.com/W01fh4cker/CVE-2023-20198-RCE](https://github.com/W01fh4cker/CVE-2023-20198-RCE) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/CVE-2023-20198-RCE.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/CVE-2023-20198-RCE.svg) 
2024-04-25T07:32:57Z

- [https://github.com/fox-it/cisco-ios-xe-implant-detection](https://github.com/fox-it/cisco-ios-xe-implant-detection) :  
![starts](https://img.shields.io/github/stars/fox-it/cisco-ios-xe-implant-detection.svg) 
![forks](https://img.shields.io/github/forks/fox-it/cisco-ios-xe-implant-detection.svg) 
2023-11-07T12:21:26Z

- [https://github.com/ZephrFish/CVE-2023-20198-Checker](https://github.com/ZephrFish/CVE-2023-20198-Checker) :  
![starts](https://img.shields.io/github/stars/ZephrFish/CVE-2023-20198-Checker.svg) 
![forks](https://img.shields.io/github/forks/ZephrFish/CVE-2023-20198-Checker.svg) 
2023-10-23T00:19:21Z

- [https://github.com/Shadow0ps/CVE-2023-20198-Scanner](https://github.com/Shadow0ps/CVE-2023-20198-Scanner) :  
![starts](https://img.shields.io/github/stars/Shadow0ps/CVE-2023-20198-Scanner.svg) 
![forks](https://img.shields.io/github/forks/Shadow0ps/CVE-2023-20198-Scanner.svg) 
2023-10-24T18:17:43Z

- [https://github.com/hackingyseguridad/nmap](https://github.com/hackingyseguridad/nmap) :  
![starts](https://img.shields.io/github/stars/hackingyseguridad/nmap.svg) 
![forks](https://img.shields.io/github/forks/hackingyseguridad/nmap.svg) 
2024-04-17T11:38:44Z

- [https://github.com/Atea-Redteam/CVE-2023-20198](https://github.com/Atea-Redteam/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/Atea-Redteam/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/Atea-Redteam/CVE-2023-20198.svg) 
2023-10-23T20:19:49Z

- [https://github.com/Tounsi007/CVE-2023-20198](https://github.com/Tounsi007/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/Tounsi007/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/Tounsi007/CVE-2023-20198.svg) 
2023-10-17T14:02:51Z

- [https://github.com/Pushkarup/CVE-2023-20198](https://github.com/Pushkarup/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/Pushkarup/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/Pushkarup/CVE-2023-20198.svg) 
2023-10-23T19:10:41Z

- [https://github.com/RevoltSecurities/CVE-2023-20198](https://github.com/RevoltSecurities/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/RevoltSecurities/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/RevoltSecurities/CVE-2023-20198.svg) 
2023-11-03T13:54:43Z

- [https://github.com/XiaomingX/cve-2023-20198-poc](https://github.com/XiaomingX/cve-2023-20198-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2023-20198-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2023-20198-poc.svg) 
2024-11-22T04:12:11Z

- [https://github.com/iveresk/cve-2023-20198](https://github.com/iveresk/cve-2023-20198) :  
![starts](https://img.shields.io/github/stars/iveresk/cve-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/iveresk/cve-2023-20198.svg) 
2023-10-20T21:51:52Z

- [https://github.com/sohaibeb/CVE-2023-20198](https://github.com/sohaibeb/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/sohaibeb/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/sohaibeb/CVE-2023-20198.svg) 
2025-02-19T16:14:24Z

- [https://github.com/Vulnmachines/Cisco_CVE-2023-20198](https://github.com/Vulnmachines/Cisco_CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/Cisco_CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/Cisco_CVE-2023-20198.svg) 
2023-12-11T10:44:03Z

- [https://github.com/alekos3/CVE_2023_20198_Detector](https://github.com/alekos3/CVE_2023_20198_Detector) :  
![starts](https://img.shields.io/github/stars/alekos3/CVE_2023_20198_Detector.svg) 
![forks](https://img.shields.io/github/forks/alekos3/CVE_2023_20198_Detector.svg) 
2023-10-31T01:53:47Z

- [https://github.com/mr-r3b00t/CVE-2023-20198-IOS-XE-Scanner](https://github.com/mr-r3b00t/CVE-2023-20198-IOS-XE-Scanner) :  
![starts](https://img.shields.io/github/stars/mr-r3b00t/CVE-2023-20198-IOS-XE-Scanner.svg) 
![forks](https://img.shields.io/github/forks/mr-r3b00t/CVE-2023-20198-IOS-XE-Scanner.svg) 
2023-10-25T11:40:13Z

- [https://github.com/securityphoenix/cisco-CVE-2023-20198-tester](https://github.com/securityphoenix/cisco-CVE-2023-20198-tester) :  
![starts](https://img.shields.io/github/stars/securityphoenix/cisco-CVE-2023-20198-tester.svg) 
![forks](https://img.shields.io/github/forks/securityphoenix/cisco-CVE-2023-20198-tester.svg) 
2023-10-20T14:43:32Z

- [https://github.com/IceBreakerCode/CVE-2023-20198](https://github.com/IceBreakerCode/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/IceBreakerCode/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/IceBreakerCode/CVE-2023-20198.svg) 
2023-10-25T21:20:41Z

- [https://github.com/kacem-expereo/CVE-2023-20198](https://github.com/kacem-expereo/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/kacem-expereo/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/kacem-expereo/CVE-2023-20198.svg) 
2023-10-24T09:42:38Z

- [https://github.com/alekos3/CVE_2023_20198_Remediator](https://github.com/alekos3/CVE_2023_20198_Remediator) :  
![starts](https://img.shields.io/github/stars/alekos3/CVE_2023_20198_Remediator.svg) 
![forks](https://img.shields.io/github/forks/alekos3/CVE_2023_20198_Remediator.svg) 
2023-10-31T01:55:58Z

- [https://github.com/codeb0ss/CVE-2023-20198-PoC](https://github.com/codeb0ss/CVE-2023-20198-PoC) :  
![starts](https://img.shields.io/github/stars/codeb0ss/CVE-2023-20198-PoC.svg) 
![forks](https://img.shields.io/github/forks/codeb0ss/CVE-2023-20198-PoC.svg) 
2023-12-13T22:50:07Z

- [https://github.com/emomeni/Simple-Ansible-for-CVE-2023-20198](https://github.com/emomeni/Simple-Ansible-for-CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/emomeni/Simple-Ansible-for-CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/emomeni/Simple-Ansible-for-CVE-2023-20198.svg) 
2023-10-17T18:46:32Z

- [https://github.com/ohlawd/CVE-2023-20198](https://github.com/ohlawd/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/ohlawd/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/ohlawd/CVE-2023-20198.svg) 
2023-10-25T21:03:24Z

- [https://github.com/sanan2004/CVE-2023-20198](https://github.com/sanan2004/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/sanan2004/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/sanan2004/CVE-2023-20198.svg) 
2024-08-26T08:31:18Z

- [https://github.com/JoyGhoshs/CVE-2023-20198](https://github.com/JoyGhoshs/CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/JoyGhoshs/CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/JoyGhoshs/CVE-2023-20198.svg) 
2023-10-18T07:58:28Z

- [https://github.com/reket99/Cisco_CVE-2023-20198](https://github.com/reket99/Cisco_CVE-2023-20198) :  
![starts](https://img.shields.io/github/stars/reket99/Cisco_CVE-2023-20198.svg) 
![forks](https://img.shields.io/github/forks/reket99/Cisco_CVE-2023-20198.svg) 
2023-10-19T13:44:22Z

- [https://github.com/raystr-atearedteam/CVE-2023-20198-checker](https://github.com/raystr-atearedteam/CVE-2023-20198-checker) :  
![starts](https://img.shields.io/github/stars/raystr-atearedteam/CVE-2023-20198-checker.svg) 
![forks](https://img.shields.io/github/forks/raystr-atearedteam/CVE-2023-20198-checker.svg) 
2023-10-17T07:52:06Z

- [https://github.com/netbell/CVE-2023-20198-Fix](https://github.com/netbell/CVE-2023-20198-Fix) :  
![starts](https://img.shields.io/github/stars/netbell/CVE-2023-20198-Fix.svg) 
![forks](https://img.shields.io/github/forks/netbell/CVE-2023-20198-Fix.svg) 
2023-12-09T17:03:38Z

- [https://github.com/AhmedMansour93/Event-ID-193-Rule-Name-SOC231-Cisco-IOS-XE-Web-UI-ZeroDay-CVE-2023-20198-](https://github.com/AhmedMansour93/Event-ID-193-Rule-Name-SOC231-Cisco-IOS-XE-Web-UI-ZeroDay-CVE-2023-20198-) :  
![starts](https://img.shields.io/github/stars/AhmedMansour93/Event-ID-193-Rule-Name-SOC231-Cisco-IOS-XE-Web-UI-ZeroDay-CVE-2023-20198-.svg) 
![forks](https://img.shields.io/github/forks/AhmedMansour93/Event-ID-193-Rule-Name-SOC231-Cisco-IOS-XE-Web-UI-ZeroDay-CVE-2023-20198-.svg) 
2024-09-13T09:18:41Z

## CVE-2021-26291
 Apache Maven will follow repositories that are defined in a dependencys Project Object Model (pom) which may be surprising to some users, resulting in potential risk if a malicious actor takes over that repository or is able to insert themselves into a position to pretend to be that repository. Maven is changing the default behavior in 3.8.1+ to no longer follow http (non-SSL) repository references by default. More details available in the referenced urls. If you are currently using a repository manager to govern the repositories used by your builds, you are unaffected by the risks present in the legacy behavior, and are unaffected by this vulnerability and change to default behavior. See this link for more information about repository management: https://maven.apache.org/repository-management.html

- [https://github.com/jpmartins/MinimalReproducer](https://github.com/jpmartins/MinimalReproducer) :  
![starts](https://img.shields.io/github/stars/jpmartins/MinimalReproducer.svg) 
![forks](https://img.shields.io/github/forks/jpmartins/MinimalReproducer.svg) 
2025-02-19T16:14:06Z

