# openKylin-system-security-analysis-tool
# 项目名称：
**openKylin操作系统安全分析工具**

## 项目描述：
“没有网络安全，就没有国家安全”，目前国产操作系统已广泛应用于军工、能源、金融、航天、交通等重要领域，而操作系统安全一直是行业研究的重点方向。本次项目，
主要的目标实现“openKylin操作系统安全分析工具”，主要考察参赛者系统编程能力及对操作系统安全基础知识的掌握。

## 所属赛道：
2024全国大学生操作系统比赛的“OS功能挑战”赛道

## 参赛要求
* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生/研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2023全国大学生操作系统比赛”的章程和技术方案要求

## 项目导师：
* 杨诏钧 yangzhaojun@kylinos.cn
* 罗雨佳 luoyujia@kylinos.cn  
* 徐建 xujian@kylinos.cn
* 宋帮诚晋 songbangchengjin@kylinos.cn
* 陈心全 chenxinquan@kylinos.cn
* 李文杰 liwenjie@kylinos.cn 

## 难度：
中等
## 特征：
1、编程语言：go、python、shell，但需要考虑可移植性以及跨平台(CPU架构)兼容性。  
2、每项安全检测功能形成模块化，可通过命令行、命令交互或配置文件进行插拔使用；  
3、可融合开源社区优秀项目，但必须是模块化；  

题目共分2个子题目，参赛者需要依次完成题目。完成数目越多，质量越高，最终得分越高。  
题目1:   实现openKylin操作系统安全配置基线检查功能生成可视化报告，并能够根据基线检测结果进行系统安全评估。    
题目2:   实现openKylin操作系统安全漏洞（POC/EXP）检查功能生成可视化报告，能够准确分析出当前操作系统中存在的已公开安全漏洞，并根据漏洞扫描报告进行系统安全评估。

## 评分参考
题目一
| 功能 | 评分 | 备注 |
| :-----| :--- | :---- |
| 功能一：实现系统安全配置基线检查 | 60 | 检查项覆盖操作系统通用安全需求(参考SCAP标准/等保安全配置基线标准) |
| 功能二：形成安全基线检查报告 | 80 | 需生成可视化报告，须支持pdf和rtf格式报告文档 |
| 功能三：系统基线检查安全评估 | 90 | 制定系统基线安全评分标准，能够根据系统安全基线检查报告，结合SCAP标准/等保安全配置基线标准，进行系统安全评估，给出安全评分|
| 功能四：实现系统总线服务接口自动化安全检查基线 | 100 | 要求针对操作系统中常见系统服务接口，能够实现自动化安全检查功能|

题目二
| 功能 | 评分 | 备注 |
| :-----| :--- | :---- |
| 功能一：实现安全漏洞（POC/EXP）检查功能 | 60 | 检查功能要求模块化，基于安全漏洞poc/exp检测 |
| 功能二：形成安全漏洞扫描报告 | 80 | 需生成可视化报告，须支持pdf和rtf格式报告文档 |
| 功能三：系统安全漏洞评估 | 90 | 制定系统漏洞评分标准，能够根据系统安全漏洞数量及等级， 进行系统安全评估，给出安全评分|
| 功能四：poc防逆向功能 | 100 | 采用加密、编译、身份认证、内存混淆等方式，对工具的敏感文件，如poc/exp等实施保护，防止敏感文件被恶意窃取 |

## License:
GPL-3.0

## 参考资料：   
[openKylin社区主页](https://www.openkylin.top/)   
[openKylin开源社区安全治理sig组主页](https://gitee.com/openkylin/community/tree/master/sig/SecurityGovernance)   
[openKylin开源社区诊脉框架](https://gitee.com/openkylin/genmai)  
[openKylin开源社区漏洞测试用例仓库](https://gitee.com/openkylin/openkylin-exploit-db)    
[openKylin操作系统下载地址](https://openkylin.top/downloads)  
[Scripted Local Linux Enumeration & Privilege Escalation Checks](https://github.com/rebootuser/LinEnum)    
[A Linux Privilege Escalation Check Script](https://github.com/sleventyeleven/linuxprivchecker)    
[Linux privilege escalation auditing tool](https://github.com/The-Z-Labs/linux-exploit-suggester)
[NIST Certified SCAP 1.2 toolkit](https://github.com/OpenSCAP/openscap)
