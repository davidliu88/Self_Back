# Penetration_test_note

## 个人记录的一些东西

## 目录

<pre><code>.
├─ README.md
├─ 书籍
│    ├─ Python黑帽子_黑客与渗透测试编程之道.pdf
│    ├─ The-hacker-playbook-3-pdf.pdf
│    └─ Violent_Python.pdf
├─ 亮神十年渗透经验分享
│    ├─ 001_windows提权-快速查找exp.pdf
│    ├─ 002_Linux提权-依赖exp篇.pdf
│    ├─ 003_Delphi代码审计--项目实战1.pdf
│    ├─ 004_Asp代码审计--项目实战2.pdf
│    ├─ 005_工具介绍-Sqlmap.pdf
│    ├─ 006_反攻的一次溯源--项目实战3.pdf
│    ├─ 007_sql server 常用操作远程桌面语句.pdf
│    ├─ 008_模拟诉求任务攻.pdf
│    ├─ 009_工具介绍-the-backdoor-factory.pdf
│    ├─ 010_msfvenom常用生成payload命令.pdf
│    ├─ 011_工具介绍Veil-Evasion.pdf
│    ├─ 012_基于UDP发现内网存活主机.pdf
│    ├─ 013_基于ARP发现内网存活主机.pdf
│    ├─ 014_基于第十课补充payload1.pdf
│    ├─ 015_基于010补充payload2.pdf
│    ├─ 016_红蓝对抗渗透测试1.pdf
│    ├─ 017_红蓝对抗渗透测试2.pdf
│    ├─ 018_红蓝对抗渗透测试3.pdf
│    ├─ 019_基于netbios发现内网存活主机.pdf
│    ├─ 020_基于snmp发现内网存活主机.pdf
│    ├─ 021_基于ICMP发现内网存活主机.pdf
│    ├─ 022_基于SMB发现内网存活主机.pdf
│    ├─ 023_基于MSF发现内网存活主机.pdf
│    ├─ 024_基于MSF发现内网存活主机.pdf
│    ├─ 025_基于MSF发现内网存活主机.pdf
│    ├─ 026_基于MSF发现内网存活主机.pdf
│    ├─ 027_基于MSF发现内网存活主机.pdf
│    ├─ 028_基于MSF发现内网存活主机.pdf
│    ├─ 029_发现目标WEB程序敏感目录.pdf
│    ├─ 030_解决msfvenom命令自动补全.pdf
│    ├─ 031_msf的前生今世.pdf
│    ├─ 032_配置vps上的msf.pdf
│    ├─ 033_攻击Mysql服务.pdf
│    ├─ 034_攻击Sql server 服.pdf
│    ├─ 035_与Sqlmap结合攻.pdf
│    ├─ 036_解决vps上ssh掉线.pdf
│    ├─ 037_vbs一句话下载payload.pdf
│    ├─ 038_certutil一句话下载payload.pdf
│    ├─ 039_vbs一句话下载payload补充.pdf
│    ├─ 040_ftp一句话下载payload.pdf
│    ├─ 041_bitsadmin一句话下载payload.pdf
│    ├─ 042_攻击FTP 服务.pdf
│    ├─ 043_js一句话下载payload.pdf
│    ├─ 044_ertutil一句话下载payload补充.pdf
│    ├─ 045_解决bat一句话下载payload黑窗.pdf
│    ├─ 046_powershell一句话下载payload.pdf
│    ├─ 047_payload分离免杀思路.pdf
│    ├─ 048_payload分离免杀思路.pdf
│    ├─ 049_关于Powershell对抗安全软件.pdf
│    ├─ 050_基于SqlDataSourceEnumerator发现内网存活主机.pdf
│    ├─ 051_项目回忆：体系的本质是知识点串联.pdf
│    ├─ 052_渗透的本质是信息搜集.pdf
│    ├─ 053_内网渗透中的文件传输.pdf
│    ├─ 054_基于Powershell做Socks 4-5代理（.pdf
│    ├─ 055_与Smbmap结合攻.pdf
│    ├─ 056_离线提取目标机hash.pdf
│    ├─ 057_高级持续渗透-关于后门.pdf
│    ├─ 058_高级持续渗透-关于后门补充一.pdf
│    ├─ 059_高级持续渗透-关于后门补充二.pdf
│    ├─ 060_高级持续渗透-关于后门.pdf
│    ├─ 061_高级持续渗透-关于后门.pdf
│    ├─ 062_高级持续渗透-关于后门.pdf
│    ├─ 063_高级持续渗透-demo的成长.pdf
│    ├─ 064_高级持续渗透-demo便是远控.pdf
│    ├─ 065_离线提取目标机hash补充.pdf
│    ├─ 066_借助aspx对payload进行分离免杀.pdf
│    ├─ 067_meterpreter下的irb操作.pdf
│    ├─ 068_基于Ruby内存加载shellcode.pdf
│    ├─ 069_渗透，持续渗透，后渗透的本质.pdf
│    ├─ 070_ftp一句话下载payload补充.pdf
│    ├─ 071_基于白名单Msbuild.exe执行payload.pdf
│    ├─ 072_基于白名单Installutil.exe执行payload.pdf
│    ├─ 073_基于白名单Regasm.exe执行payload.pdf
│    ├─ 074_基于白名单regsvcs.exe执行payload.pdf
│    ├─ 075_基于白名单Mshta.exe执行payload.pdf
│    ├─ 076_基于白名单Compiler.exe执行payload.pdf
│    ├─ 077_基于白名单Csc.exe执行payload.pdf
│    ├─ 078_基于白名单Msiexec执行payload.pdf
│    ├─ 079_基于白名单Regsvr32执行payload.pdf
│    ├─ 080_基于白名单Wmic执行payload.pdf
│    ├─ 081_基于白名单Rundll32.exe执行payload.pdf
│    ├─ 082_基于白名单Odbcconf执行payload.pdf
│    ├─ 083_基于白名单PsExec执行payload.pdf
│    ├─ 084_基于白名单Forfiles执行payload.pdf
│    ├─ 085_基于白名单Pcalua执行payload.pdf
│    ├─ 086_基于白名单Msiexec执行payload.pdf
│    ├─ 087_基于白名单Cmstp.exe执行payload.pdf
│    ├─ 088_基于白名单Ftp.exe执行payload.pdf
│    ├─ 089_基于白名单Url.dll执行payload.pdf
│    ├─ 090_基于白名单zipfldr.dll执行payload.pdf
│    ├─ 091_从目标文件中做信息搜集.pdf
│    ├─ 092_实战中的Payload应用.pdf
│    ├─ 093_与CrackMapExec结合攻击.pdf
│    ├─ 094_基于实战中的small payload.pdf
│    ├─ 095_基于portfwd端口转发.pdf
│    ├─ 096_HTTP隧道abptts.pdf
│    ├─ 097_msf配置自定义payload控制目标主机权限.pdf
│    ├─ 098_HTTP隧道reGeorg.pdf
│    ├─ 099_HTTP隧道Tunna.pdf
│    ├─ 100_HTTP隧道reDuh.pdf
│    ├─ 101_基于SCF做目标内网信息搜集第二季.pdf
│    ├─ 102_对抗权限长期把控-伪造无效签名第一季.pdf
│    ├─ 103_Http加密隧道下的横向渗透尝试.pdf
│    ├─ 104_Windows Smb 欺骗重放攻击利用.pdf
│    ├─ 105_windows 单机免杀抓明文或hash [通过dump lsass进程数据].pdf
│    ├─ 106_windows 单机免杀抓明文或hash [通过简单混淆编码绕过常规静态检测].pdf
│    ├─ 107_跨平台横向移动 [ windows计划任务利用 ].pdf
│    ├─ 108_跨平台横向移动 [wmi利用].pdf
│    ├─ 109_依托 metasploit 尽可能多的发现目标内网下的各类高价值存活主机.pdf
│    ├─ 110_窃取,伪造模拟各种windows访问令牌[token利用].pdf
│    ├─ 111_内网mssql完整利用流程 [ 基础篇 ].pdf
│    ├─ 112_利用Dropbox中转C2流量.pdf
│    ├─ 113_COM Hijacking.pdf
│    ├─ 114_渗透沉思录.pdf
│    ├─ 115_使用 CrackMapExec 进行 NTLM Hash 传递攻击.pdf
│    ├─ 116_Windows 域渗透 - 用户密码枚举.pdf
│    ├─ 117_Windows 本地特权提升技巧.pdf
│    ├─ 118_CVE-2017-11882 钓鱼攻击.pdf
│    ├─ 119_全平台高性能加密隧道 ssf.pdf
│    ├─ 120_win自带的高级网络配置管理工具深度应用 [ netsh ].pdf
│    ├─ 121_http加密代理深度应用 [ abptts ].pdf
│    ├─ 122_利用 ssh隧道实现内网断网机meterpreter反向上线.pdf
│    ├─ 123_利用ssh隧道将公网meterpreter弹至本地的msf中.pdf
│    ├─ 124_解决无meterpreter shell添加虚拟路由映射.pdf
│    ├─ 125_利用WinRAR跨目录获取Net-NTLM Hash和DLL劫持.pdf
│    ├─ README.md
│    ├─ SensePost_Eye_of_a_Needle.pdf
│    └─ 内网穿透_Presenting-Tunna-v1.1a.pdf
└─ 工具使用
       └─ BurpSuite实战指南.pdf
</code></pre>
