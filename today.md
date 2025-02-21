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
2025-02-21T09:29:36Z

## CVE-2025-24016
 Wazuh is a free and open source platform used for threat prevention, detection, and response. Starting in version 4.4.0 and prior to version 4.9.1, an unsafe deserialization vulnerability allows for remote code execution on Wazuh servers. DistributedAPI parameters are a serialized as JSON and deserialized using `as_wazuh_object` (in `framework/wazuh/core/cluster/common.py`). If an attacker manages to inject an unsanitized dictionary in DAPI request/response, they can forge an unhandled exception (`__unhandled_exc__`) to evaluate arbitrary python code. The vulnerability can be triggered by anybody with API access (compromised dashboard or Wazuh servers in the cluster) or, in certain configurations, even by a compromised agent. Version 4.9.1 contains a fix.

- [https://github.com/0xjessie21/CVE-2025-24016](https://github.com/0xjessie21/CVE-2025-24016) :  
![starts](https://img.shields.io/github/stars/0xjessie21/CVE-2025-24016.svg) 
![forks](https://img.shields.io/github/forks/0xjessie21/CVE-2025-24016.svg) 
2025-02-19T16:33:45Z

- [https://github.com/huseyinstif/CVE-2025-24016-Nuclei-Template](https://github.com/huseyinstif/CVE-2025-24016-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/huseyinstif/CVE-2025-24016-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/huseyinstif/CVE-2025-24016-Nuclei-Template.svg) 
2025-02-13T06:38:45Z

- [https://github.com/MuhammadWaseem29/CVE-2025-24016](https://github.com/MuhammadWaseem29/CVE-2025-24016) :  
![starts](https://img.shields.io/github/stars/MuhammadWaseem29/CVE-2025-24016.svg) 
![forks](https://img.shields.io/github/forks/MuhammadWaseem29/CVE-2025-24016.svg) 
2025-02-21T00:17:42Z

## CVE-2025-0924
 The WP Activity Log plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the message parameter in all versions up to, and including, 5.2.2 due to insufficient input sanitization and output escaping. This makes it possible for unauthenticated attackers to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page.

- [https://github.com/skrkcb2/CVE-2025-0924](https://github.com/skrkcb2/CVE-2025-0924) :  
![starts](https://img.shields.io/github/stars/skrkcb2/CVE-2025-0924.svg) 
![forks](https://img.shields.io/github/forks/skrkcb2/CVE-2025-0924.svg) 
2025-02-21T05:24:12Z

## CVE-2024-49138
 Windows Common Log File System Driver Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2024-49138-POC](https://github.com/MrAle98/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2024-49138-POC.svg) 
2025-02-14T22:04:41Z

- [https://github.com/aspire20x/CVE-2024-49138-POC](https://github.com/aspire20x/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/aspire20x/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/aspire20x/CVE-2024-49138-POC.svg) 
2025-02-21T12:20:17Z

- [https://github.com/bananoname/CVE-2024-49138-POC](https://github.com/bananoname/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/bananoname/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/bananoname/CVE-2024-49138-POC.svg) 
2025-01-21T02:06:00Z

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

## CVE-2025-21420
 Windows Disk Cleanup Tool Elevation of Privilege Vulnerability

- [https://github.com/Network-Sec/CVE-2025-21420-PoC](https://github.com/Network-Sec/CVE-2025-21420-PoC) :  
![starts](https://img.shields.io/github/stars/Network-Sec/CVE-2025-21420-PoC.svg) 
![forks](https://img.shields.io/github/forks/Network-Sec/CVE-2025-21420-PoC.svg) 
2025-02-17T18:53:38Z

- [https://github.com/toxy4ny/edge-maradeur](https://github.com/toxy4ny/edge-maradeur) :  
![starts](https://img.shields.io/github/stars/toxy4ny/edge-maradeur.svg) 
![forks](https://img.shields.io/github/forks/toxy4ny/edge-maradeur.svg) 
2025-02-20T15:20:50Z

## CVE-2025-21401
 Microsoft Edge (Chromium-based) Security Feature Bypass Vulnerability

- [https://github.com/toxy4ny/edge-maradeur](https://github.com/toxy4ny/edge-maradeur) :  
![starts](https://img.shields.io/github/stars/toxy4ny/edge-maradeur.svg) 
![forks](https://img.shields.io/github/forks/toxy4ny/edge-maradeur.svg) 
2025-02-20T15:20:50Z

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

- [https://github.com/ishwardeepp/CVE-2025-0411-MoTW-PoC](https://github.com/ishwardeepp/CVE-2025-0411-MoTW-PoC) :  
![starts](https://img.shields.io/github/stars/ishwardeepp/CVE-2025-0411-MoTW-PoC.svg) 
![forks](https://img.shields.io/github/forks/ishwardeepp/CVE-2025-0411-MoTW-PoC.svg) 
2025-02-20T14:15:56Z

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
2025-02-20T09:54:10Z

- [https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961](https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961) :  
![starts](https://img.shields.io/github/stars/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
2025-02-02T11:26:18Z

- [https://github.com/exfil0/test_iconv](https://github.com/exfil0/test_iconv) :  
![starts](https://img.shields.io/github/stars/exfil0/test_iconv.svg) 
![forks](https://img.shields.io/github/forks/exfil0/test_iconv.svg) 
2024-06-04T00:22:13Z

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

# 2025-02-18
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

## CVE-2024-43088
 In multiple functions in AppInfoBase.java, there is a possible way to manipulate app permission settings belonging to another user on the device due to a missing permission check. This could lead to local escalation of privilege across user boundaries with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/nidhihcl75/packages_apps_Settings_AOSP10_r33_CVE-2024-43088](https://github.com/nidhihcl75/packages_apps_Settings_AOSP10_r33_CVE-2024-43088) :  
![starts](https://img.shields.io/github/stars/nidhihcl75/packages_apps_Settings_AOSP10_r33_CVE-2024-43088.svg) 
![forks](https://img.shields.io/github/forks/nidhihcl75/packages_apps_Settings_AOSP10_r33_CVE-2024-43088.svg) 
2025-02-18T12:36:37Z

## CVE-2024-38526
 pdoc provides API Documentation for Python Projects. Documentation generated with `pdoc --math` linked to JavaScript files from polyfill.io. The polyfill.io CDN has been sold and now serves malicious code. This issue has been fixed in pdoc 14.5.1.

- [https://github.com/padayali-JD/pollyscan](https://github.com/padayali-JD/pollyscan) :  
![starts](https://img.shields.io/github/stars/padayali-JD/pollyscan.svg) 
![forks](https://img.shields.io/github/forks/padayali-JD/pollyscan.svg) 
2025-02-18T11:57:23Z

- [https://github.com/putget/pollypull](https://github.com/putget/pollypull) :  
![starts](https://img.shields.io/github/stars/putget/pollypull.svg) 
![forks](https://img.shields.io/github/forks/putget/pollypull.svg) 
2024-09-05T19:12:29Z

## CVE-2024-31903
 IBM Sterling B2B Integrator Standard Edition6.0.0.0 through 6.1.2.5 and 6.2.0.0 through 6.2.0.2 allow an attacker on the local network to execute arbitrary code on the system, caused by the deserialization of untrusted data.

- [https://github.com/WithSecureLabs/ibm-sterling-b2b-integrator-poc](https://github.com/WithSecureLabs/ibm-sterling-b2b-integrator-poc) :  
![starts](https://img.shields.io/github/stars/WithSecureLabs/ibm-sterling-b2b-integrator-poc.svg) 
![forks](https://img.shields.io/github/forks/WithSecureLabs/ibm-sterling-b2b-integrator-poc.svg) 
2025-02-18T19:40:14Z

## CVE-2024-1086
 A use-after-free vulnerability in the Linux kernel's netfilter: nf_tables component can be exploited to achieve local privilege escalation.The nft_verdict_init() function allows positive values as drop error within the hook verdict, and hence the nf_hook_slow() function can cause a double free vulnerability when NF_DROP is issued with a drop error which resembles NF_ACCEPT.We recommend upgrading past commit f342de4e2f33e0e39165d8639387aa6c19dff660.

- [https://github.com/Notselwyn/CVE-2024-1086](https://github.com/Notselwyn/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/Notselwyn/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/Notselwyn/CVE-2024-1086.svg) 
2024-04-17T16:09:54Z

- [https://github.com/andigandhi/bitpixie](https://github.com/andigandhi/bitpixie) :  
![starts](https://img.shields.io/github/stars/andigandhi/bitpixie.svg) 
![forks](https://img.shields.io/github/forks/andigandhi/bitpixie.svg) 
2025-02-18T10:31:50Z

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

# 2025-02-17
## CVE-2025-0851
 A path traversal issue in ZipUtils.unzip and TarUtils.untar in Deep Java Library (DJL) on all platforms allows a bad actor to write files to arbitrary locations.

- [https://github.com/skrkcb2/CVE-2025-0851](https://github.com/skrkcb2/CVE-2025-0851) :  
![starts](https://img.shields.io/github/stars/skrkcb2/CVE-2025-0851.svg) 
![forks](https://img.shields.io/github/forks/skrkcb2/CVE-2025-0851.svg) 
2025-02-17T12:49:59Z

## CVE-2024-56883
 Sage DPW before 2024_12_001 is vulnerable to Incorrect Access Control. The implemented role-based access controls are not always enforced on the server side. Low-privileged Sage users with employee role privileges can create external courses for other employees, even though they do not have the option to do so in the user interface. To do this, a valid request to create a course simply needs to be modified, so that the current user ID in the "id" parameter is replaced with the ID of another user.

- [https://github.com/trustcves/CVE-2024-56883](https://github.com/trustcves/CVE-2024-56883) :  
![starts](https://img.shields.io/github/stars/trustcves/CVE-2024-56883.svg) 
![forks](https://img.shields.io/github/forks/trustcves/CVE-2024-56883.svg) 
2025-02-17T15:50:14Z

## CVE-2024-56882
 Sage DPW before 2024_12_000 is vulnerable to Cross Site Scripting (XSS). Low-privileged Sage users with employee role privileges can permanently store JavaScript code in the Kurstitel and Kurzinfo input fields. The injected payload is executed for each authenticated user who views and interacts with the modified data elements.

- [https://github.com/trustcves/CVE-2024-56882](https://github.com/trustcves/CVE-2024-56882) :  
![starts](https://img.shields.io/github/stars/trustcves/CVE-2024-56882.svg) 
![forks](https://img.shields.io/github/forks/trustcves/CVE-2024-56882.svg) 
2025-02-17T15:47:46Z

## CVE-2024-55591
 AnAuthentication Bypass Using an Alternate Path or Channel vulnerability [CWE-288] affecting FortiOS version 7.0.0 through 7.0.16 and FortiProxy version 7.0.0 through 7.0.19 and 7.2.0 through 7.2.12 allows a remote attacker to gain super-admin privileges via crafted requests toNode.js websocket module.

- [https://github.com/watchtowrlabs/fortios-auth-bypass-check-CVE-2024-55591](https://github.com/watchtowrlabs/fortios-auth-bypass-check-CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/fortios-auth-bypass-check-CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/fortios-auth-bypass-check-CVE-2024-55591.svg) 
2025-01-16T08:58:49Z

- [https://github.com/watchtowrlabs/fortios-auth-bypass-poc-CVE-2024-55591](https://github.com/watchtowrlabs/fortios-auth-bypass-poc-CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/fortios-auth-bypass-poc-CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/fortios-auth-bypass-poc-CVE-2024-55591.svg) 
2025-01-27T19:11:46Z

- [https://github.com/sysirq/fortios-auth-bypass-poc-CVE-2024-55591](https://github.com/sysirq/fortios-auth-bypass-poc-CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/sysirq/fortios-auth-bypass-poc-CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/sysirq/fortios-auth-bypass-poc-CVE-2024-55591.svg) 
2025-01-23T07:40:16Z

- [https://github.com/exfil0/CVE-2024-55591-POC](https://github.com/exfil0/CVE-2024-55591-POC) :  
![starts](https://img.shields.io/github/stars/exfil0/CVE-2024-55591-POC.svg) 
![forks](https://img.shields.io/github/forks/exfil0/CVE-2024-55591-POC.svg) 
2025-02-11T20:52:22Z

- [https://github.com/virus-or-not/CVE-2024-55591](https://github.com/virus-or-not/CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/virus-or-not/CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/virus-or-not/CVE-2024-55591.svg) 
2025-01-29T21:27:21Z

- [https://github.com/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591](https://github.com/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591.svg) 
2025-02-17T15:56:42Z

- [https://github.com/sysirq/fortios-auth-bypass-exploit-CVE-2024-55591](https://github.com/sysirq/fortios-auth-bypass-exploit-CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/sysirq/fortios-auth-bypass-exploit-CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/sysirq/fortios-auth-bypass-exploit-CVE-2024-55591.svg) 
2025-01-23T07:38:18Z

- [https://github.com/rawtips/CVE-2024-55591](https://github.com/rawtips/CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/rawtips/CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/rawtips/CVE-2024-55591.svg) 
2025-01-29T19:45:36Z

- [https://github.com/amfg145/Private-CVE-2024-55591.](https://github.com/amfg145/Private-CVE-2024-55591.) :  
![starts](https://img.shields.io/github/stars/amfg145/Private-CVE-2024-55591..svg) 
![forks](https://img.shields.io/github/forks/amfg145/Private-CVE-2024-55591..svg) 
2025-01-24T13:01:26Z

- [https://github.com/0x7556/CVE-2024-55591](https://github.com/0x7556/CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/0x7556/CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/0x7556/CVE-2024-55591.svg) 
2025-02-15T08:02:16Z

## CVE-2024-54772
 An issue was discovered in the Winbox service of MikroTik RouterOS v6.43 through v7.16.1. A discrepancy in response times between connection attempts made with a valid username and those with an invalid username allows attackers to enumerate for valid accounts.

- [https://github.com/deauther890/CVE-2024-54772](https://github.com/deauther890/CVE-2024-54772) :  
![starts](https://img.shields.io/github/stars/deauther890/CVE-2024-54772.svg) 
![forks](https://img.shields.io/github/forks/deauther890/CVE-2024-54772.svg) 
2025-02-17T11:03:33Z

## CVE-2024-43762
 In multiple locations, there is a possible way to avoid unbinding of a service from the system due to a logic error in the code. This could lead to local escalation of privilege with no additional execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/Mahesh-970/CVE-2024-43762](https://github.com/Mahesh-970/CVE-2024-43762) :  
![starts](https://img.shields.io/github/stars/Mahesh-970/CVE-2024-43762.svg) 
![forks](https://img.shields.io/github/forks/Mahesh-970/CVE-2024-43762.svg) 
2025-02-17T13:03:42Z

## CVE-2024-42327
 A non-admin user account on the Zabbix frontend with the default User role, or with any other role that gives API access can exploit this vulnerability. An SQLi exists in the CUser class in the addRelatedObjects function, this function is being called from the CUser.get function which is available for every user who has API access.

- [https://github.com/BridgerAlderson/Zabbix-CVE-2024-42327-SQL-Injection-RCE](https://github.com/BridgerAlderson/Zabbix-CVE-2024-42327-SQL-Injection-RCE) :  
![starts](https://img.shields.io/github/stars/BridgerAlderson/Zabbix-CVE-2024-42327-SQL-Injection-RCE.svg) 
![forks](https://img.shields.io/github/forks/BridgerAlderson/Zabbix-CVE-2024-42327-SQL-Injection-RCE.svg) 
2025-01-03T13:49:03Z

- [https://github.com/aramosf/cve-2024-42327](https://github.com/aramosf/cve-2024-42327) :  
![starts](https://img.shields.io/github/stars/aramosf/cve-2024-42327.svg) 
![forks](https://img.shields.io/github/forks/aramosf/cve-2024-42327.svg) 
2024-12-01T01:18:36Z

- [https://github.com/compr00t/CVE-2024-42327](https://github.com/compr00t/CVE-2024-42327) :  
![starts](https://img.shields.io/github/stars/compr00t/CVE-2024-42327.svg) 
![forks](https://img.shields.io/github/forks/compr00t/CVE-2024-42327.svg) 
2024-12-03T12:56:52Z

- [https://github.com/godylockz/CVE-2024-42327](https://github.com/godylockz/CVE-2024-42327) :  
![starts](https://img.shields.io/github/stars/godylockz/CVE-2024-42327.svg) 
![forks](https://img.shields.io/github/forks/godylockz/CVE-2024-42327.svg) 
2025-02-17T05:05:47Z

- [https://github.com/watchdog1337/CVE-2024-42327_Zabbix_SQLI](https://github.com/watchdog1337/CVE-2024-42327_Zabbix_SQLI) :  
![starts](https://img.shields.io/github/stars/watchdog1337/CVE-2024-42327_Zabbix_SQLI.svg) 
![forks](https://img.shields.io/github/forks/watchdog1337/CVE-2024-42327_Zabbix_SQLI.svg) 
2024-12-08T12:27:53Z

- [https://github.com/depers-rus/CVE-2024-42327](https://github.com/depers-rus/CVE-2024-42327) :  
![starts](https://img.shields.io/github/stars/depers-rus/CVE-2024-42327.svg) 
![forks](https://img.shields.io/github/forks/depers-rus/CVE-2024-42327.svg) 
2024-12-06T18:56:49Z

- [https://github.com/igorbf495/CVE-2024-42327](https://github.com/igorbf495/CVE-2024-42327) :  
![starts](https://img.shields.io/github/stars/igorbf495/CVE-2024-42327.svg) 
![forks](https://img.shields.io/github/forks/igorbf495/CVE-2024-42327.svg) 
2024-12-12T19:21:44Z

- [https://github.com/itform-fr/Zabbix---CVE-2024-42327](https://github.com/itform-fr/Zabbix---CVE-2024-42327) :  
![starts](https://img.shields.io/github/stars/itform-fr/Zabbix---CVE-2024-42327.svg) 
![forks](https://img.shields.io/github/forks/itform-fr/Zabbix---CVE-2024-42327.svg) 
2024-12-11T00:46:22Z

## CVE-2024-23828
 Nginx-UI is a web interface to manage Nginx configurations. It is vulnerable to an authenticated arbitrary command execution via CRLF attack when changing the value of test_config_cmd or start_cmd. This vulnerability exists due to an incomplete fix for CVE-2024-22197 and CVE-2024-22198. This vulnerability has been patched in version 2.0.0.beta.12.

- [https://github.com/oxagast/oxasploits](https://github.com/oxagast/oxasploits) :  
![starts](https://img.shields.io/github/stars/oxagast/oxasploits.svg) 
![forks](https://img.shields.io/github/forks/oxagast/oxasploits.svg) 
2025-02-17T23:47:49Z

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

- [https://github.com/h8sU/wordpress-cve-2024-10924-exploit](https://github.com/h8sU/wordpress-cve-2024-10924-exploit) :  
![starts](https://img.shields.io/github/stars/h8sU/wordpress-cve-2024-10924-exploit.svg) 
![forks](https://img.shields.io/github/forks/h8sU/wordpress-cve-2024-10924-exploit.svg) 
2025-02-14T13:50:31Z

- [https://github.com/Nxploited/CVE-2024-10924-Exploit](https://github.com/Nxploited/CVE-2024-10924-Exploit) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-10924-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-10924-Exploit.svg) 
2025-02-02T23:26:52Z

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

- [https://github.com/Hunt3r850/CVE-2024-10924-PoC](https://github.com/Hunt3r850/CVE-2024-10924-PoC) :  
![starts](https://img.shields.io/github/stars/Hunt3r850/CVE-2024-10924-PoC.svg) 
![forks](https://img.shields.io/github/forks/Hunt3r850/CVE-2024-10924-PoC.svg) 
2024-12-03T13:10:44Z

## CVE-2024-4367
 A type check was missing when handling fonts in PDF.js, which would allow arbitrary JavaScript execution in the PDF.js context. This vulnerability affects Firefox  126, Firefox ESR  115.11, and Thunderbird  115.11.

- [https://github.com/LOURC0D3/CVE-2024-4367-PoC](https://github.com/LOURC0D3/CVE-2024-4367-PoC) :  
![starts](https://img.shields.io/github/stars/LOURC0D3/CVE-2024-4367-PoC.svg) 
![forks](https://img.shields.io/github/forks/LOURC0D3/CVE-2024-4367-PoC.svg) 
2024-06-07T03:28:00Z

- [https://github.com/s4vvysec/CVE-2024-4367-POC](https://github.com/s4vvysec/CVE-2024-4367-POC) :  
![starts](https://img.shields.io/github/stars/s4vvysec/CVE-2024-4367-POC.svg) 
![forks](https://img.shields.io/github/forks/s4vvysec/CVE-2024-4367-POC.svg) 
2024-05-20T23:09:43Z

- [https://github.com/spaceraccoon/detect-cve-2024-4367](https://github.com/spaceraccoon/detect-cve-2024-4367) :  
![starts](https://img.shields.io/github/stars/spaceraccoon/detect-cve-2024-4367.svg) 
![forks](https://img.shields.io/github/forks/spaceraccoon/detect-cve-2024-4367.svg) 
2024-05-27T03:06:09Z

- [https://github.com/Zombie-Kaiser/cve-2024-4367-PoC-fixed](https://github.com/Zombie-Kaiser/cve-2024-4367-PoC-fixed) :  
![starts](https://img.shields.io/github/stars/Zombie-Kaiser/cve-2024-4367-PoC-fixed.svg) 
![forks](https://img.shields.io/github/forks/Zombie-Kaiser/cve-2024-4367-PoC-fixed.svg) 
2024-06-13T15:19:57Z

- [https://github.com/snyk-labs/pdfjs-vuln-demo](https://github.com/snyk-labs/pdfjs-vuln-demo) :  
![starts](https://img.shields.io/github/stars/snyk-labs/pdfjs-vuln-demo.svg) 
![forks](https://img.shields.io/github/forks/snyk-labs/pdfjs-vuln-demo.svg) 
2024-06-20T13:40:31Z

- [https://github.com/UnHackerEnCapital/PDFernetRemotelo](https://github.com/UnHackerEnCapital/PDFernetRemotelo) :  
![starts](https://img.shields.io/github/stars/UnHackerEnCapital/PDFernetRemotelo.svg) 
![forks](https://img.shields.io/github/forks/UnHackerEnCapital/PDFernetRemotelo.svg) 
2024-06-20T00:02:49Z

- [https://github.com/clarkio/pdfjs-vuln-demo](https://github.com/clarkio/pdfjs-vuln-demo) :  
![starts](https://img.shields.io/github/stars/clarkio/pdfjs-vuln-demo.svg) 
![forks](https://img.shields.io/github/forks/clarkio/pdfjs-vuln-demo.svg) 
2024-11-10T04:17:31Z

- [https://github.com/Masamuneee/CVE-2024-4367-Analysis](https://github.com/Masamuneee/CVE-2024-4367-Analysis) :  
![starts](https://img.shields.io/github/stars/Masamuneee/CVE-2024-4367-Analysis.svg) 
![forks](https://img.shields.io/github/forks/Masamuneee/CVE-2024-4367-Analysis.svg) 
2024-09-04T15:17:57Z

- [https://github.com/inpentest/CVE-2024-4367-PoC](https://github.com/inpentest/CVE-2024-4367-PoC) :  
![starts](https://img.shields.io/github/stars/inpentest/CVE-2024-4367-PoC.svg) 
![forks](https://img.shields.io/github/forks/inpentest/CVE-2024-4367-PoC.svg) 
2025-02-17T17:31:54Z

- [https://github.com/Scivous/CVE-2024-4367-npm](https://github.com/Scivous/CVE-2024-4367-npm) :  
![starts](https://img.shields.io/github/stars/Scivous/CVE-2024-4367-npm.svg) 
![forks](https://img.shields.io/github/forks/Scivous/CVE-2024-4367-npm.svg) 
2024-06-21T08:16:42Z

- [https://github.com/exfil0/WEAPONIZING-CVE-2024-4367](https://github.com/exfil0/WEAPONIZING-CVE-2024-4367) :  
![starts](https://img.shields.io/github/stars/exfil0/WEAPONIZING-CVE-2024-4367.svg) 
![forks](https://img.shields.io/github/forks/exfil0/WEAPONIZING-CVE-2024-4367.svg) 
2025-01-05T19:21:50Z

- [https://github.com/avalahEE/pdfjs_disable_eval](https://github.com/avalahEE/pdfjs_disable_eval) :  
![starts](https://img.shields.io/github/stars/avalahEE/pdfjs_disable_eval.svg) 
![forks](https://img.shields.io/github/forks/avalahEE/pdfjs_disable_eval.svg) 
2024-05-27T07:23:33Z

- [https://github.com/pedrochalegre7/CVE-2024-4367-pdf-sample](https://github.com/pedrochalegre7/CVE-2024-4367-pdf-sample) :  
![starts](https://img.shields.io/github/stars/pedrochalegre7/CVE-2024-4367-pdf-sample.svg) 
![forks](https://img.shields.io/github/forks/pedrochalegre7/CVE-2024-4367-pdf-sample.svg) 
2024-11-07T14:28:41Z

## CVE-2023-22527
 A template injection vulnerability on older versions of Confluence Data Center and Server allows an unauthenticated attacker to achieve RCE on an affected instance. Customers using an affected version must take immediate action.Most recent supported versions of Confluence Data Center and Server are not affected by this vulnerability as it was ultimately mitigated during regular version updates. However, Atlassian recommends that customers take care to install the latest version to protect their instances from non-critical vulnerabilities outlined in Atlassians January Security Bulletin.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2024-11-20T12:44:28Z

- [https://github.com/Boogipop/CVE-2023-22527-Godzilla-MEMSHELL](https://github.com/Boogipop/CVE-2023-22527-Godzilla-MEMSHELL) :  
![starts](https://img.shields.io/github/stars/Boogipop/CVE-2023-22527-Godzilla-MEMSHELL.svg) 
![forks](https://img.shields.io/github/forks/Boogipop/CVE-2023-22527-Godzilla-MEMSHELL.svg) 
2024-02-21T05:49:59Z

- [https://github.com/M0untainShley/CVE-2023-22527-MEMSHELL](https://github.com/M0untainShley/CVE-2023-22527-MEMSHELL) :  
![starts](https://img.shields.io/github/stars/M0untainShley/CVE-2023-22527-MEMSHELL.svg) 
![forks](https://img.shields.io/github/forks/M0untainShley/CVE-2023-22527-MEMSHELL.svg) 
2024-04-24T02:34:16Z

- [https://github.com/Avento/CVE-2023-22527_Confluence_RCE](https://github.com/Avento/CVE-2023-22527_Confluence_RCE) :  
![starts](https://img.shields.io/github/stars/Avento/CVE-2023-22527_Confluence_RCE.svg) 
![forks](https://img.shields.io/github/forks/Avento/CVE-2023-22527_Confluence_RCE.svg) 
2024-01-23T09:57:31Z

- [https://github.com/Manh130902/CVE-2023-22527-POC](https://github.com/Manh130902/CVE-2023-22527-POC) :  
![starts](https://img.shields.io/github/stars/Manh130902/CVE-2023-22527-POC.svg) 
![forks](https://img.shields.io/github/forks/Manh130902/CVE-2023-22527-POC.svg) 
2024-01-23T12:03:00Z

- [https://github.com/VNCERT-CC/CVE-2023-22527-confluence](https://github.com/VNCERT-CC/CVE-2023-22527-confluence) :  
![starts](https://img.shields.io/github/stars/VNCERT-CC/CVE-2023-22527-confluence.svg) 
![forks](https://img.shields.io/github/forks/VNCERT-CC/CVE-2023-22527-confluence.svg) 
2024-01-23T07:16:40Z

- [https://github.com/Vozec/CVE-2023-22527](https://github.com/Vozec/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/Vozec/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/Vozec/CVE-2023-22527.svg) 
2024-01-23T09:13:39Z

- [https://github.com/Chocapikk/CVE-2023-22527](https://github.com/Chocapikk/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2023-22527.svg) 
2024-01-23T11:30:10Z

- [https://github.com/RevoltSecurities/CVE-2023-22527](https://github.com/RevoltSecurities/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/RevoltSecurities/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/RevoltSecurities/CVE-2023-22527.svg) 
2024-01-23T17:18:36Z

- [https://github.com/thanhlam-attt/CVE-2023-22527](https://github.com/thanhlam-attt/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/thanhlam-attt/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/thanhlam-attt/CVE-2023-22527.svg) 
2024-01-25T17:54:24Z

- [https://github.com/adminlove520/CVE-2023-22527](https://github.com/adminlove520/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/adminlove520/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/adminlove520/CVE-2023-22527.svg) 
2024-01-25T10:54:57Z

- [https://github.com/C1ph3rX13/CVE-2023-22527](https://github.com/C1ph3rX13/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/C1ph3rX13/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/C1ph3rX13/CVE-2023-22527.svg) 
2024-01-23T09:04:15Z

- [https://github.com/yoryio/CVE-2023-22527](https://github.com/yoryio/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2023-22527.svg) 
2024-03-15T05:15:05Z

- [https://github.com/BBD-YZZ/Confluence-RCE](https://github.com/BBD-YZZ/Confluence-RCE) :  
![starts](https://img.shields.io/github/stars/BBD-YZZ/Confluence-RCE.svg) 
![forks](https://img.shields.io/github/forks/BBD-YZZ/Confluence-RCE.svg) 
2024-08-26T09:24:31Z

- [https://github.com/vulncheck-oss/cve-2023-22527](https://github.com/vulncheck-oss/cve-2023-22527) :  
![starts](https://img.shields.io/github/stars/vulncheck-oss/cve-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/vulncheck-oss/cve-2023-22527.svg) 
2025-02-17T08:59:48Z

- [https://github.com/Privia-Security/CVE-2023-22527](https://github.com/Privia-Security/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/Privia-Security/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/Privia-Security/CVE-2023-22527.svg) 
2024-01-25T06:39:02Z

- [https://github.com/Niuwoo/CVE-2023-22527](https://github.com/Niuwoo/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/Niuwoo/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/Niuwoo/CVE-2023-22527.svg) 
2024-01-24T01:28:57Z

- [https://github.com/Drun1baby/CVE-2023-22527](https://github.com/Drun1baby/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/Drun1baby/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/Drun1baby/CVE-2023-22527.svg) 
2024-01-22T12:07:37Z

- [https://github.com/Sudistark/patch-diff-CVE-2023-22527](https://github.com/Sudistark/patch-diff-CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/Sudistark/patch-diff-CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/Sudistark/patch-diff-CVE-2023-22527.svg) 
2024-01-18T14:09:39Z

- [https://github.com/ga0we1/CVE-2023-22527_Confluence_RCE](https://github.com/ga0we1/CVE-2023-22527_Confluence_RCE) :  
![starts](https://img.shields.io/github/stars/ga0we1/CVE-2023-22527_Confluence_RCE.svg) 
![forks](https://img.shields.io/github/forks/ga0we1/CVE-2023-22527_Confluence_RCE.svg) 
2024-01-17T07:12:18Z

- [https://github.com/AxthonyV/CVE-2023-22527](https://github.com/AxthonyV/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/AxthonyV/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/AxthonyV/CVE-2023-22527.svg) 
2024-10-07T04:48:05Z

- [https://github.com/kh4sh3i/CVE-2023-22527](https://github.com/kh4sh3i/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/kh4sh3i/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/kh4sh3i/CVE-2023-22527.svg) 
2024-10-08T14:45:46Z

- [https://github.com/cleverg0d/CVE-2023-22527](https://github.com/cleverg0d/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/cleverg0d/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/cleverg0d/CVE-2023-22527.svg) 
2024-01-22T13:31:42Z

- [https://github.com/MaanVader/CVE-2023-22527-POC](https://github.com/MaanVader/CVE-2023-22527-POC) :  
![starts](https://img.shields.io/github/stars/MaanVader/CVE-2023-22527-POC.svg) 
![forks](https://img.shields.io/github/forks/MaanVader/CVE-2023-22527-POC.svg) 
2024-01-25T10:42:35Z

- [https://github.com/YongYe-Security/CVE-2023-22527](https://github.com/YongYe-Security/CVE-2023-22527) :  
![starts](https://img.shields.io/github/stars/YongYe-Security/CVE-2023-22527.svg) 
![forks](https://img.shields.io/github/forks/YongYe-Security/CVE-2023-22527.svg) 
2024-02-02T04:23:29Z

## CVE-2021-45046
 It was found that the fix to address CVE-2021-44228 in Apache Log4j 2.15.0 was incomplete in certain non-default configurations. This could allows attackers with control over Thread Context Map (MDC) input data when the logging configuration uses a non-default Pattern Layout with either a Context Lookup (for example, $${ctx:loginId}) or a Thread Context Map pattern (%X, %mdc, or %MDC) to craft malicious input data using a JNDI Lookup pattern resulting in an information leak and remote code execution in some environments and local code execution in all environments. Log4j 2.16.0 (Java 8) and 2.12.2 (Java 7) fix this issue by removing support for message lookup patterns and disabling JNDI functionality by default.

- [https://github.com/NCSC-NL/log4shell](https://github.com/NCSC-NL/log4shell) :  
![starts](https://img.shields.io/github/stars/NCSC-NL/log4shell.svg) 
![forks](https://img.shields.io/github/forks/NCSC-NL/log4shell.svg) 
2022-06-15T23:59:35Z

- [https://github.com/cisagov/log4j-scanner](https://github.com/cisagov/log4j-scanner) :  
![starts](https://img.shields.io/github/stars/cisagov/log4j-scanner.svg) 
![forks](https://img.shields.io/github/forks/cisagov/log4j-scanner.svg) 
2022-12-06T14:38:33Z

- [https://github.com/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words](https://github.com/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words) :  
![starts](https://img.shields.io/github/stars/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words.svg) 
![forks](https://img.shields.io/github/forks/Puliczek/CVE-2021-44228-PoC-log4j-bypass-words.svg) 
2022-01-15T16:18:44Z

- [https://github.com/logpresso/CVE-2021-44228-Scanner](https://github.com/logpresso/CVE-2021-44228-Scanner) :  
![starts](https://img.shields.io/github/stars/logpresso/CVE-2021-44228-Scanner.svg) 
![forks](https://img.shields.io/github/forks/logpresso/CVE-2021-44228-Scanner.svg) 
2022-04-07T14:47:03Z

- [https://github.com/mergebase/log4j-detector](https://github.com/mergebase/log4j-detector) :  
![starts](https://img.shields.io/github/stars/mergebase/log4j-detector.svg) 
![forks](https://img.shields.io/github/forks/mergebase/log4j-detector.svg) 
2022-03-10T18:44:50Z

- [https://github.com/fox-it/log4j-finder](https://github.com/fox-it/log4j-finder) :  
![starts](https://img.shields.io/github/stars/fox-it/log4j-finder.svg) 
![forks](https://img.shields.io/github/forks/fox-it/log4j-finder.svg) 
2022-12-27T17:57:19Z

- [https://github.com/Qualys/log4jscanwin](https://github.com/Qualys/log4jscanwin) :  
![starts](https://img.shields.io/github/stars/Qualys/log4jscanwin.svg) 
![forks](https://img.shields.io/github/forks/Qualys/log4jscanwin.svg) 
2023-03-22T06:18:58Z

- [https://github.com/alexbakker/log4shell-tools](https://github.com/alexbakker/log4shell-tools) :  
![starts](https://img.shields.io/github/stars/alexbakker/log4shell-tools.svg) 
![forks](https://img.shields.io/github/forks/alexbakker/log4shell-tools.svg) 
2024-04-07T22:45:53Z

- [https://github.com/lijiejie/log4j2_vul_local_scanner](https://github.com/lijiejie/log4j2_vul_local_scanner) :  
![starts](https://img.shields.io/github/stars/lijiejie/log4j2_vul_local_scanner.svg) 
![forks](https://img.shields.io/github/forks/lijiejie/log4j2_vul_local_scanner.svg) 
2021-12-22T06:24:42Z

- [https://github.com/zhzyker/logmap](https://github.com/zhzyker/logmap) :  
![starts](https://img.shields.io/github/stars/zhzyker/logmap.svg) 
![forks](https://img.shields.io/github/forks/zhzyker/logmap.svg) 
2021-12-24T09:42:51Z

- [https://github.com/dtact/divd-2021-00038--log4j-scanner](https://github.com/dtact/divd-2021-00038--log4j-scanner) :  
![starts](https://img.shields.io/github/stars/dtact/divd-2021-00038--log4j-scanner.svg) 
![forks](https://img.shields.io/github/forks/dtact/divd-2021-00038--log4j-scanner.svg) 
2021-12-28T22:21:52Z

- [https://github.com/1lann/log4shelldetect](https://github.com/1lann/log4shelldetect) :  
![starts](https://img.shields.io/github/stars/1lann/log4shelldetect.svg) 
![forks](https://img.shields.io/github/forks/1lann/log4shelldetect.svg) 
2022-01-05T23:07:50Z

- [https://github.com/HynekPetrak/log4shell-finder](https://github.com/HynekPetrak/log4shell-finder) :  
![starts](https://img.shields.io/github/stars/HynekPetrak/log4shell-finder.svg) 
![forks](https://img.shields.io/github/forks/HynekPetrak/log4shell-finder.svg) 
2023-06-21T11:37:03Z

- [https://github.com/darkarnium/Log4j-CVE-Detect](https://github.com/darkarnium/Log4j-CVE-Detect) :  
![starts](https://img.shields.io/github/stars/darkarnium/Log4j-CVE-Detect.svg) 
![forks](https://img.shields.io/github/forks/darkarnium/Log4j-CVE-Detect.svg) 
2021-12-18T22:20:25Z

- [https://github.com/r3kind1e/Log4Shell-obfuscated-payloads-generator](https://github.com/r3kind1e/Log4Shell-obfuscated-payloads-generator) :  
![starts](https://img.shields.io/github/stars/r3kind1e/Log4Shell-obfuscated-payloads-generator.svg) 
![forks](https://img.shields.io/github/forks/r3kind1e/Log4Shell-obfuscated-payloads-generator.svg) 
2022-05-26T03:18:31Z

- [https://github.com/cckuailong/Log4j_CVE-2021-45046](https://github.com/cckuailong/Log4j_CVE-2021-45046) :  
![starts](https://img.shields.io/github/stars/cckuailong/Log4j_CVE-2021-45046.svg) 
![forks](https://img.shields.io/github/forks/cckuailong/Log4j_CVE-2021-45046.svg) 
2021-12-23T10:57:19Z

- [https://github.com/mergebase/log4j-samples](https://github.com/mergebase/log4j-samples) :  
![starts](https://img.shields.io/github/stars/mergebase/log4j-samples.svg) 
![forks](https://img.shields.io/github/forks/mergebase/log4j-samples.svg) 
2021-12-30T05:15:54Z

- [https://github.com/xsultan/log4jshield](https://github.com/xsultan/log4jshield) :  
![starts](https://img.shields.io/github/stars/xsultan/log4jshield.svg) 
![forks](https://img.shields.io/github/forks/xsultan/log4jshield.svg) 
2021-12-23T04:50:38Z

- [https://github.com/hupe1980/scan4log4shell](https://github.com/hupe1980/scan4log4shell) :  
![starts](https://img.shields.io/github/stars/hupe1980/scan4log4shell.svg) 
![forks](https://img.shields.io/github/forks/hupe1980/scan4log4shell.svg) 
2022-02-15T13:04:54Z

- [https://github.com/0xsyr0/Log4Shell](https://github.com/0xsyr0/Log4Shell) :  
![starts](https://img.shields.io/github/stars/0xsyr0/Log4Shell.svg) 
![forks](https://img.shields.io/github/forks/0xsyr0/Log4Shell.svg) 
2024-02-21T15:47:36Z

- [https://github.com/DXC-StrikeForce/Burp-Log4j-HammerTime](https://github.com/DXC-StrikeForce/Burp-Log4j-HammerTime) :  
![starts](https://img.shields.io/github/stars/DXC-StrikeForce/Burp-Log4j-HammerTime.svg) 
![forks](https://img.shields.io/github/forks/DXC-StrikeForce/Burp-Log4j-HammerTime.svg) 
2021-12-16T17:02:30Z

- [https://github.com/pfichtner/log4shell-hunter](https://github.com/pfichtner/log4shell-hunter) :  
![starts](https://img.shields.io/github/stars/pfichtner/log4shell-hunter.svg) 
![forks](https://img.shields.io/github/forks/pfichtner/log4shell-hunter.svg) 
2025-02-17T08:21:33Z

- [https://github.com/thl-cmk/CVE-log4j-check_mk-plugin](https://github.com/thl-cmk/CVE-log4j-check_mk-plugin) :  
![starts](https://img.shields.io/github/stars/thl-cmk/CVE-log4j-check_mk-plugin.svg) 
![forks](https://img.shields.io/github/forks/thl-cmk/CVE-log4j-check_mk-plugin.svg) 
2022-02-14T11:08:43Z

- [https://github.com/BobTheShoplifter/CVE-2021-45046-Info](https://github.com/BobTheShoplifter/CVE-2021-45046-Info) :  
![starts](https://img.shields.io/github/stars/BobTheShoplifter/CVE-2021-45046-Info.svg) 
![forks](https://img.shields.io/github/forks/BobTheShoplifter/CVE-2021-45046-Info.svg) 
2022-04-07T19:07:20Z

- [https://github.com/TheInterception/Log4J-Simulation-Tool](https://github.com/TheInterception/Log4J-Simulation-Tool) :  
![starts](https://img.shields.io/github/stars/TheInterception/Log4J-Simulation-Tool.svg) 
![forks](https://img.shields.io/github/forks/TheInterception/Log4J-Simulation-Tool.svg) 
2021-12-25T01:51:35Z

- [https://github.com/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832](https://github.com/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832) :  
![starts](https://img.shields.io/github/stars/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832.svg) 
![forks](https://img.shields.io/github/forks/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832.svg) 
2022-01-03T17:43:06Z

- [https://github.com/ludy-dev/cve-2021-45046](https://github.com/ludy-dev/cve-2021-45046) :  
![starts](https://img.shields.io/github/stars/ludy-dev/cve-2021-45046.svg) 
![forks](https://img.shields.io/github/forks/ludy-dev/cve-2021-45046.svg) 
2021-12-18T11:53:12Z

- [https://github.com/trickyearlobe/inspec-log4j](https://github.com/trickyearlobe/inspec-log4j) :  
![starts](https://img.shields.io/github/stars/trickyearlobe/inspec-log4j.svg) 
![forks](https://img.shields.io/github/forks/trickyearlobe/inspec-log4j.svg) 
2021-12-19T05:29:33Z

- [https://github.com/manishkanyal/log4j-scanner](https://github.com/manishkanyal/log4j-scanner) :  
![starts](https://img.shields.io/github/stars/manishkanyal/log4j-scanner.svg) 
![forks](https://img.shields.io/github/forks/manishkanyal/log4j-scanner.svg) 
2022-04-17T11:27:22Z

- [https://github.com/Aschen/log4j-patched](https://github.com/Aschen/log4j-patched) :  
![starts](https://img.shields.io/github/stars/Aschen/log4j-patched.svg) 
![forks](https://img.shields.io/github/forks/Aschen/log4j-patched.svg) 
2021-12-17T18:41:35Z

- [https://github.com/demonrvm/Log4ShellRemediation](https://github.com/demonrvm/Log4ShellRemediation) :  
![starts](https://img.shields.io/github/stars/demonrvm/Log4ShellRemediation.svg) 
![forks](https://img.shields.io/github/forks/demonrvm/Log4ShellRemediation.svg) 
2023-04-04T00:04:34Z

- [https://github.com/gitlab-de/log4j-resources](https://github.com/gitlab-de/log4j-resources) :  
![starts](https://img.shields.io/github/stars/gitlab-de/log4j-resources.svg) 
![forks](https://img.shields.io/github/forks/gitlab-de/log4j-resources.svg) 
2021-12-18T15:25:14Z

- [https://github.com/at-bay/log4j-checker](https://github.com/at-bay/log4j-checker) :  
![starts](https://img.shields.io/github/stars/at-bay/log4j-checker.svg) 
![forks](https://img.shields.io/github/forks/at-bay/log4j-checker.svg) 
2021-12-20T20:50:48Z

- [https://github.com/andalik/log4j-filescan](https://github.com/andalik/log4j-filescan) :  
![starts](https://img.shields.io/github/stars/andalik/log4j-filescan.svg) 
![forks](https://img.shields.io/github/forks/andalik/log4j-filescan.svg) 
2022-03-05T23:01:15Z

- [https://github.com/nagten/JndiLookupRemoval](https://github.com/nagten/JndiLookupRemoval) :  
![starts](https://img.shields.io/github/stars/nagten/JndiLookupRemoval.svg) 
![forks](https://img.shields.io/github/forks/nagten/JndiLookupRemoval.svg) 
2021-12-28T20:54:01Z

- [https://github.com/juergenhoetzel/log4j2go](https://github.com/juergenhoetzel/log4j2go) :  
![starts](https://img.shields.io/github/stars/juergenhoetzel/log4j2go.svg) 
![forks](https://img.shields.io/github/forks/juergenhoetzel/log4j2go.svg) 
2021-12-20T18:11:28Z

- [https://github.com/Afrouper/MavenDependencyCVE-Scanner](https://github.com/Afrouper/MavenDependencyCVE-Scanner) :  
![starts](https://img.shields.io/github/stars/Afrouper/MavenDependencyCVE-Scanner.svg) 
![forks](https://img.shields.io/github/forks/Afrouper/MavenDependencyCVE-Scanner.svg) 
2025-02-10T04:53:00Z

- [https://github.com/tejas-nagchandi/CVE-2021-45046](https://github.com/tejas-nagchandi/CVE-2021-45046) :  
![starts](https://img.shields.io/github/stars/tejas-nagchandi/CVE-2021-45046.svg) 
![forks](https://img.shields.io/github/forks/tejas-nagchandi/CVE-2021-45046.svg) 
2021-12-16T07:13:00Z

- [https://github.com/CaptanMoss/Log4Shell-Sandbox-Signature](https://github.com/CaptanMoss/Log4Shell-Sandbox-Signature) :  
![starts](https://img.shields.io/github/stars/CaptanMoss/Log4Shell-Sandbox-Signature.svg) 
![forks](https://img.shields.io/github/forks/CaptanMoss/Log4Shell-Sandbox-Signature.svg) 
2021-12-26T19:51:55Z

- [https://github.com/shaily29-eng/CyberSecurity_CVE-2021-45046](https://github.com/shaily29-eng/CyberSecurity_CVE-2021-45046) :  
![starts](https://img.shields.io/github/stars/shaily29-eng/CyberSecurity_CVE-2021-45046.svg) 
![forks](https://img.shields.io/github/forks/shaily29-eng/CyberSecurity_CVE-2021-45046.svg) 
2024-05-21T23:30:06Z

- [https://github.com/pravin-pp/log4j2-CVE-2021-45046](https://github.com/pravin-pp/log4j2-CVE-2021-45046) :  
![starts](https://img.shields.io/github/stars/pravin-pp/log4j2-CVE-2021-45046.svg) 
![forks](https://img.shields.io/github/forks/pravin-pp/log4j2-CVE-2021-45046.svg) 
2021-12-15T19:42:12Z

- [https://github.com/DANSI/PowerShell-Log4J-Scanner](https://github.com/DANSI/PowerShell-Log4J-Scanner) :  
![starts](https://img.shields.io/github/stars/DANSI/PowerShell-Log4J-Scanner.svg) 
![forks](https://img.shields.io/github/forks/DANSI/PowerShell-Log4J-Scanner.svg) 
2022-03-29T21:43:32Z

- [https://github.com/lukepasek/log4jjndilookupremove](https://github.com/lukepasek/log4jjndilookupremove) :  
![starts](https://img.shields.io/github/stars/lukepasek/log4jjndilookupremove.svg) 
![forks](https://img.shields.io/github/forks/lukepasek/log4jjndilookupremove.svg) 
2022-01-04T14:24:19Z

- [https://github.com/yannart/log4shell-scanner-rs](https://github.com/yannart/log4shell-scanner-rs) :  
![starts](https://img.shields.io/github/stars/yannart/log4shell-scanner-rs.svg) 
![forks](https://img.shields.io/github/forks/yannart/log4shell-scanner-rs.svg) 
2022-09-26T01:32:06Z

- [https://github.com/richardbischof/log4j-detector-to-csv](https://github.com/richardbischof/log4j-detector-to-csv) :  
![starts](https://img.shields.io/github/stars/richardbischof/log4j-detector-to-csv.svg) 
![forks](https://img.shields.io/github/forks/richardbischof/log4j-detector-to-csv.svg) 
2021-12-27T11:44:36Z

## CVE-2021-44967
 A Remote Code Execution (RCE) vulnerabilty exists in LimeSurvey 5.2.4 via the upload and install plugins function, which could let a remote malicious user upload an arbitrary PHP code file. NOTE: the Supplier's position is that plugins intentionally can contain arbitrary PHP code, and can only be installed by a superadmin, and therefore the security model is not violated by this finding.

- [https://github.com/godylockz/CVE-2021-44967](https://github.com/godylockz/CVE-2021-44967) :  
![starts](https://img.shields.io/github/stars/godylockz/CVE-2021-44967.svg) 
![forks](https://img.shields.io/github/forks/godylockz/CVE-2021-44967.svg) 
2025-02-17T05:33:43Z

- [https://github.com/N4s1rl1/Limesurvey-6.6.4-RCE](https://github.com/N4s1rl1/Limesurvey-6.6.4-RCE) :  
![starts](https://img.shields.io/github/stars/N4s1rl1/Limesurvey-6.6.4-RCE.svg) 
![forks](https://img.shields.io/github/forks/N4s1rl1/Limesurvey-6.6.4-RCE.svg) 
2025-01-13T15:34:49Z

- [https://github.com/D3Ext/CVE-2021-44967](https://github.com/D3Ext/CVE-2021-44967) :  
![starts](https://img.shields.io/github/stars/D3Ext/CVE-2021-44967.svg) 
![forks](https://img.shields.io/github/forks/D3Ext/CVE-2021-44967.svg) 
2025-01-10T11:59:26Z

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
2025-02-17T00:40:17Z

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

## CVE-2021-4034
 A local privilege escalation vulnerability was found on polkit's pkexec utility. The pkexec application is a setuid tool designed to allow unprivileged users to run commands as privileged users according predefined policies. The current version of pkexec doesn't handle the calling parameters count correctly and ends trying to execute environment variables as commands. An attacker can leverage this by crafting environment variables in such a way it'll induce pkexec to execute arbitrary code. When successfully executed the attack can cause a local privilege escalation given unprivileged users administrative rights on the target machine.

- [https://github.com/berdav/CVE-2021-4034](https://github.com/berdav/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/berdav/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/berdav/CVE-2021-4034.svg) 
2022-06-08T04:00:28Z

- [https://github.com/jm33-m0/emp3r0r](https://github.com/jm33-m0/emp3r0r) :  
![starts](https://img.shields.io/github/stars/jm33-m0/emp3r0r.svg) 
![forks](https://img.shields.io/github/forks/jm33-m0/emp3r0r.svg) 
2025-02-17T07:03:19Z

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

- [https://github.com/LJP-TW/CVE-2021-4034](https://github.com/LJP-TW/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/LJP-TW/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/LJP-TW/CVE-2021-4034.svg) 
2022-02-18T07:31:30Z

- [https://github.com/Anonymous-Family/CVE-2021-4034](https://github.com/Anonymous-Family/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Anonymous-Family/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Anonymous-Family/CVE-2021-4034.svg) 
2022-01-26T19:31:04Z

- [https://github.com/locksec/CVE-2021-4034](https://github.com/locksec/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/locksec/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/locksec/CVE-2021-4034.svg) 
2022-01-27T16:53:17Z

- [https://github.com/Pixailz/CVE-2021-4034](https://github.com/Pixailz/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/Pixailz/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/Pixailz/CVE-2021-4034.svg) 
2022-10-11T00:40:47Z

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

- [https://github.com/thatstraw/CVE-2021-4034](https://github.com/thatstraw/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/thatstraw/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/thatstraw/CVE-2021-4034.svg) 
2022-01-27T10:27:15Z

- [https://github.com/defhacks/cve-2021-4034](https://github.com/defhacks/cve-2021-4034) :  
![starts](https://img.shields.io/github/stars/defhacks/cve-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/defhacks/cve-2021-4034.svg) 
2022-03-04T05:32:29Z

- [https://github.com/0x01-sec/CVE-2021-4034-](https://github.com/0x01-sec/CVE-2021-4034-) :  
![starts](https://img.shields.io/github/stars/0x01-sec/CVE-2021-4034-.svg) 
![forks](https://img.shields.io/github/forks/0x01-sec/CVE-2021-4034-.svg) 
2022-01-29T23:29:48Z

- [https://github.com/mutur4/CVE-2021-4034](https://github.com/mutur4/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/mutur4/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/mutur4/CVE-2021-4034.svg) 
2024-04-10T14:48:27Z

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

- [https://github.com/vilasboasph/CVE-2021-4034](https://github.com/vilasboasph/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/vilasboasph/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/vilasboasph/CVE-2021-4034.svg) 
2022-01-26T19:46:54Z

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

- [https://github.com/cdxiaodong/CVE-2021-4034-touch](https://github.com/cdxiaodong/CVE-2021-4034-touch) :  
![starts](https://img.shields.io/github/stars/cdxiaodong/CVE-2021-4034-touch.svg) 
![forks](https://img.shields.io/github/forks/cdxiaodong/CVE-2021-4034-touch.svg) 
2024-01-04T07:43:23Z

- [https://github.com/CYB3RK1D/CVE-2021-4034-POC](https://github.com/CYB3RK1D/CVE-2021-4034-POC) :  
![starts](https://img.shields.io/github/stars/CYB3RK1D/CVE-2021-4034-POC.svg) 
![forks](https://img.shields.io/github/forks/CYB3RK1D/CVE-2021-4034-POC.svg) 
2022-04-08T17:26:41Z

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

# 2025-02-16
## CVE-2024-48990
 Qualys discovered that needrestart, before version 3.8, allows local attackers to execute arbitrary code as root by tricking needrestart into running the Python interpreter with an attacker-controlled PYTHONPATH environment variable.

- [https://github.com/makuga01/CVE-2024-48990-PoC](https://github.com/makuga01/CVE-2024-48990-PoC) :  
![starts](https://img.shields.io/github/stars/makuga01/CVE-2024-48990-PoC.svg) 
![forks](https://img.shields.io/github/forks/makuga01/CVE-2024-48990-PoC.svg) 
2024-11-20T18:49:33Z

- [https://github.com/pentestfunctions/CVE-2024-48990-PoC-Testing](https://github.com/pentestfunctions/CVE-2024-48990-PoC-Testing) :  
![starts](https://img.shields.io/github/stars/pentestfunctions/CVE-2024-48990-PoC-Testing.svg) 
![forks](https://img.shields.io/github/forks/pentestfunctions/CVE-2024-48990-PoC-Testing.svg) 
2024-11-24T07:56:49Z

- [https://github.com/ns989/CVE-2024-48990](https://github.com/ns989/CVE-2024-48990) :  
![starts](https://img.shields.io/github/stars/ns989/CVE-2024-48990.svg) 
![forks](https://img.shields.io/github/forks/ns989/CVE-2024-48990.svg) 
2024-11-22T01:17:00Z

- [https://github.com/r0xdeadbeef/CVE-2024-48990](https://github.com/r0xdeadbeef/CVE-2024-48990) :  
![starts](https://img.shields.io/github/stars/r0xdeadbeef/CVE-2024-48990.svg) 
![forks](https://img.shields.io/github/forks/r0xdeadbeef/CVE-2024-48990.svg) 
2024-12-01T16:27:46Z

- [https://github.com/ally-petitt/CVE-2024-48990-Exploit](https://github.com/ally-petitt/CVE-2024-48990-Exploit) :  
![starts](https://img.shields.io/github/stars/ally-petitt/CVE-2024-48990-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ally-petitt/CVE-2024-48990-Exploit.svg) 
2024-11-25T05:29:10Z

- [https://github.com/Cyb3rFr0g/CVE-2024-48990-PoC](https://github.com/Cyb3rFr0g/CVE-2024-48990-PoC) :  
![starts](https://img.shields.io/github/stars/Cyb3rFr0g/CVE-2024-48990-PoC.svg) 
![forks](https://img.shields.io/github/forks/Cyb3rFr0g/CVE-2024-48990-PoC.svg) 
2024-11-24T02:32:54Z

- [https://github.com/CyberCrowCC/CVE-2024-48990](https://github.com/CyberCrowCC/CVE-2024-48990) :  
![starts](https://img.shields.io/github/stars/CyberCrowCC/CVE-2024-48990.svg) 
![forks](https://img.shields.io/github/forks/CyberCrowCC/CVE-2024-48990.svg) 
2024-12-09T04:29:19Z

- [https://github.com/NullByte-7w7/CVE-2024-48990](https://github.com/NullByte-7w7/CVE-2024-48990) :  
![starts](https://img.shields.io/github/stars/NullByte-7w7/CVE-2024-48990.svg) 
![forks](https://img.shields.io/github/forks/NullByte-7w7/CVE-2024-48990.svg) 
2024-12-19T18:16:46Z

- [https://github.com/felmoltor/CVE-2024-48990](https://github.com/felmoltor/CVE-2024-48990) :  
![starts](https://img.shields.io/github/stars/felmoltor/CVE-2024-48990.svg) 
![forks](https://img.shields.io/github/forks/felmoltor/CVE-2024-48990.svg) 
2024-11-22T17:41:34Z

- [https://github.com/ten-ops/CVE-2024-48990_needrestart](https://github.com/ten-ops/CVE-2024-48990_needrestart) :  
![starts](https://img.shields.io/github/stars/ten-ops/CVE-2024-48990_needrestart.svg) 
![forks](https://img.shields.io/github/forks/ten-ops/CVE-2024-48990_needrestart.svg) 
2025-02-16T22:07:07Z

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
2025-02-16T05:51:09Z

## CVE-2024-23897
 Jenkins 2.441 and earlier, LTS 2.426.2 and earlier does not disable a feature of its CLI command parser that replaces an '@' character followed by a file path in an argument with the file's contents, allowing unauthenticated attackers to read arbitrary files on the Jenkins controller file system.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2024-11-20T12:44:28Z

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

- [https://github.com/Maalfer/CVE-2024-23897](https://github.com/Maalfer/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/Maalfer/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/Maalfer/CVE-2024-23897.svg) 
2024-05-17T11:54:26Z

- [https://github.com/jenkinsci-cert/SECURITY-3314-3315](https://github.com/jenkinsci-cert/SECURITY-3314-3315) :  
![starts](https://img.shields.io/github/stars/jenkinsci-cert/SECURITY-3314-3315.svg) 
![forks](https://img.shields.io/github/forks/jenkinsci-cert/SECURITY-3314-3315.svg) 
2024-02-20T14:13:25Z

- [https://github.com/verylazytech/CVE-2024-23897](https://github.com/verylazytech/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-23897.svg) 
2024-11-26T14:46:59Z

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

## CVE-2024-5452
 A remote code execution (RCE) vulnerability exists in the lightning-ai/pytorch-lightning library version 2.2.1 due to improper handling of deserialized user input and mismanagement of dunder attributes by the `deepdiff` library. The library uses `deepdiff.Delta` objects to modify application state based on frontend actions. However, it is possible to bypass the intended restrictions on modifying dunder attributes, allowing an attacker to construct a serialized delta that passes the deserializer whitelist and contains dunder attributes. When processed, this can be exploited to access other modules, classes, and instances, leading to arbitrary attribute write and total RCE on any self-hosted pytorch-lightning application in its default configuration, as the delta endpoint is enabled by default.

- [https://github.com/XiaomingX/cve-2024-5452-poc](https://github.com/XiaomingX/cve-2024-5452-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-5452-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-5452-poc.svg) 
2024-11-22T06:56:32Z

- [https://github.com/skrkcb2/CVE-2024-5452](https://github.com/skrkcb2/CVE-2024-5452) :  
![starts](https://img.shields.io/github/stars/skrkcb2/CVE-2024-5452.svg) 
![forks](https://img.shields.io/github/forks/skrkcb2/CVE-2024-5452.svg) 
2025-02-16T04:41:50Z

## CVE-2024-5084
 The Hash Form  Drag & Drop Form Builder plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'file_upload_action' function in all versions up to, and including, 1.1.0. This makes it possible for unauthenticated attackers to upload arbitrary files on the affected site's server which may make remote code execution possible.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/Chocapikk/CVE-2024-5084](https://github.com/Chocapikk/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-5084.svg) 
2024-07-17T23:40:18Z

- [https://github.com/KTN1990/CVE-2024-5084](https://github.com/KTN1990/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/KTN1990/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/KTN1990/CVE-2024-5084.svg) 
2024-05-31T19:51:13Z

- [https://github.com/WOOOOONG/CVE-2024-5084](https://github.com/WOOOOONG/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/WOOOOONG/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/WOOOOONG/CVE-2024-5084.svg) 
2024-07-03T04:24:46Z

- [https://github.com/z1gazaga/CVE-2024-5084](https://github.com/z1gazaga/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/z1gazaga/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/z1gazaga/CVE-2024-5084.svg) 
2024-11-21T07:11:34Z

- [https://github.com/k3lpi3b4nsh33/CVE-2024-5084](https://github.com/k3lpi3b4nsh33/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/k3lpi3b4nsh33/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/k3lpi3b4nsh33/CVE-2024-5084.svg) 
2024-06-06T03:29:24Z

- [https://github.com/Raeezrbr/CVE-2024-5084](https://github.com/Raeezrbr/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/Raeezrbr/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/Raeezrbr/CVE-2024-5084.svg) 
2024-11-30T10:55:58Z

- [https://github.com/ModeBrutal/CVE-2024-5084-Auto-Exploit](https://github.com/ModeBrutal/CVE-2024-5084-Auto-Exploit) :  
![starts](https://img.shields.io/github/stars/ModeBrutal/CVE-2024-5084-Auto-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ModeBrutal/CVE-2024-5084-Auto-Exploit.svg) 
2025-02-16T13:39:28Z

## CVE-2020-1938
 When using the Apache JServ Protocol (AJP), care must be taken when trusting incoming connections to Apache Tomcat. Tomcat treats AJP connections as having higher trust than, for example, a similar HTTP connection. If such connections are available to an attacker, they can be exploited in ways that may be surprising. In Apache Tomcat 9.0.0.M1 to 9.0.0.30, 8.5.0 to 8.5.50 and 7.0.0 to 7.0.99, Tomcat shipped with an AJP Connector enabled by default that listened on all configured IP addresses. It was expected (and recommended in the security guide) that this Connector would be disabled if not required. This vulnerability report identified a mechanism that allowed: - returning arbitrary files from anywhere in the web application - processing any file in the web application as a JSP Further, if the web application allowed file upload and stored those files within the web application (or the attacker was able to control the content of the web application by some other means) then this, along with the ability to process a file as a JSP, made remote code execution possible. It is important to note that mitigation is only required if an AJP port is accessible to untrusted users. Users wishing to take a defence-in-depth approach and block the vector that permits returning arbitrary files and execution as JSP may upgrade to Apache Tomcat 9.0.31, 8.5.51 or 7.0.100 or later. A number of changes were made to the default AJP Connector configuration in 9.0.31 to harden the default configuration. It is likely that users upgrading to 9.0.31, 8.5.51 or 7.0.100 or later will need to make small changes to their configurations.

- [https://github.com/zhzyker/exphub](https://github.com/zhzyker/exphub) :  
![starts](https://img.shields.io/github/stars/zhzyker/exphub.svg) 
![forks](https://img.shields.io/github/forks/zhzyker/exphub.svg) 
2021-04-04T09:13:57Z

- [https://github.com/LandGrey/ClassHound](https://github.com/LandGrey/ClassHound) :  
![starts](https://img.shields.io/github/stars/LandGrey/ClassHound.svg) 
![forks](https://img.shields.io/github/forks/LandGrey/ClassHound.svg) 
2021-05-10T02:20:35Z

- [https://github.com/hypn0s/AJPy](https://github.com/hypn0s/AJPy) :  
![starts](https://img.shields.io/github/stars/hypn0s/AJPy.svg) 
![forks](https://img.shields.io/github/forks/hypn0s/AJPy.svg) 
2023-09-06T14:20:35Z

- [https://github.com/00theway/Ghostcat-CNVD-2020-10487](https://github.com/00theway/Ghostcat-CNVD-2020-10487) :  
![starts](https://img.shields.io/github/stars/00theway/Ghostcat-CNVD-2020-10487.svg) 
![forks](https://img.shields.io/github/forks/00theway/Ghostcat-CNVD-2020-10487.svg) 
2020-03-09T14:51:43Z

- [https://github.com/bkfish/CNVD-2020-10487-Tomcat-Ajp-lfi-Scanner](https://github.com/bkfish/CNVD-2020-10487-Tomcat-Ajp-lfi-Scanner) :  
![starts](https://img.shields.io/github/stars/bkfish/CNVD-2020-10487-Tomcat-Ajp-lfi-Scanner.svg) 
![forks](https://img.shields.io/github/forks/bkfish/CNVD-2020-10487-Tomcat-Ajp-lfi-Scanner.svg) 
2021-11-26T07:40:35Z

- [https://github.com/tpt11fb/AttackTomcat](https://github.com/tpt11fb/AttackTomcat) :  
![starts](https://img.shields.io/github/stars/tpt11fb/AttackTomcat.svg) 
![forks](https://img.shields.io/github/forks/tpt11fb/AttackTomcat.svg) 
2022-11-15T09:05:50Z

- [https://github.com/lizhianyuguangming/TomcatScanPro](https://github.com/lizhianyuguangming/TomcatScanPro) :  
![starts](https://img.shields.io/github/stars/lizhianyuguangming/TomcatScanPro.svg) 
![forks](https://img.shields.io/github/forks/lizhianyuguangming/TomcatScanPro.svg) 
2024-11-13T03:12:58Z

- [https://github.com/nibiwodong/CNVD-2020-10487-Tomcat-ajp-POC](https://github.com/nibiwodong/CNVD-2020-10487-Tomcat-ajp-POC) :  
![starts](https://img.shields.io/github/stars/nibiwodong/CNVD-2020-10487-Tomcat-ajp-POC.svg) 
![forks](https://img.shields.io/github/forks/nibiwodong/CNVD-2020-10487-Tomcat-ajp-POC.svg) 
2020-02-23T17:06:06Z

- [https://github.com/sv3nbeast/CVE-2020-1938-Tomact-file_include-file_read](https://github.com/sv3nbeast/CVE-2020-1938-Tomact-file_include-file_read) :  
![starts](https://img.shields.io/github/stars/sv3nbeast/CVE-2020-1938-Tomact-file_include-file_read.svg) 
![forks](https://img.shields.io/github/forks/sv3nbeast/CVE-2020-1938-Tomact-file_include-file_read.svg) 
2020-02-21T10:19:52Z

- [https://github.com/xindongzhuaizhuai/CVE-2020-1938](https://github.com/xindongzhuaizhuai/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/xindongzhuaizhuai/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/xindongzhuaizhuai/CVE-2020-1938.svg) 
2020-03-02T20:25:35Z

- [https://github.com/laolisafe/CVE-2020-1938](https://github.com/laolisafe/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/laolisafe/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/laolisafe/CVE-2020-1938.svg) 
2020-02-21T02:49:57Z

- [https://github.com/woaiqiukui/CVE-2020-1938TomcatAjpScanner](https://github.com/woaiqiukui/CVE-2020-1938TomcatAjpScanner) :  
![starts](https://img.shields.io/github/stars/woaiqiukui/CVE-2020-1938TomcatAjpScanner.svg) 
![forks](https://img.shields.io/github/forks/woaiqiukui/CVE-2020-1938TomcatAjpScanner.svg) 
2020-02-22T01:58:22Z

- [https://github.com/Hancheng-Lei/Hacking-Vulnerability-CVE-2020-1938-Ghostcat](https://github.com/Hancheng-Lei/Hacking-Vulnerability-CVE-2020-1938-Ghostcat) :  
![starts](https://img.shields.io/github/stars/Hancheng-Lei/Hacking-Vulnerability-CVE-2020-1938-Ghostcat.svg) 
![forks](https://img.shields.io/github/forks/Hancheng-Lei/Hacking-Vulnerability-CVE-2020-1938-Ghostcat.svg) 
2022-11-27T06:14:19Z

- [https://github.com/fairyming/CVE-2020-1938](https://github.com/fairyming/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/fairyming/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/fairyming/CVE-2020-1938.svg) 
2020-02-21T08:45:51Z

- [https://github.com/dacade/CVE-2020-1938](https://github.com/dacade/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/dacade/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/dacade/CVE-2020-1938.svg) 
2020-02-28T07:08:16Z

- [https://github.com/doggycheng/CNVD-2020-10487](https://github.com/doggycheng/CNVD-2020-10487) :  
![starts](https://img.shields.io/github/stars/doggycheng/CNVD-2020-10487.svg) 
![forks](https://img.shields.io/github/forks/doggycheng/CNVD-2020-10487.svg) 
2020-03-31T07:17:04Z

- [https://github.com/fatal0/tomcat-cve-2020-1938-check](https://github.com/fatal0/tomcat-cve-2020-1938-check) :  
![starts](https://img.shields.io/github/stars/fatal0/tomcat-cve-2020-1938-check.svg) 
![forks](https://img.shields.io/github/forks/fatal0/tomcat-cve-2020-1938-check.svg) 
2020-02-25T08:55:09Z

- [https://github.com/w4fz5uck5/CVE-2020-1938-Clean-Version](https://github.com/w4fz5uck5/CVE-2020-1938-Clean-Version) :  
![starts](https://img.shields.io/github/stars/w4fz5uck5/CVE-2020-1938-Clean-Version.svg) 
![forks](https://img.shields.io/github/forks/w4fz5uck5/CVE-2020-1938-Clean-Version.svg) 
2023-09-12T13:07:16Z

- [https://github.com/Just1ceP4rtn3r/CVE-2020-1938-Tool](https://github.com/Just1ceP4rtn3r/CVE-2020-1938-Tool) :  
![starts](https://img.shields.io/github/stars/Just1ceP4rtn3r/CVE-2020-1938-Tool.svg) 
![forks](https://img.shields.io/github/forks/Just1ceP4rtn3r/CVE-2020-1938-Tool.svg) 
2020-03-20T09:37:54Z

- [https://github.com/YounesTasra-R4z3rSw0rd/CVE-2020-1938](https://github.com/YounesTasra-R4z3rSw0rd/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/YounesTasra-R4z3rSw0rd/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/YounesTasra-R4z3rSw0rd/CVE-2020-1938.svg) 
2022-08-21T15:49:16Z

- [https://github.com/delsadan/CNVD-2020-10487-Bulk-verification](https://github.com/delsadan/CNVD-2020-10487-Bulk-verification) :  
![starts](https://img.shields.io/github/stars/delsadan/CNVD-2020-10487-Bulk-verification.svg) 
![forks](https://img.shields.io/github/forks/delsadan/CNVD-2020-10487-Bulk-verification.svg) 
2020-02-24T08:18:02Z

- [https://github.com/sgdream/CVE-2020-1938](https://github.com/sgdream/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/sgdream/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/sgdream/CVE-2020-1938.svg) 
2020-02-20T16:54:45Z

- [https://github.com/Warelock/cve-2020-1938](https://github.com/Warelock/cve-2020-1938) :  
![starts](https://img.shields.io/github/stars/Warelock/cve-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/Warelock/cve-2020-1938.svg) 
2024-04-14T05:32:49Z

- [https://github.com/h7hac9/CVE-2020-1938](https://github.com/h7hac9/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/h7hac9/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/h7hac9/CVE-2020-1938.svg) 
2020-02-21T04:40:38Z

- [https://github.com/Neko-chanQwQ/CVE-2020-1938](https://github.com/Neko-chanQwQ/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/Neko-chanQwQ/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/Neko-chanQwQ/CVE-2020-1938.svg) 
2021-07-15T14:13:10Z

- [https://github.com/streghstreek/CVE-2020-1938](https://github.com/streghstreek/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/streghstreek/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/streghstreek/CVE-2020-1938.svg) 
2021-04-27T14:58:39Z

- [https://github.com/jptr218/ghostcat](https://github.com/jptr218/ghostcat) :  
![starts](https://img.shields.io/github/stars/jptr218/ghostcat.svg) 
![forks](https://img.shields.io/github/forks/jptr218/ghostcat.svg) 
2021-08-14T18:21:02Z

- [https://github.com/einzbernnn/CVE-2020-1938Scan](https://github.com/einzbernnn/CVE-2020-1938Scan) :  
![starts](https://img.shields.io/github/stars/einzbernnn/CVE-2020-1938Scan.svg) 
![forks](https://img.shields.io/github/forks/einzbernnn/CVE-2020-1938Scan.svg) 
2021-11-02T09:28:04Z

- [https://github.com/shaunmclernon/ghostcat-verification](https://github.com/shaunmclernon/ghostcat-verification) :  
![starts](https://img.shields.io/github/stars/shaunmclernon/ghostcat-verification.svg) 
![forks](https://img.shields.io/github/forks/shaunmclernon/ghostcat-verification.svg) 
2020-02-26T15:33:58Z

- [https://github.com/whatboxapp/GhostCat-LFI-exp](https://github.com/whatboxapp/GhostCat-LFI-exp) :  
![starts](https://img.shields.io/github/stars/whatboxapp/GhostCat-LFI-exp.svg) 
![forks](https://img.shields.io/github/forks/whatboxapp/GhostCat-LFI-exp.svg) 
2020-02-22T05:23:53Z

- [https://github.com/Umesh2807/Ghostcat](https://github.com/Umesh2807/Ghostcat) :  
![starts](https://img.shields.io/github/stars/Umesh2807/Ghostcat.svg) 
![forks](https://img.shields.io/github/forks/Umesh2807/Ghostcat.svg) 
2020-05-12T18:09:37Z

- [https://github.com/b1cat/CVE_2020_1938_ajp_poc](https://github.com/b1cat/CVE_2020_1938_ajp_poc) :  
![starts](https://img.shields.io/github/stars/b1cat/CVE_2020_1938_ajp_poc.svg) 
![forks](https://img.shields.io/github/forks/b1cat/CVE_2020_1938_ajp_poc.svg) 
2020-02-26T13:06:44Z

- [https://github.com/WHtig3r/CVE-2020-1938](https://github.com/WHtig3r/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/WHtig3r/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/WHtig3r/CVE-2020-1938.svg) 
2024-08-20T13:05:49Z

- [https://github.com/haerin7427/CVE_2020_1938](https://github.com/haerin7427/CVE_2020_1938) :  
![starts](https://img.shields.io/github/stars/haerin7427/CVE_2020_1938.svg) 
![forks](https://img.shields.io/github/forks/haerin7427/CVE_2020_1938.svg) 
2022-05-01T15:52:38Z

- [https://github.com/I-Runtime-Error/CVE-2020-1938](https://github.com/I-Runtime-Error/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/I-Runtime-Error/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/I-Runtime-Error/CVE-2020-1938.svg) 
2020-05-12T17:08:34Z

- [https://github.com/hopsypopsy8/CVE-2020-1938-Exploitation](https://github.com/hopsypopsy8/CVE-2020-1938-Exploitation) :  
![starts](https://img.shields.io/github/stars/hopsypopsy8/CVE-2020-1938-Exploitation.svg) 
![forks](https://img.shields.io/github/forks/hopsypopsy8/CVE-2020-1938-Exploitation.svg) 
2025-02-16T00:03:28Z

- [https://github.com/acodervic/CVE-2020-1938-MSF-MODULE](https://github.com/acodervic/CVE-2020-1938-MSF-MODULE) :  
![starts](https://img.shields.io/github/stars/acodervic/CVE-2020-1938-MSF-MODULE.svg) 
![forks](https://img.shields.io/github/forks/acodervic/CVE-2020-1938-MSF-MODULE.svg) 
2021-02-01T02:10:07Z

- [https://github.com/MateoSec/ghostcatch](https://github.com/MateoSec/ghostcatch) :  
![starts](https://img.shields.io/github/stars/MateoSec/ghostcatch.svg) 
![forks](https://img.shields.io/github/forks/MateoSec/ghostcatch.svg) 
2020-07-18T00:06:30Z

## CVE-2012-1823
 sapi/cgi/cgi_main.c in PHP before 5.3.12 and 5.4.x before 5.4.2, when configured as a CGI script (aka php-cgi), does not properly handle query strings that lack an = (equals sign) character, which allows remote attackers to execute arbitrary code by placing command-line options in the query string, related to lack of skipping a certain php_getopt for the 'd' case.

- [https://github.com/0xl0k1/CVE-2012-1823](https://github.com/0xl0k1/CVE-2012-1823) :  
![starts](https://img.shields.io/github/stars/0xl0k1/CVE-2012-1823.svg) 
![forks](https://img.shields.io/github/forks/0xl0k1/CVE-2012-1823.svg) 
2023-08-24T14:15:16Z

- [https://github.com/Unix13/metasploitable2](https://github.com/Unix13/metasploitable2) :  
![starts](https://img.shields.io/github/stars/Unix13/metasploitable2.svg) 
![forks](https://img.shields.io/github/forks/Unix13/metasploitable2.svg) 
2018-07-11T18:22:51Z

- [https://github.com/tardummy01/oscp_scripts-1](https://github.com/tardummy01/oscp_scripts-1) :  
![starts](https://img.shields.io/github/stars/tardummy01/oscp_scripts-1.svg) 
![forks](https://img.shields.io/github/forks/tardummy01/oscp_scripts-1.svg) 
2017-03-22T06:00:36Z

- [https://github.com/drone789/CVE-2012-1823](https://github.com/drone789/CVE-2012-1823) :  
![starts](https://img.shields.io/github/stars/drone789/CVE-2012-1823.svg) 
![forks](https://img.shields.io/github/forks/drone789/CVE-2012-1823.svg) 
2015-09-08T14:40:12Z

- [https://github.com/Jimmy01240397/CVE-2012-1823-Analyze](https://github.com/Jimmy01240397/CVE-2012-1823-Analyze) :  
![starts](https://img.shields.io/github/stars/Jimmy01240397/CVE-2012-1823-Analyze.svg) 
![forks](https://img.shields.io/github/forks/Jimmy01240397/CVE-2012-1823-Analyze.svg) 
2024-12-09T22:45:52Z

- [https://github.com/cyberharsh/PHP_CVE-2012-1823](https://github.com/cyberharsh/PHP_CVE-2012-1823) :  
![starts](https://img.shields.io/github/stars/cyberharsh/PHP_CVE-2012-1823.svg) 
![forks](https://img.shields.io/github/forks/cyberharsh/PHP_CVE-2012-1823.svg) 
2020-08-17T20:16:11Z

- [https://github.com/JasonHobs/CVE-2012-1823-exploit-for-https-user-password-web](https://github.com/JasonHobs/CVE-2012-1823-exploit-for-https-user-password-web) :  
![starts](https://img.shields.io/github/stars/JasonHobs/CVE-2012-1823-exploit-for-https-user-password-web.svg) 
![forks](https://img.shields.io/github/forks/JasonHobs/CVE-2012-1823-exploit-for-https-user-password-web.svg) 
2025-02-16T23:49:11Z

# 2025-02-15
## CVE-2025-25064
 SQL injection vulnerability in the ZimbraSync Service SOAP endpoint in Zimbra Collaboration 10.0.x before 10.0.12 and 10.1.x before 10.1.4 due to insufficient sanitization of a user-supplied parameter. Authenticated attackers can exploit this vulnerability by manipulating a specific parameter in the request, allowing them to inject arbitrary SQL queries that could retrieve email metadata.

- [https://github.com/yelang123/Zimbra10_SQL_Injection](https://github.com/yelang123/Zimbra10_SQL_Injection) :  
![starts](https://img.shields.io/github/stars/yelang123/Zimbra10_SQL_Injection.svg) 
![forks](https://img.shields.io/github/forks/yelang123/Zimbra10_SQL_Injection.svg) 
2025-02-15T04:20:58Z

## CVE-2025-22467
 A stack-based buffer overflow in Ivanti Connect Secure before version 22.7R2.6 allows a remote authenticated attacker to achieve remote code execution.

- [https://github.com/NyxanGoat/CVE-2025-22467-PoC](https://github.com/NyxanGoat/CVE-2025-22467-PoC) :  
![starts](https://img.shields.io/github/stars/NyxanGoat/CVE-2025-22467-PoC.svg) 
![forks](https://img.shields.io/github/forks/NyxanGoat/CVE-2025-22467-PoC.svg) 
2025-02-15T01:41:43Z

## CVE-2024-49113
 Windows Lightweight Directory Access Protocol (LDAP) Denial of Service Vulnerability

- [https://github.com/SafeBreach-Labs/CVE-2024-49113](https://github.com/SafeBreach-Labs/CVE-2024-49113) :  
![starts](https://img.shields.io/github/stars/SafeBreach-Labs/CVE-2024-49113.svg) 
![forks](https://img.shields.io/github/forks/SafeBreach-Labs/CVE-2024-49113.svg) 
2025-01-02T16:07:23Z

- [https://github.com/barcrange/CVE-2024-49113-Checker](https://github.com/barcrange/CVE-2024-49113-Checker) :  
![starts](https://img.shields.io/github/stars/barcrange/CVE-2024-49113-Checker.svg) 
![forks](https://img.shields.io/github/forks/barcrange/CVE-2024-49113-Checker.svg) 
2025-01-03T08:20:03Z

- [https://github.com/Sachinart/CVE-2024-49113-Checker](https://github.com/Sachinart/CVE-2024-49113-Checker) :  
![starts](https://img.shields.io/github/stars/Sachinart/CVE-2024-49113-Checker.svg) 
![forks](https://img.shields.io/github/forks/Sachinart/CVE-2024-49113-Checker.svg) 
2025-01-06T12:04:02Z

- [https://github.com/0xMetr0/metasploit-ldapnightmare](https://github.com/0xMetr0/metasploit-ldapnightmare) :  
![starts](https://img.shields.io/github/stars/0xMetr0/metasploit-ldapnightmare.svg) 
![forks](https://img.shields.io/github/forks/0xMetr0/metasploit-ldapnightmare.svg) 
2025-02-15T20:42:14Z

## CVE-2024-7985
 The FileOrganizer  Manage WordPress and Website Files plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the "fileorganizer_ajax_handler" function in all versions up to, and including, 1.0.9. This makes it possible for authenticated attackers, with Subscriber-level access and above, and permissions granted by an administrator, to upload arbitrary files on the affected site's server which may make remote code execution possible. NOTE: The FileOrganizer Pro plugin must be installed and active to allow Subscriber+ users to upload files.

- [https://github.com/Nxploited/CVE-2024-7985-PoC](https://github.com/Nxploited/CVE-2024-7985-PoC) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-7985-PoC.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-7985-PoC.svg) 
2025-02-15T23:08:12Z

# 2025-02-14
## CVE-2024-42010
 mod_css_styles in Roundcube through 1.5.7 and 1.6.x through 1.6.7 insufficiently filters Cascading Style Sheets (CSS) token sequences in rendered e-mail messages, allowing a remote attacker to obtain sensitive information.

- [https://github.com/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC](https://github.com/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC) :  
![starts](https://img.shields.io/github/stars/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC.svg) 
![forks](https://img.shields.io/github/forks/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC.svg) 
2025-02-14T10:36:33Z

## CVE-2024-42008
 A Cross-Site Scripting vulnerability in rcmail_action_mail_get-run() in Roundcube through 1.5.7 and 1.6.x through 1.6.7 allows a remote attacker to steal and send emails of a victim via a malicious e-mail attachment served with a dangerous Content-Type header.

- [https://github.com/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC](https://github.com/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC) :  
![starts](https://img.shields.io/github/stars/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC.svg) 
![forks](https://img.shields.io/github/forks/victoni/Roundcube-CVE-2024-42008-and-CVE-2024-42010-POC.svg) 
2025-02-14T10:36:33Z

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

- [https://github.com/punitdarji/GeoServer-CVE-2024-36401](https://github.com/punitdarji/GeoServer-CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/punitdarji/GeoServer-CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/punitdarji/GeoServer-CVE-2024-36401.svg) 
2024-09-28T14:58:44Z

- [https://github.com/RevoltSecurities/CVE-2024-36401](https://github.com/RevoltSecurities/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/RevoltSecurities/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/RevoltSecurities/CVE-2024-36401.svg) 
2024-07-05T15:33:09Z

- [https://github.com/wellwornele/CVE-2024-36401](https://github.com/wellwornele/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/wellwornele/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/wellwornele/CVE-2024-36401.svg) 
2025-02-09T17:11:54Z

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

- [https://github.com/dream434/CVE-2024-34102](https://github.com/dream434/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-34102.svg) 
2024-10-09T13:47:14Z

- [https://github.com/cmsec423/CVE-2024-34102](https://github.com/cmsec423/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/cmsec423/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/cmsec423/CVE-2024-34102.svg) 
2024-07-01T05:06:42Z

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

## CVE-2024-10914
 A vulnerability was found in D-Link DNS-320, DNS-320LW, DNS-325 and DNS-340L up to 20241028. It has been declared as critical. Affected by this vulnerability is the function cgi_user_add of the file /cgi-bin/account_mgr.cgi?cmd=cgi_user_add. The manipulation of the argument name leads to os command injection. The attack can be launched remotely. The complexity of an attack is rather high. The exploitation appears to be difficult. The exploit has been disclosed to the public and may be used.

- [https://github.com/verylazytech/CVE-2024-10914](https://github.com/verylazytech/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-10914.svg) 
2024-11-27T08:26:29Z

- [https://github.com/imnotcha0s/CVE-2024-10914](https://github.com/imnotcha0s/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/imnotcha0s/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/imnotcha0s/CVE-2024-10914.svg) 
2024-11-09T19:31:42Z

- [https://github.com/ThemeHackers/CVE-2024-10914](https://github.com/ThemeHackers/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/ThemeHackers/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/ThemeHackers/CVE-2024-10914.svg) 
2025-01-02T08:17:57Z

- [https://github.com/redspy-sec/D-Link](https://github.com/redspy-sec/D-Link) :  
![starts](https://img.shields.io/github/stars/redspy-sec/D-Link.svg) 
![forks](https://img.shields.io/github/forks/redspy-sec/D-Link.svg) 
2024-12-07T07:32:30Z

- [https://github.com/silverxpymaster/CVE-2024-10914-Exploit](https://github.com/silverxpymaster/CVE-2024-10914-Exploit) :  
![starts](https://img.shields.io/github/stars/silverxpymaster/CVE-2024-10914-Exploit.svg) 
![forks](https://img.shields.io/github/forks/silverxpymaster/CVE-2024-10914-Exploit.svg) 
2025-02-14T09:26:37Z

- [https://github.com/yenyangmjaze/cve-2024-10914](https://github.com/yenyangmjaze/cve-2024-10914) :  
![starts](https://img.shields.io/github/stars/yenyangmjaze/cve-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/yenyangmjaze/cve-2024-10914.svg) 
2025-02-14T14:16:27Z

- [https://github.com/Bu0uCat/D-Link-NAS-CVE-2024-10914-](https://github.com/Bu0uCat/D-Link-NAS-CVE-2024-10914-) :  
![starts](https://img.shields.io/github/stars/Bu0uCat/D-Link-NAS-CVE-2024-10914-.svg) 
![forks](https://img.shields.io/github/forks/Bu0uCat/D-Link-NAS-CVE-2024-10914-.svg) 
2024-11-15T07:59:36Z

- [https://github.com/Egi08/CVE-2024-10914](https://github.com/Egi08/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/Egi08/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/Egi08/CVE-2024-10914.svg) 
2024-11-13T09:39:25Z

- [https://github.com/dragonXZH/CVE-2024-10914](https://github.com/dragonXZH/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/dragonXZH/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/dragonXZH/CVE-2024-10914.svg) 
2024-12-24T10:42:20Z

- [https://github.com/retuci0/cve-2024-10914-port](https://github.com/retuci0/cve-2024-10914-port) :  
![starts](https://img.shields.io/github/stars/retuci0/cve-2024-10914-port.svg) 
![forks](https://img.shields.io/github/forks/retuci0/cve-2024-10914-port.svg) 
2024-11-27T19:12:45Z

- [https://github.com/jahithoque/CVE-2024-10914-Exploit](https://github.com/jahithoque/CVE-2024-10914-Exploit) :  
![starts](https://img.shields.io/github/stars/jahithoque/CVE-2024-10914-Exploit.svg) 
![forks](https://img.shields.io/github/forks/jahithoque/CVE-2024-10914-Exploit.svg) 
2024-12-04T05:31:23Z

- [https://github.com/K3ysTr0K3R/CVE-2024-10914-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-10914-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-10914-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-10914-EXPLOIT.svg) 
2024-11-27T23:31:07Z

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

- [https://github.com/codeb0ss/CVEploiterv2](https://github.com/codeb0ss/CVEploiterv2) :  
![starts](https://img.shields.io/github/stars/codeb0ss/CVEploiterv2.svg) 
![forks](https://img.shields.io/github/forks/codeb0ss/CVEploiterv2.svg) 
2024-07-25T14:16:55Z

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

- [https://github.com/Sh0ckFR/CVE-2024-4577](https://github.com/Sh0ckFR/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Sh0ckFR/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Sh0ckFR/CVE-2024-4577.svg) 
2024-06-13T15:17:15Z

- [https://github.com/longhoangth18/CVE-2024-4577](https://github.com/longhoangth18/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/longhoangth18/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/longhoangth18/CVE-2024-4577.svg) 
2024-10-14T09:36:45Z

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

- [https://github.com/JeninSutradhar/CVE-2024-4577-checker](https://github.com/JeninSutradhar/CVE-2024-4577-checker) :  
![starts](https://img.shields.io/github/stars/JeninSutradhar/CVE-2024-4577-checker.svg) 
![forks](https://img.shields.io/github/forks/JeninSutradhar/CVE-2024-4577-checker.svg) 
2024-11-13T14:37:33Z

- [https://github.com/ggfzx/CVE-2024-4577](https://github.com/ggfzx/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ggfzx/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ggfzx/CVE-2024-4577.svg) 
2024-06-26T07:11:46Z

- [https://github.com/taida957789/CVE-2024-4577](https://github.com/taida957789/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/taida957789/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/taida957789/CVE-2024-4577.svg) 
2024-06-07T11:05:57Z

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

- [https://github.com/charis3306/CVE-2024-4577](https://github.com/charis3306/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/charis3306/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/charis3306/CVE-2024-4577.svg) 
2024-07-03T15:41:42Z

- [https://github.com/bughuntar/CVE-2024-4577](https://github.com/bughuntar/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bughuntar/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bughuntar/CVE-2024-4577.svg) 
2024-08-17T02:02:26Z

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

- [https://github.com/princew88/CVE-2024-4577](https://github.com/princew88/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/princew88/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/princew88/CVE-2024-4577.svg) 
2024-06-07T09:48:36Z

- [https://github.com/bl4cksku11/CVE-2024-4577](https://github.com/bl4cksku11/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bl4cksku11/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bl4cksku11/CVE-2024-4577.svg) 
2024-06-11T15:29:21Z

- [https://github.com/a-roshbaik/CVE-2024-4577](https://github.com/a-roshbaik/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/a-roshbaik/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/a-roshbaik/CVE-2024-4577.svg) 
2024-07-24T20:23:03Z

- [https://github.com/Jcccccx/CVE-2024-4577](https://github.com/Jcccccx/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Jcccccx/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Jcccccx/CVE-2024-4577.svg) 
2024-07-31T10:37:56Z

- [https://github.com/dbyMelina/CVE-2024-4577](https://github.com/dbyMelina/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/dbyMelina/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/dbyMelina/CVE-2024-4577.svg) 
2024-06-09T13:47:59Z

- [https://github.com/sug4r-wr41th/CVE-2024-4577](https://github.com/sug4r-wr41th/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/sug4r-wr41th/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/sug4r-wr41th/CVE-2024-4577.svg) 
2024-06-15T18:12:19Z

- [https://github.com/BitMEXResearch/CVE-2024-4577](https://github.com/BitMEXResearch/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/BitMEXResearch/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/BitMEXResearch/CVE-2024-4577.svg) 
2024-06-07T20:35:06Z

- [https://github.com/ahmetramazank/CVE-2024-4577](https://github.com/ahmetramazank/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ahmetramazank/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ahmetramazank/CVE-2024-4577.svg) 
2024-11-03T16:17:49Z

- [https://github.com/Didarul342/CVE-2024-4577](https://github.com/Didarul342/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Didarul342/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Didarul342/CVE-2024-4577.svg) 
2025-02-14T19:44:03Z

- [https://github.com/hexedbyte/cve-2024-4577](https://github.com/hexedbyte/cve-2024-4577) :  
![starts](https://img.shields.io/github/stars/hexedbyte/cve-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/hexedbyte/cve-2024-4577.svg) 
2024-06-13T12:43:03Z

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

## CVE-2023-36845
 A PHP External Variable Modification vulnerability in J-Web of Juniper Networks Junos OS on EX Series and SRX Series allows an unauthenticated, network-based attacker to remotely execute code.Using a crafted request which sets the variable PHPRC an attacker is able to modify the PHP execution environment allowing the injection und execution of code.This issue affects Juniper Networks Junos OS on EX Seriesand SRX Series:  *  All versions prior to 20.4R3-S9;  *  21.1 versions 21.1R1 and later;  *  21.2 versions prior to21.2R3-S7;  *  21.3 versions prior to21.3R3-S5;  *  21.4 versions prior to 21.4R3-S5;  *  22.1 versions prior to 22.1R3-S4;  *  22.2 versions prior to 22.2R3-S2;  *  22.3 versions prior to 22.3R2-S2, 22.3R3-S1;  *  22.4 versions prior to 22.4R2-S1, 22.4R3;  *  23.2 versions prior to 23.2R1-S1, 23.2R2.

- [https://github.com/vulncheck-oss/cve-2023-36845-scanner](https://github.com/vulncheck-oss/cve-2023-36845-scanner) :  
![starts](https://img.shields.io/github/stars/vulncheck-oss/cve-2023-36845-scanner.svg) 
![forks](https://img.shields.io/github/forks/vulncheck-oss/cve-2023-36845-scanner.svg) 
2025-02-14T18:37:30Z

- [https://github.com/kljunowsky/CVE-2023-36845](https://github.com/kljunowsky/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/kljunowsky/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/kljunowsky/CVE-2023-36845.svg) 
2023-12-29T14:56:44Z

- [https://github.com/hackingyseguridad/nmap](https://github.com/hackingyseguridad/nmap) :  
![starts](https://img.shields.io/github/stars/hackingyseguridad/nmap.svg) 
![forks](https://img.shields.io/github/forks/hackingyseguridad/nmap.svg) 
2024-04-17T11:38:44Z

- [https://github.com/Asbawy/Automation-for-Juniper-cve-2023-36845](https://github.com/Asbawy/Automation-for-Juniper-cve-2023-36845) :  
![starts](https://img.shields.io/github/stars/Asbawy/Automation-for-Juniper-cve-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/Asbawy/Automation-for-Juniper-cve-2023-36845.svg) 
2024-01-30T19:27:34Z

- [https://github.com/ak1t4/CVE-2023-36845](https://github.com/ak1t4/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/ak1t4/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/ak1t4/CVE-2023-36845.svg) 
2024-02-13T21:47:25Z

- [https://github.com/zaenhaxor/CVE-2023-36845](https://github.com/zaenhaxor/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/zaenhaxor/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/zaenhaxor/CVE-2023-36845.svg) 
2023-10-07T03:25:04Z

- [https://github.com/r3dcl1ff/CVE-2023-36844_Juniper_RCE](https://github.com/r3dcl1ff/CVE-2023-36844_Juniper_RCE) :  
![starts](https://img.shields.io/github/stars/r3dcl1ff/CVE-2023-36844_Juniper_RCE.svg) 
![forks](https://img.shields.io/github/forks/r3dcl1ff/CVE-2023-36844_Juniper_RCE.svg) 
2023-09-24T13:36:08Z

- [https://github.com/cyberh3als/CVE-2023-36845-POC](https://github.com/cyberh3als/CVE-2023-36845-POC) :  
![starts](https://img.shields.io/github/stars/cyberh3als/CVE-2023-36845-POC.svg) 
![forks](https://img.shields.io/github/forks/cyberh3als/CVE-2023-36845-POC.svg) 
2023-10-02T10:31:32Z

- [https://github.com/halencarjunior/CVE-2023-36845](https://github.com/halencarjunior/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/halencarjunior/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/halencarjunior/CVE-2023-36845.svg) 
2023-09-27T23:57:12Z

- [https://github.com/e11i0t4lders0n/CVE-2023-36845](https://github.com/e11i0t4lders0n/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/e11i0t4lders0n/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/e11i0t4lders0n/CVE-2023-36845.svg) 
2024-02-18T18:44:03Z

- [https://github.com/simrotion13/CVE-2023-36845](https://github.com/simrotion13/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/simrotion13/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/simrotion13/CVE-2023-36845.svg) 
2023-10-01T03:43:07Z

- [https://github.com/jahithoque/Juniper-CVE-2023-36845-Mass-Hunting](https://github.com/jahithoque/Juniper-CVE-2023-36845-Mass-Hunting) :  
![starts](https://img.shields.io/github/stars/jahithoque/Juniper-CVE-2023-36845-Mass-Hunting.svg) 
![forks](https://img.shields.io/github/forks/jahithoque/Juniper-CVE-2023-36845-Mass-Hunting.svg) 
2024-01-30T08:23:13Z

- [https://github.com/ifconfig-me/CVE-2023-36845](https://github.com/ifconfig-me/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/ifconfig-me/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/ifconfig-me/CVE-2023-36845.svg) 
2024-04-09T20:44:10Z

- [https://github.com/toanln-cov/CVE-2023-36845](https://github.com/toanln-cov/CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/toanln-cov/CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/toanln-cov/CVE-2023-36845.svg) 
2023-09-27T09:59:28Z

- [https://github.com/3yujw7njai/ansible-cve-2023-36845](https://github.com/3yujw7njai/ansible-cve-2023-36845) :  
![starts](https://img.shields.io/github/stars/3yujw7njai/ansible-cve-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/3yujw7njai/ansible-cve-2023-36845.svg) 
2023-11-14T16:59:57Z

- [https://github.com/iveresk/CVE-2023-36845-6-](https://github.com/iveresk/CVE-2023-36845-6-) :  
![starts](https://img.shields.io/github/stars/iveresk/CVE-2023-36845-6-.svg) 
![forks](https://img.shields.io/github/forks/iveresk/CVE-2023-36845-6-.svg) 
2024-02-13T15:11:21Z

- [https://github.com/0xNehru/CVE-2023-36845-Juniper-Vulnerability](https://github.com/0xNehru/CVE-2023-36845-Juniper-Vulnerability) :  
![starts](https://img.shields.io/github/stars/0xNehru/CVE-2023-36845-Juniper-Vulnerability.svg) 
![forks](https://img.shields.io/github/forks/0xNehru/CVE-2023-36845-Juniper-Vulnerability.svg) 
2024-02-14T14:07:11Z

- [https://github.com/cyb3rzest/Juniper-Bug-Automation-CVE-2023-36845](https://github.com/cyb3rzest/Juniper-Bug-Automation-CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/cyb3rzest/Juniper-Bug-Automation-CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/cyb3rzest/Juniper-Bug-Automation-CVE-2023-36845.svg) 
2024-02-01T04:12:50Z

- [https://github.com/Vignesh2712/Automation-for-Juniper-cve-2023-36845](https://github.com/Vignesh2712/Automation-for-Juniper-cve-2023-36845) :  
![starts](https://img.shields.io/github/stars/Vignesh2712/Automation-for-Juniper-cve-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/Vignesh2712/Automation-for-Juniper-cve-2023-36845.svg) 
2024-05-04T14:51:45Z

- [https://github.com/CharonDefalt/Juniper-exploit-CVE-2023-36845](https://github.com/CharonDefalt/Juniper-exploit-CVE-2023-36845) :  
![starts](https://img.shields.io/github/stars/CharonDefalt/Juniper-exploit-CVE-2023-36845.svg) 
![forks](https://img.shields.io/github/forks/CharonDefalt/Juniper-exploit-CVE-2023-36845.svg) 
2024-02-03T06:10:32Z

## CVE-2020-10136
 IP-in-IP protocol specifies IP Encapsulation within IP standard (RFC 2003, STD 1) that decapsulate and route IP-in-IP traffic is vulnerable to spoofing, access-control bypass and other unexpected behavior due to the lack of validation to verify network packets before decapsulation and routing.

- [https://github.com/PapayaJackal/ipeeyoupeewepee](https://github.com/PapayaJackal/ipeeyoupeewepee) :  
![starts](https://img.shields.io/github/stars/PapayaJackal/ipeeyoupeewepee.svg) 
![forks](https://img.shields.io/github/forks/PapayaJackal/ipeeyoupeewepee.svg) 
2025-01-22T13:20:58Z

- [https://github.com/GustavoHGP/ipeeyoupeewepee](https://github.com/GustavoHGP/ipeeyoupeewepee) :  
![starts](https://img.shields.io/github/stars/GustavoHGP/ipeeyoupeewepee.svg) 
![forks](https://img.shields.io/github/forks/GustavoHGP/ipeeyoupeewepee.svg) 
2025-02-14T04:49:31Z

## CVE-2019-9053
 An issue was discovered in CMS Made Simple 2.2.8. It is possible with the News module, through a crafted URL, to achieve unauthenticated blind time-based SQL injection via the m1_idlist parameter.

- [https://github.com/e-renna/CVE-2019-9053](https://github.com/e-renna/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/e-renna/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/e-renna/CVE-2019-9053.svg) 
2023-05-09T17:00:31Z

- [https://github.com/Mahamedm/CVE-2019-9053-Exploit-Python-3](https://github.com/Mahamedm/CVE-2019-9053-Exploit-Python-3) :  
![starts](https://img.shields.io/github/stars/Mahamedm/CVE-2019-9053-Exploit-Python-3.svg) 
![forks](https://img.shields.io/github/forks/Mahamedm/CVE-2019-9053-Exploit-Python-3.svg) 
2025-02-10T13:43:12Z

- [https://github.com/n3rdh4x0r/CVE-2019-9053](https://github.com/n3rdh4x0r/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/n3rdh4x0r/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/n3rdh4x0r/CVE-2019-9053.svg) 
2024-11-18T18:53:00Z

- [https://github.com/ELIZEUOPAIN/CVE-2019-9053-CMS-Made-Simple-2.2.10---SQL-Injection-Exploit](https://github.com/ELIZEUOPAIN/CVE-2019-9053-CMS-Made-Simple-2.2.10---SQL-Injection-Exploit) :  
![starts](https://img.shields.io/github/stars/ELIZEUOPAIN/CVE-2019-9053-CMS-Made-Simple-2.2.10---SQL-Injection-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ELIZEUOPAIN/CVE-2019-9053-CMS-Made-Simple-2.2.10---SQL-Injection-Exploit.svg) 
2023-06-30T13:21:24Z

- [https://github.com/SUNNYSAINI01001/46635.py_CVE-2019-9053](https://github.com/SUNNYSAINI01001/46635.py_CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/SUNNYSAINI01001/46635.py_CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/SUNNYSAINI01001/46635.py_CVE-2019-9053.svg) 
2021-05-14T04:03:50Z

- [https://github.com/davcwikla/CVE-2019-9053-exploit](https://github.com/davcwikla/CVE-2019-9053-exploit) :  
![starts](https://img.shields.io/github/stars/davcwikla/CVE-2019-9053-exploit.svg) 
![forks](https://img.shields.io/github/forks/davcwikla/CVE-2019-9053-exploit.svg) 
2023-11-26T20:48:59Z

- [https://github.com/AppyAppy/super-octo-carnival](https://github.com/AppyAppy/super-octo-carnival) :  
![starts](https://img.shields.io/github/stars/AppyAppy/super-octo-carnival.svg) 
![forks](https://img.shields.io/github/forks/AppyAppy/super-octo-carnival.svg) 
2023-05-23T18:51:06Z

- [https://github.com/kahluri/CVE-2019-9053](https://github.com/kahluri/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/kahluri/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/kahluri/CVE-2019-9053.svg) 
2023-08-07T20:34:58Z

- [https://github.com/fernandobortotti/CVE-2019-9053](https://github.com/fernandobortotti/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/fernandobortotti/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/fernandobortotti/CVE-2019-9053.svg) 
2023-10-16T22:51:16Z

- [https://github.com/byrek/CVE-2019-9053](https://github.com/byrek/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/byrek/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/byrek/CVE-2019-9053.svg) 
2023-11-20T12:40:54Z

- [https://github.com/im-suman-roy/CVE-2019-9053](https://github.com/im-suman-roy/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/im-suman-roy/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/im-suman-roy/CVE-2019-9053.svg) 
2023-07-04T11:48:19Z

- [https://github.com/louisthedonothing/CVE-2019-9053](https://github.com/louisthedonothing/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/louisthedonothing/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/louisthedonothing/CVE-2019-9053.svg) 
2024-12-02T13:14:19Z

- [https://github.com/pedrojosenavasperez/CVE-2019-9053-Python3](https://github.com/pedrojosenavasperez/CVE-2019-9053-Python3) :  
![starts](https://img.shields.io/github/stars/pedrojosenavasperez/CVE-2019-9053-Python3.svg) 
![forks](https://img.shields.io/github/forks/pedrojosenavasperez/CVE-2019-9053-Python3.svg) 
2022-12-14T13:05:03Z

- [https://github.com/BjarneVerschorre/CVE-2019-9053](https://github.com/BjarneVerschorre/CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/BjarneVerschorre/CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/BjarneVerschorre/CVE-2019-9053.svg) 
2023-11-30T15:54:34Z

- [https://github.com/FedericoTorres233/CVE-2019-9053-Fixed](https://github.com/FedericoTorres233/CVE-2019-9053-Fixed) :  
![starts](https://img.shields.io/github/stars/FedericoTorres233/CVE-2019-9053-Fixed.svg) 
![forks](https://img.shields.io/github/forks/FedericoTorres233/CVE-2019-9053-Fixed.svg) 
2024-05-17T01:03:40Z

- [https://github.com/zmiddle/Simple_CMS_SQLi](https://github.com/zmiddle/Simple_CMS_SQLi) :  
![starts](https://img.shields.io/github/stars/zmiddle/Simple_CMS_SQLi.svg) 
![forks](https://img.shields.io/github/forks/zmiddle/Simple_CMS_SQLi.svg) 
2022-10-22T21:23:42Z

- [https://github.com/jtoalu/CTF-CVE-2019-9053-GTFOBins](https://github.com/jtoalu/CTF-CVE-2019-9053-GTFOBins) :  
![starts](https://img.shields.io/github/stars/jtoalu/CTF-CVE-2019-9053-GTFOBins.svg) 
![forks](https://img.shields.io/github/forks/jtoalu/CTF-CVE-2019-9053-GTFOBins.svg) 
2024-08-09T21:02:48Z

- [https://github.com/bthnrml/guncel-cve-2019-9053.py](https://github.com/bthnrml/guncel-cve-2019-9053.py) :  
![starts](https://img.shields.io/github/stars/bthnrml/guncel-cve-2019-9053.py.svg) 
![forks](https://img.shields.io/github/forks/bthnrml/guncel-cve-2019-9053.py.svg) 
2023-07-09T08:50:38Z

- [https://github.com/Doc0x1/CVE-2019-9053-Python3](https://github.com/Doc0x1/CVE-2019-9053-Python3) :  
![starts](https://img.shields.io/github/stars/Doc0x1/CVE-2019-9053-Python3.svg) 
![forks](https://img.shields.io/github/forks/Doc0x1/CVE-2019-9053-Python3.svg) 
2023-10-16T01:30:34Z

- [https://github.com/TeymurNovruzov/CVE-2019-9053-python3-remastered](https://github.com/TeymurNovruzov/CVE-2019-9053-python3-remastered) :  
![starts](https://img.shields.io/github/stars/TeymurNovruzov/CVE-2019-9053-python3-remastered.svg) 
![forks](https://img.shields.io/github/forks/TeymurNovruzov/CVE-2019-9053-python3-remastered.svg) 
2024-06-25T10:53:22Z

- [https://github.com/Jason-Siu/CVE-2019-9053-Exploit-in-Python-3](https://github.com/Jason-Siu/CVE-2019-9053-Exploit-in-Python-3) :  
![starts](https://img.shields.io/github/stars/Jason-Siu/CVE-2019-9053-Exploit-in-Python-3.svg) 
![forks](https://img.shields.io/github/forks/Jason-Siu/CVE-2019-9053-Exploit-in-Python-3.svg) 
2024-02-21T18:56:35Z

- [https://github.com/Yzhacker/CVE-2019-9053-CMS46635-python3](https://github.com/Yzhacker/CVE-2019-9053-CMS46635-python3) :  
![starts](https://img.shields.io/github/stars/Yzhacker/CVE-2019-9053-CMS46635-python3.svg) 
![forks](https://img.shields.io/github/forks/Yzhacker/CVE-2019-9053-CMS46635-python3.svg) 
2025-02-14T01:33:48Z

- [https://github.com/maraspiras/46635.py](https://github.com/maraspiras/46635.py) :  
![starts](https://img.shields.io/github/stars/maraspiras/46635.py.svg) 
![forks](https://img.shields.io/github/forks/maraspiras/46635.py.svg) 
2021-12-09T17:49:43Z

- [https://github.com/Azrenom/CMS-Made-Simple-2.2.9-CVE-2019-9053](https://github.com/Azrenom/CMS-Made-Simple-2.2.9-CVE-2019-9053) :  
![starts](https://img.shields.io/github/stars/Azrenom/CMS-Made-Simple-2.2.9-CVE-2019-9053.svg) 
![forks](https://img.shields.io/github/forks/Azrenom/CMS-Made-Simple-2.2.9-CVE-2019-9053.svg) 
2024-09-21T13:15:50Z

- [https://github.com/Matthsh/SQLi-correction](https://github.com/Matthsh/SQLi-correction) :  
![starts](https://img.shields.io/github/stars/Matthsh/SQLi-correction.svg) 
![forks](https://img.shields.io/github/forks/Matthsh/SQLi-correction.svg) 
2022-03-30T15:44:49Z

- [https://github.com/Dh4nuJ4/SimpleCTF-UpdatedExploit](https://github.com/Dh4nuJ4/SimpleCTF-UpdatedExploit) :  
![starts](https://img.shields.io/github/stars/Dh4nuJ4/SimpleCTF-UpdatedExploit.svg) 
![forks](https://img.shields.io/github/forks/Dh4nuJ4/SimpleCTF-UpdatedExploit.svg) 
2024-06-20T22:02:24Z

# 2025-02-13
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

- [https://github.com/chiefchainer/CVE-2025-0282](https://github.com/chiefchainer/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/chiefchainer/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/chiefchainer/CVE-2025-0282.svg) 
2025-01-22T08:25:22Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

## CVE-2024-57778
 An issue in Orbe ONetView Roeador Onet-1200 Orbe 1680210096 allows a remote attacker to escalate privileges via the servers response from status code 500 to status code 200.

- [https://github.com/KUK3N4N/CVE-2024-57778](https://github.com/KUK3N4N/CVE-2024-57778) :  
![starts](https://img.shields.io/github/stars/KUK3N4N/CVE-2024-57778.svg) 
![forks](https://img.shields.io/github/forks/KUK3N4N/CVE-2024-57778.svg) 
2025-02-13T19:35:21Z

## CVE-2024-57725
 An issue in the Arcadyan Livebox Fibra PRV3399B_B_LT allows a remote or local attacker to modify the GPON link value without authentication, causing an internet service disruption via the /firstconnection.cgi endpoint.

- [https://github.com/pointedsec/CVE-2024-57725](https://github.com/pointedsec/CVE-2024-57725) :  
![starts](https://img.shields.io/github/stars/pointedsec/CVE-2024-57725.svg) 
![forks](https://img.shields.io/github/forks/pointedsec/CVE-2024-57725.svg) 
2025-02-13T22:27:16Z

## CVE-2024-54160
 dashboards-reporting (aka Dashboards Reports) before 2.19.0.0, as shipped in OpenSearch before 2.19, allows XSS because Markdown is not sanitized when previewing a header or footer.

- [https://github.com/Jflye/CVE-2024-54160-Opensearch-HTML-And-Injection-Stored-XSS](https://github.com/Jflye/CVE-2024-54160-Opensearch-HTML-And-Injection-Stored-XSS) :  
![starts](https://img.shields.io/github/stars/Jflye/CVE-2024-54160-Opensearch-HTML-And-Injection-Stored-XSS.svg) 
![forks](https://img.shields.io/github/forks/Jflye/CVE-2024-54160-Opensearch-HTML-And-Injection-Stored-XSS.svg) 
2025-02-13T13:08:25Z

## CVE-2024-42009
 A Cross-Site Scripting vulnerability in Roundcube through 1.5.7 and 1.6.x through 1.6.7 allows a remote attacker to steal and send emails of a victim via a crafted e-mail message that abuses a Desanitization issue in message_body() in program/actions/mail/show.php.

- [https://github.com/0xbassiouny1337/CVE-2024-42009](https://github.com/0xbassiouny1337/CVE-2024-42009) :  
![starts](https://img.shields.io/github/stars/0xbassiouny1337/CVE-2024-42009.svg) 
![forks](https://img.shields.io/github/forks/0xbassiouny1337/CVE-2024-42009.svg) 
2025-02-12T00:50:17Z

- [https://github.com/Bhanunamikaze/CVE-2024-42009](https://github.com/Bhanunamikaze/CVE-2024-42009) :  
![starts](https://img.shields.io/github/stars/Bhanunamikaze/CVE-2024-42009.svg) 
![forks](https://img.shields.io/github/forks/Bhanunamikaze/CVE-2024-42009.svg) 
2025-02-13T21:16:01Z

## CVE-2024-30896
 InfluxDB OSS 2.x through 2.7.11 stores the administrative operator token under the default organization which allows authorized users with read access to the authorization resource of the default organization to retrieve the operator token. InfluxDB OSS 1.x, Enterprise, Cloud, Cloud Dedicated and Clustered are not affected. NOTE: The researcher states that InfluxDB allows allAccess administrators to retrieve all raw tokens via an "influx auth ls" command. The supplier indicates that the organizations feature is operating as intended and that users may choose to add users to non-default organizations. A future release of InfluxDB 2.x will remove the ability to retrieve tokens from the API.

- [https://github.com/XenoM0rph97/CVE-2024-30896](https://github.com/XenoM0rph97/CVE-2024-30896) :  
![starts](https://img.shields.io/github/stars/XenoM0rph97/CVE-2024-30896.svg) 
![forks](https://img.shields.io/github/forks/XenoM0rph97/CVE-2024-30896.svg) 
2025-02-13T17:29:35Z

## CVE-2024-23692
 Rejetto HTTP File Server, up to and including version 2.3m, is vulnerable to a template injection vulnerability. This vulnerability allows a remote, unauthenticated attacker to execute arbitrary commands on the affected system by sending a specially crafted HTTP request. As of the CVE assignment date, Rejetto HFS 2.3m is no longer supported.

- [https://github.com/verylazytech/CVE-2024-23692](https://github.com/verylazytech/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-23692.svg) 
2025-02-13T15:29:48Z

- [https://github.com/0x20c/CVE-2024-23692-EXP](https://github.com/0x20c/CVE-2024-23692-EXP) :  
![starts](https://img.shields.io/github/stars/0x20c/CVE-2024-23692-EXP.svg) 
![forks](https://img.shields.io/github/forks/0x20c/CVE-2024-23692-EXP.svg) 
2024-06-18T04:06:25Z

- [https://github.com/jakabakos/CVE-2024-23692-RCE-in-Rejetto-HFS](https://github.com/jakabakos/CVE-2024-23692-RCE-in-Rejetto-HFS) :  
![starts](https://img.shields.io/github/stars/jakabakos/CVE-2024-23692-RCE-in-Rejetto-HFS.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/CVE-2024-23692-RCE-in-Rejetto-HFS.svg) 
2024-06-13T07:00:23Z

- [https://github.com/vanboomqi/CVE-2024-23692](https://github.com/vanboomqi/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/vanboomqi/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/vanboomqi/CVE-2024-23692.svg) 
2024-06-15T15:30:45Z

- [https://github.com/BBD-YZZ/CVE-2024-23692](https://github.com/BBD-YZZ/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/BBD-YZZ/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/BBD-YZZ/CVE-2024-23692.svg) 
2024-06-18T01:23:58Z

- [https://github.com/XiaomingX/cve-2024-23692-poc](https://github.com/XiaomingX/cve-2024-23692-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-23692-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-23692-poc.svg) 
2024-11-23T04:00:55Z

- [https://github.com/k3lpi3b4nsh33/CVE-2024-23692](https://github.com/k3lpi3b4nsh33/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/k3lpi3b4nsh33/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/k3lpi3b4nsh33/CVE-2024-23692.svg) 
2024-06-11T08:05:50Z

- [https://github.com/pradeepboo/Rejetto-HFS-2.x-RCE-CVE-2024-23692](https://github.com/pradeepboo/Rejetto-HFS-2.x-RCE-CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/pradeepboo/Rejetto-HFS-2.x-RCE-CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/pradeepboo/Rejetto-HFS-2.x-RCE-CVE-2024-23692.svg) 
2024-07-10T04:55:58Z

- [https://github.com/NingXin2002/HFS2.3_poc](https://github.com/NingXin2002/HFS2.3_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/HFS2.3_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/HFS2.3_poc.svg) 
2024-12-21T07:14:26Z

- [https://github.com/Tupler/CVE-2024-23692-exp](https://github.com/Tupler/CVE-2024-23692-exp) :  
![starts](https://img.shields.io/github/stars/Tupler/CVE-2024-23692-exp.svg) 
![forks](https://img.shields.io/github/forks/Tupler/CVE-2024-23692-exp.svg) 
2024-06-16T07:05:14Z

- [https://github.com/Mr-r00t11/CVE-2024-23692](https://github.com/Mr-r00t11/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/Mr-r00t11/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/Mr-r00t11/CVE-2024-23692.svg) 
2024-06-14T01:47:45Z

- [https://github.com/WanLiChangChengWanLiChang/CVE-2024-23692-RCE](https://github.com/WanLiChangChengWanLiChang/CVE-2024-23692-RCE) :  
![starts](https://img.shields.io/github/stars/WanLiChangChengWanLiChang/CVE-2024-23692-RCE.svg) 
![forks](https://img.shields.io/github/forks/WanLiChangChengWanLiChang/CVE-2024-23692-RCE.svg) 
2024-06-13T14:43:54Z

## CVE-2024-21887
 A command injection vulnerability in web components of Ivanti Connect Secure (9.x, 22.x) and Ivanti Policy Secure (9.x, 22.x)  allows an authenticated administrator to send specially crafted requests and execute arbitrary commands on the appliance.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2024-11-20T12:44:28Z

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

- [https://github.com/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped](https://github.com/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped) :  
![starts](https://img.shields.io/github/stars/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped.svg) 
![forks](https://img.shields.io/github/forks/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped.svg) 
2024-05-21T12:56:25Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

## CVE-2024-1093
 The Change Memory Limit plugin for WordPress is vulnerable to unauthorized modification of data due to a missing capability check on the admin_logic() function hooked via admin_init in all versions up to, and including, 1.0. This makes it possible for unauthenticated attackers to update the memory limit.

- [https://github.com/sahil3276/CVE-2024-10930](https://github.com/sahil3276/CVE-2024-10930) :  
![starts](https://img.shields.io/github/stars/sahil3276/CVE-2024-10930.svg) 
![forks](https://img.shields.io/github/forks/sahil3276/CVE-2024-10930.svg) 
2025-02-13T06:27:57Z

## CVE-2023-46805
 An authentication bypass vulnerability in the web component of Ivanti ICS 9.x, 22.x and Ivanti Policy Secure allows a remote attacker to access restricted resources by bypassing control checks.

- [https://github.com/duy-31/CVE-2023-46805_CVE-2024-21887](https://github.com/duy-31/CVE-2023-46805_CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/duy-31/CVE-2023-46805_CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/duy-31/CVE-2023-46805_CVE-2024-21887.svg) 
2024-01-17T19:14:09Z

- [https://github.com/Chocapikk/CVE-2023-46805](https://github.com/Chocapikk/CVE-2023-46805) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2023-46805.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2023-46805.svg) 
2024-01-19T03:17:13Z

- [https://github.com/seajaysec/Ivanti-Connect-Around-Scan](https://github.com/seajaysec/Ivanti-Connect-Around-Scan) :  
![starts](https://img.shields.io/github/stars/seajaysec/Ivanti-Connect-Around-Scan.svg) 
![forks](https://img.shields.io/github/forks/seajaysec/Ivanti-Connect-Around-Scan.svg) 
2024-02-03T01:59:49Z

- [https://github.com/yoryio/CVE-2023-46805](https://github.com/yoryio/CVE-2023-46805) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2023-46805.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2023-46805.svg) 
2024-07-23T16:01:11Z

- [https://github.com/cbeek-r7/CVE-2023-46805](https://github.com/cbeek-r7/CVE-2023-46805) :  
![starts](https://img.shields.io/github/stars/cbeek-r7/CVE-2023-46805.svg) 
![forks](https://img.shields.io/github/forks/cbeek-r7/CVE-2023-46805.svg) 
2024-01-19T09:02:40Z

- [https://github.com/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887](https://github.com/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887) :  
![starts](https://img.shields.io/github/stars/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887.svg) 
![forks](https://img.shields.io/github/forks/raminkarimkhani1996/CVE-2023-46805_CVE-2024-21887.svg) 
2024-03-23T14:52:22Z

- [https://github.com/w2xim3/CVE-2023-46805](https://github.com/w2xim3/CVE-2023-46805) :  
![starts](https://img.shields.io/github/stars/w2xim3/CVE-2023-46805.svg) 
![forks](https://img.shields.io/github/forks/w2xim3/CVE-2023-46805.svg) 
2024-01-25T18:04:15Z

- [https://github.com/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped](https://github.com/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped) :  
![starts](https://img.shields.io/github/stars/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped.svg) 
![forks](https://img.shields.io/github/forks/mickdec/CVE-2023-46805_CVE-2024-21887_scan_grouped.svg) 
2024-05-21T12:56:25Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

## CVE-2023-38873
 The commit 3730880 (April 2023) and v.0.9-beta1 of gugoan Economizzer is vulnerable to Clickjacking. Clickjacking, also known as a "UI redress attack", is when an attacker uses multiple transparent or opaque layers to trick a user into clicking on a button or link on another page when they were intending to click on the top-level page. Thus, the attacker is "hijacking" clicks meant for their page and routing them to another page, most likely owned by another application, domain, or both.

- [https://github.com/K9-Modz/CVE-2023-38873-G1](https://github.com/K9-Modz/CVE-2023-38873-G1) :  
![starts](https://img.shields.io/github/stars/K9-Modz/CVE-2023-38873-G1.svg) 
![forks](https://img.shields.io/github/forks/K9-Modz/CVE-2023-38873-G1.svg) 
2025-02-13T02:24:30Z

## CVE-2023-35078
 An authentication bypass vulnerability in Ivanti EPMM allows unauthorized users to access restricted functionality or resources of the application without proper authentication.

- [https://github.com/vchan-in/CVE-2023-35078-Exploit-POC](https://github.com/vchan-in/CVE-2023-35078-Exploit-POC) :  
![starts](https://img.shields.io/github/stars/vchan-in/CVE-2023-35078-Exploit-POC.svg) 
![forks](https://img.shields.io/github/forks/vchan-in/CVE-2023-35078-Exploit-POC.svg) 
2023-07-29T16:58:16Z

- [https://github.com/lager1/CVE-2023-35078](https://github.com/lager1/CVE-2023-35078) :  
![starts](https://img.shields.io/github/stars/lager1/CVE-2023-35078.svg) 
![forks](https://img.shields.io/github/forks/lager1/CVE-2023-35078.svg) 
2023-07-29T22:49:12Z

- [https://github.com/raytheon0x21/CVE-2023-35078](https://github.com/raytheon0x21/CVE-2023-35078) :  
![starts](https://img.shields.io/github/stars/raytheon0x21/CVE-2023-35078.svg) 
![forks](https://img.shields.io/github/forks/raytheon0x21/CVE-2023-35078.svg) 
2023-08-27T15:10:19Z

- [https://github.com/0nsec/CVE-2023-35078](https://github.com/0nsec/CVE-2023-35078) :  
![starts](https://img.shields.io/github/stars/0nsec/CVE-2023-35078.svg) 
![forks](https://img.shields.io/github/forks/0nsec/CVE-2023-35078.svg) 
2025-02-13T05:57:12Z

- [https://github.com/emanueldosreis/nmap-CVE-2023-35078-Exploit](https://github.com/emanueldosreis/nmap-CVE-2023-35078-Exploit) :  
![starts](https://img.shields.io/github/stars/emanueldosreis/nmap-CVE-2023-35078-Exploit.svg) 
![forks](https://img.shields.io/github/forks/emanueldosreis/nmap-CVE-2023-35078-Exploit.svg) 
2023-08-01T16:36:29Z

- [https://github.com/synfinner/CVE-2023-35078](https://github.com/synfinner/CVE-2023-35078) :  
![starts](https://img.shields.io/github/stars/synfinner/CVE-2023-35078.svg) 
![forks](https://img.shields.io/github/forks/synfinner/CVE-2023-35078.svg) 
2023-07-31T20:37:05Z

- [https://github.com/Blue-number/CVE-2023-35078](https://github.com/Blue-number/CVE-2023-35078) :  
![starts](https://img.shields.io/github/stars/Blue-number/CVE-2023-35078.svg) 
![forks](https://img.shields.io/github/forks/Blue-number/CVE-2023-35078.svg) 
2023-08-30T02:42:54Z

## CVE-2021-36934
 pAn elevation of privilege vulnerability exists because of overly permissive Access Control Lists (ACLs) on multiple system files, including the Security Accounts Manager (SAM) database. An attacker who successfully exploited this vulnerability could run arbitrary code with SYSTEM privileges. An attacker could then install programs; view, change, or delete data; or create new accounts with full user rights./ppAn attacker must have the ability to execute code on a victim system to exploit this vulnerability./ppAfter installing this security update, you emmust/em manually delete all shadow copies of system files, including the SAM database, to fully mitigate this vulnerabilty. strongSimply installing this security update will not fully mitigate this vulnerability./strong See a href="https://support.microsoft.com/topic/1ceaa637-aaa3-4b58-a48b-baf72a2fa9e7"KB5005357- Delete Volume Shadow Copies/a./p

- [https://github.com/Ascotbe/Kernelhub](https://github.com/Ascotbe/Kernelhub) :  
![starts](https://img.shields.io/github/stars/Ascotbe/Kernelhub.svg) 
![forks](https://img.shields.io/github/forks/Ascotbe/Kernelhub.svg) 
2023-02-15T06:44:14Z

- [https://github.com/HuskyHacks/ShadowSteal](https://github.com/HuskyHacks/ShadowSteal) :  
![starts](https://img.shields.io/github/stars/HuskyHacks/ShadowSteal.svg) 
![forks](https://img.shields.io/github/forks/HuskyHacks/ShadowSteal.svg) 
2022-01-16T02:09:46Z

- [https://github.com/firefart/hivenightmare](https://github.com/firefart/hivenightmare) :  
![starts](https://img.shields.io/github/stars/firefart/hivenightmare.svg) 
![forks](https://img.shields.io/github/forks/firefart/hivenightmare.svg) 
2025-02-13T09:04:20Z

- [https://github.com/WiredPulse/Invoke-HiveNightmare](https://github.com/WiredPulse/Invoke-HiveNightmare) :  
![starts](https://img.shields.io/github/stars/WiredPulse/Invoke-HiveNightmare.svg) 
![forks](https://img.shields.io/github/forks/WiredPulse/Invoke-HiveNightmare.svg) 
2022-09-24T20:40:17Z

- [https://github.com/JoranSlingerland/CVE-2021-36934](https://github.com/JoranSlingerland/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/JoranSlingerland/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/JoranSlingerland/CVE-2021-36934.svg) 
2021-10-15T23:44:37Z

- [https://github.com/romarroca/SeriousSam](https://github.com/romarroca/SeriousSam) :  
![starts](https://img.shields.io/github/stars/romarroca/SeriousSam.svg) 
![forks](https://img.shields.io/github/forks/romarroca/SeriousSam.svg) 
2021-07-22T11:39:31Z

- [https://github.com/exploitblizzard/CVE-2021-36934](https://github.com/exploitblizzard/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/exploitblizzard/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/exploitblizzard/CVE-2021-36934.svg) 
2021-07-27T06:56:18Z

- [https://github.com/Wh04m1001/VSSCopy](https://github.com/Wh04m1001/VSSCopy) :  
![starts](https://img.shields.io/github/stars/Wh04m1001/VSSCopy.svg) 
![forks](https://img.shields.io/github/forks/Wh04m1001/VSSCopy.svg) 
2021-07-22T02:15:27Z

- [https://github.com/n3tsurge/CVE-2021-36934](https://github.com/n3tsurge/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/n3tsurge/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/n3tsurge/CVE-2021-36934.svg) 
2021-07-22T02:10:56Z

- [https://github.com/Sp00p64/PyNightmare](https://github.com/Sp00p64/PyNightmare) :  
![starts](https://img.shields.io/github/stars/Sp00p64/PyNightmare.svg) 
![forks](https://img.shields.io/github/forks/Sp00p64/PyNightmare.svg) 
2021-07-25T01:19:31Z

- [https://github.com/CrackerCat/HiveNightmare](https://github.com/CrackerCat/HiveNightmare) :  
![starts](https://img.shields.io/github/stars/CrackerCat/HiveNightmare.svg) 
![forks](https://img.shields.io/github/forks/CrackerCat/HiveNightmare.svg) 
2021-07-25T14:40:25Z

- [https://github.com/chron1k/oxide_hive](https://github.com/chron1k/oxide_hive) :  
![starts](https://img.shields.io/github/stars/chron1k/oxide_hive.svg) 
![forks](https://img.shields.io/github/forks/chron1k/oxide_hive.svg) 
2022-05-01T09:47:54Z

- [https://github.com/Preventions/CVE-2021-36934](https://github.com/Preventions/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/Preventions/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/Preventions/CVE-2021-36934.svg) 
2021-07-24T13:01:47Z

- [https://github.com/websecnl/CVE-2021-36934](https://github.com/websecnl/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/websecnl/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/websecnl/CVE-2021-36934.svg) 
2021-09-04T09:27:49Z

- [https://github.com/bytesizedalex/CVE-2021-36934](https://github.com/bytesizedalex/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/bytesizedalex/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/bytesizedalex/CVE-2021-36934.svg) 
2021-07-23T19:14:19Z

- [https://github.com/irissentinel/CVE-2021-36934](https://github.com/irissentinel/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/irissentinel/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/irissentinel/CVE-2021-36934.svg) 
2021-07-30T12:29:15Z

- [https://github.com/VertigoRay/CVE-2021-36934](https://github.com/VertigoRay/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/VertigoRay/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/VertigoRay/CVE-2021-36934.svg) 
2021-07-24T12:03:28Z

- [https://github.com/grishinpv/poc_CVE-2021-36934](https://github.com/grishinpv/poc_CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/grishinpv/poc_CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/grishinpv/poc_CVE-2021-36934.svg) 
2021-08-02T13:52:20Z

- [https://github.com/OlivierLaflamme/CVE-2021-36934-export-shadow-volume-POC](https://github.com/OlivierLaflamme/CVE-2021-36934-export-shadow-volume-POC) :  
![starts](https://img.shields.io/github/stars/OlivierLaflamme/CVE-2021-36934-export-shadow-volume-POC.svg) 
![forks](https://img.shields.io/github/forks/OlivierLaflamme/CVE-2021-36934-export-shadow-volume-POC.svg) 
2021-08-10T19:43:21Z

- [https://github.com/WiredPulse/Invoke-HiveDreams](https://github.com/WiredPulse/Invoke-HiveDreams) :  
![starts](https://img.shields.io/github/stars/WiredPulse/Invoke-HiveDreams.svg) 
![forks](https://img.shields.io/github/forks/WiredPulse/Invoke-HiveDreams.svg) 
2021-07-22T14:42:51Z

- [https://github.com/wolf0x/PSHiveNightmare](https://github.com/wolf0x/PSHiveNightmare) :  
![starts](https://img.shields.io/github/stars/wolf0x/PSHiveNightmare.svg) 
![forks](https://img.shields.io/github/forks/wolf0x/PSHiveNightmare.svg) 
2021-07-26T16:12:49Z

- [https://github.com/tda90/CVE-2021-36934](https://github.com/tda90/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/tda90/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/tda90/CVE-2021-36934.svg) 
2021-07-29T06:47:20Z

- [https://github.com/0x0D1n/CVE-2021-36934](https://github.com/0x0D1n/CVE-2021-36934) :  
![starts](https://img.shields.io/github/stars/0x0D1n/CVE-2021-36934.svg) 
![forks](https://img.shields.io/github/forks/0x0D1n/CVE-2021-36934.svg) 
2021-07-26T08:18:34Z

- [https://github.com/shaktavist/SeriousSam](https://github.com/shaktavist/SeriousSam) :  
![starts](https://img.shields.io/github/stars/shaktavist/SeriousSam.svg) 
![forks](https://img.shields.io/github/forks/shaktavist/SeriousSam.svg) 
2021-08-04T10:47:52Z

- [https://github.com/jmaddington/Serious-Sam---CVE-2021-36934-Mitigation-for-Datto-RMM](https://github.com/jmaddington/Serious-Sam---CVE-2021-36934-Mitigation-for-Datto-RMM) :  
![starts](https://img.shields.io/github/stars/jmaddington/Serious-Sam---CVE-2021-36934-Mitigation-for-Datto-RMM.svg) 
![forks](https://img.shields.io/github/forks/jmaddington/Serious-Sam---CVE-2021-36934-Mitigation-for-Datto-RMM.svg) 
2021-07-25T18:10:15Z

- [https://github.com/wolf0x/HiveNightmare](https://github.com/wolf0x/HiveNightmare) :  
![starts](https://img.shields.io/github/stars/wolf0x/HiveNightmare.svg) 
![forks](https://img.shields.io/github/forks/wolf0x/HiveNightmare.svg) 
2021-07-25T15:09:01Z

## CVE-2021-21551
 Dell dbutil_2_3.sys driver contains an insufficient access control vulnerability which may lead to escalation of privileges, denial of service, or information disclosure. Local authenticated user access is required.

- [https://github.com/waldo-irc/CVE-2021-21551](https://github.com/waldo-irc/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/waldo-irc/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/waldo-irc/CVE-2021-21551.svg) 
2021-05-20T20:33:09Z

- [https://github.com/tijme/kernel-mii](https://github.com/tijme/kernel-mii) :  
![starts](https://img.shields.io/github/stars/tijme/kernel-mii.svg) 
![forks](https://img.shields.io/github/forks/tijme/kernel-mii.svg) 
2023-05-07T18:38:29Z

- [https://github.com/mathisvickie/CVE-2021-21551](https://github.com/mathisvickie/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/mathisvickie/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/mathisvickie/CVE-2021-21551.svg) 
2021-11-16T17:34:11Z

- [https://github.com/ihack4falafel/Dell-Driver-EoP-CVE-2021-21551](https://github.com/ihack4falafel/Dell-Driver-EoP-CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/ihack4falafel/Dell-Driver-EoP-CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/ihack4falafel/Dell-Driver-EoP-CVE-2021-21551.svg) 
2022-02-24T10:13:45Z

- [https://github.com/ch3rn0byl/CVE-2021-21551](https://github.com/ch3rn0byl/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/ch3rn0byl/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/ch3rn0byl/CVE-2021-21551.svg) 
2021-05-21T03:24:25Z

- [https://github.com/nanabingies/CVE-2021-21551](https://github.com/nanabingies/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/nanabingies/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/nanabingies/CVE-2021-21551.svg) 
2023-02-03T22:31:46Z

- [https://github.com/mzakocs/CVE-2021-21551-POC](https://github.com/mzakocs/CVE-2021-21551-POC) :  
![starts](https://img.shields.io/github/stars/mzakocs/CVE-2021-21551-POC.svg) 
![forks](https://img.shields.io/github/forks/mzakocs/CVE-2021-21551-POC.svg) 
2021-07-20T03:03:30Z

- [https://github.com/arnaudluti/PS-CVE-2021-21551](https://github.com/arnaudluti/PS-CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/arnaudluti/PS-CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/arnaudluti/PS-CVE-2021-21551.svg) 
2021-06-20T11:02:47Z

- [https://github.com/Kinsiinoo/PoshDellDBUtil](https://github.com/Kinsiinoo/PoshDellDBUtil) :  
![starts](https://img.shields.io/github/stars/Kinsiinoo/PoshDellDBUtil.svg) 
![forks](https://img.shields.io/github/forks/Kinsiinoo/PoshDellDBUtil.svg) 
2021-09-20T19:12:28Z

- [https://github.com/IlanDudnik/CVE-2021-21551](https://github.com/IlanDudnik/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/IlanDudnik/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/IlanDudnik/CVE-2021-21551.svg) 
2025-01-12T11:47:59Z

- [https://github.com/luke0x90/CVE-2021-21551](https://github.com/luke0x90/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/luke0x90/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/luke0x90/CVE-2021-21551.svg) 
2025-02-13T16:32:07Z

- [https://github.com/Eap2468/CVE-2021-21551](https://github.com/Eap2468/CVE-2021-21551) :  
![starts](https://img.shields.io/github/stars/Eap2468/CVE-2021-21551.svg) 
![forks](https://img.shields.io/github/forks/Eap2468/CVE-2021-21551.svg) 
2024-08-02T20:22:59Z

## CVE-2016-6914
 Ubiquiti UniFi Video before 3.8.0 for Windows uses weak permissions for the installation directory, which allows local users to gain SYSTEM privileges via a Trojan horse taskkill.exe file.

- [https://github.com/CybermonkX/CVE-2016-6914-UniFiVideo-LPE](https://github.com/CybermonkX/CVE-2016-6914-UniFiVideo-LPE) :  
![starts](https://img.shields.io/github/stars/CybermonkX/CVE-2016-6914-UniFiVideo-LPE.svg) 
![forks](https://img.shields.io/github/forks/CybermonkX/CVE-2016-6914-UniFiVideo-LPE.svg) 
2025-02-13T07:04:16Z

# 2025-02-12
## CVE-2024-55968
 An issue was discovered in DTEX DEC-M (DTEX Forwarder) 6.1.1. The com.dtexsystems.helper service, responsible for handling privileged operations within the macOS DTEX Event Forwarder agent, fails to implement critical client validation during XPC interprocess communication (IPC). Specifically, the service does not verify the code requirements, entitlements, security flags, or version of any client attempting to establish a connection. This lack of proper logic validation allows malicious actors to exploit the service's methods via unauthorized client connections, and escalate privileges to root by abusing the DTConnectionHelperProtocol protocol's submitQuery method over an unauthorized XPC connection.

- [https://github.com/Wi1DN00B/CVE-2024-55968](https://github.com/Wi1DN00B/CVE-2024-55968) :  
![starts](https://img.shields.io/github/stars/Wi1DN00B/CVE-2024-55968.svg) 
![forks](https://img.shields.io/github/forks/Wi1DN00B/CVE-2024-55968.svg) 
2025-02-12T20:40:41Z

- [https://github.com/null-event/CVE-2024-55968](https://github.com/null-event/CVE-2024-55968) :  
![starts](https://img.shields.io/github/stars/null-event/CVE-2024-55968.svg) 
![forks](https://img.shields.io/github/forks/null-event/CVE-2024-55968.svg) 
2025-02-12T20:32:07Z

## CVE-2024-51378
 getresetstatus in dns/views.py and ftp/views.py in CyberPanel (aka Cyber Panel) before 1c0c6cb allows remote attackers to bypass authentication and execute arbitrary commands via /dns/getresetstatus or /ftp/getresetstatus by bypassing secMiddleware (which is only for a POST request) and using shell metacharacters in the statusfile property, as exploited in the wild in October 2024 by PSAUX. Versions through 2.3.6 and (unpatched) 2.3.7 are affected.

- [https://github.com/refr4g/CVE-2024-51378](https://github.com/refr4g/CVE-2024-51378) :  
![starts](https://img.shields.io/github/stars/refr4g/CVE-2024-51378.svg) 
![forks](https://img.shields.io/github/forks/refr4g/CVE-2024-51378.svg) 
2024-11-01T10:12:49Z

- [https://github.com/i0x29A/CVE-2024-51378](https://github.com/i0x29A/CVE-2024-51378) :  
![starts](https://img.shields.io/github/stars/i0x29A/CVE-2024-51378.svg) 
![forks](https://img.shields.io/github/forks/i0x29A/CVE-2024-51378.svg) 
2025-01-03T08:13:35Z

- [https://github.com/qnole000/CVE-2024-51378](https://github.com/qnole000/CVE-2024-51378) :  
![starts](https://img.shields.io/github/stars/qnole000/CVE-2024-51378.svg) 
![forks](https://img.shields.io/github/forks/qnole000/CVE-2024-51378.svg) 
2025-02-12T03:59:44Z

## CVE-2024-29943
 An attacker was able to perform an out-of-bounds read or write on a JavaScript object by fooling range-based bounds check elimination. This vulnerability affects Firefox  124.0.1.

- [https://github.com/bjrjk/CVE-2024-29943](https://github.com/bjrjk/CVE-2024-29943) :  
![starts](https://img.shields.io/github/stars/bjrjk/CVE-2024-29943.svg) 
![forks](https://img.shields.io/github/forks/bjrjk/CVE-2024-29943.svg) 
2025-02-12T01:19:31Z

## CVE-2024-27448
 MailDev 2 through 2.1.0 allows Remote Code Execution via a crafted Content-ID header for an e-mail attachment, leading to lib/mailserver.js writing arbitrary code into the routes.js file.

- [https://github.com/rawtips/CVE-2024-27448-poc](https://github.com/rawtips/CVE-2024-27448-poc) :  
![starts](https://img.shields.io/github/stars/rawtips/CVE-2024-27448-poc.svg) 
![forks](https://img.shields.io/github/forks/rawtips/CVE-2024-27448-poc.svg) 
2025-02-12T21:25:09Z

## CVE-2024-23666
 A client-side enforcement of server-side security in Fortinet FortiAnalyzer-BigData at least version 7.4.0 and 7.2.0 through 7.2.6 and 7.0.1 through 7.0.6 and 6.4.5 through 6.4.7 and 6.2.5, FortiManager version 7.4.0 through 7.4.1 and 7.2.0 through 7.2.4 and 7.0.0 through 7.0.11 and 6.4.0 through 6.4.14, FortiAnalyzer version 7.4.0 through 7.4.1 and 7.2.0 through 7.2.4 and 7.0.0 through 7.0.11 and 6.4.0 through 6.4.14 allows attacker to improper access control via crafted requests.

- [https://github.com/synacktiv/CVE-2023-42791_CVE-2024-23666](https://github.com/synacktiv/CVE-2023-42791_CVE-2024-23666) :  
![starts](https://img.shields.io/github/stars/synacktiv/CVE-2023-42791_CVE-2024-23666.svg) 
![forks](https://img.shields.io/github/forks/synacktiv/CVE-2023-42791_CVE-2024-23666.svg) 
2025-02-12T14:58:09Z

## CVE-2024-21409
 .NET, .NET Framework, and Visual Studio Remote Code Execution Vulnerability

- [https://github.com/vkairy/cve-2024-21409-repro](https://github.com/vkairy/cve-2024-21409-repro) :  
![starts](https://img.shields.io/github/stars/vkairy/cve-2024-21409-repro.svg) 
![forks](https://img.shields.io/github/forks/vkairy/cve-2024-21409-repro.svg) 
2025-02-12T14:59:59Z

## CVE-2024-8743
 The Bit File Manager  100% Free & Open Source File Manager and Code Editor for WordPress plugin for WordPress is vulnerable to Limited JavaScript File Upload in all versions up to, and including, 6.5.7. This is due to a lack of proper checks on allowed file types. This makes it possible for authenticated attackers, with Subscriber-level access and above, and granted permissions by an administrator, to upload .css and .js files, which could lead to Stored Cross-Site Scripting.

- [https://github.com/siunam321/CVE-2024-8743-PoC](https://github.com/siunam321/CVE-2024-8743-PoC) :  
![starts](https://img.shields.io/github/stars/siunam321/CVE-2024-8743-PoC.svg) 
![forks](https://img.shields.io/github/forks/siunam321/CVE-2024-8743-PoC.svg) 
2025-02-12T05:17:02Z

## CVE-2024-8381
 A potentially exploitable type confusion could be triggered when looking up a property name on an object being used as the `with` environment. This vulnerability affects Firefox  130, Firefox ESR  128.2, Firefox ESR  115.15, Thunderbird  128.2, and Thunderbird  115.15.

- [https://github.com/bjrjk/CVE-2024-8381](https://github.com/bjrjk/CVE-2024-8381) :  
![starts](https://img.shields.io/github/stars/bjrjk/CVE-2024-8381.svg) 
![forks](https://img.shields.io/github/forks/bjrjk/CVE-2024-8381.svg) 
2025-02-12T01:18:11Z

## CVE-2024-7627
 The Bit File Manager plugin for WordPress is vulnerable to Remote Code Execution in versions 6.0 to 6.5.5 via the 'checkSyntax' function. This is due to writing a temporary file to a publicly accessible directory before performing file validation. This makes it possible for unauthenticated attackers to execute code on the server if an administrator has allowed Guest User read permissions.

- [https://github.com/siunam321/CVE-2024-7627-PoC](https://github.com/siunam321/CVE-2024-7627-PoC) :  
![starts](https://img.shields.io/github/stars/siunam321/CVE-2024-7627-PoC.svg) 
![forks](https://img.shields.io/github/forks/siunam321/CVE-2024-7627-PoC.svg) 
2025-02-12T05:16:01Z

## CVE-2023-26326
 The BuddyForms WordPress plugin, in versions prior to 2.7.8, was affected by an unauthenticated insecure deserialization issue. An unauthenticated attacker could leverage this issue to call files using a PHAR wrapper that will deserialize the data and call arbitrary PHP Objects that can be used to perform a variety of malicious actions granted a POP chain is also present.

- [https://github.com/mesudmammad1/CVE-2023-26326_Buddyform_exploit](https://github.com/mesudmammad1/CVE-2023-26326_Buddyform_exploit) :  
![starts](https://img.shields.io/github/stars/mesudmammad1/CVE-2023-26326_Buddyform_exploit.svg) 
![forks](https://img.shields.io/github/forks/mesudmammad1/CVE-2023-26326_Buddyform_exploit.svg) 
2025-02-12T15:34:16Z

- [https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961](https://github.com/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961) :  
![starts](https://img.shields.io/github/stars/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
![forks](https://img.shields.io/github/forks/omarelshopky/exploit_cve-2023-26326_using_cve-2024-2961.svg) 
2025-02-02T11:26:18Z

## CVE-2022-39275
 Saleor is a headless, GraphQL commerce platform. In affected versions some GraphQL mutations were not properly checking the ID type input which allowed to access database objects that the authenticated user may not be allowed to access. This vulnerability can be used to expose the following information: Estimating database row counts from tables with a sequential primary key or Exposing staff user and customer email addresses and full name through the `assignNavigation()` mutation. This issue has been patched in main and backported to multiple releases (3.7.17, 3.6.18, 3.5.23, 3.4.24, 3.3.26, 3.2.14, 3.1.24). Users are advised to upgrade. There are no known workarounds for this issue.

- [https://github.com/omar2535/CVE-2022-39275](https://github.com/omar2535/CVE-2022-39275) :  
![starts](https://img.shields.io/github/stars/omar2535/CVE-2022-39275.svg) 
![forks](https://img.shields.io/github/forks/omar2535/CVE-2022-39275.svg) 
2025-02-12T01:35:05Z

## CVE-2022-26134
 In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an unauthenticated attacker to execute arbitrary code on a Confluence Server or Data Center instance. The affected versions are from 1.3.0 before 7.4.17, from 7.13.0 before 7.13.7, from 7.14.0 before 7.14.3, from 7.15.0 before 7.15.2, from 7.16.0 before 7.16.4, from 7.17.0 before 7.17.4, and from 7.18.0 before 7.18.1.

- [https://github.com/W01fh4cker/Serein](https://github.com/W01fh4cker/Serein) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/Serein.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/Serein.svg) 
2023-02-26T14:06:05Z

- [https://github.com/BeichenDream/CVE-2022-26134-Godzilla-MEMSHELL](https://github.com/BeichenDream/CVE-2022-26134-Godzilla-MEMSHELL) :  
![starts](https://img.shields.io/github/stars/BeichenDream/CVE-2022-26134-Godzilla-MEMSHELL.svg) 
![forks](https://img.shields.io/github/forks/BeichenDream/CVE-2022-26134-Godzilla-MEMSHELL.svg) 
2022-06-07T10:35:18Z

- [https://github.com/jbaines-r7/through_the_wire](https://github.com/jbaines-r7/through_the_wire) :  
![starts](https://img.shields.io/github/stars/jbaines-r7/through_the_wire.svg) 
![forks](https://img.shields.io/github/forks/jbaines-r7/through_the_wire.svg) 
2022-06-06T16:38:49Z

- [https://github.com/CLincat/vulcat](https://github.com/CLincat/vulcat) :  
![starts](https://img.shields.io/github/stars/CLincat/vulcat.svg) 
![forks](https://img.shields.io/github/forks/CLincat/vulcat.svg) 
2023-12-04T06:43:07Z

- [https://github.com/W01fh4cker/Serein_Linux](https://github.com/W01fh4cker/Serein_Linux) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/Serein_Linux.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/Serein_Linux.svg) 
2022-07-07T03:24:07Z

- [https://github.com/hev0x/CVE-2022-26134](https://github.com/hev0x/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/hev0x/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/hev0x/CVE-2022-26134.svg) 
2022-06-06T03:37:25Z

- [https://github.com/0x14dli/cve2022-26134exp](https://github.com/0x14dli/cve2022-26134exp) :  
![starts](https://img.shields.io/github/stars/0x14dli/cve2022-26134exp.svg) 
![forks](https://img.shields.io/github/forks/0x14dli/cve2022-26134exp.svg) 
2022-08-03T13:03:48Z

- [https://github.com/crowsec-edtech/CVE-2022-26134](https://github.com/crowsec-edtech/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/crowsec-edtech/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/crowsec-edtech/CVE-2022-26134.svg) 
2022-06-03T19:59:01Z

- [https://github.com/nxtexploit/CVE-2022-26134](https://github.com/nxtexploit/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/nxtexploit/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/nxtexploit/CVE-2022-26134.svg) 
2024-08-23T18:52:52Z

- [https://github.com/SNCKER/CVE-2022-26134](https://github.com/SNCKER/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/SNCKER/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/SNCKER/CVE-2022-26134.svg) 
2022-06-18T09:27:31Z

- [https://github.com/SIFalcon/confluencePot](https://github.com/SIFalcon/confluencePot) :  
![starts](https://img.shields.io/github/stars/SIFalcon/confluencePot.svg) 
![forks](https://img.shields.io/github/forks/SIFalcon/confluencePot.svg) 
2022-06-07T08:51:53Z

- [https://github.com/AmoloHT/CVE-2022-26134](https://github.com/AmoloHT/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/AmoloHT/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/AmoloHT/CVE-2022-26134.svg) 
2022-06-19T14:08:28Z

- [https://github.com/whokilleddb/CVE-2022-26134-Confluence-RCE](https://github.com/whokilleddb/CVE-2022-26134-Confluence-RCE) :  
![starts](https://img.shields.io/github/stars/whokilleddb/CVE-2022-26134-Confluence-RCE.svg) 
![forks](https://img.shields.io/github/forks/whokilleddb/CVE-2022-26134-Confluence-RCE.svg) 
2022-07-24T06:12:44Z

- [https://github.com/iveresk/cve-2022-26134](https://github.com/iveresk/cve-2022-26134) :  
![starts](https://img.shields.io/github/stars/iveresk/cve-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/iveresk/cve-2022-26134.svg) 
2022-07-21T14:24:29Z

- [https://github.com/redhuntlabs/ConfluentPwn](https://github.com/redhuntlabs/ConfluentPwn) :  
![starts](https://img.shields.io/github/stars/redhuntlabs/ConfluentPwn.svg) 
![forks](https://img.shields.io/github/forks/redhuntlabs/ConfluentPwn.svg) 
2025-01-22T10:48:47Z

- [https://github.com/abhishekmorla/CVE-2022-26134](https://github.com/abhishekmorla/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/abhishekmorla/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/abhishekmorla/CVE-2022-26134.svg) 
2022-06-08T15:35:44Z

- [https://github.com/MaskCyberSecurityTeam/CVE-2022-26134_Behinder_MemShell](https://github.com/MaskCyberSecurityTeam/CVE-2022-26134_Behinder_MemShell) :  
![starts](https://img.shields.io/github/stars/MaskCyberSecurityTeam/CVE-2022-26134_Behinder_MemShell.svg) 
![forks](https://img.shields.io/github/forks/MaskCyberSecurityTeam/CVE-2022-26134_Behinder_MemShell.svg) 
2023-02-04T07:18:25Z

- [https://github.com/offlinehoster/CVE-2022-26134](https://github.com/offlinehoster/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/offlinehoster/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/offlinehoster/CVE-2022-26134.svg) 
2022-06-03T10:12:19Z

- [https://github.com/keven1z/CVE-2022-26134](https://github.com/keven1z/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/keven1z/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/keven1z/CVE-2022-26134.svg) 
2022-07-25T05:51:13Z

- [https://github.com/alcaparra/CVE-2022-26134](https://github.com/alcaparra/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/alcaparra/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/alcaparra/CVE-2022-26134.svg) 
2022-06-07T10:53:48Z

- [https://github.com/li8u99/CVE-2022-26134](https://github.com/li8u99/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/li8u99/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/li8u99/CVE-2022-26134.svg) 
2022-06-30T01:07:17Z

- [https://github.com/Y000o/Confluence-CVE-2022-26134](https://github.com/Y000o/Confluence-CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Y000o/Confluence-CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Y000o/Confluence-CVE-2022-26134.svg) 
2022-06-07T16:59:37Z

- [https://github.com/kh4sh3i/CVE-2022-26134](https://github.com/kh4sh3i/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/kh4sh3i/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/kh4sh3i/CVE-2022-26134.svg) 
2022-06-21T12:05:25Z

- [https://github.com/Chocapikk/CVE-2022-26134](https://github.com/Chocapikk/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2022-26134.svg) 
2022-10-19T16:27:48Z

- [https://github.com/archanchoudhury/Confluence-CVE-2022-26134](https://github.com/archanchoudhury/Confluence-CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/archanchoudhury/Confluence-CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/archanchoudhury/Confluence-CVE-2022-26134.svg) 
2022-06-10T03:12:07Z

- [https://github.com/BBD-YZZ/Confluence-RCE](https://github.com/BBD-YZZ/Confluence-RCE) :  
![starts](https://img.shields.io/github/stars/BBD-YZZ/Confluence-RCE.svg) 
![forks](https://img.shields.io/github/forks/BBD-YZZ/Confluence-RCE.svg) 
2024-08-26T09:24:31Z

- [https://github.com/kyxiaxiang/CVE-2022-26134](https://github.com/kyxiaxiang/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/kyxiaxiang/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/kyxiaxiang/CVE-2022-26134.svg) 
2022-06-04T05:48:55Z

- [https://github.com/cai-niao98/CVE-2022-26134](https://github.com/cai-niao98/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/cai-niao98/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/cai-niao98/CVE-2022-26134.svg) 
2022-06-09T02:43:05Z

- [https://github.com/Vulnmachines/Confluence-CVE-2022-26134](https://github.com/Vulnmachines/Confluence-CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/Confluence-CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/Confluence-CVE-2022-26134.svg) 
2022-07-13T14:42:02Z

- [https://github.com/CatAnnaDev/CVE-2022-26134](https://github.com/CatAnnaDev/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/CatAnnaDev/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/CatAnnaDev/CVE-2022-26134.svg) 
2022-06-06T20:20:57Z

- [https://github.com/XiaomingX/cve-2022-26134-poc](https://github.com/XiaomingX/cve-2022-26134-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2022-26134-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2022-26134-poc.svg) 
2024-11-23T05:38:10Z

- [https://github.com/cbk914/CVE-2022-26134_check](https://github.com/cbk914/CVE-2022-26134_check) :  
![starts](https://img.shields.io/github/stars/cbk914/CVE-2022-26134_check.svg) 
![forks](https://img.shields.io/github/forks/cbk914/CVE-2022-26134_check.svg) 
2023-01-15T20:14:57Z

- [https://github.com/skhalsa-sigsci/CVE-2022-26134-LAB](https://github.com/skhalsa-sigsci/CVE-2022-26134-LAB) :  
![starts](https://img.shields.io/github/stars/skhalsa-sigsci/CVE-2022-26134-LAB.svg) 
![forks](https://img.shields.io/github/forks/skhalsa-sigsci/CVE-2022-26134-LAB.svg) 
2022-10-09T17:53:18Z

- [https://github.com/KeepWannabe/BotCon](https://github.com/KeepWannabe/BotCon) :  
![starts](https://img.shields.io/github/stars/KeepWannabe/BotCon.svg) 
![forks](https://img.shields.io/github/forks/KeepWannabe/BotCon.svg) 
2022-06-10T18:22:30Z

- [https://github.com/Debajyoti0-0/CVE-2022-26134](https://github.com/Debajyoti0-0/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Debajyoti0-0/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Debajyoti0-0/CVE-2022-26134.svg) 
2022-07-05T09:40:39Z

- [https://github.com/twoning/CVE-2022-26134-PoC](https://github.com/twoning/CVE-2022-26134-PoC) :  
![starts](https://img.shields.io/github/stars/twoning/CVE-2022-26134-PoC.svg) 
![forks](https://img.shields.io/github/forks/twoning/CVE-2022-26134-PoC.svg) 
2022-07-14T01:31:13Z

- [https://github.com/f4yd4-s3c/cve-2022-26134](https://github.com/f4yd4-s3c/cve-2022-26134) :  
![starts](https://img.shields.io/github/stars/f4yd4-s3c/cve-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/f4yd4-s3c/cve-2022-26134.svg) 
2022-08-28T04:05:53Z

- [https://github.com/b4dboy17/CVE-2022-26134](https://github.com/b4dboy17/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/b4dboy17/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/b4dboy17/CVE-2022-26134.svg) 
2022-10-24T19:03:59Z

- [https://github.com/Brucetg/CVE-2022-26134](https://github.com/Brucetg/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Brucetg/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Brucetg/CVE-2022-26134.svg) 
2022-06-05T15:43:38Z

- [https://github.com/ColdFusionX/CVE-2022-26134](https://github.com/ColdFusionX/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/ColdFusionX/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/ColdFusionX/CVE-2022-26134.svg) 
2022-06-24T10:57:03Z

- [https://github.com/p4b3l1t0/confusploit](https://github.com/p4b3l1t0/confusploit) :  
![starts](https://img.shields.io/github/stars/p4b3l1t0/confusploit.svg) 
![forks](https://img.shields.io/github/forks/p4b3l1t0/confusploit.svg) 
2024-06-19T00:41:12Z

- [https://github.com/murataydemir/CVE-2022-26134](https://github.com/murataydemir/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/murataydemir/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/murataydemir/CVE-2022-26134.svg) 
2022-06-14T10:35:55Z

- [https://github.com/coskper-papa/CVE-2022-26134](https://github.com/coskper-papa/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/coskper-papa/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/coskper-papa/CVE-2022-26134.svg) 
2022-07-08T12:31:07Z

- [https://github.com/shamo0/CVE-2022-26134](https://github.com/shamo0/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/shamo0/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/shamo0/CVE-2022-26134.svg) 
2022-06-04T12:53:58Z

- [https://github.com/acfirthh/CVE-2022-26134](https://github.com/acfirthh/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/acfirthh/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/acfirthh/CVE-2022-26134.svg) 
2023-09-20T20:08:15Z

- [https://github.com/reubensammut/cve-2022-26134](https://github.com/reubensammut/cve-2022-26134) :  
![starts](https://img.shields.io/github/stars/reubensammut/cve-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/reubensammut/cve-2022-26134.svg) 
2022-06-07T09:20:03Z

- [https://github.com/kailing0220/CVE-2022-26134](https://github.com/kailing0220/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/kailing0220/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/kailing0220/CVE-2022-26134.svg) 
2022-10-15T16:07:11Z

- [https://github.com/0xAgun/CVE-2022-26134](https://github.com/0xAgun/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/0xAgun/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/0xAgun/CVE-2022-26134.svg) 
2022-06-06T08:19:24Z

- [https://github.com/Habib0x0/CVE-2022-26134](https://github.com/Habib0x0/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Habib0x0/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Habib0x0/CVE-2022-26134.svg) 
2022-06-07T22:19:34Z

- [https://github.com/1337in/CVE-2022-26134web](https://github.com/1337in/CVE-2022-26134web) :  
![starts](https://img.shields.io/github/stars/1337in/CVE-2022-26134web.svg) 
![forks](https://img.shields.io/github/forks/1337in/CVE-2022-26134web.svg) 
2022-08-26T07:40:01Z

- [https://github.com/kelemaoya/CVE-2022-26134](https://github.com/kelemaoya/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/kelemaoya/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/kelemaoya/CVE-2022-26134.svg) 
2022-10-16T10:59:12Z

- [https://github.com/axingde/CVE-2022-26134](https://github.com/axingde/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/axingde/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/axingde/CVE-2022-26134.svg) 
2022-06-05T13:50:58Z

- [https://github.com/404fu/CVE-2022-26134-POC](https://github.com/404fu/CVE-2022-26134-POC) :  
![starts](https://img.shields.io/github/stars/404fu/CVE-2022-26134-POC.svg) 
![forks](https://img.shields.io/github/forks/404fu/CVE-2022-26134-POC.svg) 
2024-03-26T14:34:11Z

- [https://github.com/ma1am/CVE-2022-26134-Exploit-Detection](https://github.com/ma1am/CVE-2022-26134-Exploit-Detection) :  
![starts](https://img.shields.io/github/stars/ma1am/CVE-2022-26134-Exploit-Detection.svg) 
![forks](https://img.shields.io/github/forks/ma1am/CVE-2022-26134-Exploit-Detection.svg) 
2022-06-06T19:37:27Z

- [https://github.com/r1skkam/TryHackMe-Atlassian-CVE-2022-26134](https://github.com/r1skkam/TryHackMe-Atlassian-CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/r1skkam/TryHackMe-Atlassian-CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/r1skkam/TryHackMe-Atlassian-CVE-2022-26134.svg) 
2022-07-04T16:49:41Z

- [https://github.com/shiftsansan/CVE-2022-26134-Console](https://github.com/shiftsansan/CVE-2022-26134-Console) :  
![starts](https://img.shields.io/github/stars/shiftsansan/CVE-2022-26134-Console.svg) 
![forks](https://img.shields.io/github/forks/shiftsansan/CVE-2022-26134-Console.svg) 
2022-08-23T11:06:33Z

- [https://github.com/latings/CVE-2022-26134](https://github.com/latings/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/latings/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/latings/CVE-2022-26134.svg) 
2022-10-16T12:14:12Z

- [https://github.com/CJ-0107/cve-2022-26134](https://github.com/CJ-0107/cve-2022-26134) :  
![starts](https://img.shields.io/github/stars/CJ-0107/cve-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/CJ-0107/cve-2022-26134.svg) 
2022-10-16T10:55:52Z

- [https://github.com/2212970396/CVE_2022_26134](https://github.com/2212970396/CVE_2022_26134) :  
![starts](https://img.shields.io/github/stars/2212970396/CVE_2022_26134.svg) 
![forks](https://img.shields.io/github/forks/2212970396/CVE_2022_26134.svg) 
2022-07-14T01:33:18Z

- [https://github.com/itwestend/cve_2022_26134](https://github.com/itwestend/cve_2022_26134) :  
![starts](https://img.shields.io/github/stars/itwestend/cve_2022_26134.svg) 
![forks](https://img.shields.io/github/forks/itwestend/cve_2022_26134.svg) 
2022-10-29T11:17:15Z

- [https://github.com/yTxZx/CVE-2022-26134](https://github.com/yTxZx/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/yTxZx/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/yTxZx/CVE-2022-26134.svg) 
2023-10-20T08:36:23Z

- [https://github.com/Khalidhaimur/CVE-2022-26134](https://github.com/Khalidhaimur/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Khalidhaimur/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Khalidhaimur/CVE-2022-26134.svg) 
2025-02-12T17:23:40Z

- [https://github.com/wjlin0/CVE-2022-26134](https://github.com/wjlin0/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/wjlin0/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/wjlin0/CVE-2022-26134.svg) 
2022-12-26T05:27:01Z

- [https://github.com/yyqxi/CVE-2022-26134](https://github.com/yyqxi/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/yyqxi/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/yyqxi/CVE-2022-26134.svg) 
2022-10-16T12:08:38Z

- [https://github.com/DARKSTUFF-LAB/-CVE-2022-26134](https://github.com/DARKSTUFF-LAB/-CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/DARKSTUFF-LAB/-CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/DARKSTUFF-LAB/-CVE-2022-26134.svg) 
2023-12-29T06:51:47Z

- [https://github.com/dream434/CVE_20222_26134](https://github.com/dream434/CVE_20222_26134) :  
![starts](https://img.shields.io/github/stars/dream434/CVE_20222_26134.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE_20222_26134.svg) 
2022-11-25T01:28:54Z

- [https://github.com/cc3305/CVE-2022-26134](https://github.com/cc3305/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/cc3305/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/cc3305/CVE-2022-26134.svg) 
2024-07-27T20:17:24Z

- [https://github.com/xsxtw/CVE-2022-26134](https://github.com/xsxtw/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/xsxtw/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/xsxtw/CVE-2022-26134.svg) 
2024-05-02T18:33:39Z

- [https://github.com/Agentgilspy/CVE-2022-26134](https://github.com/Agentgilspy/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Agentgilspy/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Agentgilspy/CVE-2022-26134.svg) 
2024-11-17T11:19:09Z

- [https://github.com/sunny-kathuria/exploit_CVE-2022-26134](https://github.com/sunny-kathuria/exploit_CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/sunny-kathuria/exploit_CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/sunny-kathuria/exploit_CVE-2022-26134.svg) 
2022-06-10T09:16:02Z

- [https://github.com/Muhammad-Ali007/Atlassian_CVE-2022-26134](https://github.com/Muhammad-Ali007/Atlassian_CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Muhammad-Ali007/Atlassian_CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Muhammad-Ali007/Atlassian_CVE-2022-26134.svg) 
2023-08-03T21:21:56Z

- [https://github.com/vesperp/CVE-2022-26134-Confluence](https://github.com/vesperp/CVE-2022-26134-Confluence) :  
![starts](https://img.shields.io/github/stars/vesperp/CVE-2022-26134-Confluence.svg) 
![forks](https://img.shields.io/github/forks/vesperp/CVE-2022-26134-Confluence.svg) 
2022-06-07T02:22:25Z

- [https://github.com/Luchoane/CVE-2022-26134_conFLU](https://github.com/Luchoane/CVE-2022-26134_conFLU) :  
![starts](https://img.shields.io/github/stars/Luchoane/CVE-2022-26134_conFLU.svg) 
![forks](https://img.shields.io/github/forks/Luchoane/CVE-2022-26134_conFLU.svg) 
2022-07-01T18:41:15Z

- [https://github.com/yigexioabai/CVE-2022-26134-cve1](https://github.com/yigexioabai/CVE-2022-26134-cve1) :  
![starts](https://img.shields.io/github/stars/yigexioabai/CVE-2022-26134-cve1.svg) 
![forks](https://img.shields.io/github/forks/yigexioabai/CVE-2022-26134-cve1.svg) 
2022-10-15T14:56:36Z

- [https://github.com/xanszZZ/ATLASSIAN-Confluence_rce](https://github.com/xanszZZ/ATLASSIAN-Confluence_rce) :  
![starts](https://img.shields.io/github/stars/xanszZZ/ATLASSIAN-Confluence_rce.svg) 
![forks](https://img.shields.io/github/forks/xanszZZ/ATLASSIAN-Confluence_rce.svg) 
2022-10-16T15:09:09Z

## CVE-2022-21449
 Vulnerability in the Oracle Java SE, Oracle GraalVM Enterprise Edition product of Oracle Java SE (component: Libraries). Supported versions that are affected are Oracle Java SE: 17.0.2 and 18; Oracle GraalVM Enterprise Edition: 21.3.1 and 22.0.0.2. Easily exploitable vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise Oracle Java SE, Oracle GraalVM Enterprise Edition. Successful attacks of this vulnerability can result in unauthorized creation, deletion or modification access to critical data or all Oracle Java SE, Oracle GraalVM Enterprise Edition accessible data. Note: This vulnerability applies to Java deployments, typically in clients running sandboxed Java Web Start applications or sandboxed Java applets, that load and run untrusted code (e.g., code that comes from the internet) and rely on the Java sandbox for security. This vulnerability can also be exploited by using APIs in the specified Component, e.g., through a web service which supplies data to the APIs. CVSS 3.1 Base Score 7.5 (Integrity impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:N/I:H/A:N).

- [https://github.com/notkmhn/CVE-2022-21449-TLS-PoC](https://github.com/notkmhn/CVE-2022-21449-TLS-PoC) :  
![starts](https://img.shields.io/github/stars/notkmhn/CVE-2022-21449-TLS-PoC.svg) 
![forks](https://img.shields.io/github/forks/notkmhn/CVE-2022-21449-TLS-PoC.svg) 
2022-04-21T12:04:10Z

- [https://github.com/jfrog/jfrog-CVE-2022-21449](https://github.com/jfrog/jfrog-CVE-2022-21449) :  
![starts](https://img.shields.io/github/stars/jfrog/jfrog-CVE-2022-21449.svg) 
![forks](https://img.shields.io/github/forks/jfrog/jfrog-CVE-2022-21449.svg) 
2022-04-24T07:07:52Z

- [https://github.com/thack1/CVE-2022-21449](https://github.com/thack1/CVE-2022-21449) :  
![starts](https://img.shields.io/github/stars/thack1/CVE-2022-21449.svg) 
![forks](https://img.shields.io/github/forks/thack1/CVE-2022-21449.svg) 
2022-05-01T15:16:50Z

- [https://github.com/jmiettinen/CVE-2022-21449-vuln-test](https://github.com/jmiettinen/CVE-2022-21449-vuln-test) :  
![starts](https://img.shields.io/github/stars/jmiettinen/CVE-2022-21449-vuln-test.svg) 
![forks](https://img.shields.io/github/forks/jmiettinen/CVE-2022-21449-vuln-test.svg) 
2022-04-20T11:48:10Z

- [https://github.com/HeyMrSalt/AIS3-2024-Project-D5Team](https://github.com/HeyMrSalt/AIS3-2024-Project-D5Team) :  
![starts](https://img.shields.io/github/stars/HeyMrSalt/AIS3-2024-Project-D5Team.svg) 
![forks](https://img.shields.io/github/forks/HeyMrSalt/AIS3-2024-Project-D5Team.svg) 
2025-02-12T17:13:36Z

- [https://github.com/fundaergn/CVE-2022-21449](https://github.com/fundaergn/CVE-2022-21449) :  
![starts](https://img.shields.io/github/stars/fundaergn/CVE-2022-21449.svg) 
![forks](https://img.shields.io/github/forks/fundaergn/CVE-2022-21449.svg) 
2022-06-12T19:42:42Z

- [https://github.com/davwwwx/CVE-2022-21449](https://github.com/davwwwx/CVE-2022-21449) :  
![starts](https://img.shields.io/github/stars/davwwwx/CVE-2022-21449.svg) 
![forks](https://img.shields.io/github/forks/davwwwx/CVE-2022-21449.svg) 
2023-01-12T14:45:42Z

- [https://github.com/AlexanderZinoni/CVE-2022-21449](https://github.com/AlexanderZinoni/CVE-2022-21449) :  
![starts](https://img.shields.io/github/stars/AlexanderZinoni/CVE-2022-21449.svg) 
![forks](https://img.shields.io/github/forks/AlexanderZinoni/CVE-2022-21449.svg) 
2024-03-19T17:28:26Z

- [https://github.com/Skipper7718/CVE-2022-21449-showcase](https://github.com/Skipper7718/CVE-2022-21449-showcase) :  
![starts](https://img.shields.io/github/stars/Skipper7718/CVE-2022-21449-showcase.svg) 
![forks](https://img.shields.io/github/forks/Skipper7718/CVE-2022-21449-showcase.svg) 
2022-07-30T20:05:04Z

- [https://github.com/marschall/psychic-signatures](https://github.com/marschall/psychic-signatures) :  
![starts](https://img.shields.io/github/stars/marschall/psychic-signatures.svg) 
![forks](https://img.shields.io/github/forks/marschall/psychic-signatures.svg) 
2022-04-21T16:27:09Z

- [https://github.com/Damok82/SignChecker](https://github.com/Damok82/SignChecker) :  
![starts](https://img.shields.io/github/stars/Damok82/SignChecker.svg) 
![forks](https://img.shields.io/github/forks/Damok82/SignChecker.svg) 
2022-04-25T16:27:35Z

## CVE-2022-4262
 Type confusion in V8 in Google Chrome prior to 108.0.5359.94 allowed a remote attacker to potentially exploit heap corruption via a crafted HTML page. (Chromium security severity: High)

- [https://github.com/bjrjk/CVE-2022-4262](https://github.com/bjrjk/CVE-2022-4262) :  
![starts](https://img.shields.io/github/stars/bjrjk/CVE-2022-4262.svg) 
![forks](https://img.shields.io/github/forks/bjrjk/CVE-2022-4262.svg) 
2025-02-12T01:17:04Z

- [https://github.com/mistymntncop/CVE-2022-4262](https://github.com/mistymntncop/CVE-2022-4262) :  
![starts](https://img.shields.io/github/stars/mistymntncop/CVE-2022-4262.svg) 
![forks](https://img.shields.io/github/forks/mistymntncop/CVE-2022-4262.svg) 
2024-01-29T22:03:03Z

- [https://github.com/quangnh89/CVE-2022-4262](https://github.com/quangnh89/CVE-2022-4262) :  
![starts](https://img.shields.io/github/stars/quangnh89/CVE-2022-4262.svg) 
![forks](https://img.shields.io/github/forks/quangnh89/CVE-2022-4262.svg) 
2024-02-11T18:53:25Z

## CVE-2022-2414
 Access to external entities when parsing XML documents can lead to XML external entity (XXE) attacks. This flaw allows a remote attacker to potentially retrieve the content of arbitrary files by sending specially crafted HTTP requests.

- [https://github.com/amitlttwo/CVE-2022-2414-Proof-Of-Concept](https://github.com/amitlttwo/CVE-2022-2414-Proof-Of-Concept) :  
![starts](https://img.shields.io/github/stars/amitlttwo/CVE-2022-2414-Proof-Of-Concept.svg) 
![forks](https://img.shields.io/github/forks/amitlttwo/CVE-2022-2414-Proof-Of-Concept.svg) 
2025-02-12T18:34:29Z

- [https://github.com/geniuszly/CVE-2022-2414](https://github.com/geniuszly/CVE-2022-2414) :  
![starts](https://img.shields.io/github/stars/geniuszly/CVE-2022-2414.svg) 
![forks](https://img.shields.io/github/forks/geniuszly/CVE-2022-2414.svg) 
2024-10-07T15:37:27Z

- [https://github.com/satyasai1460/CVE-2022-2414](https://github.com/satyasai1460/CVE-2022-2414) :  
![starts](https://img.shields.io/github/stars/satyasai1460/CVE-2022-2414.svg) 
![forks](https://img.shields.io/github/forks/satyasai1460/CVE-2022-2414.svg) 
2023-10-05T08:24:52Z

- [https://github.com/superhac/CVE-2022-2414-POC](https://github.com/superhac/CVE-2022-2414-POC) :  
![starts](https://img.shields.io/github/stars/superhac/CVE-2022-2414-POC.svg) 
![forks](https://img.shields.io/github/forks/superhac/CVE-2022-2414-POC.svg) 
2022-08-18T20:33:38Z

## CVE-2021-43798
 Grafana is an open-source platform for monitoring and observability. Grafana versions 8.0.0-beta1 through 8.3.0 (except for patched versions) iss vulnerable to directory traversal, allowing access to local files. The vulnerable URL path is: `grafana_host_url/public/plugins//`, where is the plugin ID for any installed plugin. At no time has Grafana Cloud been vulnerable. Users are advised to upgrade to patched versions 8.0.7, 8.1.8, 8.2.7, or 8.3.1. The GitHub Security Advisory contains more information about vulnerable URL paths, mitigation, and the disclosure timeline.

- [https://github.com/jas502n/Grafana-CVE-2021-43798](https://github.com/jas502n/Grafana-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/jas502n/Grafana-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/jas502n/Grafana-CVE-2021-43798.svg) 
2023-02-14T07:05:22Z

- [https://github.com/A-D-Team/grafanaExp](https://github.com/A-D-Team/grafanaExp) :  
![starts](https://img.shields.io/github/stars/A-D-Team/grafanaExp.svg) 
![forks](https://img.shields.io/github/forks/A-D-Team/grafanaExp.svg) 
2024-07-12T14:17:27Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/CLincat/vulcat](https://github.com/CLincat/vulcat) :  
![starts](https://img.shields.io/github/stars/CLincat/vulcat.svg) 
![forks](https://img.shields.io/github/forks/CLincat/vulcat.svg) 
2023-12-04T06:43:07Z

- [https://github.com/pedrohavay/exploit-grafana-CVE-2021-43798](https://github.com/pedrohavay/exploit-grafana-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/pedrohavay/exploit-grafana-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/pedrohavay/exploit-grafana-CVE-2021-43798.svg) 
2021-12-11T19:10:03Z

- [https://github.com/taythebot/CVE-2021-43798](https://github.com/taythebot/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/taythebot/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/taythebot/CVE-2021-43798.svg) 
2021-12-07T18:09:20Z

- [https://github.com/zer0yu/CVE-2021-43798](https://github.com/zer0yu/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/zer0yu/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/zer0yu/CVE-2021-43798.svg) 
2021-12-07T14:18:42Z

- [https://github.com/Mr-xn/CVE-2021-43798](https://github.com/Mr-xn/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/Mr-xn/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/Mr-xn/CVE-2021-43798.svg) 
2021-12-07T16:27:56Z

- [https://github.com/M0ge/CVE-2021-43798-grafana_fileread](https://github.com/M0ge/CVE-2021-43798-grafana_fileread) :  
![starts](https://img.shields.io/github/stars/M0ge/CVE-2021-43798-grafana_fileread.svg) 
![forks](https://img.shields.io/github/forks/M0ge/CVE-2021-43798-grafana_fileread.svg) 
2022-01-27T08:35:29Z

- [https://github.com/ScorpionsMAX/CVE-2021-43798-Grafana-POC](https://github.com/ScorpionsMAX/CVE-2021-43798-Grafana-POC) :  
![starts](https://img.shields.io/github/stars/ScorpionsMAX/CVE-2021-43798-Grafana-POC.svg) 
![forks](https://img.shields.io/github/forks/ScorpionsMAX/CVE-2021-43798-Grafana-POC.svg) 
2021-12-17T02:57:41Z

- [https://github.com/asaotomo/CVE-2021-43798-Grafana-Exp](https://github.com/asaotomo/CVE-2021-43798-Grafana-Exp) :  
![starts](https://img.shields.io/github/stars/asaotomo/CVE-2021-43798-Grafana-Exp.svg) 
![forks](https://img.shields.io/github/forks/asaotomo/CVE-2021-43798-Grafana-Exp.svg) 
2021-12-23T15:51:01Z

- [https://github.com/Mo0ns/Grafana_POC-CVE-2021-43798](https://github.com/Mo0ns/Grafana_POC-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/Mo0ns/Grafana_POC-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/Mo0ns/Grafana_POC-CVE-2021-43798.svg) 
2021-12-09T09:56:29Z

- [https://github.com/kenuosec/grafanaExp](https://github.com/kenuosec/grafanaExp) :  
![starts](https://img.shields.io/github/stars/kenuosec/grafanaExp.svg) 
![forks](https://img.shields.io/github/forks/kenuosec/grafanaExp.svg) 
2021-12-07T15:57:04Z

- [https://github.com/z3n70/CVE-2021-43798](https://github.com/z3n70/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/z3n70/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/z3n70/CVE-2021-43798.svg) 
2021-12-09T10:10:25Z

- [https://github.com/rodpwn/CVE-2021-43798-mass_scanner](https://github.com/rodpwn/CVE-2021-43798-mass_scanner) :  
![starts](https://img.shields.io/github/stars/rodpwn/CVE-2021-43798-mass_scanner.svg) 
![forks](https://img.shields.io/github/forks/rodpwn/CVE-2021-43798-mass_scanner.svg) 
2022-01-11T01:28:59Z

- [https://github.com/s1gh/CVE-2021-43798](https://github.com/s1gh/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/s1gh/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/s1gh/CVE-2021-43798.svg) 
2021-12-15T18:56:19Z

- [https://github.com/K3ysTr0K3R/CVE-2021-43798-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2021-43798-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2021-43798-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2021-43798-EXPLOIT.svg) 
2024-03-04T21:20:27Z

- [https://github.com/hupe1980/CVE-2021-43798](https://github.com/hupe1980/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/hupe1980/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/hupe1980/CVE-2021-43798.svg) 
2022-10-08T16:31:01Z

- [https://github.com/Sic4rio/Grafana-Decryptor-for-CVE-2021-43798](https://github.com/Sic4rio/Grafana-Decryptor-for-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/Sic4rio/Grafana-Decryptor-for-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/Sic4rio/Grafana-Decryptor-for-CVE-2021-43798.svg) 
2024-07-02T08:45:45Z

- [https://github.com/Ryze-T/CVE-2021-43798](https://github.com/Ryze-T/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/Ryze-T/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/Ryze-T/CVE-2021-43798.svg) 
2021-12-15T02:53:54Z

- [https://github.com/topyagyuu/CVE-2021-43798](https://github.com/topyagyuu/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/topyagyuu/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/topyagyuu/CVE-2021-43798.svg) 
2024-04-26T11:36:58Z

- [https://github.com/0xSAZZAD/Grafana-CVE-2021-43798](https://github.com/0xSAZZAD/Grafana-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/0xSAZZAD/Grafana-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/0xSAZZAD/Grafana-CVE-2021-43798.svg) 
2024-10-05T19:49:45Z

- [https://github.com/fanygit/Grafana-CVE-2021-43798Exp](https://github.com/fanygit/Grafana-CVE-2021-43798Exp) :  
![starts](https://img.shields.io/github/stars/fanygit/Grafana-CVE-2021-43798Exp.svg) 
![forks](https://img.shields.io/github/forks/fanygit/Grafana-CVE-2021-43798Exp.svg) 
2021-12-16T03:37:46Z

- [https://github.com/LongWayHomie/CVE-2021-43798](https://github.com/LongWayHomie/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/LongWayHomie/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/LongWayHomie/CVE-2021-43798.svg) 
2021-12-22T00:25:39Z

- [https://github.com/wagneralves/CVE-2021-43798](https://github.com/wagneralves/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/wagneralves/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/wagneralves/CVE-2021-43798.svg) 
2023-12-21T15:08:31Z

- [https://github.com/FAOG99/GrafanaDirectoryScanner](https://github.com/FAOG99/GrafanaDirectoryScanner) :  
![starts](https://img.shields.io/github/stars/FAOG99/GrafanaDirectoryScanner.svg) 
![forks](https://img.shields.io/github/forks/FAOG99/GrafanaDirectoryScanner.svg) 
2023-05-12T17:37:35Z

- [https://github.com/k3rwin/CVE-2021-43798-Grafana](https://github.com/k3rwin/CVE-2021-43798-Grafana) :  
![starts](https://img.shields.io/github/stars/k3rwin/CVE-2021-43798-Grafana.svg) 
![forks](https://img.shields.io/github/forks/k3rwin/CVE-2021-43798-Grafana.svg) 
2022-03-16T04:33:37Z

- [https://github.com/lfz97/CVE-2021-43798-Grafana-File-Read](https://github.com/lfz97/CVE-2021-43798-Grafana-File-Read) :  
![starts](https://img.shields.io/github/stars/lfz97/CVE-2021-43798-Grafana-File-Read.svg) 
![forks](https://img.shields.io/github/forks/lfz97/CVE-2021-43798-Grafana-File-Read.svg) 
2021-12-09T02:13:09Z

- [https://github.com/Jroo1053/GrafanaDirInclusion](https://github.com/Jroo1053/GrafanaDirInclusion) :  
![starts](https://img.shields.io/github/stars/Jroo1053/GrafanaDirInclusion.svg) 
![forks](https://img.shields.io/github/forks/Jroo1053/GrafanaDirInclusion.svg) 
2022-09-13T14:20:32Z

- [https://github.com/wezoomagency/GrafXploit](https://github.com/wezoomagency/GrafXploit) :  
![starts](https://img.shields.io/github/stars/wezoomagency/GrafXploit.svg) 
![forks](https://img.shields.io/github/forks/wezoomagency/GrafXploit.svg) 
2024-12-14T17:30:12Z

- [https://github.com/rnsss/CVE-2021-43798-poc](https://github.com/rnsss/CVE-2021-43798-poc) :  
![starts](https://img.shields.io/github/stars/rnsss/CVE-2021-43798-poc.svg) 
![forks](https://img.shields.io/github/forks/rnsss/CVE-2021-43798-poc.svg) 
2022-01-07T03:09:46Z

- [https://github.com/davidr-io/Grafana-8.3-Directory-Traversal](https://github.com/davidr-io/Grafana-8.3-Directory-Traversal) :  
![starts](https://img.shields.io/github/stars/davidr-io/Grafana-8.3-Directory-Traversal.svg) 
![forks](https://img.shields.io/github/forks/davidr-io/Grafana-8.3-Directory-Traversal.svg) 
2025-01-27T02:36:22Z

- [https://github.com/lalkaltest/CVE-2021-43798](https://github.com/lalkaltest/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/lalkaltest/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/lalkaltest/CVE-2021-43798.svg) 
2021-12-09T12:34:42Z

- [https://github.com/MalekAlthubiany/CVE-2021-43798](https://github.com/MalekAlthubiany/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/MalekAlthubiany/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/MalekAlthubiany/CVE-2021-43798.svg) 
2024-06-20T04:10:58Z

- [https://github.com/katseyres2/CVE-2021-43798](https://github.com/katseyres2/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/katseyres2/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/katseyres2/CVE-2021-43798.svg) 
2023-10-26T14:23:28Z

- [https://github.com/G01d3nW01f/CVE-2021-43798](https://github.com/G01d3nW01f/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/G01d3nW01f/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/G01d3nW01f/CVE-2021-43798.svg) 
2023-01-09T06:00:15Z

- [https://github.com/light-Life/CVE-2021-43798](https://github.com/light-Life/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/light-Life/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/light-Life/CVE-2021-43798.svg) 
2022-01-11T08:12:09Z

- [https://github.com/Iris288/CVE-2021-43798](https://github.com/Iris288/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/Iris288/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/Iris288/CVE-2021-43798.svg) 
2023-11-21T11:28:06Z

- [https://github.com/gps1949/CVE-2021-43798](https://github.com/gps1949/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/gps1949/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/gps1949/CVE-2021-43798.svg) 
2021-12-21T10:09:56Z

- [https://github.com/ticofookfook/CVE-2021-43798](https://github.com/ticofookfook/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/ticofookfook/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/ticofookfook/CVE-2021-43798.svg) 
2024-03-27T22:02:15Z

- [https://github.com/gixxyboy/CVE-2021-43798](https://github.com/gixxyboy/CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/gixxyboy/CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/gixxyboy/CVE-2021-43798.svg) 
2021-12-12T15:16:56Z

- [https://github.com/aymenbouferroum/CVE-2021-43798_exploit](https://github.com/aymenbouferroum/CVE-2021-43798_exploit) :  
![starts](https://img.shields.io/github/stars/aymenbouferroum/CVE-2021-43798_exploit.svg) 
![forks](https://img.shields.io/github/forks/aymenbouferroum/CVE-2021-43798_exploit.svg) 
2022-01-22T22:15:34Z

- [https://github.com/yasindce1998/grafana-cve-2021-43798](https://github.com/yasindce1998/grafana-cve-2021-43798) :  
![starts](https://img.shields.io/github/stars/yasindce1998/grafana-cve-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/yasindce1998/grafana-cve-2021-43798.svg) 
2022-03-03T09:42:11Z

- [https://github.com/JiuBanSec/Grafana-CVE-2021-43798](https://github.com/JiuBanSec/Grafana-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/JiuBanSec/Grafana-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/JiuBanSec/Grafana-CVE-2021-43798.svg) 
2021-12-13T11:52:58Z

- [https://github.com/halencarjunior/grafana-CVE-2021-43798](https://github.com/halencarjunior/grafana-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/halencarjunior/grafana-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/halencarjunior/grafana-CVE-2021-43798.svg) 
2021-12-21T23:40:59Z

- [https://github.com/mauricelambert/LabAutomationCVE-2021-43798](https://github.com/mauricelambert/LabAutomationCVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/mauricelambert/LabAutomationCVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/mauricelambert/LabAutomationCVE-2021-43798.svg) 
2023-01-28T11:24:33Z

- [https://github.com/victorhorowitz/grafana-exploit-CVE-2021-43798](https://github.com/victorhorowitz/grafana-exploit-CVE-2021-43798) :  
![starts](https://img.shields.io/github/stars/victorhorowitz/grafana-exploit-CVE-2021-43798.svg) 
![forks](https://img.shields.io/github/forks/victorhorowitz/grafana-exploit-CVE-2021-43798.svg) 
2023-09-03T04:59:29Z

- [https://github.com/BJLIYANLIANG/CVE-2021-43798-Grafana-File-Read](https://github.com/BJLIYANLIANG/CVE-2021-43798-Grafana-File-Read) :  
![starts](https://img.shields.io/github/stars/BJLIYANLIANG/CVE-2021-43798-Grafana-File-Read.svg) 
![forks](https://img.shields.io/github/forks/BJLIYANLIANG/CVE-2021-43798-Grafana-File-Read.svg) 
2021-12-11T08:35:13Z

- [https://github.com/ravi5hanka/CVE-2021-43798-Exploit-for-Windows-and-Linux](https://github.com/ravi5hanka/CVE-2021-43798-Exploit-for-Windows-and-Linux) :  
![starts](https://img.shields.io/github/stars/ravi5hanka/CVE-2021-43798-Exploit-for-Windows-and-Linux.svg) 
![forks](https://img.shields.io/github/forks/ravi5hanka/CVE-2021-43798-Exploit-for-Windows-and-Linux.svg) 
2025-02-12T09:11:46Z

## CVE-2020-29607
 A file upload restriction bypass vulnerability in Pluck CMS before 4.7.13 allows an admin privileged user to gain access in the host through the "manage files" functionality, which may result in remote code execution.

- [https://github.com/0xAbbarhSF/CVE-2020-29607](https://github.com/0xAbbarhSF/CVE-2020-29607) :  
![starts](https://img.shields.io/github/stars/0xAbbarhSF/CVE-2020-29607.svg) 
![forks](https://img.shields.io/github/forks/0xAbbarhSF/CVE-2020-29607.svg) 
2022-06-04T21:11:13Z

- [https://github.com/0xN7y/CVE-2020-29607](https://github.com/0xN7y/CVE-2020-29607) :  
![starts](https://img.shields.io/github/stars/0xN7y/CVE-2020-29607.svg) 
![forks](https://img.shields.io/github/forks/0xN7y/CVE-2020-29607.svg) 
2023-11-24T09:33:24Z

- [https://github.com/Alienfader/CVE-2020-29607](https://github.com/Alienfader/CVE-2020-29607) :  
![starts](https://img.shields.io/github/stars/Alienfader/CVE-2020-29607.svg) 
![forks](https://img.shields.io/github/forks/Alienfader/CVE-2020-29607.svg) 
2025-02-12T00:47:00Z

## CVE-2019-16278
 Directory Traversal in the function http_verify in nostromo nhttpd through 1.9.6 allows an attacker to achieve remote code execution via a crafted HTTP request.

- [https://github.com/jas502n/CVE-2019-16278](https://github.com/jas502n/CVE-2019-16278) :  
![starts](https://img.shields.io/github/stars/jas502n/CVE-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/jas502n/CVE-2019-16278.svg) 
2019-10-15T03:53:55Z

- [https://github.com/AnubisSec/CVE-2019-16278](https://github.com/AnubisSec/CVE-2019-16278) :  
![starts](https://img.shields.io/github/stars/AnubisSec/CVE-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/AnubisSec/CVE-2019-16278.svg) 
2019-11-22T18:57:29Z

- [https://github.com/imjdl/CVE-2019-16278-PoC](https://github.com/imjdl/CVE-2019-16278-PoC) :  
![starts](https://img.shields.io/github/stars/imjdl/CVE-2019-16278-PoC.svg) 
![forks](https://img.shields.io/github/forks/imjdl/CVE-2019-16278-PoC.svg) 
2019-10-15T09:28:25Z

- [https://github.com/aN0mad/CVE-2019-16278-Nostromo_1.9.6-RCE](https://github.com/aN0mad/CVE-2019-16278-Nostromo_1.9.6-RCE) :  
![starts](https://img.shields.io/github/stars/aN0mad/CVE-2019-16278-Nostromo_1.9.6-RCE.svg) 
![forks](https://img.shields.io/github/forks/aN0mad/CVE-2019-16278-Nostromo_1.9.6-RCE.svg) 
2019-11-26T14:26:03Z

- [https://github.com/ianxtianxt/CVE-2019-16278](https://github.com/ianxtianxt/CVE-2019-16278) :  
![starts](https://img.shields.io/github/stars/ianxtianxt/CVE-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/ianxtianxt/CVE-2019-16278.svg) 
2020-01-11T07:25:38Z

- [https://github.com/darkerego/Nostromo_Python3](https://github.com/darkerego/Nostromo_Python3) :  
![starts](https://img.shields.io/github/stars/darkerego/Nostromo_Python3.svg) 
![forks](https://img.shields.io/github/forks/darkerego/Nostromo_Python3.svg) 
2019-10-23T22:26:41Z

- [https://github.com/Kr0ff/cve-2019-16278](https://github.com/Kr0ff/cve-2019-16278) :  
![starts](https://img.shields.io/github/stars/Kr0ff/cve-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/Kr0ff/cve-2019-16278.svg) 
2019-12-31T16:07:48Z

- [https://github.com/cancela24/CVE-2019-16278-Nostromo-1.9.6-RCE](https://github.com/cancela24/CVE-2019-16278-Nostromo-1.9.6-RCE) :  
![starts](https://img.shields.io/github/stars/cancela24/CVE-2019-16278-Nostromo-1.9.6-RCE.svg) 
![forks](https://img.shields.io/github/forks/cancela24/CVE-2019-16278-Nostromo-1.9.6-RCE.svg) 
2024-11-12T00:15:57Z

- [https://github.com/sunnet-cyber/CVE2019_16278](https://github.com/sunnet-cyber/CVE2019_16278) :  
![starts](https://img.shields.io/github/stars/sunnet-cyber/CVE2019_16278.svg) 
![forks](https://img.shields.io/github/forks/sunnet-cyber/CVE2019_16278.svg) 
2021-02-09T06:43:49Z

- [https://github.com/keshiba/cve-2019-16278](https://github.com/keshiba/cve-2019-16278) :  
![starts](https://img.shields.io/github/stars/keshiba/cve-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/keshiba/cve-2019-16278.svg) 
2022-06-24T16:41:07Z

- [https://github.com/alexander-fernandes/CVE-2019-16278](https://github.com/alexander-fernandes/CVE-2019-16278) :  
![starts](https://img.shields.io/github/stars/alexander-fernandes/CVE-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/alexander-fernandes/CVE-2019-16278.svg) 
2022-03-24T12:25:13Z

- [https://github.com/n3rdh4x0r/CVE-2019-16278](https://github.com/n3rdh4x0r/CVE-2019-16278) :  
![starts](https://img.shields.io/github/stars/n3rdh4x0r/CVE-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/n3rdh4x0r/CVE-2019-16278.svg) 
2024-11-18T19:18:24Z

- [https://github.com/NHPT/CVE-2019-16278](https://github.com/NHPT/CVE-2019-16278) :  
![starts](https://img.shields.io/github/stars/NHPT/CVE-2019-16278.svg) 
![forks](https://img.shields.io/github/forks/NHPT/CVE-2019-16278.svg) 
2020-01-01T13:36:22Z

- [https://github.com/FredBrave/CVE-2019-16278-Nostromo-1.9.6-RCE](https://github.com/FredBrave/CVE-2019-16278-Nostromo-1.9.6-RCE) :  
![starts](https://img.shields.io/github/stars/FredBrave/CVE-2019-16278-Nostromo-1.9.6-RCE.svg) 
![forks](https://img.shields.io/github/forks/FredBrave/CVE-2019-16278-Nostromo-1.9.6-RCE.svg) 
2023-05-04T22:07:53Z

- [https://github.com/CybermonkX/CVE-2019-16278_Nostromo-1.9.6---Remote-Code-Execution](https://github.com/CybermonkX/CVE-2019-16278_Nostromo-1.9.6---Remote-Code-Execution) :  
![starts](https://img.shields.io/github/stars/CybermonkX/CVE-2019-16278_Nostromo-1.9.6---Remote-Code-Execution.svg) 
![forks](https://img.shields.io/github/forks/CybermonkX/CVE-2019-16278_Nostromo-1.9.6---Remote-Code-Execution.svg) 
2025-02-12T08:49:43Z

