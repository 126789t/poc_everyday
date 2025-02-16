# 2025-02-16
## CVE-2025-24016
 Wazuh is a free and open source platform used for threat prevention, detection, and response. Starting in version 4.4.0 and prior to version 4.9.1, an unsafe deserialization vulnerability allows for remote code execution on Wazuh servers. DistributedAPI parameters are a serialized as JSON and deserialized using `as_wazuh_object` (in `framework/wazuh/core/cluster/common.py`). If an attacker manages to inject an unsanitized dictionary in DAPI request/response, they can forge an unhandled exception (`__unhandled_exc__`) to evaluate arbitrary python code. The vulnerability can be triggered by anybody with API access (compromised dashboard or Wazuh servers in the cluster) or, in certain configurations, even by a compromised agent. Version 4.9.1 contains a fix.

- [https://github.com/huseyinstif/CVE-2025-24016-Nuclei-Template](https://github.com/huseyinstif/CVE-2025-24016-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/huseyinstif/CVE-2025-24016-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/huseyinstif/CVE-2025-24016-Nuclei-Template.svg) 
2025-02-13T06:38:45Z

- [https://github.com/0xjessie21/CVE-2025-24016](https://github.com/0xjessie21/CVE-2025-24016) :  
![starts](https://img.shields.io/github/stars/0xjessie21/CVE-2025-24016.svg) 
![forks](https://img.shields.io/github/forks/0xjessie21/CVE-2025-24016.svg) 
2025-02-16T11:02:25Z

## CVE-2024-57241
 Dedecms 5.71sp1 and earlier is vulnerable to URL redirect. In the web application, a logic error does not judge the input GET request resulting in URL redirection.

- [https://github.com/woshidaheike/CVE-2024-57241](https://github.com/woshidaheike/CVE-2024-57241) :  
![starts](https://img.shields.io/github/stars/woshidaheike/CVE-2024-57241.svg) 
![forks](https://img.shields.io/github/forks/woshidaheike/CVE-2024-57241.svg) 
2025-02-16T09:56:28Z

## CVE-2024-7595
 GRE and GRE6 Protocols (RFC2784) do not validate or verify the source of a network packet allowing an attacker to spoof and route arbitrary traffic via an exposed network interface that can lead to spoofing, access control bypass, and other unexpected network behaviors.This can be considered similar to CVE-2020-10136.

- [https://github.com/PapayaJackal/ipeeyoupeewepee](https://github.com/PapayaJackal/ipeeyoupeewepee) :  
![starts](https://img.shields.io/github/stars/PapayaJackal/ipeeyoupeewepee.svg) 
![forks](https://img.shields.io/github/forks/PapayaJackal/ipeeyoupeewepee.svg) 
2025-01-22T13:20:58Z

- [https://github.com/GustavoHGP/ipeeyoupeewepee](https://github.com/GustavoHGP/ipeeyoupeewepee) :  
![starts](https://img.shields.io/github/stars/GustavoHGP/ipeeyoupeewepee.svg) 
![forks](https://img.shields.io/github/forks/GustavoHGP/ipeeyoupeewepee.svg) 
2025-02-16T13:08:49Z

## CVE-2024-5452
 A remote code execution (RCE) vulnerability exists in the lightning-ai/pytorch-lightning library version 2.2.1 due to improper handling of deserialized user input and mismanagement of dunder attributes by the `deepdiff` library. The library uses `deepdiff.Delta` objects to modify application state based on frontend actions. However, it is possible to bypass the intended restrictions on modifying dunder attributes, allowing an attacker to construct a serialized delta that passes the deserializer whitelist and contains dunder attributes. When processed, this can be exploited to access other modules, classes, and instances, leading to arbitrary attribute write and total RCE on any self-hosted pytorch-lightning application in its default configuration, as the delta endpoint is enabled by default.

- [https://github.com/XiaomingX/cve-2024-5452-poc](https://github.com/XiaomingX/cve-2024-5452-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-5452-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-5452-poc.svg) 
2024-11-22T06:56:32Z

- [https://github.com/skrkcb2/CVE-2024-5452](https://github.com/skrkcb2/CVE-2024-5452) :  
![starts](https://img.shields.io/github/stars/skrkcb2/CVE-2024-5452.svg) 
![forks](https://img.shields.io/github/forks/skrkcb2/CVE-2024-5452.svg) 
2025-02-16T02:14:05Z

## CVE-2021-4034
 A local privilege escalation vulnerability was found on polkit's pkexec utility. The pkexec application is a setuid tool designed to allow unprivileged users to run commands as privileged users according predefined policies. The current version of pkexec doesn't handle the calling parameters count correctly and ends trying to execute environment variables as commands. An attacker can leverage this by crafting environment variables in such a way it'll induce pkexec to execute arbitrary code. When successfully executed the attack can cause a local privilege escalation given unprivileged users administrative rights on the target machine.

- [https://github.com/berdav/CVE-2021-4034](https://github.com/berdav/CVE-2021-4034) :  
![starts](https://img.shields.io/github/stars/berdav/CVE-2021-4034.svg) 
![forks](https://img.shields.io/github/forks/berdav/CVE-2021-4034.svg) 
2022-06-08T04:00:28Z

- [https://github.com/jm33-m0/emp3r0r](https://github.com/jm33-m0/emp3r0r) :  
![starts](https://img.shields.io/github/stars/jm33-m0/emp3r0r.svg) 
![forks](https://img.shields.io/github/forks/jm33-m0/emp3r0r.svg) 
2025-02-16T09:25:15Z

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

- [https://github.com/delsadan/CNVD-2020-10487-Bulk-verification](https://github.com/delsadan/CNVD-2020-10487-Bulk-verification) :  
![starts](https://img.shields.io/github/stars/delsadan/CNVD-2020-10487-Bulk-verification.svg) 
![forks](https://img.shields.io/github/forks/delsadan/CNVD-2020-10487-Bulk-verification.svg) 
2020-02-24T08:18:02Z

- [https://github.com/YounesTasra-R4z3rSw0rd/CVE-2020-1938](https://github.com/YounesTasra-R4z3rSw0rd/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/YounesTasra-R4z3rSw0rd/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/YounesTasra-R4z3rSw0rd/CVE-2020-1938.svg) 
2022-08-21T15:49:16Z

- [https://github.com/sgdream/CVE-2020-1938](https://github.com/sgdream/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/sgdream/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/sgdream/CVE-2020-1938.svg) 
2020-02-20T16:54:45Z

- [https://github.com/h7hac9/CVE-2020-1938](https://github.com/h7hac9/CVE-2020-1938) :  
![starts](https://img.shields.io/github/stars/h7hac9/CVE-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/h7hac9/CVE-2020-1938.svg) 
2020-02-21T04:40:38Z

- [https://github.com/Warelock/cve-2020-1938](https://github.com/Warelock/cve-2020-1938) :  
![starts](https://img.shields.io/github/stars/Warelock/cve-2020-1938.svg) 
![forks](https://img.shields.io/github/forks/Warelock/cve-2020-1938.svg) 
2024-04-14T05:32:49Z

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

- [https://github.com/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591](https://github.com/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/robomusk52/exp-cmd-add-admin-vpn-CVE-2024-55591.svg) 
2025-02-09T01:30:50Z

- [https://github.com/virus-or-not/CVE-2024-55591](https://github.com/virus-or-not/CVE-2024-55591) :  
![starts](https://img.shields.io/github/stars/virus-or-not/CVE-2024-55591.svg) 
![forks](https://img.shields.io/github/forks/virus-or-not/CVE-2024-55591.svg) 
2025-01-29T21:27:21Z

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
2025-02-15T19:47:06Z

## CVE-2024-49138
 Windows Common Log File System Driver Elevation of Privilege Vulnerability

- [https://github.com/MrAle98/CVE-2024-49138-POC](https://github.com/MrAle98/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/MrAle98/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/MrAle98/CVE-2024-49138-POC.svg) 
2025-02-14T22:04:41Z

- [https://github.com/aspire20x/CVE-2024-49138-POC](https://github.com/aspire20x/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/aspire20x/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/aspire20x/CVE-2024-49138-POC.svg) 
2025-02-15T19:48:28Z

- [https://github.com/bananoname/CVE-2024-49138-POC](https://github.com/bananoname/CVE-2024-49138-POC) :  
![starts](https://img.shields.io/github/stars/bananoname/CVE-2024-49138-POC.svg) 
![forks](https://img.shields.io/github/forks/bananoname/CVE-2024-49138-POC.svg) 
2025-01-21T02:06:00Z

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
2025-02-15T19:53:29Z

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

- [https://github.com/o7-Fire/Log4Shell](https://github.com/o7-Fire/Log4Shell) :  
![starts](https://img.shields.io/github/stars/o7-Fire/Log4Shell.svg) 
![forks](https://img.shields.io/github/forks/o7-Fire/Log4Shell.svg) 
2022-06-28T01:20:20Z

- [https://github.com/r3kind1e/Log4Shell-obfuscated-payloads-generator](https://github.com/r3kind1e/Log4Shell-obfuscated-payloads-generator) :  
![starts](https://img.shields.io/github/stars/r3kind1e/Log4Shell-obfuscated-payloads-generator.svg) 
![forks](https://img.shields.io/github/forks/r3kind1e/Log4Shell-obfuscated-payloads-generator.svg) 
2022-05-26T03:18:31Z

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

# 2025-02-14
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

- [https://github.com/wellwornele/CVE-2024-36401](https://github.com/wellwornele/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/wellwornele/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/wellwornele/CVE-2024-36401.svg) 
2025-02-09T17:11:54Z

- [https://github.com/RevoltSecurities/CVE-2024-36401](https://github.com/RevoltSecurities/CVE-2024-36401) :  
![starts](https://img.shields.io/github/stars/RevoltSecurities/CVE-2024-36401.svg) 
![forks](https://img.shields.io/github/forks/RevoltSecurities/CVE-2024-36401.svg) 
2024-07-05T15:33:09Z

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

- [https://github.com/cmsec423/CVE-2024-34102](https://github.com/cmsec423/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/cmsec423/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/cmsec423/CVE-2024-34102.svg) 
2024-07-01T05:06:42Z

- [https://github.com/dream434/CVE-2024-34102](https://github.com/dream434/CVE-2024-34102) :  
![starts](https://img.shields.io/github/stars/dream434/CVE-2024-34102.svg) 
![forks](https://img.shields.io/github/forks/dream434/CVE-2024-34102.svg) 
2024-10-09T13:47:14Z

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

- [https://github.com/Hunt3r850/CVE-2024-10924-Wordpress-Docker](https://github.com/Hunt3r850/CVE-2024-10924-Wordpress-Docker) :  
![starts](https://img.shields.io/github/stars/Hunt3r850/CVE-2024-10924-Wordpress-Docker.svg) 
![forks](https://img.shields.io/github/forks/Hunt3r850/CVE-2024-10924-Wordpress-Docker.svg) 
2024-12-03T13:14:06Z

- [https://github.com/Hunt3r850/CVE-2024-10924-PoC](https://github.com/Hunt3r850/CVE-2024-10924-PoC) :  
![starts](https://img.shields.io/github/stars/Hunt3r850/CVE-2024-10924-PoC.svg) 
![forks](https://img.shields.io/github/forks/Hunt3r850/CVE-2024-10924-PoC.svg) 
2024-12-03T13:10:44Z

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

- [https://github.com/Bu0uCat/D-Link-NAS-CVE-2024-10914-](https://github.com/Bu0uCat/D-Link-NAS-CVE-2024-10914-) :  
![starts](https://img.shields.io/github/stars/Bu0uCat/D-Link-NAS-CVE-2024-10914-.svg) 
![forks](https://img.shields.io/github/forks/Bu0uCat/D-Link-NAS-CVE-2024-10914-.svg) 
2024-11-15T07:59:36Z

- [https://github.com/yenyangmjaze/cve-2024-10914](https://github.com/yenyangmjaze/cve-2024-10914) :  
![starts](https://img.shields.io/github/stars/yenyangmjaze/cve-2024-10914.svg) 
![forks](https://img.shields.io/github/forks/yenyangmjaze/cve-2024-10914.svg) 
2025-02-14T14:16:27Z

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

- [https://github.com/huseyinstif/CVE-2024-4577-Nuclei-Template](https://github.com/huseyinstif/CVE-2024-4577-Nuclei-Template) :  
![starts](https://img.shields.io/github/stars/huseyinstif/CVE-2024-4577-Nuclei-Template.svg) 
![forks](https://img.shields.io/github/forks/huseyinstif/CVE-2024-4577-Nuclei-Template.svg) 
2024-06-24T11:54:58Z

- [https://github.com/gh-ost00/CVE-2024-4577-RCE](https://github.com/gh-ost00/CVE-2024-4577-RCE) :  
![starts](https://img.shields.io/github/stars/gh-ost00/CVE-2024-4577-RCE.svg) 
![forks](https://img.shields.io/github/forks/gh-ost00/CVE-2024-4577-RCE.svg) 
2024-08-20T03:28:28Z

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

- [https://github.com/0x20c/CVE-2024-4577-nuclei](https://github.com/0x20c/CVE-2024-4577-nuclei) :  
![starts](https://img.shields.io/github/stars/0x20c/CVE-2024-4577-nuclei.svg) 
![forks](https://img.shields.io/github/forks/0x20c/CVE-2024-4577-nuclei.svg) 
2024-06-08T04:14:28Z

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

- [https://github.com/olebris/CVE-2024-4577](https://github.com/olebris/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/olebris/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/olebris/CVE-2024-4577.svg) 
2024-06-28T10:20:19Z

- [https://github.com/ohhhh693/CVE-2024-4577](https://github.com/ohhhh693/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ohhhh693/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ohhhh693/CVE-2024-4577.svg) 
2024-06-07T10:29:59Z

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

- [https://github.com/BitMEXResearch/CVE-2024-4577](https://github.com/BitMEXResearch/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/BitMEXResearch/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/BitMEXResearch/CVE-2024-4577.svg) 
2024-06-07T20:35:06Z

- [https://github.com/dbyMelina/CVE-2024-4577](https://github.com/dbyMelina/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/dbyMelina/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/dbyMelina/CVE-2024-4577.svg) 
2024-06-09T13:47:59Z

- [https://github.com/sug4r-wr41th/CVE-2024-4577](https://github.com/sug4r-wr41th/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/sug4r-wr41th/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/sug4r-wr41th/CVE-2024-4577.svg) 
2024-06-15T18:12:19Z

- [https://github.com/ahmetramazank/CVE-2024-4577](https://github.com/ahmetramazank/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/ahmetramazank/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/ahmetramazank/CVE-2024-4577.svg) 
2024-11-03T16:17:49Z

- [https://github.com/bl4cksku11/CVE-2024-4577](https://github.com/bl4cksku11/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/bl4cksku11/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/bl4cksku11/CVE-2024-4577.svg) 
2024-06-11T15:29:21Z

- [https://github.com/Sysc4ll3r/CVE-2024-4577](https://github.com/Sysc4ll3r/CVE-2024-4577) :  
![starts](https://img.shields.io/github/stars/Sysc4ll3r/CVE-2024-4577.svg) 
![forks](https://img.shields.io/github/forks/Sysc4ll3r/CVE-2024-4577.svg) 
2024-06-07T18:41:17Z

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

## CVE-2024-1086
 A use-after-free vulnerability in the Linux kernel's netfilter: nf_tables component can be exploited to achieve local privilege escalation.The nft_verdict_init() function allows positive values as drop error within the hook verdict, and hence the nf_hook_slow() function can cause a double free vulnerability when NF_DROP is issued with a drop error which resembles NF_ACCEPT.We recommend upgrading past commit f342de4e2f33e0e39165d8639387aa6c19dff660.

- [https://github.com/Notselwyn/CVE-2024-1086](https://github.com/Notselwyn/CVE-2024-1086) :  
![starts](https://img.shields.io/github/stars/Notselwyn/CVE-2024-1086.svg) 
![forks](https://img.shields.io/github/forks/Notselwyn/CVE-2024-1086.svg) 
2024-04-17T16:09:54Z

- [https://github.com/andigandhi/bitpixie](https://github.com/andigandhi/bitpixie) :  
![starts](https://img.shields.io/github/stars/andigandhi/bitpixie.svg) 
![forks](https://img.shields.io/github/forks/andigandhi/bitpixie.svg) 
2025-02-14T16:06:57Z

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
2025-02-14T09:20:57Z

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
2025-01-10T18:05:20Z

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

- [https://github.com/XiaomingX/cve-2024-23692-poc](https://github.com/XiaomingX/cve-2024-23692-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-23692-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-23692-poc.svg) 
2024-11-23T04:00:55Z

- [https://github.com/BBD-YZZ/CVE-2024-23692](https://github.com/BBD-YZZ/CVE-2024-23692) :  
![starts](https://img.shields.io/github/stars/BBD-YZZ/CVE-2024-23692.svg) 
![forks](https://img.shields.io/github/forks/BBD-YZZ/CVE-2024-23692.svg) 
2024-06-18T01:23:58Z

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

- [https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser](https://github.com/Hexastrike/Ivanti-Connect-Secure-Logs-Parser) :  
![starts](https://img.shields.io/github/stars/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
![forks](https://img.shields.io/github/forks/Hexastrike/Ivanti-Connect-Secure-Logs-Parser.svg) 
2025-01-19T18:26:31Z

- [https://github.com/rxwx/pulse-meter](https://github.com/rxwx/pulse-meter) :  
![starts](https://img.shields.io/github/stars/rxwx/pulse-meter.svg) 
![forks](https://img.shields.io/github/forks/rxwx/pulse-meter.svg) 
2025-02-13T15:24:45Z

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

## CVE-2024-5688
 If a garbage collection was triggered at the right time, a use-after-free could have occurred during object transplant. This vulnerability affects Firefox  127, Firefox ESR  115.12, and Thunderbird  115.12.

- [https://github.com/trustcves/CVE-2024-56882](https://github.com/trustcves/CVE-2024-56882) :  
![starts](https://img.shields.io/github/stars/trustcves/CVE-2024-56882.svg) 
![forks](https://img.shields.io/github/forks/trustcves/CVE-2024-56882.svg) 
2025-02-12T14:37:47Z

- [https://github.com/trustcves/CVE-2024-56883](https://github.com/trustcves/CVE-2024-56883) :  
![starts](https://img.shields.io/github/stars/trustcves/CVE-2024-56883.svg) 
![forks](https://img.shields.io/github/forks/trustcves/CVE-2024-56883.svg) 
2025-02-12T13:36:28Z

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

- [https://github.com/wjlin0/CVE-2022-26134](https://github.com/wjlin0/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/wjlin0/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/wjlin0/CVE-2022-26134.svg) 
2022-12-26T05:27:01Z

- [https://github.com/xsxtw/CVE-2022-26134](https://github.com/xsxtw/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/xsxtw/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/xsxtw/CVE-2022-26134.svg) 
2024-05-02T18:33:39Z

- [https://github.com/Agentgilspy/CVE-2022-26134](https://github.com/Agentgilspy/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/Agentgilspy/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/Agentgilspy/CVE-2022-26134.svg) 
2024-11-17T11:19:09Z

- [https://github.com/cc3305/CVE-2022-26134](https://github.com/cc3305/CVE-2022-26134) :  
![starts](https://img.shields.io/github/stars/cc3305/CVE-2022-26134.svg) 
![forks](https://img.shields.io/github/forks/cc3305/CVE-2022-26134.svg) 
2024-07-27T20:17:24Z

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

# 2025-02-11
## CVE-2025-24200
 An authorization issue was addressed with improved state management. This issue is fixed in iPadOS 17.7.5, iOS 18.3.1 and iPadOS 18.3.1. A physical attack may disable USB Restricted Mode on a locked device. Apple is aware of a report that this issue may have been exploited in an extremely sophisticated attack against specific targeted individuals.

- [https://github.com/McTavishSue/CVE-2025-24200](https://github.com/McTavishSue/CVE-2025-24200) :  
![starts](https://img.shields.io/github/stars/McTavishSue/CVE-2025-24200.svg) 
![forks](https://img.shields.io/github/forks/McTavishSue/CVE-2025-24200.svg) 
2025-02-11T15:30:55Z

## CVE-2024-53704
 An Improper Authentication vulnerability in the SSLVPN authentication mechanism allows a remote attacker to bypass authentication.

- [https://github.com/istagmbh/CVE-2024-53704](https://github.com/istagmbh/CVE-2024-53704) :  
![starts](https://img.shields.io/github/stars/istagmbh/CVE-2024-53704.svg) 
![forks](https://img.shields.io/github/forks/istagmbh/CVE-2024-53704.svg) 
2025-02-11T20:43:36Z

## CVE-2024-38856
 Incorrect Authorization vulnerability in Apache OFBiz.This issue affects Apache OFBiz: through 18.12.14.Users are recommended to upgrade to version 18.12.15, which fixes the issue.Unauthenticated endpoints could allow execution of screen rendering code of screens if some preconditions are met (such as when the screen definitions don't explicitly check user's permissions because they rely on the configuration of their endpoints).

- [https://github.com/securelayer7/CVE-2024-38856_Scanner](https://github.com/securelayer7/CVE-2024-38856_Scanner) :  
![starts](https://img.shields.io/github/stars/securelayer7/CVE-2024-38856_Scanner.svg) 
![forks](https://img.shields.io/github/forks/securelayer7/CVE-2024-38856_Scanner.svg) 
2024-10-02T15:59:28Z

- [https://github.com/0x20c/CVE-2024-38856-EXP](https://github.com/0x20c/CVE-2024-38856-EXP) :  
![starts](https://img.shields.io/github/stars/0x20c/CVE-2024-38856-EXP.svg) 
![forks](https://img.shields.io/github/forks/0x20c/CVE-2024-38856-EXP.svg) 
2024-08-22T04:19:48Z

- [https://github.com/XiaomingX/cve-2024-38856-poc](https://github.com/XiaomingX/cve-2024-38856-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2024-38856-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2024-38856-poc.svg) 
2024-11-23T03:57:02Z

- [https://github.com/BBD-YZZ/CVE-2024-38856-RCE](https://github.com/BBD-YZZ/CVE-2024-38856-RCE) :  
![starts](https://img.shields.io/github/stars/BBD-YZZ/CVE-2024-38856-RCE.svg) 
![forks](https://img.shields.io/github/forks/BBD-YZZ/CVE-2024-38856-RCE.svg) 
2024-08-28T06:36:41Z

- [https://github.com/ThatNotEasy/CVE-2024-38856](https://github.com/ThatNotEasy/CVE-2024-38856) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-38856.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-38856.svg) 
2024-08-10T03:14:42Z

- [https://github.com/FakesiteSecurity/CVE-2024-38856_Scen](https://github.com/FakesiteSecurity/CVE-2024-38856_Scen) :  
![starts](https://img.shields.io/github/stars/FakesiteSecurity/CVE-2024-38856_Scen.svg) 
![forks](https://img.shields.io/github/forks/FakesiteSecurity/CVE-2024-38856_Scen.svg) 
2025-01-02T15:27:34Z

- [https://github.com/Praison001/CVE-2024-38856-ApacheOfBiz](https://github.com/Praison001/CVE-2024-38856-ApacheOfBiz) :  
![starts](https://img.shields.io/github/stars/Praison001/CVE-2024-38856-ApacheOfBiz.svg) 
![forks](https://img.shields.io/github/forks/Praison001/CVE-2024-38856-ApacheOfBiz.svg) 
2024-08-18T15:27:01Z

- [https://github.com/emanueldosreis/CVE-2024-38856](https://github.com/emanueldosreis/CVE-2024-38856) :  
![starts](https://img.shields.io/github/stars/emanueldosreis/CVE-2024-38856.svg) 
![forks](https://img.shields.io/github/forks/emanueldosreis/CVE-2024-38856.svg) 
2024-08-28T12:04:28Z

- [https://github.com/codeb0ss/CVE-2024-38856-PoC](https://github.com/codeb0ss/CVE-2024-38856-PoC) :  
![starts](https://img.shields.io/github/stars/codeb0ss/CVE-2024-38856-PoC.svg) 
![forks](https://img.shields.io/github/forks/codeb0ss/CVE-2024-38856-PoC.svg) 
2024-08-09T11:28:48Z

- [https://github.com/AlissonFaoli/Apache-OFBiz-Exploit](https://github.com/AlissonFaoli/Apache-OFBiz-Exploit) :  
![starts](https://img.shields.io/github/stars/AlissonFaoli/Apache-OFBiz-Exploit.svg) 
![forks](https://img.shields.io/github/forks/AlissonFaoli/Apache-OFBiz-Exploit.svg) 
2025-02-11T04:48:51Z

## CVE-2024-4437
 The etcd package distributed with the Red Hat OpenStack platform has an incomplete fix for CVE-2021-44716. This issue occurs because the etcd package in the Red Hat OpenStack platform is using http://golang.org/x/net/http2 instead of the one provided by Red Hat Enterprise Linux versions, meaning it should be updated at compile time instead.

- [https://github.com/aezdmr/CVE-2024-44378](https://github.com/aezdmr/CVE-2024-44378) :  
![starts](https://img.shields.io/github/stars/aezdmr/CVE-2024-44378.svg) 
![forks](https://img.shields.io/github/forks/aezdmr/CVE-2024-44378.svg) 
2025-02-11T15:03:18Z

## CVE-2023-24932
 Secure Boot Security Feature Bypass Vulnerability

- [https://github.com/Wack0/CVE-2022-21894](https://github.com/Wack0/CVE-2022-21894) :  
![starts](https://img.shields.io/github/stars/Wack0/CVE-2022-21894.svg) 
![forks](https://img.shields.io/github/forks/Wack0/CVE-2022-21894.svg) 
2023-09-27T06:44:27Z

- [https://github.com/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932](https://github.com/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932) :  
![starts](https://img.shields.io/github/stars/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932.svg) 
![forks](https://img.shields.io/github/forks/helleflo1312/Orchestrated-Powershell-for-CVE-2023-24932.svg) 
2025-02-11T12:40:50Z

## CVE-2022-47522
 The IEEE 802.11 specifications through 802.11ax allow physically proximate attackers to intercept (possibly cleartext) target-destined frames by spoofing a target's MAC address, sending Power Save frames to the access point, and then sending other frames to the access point (such as authentication frames or re-association frames) to remove the target's original security context. This behavior occurs because the specifications do not require an access point to purge its transmit queue before removing a client's pairwise encryption key.

- [https://github.com/toffeenutt/CVE-2022-47522-exploit](https://github.com/toffeenutt/CVE-2022-47522-exploit) :  
![starts](https://img.shields.io/github/stars/toffeenutt/CVE-2022-47522-exploit.svg) 
![forks](https://img.shields.io/github/forks/toffeenutt/CVE-2022-47522-exploit.svg) 
2025-02-11T06:22:39Z

## CVE-2021-26084
 In affected versions of Confluence Server and Data Center, an OGNL injection vulnerability exists that would allow an unauthenticated attacker to execute arbitrary code on a Confluence Server or Data Center instance. The affected versions are before version 6.13.23, from version 6.14.0 before 7.4.11, from version 7.5.0 before 7.11.6, and from version 7.12.0 before 7.12.5.

- [https://github.com/hev0x/CVE-2021-26084_Confluence](https://github.com/hev0x/CVE-2021-26084_Confluence) :  
![starts](https://img.shields.io/github/stars/hev0x/CVE-2021-26084_Confluence.svg) 
![forks](https://img.shields.io/github/forks/hev0x/CVE-2021-26084_Confluence.svg) 
2025-02-11T01:36:46Z

- [https://github.com/sma11new/PocList](https://github.com/sma11new/PocList) :  
![starts](https://img.shields.io/github/stars/sma11new/PocList.svg) 
![forks](https://img.shields.io/github/forks/sma11new/PocList.svg) 
2021-11-21T10:34:06Z

- [https://github.com/0xf4n9x/CVE-2021-26084](https://github.com/0xf4n9x/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/0xf4n9x/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/0xf4n9x/CVE-2021-26084.svg) 
2022-02-10T11:38:46Z

- [https://github.com/dinhbaouit/CVE-2021-26084](https://github.com/dinhbaouit/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/dinhbaouit/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/dinhbaouit/CVE-2021-26084.svg) 
2021-09-01T01:17:58Z

- [https://github.com/alt3kx/CVE-2021-26084_PoC](https://github.com/alt3kx/CVE-2021-26084_PoC) :  
![starts](https://img.shields.io/github/stars/alt3kx/CVE-2021-26084_PoC.svg) 
![forks](https://img.shields.io/github/forks/alt3kx/CVE-2021-26084_PoC.svg) 
2021-09-01T01:01:06Z

- [https://github.com/1ZRR4H/CVE-2021-26084](https://github.com/1ZRR4H/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/1ZRR4H/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/1ZRR4H/CVE-2021-26084.svg) 
2021-09-07T12:59:45Z

- [https://github.com/crowsec-edtech/CVE-2021-26084](https://github.com/crowsec-edtech/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/crowsec-edtech/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/crowsec-edtech/CVE-2021-26084.svg) 
2021-09-01T17:56:22Z

- [https://github.com/Vulnmachines/Confluence_CVE-2021-26084](https://github.com/Vulnmachines/Confluence_CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/Confluence_CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/Confluence_CVE-2021-26084.svg) 
2022-07-29T08:01:19Z

- [https://github.com/taythebot/CVE-2021-26084](https://github.com/taythebot/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/taythebot/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/taythebot/CVE-2021-26084.svg) 
2021-09-08T13:40:02Z

- [https://github.com/ZZ-SOCMAP/CVE-2021-26084](https://github.com/ZZ-SOCMAP/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/ZZ-SOCMAP/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/ZZ-SOCMAP/CVE-2021-26084.svg) 
2022-01-14T04:21:27Z

- [https://github.com/lleavesl/CVE-2021-26084](https://github.com/lleavesl/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/lleavesl/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/lleavesl/CVE-2021-26084.svg) 
2021-10-27T02:30:40Z

- [https://github.com/smadi0x86/CVE-2021-26084](https://github.com/smadi0x86/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/smadi0x86/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/smadi0x86/CVE-2021-26084.svg) 
2023-06-06T17:26:44Z

- [https://github.com/JKme/CVE-2021-26084](https://github.com/JKme/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/JKme/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/JKme/CVE-2021-26084.svg) 
2021-09-01T02:34:14Z

- [https://github.com/orangmuda/CVE-2021-26084](https://github.com/orangmuda/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/orangmuda/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/orangmuda/CVE-2021-26084.svg) 
2022-01-27T06:16:01Z

- [https://github.com/BBD-YZZ/Confluence-RCE](https://github.com/BBD-YZZ/Confluence-RCE) :  
![starts](https://img.shields.io/github/stars/BBD-YZZ/Confluence-RCE.svg) 
![forks](https://img.shields.io/github/forks/BBD-YZZ/Confluence-RCE.svg) 
2024-08-26T09:24:31Z

- [https://github.com/Loneyers/CVE-2021-26084](https://github.com/Loneyers/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/Loneyers/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/Loneyers/CVE-2021-26084.svg) 
2021-09-03T07:45:04Z

- [https://github.com/ludy-dev/CVE-2021-26084_PoC](https://github.com/ludy-dev/CVE-2021-26084_PoC) :  
![starts](https://img.shields.io/github/stars/ludy-dev/CVE-2021-26084_PoC.svg) 
![forks](https://img.shields.io/github/forks/ludy-dev/CVE-2021-26084_PoC.svg) 
2021-09-21T08:33:29Z

- [https://github.com/34zY/APT-Backpack](https://github.com/34zY/APT-Backpack) :  
![starts](https://img.shields.io/github/stars/34zY/APT-Backpack.svg) 
![forks](https://img.shields.io/github/forks/34zY/APT-Backpack.svg) 
2023-04-19T17:10:15Z

- [https://github.com/toowoxx/docker-confluence-patched](https://github.com/toowoxx/docker-confluence-patched) :  
![starts](https://img.shields.io/github/stars/toowoxx/docker-confluence-patched.svg) 
![forks](https://img.shields.io/github/forks/toowoxx/docker-confluence-patched.svg) 
2021-09-17T12:45:19Z

- [https://github.com/prettyrecon/CVE-2021-26084_Confluence](https://github.com/prettyrecon/CVE-2021-26084_Confluence) :  
![starts](https://img.shields.io/github/stars/prettyrecon/CVE-2021-26084_Confluence.svg) 
![forks](https://img.shields.io/github/forks/prettyrecon/CVE-2021-26084_Confluence.svg) 
2021-09-01T08:17:05Z

- [https://github.com/TheclaMcentire/CVE-2021-26084_Confluence](https://github.com/TheclaMcentire/CVE-2021-26084_Confluence) :  
![starts](https://img.shields.io/github/stars/TheclaMcentire/CVE-2021-26084_Confluence.svg) 
![forks](https://img.shields.io/github/forks/TheclaMcentire/CVE-2021-26084_Confluence.svg) 
2021-09-08T11:04:53Z

- [https://github.com/Jun-5heng/CVE-2021-26084](https://github.com/Jun-5heng/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/Jun-5heng/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/Jun-5heng/CVE-2021-26084.svg) 
2022-04-18T03:37:18Z

- [https://github.com/nizar0x1f/CVE-2021-26084-patch-](https://github.com/nizar0x1f/CVE-2021-26084-patch-) :  
![starts](https://img.shields.io/github/stars/nizar0x1f/CVE-2021-26084-patch-.svg) 
![forks](https://img.shields.io/github/forks/nizar0x1f/CVE-2021-26084-patch-.svg) 
2021-09-08T17:28:47Z

- [https://github.com/GlennPegden2/cve-2021-26084-confluence](https://github.com/GlennPegden2/cve-2021-26084-confluence) :  
![starts](https://img.shields.io/github/stars/GlennPegden2/cve-2021-26084-confluence.svg) 
![forks](https://img.shields.io/github/forks/GlennPegden2/cve-2021-26084-confluence.svg) 
2021-09-07T15:09:40Z

- [https://github.com/BeRserKerSec/CVE-2021-26084-Nuclei-template](https://github.com/BeRserKerSec/CVE-2021-26084-Nuclei-template) :  
![starts](https://img.shields.io/github/stars/BeRserKerSec/CVE-2021-26084-Nuclei-template.svg) 
![forks](https://img.shields.io/github/forks/BeRserKerSec/CVE-2021-26084-Nuclei-template.svg) 
2021-09-02T11:50:06Z

- [https://github.com/bcdannyboy/CVE-2021-26084_GoPOC](https://github.com/bcdannyboy/CVE-2021-26084_GoPOC) :  
![starts](https://img.shields.io/github/stars/bcdannyboy/CVE-2021-26084_GoPOC.svg) 
![forks](https://img.shields.io/github/forks/bcdannyboy/CVE-2021-26084_GoPOC.svg) 
2021-09-01T16:18:48Z

- [https://github.com/CrackerCat/CVE-2021-26084](https://github.com/CrackerCat/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/CrackerCat/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/CrackerCat/CVE-2021-26084.svg) 
2021-09-01T12:55:08Z

- [https://github.com/b1gw00d/CVE-2021-26084](https://github.com/b1gw00d/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/b1gw00d/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/b1gw00d/CVE-2021-26084.svg) 
2021-09-01T12:51:02Z

- [https://github.com/attacker-codeninja/CVE-2021-26084](https://github.com/attacker-codeninja/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/attacker-codeninja/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/attacker-codeninja/CVE-2021-26084.svg) 
2021-09-09T06:52:43Z

- [https://github.com/p0nymc1/CVE-2021-26084](https://github.com/p0nymc1/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/p0nymc1/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/p0nymc1/CVE-2021-26084.svg) 
2021-09-03T08:54:43Z

- [https://github.com/Xc1Ym/cve_2021_26084](https://github.com/Xc1Ym/cve_2021_26084) :  
![starts](https://img.shields.io/github/stars/Xc1Ym/cve_2021_26084.svg) 
![forks](https://img.shields.io/github/forks/Xc1Ym/cve_2021_26084.svg) 
2021-09-03T08:22:55Z

- [https://github.com/wdjcy/CVE-2021-26084](https://github.com/wdjcy/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/wdjcy/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/wdjcy/CVE-2021-26084.svg) 
2021-10-02T03:16:41Z

- [https://github.com/nahcusira/CVE-2021-26084](https://github.com/nahcusira/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/nahcusira/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/nahcusira/CVE-2021-26084.svg) 
2024-05-06T15:13:32Z

- [https://github.com/maskerTUI/CVE-2021-26084](https://github.com/maskerTUI/CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/maskerTUI/CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/maskerTUI/CVE-2021-26084.svg) 
2021-09-02T07:07:22Z

- [https://github.com/Jeromeyoung/CVE-2021-26086](https://github.com/Jeromeyoung/CVE-2021-26086) :  
![starts](https://img.shields.io/github/stars/Jeromeyoung/CVE-2021-26086.svg) 
![forks](https://img.shields.io/github/forks/Jeromeyoung/CVE-2021-26086.svg) 
2021-09-04T13:57:08Z

- [https://github.com/30579096/Confluence-CVE-2021-26084](https://github.com/30579096/Confluence-CVE-2021-26084) :  
![starts](https://img.shields.io/github/stars/30579096/Confluence-CVE-2021-26084.svg) 
![forks](https://img.shields.io/github/forks/30579096/Confluence-CVE-2021-26084.svg) 
2021-09-03T07:37:10Z

- [https://github.com/smallpiggy/cve-2021-26084-confluence](https://github.com/smallpiggy/cve-2021-26084-confluence) :  
![starts](https://img.shields.io/github/stars/smallpiggy/cve-2021-26084-confluence.svg) 
![forks](https://img.shields.io/github/forks/smallpiggy/cve-2021-26084-confluence.svg) 
2021-09-02T02:42:15Z

- [https://github.com/vpxuser/CVE-2021-26084-EXP](https://github.com/vpxuser/CVE-2021-26084-EXP) :  
![starts](https://img.shields.io/github/stars/vpxuser/CVE-2021-26084-EXP.svg) 
![forks](https://img.shields.io/github/forks/vpxuser/CVE-2021-26084-EXP.svg) 
2023-07-05T05:32:50Z

- [https://github.com/wolf1892/confluence-rce-poc](https://github.com/wolf1892/confluence-rce-poc) :  
![starts](https://img.shields.io/github/stars/wolf1892/confluence-rce-poc.svg) 
![forks](https://img.shields.io/github/forks/wolf1892/confluence-rce-poc.svg) 
2021-09-04T15:16:40Z

- [https://github.com/Osyanina/westone-CVE-2021-26084-scanner](https://github.com/Osyanina/westone-CVE-2021-26084-scanner) :  
![starts](https://img.shields.io/github/stars/Osyanina/westone-CVE-2021-26084-scanner.svg) 
![forks](https://img.shields.io/github/forks/Osyanina/westone-CVE-2021-26084-scanner.svg) 
2021-09-01T12:33:06Z

- [https://github.com/quesodipesto/conflucheck](https://github.com/quesodipesto/conflucheck) :  
![starts](https://img.shields.io/github/stars/quesodipesto/conflucheck.svg) 
![forks](https://img.shields.io/github/forks/quesodipesto/conflucheck.svg) 
2021-11-24T19:02:50Z

## CVE-2021-3156
 Sudo before 1.9.5p2 contains an off-by-one error that can result in a heap-based buffer overflow, which allows privilege escalation to root via "sudoedit -s" and a command-line argument that ends with a single backslash character.

- [https://github.com/blasty/CVE-2021-3156](https://github.com/blasty/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/blasty/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/blasty/CVE-2021-3156.svg) 
2021-02-02T17:07:09Z

- [https://github.com/worawit/CVE-2021-3156](https://github.com/worawit/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/worawit/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/worawit/CVE-2021-3156.svg) 
2022-01-13T05:48:01Z

- [https://github.com/stong/CVE-2021-3156](https://github.com/stong/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/stong/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/stong/CVE-2021-3156.svg) 
2022-04-14T11:51:18Z

- [https://github.com/Al1ex/LinuxEelvation](https://github.com/Al1ex/LinuxEelvation) :  
![starts](https://img.shields.io/github/stars/Al1ex/LinuxEelvation.svg) 
![forks](https://img.shields.io/github/forks/Al1ex/LinuxEelvation.svg) 
2022-07-29T09:34:03Z

- [https://github.com/LiveOverflow/pwnedit](https://github.com/LiveOverflow/pwnedit) :  
![starts](https://img.shields.io/github/stars/LiveOverflow/pwnedit.svg) 
![forks](https://img.shields.io/github/forks/LiveOverflow/pwnedit.svg) 
2022-02-12T19:33:07Z

- [https://github.com/Rvn0xsy/CVE-2021-3156-plus](https://github.com/Rvn0xsy/CVE-2021-3156-plus) :  
![starts](https://img.shields.io/github/stars/Rvn0xsy/CVE-2021-3156-plus.svg) 
![forks](https://img.shields.io/github/forks/Rvn0xsy/CVE-2021-3156-plus.svg) 
2021-02-09T19:31:33Z

- [https://github.com/CptGibbon/CVE-2021-3156](https://github.com/CptGibbon/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/CptGibbon/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/CptGibbon/CVE-2021-3156.svg) 
2022-02-13T12:21:53Z

- [https://github.com/reverse-ex/CVE-2021-3156](https://github.com/reverse-ex/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/reverse-ex/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/reverse-ex/CVE-2021-3156.svg) 
2021-01-31T04:56:56Z

- [https://github.com/0x4ndy/clif](https://github.com/0x4ndy/clif) :  
![starts](https://img.shields.io/github/stars/0x4ndy/clif.svg) 
![forks](https://img.shields.io/github/forks/0x4ndy/clif.svg) 
2022-12-22T12:38:31Z

- [https://github.com/0xdevil/CVE-2021-3156](https://github.com/0xdevil/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/0xdevil/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/0xdevil/CVE-2021-3156.svg) 
2021-12-03T14:34:18Z

- [https://github.com/mbcrump/CVE-2021-3156](https://github.com/mbcrump/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/mbcrump/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/mbcrump/CVE-2021-3156.svg) 
2021-01-31T02:21:37Z

- [https://github.com/mr-r3b00t/CVE-2021-3156](https://github.com/mr-r3b00t/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/mr-r3b00t/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/mr-r3b00t/CVE-2021-3156.svg) 
2021-01-26T20:09:53Z

- [https://github.com/PhuketIsland/CVE-2021-3156-centos7](https://github.com/PhuketIsland/CVE-2021-3156-centos7) :  
![starts](https://img.shields.io/github/stars/PhuketIsland/CVE-2021-3156-centos7.svg) 
![forks](https://img.shields.io/github/forks/PhuketIsland/CVE-2021-3156-centos7.svg) 
2022-11-03T13:52:35Z

- [https://github.com/kernelzeroday/CVE-2021-3156-Baron-Samedit](https://github.com/kernelzeroday/CVE-2021-3156-Baron-Samedit) :  
![starts](https://img.shields.io/github/stars/kernelzeroday/CVE-2021-3156-Baron-Samedit.svg) 
![forks](https://img.shields.io/github/forks/kernelzeroday/CVE-2021-3156-Baron-Samedit.svg) 
2021-01-29T03:21:13Z

- [https://github.com/jm33-m0/CVE-2021-3156](https://github.com/jm33-m0/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/jm33-m0/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/jm33-m0/CVE-2021-3156.svg) 
2021-02-09T08:11:04Z

- [https://github.com/redhawkeye/sudo-exploit](https://github.com/redhawkeye/sudo-exploit) :  
![starts](https://img.shields.io/github/stars/redhawkeye/sudo-exploit.svg) 
![forks](https://img.shields.io/github/forks/redhawkeye/sudo-exploit.svg) 
2021-09-25T16:13:19Z

- [https://github.com/teamtopkarl/CVE-2021-3156](https://github.com/teamtopkarl/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/teamtopkarl/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/teamtopkarl/CVE-2021-3156.svg) 
2021-01-31T04:02:08Z

- [https://github.com/chenaotian/CVE-2021-3156](https://github.com/chenaotian/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/chenaotian/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/chenaotian/CVE-2021-3156.svg) 
2022-05-23T01:51:14Z

- [https://github.com/apogiatzis/docker-CVE-2021-3156](https://github.com/apogiatzis/docker-CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/apogiatzis/docker-CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/apogiatzis/docker-CVE-2021-3156.svg) 
2021-01-31T23:03:51Z

- [https://github.com/dinhbaouit/CVE-2021-3156](https://github.com/dinhbaouit/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/dinhbaouit/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/dinhbaouit/CVE-2021-3156.svg) 
2021-02-03T10:58:39Z

- [https://github.com/yaunsky/cve-2021-3156](https://github.com/yaunsky/cve-2021-3156) :  
![starts](https://img.shields.io/github/stars/yaunsky/cve-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/yaunsky/cve-2021-3156.svg) 
2021-01-28T02:21:30Z

- [https://github.com/1N53C/CVE-2021-3156-PoC](https://github.com/1N53C/CVE-2021-3156-PoC) :  
![starts](https://img.shields.io/github/stars/1N53C/CVE-2021-3156-PoC.svg) 
![forks](https://img.shields.io/github/forks/1N53C/CVE-2021-3156-PoC.svg) 
2021-02-06T21:20:04Z

- [https://github.com/Mhackiori/CVE-2021-3156](https://github.com/Mhackiori/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/Mhackiori/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/Mhackiori/CVE-2021-3156.svg) 
2022-07-15T04:41:17Z

- [https://github.com/baka9moe/CVE-2021-3156-Exp](https://github.com/baka9moe/CVE-2021-3156-Exp) :  
![starts](https://img.shields.io/github/stars/baka9moe/CVE-2021-3156-Exp.svg) 
![forks](https://img.shields.io/github/forks/baka9moe/CVE-2021-3156-Exp.svg) 
2021-01-28T09:12:29Z

- [https://github.com/lmol/CVE-2021-3156](https://github.com/lmol/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/lmol/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/lmol/CVE-2021-3156.svg) 
2021-03-25T23:52:40Z

- [https://github.com/PurpleOzone/PE_CVE-CVE-2021-3156](https://github.com/PurpleOzone/PE_CVE-CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/PurpleOzone/PE_CVE-CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/PurpleOzone/PE_CVE-CVE-2021-3156.svg) 
2023-05-13T07:48:55Z

- [https://github.com/elbee-cyber/CVE-2021-3156-PATCHER](https://github.com/elbee-cyber/CVE-2021-3156-PATCHER) :  
![starts](https://img.shields.io/github/stars/elbee-cyber/CVE-2021-3156-PATCHER.svg) 
![forks](https://img.shields.io/github/forks/elbee-cyber/CVE-2021-3156-PATCHER.svg) 
2021-01-28T05:25:26Z

- [https://github.com/ph4ntonn/CVE-2021-3156](https://github.com/ph4ntonn/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/ph4ntonn/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/ph4ntonn/CVE-2021-3156.svg) 
2021-01-28T10:02:05Z

- [https://github.com/kal1gh0st/CVE-2021-3156](https://github.com/kal1gh0st/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/kal1gh0st/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/kal1gh0st/CVE-2021-3156.svg) 
2021-05-04T14:41:30Z

- [https://github.com/marcellomaugeri/Hardening-7-Fuzzing](https://github.com/marcellomaugeri/Hardening-7-Fuzzing) :  
![starts](https://img.shields.io/github/stars/marcellomaugeri/Hardening-7-Fuzzing.svg) 
![forks](https://img.shields.io/github/forks/marcellomaugeri/Hardening-7-Fuzzing.svg) 
2024-05-29T15:25:49Z

- [https://github.com/Q4n/CVE-2021-3156](https://github.com/Q4n/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/Q4n/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/Q4n/CVE-2021-3156.svg) 
2021-01-31T07:02:44Z

- [https://github.com/musergi/CVE-2021-3156](https://github.com/musergi/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/musergi/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/musergi/CVE-2021-3156.svg) 
2021-12-01T13:51:47Z

- [https://github.com/ypl6/heaplens](https://github.com/ypl6/heaplens) :  
![starts](https://img.shields.io/github/stars/ypl6/heaplens.svg) 
![forks](https://img.shields.io/github/forks/ypl6/heaplens.svg) 
2022-04-13T01:16:07Z

- [https://github.com/pmihsan/Sudo-HeapBased-Buffer-Overflow](https://github.com/pmihsan/Sudo-HeapBased-Buffer-Overflow) :  
![starts](https://img.shields.io/github/stars/pmihsan/Sudo-HeapBased-Buffer-Overflow.svg) 
![forks](https://img.shields.io/github/forks/pmihsan/Sudo-HeapBased-Buffer-Overflow.svg) 
2023-01-16T04:40:03Z

- [https://github.com/unauth401/CVE-2021-3156](https://github.com/unauth401/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/unauth401/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/unauth401/CVE-2021-3156.svg) 
2021-01-27T15:19:23Z

- [https://github.com/RodricBr/CVE-2021-3156](https://github.com/RodricBr/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/RodricBr/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/RodricBr/CVE-2021-3156.svg) 
2022-08-19T20:56:10Z

- [https://github.com/TheFlash2k/CVE-2021-3156](https://github.com/TheFlash2k/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/TheFlash2k/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/TheFlash2k/CVE-2021-3156.svg) 
2021-06-30T18:00:24Z

- [https://github.com/nobodyatall648/CVE-2021-3156](https://github.com/nobodyatall648/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/nobodyatall648/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/nobodyatall648/CVE-2021-3156.svg) 
2021-02-01T02:19:20Z

- [https://github.com/0x7183/CVE-2021-3156](https://github.com/0x7183/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/0x7183/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/0x7183/CVE-2021-3156.svg) 
2021-10-12T20:51:00Z

- [https://github.com/donghyunlee00/CVE-2021-3156](https://github.com/donghyunlee00/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/donghyunlee00/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/donghyunlee00/CVE-2021-3156.svg) 
2021-06-25T06:10:59Z

- [https://github.com/BearCat4/CVE-2021-3156](https://github.com/BearCat4/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/BearCat4/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/BearCat4/CVE-2021-3156.svg) 
2021-03-30T06:58:11Z

- [https://github.com/puckiestyle/CVE-2021-3156](https://github.com/puckiestyle/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/puckiestyle/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/puckiestyle/CVE-2021-3156.svg) 
2022-03-04T13:11:57Z

- [https://github.com/q77190858/CVE-2021-3156](https://github.com/q77190858/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/q77190858/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/q77190858/CVE-2021-3156.svg) 
2022-05-26T02:49:56Z

- [https://github.com/lypd0/CVE-2021-3156-checker](https://github.com/lypd0/CVE-2021-3156-checker) :  
![starts](https://img.shields.io/github/stars/lypd0/CVE-2021-3156-checker.svg) 
![forks](https://img.shields.io/github/forks/lypd0/CVE-2021-3156-checker.svg) 
2024-05-14T17:04:52Z

- [https://github.com/SantiagoSerrao/ScannerCVE-2021-3156](https://github.com/SantiagoSerrao/ScannerCVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/SantiagoSerrao/ScannerCVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/SantiagoSerrao/ScannerCVE-2021-3156.svg) 
2021-02-01T18:50:07Z

- [https://github.com/DASICS-ICT/DASICS-CVE-2021-3156](https://github.com/DASICS-ICT/DASICS-CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/DASICS-ICT/DASICS-CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/DASICS-ICT/DASICS-CVE-2021-3156.svg) 
2024-01-22T01:02:03Z

- [https://github.com/binw2018/CVE-2021-3156-SCRIPT](https://github.com/binw2018/CVE-2021-3156-SCRIPT) :  
![starts](https://img.shields.io/github/stars/binw2018/CVE-2021-3156-SCRIPT.svg) 
![forks](https://img.shields.io/github/forks/binw2018/CVE-2021-3156-SCRIPT.svg) 
2021-01-29T06:49:07Z

- [https://github.com/r3k4t/how-to-solve-sudo-heap-based-bufferoverflow-vulnerability](https://github.com/r3k4t/how-to-solve-sudo-heap-based-bufferoverflow-vulnerability) :  
![starts](https://img.shields.io/github/stars/r3k4t/how-to-solve-sudo-heap-based-bufferoverflow-vulnerability.svg) 
![forks](https://img.shields.io/github/forks/r3k4t/how-to-solve-sudo-heap-based-bufferoverflow-vulnerability.svg) 
2021-02-12T10:21:43Z

- [https://github.com/AbdullahRizwan101/Baron-Samedit](https://github.com/AbdullahRizwan101/Baron-Samedit) :  
![starts](https://img.shields.io/github/stars/AbdullahRizwan101/Baron-Samedit.svg) 
![forks](https://img.shields.io/github/forks/AbdullahRizwan101/Baron-Samedit.svg) 
2021-02-02T12:56:23Z

- [https://github.com/usr2r00t/patches](https://github.com/usr2r00t/patches) :  
![starts](https://img.shields.io/github/stars/usr2r00t/patches.svg) 
![forks](https://img.shields.io/github/forks/usr2r00t/patches.svg) 
2021-11-19T20:02:59Z

- [https://github.com/oneoy/CVE-2021-3156](https://github.com/oneoy/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/oneoy/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/oneoy/CVE-2021-3156.svg) 
2021-02-23T03:14:45Z

- [https://github.com/CyberCommands/CVE-2021-3156](https://github.com/CyberCommands/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/CyberCommands/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/CyberCommands/CVE-2021-3156.svg) 
2021-08-07T08:43:19Z

- [https://github.com/ymrsmns/CVE-2021-3156](https://github.com/ymrsmns/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/ymrsmns/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/ymrsmns/CVE-2021-3156.svg) 
2021-01-31T13:08:34Z

- [https://github.com/halissha/CVE-2021-3156](https://github.com/halissha/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/halissha/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/halissha/CVE-2021-3156.svg) 
2021-10-20T07:48:38Z

- [https://github.com/Jauler/cve2021-3156-sudo-heap-overflow](https://github.com/Jauler/cve2021-3156-sudo-heap-overflow) :  
![starts](https://img.shields.io/github/stars/Jauler/cve2021-3156-sudo-heap-overflow.svg) 
![forks](https://img.shields.io/github/forks/Jauler/cve2021-3156-sudo-heap-overflow.svg) 
2021-05-19T09:45:16Z

- [https://github.com/ret2basic/SudoScience](https://github.com/ret2basic/SudoScience) :  
![starts](https://img.shields.io/github/stars/ret2basic/SudoScience.svg) 
![forks](https://img.shields.io/github/forks/ret2basic/SudoScience.svg) 
2022-04-08T08:32:42Z

- [https://github.com/barebackbandit/CVE-2021-3156](https://github.com/barebackbandit/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/barebackbandit/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/barebackbandit/CVE-2021-3156.svg) 
2022-01-30T06:58:29Z

- [https://github.com/wurwur/CVE-2021-3156](https://github.com/wurwur/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/wurwur/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/wurwur/CVE-2021-3156.svg) 
2024-01-22T08:07:51Z

- [https://github.com/gmldbd94/cve-2021-3156](https://github.com/gmldbd94/cve-2021-3156) :  
![starts](https://img.shields.io/github/stars/gmldbd94/cve-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/gmldbd94/cve-2021-3156.svg) 
2021-02-09T07:22:13Z

- [https://github.com/Sebastianbedoya25/CVE-2021-3156](https://github.com/Sebastianbedoya25/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/Sebastianbedoya25/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/Sebastianbedoya25/CVE-2021-3156.svg) 
2024-12-03T03:17:08Z

- [https://github.com/arvindshima/CVE-2021-3156](https://github.com/arvindshima/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/arvindshima/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/arvindshima/CVE-2021-3156.svg) 
2022-06-24T11:55:52Z

- [https://github.com/Exodusro/CVE-2021-3156](https://github.com/Exodusro/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/Exodusro/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/Exodusro/CVE-2021-3156.svg) 
2021-07-25T23:01:24Z

- [https://github.com/ZTK-009/CVE-2021-3156](https://github.com/ZTK-009/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/ZTK-009/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/ZTK-009/CVE-2021-3156.svg) 
2021-04-04T01:15:12Z

- [https://github.com/freeFV/CVE-2021-3156](https://github.com/freeFV/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/freeFV/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/freeFV/CVE-2021-3156.svg) 
2021-01-29T11:36:52Z

- [https://github.com/Typical0day/CVE-2021-3156](https://github.com/Typical0day/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/Typical0day/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/Typical0day/CVE-2021-3156.svg) 
2024-07-08T01:49:51Z

- [https://github.com/hycheng15/CVE-2021-3156](https://github.com/hycheng15/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/hycheng15/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/hycheng15/CVE-2021-3156.svg) 
2023-11-14T10:24:57Z

- [https://github.com/DDayLuong/CVE-2021-3156](https://github.com/DDayLuong/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/DDayLuong/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/DDayLuong/CVE-2021-3156.svg) 
2023-12-27T03:54:30Z

- [https://github.com/mutur4/CVE-2021-3156](https://github.com/mutur4/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/mutur4/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/mutur4/CVE-2021-3156.svg) 
2024-04-10T14:50:04Z

- [https://github.com/d3c3ptic0n/CVE-2021-3156](https://github.com/d3c3ptic0n/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/d3c3ptic0n/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/d3c3ptic0n/CVE-2021-3156.svg) 
2021-08-16T01:26:26Z

- [https://github.com/acidburn2049/CVE-2021-3156](https://github.com/acidburn2049/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/acidburn2049/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/acidburn2049/CVE-2021-3156.svg) 
2024-09-13T04:20:37Z

- [https://github.com/capturingcats/CVE-2021-3156](https://github.com/capturingcats/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/capturingcats/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/capturingcats/CVE-2021-3156.svg) 
2021-04-05T18:03:00Z

- [https://github.com/asepsaepdin/CVE-2021-3156](https://github.com/asepsaepdin/CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/asepsaepdin/CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/asepsaepdin/CVE-2021-3156.svg) 
2023-09-05T14:23:29Z

- [https://github.com/SamTruss/LMU-CVE-2021-3156](https://github.com/SamTruss/LMU-CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/SamTruss/LMU-CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/SamTruss/LMU-CVE-2021-3156.svg) 
2024-02-12T14:31:50Z

- [https://github.com/cdeletre/Serpentiel-CVE-2021-3156](https://github.com/cdeletre/Serpentiel-CVE-2021-3156) :  
![starts](https://img.shields.io/github/stars/cdeletre/Serpentiel-CVE-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/cdeletre/Serpentiel-CVE-2021-3156.svg) 
2021-02-03T09:04:15Z

- [https://github.com/nexcess/sudo_cve-2021-3156](https://github.com/nexcess/sudo_cve-2021-3156) :  
![starts](https://img.shields.io/github/stars/nexcess/sudo_cve-2021-3156.svg) 
![forks](https://img.shields.io/github/forks/nexcess/sudo_cve-2021-3156.svg) 
2021-01-27T18:21:48Z

- [https://github.com/Ashish-dawani/CVE-2021-3156-Patch](https://github.com/Ashish-dawani/CVE-2021-3156-Patch) :  
![starts](https://img.shields.io/github/stars/Ashish-dawani/CVE-2021-3156-Patch.svg) 
![forks](https://img.shields.io/github/forks/Ashish-dawani/CVE-2021-3156-Patch.svg) 
2021-02-01T11:24:49Z

- [https://github.com/sharkmoos/Baron-Samedit](https://github.com/sharkmoos/Baron-Samedit) :  
![starts](https://img.shields.io/github/stars/sharkmoos/Baron-Samedit.svg) 
![forks](https://img.shields.io/github/forks/sharkmoos/Baron-Samedit.svg) 
2022-01-23T16:37:27Z

- [https://github.com/Bad3r/CVE-2021-3156-without-ip-command](https://github.com/Bad3r/CVE-2021-3156-without-ip-command) :  
![starts](https://img.shields.io/github/stars/Bad3r/CVE-2021-3156-without-ip-command.svg) 
![forks](https://img.shields.io/github/forks/Bad3r/CVE-2021-3156-without-ip-command.svg) 
2024-11-13T10:04:19Z

- [https://github.com/ajtech-hue/CVE-2021-3156-Mitigation-ShellScript-Build](https://github.com/ajtech-hue/CVE-2021-3156-Mitigation-ShellScript-Build) :  
![starts](https://img.shields.io/github/stars/ajtech-hue/CVE-2021-3156-Mitigation-ShellScript-Build.svg) 
![forks](https://img.shields.io/github/forks/ajtech-hue/CVE-2021-3156-Mitigation-ShellScript-Build.svg) 
2021-05-05T04:58:50Z

- [https://github.com/perlun/sudo-1.8.3p1-patched](https://github.com/perlun/sudo-1.8.3p1-patched) :  
![starts](https://img.shields.io/github/stars/perlun/sudo-1.8.3p1-patched.svg) 
![forks](https://img.shields.io/github/forks/perlun/sudo-1.8.3p1-patched.svg) 
2021-02-05T09:25:34Z

- [https://github.com/DanielAzulayy/CTF-2021](https://github.com/DanielAzulayy/CTF-2021) :  
![starts](https://img.shields.io/github/stars/DanielAzulayy/CTF-2021.svg) 
![forks](https://img.shields.io/github/forks/DanielAzulayy/CTF-2021.svg) 
2021-03-05T16:22:09Z

- [https://github.com/ten-ops/baron-samedit](https://github.com/ten-ops/baron-samedit) :  
![starts](https://img.shields.io/github/stars/ten-ops/baron-samedit.svg) 
![forks](https://img.shields.io/github/forks/ten-ops/baron-samedit.svg) 
2025-02-11T01:52:51Z

## CVE-2020-14871
 Vulnerability in the Oracle Solaris product of Oracle Systems (component: Pluggable authentication module). Supported versions that are affected are 10 and 11. Easily exploitable vulnerability allows unauthenticated attacker with network access via multiple protocols to compromise Oracle Solaris. While the vulnerability is in Oracle Solaris, attacks may significantly impact additional products. Successful attacks of this vulnerability can result in takeover of Oracle Solaris. Note: This CVE is not exploitable for Solaris 11.1 and later releases, and ZFSSA 8.7 and later releases, thus the CVSS Base Score is 0.0. CVSS 3.1 Base Score 10.0 (Confidentiality, Integrity and Availability impacts). CVSS Vector: (CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:C/C:H/I:H/A:H).

- [https://github.com/hackingyseguridad/ssha](https://github.com/hackingyseguridad/ssha) :  
![starts](https://img.shields.io/github/stars/hackingyseguridad/ssha.svg) 
![forks](https://img.shields.io/github/forks/hackingyseguridad/ssha.svg) 
2025-02-11T08:49:44Z

- [https://github.com/robidev/CVE-2020-14871-Exploit](https://github.com/robidev/CVE-2020-14871-Exploit) :  
![starts](https://img.shields.io/github/stars/robidev/CVE-2020-14871-Exploit.svg) 
![forks](https://img.shields.io/github/forks/robidev/CVE-2020-14871-Exploit.svg) 
2021-12-25T21:29:30Z

## CVE-2018-15473
 OpenSSH through 7.7 is prone to a user enumeration vulnerability due to not delaying bailout for an invalid authenticating user until after the packet containing the request has been fully parsed, related to auth2-gss.c, auth2-hostbased.c, and auth2-pubkey.c.

- [https://github.com/Rhynorater/CVE-2018-15473-Exploit](https://github.com/Rhynorater/CVE-2018-15473-Exploit) :  
![starts](https://img.shields.io/github/stars/Rhynorater/CVE-2018-15473-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Rhynorater/CVE-2018-15473-Exploit.svg) 
2024-07-12T08:47:49Z

- [https://github.com/trimstray/massh-enum](https://github.com/trimstray/massh-enum) :  
![starts](https://img.shields.io/github/stars/trimstray/massh-enum.svg) 
![forks](https://img.shields.io/github/forks/trimstray/massh-enum.svg) 
2019-11-15T08:12:32Z

- [https://github.com/epi052/cve-2018-15473](https://github.com/epi052/cve-2018-15473) :  
![starts](https://img.shields.io/github/stars/epi052/cve-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/epi052/cve-2018-15473.svg) 
2024-04-29T13:17:43Z

- [https://github.com/Sait-Nuri/CVE-2018-15473](https://github.com/Sait-Nuri/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/Sait-Nuri/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/Sait-Nuri/CVE-2018-15473.svg) 
2023-09-04T20:57:42Z

- [https://github.com/ilyaglow/dockerfiles](https://github.com/ilyaglow/dockerfiles) :  
![starts](https://img.shields.io/github/stars/ilyaglow/dockerfiles.svg) 
![forks](https://img.shields.io/github/forks/ilyaglow/dockerfiles.svg) 
2020-12-24T13:05:58Z

- [https://github.com/r3dxpl0it/CVE-2018-15473](https://github.com/r3dxpl0it/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/r3dxpl0it/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/r3dxpl0it/CVE-2018-15473.svg) 
2020-10-23T17:03:06Z

- [https://github.com/W-GOULD/ssh-user-enumeration](https://github.com/W-GOULD/ssh-user-enumeration) :  
![starts](https://img.shields.io/github/stars/W-GOULD/ssh-user-enumeration.svg) 
![forks](https://img.shields.io/github/forks/W-GOULD/ssh-user-enumeration.svg) 
2023-03-21T20:09:40Z

- [https://github.com/hackingyseguridad/ssha](https://github.com/hackingyseguridad/ssha) :  
![starts](https://img.shields.io/github/stars/hackingyseguridad/ssha.svg) 
![forks](https://img.shields.io/github/forks/hackingyseguridad/ssha.svg) 
2025-02-11T08:49:44Z

- [https://github.com/sergiovks/SSH-User-Enum-Python3-CVE-2018-15473](https://github.com/sergiovks/SSH-User-Enum-Python3-CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/sergiovks/SSH-User-Enum-Python3-CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/sergiovks/SSH-User-Enum-Python3-CVE-2018-15473.svg) 
2023-03-12T20:38:31Z

- [https://github.com/MrDottt/CVE-2018-15473](https://github.com/MrDottt/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/MrDottt/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/MrDottt/CVE-2018-15473.svg) 
2021-09-14T23:49:47Z

- [https://github.com/gbonacini/opensshenum](https://github.com/gbonacini/opensshenum) :  
![starts](https://img.shields.io/github/stars/gbonacini/opensshenum.svg) 
![forks](https://img.shields.io/github/forks/gbonacini/opensshenum.svg) 
2018-10-17T12:27:40Z

- [https://github.com/gbonacini/openssh_password_logger](https://github.com/gbonacini/openssh_password_logger) :  
![starts](https://img.shields.io/github/stars/gbonacini/openssh_password_logger.svg) 
![forks](https://img.shields.io/github/forks/gbonacini/openssh_password_logger.svg) 
2017-07-15T22:56:25Z

- [https://github.com/LINYIKAI/CVE-2018-15473-exp](https://github.com/LINYIKAI/CVE-2018-15473-exp) :  
![starts](https://img.shields.io/github/stars/LINYIKAI/CVE-2018-15473-exp.svg) 
![forks](https://img.shields.io/github/forks/LINYIKAI/CVE-2018-15473-exp.svg) 
2019-01-23T07:30:48Z

- [https://github.com/JoeBlackSecurity/SSHUsernameBruter-SSHUB](https://github.com/JoeBlackSecurity/SSHUsernameBruter-SSHUB) :  
![starts](https://img.shields.io/github/stars/JoeBlackSecurity/SSHUsernameBruter-SSHUB.svg) 
![forks](https://img.shields.io/github/forks/JoeBlackSecurity/SSHUsernameBruter-SSHUB.svg) 
2018-12-05T12:04:40Z

- [https://github.com/NHPT/SSH-account-enumeration-verification-script](https://github.com/NHPT/SSH-account-enumeration-verification-script) :  
![starts](https://img.shields.io/github/stars/NHPT/SSH-account-enumeration-verification-script.svg) 
![forks](https://img.shields.io/github/forks/NHPT/SSH-account-enumeration-verification-script.svg) 
2019-08-03T09:15:15Z

- [https://github.com/cved-sources/cve-2018-15473](https://github.com/cved-sources/cve-2018-15473) :  
![starts](https://img.shields.io/github/stars/cved-sources/cve-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/cved-sources/cve-2018-15473.svg) 
2021-04-15T21:31:46Z

- [https://github.com/mclbn/docker-cve-2018-15473](https://github.com/mclbn/docker-cve-2018-15473) :  
![starts](https://img.shields.io/github/stars/mclbn/docker-cve-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/mclbn/docker-cve-2018-15473.svg) 
2024-07-12T14:25:53Z

- [https://github.com/procamora/OpenSSH-Username-Enumeration](https://github.com/procamora/OpenSSH-Username-Enumeration) :  
![starts](https://img.shields.io/github/stars/procamora/OpenSSH-Username-Enumeration.svg) 
![forks](https://img.shields.io/github/forks/procamora/OpenSSH-Username-Enumeration.svg) 
2023-12-19T20:45:01Z

- [https://github.com/trickster1103/-](https://github.com/trickster1103/-) :  
![starts](https://img.shields.io/github/stars/trickster1103/-.svg) 
![forks](https://img.shields.io/github/forks/trickster1103/-.svg) 
2019-06-19T13:39:55Z

- [https://github.com/m-kis/ssh-enum-cve2018-15473](https://github.com/m-kis/ssh-enum-cve2018-15473) :  
![starts](https://img.shields.io/github/stars/m-kis/ssh-enum-cve2018-15473.svg) 
![forks](https://img.shields.io/github/forks/m-kis/ssh-enum-cve2018-15473.svg) 
2023-05-22T11:50:59Z

- [https://github.com/CaioCGH/EP4-redes](https://github.com/CaioCGH/EP4-redes) :  
![starts](https://img.shields.io/github/stars/CaioCGH/EP4-redes.svg) 
![forks](https://img.shields.io/github/forks/CaioCGH/EP4-redes.svg) 
2019-11-01T06:48:19Z

- [https://github.com/yZ1337/CVE-2018-15473](https://github.com/yZ1337/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/yZ1337/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/yZ1337/CVE-2018-15473.svg) 
2024-06-17T11:45:01Z

- [https://github.com/1stPeak/CVE-2018-15473](https://github.com/1stPeak/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/1stPeak/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/1stPeak/CVE-2018-15473.svg) 
2020-11-25T02:30:14Z

- [https://github.com/Wh1t3Fox/cve-2018-15473](https://github.com/Wh1t3Fox/cve-2018-15473) :  
![starts](https://img.shields.io/github/stars/Wh1t3Fox/cve-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/Wh1t3Fox/cve-2018-15473.svg) 
2022-03-29T22:02:30Z

- [https://github.com/0xrobiul/CVE-2018-15473](https://github.com/0xrobiul/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/0xrobiul/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/0xrobiul/CVE-2018-15473.svg) 
2022-09-03T11:45:12Z

- [https://github.com/4xolotl/CVE-2018-15473](https://github.com/4xolotl/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/4xolotl/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/4xolotl/CVE-2018-15473.svg) 
2023-10-31T13:23:31Z

- [https://github.com/philippedixon/CVE-2018-15473](https://github.com/philippedixon/CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/philippedixon/CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/philippedixon/CVE-2018-15473.svg) 
2023-01-01T19:35:41Z

- [https://github.com/GaboLC98/userenum-CVE-2018-15473](https://github.com/GaboLC98/userenum-CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/GaboLC98/userenum-CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/GaboLC98/userenum-CVE-2018-15473.svg) 
2023-05-15T16:43:11Z

- [https://github.com/66quentin/shodan-CVE-2018-15473](https://github.com/66quentin/shodan-CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/66quentin/shodan-CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/66quentin/shodan-CVE-2018-15473.svg) 
2021-12-11T16:02:26Z

- [https://github.com/coollce/CVE-2018-15473_burte](https://github.com/coollce/CVE-2018-15473_burte) :  
![starts](https://img.shields.io/github/stars/coollce/CVE-2018-15473_burte.svg) 
![forks](https://img.shields.io/github/forks/coollce/CVE-2018-15473_burte.svg) 
2020-11-26T05:32:17Z

- [https://github.com/pyperanger/CVE-2018-15473_exploit](https://github.com/pyperanger/CVE-2018-15473_exploit) :  
![starts](https://img.shields.io/github/stars/pyperanger/CVE-2018-15473_exploit.svg) 
![forks](https://img.shields.io/github/forks/pyperanger/CVE-2018-15473_exploit.svg) 
2021-04-06T19:17:05Z

- [https://github.com/NestyF/SSH_Enum_CVE-2018-15473](https://github.com/NestyF/SSH_Enum_CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/NestyF/SSH_Enum_CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/NestyF/SSH_Enum_CVE-2018-15473.svg) 
2024-10-17T14:42:19Z

- [https://github.com/Dirty-Racoon/CVE-2018-15473-py3](https://github.com/Dirty-Racoon/CVE-2018-15473-py3) :  
![starts](https://img.shields.io/github/stars/Dirty-Racoon/CVE-2018-15473-py3.svg) 
![forks](https://img.shields.io/github/forks/Dirty-Racoon/CVE-2018-15473-py3.svg) 
2020-11-27T12:30:51Z

- [https://github.com/SUDORM0X/PoC-CVE-2018-15473](https://github.com/SUDORM0X/PoC-CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/SUDORM0X/PoC-CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/SUDORM0X/PoC-CVE-2018-15473.svg) 
2024-11-20T13:48:04Z

- [https://github.com/Anonimo501/ssh_enum_users_CVE-2018-15473](https://github.com/Anonimo501/ssh_enum_users_CVE-2018-15473) :  
![starts](https://img.shields.io/github/stars/Anonimo501/ssh_enum_users_CVE-2018-15473.svg) 
![forks](https://img.shields.io/github/forks/Anonimo501/ssh_enum_users_CVE-2018-15473.svg) 
2023-04-21T13:23:02Z

- [https://github.com/WildfootW/CVE-2018-15473_OpenSSH_7.7](https://github.com/WildfootW/CVE-2018-15473_OpenSSH_7.7) :  
![starts](https://img.shields.io/github/stars/WildfootW/CVE-2018-15473_OpenSSH_7.7.svg) 
![forks](https://img.shields.io/github/forks/WildfootW/CVE-2018-15473_OpenSSH_7.7.svg) 
2020-12-09T15:10:02Z

- [https://github.com/MahdiOsman/CVE-2018-15473-SNMPv1-2-Community-String-Vulnerability-Testing](https://github.com/MahdiOsman/CVE-2018-15473-SNMPv1-2-Community-String-Vulnerability-Testing) :  
![starts](https://img.shields.io/github/stars/MahdiOsman/CVE-2018-15473-SNMPv1-2-Community-String-Vulnerability-Testing.svg) 
![forks](https://img.shields.io/github/forks/MahdiOsman/CVE-2018-15473-SNMPv1-2-Community-String-Vulnerability-Testing.svg) 
2024-08-15T11:42:01Z

- [https://github.com/Moon1705/easy_security](https://github.com/Moon1705/easy_security) :  
![starts](https://img.shields.io/github/stars/Moon1705/easy_security.svg) 
![forks](https://img.shields.io/github/forks/Moon1705/easy_security.svg) 
2023-12-19T20:44:38Z

- [https://github.com/An0nYm0u5101/enumpossible](https://github.com/An0nYm0u5101/enumpossible) :  
![starts](https://img.shields.io/github/stars/An0nYm0u5101/enumpossible.svg) 
![forks](https://img.shields.io/github/forks/An0nYm0u5101/enumpossible.svg) 
2019-09-24T21:38:00Z

- [https://github.com/OmarV4066/SSHEnumKL](https://github.com/OmarV4066/SSHEnumKL) :  
![starts](https://img.shields.io/github/stars/OmarV4066/SSHEnumKL.svg) 
![forks](https://img.shields.io/github/forks/OmarV4066/SSHEnumKL.svg) 
2025-02-09T20:21:37Z

## CVE-2016-6210
 sshd in OpenSSH before 7.3, when SHA256 or SHA512 are used for user password hashing, uses BLOWFISH hashing on a static password when the username does not exist, which allows remote attackers to enumerate users by leveraging the timing difference between responses when a large password is provided.

- [https://github.com/hackingyseguridad/ssha](https://github.com/hackingyseguridad/ssha) :  
![starts](https://img.shields.io/github/stars/hackingyseguridad/ssha.svg) 
![forks](https://img.shields.io/github/forks/hackingyseguridad/ssha.svg) 
2025-02-11T08:49:44Z

- [https://github.com/justlce/CVE-2016-6210-Exploit](https://github.com/justlce/CVE-2016-6210-Exploit) :  
![starts](https://img.shields.io/github/stars/justlce/CVE-2016-6210-Exploit.svg) 
![forks](https://img.shields.io/github/forks/justlce/CVE-2016-6210-Exploit.svg) 
2019-08-25T07:28:06Z

- [https://github.com/calebshortt/opensshd_user_enumeration](https://github.com/calebshortt/opensshd_user_enumeration) :  
![starts](https://img.shields.io/github/stars/calebshortt/opensshd_user_enumeration.svg) 
![forks](https://img.shields.io/github/forks/calebshortt/opensshd_user_enumeration.svg) 
2020-04-30T02:19:51Z

- [https://github.com/Tardcircus/CVE2016-6210](https://github.com/Tardcircus/CVE2016-6210) :  
![starts](https://img.shields.io/github/stars/Tardcircus/CVE2016-6210.svg) 
![forks](https://img.shields.io/github/forks/Tardcircus/CVE2016-6210.svg) 
2022-10-06T01:57:02Z

- [https://github.com/goomdan/CVE-2016-6210-exploit](https://github.com/goomdan/CVE-2016-6210-exploit) :  
![starts](https://img.shields.io/github/stars/goomdan/CVE-2016-6210-exploit.svg) 
![forks](https://img.shields.io/github/forks/goomdan/CVE-2016-6210-exploit.svg) 
2024-03-23T16:12:12Z

- [https://github.com/samh4cks/CVE-2016-6210-OpenSSH-User-Enumeration](https://github.com/samh4cks/CVE-2016-6210-OpenSSH-User-Enumeration) :  
![starts](https://img.shields.io/github/stars/samh4cks/CVE-2016-6210-OpenSSH-User-Enumeration.svg) 
![forks](https://img.shields.io/github/forks/samh4cks/CVE-2016-6210-OpenSSH-User-Enumeration.svg) 
2023-09-01T20:44:38Z

- [https://github.com/bassitone/OpenSSH-User-Enumeration](https://github.com/bassitone/OpenSSH-User-Enumeration) :  
![starts](https://img.shields.io/github/stars/bassitone/OpenSSH-User-Enumeration.svg) 
![forks](https://img.shields.io/github/forks/bassitone/OpenSSH-User-Enumeration.svg) 
2016-07-26T21:37:26Z

# 2025-02-10
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
2025-02-10T06:06:55Z

## CVE-2024-27348
 RCE-Remote Command Execution vulnerability in Apache HugeGraph-Server.This issue affects Apache HugeGraph-Server: from 1.0.0 before 1.3.0 in Java8 & Java11Users are recommended to upgrade to version 1.3.0 with Java11 & enable the Auth system, which fixes the issue.

- [https://github.com/Zeyad-Azima/CVE-2024-27348](https://github.com/Zeyad-Azima/CVE-2024-27348) :  
![starts](https://img.shields.io/github/stars/Zeyad-Azima/CVE-2024-27348.svg) 
![forks](https://img.shields.io/github/forks/Zeyad-Azima/CVE-2024-27348.svg) 
2024-06-08T09:12:43Z

- [https://github.com/kljunowsky/CVE-2024-27348](https://github.com/kljunowsky/CVE-2024-27348) :  
![starts](https://img.shields.io/github/stars/kljunowsky/CVE-2024-27348.svg) 
![forks](https://img.shields.io/github/forks/kljunowsky/CVE-2024-27348.svg) 
2024-06-03T19:20:10Z

- [https://github.com/jakabakos/CVE-2024-27348-Apache-HugeGraph-RCE](https://github.com/jakabakos/CVE-2024-27348-Apache-HugeGraph-RCE) :  
![starts](https://img.shields.io/github/stars/jakabakos/CVE-2024-27348-Apache-HugeGraph-RCE.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/CVE-2024-27348-Apache-HugeGraph-RCE.svg) 
2024-06-12T08:19:55Z

- [https://github.com/p0et08/CVE-2024-27348](https://github.com/p0et08/CVE-2024-27348) :  
![starts](https://img.shields.io/github/stars/p0et08/CVE-2024-27348.svg) 
![forks](https://img.shields.io/github/forks/p0et08/CVE-2024-27348.svg) 
2025-02-10T03:44:28Z

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

- [https://github.com/DerZiad/CVE-2024-21413](https://github.com/DerZiad/CVE-2024-21413) :  
![starts](https://img.shields.io/github/stars/DerZiad/CVE-2024-21413.svg) 
![forks](https://img.shields.io/github/forks/DerZiad/CVE-2024-21413.svg) 
2024-06-30T11:10:05Z

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

- [https://github.com/Cyber-Trambon/CVE-2024-21413-exploit](https://github.com/Cyber-Trambon/CVE-2024-21413-exploit) :  
![starts](https://img.shields.io/github/stars/Cyber-Trambon/CVE-2024-21413-exploit.svg) 
![forks](https://img.shields.io/github/forks/Cyber-Trambon/CVE-2024-21413-exploit.svg) 
2025-02-10T20:37:29Z

- [https://github.com/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape](https://github.com/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape) :  
![starts](https://img.shields.io/github/stars/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape.svg) 
![forks](https://img.shields.io/github/forks/Redfox-Secuirty/Unveiling-Moniker-Link-CVE-2024-21413-Navigating-the-Latest-Cybersecurity-Landscape.svg) 
2024-07-03T08:45:05Z

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

- [https://github.com/asterictnl-lvdw/CVE-2024-6387](https://github.com/asterictnl-lvdw/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/asterictnl-lvdw/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/asterictnl-lvdw/CVE-2024-6387.svg) 
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

- [https://github.com/ahlfors/CVE-2024-6387](https://github.com/ahlfors/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ahlfors/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ahlfors/CVE-2024-6387.svg) 
2024-07-02T09:57:35Z

- [https://github.com/ThatNotEasy/CVE-2024-6387](https://github.com/ThatNotEasy/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2024-6387.svg) 
2024-07-15T16:06:41Z

- [https://github.com/prelearn-code/CVE-2024-6387](https://github.com/prelearn-code/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/prelearn-code/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/prelearn-code/CVE-2024-6387.svg) 
2024-07-25T02:37:55Z

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

- [https://github.com/AzrDll/CVE-2024-6387](https://github.com/AzrDll/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/AzrDll/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/AzrDll/CVE-2024-6387.svg) 
2025-01-20T09:40:27Z

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

- [https://github.com/no-one-sec/CVE-2024-6387](https://github.com/no-one-sec/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/no-one-sec/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/no-one-sec/CVE-2024-6387.svg) 
2024-07-02T15:13:09Z

- [https://github.com/imv7/CVE-2024-6387](https://github.com/imv7/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/imv7/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/imv7/CVE-2024-6387.svg) 
2024-07-05T11:19:21Z

- [https://github.com/sms2056/CVE-2024-6387](https://github.com/sms2056/CVE-2024-6387) :  
![starts](https://img.shields.io/github/stars/sms2056/CVE-2024-6387.svg) 
![forks](https://img.shields.io/github/forks/sms2056/CVE-2024-6387.svg) 
2024-07-04T06:16:19Z

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
2024-07-14T18:02:26Z

- [https://github.com/DimaMend/cve-2024-6387-poc](https://github.com/DimaMend/cve-2024-6387-poc) :  
![starts](https://img.shields.io/github/stars/DimaMend/cve-2024-6387-poc.svg) 
![forks](https://img.shields.io/github/forks/DimaMend/cve-2024-6387-poc.svg) 
2024-07-10T13:33:50Z

- [https://github.com/Mufti22/CVE-2024-6387-checkher](https://github.com/Mufti22/CVE-2024-6387-checkher) :  
![starts](https://img.shields.io/github/stars/Mufti22/CVE-2024-6387-checkher.svg) 
![forks](https://img.shields.io/github/forks/Mufti22/CVE-2024-6387-checkher.svg) 
2024-07-02T03:49:06Z

- [https://github.com/CognisysGroup/CVE-2024-6387-Checker](https://github.com/CognisysGroup/CVE-2024-6387-Checker) :  
![starts](https://img.shields.io/github/stars/CognisysGroup/CVE-2024-6387-Checker.svg) 
![forks](https://img.shields.io/github/forks/CognisysGroup/CVE-2024-6387-Checker.svg) 
2024-07-03T12:13:37Z

- [https://github.com/edsonjt81/CVE-2024-6387_Check](https://github.com/edsonjt81/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/edsonjt81/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/edsonjt81/CVE-2024-6387_Check.svg) 
2024-07-02T20:38:06Z

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

- [https://github.com/SkyGodling/CVE-2024-6387-POC](https://github.com/SkyGodling/CVE-2024-6387-POC) :  
![starts](https://img.shields.io/github/stars/SkyGodling/CVE-2024-6387-POC.svg) 
![forks](https://img.shields.io/github/forks/SkyGodling/CVE-2024-6387-POC.svg) 
2025-02-10T06:25:56Z

- [https://github.com/HadesNull123/CVE-2024-6387_Check](https://github.com/HadesNull123/CVE-2024-6387_Check) :  
![starts](https://img.shields.io/github/stars/HadesNull123/CVE-2024-6387_Check.svg) 
![forks](https://img.shields.io/github/forks/HadesNull123/CVE-2024-6387_Check.svg) 
2024-08-26T04:41:02Z

- [https://github.com/RickGeex/CVE-2024-6387-Checker](https://github.com/RickGeex/CVE-2024-6387-Checker) :  
![starts](https://img.shields.io/github/stars/RickGeex/CVE-2024-6387-Checker.svg) 
![forks](https://img.shields.io/github/forks/RickGeex/CVE-2024-6387-Checker.svg) 
2024-07-02T20:32:48Z

- [https://github.com/jocker2410/CVE-2024-6387_poc](https://github.com/jocker2410/CVE-2024-6387_poc) :  
![starts](https://img.shields.io/github/stars/jocker2410/CVE-2024-6387_poc.svg) 
![forks](https://img.shields.io/github/forks/jocker2410/CVE-2024-6387_poc.svg) 
2024-08-04T10:50:53Z

- [https://github.com/4lxprime/regreSSHive](https://github.com/4lxprime/regreSSHive) :  
![starts](https://img.shields.io/github/stars/4lxprime/regreSSHive.svg) 
![forks](https://img.shields.io/github/forks/4lxprime/regreSSHive.svg) 
2024-07-04T14:34:23Z

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

- [https://github.com/almogopp/OpenSSH-CVE-2024-6387-Fix](https://github.com/almogopp/OpenSSH-CVE-2024-6387-Fix) :  
![starts](https://img.shields.io/github/stars/almogopp/OpenSSH-CVE-2024-6387-Fix.svg) 
![forks](https://img.shields.io/github/forks/almogopp/OpenSSH-CVE-2024-6387-Fix.svg) 
2024-08-20T09:58:32Z

- [https://github.com/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook](https://github.com/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook) :  
![starts](https://img.shields.io/github/stars/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook.svg) 
![forks](https://img.shields.io/github/forks/daniel-odrinski/CVE-2024-6387-Mitigation-Ansible-Playbook.svg) 
2024-07-02T11:05:55Z

- [https://github.com/vkaushik-chef/regreSSHion](https://github.com/vkaushik-chef/regreSSHion) :  
![starts](https://img.shields.io/github/stars/vkaushik-chef/regreSSHion.svg) 
![forks](https://img.shields.io/github/forks/vkaushik-chef/regreSSHion.svg) 
2024-07-08T12:04:33Z

- [https://github.com/Passyed/regreSSHion-Fix](https://github.com/Passyed/regreSSHion-Fix) :  
![starts](https://img.shields.io/github/stars/Passyed/regreSSHion-Fix.svg) 
![forks](https://img.shields.io/github/forks/Passyed/regreSSHion-Fix.svg) 
2024-07-12T00:06:59Z

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

## CVE-2023-46604
 The Java OpenWire protocol marshaller is vulnerable to Remote Code Execution. This vulnerability may allow a remote attacker with network access to either a Java-based OpenWire broker or client to run arbitrary shell commands by manipulating serialized class types in the OpenWire protocol to cause either the client or the broker (respectively) to instantiate any class on the classpath.Users are recommended to upgrade both brokers and clients to version 5.15.16, 5.16.7, 5.17.6, or 5.18.3 which fixes this issue.

- [https://github.com/X1r0z/ActiveMQ-RCE](https://github.com/X1r0z/ActiveMQ-RCE) :  
![starts](https://img.shields.io/github/stars/X1r0z/ActiveMQ-RCE.svg) 
![forks](https://img.shields.io/github/forks/X1r0z/ActiveMQ-RCE.svg) 
2024-01-29T02:28:11Z

- [https://github.com/SaumyajeetDas/CVE-2023-46604-RCE-Reverse-Shell-Apache-ActiveMQ](https://github.com/SaumyajeetDas/CVE-2023-46604-RCE-Reverse-Shell-Apache-ActiveMQ) :  
![starts](https://img.shields.io/github/stars/SaumyajeetDas/CVE-2023-46604-RCE-Reverse-Shell-Apache-ActiveMQ.svg) 
![forks](https://img.shields.io/github/forks/SaumyajeetDas/CVE-2023-46604-RCE-Reverse-Shell-Apache-ActiveMQ.svg) 
2024-01-20T16:59:23Z

- [https://github.com/JaneMandy/ActiveMQ_RCE_Pro_Max](https://github.com/JaneMandy/ActiveMQ_RCE_Pro_Max) :  
![starts](https://img.shields.io/github/stars/JaneMandy/ActiveMQ_RCE_Pro_Max.svg) 
![forks](https://img.shields.io/github/forks/JaneMandy/ActiveMQ_RCE_Pro_Max.svg) 
2023-11-03T14:14:31Z

- [https://github.com/evkl1d/CVE-2023-46604](https://github.com/evkl1d/CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/evkl1d/CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/evkl1d/CVE-2023-46604.svg) 
2023-11-06T07:26:30Z

- [https://github.com/trganda/ActiveMQ-RCE](https://github.com/trganda/ActiveMQ-RCE) :  
![starts](https://img.shields.io/github/stars/trganda/ActiveMQ-RCE.svg) 
![forks](https://img.shields.io/github/forks/trganda/ActiveMQ-RCE.svg) 
2023-10-26T03:28:14Z

- [https://github.com/duck-sec/CVE-2023-46604-ActiveMQ-RCE-pseudoshell](https://github.com/duck-sec/CVE-2023-46604-ActiveMQ-RCE-pseudoshell) :  
![starts](https://img.shields.io/github/stars/duck-sec/CVE-2023-46604-ActiveMQ-RCE-pseudoshell.svg) 
![forks](https://img.shields.io/github/forks/duck-sec/CVE-2023-46604-ActiveMQ-RCE-pseudoshell.svg) 
2024-01-24T13:44:29Z

- [https://github.com/Arlenhiack/ActiveMQ-RCE-Exploit](https://github.com/Arlenhiack/ActiveMQ-RCE-Exploit) :  
![starts](https://img.shields.io/github/stars/Arlenhiack/ActiveMQ-RCE-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Arlenhiack/ActiveMQ-RCE-Exploit.svg) 
2024-09-13T05:35:25Z

- [https://github.com/justdoit-cai/CVE-2023-46604-Apache-ActiveMQ-RCE-exp](https://github.com/justdoit-cai/CVE-2023-46604-Apache-ActiveMQ-RCE-exp) :  
![starts](https://img.shields.io/github/stars/justdoit-cai/CVE-2023-46604-Apache-ActiveMQ-RCE-exp.svg) 
![forks](https://img.shields.io/github/forks/justdoit-cai/CVE-2023-46604-Apache-ActiveMQ-RCE-exp.svg) 
2023-11-08T07:52:43Z

- [https://github.com/h3x3h0g/ActiveMQ-RCE-CVE-2023-46604-Write-up](https://github.com/h3x3h0g/ActiveMQ-RCE-CVE-2023-46604-Write-up) :  
![starts](https://img.shields.io/github/stars/h3x3h0g/ActiveMQ-RCE-CVE-2023-46604-Write-up.svg) 
![forks](https://img.shields.io/github/forks/h3x3h0g/ActiveMQ-RCE-CVE-2023-46604-Write-up.svg) 
2023-11-09T11:36:18Z

- [https://github.com/infokek/activemq-honeypot](https://github.com/infokek/activemq-honeypot) :  
![starts](https://img.shields.io/github/stars/infokek/activemq-honeypot.svg) 
![forks](https://img.shields.io/github/forks/infokek/activemq-honeypot.svg) 
2024-05-26T22:10:17Z

- [https://github.com/LiritoShawshark/CVE-2023-46604_ActiveMQ_RCE_Recurrence](https://github.com/LiritoShawshark/CVE-2023-46604_ActiveMQ_RCE_Recurrence) :  
![starts](https://img.shields.io/github/stars/LiritoShawshark/CVE-2023-46604_ActiveMQ_RCE_Recurrence.svg) 
![forks](https://img.shields.io/github/forks/LiritoShawshark/CVE-2023-46604_ActiveMQ_RCE_Recurrence.svg) 
2023-11-16T02:37:56Z

- [https://github.com/dcm2406/CVE-Lab](https://github.com/dcm2406/CVE-Lab) :  
![starts](https://img.shields.io/github/stars/dcm2406/CVE-Lab.svg) 
![forks](https://img.shields.io/github/forks/dcm2406/CVE-Lab.svg) 
2024-03-20T06:20:44Z

- [https://github.com/Anekant-Singhai/Exploits](https://github.com/Anekant-Singhai/Exploits) :  
![starts](https://img.shields.io/github/stars/Anekant-Singhai/Exploits.svg) 
![forks](https://img.shields.io/github/forks/Anekant-Singhai/Exploits.svg) 
2024-05-04T13:25:52Z

- [https://github.com/mrpentst/CVE-2023-46604](https://github.com/mrpentst/CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/mrpentst/CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/mrpentst/CVE-2023-46604.svg) 
2024-02-24T16:15:58Z

- [https://github.com/pulentoski/CVE-2023-46604](https://github.com/pulentoski/CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/pulentoski/CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/pulentoski/CVE-2023-46604.svg) 
2024-05-31T02:29:59Z

- [https://github.com/NKeshawarz/CVE-2023-46604-RCE](https://github.com/NKeshawarz/CVE-2023-46604-RCE) :  
![starts](https://img.shields.io/github/stars/NKeshawarz/CVE-2023-46604-RCE.svg) 
![forks](https://img.shields.io/github/forks/NKeshawarz/CVE-2023-46604-RCE.svg) 
2023-11-18T13:18:51Z

- [https://github.com/stegano5/ExploitScript-CVE-2023-46604](https://github.com/stegano5/ExploitScript-CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/stegano5/ExploitScript-CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/stegano5/ExploitScript-CVE-2023-46604.svg) 
2024-02-14T19:19:47Z

- [https://github.com/minhangxiaohui/ActiveMQ_CVE-2023-46604](https://github.com/minhangxiaohui/ActiveMQ_CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/minhangxiaohui/ActiveMQ_CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/minhangxiaohui/ActiveMQ_CVE-2023-46604.svg) 
2023-11-20T07:41:12Z

- [https://github.com/thinkycx/activemq-rce-cve-2023-46604](https://github.com/thinkycx/activemq-rce-cve-2023-46604) :  
![starts](https://img.shields.io/github/stars/thinkycx/activemq-rce-cve-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/thinkycx/activemq-rce-cve-2023-46604.svg) 
2024-04-26T11:45:29Z

- [https://github.com/cuanh2333/CVE-2023-46604](https://github.com/cuanh2333/CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/cuanh2333/CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/cuanh2333/CVE-2023-46604.svg) 
2024-12-15T08:21:46Z

- [https://github.com/hh-hunter/cve-2023-46604](https://github.com/hh-hunter/cve-2023-46604) :  
![starts](https://img.shields.io/github/stars/hh-hunter/cve-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/hh-hunter/cve-2023-46604.svg) 
2024-01-09T03:18:19Z

- [https://github.com/vulncheck-oss/cve-2023-46604](https://github.com/vulncheck-oss/cve-2023-46604) :  
![starts](https://img.shields.io/github/stars/vulncheck-oss/cve-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/vulncheck-oss/cve-2023-46604.svg) 
2025-02-10T16:21:40Z

- [https://github.com/dcm2406/CVE-2023-46604](https://github.com/dcm2406/CVE-2023-46604) :  
![starts](https://img.shields.io/github/stars/dcm2406/CVE-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/dcm2406/CVE-2023-46604.svg) 
2023-12-21T12:00:08Z

- [https://github.com/nitzanoligo/CVE-2023-46604-demo](https://github.com/nitzanoligo/CVE-2023-46604-demo) :  
![starts](https://img.shields.io/github/stars/nitzanoligo/CVE-2023-46604-demo.svg) 
![forks](https://img.shields.io/github/forks/nitzanoligo/CVE-2023-46604-demo.svg) 
2024-11-05T13:10:01Z

- [https://github.com/tomasmussi/activemq-cve-2023-46604](https://github.com/tomasmussi/activemq-cve-2023-46604) :  
![starts](https://img.shields.io/github/stars/tomasmussi/activemq-cve-2023-46604.svg) 
![forks](https://img.shields.io/github/forks/tomasmussi/activemq-cve-2023-46604.svg) 
2025-01-21T20:11:37Z

- [https://github.com/vjayant93/CVE-2023-46604-POC](https://github.com/vjayant93/CVE-2023-46604-POC) :  
![starts](https://img.shields.io/github/stars/vjayant93/CVE-2023-46604-POC.svg) 
![forks](https://img.shields.io/github/forks/vjayant93/CVE-2023-46604-POC.svg) 
2023-11-16T21:21:54Z

- [https://github.com/Mudoleto/Broker_ApacheMQ](https://github.com/Mudoleto/Broker_ApacheMQ) :  
![starts](https://img.shields.io/github/stars/Mudoleto/Broker_ApacheMQ.svg) 
![forks](https://img.shields.io/github/forks/Mudoleto/Broker_ApacheMQ.svg) 
2023-12-26T05:21:06Z

- [https://github.com/mranv/honeypot.rs](https://github.com/mranv/honeypot.rs) :  
![starts](https://img.shields.io/github/stars/mranv/honeypot.rs.svg) 
![forks](https://img.shields.io/github/forks/mranv/honeypot.rs.svg) 
2024-07-22T18:11:00Z

## CVE-2023-26136
 Versions of the package tough-cookie before 4.1.3 are vulnerable to Prototype Pollution due to improper handling of Cookies when using CookieJar in rejectPublicSuffixes=false mode. This issue arises from the manner in which the objects are initialized.

- [https://github.com/CUCUMBERanOrSNCompany/SealSecurityAssignment](https://github.com/CUCUMBERanOrSNCompany/SealSecurityAssignment) :  
![starts](https://img.shields.io/github/stars/CUCUMBERanOrSNCompany/SealSecurityAssignment.svg) 
![forks](https://img.shields.io/github/forks/CUCUMBERanOrSNCompany/SealSecurityAssignment.svg) 
2023-12-06T10:50:09Z

- [https://github.com/dani33339/tough-cookie-Seal-Security](https://github.com/dani33339/tough-cookie-Seal-Security) :  
![starts](https://img.shields.io/github/stars/dani33339/tough-cookie-Seal-Security.svg) 
![forks](https://img.shields.io/github/forks/dani33339/tough-cookie-Seal-Security.svg) 
2025-02-05T18:07:08Z

- [https://github.com/morrisel/CVE-2023-26136](https://github.com/morrisel/CVE-2023-26136) :  
![starts](https://img.shields.io/github/stars/morrisel/CVE-2023-26136.svg) 
![forks](https://img.shields.io/github/forks/morrisel/CVE-2023-26136.svg) 
2025-02-10T13:06:08Z

- [https://github.com/m-lito13/SealSecurity_Exam](https://github.com/m-lito13/SealSecurity_Exam) :  
![starts](https://img.shields.io/github/stars/m-lito13/SealSecurity_Exam.svg) 
![forks](https://img.shields.io/github/forks/m-lito13/SealSecurity_Exam.svg) 
2024-09-04T11:36:13Z

- [https://github.com/ronmadar/Open-Source-Seal-Security](https://github.com/ronmadar/Open-Source-Seal-Security) :  
![starts](https://img.shields.io/github/stars/ronmadar/Open-Source-Seal-Security.svg) 
![forks](https://img.shields.io/github/forks/ronmadar/Open-Source-Seal-Security.svg) 
2024-05-07T12:18:56Z

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
2025-02-10T08:53:08Z

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

## CVE-2023-3824
 In PHP version 8.0.* before 8.0.30, 8.1.* before 8.1.22, and 8.2.* before 8.2.8, when loading phar file, while reading PHAR directory entries, insufficient length checking may lead to a stack buffer overflow, leading potentially to memory corruption or RCE.

- [https://github.com/exploitdevelop/CVE-2023-3824](https://github.com/exploitdevelop/CVE-2023-3824) :  
![starts](https://img.shields.io/github/stars/exploitdevelop/CVE-2023-3824.svg) 
![forks](https://img.shields.io/github/forks/exploitdevelop/CVE-2023-3824.svg) 
2025-02-10T16:04:33Z

- [https://github.com/fr33c0d3/poc-cve-2023-3824](https://github.com/fr33c0d3/poc-cve-2023-3824) :  
![starts](https://img.shields.io/github/stars/fr33c0d3/poc-cve-2023-3824.svg) 
![forks](https://img.shields.io/github/forks/fr33c0d3/poc-cve-2023-3824.svg) 
2025-01-08T01:49:58Z

- [https://github.com/jhonnybonny/CVE-2023-3824](https://github.com/jhonnybonny/CVE-2023-3824) :  
![starts](https://img.shields.io/github/stars/jhonnybonny/CVE-2023-3824.svg) 
![forks](https://img.shields.io/github/forks/jhonnybonny/CVE-2023-3824.svg) 
2024-03-18T10:49:20Z

- [https://github.com/bluefish3r/poc-cve](https://github.com/bluefish3r/poc-cve) :  
![starts](https://img.shields.io/github/stars/bluefish3r/poc-cve.svg) 
![forks](https://img.shields.io/github/forks/bluefish3r/poc-cve.svg) 
2025-01-11T17:42:37Z

- [https://github.com/s1mpl3c0d3/cvepoc](https://github.com/s1mpl3c0d3/cvepoc) :  
![starts](https://img.shields.io/github/stars/s1mpl3c0d3/cvepoc.svg) 
![forks](https://img.shields.io/github/forks/s1mpl3c0d3/cvepoc.svg) 
2025-02-08T13:21:07Z

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
2025-01-24T11:47:24Z

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

## CVE-2022-41742
 NGINX Open Source before versions 1.23.2 and 1.22.1, NGINX Open Source Subscription before versions R2 P1 and R1 P1, and NGINX Plus before versions R27 P1 and R26 P1 have a vulnerability in the module ngx_http_mp4_module that might allow a local attacker to cause a worker process crash, or might result in worker process memory disclosure by using a specially crafted audio or video file. The issue affects only NGINX products that are built with the module ngx_http_mp4_module, when the mp4 directive is used in the configuration file. Further, the attack is possible only if an attacker can trigger processing of a specially crafted audio or video file with the module ngx_http_mp4_module.

- [https://github.com/moften/CVE-2022-4174_CVE-2022-41742](https://github.com/moften/CVE-2022-4174_CVE-2022-41742) :  
![starts](https://img.shields.io/github/stars/moften/CVE-2022-4174_CVE-2022-41742.svg) 
![forks](https://img.shields.io/github/forks/moften/CVE-2022-4174_CVE-2022-41742.svg) 
2025-02-10T23:07:29Z

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
2025-02-10T15:09:36Z

- [https://github.com/niklasmato/fortileak-01-2025-Be](https://github.com/niklasmato/fortileak-01-2025-Be) :  
![starts](https://img.shields.io/github/stars/niklasmato/fortileak-01-2025-Be.svg) 
![forks](https://img.shields.io/github/forks/niklasmato/fortileak-01-2025-Be.svg) 
2025-01-24T14:54:56Z

## CVE-2021-45105
 Apache Log4j2 versions 2.0-alpha1 through 2.16.0 (excluding 2.12.3 and 2.3.1) did not protect from uncontrolled recursion from self-referential lookups. This allows an attacker with control over Thread Context Map data to cause a denial of service when a crafted string is interpreted. This issue was fixed in Log4j 2.17.0, 2.12.3, and 2.3.1.

- [https://github.com/NCSC-NL/log4shell](https://github.com/NCSC-NL/log4shell) :  
![starts](https://img.shields.io/github/stars/NCSC-NL/log4shell.svg) 
![forks](https://img.shields.io/github/forks/NCSC-NL/log4shell.svg) 
2022-06-15T23:59:35Z

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

- [https://github.com/dtact/divd-2021-00038--log4j-scanner](https://github.com/dtact/divd-2021-00038--log4j-scanner) :  
![starts](https://img.shields.io/github/stars/dtact/divd-2021-00038--log4j-scanner.svg) 
![forks](https://img.shields.io/github/forks/dtact/divd-2021-00038--log4j-scanner.svg) 
2021-12-28T22:21:52Z

- [https://github.com/HynekPetrak/log4shell-finder](https://github.com/HynekPetrak/log4shell-finder) :  
![starts](https://img.shields.io/github/stars/HynekPetrak/log4shell-finder.svg) 
![forks](https://img.shields.io/github/forks/HynekPetrak/log4shell-finder.svg) 
2023-06-21T11:37:03Z

- [https://github.com/cckuailong/Log4j_dos_CVE-2021-45105](https://github.com/cckuailong/Log4j_dos_CVE-2021-45105) :  
![starts](https://img.shields.io/github/stars/cckuailong/Log4j_dos_CVE-2021-45105.svg) 
![forks](https://img.shields.io/github/forks/cckuailong/Log4j_dos_CVE-2021-45105.svg) 
2021-12-19T01:59:52Z

- [https://github.com/hupe1980/scan4log4shell](https://github.com/hupe1980/scan4log4shell) :  
![starts](https://img.shields.io/github/stars/hupe1980/scan4log4shell.svg) 
![forks](https://img.shields.io/github/forks/hupe1980/scan4log4shell.svg) 
2022-02-15T13:04:54Z

- [https://github.com/pfichtner/log4shell-hunter](https://github.com/pfichtner/log4shell-hunter) :  
![starts](https://img.shields.io/github/stars/pfichtner/log4shell-hunter.svg) 
![forks](https://img.shields.io/github/forks/pfichtner/log4shell-hunter.svg) 
2025-02-10T06:27:29Z

- [https://github.com/thl-cmk/CVE-log4j-check_mk-plugin](https://github.com/thl-cmk/CVE-log4j-check_mk-plugin) :  
![starts](https://img.shields.io/github/stars/thl-cmk/CVE-log4j-check_mk-plugin.svg) 
![forks](https://img.shields.io/github/forks/thl-cmk/CVE-log4j-check_mk-plugin.svg) 
2022-02-14T11:08:43Z

- [https://github.com/iAmSOScArEd/log4j2_dos_exploit](https://github.com/iAmSOScArEd/log4j2_dos_exploit) :  
![starts](https://img.shields.io/github/stars/iAmSOScArEd/log4j2_dos_exploit.svg) 
![forks](https://img.shields.io/github/forks/iAmSOScArEd/log4j2_dos_exploit.svg) 
2021-12-22T02:37:35Z

- [https://github.com/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832](https://github.com/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832) :  
![starts](https://img.shields.io/github/stars/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832.svg) 
![forks](https://img.shields.io/github/forks/thedevappsecguy/Log4J-Mitigation-CVE-2021-44228--CVE-2021-45046--CVE-2021-45105--CVE-2021-44832.svg) 
2022-01-03T17:43:06Z

- [https://github.com/name/log4j-remediation](https://github.com/name/log4j-remediation) :  
![starts](https://img.shields.io/github/stars/name/log4j-remediation.svg) 
![forks](https://img.shields.io/github/forks/name/log4j-remediation.svg) 
2021-12-24T00:56:20Z

- [https://github.com/demonrvm/Log4ShellRemediation](https://github.com/demonrvm/Log4ShellRemediation) :  
![starts](https://img.shields.io/github/stars/demonrvm/Log4ShellRemediation.svg) 
![forks](https://img.shields.io/github/forks/demonrvm/Log4ShellRemediation.svg) 
2023-04-04T00:04:34Z

- [https://github.com/andalik/log4j-filescan](https://github.com/andalik/log4j-filescan) :  
![starts](https://img.shields.io/github/stars/andalik/log4j-filescan.svg) 
![forks](https://img.shields.io/github/forks/andalik/log4j-filescan.svg) 
2022-03-05T23:01:15Z

- [https://github.com/Afrouper/MavenDependencyCVE-Scanner](https://github.com/Afrouper/MavenDependencyCVE-Scanner) :  
![starts](https://img.shields.io/github/stars/Afrouper/MavenDependencyCVE-Scanner.svg) 
![forks](https://img.shields.io/github/forks/Afrouper/MavenDependencyCVE-Scanner.svg) 
2025-02-10T04:53:00Z

- [https://github.com/Locj41/demo-cve2021-45105](https://github.com/Locj41/demo-cve2021-45105) :  
![starts](https://img.shields.io/github/stars/Locj41/demo-cve2021-45105.svg) 
![forks](https://img.shields.io/github/forks/Locj41/demo-cve2021-45105.svg) 
2024-01-02T14:13:23Z

- [https://github.com/tejas-nagchandi/CVE-2021-45105](https://github.com/tejas-nagchandi/CVE-2021-45105) :  
![starts](https://img.shields.io/github/stars/tejas-nagchandi/CVE-2021-45105.svg) 
![forks](https://img.shields.io/github/forks/tejas-nagchandi/CVE-2021-45105.svg) 
2021-12-20T00:49:02Z

- [https://github.com/pravin-pp/log4j2-CVE-2021-45105](https://github.com/pravin-pp/log4j2-CVE-2021-45105) :  
![starts](https://img.shields.io/github/stars/pravin-pp/log4j2-CVE-2021-45105.svg) 
![forks](https://img.shields.io/github/forks/pravin-pp/log4j2-CVE-2021-45105.svg) 
2021-12-18T14:34:39Z

- [https://github.com/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105](https://github.com/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105) :  
![starts](https://img.shields.io/github/stars/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105.svg) 
![forks](https://img.shields.io/github/forks/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105.svg) 
2021-12-23T11:38:33Z

- [https://github.com/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105-1](https://github.com/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105-1) :  
![starts](https://img.shields.io/github/stars/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105-1.svg) 
![forks](https://img.shields.io/github/forks/dileepdkumar/https-github.com-pravin-pp-log4j2-CVE-2021-45105-1.svg) 
2021-12-23T17:46:11Z

- [https://github.com/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105-v](https://github.com/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105-v) :  
![starts](https://img.shields.io/github/stars/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105-v.svg) 
![forks](https://img.shields.io/github/forks/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105-v.svg) 
2021-12-23T11:41:26Z

- [https://github.com/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105](https://github.com/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105) :  
![starts](https://img.shields.io/github/stars/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105.svg) 
![forks](https://img.shields.io/github/forks/dileepdkumar/https-github.com-dileepdkumar-https-github.com-pravin-pp-log4j2-CVE-2021-45105.svg) 
2021-12-23T11:40:50Z

- [https://github.com/yannart/log4shell-scanner-rs](https://github.com/yannart/log4shell-scanner-rs) :  
![starts](https://img.shields.io/github/stars/yannart/log4shell-scanner-rs.svg) 
![forks](https://img.shields.io/github/forks/yannart/log4shell-scanner-rs.svg) 
2022-09-26T01:32:06Z

- [https://github.com/richardbischof/log4j-detector-to-csv](https://github.com/richardbischof/log4j-detector-to-csv) :  
![starts](https://img.shields.io/github/stars/richardbischof/log4j-detector-to-csv.svg) 
![forks](https://img.shields.io/github/forks/richardbischof/log4j-detector-to-csv.svg) 
2021-12-27T11:44:36Z

## CVE-2020-9529
 Firmware developed by Shenzhen Hichip Vision Technology (V6 through V20), as used by many different vendors in millions of Internet of Things devices, suffers from a privilege escalation vulnerability that allows attackers on the local network to reset the device's administrator password. This affects products marketed under the following brand names: Accfly, Alptop, Anlink, Besdersec, BOAVISION, COOAU, CPVAN, Ctronics, D3D Security, Dericam, Elex System, Elite Security, ENSTER, ePGes, Escam, FLOUREON, GENBOLT, Hongjingtian (HJT), ICAMI, Iegeek, Jecurity, Jennov, KKMoon, LEFTEK, Loosafe, Luowice, Nesuniq, Nettoly, ProElite, QZT, Royallite, SDETER, SV3C, SY2L, Tenvis, ThinkValue, TOMLOV, TPTEK, WGCC, and ZILINK.

- [https://github.com/dimalmfao/hichipreset](https://github.com/dimalmfao/hichipreset) :  
![starts](https://img.shields.io/github/stars/dimalmfao/hichipreset.svg) 
![forks](https://img.shields.io/github/forks/dimalmfao/hichipreset.svg) 
2025-02-10T18:49:20Z

## CVE-2019-20372
 NGINX before 1.17.7, with certain error_page configurations, allows HTTP request smuggling, as demonstrated by the ability of an attacker to read unauthorized web pages in environments where NGINX is being fronted by a load balancer.

- [https://github.com/0xleft/CVE-2019-20372](https://github.com/0xleft/CVE-2019-20372) :  
![starts](https://img.shields.io/github/stars/0xleft/CVE-2019-20372.svg) 
![forks](https://img.shields.io/github/forks/0xleft/CVE-2019-20372.svg) 
2023-09-16T19:49:56Z

- [https://github.com/moften/CVE-2019-20372](https://github.com/moften/CVE-2019-20372) :  
![starts](https://img.shields.io/github/stars/moften/CVE-2019-20372.svg) 
![forks](https://img.shields.io/github/forks/moften/CVE-2019-20372.svg) 
2025-02-10T23:11:43Z

- [https://github.com/vuongnv3389-sec/CVE-2019-20372](https://github.com/vuongnv3389-sec/CVE-2019-20372) :  
![starts](https://img.shields.io/github/stars/vuongnv3389-sec/CVE-2019-20372.svg) 
![forks](https://img.shields.io/github/forks/vuongnv3389-sec/CVE-2019-20372.svg) 
2022-04-06T17:13:05Z

## CVE-2019-18935
 Progress Telerik UI for ASP.NET AJAX through 2019.3.1023 contains a .NET deserialization vulnerability in the RadAsyncUpload function. This is exploitable when the encryption keys are known due to the presence of CVE-2017-11317 or CVE-2017-11357, or other means. Exploitation can result in remote code execution. (As of 2020.1.114, a default setting prevents the exploit. In 2019.3.1023, but not earlier versions, a non-default setting can prevent exploitation.)

- [https://github.com/noperator/CVE-2019-18935](https://github.com/noperator/CVE-2019-18935) :  
![starts](https://img.shields.io/github/stars/noperator/CVE-2019-18935.svg) 
![forks](https://img.shields.io/github/forks/noperator/CVE-2019-18935.svg) 
2022-04-14T18:23:38Z

- [https://github.com/bao7uo/RAU_crypto](https://github.com/bao7uo/RAU_crypto) :  
![starts](https://img.shields.io/github/stars/bao7uo/RAU_crypto.svg) 
![forks](https://img.shields.io/github/forks/bao7uo/RAU_crypto.svg) 
2020-08-22T06:15:54Z

- [https://github.com/murataydemir/CVE-2019-18935](https://github.com/murataydemir/CVE-2019-18935) :  
![starts](https://img.shields.io/github/stars/murataydemir/CVE-2019-18935.svg) 
![forks](https://img.shields.io/github/forks/murataydemir/CVE-2019-18935.svg) 
2020-08-25T07:55:22Z

- [https://github.com/ThanHuuTuan/Telerik_CVE-2019-18935](https://github.com/ThanHuuTuan/Telerik_CVE-2019-18935) :  
![starts](https://img.shields.io/github/stars/ThanHuuTuan/Telerik_CVE-2019-18935.svg) 
![forks](https://img.shields.io/github/forks/ThanHuuTuan/Telerik_CVE-2019-18935.svg) 
2023-05-10T02:17:34Z

- [https://github.com/dust-life/CVE-2019-18935-memShell](https://github.com/dust-life/CVE-2019-18935-memShell) :  
![starts](https://img.shields.io/github/stars/dust-life/CVE-2019-18935-memShell.svg) 
![forks](https://img.shields.io/github/forks/dust-life/CVE-2019-18935-memShell.svg) 
2024-11-25T04:04:18Z

- [https://github.com/random-robbie/CVE-2019-18935](https://github.com/random-robbie/CVE-2019-18935) :  
![starts](https://img.shields.io/github/stars/random-robbie/CVE-2019-18935.svg) 
![forks](https://img.shields.io/github/forks/random-robbie/CVE-2019-18935.svg) 
2020-09-30T10:00:43Z

- [https://github.com/ThanHuuTuan/CVE_2019_18935](https://github.com/ThanHuuTuan/CVE_2019_18935) :  
![starts](https://img.shields.io/github/stars/ThanHuuTuan/CVE_2019_18935.svg) 
![forks](https://img.shields.io/github/forks/ThanHuuTuan/CVE_2019_18935.svg) 
2020-05-29T07:33:42Z

- [https://github.com/becrevex/Telerik_CVE-2019-18935](https://github.com/becrevex/Telerik_CVE-2019-18935) :  
![starts](https://img.shields.io/github/stars/becrevex/Telerik_CVE-2019-18935.svg) 
![forks](https://img.shields.io/github/forks/becrevex/Telerik_CVE-2019-18935.svg) 
2021-01-21T06:12:57Z

- [https://github.com/appliedi/Telerik_CVE-2019-18935](https://github.com/appliedi/Telerik_CVE-2019-18935) :  
![starts](https://img.shields.io/github/stars/appliedi/Telerik_CVE-2019-18935.svg) 
![forks](https://img.shields.io/github/forks/appliedi/Telerik_CVE-2019-18935.svg) 
2020-07-22T14:17:10Z

- [https://github.com/0xAgun/CVE-2019-18935-checker](https://github.com/0xAgun/CVE-2019-18935-checker) :  
![starts](https://img.shields.io/github/stars/0xAgun/CVE-2019-18935-checker.svg) 
![forks](https://img.shields.io/github/forks/0xAgun/CVE-2019-18935-checker.svg) 
2021-10-29T17:04:20Z

- [https://github.com/luuquy/DecryptRawdata_CVE_2019_18935](https://github.com/luuquy/DecryptRawdata_CVE_2019_18935) :  
![starts](https://img.shields.io/github/stars/luuquy/DecryptRawdata_CVE_2019_18935.svg) 
![forks](https://img.shields.io/github/forks/luuquy/DecryptRawdata_CVE_2019_18935.svg) 
2020-10-21T09:44:35Z

- [https://github.com/KasunPriyashan/Telerik-UI-ASP.NET-AJAX-Exploitation](https://github.com/KasunPriyashan/Telerik-UI-ASP.NET-AJAX-Exploitation) :  
![starts](https://img.shields.io/github/stars/KasunPriyashan/Telerik-UI-ASP.NET-AJAX-Exploitation.svg) 
![forks](https://img.shields.io/github/forks/KasunPriyashan/Telerik-UI-ASP.NET-AJAX-Exploitation.svg) 
2022-10-13T14:22:09Z

- [https://github.com/MorphyKutay/TelerikVulnCheck](https://github.com/MorphyKutay/TelerikVulnCheck) :  
![starts](https://img.shields.io/github/stars/MorphyKutay/TelerikVulnCheck.svg) 
![forks](https://img.shields.io/github/forks/MorphyKutay/TelerikVulnCheck.svg) 
2025-02-10T18:23:56Z

## CVE-2019-5420
 A remote code execution vulnerability in development mode Rails 5.2.2.1, 6.0.0.beta3 can allow an attacker to guess the automatically generated development mode secret token. This secret token can be used in combination with other Rails internals to escalate to a remote code execution exploit.

- [https://github.com/mpgn/Rails-doubletap-RCE](https://github.com/mpgn/Rails-doubletap-RCE) :  
![starts](https://img.shields.io/github/stars/mpgn/Rails-doubletap-RCE.svg) 
![forks](https://img.shields.io/github/forks/mpgn/Rails-doubletap-RCE.svg) 
2023-01-19T12:13:40Z

- [https://github.com/knqyf263/CVE-2019-5420](https://github.com/knqyf263/CVE-2019-5420) :  
![starts](https://img.shields.io/github/stars/knqyf263/CVE-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/knqyf263/CVE-2019-5420.svg) 
2019-03-21T23:52:48Z

- [https://github.com/j4k0m/CVE-2019-5420](https://github.com/j4k0m/CVE-2019-5420) :  
![starts](https://img.shields.io/github/stars/j4k0m/CVE-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/j4k0m/CVE-2019-5420.svg) 
2021-09-07T13:11:02Z

- [https://github.com/laffray/ruby-RCE-CVE-2019-5420-](https://github.com/laffray/ruby-RCE-CVE-2019-5420-) :  
![starts](https://img.shields.io/github/stars/laffray/ruby-RCE-CVE-2019-5420-.svg) 
![forks](https://img.shields.io/github/forks/laffray/ruby-RCE-CVE-2019-5420-.svg) 
2022-07-02T15:48:28Z

- [https://github.com/scumdestroy/CVE-2019-5420.rb](https://github.com/scumdestroy/CVE-2019-5420.rb) :  
![starts](https://img.shields.io/github/stars/scumdestroy/CVE-2019-5420.rb.svg) 
![forks](https://img.shields.io/github/forks/scumdestroy/CVE-2019-5420.rb.svg) 
2022-01-12T02:39:51Z

- [https://github.com/WildWestCyberSecurity/cve-2019-5420-POC](https://github.com/WildWestCyberSecurity/cve-2019-5420-POC) :  
![starts](https://img.shields.io/github/stars/WildWestCyberSecurity/cve-2019-5420-POC.svg) 
![forks](https://img.shields.io/github/forks/WildWestCyberSecurity/cve-2019-5420-POC.svg) 
2025-02-10T15:36:06Z

- [https://github.com/cved-sources/cve-2019-5420](https://github.com/cved-sources/cve-2019-5420) :  
![starts](https://img.shields.io/github/stars/cved-sources/cve-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/cved-sources/cve-2019-5420.svg) 
2023-01-19T12:16:29Z

- [https://github.com/trickstersec/CVE-2019-5420](https://github.com/trickstersec/CVE-2019-5420) :  
![starts](https://img.shields.io/github/stars/trickstersec/CVE-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/trickstersec/CVE-2019-5420.svg) 
2022-03-14T17:46:27Z

- [https://github.com/Eremiel/CVE-2019-5420](https://github.com/Eremiel/CVE-2019-5420) :  
![starts](https://img.shields.io/github/stars/Eremiel/CVE-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/Eremiel/CVE-2019-5420.svg) 
2021-01-20T15:14:10Z

- [https://github.com/PenTestical/CVE-2019-5420](https://github.com/PenTestical/CVE-2019-5420) :  
![starts](https://img.shields.io/github/stars/PenTestical/CVE-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/PenTestical/CVE-2019-5420.svg) 
2022-06-06T10:16:34Z

- [https://github.com/AnasTaoutaou/CVE-2019-5420](https://github.com/AnasTaoutaou/CVE-2019-5420) :  
![starts](https://img.shields.io/github/stars/AnasTaoutaou/CVE-2019-5420.svg) 
![forks](https://img.shields.io/github/forks/AnasTaoutaou/CVE-2019-5420.svg) 
2021-01-11T19:24:31Z

- [https://github.com/mmeza-developer/CVE-2019-5420-RCE](https://github.com/mmeza-developer/CVE-2019-5420-RCE) :  
![starts](https://img.shields.io/github/stars/mmeza-developer/CVE-2019-5420-RCE.svg) 
![forks](https://img.shields.io/github/forks/mmeza-developer/CVE-2019-5420-RCE.svg) 
2021-11-06T04:24:58Z

## CVE-2018-17240
 There is a memory dump vulnerability on Netwave IP camera devices at //proc/kcore that allows an unauthenticated attacker to exfiltrate sensitive information from the network configuration (e.g., username and password).

- [https://github.com/Xewdy444/Netgrave](https://github.com/Xewdy444/Netgrave) :  
![starts](https://img.shields.io/github/stars/Xewdy444/Netgrave.svg) 
![forks](https://img.shields.io/github/forks/Xewdy444/Netgrave.svg) 
2025-02-10T16:38:42Z

- [https://github.com/FenrirSec/CVE-2018-17240_exploit](https://github.com/FenrirSec/CVE-2018-17240_exploit) :  
![starts](https://img.shields.io/github/stars/FenrirSec/CVE-2018-17240_exploit.svg) 
![forks](https://img.shields.io/github/forks/FenrirSec/CVE-2018-17240_exploit.svg) 
2025-01-07T15:25:02Z

- [https://github.com/BBge/CVE-2018-17240](https://github.com/BBge/CVE-2018-17240) :  
![starts](https://img.shields.io/github/stars/BBge/CVE-2018-17240.svg) 
![forks](https://img.shields.io/github/forks/BBge/CVE-2018-17240.svg) 
2022-06-10T04:39:45Z

## CVE-2017-5941
 An issue was discovered in the node-serialize package 0.0.4 for Node.js. Untrusted data passed into the unserialize() function can be exploited to achieve arbitrary code execution by passing a JavaScript Object with an Immediately Invoked Function Expression (IIFE).

- [https://github.com/rodolfomarianocy/nodeserial](https://github.com/rodolfomarianocy/nodeserial) :  
![starts](https://img.shields.io/github/stars/rodolfomarianocy/nodeserial.svg) 
![forks](https://img.shields.io/github/forks/rodolfomarianocy/nodeserial.svg) 
2024-06-02T02:41:42Z

- [https://github.com/uartu0/nodejshell](https://github.com/uartu0/nodejshell) :  
![starts](https://img.shields.io/github/stars/uartu0/nodejshell.svg) 
![forks](https://img.shields.io/github/forks/uartu0/nodejshell.svg) 
2023-08-27T23:32:41Z

- [https://github.com/Cr4zyD14m0nd137/Lab-for-cve-2018-15133](https://github.com/Cr4zyD14m0nd137/Lab-for-cve-2018-15133) :  
![starts](https://img.shields.io/github/stars/Cr4zyD14m0nd137/Lab-for-cve-2018-15133.svg) 
![forks](https://img.shields.io/github/forks/Cr4zyD14m0nd137/Lab-for-cve-2018-15133.svg) 
2023-05-13T05:22:48Z

- [https://github.com/turnernator1/Node.js-CVE-2017-5941](https://github.com/turnernator1/Node.js-CVE-2017-5941) :  
![starts](https://img.shields.io/github/stars/turnernator1/Node.js-CVE-2017-5941.svg) 
![forks](https://img.shields.io/github/forks/turnernator1/Node.js-CVE-2017-5941.svg) 
2025-02-10T03:58:57Z

- [https://github.com/Frivolous-scholar/CVE-2017-5941-NodeJS-RCE](https://github.com/Frivolous-scholar/CVE-2017-5941-NodeJS-RCE) :  
![starts](https://img.shields.io/github/stars/Frivolous-scholar/CVE-2017-5941-NodeJS-RCE.svg) 
![forks](https://img.shields.io/github/forks/Frivolous-scholar/CVE-2017-5941-NodeJS-RCE.svg) 
2020-05-12T07:38:12Z

## CVE-2011-2523
 vsftpd 2.3.4 downloaded between 20110630 and 20110703 contains a backdoor which opens a shell on port 6200/tcp.

- [https://github.com/padsalatushal/CVE-2011-2523](https://github.com/padsalatushal/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/padsalatushal/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/padsalatushal/CVE-2011-2523.svg) 
2023-01-08T17:46:12Z

- [https://github.com/4m3rr0r/CVE-2011-2523-poc](https://github.com/4m3rr0r/CVE-2011-2523-poc) :  
![starts](https://img.shields.io/github/stars/4m3rr0r/CVE-2011-2523-poc.svg) 
![forks](https://img.shields.io/github/forks/4m3rr0r/CVE-2011-2523-poc.svg) 
2023-11-28T13:36:42Z

- [https://github.com/Lynk4/CVE-2011-2523](https://github.com/Lynk4/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/Lynk4/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/Lynk4/CVE-2011-2523.svg) 
2023-05-09T19:14:25Z

- [https://github.com/cowsecurity/CVE-2011-2523](https://github.com/cowsecurity/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/cowsecurity/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/cowsecurity/CVE-2011-2523.svg) 
2023-02-05T22:19:06Z

- [https://github.com/nobodyatall648/CVE-2011-2523](https://github.com/nobodyatall648/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/nobodyatall648/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/nobodyatall648/CVE-2011-2523.svg) 
2021-06-25T19:05:49Z

- [https://github.com/NullBrunk/CVE-2011-2523](https://github.com/NullBrunk/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/NullBrunk/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/NullBrunk/CVE-2011-2523.svg) 
2024-12-26T13:05:41Z

- [https://github.com/MFernstrom/OffensivePascal-CVE-2011-2523](https://github.com/MFernstrom/OffensivePascal-CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/MFernstrom/OffensivePascal-CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/MFernstrom/OffensivePascal-CVE-2011-2523.svg) 
2022-05-28T00:24:53Z

- [https://github.com/everythingBlackkk/vsFTPd-Backdoor-Exploit-CVE-2011-2523-](https://github.com/everythingBlackkk/vsFTPd-Backdoor-Exploit-CVE-2011-2523-) :  
![starts](https://img.shields.io/github/stars/everythingBlackkk/vsFTPd-Backdoor-Exploit-CVE-2011-2523-.svg) 
![forks](https://img.shields.io/github/forks/everythingBlackkk/vsFTPd-Backdoor-Exploit-CVE-2011-2523-.svg) 
2025-02-10T10:53:04Z

- [https://github.com/Gill-Singh-A/vsFTP-2.3.4-Remote-Root-Shell-Exploit](https://github.com/Gill-Singh-A/vsFTP-2.3.4-Remote-Root-Shell-Exploit) :  
![starts](https://img.shields.io/github/stars/Gill-Singh-A/vsFTP-2.3.4-Remote-Root-Shell-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Gill-Singh-A/vsFTP-2.3.4-Remote-Root-Shell-Exploit.svg) 
2024-08-03T19:07:19Z

- [https://github.com/0xB0y426/CVE-2011-2523-PoC](https://github.com/0xB0y426/CVE-2011-2523-PoC) :  
![starts](https://img.shields.io/github/stars/0xB0y426/CVE-2011-2523-PoC.svg) 
![forks](https://img.shields.io/github/forks/0xB0y426/CVE-2011-2523-PoC.svg) 
2024-05-27T19:16:03Z

- [https://github.com/0xSojalSec/-CVE-2011-2523](https://github.com/0xSojalSec/-CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/0xSojalSec/-CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/0xSojalSec/-CVE-2011-2523.svg) 
2022-06-09T16:31:05Z

- [https://github.com/Gr4ykt/CVE-2011-2523](https://github.com/Gr4ykt/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/Gr4ykt/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/Gr4ykt/CVE-2011-2523.svg) 
2021-08-31T17:34:38Z

- [https://github.com/0xSojalSec/CVE-2011-2523](https://github.com/0xSojalSec/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/0xSojalSec/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/0xSojalSec/CVE-2011-2523.svg) 
2022-06-04T17:26:15Z

- [https://github.com/sug4r-wr41th/CVE-2011-2523](https://github.com/sug4r-wr41th/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/sug4r-wr41th/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/sug4r-wr41th/CVE-2011-2523.svg) 
2024-06-15T18:03:42Z

- [https://github.com/vaishnavucv/CVE-2011-2523](https://github.com/vaishnavucv/CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/vaishnavucv/CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/vaishnavucv/CVE-2011-2523.svg) 
2024-10-22T16:11:15Z

- [https://github.com/XiangSi-Howard/CTF---CVE-2011-2523](https://github.com/XiangSi-Howard/CTF---CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/XiangSi-Howard/CTF---CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/XiangSi-Howard/CTF---CVE-2011-2523.svg) 
2022-12-04T15:22:57Z

- [https://github.com/Shubham-2k1/Exploit-CVE-2011-2523](https://github.com/Shubham-2k1/Exploit-CVE-2011-2523) :  
![starts](https://img.shields.io/github/stars/Shubham-2k1/Exploit-CVE-2011-2523.svg) 
![forks](https://img.shields.io/github/forks/Shubham-2k1/Exploit-CVE-2011-2523.svg) 
2024-03-05T10:35:09Z

- [https://github.com/Tenor-Z/SmileySploit](https://github.com/Tenor-Z/SmileySploit) :  
![starts](https://img.shields.io/github/stars/Tenor-Z/SmileySploit.svg) 
![forks](https://img.shields.io/github/forks/Tenor-Z/SmileySploit.svg) 
2024-04-23T05:36:54Z

- [https://github.com/chleba124/vsftpd-exploit](https://github.com/chleba124/vsftpd-exploit) :  
![starts](https://img.shields.io/github/stars/chleba124/vsftpd-exploit.svg) 
![forks](https://img.shields.io/github/forks/chleba124/vsftpd-exploit.svg) 
2024-03-02T07:04:25Z

- [https://github.com/AnugiArrawwala/CVE-Research](https://github.com/AnugiArrawwala/CVE-Research) :  
![starts](https://img.shields.io/github/stars/AnugiArrawwala/CVE-Research.svg) 
![forks](https://img.shields.io/github/forks/AnugiArrawwala/CVE-Research.svg) 
2024-07-03T06:52:37Z

- [https://github.com/davidlares/vsftpd-exploitation](https://github.com/davidlares/vsftpd-exploitation) :  
![starts](https://img.shields.io/github/stars/davidlares/vsftpd-exploitation.svg) 
![forks](https://img.shields.io/github/forks/davidlares/vsftpd-exploitation.svg) 
2021-05-07T16:59:05Z

- [https://github.com/HerculesRD/vsftpd2.3.4PyExploit](https://github.com/HerculesRD/vsftpd2.3.4PyExploit) :  
![starts](https://img.shields.io/github/stars/HerculesRD/vsftpd2.3.4PyExploit.svg) 
![forks](https://img.shields.io/github/forks/HerculesRD/vsftpd2.3.4PyExploit.svg) 
2021-04-12T17:16:06Z

# 2025-02-09
## CVE-2025-23369
 An improper verification of cryptographic signature vulnerability was identified in GitHub Enterprise Server that allowed signature spoofing for unauthorized internal users.  Instances not utilizing SAML single sign-on or where the attacker is not already an existing user were not impacted. This vulnerability affected all versions of GitHub Enterprise Server prior to 3.12.14, 3.13.10, 3.14.7, 3.15.2, and 3.16.0. This vulnerability was reported via the GitHub Bug Bounty program.

- [https://github.com/hakivvi/CVE-2025-23369](https://github.com/hakivvi/CVE-2025-23369) :  
![starts](https://img.shields.io/github/stars/hakivvi/CVE-2025-23369.svg) 
![forks](https://img.shields.io/github/forks/hakivvi/CVE-2025-23369.svg) 
2025-02-08T18:15:12Z

- [https://github.com/Arian91/CVE-2025-23369_SAML_bypass](https://github.com/Arian91/CVE-2025-23369_SAML_bypass) :  
![starts](https://img.shields.io/github/stars/Arian91/CVE-2025-23369_SAML_bypass.svg) 
![forks](https://img.shields.io/github/forks/Arian91/CVE-2025-23369_SAML_bypass.svg) 
2025-02-09T07:21:38Z

## CVE-2024-52033
 Exposure of sensitive system information to an unauthorized control sphere issue exists in Rakuten Turbo 5G firmware version V1.3.18 and earlier. If this vulnerability is exploited, a remote unauthenticated attacker may obtain information of the other devices connected through the Wi-Fi.

- [https://github.com/0xNslabs/Rakuten5GTurboAPI](https://github.com/0xNslabs/Rakuten5GTurboAPI) :  
![starts](https://img.shields.io/github/stars/0xNslabs/Rakuten5GTurboAPI.svg) 
![forks](https://img.shields.io/github/forks/0xNslabs/Rakuten5GTurboAPI.svg) 
2025-02-09T23:24:43Z

## CVE-2024-48895
 Improper neutralization of special elements used in an OS command ('OS Command Injection') issue exists in Rakuten Turbo 5G firmware version V1.3.18 and earlier. If this vulnerability is exploited, a remote authenticated attacker may execute an arbitrary OS command.

- [https://github.com/0xNslabs/Rakuten5GTurboAPI](https://github.com/0xNslabs/Rakuten5GTurboAPI) :  
![starts](https://img.shields.io/github/stars/0xNslabs/Rakuten5GTurboAPI.svg) 
![forks](https://img.shields.io/github/forks/0xNslabs/Rakuten5GTurboAPI.svg) 
2025-02-09T23:24:43Z

## CVE-2024-47865
 Missing authentication for critical function vulnerability exists in Rakuten Turbo 5G firmware version V1.3.18 and earlier. If this vulnerability is exploited, a remote unauthenticated attacker may update or downgrade the firmware on the device.

- [https://github.com/0xNslabs/Rakuten5GTurboAPI](https://github.com/0xNslabs/Rakuten5GTurboAPI) :  
![starts](https://img.shields.io/github/stars/0xNslabs/Rakuten5GTurboAPI.svg) 
![forks](https://img.shields.io/github/forks/0xNslabs/Rakuten5GTurboAPI.svg) 
2025-02-09T23:24:43Z

## CVE-2024-39119
 idccms v1.35 was discovered to contain a Cross-Site Request Forgery (CSRF) via admin/info_deal.php?mudi=rev&nohrefStr=close.

- [https://github.com/phtcloud-dev/CVE-2024-39199](https://github.com/phtcloud-dev/CVE-2024-39199) :  
![starts](https://img.shields.io/github/stars/phtcloud-dev/CVE-2024-39199.svg) 
![forks](https://img.shields.io/github/forks/phtcloud-dev/CVE-2024-39199.svg) 
2025-02-09T19:13:20Z

## CVE-2024-36837
 SQL Injection vulnerability in CRMEB v.5.2.2 allows a remote attacker to obtain sensitive information via the getProductList function in the ProductController.php file.

- [https://github.com/phtcloud-dev/CVE-2024-36837](https://github.com/phtcloud-dev/CVE-2024-36837) :  
![starts](https://img.shields.io/github/stars/phtcloud-dev/CVE-2024-36837.svg) 
![forks](https://img.shields.io/github/forks/phtcloud-dev/CVE-2024-36837.svg) 
2025-02-09T19:14:02Z

- [https://github.com/lhc321-source/CVE-2024-36837](https://github.com/lhc321-source/CVE-2024-36837) :  
![starts](https://img.shields.io/github/stars/lhc321-source/CVE-2024-36837.svg) 
![forks](https://img.shields.io/github/forks/lhc321-source/CVE-2024-36837.svg) 
2024-09-28T10:48:05Z

## CVE-2024-23443
 A high-privileged user, allowed to create custom osquery packs 17 could affect the availability of Kibana by uploading a maliciously crafted osquery pack.

- [https://github.com/zhazhalove/osquery_cve-2024-23443](https://github.com/zhazhalove/osquery_cve-2024-23443) :  
![starts](https://img.shields.io/github/stars/zhazhalove/osquery_cve-2024-23443.svg) 
![forks](https://img.shields.io/github/forks/zhazhalove/osquery_cve-2024-23443.svg) 
2025-02-09T13:54:58Z

## CVE-2024-3919
 The OpenPGP Form Encryption for WordPress plugin before 1.5.1 does not validate and escape some of its shortcode attributes before outputting them back in a page/post where the shortcode is embed, which could allow users with the contributor role and above to perform Stored Cross-Site Scripting attacks.

- [https://github.com/phtcloud-dev/CVE-2024-39199](https://github.com/phtcloud-dev/CVE-2024-39199) :  
![starts](https://img.shields.io/github/stars/phtcloud-dev/CVE-2024-39199.svg) 
![forks](https://img.shields.io/github/forks/phtcloud-dev/CVE-2024-39199.svg) 
2025-02-09T19:13:20Z

## CVE-2022-0847
 A flaw was found in the way the "flags" member of the new pipe buffer structure was lacking proper initialization in copy_page_to_iter_pipe and push_pipe functions in the Linux kernel and could thus contain stale values. An unprivileged local user could use this flaw to write to pages in the page cache backed by read only files and as such escalate their privileges on the system.

- [https://github.com/liamg/traitor](https://github.com/liamg/traitor) :  
![starts](https://img.shields.io/github/stars/liamg/traitor.svg) 
![forks](https://img.shields.io/github/forks/liamg/traitor.svg) 
2024-03-12T21:01:14Z

- [https://github.com/Arinerron/CVE-2022-0847-DirtyPipe-Exploit](https://github.com/Arinerron/CVE-2022-0847-DirtyPipe-Exploit) :  
![starts](https://img.shields.io/github/stars/Arinerron/CVE-2022-0847-DirtyPipe-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Arinerron/CVE-2022-0847-DirtyPipe-Exploit.svg) 
2022-03-08T06:20:05Z

- [https://github.com/AlexisAhmed/CVE-2022-0847-DirtyPipe-Exploits](https://github.com/AlexisAhmed/CVE-2022-0847-DirtyPipe-Exploits) :  
![starts](https://img.shields.io/github/stars/AlexisAhmed/CVE-2022-0847-DirtyPipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/AlexisAhmed/CVE-2022-0847-DirtyPipe-Exploits.svg) 
2023-05-20T05:55:45Z

- [https://github.com/Al1ex/LinuxEelvation](https://github.com/Al1ex/LinuxEelvation) :  
![starts](https://img.shields.io/github/stars/Al1ex/LinuxEelvation.svg) 
![forks](https://img.shields.io/github/forks/Al1ex/LinuxEelvation.svg) 
2022-07-29T09:34:03Z

- [https://github.com/r1is/CVE-2022-0847](https://github.com/r1is/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/r1is/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/r1is/CVE-2022-0847.svg) 
2023-02-02T02:17:30Z

- [https://github.com/Al1ex/CVE-2022-0847](https://github.com/Al1ex/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/Al1ex/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/Al1ex/CVE-2022-0847.svg) 
2022-03-09T02:47:32Z

- [https://github.com/DataDog/dirtypipe-container-breakout-poc](https://github.com/DataDog/dirtypipe-container-breakout-poc) :  
![starts](https://img.shields.io/github/stars/DataDog/dirtypipe-container-breakout-poc.svg) 
![forks](https://img.shields.io/github/forks/DataDog/dirtypipe-container-breakout-poc.svg) 
2022-04-20T20:23:36Z

- [https://github.com/basharkey/CVE-2022-0847-dirty-pipe-checker](https://github.com/basharkey/CVE-2022-0847-dirty-pipe-checker) :  
![starts](https://img.shields.io/github/stars/basharkey/CVE-2022-0847-dirty-pipe-checker.svg) 
![forks](https://img.shields.io/github/forks/basharkey/CVE-2022-0847-dirty-pipe-checker.svg) 
2023-06-14T23:25:46Z

- [https://github.com/ZZ-SOCMAP/CVE-2022-0847](https://github.com/ZZ-SOCMAP/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/ZZ-SOCMAP/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/ZZ-SOCMAP/CVE-2022-0847.svg) 
2022-03-08T09:14:25Z

- [https://github.com/febinrev/dirtypipez-exploit](https://github.com/febinrev/dirtypipez-exploit) :  
![starts](https://img.shields.io/github/stars/febinrev/dirtypipez-exploit.svg) 
![forks](https://img.shields.io/github/forks/febinrev/dirtypipez-exploit.svg) 
2022-03-08T11:52:22Z

- [https://github.com/bbaranoff/CVE-2022-0847](https://github.com/bbaranoff/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/bbaranoff/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/bbaranoff/CVE-2022-0847.svg) 
2022-03-07T15:52:23Z

- [https://github.com/knqyf263/CVE-2022-0847](https://github.com/knqyf263/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/knqyf263/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/knqyf263/CVE-2022-0847.svg) 
2022-03-08T13:54:08Z

- [https://github.com/greenhandatsjtu/CVE-2022-0847-Container-Escape](https://github.com/greenhandatsjtu/CVE-2022-0847-Container-Escape) :  
![starts](https://img.shields.io/github/stars/greenhandatsjtu/CVE-2022-0847-Container-Escape.svg) 
![forks](https://img.shields.io/github/forks/greenhandatsjtu/CVE-2022-0847-Container-Escape.svg) 
2022-06-16T17:14:10Z

- [https://github.com/airbus-cert/dirtypipe-ebpf_detection](https://github.com/airbus-cert/dirtypipe-ebpf_detection) :  
![starts](https://img.shields.io/github/stars/airbus-cert/dirtypipe-ebpf_detection.svg) 
![forks](https://img.shields.io/github/forks/airbus-cert/dirtypipe-ebpf_detection.svg) 
2022-07-05T14:25:46Z

- [https://github.com/chenaotian/CVE-2022-0847](https://github.com/chenaotian/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/chenaotian/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/chenaotian/CVE-2022-0847.svg) 
2022-03-10T01:31:57Z

- [https://github.com/ahrixia/CVE_2022_0847](https://github.com/ahrixia/CVE_2022_0847) :  
![starts](https://img.shields.io/github/stars/ahrixia/CVE_2022_0847.svg) 
![forks](https://img.shields.io/github/forks/ahrixia/CVE_2022_0847.svg) 
2022-03-08T13:15:35Z

- [https://github.com/breachnix/dirty-pipe-poc](https://github.com/breachnix/dirty-pipe-poc) :  
![starts](https://img.shields.io/github/stars/breachnix/dirty-pipe-poc.svg) 
![forks](https://img.shields.io/github/forks/breachnix/dirty-pipe-poc.svg) 
2022-03-14T20:34:57Z

- [https://github.com/xndpxs/CVE-2022-0847](https://github.com/xndpxs/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/xndpxs/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/xndpxs/CVE-2022-0847.svg) 
2022-03-07T17:59:12Z

- [https://github.com/0xIronGoat/dirty-pipe](https://github.com/0xIronGoat/dirty-pipe) :  
![starts](https://img.shields.io/github/stars/0xIronGoat/dirty-pipe.svg) 
![forks](https://img.shields.io/github/forks/0xIronGoat/dirty-pipe.svg) 
2022-03-08T15:47:53Z

- [https://github.com/crusoe112/DirtyPipePython](https://github.com/crusoe112/DirtyPipePython) :  
![starts](https://img.shields.io/github/stars/crusoe112/DirtyPipePython.svg) 
![forks](https://img.shields.io/github/forks/crusoe112/DirtyPipePython.svg) 
2022-03-23T22:46:58Z

- [https://github.com/n3rada/DirtyPipe](https://github.com/n3rada/DirtyPipe) :  
![starts](https://img.shields.io/github/stars/n3rada/DirtyPipe.svg) 
![forks](https://img.shields.io/github/forks/n3rada/DirtyPipe.svg) 
2023-10-15T22:23:44Z

- [https://github.com/crowsec-edtech/Dirty-Pipe](https://github.com/crowsec-edtech/Dirty-Pipe) :  
![starts](https://img.shields.io/github/stars/crowsec-edtech/Dirty-Pipe.svg) 
![forks](https://img.shields.io/github/forks/crowsec-edtech/Dirty-Pipe.svg) 
2022-03-07T21:01:15Z

- [https://github.com/rexpository/linux-privilege-escalation](https://github.com/rexpository/linux-privilege-escalation) :  
![starts](https://img.shields.io/github/stars/rexpository/linux-privilege-escalation.svg) 
![forks](https://img.shields.io/github/forks/rexpository/linux-privilege-escalation.svg) 
2022-04-18T10:20:32Z

- [https://github.com/h4ckm310n/CVE-2022-0847-eBPF](https://github.com/h4ckm310n/CVE-2022-0847-eBPF) :  
![starts](https://img.shields.io/github/stars/h4ckm310n/CVE-2022-0847-eBPF.svg) 
![forks](https://img.shields.io/github/forks/h4ckm310n/CVE-2022-0847-eBPF.svg) 
2023-11-04T15:49:51Z

- [https://github.com/Mustafa1986/CVE-2022-0847-DirtyPipe-Exploit](https://github.com/Mustafa1986/CVE-2022-0847-DirtyPipe-Exploit) :  
![starts](https://img.shields.io/github/stars/Mustafa1986/CVE-2022-0847-DirtyPipe-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Mustafa1986/CVE-2022-0847-DirtyPipe-Exploit.svg) 
2022-03-09T06:16:23Z

- [https://github.com/drapl0n/dirtypipe](https://github.com/drapl0n/dirtypipe) :  
![starts](https://img.shields.io/github/stars/drapl0n/dirtypipe.svg) 
![forks](https://img.shields.io/github/forks/drapl0n/dirtypipe.svg) 
2022-04-02T13:50:21Z

- [https://github.com/arttnba3/CVE-2022-0847](https://github.com/arttnba3/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/arttnba3/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/arttnba3/CVE-2022-0847.svg) 
2024-06-17T00:32:05Z

- [https://github.com/qwert419/linux-](https://github.com/qwert419/linux-) :  
![starts](https://img.shields.io/github/stars/qwert419/linux-.svg) 
![forks](https://img.shields.io/github/forks/qwert419/linux-.svg) 
2022-11-21T01:24:59Z

- [https://github.com/LudovicPatho/CVE-2022-0847_dirty-pipe](https://github.com/LudovicPatho/CVE-2022-0847_dirty-pipe) :  
![starts](https://img.shields.io/github/stars/LudovicPatho/CVE-2022-0847_dirty-pipe.svg) 
![forks](https://img.shields.io/github/forks/LudovicPatho/CVE-2022-0847_dirty-pipe.svg) 
2022-04-05T20:33:28Z

- [https://github.com/yoeelingBin/CVE-2022-0847-Container-Escape](https://github.com/yoeelingBin/CVE-2022-0847-Container-Escape) :  
![starts](https://img.shields.io/github/stars/yoeelingBin/CVE-2022-0847-Container-Escape.svg) 
![forks](https://img.shields.io/github/forks/yoeelingBin/CVE-2022-0847-Container-Escape.svg) 
2022-08-22T03:37:04Z

- [https://github.com/4luc4rdr5290/CVE-2022-0847](https://github.com/4luc4rdr5290/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/4luc4rdr5290/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/4luc4rdr5290/CVE-2022-0847.svg) 
2022-03-08T20:41:15Z

- [https://github.com/MrP1xel/CVE-2022-0847-dirty-pipe-kernel-checker](https://github.com/MrP1xel/CVE-2022-0847-dirty-pipe-kernel-checker) :  
![starts](https://img.shields.io/github/stars/MrP1xel/CVE-2022-0847-dirty-pipe-kernel-checker.svg) 
![forks](https://img.shields.io/github/forks/MrP1xel/CVE-2022-0847-dirty-pipe-kernel-checker.svg) 
2022-03-15T11:30:58Z

- [https://github.com/DanaEpp/pwncat_dirtypipe](https://github.com/DanaEpp/pwncat_dirtypipe) :  
![starts](https://img.shields.io/github/stars/DanaEpp/pwncat_dirtypipe.svg) 
![forks](https://img.shields.io/github/forks/DanaEpp/pwncat_dirtypipe.svg) 
2022-03-21T19:28:18Z

- [https://github.com/Shotokhan/cve_2022_0847_shellcode](https://github.com/Shotokhan/cve_2022_0847_shellcode) :  
![starts](https://img.shields.io/github/stars/Shotokhan/cve_2022_0847_shellcode.svg) 
![forks](https://img.shields.io/github/forks/Shotokhan/cve_2022_0847_shellcode.svg) 
2022-03-14T23:05:15Z

- [https://github.com/sa-infinity8888/Dirty-Pipe-CVE-2022-0847](https://github.com/sa-infinity8888/Dirty-Pipe-CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/sa-infinity8888/Dirty-Pipe-CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/sa-infinity8888/Dirty-Pipe-CVE-2022-0847.svg) 
2022-03-13T06:02:30Z

- [https://github.com/dadhee/CVE-2022-0847_DirtyPipeExploit](https://github.com/dadhee/CVE-2022-0847_DirtyPipeExploit) :  
![starts](https://img.shields.io/github/stars/dadhee/CVE-2022-0847_DirtyPipeExploit.svg) 
![forks](https://img.shields.io/github/forks/dadhee/CVE-2022-0847_DirtyPipeExploit.svg) 
2022-03-09T02:01:28Z

- [https://github.com/edr1412/Dirty-Pipe](https://github.com/edr1412/Dirty-Pipe) :  
![starts](https://img.shields.io/github/stars/edr1412/Dirty-Pipe.svg) 
![forks](https://img.shields.io/github/forks/edr1412/Dirty-Pipe.svg) 
2022-07-05T19:23:27Z

- [https://github.com/gyaansastra/CVE-2022-0847](https://github.com/gyaansastra/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/gyaansastra/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/gyaansastra/CVE-2022-0847.svg) 
2022-03-20T15:46:04Z

- [https://github.com/VinuKalana/DirtyPipe-CVE-2022-0847](https://github.com/VinuKalana/DirtyPipe-CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/VinuKalana/DirtyPipe-CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/VinuKalana/DirtyPipe-CVE-2022-0847.svg) 
2022-06-02T11:04:25Z

- [https://github.com/nanaao/dirtyPipe-automaticRoot](https://github.com/nanaao/dirtyPipe-automaticRoot) :  
![starts](https://img.shields.io/github/stars/nanaao/dirtyPipe-automaticRoot.svg) 
![forks](https://img.shields.io/github/forks/nanaao/dirtyPipe-automaticRoot.svg) 
2022-03-11T22:27:18Z

- [https://github.com/tmoneypenny/CVE-2022-0847](https://github.com/tmoneypenny/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/tmoneypenny/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/tmoneypenny/CVE-2022-0847.svg) 
2022-12-19T06:10:52Z

- [https://github.com/mhanief/dirtypipe](https://github.com/mhanief/dirtypipe) :  
![starts](https://img.shields.io/github/stars/mhanief/dirtypipe.svg) 
![forks](https://img.shields.io/github/forks/mhanief/dirtypipe.svg) 
2022-04-06T03:32:39Z

- [https://github.com/mutur4/CVE-2022-0847](https://github.com/mutur4/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/mutur4/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/mutur4/CVE-2022-0847.svg) 
2023-09-06T12:28:47Z

- [https://github.com/EagleTube/CVE-2022-0847](https://github.com/EagleTube/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/EagleTube/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/EagleTube/CVE-2022-0847.svg) 
2022-08-14T07:48:51Z

- [https://github.com/puckiestyle/CVE-2022-0847](https://github.com/puckiestyle/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/puckiestyle/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/puckiestyle/CVE-2022-0847.svg) 
2022-03-10T08:10:40Z

- [https://github.com/CYB3RK1D/CVE-2022-0847-POC](https://github.com/CYB3RK1D/CVE-2022-0847-POC) :  
![starts](https://img.shields.io/github/stars/CYB3RK1D/CVE-2022-0847-POC.svg) 
![forks](https://img.shields.io/github/forks/CYB3RK1D/CVE-2022-0847-POC.svg) 
2022-03-15T17:41:13Z

- [https://github.com/Gustavo-Nogueira/Dirty-Pipe-Exploits](https://github.com/Gustavo-Nogueira/Dirty-Pipe-Exploits) :  
![starts](https://img.shields.io/github/stars/Gustavo-Nogueira/Dirty-Pipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/Gustavo-Nogueira/Dirty-Pipe-Exploits.svg) 
2022-09-26T14:06:13Z

- [https://github.com/JlSakuya/CVE-2022-0847-container-escape](https://github.com/JlSakuya/CVE-2022-0847-container-escape) :  
![starts](https://img.shields.io/github/stars/JlSakuya/CVE-2022-0847-container-escape.svg) 
![forks](https://img.shields.io/github/forks/JlSakuya/CVE-2022-0847-container-escape.svg) 
2023-04-26T13:38:38Z

- [https://github.com/eduquintanilha/CVE-2022-0847-DirtyPipe-Exploits](https://github.com/eduquintanilha/CVE-2022-0847-DirtyPipe-Exploits) :  
![starts](https://img.shields.io/github/stars/eduquintanilha/CVE-2022-0847-DirtyPipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/eduquintanilha/CVE-2022-0847-DirtyPipe-Exploits.svg) 
2022-08-02T15:11:57Z

- [https://github.com/ih3na/debian11-dirty_pipe-patcher](https://github.com/ih3na/debian11-dirty_pipe-patcher) :  
![starts](https://img.shields.io/github/stars/ih3na/debian11-dirty_pipe-patcher.svg) 
![forks](https://img.shields.io/github/forks/ih3na/debian11-dirty_pipe-patcher.svg) 
2023-06-21T15:24:03Z

- [https://github.com/mutur4/Hacking-Scripts](https://github.com/mutur4/Hacking-Scripts) :  
![starts](https://img.shields.io/github/stars/mutur4/Hacking-Scripts.svg) 
![forks](https://img.shields.io/github/forks/mutur4/Hacking-Scripts.svg) 
2023-01-29T19:39:29Z

- [https://github.com/lucksec/CVE-2022-0847](https://github.com/lucksec/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/lucksec/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/lucksec/CVE-2022-0847.svg) 
2022-03-08T01:50:39Z

- [https://github.com/scopion/dirty-pipe](https://github.com/scopion/dirty-pipe) :  
![starts](https://img.shields.io/github/stars/scopion/dirty-pipe.svg) 
![forks](https://img.shields.io/github/forks/scopion/dirty-pipe.svg) 
2022-03-31T11:48:45Z

- [https://github.com/cspshivam/CVE-2022-0847-dirty-pipe-exploit](https://github.com/cspshivam/CVE-2022-0847-dirty-pipe-exploit) :  
![starts](https://img.shields.io/github/stars/cspshivam/CVE-2022-0847-dirty-pipe-exploit.svg) 
![forks](https://img.shields.io/github/forks/cspshivam/CVE-2022-0847-dirty-pipe-exploit.svg) 
2022-03-08T11:15:00Z

- [https://github.com/pashayogi/DirtyPipe](https://github.com/pashayogi/DirtyPipe) :  
![starts](https://img.shields.io/github/stars/pashayogi/DirtyPipe.svg) 
![forks](https://img.shields.io/github/forks/pashayogi/DirtyPipe.svg) 
2023-09-17T12:44:59Z

- [https://github.com/Mephierr/DirtyPipe_exploit](https://github.com/Mephierr/DirtyPipe_exploit) :  
![starts](https://img.shields.io/github/stars/Mephierr/DirtyPipe_exploit.svg) 
![forks](https://img.shields.io/github/forks/Mephierr/DirtyPipe_exploit.svg) 
2025-01-21T11:26:36Z

- [https://github.com/Turzum/ps-lab-cve-2022-0847](https://github.com/Turzum/ps-lab-cve-2022-0847) :  
![starts](https://img.shields.io/github/stars/Turzum/ps-lab-cve-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/Turzum/ps-lab-cve-2022-0847.svg) 
2023-01-19T21:27:20Z

- [https://github.com/realbatuhan/dirtypipetester](https://github.com/realbatuhan/dirtypipetester) :  
![starts](https://img.shields.io/github/stars/realbatuhan/dirtypipetester.svg) 
![forks](https://img.shields.io/github/forks/realbatuhan/dirtypipetester.svg) 
2022-03-13T19:49:29Z

- [https://github.com/joeymeech/CVE-2022-0847-Exploit-Implementation](https://github.com/joeymeech/CVE-2022-0847-Exploit-Implementation) :  
![starts](https://img.shields.io/github/stars/joeymeech/CVE-2022-0847-Exploit-Implementation.svg) 
![forks](https://img.shields.io/github/forks/joeymeech/CVE-2022-0847-Exploit-Implementation.svg) 
2023-07-11T02:02:36Z

- [https://github.com/muhammad1596/CVE-2022-0847-dirty-pipe-checker](https://github.com/muhammad1596/CVE-2022-0847-dirty-pipe-checker) :  
![starts](https://img.shields.io/github/stars/muhammad1596/CVE-2022-0847-dirty-pipe-checker.svg) 
![forks](https://img.shields.io/github/forks/muhammad1596/CVE-2022-0847-dirty-pipe-checker.svg) 
2024-06-04T16:07:47Z

- [https://github.com/ITMarcin2211/CVE-2022-0847-DirtyPipe-Exploit](https://github.com/ITMarcin2211/CVE-2022-0847-DirtyPipe-Exploit) :  
![starts](https://img.shields.io/github/stars/ITMarcin2211/CVE-2022-0847-DirtyPipe-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ITMarcin2211/CVE-2022-0847-DirtyPipe-Exploit.svg) 
2022-03-08T15:36:53Z

- [https://github.com/jpts/CVE-2022-0847-DirtyPipe-Container-Breakout](https://github.com/jpts/CVE-2022-0847-DirtyPipe-Container-Breakout) :  
![starts](https://img.shields.io/github/stars/jpts/CVE-2022-0847-DirtyPipe-Container-Breakout.svg) 
![forks](https://img.shields.io/github/forks/jpts/CVE-2022-0847-DirtyPipe-Container-Breakout.svg) 
2022-04-20T22:07:12Z

- [https://github.com/0xeremus/dirty-pipe-poc](https://github.com/0xeremus/dirty-pipe-poc) :  
![starts](https://img.shields.io/github/stars/0xeremus/dirty-pipe-poc.svg) 
![forks](https://img.shields.io/github/forks/0xeremus/dirty-pipe-poc.svg) 
2023-06-20T23:48:52Z

- [https://github.com/b4dboy17/Dirty-Pipe-Oneshot](https://github.com/b4dboy17/Dirty-Pipe-Oneshot) :  
![starts](https://img.shields.io/github/stars/b4dboy17/Dirty-Pipe-Oneshot.svg) 
![forks](https://img.shields.io/github/forks/b4dboy17/Dirty-Pipe-Oneshot.svg) 
2022-10-11T17:42:10Z

- [https://github.com/bohr777/cve-2022-0847dirtypipe-exploit](https://github.com/bohr777/cve-2022-0847dirtypipe-exploit) :  
![starts](https://img.shields.io/github/stars/bohr777/cve-2022-0847dirtypipe-exploit.svg) 
![forks](https://img.shields.io/github/forks/bohr777/cve-2022-0847dirtypipe-exploit.svg) 
2022-03-08T05:18:30Z

- [https://github.com/si1ent-le/CVE-2022-0847](https://github.com/si1ent-le/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/si1ent-le/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/si1ent-le/CVE-2022-0847.svg) 
2022-03-08T05:18:15Z

- [https://github.com/ajith737/Dirty-Pipe-CVE-2022-0847-POCs](https://github.com/ajith737/Dirty-Pipe-CVE-2022-0847-POCs) :  
![starts](https://img.shields.io/github/stars/ajith737/Dirty-Pipe-CVE-2022-0847-POCs.svg) 
![forks](https://img.shields.io/github/forks/ajith737/Dirty-Pipe-CVE-2022-0847-POCs.svg) 
2023-01-04T12:51:32Z

- [https://github.com/DataFox/CVE-2022-0847](https://github.com/DataFox/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/DataFox/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/DataFox/CVE-2022-0847.svg) 
2022-12-21T16:56:34Z

- [https://github.com/Patocoh/Research-Dirty-Pipe](https://github.com/Patocoh/Research-Dirty-Pipe) :  
![starts](https://img.shields.io/github/stars/Patocoh/Research-Dirty-Pipe.svg) 
![forks](https://img.shields.io/github/forks/Patocoh/Research-Dirty-Pipe.svg) 
2022-03-25T16:27:56Z

- [https://github.com/ShaharyarJalaluddin/cve20220847](https://github.com/ShaharyarJalaluddin/cve20220847) :  
![starts](https://img.shields.io/github/stars/ShaharyarJalaluddin/cve20220847.svg) 
![forks](https://img.shields.io/github/forks/ShaharyarJalaluddin/cve20220847.svg) 
2024-10-29T02:18:12Z

- [https://github.com/jonathanbest7/cve-2022-0847](https://github.com/jonathanbest7/cve-2022-0847) :  
![starts](https://img.shields.io/github/stars/jonathanbest7/cve-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/jonathanbest7/cve-2022-0847.svg) 
2023-04-30T23:52:15Z

- [https://github.com/V0WKeep3r/CVE-2022-0847-DirtyPipe-Exploit](https://github.com/V0WKeep3r/CVE-2022-0847-DirtyPipe-Exploit) :  
![starts](https://img.shields.io/github/stars/V0WKeep3r/CVE-2022-0847-DirtyPipe-Exploit.svg) 
![forks](https://img.shields.io/github/forks/V0WKeep3r/CVE-2022-0847-DirtyPipe-Exploit.svg) 
2022-03-10T13:41:19Z

- [https://github.com/RogelioPumajulca/CVE-2022-0847](https://github.com/RogelioPumajulca/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/RogelioPumajulca/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/RogelioPumajulca/CVE-2022-0847.svg) 
2025-02-09T21:52:58Z

- [https://github.com/letsr00t/CVE-2022-0847](https://github.com/letsr00t/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/letsr00t/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/letsr00t/CVE-2022-0847.svg) 
2024-02-15T02:28:33Z

- [https://github.com/babyshen/CVE-2022-0847](https://github.com/babyshen/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/babyshen/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/babyshen/CVE-2022-0847.svg) 
2022-03-10T01:02:13Z

- [https://github.com/CPT-Jack-A-Castle/CVE-2022-0847](https://github.com/CPT-Jack-A-Castle/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/CPT-Jack-A-Castle/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/CPT-Jack-A-Castle/CVE-2022-0847.svg) 
2022-04-25T03:27:10Z

- [https://github.com/xsxtw/CVE-2022-0847](https://github.com/xsxtw/CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/xsxtw/CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/xsxtw/CVE-2022-0847.svg) 
2024-05-01T05:18:07Z

- [https://github.com/s3mPr1linux/CVE_2022_0847](https://github.com/s3mPr1linux/CVE_2022_0847) :  
![starts](https://img.shields.io/github/stars/s3mPr1linux/CVE_2022_0847.svg) 
![forks](https://img.shields.io/github/forks/s3mPr1linux/CVE_2022_0847.svg) 
2023-03-25T03:56:07Z

- [https://github.com/qdagustian/CVE_2022_0847](https://github.com/qdagustian/CVE_2022_0847) :  
![starts](https://img.shields.io/github/stars/qdagustian/CVE_2022_0847.svg) 
![forks](https://img.shields.io/github/forks/qdagustian/CVE_2022_0847.svg) 
2022-03-14T05:08:28Z

- [https://github.com/pentestblogin/pentestblog-CVE-2022-0847](https://github.com/pentestblogin/pentestblog-CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/pentestblogin/pentestblog-CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/pentestblogin/pentestblog-CVE-2022-0847.svg) 
2022-03-09T10:26:07Z

- [https://github.com/mrchucu1/CVE-2022-0847-Docker](https://github.com/mrchucu1/CVE-2022-0847-Docker) :  
![starts](https://img.shields.io/github/stars/mrchucu1/CVE-2022-0847-Docker.svg) 
![forks](https://img.shields.io/github/forks/mrchucu1/CVE-2022-0847-Docker.svg) 
2022-03-08T17:05:01Z

- [https://github.com/edsonjt81/CVE-2022-0847-Linux](https://github.com/edsonjt81/CVE-2022-0847-Linux) :  
![starts](https://img.shields.io/github/stars/edsonjt81/CVE-2022-0847-Linux.svg) 
![forks](https://img.shields.io/github/forks/edsonjt81/CVE-2022-0847-Linux.svg) 
2022-03-10T01:18:33Z

- [https://github.com/JustinYe377/CTF-CVE-2022-0847](https://github.com/JustinYe377/CTF-CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/JustinYe377/CTF-CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/JustinYe377/CTF-CVE-2022-0847.svg) 
2025-01-07T04:02:44Z

- [https://github.com/githublihaha/DirtyPIPE-CVE-2022-0847](https://github.com/githublihaha/DirtyPIPE-CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/githublihaha/DirtyPIPE-CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/githublihaha/DirtyPIPE-CVE-2022-0847.svg) 
2022-03-15T08:55:41Z

- [https://github.com/Asbatel/CBDS_CVE-2022-0847_POC](https://github.com/Asbatel/CBDS_CVE-2022-0847_POC) :  
![starts](https://img.shields.io/github/stars/Asbatel/CBDS_CVE-2022-0847_POC.svg) 
![forks](https://img.shields.io/github/forks/Asbatel/CBDS_CVE-2022-0847_POC.svg) 
2025-01-12T11:29:27Z

- [https://github.com/Greetdawn/CVE-2022-0847-DirtyPipe-](https://github.com/Greetdawn/CVE-2022-0847-DirtyPipe-) :  
![starts](https://img.shields.io/github/stars/Greetdawn/CVE-2022-0847-DirtyPipe-.svg) 
![forks](https://img.shields.io/github/forks/Greetdawn/CVE-2022-0847-DirtyPipe-.svg) 
2022-03-11T02:51:55Z

- [https://github.com/pmihsan/Dirty-Pipe-CVE-2022-0847](https://github.com/pmihsan/Dirty-Pipe-CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/pmihsan/Dirty-Pipe-CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/pmihsan/Dirty-Pipe-CVE-2022-0847.svg) 
2022-12-30T17:33:04Z

- [https://github.com/edsonjt81/CVE-2022-0847-DirtyPipe-](https://github.com/edsonjt81/CVE-2022-0847-DirtyPipe-) :  
![starts](https://img.shields.io/github/stars/edsonjt81/CVE-2022-0847-DirtyPipe-.svg) 
![forks](https://img.shields.io/github/forks/edsonjt81/CVE-2022-0847-DirtyPipe-.svg) 
2022-10-12T18:27:09Z

- [https://github.com/al4xs/CVE-2022-0847-Dirty-Pipe](https://github.com/al4xs/CVE-2022-0847-Dirty-Pipe) :  
![starts](https://img.shields.io/github/stars/al4xs/CVE-2022-0847-Dirty-Pipe.svg) 
![forks](https://img.shields.io/github/forks/al4xs/CVE-2022-0847-Dirty-Pipe.svg) 
2022-03-10T16:09:25Z

- [https://github.com/Greetdawn/CVE-2022-0847-DirtyPipe](https://github.com/Greetdawn/CVE-2022-0847-DirtyPipe) :  
![starts](https://img.shields.io/github/stars/Greetdawn/CVE-2022-0847-DirtyPipe.svg) 
![forks](https://img.shields.io/github/forks/Greetdawn/CVE-2022-0847-DirtyPipe.svg) 
2022-03-11T02:55:37Z

- [https://github.com/AyoubNajim/cve-2022-0847dirtypipe-exploit](https://github.com/AyoubNajim/cve-2022-0847dirtypipe-exploit) :  
![starts](https://img.shields.io/github/stars/AyoubNajim/cve-2022-0847dirtypipe-exploit.svg) 
![forks](https://img.shields.io/github/forks/AyoubNajim/cve-2022-0847dirtypipe-exploit.svg) 
2022-03-09T10:16:13Z

- [https://github.com/jxpsx/CVE-2022-0847-DirtyPipe-Exploits](https://github.com/jxpsx/CVE-2022-0847-DirtyPipe-Exploits) :  
![starts](https://img.shields.io/github/stars/jxpsx/CVE-2022-0847-DirtyPipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/jxpsx/CVE-2022-0847-DirtyPipe-Exploits.svg) 
2022-06-29T12:05:12Z

- [https://github.com/stfnw/Debugging_Dirty_Pipe_CVE-2022-0847](https://github.com/stfnw/Debugging_Dirty_Pipe_CVE-2022-0847) :  
![starts](https://img.shields.io/github/stars/stfnw/Debugging_Dirty_Pipe_CVE-2022-0847.svg) 
![forks](https://img.shields.io/github/forks/stfnw/Debugging_Dirty_Pipe_CVE-2022-0847.svg) 
2022-04-01T05:53:46Z

- [https://github.com/ayushx007/CVE-2022-0847-dirty-pipe-checker](https://github.com/ayushx007/CVE-2022-0847-dirty-pipe-checker) :  
![starts](https://img.shields.io/github/stars/ayushx007/CVE-2022-0847-dirty-pipe-checker.svg) 
![forks](https://img.shields.io/github/forks/ayushx007/CVE-2022-0847-dirty-pipe-checker.svg) 
2023-10-25T11:29:22Z

- [https://github.com/muhammad1596/CVE-2022-0847-DirtyPipe-Exploits](https://github.com/muhammad1596/CVE-2022-0847-DirtyPipe-Exploits) :  
![starts](https://img.shields.io/github/stars/muhammad1596/CVE-2022-0847-DirtyPipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/muhammad1596/CVE-2022-0847-DirtyPipe-Exploits.svg) 
2024-06-06T14:39:17Z

- [https://github.com/ayushx007/CVE-2022-0847-DirtyPipe-Exploits](https://github.com/ayushx007/CVE-2022-0847-DirtyPipe-Exploits) :  
![starts](https://img.shields.io/github/stars/ayushx007/CVE-2022-0847-DirtyPipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/ayushx007/CVE-2022-0847-DirtyPipe-Exploits.svg) 
2023-11-05T15:35:47Z

- [https://github.com/orsuprasad/CVE-2022-0847-DirtyPipe-Exploits](https://github.com/orsuprasad/CVE-2022-0847-DirtyPipe-Exploits) :  
![starts](https://img.shields.io/github/stars/orsuprasad/CVE-2022-0847-DirtyPipe-Exploits.svg) 
![forks](https://img.shields.io/github/forks/orsuprasad/CVE-2022-0847-DirtyPipe-Exploits.svg) 
2023-02-26T07:09:43Z

- [https://github.com/tufanturhan/CVE-2022-0847-L-nux-PrivEsc](https://github.com/tufanturhan/CVE-2022-0847-L-nux-PrivEsc) :  
![starts](https://img.shields.io/github/stars/tufanturhan/CVE-2022-0847-L-nux-PrivEsc.svg) 
![forks](https://img.shields.io/github/forks/tufanturhan/CVE-2022-0847-L-nux-PrivEsc.svg) 
2022-04-15T09:11:51Z

- [https://github.com/solomon12354/LockingGirl-----CVE-2022-0847-Dirty_Pipe_virus](https://github.com/solomon12354/LockingGirl-----CVE-2022-0847-Dirty_Pipe_virus) :  
![starts](https://img.shields.io/github/stars/solomon12354/LockingGirl-----CVE-2022-0847-Dirty_Pipe_virus.svg) 
![forks](https://img.shields.io/github/forks/solomon12354/LockingGirl-----CVE-2022-0847-Dirty_Pipe_virus.svg) 
2024-05-27T16:41:22Z

- [https://github.com/notl0cal/dpipe](https://github.com/notl0cal/dpipe) :  
![starts](https://img.shields.io/github/stars/notl0cal/dpipe.svg) 
![forks](https://img.shields.io/github/forks/notl0cal/dpipe.svg) 
2022-08-31T23:25:58Z

## CVE-2020-8012
 CA Unified Infrastructure Management (Nimsoft/UIM) 20.1, 20.3.x, and 9.20 and below contains a buffer overflow vulnerability in the robot (controller) component. A remote attacker can execute arbitrary code.

- [https://github.com/wetw0rk/Exploit-Development](https://github.com/wetw0rk/Exploit-Development) :  
![starts](https://img.shields.io/github/stars/wetw0rk/Exploit-Development.svg) 
![forks](https://img.shields.io/github/forks/wetw0rk/Exploit-Development.svg) 
2025-02-09T20:30:23Z

## CVE-2019-1003000
 A sandbox bypass vulnerability exists in Script Security Plugin 1.49 and earlier in src/main/java/org/jenkinsci/plugins/scriptsecurity/sandbox/groovy/GroovySandbox.java that allows attackers with the ability to provide sandboxed scripts to execute arbitrary code on the Jenkins master JVM.

- [https://github.com/adamyordan/cve-2019-1003000-jenkins-rce-poc](https://github.com/adamyordan/cve-2019-1003000-jenkins-rce-poc) :  
![starts](https://img.shields.io/github/stars/adamyordan/cve-2019-1003000-jenkins-rce-poc.svg) 
![forks](https://img.shields.io/github/forks/adamyordan/cve-2019-1003000-jenkins-rce-poc.svg) 
2019-04-01T13:19:49Z

- [https://github.com/wetw0rk/Exploit-Development](https://github.com/wetw0rk/Exploit-Development) :  
![starts](https://img.shields.io/github/stars/wetw0rk/Exploit-Development.svg) 
![forks](https://img.shields.io/github/forks/wetw0rk/Exploit-Development.svg) 
2025-02-09T20:30:23Z

- [https://github.com/1NTheKut/CVE-2019-1003000_RCE-DETECTION](https://github.com/1NTheKut/CVE-2019-1003000_RCE-DETECTION) :  
![starts](https://img.shields.io/github/stars/1NTheKut/CVE-2019-1003000_RCE-DETECTION.svg) 
![forks](https://img.shields.io/github/forks/1NTheKut/CVE-2019-1003000_RCE-DETECTION.svg) 
2019-05-01T07:11:28Z

- [https://github.com/purple-WL/Jenkins_CVE-2019-1003000](https://github.com/purple-WL/Jenkins_CVE-2019-1003000) :  
![starts](https://img.shields.io/github/stars/purple-WL/Jenkins_CVE-2019-1003000.svg) 
![forks](https://img.shields.io/github/forks/purple-WL/Jenkins_CVE-2019-1003000.svg) 
2022-02-12T11:27:49Z

- [https://github.com/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins](https://github.com/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins) :  
![starts](https://img.shields.io/github/stars/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins.svg) 
![forks](https://img.shields.io/github/forks/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins.svg) 
2019-02-23T10:01:26Z

## CVE-2018-1999002
 A arbitrary file read vulnerability exists in Jenkins 2.132 and earlier, 2.121.1 and earlier in the Stapler web framework's org/kohsuke/stapler/Stapler.java that allows attackers to send crafted HTTP requests returning the contents of any file on the Jenkins master file system that the Jenkins master has access to.

- [https://github.com/wetw0rk/Exploit-Development](https://github.com/wetw0rk/Exploit-Development) :  
![starts](https://img.shields.io/github/stars/wetw0rk/Exploit-Development.svg) 
![forks](https://img.shields.io/github/forks/wetw0rk/Exploit-Development.svg) 
2025-02-09T20:30:23Z

- [https://github.com/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins](https://github.com/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins) :  
![starts](https://img.shields.io/github/stars/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins.svg) 
![forks](https://img.shields.io/github/forks/slowmistio/CVE-2019-1003000-and-CVE-2018-1999002-Pre-Auth-RCE-Jenkins.svg) 
2019-02-23T10:01:26Z

- [https://github.com/0x6b7966/CVE-2018-1999002](https://github.com/0x6b7966/CVE-2018-1999002) :  
![starts](https://img.shields.io/github/stars/0x6b7966/CVE-2018-1999002.svg) 
![forks](https://img.shields.io/github/forks/0x6b7966/CVE-2018-1999002.svg) 
2019-09-10T05:24:32Z

## CVE-2017-20165
 A vulnerability classified as problematic has been found in debug-js debug up to 3.0.x. This affects the function useColors of the file src/node.js. The manipulation of the argument str leads to inefficient regular expression complexity. Upgrading to version 3.1.0 is able to address this issue. The identifier of the patch is c38a0166c266a679c8de012d4eaccec3f944e685. It is recommended to upgrade the affected component. The identifier VDB-217665 was assigned to this vulnerability.

- [https://github.com/fastify/send](https://github.com/fastify/send) :  
![starts](https://img.shields.io/github/stars/fastify/send.svg) 
![forks](https://img.shields.io/github/forks/fastify/send.svg) 
2025-02-09T17:16:57Z

## CVE-2017-18047
 Buffer Overflow in the FTP client in LabF nfsAxe 3.7 allows remote FTP servers to execute arbitrary code via a long reply.

- [https://github.com/wetw0rk/Exploit-Development](https://github.com/wetw0rk/Exploit-Development) :  
![starts](https://img.shields.io/github/stars/wetw0rk/Exploit-Development.svg) 
![forks](https://img.shields.io/github/forks/wetw0rk/Exploit-Development.svg) 
2025-02-09T20:30:23Z

## CVE-2017-17099
 There exists an unauthenticated SEH based Buffer Overflow vulnerability in the HTTP server of Flexense SyncBreeze Enterprise v10.1.16. When sending a GET request with an excessive length, it is possible for a malicious user to overwrite the SEH record and execute a payload that would run under the Windows SYSTEM account.

- [https://github.com/wetw0rk/Exploit-Development](https://github.com/wetw0rk/Exploit-Development) :  
![starts](https://img.shields.io/github/stars/wetw0rk/Exploit-Development.svg) 
![forks](https://img.shields.io/github/forks/wetw0rk/Exploit-Development.svg) 
2025-02-09T20:30:23Z

## CVE-2016-10709
 pfSense before 2.3 allows remote authenticated users to execute arbitrary OS commands via a '|' character in the status_rrd_graph_img.php graph parameter, related to _rrd_graph_img.php.

- [https://github.com/wetw0rk/Exploit-Development](https://github.com/wetw0rk/Exploit-Development) :  
![starts](https://img.shields.io/github/stars/wetw0rk/Exploit-Development.svg) 
![forks](https://img.shields.io/github/forks/wetw0rk/Exploit-Development.svg) 
2025-02-09T20:30:23Z

## CVE-2014-4210
 Unspecified vulnerability in the Oracle WebLogic Server component in Oracle Fusion Middleware 10.0.2.0 and 10.3.6.0 allows remote attackers to affect confidentiality via vectors related to WLS - Web Services.

- [https://github.com/0xn0ne/weblogicScanner](https://github.com/0xn0ne/weblogicScanner) :  
![starts](https://img.shields.io/github/stars/0xn0ne/weblogicScanner.svg) 
![forks](https://img.shields.io/github/forks/0xn0ne/weblogicScanner.svg) 
2023-11-24T09:21:56Z

- [https://github.com/NoneNotNull/SSRFX](https://github.com/NoneNotNull/SSRFX) :  
![starts](https://img.shields.io/github/stars/NoneNotNull/SSRFX.svg) 
![forks](https://img.shields.io/github/forks/NoneNotNull/SSRFX.svg) 
2017-03-10T08:35:42Z

- [https://github.com/NHPT/WebLogic-SSRF_CVE-2014-4210](https://github.com/NHPT/WebLogic-SSRF_CVE-2014-4210) :  
![starts](https://img.shields.io/github/stars/NHPT/WebLogic-SSRF_CVE-2014-4210.svg) 
![forks](https://img.shields.io/github/forks/NHPT/WebLogic-SSRF_CVE-2014-4210.svg) 
2020-11-20T05:55:15Z

- [https://github.com/unmanarc/CVE-2014-4210-SSRF-PORTSCANNER-POC](https://github.com/unmanarc/CVE-2014-4210-SSRF-PORTSCANNER-POC) :  
![starts](https://img.shields.io/github/stars/unmanarc/CVE-2014-4210-SSRF-PORTSCANNER-POC.svg) 
![forks](https://img.shields.io/github/forks/unmanarc/CVE-2014-4210-SSRF-PORTSCANNER-POC.svg) 
2020-07-21T03:46:09Z

- [https://github.com/ZorvithonLeo/Exploit-CVE-2014-4210-](https://github.com/ZorvithonLeo/Exploit-CVE-2014-4210-) :  
![starts](https://img.shields.io/github/stars/ZorvithonLeo/Exploit-CVE-2014-4210-.svg) 
![forks](https://img.shields.io/github/forks/ZorvithonLeo/Exploit-CVE-2014-4210-.svg) 
2025-02-09T19:43:56Z

# 2025-02-08
## CVE-2025-1015
 The Thunderbird Address Book URI fields contained unsanitized links. This could be used by an attacker to create and export an address book containing a malicious payload in a field. For example, in the Other field of the Instant Messaging section. If another user imported the address book, clicking on the link could result in opening a web page inside Thunderbird, and that page could execute (unprivileged) JavaScript. This vulnerability affects Thunderbird  128.7.

- [https://github.com/r3m0t3nu11/CVE-2025-1015](https://github.com/r3m0t3nu11/CVE-2025-1015) :  
![starts](https://img.shields.io/github/stars/r3m0t3nu11/CVE-2025-1015.svg) 
![forks](https://img.shields.io/github/forks/r3m0t3nu11/CVE-2025-1015.svg) 
2025-02-08T13:54:25Z

## CVE-2024-54916
 An issue in the SharedConfig class of Telegram Android APK v.11.7.0 allows a physically proximate attacker to bypass authentication and escalate privileges by manipulating the return value of the checkPasscode method.

- [https://github.com/SAHALLL/CVE-2024-54916](https://github.com/SAHALLL/CVE-2024-54916) :  
![starts](https://img.shields.io/github/stars/SAHALLL/CVE-2024-54916.svg) 
![forks](https://img.shields.io/github/forks/SAHALLL/CVE-2024-54916.svg) 
2025-02-08T03:42:22Z

## CVE-2024-6244
 The PZ Frontend Manager WordPress plugin before 1.0.6 does not have CSRF checks in some places, which could allow attackers to make logged in users perform unwanted actions via CSRF attacks

- [https://github.com/Nxploited/CVE-2024-6244](https://github.com/Nxploited/CVE-2024-6244) :  
![starts](https://img.shields.io/github/stars/Nxploited/CVE-2024-6244.svg) 
![forks](https://img.shields.io/github/forks/Nxploited/CVE-2024-6244.svg) 
2025-02-08T20:30:30Z

## CVE-2024-5057
 Improper Neutralization of Special Elements used in an SQL Command ('SQL Injection') vulnerability in Easy Digital Downloads allows SQL Injection.This issue affects Easy Digital Downloads: from n/a through 3.2.12.

- [https://github.com/s1mpl3c0d3/cvepoc](https://github.com/s1mpl3c0d3/cvepoc) :  
![starts](https://img.shields.io/github/stars/s1mpl3c0d3/cvepoc.svg) 
![forks](https://img.shields.io/github/forks/s1mpl3c0d3/cvepoc.svg) 
2025-02-08T13:21:07Z

## CVE-2023-21716
 Microsoft Word Remote Code Execution Vulnerability

- [https://github.com/gyaansastra/CVE-2023-21716](https://github.com/gyaansastra/CVE-2023-21716) :  
![starts](https://img.shields.io/github/stars/gyaansastra/CVE-2023-21716.svg) 
![forks](https://img.shields.io/github/forks/gyaansastra/CVE-2023-21716.svg) 
2023-03-08T06:21:58Z

- [https://github.com/Xnuvers007/CVE-2023-21716](https://github.com/Xnuvers007/CVE-2023-21716) :  
![starts](https://img.shields.io/github/stars/Xnuvers007/CVE-2023-21716.svg) 
![forks](https://img.shields.io/github/forks/Xnuvers007/CVE-2023-21716.svg) 
2023-03-07T15:17:47Z

- [https://github.com/hv0l/CVE-2023-21716_exploit](https://github.com/hv0l/CVE-2023-21716_exploit) :  
![starts](https://img.shields.io/github/stars/hv0l/CVE-2023-21716_exploit.svg) 
![forks](https://img.shields.io/github/forks/hv0l/CVE-2023-21716_exploit.svg) 
2023-03-24T16:00:42Z

- [https://github.com/JMousqueton/CVE-2023-21716](https://github.com/JMousqueton/CVE-2023-21716) :  
![starts](https://img.shields.io/github/stars/JMousqueton/CVE-2023-21716.svg) 
![forks](https://img.shields.io/github/forks/JMousqueton/CVE-2023-21716.svg) 
2023-04-16T21:16:25Z

- [https://github.com/FeatherStark/CVE-2023-21716](https://github.com/FeatherStark/CVE-2023-21716) :  
![starts](https://img.shields.io/github/stars/FeatherStark/CVE-2023-21716.svg) 
![forks](https://img.shields.io/github/forks/FeatherStark/CVE-2023-21716.svg) 
2023-03-07T09:35:33Z

- [https://github.com/maldev866/WordExp_CVE_2023_21716](https://github.com/maldev866/WordExp_CVE_2023_21716) :  
![starts](https://img.shields.io/github/stars/maldev866/WordExp_CVE_2023_21716.svg) 
![forks](https://img.shields.io/github/forks/maldev866/WordExp_CVE_2023_21716.svg) 
2023-03-08T12:09:06Z

- [https://github.com/MojithaR/CVE-2023-21716-EXPLOIT.py](https://github.com/MojithaR/CVE-2023-21716-EXPLOIT.py) :  
![starts](https://img.shields.io/github/stars/MojithaR/CVE-2023-21716-EXPLOIT.py.svg) 
![forks](https://img.shields.io/github/forks/MojithaR/CVE-2023-21716-EXPLOIT.py.svg) 
2023-11-05T12:23:00Z

- [https://github.com/Lord-of-the-IoT/CVE-2023-21716](https://github.com/Lord-of-the-IoT/CVE-2023-21716) :  
![starts](https://img.shields.io/github/stars/Lord-of-the-IoT/CVE-2023-21716.svg) 
![forks](https://img.shields.io/github/forks/Lord-of-the-IoT/CVE-2023-21716.svg) 
2023-06-13T19:04:46Z

- [https://github.com/3yujw7njai/CVE-2023-21716-POC](https://github.com/3yujw7njai/CVE-2023-21716-POC) :  
![starts](https://img.shields.io/github/stars/3yujw7njai/CVE-2023-21716-POC.svg) 
![forks](https://img.shields.io/github/forks/3yujw7njai/CVE-2023-21716-POC.svg) 
2023-03-10T02:48:21Z

- [https://github.com/RonF98/CVE-2023-21716-POC](https://github.com/RonF98/CVE-2023-21716-POC) :  
![starts](https://img.shields.io/github/stars/RonF98/CVE-2023-21716-POC.svg) 
![forks](https://img.shields.io/github/forks/RonF98/CVE-2023-21716-POC.svg) 
2024-09-23T13:46:22Z

- [https://github.com/mikesxrs/CVE-2023-21716_YARA_Results](https://github.com/mikesxrs/CVE-2023-21716_YARA_Results) :  
![starts](https://img.shields.io/github/stars/mikesxrs/CVE-2023-21716_YARA_Results.svg) 
![forks](https://img.shields.io/github/forks/mikesxrs/CVE-2023-21716_YARA_Results.svg) 
2023-03-11T00:04:47Z

- [https://github.com/s1mpl3c0d3/cvepoc](https://github.com/s1mpl3c0d3/cvepoc) :  
![starts](https://img.shields.io/github/stars/s1mpl3c0d3/cvepoc.svg) 
![forks](https://img.shields.io/github/forks/s1mpl3c0d3/cvepoc.svg) 
2025-02-08T13:21:07Z

## CVE-2021-31755
 An issue was discovered on Tenda AC11 devices with firmware through 02.03.01.104_CN. A stack buffer overflow vulnerability in /goform/setmac allows attackers to execute arbitrary code on the system via a crafted post request.

- [https://github.com/s1mpl3c0d3/cvepoc](https://github.com/s1mpl3c0d3/cvepoc) :  
![starts](https://img.shields.io/github/stars/s1mpl3c0d3/cvepoc.svg) 
![forks](https://img.shields.io/github/forks/s1mpl3c0d3/cvepoc.svg) 
2025-02-08T13:21:07Z

## CVE-2019-11248
 The debugging endpoint /debug/pprof is exposed over the unauthenticated Kubelet healthz port. The go pprof endpoint is exposed over the Kubelet's healthz port. This debugging endpoint can potentially leak sensitive information such as internal Kubelet memory addresses and configuration, or for limited denial of service. Versions prior to 1.15.0, 1.14.4, 1.13.8, and 1.12.10 are affected. The issue is of medium severity, but not exposed by the default configuration.

- [https://github.com/s1mpl3c0d3/cvepoc](https://github.com/s1mpl3c0d3/cvepoc) :  
![starts](https://img.shields.io/github/stars/s1mpl3c0d3/cvepoc.svg) 
![forks](https://img.shields.io/github/forks/s1mpl3c0d3/cvepoc.svg) 
2025-02-08T13:21:07Z

## CVE-2017-14980
 Buffer overflow in Sync Breeze Enterprise 10.0.28 allows remote attackers to have unspecified impact via a long username parameter to /login.

- [https://github.com/TheDarthMole/CVE-2017-14980](https://github.com/TheDarthMole/CVE-2017-14980) :  
![starts](https://img.shields.io/github/stars/TheDarthMole/CVE-2017-14980.svg) 
![forks](https://img.shields.io/github/forks/TheDarthMole/CVE-2017-14980.svg) 
2023-02-03T18:40:18Z

- [https://github.com/xn0kkx/Exploit_Sync_Breeze_v10.0.28_CVE-2017-14980](https://github.com/xn0kkx/Exploit_Sync_Breeze_v10.0.28_CVE-2017-14980) :  
![starts](https://img.shields.io/github/stars/xn0kkx/Exploit_Sync_Breeze_v10.0.28_CVE-2017-14980.svg) 
![forks](https://img.shields.io/github/forks/xn0kkx/Exploit_Sync_Breeze_v10.0.28_CVE-2017-14980.svg) 
2025-02-08T15:17:18Z

## CVE-2001-1473
 The SSH-1 protocol allows remote servers to conduct man-in-the-middle attacks and replay a client challenge response to a target server by creating a Session ID that matches the Session ID of the target, but which uses a public key pair that is weaker than the target's public key, which allows the attacker to compute the corresponding private key and use the target's Session ID with the compromised key pair to masquerade as the target.

- [https://github.com/s1mpl3c0d3/cvepoc](https://github.com/s1mpl3c0d3/cvepoc) :  
![starts](https://img.shields.io/github/stars/s1mpl3c0d3/cvepoc.svg) 
![forks](https://img.shields.io/github/forks/s1mpl3c0d3/cvepoc.svg) 
2025-02-08T13:21:07Z

# 2025-02-07
## CVE-2025-0994
 Trimble Cityworks versions prior to 15.8.9 and Cityworks with office companion versions prior to 23.10 are vulnerable to a deserialization vulnerability. This could allow an authenticated user to perform a remote code execution attack against a customers Microsoft Internet Information Services (IIS) web server.

- [https://github.com/rxerium/CVE-2025-0994](https://github.com/rxerium/CVE-2025-0994) :  
![starts](https://img.shields.io/github/stars/rxerium/CVE-2025-0994.svg) 
![forks](https://img.shields.io/github/forks/rxerium/CVE-2025-0994.svg) 
2025-02-07T14:15:32Z

## CVE-2024-57373
 Cross Site Request Forgery (CSRF) vulnerability in LifestyleStore v1.0 allows a remote attacker to execute unauthorized actions on behalf of an authenticated user, potentially leading to account modifications or data compromise.

- [https://github.com/cypherdavy/CVE-2024-57373](https://github.com/cypherdavy/CVE-2024-57373) :  
![starts](https://img.shields.io/github/stars/cypherdavy/CVE-2024-57373.svg) 
![forks](https://img.shields.io/github/forks/cypherdavy/CVE-2024-57373.svg) 
2025-02-07T20:55:16Z

## CVE-2024-55215
 An issue in trojan v.2.0.0 through v.2.15.3 allows a remote attacker to escalate privileges via the initialization interface /auth/register.

- [https://github.com/ainrm/Jrohy-trojan-unauth-poc](https://github.com/ainrm/Jrohy-trojan-unauth-poc) :  
![starts](https://img.shields.io/github/stars/ainrm/Jrohy-trojan-unauth-poc.svg) 
![forks](https://img.shields.io/github/forks/ainrm/Jrohy-trojan-unauth-poc.svg) 
2025-02-07T02:10:22Z

## CVE-2024-43425
 A flaw was found in Moodle. Additional restrictions are required to avoid a remote code execution risk in calculated question types. Note: This requires the capability to add/update questions.

- [https://github.com/RedTeamPentesting/moodle-rce-calculatedquestions](https://github.com/RedTeamPentesting/moodle-rce-calculatedquestions) :  
![starts](https://img.shields.io/github/stars/RedTeamPentesting/moodle-rce-calculatedquestions.svg) 
![forks](https://img.shields.io/github/forks/RedTeamPentesting/moodle-rce-calculatedquestions.svg) 
2024-08-23T09:36:55Z

- [https://github.com/Snizi/Moodle-CVE-2024-43425-Exploit](https://github.com/Snizi/Moodle-CVE-2024-43425-Exploit) :  
![starts](https://img.shields.io/github/stars/Snizi/Moodle-CVE-2024-43425-Exploit.svg) 
![forks](https://img.shields.io/github/forks/Snizi/Moodle-CVE-2024-43425-Exploit.svg) 
2025-02-07T22:12:52Z

## CVE-2024-39713
 A Server-Side Request Forgery (SSRF) affects Rocket.Chat's Twilio webhook endpoint before version 6.10.1.

- [https://github.com/typical-pashochek/CVE-2024-39713](https://github.com/typical-pashochek/CVE-2024-39713) :  
![starts](https://img.shields.io/github/stars/typical-pashochek/CVE-2024-39713.svg) 
![forks](https://img.shields.io/github/forks/typical-pashochek/CVE-2024-39713.svg) 
2025-02-07T14:20:02Z

## CVE-2024-25600
 Improper Control of Generation of Code ('Code Injection') vulnerability in Codeer Limited Bricks Builder allows Code Injection.This issue affects Bricks Builder: from n/a through 1.9.6.

- [https://github.com/gobysec/Goby](https://github.com/gobysec/Goby) :  
![starts](https://img.shields.io/github/stars/gobysec/Goby.svg) 
![forks](https://img.shields.io/github/forks/gobysec/Goby.svg) 
2024-02-29T09:48:14Z

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2024-11-20T12:44:28Z

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

- [https://github.com/WanLiChangChengWanLiChang/CVE-2024-25600](https://github.com/WanLiChangChengWanLiChang/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/WanLiChangChengWanLiChang/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/WanLiChangChengWanLiChang/CVE-2024-25600.svg) 
2024-06-07T17:15:43Z

- [https://github.com/wh6amiGit/CVE-2024-25600](https://github.com/wh6amiGit/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/wh6amiGit/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/wh6amiGit/CVE-2024-25600.svg) 
2024-08-20T13:57:56Z

- [https://github.com/k3lpi3b4nsh33/CVE-2024-25600](https://github.com/k3lpi3b4nsh33/CVE-2024-25600) :  
![starts](https://img.shields.io/github/stars/k3lpi3b4nsh33/CVE-2024-25600.svg) 
![forks](https://img.shields.io/github/forks/k3lpi3b4nsh33/CVE-2024-25600.svg) 
2024-06-06T02:36:34Z

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

- [https://github.com/Raeezrbr/CVE-2024-5084](https://github.com/Raeezrbr/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/Raeezrbr/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/Raeezrbr/CVE-2024-5084.svg) 
2024-11-30T10:55:58Z

- [https://github.com/k3lpi3b4nsh33/CVE-2024-5084](https://github.com/k3lpi3b4nsh33/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/k3lpi3b4nsh33/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/k3lpi3b4nsh33/CVE-2024-5084.svg) 
2024-06-06T03:29:24Z

- [https://github.com/z1gazaga/CVE-2024-5084](https://github.com/z1gazaga/CVE-2024-5084) :  
![starts](https://img.shields.io/github/stars/z1gazaga/CVE-2024-5084.svg) 
![forks](https://img.shields.io/github/forks/z1gazaga/CVE-2024-5084.svg) 
2024-11-21T07:11:34Z

## CVE-2023-51467
 The vulnerability permits attackers to circumvent authentication processes, enabling them to remotely execute arbitrary code

- [https://github.com/gobysec/GobyVuls](https://github.com/gobysec/GobyVuls) :  
![starts](https://img.shields.io/github/stars/gobysec/GobyVuls.svg) 
![forks](https://img.shields.io/github/forks/gobysec/GobyVuls.svg) 
2024-11-20T12:44:28Z

- [https://github.com/jakabakos/Apache-OFBiz-Authentication-Bypass](https://github.com/jakabakos/Apache-OFBiz-Authentication-Bypass) :  
![starts](https://img.shields.io/github/stars/jakabakos/Apache-OFBiz-Authentication-Bypass.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/Apache-OFBiz-Authentication-Bypass.svg) 
2024-03-24T18:20:52Z

- [https://github.com/JaneMandy/CVE-2023-51467-Exploit](https://github.com/JaneMandy/CVE-2023-51467-Exploit) :  
![starts](https://img.shields.io/github/stars/JaneMandy/CVE-2023-51467-Exploit.svg) 
![forks](https://img.shields.io/github/forks/JaneMandy/CVE-2023-51467-Exploit.svg) 
2024-01-06T10:33:34Z

- [https://github.com/D0g3-8Bit/OFBiz-Attack](https://github.com/D0g3-8Bit/OFBiz-Attack) :  
![starts](https://img.shields.io/github/stars/D0g3-8Bit/OFBiz-Attack.svg) 
![forks](https://img.shields.io/github/forks/D0g3-8Bit/OFBiz-Attack.svg) 
2024-03-12T11:06:55Z

- [https://github.com/Chocapikk/CVE-2023-51467](https://github.com/Chocapikk/CVE-2023-51467) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2023-51467.svg) 
2023-12-31T01:23:55Z

- [https://github.com/K3ysTr0K3R/CVE-2023-51467-EXPLOIT](https://github.com/K3ysTr0K3R/CVE-2023-51467-EXPLOIT) :  
![starts](https://img.shields.io/github/stars/K3ysTr0K3R/CVE-2023-51467-EXPLOIT.svg) 
![forks](https://img.shields.io/github/forks/K3ysTr0K3R/CVE-2023-51467-EXPLOIT.svg) 
2023-12-31T21:29:59Z

- [https://github.com/vulncheck-oss/cve-2023-51467](https://github.com/vulncheck-oss/cve-2023-51467) :  
![starts](https://img.shields.io/github/stars/vulncheck-oss/cve-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/vulncheck-oss/cve-2023-51467.svg) 
2025-02-07T17:28:56Z

- [https://github.com/UserConnecting/Exploit-CVE-2023-49070-and-CVE-2023-51467-Apache-OFBiz](https://github.com/UserConnecting/Exploit-CVE-2023-49070-and-CVE-2023-51467-Apache-OFBiz) :  
![starts](https://img.shields.io/github/stars/UserConnecting/Exploit-CVE-2023-49070-and-CVE-2023-51467-Apache-OFBiz.svg) 
![forks](https://img.shields.io/github/forks/UserConnecting/Exploit-CVE-2023-49070-and-CVE-2023-51467-Apache-OFBiz.svg) 
2025-02-05T18:46:48Z

- [https://github.com/JaneMandy/CVE-2023-51467](https://github.com/JaneMandy/CVE-2023-51467) :  
![starts](https://img.shields.io/github/stars/JaneMandy/CVE-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/JaneMandy/CVE-2023-51467.svg) 
2024-01-02T07:28:24Z

- [https://github.com/yukselberkay/CVE-2023-49070_CVE-2023-51467](https://github.com/yukselberkay/CVE-2023-49070_CVE-2023-51467) :  
![starts](https://img.shields.io/github/stars/yukselberkay/CVE-2023-49070_CVE-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/yukselberkay/CVE-2023-49070_CVE-2023-51467.svg) 
2024-01-12T10:37:18Z

- [https://github.com/Subha-BOO7/Exploit_CVE-2023-51467](https://github.com/Subha-BOO7/Exploit_CVE-2023-51467) :  
![starts](https://img.shields.io/github/stars/Subha-BOO7/Exploit_CVE-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/Subha-BOO7/Exploit_CVE-2023-51467.svg) 
2024-01-04T12:45:24Z

- [https://github.com/2ptr/BadBizness-CVE-2023-51467](https://github.com/2ptr/BadBizness-CVE-2023-51467) :  
![starts](https://img.shields.io/github/stars/2ptr/BadBizness-CVE-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/2ptr/BadBizness-CVE-2023-51467.svg) 
2024-01-13T06:43:24Z

- [https://github.com/Praison001/Apache-OFBiz-Auth-Bypass-and-RCE-Exploit-CVE-2023-49070-CVE-2023-51467](https://github.com/Praison001/Apache-OFBiz-Auth-Bypass-and-RCE-Exploit-CVE-2023-49070-CVE-2023-51467) :  
![starts](https://img.shields.io/github/stars/Praison001/Apache-OFBiz-Auth-Bypass-and-RCE-Exploit-CVE-2023-49070-CVE-2023-51467.svg) 
![forks](https://img.shields.io/github/forks/Praison001/Apache-OFBiz-Auth-Bypass-and-RCE-Exploit-CVE-2023-49070-CVE-2023-51467.svg) 
2024-01-25T08:21:44Z

- [https://github.com/AhmedMansour93/Event-ID-217-Rule-Name-SOC254-Apache-OFBiz-Auth-Bypass-and-Code-Injection-0Day-CVE-2023-51467-](https://github.com/AhmedMansour93/Event-ID-217-Rule-Name-SOC254-Apache-OFBiz-Auth-Bypass-and-Code-Injection-0Day-CVE-2023-51467-) :  
![starts](https://img.shields.io/github/stars/AhmedMansour93/Event-ID-217-Rule-Name-SOC254-Apache-OFBiz-Auth-Bypass-and-Code-Injection-0Day-CVE-2023-51467-.svg) 
![forks](https://img.shields.io/github/forks/AhmedMansour93/Event-ID-217-Rule-Name-SOC254-Apache-OFBiz-Auth-Bypass-and-Code-Injection-0Day-CVE-2023-51467-.svg) 
2024-09-13T11:48:02Z

## CVE-2023-34960
 A command injection vulnerability in the wsConvertPpt component of Chamilo v1.11.* up to v1.11.18 allows attackers to execute arbitrary commands via a SOAP API call with a crafted PowerPoint name.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/getdrive/PoC](https://github.com/getdrive/PoC) :  
![starts](https://img.shields.io/github/stars/getdrive/PoC.svg) 
![forks](https://img.shields.io/github/forks/getdrive/PoC.svg) 
2024-08-12T07:34:08Z

- [https://github.com/Aituglo/CVE-2023-34960](https://github.com/Aituglo/CVE-2023-34960) :  
![starts](https://img.shields.io/github/stars/Aituglo/CVE-2023-34960.svg) 
![forks](https://img.shields.io/github/forks/Aituglo/CVE-2023-34960.svg) 
2023-06-09T10:33:47Z

- [https://github.com/ThatNotEasy/CVE-2023-34960](https://github.com/ThatNotEasy/CVE-2023-34960) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2023-34960.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2023-34960.svg) 
2023-07-31T20:39:37Z

- [https://github.com/Mantodkaz/CVE-2023-34960](https://github.com/Mantodkaz/CVE-2023-34960) :  
![starts](https://img.shields.io/github/stars/Mantodkaz/CVE-2023-34960.svg) 
![forks](https://img.shields.io/github/forks/Mantodkaz/CVE-2023-34960.svg) 
2023-09-05T12:17:22Z

- [https://github.com/dvtarsoul/ChExp](https://github.com/dvtarsoul/ChExp) :  
![starts](https://img.shields.io/github/stars/dvtarsoul/ChExp.svg) 
![forks](https://img.shields.io/github/forks/dvtarsoul/ChExp.svg) 
2024-10-21T18:24:28Z

- [https://github.com/Jenderal92/CHAMILO-CVE-2023-34960](https://github.com/Jenderal92/CHAMILO-CVE-2023-34960) :  
![starts](https://img.shields.io/github/stars/Jenderal92/CHAMILO-CVE-2023-34960.svg) 
![forks](https://img.shields.io/github/forks/Jenderal92/CHAMILO-CVE-2023-34960.svg) 
2024-11-17T23:46:28Z

- [https://github.com/YongYe-Security/CVE-2023-34960](https://github.com/YongYe-Security/CVE-2023-34960) :  
![starts](https://img.shields.io/github/stars/YongYe-Security/CVE-2023-34960.svg) 
![forks](https://img.shields.io/github/forks/YongYe-Security/CVE-2023-34960.svg) 
2023-07-09T11:57:07Z

- [https://github.com/tucommenceapousser/CVE-2023-34960-ex](https://github.com/tucommenceapousser/CVE-2023-34960-ex) :  
![starts](https://img.shields.io/github/stars/tucommenceapousser/CVE-2023-34960-ex.svg) 
![forks](https://img.shields.io/github/forks/tucommenceapousser/CVE-2023-34960-ex.svg) 
2023-08-01T08:39:57Z

## CVE-2023-28432
 Minio is a Multi-Cloud Object Storage framework. In a cluster deployment starting with RELEASE.2019-12-17T23-16-33Z and prior to RELEASE.2023-03-20T20-16-18Z, MinIO returns all environment variables, including `MINIO_SECRET_KEY`and `MINIO_ROOT_PASSWORD`, resulting in information disclosure. All users of distributed deployment are impacted. All users are advised to upgrade to RELEASE.2023-03-20T20-16-18Z.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/MzzdToT/CVE-2023-28432](https://github.com/MzzdToT/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/MzzdToT/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/MzzdToT/CVE-2023-28432.svg) 
2023-03-24T08:19:42Z

- [https://github.com/Mr-xn/CVE-2023-28432](https://github.com/Mr-xn/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/Mr-xn/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/Mr-xn/CVE-2023-28432.svg) 
2023-03-23T15:53:05Z

- [https://github.com/gobysec/CVE-2023-28432](https://github.com/gobysec/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/gobysec/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/gobysec/CVE-2023-28432.svg) 
2023-03-24T02:27:36Z

- [https://github.com/acheiii/CVE-2023-28432](https://github.com/acheiii/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/acheiii/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/acheiii/CVE-2023-28432.svg) 
2023-03-24T08:53:49Z

- [https://github.com/Cuerz/CVE-2023-28432](https://github.com/Cuerz/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/Cuerz/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/Cuerz/CVE-2023-28432.svg) 
2023-03-29T01:40:42Z

- [https://github.com/bingtangbanli/VulnerabilityTools](https://github.com/bingtangbanli/VulnerabilityTools) :  
![starts](https://img.shields.io/github/stars/bingtangbanli/VulnerabilityTools.svg) 
![forks](https://img.shields.io/github/forks/bingtangbanli/VulnerabilityTools.svg) 
2023-08-31T06:46:17Z

- [https://github.com/Okaytc/minio_unauth_check](https://github.com/Okaytc/minio_unauth_check) :  
![starts](https://img.shields.io/github/stars/Okaytc/minio_unauth_check.svg) 
![forks](https://img.shields.io/github/forks/Okaytc/minio_unauth_check.svg) 
2023-03-24T06:31:37Z

- [https://github.com/yTxZx/CVE-2023-28432](https://github.com/yTxZx/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/yTxZx/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/yTxZx/CVE-2023-28432.svg) 
2023-10-20T10:26:05Z

- [https://github.com/Chocapikk/CVE-2023-28432](https://github.com/Chocapikk/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2023-28432.svg) 
2023-09-05T14:02:34Z

- [https://github.com/steponeerror/Cve-2023-28432-](https://github.com/steponeerror/Cve-2023-28432-) :  
![starts](https://img.shields.io/github/stars/steponeerror/Cve-2023-28432-.svg) 
![forks](https://img.shields.io/github/forks/steponeerror/Cve-2023-28432-.svg) 
2023-03-27T07:17:27Z

- [https://github.com/Romanc9/Gui-poc-test](https://github.com/Romanc9/Gui-poc-test) :  
![starts](https://img.shields.io/github/stars/Romanc9/Gui-poc-test.svg) 
![forks](https://img.shields.io/github/forks/Romanc9/Gui-poc-test.svg) 
2023-12-05T17:58:36Z

- [https://github.com/BitWiz4rd/CVE-2023-28432](https://github.com/BitWiz4rd/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/BitWiz4rd/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/BitWiz4rd/CVE-2023-28432.svg) 
2024-04-13T13:56:28Z

- [https://github.com/netuseradministrator/CVE-2023-28432](https://github.com/netuseradministrator/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/netuseradministrator/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/netuseradministrator/CVE-2023-28432.svg) 
2024-01-07T15:20:56Z

- [https://github.com/C1ph3rX13/CVE-2023-28432](https://github.com/C1ph3rX13/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/C1ph3rX13/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/C1ph3rX13/CVE-2023-28432.svg) 
2023-12-25T09:41:34Z

- [https://github.com/LHXHL/Minio-CVE-2023-28432](https://github.com/LHXHL/Minio-CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/LHXHL/Minio-CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/LHXHL/Minio-CVE-2023-28432.svg) 
2023-04-06T12:52:02Z

- [https://github.com/TaroballzChen/CVE-2023-28432-metasploit-scanner](https://github.com/TaroballzChen/CVE-2023-28432-metasploit-scanner) :  
![starts](https://img.shields.io/github/stars/TaroballzChen/CVE-2023-28432-metasploit-scanner.svg) 
![forks](https://img.shields.io/github/forks/TaroballzChen/CVE-2023-28432-metasploit-scanner.svg) 
2023-05-27T15:35:55Z

- [https://github.com/unam4/CVE-2023-28432-minio_update_rce](https://github.com/unam4/CVE-2023-28432-minio_update_rce) :  
![starts](https://img.shields.io/github/stars/unam4/CVE-2023-28432-minio_update_rce.svg) 
![forks](https://img.shields.io/github/forks/unam4/CVE-2023-28432-minio_update_rce.svg) 
2023-11-26T18:36:57Z

- [https://github.com/xk-mt/CVE-2023-28432](https://github.com/xk-mt/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/xk-mt/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/xk-mt/CVE-2023-28432.svg) 
2024-01-15T08:35:51Z

- [https://github.com/bingtangbanli/CVE-2023-28432](https://github.com/bingtangbanli/CVE-2023-28432) :  
![starts](https://img.shields.io/github/stars/bingtangbanli/CVE-2023-28432.svg) 
![forks](https://img.shields.io/github/forks/bingtangbanli/CVE-2023-28432.svg) 
2023-08-26T15:30:00Z

- [https://github.com/h0ng10/CVE-2023-28432_docker](https://github.com/h0ng10/CVE-2023-28432_docker) :  
![starts](https://img.shields.io/github/stars/h0ng10/CVE-2023-28432_docker.svg) 
![forks](https://img.shields.io/github/forks/h0ng10/CVE-2023-28432_docker.svg) 
2023-04-10T04:18:23Z

- [https://github.com/CHINA-china/MinIO_CVE-2023-28432_EXP](https://github.com/CHINA-china/MinIO_CVE-2023-28432_EXP) :  
![starts](https://img.shields.io/github/stars/CHINA-china/MinIO_CVE-2023-28432_EXP.svg) 
![forks](https://img.shields.io/github/forks/CHINA-china/MinIO_CVE-2023-28432_EXP.svg) 
2023-04-13T08:50:11Z

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
2024-08-02T12:54:25Z

- [https://github.com/redboltsec/CVE-2023-27372-PoC](https://github.com/redboltsec/CVE-2023-27372-PoC) :  
![starts](https://img.shields.io/github/stars/redboltsec/CVE-2023-27372-PoC.svg) 
![forks](https://img.shields.io/github/forks/redboltsec/CVE-2023-27372-PoC.svg) 
2023-09-07T16:20:46Z

## CVE-2023-21563
 BitLocker Security Feature Bypass Vulnerability

- [https://github.com/Wack0/bitlocker-attacks](https://github.com/Wack0/bitlocker-attacks) :  
![starts](https://img.shields.io/github/stars/Wack0/bitlocker-attacks.svg) 
![forks](https://img.shields.io/github/forks/Wack0/bitlocker-attacks.svg) 
2023-08-18T10:45:49Z

- [https://github.com/andigandhi/bitpixie](https://github.com/andigandhi/bitpixie) :  
![starts](https://img.shields.io/github/stars/andigandhi/bitpixie.svg) 
![forks](https://img.shields.io/github/forks/andigandhi/bitpixie.svg) 
2025-02-07T14:17:17Z

## CVE-2022-30525
 A OS command injection vulnerability in the CGI program of Zyxel USG FLEX 100(W) firmware versions 5.00 through 5.21 Patch 1, USG FLEX 200 firmware versions 5.00 through 5.21 Patch 1, USG FLEX 500 firmware versions 5.00 through 5.21 Patch 1, USG FLEX 700 firmware versions 5.00 through 5.21 Patch 1, USG FLEX 50(W) firmware versions 5.10 through 5.21 Patch 1, USG20(W)-VPN firmware versions 5.10 through 5.21 Patch 1, ATP series firmware versions 5.10 through 5.21 Patch 1, VPN series firmware versions 4.60 through 5.21 Patch 1, which could allow an attacker to modify specific files and then execute some OS commands on a vulnerable device.

- [https://github.com/W01fh4cker/Serein](https://github.com/W01fh4cker/Serein) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/Serein.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/Serein.svg) 
2023-02-26T14:06:05Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/shuai06/CVE-2022-30525](https://github.com/shuai06/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/shuai06/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/shuai06/CVE-2022-30525.svg) 
2022-05-13T14:46:04Z

- [https://github.com/jbaines-r7/victorian_machinery](https://github.com/jbaines-r7/victorian_machinery) :  
![starts](https://img.shields.io/github/stars/jbaines-r7/victorian_machinery.svg) 
![forks](https://img.shields.io/github/forks/jbaines-r7/victorian_machinery.svg) 
2022-05-12T10:37:44Z

- [https://github.com/Henry4E36/CVE-2022-30525](https://github.com/Henry4E36/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/Henry4E36/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/Henry4E36/CVE-2022-30525.svg) 
2022-05-13T12:29:47Z

- [https://github.com/west9b/CVE-2022-30525](https://github.com/west9b/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/west9b/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/west9b/CVE-2022-30525.svg) 
2022-05-28T07:52:19Z

- [https://github.com/savior-only/CVE-2022-30525](https://github.com/savior-only/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/savior-only/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/savior-only/CVE-2022-30525.svg) 
2022-05-14T04:45:38Z

- [https://github.com/k0sf/CVE-2022-30525](https://github.com/k0sf/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/k0sf/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/k0sf/CVE-2022-30525.svg) 
2022-05-16T04:57:20Z

- [https://github.com/iveresk/cve-2022-30525](https://github.com/iveresk/cve-2022-30525) :  
![starts](https://img.shields.io/github/stars/iveresk/cve-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/iveresk/cve-2022-30525.svg) 
2022-05-24T15:06:23Z

- [https://github.com/cbk914/CVE-2022-30525_check](https://github.com/cbk914/CVE-2022-30525_check) :  
![starts](https://img.shields.io/github/stars/cbk914/CVE-2022-30525_check.svg) 
![forks](https://img.shields.io/github/forks/cbk914/CVE-2022-30525_check.svg) 
2023-01-15T20:06:36Z

- [https://github.com/Chocapikk/CVE-2022-30525-Reverse-Shell](https://github.com/Chocapikk/CVE-2022-30525-Reverse-Shell) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2022-30525-Reverse-Shell.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2022-30525-Reverse-Shell.svg) 
2022-05-19T11:29:16Z

- [https://github.com/ProngedFork/CVE-2022-30525](https://github.com/ProngedFork/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/ProngedFork/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/ProngedFork/CVE-2022-30525.svg) 
2022-06-13T21:22:41Z

- [https://github.com/superzerosec/CVE-2022-30525](https://github.com/superzerosec/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/superzerosec/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/superzerosec/CVE-2022-30525.svg) 
2022-05-17T23:42:09Z

- [https://github.com/furkanzengin/CVE-2022-30525](https://github.com/furkanzengin/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/furkanzengin/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/furkanzengin/CVE-2022-30525.svg) 
2022-06-12T19:27:56Z

- [https://github.com/arajsingh-infosec/CVE-2022-30525_Exploit](https://github.com/arajsingh-infosec/CVE-2022-30525_Exploit) :  
![starts](https://img.shields.io/github/stars/arajsingh-infosec/CVE-2022-30525_Exploit.svg) 
![forks](https://img.shields.io/github/forks/arajsingh-infosec/CVE-2022-30525_Exploit.svg) 
2024-02-27T03:33:00Z

- [https://github.com/160Team/CVE-2022-30525](https://github.com/160Team/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/160Team/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/160Team/CVE-2022-30525.svg) 
2022-05-19T12:09:43Z

- [https://github.com/M4fiaB0y/CVE-2022-30525](https://github.com/M4fiaB0y/CVE-2022-30525) :  
![starts](https://img.shields.io/github/stars/M4fiaB0y/CVE-2022-30525.svg) 
![forks](https://img.shields.io/github/forks/M4fiaB0y/CVE-2022-30525.svg) 
2022-05-15T07:31:40Z

## CVE-2022-30190
 A remote code execution vulnerability exists when MSDT is called using the URL protocol from a calling application such as Word. An attacker who successfully exploits this vulnerability can run arbitrary code with the privileges of the calling application. The attacker can then install programs, view, change, or delete data, or create new accounts in the context allowed by the users rights.Please see theMSRC Blog Entry for important information about steps you can take to protect your system from this vulnerability.

- [https://github.com/komomon/CVE-2022-30190-follina-Office-MSDT-Fixed](https://github.com/komomon/CVE-2022-30190-follina-Office-MSDT-Fixed) :  
![starts](https://img.shields.io/github/stars/komomon/CVE-2022-30190-follina-Office-MSDT-Fixed.svg) 
![forks](https://img.shields.io/github/forks/komomon/CVE-2022-30190-follina-Office-MSDT-Fixed.svg) 
2023-04-13T16:46:26Z

- [https://github.com/JMousqueton/PoC-CVE-2022-30190](https://github.com/JMousqueton/PoC-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/JMousqueton/PoC-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/JMousqueton/PoC-CVE-2022-30190.svg) 
2022-06-05T21:06:13Z

- [https://github.com/onecloudemoji/CVE-2022-30190](https://github.com/onecloudemoji/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/onecloudemoji/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/onecloudemoji/CVE-2022-30190.svg) 
2022-05-31T09:35:37Z

- [https://github.com/doocop/CVE-2022-30190](https://github.com/doocop/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/doocop/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/doocop/CVE-2022-30190.svg) 
2022-05-31T12:27:50Z

- [https://github.com/archanchoudhury/MSDT_CVE-2022-30190](https://github.com/archanchoudhury/MSDT_CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/archanchoudhury/MSDT_CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/archanchoudhury/MSDT_CVE-2022-30190.svg) 
2022-06-02T09:12:54Z

- [https://github.com/Malwareman007/Deathnote](https://github.com/Malwareman007/Deathnote) :  
![starts](https://img.shields.io/github/stars/Malwareman007/Deathnote.svg) 
![forks](https://img.shields.io/github/forks/Malwareman007/Deathnote.svg) 
2022-10-06T14:49:56Z

- [https://github.com/MalwareTech/FollinaExtractor](https://github.com/MalwareTech/FollinaExtractor) :  
![starts](https://img.shields.io/github/stars/MalwareTech/FollinaExtractor.svg) 
![forks](https://img.shields.io/github/forks/MalwareTech/FollinaExtractor.svg) 
2022-06-15T02:24:00Z

- [https://github.com/Hrishikesh7665/Follina_Exploiter_CLI](https://github.com/Hrishikesh7665/Follina_Exploiter_CLI) :  
![starts](https://img.shields.io/github/stars/Hrishikesh7665/Follina_Exploiter_CLI.svg) 
![forks](https://img.shields.io/github/forks/Hrishikesh7665/Follina_Exploiter_CLI.svg) 
2022-06-16T07:28:13Z

- [https://github.com/ErrorNoInternet/FollinaScanner](https://github.com/ErrorNoInternet/FollinaScanner) :  
![starts](https://img.shields.io/github/stars/ErrorNoInternet/FollinaScanner.svg) 
![forks](https://img.shields.io/github/forks/ErrorNoInternet/FollinaScanner.svg) 
2022-09-13T10:05:02Z

- [https://github.com/Noxtal/follina](https://github.com/Noxtal/follina) :  
![starts](https://img.shields.io/github/stars/Noxtal/follina.svg) 
![forks](https://img.shields.io/github/forks/Noxtal/follina.svg) 
2022-08-06T01:04:51Z

- [https://github.com/0xflagplz/MS-MSDT-Office-RCE-Follina](https://github.com/0xflagplz/MS-MSDT-Office-RCE-Follina) :  
![starts](https://img.shields.io/github/stars/0xflagplz/MS-MSDT-Office-RCE-Follina.svg) 
![forks](https://img.shields.io/github/forks/0xflagplz/MS-MSDT-Office-RCE-Follina.svg) 
2022-06-03T08:14:10Z

- [https://github.com/dwisiswant0/gollina](https://github.com/dwisiswant0/gollina) :  
![starts](https://img.shields.io/github/stars/dwisiswant0/gollina.svg) 
![forks](https://img.shields.io/github/forks/dwisiswant0/gollina.svg) 
2022-06-01T09:31:58Z

- [https://github.com/drgreenthumb93/CVE-2022-30190-follina](https://github.com/drgreenthumb93/CVE-2022-30190-follina) :  
![starts](https://img.shields.io/github/stars/drgreenthumb93/CVE-2022-30190-follina.svg) 
![forks](https://img.shields.io/github/forks/drgreenthumb93/CVE-2022-30190-follina.svg) 
2023-04-20T20:34:05Z

- [https://github.com/Gra3s/CVE-2022-30190_EXP_PowerPoint](https://github.com/Gra3s/CVE-2022-30190_EXP_PowerPoint) :  
![starts](https://img.shields.io/github/stars/Gra3s/CVE-2022-30190_EXP_PowerPoint.svg) 
![forks](https://img.shields.io/github/forks/Gra3s/CVE-2022-30190_EXP_PowerPoint.svg) 
2023-03-23T03:18:46Z

- [https://github.com/0xAbbarhSF/FollinaXploit](https://github.com/0xAbbarhSF/FollinaXploit) :  
![starts](https://img.shields.io/github/stars/0xAbbarhSF/FollinaXploit.svg) 
![forks](https://img.shields.io/github/forks/0xAbbarhSF/FollinaXploit.svg) 
2022-11-19T18:41:57Z

- [https://github.com/aminetitrofine/CVE-2022-30190](https://github.com/aminetitrofine/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/aminetitrofine/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/aminetitrofine/CVE-2022-30190.svg) 
2023-05-14T13:45:18Z

- [https://github.com/sudoaza/CVE-2022-30190](https://github.com/sudoaza/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/sudoaza/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/sudoaza/CVE-2022-30190.svg) 
2022-06-01T23:30:26Z

- [https://github.com/PaddlingCode/cve-2022-30190](https://github.com/PaddlingCode/cve-2022-30190) :  
![starts](https://img.shields.io/github/stars/PaddlingCode/cve-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/PaddlingCode/cve-2022-30190.svg) 
2022-05-31T23:43:02Z

- [https://github.com/DerZiad/CVE-2022-30190](https://github.com/DerZiad/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/DerZiad/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/DerZiad/CVE-2022-30190.svg) 
2023-07-25T07:47:33Z

- [https://github.com/AbdulRKB/Follina](https://github.com/AbdulRKB/Follina) :  
![starts](https://img.shields.io/github/stars/AbdulRKB/Follina.svg) 
![forks](https://img.shields.io/github/forks/AbdulRKB/Follina.svg) 
2024-02-09T17:18:42Z

- [https://github.com/ItsNee/Follina-CVE-2022-30190-POC](https://github.com/ItsNee/Follina-CVE-2022-30190-POC) :  
![starts](https://img.shields.io/github/stars/ItsNee/Follina-CVE-2022-30190-POC.svg) 
![forks](https://img.shields.io/github/forks/ItsNee/Follina-CVE-2022-30190-POC.svg) 
2022-07-04T13:27:13Z

- [https://github.com/Cosmo121/Follina-Remediation](https://github.com/Cosmo121/Follina-Remediation) :  
![starts](https://img.shields.io/github/stars/Cosmo121/Follina-Remediation.svg) 
![forks](https://img.shields.io/github/forks/Cosmo121/Follina-Remediation.svg) 
2022-10-08T23:22:12Z

- [https://github.com/sentinelblue/CVE-2022-30190](https://github.com/sentinelblue/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/sentinelblue/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/sentinelblue/CVE-2022-30190.svg) 
2022-06-08T15:18:45Z

- [https://github.com/dsibilio/follina-spring](https://github.com/dsibilio/follina-spring) :  
![starts](https://img.shields.io/github/stars/dsibilio/follina-spring.svg) 
![forks](https://img.shields.io/github/forks/dsibilio/follina-spring.svg) 
2022-06-14T20:30:12Z

- [https://github.com/SrikeshMaharaj/CVE-2022-30190](https://github.com/SrikeshMaharaj/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/SrikeshMaharaj/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/SrikeshMaharaj/CVE-2022-30190.svg) 
2022-06-03T08:04:36Z

- [https://github.com/rouben/CVE-2022-30190-NSIS](https://github.com/rouben/CVE-2022-30190-NSIS) :  
![starts](https://img.shields.io/github/stars/rouben/CVE-2022-30190-NSIS.svg) 
![forks](https://img.shields.io/github/forks/rouben/CVE-2022-30190-NSIS.svg) 
2022-06-01T22:23:34Z

- [https://github.com/swaiist/CVE-2022-30190-Fix](https://github.com/swaiist/CVE-2022-30190-Fix) :  
![starts](https://img.shields.io/github/stars/swaiist/CVE-2022-30190-Fix.svg) 
![forks](https://img.shields.io/github/forks/swaiist/CVE-2022-30190-Fix.svg) 
2022-12-16T15:09:34Z

- [https://github.com/EkamSinghWalia/Follina-MSDT-Vulnerability-CVE-2022-30190-](https://github.com/EkamSinghWalia/Follina-MSDT-Vulnerability-CVE-2022-30190-) :  
![starts](https://img.shields.io/github/stars/EkamSinghWalia/Follina-MSDT-Vulnerability-CVE-2022-30190-.svg) 
![forks](https://img.shields.io/github/forks/EkamSinghWalia/Follina-MSDT-Vulnerability-CVE-2022-30190-.svg) 
2022-07-22T15:00:30Z

- [https://github.com/gamingwithevets/msdt-disable](https://github.com/gamingwithevets/msdt-disable) :  
![starts](https://img.shields.io/github/stars/gamingwithevets/msdt-disable.svg) 
![forks](https://img.shields.io/github/forks/gamingwithevets/msdt-disable.svg) 
2022-06-26T10:10:37Z

- [https://github.com/arozx/CVE-2022-30190](https://github.com/arozx/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/arozx/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/arozx/CVE-2022-30190.svg) 
2022-11-01T16:53:17Z

- [https://github.com/winstxnhdw/CVE-2022-30190](https://github.com/winstxnhdw/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/winstxnhdw/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/winstxnhdw/CVE-2022-30190.svg) 
2024-03-01T16:26:36Z

- [https://github.com/gyaansastra/CVE-2022-30190](https://github.com/gyaansastra/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/gyaansastra/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/gyaansastra/CVE-2022-30190.svg) 
2022-06-02T13:00:33Z

- [https://github.com/amitniz/follina_cve_2022-30190](https://github.com/amitniz/follina_cve_2022-30190) :  
![starts](https://img.shields.io/github/stars/amitniz/follina_cve_2022-30190.svg) 
![forks](https://img.shields.io/github/forks/amitniz/follina_cve_2022-30190.svg) 
2022-06-11T19:12:53Z

- [https://github.com/suenerve/CVE-2022-30190-Follina-Patch](https://github.com/suenerve/CVE-2022-30190-Follina-Patch) :  
![starts](https://img.shields.io/github/stars/suenerve/CVE-2022-30190-Follina-Patch.svg) 
![forks](https://img.shields.io/github/forks/suenerve/CVE-2022-30190-Follina-Patch.svg) 
2022-06-05T12:37:12Z

- [https://github.com/Zitchev/go_follina](https://github.com/Zitchev/go_follina) :  
![starts](https://img.shields.io/github/stars/Zitchev/go_follina.svg) 
![forks](https://img.shields.io/github/forks/Zitchev/go_follina.svg) 
2023-02-21T19:21:48Z

- [https://github.com/SonicWave21/Follina-CVE-2022-30190-Unofficial-patch](https://github.com/SonicWave21/Follina-CVE-2022-30190-Unofficial-patch) :  
![starts](https://img.shields.io/github/stars/SonicWave21/Follina-CVE-2022-30190-Unofficial-patch.svg) 
![forks](https://img.shields.io/github/forks/SonicWave21/Follina-CVE-2022-30190-Unofficial-patch.svg) 
2022-06-14T13:32:17Z

- [https://github.com/jeffreybxu/five-nights-at-follina-s](https://github.com/jeffreybxu/five-nights-at-follina-s) :  
![starts](https://img.shields.io/github/stars/jeffreybxu/five-nights-at-follina-s.svg) 
![forks](https://img.shields.io/github/forks/jeffreybxu/five-nights-at-follina-s.svg) 
2022-08-05T16:16:13Z

- [https://github.com/Muhammad-Ali007/Follina_MSDT_CVE-2022-30190](https://github.com/Muhammad-Ali007/Follina_MSDT_CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/Muhammad-Ali007/Follina_MSDT_CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/Muhammad-Ali007/Follina_MSDT_CVE-2022-30190.svg) 
2023-07-18T20:13:14Z

- [https://github.com/Jump-Wang-111/AmzWord](https://github.com/Jump-Wang-111/AmzWord) :  
![starts](https://img.shields.io/github/stars/Jump-Wang-111/AmzWord.svg) 
![forks](https://img.shields.io/github/forks/Jump-Wang-111/AmzWord.svg) 
2023-11-28T10:16:25Z

- [https://github.com/melting0256/Enterprise-Cybersecurity](https://github.com/melting0256/Enterprise-Cybersecurity) :  
![starts](https://img.shields.io/github/stars/melting0256/Enterprise-Cybersecurity.svg) 
![forks](https://img.shields.io/github/forks/melting0256/Enterprise-Cybersecurity.svg) 
2022-12-29T13:08:39Z

- [https://github.com/michealadams30/Cve-2022-30190](https://github.com/michealadams30/Cve-2022-30190) :  
![starts](https://img.shields.io/github/stars/michealadams30/Cve-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/michealadams30/Cve-2022-30190.svg) 
2022-12-26T10:32:31Z

- [https://github.com/hycheng15/CVE-2022-30190](https://github.com/hycheng15/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/hycheng15/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/hycheng15/CVE-2022-30190.svg) 
2023-11-14T10:19:33Z

- [https://github.com/ITMarcin2211/CVE-2022-30190](https://github.com/ITMarcin2211/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/ITMarcin2211/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/ITMarcin2211/CVE-2022-30190.svg) 
2022-06-02T07:04:59Z

- [https://github.com/rickhenderson/cve-2022-30190](https://github.com/rickhenderson/cve-2022-30190) :  
![starts](https://img.shields.io/github/stars/rickhenderson/cve-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/rickhenderson/cve-2022-30190.svg) 
2022-05-31T15:59:25Z

- [https://github.com/joshuavanderpoll/CVE-2022-30190](https://github.com/joshuavanderpoll/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/joshuavanderpoll/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/joshuavanderpoll/CVE-2022-30190.svg) 
2022-06-07T10:10:39Z

- [https://github.com/alien-keric/CVE-2022-30190](https://github.com/alien-keric/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/alien-keric/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/alien-keric/CVE-2022-30190.svg) 
2024-04-09T22:41:53Z

- [https://github.com/ToxicEnvelope/FOLLINA-CVE-2022-30190](https://github.com/ToxicEnvelope/FOLLINA-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/ToxicEnvelope/FOLLINA-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/ToxicEnvelope/FOLLINA-CVE-2022-30190.svg) 
2023-08-27T09:39:26Z

- [https://github.com/derco0n/mitigate-folina](https://github.com/derco0n/mitigate-folina) :  
![starts](https://img.shields.io/github/stars/derco0n/mitigate-folina.svg) 
![forks](https://img.shields.io/github/forks/derco0n/mitigate-folina.svg) 
2022-06-08T05:57:31Z

- [https://github.com/IamVSM/msdt-follina](https://github.com/IamVSM/msdt-follina) :  
![starts](https://img.shields.io/github/stars/IamVSM/msdt-follina.svg) 
![forks](https://img.shields.io/github/forks/IamVSM/msdt-follina.svg) 
2022-06-06T09:17:28Z

- [https://github.com/b401/Clickstudio-compromised-certificate](https://github.com/b401/Clickstudio-compromised-certificate) :  
![starts](https://img.shields.io/github/stars/b401/Clickstudio-compromised-certificate.svg) 
![forks](https://img.shields.io/github/forks/b401/Clickstudio-compromised-certificate.svg) 
2022-06-09T10:06:41Z

- [https://github.com/Nyx2022/Follina-CVE-2022-30190-Sample](https://github.com/Nyx2022/Follina-CVE-2022-30190-Sample) :  
![starts](https://img.shields.io/github/stars/Nyx2022/Follina-CVE-2022-30190-Sample.svg) 
![forks](https://img.shields.io/github/forks/Nyx2022/Follina-CVE-2022-30190-Sample.svg) 
2022-12-07T17:58:20Z

- [https://github.com/zkl21hoang/msdt-follina-office-rce](https://github.com/zkl21hoang/msdt-follina-office-rce) :  
![starts](https://img.shields.io/github/stars/zkl21hoang/msdt-follina-office-rce.svg) 
![forks](https://img.shields.io/github/forks/zkl21hoang/msdt-follina-office-rce.svg) 
2022-06-02T08:20:54Z

- [https://github.com/k508/CVE-2022-30190](https://github.com/k508/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/k508/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/k508/CVE-2022-30190.svg) 
2022-06-10T00:33:19Z

- [https://github.com/Potato-9257/CVE-2022-30190_page](https://github.com/Potato-9257/CVE-2022-30190_page) :  
![starts](https://img.shields.io/github/stars/Potato-9257/CVE-2022-30190_page.svg) 
![forks](https://img.shields.io/github/forks/Potato-9257/CVE-2022-30190_page.svg) 
2025-02-07T00:37:24Z

- [https://github.com/yrkuo/CVE-2022-30190](https://github.com/yrkuo/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/yrkuo/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/yrkuo/CVE-2022-30190.svg) 
2023-02-14T01:29:20Z

- [https://github.com/droidrzrlover/CVE-2022-30190](https://github.com/droidrzrlover/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/droidrzrlover/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/droidrzrlover/CVE-2022-30190.svg) 
2022-06-03T05:53:02Z

- [https://github.com/ernestak/CVE-2022-30190](https://github.com/ernestak/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/ernestak/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/ernestak/CVE-2022-30190.svg) 
2022-06-14T08:44:15Z

- [https://github.com/hscorpion/CVE-2022-30190](https://github.com/hscorpion/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/hscorpion/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/hscorpion/CVE-2022-30190.svg) 
2022-06-06T17:08:13Z

- [https://github.com/XxToxicScriptxX/CVE-2022-30190](https://github.com/XxToxicScriptxX/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/XxToxicScriptxX/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/XxToxicScriptxX/CVE-2022-30190.svg) 
2022-06-13T21:36:37Z

- [https://github.com/2867a0/CVE-2022-30190](https://github.com/2867a0/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/2867a0/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/2867a0/CVE-2022-30190.svg) 
2022-05-31T08:43:28Z

- [https://github.com/rayorole/CVE-2022-30190](https://github.com/rayorole/CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/rayorole/CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/rayorole/CVE-2022-30190.svg) 
2022-06-01T21:36:44Z

- [https://github.com/abhirules27/Follina](https://github.com/abhirules27/Follina) :  
![starts](https://img.shields.io/github/stars/abhirules27/Follina.svg) 
![forks](https://img.shields.io/github/forks/abhirules27/Follina.svg) 
2022-06-07T17:14:09Z

- [https://github.com/ethicalblue/Follina-CVE-2022-30190-Sample](https://github.com/ethicalblue/Follina-CVE-2022-30190-Sample) :  
![starts](https://img.shields.io/github/stars/ethicalblue/Follina-CVE-2022-30190-Sample.svg) 
![forks](https://img.shields.io/github/forks/ethicalblue/Follina-CVE-2022-30190-Sample.svg) 
2024-07-20T18:23:38Z

- [https://github.com/skitkat/CVE-2022-30190-POC](https://github.com/skitkat/CVE-2022-30190-POC) :  
![starts](https://img.shields.io/github/stars/skitkat/CVE-2022-30190-POC.svg) 
![forks](https://img.shields.io/github/forks/skitkat/CVE-2022-30190-POC.svg) 
2024-07-08T14:49:29Z

- [https://github.com/kdk2933/msdt-CVE-2022-30190](https://github.com/kdk2933/msdt-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/kdk2933/msdt-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/kdk2933/msdt-CVE-2022-30190.svg) 
2022-05-31T17:54:21Z

- [https://github.com/mitespsoc/CVE-2022-30190-POC](https://github.com/mitespsoc/CVE-2022-30190-POC) :  
![starts](https://img.shields.io/github/stars/mitespsoc/CVE-2022-30190-POC.svg) 
![forks](https://img.shields.io/github/forks/mitespsoc/CVE-2022-30190-POC.svg) 
2022-06-01T15:41:26Z

- [https://github.com/Cerebrovinny/follina-CVE-2022-30190](https://github.com/Cerebrovinny/follina-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/Cerebrovinny/follina-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/Cerebrovinny/follina-CVE-2022-30190.svg) 
2022-06-16T00:04:16Z

- [https://github.com/notherealhazard/follina-CVE-2022-30190](https://github.com/notherealhazard/follina-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/notherealhazard/follina-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/notherealhazard/follina-CVE-2022-30190.svg) 
2022-06-15T11:01:19Z

- [https://github.com/hilt86/cve-2022-30190-mitigate](https://github.com/hilt86/cve-2022-30190-mitigate) :  
![starts](https://img.shields.io/github/stars/hilt86/cve-2022-30190-mitigate.svg) 
![forks](https://img.shields.io/github/forks/hilt86/cve-2022-30190-mitigate.svg) 
2022-06-03T06:55:10Z

- [https://github.com/mattjmillner/CVE-Smackdown](https://github.com/mattjmillner/CVE-Smackdown) :  
![starts](https://img.shields.io/github/stars/mattjmillner/CVE-Smackdown.svg) 
![forks](https://img.shields.io/github/forks/mattjmillner/CVE-Smackdown.svg) 
2022-11-10T18:59:57Z

- [https://github.com/SrCroqueta/CVE-2022-30190_Temporary_Fix](https://github.com/SrCroqueta/CVE-2022-30190_Temporary_Fix) :  
![starts](https://img.shields.io/github/stars/SrCroqueta/CVE-2022-30190_Temporary_Fix.svg) 
![forks](https://img.shields.io/github/forks/SrCroqueta/CVE-2022-30190_Temporary_Fix.svg) 
2022-06-26T17:27:34Z

- [https://github.com/Imeneallouche/Follina-attack-CVE-2022-30190-](https://github.com/Imeneallouche/Follina-attack-CVE-2022-30190-) :  
![starts](https://img.shields.io/github/stars/Imeneallouche/Follina-attack-CVE-2022-30190-.svg) 
![forks](https://img.shields.io/github/forks/Imeneallouche/Follina-attack-CVE-2022-30190-.svg) 
2022-10-06T21:22:48Z

- [https://github.com/aymankhder/MSDT_CVE-2022-30190-follina-](https://github.com/aymankhder/MSDT_CVE-2022-30190-follina-) :  
![starts](https://img.shields.io/github/stars/aymankhder/MSDT_CVE-2022-30190-follina-.svg) 
![forks](https://img.shields.io/github/forks/aymankhder/MSDT_CVE-2022-30190-follina-.svg) 
2022-05-31T18:51:30Z

- [https://github.com/sentrium-security/Follina-Workaround-CVE-2022-30190](https://github.com/sentrium-security/Follina-Workaround-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/sentrium-security/Follina-Workaround-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/sentrium-security/Follina-Workaround-CVE-2022-30190.svg) 
2022-07-14T16:18:28Z

- [https://github.com/ernestak/Sigma-Rule-for-CVE-2022-30190](https://github.com/ernestak/Sigma-Rule-for-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/ernestak/Sigma-Rule-for-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/ernestak/Sigma-Rule-for-CVE-2022-30190.svg) 
2022-06-14T09:27:50Z

- [https://github.com/WesyHub/CVE-2022-30190---Follina---Poc-Exploit](https://github.com/WesyHub/CVE-2022-30190---Follina---Poc-Exploit) :  
![starts](https://img.shields.io/github/stars/WesyHub/CVE-2022-30190---Follina---Poc-Exploit.svg) 
![forks](https://img.shields.io/github/forks/WesyHub/CVE-2022-30190---Follina---Poc-Exploit.svg) 
2022-06-03T06:49:34Z

- [https://github.com/castlesmadeofsand/ms-msdt-vulnerability-pdq-package](https://github.com/castlesmadeofsand/ms-msdt-vulnerability-pdq-package) :  
![starts](https://img.shields.io/github/stars/castlesmadeofsand/ms-msdt-vulnerability-pdq-package.svg) 
![forks](https://img.shields.io/github/forks/castlesmadeofsand/ms-msdt-vulnerability-pdq-package.svg) 
2022-06-08T21:04:55Z

- [https://github.com/SrCroqueta/CVE-2022-30190_Temporary_Fix_Source_Code](https://github.com/SrCroqueta/CVE-2022-30190_Temporary_Fix_Source_Code) :  
![starts](https://img.shields.io/github/stars/SrCroqueta/CVE-2022-30190_Temporary_Fix_Source_Code.svg) 
![forks](https://img.shields.io/github/forks/SrCroqueta/CVE-2022-30190_Temporary_Fix_Source_Code.svg) 
2022-06-21T17:29:25Z

- [https://github.com/Vaisakhkm2625/MSDT-0-Day-CVE-2022-30190-Poc](https://github.com/Vaisakhkm2625/MSDT-0-Day-CVE-2022-30190-Poc) :  
![starts](https://img.shields.io/github/stars/Vaisakhkm2625/MSDT-0-Day-CVE-2022-30190-Poc.svg) 
![forks](https://img.shields.io/github/forks/Vaisakhkm2625/MSDT-0-Day-CVE-2022-30190-Poc.svg) 
2022-06-01T16:48:37Z

- [https://github.com/DOV3Y/CVE-2022-30190-ASR-Senintel-Process-Pickup](https://github.com/DOV3Y/CVE-2022-30190-ASR-Senintel-Process-Pickup) :  
![starts](https://img.shields.io/github/stars/DOV3Y/CVE-2022-30190-ASR-Senintel-Process-Pickup.svg) 
![forks](https://img.shields.io/github/forks/DOV3Y/CVE-2022-30190-ASR-Senintel-Process-Pickup.svg) 
2022-05-31T16:15:51Z

- [https://github.com/Abdibimantara/CVE-2022-30190-Analysis-With-LetsDefends-Lab](https://github.com/Abdibimantara/CVE-2022-30190-Analysis-With-LetsDefends-Lab) :  
![starts](https://img.shields.io/github/stars/Abdibimantara/CVE-2022-30190-Analysis-With-LetsDefends-Lab.svg) 
![forks](https://img.shields.io/github/forks/Abdibimantara/CVE-2022-30190-Analysis-With-LetsDefends-Lab.svg) 
2022-06-10T16:37:46Z

- [https://github.com/ImproveCybersecurityJaro/2022_PoC-MSDT-Follina-CVE-2022-30190](https://github.com/ImproveCybersecurityJaro/2022_PoC-MSDT-Follina-CVE-2022-30190) :  
![starts](https://img.shields.io/github/stars/ImproveCybersecurityJaro/2022_PoC-MSDT-Follina-CVE-2022-30190.svg) 
![forks](https://img.shields.io/github/forks/ImproveCybersecurityJaro/2022_PoC-MSDT-Follina-CVE-2022-30190.svg) 
2022-06-01T23:30:01Z

- [https://github.com/tej7gandhi/CVE-2022-30190-Zero-Click-Zero-Day-in-msdt](https://github.com/tej7gandhi/CVE-2022-30190-Zero-Click-Zero-Day-in-msdt) :  
![starts](https://img.shields.io/github/stars/tej7gandhi/CVE-2022-30190-Zero-Click-Zero-Day-in-msdt.svg) 
![forks](https://img.shields.io/github/forks/tej7gandhi/CVE-2022-30190-Zero-Click-Zero-Day-in-msdt.svg) 
2022-06-05T08:54:27Z

- [https://github.com/nanaao/PicusSecurity4.Week.Repo](https://github.com/nanaao/PicusSecurity4.Week.Repo) :  
![starts](https://img.shields.io/github/stars/nanaao/PicusSecurity4.Week.Repo.svg) 
![forks](https://img.shields.io/github/forks/nanaao/PicusSecurity4.Week.Repo.svg) 
2022-06-12T20:45:42Z

- [https://github.com/shri142/ZipScan](https://github.com/shri142/ZipScan) :  
![starts](https://img.shields.io/github/stars/shri142/ZipScan.svg) 
![forks](https://img.shields.io/github/forks/shri142/ZipScan.svg) 
2024-02-24T17:59:25Z

- [https://github.com/Rojacur/FollinaPatcherCLI](https://github.com/Rojacur/FollinaPatcherCLI) :  
![starts](https://img.shields.io/github/stars/Rojacur/FollinaPatcherCLI.svg) 
![forks](https://img.shields.io/github/forks/Rojacur/FollinaPatcherCLI.svg) 
2022-06-07T11:09:03Z

- [https://github.com/maxgestic/Follina-Generator](https://github.com/maxgestic/Follina-Generator) :  
![starts](https://img.shields.io/github/stars/maxgestic/Follina-Generator.svg) 
![forks](https://img.shields.io/github/forks/maxgestic/Follina-Generator.svg) 
2022-07-12T13:42:59Z

## CVE-2022-29464
 Certain WSO2 products allow unrestricted file upload with resultant remote code execution. The attacker must use a /fileupload endpoint with a Content-Disposition directory traversal sequence to reach a directory under the web root, such as a ../../../../repository/deployment/server/webapps directory. This affects WSO2 API Manager 2.2.0 up to 4.0.0, WSO2 Identity Server 5.2.0 up to 5.11.0, WSO2 Identity Server Analytics 5.4.0, 5.4.1, 5.5.0 and 5.6.0, WSO2 Identity Server as Key Manager 5.3.0 up to 5.11.0, WSO2 Enterprise Integrator 6.2.0 up to 6.6.0, WSO2 Open Banking AM 1.4.0 up to 2.0.0 and WSO2 Open Banking KM 1.4.0, up to 2.0.0.

- [https://github.com/W01fh4cker/Serein](https://github.com/W01fh4cker/Serein) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/Serein.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/Serein.svg) 
2023-02-26T14:06:05Z

- [https://github.com/hakivvi/CVE-2022-29464](https://github.com/hakivvi/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/hakivvi/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/hakivvi/CVE-2022-29464.svg) 
2022-04-27T05:52:43Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/W01fh4cker/Serein_Linux](https://github.com/W01fh4cker/Serein_Linux) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/Serein_Linux.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/Serein_Linux.svg) 
2022-07-07T03:24:07Z

- [https://github.com/oppsec/WSOB](https://github.com/oppsec/WSOB) :  
![starts](https://img.shields.io/github/stars/oppsec/WSOB.svg) 
![forks](https://img.shields.io/github/forks/oppsec/WSOB.svg) 
2023-05-23T03:42:31Z

- [https://github.com/Inplex-sys/CVE-2022-29464-loader](https://github.com/Inplex-sys/CVE-2022-29464-loader) :  
![starts](https://img.shields.io/github/stars/Inplex-sys/CVE-2022-29464-loader.svg) 
![forks](https://img.shields.io/github/forks/Inplex-sys/CVE-2022-29464-loader.svg) 
2022-08-08T15:31:54Z

- [https://github.com/gbrsh/CVE-2022-29464](https://github.com/gbrsh/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/gbrsh/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/gbrsh/CVE-2022-29464.svg) 
2022-11-14T18:24:56Z

- [https://github.com/ThatNotEasy/CVE-2022-29464](https://github.com/ThatNotEasy/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/ThatNotEasy/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/ThatNotEasy/CVE-2022-29464.svg) 
2023-07-24T22:21:30Z

- [https://github.com/Lidong-io/cve-2022-29464](https://github.com/Lidong-io/cve-2022-29464) :  
![starts](https://img.shields.io/github/stars/Lidong-io/cve-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/Lidong-io/cve-2022-29464.svg) 
2022-04-22T02:09:42Z

- [https://github.com/r4x0r1337/-CVE-2022-29464](https://github.com/r4x0r1337/-CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/r4x0r1337/-CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/r4x0r1337/-CVE-2022-29464.svg) 
2023-02-28T08:57:49Z

- [https://github.com/jimidk/Better-CVE-2022-29464](https://github.com/jimidk/Better-CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/jimidk/Better-CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/jimidk/Better-CVE-2022-29464.svg) 
2022-06-04T17:55:28Z

- [https://github.com/gpiechnik2/nmap-CVE-2022-29464](https://github.com/gpiechnik2/nmap-CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/gpiechnik2/nmap-CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/gpiechnik2/nmap-CVE-2022-29464.svg) 
2022-04-22T22:38:25Z

- [https://github.com/hupe1980/CVE-2022-29464](https://github.com/hupe1980/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/hupe1980/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/hupe1980/CVE-2022-29464.svg) 
2022-09-25T07:58:52Z

- [https://github.com/hev0x/CVE-2022-29464](https://github.com/hev0x/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/hev0x/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/hev0x/CVE-2022-29464.svg) 
2022-04-28T05:18:56Z

- [https://github.com/Chocapikk/CVE-2022-29464](https://github.com/Chocapikk/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2022-29464.svg) 
2022-06-01T03:29:40Z

- [https://github.com/superzerosec/CVE-2022-29464](https://github.com/superzerosec/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/superzerosec/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/superzerosec/CVE-2022-29464.svg) 
2022-04-30T16:44:39Z

- [https://github.com/mr-r3bot/WSO2-CVE-2022-29464](https://github.com/mr-r3bot/WSO2-CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/mr-r3bot/WSO2-CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/mr-r3bot/WSO2-CVE-2022-29464.svg) 
2022-04-26T08:36:29Z

- [https://github.com/tufanturhan/wso2-rce-cve-2022-29464](https://github.com/tufanturhan/wso2-rce-cve-2022-29464) :  
![starts](https://img.shields.io/github/stars/tufanturhan/wso2-rce-cve-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/tufanturhan/wso2-rce-cve-2022-29464.svg) 
2022-04-21T06:48:47Z

- [https://github.com/amit-pathak009/CVE-2022-29464-mass](https://github.com/amit-pathak009/CVE-2022-29464-mass) :  
![starts](https://img.shields.io/github/stars/amit-pathak009/CVE-2022-29464-mass.svg) 
![forks](https://img.shields.io/github/forks/amit-pathak009/CVE-2022-29464-mass.svg) 
2022-05-29T19:16:06Z

- [https://github.com/Pasch0/WSO2RCE](https://github.com/Pasch0/WSO2RCE) :  
![starts](https://img.shields.io/github/stars/Pasch0/WSO2RCE.svg) 
![forks](https://img.shields.io/github/forks/Pasch0/WSO2RCE.svg) 
2023-11-29T17:37:16Z

- [https://github.com/LinJacck/CVE-2022-29464](https://github.com/LinJacck/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/LinJacck/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/LinJacck/CVE-2022-29464.svg) 
2022-05-07T03:31:16Z

- [https://github.com/0xAgun/CVE-2022-29464](https://github.com/0xAgun/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/0xAgun/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/0xAgun/CVE-2022-29464.svg) 
2022-04-22T22:15:20Z

- [https://github.com/Pushkarup/CVE-2022-29464](https://github.com/Pushkarup/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/Pushkarup/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/Pushkarup/CVE-2022-29464.svg) 
2023-10-25T03:54:41Z

- [https://github.com/axin2019/CVE-2022-29464](https://github.com/axin2019/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/axin2019/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/axin2019/CVE-2022-29464.svg) 
2022-05-05T06:06:47Z

- [https://github.com/badguy233/CVE-2022-29465](https://github.com/badguy233/CVE-2022-29465) :  
![starts](https://img.shields.io/github/stars/badguy233/CVE-2022-29465.svg) 
![forks](https://img.shields.io/github/forks/badguy233/CVE-2022-29465.svg) 
2022-04-30T05:10:35Z

- [https://github.com/g0dxing/CVE-2022-29464](https://github.com/g0dxing/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/g0dxing/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/g0dxing/CVE-2022-29464.svg) 
2022-06-28T01:11:02Z

- [https://github.com/devengpk/CVE-2022-29464](https://github.com/devengpk/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/devengpk/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/devengpk/CVE-2022-29464.svg) 
2022-12-18T08:07:23Z

- [https://github.com/lowkey0808/cve-2022-29464](https://github.com/lowkey0808/cve-2022-29464) :  
![starts](https://img.shields.io/github/stars/lowkey0808/cve-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/lowkey0808/cve-2022-29464.svg) 
2022-04-26T08:33:30Z

- [https://github.com/c1ph3rbyt3/CVE-2022-29464](https://github.com/c1ph3rbyt3/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/c1ph3rbyt3/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/c1ph3rbyt3/CVE-2022-29464.svg) 
2025-01-17T17:41:11Z

- [https://github.com/amit-pathak009/CVE-2022-29464](https://github.com/amit-pathak009/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/amit-pathak009/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/amit-pathak009/CVE-2022-29464.svg) 
2022-05-19T21:24:10Z

- [https://github.com/SynixCyberCrimeMy/CVE-2022-29464](https://github.com/SynixCyberCrimeMy/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/SynixCyberCrimeMy/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/SynixCyberCrimeMy/CVE-2022-29464.svg) 
2023-11-16T18:32:29Z

- [https://github.com/n3rdh4x0r/CVE-2022-29464](https://github.com/n3rdh4x0r/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/n3rdh4x0r/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/n3rdh4x0r/CVE-2022-29464.svg) 
2022-04-24T22:56:19Z

- [https://github.com/cc3305/CVE-2022-29464](https://github.com/cc3305/CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/cc3305/CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/cc3305/CVE-2022-29464.svg) 
2024-07-27T20:18:06Z

- [https://github.com/hxlxmj/Mass-exploit-CVE-2022-29464](https://github.com/hxlxmj/Mass-exploit-CVE-2022-29464) :  
![starts](https://img.shields.io/github/stars/hxlxmj/Mass-exploit-CVE-2022-29464.svg) 
![forks](https://img.shields.io/github/forks/hxlxmj/Mass-exploit-CVE-2022-29464.svg) 
2022-06-22T23:54:38Z

## CVE-2022-23131
 In the case of instances where the SAML SSO authentication is enabled (non-default), session data can be modified by a malicious actor, because a user login stored in the session was not verified. Malicious unauthenticated actor may exploit this issue to escalate privileges and gain admin access to Zabbix Frontend. To perform the attack, SAML authentication is required to be enabled and the actor has to know the username of Zabbix user (or use the guest account, which is disabled by default).

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/Mr-xn/cve-2022-23131](https://github.com/Mr-xn/cve-2022-23131) :  
![starts](https://img.shields.io/github/stars/Mr-xn/cve-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/Mr-xn/cve-2022-23131.svg) 
2024-08-11T18:14:56Z

- [https://github.com/jweny/CVE-2022-23131](https://github.com/jweny/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/jweny/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/jweny/CVE-2022-23131.svg) 
2022-02-21T04:27:48Z

- [https://github.com/L0ading-x/cve-2022-23131](https://github.com/L0ading-x/cve-2022-23131) :  
![starts](https://img.shields.io/github/stars/L0ading-x/cve-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/L0ading-x/cve-2022-23131.svg) 
2022-02-22T01:45:34Z

- [https://github.com/kh4sh3i/CVE-2022-23131](https://github.com/kh4sh3i/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/kh4sh3i/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/kh4sh3i/CVE-2022-23131.svg) 
2022-03-31T20:17:36Z

- [https://github.com/Kazaf6s/CVE-2022-23131](https://github.com/Kazaf6s/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/Kazaf6s/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/Kazaf6s/CVE-2022-23131.svg) 
2022-04-02T19:00:40Z

- [https://github.com/random-robbie/cve-2022-23131-exp](https://github.com/random-robbie/cve-2022-23131-exp) :  
![starts](https://img.shields.io/github/stars/random-robbie/cve-2022-23131-exp.svg) 
![forks](https://img.shields.io/github/forks/random-robbie/cve-2022-23131-exp.svg) 
2022-02-23T16:37:13Z

- [https://github.com/SCAMagic/CVE-2022-23131poc-exp-zabbix-](https://github.com/SCAMagic/CVE-2022-23131poc-exp-zabbix-) :  
![starts](https://img.shields.io/github/stars/SCAMagic/CVE-2022-23131poc-exp-zabbix-.svg) 
![forks](https://img.shields.io/github/forks/SCAMagic/CVE-2022-23131poc-exp-zabbix-.svg) 
2022-07-22T05:55:23Z

- [https://github.com/fork-bombed/CVE-2022-23131](https://github.com/fork-bombed/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/fork-bombed/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/fork-bombed/CVE-2022-23131.svg) 
2024-09-18T15:58:35Z

- [https://github.com/1mxml/CVE-2022-23131](https://github.com/1mxml/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/1mxml/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/1mxml/CVE-2022-23131.svg) 
2022-02-19T03:14:47Z

- [https://github.com/pykiller/CVE-2022-23131](https://github.com/pykiller/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/pykiller/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/pykiller/CVE-2022-23131.svg) 
2022-02-24T11:59:48Z

- [https://github.com/zwjjustdoit/cve-2022-23131](https://github.com/zwjjustdoit/cve-2022-23131) :  
![starts](https://img.shields.io/github/stars/zwjjustdoit/cve-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/zwjjustdoit/cve-2022-23131.svg) 
2022-02-21T04:55:57Z

- [https://github.com/wr0x00/cve-2022-23131](https://github.com/wr0x00/cve-2022-23131) :  
![starts](https://img.shields.io/github/stars/wr0x00/cve-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/wr0x00/cve-2022-23131.svg) 
2023-01-07T14:22:29Z

- [https://github.com/Vulnmachines/Zabbix-CVE-2022-23131](https://github.com/Vulnmachines/Zabbix-CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/Zabbix-CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/Zabbix-CVE-2022-23131.svg) 
2022-09-02T13:26:54Z

- [https://github.com/trganda/CVE-2022-23131](https://github.com/trganda/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/trganda/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/trganda/CVE-2022-23131.svg) 
2022-02-24T11:50:28Z

- [https://github.com/davidzzo23/CVE-2022-23131](https://github.com/davidzzo23/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/davidzzo23/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/davidzzo23/CVE-2022-23131.svg) 
2024-10-25T14:00:09Z

- [https://github.com/Fa1c0n35/zabbix-cve-2022-23131](https://github.com/Fa1c0n35/zabbix-cve-2022-23131) :  
![starts](https://img.shields.io/github/stars/Fa1c0n35/zabbix-cve-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/Fa1c0n35/zabbix-cve-2022-23131.svg) 
2022-02-27T11:31:02Z

- [https://github.com/clearcdq/Zabbix-SAML-SSO-_CVE-2022-23131](https://github.com/clearcdq/Zabbix-SAML-SSO-_CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/clearcdq/Zabbix-SAML-SSO-_CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/clearcdq/Zabbix-SAML-SSO-_CVE-2022-23131.svg) 
2023-02-21T03:45:25Z

- [https://github.com/r10lab/CVE-2022-23131](https://github.com/r10lab/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/r10lab/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/r10lab/CVE-2022-23131.svg) 
2023-10-24T08:13:32Z

- [https://github.com/qq1549176285/CVE-2022-23131](https://github.com/qq1549176285/CVE-2022-23131) :  
![starts](https://img.shields.io/github/stars/qq1549176285/CVE-2022-23131.svg) 
![forks](https://img.shields.io/github/forks/qq1549176285/CVE-2022-23131.svg) 
2022-02-18T03:03:27Z

- [https://github.com/Arrnitage/CVE-2022-23131_exp](https://github.com/Arrnitage/CVE-2022-23131_exp) :  
![starts](https://img.shields.io/github/stars/Arrnitage/CVE-2022-23131_exp.svg) 
![forks](https://img.shields.io/github/forks/Arrnitage/CVE-2022-23131_exp.svg) 
2023-01-09T04:10:36Z

- [https://github.com/dagowda/Zabbix-cve-2022-23131-SSO-bypass](https://github.com/dagowda/Zabbix-cve-2022-23131-SSO-bypass) :  
![starts](https://img.shields.io/github/stars/dagowda/Zabbix-cve-2022-23131-SSO-bypass.svg) 
![forks](https://img.shields.io/github/forks/dagowda/Zabbix-cve-2022-23131-SSO-bypass.svg) 
2024-11-30T06:01:15Z

## CVE-2022-22965
 A Spring MVC or Spring WebFlux application running on JDK 9+ may be vulnerable to remote code execution (RCE) via data binding. The specific exploit requires the application to run on Tomcat as a WAR deployment. If the application is deployed as a Spring Boot executable jar, i.e. the default, it is not vulnerable to the exploit. However, the nature of the vulnerability is more general, and there may be other ways to exploit it.

- [https://github.com/AabyssZG/SpringBoot-Scan](https://github.com/AabyssZG/SpringBoot-Scan) :  
![starts](https://img.shields.io/github/stars/AabyssZG/SpringBoot-Scan.svg) 
![forks](https://img.shields.io/github/forks/AabyssZG/SpringBoot-Scan.svg) 
2025-01-12T09:50:06Z

- [https://github.com/BobTheShoplifter/Spring4Shell-POC](https://github.com/BobTheShoplifter/Spring4Shell-POC) :  
![starts](https://img.shields.io/github/stars/BobTheShoplifter/Spring4Shell-POC.svg) 
![forks](https://img.shields.io/github/forks/BobTheShoplifter/Spring4Shell-POC.svg) 
2022-11-09T15:46:06Z

- [https://github.com/reznok/Spring4Shell-POC](https://github.com/reznok/Spring4Shell-POC) :  
![starts](https://img.shields.io/github/stars/reznok/Spring4Shell-POC.svg) 
![forks](https://img.shields.io/github/forks/reznok/Spring4Shell-POC.svg) 
2022-08-04T18:26:18Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/tpt11fb/SpringVulScan](https://github.com/tpt11fb/SpringVulScan) :  
![starts](https://img.shields.io/github/stars/tpt11fb/SpringVulScan.svg) 
![forks](https://img.shields.io/github/forks/tpt11fb/SpringVulScan.svg) 
2023-01-23T13:00:34Z

- [https://github.com/TheGejr/SpringShell](https://github.com/TheGejr/SpringShell) :  
![starts](https://img.shields.io/github/stars/TheGejr/SpringShell.svg) 
![forks](https://img.shields.io/github/forks/TheGejr/SpringShell.svg) 
2022-04-04T14:09:11Z

- [https://github.com/alt3kx/CVE-2022-22965](https://github.com/alt3kx/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/alt3kx/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/alt3kx/CVE-2022-22965.svg) 
2022-04-07T23:00:29Z

- [https://github.com/zangcc/CVE-2022-22965-rexbb](https://github.com/zangcc/CVE-2022-22965-rexbb) :  
![starts](https://img.shields.io/github/stars/zangcc/CVE-2022-22965-rexbb.svg) 
![forks](https://img.shields.io/github/forks/zangcc/CVE-2022-22965-rexbb.svg) 
2023-11-14T03:08:10Z

- [https://github.com/Axx8/SpringFramework_CVE-2022-22965_RCE](https://github.com/Axx8/SpringFramework_CVE-2022-22965_RCE) :  
![starts](https://img.shields.io/github/stars/Axx8/SpringFramework_CVE-2022-22965_RCE.svg) 
![forks](https://img.shields.io/github/forks/Axx8/SpringFramework_CVE-2022-22965_RCE.svg) 
2022-04-01T12:08:45Z

- [https://github.com/4nth0ny1130/spring4shell_behinder](https://github.com/4nth0ny1130/spring4shell_behinder) :  
![starts](https://img.shields.io/github/stars/4nth0ny1130/spring4shell_behinder.svg) 
![forks](https://img.shields.io/github/forks/4nth0ny1130/spring4shell_behinder.svg) 
2022-05-10T03:54:23Z

- [https://github.com/Mr-xn/spring-core-rce](https://github.com/Mr-xn/spring-core-rce) :  
![starts](https://img.shields.io/github/stars/Mr-xn/spring-core-rce.svg) 
![forks](https://img.shields.io/github/forks/Mr-xn/spring-core-rce.svg) 
2022-04-01T15:34:03Z

- [https://github.com/colincowie/Safer_PoC_CVE-2022-22965](https://github.com/colincowie/Safer_PoC_CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/colincowie/Safer_PoC_CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/colincowie/Safer_PoC_CVE-2022-22965.svg) 
2022-05-27T12:56:40Z

- [https://github.com/FourCoreLabs/spring4shell-exploit-poc](https://github.com/FourCoreLabs/spring4shell-exploit-poc) :  
![starts](https://img.shields.io/github/stars/FourCoreLabs/spring4shell-exploit-poc.svg) 
![forks](https://img.shields.io/github/forks/FourCoreLabs/spring4shell-exploit-poc.svg) 
2022-04-06T15:00:14Z

- [https://github.com/HackJava/Spring](https://github.com/HackJava/Spring) :  
![starts](https://img.shields.io/github/stars/HackJava/Spring.svg) 
![forks](https://img.shields.io/github/forks/HackJava/Spring.svg) 
2022-04-26T13:08:31Z

- [https://github.com/tangxiaofeng7/CVE-2022-22965-Spring-Core-Rce](https://github.com/tangxiaofeng7/CVE-2022-22965-Spring-Core-Rce) :  
![starts](https://img.shields.io/github/stars/tangxiaofeng7/CVE-2022-22965-Spring-Core-Rce.svg) 
![forks](https://img.shields.io/github/forks/tangxiaofeng7/CVE-2022-22965-Spring-Core-Rce.svg) 
2022-04-01T08:44:19Z

- [https://github.com/XuCcc/VulEnv](https://github.com/XuCcc/VulEnv) :  
![starts](https://img.shields.io/github/stars/XuCcc/VulEnv.svg) 
![forks](https://img.shields.io/github/forks/XuCcc/VulEnv.svg) 
2023-08-13T14:36:28Z

- [https://github.com/Kirill89/CVE-2022-22965-PoC](https://github.com/Kirill89/CVE-2022-22965-PoC) :  
![starts](https://img.shields.io/github/stars/Kirill89/CVE-2022-22965-PoC.svg) 
![forks](https://img.shields.io/github/forks/Kirill89/CVE-2022-22965-PoC.svg) 
2022-04-05T21:30:19Z

- [https://github.com/k3rwin/spring-core-rce](https://github.com/k3rwin/spring-core-rce) :  
![starts](https://img.shields.io/github/stars/k3rwin/spring-core-rce.svg) 
![forks](https://img.shields.io/github/forks/k3rwin/spring-core-rce.svg) 
2022-04-22T07:37:16Z

- [https://github.com/liangyueliangyue/spring-core-rce](https://github.com/liangyueliangyue/spring-core-rce) :  
![starts](https://img.shields.io/github/stars/liangyueliangyue/spring-core-rce.svg) 
![forks](https://img.shields.io/github/forks/liangyueliangyue/spring-core-rce.svg) 
2022-04-07T10:28:11Z

- [https://github.com/jschauma/check-springshell](https://github.com/jschauma/check-springshell) :  
![starts](https://img.shields.io/github/stars/jschauma/check-springshell.svg) 
![forks](https://img.shields.io/github/forks/jschauma/check-springshell.svg) 
2022-04-01T18:15:31Z

- [https://github.com/p1ckzi/CVE-2022-22965](https://github.com/p1ckzi/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/p1ckzi/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/p1ckzi/CVE-2022-22965.svg) 
2022-06-30T10:55:54Z

- [https://github.com/DDuarte/springshell-rce-poc](https://github.com/DDuarte/springshell-rce-poc) :  
![starts](https://img.shields.io/github/stars/DDuarte/springshell-rce-poc.svg) 
![forks](https://img.shields.io/github/forks/DDuarte/springshell-rce-poc.svg) 
2023-04-18T14:15:42Z

- [https://github.com/alt3kx/CVE-2022-22965_PoC](https://github.com/alt3kx/CVE-2022-22965_PoC) :  
![starts](https://img.shields.io/github/stars/alt3kx/CVE-2022-22965_PoC.svg) 
![forks](https://img.shields.io/github/forks/alt3kx/CVE-2022-22965_PoC.svg) 
2022-04-07T19:12:38Z

- [https://github.com/light-Life/CVE-2022-22965-GUItools](https://github.com/light-Life/CVE-2022-22965-GUItools) :  
![starts](https://img.shields.io/github/stars/light-Life/CVE-2022-22965-GUItools.svg) 
![forks](https://img.shields.io/github/forks/light-Life/CVE-2022-22965-GUItools.svg) 
2022-04-02T15:29:31Z

- [https://github.com/itsecurityco/CVE-2022-22965](https://github.com/itsecurityco/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/itsecurityco/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/itsecurityco/CVE-2022-22965.svg) 
2022-04-03T08:38:30Z

- [https://github.com/kh4sh3i/Spring-CVE](https://github.com/kh4sh3i/Spring-CVE) :  
![starts](https://img.shields.io/github/stars/kh4sh3i/Spring-CVE.svg) 
![forks](https://img.shields.io/github/forks/kh4sh3i/Spring-CVE.svg) 
2022-03-31T20:58:54Z

- [https://github.com/me2nuk/CVE-2022-22965](https://github.com/me2nuk/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/me2nuk/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/me2nuk/CVE-2022-22965.svg) 
2022-04-04T01:16:41Z

- [https://github.com/wjl110/CVE-2022-22965_Spring_Core_RCE](https://github.com/wjl110/CVE-2022-22965_Spring_Core_RCE) :  
![starts](https://img.shields.io/github/stars/wjl110/CVE-2022-22965_Spring_Core_RCE.svg) 
![forks](https://img.shields.io/github/forks/wjl110/CVE-2022-22965_Spring_Core_RCE.svg) 
2022-04-02T10:14:11Z

- [https://github.com/viniciuspereiras/CVE-2022-22965-poc](https://github.com/viniciuspereiras/CVE-2022-22965-poc) :  
![starts](https://img.shields.io/github/stars/viniciuspereiras/CVE-2022-22965-poc.svg) 
![forks](https://img.shields.io/github/forks/viniciuspereiras/CVE-2022-22965-poc.svg) 
2023-11-29T20:11:53Z

- [https://github.com/west-wind/Spring4Shell-Detection](https://github.com/west-wind/Spring4Shell-Detection) :  
![starts](https://img.shields.io/github/stars/west-wind/Spring4Shell-Detection.svg) 
![forks](https://img.shields.io/github/forks/west-wind/Spring4Shell-Detection.svg) 
2022-07-08T15:59:33Z

- [https://github.com/zer0yu/CVE-2022-22965](https://github.com/zer0yu/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/zer0yu/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/zer0yu/CVE-2022-22965.svg) 
2022-04-07T11:46:54Z

- [https://github.com/fracturelabs/go-scan-spring](https://github.com/fracturelabs/go-scan-spring) :  
![starts](https://img.shields.io/github/stars/fracturelabs/go-scan-spring.svg) 
![forks](https://img.shields.io/github/forks/fracturelabs/go-scan-spring.svg) 
2022-04-07T16:04:53Z

- [https://github.com/WuliRuler/SBSCAN](https://github.com/WuliRuler/SBSCAN) :  
![starts](https://img.shields.io/github/stars/WuliRuler/SBSCAN.svg) 
![forks](https://img.shields.io/github/forks/WuliRuler/SBSCAN.svg) 
2024-11-03T07:56:43Z

- [https://github.com/gpiechnik2/nmap-spring4shell](https://github.com/gpiechnik2/nmap-spring4shell) :  
![starts](https://img.shields.io/github/stars/gpiechnik2/nmap-spring4shell.svg) 
![forks](https://img.shields.io/github/forks/gpiechnik2/nmap-spring4shell.svg) 
2022-04-08T19:24:41Z

- [https://github.com/irgoncalves/f5-waf-enforce-sig-Spring4Shell](https://github.com/irgoncalves/f5-waf-enforce-sig-Spring4Shell) :  
![starts](https://img.shields.io/github/stars/irgoncalves/f5-waf-enforce-sig-Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/irgoncalves/f5-waf-enforce-sig-Spring4Shell.svg) 
2022-03-31T22:59:14Z

- [https://github.com/sunnyvale-it/CVE-2022-22965-PoC](https://github.com/sunnyvale-it/CVE-2022-22965-PoC) :  
![starts](https://img.shields.io/github/stars/sunnyvale-it/CVE-2022-22965-PoC.svg) 
![forks](https://img.shields.io/github/forks/sunnyvale-it/CVE-2022-22965-PoC.svg) 
2023-04-27T15:18:02Z

- [https://github.com/Wrin9/CVE-2022-22965](https://github.com/Wrin9/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/Wrin9/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/Wrin9/CVE-2022-22965.svg) 
2022-04-02T08:45:17Z

- [https://github.com/Qualys/spring4scanwin](https://github.com/Qualys/spring4scanwin) :  
![starts](https://img.shields.io/github/stars/Qualys/spring4scanwin.svg) 
![forks](https://img.shields.io/github/forks/Qualys/spring4scanwin.svg) 
2022-04-09T20:36:38Z

- [https://github.com/GuayoyoCyber/CVE-2022-22965](https://github.com/GuayoyoCyber/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/GuayoyoCyber/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/GuayoyoCyber/CVE-2022-22965.svg) 
2022-04-19T15:05:47Z

- [https://github.com/wikiZ/springboot_CVE-2022-22965](https://github.com/wikiZ/springboot_CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/wikiZ/springboot_CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/wikiZ/springboot_CVE-2022-22965.svg) 
2022-04-07T02:31:28Z

- [https://github.com/mariomamo/CVE-2022-22965](https://github.com/mariomamo/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/mariomamo/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/mariomamo/CVE-2022-22965.svg) 
2022-04-28T13:25:08Z

- [https://github.com/nu0l/CVE-2022-22965](https://github.com/nu0l/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/nu0l/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/nu0l/CVE-2022-22965.svg) 
2022-04-08T04:24:30Z

- [https://github.com/Loneyers/Spring4Shell](https://github.com/Loneyers/Spring4Shell) :  
![starts](https://img.shields.io/github/stars/Loneyers/Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/Loneyers/Spring4Shell.svg) 
2022-04-11T12:39:39Z

- [https://github.com/wshon/spring-framework-rce](https://github.com/wshon/spring-framework-rce) :  
![starts](https://img.shields.io/github/stars/wshon/spring-framework-rce.svg) 
![forks](https://img.shields.io/github/forks/wshon/spring-framework-rce.svg) 
2022-04-01T14:31:35Z

- [https://github.com/iloveflag/Fast-CVE-2022-22965](https://github.com/iloveflag/Fast-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/iloveflag/Fast-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/iloveflag/Fast-CVE-2022-22965.svg) 
2022-11-08T14:15:29Z

- [https://github.com/netcode/Spring4shell-CVE-2022-22965-POC](https://github.com/netcode/Spring4shell-CVE-2022-22965-POC) :  
![starts](https://img.shields.io/github/stars/netcode/Spring4shell-CVE-2022-22965-POC.svg) 
![forks](https://img.shields.io/github/forks/netcode/Spring4shell-CVE-2022-22965-POC.svg) 
2022-04-04T21:11:13Z

- [https://github.com/BKLockly/CVE-2022-22965](https://github.com/BKLockly/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/BKLockly/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/BKLockly/CVE-2022-22965.svg) 
2023-06-04T03:51:56Z

- [https://github.com/likewhite/CVE-2022-22965](https://github.com/likewhite/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/likewhite/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/likewhite/CVE-2022-22965.svg) 
2023-01-31T08:54:27Z

- [https://github.com/khidottrivi/CVE-2022-22965](https://github.com/khidottrivi/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/khidottrivi/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/khidottrivi/CVE-2022-22965.svg) 
2022-04-27T08:10:46Z

- [https://github.com/anair-it/springshell-vuln-POC](https://github.com/anair-it/springshell-vuln-POC) :  
![starts](https://img.shields.io/github/stars/anair-it/springshell-vuln-POC.svg) 
![forks](https://img.shields.io/github/forks/anair-it/springshell-vuln-POC.svg) 
2022-04-04T19:29:18Z

- [https://github.com/CalumHutton/CVE-2022-22965-PoC_Payara](https://github.com/CalumHutton/CVE-2022-22965-PoC_Payara) :  
![starts](https://img.shields.io/github/stars/CalumHutton/CVE-2022-22965-PoC_Payara.svg) 
![forks](https://img.shields.io/github/forks/CalumHutton/CVE-2022-22965-PoC_Payara.svg) 
2022-04-08T12:16:46Z

- [https://github.com/LudovicPatho/CVE-2022-22965_Spring4Shell](https://github.com/LudovicPatho/CVE-2022-22965_Spring4Shell) :  
![starts](https://img.shields.io/github/stars/LudovicPatho/CVE-2022-22965_Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/LudovicPatho/CVE-2022-22965_Spring4Shell.svg) 
2022-04-05T20:53:28Z

- [https://github.com/jakabakos/CVE-2022-22965-Spring4Shell](https://github.com/jakabakos/CVE-2022-22965-Spring4Shell) :  
![starts](https://img.shields.io/github/stars/jakabakos/CVE-2022-22965-Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/jakabakos/CVE-2022-22965-Spring4Shell.svg) 
2023-06-21T10:28:40Z

- [https://github.com/fracturelabs/spring4shell_victim](https://github.com/fracturelabs/spring4shell_victim) :  
![starts](https://img.shields.io/github/stars/fracturelabs/spring4shell_victim.svg) 
![forks](https://img.shields.io/github/forks/fracturelabs/spring4shell_victim.svg) 
2022-04-07T03:56:37Z

- [https://github.com/twseptian/cve-2022-22965](https://github.com/twseptian/cve-2022-22965) :  
![starts](https://img.shields.io/github/stars/twseptian/cve-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/twseptian/cve-2022-22965.svg) 
2022-04-04T16:54:37Z

- [https://github.com/irgoncalves/irule-cve-2022-22965](https://github.com/irgoncalves/irule-cve-2022-22965) :  
![starts](https://img.shields.io/github/stars/irgoncalves/irule-cve-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/irgoncalves/irule-cve-2022-22965.svg) 
2022-04-06T20:15:51Z

- [https://github.com/D1mang/Spring4Shell-CVE-2022-22965](https://github.com/D1mang/Spring4Shell-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/D1mang/Spring4Shell-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/D1mang/Spring4Shell-CVE-2022-22965.svg) 
2022-07-13T00:30:22Z

- [https://github.com/rwincey/spring4shell-CVE-2022-22965](https://github.com/rwincey/spring4shell-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/rwincey/spring4shell-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/rwincey/spring4shell-CVE-2022-22965.svg) 
2022-04-01T13:59:13Z

- [https://github.com/datawiza-inc/spring-rec-demo](https://github.com/datawiza-inc/spring-rec-demo) :  
![starts](https://img.shields.io/github/stars/datawiza-inc/spring-rec-demo.svg) 
![forks](https://img.shields.io/github/forks/datawiza-inc/spring-rec-demo.svg) 
2022-04-07T06:52:39Z

- [https://github.com/bL34cHig0/Telstra-Cybersecurity-Virtual-Experience-](https://github.com/bL34cHig0/Telstra-Cybersecurity-Virtual-Experience-) :  
![starts](https://img.shields.io/github/stars/bL34cHig0/Telstra-Cybersecurity-Virtual-Experience-.svg) 
![forks](https://img.shields.io/github/forks/bL34cHig0/Telstra-Cybersecurity-Virtual-Experience-.svg) 
2024-03-19T13:42:29Z

- [https://github.com/Joe1sn/CVE-2022-22965](https://github.com/Joe1sn/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/Joe1sn/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/Joe1sn/CVE-2022-22965.svg) 
2022-04-02T09:50:34Z

- [https://github.com/helsecert/CVE-2022-22965](https://github.com/helsecert/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/helsecert/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/helsecert/CVE-2022-22965.svg) 
2022-04-04T11:27:30Z

- [https://github.com/lcarea/CVE-2022-22965](https://github.com/lcarea/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/lcarea/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/lcarea/CVE-2022-22965.svg) 
2022-04-01T11:19:48Z

- [https://github.com/0xrobiul/CVE-2022-22965](https://github.com/0xrobiul/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/0xrobiul/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/0xrobiul/CVE-2022-22965.svg) 
2023-12-26T19:55:00Z

- [https://github.com/cxzero/CVE-2022-22965-spring4shell](https://github.com/cxzero/CVE-2022-22965-spring4shell) :  
![starts](https://img.shields.io/github/stars/cxzero/CVE-2022-22965-spring4shell.svg) 
![forks](https://img.shields.io/github/forks/cxzero/CVE-2022-22965-spring4shell.svg) 
2023-12-21T22:07:02Z

- [https://github.com/clemoregan/SSE4-CVE-2022-22965](https://github.com/clemoregan/SSE4-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/clemoregan/SSE4-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/clemoregan/SSE4-CVE-2022-22965.svg) 
2022-11-28T15:26:02Z

- [https://github.com/daniel0x00/Invoke-CVE-2022-22965-SafeCheck](https://github.com/daniel0x00/Invoke-CVE-2022-22965-SafeCheck) :  
![starts](https://img.shields.io/github/stars/daniel0x00/Invoke-CVE-2022-22965-SafeCheck.svg) 
![forks](https://img.shields.io/github/forks/daniel0x00/Invoke-CVE-2022-22965-SafeCheck.svg) 
2022-04-04T18:55:02Z

- [https://github.com/gokul-ramesh/Spring4Shell-PoC-exploit](https://github.com/gokul-ramesh/Spring4Shell-PoC-exploit) :  
![starts](https://img.shields.io/github/stars/gokul-ramesh/Spring4Shell-PoC-exploit.svg) 
![forks](https://img.shields.io/github/forks/gokul-ramesh/Spring4Shell-PoC-exploit.svg) 
2023-03-17T14:30:25Z

- [https://github.com/sinjap/spring4shell](https://github.com/sinjap/spring4shell) :  
![starts](https://img.shields.io/github/stars/sinjap/spring4shell.svg) 
![forks](https://img.shields.io/github/forks/sinjap/spring4shell.svg) 
2022-04-04T20:03:16Z

- [https://github.com/Snip3R69/spring-shell-vuln](https://github.com/Snip3R69/spring-shell-vuln) :  
![starts](https://img.shields.io/github/stars/Snip3R69/spring-shell-vuln.svg) 
![forks](https://img.shields.io/github/forks/Snip3R69/spring-shell-vuln.svg) 
2022-04-05T10:23:32Z

- [https://github.com/c33dd/CVE-2022-22965](https://github.com/c33dd/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/c33dd/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/c33dd/CVE-2022-22965.svg) 
2023-02-28T16:49:04Z

- [https://github.com/luoqianlin/CVE-2022-22965](https://github.com/luoqianlin/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/luoqianlin/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/luoqianlin/CVE-2022-22965.svg) 
2022-04-05T15:58:58Z

- [https://github.com/LucasPDiniz/CVE-2022-22965](https://github.com/LucasPDiniz/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/LucasPDiniz/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/LucasPDiniz/CVE-2022-22965.svg) 
2024-06-30T21:57:31Z

- [https://github.com/devengpk/CVE-2022-22965](https://github.com/devengpk/CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/devengpk/CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/devengpk/CVE-2022-22965.svg) 
2022-12-16T19:17:12Z

- [https://github.com/t3amj3ff/Spring4ShellPoC](https://github.com/t3amj3ff/Spring4ShellPoC) :  
![starts](https://img.shields.io/github/stars/t3amj3ff/Spring4ShellPoC.svg) 
![forks](https://img.shields.io/github/forks/t3amj3ff/Spring4ShellPoC.svg) 
2022-04-08T09:21:16Z

- [https://github.com/mwojterski/cve-2022-22965](https://github.com/mwojterski/cve-2022-22965) :  
![starts](https://img.shields.io/github/stars/mwojterski/cve-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/mwojterski/cve-2022-22965.svg) 
2022-04-02T20:23:06Z

- [https://github.com/fransvanbuul/CVE-2022-22965-susceptibility](https://github.com/fransvanbuul/CVE-2022-22965-susceptibility) :  
![starts](https://img.shields.io/github/stars/fransvanbuul/CVE-2022-22965-susceptibility.svg) 
![forks](https://img.shields.io/github/forks/fransvanbuul/CVE-2022-22965-susceptibility.svg) 
2022-04-09T07:51:53Z

- [https://github.com/Enokiy/spring-RCE-CVE-2022-22965](https://github.com/Enokiy/spring-RCE-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/Enokiy/spring-RCE-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/Enokiy/spring-RCE-CVE-2022-22965.svg) 
2022-04-29T10:03:35Z

- [https://github.com/c4mx/CVE-2022-22965_PoC](https://github.com/c4mx/CVE-2022-22965_PoC) :  
![starts](https://img.shields.io/github/stars/c4mx/CVE-2022-22965_PoC.svg) 
![forks](https://img.shields.io/github/forks/c4mx/CVE-2022-22965_PoC.svg) 
2022-04-21T10:18:47Z

- [https://github.com/snicoll-scratches/spring-boot-cve-2022-22965](https://github.com/snicoll-scratches/spring-boot-cve-2022-22965) :  
![starts](https://img.shields.io/github/stars/snicoll-scratches/spring-boot-cve-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/snicoll-scratches/spring-boot-cve-2022-22965.svg) 
2022-04-13T14:45:26Z

- [https://github.com/Omaraitbenhaddi/-Spring4Shell-CVE-2022-22965-](https://github.com/Omaraitbenhaddi/-Spring4Shell-CVE-2022-22965-) :  
![starts](https://img.shields.io/github/stars/Omaraitbenhaddi/-Spring4Shell-CVE-2022-22965-.svg) 
![forks](https://img.shields.io/github/forks/Omaraitbenhaddi/-Spring4Shell-CVE-2022-22965-.svg) 
2022-04-13T00:19:58Z

- [https://github.com/ClemExp/CVE-2022-22965-PoC](https://github.com/ClemExp/CVE-2022-22965-PoC) :  
![starts](https://img.shields.io/github/stars/ClemExp/CVE-2022-22965-PoC.svg) 
![forks](https://img.shields.io/github/forks/ClemExp/CVE-2022-22965-PoC.svg) 
2022-11-28T14:28:07Z

- [https://github.com/dbgee/Spring4Shell](https://github.com/dbgee/Spring4Shell) :  
![starts](https://img.shields.io/github/stars/dbgee/Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/dbgee/Spring4Shell.svg) 
2023-06-08T03:37:58Z

- [https://github.com/xsxtw/SpringFramework_CVE-2022-22965_RCE](https://github.com/xsxtw/SpringFramework_CVE-2022-22965_RCE) :  
![starts](https://img.shields.io/github/stars/xsxtw/SpringFramework_CVE-2022-22965_RCE.svg) 
![forks](https://img.shields.io/github/forks/xsxtw/SpringFramework_CVE-2022-22965_RCE.svg) 
2024-05-01T02:39:14Z

- [https://github.com/sohamsharma966/Spring4Shell-CVE-2022-22965](https://github.com/sohamsharma966/Spring4Shell-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/sohamsharma966/Spring4Shell-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/sohamsharma966/Spring4Shell-CVE-2022-22965.svg) 
2023-09-02T10:51:27Z

- [https://github.com/ajith737/Spring4Shell-CVE-2022-22965-POC](https://github.com/ajith737/Spring4Shell-CVE-2022-22965-POC) :  
![starts](https://img.shields.io/github/stars/ajith737/Spring4Shell-CVE-2022-22965-POC.svg) 
![forks](https://img.shields.io/github/forks/ajith737/Spring4Shell-CVE-2022-22965-POC.svg) 
2023-01-03T18:53:07Z

- [https://github.com/te5t321/Spring4Shell-CVE-2022-22965.py](https://github.com/te5t321/Spring4Shell-CVE-2022-22965.py) :  
![starts](https://img.shields.io/github/stars/te5t321/Spring4Shell-CVE-2022-22965.py.svg) 
![forks](https://img.shields.io/github/forks/te5t321/Spring4Shell-CVE-2022-22965.py.svg) 
2022-04-10T14:47:26Z

- [https://github.com/guigui237/Expoitation-de-la-vuln-rabilit-CVE-2022-22965](https://github.com/guigui237/Expoitation-de-la-vuln-rabilit-CVE-2022-22965) :  
![starts](https://img.shields.io/github/stars/guigui237/Expoitation-de-la-vuln-rabilit-CVE-2022-22965.svg) 
![forks](https://img.shields.io/github/forks/guigui237/Expoitation-de-la-vuln-rabilit-CVE-2022-22965.svg) 
2024-11-06T23:04:39Z

- [https://github.com/Aur3ns/Block-Spring4Shell](https://github.com/Aur3ns/Block-Spring4Shell) :  
![starts](https://img.shields.io/github/stars/Aur3ns/Block-Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/Aur3ns/Block-Spring4Shell.svg) 
2024-12-15T00:16:04Z

- [https://github.com/mebibite/springhound](https://github.com/mebibite/springhound) :  
![starts](https://img.shields.io/github/stars/mebibite/springhound.svg) 
![forks](https://img.shields.io/github/forks/mebibite/springhound.svg) 
2022-04-01T00:42:35Z

- [https://github.com/jashan-lefty/Spring4Shell](https://github.com/jashan-lefty/Spring4Shell) :  
![starts](https://img.shields.io/github/stars/jashan-lefty/Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/jashan-lefty/Spring4Shell.svg) 
2025-02-03T10:34:19Z

- [https://github.com/delyee/Spring4Shell](https://github.com/delyee/Spring4Shell) :  
![starts](https://img.shields.io/github/stars/delyee/Spring4Shell.svg) 
![forks](https://img.shields.io/github/forks/delyee/Spring4Shell.svg) 
2022-04-25T13:13:44Z

## CVE-2022-22963
 In Spring Cloud Function versions 3.1.6, 3.2.2 and older unsupported versions, when using routing functionality it is possible for a user to provide a specially crafted SpEL as a routing-expression that may result in remote code execution and access to local resources.

- [https://github.com/AabyssZG/SpringBoot-Scan](https://github.com/AabyssZG/SpringBoot-Scan) :  
![starts](https://img.shields.io/github/stars/AabyssZG/SpringBoot-Scan.svg) 
![forks](https://img.shields.io/github/forks/AabyssZG/SpringBoot-Scan.svg) 
2025-01-12T09:50:06Z

- [https://github.com/hktalent/spring-spel-0day-poc](https://github.com/hktalent/spring-spel-0day-poc) :  
![starts](https://img.shields.io/github/stars/hktalent/spring-spel-0day-poc.svg) 
![forks](https://img.shields.io/github/forks/hktalent/spring-spel-0day-poc.svg) 
2023-03-05T12:41:19Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/tpt11fb/SpringVulScan](https://github.com/tpt11fb/SpringVulScan) :  
![starts](https://img.shields.io/github/stars/tpt11fb/SpringVulScan.svg) 
![forks](https://img.shields.io/github/forks/tpt11fb/SpringVulScan.svg) 
2023-01-23T13:00:34Z

- [https://github.com/dinosn/CVE-2022-22963](https://github.com/dinosn/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/dinosn/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/dinosn/CVE-2022-22963.svg) 
2022-03-30T06:01:04Z

- [https://github.com/darryk10/CVE-2022-22963](https://github.com/darryk10/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/darryk10/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/darryk10/CVE-2022-22963.svg) 
2022-04-15T06:39:52Z

- [https://github.com/XuCcc/VulEnv](https://github.com/XuCcc/VulEnv) :  
![starts](https://img.shields.io/github/stars/XuCcc/VulEnv.svg) 
![forks](https://img.shields.io/github/forks/XuCcc/VulEnv.svg) 
2023-08-13T14:36:28Z

- [https://github.com/jschauma/check-springshell](https://github.com/jschauma/check-springshell) :  
![starts](https://img.shields.io/github/stars/jschauma/check-springshell.svg) 
![forks](https://img.shields.io/github/forks/jschauma/check-springshell.svg) 
2022-04-01T18:15:31Z

- [https://github.com/J0ey17/CVE-2022-22963_Reverse-Shell-Exploit](https://github.com/J0ey17/CVE-2022-22963_Reverse-Shell-Exploit) :  
![starts](https://img.shields.io/github/stars/J0ey17/CVE-2022-22963_Reverse-Shell-Exploit.svg) 
![forks](https://img.shields.io/github/forks/J0ey17/CVE-2022-22963_Reverse-Shell-Exploit.svg) 
2023-03-18T11:47:55Z

- [https://github.com/me2nuk/CVE-2022-22963](https://github.com/me2nuk/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/me2nuk/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/me2nuk/CVE-2022-22963.svg) 
2022-04-01T12:51:25Z

- [https://github.com/RanDengShiFu/CVE-2022-22963](https://github.com/RanDengShiFu/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/RanDengShiFu/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/RanDengShiFu/CVE-2022-22963.svg) 
2022-03-30T11:54:22Z

- [https://github.com/kh4sh3i/Spring-CVE](https://github.com/kh4sh3i/Spring-CVE) :  
![starts](https://img.shields.io/github/stars/kh4sh3i/Spring-CVE.svg) 
![forks](https://img.shields.io/github/forks/kh4sh3i/Spring-CVE.svg) 
2022-03-31T20:58:54Z

- [https://github.com/west-wind/Spring4Shell-Detection](https://github.com/west-wind/Spring4Shell-Detection) :  
![starts](https://img.shields.io/github/stars/west-wind/Spring4Shell-Detection.svg) 
![forks](https://img.shields.io/github/forks/west-wind/Spring4Shell-Detection.svg) 
2022-07-08T15:59:33Z

- [https://github.com/WuliRuler/SBSCAN](https://github.com/WuliRuler/SBSCAN) :  
![starts](https://img.shields.io/github/stars/WuliRuler/SBSCAN.svg) 
![forks](https://img.shields.io/github/forks/WuliRuler/SBSCAN.svg) 
2024-11-03T07:56:43Z

- [https://github.com/Kirill89/CVE-2022-22963-PoC](https://github.com/Kirill89/CVE-2022-22963-PoC) :  
![starts](https://img.shields.io/github/stars/Kirill89/CVE-2022-22963-PoC.svg) 
![forks](https://img.shields.io/github/forks/Kirill89/CVE-2022-22963-PoC.svg) 
2022-03-30T17:40:21Z

- [https://github.com/k3rwin/spring-cloud-function-rce](https://github.com/k3rwin/spring-cloud-function-rce) :  
![starts](https://img.shields.io/github/stars/k3rwin/spring-cloud-function-rce.svg) 
![forks](https://img.shields.io/github/forks/k3rwin/spring-cloud-function-rce.svg) 
2022-04-22T05:13:32Z

- [https://github.com/charis3306/CVE-2022-22963](https://github.com/charis3306/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/charis3306/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/charis3306/CVE-2022-22963.svg) 
2023-06-04T08:02:23Z

- [https://github.com/Qualys/spring4scanwin](https://github.com/Qualys/spring4scanwin) :  
![starts](https://img.shields.io/github/stars/Qualys/spring4scanwin.svg) 
![forks](https://img.shields.io/github/forks/Qualys/spring4scanwin.svg) 
2022-04-09T20:36:38Z

- [https://github.com/iliass-dahman/CVE-2022-22963-POC](https://github.com/iliass-dahman/CVE-2022-22963-POC) :  
![starts](https://img.shields.io/github/stars/iliass-dahman/CVE-2022-22963-POC.svg) 
![forks](https://img.shields.io/github/forks/iliass-dahman/CVE-2022-22963-POC.svg) 
2023-01-22T22:39:49Z

- [https://github.com/lemmyz4n3771/CVE-2022-22963-PoC](https://github.com/lemmyz4n3771/CVE-2022-22963-PoC) :  
![starts](https://img.shields.io/github/stars/lemmyz4n3771/CVE-2022-22963-PoC.svg) 
![forks](https://img.shields.io/github/forks/lemmyz4n3771/CVE-2022-22963-PoC.svg) 
2023-03-14T15:23:12Z

- [https://github.com/stevemats/Spring0DayCoreExploit](https://github.com/stevemats/Spring0DayCoreExploit) :  
![starts](https://img.shields.io/github/stars/stevemats/Spring0DayCoreExploit.svg) 
![forks](https://img.shields.io/github/forks/stevemats/Spring0DayCoreExploit.svg) 
2022-03-30T19:10:21Z

- [https://github.com/randallbanner/Spring-Cloud-Function-Vulnerability-CVE-2022-22963-RCE](https://github.com/randallbanner/Spring-Cloud-Function-Vulnerability-CVE-2022-22963-RCE) :  
![starts](https://img.shields.io/github/stars/randallbanner/Spring-Cloud-Function-Vulnerability-CVE-2022-22963-RCE.svg) 
![forks](https://img.shields.io/github/forks/randallbanner/Spring-Cloud-Function-Vulnerability-CVE-2022-22963-RCE.svg) 
2023-04-17T14:01:46Z

- [https://github.com/viemsr/Spring_Cloud_Function_memshell](https://github.com/viemsr/Spring_Cloud_Function_memshell) :  
![starts](https://img.shields.io/github/stars/viemsr/Spring_Cloud_Function_memshell.svg) 
![forks](https://img.shields.io/github/forks/viemsr/Spring_Cloud_Function_memshell.svg) 
2022-03-31T06:06:49Z

- [https://github.com/twseptian/cve-2022-22963](https://github.com/twseptian/cve-2022-22963) :  
![starts](https://img.shields.io/github/stars/twseptian/cve-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/twseptian/cve-2022-22963.svg) 
2022-04-03T07:08:45Z

- [https://github.com/SealPaPaPa/SpringCloudFunction-Research](https://github.com/SealPaPaPa/SpringCloudFunction-Research) :  
![starts](https://img.shields.io/github/stars/SealPaPaPa/SpringCloudFunction-Research.svg) 
![forks](https://img.shields.io/github/forks/SealPaPaPa/SpringCloudFunction-Research.svg) 
2022-04-05T18:09:39Z

- [https://github.com/AayushmanThapaMagar/CVE-2022-22963](https://github.com/AayushmanThapaMagar/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/AayushmanThapaMagar/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/AayushmanThapaMagar/CVE-2022-22963.svg) 
2022-04-01T10:48:39Z

- [https://github.com/dr6817/CVE-2022-22963](https://github.com/dr6817/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/dr6817/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/dr6817/CVE-2022-22963.svg) 
2022-11-25T15:42:12Z

- [https://github.com/puckiestyle/CVE-2022-22963](https://github.com/puckiestyle/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/puckiestyle/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/puckiestyle/CVE-2022-22963.svg) 
2022-03-31T11:33:34Z

- [https://github.com/SourM1lk/CVE-2022-22963-Exploit](https://github.com/SourM1lk/CVE-2022-22963-Exploit) :  
![starts](https://img.shields.io/github/stars/SourM1lk/CVE-2022-22963-Exploit.svg) 
![forks](https://img.shields.io/github/forks/SourM1lk/CVE-2022-22963-Exploit.svg) 
2023-04-11T13:46:45Z

- [https://github.com/gunzf0x/CVE-2022-22963](https://github.com/gunzf0x/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/gunzf0x/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/gunzf0x/CVE-2022-22963.svg) 
2023-05-04T23:24:46Z

- [https://github.com/75ACOL/CVE-2022-22963](https://github.com/75ACOL/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/75ACOL/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/75ACOL/CVE-2022-22963.svg) 
2022-09-01T09:14:00Z

- [https://github.com/Shayz614/CVE-2022-22963](https://github.com/Shayz614/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/Shayz614/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/Shayz614/CVE-2022-22963.svg) 
2024-12-13T22:56:43Z

- [https://github.com/G01d3nW01f/CVE-2022-22963](https://github.com/G01d3nW01f/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/G01d3nW01f/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/G01d3nW01f/CVE-2022-22963.svg) 
2023-03-12T06:19:55Z

- [https://github.com/Mustafa1986/CVE-2022-22963](https://github.com/Mustafa1986/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/Mustafa1986/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/Mustafa1986/CVE-2022-22963.svg) 
2023-03-21T06:15:56Z

- [https://github.com/jrbH4CK/CVE-2022-22963](https://github.com/jrbH4CK/CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/jrbH4CK/CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/jrbH4CK/CVE-2022-22963.svg) 
2024-07-30T23:22:36Z

- [https://github.com/BearClaw96/CVE-2022-22963-Poc-Bearcules](https://github.com/BearClaw96/CVE-2022-22963-Poc-Bearcules) :  
![starts](https://img.shields.io/github/stars/BearClaw96/CVE-2022-22963-Poc-Bearcules.svg) 
![forks](https://img.shields.io/github/forks/BearClaw96/CVE-2022-22963-Poc-Bearcules.svg) 
2023-10-28T21:56:35Z

- [https://github.com/nikn0laty/RCE-in-Spring-Cloud-CVE-2022-22963](https://github.com/nikn0laty/RCE-in-Spring-Cloud-CVE-2022-22963) :  
![starts](https://img.shields.io/github/stars/nikn0laty/RCE-in-Spring-Cloud-CVE-2022-22963.svg) 
![forks](https://img.shields.io/github/forks/nikn0laty/RCE-in-Spring-Cloud-CVE-2022-22963.svg) 
2023-05-26T21:50:27Z

- [https://github.com/mebibite/springhound](https://github.com/mebibite/springhound) :  
![starts](https://img.shields.io/github/stars/mebibite/springhound.svg) 
![forks](https://img.shields.io/github/forks/mebibite/springhound.svg) 
2022-04-01T00:42:35Z

## CVE-2022-22954
 VMware Workspace ONE Access and Identity Manager contain a remote code execution vulnerability due to server-side template injection. A malicious actor with network access can trigger a server-side template injection that may result in remote code execution.

- [https://github.com/Schira4396/VcenterKiller](https://github.com/Schira4396/VcenterKiller) :  
![starts](https://img.shields.io/github/stars/Schira4396/VcenterKiller.svg) 
![forks](https://img.shields.io/github/forks/Schira4396/VcenterKiller.svg) 
2024-04-25T06:09:38Z

- [https://github.com/W01fh4cker/Serein](https://github.com/W01fh4cker/Serein) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/Serein.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/Serein.svg) 
2023-02-26T14:06:05Z

- [https://github.com/W01fh4cker/VcenterKit](https://github.com/W01fh4cker/VcenterKit) :  
![starts](https://img.shields.io/github/stars/W01fh4cker/VcenterKit.svg) 
![forks](https://img.shields.io/github/forks/W01fh4cker/VcenterKit.svg) 
2024-10-25T08:56:45Z

- [https://github.com/sherlocksecurity/VMware-CVE-2022-22954](https://github.com/sherlocksecurity/VMware-CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/sherlocksecurity/VMware-CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/sherlocksecurity/VMware-CVE-2022-22954.svg) 
2022-04-13T06:15:11Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/bewhale/CVE-2022-22954](https://github.com/bewhale/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/bewhale/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/bewhale/CVE-2022-22954.svg) 
2022-04-26T04:26:00Z

- [https://github.com/24-2021/EXP-POC](https://github.com/24-2021/EXP-POC) :  
![starts](https://img.shields.io/github/stars/24-2021/EXP-POC.svg) 
![forks](https://img.shields.io/github/forks/24-2021/EXP-POC.svg) 
2023-01-11T06:20:26Z

- [https://github.com/jax7sec/CVE-2022-22954](https://github.com/jax7sec/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/jax7sec/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/jax7sec/CVE-2022-22954.svg) 
2022-04-15T11:35:35Z

- [https://github.com/Vulnmachines/VMWare_CVE-2022-22954](https://github.com/Vulnmachines/VMWare_CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/VMWare_CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/VMWare_CVE-2022-22954.svg) 
2022-04-11T19:59:53Z

- [https://github.com/tunelko/CVE-2022-22954-PoC](https://github.com/tunelko/CVE-2022-22954-PoC) :  
![starts](https://img.shields.io/github/stars/tunelko/CVE-2022-22954-PoC.svg) 
![forks](https://img.shields.io/github/forks/tunelko/CVE-2022-22954-PoC.svg) 
2024-02-13T13:51:41Z

- [https://github.com/DrorDvash/CVE-2022-22954_VMware_PoC](https://github.com/DrorDvash/CVE-2022-22954_VMware_PoC) :  
![starts](https://img.shields.io/github/stars/DrorDvash/CVE-2022-22954_VMware_PoC.svg) 
![forks](https://img.shields.io/github/forks/DrorDvash/CVE-2022-22954_VMware_PoC.svg) 
2022-04-12T23:19:41Z

- [https://github.com/orwagodfather/CVE-2022-22954](https://github.com/orwagodfather/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/orwagodfather/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/orwagodfather/CVE-2022-22954.svg) 
2022-06-03T08:52:06Z

- [https://github.com/aniqfakhrul/CVE-2022-22954](https://github.com/aniqfakhrul/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/aniqfakhrul/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/aniqfakhrul/CVE-2022-22954.svg) 
2022-05-27T09:07:19Z

- [https://github.com/MLX15/CVE-2022-22954](https://github.com/MLX15/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/MLX15/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/MLX15/CVE-2022-22954.svg) 
2022-04-15T19:39:10Z

- [https://github.com/b4dboy17/CVE-2022-22954](https://github.com/b4dboy17/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/b4dboy17/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/b4dboy17/CVE-2022-22954.svg) 
2022-06-03T09:18:37Z

- [https://github.com/axingde/CVE-2022-22954-POC](https://github.com/axingde/CVE-2022-22954-POC) :  
![starts](https://img.shields.io/github/stars/axingde/CVE-2022-22954-POC.svg) 
![forks](https://img.shields.io/github/forks/axingde/CVE-2022-22954-POC.svg) 
2022-04-15T09:33:01Z

- [https://github.com/Chocapikk/CVE-2022-22954](https://github.com/Chocapikk/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2022-22954.svg) 
2022-06-01T23:50:18Z

- [https://github.com/bb33bb/CVE-2022-22954-VMware-RCE](https://github.com/bb33bb/CVE-2022-22954-VMware-RCE) :  
![starts](https://img.shields.io/github/stars/bb33bb/CVE-2022-22954-VMware-RCE.svg) 
![forks](https://img.shields.io/github/forks/bb33bb/CVE-2022-22954-VMware-RCE.svg) 
2022-04-12T13:21:37Z

- [https://github.com/corelight/cve-2022-22954](https://github.com/corelight/cve-2022-22954) :  
![starts](https://img.shields.io/github/stars/corelight/cve-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/corelight/cve-2022-22954.svg) 
2024-10-25T12:23:15Z

- [https://github.com/mumu2020629/-CVE-2022-22954-scanner](https://github.com/mumu2020629/-CVE-2022-22954-scanner) :  
![starts](https://img.shields.io/github/stars/mumu2020629/-CVE-2022-22954-scanner.svg) 
![forks](https://img.shields.io/github/forks/mumu2020629/-CVE-2022-22954-scanner.svg) 
2022-04-14T13:19:28Z

- [https://github.com/MSeymenD/CVE-2022-22954-Testi](https://github.com/MSeymenD/CVE-2022-22954-Testi) :  
![starts](https://img.shields.io/github/stars/MSeymenD/CVE-2022-22954-Testi.svg) 
![forks](https://img.shields.io/github/forks/MSeymenD/CVE-2022-22954-Testi.svg) 
2022-04-12T09:44:09Z

- [https://github.com/emilyastranova/VMware-CVE-2022-22954-Command-Injector](https://github.com/emilyastranova/VMware-CVE-2022-22954-Command-Injector) :  
![starts](https://img.shields.io/github/stars/emilyastranova/VMware-CVE-2022-22954-Command-Injector.svg) 
![forks](https://img.shields.io/github/forks/emilyastranova/VMware-CVE-2022-22954-Command-Injector.svg) 
2022-04-15T00:11:50Z

- [https://github.com/secfb/CVE-2022-22954](https://github.com/secfb/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/secfb/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/secfb/CVE-2022-22954.svg) 
2022-06-01T23:53:17Z

- [https://github.com/lucksec/VMware-CVE-2022-22954](https://github.com/lucksec/VMware-CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/lucksec/VMware-CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/lucksec/VMware-CVE-2022-22954.svg) 
2022-04-12T06:46:33Z

- [https://github.com/nguyenv1nK/CVE-2022-22954](https://github.com/nguyenv1nK/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/nguyenv1nK/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/nguyenv1nK/CVE-2022-22954.svg) 
2022-05-05T10:43:48Z

- [https://github.com/arzuozkan/CVE-2022-22954](https://github.com/arzuozkan/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/arzuozkan/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/arzuozkan/CVE-2022-22954.svg) 
2022-06-11T14:42:18Z

- [https://github.com/Jun-5heng/CVE-2022-22954](https://github.com/Jun-5heng/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/Jun-5heng/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/Jun-5heng/CVE-2022-22954.svg) 
2022-04-19T06:38:58Z

- [https://github.com/amit-pathak009/CVE-2022-22954](https://github.com/amit-pathak009/CVE-2022-22954) :  
![starts](https://img.shields.io/github/stars/amit-pathak009/CVE-2022-22954.svg) 
![forks](https://img.shields.io/github/forks/amit-pathak009/CVE-2022-22954.svg) 
2022-06-02T01:44:15Z

- [https://github.com/mhurts/CVE-2022-22954-POC](https://github.com/mhurts/CVE-2022-22954-POC) :  
![starts](https://img.shields.io/github/stars/mhurts/CVE-2022-22954-POC.svg) 
![forks](https://img.shields.io/github/forks/mhurts/CVE-2022-22954-POC.svg) 
2022-04-15T02:33:01Z

- [https://github.com/amit-pathak009/CVE-2022-22954-PoC](https://github.com/amit-pathak009/CVE-2022-22954-PoC) :  
![starts](https://img.shields.io/github/stars/amit-pathak009/CVE-2022-22954-PoC.svg) 
![forks](https://img.shields.io/github/forks/amit-pathak009/CVE-2022-22954-PoC.svg) 
2022-06-01T22:41:06Z

## CVE-2022-22947
 In spring cloud gateway versions prior to 3.1.1+ and 3.0.7+ , applications are vulnerable to a code injection attack when the Gateway Actuator endpoint is enabled, exposed and unsecured. A remote attacker could make a maliciously crafted request that could allow arbitrary remote execution on the remote host.

- [https://github.com/AabyssZG/SpringBoot-Scan](https://github.com/AabyssZG/SpringBoot-Scan) :  
![starts](https://img.shields.io/github/stars/AabyssZG/SpringBoot-Scan.svg) 
![forks](https://img.shields.io/github/forks/AabyssZG/SpringBoot-Scan.svg) 
2025-01-12T09:50:06Z

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/lucksec/Spring-Cloud-Gateway-CVE-2022-22947](https://github.com/lucksec/Spring-Cloud-Gateway-CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/lucksec/Spring-Cloud-Gateway-CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/lucksec/Spring-Cloud-Gateway-CVE-2022-22947.svg) 
2022-03-03T14:03:30Z

- [https://github.com/whwlsfb/cve-2022-22947-godzilla-memshell](https://github.com/whwlsfb/cve-2022-22947-godzilla-memshell) :  
![starts](https://img.shields.io/github/stars/whwlsfb/cve-2022-22947-godzilla-memshell.svg) 
![forks](https://img.shields.io/github/forks/whwlsfb/cve-2022-22947-godzilla-memshell.svg) 
2022-04-26T05:55:58Z

- [https://github.com/tpt11fb/SpringVulScan](https://github.com/tpt11fb/SpringVulScan) :  
![starts](https://img.shields.io/github/stars/tpt11fb/SpringVulScan.svg) 
![forks](https://img.shields.io/github/forks/tpt11fb/SpringVulScan.svg) 
2023-01-23T13:00:34Z

- [https://github.com/Axx8/CVE-2022-22947_Rce_Exp](https://github.com/Axx8/CVE-2022-22947_Rce_Exp) :  
![starts](https://img.shields.io/github/stars/Axx8/CVE-2022-22947_Rce_Exp.svg) 
![forks](https://img.shields.io/github/forks/Axx8/CVE-2022-22947_Rce_Exp.svg) 
2022-11-14T01:34:04Z

- [https://github.com/tangxiaofeng7/CVE-2022-22947-Spring-Cloud-Gateway](https://github.com/tangxiaofeng7/CVE-2022-22947-Spring-Cloud-Gateway) :  
![starts](https://img.shields.io/github/stars/tangxiaofeng7/CVE-2022-22947-Spring-Cloud-Gateway.svg) 
![forks](https://img.shields.io/github/forks/tangxiaofeng7/CVE-2022-22947-Spring-Cloud-Gateway.svg) 
2022-03-04T10:49:00Z

- [https://github.com/0730Nophone/CVE-2022-22947-](https://github.com/0730Nophone/CVE-2022-22947-) :  
![starts](https://img.shields.io/github/stars/0730Nophone/CVE-2022-22947-.svg) 
![forks](https://img.shields.io/github/forks/0730Nophone/CVE-2022-22947-.svg) 
2022-05-16T15:33:37Z

- [https://github.com/crowsec-edtech/CVE-2022-22947](https://github.com/crowsec-edtech/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/crowsec-edtech/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/crowsec-edtech/CVE-2022-22947.svg) 
2022-03-04T21:10:45Z

- [https://github.com/0x7eTeam/CVE-2022-22947](https://github.com/0x7eTeam/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/0x7eTeam/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/0x7eTeam/CVE-2022-22947.svg) 
2022-03-08T09:36:31Z

- [https://github.com/XuCcc/VulEnv](https://github.com/XuCcc/VulEnv) :  
![starts](https://img.shields.io/github/stars/XuCcc/VulEnv.svg) 
![forks](https://img.shields.io/github/forks/XuCcc/VulEnv.svg) 
2023-08-13T14:36:28Z

- [https://github.com/Tas9er/SpringCloudGatewayRCE](https://github.com/Tas9er/SpringCloudGatewayRCE) :  
![starts](https://img.shields.io/github/stars/Tas9er/SpringCloudGatewayRCE.svg) 
![forks](https://img.shields.io/github/forks/Tas9er/SpringCloudGatewayRCE.svg) 
2022-03-03T20:44:25Z

- [https://github.com/Zh0um1/CVE-2022-22947](https://github.com/Zh0um1/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Zh0um1/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Zh0um1/CVE-2022-22947.svg) 
2023-06-21T15:43:11Z

- [https://github.com/24-2021/EXP-POC](https://github.com/24-2021/EXP-POC) :  
![starts](https://img.shields.io/github/stars/24-2021/EXP-POC.svg) 
![forks](https://img.shields.io/github/forks/24-2021/EXP-POC.svg) 
2023-01-11T06:20:26Z

- [https://github.com/viemsr/spring_cloud_gateway_memshell](https://github.com/viemsr/spring_cloud_gateway_memshell) :  
![starts](https://img.shields.io/github/stars/viemsr/spring_cloud_gateway_memshell.svg) 
![forks](https://img.shields.io/github/forks/viemsr/spring_cloud_gateway_memshell.svg) 
2022-03-18T07:17:45Z

- [https://github.com/Enokiy/cve-2022-22947-spring-cloud-gateway](https://github.com/Enokiy/cve-2022-22947-spring-cloud-gateway) :  
![starts](https://img.shields.io/github/stars/Enokiy/cve-2022-22947-spring-cloud-gateway.svg) 
![forks](https://img.shields.io/github/forks/Enokiy/cve-2022-22947-spring-cloud-gateway.svg) 
2022-04-07T01:21:34Z

- [https://github.com/B0rn2d/Spring-Cloud-Gateway-Nacos](https://github.com/B0rn2d/Spring-Cloud-Gateway-Nacos) :  
![starts](https://img.shields.io/github/stars/B0rn2d/Spring-Cloud-Gateway-Nacos.svg) 
![forks](https://img.shields.io/github/forks/B0rn2d/Spring-Cloud-Gateway-Nacos.svg) 
2022-06-25T13:43:53Z

- [https://github.com/M0ge/CVE-2022-22947-Spring-Cloud-Gateway-SpelRCE](https://github.com/M0ge/CVE-2022-22947-Spring-Cloud-Gateway-SpelRCE) :  
![starts](https://img.shields.io/github/stars/M0ge/CVE-2022-22947-Spring-Cloud-Gateway-SpelRCE.svg) 
![forks](https://img.shields.io/github/forks/M0ge/CVE-2022-22947-Spring-Cloud-Gateway-SpelRCE.svg) 
2022-03-09T05:43:23Z

- [https://github.com/Wrin9/CVE-2022-22947](https://github.com/Wrin9/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Wrin9/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Wrin9/CVE-2022-22947.svg) 
2022-03-17T09:58:23Z

- [https://github.com/k3rwin/spring-cloud-gateway-rce](https://github.com/k3rwin/spring-cloud-gateway-rce) :  
![starts](https://img.shields.io/github/stars/k3rwin/spring-cloud-gateway-rce.svg) 
![forks](https://img.shields.io/github/forks/k3rwin/spring-cloud-gateway-rce.svg) 
2022-07-13T02:38:10Z

- [https://github.com/4nNns/CVE-2022-22947](https://github.com/4nNns/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/4nNns/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/4nNns/CVE-2022-22947.svg) 
2022-09-16T08:00:46Z

- [https://github.com/twseptian/cve-2022-22947](https://github.com/twseptian/cve-2022-22947) :  
![starts](https://img.shields.io/github/stars/twseptian/cve-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/twseptian/cve-2022-22947.svg) 
2022-04-15T15:48:07Z

- [https://github.com/Vulnmachines/spring-cve-2022-22947](https://github.com/Vulnmachines/spring-cve-2022-22947) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/spring-cve-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/spring-cve-2022-22947.svg) 
2022-03-03T11:27:18Z

- [https://github.com/wjl110/Spring_CVE_2022_22947](https://github.com/wjl110/Spring_CVE_2022_22947) :  
![starts](https://img.shields.io/github/stars/wjl110/Spring_CVE_2022_22947.svg) 
![forks](https://img.shields.io/github/forks/wjl110/Spring_CVE_2022_22947.svg) 
2022-03-04T13:49:25Z

- [https://github.com/WuliRuler/SBSCAN](https://github.com/WuliRuler/SBSCAN) :  
![starts](https://img.shields.io/github/stars/WuliRuler/SBSCAN.svg) 
![forks](https://img.shields.io/github/forks/WuliRuler/SBSCAN.svg) 
2024-11-03T07:56:43Z

- [https://github.com/dingxiao77/-cve-2022-22947-](https://github.com/dingxiao77/-cve-2022-22947-) :  
![starts](https://img.shields.io/github/stars/dingxiao77/-cve-2022-22947-.svg) 
![forks](https://img.shields.io/github/forks/dingxiao77/-cve-2022-22947-.svg) 
2022-03-04T08:14:45Z

- [https://github.com/SiJiDo/CVE-2022-22947](https://github.com/SiJiDo/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/SiJiDo/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/SiJiDo/CVE-2022-22947.svg) 
2022-08-23T06:40:24Z

- [https://github.com/hunzi0/CVE-2022-22947-Rce_POC](https://github.com/hunzi0/CVE-2022-22947-Rce_POC) :  
![starts](https://img.shields.io/github/stars/hunzi0/CVE-2022-22947-Rce_POC.svg) 
![forks](https://img.shields.io/github/forks/hunzi0/CVE-2022-22947-Rce_POC.svg) 
2022-03-04T15:15:43Z

- [https://github.com/mrknow001/CVE-2022-22947](https://github.com/mrknow001/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/mrknow001/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/mrknow001/CVE-2022-22947.svg) 
2022-03-08T07:05:18Z

- [https://github.com/Arrnitage/CVE-2022-22947_exp](https://github.com/Arrnitage/CVE-2022-22947_exp) :  
![starts](https://img.shields.io/github/stars/Arrnitage/CVE-2022-22947_exp.svg) 
![forks](https://img.shields.io/github/forks/Arrnitage/CVE-2022-22947_exp.svg) 
2022-03-10T08:43:59Z

- [https://github.com/darkb1rd/cve-2022-22947](https://github.com/darkb1rd/cve-2022-22947) :  
![starts](https://img.shields.io/github/stars/darkb1rd/cve-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/darkb1rd/cve-2022-22947.svg) 
2022-03-07T15:28:16Z

- [https://github.com/YutuSec/SpEL](https://github.com/YutuSec/SpEL) :  
![starts](https://img.shields.io/github/stars/YutuSec/SpEL.svg) 
![forks](https://img.shields.io/github/forks/YutuSec/SpEL.svg) 
2022-03-08T02:09:38Z

- [https://github.com/Greetdawn/CVE-2022-22947](https://github.com/Greetdawn/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Greetdawn/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Greetdawn/CVE-2022-22947.svg) 
2022-03-04T03:22:02Z

- [https://github.com/anansec/CVE-2022-22947_EXP](https://github.com/anansec/CVE-2022-22947_EXP) :  
![starts](https://img.shields.io/github/stars/anansec/CVE-2022-22947_EXP.svg) 
![forks](https://img.shields.io/github/forks/anansec/CVE-2022-22947_EXP.svg) 
2022-05-19T16:26:41Z

- [https://github.com/sagaryadav8742/springcloudRCE](https://github.com/sagaryadav8742/springcloudRCE) :  
![starts](https://img.shields.io/github/stars/sagaryadav8742/springcloudRCE.svg) 
![forks](https://img.shields.io/github/forks/sagaryadav8742/springcloudRCE.svg) 
2022-03-30T23:35:43Z

- [https://github.com/LY613313/CVE-2022-22947](https://github.com/LY613313/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/LY613313/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/LY613313/CVE-2022-22947.svg) 
2022-08-03T03:09:05Z

- [https://github.com/nu0l/cve-2022-22947](https://github.com/nu0l/cve-2022-22947) :  
![starts](https://img.shields.io/github/stars/nu0l/cve-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/nu0l/cve-2022-22947.svg) 
2022-03-04T10:33:41Z

- [https://github.com/expzhizhuo/Burp_VulPscan](https://github.com/expzhizhuo/Burp_VulPscan) :  
![starts](https://img.shields.io/github/stars/expzhizhuo/Burp_VulPscan.svg) 
![forks](https://img.shields.io/github/forks/expzhizhuo/Burp_VulPscan.svg) 
2022-04-11T11:32:17Z

- [https://github.com/Le1a/CVE-2022-22947](https://github.com/Le1a/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Le1a/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Le1a/CVE-2022-22947.svg) 
2023-05-27T04:38:31Z

- [https://github.com/stayfoolish777/CVE-2022-22947-POC](https://github.com/stayfoolish777/CVE-2022-22947-POC) :  
![starts](https://img.shields.io/github/stars/stayfoolish777/CVE-2022-22947-POC.svg) 
![forks](https://img.shields.io/github/forks/stayfoolish777/CVE-2022-22947-POC.svg) 
2022-06-09T09:03:44Z

- [https://github.com/dbgee/CVE-2022-22947](https://github.com/dbgee/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/dbgee/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/dbgee/CVE-2022-22947.svg) 
2022-03-04T09:54:40Z

- [https://github.com/22ke/CVE-2022-22947](https://github.com/22ke/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/22ke/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/22ke/CVE-2022-22947.svg) 
2022-03-05T06:39:43Z

- [https://github.com/Nathaniel1025/CVE-2022-22947](https://github.com/Nathaniel1025/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Nathaniel1025/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Nathaniel1025/CVE-2022-22947.svg) 
2022-03-25T12:57:10Z

- [https://github.com/aesm1p/CVE-2022-22947-POC-Reproduce](https://github.com/aesm1p/CVE-2022-22947-POC-Reproduce) :  
![starts](https://img.shields.io/github/stars/aesm1p/CVE-2022-22947-POC-Reproduce.svg) 
![forks](https://img.shields.io/github/forks/aesm1p/CVE-2022-22947-POC-Reproduce.svg) 
2022-04-05T10:14:01Z

- [https://github.com/Jun-5heng/CVE-2022-22947](https://github.com/Jun-5heng/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Jun-5heng/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Jun-5heng/CVE-2022-22947.svg) 
2022-03-29T06:10:22Z

- [https://github.com/bysinks/CVE-2022-22947](https://github.com/bysinks/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/bysinks/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/bysinks/CVE-2022-22947.svg) 
2022-03-15T08:52:38Z

- [https://github.com/qq87234770/CVE-2022-22947](https://github.com/qq87234770/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/qq87234770/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/qq87234770/CVE-2022-22947.svg) 
2022-11-15T09:16:04Z

- [https://github.com/kmahyyg/CVE-2022-22947](https://github.com/kmahyyg/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/kmahyyg/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/kmahyyg/CVE-2022-22947.svg) 
2022-07-12T08:24:09Z

- [https://github.com/Vancomycin-g/CVE-2022-22947](https://github.com/Vancomycin-g/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Vancomycin-g/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Vancomycin-g/CVE-2022-22947.svg) 
2022-03-30T15:43:21Z

- [https://github.com/talentsec/Spring-Cloud-Gateway-CVE-2022-22947](https://github.com/talentsec/Spring-Cloud-Gateway-CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/talentsec/Spring-Cloud-Gateway-CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/talentsec/Spring-Cloud-Gateway-CVE-2022-22947.svg) 
2022-04-01T10:24:44Z

- [https://github.com/Wrong-pixel/CVE-2022-22947-exp](https://github.com/Wrong-pixel/CVE-2022-22947-exp) :  
![starts](https://img.shields.io/github/stars/Wrong-pixel/CVE-2022-22947-exp.svg) 
![forks](https://img.shields.io/github/forks/Wrong-pixel/CVE-2022-22947-exp.svg) 
2022-05-29T01:08:10Z

- [https://github.com/nanaao/CVE-2022-22947-POC](https://github.com/nanaao/CVE-2022-22947-POC) :  
![starts](https://img.shields.io/github/stars/nanaao/CVE-2022-22947-POC.svg) 
![forks](https://img.shields.io/github/forks/nanaao/CVE-2022-22947-POC.svg) 
2022-03-04T11:36:47Z

- [https://github.com/scopion/cve-2022-22947](https://github.com/scopion/cve-2022-22947) :  
![starts](https://img.shields.io/github/stars/scopion/cve-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/scopion/cve-2022-22947.svg) 
2022-03-03T09:27:42Z

- [https://github.com/Summer177/Spring-Cloud-Gateway-CVE-2022-22947](https://github.com/Summer177/Spring-Cloud-Gateway-CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Summer177/Spring-Cloud-Gateway-CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Summer177/Spring-Cloud-Gateway-CVE-2022-22947.svg) 
2022-03-04T05:19:21Z

- [https://github.com/hh-hunter/cve-2022-22947-docker](https://github.com/hh-hunter/cve-2022-22947-docker) :  
![starts](https://img.shields.io/github/stars/hh-hunter/cve-2022-22947-docker.svg) 
![forks](https://img.shields.io/github/forks/hh-hunter/cve-2022-22947-docker.svg) 
2022-03-11T02:53:36Z

- [https://github.com/BerMalBerIst/CVE-2022-22947](https://github.com/BerMalBerIst/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/BerMalBerIst/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/BerMalBerIst/CVE-2022-22947.svg) 
2022-03-04T05:33:47Z

- [https://github.com/cc3305/CVE-2022-22947](https://github.com/cc3305/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/cc3305/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/cc3305/CVE-2022-22947.svg) 
2024-07-27T20:16:34Z

- [https://github.com/fbion/CVE-2022-22947](https://github.com/fbion/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/fbion/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/fbion/CVE-2022-22947.svg) 
2022-03-04T18:45:41Z

- [https://github.com/Sumitpathania03/CVE-2022-22947](https://github.com/Sumitpathania03/CVE-2022-22947) :  
![starts](https://img.shields.io/github/stars/Sumitpathania03/CVE-2022-22947.svg) 
![forks](https://img.shields.io/github/forks/Sumitpathania03/CVE-2022-22947.svg) 
2024-04-02T06:35:30Z

- [https://github.com/PaoPaoLong-lab/Spring-CVE-2022-22947-](https://github.com/PaoPaoLong-lab/Spring-CVE-2022-22947-) :  
![starts](https://img.shields.io/github/stars/PaoPaoLong-lab/Spring-CVE-2022-22947-.svg) 
![forks](https://img.shields.io/github/forks/PaoPaoLong-lab/Spring-CVE-2022-22947-.svg) 
2022-03-10T10:46:32Z

- [https://github.com/flying0er/CVE-2022-22947-goby](https://github.com/flying0er/CVE-2022-22947-goby) :  
![starts](https://img.shields.io/github/stars/flying0er/CVE-2022-22947-goby.svg) 
![forks](https://img.shields.io/github/forks/flying0er/CVE-2022-22947-goby.svg) 
2022-03-04T05:47:14Z

- [https://github.com/scopion/CVE-2022-22947-exp](https://github.com/scopion/CVE-2022-22947-exp) :  
![starts](https://img.shields.io/github/stars/scopion/CVE-2022-22947-exp.svg) 
![forks](https://img.shields.io/github/forks/scopion/CVE-2022-22947-exp.svg) 
2022-03-30T03:15:09Z

- [https://github.com/ba1ma0/Spring-Cloud-GateWay-CVE-2022-22947-demon-code](https://github.com/ba1ma0/Spring-Cloud-GateWay-CVE-2022-22947-demon-code) :  
![starts](https://img.shields.io/github/stars/ba1ma0/Spring-Cloud-GateWay-CVE-2022-22947-demon-code.svg) 
![forks](https://img.shields.io/github/forks/ba1ma0/Spring-Cloud-GateWay-CVE-2022-22947-demon-code.svg) 
2022-03-09T07:44:53Z

## CVE-2022-1388
 On F5 BIG-IP 16.1.x versions prior to 16.1.2.2, 15.1.x versions prior to 15.1.5.1, 14.1.x versions prior to 14.1.4.6, 13.1.x versions prior to 13.1.5, and all 12.1.x and 11.6.x versions, undisclosed requests may bypass iControl REST authentication. Note: Software versions which have reached End of Technical Support (EoTS) are not evaluated

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/horizon3ai/CVE-2022-1388](https://github.com/horizon3ai/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/horizon3ai/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/horizon3ai/CVE-2022-1388.svg) 
2022-05-09T20:52:07Z

- [https://github.com/CLincat/vulcat](https://github.com/CLincat/vulcat) :  
![starts](https://img.shields.io/github/stars/CLincat/vulcat.svg) 
![forks](https://img.shields.io/github/forks/CLincat/vulcat.svg) 
2023-12-04T06:43:07Z

- [https://github.com/doocop/CVE-2022-1388-EXP](https://github.com/doocop/CVE-2022-1388-EXP) :  
![starts](https://img.shields.io/github/stars/doocop/CVE-2022-1388-EXP.svg) 
![forks](https://img.shields.io/github/forks/doocop/CVE-2022-1388-EXP.svg) 
2022-05-09T11:15:27Z

- [https://github.com/alt3kx/CVE-2022-1388_PoC](https://github.com/alt3kx/CVE-2022-1388_PoC) :  
![starts](https://img.shields.io/github/stars/alt3kx/CVE-2022-1388_PoC.svg) 
![forks](https://img.shields.io/github/forks/alt3kx/CVE-2022-1388_PoC.svg) 
2022-05-16T12:40:51Z

- [https://github.com/0xf4n9x/CVE-2022-1388](https://github.com/0xf4n9x/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/0xf4n9x/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/0xf4n9x/CVE-2022-1388.svg) 
2022-06-28T18:14:40Z

- [https://github.com/ZephrFish/F5-CVE-2022-1388-Exploit](https://github.com/ZephrFish/F5-CVE-2022-1388-Exploit) :  
![starts](https://img.shields.io/github/stars/ZephrFish/F5-CVE-2022-1388-Exploit.svg) 
![forks](https://img.shields.io/github/forks/ZephrFish/F5-CVE-2022-1388-Exploit.svg) 
2022-05-26T23:51:01Z

- [https://github.com/sherlocksecurity/CVE-2022-1388-Exploit-POC](https://github.com/sherlocksecurity/CVE-2022-1388-Exploit-POC) :  
![starts](https://img.shields.io/github/stars/sherlocksecurity/CVE-2022-1388-Exploit-POC.svg) 
![forks](https://img.shields.io/github/forks/sherlocksecurity/CVE-2022-1388-Exploit-POC.svg) 
2022-05-15T02:30:40Z

- [https://github.com/numanturle/CVE-2022-1388](https://github.com/numanturle/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/numanturle/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/numanturle/CVE-2022-1388.svg) 
2022-05-09T21:09:45Z

- [https://github.com/Al1ex/CVE-2022-1388](https://github.com/Al1ex/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Al1ex/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Al1ex/CVE-2022-1388.svg) 
2022-05-09T14:20:40Z

- [https://github.com/jheeree/CVE-2022-1388-checker](https://github.com/jheeree/CVE-2022-1388-checker) :  
![starts](https://img.shields.io/github/stars/jheeree/CVE-2022-1388-checker.svg) 
![forks](https://img.shields.io/github/forks/jheeree/CVE-2022-1388-checker.svg) 
2022-05-05T22:49:40Z

- [https://github.com/MrCl0wnLab/Nuclei-Template-CVE-2022-1388-BIG-IP-iControl-REST-Exposed](https://github.com/MrCl0wnLab/Nuclei-Template-CVE-2022-1388-BIG-IP-iControl-REST-Exposed) :  
![starts](https://img.shields.io/github/stars/MrCl0wnLab/Nuclei-Template-CVE-2022-1388-BIG-IP-iControl-REST-Exposed.svg) 
![forks](https://img.shields.io/github/forks/MrCl0wnLab/Nuclei-Template-CVE-2022-1388-BIG-IP-iControl-REST-Exposed.svg) 
2022-05-06T15:33:14Z

- [https://github.com/justakazh/CVE-2022-1388](https://github.com/justakazh/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/justakazh/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/justakazh/CVE-2022-1388.svg) 
2022-05-13T10:22:08Z

- [https://github.com/PsychoSec2/CVE-2022-1388-POC](https://github.com/PsychoSec2/CVE-2022-1388-POC) :  
![starts](https://img.shields.io/github/stars/PsychoSec2/CVE-2022-1388-POC.svg) 
![forks](https://img.shields.io/github/forks/PsychoSec2/CVE-2022-1388-POC.svg) 
2022-05-15T16:34:54Z

- [https://github.com/Zeyad-Azima/CVE-2022-1388](https://github.com/Zeyad-Azima/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Zeyad-Azima/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Zeyad-Azima/CVE-2022-1388.svg) 
2023-05-11T02:55:01Z

- [https://github.com/west9b/F5-BIG-IP-POC](https://github.com/west9b/F5-BIG-IP-POC) :  
![starts](https://img.shields.io/github/stars/west9b/F5-BIG-IP-POC.svg) 
![forks](https://img.shields.io/github/forks/west9b/F5-BIG-IP-POC.svg) 
2022-07-30T00:16:29Z

- [https://github.com/qusaialhaddad/F5-BigIP-CVE-2022-1388](https://github.com/qusaialhaddad/F5-BigIP-CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/qusaialhaddad/F5-BigIP-CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/qusaialhaddad/F5-BigIP-CVE-2022-1388.svg) 
2022-05-10T05:00:43Z

- [https://github.com/Henry4E36/CVE-2022-1388](https://github.com/Henry4E36/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Henry4E36/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Henry4E36/CVE-2022-1388.svg) 
2022-08-22T01:20:14Z

- [https://github.com/blind-intruder/CVE-2022-1388-RCE-checker-and-POC-Exploit](https://github.com/blind-intruder/CVE-2022-1388-RCE-checker-and-POC-Exploit) :  
![starts](https://img.shields.io/github/stars/blind-intruder/CVE-2022-1388-RCE-checker-and-POC-Exploit.svg) 
![forks](https://img.shields.io/github/forks/blind-intruder/CVE-2022-1388-RCE-checker-and-POC-Exploit.svg) 
2022-05-12T11:46:56Z

- [https://github.com/vaelwolf/CVE-2022-1388](https://github.com/vaelwolf/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/vaelwolf/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/vaelwolf/CVE-2022-1388.svg) 
2022-12-25T02:43:04Z

- [https://github.com/MrCl0wnLab/Nuclei-Template-Exploit-F5-BIG-IP-iControl-REST-Auth-Bypass-RCE-Command-Parameter](https://github.com/MrCl0wnLab/Nuclei-Template-Exploit-F5-BIG-IP-iControl-REST-Auth-Bypass-RCE-Command-Parameter) :  
![starts](https://img.shields.io/github/stars/MrCl0wnLab/Nuclei-Template-Exploit-F5-BIG-IP-iControl-REST-Auth-Bypass-RCE-Command-Parameter.svg) 
![forks](https://img.shields.io/github/forks/MrCl0wnLab/Nuclei-Template-Exploit-F5-BIG-IP-iControl-REST-Auth-Bypass-RCE-Command-Parameter.svg) 
2022-05-12T17:06:29Z

- [https://github.com/Vulnmachines/F5-Big-IP-CVE-2022-1388](https://github.com/Vulnmachines/F5-Big-IP-CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Vulnmachines/F5-Big-IP-CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Vulnmachines/F5-Big-IP-CVE-2022-1388.svg) 
2022-07-26T05:18:58Z

- [https://github.com/Stonzyy/Exploit-F5-CVE-2022-1388](https://github.com/Stonzyy/Exploit-F5-CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Stonzyy/Exploit-F5-CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Stonzyy/Exploit-F5-CVE-2022-1388.svg) 
2022-05-10T08:38:58Z

- [https://github.com/Angus-Team/F5-BIG-IP-RCE-CVE-2022-1388](https://github.com/Angus-Team/F5-BIG-IP-RCE-CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Angus-Team/F5-BIG-IP-RCE-CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Angus-Team/F5-BIG-IP-RCE-CVE-2022-1388.svg) 
2022-05-10T05:35:23Z

- [https://github.com/AmirHoseinTangsiriNET/CVE-2022-1388-Scanner](https://github.com/AmirHoseinTangsiriNET/CVE-2022-1388-Scanner) :  
![starts](https://img.shields.io/github/stars/AmirHoseinTangsiriNET/CVE-2022-1388-Scanner.svg) 
![forks](https://img.shields.io/github/forks/AmirHoseinTangsiriNET/CVE-2022-1388-Scanner.svg) 
2022-05-27T11:27:32Z

- [https://github.com/0x7eTeam/CVE-2022-1388-PocExp](https://github.com/0x7eTeam/CVE-2022-1388-PocExp) :  
![starts](https://img.shields.io/github/stars/0x7eTeam/CVE-2022-1388-PocExp.svg) 
![forks](https://img.shields.io/github/forks/0x7eTeam/CVE-2022-1388-PocExp.svg) 
2022-05-16T14:02:29Z

- [https://github.com/gotr00t0day/CVE-2022-1388](https://github.com/gotr00t0day/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/gotr00t0day/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/gotr00t0day/CVE-2022-1388.svg) 
2024-04-30T01:12:19Z

- [https://github.com/bandit92/CVE2022-1388_TestAPI](https://github.com/bandit92/CVE2022-1388_TestAPI) :  
![starts](https://img.shields.io/github/stars/bandit92/CVE2022-1388_TestAPI.svg) 
![forks](https://img.shields.io/github/forks/bandit92/CVE2022-1388_TestAPI.svg) 
2022-05-10T15:37:42Z

- [https://github.com/revanmalang/CVE-2022-1388](https://github.com/revanmalang/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/revanmalang/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/revanmalang/CVE-2022-1388.svg) 
2022-11-30T04:07:51Z

- [https://github.com/aancw/CVE-2022-1388-rs](https://github.com/aancw/CVE-2022-1388-rs) :  
![starts](https://img.shields.io/github/stars/aancw/CVE-2022-1388-rs.svg) 
![forks](https://img.shields.io/github/forks/aancw/CVE-2022-1388-rs.svg) 
2022-06-01T09:09:07Z

- [https://github.com/XiaomingX/cve-2022-1388-poc](https://github.com/XiaomingX/cve-2022-1388-poc) :  
![starts](https://img.shields.io/github/stars/XiaomingX/cve-2022-1388-poc.svg) 
![forks](https://img.shields.io/github/forks/XiaomingX/cve-2022-1388-poc.svg) 
2024-11-23T05:41:08Z

- [https://github.com/saucer-man/CVE-2022-1388](https://github.com/saucer-man/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/saucer-man/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/saucer-man/CVE-2022-1388.svg) 
2022-05-09T16:14:49Z

- [https://github.com/EvilLizard666/CVE-2022-1388](https://github.com/EvilLizard666/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/EvilLizard666/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/EvilLizard666/CVE-2022-1388.svg) 
2023-01-22T02:08:58Z

- [https://github.com/superzerosec/CVE-2022-1388](https://github.com/superzerosec/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/superzerosec/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/superzerosec/CVE-2022-1388.svg) 
2022-05-10T04:53:23Z

- [https://github.com/savior-only/CVE-2022-1388](https://github.com/savior-only/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/savior-only/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/savior-only/CVE-2022-1388.svg) 
2022-05-13T18:18:48Z

- [https://github.com/devengpk/CVE-2022-1388](https://github.com/devengpk/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/devengpk/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/devengpk/CVE-2022-1388.svg) 
2022-12-21T17:35:41Z

- [https://github.com/forktheplanet/CVE-2022-1388](https://github.com/forktheplanet/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/forktheplanet/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/forktheplanet/CVE-2022-1388.svg) 
2023-05-19T05:55:52Z

- [https://github.com/nvk0x/CVE-2022-1388-exploit](https://github.com/nvk0x/CVE-2022-1388-exploit) :  
![starts](https://img.shields.io/github/stars/nvk0x/CVE-2022-1388-exploit.svg) 
![forks](https://img.shields.io/github/forks/nvk0x/CVE-2022-1388-exploit.svg) 
2024-01-03T12:28:54Z

- [https://github.com/Chocapikk/CVE-2022-1388](https://github.com/Chocapikk/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Chocapikk/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Chocapikk/CVE-2022-1388.svg) 
2022-10-16T15:21:17Z

- [https://github.com/thatonesecguy/CVE-2022-1388-Exploit](https://github.com/thatonesecguy/CVE-2022-1388-Exploit) :  
![starts](https://img.shields.io/github/stars/thatonesecguy/CVE-2022-1388-Exploit.svg) 
![forks](https://img.shields.io/github/forks/thatonesecguy/CVE-2022-1388-Exploit.svg) 
2022-05-10T15:28:13Z

- [https://github.com/yukar1z0e/CVE-2022-1388](https://github.com/yukar1z0e/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/yukar1z0e/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/yukar1z0e/CVE-2022-1388.svg) 
2022-05-09T10:07:45Z

- [https://github.com/chesterblue/CVE-2022-1388](https://github.com/chesterblue/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/chesterblue/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/chesterblue/CVE-2022-1388.svg) 
2022-05-10T04:58:30Z

- [https://github.com/SecTheBit/CVE-2022-1388](https://github.com/SecTheBit/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/SecTheBit/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/SecTheBit/CVE-2022-1388.svg) 
2022-05-12T12:32:38Z

- [https://github.com/amitlttwo/CVE-2022-1388](https://github.com/amitlttwo/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/amitlttwo/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/amitlttwo/CVE-2022-1388.svg) 
2023-02-07T11:02:37Z

- [https://github.com/shamo0/CVE-2022-1388](https://github.com/shamo0/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/shamo0/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/shamo0/CVE-2022-1388.svg) 
2022-05-10T09:09:23Z

- [https://github.com/nico989/CVE-2022-1388](https://github.com/nico989/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/nico989/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/nico989/CVE-2022-1388.svg) 
2024-01-12T22:42:14Z

- [https://github.com/0xAgun/CVE-2022-1388](https://github.com/0xAgun/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/0xAgun/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/0xAgun/CVE-2022-1388.svg) 
2022-05-14T15:01:16Z

- [https://github.com/Luchoane/CVE-2022-1388_refresh](https://github.com/Luchoane/CVE-2022-1388_refresh) :  
![starts](https://img.shields.io/github/stars/Luchoane/CVE-2022-1388_refresh.svg) 
![forks](https://img.shields.io/github/forks/Luchoane/CVE-2022-1388_refresh.svg) 
2022-07-01T20:04:27Z

- [https://github.com/LinJacck/CVE-2022-1388-EXP](https://github.com/LinJacck/CVE-2022-1388-EXP) :  
![starts](https://img.shields.io/github/stars/LinJacck/CVE-2022-1388-EXP.svg) 
![forks](https://img.shields.io/github/forks/LinJacck/CVE-2022-1388-EXP.svg) 
2022-05-10T08:14:49Z

- [https://github.com/iveresk/cve-2022-1388-1veresk](https://github.com/iveresk/cve-2022-1388-1veresk) :  
![starts](https://img.shields.io/github/stars/iveresk/cve-2022-1388-1veresk.svg) 
![forks](https://img.shields.io/github/forks/iveresk/cve-2022-1388-1veresk.svg) 
2022-05-24T12:39:02Z

- [https://github.com/iveresk/cve-2022-1388-iveresk-command-shell](https://github.com/iveresk/cve-2022-1388-iveresk-command-shell) :  
![starts](https://img.shields.io/github/stars/iveresk/cve-2022-1388-iveresk-command-shell.svg) 
![forks](https://img.shields.io/github/forks/iveresk/cve-2022-1388-iveresk-command-shell.svg) 
2022-05-24T12:39:26Z

- [https://github.com/vesperp/CVE-2022-1388-F5-BIG-IP](https://github.com/vesperp/CVE-2022-1388-F5-BIG-IP) :  
![starts](https://img.shields.io/github/stars/vesperp/CVE-2022-1388-F5-BIG-IP.svg) 
![forks](https://img.shields.io/github/forks/vesperp/CVE-2022-1388-F5-BIG-IP.svg) 
2022-05-18T08:32:27Z

- [https://github.com/j-baines/tippa-my-tongue](https://github.com/j-baines/tippa-my-tongue) :  
![starts](https://img.shields.io/github/stars/j-baines/tippa-my-tongue.svg) 
![forks](https://img.shields.io/github/forks/j-baines/tippa-my-tongue.svg) 
2023-04-12T21:03:44Z

- [https://github.com/li8u99/CVE-2022-1388](https://github.com/li8u99/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/li8u99/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/li8u99/CVE-2022-1388.svg) 
2022-06-20T02:00:06Z

- [https://github.com/pauloink/CVE-2022-1388](https://github.com/pauloink/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/pauloink/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/pauloink/CVE-2022-1388.svg) 
2022-05-11T22:00:12Z

- [https://github.com/sashka3076/F5-BIG-IP-exploit](https://github.com/sashka3076/F5-BIG-IP-exploit) :  
![starts](https://img.shields.io/github/stars/sashka3076/F5-BIG-IP-exploit.svg) 
![forks](https://img.shields.io/github/forks/sashka3076/F5-BIG-IP-exploit.svg) 
2022-05-17T10:45:04Z

- [https://github.com/mr-vill4in/CVE-2022-1388](https://github.com/mr-vill4in/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/mr-vill4in/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/mr-vill4in/CVE-2022-1388.svg) 
2022-05-11T20:15:49Z

- [https://github.com/impost0r/CVE-2022-1388](https://github.com/impost0r/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/impost0r/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/impost0r/CVE-2022-1388.svg) 
2024-09-12T17:27:10Z

- [https://github.com/battleofthebots/refresh](https://github.com/battleofthebots/refresh) :  
![starts](https://img.shields.io/github/stars/battleofthebots/refresh.svg) 
![forks](https://img.shields.io/github/forks/battleofthebots/refresh.svg) 
2023-10-11T22:07:52Z

- [https://github.com/M4fiaB0y/CVE-2022-1388](https://github.com/M4fiaB0y/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/M4fiaB0y/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/M4fiaB0y/CVE-2022-1388.svg) 
2022-12-09T06:51:48Z

- [https://github.com/On-Cyber-War/CVE-2022-1388](https://github.com/On-Cyber-War/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/On-Cyber-War/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/On-Cyber-War/CVE-2022-1388.svg) 
2022-10-25T12:23:50Z

- [https://github.com/jbharucha05/CVE-2022-1388](https://github.com/jbharucha05/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/jbharucha05/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/jbharucha05/CVE-2022-1388.svg) 
2022-07-04T10:37:39Z

- [https://github.com/omnigodz/CVE-2022-1388](https://github.com/omnigodz/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/omnigodz/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/omnigodz/CVE-2022-1388.svg) 
2022-06-08T13:57:39Z

- [https://github.com/Hudi233/CVE-2022-1388](https://github.com/Hudi233/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Hudi233/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Hudi233/CVE-2022-1388.svg) 
2022-05-09T03:35:31Z

- [https://github.com/v4sh25/CVE_2022_1388](https://github.com/v4sh25/CVE_2022_1388) :  
![starts](https://img.shields.io/github/stars/v4sh25/CVE_2022_1388.svg) 
![forks](https://img.shields.io/github/forks/v4sh25/CVE_2022_1388.svg) 
2023-07-21T04:27:13Z

- [https://github.com/Wrin9/CVE-2022-1388](https://github.com/Wrin9/CVE-2022-1388) :  
![starts](https://img.shields.io/github/stars/Wrin9/CVE-2022-1388.svg) 
![forks](https://img.shields.io/github/forks/Wrin9/CVE-2022-1388.svg) 
2022-05-16T01:52:19Z

- [https://github.com/hackeyes/CVE-2022-1388-POC](https://github.com/hackeyes/CVE-2022-1388-POC) :  
![starts](https://img.shields.io/github/stars/hackeyes/CVE-2022-1388-POC.svg) 
![forks](https://img.shields.io/github/forks/hackeyes/CVE-2022-1388-POC.svg) 
2022-05-05T15:30:37Z

- [https://github.com/Osyanina/westone-CVE-2022-1388-scanner](https://github.com/Osyanina/westone-CVE-2022-1388-scanner) :  
![starts](https://img.shields.io/github/stars/Osyanina/westone-CVE-2022-1388-scanner.svg) 
![forks](https://img.shields.io/github/forks/Osyanina/westone-CVE-2022-1388-scanner.svg) 
2022-05-07T12:41:34Z

- [https://github.com/SudeepaShiranthaka/F5-BIG-IP-Remote-Code-Execution-Vulnerability-CVE-2022-1388-A-Case-Study](https://github.com/SudeepaShiranthaka/F5-BIG-IP-Remote-Code-Execution-Vulnerability-CVE-2022-1388-A-Case-Study) :  
![starts](https://img.shields.io/github/stars/SudeepaShiranthaka/F5-BIG-IP-Remote-Code-Execution-Vulnerability-CVE-2022-1388-A-Case-Study.svg) 
![forks](https://img.shields.io/github/forks/SudeepaShiranthaka/F5-BIG-IP-Remote-Code-Execution-Vulnerability-CVE-2022-1388-A-Case-Study.svg) 
2023-07-12T15:54:04Z

## CVE-2021-45232
 In Apache APISIX Dashboard before 2.10.1, the Manager API uses two frameworks and introduces framework `droplet` on the basis of framework `gin`, all APIs and authentication middleware are developed based on framework `droplet`, but some API directly use the interface of framework `gin` thus bypassing the authentication.

- [https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main](https://github.com/peiqiF4ck/WebFrameworkTools-5.1-main) :  
![starts](https://img.shields.io/github/stars/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
![forks](https://img.shields.io/github/forks/peiqiF4ck/WebFrameworkTools-5.1-main.svg) 
2025-02-07T12:43:37Z

- [https://github.com/wuppp/cve-2021-45232-exp](https://github.com/wuppp/cve-2021-45232-exp) :  
![starts](https://img.shields.io/github/stars/wuppp/cve-2021-45232-exp.svg) 
![forks](https://img.shields.io/github/forks/wuppp/cve-2021-45232-exp.svg) 
2021-12-31T08:30:33Z

- [https://github.com/GYLQ/CVE-2021-45232-RCE](https://github.com/GYLQ/CVE-2021-45232-RCE) :  
![starts](https://img.shields.io/github/stars/GYLQ/CVE-2021-45232-RCE.svg) 
![forks](https://img.shields.io/github/forks/GYLQ/CVE-2021-45232-RCE.svg) 
2022-01-13T05:12:49Z

- [https://github.com/YutuSec/Apisix_Crack](https://github.com/YutuSec/Apisix_Crack) :  
![starts](https://img.shields.io/github/stars/YutuSec/Apisix_Crack.svg) 
![forks](https://img.shields.io/github/forks/YutuSec/Apisix_Crack.svg) 
2022-05-09T12:32:43Z

- [https://github.com/Ilovewomen/cve-2021-45232](https://github.com/Ilovewomen/cve-2021-45232) :  
![starts](https://img.shields.io/github/stars/Ilovewomen/cve-2021-45232.svg) 
![forks](https://img.shields.io/github/forks/Ilovewomen/cve-2021-45232.svg) 
2021-12-29T02:22:09Z

- [https://github.com/fany0r/CVE-2021-45232-RCE](https://github.com/fany0r/CVE-2021-45232-RCE) :  
![starts](https://img.shields.io/github/stars/fany0r/CVE-2021-45232-RCE.svg) 
![forks](https://img.shields.io/github/forks/fany0r/CVE-2021-45232-RCE.svg) 
2023-06-24T08:52:41Z

- [https://github.com/LTiDi2000/CVE-2021-45232](https://github.com/LTiDi2000/CVE-2021-45232) :  
![starts](https://img.shields.io/github/stars/LTiDi2000/CVE-2021-45232.svg) 
![forks](https://img.shields.io/github/forks/LTiDi2000/CVE-2021-45232.svg) 
2021-12-28T13:30:29Z

- [https://github.com/yggcwhat/CVE-2021-45232](https://github.com/yggcwhat/CVE-2021-45232) :  
![starts](https://img.shields.io/github/stars/yggcwhat/CVE-2021-45232.svg) 
![forks](https://img.shields.io/github/forks/yggcwhat/CVE-2021-45232.svg) 
2022-01-08T08:27:19Z

- [https://github.com/jxpsx/CVE-2021-45232-RCE](https://github.com/jxpsx/CVE-2021-45232-RCE) :  
![starts](https://img.shields.io/github/stars/jxpsx/CVE-2021-45232-RCE.svg) 
![forks](https://img.shields.io/github/forks/jxpsx/CVE-2021-45232-RCE.svg) 
2021-12-28T13:59:50Z

- [https://github.com/dskho/CVE-2021-45232](https://github.com/dskho/CVE-2021-45232) :  
![starts](https://img.shields.io/github/stars/dskho/CVE-2021-45232.svg) 
![forks](https://img.shields.io/github/forks/dskho/CVE-2021-45232.svg) 
2021-12-29T05:51:13Z

- [https://github.com/xiju2003/-cve-2021-45232](https://github.com/xiju2003/-cve-2021-45232) :  
![starts](https://img.shields.io/github/stars/xiju2003/-cve-2021-45232.svg) 
![forks](https://img.shields.io/github/forks/xiju2003/-cve-2021-45232.svg) 
2022-01-01T20:22:13Z

- [https://github.com/badboycxcc/CVE-2021-45232-POC](https://github.com/badboycxcc/CVE-2021-45232-POC) :  
![starts](https://img.shields.io/github/stars/badboycxcc/CVE-2021-45232-POC.svg) 
![forks](https://img.shields.io/github/forks/badboycxcc/CVE-2021-45232-POC.svg) 
2021-12-28T14:37:31Z

- [https://github.com/Osyanina/westone-CVE-2021-45232-scanner](https://github.com/Osyanina/westone-CVE-2021-45232-scanner) :  
![starts](https://img.shields.io/github/stars/Osyanina/westone-CVE-2021-45232-scanner.svg) 
![forks](https://img.shields.io/github/forks/Osyanina/westone-CVE-2021-45232-scanner.svg) 
2021-12-28T11:40:03Z

- [https://github.com/yggcwhat/Demo](https://github.com/yggcwhat/Demo) :  
![starts](https://img.shields.io/github/stars/yggcwhat/Demo.svg) 
![forks](https://img.shields.io/github/forks/yggcwhat/Demo.svg) 
2022-01-08T07:42:44Z

