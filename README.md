# EZ-InSAR_For_Windows
Distribute EZ-InSAR on Windows OS through WSL

### 简介

EZ-InSAR (原名为 MIESAR，Matlab Interface for Easy InSAR) 是一个基于 MATLAB 编写拥有图形界面的 InSAR 数据处理工具箱，其整合集成了业界目前最广 泛使用的 InSAR 开源软件 ISCE、StaMPS 和 MintPy，能够自动下载 SAR 数据、DEM 和轨道数据，进行流程化的 SAR 数据干涉处理和时序形变分析，并具有详细的中、英 文使用帮助文档。

WSL:Windows Subsystem for Linux (简称 WSL)是一个可以在 Windows 10/11 上能 够运行 Linux 系统的兼容层。它由微软与 Canonical 公司合作开发，其目标是使纯正的 Ubuntu、Debian 等映像能够下载和解压到用户的本地计算机，并且映像内的工具和实 用工具能在此子系统上原生运行。WSL 区别于一般的虚拟机，具有配置简单、能够充 分利用计算机系统资源的优点。

EZ-InSAR 目前依赖 Linux 系统环境运行，考虑到非专业用户多在 Window 系统下 办公，本团队发布了基于WSL预装了EZ-InSAR和其依赖环境的Ubuntu系统(Ubuntu 22.04)，目的是让用户在 Windows 下轻松使用 EZ-InSAR。

本文档主要介绍如何利用 WSL 导入本团队发布的 Ubuntu 系统，并机进行相关配 置和激活 MATLAB。文档内容有五部分组成，包括:软件系统下载、Windows WSL 配 置、WSL 导入 Ubuntu、WSL 图形界面配置等。

用户在使用过程中如有改进意见，欢迎反馈给 EZ-InSAR 和本文档编写小组。

### 文档作者

- 任旭，研究生，西南交通大学地球科学与环境工程学院 
- 王晓文，副教授, 西南交通大学地球科学与环境工程学院

联系邮箱: insarwxw@swjtu.edu.cn
