# 2024-12-23
## CVE-2024-56337
 Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability in Apache Tomcat.This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.1, from 10.1.0-M1 through 10.1.33, from 9.0.0.M1 through 9.0.97.The mitigation for CVE-2024-50379 was incomplete.Users running Tomcat on a case insensitive file system with the default servlet write enabled (readonly initialisation parameter set to the non-default value of false) may need additional configuration to fully mitigate CVE-2024-50379 depending on which version of Java they are using with Tomcat:- running on Java 8 or Java 11: the system propertysun.io.useCanonCaches must be explicitly set to false (it defaults to true)- running on Java 17: thesystem property sun.io.useCanonCaches, if set, must be set to false(it defaults to false)- running on Java 21 onwards: no further configuration is required(the system property and the problematic cache have been removed)Tomcat 11.0.3, 10.1.35 and 9.0.99 onwards will include checks thatsun.io.useCanonCaches is set appropriately before allowing the default servlet to be write enabled on a case insensitive file system. Tomcat will also setsun.io.useCanonCaches to false by default where it can.

- [https://github.com/SleepingBag945/CVE-2024-50379](https://github.com/SleepingBag945/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/SleepingBag945/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/SleepingBag945/CVE-2024-50379.svg) 
2024-12-23T07:30:27Z

## CVE-2024-56145
 Craft is a flexible, user-friendly CMS for creating custom digital experiences on the web and beyond. Users of affected versions are affected by this vulnerability if their php.ini configuration has `register_argc_argv` enabled. For these users an unspecified remote code execution vector is present. Users are advised to update to version 3.9.14, 4.13.2, or 5.5.2. Users unable to upgrade should disable `register_argc_argv` to mitigate the issue.

- [https://github.com/Chocapikk/CVE-2024-56145](https://github.com/Chocapikk/CVE-2024-56145) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-56145.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-56145.svg) 
2024-12-23T12:51:54Z

- [https://github.com/Sachinart/CVE-2024-56145-craftcms-rce](https://github.com/Sachinart/CVE-2024-56145-craftcms-rce) :  
![starts](https://img.shields.io/github/stars/Sachinart/CVE-2024-56145-craftcms-rce.svg) 
![forks](https://img.shields.io/github/forks/Sachinart/CVE-2024-56145-craftcms-rce.svg) 
2024-12-22T15:02:07Z

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

- [https://github.com/c4oocO/CVE-2024-53677-Docker](https://github.com/c4oocO/CVE-2024-53677-Docker) :  
![starts](https://img.shields.io/github/stars/c4oocO/CVE-2024-53677-Docker.svg) 
![forks](https://img.shields.io/github/forks/c4oocO/CVE-2024-53677-Docker.svg) 
2024-12-17T07:01:11Z

- [https://github.com/XiaomingX/CVE-2024-53677-S2-067](https://github.com/XiaomingX/CVE-2024-53677-S2-067) :  
![starts](https://img.shields.io/github/stars/XiaomingX/CVE-2024-53677-S2-067.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/CVE-2024-53677-S2-067.svg) 
2024-12-18T02:08:09Z

- [https://github.com/yangyanglo/CVE-2024-53677](https://github.com/yangyanglo/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/yangyanglo/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/yangyanglo/CVE-2024-53677.svg) 
2024-12-17T08:52:36Z

- [https://github.com/dustblessnotdust/CVE-2024-53677-S2-067-thread](https://github.com/dustblessnotdust/CVE-2024-53677-S2-067-thread) :  
![starts](https://img.shields.io/github/stars/dustblessnotdust/CVE-2024-53677-S2-067-thread.svg) 
![forks](https://img.shields.io/github/forks/dustblessnotdust/CVE-2024-53677-S2-067-thread.svg) 
2024-12-18T19:10:48Z

- [https://github.com/0xdeviner/CVE-2024-53677](https://github.com/0xdeviner/CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/0xdeviner/CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/0xdeviner/CVE-2024-53677.svg) 
2024-12-23T14:27:51Z

- [https://github.com/Q0LT/VM-CVE-2024-53677](https://github.com/Q0LT/VM-CVE-2024-53677) :  
![starts](https://img.shields.io/github/stars/Q0LT/VM-CVE-2024-53677.svg) 
![forks](https://img.shields.io/github/forks/Q0LT/VM-CVE-2024-53677.svg) 
2024-12-23T17:31:32Z

## CVE-2024-51228
 An issue in TOTOLINK-CX-A3002RU V1.0.4-B20171106.1512 and TOTOLINK-CX-N150RT V2.1.6-B20171121.1002 and TOTOLINK-CX-N300RT V2.1.6-B20170724.1420 and TOTOLINK-CX-N300RT V2.1.8-B20171113.1408 and TOTOLINK-CX-N300RT V2.1.8-B20191010.1107 and TOTOLINK-CX-N302RE V2.0.2-B20170511.1523 allows a remote attacker to execute arbitrary code via the /boafrm/formSysCmd component.

- [https://github.com/tequilasunsh1ne/CVE_2024_51228](https://github.com/tequilasunsh1ne/CVE_2024_51228) :  
![starts](https://img.shields.io/github/stars/tequilasunsh1ne/CVE_2024_51228.svg) 
![forks](https://img.shields.io/github/forks/tequilasunsh1ne/CVE_2024_51228.svg) 
2024-12-23T02:38:40Z

## CVE-2024-50623
 In Cleo Harmony before 5.8.0.21, VLTrader before 5.8.0.21, and LexiCom before 5.8.0.21, there is an unrestricted file upload and download that could lead to remote code execution.

- [https://github.com/watchtowrlabs/CVE-2024-50623](https://github.com/watchtowrlabs/CVE-2024-50623) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/CVE-2024-50623.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/CVE-2024-50623.svg) 
2024-12-11T14:23:19Z

- [https://github.com/verylazytech/CVE-2024-50623](https://github.com/verylazytech/CVE-2024-50623) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-50623.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-50623.svg) 
2024-12-23T09:16:15Z

## CVE-2024-50379
 Time-of-check Time-of-use (TOCTOU) Race Condition vulnerability during JSP compilation in Apache Tomcat permits an RCE on case insensitive file systems when the default servlet is enabled for write (non-default configuration).This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.1, from 10.1.0-M1 through 10.1.33, from 9.0.0.M1 through 9.0.97.Users are recommended to upgrade to version 11.0.2, 10.1.34 or 9.0.98, which fixes the issue.

- [https://github.com/ph0ebus/Tomcat-CVE-2024-50379-Poc](https://github.com/ph0ebus/Tomcat-CVE-2024-50379-Poc) :  
![starts](https://img.shields.io/github/stars/ph0ebus/Tomcat-CVE-2024-50379-Poc.svg) 
![forks](https://img.shields.io/github/forks/ph0ebus/Tomcat-CVE-2024-50379-Poc.svg) 
2024-12-21T08:56:44Z

- [https://github.com/SleepingBag945/CVE-2024-50379](https://github.com/SleepingBag945/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/SleepingBag945/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/SleepingBag945/CVE-2024-50379.svg) 
2024-12-23T07:30:27Z

- [https://github.com/iSee857/CVE-2024-50379-PoC](https://github.com/iSee857/CVE-2024-50379-PoC) :  
![starts](https://img.shields.io/github/stars/iSee857/CVE-2024-50379-PoC.svg) 
![forks](https://img.shields.io/github/forks/iSee857/CVE-2024-50379-PoC.svg) 
2024-12-20T05:41:23Z

- [https://github.com/yiliufeng168/CVE-2024-50379-POC](https://github.com/yiliufeng168/CVE-2024-50379-POC) :  
![starts](https://img.shields.io/github/stars/yiliufeng168/CVE-2024-50379-POC.svg) 
![forks](https://img.shields.io/github/forks/yiliufeng168/CVE-2024-50379-POC.svg) 
2024-12-18T20:18:39Z

- [https://github.com/JFOZ1010/Nuclei-Template-CVE-2024-50379](https://github.com/JFOZ1010/Nuclei-Template-CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/JFOZ1010/Nuclei-Template-CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/JFOZ1010/Nuclei-Template-CVE-2024-50379.svg) 
2024-12-20T03:54:28Z

- [https://github.com/Alchemist3dot14/CVE-2024-50379](https://github.com/Alchemist3dot14/CVE-2024-50379) :  
![starts](https://img.shields.io/github/stars/Alchemist3dot14/CVE-2024-50379.svg) 
![forks](https://img.shields.io/github/forks/Alchemist3dot14/CVE-2024-50379.svg) 
2024-12-20T21:55:31Z

## CVE-2024-5334
 A local file read vulnerability exists in the stitionai/devika repository, affecting the latest version. The vulnerability is due to improper handling of the 'snapshot_path' parameter in the '/api/get-browser-snapshot' endpoint. An attacker can exploit this vulnerability by crafting a request with a malicious 'snapshot_path' parameter, leading to arbitrary file read from the system. This issue impacts the security of the application by allowing unauthorized access to sensitive files on the server.

- [https://github.com/ShadowByte1/CVE-2024-53345](https://github.com/ShadowByte1/CVE-2024-53345) :  
![starts](https://img.shields.io/github/stars/ShadowByte1/CVE-2024-53345.svg) 
![forks](https://img.shields.io/github/forks/ShadowByte1/CVE-2024-53345.svg) 
2024-12-23T09:10:52Z

## CVE-2024-4824
 Vulnerability in School ERP Pro+Responsive 1.0 that allows SQL injection through the '/SchoolERP/office_admin/' index in the parameters groups_id, examname, classes_id, es_voucherid, es_class, etc. This vulnerability could allow a remote attacker to send a specially crafted SQL query to the server and retrieve all the information stored in the database.

- [https://github.com/ShadowByte1/CVE-2024-48245](https://github.com/ShadowByte1/CVE-2024-48245) :  
![starts](https://img.shields.io/github/stars/ShadowByte1/CVE-2024-48245.svg) 
![forks](https://img.shields.io/github/forks/ShadowByte1/CVE-2024-48245.svg) 
2024-12-23T09:18:35Z

- [https://github.com/ShadowByte1/CVE-2024-48246](https://github.com/ShadowByte1/CVE-2024-48246) :  
![starts](https://img.shields.io/github/stars/ShadowByte1/CVE-2024-48246.svg) 
![forks](https://img.shields.io/github/forks/ShadowByte1/CVE-2024-48246.svg) 
2024-12-23T09:25:39Z

# 2024-12-22
## CVE-2024-38063
 Windows TCP/IP Remote Code Execution Vulnerability

- [https://github.com/ynwarcs/CVE-2024-38063](https://github.com/ynwarcs/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/ynwarcs/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/ynwarcs/CVE-2024-38063.svg) 
2024-08-27T12:22:39Z

- [https://github.com/Sachinart/CVE-2024-38063-poc](https://github.com/Sachinart/CVE-2024-38063-poc) :  
![starts](https://img.shields.io/github/stars/Sachinart/CVE-2024-38063-poc.svg) 
![forks](https://img.shields.io/github/forks/Sachinart/CVE-2024-38063-poc.svg) 
2024-08-28T20:56:40Z

- [https://github.com/patchpoint/CVE-2024-38063](https://github.com/patchpoint/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/patchpoint/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/patchpoint/CVE-2024-38063.svg) 
2024-08-27T17:48:16Z

- [https://github.com/ThemeHackers/CVE-2024-38063](https://github.com/ThemeHackers/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/ThemeHackers/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/ThemeHackers/CVE-2024-38063.svg) 
2024-12-15T05:49:39Z

- [https://github.com/diegoalbuquerque/CVE-2024-38063](https://github.com/diegoalbuquerque/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/diegoalbuquerque/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/diegoalbuquerque/CVE-2024-38063.svg) 
2024-08-15T13:53:45Z

- [https://github.com/zenzue/CVE-2024-38063-POC](https://github.com/zenzue/CVE-2024-38063-POC) :  
![starts](https://img.shields.io/github/stars/zenzue/CVE-2024-38063-POC.svg) 
![forks](https://img.shields.io/github/forks/zenzue/CVE-2024-38063-POC.svg) 
2024-08-28T09:02:59Z

- [https://github.com/KernelKraze/CVE-2024-38063_PoC](https://github.com/KernelKraze/CVE-2024-38063_PoC) :  
![starts](https://img.shields.io/github/stars/KernelKraze/CVE-2024-38063_PoC.svg) 
![forks](https://img.shields.io/github/forks/KernelKraze/CVE-2024-38063_PoC.svg) 
2024-09-08T07:12:26Z

- [https://github.com/haroonawanofficial/CVE-2024-38063-Research-Tool](https://github.com/haroonawanofficial/CVE-2024-38063-Research-Tool) :  
![starts](https://img.shields.io/github/stars/haroonawanofficial/CVE-2024-38063-Research-Tool.svg) 
![forks](https://img.shields.io/github/forks/haroonawanofficial/CVE-2024-38063-Research-Tool.svg) 
2024-08-26T06:18:08Z

- [https://github.com/PumpkinBridge/Windows-CVE-2024-38063](https://github.com/PumpkinBridge/Windows-CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/PumpkinBridge/Windows-CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/PumpkinBridge/Windows-CVE-2024-38063.svg) 
2024-08-28T01:53:43Z

- [https://github.com/thanawee321/CVE-2024-38063](https://github.com/thanawee321/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/thanawee321/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/thanawee321/CVE-2024-38063.svg) 
2024-10-18T11:48:06Z

- [https://github.com/Th3Tr1ckst3r/CVE-2024-38063](https://github.com/Th3Tr1ckst3r/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/Th3Tr1ckst3r/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/Th3Tr1ckst3r/CVE-2024-38063.svg) 
2024-08-30T22:18:44Z

- [https://github.com/Th3Tr1ckst3r/Exip6](https://github.com/Th3Tr1ckst3r/Exip6) :  
![starts](https://img.shields.io/github/stars/Th3Tr1ckst3r/Exip6.svg) 
![forks](https://img.shields.io/github/forks/Th3Tr1ckst3r/Exip6.svg) 
2024-09-13T09:14:00Z

- [https://github.com/Faizan-Khanx/CVE-2024-38063](https://github.com/Faizan-Khanx/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/Faizan-Khanx/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/Faizan-Khanx/CVE-2024-38063.svg) 
2024-09-10T10:19:14Z

- [https://github.com/becrevex/CVE-2024-38063](https://github.com/becrevex/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/becrevex/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/becrevex/CVE-2024-38063.svg) 
2024-11-16T06:07:24Z

- [https://github.com/Dragkob/CVE-2024-38063](https://github.com/Dragkob/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/Dragkob/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/Dragkob/CVE-2024-38063.svg) 
2024-11-20T13:18:16Z

- [https://github.com/AdminPentester/CVE-2024-38063-](https://github.com/AdminPentester/CVE-2024-38063-) :  
![starts](https://img.shields.io/github/stars/AdminPentester/CVE-2024-38063-.svg) 
![forks](https://img.shields.io/github/forks/AdminPentester/CVE-2024-38063-.svg) 
2024-08-30T01:27:16Z

- [https://github.com/zaneoblaneo/cve_2024_38063_research](https://github.com/zaneoblaneo/cve_2024_38063_research) :  
![starts](https://img.shields.io/github/stars/zaneoblaneo/cve_2024_38063_research.svg) 
![forks](https://img.shields.io/github/forks/zaneoblaneo/cve_2024_38063_research.svg) 
2024-08-22T08:13:16Z

- [https://github.com/noradlb1/CVE-2024-38063-VB](https://github.com/noradlb1/CVE-2024-38063-VB) :  
![starts](https://img.shields.io/github/stars/noradlb1/CVE-2024-38063-VB.svg) 
![forks](https://img.shields.io/github/forks/noradlb1/CVE-2024-38063-VB.svg) 
2024-08-17T01:20:02Z

- [https://github.com/ArenaldyP/CVE-2024-38063-Medium](https://github.com/ArenaldyP/CVE-2024-38063-Medium) :  
![starts](https://img.shields.io/github/stars/ArenaldyP/CVE-2024-38063-Medium.svg) 
![forks](https://img.shields.io/github/forks/ArenaldyP/CVE-2024-38063-Medium.svg) 
2024-09-22T16:03:45Z

- [https://github.com/ps-interactive/cve-2024-38063](https://github.com/ps-interactive/cve-2024-38063) :  
![starts](https://img.shields.io/github/stars/ps-interactive/cve-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/ps-interactive/cve-2024-38063.svg) 
2024-09-02T14:16:52Z

- [https://github.com/lnx-dvlpr/cve-2024-38063](https://github.com/lnx-dvlpr/cve-2024-38063) :  
![starts](https://img.shields.io/github/stars/lnx-dvlpr/cve-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/lnx-dvlpr/cve-2024-38063.svg) 
2024-09-25T12:01:14Z

- [https://github.com/selenagomez25/CVE-2024-38063](https://github.com/selenagomez25/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/selenagomez25/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/selenagomez25/CVE-2024-38063.svg) 
2024-11-18T15:21:09Z

- [https://github.com/p33d/cve-2024-38063](https://github.com/p33d/cve-2024-38063) :  
![starts](https://img.shields.io/github/stars/p33d/cve-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/p33d/cve-2024-38063.svg) 
2024-08-18T22:24:43Z

- [https://github.com/Brownpanda29/Cve-2024-38063](https://github.com/Brownpanda29/Cve-2024-38063) :  
![starts](https://img.shields.io/github/stars/Brownpanda29/Cve-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/Brownpanda29/Cve-2024-38063.svg) 
2024-09-03T14:59:39Z

- [https://github.com/idkwastaken/CVE-2024-38063](https://github.com/idkwastaken/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/idkwastaken/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/idkwastaken/CVE-2024-38063.svg) 
2024-10-14T17:59:56Z

- [https://github.com/jamesbishop785/CVE-2024-38063](https://github.com/jamesbishop785/CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/jamesbishop785/CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/jamesbishop785/CVE-2024-38063.svg) 
2024-12-22T06:27:08Z

- [https://github.com/Laukage/Windows-CVE-2024-38063](https://github.com/Laukage/Windows-CVE-2024-38063) :  
![starts](https://img.shields.io/github/stars/Laukage/Windows-CVE-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/Laukage/Windows-CVE-2024-38063.svg) 
2024-12-06T22:54:01Z

- [https://github.com/dweger-scripts/CVE-2024-38063-Remediation](https://github.com/dweger-scripts/CVE-2024-38063-Remediation) :  
![starts](https://img.shields.io/github/stars/dweger-scripts/CVE-2024-38063-Remediation.svg) 
![forks](https://img.shields.io/github/forks/dweger-scripts/CVE-2024-38063-Remediation.svg) 
2024-08-21T14:58:48Z

- [https://github.com/AliHj98/cve-2024-38063-Anonyvader](https://github.com/AliHj98/cve-2024-38063-Anonyvader) :  
![starts](https://img.shields.io/github/stars/AliHj98/cve-2024-38063-Anonyvader.svg) 
![forks](https://img.shields.io/github/forks/AliHj98/cve-2024-38063-Anonyvader.svg) 
2024-11-07T10:47:48Z

- [https://github.com/FrancescoDiSalesGithub/quick-fix-cve-2024-38063](https://github.com/FrancescoDiSalesGithub/quick-fix-cve-2024-38063) :  
![starts](https://img.shields.io/github/stars/FrancescoDiSalesGithub/quick-fix-cve-2024-38063.svg) 
![forks](https://img.shields.io/github/forks/FrancescoDiSalesGithub/quick-fix-cve-2024-38063.svg) 
2024-09-08T08:59:29Z

- [https://github.com/almogopp/Disable-IPv6-CVE-2024-38063-Fix](https://github.com/almogopp/Disable-IPv6-CVE-2024-38063-Fix) :  
![starts](https://img.shields.io/github/stars/almogopp/Disable-IPv6-CVE-2024-38063-Fix.svg) 
![forks](https://img.shields.io/github/forks/almogopp/Disable-IPv6-CVE-2024-38063-Fix.svg) 
2024-08-20T08:50:28Z

## CVE-2024-7481
 Improper verification of cryptographic signature during installation of a Printer driver via the TeamViewer_service.exe component of TeamViewer Remote Clients prior version 15.58.4 for Windows allows an attacker with local unprivileged access on a Windows system to elevate their privileges and install drivers.

- [https://github.com/PeterGabaldon/CVE-2024-7479_CVE-2024-7481](https://github.com/PeterGabaldon/CVE-2024-7479_CVE-2024-7481) :  
![starts](https://img.shields.io/github/stars/PeterGabaldon/CVE-2024-7479_CVE-2024-7481.svg) 
![forks](https://img.shields.io/github/forks/PeterGabaldon/CVE-2024-7479_CVE-2024-7481.svg) 
2024-12-22T21:34:26Z

## CVE-2024-7479
 Improper verification of cryptographic signature during installation of a VPN driver via the TeamViewer_service.exe component of TeamViewer Remote Clients prior version 15.58.4 for Windows allows an attacker with local unprivileged access on a Windows system to elevate their privileges and install drivers.

- [https://github.com/PeterGabaldon/CVE-2024-7479_CVE-2024-7481](https://github.com/PeterGabaldon/CVE-2024-7479_CVE-2024-7481) :  
![starts](https://img.shields.io/github/stars/PeterGabaldon/CVE-2024-7479_CVE-2024-7481.svg) 
![forks](https://img.shields.io/github/forks/PeterGabaldon/CVE-2024-7479_CVE-2024-7481.svg) 
2024-12-22T21:34:26Z

## CVE-2024-6387
 A security regression (CVE-2006-5051) was discovered in OpenSSH's server (sshd). There is a race condition which can lead sshd to handle some signals in an unsafe manner. An unauthenticated, remote attacker may be able to trigger it by failing to authenticate within a set time period.

- [https://github.com/zgzhang/cve-2024-6387-poc](https://github.com/zgzhang/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/zgzhang/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/zgzhang/cve-2024-6387-poc.svg) 
2024-07-01T10:54:02Z

- [https://github.com/xaitax/CVE-2024-6387_Check](https://github.com/xaitax/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/xaitax/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/xaitax/CVE-2024-6387_Check.svg) 
2024-09-24T19:18:56Z

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

- [https://github.com/l0n3m4n/CVE-2024-6387](https://github.com/l0n3m4n/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/l0n3m4n/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/l0n3m4n/CVE-2024-6387.svg) 
2024-07-05T15:19:28Z

- [https://github.com/theaog/spirit](https://github.com/theaog/spirit) :  
![starts](https://img.shields.io/github/stars/theaog/spirit.svg) 
![forks](https://img.shields.io/github/forks/theaog/spirit.svg) 
2024-11-10T21:17:44Z

- [https://github.com/asterictnl-lvdw/CVE-2024-6387](https://github.com/asterictnl-lvdw/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/asterictnl-lvdw/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/asterictnl-lvdw/CVE-2024-6387.svg) 
2024-08-22T08:50:25Z

- [https://github.com/d0rb/CVE-2024-6387](https://github.com/d0rb/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/d0rb/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/d0rb/CVE-2024-6387.svg) 
2024-07-04T20:04:30Z

- [https://github.com/xonoxitron/regreSSHion](https://github.com/xonoxitron/regreSSHion) :  
![starts](https://img.shields.io/github/stars/xonoxitron/regreSSHion.svg) 
![forks](https://img.shields.io/github/forks/xonoxitron/regreSSHion.svg) 
2024-07-02T15:16:04Z

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

- [https://github.com/devarshishimpi/CVE-2024-6387-Check](https://github.com/devarshishimpi/CVE-2024-6387-Check) :  
![starts](https://img.shields.io/github/stars/devarshishimpi/CVE-2024-6387-Check.svg) 
![forks](https://img.shields.io/github/forks/devarshishimpi/CVE-2024-6387-Check.svg) 
2024-07-08T20:39:03Z

- [https://github.com/sxlmnwb/CVE-2024-6387](https://github.com/sxlmnwb/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/sxlmnwb/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/sxlmnwb/CVE-2024-6387.svg) 
2024-07-03T06:47:46Z

- [https://github.com/TAM-K592/CVE-2024-6387](https://github.com/TAM-K592/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/TAM-K592/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/TAM-K592/CVE-2024-6387.svg) 
2024-07-02T03:23:00Z

- [https://github.com/AiGptCode/ssh_exploiter_CVE-2024-6387](https://github.com/AiGptCode/ssh_exploiter_CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/AiGptCode/ssh_exploiter_CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/AiGptCode/ssh_exploiter_CVE-2024-6387.svg) 
2024-07-04T01:55:26Z

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

- [https://github.com/3yujw7njai/CVE-2024-6387](https://github.com/3yujw7njai/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/3yujw7njai/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/3yujw7njai/CVE-2024-6387.svg) 
2024-07-02T01:13:22Z

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

- [https://github.com/betancour/OpenSSH-Vulnerability-test](https://github.com/betancour/OpenSSH-Vulnerability-test) :  
![starts](https://img.shields.io/github/stars/betancour/OpenSSH-Vulnerability-test.svg) 
![forks](https://img.shields.io/github/forks/betancour/OpenSSH-Vulnerability-test.svg) 
2024-07-02T01:31:11Z

- [https://github.com/BrandonLynch2402/cve-2024-6387-nuclei-template](https://github.com/BrandonLynch2402/cve-2024-6387-nuclei-template) :  
![starts](https://img.shields.io/github/stars/BrandonLynch2402/cve-2024-6387-nuclei-template.svg) 
![forks](https://img.shields.io/github/forks/BrandonLynch2402/cve-2024-6387-nuclei-template.svg) 
2024-07-02T20:28:35Z

- [https://github.com/harshinsecurity/sentinelssh](https://github.com/harshinsecurity/sentinelssh) :  
![starts](https://img.shields.io/github/stars/harshinsecurity/sentinelssh.svg) 
![forks](https://img.shields.io/github/forks/harshinsecurity/sentinelssh.svg) 
2024-07-08T07:32:32Z

- [https://github.com/MaulikxLakhani/SSHScout](https://github.com/MaulikxLakhani/SSHScout) :  
![starts](https://img.shields.io/github/stars/MaulikxLakhani/SSHScout.svg) 
![forks](https://img.shields.io/github/forks/MaulikxLakhani/SSHScout.svg) 
2024-07-02T12:29:46Z

- [https://github.com/prelearn-code/CVE-2024-6387](https://github.com/prelearn-code/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/prelearn-code/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/prelearn-code/CVE-2024-6387.svg) 
2024-07-25T02:37:55Z

- [https://github.com/ThemeHackers/CVE-2024-6387](https://github.com/ThemeHackers/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ThemeHackers/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ThemeHackers/CVE-2024-6387.svg) 
2024-07-11T14:59:20Z

- [https://github.com/Symbolexe/CVE-2024-6387](https://github.com/Symbolexe/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/Symbolexe/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/Symbolexe/CVE-2024-6387.svg) 
2024-07-04T15:07:21Z

- [https://github.com/ahlfors/CVE-2024-6387](https://github.com/ahlfors/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ahlfors/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ahlfors/CVE-2024-6387.svg) 
2024-07-02T09:57:35Z

- [https://github.com/ThatNotEasy/CVE-2024-6387](https://github.com/ThatNotEasy/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-6387.svg) 
2024-07-15T16:06:41Z

- [https://github.com/ACHUX21/checker-CVE-2024-6387](https://github.com/ACHUX21/checker-CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ACHUX21/checker-CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ACHUX21/checker-CVE-2024-6387.svg) 
2024-07-02T13:18:38Z

- [https://github.com/muyuanlove/CVE-2024-6387fixshell](https://github.com/muyuanlove/CVE-2024-6387fixshell) :  
![starts](https://img.shields.io/github/stars/muyuanlove/CVE-2024-6387fixshell.svg) 
![forks](https://img.shields.io/github/forks/muyuanlove/CVE-2024-6387fixshell.svg) 
2024-07-02T02:39:40Z

- [https://github.com/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker](https://github.com/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker) :  
![starts](https://img.shields.io/github/stars/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker.svg) 
![forks](https://img.shields.io/github/forks/identity-threat-labs/CVE-2024-6387-Vulnerability-Checker.svg) 
2024-08-29T14:52:33Z

- [https://github.com/MrR0b0t19/CVE-2024-6387-Exploit-POC](https://github.com/MrR0b0t19/CVE-2024-6387-Exploit-POC) :  
![starts](https://img.shields.io/github/stars/MrR0b0t19/CVE-2024-6387-Exploit-POC.svg) 
![forks](https://img.shields.io/github/forks/MrR0b0t19/CVE-2024-6387-Exploit-POC.svg) 
2024-07-02T16:38:33Z

- [https://github.com/PrincipalAnthony/CVE-2024-6387-Updated-x64bit](https://github.com/PrincipalAnthony/CVE-2024-6387-Updated-x64bit) :  
![starts](https://img.shields.io/github/stars/PrincipalAnthony/CVE-2024-6387-Updated-x64bit.svg) 
![forks](https://img.shields.io/github/forks/PrincipalAnthony/CVE-2024-6387-Updated-x64bit.svg) 
2024-07-02T09:46:08Z

- [https://github.com/rumochnaya/openssh-cve-2024-6387.sh](https://github.com/rumochnaya/openssh-cve-2024-6387.sh) :  
![starts](https://img.shields.io/github/stars/rumochnaya/openssh-cve-2024-6387.sh.svg) 
![forks](https://img.shields.io/github/forks/rumochnaya/openssh-cve-2024-6387.sh.svg) 
2024-07-02T11:23:35Z

- [https://github.com/Sibijo/mitigate_ssh](https://github.com/Sibijo/mitigate_ssh) :  
![starts](https://img.shields.io/github/stars/Sibijo/mitigate_ssh.svg) 
![forks](https://img.shields.io/github/forks/Sibijo/mitigate_ssh.svg) 
2024-07-11T16:55:52Z

- [https://github.com/SecWithMoh/CVE-2024-6387](https://github.com/SecWithMoh/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/SecWithMoh/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/SecWithMoh/CVE-2024-6387.svg) 
2024-07-02T10:05:02Z

- [https://github.com/R4Tw1z/CVE-2024-6387](https://github.com/R4Tw1z/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/R4Tw1z/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/R4Tw1z/CVE-2024-6387.svg) 
2024-07-02T09:01:55Z

- [https://github.com/grupooruss/CVE-2024-6387](https://github.com/grupooruss/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/grupooruss/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/grupooruss/CVE-2024-6387.svg) 
2024-07-02T21:30:12Z

- [https://github.com/n1cks0n/Test_CVE-2024-6387](https://github.com/n1cks0n/Test_CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/n1cks0n/Test_CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/n1cks0n/Test_CVE-2024-6387.svg) 
2024-07-02T18:31:41Z

- [https://github.com/passwa11/cve-2024-6387-poc](https://github.com/passwa11/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/passwa11/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/passwa11/cve-2024-6387-poc.svg) 
2024-07-01T14:10:08Z

- [https://github.com/shamo0/CVE-2024-6387_PoC](https://github.com/shamo0/CVE-2024-6387_PoC) :  
![starts](https://img.shields.io/github/stars/shamo0/CVE-2024-6387_PoC.svg) 
![forks](https://img.shields.io/github/forks/shamo0/CVE-2024-6387_PoC.svg) 
2024-07-02T08:40:31Z

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

- [https://github.com/jack0we/CVE-2024-6387](https://github.com/jack0we/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/jack0we/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/jack0we/CVE-2024-6387.svg) 
2024-07-01T18:32:41Z

- [https://github.com/sms2056/CVE-2024-6387](https://github.com/sms2056/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/sms2056/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/sms2056/CVE-2024-6387.svg) 
2024-07-04T06:16:19Z

- [https://github.com/YassDEV221608/CVE-2024-6387](https://github.com/YassDEV221608/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/YassDEV221608/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/YassDEV221608/CVE-2024-6387.svg) 
2024-11-24T17:14:29Z

- [https://github.com/mrmtwoj/CVE-2024-6387](https://github.com/mrmtwoj/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/mrmtwoj/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/mrmtwoj/CVE-2024-6387.svg) 
2024-07-09T14:29:30Z

- [https://github.com/zql-gif/CVE-2024-6387](https://github.com/zql-gif/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/zql-gif/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/zql-gif/CVE-2024-6387.svg) 
2024-12-19T06:49:52Z

- [https://github.com/dream434/CVE-2024-6387](https://github.com/dream434/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-6387.svg) 
2024-07-14T18:02:26Z

- [https://github.com/HadesNull123/CVE-2024-6387_Check](https://github.com/HadesNull123/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/HadesNull123/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/HadesNull123/CVE-2024-6387_Check.svg) 
2024-08-26T04:41:02Z

- [https://github.com/DimaMend/cve-2024-6387-poc](https://github.com/DimaMend/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/DimaMend/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/DimaMend/cve-2024-6387-poc.svg) 
2024-07-10T13:33:50Z

- [https://github.com/Mufti22/CVE-2024-6387-checkher](https://github.com/Mufti22/CVE-2024-6387-checkher) :  
![starts](https://img.shields.io/github/stars/Mufti22/CVE-2024-6387-checkher.svg) 
![forks](https://img.shields.io/github/forks/Mufti22/CVE-2024-6387-checkher.svg) 
2024-07-02T03:49:06Z

- [https://github.com/t3rry327/cve-2024-6387-poc](https://github.com/t3rry327/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/t3rry327/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/t3rry327/cve-2024-6387-poc.svg) 
2024-07-03T13:24:59Z

- [https://github.com/dgourillon/mitigate-CVE-2024-6387](https://github.com/dgourillon/mitigate-CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/dgourillon/mitigate-CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/dgourillon/mitigate-CVE-2024-6387.svg) 
2024-07-09T16:03:03Z

- [https://github.com/zenzue/CVE-2024-6387-Mitigation](https://github.com/zenzue/CVE-2024-6387-Mitigation) :  
![starts](https://img.shields.io/github/stars/zenzue/CVE-2024-6387-Mitigation.svg) 
![forks](https://img.shields.io/github/forks/zenzue/CVE-2024-6387-Mitigation.svg) 
2024-07-02T11:17:12Z

- [https://github.com/sardine-web/CVE-2024-6387_Check](https://github.com/sardine-web/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/sardine-web/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/sardine-web/CVE-2024-6387_Check.svg) 
2024-07-04T21:31:17Z

- [https://github.com/edsonjt81/CVE-2024-6387_Check](https://github.com/edsonjt81/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/edsonjt81/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/edsonjt81/CVE-2024-6387_Check.svg) 
2024-07-02T20:38:06Z

- [https://github.com/CognisysGroup/CVE-2024-6387-Checker](https://github.com/CognisysGroup/CVE-2024-6387-Checker) :  
![starts](https://img.shields.io/github/stars/CognisysGroup/CVE-2024-6387-Checker.svg) 
![forks](https://img.shields.io/github/forks/CognisysGroup/CVE-2024-6387-Checker.svg) 
2024-07-03T12:13:37Z

- [https://github.com/sardine-web/CVE-2024-6387-template](https://github.com/sardine-web/CVE-2024-6387-template) :  
![starts](https://img.shields.io/github/stars/sardine-web/CVE-2024-6387-template.svg) 
![forks](https://img.shields.io/github/forks/sardine-web/CVE-2024-6387-template.svg) 
2024-07-06T17:26:21Z

- [https://github.com/shyrwall/cve-2024-6387-poc](https://github.com/shyrwall/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/shyrwall/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/shyrwall/cve-2024-6387-poc.svg) 
2024-07-01T12:50:29Z

- [https://github.com/skyalliance/CVE-2024-6387-POC](https://github.com/skyalliance/CVE-2024-6387-POC) :  
![starts](https://img.shields.io/github/stars/skyalliance/CVE-2024-6387-POC.svg) 
![forks](https://img.shields.io/github/forks/skyalliance/CVE-2024-6387-POC.svg) 
2024-07-02T13:24:37Z

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

- [https://github.com/invaderslabs/regreSSHion-CVE-2024-6387-](https://github.com/invaderslabs/regreSSHion-CVE-2024-6387-) :  
![starts](https://img.shields.io/github/stars/invaderslabs/regreSSHion-CVE-2024-6387-.svg) 
![forks](https://img.shields.io/github/forks/invaderslabs/regreSSHion-CVE-2024-6387-.svg) 
2024-07-04T22:22:15Z

- [https://github.com/4lxprime/regreSSHive](https://github.com/4lxprime/regreSSHive) :  
![starts](https://img.shields.io/github/stars/4lxprime/regreSSHive.svg) 
![forks](https://img.shields.io/github/forks/4lxprime/regreSSHive.svg) 
2024-07-04T14:34:23Z

- [https://github.com/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook](https://github.com/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook) :  
![starts](https://img.shields.io/github/stars/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook.svg) 
![forks](https://img.shields.io/github/forks/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook.svg) 
2024-07-02T11:05:55Z

- [https://github.com/almogopp/OpenSSH-CVE-2024-6387-Fix](https://github.com/almogopp/OpenSSH-CVE-2024-6387-Fix) :  
![starts](https://img.shields.io/github/stars/almogopp/OpenSSH-CVE-2024-6387-Fix.svg) 
![forks](https://img.shields.io/github/forks/almogopp/OpenSSH-CVE-2024-6387-Fix.svg) 
2024-08-20T09:58:32Z

- [https://github.com/Passyed/regreSSHion-Fix](https://github.com/Passyed/regreSSHion-Fix) :  
![starts](https://img.shields.io/github/stars/Passyed/regreSSHion-Fix.svg) 
![forks](https://img.shields.io/github/forks/Passyed/regreSSHion-Fix.svg) 
2024-07-12T00:06:59Z

- [https://github.com/vkaushik-chef/regreSSHion](https://github.com/vkaushik-chef/regreSSHion) :  
![starts](https://img.shields.io/github/stars/vkaushik-chef/regreSSHion.svg) 
![forks](https://img.shields.io/github/forks/vkaushik-chef/regreSSHion.svg) 
2024-07-08T12:04:33Z

- [https://github.com/liqhtnd/sshd-logingracetime0](https://github.com/liqhtnd/sshd-logingracetime0) :  
![starts](https://img.shields.io/github/stars/liqhtnd/sshd-logingracetime0.svg) 
![forks](https://img.shields.io/github/forks/liqhtnd/sshd-logingracetime0.svg) 
2024-07-13T18:43:04Z

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

# 2024-12-21
## CVE-2024-56331
 Uptime Kuma is an open source, self-hosted monitoring tool. An **Improper URL Handling Vulnerability** allows an attacker to access sensitive local files on the server by exploiting the `file:///` protocol. This vulnerability is triggered via the **"real-browser"** request type, which takes a screenshot of the URL provided by the attacker. By supplying local file paths, such as `file:///etc/passwd`, an attacker can read sensitive data from the server. This vulnerability arises because the system does not properly validate or sanitize the user input for the URL field. Specifically: 1. The URL input (`input data-v-5f5c86d7="" id="url" type="url" class="form-control" pattern="https?://.+" required=""`) allows users to input arbitrary file paths, including those using the `file:///` protocol, without server-side validation. 2. The server then uses the user-provided URL to make a request, passing it to a browser instance that performs the "real-browser" request, which takes a screenshot of the content at the given URL. If a local file path is entered (e.g., `file:///etc/passwd`), the browser fetches and captures the files content. Since the user input is not validated, an attacker can manipulate the URL to request local files (e.g., `file:///etc/passwd`), and the system will capture a screenshot of the file's content, potentially exposing sensitive data. Any **authenticated user** who can submit a URL in "real-browser" mode is at risk of exposing sensitive data through screenshots of these files. This issue has been addressed in version 1.23.16 and all users are advised to upgrade. There are no known workarounds for this vulnerability.

- [https://github.com/griisemine/CVE-2024-56331](https://github.com/griisemine/CVE-2024-56331) :  
![starts](https://img.shields.io/github/stars/griisemine/CVE-2024-56331.svg) 
![forks](https://img.shields.io/github/forks/griisemine/CVE-2024-56331.svg) 
2024-12-21T21:09:33Z

## CVE-2024-41713
 A vulnerability in the NuPoint Unified Messaging (NPM) component of Mitel MiCollab through 9.8 SP1 FP2 (9.8.1.201) could allow an unauthenticated attacker to conduct a path traversal attack, due to insufficient input validation. A successful exploit could allow unauthorized access, enabling the attacker to view, corrupt, or delete users' data and system configurations.

- [https://github.com/watchtowrlabs/Mitel-MiCollab-Auth-Bypass_CVE-2024-41713](https://github.com/watchtowrlabs/Mitel-MiCollab-Auth-Bypass_CVE-2024-41713) :  
![starts](https://img.shields.io/github/stars/watchtowrlabs/Mitel-MiCollab-Auth-Bypass_CVE-2024-41713.svg) 
![forks](https://img.shields.io/github/forks/watchtowrlabs/Mitel-MiCollab-Auth-Bypass_CVE-2024-41713.svg) 
2024-12-05T07:55:04Z

- [https://github.com/Sanandd/cve-2024-CVE-2024-41713](https://github.com/Sanandd/cve-2024-CVE-2024-41713) :  
![starts](https://img.shields.io/github/stars/Sanandd/cve-2024-CVE-2024-41713.svg) 
![forks](https://img.shields.io/github/forks/Sanandd/cve-2024-CVE-2024-41713.svg) 
2024-12-21T09:36:17Z

- [https://github.com/zxj-hub/CVE-2024-41713POC](https://github.com/zxj-hub/CVE-2024-41713POC) :  
![starts](https://img.shields.io/github/stars/zxj-hub/CVE-2024-41713POC.svg) 
![forks](https://img.shields.io/github/forks/zxj-hub/CVE-2024-41713POC.svg) 
2024-12-21T02:28:22Z

## CVE-2024-39914
 FOG is a cloning/imaging/rescue suite/inventory management system. Prior to 1.5.10.34, packages/web/lib/fog/reportmaker.class.php in FOG was affected by a command injection via the filename parameter to /fog/management/export.php. This vulnerability is fixed in 1.5.10.34.

- [https://github.com/9874621368/FOG-Project](https://github.com/9874621368/FOG-Project) :  
![starts](https://img.shields.io/github/stars/9874621368/FOG-Project.svg) 
![forks](https://img.shields.io/github/forks/9874621368/FOG-Project.svg) 
2024-12-21T08:33:54Z

## CVE-2024-27292
 Docassemble is an expert system for guided interviews and document assembly. The vulnerability allows attackers to gain unauthorized access to information on the system through URL manipulation. It affects versions 1.4.53 to 1.4.96. The vulnerability has been patched in version 1.4.97 of the master branch.

- [https://github.com/th3gokul/CVE-2024-27292](https://github.com/th3gokul/CVE-2024-27292) :  
![starts](https://img.shields.io/github/stars/th3gokul/CVE-2024-27292.svg) 
![forks](https://img.shields.io/github/forks/th3gokul/CVE-2024-27292.svg) 
2024-07-02T11:39:54Z

- [https://github.com/tequilasunsh1ne/CVE_2024_27292](https://github.com/tequilasunsh1ne/CVE_2024_27292) :  
![starts](https://img.shields.io/github/stars/tequilasunsh1ne/CVE_2024_27292.svg) 
![forks](https://img.shields.io/github/forks/tequilasunsh1ne/CVE_2024_27292.svg) 
2024-07-08T03:30:43Z

- [https://github.com/NingXin2002/Docassemble_poc](https://github.com/NingXin2002/Docassemble_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/Docassemble_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/Docassemble_poc.svg) 
2024-12-21T03:36:49Z

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

- [https://github.com/LucasKatashi/CVE-2024-24919](https://github.com/LucasKatashi/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/LucasKatashi/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/LucasKatashi/CVE-2024-24919.svg) 
2024-05-30T17:08:11Z

- [https://github.com/un9nplayer/CVE-2024-24919](https://github.com/un9nplayer/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/un9nplayer/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/un9nplayer/CVE-2024-24919.svg) 
2024-06-05T16:13:51Z

- [https://github.com/verylazytech/CVE-2024-24919](https://github.com/verylazytech/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-24919.svg) 
2024-11-26T14:45:44Z

- [https://github.com/geniuszlyy/CVE-2024-24919](https://github.com/geniuszlyy/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/geniuszlyy/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/geniuszlyy/CVE-2024-24919.svg) 
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

- [https://github.com/zam89/CVE-2024-24919](https://github.com/zam89/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/zam89/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/zam89/CVE-2024-24919.svg) 
2024-05-31T08:16:57Z

- [https://github.com/Bytenull00/CVE-2024-24919](https://github.com/Bytenull00/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/Bytenull00/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Bytenull00/CVE-2024-24919.svg) 
2024-05-30T21:49:43Z

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

- [https://github.com/fernandobortotti/CVE-2024-24919](https://github.com/fernandobortotti/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/fernandobortotti/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/fernandobortotti/CVE-2024-24919.svg) 
2024-06-01T03:44:23Z

- [https://github.com/SalehLardhi/CVE-2024-24919](https://github.com/SalehLardhi/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/SalehLardhi/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/SalehLardhi/CVE-2024-24919.svg) 
2024-06-11T03:37:04Z

- [https://github.com/skyrowalker/CVE-2024-24919](https://github.com/skyrowalker/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/skyrowalker/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/skyrowalker/CVE-2024-24919.svg) 
2024-10-10T13:34:31Z

- [https://github.com/0xYumeko/CVE-2024-24919](https://github.com/0xYumeko/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/0xYumeko/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/0xYumeko/CVE-2024-24919.svg) 
2024-06-01T12:22:11Z

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

- [https://github.com/mr-kasim-mehar/CVE-2024-24919-Exploit](https://github.com/mr-kasim-mehar/CVE-2024-24919-Exploit) :  
![starts](https://img.shields.io/github/stars/mr-kasim-mehar/CVE-2024-24919-Exploit.svg) 
![forks](https://img.shields.io/github/forks/mr-kasim-mehar/CVE-2024-24919-Exploit.svg) 
2024-06-02T08:24:32Z

- [https://github.com/starlox0/CVE-2024-24919-POC](https://github.com/starlox0/CVE-2024-24919-POC) :  
![starts](https://img.shields.io/github/stars/starlox0/CVE-2024-24919-POC.svg) 
![forks](https://img.shields.io/github/forks/starlox0/CVE-2024-24919-POC.svg) 
2024-06-06T16:12:42Z

- [https://github.com/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check](https://github.com/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check) :  
![starts](https://img.shields.io/github/stars/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check.svg) 
![forks](https://img.shields.io/github/forks/r4p3c4/CVE-2024-24919-Checkpoint-Firewall-VPN-Check.svg) 
2024-06-01T11:56:27Z

- [https://github.com/NingXin2002/Check-Point_poc](https://github.com/NingXin2002/Check-Point_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/Check-Point_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/Check-Point_poc.svg) 
2024-12-21T02:43:40Z

- [https://github.com/am-eid/CVE-2024-24919](https://github.com/am-eid/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/am-eid/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/am-eid/CVE-2024-24919.svg) 
2024-05-31T00:06:39Z

- [https://github.com/P3wc0/CVE-2024-24919](https://github.com/P3wc0/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/P3wc0/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/P3wc0/CVE-2024-24919.svg) 
2024-05-31T01:39:02Z

- [https://github.com/ShadowByte1/CVE-2024-24919](https://github.com/ShadowByte1/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/ShadowByte1/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/ShadowByte1/CVE-2024-24919.svg) 
2024-07-14T23:33:00Z

- [https://github.com/yagyuufellinluvv/CVE-2024-24919](https://github.com/yagyuufellinluvv/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/yagyuufellinluvv/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/yagyuufellinluvv/CVE-2024-24919.svg) 
2024-06-01T00:09:51Z

- [https://github.com/nicolvsrlr27/CVE-2024-24919](https://github.com/nicolvsrlr27/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/nicolvsrlr27/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/nicolvsrlr27/CVE-2024-24919.svg) 
2024-06-01T03:05:35Z

- [https://github.com/satriarizka/CVE-2024-24919](https://github.com/satriarizka/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/satriarizka/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/satriarizka/CVE-2024-24919.svg) 
2024-05-31T08:37:35Z

- [https://github.com/hendprw/CVE-2024-24919](https://github.com/hendprw/CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/hendprw/CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/hendprw/CVE-2024-24919.svg) 
2024-05-30T15:42:23Z

- [https://github.com/Jutrm/cve-2024-24919](https://github.com/Jutrm/cve-2024-24919) :  
![starts](https://img.shields.io/github/stars/Jutrm/cve-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/Jutrm/cve-2024-24919.svg) 
2024-07-26T15:23:03Z

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

- [https://github.com/B1naryo/CVE-2024-24919-POC](https://github.com/B1naryo/CVE-2024-24919-POC) :  
![starts](https://img.shields.io/github/stars/B1naryo/CVE-2024-24919-POC.svg) 
![forks](https://img.shields.io/github/forks/B1naryo/CVE-2024-24919-POC.svg) 
2024-06-02T13:18:24Z

- [https://github.com/birdlex/cve-2024-24919-checker](https://github.com/birdlex/cve-2024-24919-checker) :  
![starts](https://img.shields.io/github/stars/birdlex/cve-2024-24919-checker.svg) 
![forks](https://img.shields.io/github/forks/birdlex/cve-2024-24919-checker.svg) 
2024-06-04T06:54:55Z

- [https://github.com/Expl0itD0g/CVE-2024-24919---Poc](https://github.com/Expl0itD0g/CVE-2024-24919---Poc) :  
![starts](https://img.shields.io/github/stars/Expl0itD0g/CVE-2024-24919---Poc.svg) 
![forks](https://img.shields.io/github/forks/Expl0itD0g/CVE-2024-24919---Poc.svg) 
2024-06-02T14:00:44Z

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

- [https://github.com/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919](https://github.com/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919) :  
![starts](https://img.shields.io/github/stars/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919.svg) 
![forks](https://img.shields.io/github/forks/LuisMateo1/Arbitrary-File-Read-CVE-2024-24919.svg) 
2024-08-29T14:37:31Z

- [https://github.com/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN](https://github.com/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN) :  
![starts](https://img.shields.io/github/stars/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN.svg) 
![forks](https://img.shields.io/github/forks/Praison001/CVE-2024-24919-Check-Point-Remote-Access-VPN.svg) 
2024-06-02T12:39:57Z

- [https://github.com/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-](https://github.com/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-) :  
![starts](https://img.shields.io/github/stars/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-.svg) 
![forks](https://img.shields.io/github/forks/AhmedMansour93/Event-ID-263-Rule-Name-SOC287---Arbitrary-File-Read-on-Checkpoint-Security-Gateway-CVE-2024-24919-.svg) 
2024-08-31T16:58:20Z

## CVE-2024-23692
 Rejetto HTTP File Server, up to and including version 2.3m, is vulnerable to a template injection vulnerability. This vulnerability allows a remote, unauthenticated attacker to execute arbitrary commands on the affected system by sending a specially crafted HTTP request. As of the CVE assignment date, Rejetto HFS 2.3m is no longer supported.

- [https://github.com/verylazytech/CVE-2024-23692](https://github.com/verylazytech/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-23692.svg) 
2024-11-26T14:45:12Z

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

- [https://github.com/NingXin2002/HFS2.3_poc](https://github.com/NingXin2002/HFS2.3_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/HFS2.3_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/HFS2.3_poc.svg) 
2024-12-21T07:14:26Z

## CVE-2024-4819
 A vulnerability was found in Campcodes Online Laundry Management System 1.0. It has been classified as problematic. Affected is an unknown function of the file admin_class.php. The manipulation of the argument type with the input 1 leads to improper authorization. It is possible to launch the attack remotely. The exploit has been disclosed to the public and may be used. The identifier of this vulnerability is VDB-263940.

- [https://github.com/GCatt-AS/CVE-2024-48197](https://github.com/GCatt-AS/CVE-2024-48197) :  
![starts](https://img.shields.io/github/stars/GCatt-AS/CVE-2024-48197.svg) 
![forks](https://img.shields.io/github/forks/GCatt-AS/CVE-2024-48197.svg) 
2024-12-21T13:12:29Z

# 2024-12-20
## CVE-2024-44825
 Directory Traversal vulnerability in Centro de Tecnologia da Informaco Renato Archer InVesalius3 v3.1.99995 allows attackers to write arbitrary files unto the system via a crafted .inv3 file.

- [https://github.com/partywavesec/invesalius3_vulnerabilities](https://github.com/partywavesec/invesalius3_vulnerabilities) :  
![starts](https://img.shields.io/github/stars/partywavesec/invesalius3_vulnerabilities.svg) 
![forks](https://img.shields.io/github/forks/partywavesec/invesalius3_vulnerabilities.svg) 
2024-12-20T09:48:52Z

## CVE-2024-42845
 An eval Injection vulnerability in the component invesalius/reader/dicom.py of InVesalius 3.1.99991 through 3.1.99998 allows attackers to execute arbitrary code via loading a crafted DICOM file.

- [https://github.com/partywavesec/invesalius3_vulnerabilities](https://github.com/partywavesec/invesalius3_vulnerabilities) :  
![starts](https://img.shields.io/github/stars/partywavesec/invesalius3_vulnerabilities.svg) 
![forks](https://img.shields.io/github/forks/partywavesec/invesalius3_vulnerabilities.svg) 
2024-12-20T09:48:52Z

## CVE-2024-41319
 TOTOLINK A6000R V1.0.1-B20201211.2000 was discovered to contain a command injection vulnerability via the cmd parameter in the webcmd function.

- [https://github.com/NingXin2002/TOTOLINK_poc](https://github.com/NingXin2002/TOTOLINK_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/TOTOLINK_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/TOTOLINK_poc.svg) 
2024-12-20T09:35:47Z

## CVE-2024-40348
 An issue in the component /api/swaggerui/static of Bazaar v1.4.3 allows unauthenticated attackers to execute a directory traversal.

- [https://github.com/bigb0x/CVE-2024-40348](https://github.com/bigb0x/CVE-2024-40348) :  
![starts](https://img.shields.io/github/stars/bigb0x/CVE-2024-40348.svg) 
![forks](https://img.shields.io/github/forks/bigb0x/CVE-2024-40348.svg) 
2024-07-21T09:54:02Z

- [https://github.com/codeb0ss/CVEploiterv2](https://github.com/codeb0ss/CVEploiterv2) :  
![starts](https://img.shields.io/github/stars/codeb0ss/CVEploiterv2.svg) 
![forks](https://img.shields.io/github/forks/codeb0ss/CVEploiterv2.svg) 
2024-07-25T14:16:55Z

- [https://github.com/codeb0ss/CVE-2024-40348-PoC](https://github.com/codeb0ss/CVE-2024-40348-PoC) :  
![starts](https://img.shields.io/github/stars/codeb0ss/CVE-2024-40348-PoC.svg) 
![forks](https://img.shields.io/github/forks/codeb0ss/CVE-2024-40348-PoC.svg) 
2024-07-24T16:15:05Z

- [https://github.com/NingXin2002/Bazaar_poc](https://github.com/NingXin2002/Bazaar_poc) :  
![starts](https://img.shields.io/github/stars/NingXin2002/Bazaar_poc.svg) 
![forks](https://img.shields.io/github/forks/NingXin2002/Bazaar_poc.svg) 
2024-12-20T09:49:39Z

## CVE-2024-27956
 Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in ValvePress Automatic allows SQL Injection.This issue affects Automatic: from n/a through 3.92.0.

- [https://github.com/AiGptCode/WordPress-Auto-Admin-Account-and-Reverse-Shell-cve-2024-27956](https://github.com/AiGptCode/WordPress-Auto-Admin-Account-and-Reverse-Shell-cve-2024-27956) :  
![starts](https://img.shields.io/github/stars/AiGptCode/WordPress-Auto-Admin-Account-and-Reverse-Shell-cve-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/AiGptCode/WordPress-Auto-Admin-Account-and-Reverse-Shell-cve-2024-27956.svg) 
2024-07-01T09:29:02Z

- [https://github.com/diego-tella/CVE-2024-27956-RCE](https://github.com/diego-tella/CVE-2024-27956-RCE) :  
![starts](https://img.shields.io/github/stars/diego-tella/CVE-2024-27956-RCE.svg) 
![forks](https://img.shields.io/github/forks/diego-tella/CVE-2024-27956-RCE.svg) 
2024-05-03T11:28:21Z

- [https://github.com/truonghuuphuc/CVE-2024-27956](https://github.com/truonghuuphuc/CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/truonghuuphuc/CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/truonghuuphuc/CVE-2024-27956.svg) 
2024-04-27T11:37:02Z

- [https://github.com/ThatNotEasy/CVE-2024-27956](https://github.com/ThatNotEasy/CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-27956.svg) 
2024-07-11T14:20:59Z

- [https://github.com/itzheartzz/MASS-CVE-2024-27956](https://github.com/itzheartzz/MASS-CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/itzheartzz/MASS-CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/itzheartzz/MASS-CVE-2024-27956.svg) 
2024-06-09T16:37:41Z

- [https://github.com/Cappricio-Securities/CVE-2024-27956](https://github.com/Cappricio-Securities/CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/Cappricio-Securities/CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/Cappricio-Securities/CVE-2024-27956.svg) 
2024-06-24T10:43:34Z

- [https://github.com/FoxyProxys/CVE-2024-27956](https://github.com/FoxyProxys/CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/FoxyProxys/CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/FoxyProxys/CVE-2024-27956.svg) 
2024-05-15T15:36:50Z

- [https://github.com/k3ppf0r/CVE-2024-27956](https://github.com/k3ppf0r/CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/k3ppf0r/CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/k3ppf0r/CVE-2024-27956.svg) 
2024-05-07T14:32:38Z

- [https://github.com/X-Projetion/CVE-2024-27956-WORDPRESS-RCE-PLUGIN](https://github.com/X-Projetion/CVE-2024-27956-WORDPRESS-RCE-PLUGIN) :  
![starts](https://img.shields.io/github/stars/X-Projetion/CVE-2024-27956-WORDPRESS-RCE-PLUGIN.svg) 
![forks](https://img.shields.io/github/forks/X-Projetion/CVE-2024-27956-WORDPRESS-RCE-PLUGIN.svg) 
2024-05-03T16:31:23Z

- [https://github.com/cve-2024/CVE-2024-27956-RCE](https://github.com/cve-2024/CVE-2024-27956-RCE) :  
![starts](https://img.shields.io/github/stars/cve-2024/CVE-2024-27956-RCE.svg) 
![forks](https://img.shields.io/github/forks/cve-2024/CVE-2024-27956-RCE.svg) 
2024-06-14T07:15:36Z

- [https://github.com/CERTologists/EXPLOITING-CVE-2024-27956](https://github.com/CERTologists/EXPLOITING-CVE-2024-27956) :  
![starts](https://img.shields.io/github/stars/CERTologists/EXPLOITING-CVE-2024-27956.svg) 
![forks](https://img.shields.io/github/forks/CERTologists/EXPLOITING-CVE-2024-27956.svg) 
2024-07-23T08:27:13Z

- [https://github.com/7aRanchi/CVE-2024-27956-for-fscan](https://github.com/7aRanchi/CVE-2024-27956-for-fscan) :  
![starts](https://img.shields.io/github/stars/7aRanchi/CVE-2024-27956-for-fscan.svg) 
![forks](https://img.shields.io/github/forks/7aRanchi/CVE-2024-27956-for-fscan.svg) 
2024-12-20T08:09:08Z

- [https://github.com/W3BW/CVE-2024-27956-RCE-File-Package](https://github.com/W3BW/CVE-2024-27956-RCE-File-Package) :  
![starts](https://img.shields.io/github/stars/W3BW/CVE-2024-27956-RCE-File-Package.svg) 
![forks](https://img.shields.io/github/forks/W3BW/CVE-2024-27956-RCE-File-Package.svg) 
2024-05-15T08:11:48Z

- [https://github.com/TadashiJei/Valve-Press-CVE-2024-27956-RCE](https://github.com/TadashiJei/Valve-Press-CVE-2024-27956-RCE) :  
![starts](https://img.shields.io/github/stars/TadashiJei/Valve-Press-CVE-2024-27956-RCE.svg) 
![forks](https://img.shields.io/github/forks/TadashiJei/Valve-Press-CVE-2024-27956-RCE.svg) 
2024-06-13T02:07:35Z

## CVE-2024-7954
 The porte_plume plugin used by SPIP before 4.30-alpha2, 4.2.13, and 4.1.16 is vulnerable to an arbitrary code execution vulnerability. A remote and unauthenticated attacker can execute arbitrary PHP as the SPIP user by sending a crafted HTTP request.

- [https://github.com/Chocapikk/CVE-2024-7954](https://github.com/Chocapikk/CVE-2024-7954) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-7954.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-7954.svg) 
2024-08-12T13:46:06Z

- [https://github.com/gh-ost00/CVE-2024-7954-RCE](https://github.com/gh-ost00/CVE-2024-7954-RCE) :  
![starts](https://img.shields.io/github/stars/gh-ost00/CVE-2024-7954-RCE.svg) 
![forks](https://img.shields.io/github/forks/gh-ost00/CVE-2024-7954-RCE.svg) 
2024-09-01T11:07:15Z

- [https://github.com/bigb0x/CVE-2024-7954](https://github.com/bigb0x/CVE-2024-7954) :  
![starts](https://img.shields.io/github/stars/bigb0x/CVE-2024-7954.svg) 
![forks](https://img.shields.io/github/forks/bigb0x/CVE-2024-7954.svg) 
2024-08-28T18:26:25Z

- [https://github.com/MuhammadWaseem29/RCE-CVE-2024-7954](https://github.com/MuhammadWaseem29/RCE-CVE-2024-7954) :  
![starts](https://img.shields.io/github/stars/MuhammadWaseem29/RCE-CVE-2024-7954.svg) 
![forks](https://img.shields.io/github/forks/MuhammadWaseem29/RCE-CVE-2024-7954.svg) 
2024-10-05T07:55:00Z

- [https://github.com/TheCyberguy-17/RCE_CVE-2024-7954](https://github.com/TheCyberguy-17/RCE_CVE-2024-7954) :  
![starts](https://img.shields.io/github/stars/TheCyberguy-17/RCE_CVE-2024-7954.svg) 
![forks](https://img.shields.io/github/forks/TheCyberguy-17/RCE_CVE-2024-7954.svg) 
2024-09-23T16:27:12Z

- [https://github.com/issamjr/CVE-2024-7954](https://github.com/issamjr/CVE-2024-7954) :  
![starts](https://img.shields.io/github/stars/issamjr/CVE-2024-7954.svg) 
![forks](https://img.shields.io/github/forks/issamjr/CVE-2024-7954.svg) 
2024-11-15T21:10:55Z

- [https://github.com/zxj-hub/CVE-2024-7954POC](https://github.com/zxj-hub/CVE-2024-7954POC) :  
![starts](https://img.shields.io/github/stars/zxj-hub/CVE-2024-7954POC.svg) 
![forks](https://img.shields.io/github/forks/zxj-hub/CVE-2024-7954POC.svg) 
2024-12-20T15:40:36Z

## CVE-2024-5347
 The Happy Addons for Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the 'arrow' attribute within the plugin's Post Navigation widget in all versions up to, and including, 3.10.9 due to insufficient input sanitization and output escaping on user supplied attributes. This makes it possible for authenticated attackers, with contributor-level access and above, to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page.

- [https://github.com/AbdullahAlmutawa/CVE-2024-53476](https://github.com/AbdullahAlmutawa/CVE-2024-53476) :  
![starts](https://img.shields.io/github/stars/AbdullahAlmutawa/CVE-2024-53476.svg) 
![forks](https://img.shields.io/github/forks/AbdullahAlmutawa/CVE-2024-53476.svg) 
2024-12-20T21:17:57Z

## CVE-2024-5094
 A vulnerability was found in SourceCodester Best House Rental Management System 1.0 and classified as critical. This issue affects some unknown processing of the file view_payment.php. The manipulation of the argument id leads to sql injection. The attack may be initiated remotely. The exploit has been disclosed to the public and may be used. The identifier VDB-265073 was assigned to this vulnerability.

- [https://github.com/AbdullahAlmutawa/CVE-2024-50944](https://github.com/AbdullahAlmutawa/CVE-2024-50944) :  
![starts](https://img.shields.io/github/stars/AbdullahAlmutawa/CVE-2024-50944.svg) 
![forks](https://img.shields.io/github/forks/AbdullahAlmutawa/CVE-2024-50944.svg) 
2024-12-20T21:17:36Z

- [https://github.com/AbdullahAlmutawa/CVE-2024-50945](https://github.com/AbdullahAlmutawa/CVE-2024-50945) :  
![starts](https://img.shields.io/github/stars/AbdullahAlmutawa/CVE-2024-50945.svg) 
![forks](https://img.shields.io/github/forks/AbdullahAlmutawa/CVE-2024-50945.svg) 
2024-12-20T21:18:11Z

# 2024-12-19
## CVE-2024-54262
 Unrestricted Upload of File with Dangerous Type vulnerability in Siddharth Nagar Import Export For WooCommerce allows Upload a Web Shell to a Web Server.This issue affects Import Export For WooCommerce: from n/a through 1.5.

- [https://github.com/RandomRobbieBF/CVE-2024-54262](https://github.com/RandomRobbieBF/CVE-2024-54262) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-54262.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-54262.svg) 
2024-12-19T14:43:46Z

## CVE-2024-53376
 CyberPanel before 2.3.8 allows remote authenticated users to execute arbitrary commands via shell metacharacters in the phpSelection field to the websites/submitWebsiteCreation URI.

- [https://github.com/ThottySploity/CVE-2024-53376](https://github.com/ThottySploity/CVE-2024-53376) :  
![starts](https://img.shields.io/github/stars/ThottySploity/CVE-2024-53376.svg) 
![forks](https://img.shields.io/github/forks/ThottySploity/CVE-2024-53376.svg) 
2024-12-19T09:36:58Z

## CVE-2024-53375
 An Authenticated Remote Code Execution (RCE) vulnerability affects the TP-Link Archer router series. A vulnerability exists in the "tmp_get_sites" function of the HomeShield functionality provided by TP-Link. This vulnerability is still exploitable without the activation of the HomeShield functionality.

- [https://github.com/ThottySploity/CVE-2024-53375](https://github.com/ThottySploity/CVE-2024-53375) :  
![starts](https://img.shields.io/github/stars/ThottySploity/CVE-2024-53375.svg) 
![forks](https://img.shields.io/github/forks/ThottySploity/CVE-2024-53375.svg) 
2024-12-19T09:34:33Z

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

- [https://github.com/Cyb3rFr0g/CVE-2024-48990-PoC](https://github.com/Cyb3rFr0g/CVE-2024-48990-PoC) :  
![starts](https://img.shields.io/github/stars/Cyb3rFr0g/CVE-2024-48990-PoC.svg) 
![forks](https://img.shields.io/github/forks/Cyb3rFr0g/CVE-2024-48990-PoC.svg) 
2024-11-24T02:32:54Z

- [https://github.com/r0xdeadbeef/CVE-2024-48990](https://github.com/r0xdeadbeef/CVE-2024-48990) :  
![starts](https://img.shields.io/github/stars/r0xdeadbeef/CVE-2024-48990.svg) 
![forks](https://img.shields.io/github/forks/r0xdeadbeef/CVE-2024-48990.svg) 
2024-12-01T16:27:46Z

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

- [https://github.com/ally-petitt/CVE-2024-48990-Exploit](https://github.com/ally-petitt/CVE-2024-48990-Exploit) :  
![starts](https://img.shields.io/github/stars/ally-petitt/CVE-2024-48990-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ally-petitt/CVE-2024-48990-Exploit.svg) 
2024-11-25T05:29:10Z

## CVE-2024-44765
 An Improper Authorization (Access Control Misconfiguration) vulnerability in MGT-COMMERCE GmbH CloudPanel v2.0.0 to v2.4.2 allows low-privilege users to bypass access controls and gain unauthorized access to sensitive configuration files and administrative functionality.

- [https://github.com/josephgodwinkimani/CVE-2024-44765](https://github.com/josephgodwinkimani/CVE-2024-44765) :  
![starts](https://img.shields.io/github/stars/josephgodwinkimani/CVE-2024-44765.svg) 
![forks](https://img.shields.io/github/forks/josephgodwinkimani/CVE-2024-44765.svg) 
2024-12-19T06:50:07Z

## CVE-2024-39908
  REXML is an XML toolkit for Ruby. The REXML gem before 3.3.1 has some DoS vulnerabilities when it parses an XML that has many specific characters such as ``, `0` and `%`. If you need to parse untrusted XMLs, you many be impacted to these vulnerabilities. The REXML gem 3.3.2 or later include the patches to fix these vulnerabilities. Users are advised to upgrade. Users unable to upgrade should avoid parsing untrusted XML strings.

- [https://github.com/SpiralBL0CK/CVE-2024-39908](https://github.com/SpiralBL0CK/CVE-2024-39908) :  
![starts](https://img.shields.io/github/stars/SpiralBL0CK/CVE-2024-39908.svg) 
![forks](https://img.shields.io/github/forks/SpiralBL0CK/CVE-2024-39908.svg) 
2024-12-19T19:00:03Z

## CVE-2024-35176
  REXML is an XML toolkit for Ruby. The REXML gem before 3.2.6 has a denial of service vulnerability when it parses an XML that has many ``s in an attribute value. Those who need to parse untrusted XMLs may be impacted to this vulnerability. The REXML gem 3.2.7 or later include the patch to fix this vulnerability. As a workaround, don't parse untrusted XMLs.

- [https://github.com/SpiralBL0CK/CVE-2024-35176](https://github.com/SpiralBL0CK/CVE-2024-35176) :  
![starts](https://img.shields.io/github/stars/SpiralBL0CK/CVE-2024-35176.svg) 
![forks](https://img.shields.io/github/forks/SpiralBL0CK/CVE-2024-35176.svg) 
2024-12-19T22:16:06Z

## CVE-2024-27198
 In JetBrains TeamCity before 2023.11.4 authentication bypass allowing to perform admin actions was possible

- [https://github.com/W01fh4cker/CVE-2024-27198-RCE](https://github.com/W01fh4cker/CVE-2024-27198-RCE) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/CVE-2024-27198-RCE.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/CVE-2024-27198-RCE.svg) 
2024-03-11T07:57:40Z

- [https://github.com/Chocapikk/CVE-2024-27198](https://github.com/Chocapikk/CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-27198.svg) 
2024-03-05T20:53:11Z

- [https://github.com/yoryio/CVE-2024-27198](https://github.com/yoryio/CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2024-27198.svg) 
2024-12-19T04:08:43Z

- [https://github.com/Stuub/RCity-CVE-2024-27198](https://github.com/Stuub/RCity-CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/Stuub/RCity-CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/Stuub/RCity-CVE-2024-27198.svg) 
2024-07-19T14:42:24Z

- [https://github.com/K3ysTr0K3R/CVE-2024-27198-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-27198-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-27198-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-27198-EXPLOIT.svg) 
2024-03-09T22:16:46Z

- [https://github.com/geniuszlyy/CVE-2024-27198](https://github.com/geniuszlyy/CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/geniuszlyy/CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/geniuszlyy/CVE-2024-27198.svg) 
2024-10-09T13:37:56Z

- [https://github.com/CharonDefalt/CVE-2024-27198-RCE](https://github.com/CharonDefalt/CVE-2024-27198-RCE) :  
![starts](https://img.shields.io/github/stars/CharonDefalt/CVE-2024-27198-RCE.svg) 
![forks](https://img.shields.io/github/forks/CharonDefalt/CVE-2024-27198-RCE.svg) 
2024-03-09T04:09:09Z

- [https://github.com/passwa11/CVE-2024-27198-RCE](https://github.com/passwa11/CVE-2024-27198-RCE) :  
![starts](https://img.shields.io/github/stars/passwa11/CVE-2024-27198-RCE.svg) 
![forks](https://img.shields.io/github/forks/passwa11/CVE-2024-27198-RCE.svg) 
2024-03-08T12:40:19Z

- [https://github.com/jrbH4CK/CVE-2024-27198](https://github.com/jrbH4CK/CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/jrbH4CK/CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/jrbH4CK/CVE-2024-27198.svg) 
2024-08-16T16:43:56Z

- [https://github.com/rampantspark/CVE-2024-27198](https://github.com/rampantspark/CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/rampantspark/CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/rampantspark/CVE-2024-27198.svg) 
2024-03-10T16:57:07Z

- [https://github.com/dkhacks/CVE_2024_27198](https://github.com/dkhacks/CVE_2024_27198) :  
![starts](https://img.shields.io/github/stars/dkhacks/CVE_2024_27198.svg) 
![forks](https://img.shields.io/github/forks/dkhacks/CVE_2024_27198.svg) 
2024-09-03T16:11:54Z

- [https://github.com/HPT-Intern-Task-Submission/CVE-2024-27198](https://github.com/HPT-Intern-Task-Submission/CVE-2024-27198) :  
![starts](https://img.shields.io/github/stars/HPT-Intern-Task-Submission/CVE-2024-27198.svg) 
![forks](https://img.shields.io/github/forks/HPT-Intern-Task-Submission/CVE-2024-27198.svg) 
2024-07-20T17:28:41Z

- [https://github.com/Cythonic1/CVE-2024-27198_POC](https://github.com/Cythonic1/CVE-2024-27198_POC) :  
![starts](https://img.shields.io/github/stars/Cythonic1/CVE-2024-27198_POC.svg) 
![forks](https://img.shields.io/github/forks/Cythonic1/CVE-2024-27198_POC.svg) 
2024-10-21T10:05:35Z

- [https://github.com/Shimon03/Explora-o-RCE-n-o-autenticado-JetBrains-TeamCity-CVE-2024-27198-](https://github.com/Shimon03/Explora-o-RCE-n-o-autenticado-JetBrains-TeamCity-CVE-2024-27198-) :  
![starts](https://img.shields.io/github/stars/Shimon03/Explora-o-RCE-n-o-autenticado-JetBrains-TeamCity-CVE-2024-27198-.svg) 
![forks](https://img.shields.io/github/forks/Shimon03/Explora-o-RCE-n-o-autenticado-JetBrains-TeamCity-CVE-2024-27198-.svg) 
2024-04-02T09:46:51Z

## CVE-2024-20767
 ColdFusion versions 2023.6, 2021.12 and earlier are affected by an Improper Access Control vulnerability that could result in arbitrary file system read. An attacker could leverage this vulnerability to access or modify restricted files. Exploitation of this issue does not require user interaction. Exploitation of this issue requires the admin panel be exposed to the internet.

- [https://github.com/yoryio/CVE-2024-20767](https://github.com/yoryio/CVE-2024-20767) :  
![starts](https://img.shields.io/github/stars/yoryio/CVE-2024-20767.svg) 
![forks](https://img.shields.io/github/forks/yoryio/CVE-2024-20767.svg) 
2024-12-19T04:04:52Z

- [https://github.com/Chocapikk/CVE-2024-20767](https://github.com/Chocapikk/CVE-2024-20767) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2024-20767.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2024-20767.svg) 
2024-03-26T19:21:19Z

- [https://github.com/m-cetin/CVE-2024-20767](https://github.com/m-cetin/CVE-2024-20767) :  
![starts](https://img.shields.io/github/stars/m-cetin/CVE-2024-20767.svg) 
![forks](https://img.shields.io/github/forks/m-cetin/CVE-2024-20767.svg) 
2024-03-26T10:18:46Z

- [https://github.com/Praison001/CVE-2024-20767-Adobe-ColdFusion](https://github.com/Praison001/CVE-2024-20767-Adobe-ColdFusion) :  
![starts](https://img.shields.io/github/stars/Praison001/CVE-2024-20767-Adobe-ColdFusion.svg) 
![forks](https://img.shields.io/github/forks/Praison001/CVE-2024-20767-Adobe-ColdFusion.svg) 
2024-04-01T09:03:31Z

## CVE-2024-12025
 The Collapsing Categories plugin for WordPress is vulnerable to SQL Injection via the 'taxonomy' parameter of the /wp-json/collapsing-categories/v1/get REST API in all versions up to, and including, 3.0.8 due to insufficient escaping on the user supplied parameter and lack of sufficient preparation on the existing SQL query.  This makes it possible for unauthenticated attackers to append additional SQL queries into already existing queries that can be used to extract sensitive information from the database.

- [https://github.com/RandomRobbieBF/CVE-2024-12025](https://github.com/RandomRobbieBF/CVE-2024-12025) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-12025.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-12025.svg) 
2024-12-19T14:16:35Z

## CVE-2024-10793
 The WP Activity Log plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the user_id parameter in all versions up to, and including, 5.2.1 due to insufficient input sanitization and output escaping. This makes it possible for unauthenticated attackers to inject arbitrary web scripts in pages that will execute whenever an administrative user accesses an injected page.

- [https://github.com/windz3r0day/CVE-2024-10793](https://github.com/windz3r0day/CVE-2024-10793) :  
![starts](https://img.shields.io/github/stars/windz3r0day/CVE-2024-10793.svg) 
![forks](https://img.shields.io/github/forks/windz3r0day/CVE-2024-10793.svg) 
2024-11-17T19:51:53Z

- [https://github.com/MAHajian/CVE-2024-10793](https://github.com/MAHajian/CVE-2024-10793) :  
![starts](https://img.shields.io/github/stars/MAHajian/CVE-2024-10793.svg) 
![forks](https://img.shields.io/github/forks/MAHajian/CVE-2024-10793.svg) 
2024-12-19T16:38:15Z

## CVE-2024-9935
 The PDF Generator Addon for Elementor Page Builder plugin for WordPress is vulnerable to Path Traversal in all versions up to, and including, 1.7.5 via the rtw_pgaepb_dwnld_pdf() function. This makes it possible for unauthenticated attackers to read the contents of arbitrary files on the server, which can contain sensitive information.

- [https://github.com/verylazytech/CVE-2024-9935](https://github.com/verylazytech/CVE-2024-9935) :  
![starts](https://img.shields.io/github/stars/verylazytech/CVE-2024-9935.svg) 
![forks](https://img.shields.io/github/forks/verylazytech/CVE-2024-9935.svg) 
2024-12-19T09:43:37Z

- [https://github.com/RandomRobbieBF/CVE-2024-9935](https://github.com/RandomRobbieBF/CVE-2024-9935) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-9935.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-9935.svg) 
2024-11-18T10:15:49Z

## CVE-2024-5596
 The ARMember Premium plugin for WordPress is vulnerable to Cross-Site Request Forgery in versions up to, and including, 6.7. This is due to incorrectly implemented nonce validation function on multiple functions. This makes it possible for unauthenticated attackers to modify, or delete user meta and plugin options which can lead to limited privilege escalation.

- [https://github.com/null-event/CVE-2024-55968](https://github.com/null-event/CVE-2024-55968) :  
![starts](https://img.shields.io/github/stars/null-event/CVE-2024-55968.svg) 
![forks](https://img.shields.io/github/forks/null-event/CVE-2024-55968.svg) 
2024-12-17T21:14:29Z

- [https://github.com/Wi1DN00B/CVE-2024-55968](https://github.com/Wi1DN00B/CVE-2024-55968) :  
![starts](https://img.shields.io/github/stars/Wi1DN00B/CVE-2024-55968.svg) 
![forks](https://img.shields.io/github/forks/Wi1DN00B/CVE-2024-55968.svg) 
2024-12-19T04:47:30Z

# 2024-12-18
## CVE-2024-49112
 Windows Lightweight Directory Access Protocol (LDAP) Remote Code Execution Vulnerability

- [https://github.com/tnkr/poc_monitor](https://github.com/tnkr/poc_monitor) :  
![starts](https://img.shields.io/github/stars/tnkr/poc_monitor.svg) 
![forks](https://img.shields.io/github/forks/tnkr/poc_monitor.svg) 
2024-12-16T19:35:02Z

- [https://github.com/b0l1o/CVE-2024-49112-PoC](https://github.com/b0l1o/CVE-2024-49112-PoC) :  
![starts](https://img.shields.io/github/stars/b0l1o/CVE-2024-49112-PoC.svg) 
![forks](https://img.shields.io/github/forks/b0l1o/CVE-2024-49112-PoC.svg) 
2024-12-18T01:17:11Z

## CVE-2024-40725
 A partial fix for CVE-2024-39884 in the core of Apache HTTP Server 2.4.61 ignores some use of the legacy content-type based configuration of handlers. "AddType" and similar configuration, under some circumstances where files are requested indirectly, result in source code disclosure of local content. For example, PHP scripts may be served instead of interpreted.Users are recommended to upgrade to version 2.4.62, which fixes this issue.

- [https://github.com/TAM-K592/CVE-2024-40725-CVE-2024-40898](https://github.com/TAM-K592/CVE-2024-40725-CVE-2024-40898) :  
![starts](https://img.shields.io/github/stars/TAM-K592/CVE-2024-40725-CVE-2024-40898.svg) 
![forks](https://img.shields.io/github/forks/TAM-K592/CVE-2024-40725-CVE-2024-40898.svg) 
2024-07-19T04:01:13Z

- [https://github.com/soltanali0/CVE-2024-40725](https://github.com/soltanali0/CVE-2024-40725) :  
![starts](https://img.shields.io/github/stars/soltanali0/CVE-2024-40725.svg) 
![forks](https://img.shields.io/github/forks/soltanali0/CVE-2024-40725.svg) 
2024-12-18T15:12:31Z

- [https://github.com/whiterose7777/CVE-2024-40725-CVE-2024-40898](https://github.com/whiterose7777/CVE-2024-40725-CVE-2024-40898) :  
![starts](https://img.shields.io/github/stars/whiterose7777/CVE-2024-40725-CVE-2024-40898.svg) 
![forks](https://img.shields.io/github/forks/whiterose7777/CVE-2024-40725-CVE-2024-40898.svg) 
2024-11-11T09:01:01Z

## CVE-2024-29296
 A user enumeration vulnerability was found in Portainer CE 2.19.4. This issue occurs during user authentication process, where a difference in response time could allow a remote unauthenticated user to determine if a username is valid or not.

- [https://github.com/ThaySolis/CVE-2024-29296](https://github.com/ThaySolis/CVE-2024-29296) :  
![starts](https://img.shields.io/github/stars/ThaySolis/CVE-2024-29296.svg) 
![forks](https://img.shields.io/github/forks/ThaySolis/CVE-2024-29296.svg) 
2024-12-18T01:47:02Z

- [https://github.com/Lavender-exe/CVE-2024-29296-PoC](https://github.com/Lavender-exe/CVE-2024-29296-PoC) :  
![starts](https://img.shields.io/github/stars/Lavender-exe/CVE-2024-29296-PoC.svg) 
![forks](https://img.shields.io/github/forks/Lavender-exe/CVE-2024-29296-PoC.svg) 
2024-04-29T19:12:38Z

## CVE-2024-23653
 BuildKit is a toolkit for converting source code to build artifacts in an efficient, expressive and repeatable manner. In addition to running containers as build steps, BuildKit also provides APIs for running interactive containers based on built images. It was possible to use these APIs to ask BuildKit to run a container with elevated privileges. Normally, running such containers is only allowed if special `security.insecure` entitlement is enabled both by buildkitd configuration and allowed by the user initializing the build request. The issue has been fixed in v0.12.5 . Avoid using BuildKit frontends from untrusted sources.

- [https://github.com/666asd/CVE-2024-23653](https://github.com/666asd/CVE-2024-23653) :  
![starts](https://img.shields.io/github/stars/666asd/CVE-2024-23653.svg) 
![forks](https://img.shields.io/github/forks/666asd/CVE-2024-23653.svg) 
2024-12-18T17:31:56Z

## CVE-2024-23298
 A logic issue was addressed with improved state management.

- [https://github.com/p1tsi/CVE-2024-23298.app](https://github.com/p1tsi/CVE-2024-23298.app) :  
![starts](https://img.shields.io/github/stars/p1tsi/CVE-2024-23298.app.svg) 
![forks](https://img.shields.io/github/forks/p1tsi/CVE-2024-23298.app.svg) 
2024-12-18T18:15:28Z

## CVE-2024-4876
 The HT Mega  Absolute Addons For Elementor plugin for WordPress is vulnerable to Stored Cross-Site Scripting via the popover_header_text parameter in versions up to, and including, 2.5.2 due to insufficient input sanitization and output escaping. This makes it possible for authenticated attackers, with contributor-level permissions and above, to inject arbitrary web scripts in pages that will execute whenever a user accesses an injected page.

- [https://github.com/YZS17/CVE-2024-48762](https://github.com/YZS17/CVE-2024-48762) :  
![starts](https://img.shields.io/github/stars/YZS17/CVE-2024-48762.svg) 
![forks](https://img.shields.io/github/forks/YZS17/CVE-2024-48762.svg) 
2024-12-18T13:37:17Z

## CVE-2024-1197
 A vulnerability, which was classified as critical, has been found in SourceCodester Testimonial Page Manager 1.0. This issue affects some unknown processing of the file delete-testimonial.php of the component HTTP GET Request Handler. The manipulation of the argument testimony leads to sql injection. The attack may be initiated remotely. The associated identifier of this vulnerability is VDB-252695.

- [https://github.com/JunTakemura/exploit-CVE-2024-11972](https://github.com/JunTakemura/exploit-CVE-2024-11972) :  
![starts](https://img.shields.io/github/stars/JunTakemura/exploit-CVE-2024-11972.svg) 
![forks](https://img.shields.io/github/forks/JunTakemura/exploit-CVE-2024-11972.svg) 
2024-12-18T07:17:01Z

# 2024-12-17
## CVE-2024-55557
 ui/pref/ProxyPrefView.java in weasis-core in Weasis 4.5.1 has a hardcoded key for symmetric encryption of proxy credentials.

- [https://github.com/partywavesec/CVE-2024-55557](https://github.com/partywavesec/CVE-2024-55557) :  
![starts](https://img.shields.io/github/stars/partywavesec/CVE-2024-55557.svg) 
![forks](https://img.shields.io/github/forks/partywavesec/CVE-2024-55557.svg) 
2024-12-17T10:24:18Z

## CVE-2024-49124
 Lightweight Directory Access Protocol (LDAP) Client Remote Code Execution Vulnerability

- [https://github.com/mutkus/Microsoft-2024-December-Update-Control](https://github.com/mutkus/Microsoft-2024-December-Update-Control) :  
![starts](https://img.shields.io/github/stars/mutkus/Microsoft-2024-December-Update-Control.svg) 
![forks](https://img.shields.io/github/forks/mutkus/Microsoft-2024-December-Update-Control.svg) 
2024-12-17T21:21:32Z

## CVE-2024-49122
 Microsoft Message Queuing (MSMQ) Remote Code Execution Vulnerability

- [https://github.com/mutkus/Microsoft-2024-December-Update-Control](https://github.com/mutkus/Microsoft-2024-December-Update-Control) :  
![starts](https://img.shields.io/github/stars/mutkus/Microsoft-2024-December-Update-Control.svg) 
![forks](https://img.shields.io/github/forks/mutkus/Microsoft-2024-December-Update-Control.svg) 
2024-12-17T21:21:32Z

## CVE-2024-49118
 Microsoft Message Queuing (MSMQ) Remote Code Execution Vulnerability

- [https://github.com/mutkus/Microsoft-2024-December-Update-Control](https://github.com/mutkus/Microsoft-2024-December-Update-Control) :  
![starts](https://img.shields.io/github/stars/mutkus/Microsoft-2024-December-Update-Control.svg) 
![forks](https://img.shields.io/github/forks/mutkus/Microsoft-2024-December-Update-Control.svg) 
2024-12-17T21:21:32Z

## CVE-2024-49117
 Windows Hyper-V Remote Code Execution Vulnerability

- [https://github.com/mutkus/Microsoft-2024-December-Update-Control](https://github.com/mutkus/Microsoft-2024-December-Update-Control) :  
![starts](https://img.shields.io/github/stars/mutkus/Microsoft-2024-December-Update-Control.svg) 
![forks](https://img.shields.io/github/forks/mutkus/Microsoft-2024-December-Update-Control.svg) 
2024-12-17T21:21:32Z

## CVE-2024-45337
 Applications and libraries which misuse the ServerConfig.PublicKeyCallback callback may be susceptible to an authorization bypass. The documentation for ServerConfig.PublicKeyCallback says that "A call to this function does not guarantee that the key offered is in fact used to authenticate." Specifically, the SSH protocol allows clients to inquire about whether a public key is acceptable before proving control of the corresponding private key. PublicKeyCallback may be called with multiple keys, and the order in which the keys were provided cannot be used to infer which key the client successfully authenticated with, if any. Some applications, which store the key(s) passed to PublicKeyCallback (or derived information) and make security relevant determinations based on it once the connection is established, may make incorrect assumptions. For example, an attacker may send public keys A and B, and then authenticate with A. PublicKeyCallback would be called only twice, first with A and then with B. A vulnerable application may then make authorization decisions based on key B for which the attacker does not actually control the private key. Since this API is widely misused, as a partial mitigation golang.org/x/cry...@v0.31.0 enforces the property that, when successfully authenticating via public key, the last key passed to ServerConfig.PublicKeyCallback will be the key used to authenticate the connection. PublicKeyCallback will now be called multiple times with the same key, if necessary. Note that the client may still not control the last key passed to PublicKeyCallback if the connection is then authenticated with a different method, such as PasswordCallback, KeyboardInteractiveCallback, or NoClientAuth. Users should be using the Extensions field of the Permissions return value from the various authentication callbacks to record data associated with the authentication attempt instead of referencing external state. Once the connection is established the state corresponding to the successful authentication attempt can be retrieved via the ServerConn.Permissions field. Note that some third-party libraries misuse the Permissions type by sharing it across authentication attempts; users of third-party libraries should refer to the relevant projects for guidance.

- [https://github.com/NHAS/CVE-2024-45337-POC](https://github.com/NHAS/CVE-2024-45337-POC) :  
![starts](https://img.shields.io/github/stars/NHAS/CVE-2024-45337-POC.svg) 
![forks](https://img.shields.io/github/forks/NHAS/CVE-2024-45337-POC.svg) 
2024-12-17T22:27:03Z

- [https://github.com/NHAS/VULNERABLE-CVE-2024-45337](https://github.com/NHAS/VULNERABLE-CVE-2024-45337) :  
![starts](https://img.shields.io/github/stars/NHAS/VULNERABLE-CVE-2024-45337.svg) 
![forks](https://img.shields.io/github/forks/NHAS/VULNERABLE-CVE-2024-45337.svg) 
2024-12-17T22:25:48Z

## CVE-2024-29671
 Buffer Overflow vulnerability in NEXTU FLATA AX1500 Router v.1.0.2 allows a remote attacker to execute arbitrary code via the POST request handler component.

- [https://github.com/laskdjlaskdj12/CVE-2024-29671-POC](https://github.com/laskdjlaskdj12/CVE-2024-29671-POC) :  
![starts](https://img.shields.io/github/stars/laskdjlaskdj12/CVE-2024-29671-POC.svg) 
![forks](https://img.shields.io/github/forks/laskdjlaskdj12/CVE-2024-29671-POC.svg) 
2024-12-17T12:22:24Z

## CVE-2024-12356
 A critical vulnerability has been discovered in Privileged Remote Access (PRA) and Remote Support (RS) products which can allow an unauthenticated attacker to inject commands that are run as a site user.

- [https://github.com/cloudefence/CVE-2024-12356](https://github.com/cloudefence/CVE-2024-12356) :  
![starts](https://img.shields.io/github/stars/cloudefence/CVE-2024-12356.svg) 
![forks](https://img.shields.io/github/forks/cloudefence/CVE-2024-12356.svg) 
2024-12-17T15:31:40Z

## CVE-2024-10220
 The Kubernetes kubelet component allows arbitrary command execution via specially crafted gitRepo volumes.This issue affects kubelet: through 1.28.11, from 1.29.0 through 1.29.6, from 1.30.0 through 1.30.2.

- [https://github.com/XiaomingX/cve-2024-10220-githooks](https://github.com/XiaomingX/cve-2024-10220-githooks) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-10220-githooks.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-10220-githooks.svg) 
2024-12-01T05:18:39Z

- [https://github.com/mochizuki875/CVE-2024-10220-githooks](https://github.com/mochizuki875/CVE-2024-10220-githooks) :  
![starts](https://img.shields.io/github/stars/mochizuki875/CVE-2024-10220-githooks.svg) 
![forks](https://img.shields.io/github/forks/mochizuki875/CVE-2024-10220-githooks.svg) 
2024-11-21T07:28:49Z

- [https://github.com/candranapits/poc-CVE-2024-10220](https://github.com/candranapits/poc-CVE-2024-10220) :  
![starts](https://img.shields.io/github/stars/candranapits/poc-CVE-2024-10220.svg) 
![forks](https://img.shields.io/github/forks/candranapits/poc-CVE-2024-10220.svg) 
2024-12-17T08:19:55Z

- [https://github.com/any2sec/cve-2024-10220](https://github.com/any2sec/cve-2024-10220) :  
![starts](https://img.shields.io/github/stars/any2sec/cve-2024-10220.svg) 
![forks](https://img.shields.io/github/forks/any2sec/cve-2024-10220.svg) 
2024-11-29T11:24:00Z

- [https://github.com/filipzag/CVE-2024-10220](https://github.com/filipzag/CVE-2024-10220) :  
![starts](https://img.shields.io/github/stars/filipzag/CVE-2024-10220.svg) 
![forks](https://img.shields.io/github/forks/filipzag/CVE-2024-10220.svg) 
2024-12-15T11:34:21Z

# 2024-12-16
## CVE-2024-56116
 A Cross-Site Request Forgery vulnerability in Amiro.CMS before 7.8.4 allows remote attackers to create an administrator account.

- [https://github.com/ComplianceControl/CVE-2024-56116](https://github.com/ComplianceControl/CVE-2024-56116) :  
![starts](https://img.shields.io/github/stars/ComplianceControl/CVE-2024-56116.svg) 
![forks](https://img.shields.io/github/forks/ComplianceControl/CVE-2024-56116.svg) 
2024-12-16T07:46:15Z

## CVE-2024-56115
 A vulnerability in Amiro.CMS before 7.8.4 exists due to the failure to take measures to neutralize special elements. It allows remote attackers to conduct a Cross-Site Scripting (XSS) attack.

- [https://github.com/ComplianceControl/CVE-2024-56115](https://github.com/ComplianceControl/CVE-2024-56115) :  
![starts](https://img.shields.io/github/stars/ComplianceControl/CVE-2024-56115.svg) 
![forks](https://img.shields.io/github/forks/ComplianceControl/CVE-2024-56115.svg) 
2024-12-16T07:47:05Z

## CVE-2024-50509
 Improper Limitation of a Pathname to a Restricted Directory ('Path Traversal') vulnerability in Chetan Khandla Woocommerce Product Design allows Path Traversal.This issue affects Woocommerce Product Design: from n/a through 1.0.0.

- [https://github.com/RandomRobbieBF/CVE-2024-50509](https://github.com/RandomRobbieBF/CVE-2024-50509) :  
![starts](https://img.shields.io/github/stars/RandomRobbieBF/CVE-2024-50509.svg) 
![forks](https://img.shields.io/github/forks/RandomRobbieBF/CVE-2024-50509.svg) 
2024-12-16T19:53:11Z

## CVE-2024-49039
 Windows Task Scheduler Elevation of Privilege Vulnerability

- [https://github.com/je5442804/WPTaskScheduler_CVE-2024-49039](https://github.com/je5442804/WPTaskScheduler_CVE-2024-49039) :  
![starts](https://img.shields.io/github/stars/je5442804/WPTaskScheduler_CVE-2024-49039.svg) 
![forks](https://img.shields.io/github/forks/je5442804/WPTaskScheduler_CVE-2024-49039.svg) 
2024-11-19T09:15:26Z

- [https://github.com/Alexandr-bit253/CVE-2024-49039](https://github.com/Alexandr-bit253/CVE-2024-49039) :  
![starts](https://img.shields.io/github/stars/Alexandr-bit253/CVE-2024-49039.svg) 
![forks](https://img.shields.io/github/forks/Alexandr-bit253/CVE-2024-49039.svg) 
2024-12-16T13:28:19Z

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

## CVE-2024-24549
 Denial of Service due to improper input validation vulnerability for HTTP/2 requests in Apache Tomcat. When processing an HTTP/2 request, if the request exceeded any of the configured limits for headers, the associated HTTP/2 stream was not reset until after all of the headers had been processed.This issue affects Apache Tomcat: from 11.0.0-M1 through 11.0.0-M16, from 10.1.0-M1 through 10.1.18, from 9.0.0-M1 through 9.0.85, from 8.5.0 through 8.5.98.Users are recommended to upgrade to version 11.0.0-M17, 10.1.19, 9.0.86 or 8.5.99 which fix the issue.

- [https://github.com/JFOZ1010/CVE-2024-24549](https://github.com/JFOZ1010/CVE-2024-24549) :  
![starts](https://img.shields.io/github/stars/JFOZ1010/CVE-2024-24549.svg) 
![forks](https://img.shields.io/github/forks/JFOZ1010/CVE-2024-24549.svg) 
2024-12-16T23:48:12Z

- [https://github.com/Abdurahmon3236/CVE-2024-24549](https://github.com/Abdurahmon3236/CVE-2024-24549) :  
![starts](https://img.shields.io/github/stars/Abdurahmon3236/CVE-2024-24549.svg) 
![forks](https://img.shields.io/github/forks/Abdurahmon3236/CVE-2024-24549.svg) 
2024-09-01T14:10:12Z

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

- [https://github.com/redspy-sec/D-Link](https://github.com/redspy-sec/D-Link) :  
![starts](https://img.shields.io/github/stars/redspy-sec/D-Link.svg) 
![forks](https://img.shields.io/github/forks/redspy-sec/D-Link.svg) 
2024-12-07T07:32:30Z

- [https://github.com/ThemeHackers/CVE-2024-10914](https://github.com/ThemeHackers/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/ThemeHackers/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/ThemeHackers/CVE-2024-10914.svg) 
2024-12-16T14:08:53Z

- [https://github.com/Bu0uCat/D-Link-NAS-CVE-2024-10914-](https://github.com/Bu0uCat/D-Link-NAS-CVE-2024-10914-) :  
![starts](https://img.shields.io/github/stars/Bu0uCat/D-Link-NAS-CVE-2024-10914-.svg) 
![forks](https://img.shields.io/github/forks/Bu0uCat/D-Link-NAS-CVE-2024-10914-.svg) 
2024-11-15T07:59:36Z

- [https://github.com/Egi08/CVE-2024-10914](https://github.com/Egi08/CVE-2024-10914) :  
![starts](https://img.shields.io/github/stars/Egi08/CVE-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/Egi08/CVE-2024-10914.svg) 
2024-11-13T09:39:25Z

- [https://github.com/retuci0/cve-2024-10914-port](https://github.com/retuci0/cve-2024-10914-port) :  
![starts](https://img.shields.io/github/stars/retuci0/cve-2024-10914-port.svg) 
![forks](https://img.shields.io/github/forks/retuci0/cve-2024-10914-port.svg) 
2024-11-27T19:12:45Z

- [https://github.com/K3ysTr0K3R/CVE-2024-10914-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2024-10914-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2024-10914-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2024-10914-EXPLOIT.svg) 
2024-11-27T23:31:07Z

- [https://github.com/jahithoque/CVE-2024-10914-Exploit](https://github.com/jahithoque/CVE-2024-10914-Exploit) :  
![starts](https://img.shields.io/github/stars/jahithoque/CVE-2024-10914-Exploit.svg) 
![forks](https://img.shields.io/github/forks/jahithoque/CVE-2024-10914-Exploit.svg) 
2024-12-04T05:31:23Z

## CVE-2024-9264
 The SQL Expressions experimental feature of Grafana allows for the evaluation of `duckdb` queries containing user input. These queries are insufficiently sanitized before being passed to `duckdb`, leading to a command injection and local file inclusion vulnerability. Any user with the VIEWER or higher permission is capable of executing this attack.  The `duckdb` binary must be present in Grafana's $PATH for this attack to function; by default, this binary is not installed in Grafana distributions.

- [https://github.com/nollium/CVE-2024-9264](https://github.com/nollium/CVE-2024-9264) :  
![starts](https://img.shields.io/github/stars/nollium/CVE-2024-9264.svg) 
![forks](https://img.shields.io/github/forks/nollium/CVE-2024-9264.svg) 
2024-12-16T20:15:28Z

- [https://github.com/z3k0sec/CVE-2024-9264-RCE-Exploit](https://github.com/z3k0sec/CVE-2024-9264-RCE-Exploit) :  
![starts](https://img.shields.io/github/stars/z3k0sec/CVE-2024-9264-RCE-Exploit.svg) 
![forks](https://img.shields.io/github/forks/z3k0sec/CVE-2024-9264-RCE-Exploit.svg) 
2024-10-21T22:31:47Z

- [https://github.com/z3k0sec/File-Read-CVE-2024-9264](https://github.com/z3k0sec/File-Read-CVE-2024-9264) :  
![starts](https://img.shields.io/github/stars/z3k0sec/File-Read-CVE-2024-9264.svg) 
![forks](https://img.shields.io/github/forks/z3k0sec/File-Read-CVE-2024-9264.svg) 
2024-10-20T11:46:34Z

- [https://github.com/punitdarji/Grafana-CVE-2024-9264](https://github.com/punitdarji/Grafana-CVE-2024-9264) :  
![starts](https://img.shields.io/github/stars/punitdarji/Grafana-CVE-2024-9264.svg) 
![forks](https://img.shields.io/github/forks/punitdarji/Grafana-CVE-2024-9264.svg) 
2024-10-21T10:26:13Z

## CVE-2024-1086
 A use-after-free vulnerability in the Linux kernel's netfilter: nf_tables component can be exploited to achieve local privilege escalation.The nft_verdict_init() function allows positive values as drop error within the hook verdict, and hence the nf_hook_slow() function can cause a double free vulnerability when NF_DROP is issued with a drop error which resembles NF_ACCEPT.We recommend upgrading past commit f342de4e2f33e0e39165d8639387aa6c19dff660.

- [https://github.com/Notselwyn/CVE-2024-1086](https://github.com/Notselwyn/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/Notselwyn/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/Notselwyn/CVE-2024-1086.svg) 
2024-04-17T16:09:54Z

- [https://github.com/LLfam/CVE-2024-1086](https://github.com/LLfam/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/LLfam/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/LLfam/CVE-2024-1086.svg) 
2024-12-16T17:38:23Z

- [https://github.com/Alicey0719/docker-POC_CVE-2024-1086](https://github.com/Alicey0719/docker-POC_CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/Alicey0719/docker-POC_CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/Alicey0719/docker-POC_CVE-2024-1086.svg) 
2024-05-19T06:51:46Z

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

- [https://github.com/kevcooper/CVE-2024-1086-checker](https://github.com/kevcooper/CVE-2024-1086-checker) :  
![starts](https://img.shields.io/github/stars/kevcooper/CVE-2024-1086-checker.svg) 
![forks](https://img.shields.io/github/forks/kevcooper/CVE-2024-1086-checker.svg) 
2024-06-10T17:13:07Z

## CVE-2023-38831
 RARLAB WinRAR before 6.23 allows attackers to execute arbitrary code when a user attempts to view a benign file within a ZIP archive. The issue occurs because a ZIP archive may include a benign file (such as an ordinary .JPG file) and also a folder that has the same name as the benign file, and the contents of the folder (which may include executable content) are processed during an attempt to access only the benign file. This was exploited in the wild in April through October 2023.

- [https://github.com/b1tg/CVE-2023-38831-winrar-exploit](https://github.com/b1tg/CVE-2023-38831-winrar-exploit) :  
![starts](https://img.shields.io/github/stars/b1tg/CVE-2023-38831-winrar-exploit.svg) 
![forks](https://img.shields.io/github/forks/b1tg/CVE-2023-38831-winrar-exploit.svg) 
2023-11-26T06:46:44Z

- [https://github.com/Garck3h/cve-2023-38831](https://github.com/Garck3h/cve-2023-38831) :  
![starts](https://img.shields.io/github/stars/Garck3h/cve-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/Garck3h/cve-2023-38831.svg) 
2023-08-27T14:35:00Z

- [https://github.com/ignis-sec/CVE-2023-38831-RaRCE](https://github.com/ignis-sec/CVE-2023-38831-RaRCE) :  
![starts](https://img.shields.io/github/stars/ignis-sec/CVE-2023-38831-RaRCE.svg) 
![forks](https://img.shields.io/github/forks/ignis-sec/CVE-2023-38831-RaRCE.svg) 
2023-08-27T22:17:56Z

- [https://github.com/BoredHackerBlog/winrar_CVE-2023-38831_lazy_poc](https://github.com/BoredHackerBlog/winrar_CVE-2023-38831_lazy_poc) :  
![starts](https://img.shields.io/github/stars/BoredHackerBlog/winrar_CVE-2023-38831_lazy_poc.svg) 
![forks](https://img.shields.io/github/forks/BoredHackerBlog/winrar_CVE-2023-38831_lazy_poc.svg) 
2023-08-24T16:13:02Z

- [https://github.com/HDCE-inc/CVE-2023-38831](https://github.com/HDCE-inc/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/HDCE-inc/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/HDCE-inc/CVE-2023-38831.svg) 
2024-08-04T01:00:35Z

- [https://github.com/knight0x07/WinRAR-Code-Execution-Vulnerability-CVE-2023-38831](https://github.com/knight0x07/WinRAR-Code-Execution-Vulnerability-CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/knight0x07/WinRAR-Code-Execution-Vulnerability-CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/knight0x07/WinRAR-Code-Execution-Vulnerability-CVE-2023-38831.svg) 
2023-08-28T15:33:27Z

- [https://github.com/Maalfer/CVE-2023-38831_ReverseShell_Winrar-RCE](https://github.com/Maalfer/CVE-2023-38831_ReverseShell_Winrar-RCE) :  
![starts](https://img.shields.io/github/stars/Maalfer/CVE-2023-38831_ReverseShell_Winrar-RCE.svg) 
![forks](https://img.shields.io/github/forks/Maalfer/CVE-2023-38831_ReverseShell_Winrar-RCE.svg) 
2023-08-31T07:40:12Z

- [https://github.com/xaitax/WinRAR-CVE-2023-38831](https://github.com/xaitax/WinRAR-CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/xaitax/WinRAR-CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/xaitax/WinRAR-CVE-2023-38831.svg) 
2023-09-08T06:15:42Z

- [https://github.com/ahmed-fa7im/CVE-2023-38831-winrar-expoit-simple-Poc](https://github.com/ahmed-fa7im/CVE-2023-38831-winrar-expoit-simple-Poc) :  
![starts](https://img.shields.io/github/stars/ahmed-fa7im/CVE-2023-38831-winrar-expoit-simple-Poc.svg) 
![forks](https://img.shields.io/github/forks/ahmed-fa7im/CVE-2023-38831-winrar-expoit-simple-Poc.svg) 
2023-08-28T23:51:31Z

- [https://github.com/Malwareman007/CVE-2023-38831](https://github.com/Malwareman007/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/Malwareman007/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/Malwareman007/CVE-2023-38831.svg) 
2023-09-12T16:39:44Z

- [https://github.com/youmulijiang/evil-winrar](https://github.com/youmulijiang/evil-winrar) :  
![starts](https://img.shields.io/github/stars/youmulijiang/evil-winrar.svg) 
![forks](https://img.shields.io/github/forks/youmulijiang/evil-winrar.svg) 
2024-03-25T14:38:29Z

- [https://github.com/MorDavid/CVE-2023-38831-Winrar-Exploit-Generator-POC](https://github.com/MorDavid/CVE-2023-38831-Winrar-Exploit-Generator-POC) :  
![starts](https://img.shields.io/github/stars/MorDavid/CVE-2023-38831-Winrar-Exploit-Generator-POC.svg) 
![forks](https://img.shields.io/github/forks/MorDavid/CVE-2023-38831-Winrar-Exploit-Generator-POC.svg) 
2023-08-31T15:07:51Z

- [https://github.com/z3r0sw0rd/CVE-2023-38831-PoC](https://github.com/z3r0sw0rd/CVE-2023-38831-PoC) :  
![starts](https://img.shields.io/github/stars/z3r0sw0rd/CVE-2023-38831-PoC.svg) 
![forks](https://img.shields.io/github/forks/z3r0sw0rd/CVE-2023-38831-PoC.svg) 
2023-09-01T07:37:20Z

- [https://github.com/PascalAsch/CVE-2023-38831-KQL](https://github.com/PascalAsch/CVE-2023-38831-KQL) :  
![starts](https://img.shields.io/github/stars/PascalAsch/CVE-2023-38831-KQL.svg) 
![forks](https://img.shields.io/github/forks/PascalAsch/CVE-2023-38831-KQL.svg) 
2023-08-28T16:06:17Z

- [https://github.com/xk-mt/WinRAR-Vulnerability-recurrence-tutorial](https://github.com/xk-mt/WinRAR-Vulnerability-recurrence-tutorial) :  
![starts](https://img.shields.io/github/stars/xk-mt/WinRAR-Vulnerability-recurrence-tutorial.svg) 
![forks](https://img.shields.io/github/forks/xk-mt/WinRAR-Vulnerability-recurrence-tutorial.svg) 
2024-01-15T08:32:01Z

- [https://github.com/akhomlyuk/cve-2023-38831](https://github.com/akhomlyuk/cve-2023-38831) :  
![starts](https://img.shields.io/github/stars/akhomlyuk/cve-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/akhomlyuk/cve-2023-38831.svg) 
2023-08-28T15:35:43Z

- [https://github.com/malvika-thakur/CVE-2023-38831](https://github.com/malvika-thakur/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/malvika-thakur/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/malvika-thakur/CVE-2023-38831.svg) 
2023-09-21T09:30:59Z

- [https://github.com/Mich-ele/CVE-2023-38831-winrar](https://github.com/Mich-ele/CVE-2023-38831-winrar) :  
![starts](https://img.shields.io/github/stars/Mich-ele/CVE-2023-38831-winrar.svg) 
![forks](https://img.shields.io/github/forks/Mich-ele/CVE-2023-38831-winrar.svg) 
2023-09-01T17:43:16Z

- [https://github.com/ameerpornillos/CVE-2023-38831-WinRAR-Exploit](https://github.com/ameerpornillos/CVE-2023-38831-WinRAR-Exploit) :  
![starts](https://img.shields.io/github/stars/ameerpornillos/CVE-2023-38831-WinRAR-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ameerpornillos/CVE-2023-38831-WinRAR-Exploit.svg) 
2023-09-12T16:26:22Z

- [https://github.com/UnHackerEnCapital/PDFernetRemotelo](https://github.com/UnHackerEnCapital/PDFernetRemotelo) :  
![starts](https://img.shields.io/github/stars/UnHackerEnCapital/PDFernetRemotelo.svg) 
![forks](https://img.shields.io/github/forks/UnHackerEnCapital/PDFernetRemotelo.svg) 
2024-06-20T00:02:49Z

- [https://github.com/SugiB3o/Keylog_CVE2023-38831](https://github.com/SugiB3o/Keylog_CVE2023-38831) :  
![starts](https://img.shields.io/github/stars/SugiB3o/Keylog_CVE2023-38831.svg) 
![forks](https://img.shields.io/github/forks/SugiB3o/Keylog_CVE2023-38831.svg) 
2023-08-30T12:55:44Z

- [https://github.com/IR-HuntGuardians/CVE-2023-38831-HUNT](https://github.com/IR-HuntGuardians/CVE-2023-38831-HUNT) :  
![starts](https://img.shields.io/github/stars/IR-HuntGuardians/CVE-2023-38831-HUNT.svg) 
![forks](https://img.shields.io/github/forks/IR-HuntGuardians/CVE-2023-38831-HUNT.svg) 
2023-08-27T08:52:19Z

- [https://github.com/r1yaz/winDED](https://github.com/r1yaz/winDED) :  
![starts](https://img.shields.io/github/stars/r1yaz/winDED.svg) 
![forks](https://img.shields.io/github/forks/r1yaz/winDED.svg) 
2023-12-28T18:48:21Z

- [https://github.com/ruycr4ft/CVE-2023-38831](https://github.com/ruycr4ft/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/ruycr4ft/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/ruycr4ft/CVE-2023-38831.svg) 
2023-10-12T13:23:29Z

- [https://github.com/SpamixOfficial/CVE-2023-38831](https://github.com/SpamixOfficial/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/SpamixOfficial/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/SpamixOfficial/CVE-2023-38831.svg) 
2023-12-20T11:24:29Z

- [https://github.com/elefantesagradodeluzinfinita/cve-2023-38831](https://github.com/elefantesagradodeluzinfinita/cve-2023-38831) :  
![starts](https://img.shields.io/github/stars/elefantesagradodeluzinfinita/cve-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/elefantesagradodeluzinfinita/cve-2023-38831.svg) 
2023-09-24T05:30:38Z

- [https://github.com/yezzfusl/cve_2023_38831_scanner](https://github.com/yezzfusl/cve_2023_38831_scanner) :  
![starts](https://img.shields.io/github/stars/yezzfusl/cve_2023_38831_scanner.svg) 
![forks](https://img.shields.io/github/forks/yezzfusl/cve_2023_38831_scanner.svg) 
2024-12-02T04:08:41Z

- [https://github.com/s4m98/winrar-cve-2023-38831-poc-gen](https://github.com/s4m98/winrar-cve-2023-38831-poc-gen) :  
![starts](https://img.shields.io/github/stars/s4m98/winrar-cve-2023-38831-poc-gen.svg) 
![forks](https://img.shields.io/github/forks/s4m98/winrar-cve-2023-38831-poc-gen.svg) 
2023-11-07T05:24:44Z

- [https://github.com/BeniB3astt/CVE-2023-38831_ReverseShell_Winrar](https://github.com/BeniB3astt/CVE-2023-38831_ReverseShell_Winrar) :  
![starts](https://img.shields.io/github/stars/BeniB3astt/CVE-2023-38831_ReverseShell_Winrar.svg) 
![forks](https://img.shields.io/github/forks/BeniB3astt/CVE-2023-38831_ReverseShell_Winrar.svg) 
2023-08-30T18:11:13Z

- [https://github.com/MaorBuskila/Windows-X64-RAT](https://github.com/MaorBuskila/Windows-X64-RAT) :  
![starts](https://img.shields.io/github/stars/MaorBuskila/Windows-X64-RAT.svg) 
![forks](https://img.shields.io/github/forks/MaorBuskila/Windows-X64-RAT.svg) 
2024-07-23T17:30:46Z

- [https://github.com/TranKuBao/winrar_CVE2023-38831](https://github.com/TranKuBao/winrar_CVE2023-38831) :  
![starts](https://img.shields.io/github/stars/TranKuBao/winrar_CVE2023-38831.svg) 
![forks](https://img.shields.io/github/forks/TranKuBao/winrar_CVE2023-38831.svg) 
2024-12-13T08:18:59Z

- [https://github.com/kehrijksen/CVE-2023-38831](https://github.com/kehrijksen/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/kehrijksen/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/kehrijksen/CVE-2023-38831.svg) 
2023-10-24T01:26:50Z

- [https://github.com/FirFirdaus/CVE-2023-38831](https://github.com/FirFirdaus/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/FirFirdaus/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/FirFirdaus/CVE-2023-38831.svg) 
2024-08-31T08:33:08Z

- [https://github.com/sh770/CVE-2023-38831](https://github.com/sh770/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/sh770/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/sh770/CVE-2023-38831.svg) 
2023-08-30T10:23:24Z

- [https://github.com/an040702/CVE-2023-38831](https://github.com/an040702/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/an040702/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/an040702/CVE-2023-38831.svg) 
2023-09-17T05:26:44Z

- [https://github.com/Nielk74/CVE-2023-38831](https://github.com/Nielk74/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/Nielk74/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/Nielk74/CVE-2023-38831.svg) 
2023-10-21T17:16:33Z

- [https://github.com/RomainBayle08/CVE-2023-38831](https://github.com/RomainBayle08/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/RomainBayle08/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/RomainBayle08/CVE-2023-38831.svg) 
2024-04-06T17:00:28Z

- [https://github.com/asepsaepdin/CVE-2023-38831](https://github.com/asepsaepdin/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/asepsaepdin/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/asepsaepdin/CVE-2023-38831.svg) 
2023-09-03T14:08:09Z

- [https://github.com/idkwastaken/CVE-2023-38831](https://github.com/idkwastaken/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/idkwastaken/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/idkwastaken/CVE-2023-38831.svg) 
2024-10-15T06:30:41Z

- [https://github.com/thegr1ffyn/CVE-2023-38831](https://github.com/thegr1ffyn/CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/thegr1ffyn/CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/thegr1ffyn/CVE-2023-38831.svg) 
2023-08-29T06:36:44Z

- [https://github.com/GOTonyGO/CVE-2023-38831-winrar](https://github.com/GOTonyGO/CVE-2023-38831-winrar) :  
![starts](https://img.shields.io/github/stars/GOTonyGO/CVE-2023-38831-winrar.svg) 
![forks](https://img.shields.io/github/forks/GOTonyGO/CVE-2023-38831-winrar.svg) 
2023-09-07T06:45:37Z

- [https://github.com/khanhtranngoccva/cve-2023-38831-poc](https://github.com/khanhtranngoccva/cve-2023-38831-poc) :  
![starts](https://img.shields.io/github/stars/khanhtranngoccva/cve-2023-38831-poc.svg) 
![forks](https://img.shields.io/github/forks/khanhtranngoccva/cve-2023-38831-poc.svg) 
2024-07-16T13:54:51Z

- [https://github.com/technicalcorp0/CVE-2023-38831-Exploit](https://github.com/technicalcorp0/CVE-2023-38831-Exploit) :  
![starts](https://img.shields.io/github/stars/technicalcorp0/CVE-2023-38831-Exploit.svg) 
![forks](https://img.shields.io/github/forks/technicalcorp0/CVE-2023-38831-Exploit.svg) 
2024-09-27T18:28:05Z

- [https://github.com/MyStuffYT/CVE-2023-38831-POC](https://github.com/MyStuffYT/CVE-2023-38831-POC) :  
![starts](https://img.shields.io/github/stars/MyStuffYT/CVE-2023-38831-POC.svg) 
![forks](https://img.shields.io/github/forks/MyStuffYT/CVE-2023-38831-POC.svg) 
2024-03-01T20:54:54Z

- [https://github.com/RonF98/CVE-2023-38831-POC](https://github.com/RonF98/CVE-2023-38831-POC) :  
![starts](https://img.shields.io/github/stars/RonF98/CVE-2023-38831-POC.svg) 
![forks](https://img.shields.io/github/forks/RonF98/CVE-2023-38831-POC.svg) 
2024-11-19T14:07:27Z

- [https://github.com/VictoriousKnight/CVE-2023-38831_Exploit](https://github.com/VictoriousKnight/CVE-2023-38831_Exploit) :  
![starts](https://img.shields.io/github/stars/VictoriousKnight/CVE-2023-38831_Exploit.svg) 
![forks](https://img.shields.io/github/forks/VictoriousKnight/CVE-2023-38831_Exploit.svg) 
2024-12-16T15:10:46Z

- [https://github.com/h3xecute/SideCopy-Exploits-CVE-2023-38831](https://github.com/h3xecute/SideCopy-Exploits-CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/h3xecute/SideCopy-Exploits-CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/h3xecute/SideCopy-Exploits-CVE-2023-38831.svg) 
2023-11-01T09:06:27Z

- [https://github.com/ra3edAJ/LAB-DFIR-cve-2023-38831](https://github.com/ra3edAJ/LAB-DFIR-cve-2023-38831) :  
![starts](https://img.shields.io/github/stars/ra3edAJ/LAB-DFIR-cve-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/ra3edAJ/LAB-DFIR-cve-2023-38831.svg) 
2024-09-26T19:49:30Z

- [https://github.com/Fa1c0n35/CVE-2023-38831-winrar-exploit](https://github.com/Fa1c0n35/CVE-2023-38831-winrar-exploit) :  
![starts](https://img.shields.io/github/stars/Fa1c0n35/CVE-2023-38831-winrar-exploit.svg) 
![forks](https://img.shields.io/github/forks/Fa1c0n35/CVE-2023-38831-winrar-exploit.svg) 
2023-09-03T14:53:52Z

- [https://github.com/MortySecurity/CVE-2023-38831-Exploit-and-Detection](https://github.com/MortySecurity/CVE-2023-38831-Exploit-and-Detection) :  
![starts](https://img.shields.io/github/stars/MortySecurity/CVE-2023-38831-Exploit-and-Detection.svg) 
![forks](https://img.shields.io/github/forks/MortySecurity/CVE-2023-38831-Exploit-and-Detection.svg) 
2023-08-29T16:15:56Z

- [https://github.com/imbyter/imbyter-WinRAR_CVE-2023-38831](https://github.com/imbyter/imbyter-WinRAR_CVE-2023-38831) :  
![starts](https://img.shields.io/github/stars/imbyter/imbyter-WinRAR_CVE-2023-38831.svg) 
![forks](https://img.shields.io/github/forks/imbyter/imbyter-WinRAR_CVE-2023-38831.svg) 
2024-06-17T07:34:33Z

- [https://github.com/solomon12354/VolleyballSquid-----CVE-2023-38831-and-Bypass-UAC](https://github.com/solomon12354/VolleyballSquid-----CVE-2023-38831-and-Bypass-UAC) :  
![starts](https://img.shields.io/github/stars/solomon12354/VolleyballSquid-----CVE-2023-38831-and-Bypass-UAC.svg) 
![forks](https://img.shields.io/github/forks/solomon12354/VolleyballSquid-----CVE-2023-38831-and-Bypass-UAC.svg) 
2024-06-18T01:15:21Z

- [https://github.com/Hirusha-N/CVE-2021-34527-CVE-2023-38831-and-CVE-2023-32784](https://github.com/Hirusha-N/CVE-2021-34527-CVE-2023-38831-and-CVE-2023-32784) :  
![starts](https://img.shields.io/github/stars/Hirusha-N/CVE-2021-34527-CVE-2023-38831-and-CVE-2023-32784.svg) 
![forks](https://img.shields.io/github/forks/Hirusha-N/CVE-2021-34527-CVE-2023-38831-and-CVE-2023-32784.svg) 
2024-06-25T02:32:37Z

# 2024-12-15
## CVE-2024-21542
 Versions of the package luigi before 3.6.0 are vulnerable to Arbitrary File Write via Archive Extraction (Zip Slip) due to improper destination file path validation in the _extract_packages_archive function.

- [https://github.com/L3ster1337/Poc-CVE-2024-21542](https://github.com/L3ster1337/Poc-CVE-2024-21542) :  
![starts](https://img.shields.io/github/stars/L3ster1337/Poc-CVE-2024-21542.svg) 
![forks](https://img.shields.io/github/forks/L3ster1337/Poc-CVE-2024-21542.svg) 
2024-12-15T22:32:58Z

## CVE-2024-21413
 Microsoft Outlook Remote Code Execution Vulnerability

- [https://github.com/xaitax/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability](https://github.com/xaitax/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability) :  
![starts](https://img.shields.io/github/stars/xaitax/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability.svg) 
![forks](https://img.shields.io/github/forks/xaitax/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability.svg) 
2024-02-19T20:00:35Z

- [https://github.com/duy-31/CVE-2024-21413](https://github.com/duy-31/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/duy-31/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/duy-31/CVE-2024-21413.svg) 
2024-02-17T07:08:49Z

- [https://github.com/CMNatic/CVE-2024-21413](https://github.com/CMNatic/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/CMNatic/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/CMNatic/CVE-2024-21413.svg) 
2024-03-13T02:44:28Z

- [https://github.com/r00tb1t/CVE-2024-21413-POC](https://github.com/r00tb1t/CVE-2024-21413-POC) :  
![starts](https://img.shields.io/github/stars/r00tb1t/CVE-2024-21413-POC.svg) 
![forks](https://img.shields.io/github/forks/r00tb1t/CVE-2024-21413-POC.svg) 
2024-02-16T22:23:37Z

- [https://github.com/ThemeHackers/CVE-2024-21413](https://github.com/ThemeHackers/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/ThemeHackers/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/ThemeHackers/CVE-2024-21413.svg) 
2024-12-15T05:47:04Z

- [https://github.com/Mdusmandasthaheer/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability](https://github.com/Mdusmandasthaheer/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability) :  
![starts](https://img.shields.io/github/stars/Mdusmandasthaheer/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability.svg) 
![forks](https://img.shields.io/github/forks/Mdusmandasthaheer/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability.svg) 
2024-02-20T13:37:39Z

- [https://github.com/ahmetkarakayaoffical/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability](https://github.com/ahmetkarakayaoffical/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability) :  
![starts](https://img.shields.io/github/stars/ahmetkarakayaoffical/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability.svg) 
![forks](https://img.shields.io/github/forks/ahmetkarakayaoffical/CVE-2024-21413-Microsoft-Outlook-Remote-Code-Execution-Vulnerability.svg) 
2024-02-24T15:36:22Z

- [https://github.com/X-Projetion/CVE-2024-21413-Microsoft-Outlook-RCE-Exploit](https://github.com/X-Projetion/CVE-2024-21413-Microsoft-Outlook-RCE-Exploit) :  
![starts](https://img.shields.io/github/stars/X-Projetion/CVE-2024-21413-Microsoft-Outlook-RCE-Exploit.svg) 
![forks](https://img.shields.io/github/forks/X-Projetion/CVE-2024-21413-Microsoft-Outlook-RCE-Exploit.svg) 
2024-05-03T16:11:46Z

- [https://github.com/dshabani96/CVE-2024-21413](https://github.com/dshabani96/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/dshabani96/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/dshabani96/CVE-2024-21413.svg) 
2024-02-29T13:22:17Z

- [https://github.com/D1se0/CVE-2024-21413-Vulnerabilidad-Outlook-LAB](https://github.com/D1se0/CVE-2024-21413-Vulnerabilidad-Outlook-LAB) :  
![starts](https://img.shields.io/github/stars/D1se0/CVE-2024-21413-Vulnerabilidad-Outlook-LAB.svg) 
![forks](https://img.shields.io/github/forks/D1se0/CVE-2024-21413-Vulnerabilidad-Outlook-LAB.svg) 
2024-12-05T09:50:57Z

- [https://github.com/olebris/CVE-2024-21413](https://github.com/olebris/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/olebris/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/olebris/CVE-2024-21413.svg) 
2024-06-28T10:27:51Z

- [https://github.com/th3Hellion/CVE-2024-21413](https://github.com/th3Hellion/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/th3Hellion/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/th3Hellion/CVE-2024-21413.svg) 
2024-05-11T12:34:24Z

- [https://github.com/MSeymenD/CVE-2024-21413](https://github.com/MSeymenD/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/MSeymenD/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/MSeymenD/CVE-2024-21413.svg) 
2024-02-19T01:54:11Z

- [https://github.com/ShubhamKanhere307/CVE-2024-21413](https://github.com/ShubhamKanhere307/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/ShubhamKanhere307/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/ShubhamKanhere307/CVE-2024-21413.svg) 
2024-06-18T08:18:13Z

- [https://github.com/DerZiad/CVE-2024-21413](https://github.com/DerZiad/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/DerZiad/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/DerZiad/CVE-2024-21413.svg) 
2024-06-30T11:10:05Z

- [https://github.com/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape](https://github.com/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape) :  
![starts](https://img.shields.io/github/stars/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape.svg) 
![forks](https://img.shields.io/github/forks/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape.svg) 
2024-07-03T08:45:05Z

## CVE-2024-21306
 Microsoft Bluetooth Driver Spoofing Vulnerability

- [https://github.com/PhucHauDeveloper/BadBlue](https://github.com/PhucHauDeveloper/BadBlue) :  
![starts](https://img.shields.io/github/stars/PhucHauDeveloper/BadBlue.svg) 
![forks](https://img.shields.io/github/forks/PhucHauDeveloper/BadBlue.svg) 
2024-07-11T05:13:43Z

- [https://github.com/Danyw24/blueXploit](https://github.com/Danyw24/blueXploit) :  
![starts](https://img.shields.io/github/stars/Danyw24/blueXploit.svg) 
![forks](https://img.shields.io/github/forks/Danyw24/blueXploit.svg) 
2024-12-15T06:41:13Z

- [https://github.com/d4rks1d33/C-PoC-for-CVE-2024-21306](https://github.com/d4rks1d33/C-PoC-for-CVE-2024-21306) :  
![starts](https://img.shields.io/github/stars/d4rks1d33/C-PoC-for-CVE-2024-21306.svg) 
![forks](https://img.shields.io/github/forks/d4rks1d33/C-PoC-for-CVE-2024-21306.svg) 
2024-04-08T23:59:25Z

## CVE-2024-0582
 A memory leak flaw was found in the Linux kernels io_uring functionality in how a user registers a buffer ring with IORING_REGISTER_PBUF_RING, mmap() it, and then frees it. This flaw allows a local user to crash or potentially escalate their privileges on the system.

- [https://github.com/ysanatomic/io_uring_LPE-CVE-2024-0582](https://github.com/ysanatomic/io_uring_LPE-CVE-2024-0582) :  
![starts](https://img.shields.io/github/stars/ysanatomic/io_uring_LPE-CVE-2024-0582.svg) 
![forks](https://img.shields.io/github/forks/ysanatomic/io_uring_LPE-CVE-2024-0582.svg) 
2024-03-29T16:05:31Z

- [https://github.com/geniuszlyy/CVE-2024-0582](https://github.com/geniuszlyy/CVE-2024-0582) :  
![starts](https://img.shields.io/github/stars/geniuszlyy/CVE-2024-0582.svg) 
![forks](https://img.shields.io/github/forks/geniuszlyy/CVE-2024-0582.svg) 
2024-10-03T07:58:47Z

- [https://github.com/Forsaken0129/CVE-2024-0582](https://github.com/Forsaken0129/CVE-2024-0582) :  
![starts](https://img.shields.io/github/stars/Forsaken0129/CVE-2024-0582.svg) 
![forks](https://img.shields.io/github/forks/Forsaken0129/CVE-2024-0582.svg) 
2024-04-05T17:32:22Z

- [https://github.com/0ptyx/cve-2024-0582](https://github.com/0ptyx/cve-2024-0582) :  
![starts](https://img.shields.io/github/stars/0ptyx/cve-2024-0582.svg) 
![forks](https://img.shields.io/github/forks/0ptyx/cve-2024-0582.svg) 
2024-05-28T11:15:02Z

- [https://github.com/101010zyl/CVE-2024-0582](https://github.com/101010zyl/CVE-2024-0582) :  
![starts](https://img.shields.io/github/stars/101010zyl/CVE-2024-0582.svg) 
![forks](https://img.shields.io/github/forks/101010zyl/CVE-2024-0582.svg) 
2024-12-15T22:21:14Z

# 2024-12-14
## CVE-2024-46982
 Next.js is a React framework for building full-stack web applications. By sending a crafted HTTP request, it is possible to poison the cache of a non-dynamic server-side rendered route in the pages router (this does not affect the app router). When this crafted request is sent it could coerce Next.js to cache a route that is meant to not be cached and send a `Cache-Control: s-maxage=1, stale-while-revalidate` header which some upstream CDNs may cache as well. To be potentially affected all of the following must apply: 1. Next.js between 13.5.1 and 14.2.9, 2. Using pages router, & 3. Using non-dynamic server-side rendered routes e.g. `pages/dashboard.tsx` not `pages/blog/[slug].tsx`. This vulnerability was resolved in Next.js v13.5.7, v14.2.10, and later. We recommend upgrading regardless of whether you can reproduce the issue or not. There are no official or recommended workarounds for this issue, we recommend that users patch to a safe version.

- [https://github.com/CodePontiff/next_js_poisoning](https://github.com/CodePontiff/next_js_poisoning) :  
![starts](https://img.shields.io/github/stars/CodePontiff/next_js_poisoning.svg) 
![forks](https://img.shields.io/github/forks/CodePontiff/next_js_poisoning.svg) 
2024-12-14T09:42:57Z

## CVE-2024-3690
 A vulnerability classified as critical was found in PHPGurukul Small CRM 3.0. Affected by this vulnerability is an unknown functionality of the component Change Password Handler. The manipulation leads to sql injection. The attack can be launched remotely. The exploit has been disclosed to the public and may be used. The associated identifier of this vulnerability is VDB-260479.

- [https://github.com/taeseongk/CVE-2024-3690](https://github.com/taeseongk/CVE-2024-3690) :  
![starts](https://img.shields.io/github/stars/taeseongk/CVE-2024-3690.svg) 
![forks](https://img.shields.io/github/forks/taeseongk/CVE-2024-3690.svg) 
2024-12-14T01:44:46Z

