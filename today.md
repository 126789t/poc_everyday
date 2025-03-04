# 2025-03-04
## CVE-2024-56801
 Tasklists provides plugin tasklists for GLPI. Versions prior to 2.0.4 have a blind SQL injection vulnerability. Version 2.0.4 contains a patch for the vulnerability.

- [https://github.com/kz0xpwn/CVE-2024-56801](https://github.com/kz0xpwn/CVE-2024-56801) :  
![starts](https://img.shields.io/github/stars/kz0xpwn/CVE-2024-56801.svg) 
![forks](https://img.shields.io/github/forks/kz0xpwn/CVE-2024-56801.svg) 
2025-03-04T06:34:04Z

## CVE-2024-49138
 Windows Common Log File System Driver Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2024-49138-POC](https://github.com/MrAle98/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2024-49138-POC.svg) 
2025-02-14T22:04:41Z

- [https://github.com/aspire20x/CVE-2024-49138-POC](https://github.com/aspire20x/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/aspire20x/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/aspire20x/CVE-2024-49138-POC.svg) 
2025-03-04T12:29:46Z

- [https://github.com/bananoname/CVE-2024-49138-POC](https://github.com/bananoname/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/bananoname/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/bananoname/CVE-2024-49138-POC.svg) 
2025-01-21T02:06:00Z

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
2025-03-04T07:08:14Z

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

- [https://github.com/SalehLardhi/CVE-2024-24919](https://github.com/SalehLardhi/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/SalehLardhi/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/SalehLardhi/CVE-2024-24919.svg) 
2024-06-11T03:37:04Z

- [https://github.com/0xlf/CVE-2024-24919](https://github.com/0xlf/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/0xlf/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/0xlf/CVE-2024-24919.svg) 
2025-03-04T08:01:41Z

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

- [https://github.com/Jutrm/cve-2024-24919](https://github.com/Jutrm/cve-2024-24919) :  
![starts](https://img.shields.io/github/stars/Jutrm/cve-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Jutrm/cve-2024-24919.svg) 
2024-07-26T15:23:03Z

- [https://github.com/nicolvsrlr27/CVE-2024-24919](https://github.com/nicolvsrlr27/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/nicolvsrlr27/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/nicolvsrlr27/CVE-2024-24919.svg) 
2024-06-01T03:05:35Z

- [https://github.com/satriarizka/CVE-2024-24919](https://github.com/satriarizka/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/satriarizka/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/satriarizka/CVE-2024-24919.svg) 
2024-05-31T08:37:35Z

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

- [https://github.com/Vulnpire/CVE-2024-24919](https://github.com/Vulnpire/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/Vulnpire/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Vulnpire/CVE-2024-24919.svg) 
2024-05-31T11:36:26Z

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

## CVE-2024-21513
 Versions of the package langchain-experimental from 0.0.15 and before 0.0.21 are vulnerable to Arbitrary Code Execution when retrieving values from the database, the code will attempt to call 'eval' on all values. An attacker can exploit this vulnerability and execute arbitrary python code if they can control the input prompt and the server is configured with VectorSQLDatabaseChain.**Notes:**Impact on the Confidentiality, Integrity and Availability of the vulnerable component:Confidentiality: Code execution happens within the impacted component, in this case langchain-experimental, so all resources are necessarily accessible.Integrity: There is nothing protected by the impacted component inherently. Although anything returned from the component counts as 'information' for which the trustworthiness can be compromised.Availability: The loss of availability isn't caused by the attack itself, but it happens as a result during the attacker's post-exploitation steps.Impact on the Confidentiality, Integrity and Availability of the subsequent system:As a legitimate low-privileged user of the package (PR:L) the attacker does not have more access to data owned by the package as a result of this vulnerability than they did with normal usage (e.g. can query the DB). The unintended action that one can perform by breaking out of the app environment and exfiltrating files, making remote connections etc. happens during the post exploitation phase in the subsequent system - in this case, the OS.AT:P: An attacker needs to be able to influence the input prompt, whilst the server is configured with the VectorSQLDatabaseChain plugin.

- [https://github.com/SavageSanta11/Reproduce-CVE-2024-21513](https://github.com/SavageSanta11/Reproduce-CVE-2024-21513) :  
![starts](https://img.shields.io/github/stars/SavageSanta11/Reproduce-CVE-2024-21513.svg) 
![forks](https://img.shields.io/github/forks/SavageSanta11/Reproduce-CVE-2024-21513.svg) 
2025-03-04T13:55:04Z

## CVE-2024-8963
 Path Traversal in the Ivanti CSA before 4.6 Patch 519 allows a remote unauthenticated attacker to access restricted functionality.

- [https://github.com/flyingllama87/CVE-2024-8190-unauth](https://github.com/flyingllama87/CVE-2024-8190-unauth) :  
![starts](https://img.shields.io/github/stars/flyingllama87/CVE-2024-8190-unauth.svg) 
![forks](https://img.shields.io/github/forks/flyingllama87/CVE-2024-8190-unauth.svg) 
2025-03-04T14:16:51Z

- [https://github.com/patfire94/CVE-2024-8963](https://github.com/patfire94/CVE-2024-8963) :  
![starts](https://img.shields.io/github/stars/patfire94/CVE-2024-8963.svg) 
![forks](https://img.shields.io/github/forks/patfire94/CVE-2024-8963.svg) 
2024-11-13T20:10:03Z

## CVE-2024-8190
 An OS command injection vulnerability in Ivanti Cloud Services Appliance versions 4.6 Patch 518 and before allows a remote authenticated attacker to obtain remote code execution. The attacker must have admin level privileges to exploit this vulnerability.

- [https://github.com/horizon3ai/CVE-2024-8190](https://github.com/horizon3ai/CVE-2024-8190) :  
![starts](https://img.shields.io/github/stars/horizon3ai/CVE-2024-8190.svg) 
![forks](https://img.shields.io/github/forks/horizon3ai/CVE-2024-8190.svg) 
2024-09-16T15:43:44Z

- [https://github.com/flyingllama87/CVE-2024-8190-unauth](https://github.com/flyingllama87/CVE-2024-8190-unauth) :  
![starts](https://img.shields.io/github/stars/flyingllama87/CVE-2024-8190-unauth.svg) 
![forks](https://img.shields.io/github/forks/flyingllama87/CVE-2024-8190-unauth.svg) 
2025-03-04T14:16:51Z

- [https://github.com/tequilasunsh1ne/ivanti_CVE_2024_8190](https://github.com/tequilasunsh1ne/ivanti_CVE_2024_8190) :  
![starts](https://img.shields.io/github/stars/tequilasunsh1ne/ivanti_CVE_2024_8190.svg) 
![forks](https://img.shields.io/github/forks/tequilasunsh1ne/ivanti_CVE_2024_8190.svg) 
2024-10-08T09:35:01Z

## CVE-2024-4650
 A vulnerability classified as problematic was found in Campcodes Complete Web-Based School Management System 1.0. This vulnerability affects unknown code of the file /view/student_due_payment.php. The manipulation of the argument due_month leads to cross site scripting. The attack can be initiated remotely. The exploit has been disclosed to the public and may be used. VDB-263494 is the identifier assigned to this vulnerability.

- [https://github.com/Somchandra17/CVE-2024-46507](https://github.com/Somchandra17/CVE-2024-46507) :  
![starts](https://img.shields.io/github/stars/Somchandra17/CVE-2024-46507.svg) 
![forks](https://img.shields.io/github/forks/Somchandra17/CVE-2024-46507.svg) 
2025-03-04T00:54:57Z

## CVE-2024-2876
 The Email Subscribers by Icegram Express  Email Marketing, Newsletters, Automation for WordPress & WooCommerce plugin for WordPress is vulnerable to SQL Injection via the 'run' function of the 'IG_ES_Subscribers_Query' class in all versions up to, and including, 5.7.14 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/c0d3zilla/CVE-2024-2876](https://github.com/c0d3zilla/CVE-2024-2876) :  
![starts](https://img.shields.io/github/stars/c0d3zilla/CVE-2024-2876.svg) 
![forks](https://img.shields.io/github/forks/c0d3zilla/CVE-2024-2876.svg) 
2024-04-25T09:55:55Z

- [https://github.com/Quantum-Hacker/CVE-2024-2876](https://github.com/Quantum-Hacker/CVE-2024-2876) :  
![starts](https://img.shields.io/github/stars/Quantum-Hacker/CVE-2024-2876.svg) 
![forks](https://img.shields.io/github/forks/Quantum-Hacker/CVE-2024-2876.svg) 
2025-01-20T18:54:22Z

- [https://github.com/0xAgun/CVE-2024-2876](https://github.com/0xAgun/CVE-2024-2876) :  
![starts](https://img.shields.io/github/stars/0xAgun/CVE-2024-2876.svg) 
![forks](https://img.shields.io/github/forks/0xAgun/CVE-2024-2876.svg) 
2024-09-17T05:54:52Z

- [https://github.com/0xlf/CVE-2024-2876](https://github.com/0xlf/CVE-2024-2876) :  
![starts](https://img.shields.io/github/stars/0xlf/CVE-2024-2876.svg) 
![forks](https://img.shields.io/github/forks/0xlf/CVE-2024-2876.svg) 
2025-03-04T08:00:25Z

- [https://github.com/issamjr/CVE-2024-2876](https://github.com/issamjr/CVE-2024-2876) :  
![starts](https://img.shields.io/github/stars/issamjr/CVE-2024-2876.svg) 
![forks](https://img.shields.io/github/forks/issamjr/CVE-2024-2876.svg) 
2024-11-15T22:50:43Z

# 2025-03-03
## CVE-2025-26326
 A vulnerability in the remote connection complements of the NVDA (Nonvisual Desktop Access) 2024.4.1 and 2024.4.2 was identified, which allows an attacker to obtain total control of the remote system when guessing a weak password. The problem occurs because the complements accept any password typed by the user and do not have an additional authentication or checking mechanism by the computer that will be accessed. Tests indicate that over 1,000 systems use easy to guess passwords, many with less than 4 to 6 characters, including common sequences. This enables brute strength or attempt and error attacks on the part of malicious invaders. Vulnerability can be explored by a remote striker who knows or can guess the password used in the connection. As a result, the invader gets complete access to the affected system and can run commands, modify files and compromise user security.

- [https://github.com/azurejoga/CVE-2025-26326](https://github.com/azurejoga/CVE-2025-26326) :  
![starts](https://img.shields.io/github/stars/azurejoga/CVE-2025-26326.svg) 
![forks](https://img.shields.io/github/forks/azurejoga/CVE-2025-26326.svg) 
2025-03-03T16:55:06Z

## CVE-2024-56340
 IBM Cognos Analytics 11.2.0 through 11.2.4 FP5 is vulnerable to local file inclusion vulnerability, allowing an attacker to access sensitive files by inserting path traversal payloads inside the deficon parameter.

- [https://github.com/MarioTesoro/CVE-2024-56340](https://github.com/MarioTesoro/CVE-2024-56340) :  
![starts](https://img.shields.io/github/stars/MarioTesoro/CVE-2024-56340.svg) 
![forks](https://img.shields.io/github/forks/MarioTesoro/CVE-2024-56340.svg) 
2025-03-03T17:10:18Z

## CVE-2024-56337
 Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability in Apache Tomcat.This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.1, from 10.1.0-M1 through 10.1.33, from 9.0.0.M1 through 9.0.97.The mitigation for CVE-2024-50379 was incomplete.Users running Tomcat on a case insensitive file system with the default servlet write enabled (readonly initialisation parameter set to the non-default value of false) may need additional configuration to fully mitigate CVE-2024-50379 depending on which version of Java they are using with Tomcat:- running on Java 8 or Java 11: the system propertysun.io.useCanonCaches must be explicitly set to false (it defaults to true)- running on Java 17: thesystem property sun.io.useCanonCaches, if set, must be set to false(it defaults to false)- running on Java 21 onwards: no further configuration is required(the system property and the problematic cache have been removed)Tomcat 11.0.3, 10.1.35 and 9.0.99 onwards will include checks thatsun.io.useCanonCaches is set appropriately before allowing the default servlet to be write enabled on a case insensitive file system. Tomcat will also setsun.io.useCanonCaches to false by default where it can.

- [https://github.com/SleepingBag945/CVE-2024-50379](https://github.com/SleepingBag945/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/SleepingBag945/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/SleepingBag945/CVE-2024-50379.svg) 
2024-12-23T07:30:27Z

- [https://github.com/shoddykilom/CVE-2024-50379](https://github.com/shoddykilom/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/shoddykilom/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/shoddykilom/CVE-2024-50379.svg) 
2025-03-03T22:22:54Z

## CVE-2024-50379
 Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability during JSP compilation in Apache Tomcat permits an RCE on case insensitive file systems when the default servlet is enabled for write (non-default configuration).This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.1, from 10.1.0-M1 through 10.1.33, from 9.0.0.M1 through 9.0.97.Users are recommended to upgrade to version 11.0.2, 10.1.34 or 9.0.98, which fixes the issue.

- [https://github.com/SleepingBag945/CVE-2024-50379](https://github.com/SleepingBag945/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/SleepingBag945/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/SleepingBag945/CVE-2024-50379.svg) 
2024-12-23T07:30:27Z

- [https://github.com/ph0ebus/Tomcat-CVE-2024-50379-Poc](https://github.com/ph0ebus/Tomcat-CVE-2024-50379-Poc) :  
![starts](https://img.shields.io/github/stars/ph0ebus/Tomcat-CVE-2024-50379-Poc.svg) 
![forks](https://img.shields.io/github/forks/ph0ebus/Tomcat-CVE-2024-50379-Poc.svg) 
2024-12-21T08:56:44Z

- [https://github.com/iSee857/CVE-2024-50379-PoC](https://github.com/iSee857/CVE-2024-50379-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2024-50379-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2024-50379-PoC.svg) 
2024-12-20T05:41:23Z

- [https://github.com/lizhianyuguangming/CVE-2024-50379-exp](https://github.com/lizhianyuguangming/CVE-2024-50379-exp) :  
![starts](https://img.shields.io/github/stars/lizhianyuguangming/CVE-2024-50379-exp.svg) 
![forks](https://img.shields.io/github/forks/lizhianyuguangming/CVE-2024-50379-exp.svg) 
2024-12-31T07:11:13Z

- [https://github.com/v3153/CVE-2024-50379-POC](https://github.com/v3153/CVE-2024-50379-POC) :  
![starts](https://img.shields.io/github/stars/v3153/CVE-2024-50379-POC.svg) 
![forks](https://img.shields.io/github/forks/v3153/CVE-2024-50379-POC.svg) 
2024-12-26T15:22:46Z

- [https://github.com/dragonked2/CVE-2024-50379-POC](https://github.com/dragonked2/CVE-2024-50379-POC) :  
![starts](https://img.shields.io/github/stars/dragonked2/CVE-2024-50379-POC.svg) 
![forks](https://img.shields.io/github/forks/dragonked2/CVE-2024-50379-POC.svg) 
2024-12-25T19:01:10Z

- [https://github.com/JFOZ1010/Nuclei-Template-CVE-2024-50379](https://github.com/JFOZ1010/Nuclei-Template-CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/JFOZ1010/Nuclei-Template-CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/JFOZ1010/Nuclei-Template-CVE-2024-50379.svg) 
2024-12-20T03:54:28Z

- [https://github.com/yiliufeng168/CVE-2024-50379-POC](https://github.com/yiliufeng168/CVE-2024-50379-POC) :  
![starts](https://img.shields.io/github/stars/yiliufeng168/CVE-2024-50379-POC.svg) 
![forks](https://img.shields.io/github/forks/yiliufeng168/CVE-2024-50379-POC.svg) 
2024-12-18T20:18:39Z

- [https://github.com/pwnosec/CVE-2024-50379](https://github.com/pwnosec/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/pwnosec/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/pwnosec/CVE-2024-50379.svg) 
2025-01-23T11:40:26Z

- [https://github.com/dear-cell/CVE-2024-50379](https://github.com/dear-cell/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/dear-cell/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/dear-cell/CVE-2024-50379.svg) 
2024-12-23T14:13:11Z

- [https://github.com/Alchemist3dot14/CVE-2024-50379](https://github.com/Alchemist3dot14/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/Alchemist3dot14/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/Alchemist3dot14/CVE-2024-50379.svg) 
2024-12-20T21:55:31Z

- [https://github.com/shoddykilom/CVE-2024-50379](https://github.com/shoddykilom/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/shoddykilom/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/shoddykilom/CVE-2024-50379.svg) 
2025-03-03T22:22:54Z

- [https://github.com/dkstar11q/CVE-2024-50379-nuclei](https://github.com/dkstar11q/CVE-2024-50379-nuclei) :  
![starts](https://img.shields.io/github/stars/dkstar11q/CVE-2024-50379-nuclei.svg) 
![forks](https://img.shields.io/github/forks/dkstar11q/CVE-2024-50379-nuclei.svg) 
2024-12-25T21:51:37Z

## CVE-2024-42009
 A Cross-Site Scripting vulnerability in Roundcube through 1.5.7 and 1.6.x through 1.6.7 allows a remote attacker to steal and send emails of a victim via a crafted e-mail message that abuses a Desanitization issue in message_body() in program/actions/mail/show.php.

- [https://github.com/0xbassiouny1337/CVE-2024-42009](https://github.com/0xbassiouny1337/CVE-2024-42009) :  
![starts](https://img.shields.io/github/stars/0xbassiouny1337/CVE-2024-42009.svg) 
![forks](https://img.shields.io/github/forks/0xbassiouny1337/CVE-2024-42009.svg) 
2025-02-12T00:50:17Z

- [https://github.com/Bhanunamikaze/CVE-2024-42009](https://github.com/Bhanunamikaze/CVE-2024-42009) :  
![starts](https://img.shields.io/github/stars/Bhanunamikaze/CVE-2024-42009.svg) 
![forks](https://img.shields.io/github/forks/Bhanunamikaze/CVE-2024-42009.svg) 
2025-03-03T20:13:07Z

## CVE-2024-25600
 Improper Control of Generation of Code ('Code Injection') vulnerability in Codeer Limited Bricks Builder allows Code Injection.This issue affects Bricks Builder: from n/a through 1.9.6.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-03T10:37:09Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/Chocapikk/CVE-2024-25600](https://github.com/Chocapikk/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-25600.svg) 
2024-02-25T21:50:09Z

- [https://github.com/K3ysTr0K3R/CVE-2024-25600-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-25600-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-25600-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-25600-EXPLOIT.svg) 
2024-03-01T09:46:56Z

- [https://github.com/Christbowel/CVE-2024-25600_Nuclei-Template](https://github.com/Christbowel/CVE-2024-25600_Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/Christbowel/CVE-2024-25600_Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/Christbowel/CVE-2024-25600_Nuclei-Template.svg) 
2024-02-21T02:11:08Z

- [https://github.com/Tornad0007/CVE-2024-25600-Bricks-Builder-plugin-for-WordPress](https://github.com/Tornad0007/CVE-2024-25600-Bricks-Builder-plugin-for-WordPress) :  
![starts](https://img.shields.io/github/stars/Tornad0007/CVE-2024-25600-Bricks-Builder-plugin-for-WordPress.svg) 
![forks](https://img.shields.io/github/forks/Tornad0007/CVE-2024-25600-Bricks-Builder-plugin-for-WordPress.svg) 
2024-02-22T10:54:26Z

- [https://github.com/hy011121/CVE-2024-25600-wordpress-Exploit-RCE](https://github.com/hy011121/CVE-2024-25600-wordpress-Exploit-RCE) :  
![starts](https://img.shields.io/github/stars/hy011121/CVE-2024-25600-wordpress-Exploit-RCE.svg) 
![forks](https://img.shields.io/github/forks/hy011121/CVE-2024-25600-wordpress-Exploit-RCE.svg) 
2024-02-29T21:04:40Z

- [https://github.com/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress](https://github.com/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress) :  
![starts](https://img.shields.io/github/stars/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress.svg) 
![forks](https://img.shields.io/github/forks/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress.svg) 
2024-06-02T11:12:04Z

- [https://github.com/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE](https://github.com/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE) :  
![starts](https://img.shields.io/github/stars/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE.svg) 
![forks](https://img.shields.io/github/forks/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE.svg) 
2024-04-20T06:37:22Z

- [https://github.com/wh6amiGit/CVE-2024-25600](https://github.com/wh6amiGit/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/wh6amiGit/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/wh6amiGit/CVE-2024-25600.svg) 
2024-08-20T13:57:56Z

- [https://github.com/k3lpi3b4nsh33/CVE-2024-25600](https://github.com/k3lpi3b4nsh33/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/k3lpi3b4nsh33/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/k3lpi3b4nsh33/CVE-2024-25600.svg) 
2024-06-06T02:36:34Z

- [https://github.com/WanLiChangChengWanLiChang/CVE-2024-25600](https://github.com/WanLiChangChengWanLiChang/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/WanLiChangChengWanLiChang/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/WanLiChangChengWanLiChang/CVE-2024-25600.svg) 
2024-06-07T17:15:43Z

- [https://github.com/svchostmm/CVE-2024-25600-mass](https://github.com/svchostmm/CVE-2024-25600-mass) :  
![starts](https://img.shields.io/github/stars/svchostmm/CVE-2024-25600-mass.svg) 
![forks](https://img.shields.io/github/forks/svchostmm/CVE-2024-25600-mass.svg) 
2024-05-05T02:22:47Z

- [https://github.com/Sibul-Dan-Glokta/test-task-CVE-2024-25600](https://github.com/Sibul-Dan-Glokta/test-task-CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/Sibul-Dan-Glokta/test-task-CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/Sibul-Dan-Glokta/test-task-CVE-2024-25600.svg) 
2025-01-26T23:44:27Z

- [https://github.com/KaSooMi0228/CVE-2024-25600-Bricks-Builder-WordPress](https://github.com/KaSooMi0228/CVE-2024-25600-Bricks-Builder-WordPress) :  
![starts](https://img.shields.io/github/stars/KaSooMi0228/CVE-2024-25600-Bricks-Builder-WordPress.svg) 
![forks](https://img.shields.io/github/forks/KaSooMi0228/CVE-2024-25600-Bricks-Builder-WordPress.svg) 
2024-07-30T09:04:30Z

## CVE-2024-23897
 Jenkins 2.441 and earlier, LTS 2.426.2 and earlier does not disable a feature of its CLI command parser that replaces an '@' character followed by a file path in an argument with the file's contents, allowing unauthenticated attackers to read arbitrary files on the Jenkins controller file system.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-03T10:37:09Z

- [https://github.com/h4x0r-dz/CVE-2024-23897](https://github.com/h4x0r-dz/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/h4x0r-dz/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/h4x0r-dz/CVE-2024-23897.svg) 
2024-01-28T06:47:28Z

- [https://github.com/binganao/CVE-2024-23897](https://github.com/binganao/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/binganao/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/binganao/CVE-2024-23897.svg) 
2024-02-01T06:50:32Z

- [https://github.com/wjlin0/CVE-2024-23897](https://github.com/wjlin0/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/wjlin0/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/wjlin0/CVE-2024-23897.svg) 
2024-03-16T07:55:41Z

- [https://github.com/xaitax/CVE-2024-23897](https://github.com/xaitax/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/xaitax/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/xaitax/CVE-2024-23897.svg) 
2024-02-29T12:13:21Z

- [https://github.com/godylockz/CVE-2024-23897](https://github.com/godylockz/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/godylockz/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/godylockz/CVE-2024-23897.svg) 
2025-02-16T07:47:31Z

- [https://github.com/kaanatmacaa/CVE-2024-23897](https://github.com/kaanatmacaa/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/kaanatmacaa/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/kaanatmacaa/CVE-2024-23897.svg) 
2024-02-05T14:10:26Z

- [https://github.com/Vozec/CVE-2024-23897](https://github.com/Vozec/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/Vozec/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/Vozec/CVE-2024-23897.svg) 
2024-04-16T06:56:39Z

- [https://github.com/3yujw7njai/CVE-2024-23897](https://github.com/3yujw7njai/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/3yujw7njai/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/3yujw7njai/CVE-2024-23897.svg) 
2024-01-27T13:10:37Z

- [https://github.com/verylazytech/CVE-2024-23897](https://github.com/verylazytech/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-23897.svg) 
2024-11-26T14:46:59Z

- [https://github.com/Maalfer/CVE-2024-23897](https://github.com/Maalfer/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/Maalfer/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/Maalfer/CVE-2024-23897.svg) 
2024-05-17T11:54:26Z

- [https://github.com/jenkinsci-cert/SECURITY-3314-3315](https://github.com/jenkinsci-cert/SECURITY-3314-3315) :  
![starts](https://img.shields.io/github/stars/jenkinsci-cert/SECURITY-3314-3315.svg) 
![forks](https://img.shields.io/github/forks/jenkinsci-cert/SECURITY-3314-3315.svg) 
2024-02-20T14:13:25Z

- [https://github.com/10T4/PoC-Fix-jenkins-rce_CVE-2024-23897](https://github.com/10T4/PoC-Fix-jenkins-rce_CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/10T4/PoC-Fix-jenkins-rce_CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/10T4/PoC-Fix-jenkins-rce_CVE-2024-23897.svg) 
2024-01-27T14:43:18Z

- [https://github.com/viszsec/CVE-2024-23897](https://github.com/viszsec/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/viszsec/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/viszsec/CVE-2024-23897.svg) 
2024-01-31T03:14:07Z

- [https://github.com/mil4ne/CVE-2024-23897-Jenkins-4.441](https://github.com/mil4ne/CVE-2024-23897-Jenkins-4.441) :  
![starts](https://img.shields.io/github/stars/mil4ne/CVE-2024-23897-Jenkins-4.441.svg) 
![forks](https://img.shields.io/github/forks/mil4ne/CVE-2024-23897-Jenkins-4.441.svg) 
2024-05-08T02:34:04Z

- [https://github.com/Praison001/CVE-2024-23897-Jenkins-Arbitrary-Read-File-Vulnerability](https://github.com/Praison001/CVE-2024-23897-Jenkins-Arbitrary-Read-File-Vulnerability) :  
![starts](https://img.shields.io/github/stars/Praison001/CVE-2024-23897-Jenkins-Arbitrary-Read-File-Vulnerability.svg) 
![forks](https://img.shields.io/github/forks/Praison001/CVE-2024-23897-Jenkins-Arbitrary-Read-File-Vulnerability.svg) 
2024-02-09T13:22:36Z

- [https://github.com/yoryio/CVE-2024-23897](https://github.com/yoryio/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2024-23897.svg) 
2024-03-13T05:52:30Z

- [https://github.com/ThatNotEasy/CVE-2024-23897](https://github.com/ThatNotEasy/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-23897.svg) 
2024-03-02T07:55:22Z

- [https://github.com/vmtyan/poc-cve-2024-23897](https://github.com/vmtyan/poc-cve-2024-23897) :  
![starts](https://img.shields.io/github/stars/vmtyan/poc-cve-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/vmtyan/poc-cve-2024-23897.svg) 
2024-01-26T21:46:10Z

- [https://github.com/Anekant-Singhai/Exploits](https://github.com/Anekant-Singhai/Exploits) :  
![starts](https://img.shields.io/github/stars/Anekant-Singhai/Exploits.svg) 
![forks](https://img.shields.io/github/forks/Anekant-Singhai/Exploits.svg) 
2024-05-04T13:25:52Z

- [https://github.com/jopraveen/CVE-2024-23897](https://github.com/jopraveen/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/jopraveen/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/jopraveen/CVE-2024-23897.svg) 
2024-01-29T12:14:08Z

- [https://github.com/JAthulya/CVE-2024-23897](https://github.com/JAthulya/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/JAthulya/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/JAthulya/CVE-2024-23897.svg) 
2024-05-03T08:33:11Z

- [https://github.com/Nebian/CVE-2024-23897](https://github.com/Nebian/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/Nebian/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/Nebian/CVE-2024-23897.svg) 
2024-02-21T19:07:17Z

- [https://github.com/r0xdeadbeef/CVE-2024-23897](https://github.com/r0xdeadbeef/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/r0xdeadbeef/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/r0xdeadbeef/CVE-2024-23897.svg) 
2024-01-28T13:28:09Z

- [https://github.com/AbraXa5/Jenkins-CVE-2024-23897](https://github.com/AbraXa5/Jenkins-CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/AbraXa5/Jenkins-CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/AbraXa5/Jenkins-CVE-2024-23897.svg) 
2024-02-04T18:31:47Z

- [https://github.com/D1se0/CVE-2024-23897-Vulnerabilidad-Jenkins](https://github.com/D1se0/CVE-2024-23897-Vulnerabilidad-Jenkins) :  
![starts](https://img.shields.io/github/stars/D1se0/CVE-2024-23897-Vulnerabilidad-Jenkins.svg) 
![forks](https://img.shields.io/github/forks/D1se0/CVE-2024-23897-Vulnerabilidad-Jenkins.svg) 
2024-12-08T08:46:36Z

- [https://github.com/B4CK4TT4CK/CVE-2024-23897](https://github.com/B4CK4TT4CK/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/B4CK4TT4CK/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/B4CK4TT4CK/CVE-2024-23897.svg) 
2024-02-13T22:44:48Z

- [https://github.com/ShieldAuth-PHP/PBL05-CVE-Analsys](https://github.com/ShieldAuth-PHP/PBL05-CVE-Analsys) :  
![starts](https://img.shields.io/github/stars/ShieldAuth-PHP/PBL05-CVE-Analsys.svg) 
![forks](https://img.shields.io/github/forks/ShieldAuth-PHP/PBL05-CVE-Analsys.svg) 
2024-09-09T18:42:34Z

- [https://github.com/cc3305/CVE-2024-23897](https://github.com/cc3305/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/cc3305/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/cc3305/CVE-2024-23897.svg) 
2024-10-28T21:15:44Z

- [https://github.com/ifconfig-me/CVE-2024-23897](https://github.com/ifconfig-me/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/ifconfig-me/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/ifconfig-me/CVE-2024-23897.svg) 
2024-02-17T15:20:01Z

- [https://github.com/murataydemir/CVE-2024-23897](https://github.com/murataydemir/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/murataydemir/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/murataydemir/CVE-2024-23897.svg) 
2024-05-07T14:28:44Z

- [https://github.com/tamatee/test_cve_2024_23897](https://github.com/tamatee/test_cve_2024_23897) :  
![starts](https://img.shields.io/github/stars/tamatee/test_cve_2024_23897.svg) 
![forks](https://img.shields.io/github/forks/tamatee/test_cve_2024_23897.svg) 
2024-11-07T09:35:26Z

- [https://github.com/brijne/CVE-2024-23897-RCE](https://github.com/brijne/CVE-2024-23897-RCE) :  
![starts](https://img.shields.io/github/stars/brijne/CVE-2024-23897-RCE.svg) 
![forks](https://img.shields.io/github/forks/brijne/CVE-2024-23897-RCE.svg) 
2024-02-02T23:19:35Z

- [https://github.com/WLXQqwer/Jenkins-CVE-2024-23897-](https://github.com/WLXQqwer/Jenkins-CVE-2024-23897-) :  
![starts](https://img.shields.io/github/stars/WLXQqwer/Jenkins-CVE-2024-23897-.svg) 
![forks](https://img.shields.io/github/forks/WLXQqwer/Jenkins-CVE-2024-23897-.svg) 
2024-02-04T01:23:45Z

- [https://github.com/BinaryGoodBoy0101/Jenkins-Exploit-CVE-2024-23897-Fsociety](https://github.com/BinaryGoodBoy0101/Jenkins-Exploit-CVE-2024-23897-Fsociety) :  
![starts](https://img.shields.io/github/stars/BinaryGoodBoy0101/Jenkins-Exploit-CVE-2024-23897-Fsociety.svg) 
![forks](https://img.shields.io/github/forks/BinaryGoodBoy0101/Jenkins-Exploit-CVE-2024-23897-Fsociety.svg) 
2024-09-03T16:06:41Z

- [https://github.com/Surko888/Surko-Exploit-Jenkins-CVE-2024-23897](https://github.com/Surko888/Surko-Exploit-Jenkins-CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/Surko888/Surko-Exploit-Jenkins-CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/Surko888/Surko-Exploit-Jenkins-CVE-2024-23897.svg) 
2024-06-01T23:48:44Z

- [https://github.com/pulentoski/CVE-2024-23897-Arbitrary-file-read](https://github.com/pulentoski/CVE-2024-23897-Arbitrary-file-read) :  
![starts](https://img.shields.io/github/stars/pulentoski/CVE-2024-23897-Arbitrary-file-read.svg) 
![forks](https://img.shields.io/github/forks/pulentoski/CVE-2024-23897-Arbitrary-file-read.svg) 
2024-11-18T19:25:20Z

- [https://github.com/Marouane133/jenkins-lfi](https://github.com/Marouane133/jenkins-lfi) :  
![starts](https://img.shields.io/github/stars/Marouane133/jenkins-lfi.svg) 
![forks](https://img.shields.io/github/forks/Marouane133/jenkins-lfi.svg) 
2025-01-03T02:56:38Z

## CVE-2024-21893
 A server-side request forgery vulnerability in the SAML component of Ivanti Connect Secure (9.x, 22.x) and Ivanti Policy Secure (9.x, 22.x) and Ivanti Neurons for ZTA allows an attacker to access certain restricted resources without authentication.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-03T10:37:09Z

- [https://github.com/h4x0r-dz/CVE-2024-21893.py](https://github.com/h4x0r-dz/CVE-2024-21893.py) :  
![starts](https://img.shields.io/github/stars/h4x0r-dz/CVE-2024-21893.py.svg) 
![forks](https://img.shields.io/github/forks/h4x0r-dz/CVE-2024-21893.py.svg) 
2024-02-02T23:27:10Z

- [https://github.com/Chocapikk/CVE-2024-21893-to-CVE-2024-21887](https://github.com/Chocapikk/CVE-2024-21893-to-CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-21893-to-CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-21893-to-CVE-2024-21887.svg) 
2024-02-03T11:48:37Z

## CVE-2024-21887
 A command injection vulnerability in web components of Ivanti Connect Secure (9.x, 22.x) and Ivanti Policy Secure (9.x, 22.x)  allows an authenticated administrator to send specially crafted requests and execute arbitrary commands on the appliance.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-03T10:37:09Z

- [https://github.com/Chocapikk/CVE-2024-21887](https://github.com/Chocapikk/CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-21887.svg) 
2024-01-17T00:38:28Z

- [https://github.com/Chocapikk/CVE-2024-21893-to-CVE-2024-21887](https://github.com/Chocapikk/CVE-2024-21893-to-CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-21893-to-CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-21893-to-CVE-2024-21887.svg) 
2024-02-03T11:48:37Z

- [https://github.com/duy-31/CVE-2023-46805_CVE-2024-21887](https://github.com/duy-31/CVE-2023-46805_CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/duy-31/CVE-2023-46805_CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/duy-31/CVE-2023-46805_CVE-2024-21887.svg) 
2024-01-17T19:14:09Z

- [https://github.com/seajaysec/Ivanti-Connect-Around-Scan](https://github.com/seajaysec/Ivanti-Connect-Around-Scan) :  
![starts](https://img.shields.io/github/stars/seajaysec/Ivanti-Connect-Around-Scan.svg) 
![forks](https://img.shields.io/github/forks/seajaysec/Ivanti-Connect-Around-Scan.svg) 
2024-02-03T01:59:49Z

- [https://github.com/yoryio/CVE-2023-46805](https://github.com/yoryio/CVE-2023-46805) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2023-46805.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2023-46805.svg) 
2024-07-23T16:01:11Z

- [https://github.com/oways/ivanti-CVE-2024-21887](https://github.com/oways/ivanti-CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/oways/ivanti-CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/oways/ivanti-CVE-2024-21887.svg) 
2024-01-14T09:27:36Z

- [https://github.com/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887](https://github.com/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887.svg) 
2024-03-23T14:52:22Z

- [https://github.com/tucommenceapousser/CVE-2024-21887](https://github.com/tucommenceapousser/CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/tucommenceapousser/CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/tucommenceapousser/CVE-2024-21887.svg) 
2024-01-20T19:20:25Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

- [https://github.com/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped](https://github.com/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped) :  
![starts](https://img.shields.io/github/stars/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped.svg) 
![forks](https://img.shields.io/github/forks/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped.svg) 
2024-05-21T12:56:25Z

## CVE-2024-20931
 Vulnerability in the Oracle WebLogic Server product of Oracle Fusion Middleware (component: Core).  Supported versions that are affected are 12.2.1.4.0 and  14.1.1.0.0. Easily exploitable vulnerability allows unauthenticated attacker with network access via T3, IIOP to compromise Oracle WebLogic Server.  Successful attacks of this vulnerability can result in  unauthorized access to critical data or complete access to all Oracle WebLogic Server accessible data. CVSS 3.1 Base Score 7.5 (Confidentiality impacts).  CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:N/A:N).

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-03T10:37:09Z

- [https://github.com/GlassyAmadeus/CVE-2024-20931](https://github.com/GlassyAmadeus/CVE-2024-20931) :  
![starts](https://img.shields.io/github/stars/GlassyAmadeus/CVE-2024-20931.svg) 
![forks](https://img.shields.io/github/forks/GlassyAmadeus/CVE-2024-20931.svg) 
2024-02-02T02:05:01Z

- [https://github.com/dinosn/CVE-2024-20931](https://github.com/dinosn/CVE-2024-20931) :  
![starts](https://img.shields.io/github/stars/dinosn/CVE-2024-20931.svg) 
![forks](https://img.shields.io/github/forks/dinosn/CVE-2024-20931.svg) 
2024-02-06T15:56:12Z

- [https://github.com/ATonysan/CVE-2024-20931_weblogic](https://github.com/ATonysan/CVE-2024-20931_weblogic) :  
![starts](https://img.shields.io/github/stars/ATonysan/CVE-2024-20931_weblogic.svg) 
![forks](https://img.shields.io/github/forks/ATonysan/CVE-2024-20931_weblogic.svg) 
2024-02-06T09:49:46Z

- [https://github.com/Leocodefocus/CVE-2024-20931-Poc](https://github.com/Leocodefocus/CVE-2024-20931-Poc) :  
![starts](https://img.shields.io/github/stars/Leocodefocus/CVE-2024-20931-Poc.svg) 
![forks](https://img.shields.io/github/forks/Leocodefocus/CVE-2024-20931-Poc.svg) 
2024-02-07T00:34:30Z

## CVE-2024-9474
 A privilege escalation vulnerability in Palo Alto Networks PAN-OS software allows a PAN-OS administrator with access to the management web interface to perform actions on the firewall with root privileges.Cloud NGFW and Prisma Access are not impacted by this vulnerability.

- [https://github.com/Chocapikk/CVE-2024-9474](https://github.com/Chocapikk/CVE-2024-9474) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-9474.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-9474.svg) 
2024-11-19T17:38:29Z

- [https://github.com/k4nfr3/CVE-2024-9474](https://github.com/k4nfr3/CVE-2024-9474) :  
![starts](https://img.shields.io/github/stars/k4nfr3/CVE-2024-9474.svg) 
![forks](https://img.shields.io/github/forks/k4nfr3/CVE-2024-9474.svg) 
2024-11-22T16:39:20Z

- [https://github.com/TalatumLabs/CVE-2024-0012_CVE-2024-9474_PoC](https://github.com/TalatumLabs/CVE-2024-0012_CVE-2024-9474_PoC) :  
![starts](https://img.shields.io/github/stars/TalatumLabs/CVE-2024-0012_CVE-2024-9474_PoC.svg) 
![forks](https://img.shields.io/github/forks/TalatumLabs/CVE-2024-0012_CVE-2024-9474_PoC.svg) 
2024-12-12T15:48:10Z

- [https://github.com/XiaomingX/cve-2024-0012-poc](https://github.com/XiaomingX/cve-2024-0012-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-0012-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-0012-poc.svg) 
2024-11-22T14:37:04Z

- [https://github.com/coskper-papa/PAN-OS_CVE-2024-9474](https://github.com/coskper-papa/PAN-OS_CVE-2024-9474) :  
![starts](https://img.shields.io/github/stars/coskper-papa/PAN-OS_CVE-2024-9474.svg) 
![forks](https://img.shields.io/github/forks/coskper-papa/PAN-OS_CVE-2024-9474.svg) 
2024-12-11T03:36:19Z

- [https://github.com/dcollaoa/cve-2024-0012-gui-poc](https://github.com/dcollaoa/cve-2024-0012-gui-poc) :  
![starts](https://img.shields.io/github/stars/dcollaoa/cve-2024-0012-gui-poc.svg) 
![forks](https://img.shields.io/github/forks/dcollaoa/cve-2024-0012-gui-poc.svg) 
2025-02-06T20:35:42Z

- [https://github.com/deathvu/CVE-2024-9474](https://github.com/deathvu/CVE-2024-9474) :  
![starts](https://img.shields.io/github/stars/deathvu/CVE-2024-9474.svg) 
![forks](https://img.shields.io/github/forks/deathvu/CVE-2024-9474.svg) 
2024-11-20T22:35:09Z

- [https://github.com/concretesign/CVE-2024-9474](https://github.com/concretesign/CVE-2024-9474) :  
![starts](https://img.shields.io/github/stars/concretesign/CVE-2024-9474.svg) 
![forks](https://img.shields.io/github/forks/concretesign/CVE-2024-9474.svg) 
2025-03-03T15:14:57Z

- [https://github.com/aratane/CVE-2024-9474](https://github.com/aratane/CVE-2024-9474) :  
![starts](https://img.shields.io/github/stars/aratane/CVE-2024-9474.svg) 
![forks](https://img.shields.io/github/forks/aratane/CVE-2024-9474.svg) 
2025-01-16T20:35:35Z

## CVE-2024-0204
 Authentication bypass in Fortra's GoAnywhere MFT prior to 7.4.1 allows an unauthorized user to create an admin user via the administration portal.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-03T10:37:09Z

- [https://github.com/horizon3ai/CVE-2024-0204](https://github.com/horizon3ai/CVE-2024-0204) :  
![starts](https://img.shields.io/github/stars/horizon3ai/CVE-2024-0204.svg) 
![forks](https://img.shields.io/github/forks/horizon3ai/CVE-2024-0204.svg) 
2024-01-23T20:33:30Z

- [https://github.com/cbeek-r7/CVE-2024-0204](https://github.com/cbeek-r7/CVE-2024-0204) :  
![starts](https://img.shields.io/github/stars/cbeek-r7/CVE-2024-0204.svg) 
![forks](https://img.shields.io/github/forks/cbeek-r7/CVE-2024-0204.svg) 
2024-01-23T22:44:05Z

- [https://github.com/m-cetin/CVE-2024-0204](https://github.com/m-cetin/CVE-2024-0204) :  
![starts](https://img.shields.io/github/stars/m-cetin/CVE-2024-0204.svg) 
![forks](https://img.shields.io/github/forks/m-cetin/CVE-2024-0204.svg) 
2024-01-24T20:17:01Z

- [https://github.com/adminlove520/CVE-2024-0204](https://github.com/adminlove520/CVE-2024-0204) :  
![starts](https://img.shields.io/github/stars/adminlove520/CVE-2024-0204.svg) 
![forks](https://img.shields.io/github/forks/adminlove520/CVE-2024-0204.svg) 
2024-02-04T01:43:30Z

# 2025-03-02
## CVE-2024-2997
 A vulnerability was found in Bdtask Multi-Store Inventory Management System up to 20240320. It has been declared as problematic. Affected by this vulnerability is an unknown functionality. The manipulation of the argument Category Name/Model Name/Brand Name/Unit Name leads to cross site scripting. The attack can be launched remotely. The exploit has been disclosed to the public and may be used. The associated identifier of this vulnerability is VDB-258199. NOTE: The vendor was contacted early about this disclosure but did not respond in any way.

- [https://github.com/lfillaz/CVE-2024-2997](https://github.com/lfillaz/CVE-2024-2997) :  
![starts](https://img.shields.io/github/stars/lfillaz/CVE-2024-2997.svg) 
![forks](https://img.shields.io/github/forks/lfillaz/CVE-2024-2997.svg) 
2025-03-02T21:57:16Z

# 2025-03-01
## CVE-2025-25296
 Label Studio is an open source data labeling tool. Prior to version 1.16.0, Label Studio's `/projects/upload-example` endpoint allows injection of arbitrary HTML through a `GET` request with an appropriately crafted `label_config` query parameter. By crafting a specially formatted XML label config with inline task data containing malicious HTML/JavaScript, an attacker can achieve Cross-Site Scripting (XSS). While the application has a Content Security Policy (CSP), it is only set in report-only mode, making it ineffective at preventing script execution. The vulnerability exists because the upload-example endpoint renders user-provided HTML content without proper sanitization on a GET request. This allows attackers to inject and execute arbitrary JavaScript in victims' browsers by getting them to visit a maliciously crafted URL. This is considered vulnerable because it enables attackers to execute JavaScript in victims' contexts, potentially allowing theft of sensitive data, session hijacking, or other malicious actions. Version 1.16.0 contains a patch for the issue.

- [https://github.com/math-x-io/CVE-2025-25296-POC](https://github.com/math-x-io/CVE-2025-25296-POC) :  
![starts](https://img.shields.io/github/stars/math-x-io/CVE-2025-25296-POC.svg) 
![forks](https://img.shields.io/github/forks/math-x-io/CVE-2025-25296-POC.svg) 
2025-03-01T02:09:07Z

# 2025-02-28
## CVE-2025-25967
 Acora CMS version 10.1.1 is vulnerable to Cross-Site Request Forgery (CSRF). This flaw enables attackers to trick authenticated users into performing unauthorized actions, such as account deletion or user creation, by embedding malicious requests in external content. The lack of CSRF protections allows exploitation via crafted requests.

- [https://github.com/padayali-JD/CVE-2025-25967](https://github.com/padayali-JD/CVE-2025-25967) :  
![starts](https://img.shields.io/github/stars/padayali-JD/CVE-2025-25967.svg) 
![forks](https://img.shields.io/github/forks/padayali-JD/CVE-2025-25967.svg) 
2025-02-28T04:26:06Z

## CVE-2025-24971
 DumpDrop is a stupid simple file upload application that provides an interface for dragging and dropping files. An OS Command Injection vulnerability was discovered in the DumbDrop application, `/upload/init` endpoint. This vulnerability could allow an attacker to execute arbitrary code remotely when the **Apprise Notification** enabled. This issue has been addressed in commit `4ff8469d` and all users are advised to patch. There are no known workarounds for this vulnerability.

- [https://github.com/be4zad/CVE-2025-24971](https://github.com/be4zad/CVE-2025-24971) :  
![starts](https://img.shields.io/github/stars/be4zad/CVE-2025-24971.svg) 
![forks](https://img.shields.io/github/forks/be4zad/CVE-2025-24971.svg) 
2025-02-28T16:13:21Z

## CVE-2025-22964
 DDSN Interactive cm3 Acora CMS version 10.1.1 has an unauthenticated time-based blind SQL Injection vulnerability caused by insufficient input sanitization and validation in the "table" parameter. This flaw allows attackers to inject malicious SQL queries by directly incorporating user-supplied input into database queries without proper escaping or validation. Exploiting this issue enables unauthorized access, manipulation of data, or exposure of sensitive information, posing significant risks to the integrity and confidentiality of the application.

- [https://github.com/padayali-JD/CVE-2025-22964](https://github.com/padayali-JD/CVE-2025-22964) :  
![starts](https://img.shields.io/github/stars/padayali-JD/CVE-2025-22964.svg) 
![forks](https://img.shields.io/github/forks/padayali-JD/CVE-2025-22964.svg) 
2025-02-28T04:33:03Z

## CVE-2024-55511
 A null pointer dereference vulnerability in Macrium Reflect prior to 8.1.8017 allows a local attacker to cause a system crash or potentially elevate their privileges via executing a specially crafted executable.

- [https://github.com/nikosecurity/CVE-2024-55511](https://github.com/nikosecurity/CVE-2024-55511) :  
![starts](https://img.shields.io/github/stars/nikosecurity/CVE-2024-55511.svg) 
![forks](https://img.shields.io/github/forks/nikosecurity/CVE-2024-55511.svg) 
2025-02-28T21:47:47Z

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
2025-02-28T18:56:30Z

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

- [https://github.com/ggfzx/CVE-2024-4577](https://github.com/ggfzx/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ggfzx/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ggfzx/CVE-2024-4577.svg) 
2024-06-26T07:11:46Z

- [https://github.com/AlperenY-cs/CVE-2024-4577](https://github.com/AlperenY-cs/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/AlperenY-cs/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/AlperenY-cs/CVE-2024-4577.svg) 
2024-06-29T10:39:30Z

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

- [https://github.com/Sysc4ll3r/CVE-2024-4577](https://github.com/Sysc4ll3r/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Sysc4ll3r/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Sysc4ll3r/CVE-2024-4577.svg) 
2024-06-07T18:41:17Z

- [https://github.com/sug4r-wr41th/CVE-2024-4577](https://github.com/sug4r-wr41th/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/sug4r-wr41th/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/sug4r-wr41th/CVE-2024-4577.svg) 
2025-02-27T21:20:16Z

- [https://github.com/BitMEXResearch/CVE-2024-4577](https://github.com/BitMEXResearch/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/BitMEXResearch/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/BitMEXResearch/CVE-2024-4577.svg) 
2024-06-07T20:35:06Z

- [https://github.com/princew88/CVE-2024-4577](https://github.com/princew88/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/princew88/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/princew88/CVE-2024-4577.svg) 
2024-06-07T09:48:36Z

- [https://github.com/a-roshbaik/CVE-2024-4577](https://github.com/a-roshbaik/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/a-roshbaik/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/a-roshbaik/CVE-2024-4577.svg) 
2024-07-24T20:23:03Z

- [https://github.com/Jcccccx/CVE-2024-4577](https://github.com/Jcccccx/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Jcccccx/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Jcccccx/CVE-2024-4577.svg) 
2024-07-31T10:37:56Z

- [https://github.com/bl4cksku11/CVE-2024-4577](https://github.com/bl4cksku11/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bl4cksku11/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bl4cksku11/CVE-2024-4577.svg) 
2024-06-11T15:29:21Z

- [https://github.com/hexedbyte/cve-2024-4577](https://github.com/hexedbyte/cve-2024-4577) :  
![starts](https://img.shields.io/github/stars/hexedbyte/cve-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/hexedbyte/cve-2024-4577.svg) 
2024-06-13T12:43:03Z

- [https://github.com/dbyMelina/CVE-2024-4577](https://github.com/dbyMelina/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/dbyMelina/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/dbyMelina/CVE-2024-4577.svg) 
2024-06-09T13:47:59Z

- [https://github.com/ahmetramazank/CVE-2024-4577](https://github.com/ahmetramazank/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ahmetramazank/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ahmetramazank/CVE-2024-4577.svg) 
2024-11-03T16:17:49Z

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

## CVE-2025-26263
 GeoVision ASManager Windows desktop application with the version 6.1.2.0 or less, is vulnerable to credentials disclosure due to improper memory handling in the ASManagerService.exe process.

- [https://github.com/DRAGOWN/CVE-2025-26263](https://github.com/DRAGOWN/CVE-2025-26263) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2025-26263.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2025-26263.svg) 
2025-02-26T18:03:50Z

## CVE-2025-25461
 A Stored Cross-Site Scripting (XSS) vulnerability exists in SeedDMS 6.0.29. A user or rogue admin with the "Add Category" permission can inject a malicious XSS payload into the category name field. When a document is subsequently associated with this category, the payload is stored on the server and rendered without proper sanitization or output encoding. This results in the XSS payload executing in the browser of any user who views the document.

- [https://github.com/RoNiXxCybSeC0101/CVE-2025-25461](https://github.com/RoNiXxCybSeC0101/CVE-2025-25461) :  
![starts](https://img.shields.io/github/stars/RoNiXxCybSeC0101/CVE-2025-25461.svg) 
![forks](https://img.shields.io/github/forks/RoNiXxCybSeC0101/CVE-2025-25461.svg) 
2025-02-26T04:39:06Z

## CVE-2025-1302
 Versions of the package jsonpath-plus before 10.3.0 are vulnerable to Remote Code Execution (RCE) due to improper input sanitization. An attacker can execute aribitrary code on the system by exploiting the unsafe default usage of eval='safe' mode.**Note:**This is caused by an incomplete fix for [CVE-2024-21534](https://security.snyk.io/vuln/SNYK-JS-JSONPATHPLUS-7945884).

- [https://github.com/EQSTLab/CVE-2025-1302](https://github.com/EQSTLab/CVE-2025-1302) :  
![starts](https://img.shields.io/github/stars/EQSTLab/CVE-2025-1302.svg) 
![forks](https://img.shields.io/github/forks/EQSTLab/CVE-2025-1302.svg) 
2025-02-26T05:00:18Z

## CVE-2024-56903
 Geovision GV-ASWeb with the version 6.1.1.0 or less allows attackers to modify POST request method with the GET against critical functionalities, such as account management. This vulnerability is used in chain with CVE-2024-56901 for a successful CSRF attack.

- [https://github.com/DRAGOWN/CVE-2024-56903](https://github.com/DRAGOWN/CVE-2024-56903) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56903.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56903.svg) 
2025-02-26T17:33:49Z

## CVE-2024-56901
 A Cross-Site Request Forgery (CSRF) vulnerability in Geovision GV-ASWeb application with the version 6.1.1.0 or less that allows attackers to arbitrarily create Administrator accounts via a crafted GET request method. This vulnerability is used in chain with CVE-2024-56903 for a successful CSRF attack.

- [https://github.com/DRAGOWN/CVE-2024-56901](https://github.com/DRAGOWN/CVE-2024-56901) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56901.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56901.svg) 
2025-02-02T22:26:39Z

- [https://github.com/DRAGOWN/CVE-2024-56903](https://github.com/DRAGOWN/CVE-2024-56903) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56903.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56903.svg) 
2025-02-26T17:33:49Z

## CVE-2024-56898
 Broken access control vulnerability in Geovision GV-ASWeb with version v6.1.0.0 or less. This vulnerability allows low privilege users perform actions that they aren't authorized to, which can be leveraged to escalate privileges, create, modify or delete accounts.

- [https://github.com/DRAGOWN/CVE-2024-56898](https://github.com/DRAGOWN/CVE-2024-56898) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2024-56898.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2024-56898.svg) 
2025-02-04T16:50:13Z

- [https://github.com/DRAGOWN/CVE-2025-26263](https://github.com/DRAGOWN/CVE-2025-26263) :  
![starts](https://img.shields.io/github/stars/DRAGOWN/CVE-2025-26263.svg) 
![forks](https://img.shields.io/github/forks/DRAGOWN/CVE-2025-26263.svg) 
2025-02-26T18:03:50Z

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

- [https://github.com/almanatra/CVE-2025-0282](https://github.com/almanatra/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/almanatra/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/almanatra/CVE-2025-0282.svg) 
2025-01-22T08:25:22Z

## CVE-2024-54772
 An issue was discovered in the Winbox service of MikroTik RouterOS long-term release v6.43.13 through v6.49.13 and stable v6.43 through v7.17.2. A patch is available in the stable release v6.49.18. A discrepancy in response size between connection attempts made with a valid username and those with an invalid username allows attackers to enumerate for valid accounts.

- [https://github.com/deauther890/CVE-2024-54772](https://github.com/deauther890/CVE-2024-54772) :  
![starts](https://img.shields.io/github/stars/deauther890/CVE-2024-54772.svg) 
![forks](https://img.shields.io/github/forks/deauther890/CVE-2024-54772.svg) 
2025-02-25T12:43:32Z

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

- [https://github.com/l-urk/CVE-2024-6387](https://github.com/l-urk/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/l-urk/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/l-urk/CVE-2024-6387.svg) 
2024-10-19T04:58:22Z

- [https://github.com/TAM-K592/CVE-2024-6387](https://github.com/TAM-K592/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/TAM-K592/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/TAM-K592/CVE-2024-6387.svg) 
2024-07-02T03:23:00Z

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

- [https://github.com/dawnl3ss/CVE-2024-6387](https://github.com/dawnl3ss/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dawnl3ss/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dawnl3ss/CVE-2024-6387.svg) 
2024-07-02T15:14:37Z

- [https://github.com/no-one-sec/CVE-2024-6387](https://github.com/no-one-sec/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/no-one-sec/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/no-one-sec/CVE-2024-6387.svg) 
2024-07-02T15:13:09Z

- [https://github.com/imv7/CVE-2024-6387](https://github.com/imv7/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/imv7/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/imv7/CVE-2024-6387.svg) 
2024-07-05T11:19:21Z

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

- [https://github.com/sardine-web/CVE-2024-6387_Check](https://github.com/sardine-web/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/sardine-web/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/sardine-web/CVE-2024-6387_Check.svg) 
2024-07-04T21:31:17Z

- [https://github.com/zenzue/CVE-2024-6387-Mitigation](https://github.com/zenzue/CVE-2024-6387-Mitigation) :  
![starts](https://img.shields.io/github/stars/zenzue/CVE-2024-6387-Mitigation.svg) 
![forks](https://img.shields.io/github/forks/zenzue/CVE-2024-6387-Mitigation.svg) 
2024-07-02T11:17:12Z

- [https://github.com/t3rry327/cve-2024-6387-poc](https://github.com/t3rry327/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/t3rry327/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/t3rry327/cve-2024-6387-poc.svg) 
2024-07-03T13:24:59Z

- [https://github.com/dgourillon/mitigate-CVE-2024-6387](https://github.com/dgourillon/mitigate-CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dgourillon/mitigate-CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dgourillon/mitigate-CVE-2024-6387.svg) 
2024-07-09T16:03:03Z

- [https://github.com/shyrwall/cve-2024-6387-poc](https://github.com/shyrwall/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/shyrwall/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/shyrwall/cve-2024-6387-poc.svg) 
2024-07-01T12:50:29Z

- [https://github.com/SkyGodling/CVE-2024-6387-POC](https://github.com/SkyGodling/CVE-2024-6387-POC) :  
![starts](https://img.shields.io/github/stars/SkyGodling/CVE-2024-6387-POC.svg) 
![forks](https://img.shields.io/github/forks/SkyGodling/CVE-2024-6387-POC.svg) 
2025-02-10T06:25:56Z

- [https://github.com/jocker2410/CVE-2024-6387_poc](https://github.com/jocker2410/CVE-2024-6387_poc) :  
![starts](https://img.shields.io/github/stars/jocker2410/CVE-2024-6387_poc.svg) 
![forks](https://img.shields.io/github/forks/jocker2410/CVE-2024-6387_poc.svg) 
2024-08-04T10:50:53Z

- [https://github.com/RickGeex/CVE-2024-6387-Checker](https://github.com/RickGeex/CVE-2024-6387-Checker) :  
![starts](https://img.shields.io/github/stars/RickGeex/CVE-2024-6387-Checker.svg) 
![forks](https://img.shields.io/github/forks/RickGeex/CVE-2024-6387-Checker.svg) 
2024-07-02T20:32:48Z

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
## CVE-2025-26206
 Cross Site Request Forgery vulnerability in sell done storefront v.1.0 allows a remote attacker to escalate privileges via the index.html component

- [https://github.com/xibhi/CVE-2025-26206](https://github.com/xibhi/CVE-2025-26206) :  
![starts](https://img.shields.io/github/stars/xibhi/CVE-2025-26206.svg) 
![forks](https://img.shields.io/github/forks/xibhi/CVE-2025-26206.svg) 
2025-02-24T06:40:41Z

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

- [https://github.com/yangyanglo/CVE-2024-53677](https://github.com/yangyanglo/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/yangyanglo/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/yangyanglo/CVE-2024-53677.svg) 
2024-12-17T08:52:36Z

- [https://github.com/SeanRickerd/CVE-2024-53677](https://github.com/SeanRickerd/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/SeanRickerd/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/SeanRickerd/CVE-2024-53677.svg) 
2025-02-18T13:36:17Z

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

- [https://github.com/hopsypopsy8/CVE-2024-53677-Exploitation](https://github.com/hopsypopsy8/CVE-2024-53677-Exploitation) :  
![starts](https://img.shields.io/github/stars/hopsypopsy8/CVE-2024-53677-Exploitation.svg) 
![forks](https://img.shields.io/github/forks/hopsypopsy8/CVE-2024-53677-Exploitation.svg) 
2025-02-13T09:10:53Z

- [https://github.com/0xPThree/struts_cve-2024-53677](https://github.com/0xPThree/struts_cve-2024-53677) :  
![starts](https://img.shields.io/github/stars/0xPThree/struts_cve-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/0xPThree/struts_cve-2024-53677.svg) 
2025-01-07T11:39:34Z

- [https://github.com/shishirghimir/CVE-2024-53677-Exploit](https://github.com/shishirghimir/CVE-2024-53677-Exploit) :  
![starts](https://img.shields.io/github/stars/shishirghimir/CVE-2024-53677-Exploit.svg) 
![forks](https://img.shields.io/github/forks/shishirghimir/CVE-2024-53677-Exploit.svg) 
2025-02-24T13:09:53Z

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

- [https://github.com/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-](https://github.com/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-) :  
![starts](https://img.shields.io/github/stars/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-.svg) 
![forks](https://img.shields.io/github/forks/regantemudo/PHP-file-read-to-RCE-CVE-2024-2961-.svg) 
2025-02-24T04:06:50Z

- [https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961](https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961) :  
![starts](https://img.shields.io/github/stars/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
2025-02-02T11:26:18Z

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

- [https://github.com/xzx482/CVE-2024-1086](https://github.com/xzx482/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/xzx482/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/xzx482/CVE-2024-1086.svg) 
2024-07-04T10:54:20Z

- [https://github.com/CCIEVoice2009/CVE-2024-1086](https://github.com/CCIEVoice2009/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/CCIEVoice2009/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/CCIEVoice2009/CVE-2024-1086.svg) 
2024-04-30T16:13:00Z

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

