基于python的网络安全态势感知系统


## 网络安全态势感知系统

### 系统概述

本系统是一个基于Django + Vue.js的网络安全态势感知平台，有：SSH监控、流量分析等功能，实现对网络安全的实时监控、分析和可视化展示。

#### 后端技术栈
- **框架**: Django 
- **数据库**: MySQL
- **其他**: CORS支持、Token认证

### 核心功能模块

#### 1. 用户认证模块
- **功能**: 用户登录、Token认证、会话管理
- **文件**: `views_auth.py`, `Login.vue`

#### 2. 态势感知仪表板
- **功能**: 实时安全态势展示、攻击事件监控、风险指数评估
- **文件**: `views_dashboard.py`, `Dashboard.vue`
- **特性**: 
  - 世界地图攻击源可视化
  - SSH风险分析饼图
  - 最近攻击事件滚动显示
  - 中间件分析统计
  - 流量分析统计
  - 服务状态监控

#### 3. IP地址管理
- **功能**: IP地址威胁等级管理、地理位置信息、统计信息
- **文件**: `views_ip.py`, `IPManagement.vue`
- **特性**: 
  - IP威胁等级分类
  - 地理位置可视化
  - 攻击统计信息
  - 批量操作支持

#### 4. 流量溯源分析
- **功能**: 网络流量追踪、攻击路径分析、威胁情报
- **文件**: `views_snort.py`, `Traceability.vue`
- **特性**: 
  - 多维度搜索过滤
  - 攻击路径可视化
  - 威胁等级评估
  - 历史数据查询

#### 5. 数据包分析
- **功能**: 网络数据包深度分析、协议解析
- **文件**: `PacketAnalysis.vue`
- **特性**: 
  - 数据包内容解析
  - 协议分析
  - 异常检测

### 攻击检测能力

系统支持检测以下攻击类型：
- **XSS跨站脚本攻击**
- **SQL注入攻击**
- **目录扫描**
- **DoS拒绝服务攻击**
- **暴力破解攻击**
- **端口扫描**
- **SSH攻击**
- **恶意文件上传**
- **权限提升**
- **数据泄露**

<img width="2912" height="1877" alt="image" src="https://github.com/user-attachments/assets/d8b76457-a224-4930-89bb-6e10cafc25cb" />


<img width="2589" height="1735" alt="image" src="https://github.com/user-attachments/assets/e8907d6e-54f3-46ee-b087-2558bdf7d95b" />

<img width="2591" height="1735" alt="image" src="https://github.com/user-attachments/assets/2fcb40a6-f87f-4627-8fc2-049596a6b10d" />





