# KMS
KMS 激活服务，slmgr 命令激活 Windows 系统、Office

### 激活步骤（管理员命令执行）
1. 设置服务 `slmgr -skms kms.org.cn`
2. 安装密钥 `slmgr -ipk 版本对应秘钥`
3. 激活系统 `slmgr -ato`

### 可用服务
- `kms.org.cn` 维护 **CNAME** 指向有效的服务

+ `telnet kms.org.cn 1688` 测试服务是否可用
+ `tcping kms.org.cn 1688`

### Windows Server（LTSC 版本）

#### Windows Server 2025

操作系统版本 | KMS 客户端安装密钥
--- | ---
Windows Server 2025 Standard   | TVRH6-WHNXV-R9WG3-9XRFY-MY832
Windows Server 2025 Datacenter | D764K-2NDRG-47T6Q-P8T8W-YP6DF
Windows Server 2025 Datacenter: Azure Edition | XGN3F-F394H-FD2MY-PP6FD-8MCRC

#### Windows Server 2022

操作系统版本 | KMS 客户端安装密钥
--- | ---
Windows Server 2022 Standard   | VDYBN-27WPP-V4HQT-9VMD4-VMK7H
Windows Server 2022 Datacenter | WX4NM-KYWYW-QJJR4-XV3QB-6VM33
Windows Server 2022 Datacenter: Azure Edition | NTBV8-9K7Q8-V27C6-M2BTV-KHMXV

### Windows 11 和 Windows 10 (半年频道版本)

操作系统版本 | KMS 客户端安装密钥
--- | ---
Windows 10/11 专业版 | W269N-WFGWX-YVC9B-4J6C9-T83GX
Windows 10/11 专业版 N	 | MH37W-N47XK-V7XM9-C7227-GCQG9
Windows 10/11 专业工作站 | NRG8B-VKK3Q-CXVCJ-9G2XF-6Q84J
Windows 10/11 专业工作站 N	 | 9FNHH-K3HBT-3W4TD-6383H-6XYWF
Windows 10/11 专业教育版 | 6TP4R-GNPTD-KYYHQ-7B7DP-J447Y
Windows 10/11 专业教育版 N | YVWGF-BXNMC-HTQYQ-CPQ99-66QFC
Windows 10/11 教育版 | NW6C2-QMPVW-D7KKK-3GKT6-VCFB2
Windows 10/11 教育版 N | 2WH4N-8QGBV-H22JP-CT43Q-MDWWJ
Windows 10/11 企业版 | NPPR9-FWDCX-D2C8J-H872K-2YT43
Windows 10/11 企业版 N | DPH2V-TTNVB-4X9Q3-TJR4H-KHJW4
Windows 10/11 企业版 G | YYVX9-NTFWV-6MDM3-9PT4T-4M68B
Windows 10/11 企业版 G N | 44RPN-FTY23-9VTTB-MP9BX-T84FV

### Windows 10 (LTSC/LTSB 版本)

#### Windows 10 LTSC 2019

操作系统版本 | KMS 客户端安装密钥
--- | ---
Windows 10 企业版 LTSC 2019   | M7XTQ-FN8P6-TTKYV-9D4CC-J462D
Windows 10 企业版 N LTSC 2019 | 92NFX-8DJQP-P6BBQ-THF9C-7CG2H

#### Windows 10 LTSB 2016

操作系统版本 | KMS 客户端安装密钥
--- | ---
Windows 10 企业版 LTSB 2016   | DCPHK-NFMTC-H88MJ-PFHPY-QJ4BJ
Windows 10 企业版 N LTSB 2016 | QFFDN-GRT3P-VKWWX-X7T3R-8B639

#### Windows 10 LTSB 2015

操作系统版本 | KMS 客户端安装密钥
--- | ---
Windows 10 企业版 2015 LTSB   | WNMTR-4C88C-JK8YV-HQ7T2-76DF9
Windows 10 企业版 2015 LTSB N | 2F77B-TNFGY-69QQF-B8YKP-D69TJ

### 激活说明
- KMS 激活有 180 天期限，此期限称为激活有效间隔
- 若要保持激活状态，您的系统必须通过至少每 180 天连接一次 KMS 服务器来续订激活
- 默认情况下，系统每 7 天自动进行一次激活续订尝试
- 在续订客户端激活之后，激活有效间隔重新开始
- 综上所述，只要您不超过 180 天以上无法连接互联网，系统会自行续期保持激活状态

----------
### 更多密钥 
<https://learn.microsoft.com/zh-cn/windows-server/get-started/kms-client-activation-keys>
