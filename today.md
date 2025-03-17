# 2025-03-17
## CVE-2025-30066
 tj-actions changed-files before 46 allows remote attackers to discover secrets by reading actions logs. (The tags v1 through v45.0.7 were affected on 2025-03-14 and 2025-03-15 because they were modified by a threat actor to point at commit 0e58ed8, which contained malicious updateFeatures code.)

- [https://github.com/OS-pedrogustavobilro/test-changed-files](https://github.com/OS-pedrogustavobilro/test-changed-files) :  
![starts](https://img.shields.io/github/stars/OS-pedrogustavobilro/test-changed-files.svg) 
![forks](https://img.shields.io/github/forks/OS-pedrogustavobilro/test-changed-files.svg) 
2025-03-17T10:07:10Z

## CVE-2025-25763
 crmeb CRMEB-KY v5.4.0 and before has a SQL Injection vulnerability at getRead() in /system/SystemDatabackupServices.php

- [https://github.com/Oyst3r1ng/CVE-2025-25763](https://github.com/Oyst3r1ng/CVE-2025-25763) :  
![starts](https://img.shields.io/github/stars/Oyst3r1ng/CVE-2025-25763.svg) 
![forks](https://img.shields.io/github/forks/Oyst3r1ng/CVE-2025-25763.svg) 
2025-03-17T05:58:52Z

## CVE-2025-24813
 Path Equivalence: 'file.Name' (Internal Dot) leading toRemote Code Execution and/or Information disclosureand/or malicious content added to uploaded files via write enabledDefault Servletin Apache Tomcat.This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.2, from 10.1.0-M1 through 10.1.34, from 9.0.0.M1 through 9.0.98.If all of the following were true, a malicious user was able to view       security sensitive files and/or inject content into those files:-writes enabled for the default servlet (disabled by default)- support for partial PUT (enabled by default)- a target URL for security sensitive uploads that was a sub-directory ofa target URL for public uploads-attacker knowledge of the names of security sensitive files beinguploaded-the security sensitive files also being uploaded via partial PUTIf all of the following were true, a malicious user was able to       perform remote code execution:- writes enabled for the default servlet (disabled by default)-support for partial PUT (enabled by default)-application was using Tomcat's file based session persistence with thedefault storage location-application included a library that may be leveraged in adeserialization attackUsers are recommended to upgrade to version 11.0.3, 10.1.35 or 9.0.98, which fixes the issue.

- [https://github.com/iSee857/CVE-2025-24813-PoC](https://github.com/iSee857/CVE-2025-24813-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2025-24813-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2025-24813-PoC.svg) 
2025-03-13T10:06:35Z

- [https://github.com/absholi7ly/POC-CVE-2025-24813](https://github.com/absholi7ly/POC-CVE-2025-24813) :  
![starts](https://img.shields.io/github/stars/absholi7ly/POC-CVE-2025-24813.svg) 
![forks](https://img.shields.io/github/forks/absholi7ly/POC-CVE-2025-24813.svg) 
2025-03-14T07:57:27Z

- [https://github.com/FY036/cve-2025-24813_poc](https://github.com/FY036/cve-2025-24813_poc) :  
![starts](https://img.shields.io/github/stars/FY036/cve-2025-24813_poc.svg) 
![forks](https://img.shields.io/github/forks/FY036/cve-2025-24813_poc.svg) 
2025-03-14T08:04:00Z

- [https://github.com/N0c1or/CVE-2025-24813_POC](https://github.com/N0c1or/CVE-2025-24813_POC) :  
![starts](https://img.shields.io/github/stars/N0c1or/CVE-2025-24813_POC.svg) 
![forks](https://img.shields.io/github/forks/N0c1or/CVE-2025-24813_POC.svg) 
2025-03-15T22:08:29Z

- [https://github.com/charis3306/CVE-2025-24813](https://github.com/charis3306/CVE-2025-24813) :  
![starts](https://img.shields.io/github/stars/charis3306/CVE-2025-24813.svg) 
![forks](https://img.shields.io/github/forks/charis3306/CVE-2025-24813.svg) 
2025-03-16T12:11:18Z

- [https://github.com/gregk4sec/CVE-2025-24813](https://github.com/gregk4sec/CVE-2025-24813) :  
![starts](https://img.shields.io/github/stars/gregk4sec/CVE-2025-24813.svg) 
![forks](https://img.shields.io/github/forks/gregk4sec/CVE-2025-24813.svg) 
2025-03-14T07:47:24Z

- [https://github.com/issamjr/CVE-2025-24813-Scanner](https://github.com/issamjr/CVE-2025-24813-Scanner) :  
![starts](https://img.shields.io/github/stars/issamjr/CVE-2025-24813-Scanner.svg) 
![forks](https://img.shields.io/github/forks/issamjr/CVE-2025-24813-Scanner.svg) 
2025-03-17T04:06:38Z

## CVE-2025-21333
 Windows Hyper-V NT Kernel Integration VSP Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2025-21333-POC](https://github.com/MrAle98/CVE-2025-21333-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2025-21333-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2025-21333-POC.svg) 
2025-03-11T17:12:48Z

- [https://github.com/aleongx/KQL_sentinel_CVE-2025-21333](https://github.com/aleongx/KQL_sentinel_CVE-2025-21333) :  
![starts](https://img.shields.io/github/stars/aleongx/KQL_sentinel_CVE-2025-21333.svg) 
![forks](https://img.shields.io/github/forks/aleongx/KQL_sentinel_CVE-2025-21333.svg) 
2025-03-11T17:34:11Z

- [https://github.com/Mukesh-blend/CVE-2025-21333-POC](https://github.com/Mukesh-blend/CVE-2025-21333-POC) :  
![starts](https://img.shields.io/github/stars/Mukesh-blend/CVE-2025-21333-POC.svg) 
![forks](https://img.shields.io/github/forks/Mukesh-blend/CVE-2025-21333-POC.svg) 
2025-03-17T11:45:34Z

## CVE-2025-0411
 7-Zip Mark-of-the-Web Bypass Vulnerability. This vulnerability allows remote attackers to bypass the Mark-of-the-Web protection mechanism on affected installations of 7-Zip. User interaction is required to exploit this vulnerability in that the target must visit a malicious page or open a malicious file.The specific flaw exists within the handling of archived files. When extracting files from a crafted archive that bears the Mark-of-the-Web, 7-Zip does not propagate the Mark-of-the-Web to the extracted files. An attacker can leverage this vulnerability to execute arbitrary code in the context of the current user. Was ZDI-CAN-25456.

- [https://github.com/dhmosfunk/7-Zip-CVE-2025-0411-POC](https://github.com/dhmosfunk/7-Zip-CVE-2025-0411-POC) :  
![starts](https://img.shields.io/github/stars/dhmosfunk/7-Zip-CVE-2025-0411-POC.svg) 
![forks](https://img.shields.io/github/forks/dhmosfunk/7-Zip-CVE-2025-0411-POC.svg) 
2025-03-06T11:31:36Z

- [https://github.com/iSee857/CVE-2025-0411-PoC](https://github.com/iSee857/CVE-2025-0411-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2025-0411-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2025-0411-PoC.svg) 
2025-01-27T07:34:46Z

- [https://github.com/cesarbtakeda/7-Zip-CVE-2025-0411-POC](https://github.com/cesarbtakeda/7-Zip-CVE-2025-0411-POC) :  
![starts](https://img.shields.io/github/stars/cesarbtakeda/7-Zip-CVE-2025-0411-POC.svg) 
![forks](https://img.shields.io/github/forks/cesarbtakeda/7-Zip-CVE-2025-0411-POC.svg) 
2025-02-23T03:22:56Z

- [https://github.com/dpextreme/7-Zip-CVE-2025-0411-POC](https://github.com/dpextreme/7-Zip-CVE-2025-0411-POC) :  
![starts](https://img.shields.io/github/stars/dpextreme/7-Zip-CVE-2025-0411-POC.svg) 
![forks](https://img.shields.io/github/forks/dpextreme/7-Zip-CVE-2025-0411-POC.svg) 
2025-03-17T12:10:47Z

- [https://github.com/SalehAlgnay/7-Zip-CVE-2025-0411-POC](https://github.com/SalehAlgnay/7-Zip-CVE-2025-0411-POC) :  
![starts](https://img.shields.io/github/stars/SalehAlgnay/7-Zip-CVE-2025-0411-POC.svg) 
![forks](https://img.shields.io/github/forks/SalehAlgnay/7-Zip-CVE-2025-0411-POC.svg) 
2025-03-17T12:11:14Z

- [https://github.com/ishwardeepp/CVE-2025-0411-MoTW-PoC](https://github.com/ishwardeepp/CVE-2025-0411-MoTW-PoC) :  
![starts](https://img.shields.io/github/stars/ishwardeepp/CVE-2025-0411-MoTW-PoC.svg) 
![forks](https://img.shields.io/github/forks/ishwardeepp/CVE-2025-0411-MoTW-PoC.svg) 
2025-03-12T11:54:18Z

## CVE-2024-31317
 In multiple functions of ZygoteProcess.java, there is a possible way to achieve code execution as any app via WRITE_SECURE_SETTINGS due to unsafe deserialization. This could lead to local escalation of privilege with User execution privileges needed. User interaction is not needed for exploitation.

- [https://github.com/fuhei/CVE-2024-31317](https://github.com/fuhei/CVE-2024-31317) :  
![starts](https://img.shields.io/github/stars/fuhei/CVE-2024-31317.svg) 
![forks](https://img.shields.io/github/forks/fuhei/CVE-2024-31317.svg) 
2024-12-05T01:52:45Z

- [https://github.com/jmywh1/CVE-2024-31317](https://github.com/jmywh1/CVE-2024-31317) :  
![starts](https://img.shields.io/github/stars/jmywh1/CVE-2024-31317.svg) 
![forks](https://img.shields.io/github/forks/jmywh1/CVE-2024-31317.svg) 
2025-03-17T04:09:09Z

## CVE-2024-8926
 In PHP versions 8.1.* before 8.1.30, 8.2.* before 8.2.24, 8.3.* before 8.3.12,when using a certain non-standard configurations of Windows codepages, the fixes for CVE-2024-4577 https://github.com/advisories/GHSA-vxpp-6299-mxw3 may still be bypassed and the same command injection related to Windows "Best Fit" codepage behavior can be achieved. Thismay allow a malicious user to pass options to PHP binary being run, and thus reveal the source code of scripts, run arbitrary PHP code on the server, etc.

- [https://github.com/Night-have-dreams/php-cgi-Injector](https://github.com/Night-have-dreams/php-cgi-Injector) :  
![starts](https://img.shields.io/github/stars/Night-have-dreams/php-cgi-Injector.svg) 
![forks](https://img.shields.io/github/forks/Night-have-dreams/php-cgi-Injector.svg) 
2025-03-17T16:02:07Z

## CVE-2024-7014
 EvilVideo vulnerability allows sending malicious apps disguised as videos in Telegram for Android application affecting  versions 10.14.4 and older.

- [https://github.com/hexspectrum1/CVE-2024-7014](https://github.com/hexspectrum1/CVE-2024-7014) :  
![starts](https://img.shields.io/github/stars/hexspectrum1/CVE-2024-7014.svg) 
![forks](https://img.shields.io/github/forks/hexspectrum1/CVE-2024-7014.svg) 
2025-03-08T06:51:34Z

- [https://github.com/absholi7ly/PoC-for-CVE-2024-7014-Exploit](https://github.com/absholi7ly/PoC-for-CVE-2024-7014-Exploit) :  
![starts](https://img.shields.io/github/stars/absholi7ly/PoC-for-CVE-2024-7014-Exploit.svg) 
![forks](https://img.shields.io/github/forks/absholi7ly/PoC-for-CVE-2024-7014-Exploit.svg) 
2025-03-17T03:48:24Z

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

- [https://github.com/huseyinstif/CVE-2024-4577-Nuclei-Template](https://github.com/huseyinstif/CVE-2024-4577-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/huseyinstif/CVE-2024-4577-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/huseyinstif/CVE-2024-4577-Nuclei-Template.svg) 
2024-06-24T11:54:58Z

- [https://github.com/gh-ost00/CVE-2024-4577-RCE](https://github.com/gh-ost00/CVE-2024-4577-RCE) :  
![starts](https://img.shields.io/github/stars/gh-ost00/CVE-2024-4577-RCE.svg) 
![forks](https://img.shields.io/github/forks/gh-ost00/CVE-2024-4577-RCE.svg) 
2024-08-20T03:28:28Z

- [https://github.com/Night-have-dreams/php-cgi-Injector](https://github.com/Night-have-dreams/php-cgi-Injector) :  
![starts](https://img.shields.io/github/stars/Night-have-dreams/php-cgi-Injector.svg) 
![forks](https://img.shields.io/github/forks/Night-have-dreams/php-cgi-Injector.svg) 
2025-03-17T16:02:07Z

- [https://github.com/gotr00t0day/CVE-2024-4577](https://github.com/gotr00t0day/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/gotr00t0day/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/gotr00t0day/CVE-2024-4577.svg) 
2024-06-15T02:57:48Z

- [https://github.com/manuelinfosec/CVE-2024-4577](https://github.com/manuelinfosec/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/manuelinfosec/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/manuelinfosec/CVE-2024-4577.svg) 
2024-06-08T05:50:27Z

- [https://github.com/K3ysTr0K3R/CVE-2024-4577-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-4577-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-4577-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-4577-EXPLOIT.svg) 
2024-07-12T02:56:25Z

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

- [https://github.com/zomasec/CVE-2024-4577](https://github.com/zomasec/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/zomasec/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/zomasec/CVE-2024-4577.svg) 
2024-06-09T16:47:11Z

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

- [https://github.com/mr-won/php-cgi-cve-2024-4577](https://github.com/mr-won/php-cgi-cve-2024-4577) :  
![starts](https://img.shields.io/github/stars/mr-won/php-cgi-cve-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/mr-won/php-cgi-cve-2024-4577.svg) 
2025-02-14T11:16:39Z

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

- [https://github.com/Sysc4ll3r/CVE-2024-4577](https://github.com/Sysc4ll3r/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Sysc4ll3r/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Sysc4ll3r/CVE-2024-4577.svg) 
2024-06-07T18:41:17Z

- [https://github.com/bl4cksku11/CVE-2024-4577](https://github.com/bl4cksku11/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bl4cksku11/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bl4cksku11/CVE-2024-4577.svg) 
2024-06-11T15:29:21Z

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

# 2025-03-16
## CVE-2025-22604
 Cacti is an open source performance and fault management framework. Due to a flaw in multi-line SNMP result parser, authenticated users can inject malformed OIDs in the response. When processed by ss_net_snmp_disk_io() or ss_net_snmp_disk_bytes(), a part of each OID will be used as a key in an array that is used as part of a system command, causing a command execution vulnerability. This vulnerability is fixed in 1.2.29.

- [https://github.com/ishwardeepp/CVE-2025-22604-Cacti-RCE](https://github.com/ishwardeepp/CVE-2025-22604-Cacti-RCE) :  
![starts](https://img.shields.io/github/stars/ishwardeepp/CVE-2025-22604-Cacti-RCE.svg) 
![forks](https://img.shields.io/github/forks/ishwardeepp/CVE-2025-22604-Cacti-RCE.svg) 
2025-03-16T09:21:50Z

## CVE-2024-23334
 aiohttp is an asynchronous HTTP client/server framework for asyncio and Python. When using aiohttp as a web server and configuring static routes, it is necessary to specify the root path for static files. Additionally, the option 'follow_symlinks' can be used to determine whether to follow symbolic links outside the static root directory. When 'follow_symlinks' is set to True, there is no validation to check if reading a file is within the root directory. This can lead to directory traversal vulnerabilities, resulting in unauthorized access to arbitrary files on the system, even when symlinks are not present.  Disabling follow_symlinks and using a reverse proxy are encouraged mitigations.  Version 3.9.2 fixes this issue.

- [https://github.com/jhonnybonny/CVE-2024-23334](https://github.com/jhonnybonny/CVE-2024-23334) :  
![starts](https://img.shields.io/github/stars/jhonnybonny/CVE-2024-23334.svg) 
![forks](https://img.shields.io/github/forks/jhonnybonny/CVE-2024-23334.svg) 
2024-03-19T17:06:26Z

- [https://github.com/z3rObyte/CVE-2024-23334-PoC](https://github.com/z3rObyte/CVE-2024-23334-PoC) :  
![starts](https://img.shields.io/github/stars/z3rObyte/CVE-2024-23334-PoC.svg) 
![forks](https://img.shields.io/github/forks/z3rObyte/CVE-2024-23334-PoC.svg) 
2024-03-19T06:37:30Z

- [https://github.com/ox1111/CVE-2024-23334](https://github.com/ox1111/CVE-2024-23334) :  
![starts](https://img.shields.io/github/stars/ox1111/CVE-2024-23334.svg) 
![forks](https://img.shields.io/github/forks/ox1111/CVE-2024-23334.svg) 
2024-02-29T02:00:16Z

- [https://github.com/s4botai/CVE-2024-23334-PoC](https://github.com/s4botai/CVE-2024-23334-PoC) :  
![starts](https://img.shields.io/github/stars/s4botai/CVE-2024-23334-PoC.svg) 
![forks](https://img.shields.io/github/forks/s4botai/CVE-2024-23334-PoC.svg) 
2024-09-08T10:49:44Z

- [https://github.com/sxyrxyy/aiohttp-exploit-CVE-2024-23334-certstream](https://github.com/sxyrxyy/aiohttp-exploit-CVE-2024-23334-certstream) :  
![starts](https://img.shields.io/github/stars/sxyrxyy/aiohttp-exploit-CVE-2024-23334-certstream.svg) 
![forks](https://img.shields.io/github/forks/sxyrxyy/aiohttp-exploit-CVE-2024-23334-certstream.svg) 
2024-03-18T12:25:54Z

- [https://github.com/wizarddos/CVE-2024-23334](https://github.com/wizarddos/CVE-2024-23334) :  
![starts](https://img.shields.io/github/stars/wizarddos/CVE-2024-23334.svg) 
![forks](https://img.shields.io/github/forks/wizarddos/CVE-2024-23334.svg) 
2024-10-20T16:48:53Z

- [https://github.com/Betan423/CVE-2024-23334-PoC](https://github.com/Betan423/CVE-2024-23334-PoC) :  
![starts](https://img.shields.io/github/stars/Betan423/CVE-2024-23334-PoC.svg) 
![forks](https://img.shields.io/github/forks/Betan423/CVE-2024-23334-PoC.svg) 
2024-12-09T09:25:16Z

- [https://github.com/TheRedP4nther/LFI-aiohttp-CVE-2024-23334-PoC](https://github.com/TheRedP4nther/LFI-aiohttp-CVE-2024-23334-PoC) :  
![starts](https://img.shields.io/github/stars/TheRedP4nther/LFI-aiohttp-CVE-2024-23334-PoC.svg) 
![forks](https://img.shields.io/github/forks/TheRedP4nther/LFI-aiohttp-CVE-2024-23334-PoC.svg) 
2025-03-16T13:22:26Z

- [https://github.com/Pylonet/CVE-2024-23334](https://github.com/Pylonet/CVE-2024-23334) :  
![starts](https://img.shields.io/github/stars/Pylonet/CVE-2024-23334.svg) 
![forks](https://img.shields.io/github/forks/Pylonet/CVE-2024-23334.svg) 
2024-11-24T14:33:37Z

- [https://github.com/brian-edgar-re/poc-cve-2024-23334](https://github.com/brian-edgar-re/poc-cve-2024-23334) :  
![starts](https://img.shields.io/github/stars/brian-edgar-re/poc-cve-2024-23334.svg) 
![forks](https://img.shields.io/github/forks/brian-edgar-re/poc-cve-2024-23334.svg) 
2024-04-29T01:40:19Z

- [https://github.com/binaryninja/CVE-2024-23334](https://github.com/binaryninja/CVE-2024-23334) :  
![starts](https://img.shields.io/github/stars/binaryninja/CVE-2024-23334.svg) 
![forks](https://img.shields.io/github/forks/binaryninja/CVE-2024-23334.svg) 
2024-06-17T16:37:11Z

- [https://github.com/BestDevOfc/CVE-2024-23334-PoC](https://github.com/BestDevOfc/CVE-2024-23334-PoC) :  
![starts](https://img.shields.io/github/stars/BestDevOfc/CVE-2024-23334-PoC.svg) 
![forks](https://img.shields.io/github/forks/BestDevOfc/CVE-2024-23334-PoC.svg) 
2024-12-27T11:21:36Z

- [https://github.com/Arc4he/CVE-2024-23334-PoC](https://github.com/Arc4he/CVE-2024-23334-PoC) :  
![starts](https://img.shields.io/github/stars/Arc4he/CVE-2024-23334-PoC.svg) 
![forks](https://img.shields.io/github/forks/Arc4he/CVE-2024-23334-PoC.svg) 
2024-11-09T14:18:02Z

## CVE-2024-9047
 The WordPress File Upload plugin for WordPress is vulnerable to Path Traversal in all versions up to, and including, 4.24.11 via wfu_file_downloader.php. This makes it possible for unauthenticated attackers to read or delete files outside of the originally intended directory. Successful exploitation requires the targeted WordPress installation to be using PHP 7.4 or earlier.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/verylazytech/CVE-2024-9047](https://github.com/verylazytech/CVE-2024-9047) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-9047.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-9047.svg) 
2025-01-08T07:36:19Z

- [https://github.com/iSee857/CVE-2024-9047-PoC](https://github.com/iSee857/CVE-2024-9047-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2024-9047-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2024-9047-PoC.svg) 
2024-12-25T05:28:55Z

- [https://github.com/Nxploited/CVE-2024-9047-Exploit](https://github.com/Nxploited/CVE-2024-9047-Exploit) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-9047-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-9047-Exploit.svg) 
2025-01-25T03:20:25Z

- [https://github.com/mr-won/CVE-2024-9047](https://github.com/mr-won/CVE-2024-9047) :  
![starts](https://img.shields.io/github/stars/mr-won/CVE-2024-9047.svg) 
![forks](https://img.shields.io/github/forks/mr-won/CVE-2024-9047.svg) 
2025-03-16T18:07:11Z

# 2025-03-15
## CVE-2024-51788
 Unrestricted Upload of File with Dangerous Type vulnerability in Joshua Wolfe The Novel Design Store Directory allows Upload a Web Shell to a Web Server.This issue affects The Novel Design Store Directory: from n/a through 4.3.0.

- [https://github.com/Nxploited/CVE-2024-51788](https://github.com/Nxploited/CVE-2024-51788) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-51788.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-51788.svg) 
2025-03-15T04:39:16Z

## CVE-2024-27398
 In the Linux kernel, the following vulnerability has been resolved:Bluetooth: Fix use-after-free bugs caused by sco_sock_timeoutWhen the sco connection is established and then, the sco socketis releasing, timeout_work will be scheduled to judge whetherthe sco disconnection is timeout. The sock will be deallocatedlater, but it is dereferenced again in sco_sock_timeout. As aresult, the use-after-free bugs will happen. The root cause isshown below:    Cleanup Thread               |      Worker Threadsco_sock_release                 |  sco_sock_close                 |    __sco_sock_close             |      sco_sock_set_timer         |        schedule_delayed_work    |  sco_sock_kill                  |    (wait a time)    sock_put(sk) //FREE          |  sco_sock_timeout                                 |    sock_hold(sk) //USEThe KASAN report triggered by POC is shown below:[   95.890016] ==================================================================[   95.890496] BUG: KASAN: slab-use-after-free in sco_sock_timeout+0x5e/0x1c0[   95.890755] Write of size 4 at addr ffff88800c388080 by task kworker/0:0/7...[   95.890755] Workqueue: events sco_sock_timeout[   95.890755] Call Trace:[   95.890755]  TASK[   95.890755]  dump_stack_lvl+0x45/0x110[   95.890755]  print_address_description+0x78/0x390[   95.890755]  print_report+0x11b/0x250[   95.890755]  ? __virt_addr_valid+0xbe/0xf0[   95.890755]  ? sco_sock_timeout+0x5e/0x1c0[   95.890755]  kasan_report+0x139/0x170[   95.890755]  ? update_load_avg+0xe5/0x9f0[   95.890755]  ? sco_sock_timeout+0x5e/0x1c0[   95.890755]  kasan_check_range+0x2c3/0x2e0[   95.890755]  sco_sock_timeout+0x5e/0x1c0[   95.890755]  process_one_work+0x561/0xc50[   95.890755]  worker_thread+0xab2/0x13c0[   95.890755]  ? pr_cont_work+0x490/0x490[   95.890755]  kthread+0x279/0x300[   95.890755]  ? pr_cont_work+0x490/0x490[   95.890755]  ? kthread_blkcg+0xa0/0xa0[   95.890755]  ret_from_fork+0x34/0x60[   95.890755]  ? kthread_blkcg+0xa0/0xa0[   95.890755]  ret_from_fork_asm+0x11/0x20[   95.890755]  /TASK[   95.890755][   95.890755] Allocated by task 506:[   95.890755]  kasan_save_track+0x3f/0x70[   95.890755]  __kasan_kmalloc+0x86/0x90[   95.890755]  __kmalloc+0x17f/0x360[   95.890755]  sk_prot_alloc+0xe1/0x1a0[   95.890755]  sk_alloc+0x31/0x4e0[   95.890755]  bt_sock_alloc+0x2b/0x2a0[   95.890755]  sco_sock_create+0xad/0x320[   95.890755]  bt_sock_create+0x145/0x320[   95.890755]  __sock_create+0x2e1/0x650[   95.890755]  __sys_socket+0xd0/0x280[   95.890755]  __x64_sys_socket+0x75/0x80[   95.890755]  do_syscall_64+0xc4/0x1b0[   95.890755]  entry_SYSCALL_64_after_hwframe+0x67/0x6f[   95.890755][   95.890755] Freed by task 506:[   95.890755]  kasan_save_track+0x3f/0x70[   95.890755]  kasan_save_free_info+0x40/0x50[   95.890755]  poison_slab_object+0x118/0x180[   95.890755]  __kasan_slab_free+0x12/0x30[   95.890755]  kfree+0xb2/0x240[   95.890755]  __sk_destruct+0x317/0x410[   95.890755]  sco_sock_release+0x232/0x280[   95.890755]  sock_close+0xb2/0x210[   95.890755]  __fput+0x37f/0x770[   95.890755]  task_work_run+0x1ae/0x210[   95.890755]  get_signal+0xe17/0xf70[   95.890755]  arch_do_signal_or_restart+0x3f/0x520[   95.890755]  syscall_exit_to_user_mode+0x55/0x120[   95.890755]  do_syscall_64+0xd1/0x1b0[   95.890755]  entry_SYSCALL_64_after_hwframe+0x67/0x6f[   95.890755][   95.890755] The buggy address belongs to the object at ffff88800c388000[   95.890755]  which belongs to the cache kmalloc-1k of size 1024[   95.890755] The buggy address is located 128 bytes inside of[   95.890755]  freed 1024-byte region [ffff88800c388000, ffff88800c388400)[   95.890755][   95.890755] The buggy address belongs to the physical page:[   95.890755] page: refcount:1 mapcount:0 mapping:0000000000000000 index:0xffff88800c38a800 pfn:0xc388[   95.890755] head: order:3 entire_mapcount:0 nr_pages_mapped:0 pincount:0[   95.890755] ano---truncated---

- [https://github.com/secunnix/CVE-2024-27398](https://github.com/secunnix/CVE-2024-27398) :  
![starts](https://img.shields.io/github/stars/secunnix/CVE-2024-27398.svg) 
![forks](https://img.shields.io/github/forks/secunnix/CVE-2024-27398.svg) 
2025-03-15T02:53:56Z

# 2025-03-14
## CVE-2025-28915
 Unrestricted Upload of File with Dangerous Type vulnerability in Theme Egg ThemeEgg ToolKit allows Upload a Web Shell to a Web Server. This issue affects ThemeEgg ToolKit: from n/a through 1.2.9.

- [https://github.com/Nxploited/CVE-2025-28915](https://github.com/Nxploited/CVE-2025-28915) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2025-28915.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2025-28915.svg) 
2025-03-12T03:35:07Z

- [https://github.com/Pei4AN/CVE-2025-28915](https://github.com/Pei4AN/CVE-2025-28915) :  
![starts](https://img.shields.io/github/stars/Pei4AN/CVE-2025-28915.svg) 
![forks](https://img.shields.io/github/forks/Pei4AN/CVE-2025-28915.svg) 
2025-03-14T09:43:59Z

## CVE-2025-27607
 Python JSON Logger is a JSON Formatter for Python Logging. Between 30 December 2024 and 4 March 2025 Python JSON Logger was vulnerable to RCE through a missing dependency. This occurred because msgspec-python313-pre was deleted by the owner leaving the name open to being claimed by a third party. If the package was claimed, it would allow them RCE on any Python JSON Logger user who installed the development dependencies on Python 3.13 (e.g. pip install python-json-logger[dev]). This issue has been resolved with 3.3.0.

- [https://github.com/Barsug/msgspec-python313-pre](https://github.com/Barsug/msgspec-python313-pre) :  
![starts](https://img.shields.io/github/stars/Barsug/msgspec-python313-pre.svg) 
![forks](https://img.shields.io/github/forks/Barsug/msgspec-python313-pre.svg) 
2025-03-14T11:41:48Z

## CVE-2025-25101
 Cross-Site Request Forgery (CSRF) vulnerability in MetricThemes Munk Sites allows Cross Site Request Forgery. This issue affects Munk Sites: from n/a through 1.0.7.

- [https://github.com/Nxploited/CVE-2025-25101](https://github.com/Nxploited/CVE-2025-25101) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2025-25101.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2025-25101.svg) 
2025-03-14T02:55:59Z

## CVE-2025-1094
 Improper neutralization of quoting syntax in PostgreSQL libpq functions PQescapeLiteral(), PQescapeIdentifier(), PQescapeString(), and PQescapeStringConn() allows a database input provider to achieve SQL injection in certain usage patterns.  Specifically, SQL injection requires the application to use the function result to construct input to psql, the PostgreSQL interactive terminal.  Similarly, improper neutralization of quoting syntax in PostgreSQL command line utility programs allows a source of command line arguments to achieve SQL injection when client_encoding is BIG5 and server_encoding is one of EUC_TW or MULE_INTERNAL.  Versions before PostgreSQL 17.3, 16.7, 15.11, 14.16, and 13.19 are affected.

- [https://github.com/soltanali0/CVE-2025-1094-Exploit](https://github.com/soltanali0/CVE-2025-1094-Exploit) :  
![starts](https://img.shields.io/github/stars/soltanali0/CVE-2025-1094-Exploit.svg) 
![forks](https://img.shields.io/github/forks/soltanali0/CVE-2025-1094-Exploit.svg) 
2025-02-27T11:12:44Z

- [https://github.com/shacojx/CVE-2025-1094-Exploit](https://github.com/shacojx/CVE-2025-1094-Exploit) :  
![starts](https://img.shields.io/github/stars/shacojx/CVE-2025-1094-Exploit.svg) 
![forks](https://img.shields.io/github/forks/shacojx/CVE-2025-1094-Exploit.svg) 
2025-03-06T06:40:02Z

- [https://github.com/ishwardeepp/CVE-2025-1094-PoC-Postgre-SQLi](https://github.com/ishwardeepp/CVE-2025-1094-PoC-Postgre-SQLi) :  
![starts](https://img.shields.io/github/stars/ishwardeepp/CVE-2025-1094-PoC-Postgre-SQLi.svg) 
![forks](https://img.shields.io/github/forks/ishwardeepp/CVE-2025-1094-PoC-Postgre-SQLi.svg) 
2025-03-14T22:07:58Z

## CVE-2024-49138
 Windows Common Log File System Driver Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2024-49138-POC](https://github.com/MrAle98/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2024-49138-POC.svg) 
2025-02-14T22:04:41Z

- [https://github.com/bananoname/CVE-2024-49138-POC](https://github.com/bananoname/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/bananoname/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/bananoname/CVE-2024-49138-POC.svg) 
2025-01-21T02:06:00Z

- [https://github.com/DeividasTerechovas/SOC335-CVE-2024-49138-Exploitation-Detected](https://github.com/DeividasTerechovas/SOC335-CVE-2024-49138-Exploitation-Detected) :  
![starts](https://img.shields.io/github/stars/DeividasTerechovas/SOC335-CVE-2024-49138-Exploitation-Detected.svg) 
![forks](https://img.shields.io/github/forks/DeividasTerechovas/SOC335-CVE-2024-49138-Exploitation-Detected.svg) 
2025-03-14T13:10:20Z

## CVE-2024-9513
 A vulnerability was found in Netadmin Software NetAdmin IAM up to 3.5 and classified as problematic. Affected by this issue is some unknown functionality of the file /controller/api/Answer/ReturnUserQuestionsFilled of the component HTTP POST Request Handler. The manipulation of the argument username leads to information exposure through discrepancy. The attack may be launched remotely. The complexity of an attack is rather high. The exploitation is known to be difficult. The exploit has been disclosed to the public and may be used. The vendor was contacted early about this disclosure is planning to release a fix in mid-October 2024.

- [https://github.com/ELIZEUOPAIN/Exploit-CVE-2024-9513-NetAdmin-IAM-Allows-User-Enumeration-In-Active-Directory](https://github.com/ELIZEUOPAIN/Exploit-CVE-2024-9513-NetAdmin-IAM-Allows-User-Enumeration-In-Active-Directory) :  
![starts](https://img.shields.io/github/stars/ELIZEUOPAIN/Exploit-CVE-2024-9513-NetAdmin-IAM-Allows-User-Enumeration-In-Active-Directory.svg) 
![forks](https://img.shields.io/github/forks/ELIZEUOPAIN/Exploit-CVE-2024-9513-NetAdmin-IAM-Allows-User-Enumeration-In-Active-Directory.svg) 
2025-03-14T20:19:20Z

## CVE-2024-0406
 A flaw was discovered in the mholt/archiver package. This flaw allows an attacker to create a specially crafted tar file, which, when unpacked, may allow access to restricted files or directories. This issue can allow the creation or overwriting of files with the user's or application's privileges using the library.

- [https://github.com/walidpyh/CVE-2024-0406-POC](https://github.com/walidpyh/CVE-2024-0406-POC) :  
![starts](https://img.shields.io/github/stars/walidpyh/CVE-2024-0406-POC.svg) 
![forks](https://img.shields.io/github/forks/walidpyh/CVE-2024-0406-POC.svg) 
2025-03-14T20:20:35Z

# 2025-03-13
## CVE-2025-26319
 FlowiseAI Flowise v2.2.6 was discovered to contain an arbitrary file upload vulnerability in /api/v1/attachments.

- [https://github.com/YuoLuo/CVE-2025-26319](https://github.com/YuoLuo/CVE-2025-26319) :  
![starts](https://img.shields.io/github/stars/YuoLuo/CVE-2025-26319.svg) 
![forks](https://img.shields.io/github/forks/YuoLuo/CVE-2025-26319.svg) 
2025-03-13T08:09:43Z

- [https://github.com/dorattias/CVE-2025-26319](https://github.com/dorattias/CVE-2025-26319) :  
![starts](https://img.shields.io/github/stars/dorattias/CVE-2025-26319.svg) 
![forks](https://img.shields.io/github/forks/dorattias/CVE-2025-26319.svg) 
2025-03-06T14:58:35Z

## CVE-2025-1661
 The HUSKY  Products Filter Professional for WooCommerce plugin for WordPress is vulnerable to Local File Inclusion in all versions up to, and including, 1.3.6.5 via the 'template' parameter of the woof_text_search AJAX action. This makes it possible for unauthenticated attackers to include and execute arbitrary files on the server, allowing the execution of any PHP code in those files. This can be used to bypass access controls, obtain sensitive data, or achieve code execution in cases where images and other safe file types can be uploaded and included.

- [https://github.com/gbrsh/CVE-2025-1661](https://github.com/gbrsh/CVE-2025-1661) :  
![starts](https://img.shields.io/github/stars/gbrsh/CVE-2025-1661.svg) 
![forks](https://img.shields.io/github/forks/gbrsh/CVE-2025-1661.svg) 
2025-03-13T13:48:30Z

## CVE-2025-1639
 The Animation Addons for Elementor Pro plugin for WordPress is vulnerable to unauthorized arbitrary plugin installation due to a missing capability check on the install_elementor_plugin_handler() function in all versions up to, and including, 1.6. This makes it possible for authenticated attackers, with Subscriber-level access and above, to install and activate arbitrary plugins which can be leveraged to further infect a victim when Elementor is not activated on a vulnerable site.

- [https://github.com/Nxploited/CVE-2025-1639](https://github.com/Nxploited/CVE-2025-1639) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2025-1639.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2025-1639.svg) 
2025-03-13T10:58:40Z

## CVE-2024-38112
 Windows MSHTML Platform Spoofing Vulnerability

- [https://github.com/Anurag-Chevendra/CVE-2024-38112](https://github.com/Anurag-Chevendra/CVE-2024-38112) :  
![starts](https://img.shields.io/github/stars/Anurag-Chevendra/CVE-2024-38112.svg) 
![forks](https://img.shields.io/github/forks/Anurag-Chevendra/CVE-2024-38112.svg) 
2025-03-13T10:04:11Z

## CVE-2024-38014
 Windows Installer Elevation of Privilege Vulnerability

- [https://github.com/Anurag-Chevendra/CVE-2024-38112](https://github.com/Anurag-Chevendra/CVE-2024-38112) :  
![starts](https://img.shields.io/github/stars/Anurag-Chevendra/CVE-2024-38112.svg) 
![forks](https://img.shields.io/github/forks/Anurag-Chevendra/CVE-2024-38112.svg) 
2025-03-13T10:04:11Z

## CVE-2024-25092
 Missing Authorization vulnerability in XLPlugins NextMove Lite.This issue affects NextMove Lite: from n/a through 2.17.0.

- [https://github.com/RandomRobbieBF/CVE-2024-25092](https://github.com/RandomRobbieBF/CVE-2024-25092) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-25092.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-25092.svg) 
2024-02-14T11:32:33Z

- [https://github.com/Nxploited/CVE-2024-25092](https://github.com/Nxploited/CVE-2024-25092) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-25092.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-25092.svg) 
2025-03-13T11:36:50Z

## CVE-2024-24451
 A stack overflow in the sctp_server::sctp_receiver_thread component of OpenAirInterface CN5G AMF (oai-cn5g-amf) up to v2.0.0 allows attackers to cause a Denial of Service (DoS) by repeatedly establishing SCTP connections with the N2 interface.

- [https://github.com/SpiralBL0CK/CVE-2024-24451](https://github.com/SpiralBL0CK/CVE-2024-24451) :  
![starts](https://img.shields.io/github/stars/SpiralBL0CK/CVE-2024-24451.svg) 
![forks](https://img.shields.io/github/forks/SpiralBL0CK/CVE-2024-24451.svg) 
2025-03-13T21:48:19Z

## CVE-2024-24450
 Stack-based memcpy buffer overflow in the ngap_handle_pdu_session_resource_setup_response routine in OpenAirInterface CN5G AMF = 2.0.0 allows a remote attacker with access to the N2 interface to carry out denial of service against the AMF and potentially execute code by sending a PDU Session Resource Setup Response with a suffciently large FailedToSetupList IE.

- [https://github.com/SpiralBL0CK/-CVE-2024-24450-](https://github.com/SpiralBL0CK/-CVE-2024-24450-) :  
![starts](https://img.shields.io/github/stars/SpiralBL0CK/-CVE-2024-24450-.svg) 
![forks](https://img.shields.io/github/forks/SpiralBL0CK/-CVE-2024-24450-.svg) 
2025-03-13T21:19:11Z

# 2025-03-12
## CVE-2025-27636
 Bypass/Injection vulnerability in Apache Camel components under particular conditions.This issue affects Apache Camel: from 4.10.0 through = 4.10.1, from 4.8.0 through = 4.8.4, from 3.10.0 through = 3.22.3.Users are recommended to upgrade to version 4.10.2 for 4.10.x LTS, 4.8.5 for 4.8.x LTS and 3.22.4 for 3.x releases.This vulnerability is present in Camel's default incoming header filter, that allows an attacker to include Camel specificheaders that for some Camel components can alter the behaviours such as the camel-bean component, to call another methodon the bean, than was coded in the application. In the camel-jms component, then a mallicous header can be used to sendthe message to another queue (on the same broker) than was coded in the application.The attacker would need to inject custom headers, such as HTTP protocols. So if you have Camel applications that aredirectly connected to the internet via HTTP, then an attacker could include malicious HTTP headers in the HTTP requeststhat are send to the Camel application.All the known Camel HTTP component such as camel-servlet, camel-jetty, camel-undertow, camel-platform-http, and camel-netty-http would be vulnerable out of the box.In these conditions an attacker could be able to forge a Camel header name and make the bean component invoking other methods in the same bean.In terms of usage of the default header filter strategy the list of components using that is:   *  camel-activemq  *  camel-activemq6  *  camel-amqp  *  camel-aws2-sqs  *  camel-azure-servicebus  *  camel-cxf-rest  *  camel-cxf-soap  *  camel-http  *  camel-jetty  *  camel-jms  *  camel-kafka  *  camel-knative  *  camel-mail  *  camel-nats  *  camel-netty-http  *  camel-platform-http  *  camel-rest  *  camel-sjms  *  camel-spring-rabbitmq  *  camel-stomp  *  camel-tahu  *  camel-undertow  *  camel-xmppThe vulnerability arises due to a bug in the default filtering mechanism that only blocks headers starting with "Camel", "camel", or "org.apache.camel.".Mitigation:You can easily work around this in your Camel applications by removing theheaders in your Camel routes. There are many ways of doing this, alsoglobally or per route. This means you could use the removeHeaders EIP, to filter out anything like "cAmel, cAMEL" etc, or in general everything not starting with "Camel", "camel" or "org.apache.camel.".

- [https://github.com/akamai/CVE-2025-27636-Apache-Camel-PoC](https://github.com/akamai/CVE-2025-27636-Apache-Camel-PoC) :  
![starts](https://img.shields.io/github/stars/akamai/CVE-2025-27636-Apache-Camel-PoC.svg) 
![forks](https://img.shields.io/github/forks/akamai/CVE-2025-27636-Apache-Camel-PoC.svg) 
2025-03-12T19:06:26Z

## CVE-2025-26794
 Exim 4.98 before 4.98.1, when SQLite hints and ETRN serialization are used, allows remote SQL injection.

- [https://github.com/OscarBataille/CVE-2025-26794](https://github.com/OscarBataille/CVE-2025-26794) :  
![starts](https://img.shields.io/github/stars/OscarBataille/CVE-2025-26794.svg) 
![forks](https://img.shields.io/github/forks/OscarBataille/CVE-2025-26794.svg) 
2025-03-12T10:56:41Z

- [https://github.com/ishwardeepp/CVE-2025-26794-Exim-Mail-SQLi](https://github.com/ishwardeepp/CVE-2025-26794-Exim-Mail-SQLi) :  
![starts](https://img.shields.io/github/stars/ishwardeepp/CVE-2025-26794-Exim-Mail-SQLi.svg) 
![forks](https://img.shields.io/github/forks/ishwardeepp/CVE-2025-26794-Exim-Mail-SQLi.svg) 
2025-03-05T07:39:12Z

## CVE-2025-2233
 Samsung SmartThings Improper Verification of Cryptographic Signature Authentication Bypass Vulnerability. This vulnerability allows network-adjacent attackers to bypass authentication on affected installations of Samsung SmartThings. Authentication is not required to exploit this vulnerability.The specific flaw exists within the Hub Local API service, which listens on TCP port 8766 by default. The issue results from the lack of proper verification of a cryptographic signature. An attacker can leverage this vulnerability to bypass authentication on the system. Was ZDI-CAN-25615.

- [https://github.com/McTavishSue/CVE-2025-2233](https://github.com/McTavishSue/CVE-2025-2233) :  
![starts](https://img.shields.io/github/stars/McTavishSue/CVE-2025-2233.svg) 
![forks](https://img.shields.io/github/forks/McTavishSue/CVE-2025-2233.svg) 
2025-03-12T09:04:07Z

## CVE-2024-55060
 A cross-site scripting (XSS) vulnerability in the component index.php of Rafed CMS Website v1.44 allows attackers to execute arbitrary web scripts or HTML via a crafted payload.

- [https://github.com/bigzooooz/CVE-2024-55060](https://github.com/bigzooooz/CVE-2024-55060) :  
![starts](https://img.shields.io/github/stars/bigzooooz/CVE-2024-55060.svg) 
![forks](https://img.shields.io/github/forks/bigzooooz/CVE-2024-55060.svg) 
2025-03-12T18:07:37Z

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

- [https://github.com/dkstar11q/CVE-2024-50379-nuclei](https://github.com/dkstar11q/CVE-2024-50379-nuclei) :  
![starts](https://img.shields.io/github/stars/dkstar11q/CVE-2024-50379-nuclei.svg) 
![forks](https://img.shields.io/github/forks/dkstar11q/CVE-2024-50379-nuclei.svg) 
2024-12-25T21:51:37Z

- [https://github.com/YuoLuo/tomcat_cve_2024_50379_exploit](https://github.com/YuoLuo/tomcat_cve_2024_50379_exploit) :  
![starts](https://img.shields.io/github/stars/YuoLuo/tomcat_cve_2024_50379_exploit.svg) 
![forks](https://img.shields.io/github/forks/YuoLuo/tomcat_cve_2024_50379_exploit.svg) 
2025-03-12T06:18:27Z

## CVE-2024-30485
 Missing Authorization vulnerability in XLPlugins Finale Lite.This issue affects Finale Lite: from n/a through 2.18.0.

- [https://github.com/Nxploited/CVE-2024-30485](https://github.com/Nxploited/CVE-2024-30485) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-30485.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-30485.svg) 
2025-03-12T17:23:44Z

## CVE-2024-26229
 Windows CSC Service Elevation of Privilege Vulnerability

- [https://github.com/varwara/CVE-2024-26229](https://github.com/varwara/CVE-2024-26229) :  
![starts](https://img.shields.io/github/stars/varwara/CVE-2024-26229.svg) 
![forks](https://img.shields.io/github/forks/varwara/CVE-2024-26229.svg) 
2024-07-04T10:39:15Z

- [https://github.com/RalfHacker/CVE-2024-26229-exploit](https://github.com/RalfHacker/CVE-2024-26229-exploit) :  
![starts](https://img.shields.io/github/stars/RalfHacker/CVE-2024-26229-exploit.svg) 
![forks](https://img.shields.io/github/forks/RalfHacker/CVE-2024-26229-exploit.svg) 
2024-06-11T20:41:59Z

- [https://github.com/Cracked5pider/eop24-26229](https://github.com/Cracked5pider/eop24-26229) :  
![starts](https://img.shields.io/github/stars/Cracked5pider/eop24-26229.svg) 
![forks](https://img.shields.io/github/forks/Cracked5pider/eop24-26229.svg) 
2024-08-15T10:48:05Z

- [https://github.com/apkc/CVE-2024-26229-BOF](https://github.com/apkc/CVE-2024-26229-BOF) :  
![starts](https://img.shields.io/github/stars/apkc/CVE-2024-26229-BOF.svg) 
![forks](https://img.shields.io/github/forks/apkc/CVE-2024-26229-BOF.svg) 
2024-06-13T07:30:48Z

- [https://github.com/team-MineDEV/CVE-2024-26229](https://github.com/team-MineDEV/CVE-2024-26229) :  
![starts](https://img.shields.io/github/stars/team-MineDEV/CVE-2024-26229.svg) 
![forks](https://img.shields.io/github/forks/team-MineDEV/CVE-2024-26229.svg) 
2024-06-16T05:29:26Z

- [https://github.com/mqxmm/CVE-2024-26229](https://github.com/mqxmm/CVE-2024-26229) :  
![starts](https://img.shields.io/github/stars/mqxmm/CVE-2024-26229.svg) 
![forks](https://img.shields.io/github/forks/mqxmm/CVE-2024-26229.svg) 
2024-10-13T12:11:21Z

- [https://github.com/shinspace92/cve-2024-26229](https://github.com/shinspace92/cve-2024-26229) :  
![starts](https://img.shields.io/github/stars/shinspace92/cve-2024-26229.svg) 
![forks](https://img.shields.io/github/forks/shinspace92/cve-2024-26229.svg) 
2025-03-12T20:21:27Z

## CVE-2024-25600
 Improper Control of Generation of Code ('Code Injection') vulnerability in Codeer Limited Bricks Builder allows Code Injection.This issue affects Bricks Builder: from n/a through 1.9.6.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-12T12:11:34Z

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

- [https://github.com/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress](https://github.com/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress) :  
![starts](https://img.shields.io/github/stars/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress.svg) 
![forks](https://img.shields.io/github/forks/ivanbg2004/0BL1V10N-CVE-2024-25600-Bricks-Builder-plugin-for-WordPress.svg) 
2024-06-02T11:12:04Z

- [https://github.com/hy011121/CVE-2024-25600-wordpress-Exploit-RCE](https://github.com/hy011121/CVE-2024-25600-wordpress-Exploit-RCE) :  
![starts](https://img.shields.io/github/stars/hy011121/CVE-2024-25600-wordpress-Exploit-RCE.svg) 
![forks](https://img.shields.io/github/forks/hy011121/CVE-2024-25600-wordpress-Exploit-RCE.svg) 
2024-02-29T21:04:40Z

- [https://github.com/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE](https://github.com/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE) :  
![starts](https://img.shields.io/github/stars/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE.svg) 
![forks](https://img.shields.io/github/forks/X-Projetion/WORDPRESS-CVE-2024-25600-EXPLOIT-RCE.svg) 
2024-04-20T06:37:22Z

- [https://github.com/k3lpi3b4nsh33/CVE-2024-25600](https://github.com/k3lpi3b4nsh33/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/k3lpi3b4nsh33/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/k3lpi3b4nsh33/CVE-2024-25600.svg) 
2024-06-06T02:36:34Z

- [https://github.com/WanLiChangChengWanLiChang/CVE-2024-25600](https://github.com/WanLiChangChengWanLiChang/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/WanLiChangChengWanLiChang/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/WanLiChangChengWanLiChang/CVE-2024-25600.svg) 
2024-06-07T17:15:43Z

- [https://github.com/wh6amiGit/CVE-2024-25600](https://github.com/wh6amiGit/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/wh6amiGit/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/wh6amiGit/CVE-2024-25600.svg) 
2024-08-20T13:57:56Z

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
2025-03-12T12:11:34Z

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

- [https://github.com/AiK1d/CVE-2024-23897](https://github.com/AiK1d/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/AiK1d/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/AiK1d/CVE-2024-23897.svg) 
2024-01-27T13:10:37Z

- [https://github.com/jenkinsci-cert/SECURITY-3314-3315](https://github.com/jenkinsci-cert/SECURITY-3314-3315) :  
![starts](https://img.shields.io/github/stars/jenkinsci-cert/SECURITY-3314-3315.svg) 
![forks](https://img.shields.io/github/forks/jenkinsci-cert/SECURITY-3314-3315.svg) 
2024-02-20T14:13:25Z

- [https://github.com/verylazytech/CVE-2024-23897](https://github.com/verylazytech/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-23897.svg) 
2024-11-26T14:46:59Z

- [https://github.com/Maalfer/CVE-2024-23897](https://github.com/Maalfer/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/Maalfer/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/Maalfer/CVE-2024-23897.svg) 
2024-05-17T11:54:26Z

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

- [https://github.com/ThatNotEasy/CVE-2024-23897](https://github.com/ThatNotEasy/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-23897.svg) 
2024-03-02T07:55:22Z

- [https://github.com/yoryio/CVE-2024-23897](https://github.com/yoryio/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2024-23897.svg) 
2024-03-13T05:52:30Z

- [https://github.com/vmtyan/poc-cve-2024-23897](https://github.com/vmtyan/poc-cve-2024-23897) :  
![starts](https://img.shields.io/github/stars/vmtyan/poc-cve-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/vmtyan/poc-cve-2024-23897.svg) 
2024-01-26T21:46:10Z

- [https://github.com/Anekant-Singhai/Exploits](https://github.com/Anekant-Singhai/Exploits) :  
![starts](https://img.shields.io/github/stars/Anekant-Singhai/Exploits.svg) 
![forks](https://img.shields.io/github/forks/Anekant-Singhai/Exploits.svg) 
2024-05-04T13:25:52Z

- [https://github.com/JAthulya/CVE-2024-23897](https://github.com/JAthulya/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/JAthulya/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/JAthulya/CVE-2024-23897.svg) 
2024-05-03T08:33:11Z

- [https://github.com/jopraveen/CVE-2024-23897](https://github.com/jopraveen/CVE-2024-23897) :  
![starts](https://img.shields.io/github/stars/jopraveen/CVE-2024-23897.svg) 
![forks](https://img.shields.io/github/forks/jopraveen/CVE-2024-23897.svg) 
2024-01-29T12:14:08Z

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
2025-03-12T12:11:34Z

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
2025-03-12T12:11:34Z

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

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

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
2025-03-12T12:11:34Z

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

## CVE-2024-10674
 The Th Shop Mania theme for WordPress is vulnerable to unauthorized arbitrary plugin installation due to a missing capability check on the th_shop_mania_install_and_activate_callback() function in all versions up to, and including, 1.4.9. This makes it possible for authenticated attackers, with Subscriber-level access and above, to install arbitrary plugins which can be leveraged to exploit other vulnerabilities and achieve remote code execution and privilege escalation.

- [https://github.com/Nxploited/CVE-2024-10674](https://github.com/Nxploited/CVE-2024-10674) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-10674.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-10674.svg) 
2025-03-12T21:05:34Z

## CVE-2024-10673
 The Top Store theme for WordPress is vulnerable to unauthorized arbitrary plugin installation due to a missing capability check on the top_store_install_and_activate_callback() function in all versions up to, and including, 1.5.4. This makes it possible for authenticated attackers, with subscriber-level access and above, to install arbitrary plugins which can contain other exploitable vulnerabilities to elevate privileges and gain remote code execution.

- [https://github.com/Nxploited/CVE-2024-10673](https://github.com/Nxploited/CVE-2024-10673) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-10673.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-10673.svg) 
2025-03-12T06:44:38Z

## CVE-2024-0760
 A malicious client can send many DNS messages over TCP, potentially causing the server to become unstable while the attack is in progress. The server may recover after the attack ceases. Use of ACLs will not mitigate the attack. This issue affects BIND 9 versions 9.18.1 through 9.18.27, 9.19.0 through 9.19.24, and 9.18.11-S1 through 9.18.27-S1.

- [https://github.com/SpiralBL0CK/CVE-2024-0760](https://github.com/SpiralBL0CK/CVE-2024-0760) :  
![starts](https://img.shields.io/github/stars/SpiralBL0CK/CVE-2024-0760.svg) 
![forks](https://img.shields.io/github/forks/SpiralBL0CK/CVE-2024-0760.svg) 
2025-03-12T20:51:22Z

## CVE-2024-0204
 Authentication bypass in Fortra's GoAnywhere MFT prior to 7.4.1 allows an unauthorized user to create an admin user via the administration portal.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2025-03-12T12:11:34Z

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

# 2025-03-11
## CVE-2025-27893
 In Archer Platform 6 through 6.14.00202.10024, an authenticated user with record creation privileges can manipulate immutable fields, such as the creation date, by intercepting and modifying a Copy request via a GenericContent/Record.aspx?id= URI. This enables unauthorized modification of system-generated metadata, compromising data integrity and potentially impacting auditing, compliance, and security controls.

- [https://github.com/NastyCrow/CVE-2025-27893](https://github.com/NastyCrow/CVE-2025-27893) :  
![starts](https://img.shields.io/github/stars/NastyCrow/CVE-2025-27893.svg) 
![forks](https://img.shields.io/github/forks/NastyCrow/CVE-2025-27893.svg) 
2025-03-11T10:40:40Z

## CVE-2024-54383
 Incorrect Privilege Assignment vulnerability in wpweb WooCommerce PDF Vouchers allows Privilege Escalation.This issue affects WooCommerce PDF Vouchers: from n/a before 4.9.9.

- [https://github.com/pashayogi/CVE-2024-54383](https://github.com/pashayogi/CVE-2024-54383) :  
![starts](https://img.shields.io/github/stars/pashayogi/CVE-2024-54383.svg) 
![forks](https://img.shields.io/github/forks/pashayogi/CVE-2024-54383.svg) 
2025-03-11T14:26:59Z

## CVE-2024-49019
 Active Directory Certificate Services Elevation of Privilege Vulnerability

- [https://github.com/rayngnpc/CVE-2024-49019-rayng](https://github.com/rayngnpc/CVE-2024-49019-rayng) :  
![starts](https://img.shields.io/github/stars/rayngnpc/CVE-2024-49019-rayng.svg) 
![forks](https://img.shields.io/github/forks/rayngnpc/CVE-2024-49019-rayng.svg) 
2025-03-11T16:41:18Z

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
2025-03-11T02:01:55Z

## CVE-2024-34370
 Improper Privilege Management vulnerability in WPFactory EAN for WooCommerce allows Privilege Escalation.This issue affects EAN for WooCommerce: from n/a through 4.8.9.

- [https://github.com/pashayogi/CVE-2024-34370](https://github.com/pashayogi/CVE-2024-34370) :  
![starts](https://img.shields.io/github/stars/pashayogi/CVE-2024-34370.svg) 
![forks](https://img.shields.io/github/forks/pashayogi/CVE-2024-34370.svg) 
2025-03-11T16:35:40Z

- [https://github.com/Akshath-Nagulapally/ReproducingCVEs_Akshath_Nagulapally](https://github.com/Akshath-Nagulapally/ReproducingCVEs_Akshath_Nagulapally) :  
![starts](https://img.shields.io/github/stars/Akshath-Nagulapally/ReproducingCVEs_Akshath_Nagulapally.svg) 
![forks](https://img.shields.io/github/forks/Akshath-Nagulapally/ReproducingCVEs_Akshath_Nagulapally.svg) 
2024-08-20T21:27:50Z

## CVE-2024-23346
 Pymatgen (Python Materials Genomics) is an open-source Python library for materials analysis. A critical security vulnerability exists in the `JonesFaithfulTransformation.from_transformation_str()` method within the `pymatgen` library prior to version 2024.2.20. This method insecurely utilizes `eval()` for processing input, enabling execution of arbitrary code when parsing untrusted input. Version 2024.2.20 fixes this issue.

- [https://github.com/9carlo6/CVE-2024-23346](https://github.com/9carlo6/CVE-2024-23346) :  
![starts](https://img.shields.io/github/stars/9carlo6/CVE-2024-23346.svg) 
![forks](https://img.shields.io/github/forks/9carlo6/CVE-2024-23346.svg) 
2025-03-11T11:42:52Z

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

## CVE-2024-12365
 The W3 Total Cache plugin for WordPress is vulnerable to unauthorized access of data due to a missing capability check on the is_w3tc_admin_page function in all versions up to, and including, 2.8.1. This makes it possible for authenticated attackers, with Subscriber-level access and above, to obtain the plugin's nonce value and perform unauthorized actions, resulting in information disclosure, service plan limits consumption as well as making web requests to arbitrary locations originating from the web application that can be used to query information from internal services, including instance metadata on cloud-based applications.

- [https://github.com/spyata123/W3TotalChache](https://github.com/spyata123/W3TotalChache) :  
![starts](https://img.shields.io/github/stars/spyata123/W3TotalChache.svg) 
![forks](https://img.shields.io/github/forks/spyata123/W3TotalChache.svg) 
2025-03-11T13:40:16Z

## CVE-2024-12008
 The W3 Total Cache plugin for WordPress is vulnerable to Information Exposure in all versions up to, and including, 2.8.1 through the publicly exposed debug log file. This makes it possible for unauthenticated attackers to view potentially sensitive information in the exposed log file. For example, the log file may contain nonce values that can be used in further CSRF attacks.Note: the debug feature must be enabled for this to be a concern, and it is disabled by default.

- [https://github.com/spyata123/CVE-2024-12008-information-exposure-vulnerability-in-W3-Total-Cache](https://github.com/spyata123/CVE-2024-12008-information-exposure-vulnerability-in-W3-Total-Cache) :  
![starts](https://img.shields.io/github/stars/spyata123/CVE-2024-12008-information-exposure-vulnerability-in-W3-Total-Cache.svg) 
![forks](https://img.shields.io/github/forks/spyata123/CVE-2024-12008-information-exposure-vulnerability-in-W3-Total-Cache.svg) 
2025-03-11T14:05:01Z

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

- [https://github.com/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB](https://github.com/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB) :  
![starts](https://img.shields.io/github/stars/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB.svg) 
![forks](https://img.shields.io/github/forks/D1se0/CVE-2024-10924-Bypass-MFA-Wordpress-LAB.svg) 
2024-12-02T08:32:47Z

- [https://github.com/Trackflaw/CVE-2024-10924-Wordpress-Docker](https://github.com/Trackflaw/CVE-2024-10924-Wordpress-Docker) :  
![starts](https://img.shields.io/github/stars/Trackflaw/CVE-2024-10924-Wordpress-Docker.svg) 
![forks](https://img.shields.io/github/forks/Trackflaw/CVE-2024-10924-Wordpress-Docker.svg) 
2024-11-22T09:28:08Z

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

- [https://github.com/sharafu-sblsec/CVE-2024-10924](https://github.com/sharafu-sblsec/CVE-2024-10924) :  
![starts](https://img.shields.io/github/stars/sharafu-sblsec/CVE-2024-10924.svg) 
![forks](https://img.shields.io/github/forks/sharafu-sblsec/CVE-2024-10924.svg) 
2025-03-11T15:46:28Z

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

## CVE-2024-9756
 The Order Attachments for WooCommerce plugin for WordPress is vulnerable to unauthorized limited arbitrary file uploads due to a missing capability check on the wcoa_add_attachment AJAX action in versions 2.0 to 2.4.1. This makes it possible for authenticated attackers, with subscriber-level access and above, to upload limited file types.

- [https://github.com/Nxploited/CVE-2024-9756](https://github.com/Nxploited/CVE-2024-9756) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-9756.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-9756.svg) 
2025-03-11T02:06:59Z

## CVE-2024-8289
 The MultiVendorX  The Ultimate WooCommerce Multivendor Marketplace Solution plugin for WordPress is vulnerable to privilege escalation/de-escalation and account takeover due to an insufficient capability check on the update_item_permissions_check and create_item_permissions_check functions in all versions up to, and including, 4.2.0. This makes it possible for unauthenticated attackers to change the password of any user with the vendor role, create new users with the vendor role, and demote other users like administrators to the vendor role.

- [https://github.com/pashayogi/CVE-2024-8289](https://github.com/pashayogi/CVE-2024-8289) :  
![starts](https://img.shields.io/github/stars/pashayogi/CVE-2024-8289.svg) 
![forks](https://img.shields.io/github/forks/pashayogi/CVE-2024-8289.svg) 
2025-03-11T14:06:15Z

## CVE-2024-6132
 The Pexels: Free Stock Photos plugin for WordPress is vulnerable to arbitrary file uploads due to missing file type validation in the 'pexels_fsp_images_options_validate' function in all versions up to, and including, 1.2.2. This makes it possible for authenticated attackers, with contributor-level and above permissions, to upload arbitrary files on the affected site's server which may make remote code execution possible.

- [https://github.com/Nxploited/CVE-2024-6132](https://github.com/Nxploited/CVE-2024-6132) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-6132.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-6132.svg) 
2025-03-11T11:28:17Z

# 2025-03-10
## CVE-2025-21293
 Active Directory Domain Services Elevation of Privilege Vulnerability

- [https://github.com/ahmedumarehman/CVE-2025-21293](https://github.com/ahmedumarehman/CVE-2025-21293) :  
![starts](https://img.shields.io/github/stars/ahmedumarehman/CVE-2025-21293.svg) 
![forks](https://img.shields.io/github/forks/ahmedumarehman/CVE-2025-21293.svg) 
2025-03-10T20:58:44Z

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

- [https://github.com/AnonStorks/CVE-2025-0282-Full-version](https://github.com/AnonStorks/CVE-2025-0282-Full-version) :  
![starts](https://img.shields.io/github/stars/AnonStorks/CVE-2025-0282-Full-version.svg) 
![forks](https://img.shields.io/github/forks/AnonStorks/CVE-2025-0282-Full-version.svg) 
2025-01-12T12:15:44Z

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

- [https://github.com/AdaniKamal/CVE-2025-0282](https://github.com/AdaniKamal/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/AdaniKamal/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/AdaniKamal/CVE-2025-0282.svg) 
2025-01-28T08:46:44Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

- [https://github.com/almanatra/CVE-2025-0282](https://github.com/almanatra/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/almanatra/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/almanatra/CVE-2025-0282.svg) 
2025-01-22T08:25:22Z

- [https://github.com/44xo/CVE-2025-0282](https://github.com/44xo/CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/44xo/CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/44xo/CVE-2025-0282.svg) 
2025-02-25T16:45:32Z

- [https://github.com/punitdarji/Ivanti-CVE-2025-0282](https://github.com/punitdarji/Ivanti-CVE-2025-0282) :  
![starts](https://img.shields.io/github/stars/punitdarji/Ivanti-CVE-2025-0282.svg) 
![forks](https://img.shields.io/github/forks/punitdarji/Ivanti-CVE-2025-0282.svg) 
2025-03-10T21:36:06Z

# 2025-03-09
## CVE-2025-27840
 Espressif ESP32 chips allow 29 hidden HCI commands, such as 0xFC02 (Write memory).

- [https://github.com/em0gi/CVE-2025-27840](https://github.com/em0gi/CVE-2025-27840) :  
![starts](https://img.shields.io/github/stars/em0gi/CVE-2025-27840.svg) 
![forks](https://img.shields.io/github/forks/em0gi/CVE-2025-27840.svg) 
2025-03-09T16:16:50Z

## CVE-2025-1316
 Edimax IC-7100 does not properly neutralize requests. An attacker can create specially crafted requests to achieve remote code execution on the device

- [https://github.com/Rimasue/CVE-2025-1316](https://github.com/Rimasue/CVE-2025-1316) :  
![starts](https://img.shields.io/github/stars/Rimasue/CVE-2025-1316.svg) 
![forks](https://img.shields.io/github/forks/Rimasue/CVE-2025-1316.svg) 
2025-03-09T11:06:41Z

## CVE-2024-45436
 extractFromZipFile in model.go in Ollama before 0.1.47 can extract members of a ZIP archive outside of the parent directory.

- [https://github.com/XiaomingX/cve-2024-45436-exp](https://github.com/XiaomingX/cve-2024-45436-exp) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-45436-exp.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-45436-exp.svg) 
2024-11-21T09:08:28Z

- [https://github.com/pankass/CVE-2024-37032_CVE-2024-45436](https://github.com/pankass/CVE-2024-37032_CVE-2024-45436) :  
![starts](https://img.shields.io/github/stars/pankass/CVE-2024-37032_CVE-2024-45436.svg) 
![forks](https://img.shields.io/github/forks/pankass/CVE-2024-37032_CVE-2024-45436.svg) 
2025-03-09T11:38:42Z

## CVE-2024-37032
 Ollama before 0.1.34 does not validate the format of the digest (sha256 with 64 hex digits) when getting the model path, and thus mishandles the TestGetBlobsPath test cases such as fewer than 64 hex digits, more than 64 hex digits, or an initial ../ substring.

- [https://github.com/Bi0x/CVE-2024-37032](https://github.com/Bi0x/CVE-2024-37032) :  
![starts](https://img.shields.io/github/stars/Bi0x/CVE-2024-37032.svg) 
![forks](https://img.shields.io/github/forks/Bi0x/CVE-2024-37032.svg) 
2024-06-28T03:14:05Z

- [https://github.com/pankass/CVE-2024-37032_CVE-2024-45436](https://github.com/pankass/CVE-2024-37032_CVE-2024-45436) :  
![starts](https://img.shields.io/github/stars/pankass/CVE-2024-37032_CVE-2024-45436.svg) 
![forks](https://img.shields.io/github/forks/pankass/CVE-2024-37032_CVE-2024-45436.svg) 
2025-03-09T11:38:42Z

- [https://github.com/ahboon/CVE-2024-37032-scanner](https://github.com/ahboon/CVE-2024-37032-scanner) :  
![starts](https://img.shields.io/github/stars/ahboon/CVE-2024-37032-scanner.svg) 
![forks](https://img.shields.io/github/forks/ahboon/CVE-2024-37032-scanner.svg) 
2024-07-10T07:26:21Z

## CVE-2024-10629
 The GPX Viewer plugin for WordPress is vulnerable to arbitrary file creation due to a missing capability check and file type validation in the gpxv_file_upload() function in all versions up to, and including, 2.2.8. This makes it possible for authenticated attackers, with subscriber-level access and above, to create arbitrary files on the affected site's server which may make remote code execution possible.

- [https://github.com/RandomRobbieBF/CVE-2024-10629](https://github.com/RandomRobbieBF/CVE-2024-10629) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-10629.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-10629.svg) 
2024-11-12T16:38:19Z

- [https://github.com/Nxploited/CVE-2024-10629](https://github.com/Nxploited/CVE-2024-10629) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-10629.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-10629.svg) 
2025-03-09T19:42:04Z

# 2025-03-08
## CVE-2024-45519
 The postjournal service in Zimbra Collaboration (ZCS) before 8.8.15 Patch 46, 9 before 9.0.0 Patch 41, 10 before 10.0.9, and 10.1 before 10.1.1 sometimes allows unauthenticated users to execute commands.

- [https://github.com/Chocapikk/CVE-2024-45519](https://github.com/Chocapikk/CVE-2024-45519) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-45519.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-45519.svg) 
2024-11-05T10:10:40Z

- [https://github.com/p33d/CVE-2024-45519](https://github.com/p33d/CVE-2024-45519) :  
![starts](https://img.shields.io/github/stars/p33d/CVE-2024-45519.svg) 
![forks](https://img.shields.io/github/forks/p33d/CVE-2024-45519.svg) 
2024-09-28T08:34:05Z

- [https://github.com/XiaomingX/cve-2024-45519-poc](https://github.com/XiaomingX/cve-2024-45519-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-45519-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-45519-poc.svg) 
2024-11-22T02:00:35Z

- [https://github.com/whiterose7777/CVE-2024-45519](https://github.com/whiterose7777/CVE-2024-45519) :  
![starts](https://img.shields.io/github/stars/whiterose7777/CVE-2024-45519.svg) 
![forks](https://img.shields.io/github/forks/whiterose7777/CVE-2024-45519.svg) 
2024-11-11T08:58:18Z

- [https://github.com/sec13b/CVE-2024-45519](https://github.com/sec13b/CVE-2024-45519) :  
![starts](https://img.shields.io/github/stars/sec13b/CVE-2024-45519.svg) 
![forks](https://img.shields.io/github/forks/sec13b/CVE-2024-45519.svg) 
2025-03-08T20:56:38Z

## CVE-2024-23828
 Nginx-UI is a web interface to manage Nginx configurations. It is vulnerable to an authenticated arbitrary command execution via CRLF attack when changing the value of test_config_cmd or start_cmd. This vulnerability exists due to an incomplete fix for CVE-2024-22197 and CVE-2024-22198. This vulnerability has been patched in version 2.0.0.beta.12.

- [https://github.com/oxagast/oxasploits](https://github.com/oxagast/oxasploits) :  
![starts](https://img.shields.io/github/stars/oxagast/oxasploits.svg) 
![forks](https://img.shields.io/github/forks/oxagast/oxasploits.svg) 
2025-03-08T01:05:29Z

## CVE-2024-5806
 Improper Authentication vulnerability in Progress MOVEit Transfer (SFTP module) can lead to Authentication Bypass.This issue affects MOVEit Transfer: from 2023.0.0 before 2023.0.11, from 2023.1.0 before 2023.1.6, from 2024.0.0 before 2024.0.2.

- [https://github.com/watchtowrlabs/watchTowr-vs-progress-moveit_CVE-2024-5806](https://github.com/watchtowrlabs/watchTowr-vs-progress-moveit_CVE-2024-5806) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/watchTowr-vs-progress-moveit_CVE-2024-5806.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/watchTowr-vs-progress-moveit_CVE-2024-5806.svg) 
2024-06-24T16:52:12Z

- [https://github.com/sec13b/CVE-2024-5806](https://github.com/sec13b/CVE-2024-5806) :  
![starts](https://img.shields.io/github/stars/sec13b/CVE-2024-5806.svg) 
![forks](https://img.shields.io/github/forks/sec13b/CVE-2024-5806.svg) 
2025-03-08T20:54:22Z

