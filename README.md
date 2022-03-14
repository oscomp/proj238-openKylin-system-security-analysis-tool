# kylin-system-security-testing-tools
## 项目名称：
麒麟操作系统安全性测试工具
## 项目描述：
“没有网络安全，就没有国家安全”，目前麒麟操作系统已广泛应用于军工、能源、金融、航天、交通等重要领域。操作系统安全一直是行业研究的重点方向。本次项目，
主要的目标实现“麒麟操作系统安全性测试工具”。主要考察参赛者系统编程能力及对操作系统安全知识的掌握。
## 所属赛道：
2022全国大学生操作系统比赛的“OS功能挑战”赛道
## 参赛要求
* 以小组为单位参赛，最多三人一个小组，且小组成员是来自同一所高校的本科生/研究生
* 如学生参加了多个项目，参赛学生选择一个自己参加的项目参与评奖
* 请遵循“2022全国大学生操作系统比赛”的章程和技术方案要求
## 项目导师：
* 杨诏钧 yangzhaojun@kylinos.cn  
* 罗雨佳 luoyujia@kylinos.cn  
* 史昕岭 shixinling@kylinos.cn  
* 李文杰 liwenjie@kylinos.cn  
## 难度：
中等
## 特征：
1、编程语言不限，但需要考虑可移植性以及跨平台兼容性，需要同时满足支持银河麒麟桌面操作系统、银河麒麟服务器操作系统、优麒麟操作系统。  
2、每种安全检测功能形成一个插件，可通过命令行、命令交互或配置文件进行插拔；  
3、工具可独立于编译环境运行；  
4、可融合社区优秀项目；  
5、除社区优秀项目外，可通过fuzzing等方式探索发现其他不稳定或存在漏洞的场景，形成自己的插件；  
## 参考资料：
http://www.open-scap.org/  
https://github.com/rebootuser/LinEnum  
https://github.com/sleventyeleven/linuxprivchecker  
https://github.com/mzet-/linux-exploit-suggester  
https://github.com/kernelslacker/trinity  
https://github.com/google/syzkaller  
## License:
GPL-3.0
## 预期说明：
题目共分4个子题目，参赛者需要依次完成题目。完成数目越多，质量越高，最终得分越高。  
题目1:   实现麒麟操作系统安全基线检查功能，并对基线项给出修复指导，实现全平台兼容。  
题目2:   实现麒麟操作系统权限提升检查功能，并对风险项给出修复指导，实现全平台兼容。  
题目3:   实现系统调用fuzzing测试功能，实现x86架构测试功能为基础。  
题目4:   实现麒麟操作系统内核漏洞检查功能，实现x86架构功能为基础。  
