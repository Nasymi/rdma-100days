# RDMA 100 Days Learning Notes 记录为期100天 RDMA、RoCEv2 及 Linux rdma-core完整学习笔记，包含理论、实操、排障、调优。

## 仓库目录说明 
- days/：每日连载学习笔记，按 day001~day100 拆分，包含概念、实验复盘、踩坑记录 
- assets/：笔记配套截图、抓包拓扑、网卡监控、日志截图 
- cheatsheets/：高频速查表，RDMA命令、内核参数、RoCE排障SOP、perftest使用模板 
- template.md：每日笔记通用模板，统一格式

## 实验环境 
1. Windows 11 + WSL2 Ubuntu 22.04 
2. CPU：i5-14600K / 内存：48GB DDR5
3. 工具链：rdma-core、perftest、ibverbs-utils、Linux kernel source 
4. 版本控制：Git + GitHub 远程仓库同步