# Unify Biz Hub

> **统一平台 · 业务友好 · 开源企业系统集合**

[![GitHub Org](https://img.shields.io/badge/GitHub-UnifyBizHub-181717?logo=github)](https://github.com/unify-biz-hub)
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

---

## 📖 简介

**Unify Biz Hub** 是一个面向业务人员的开源企业系统集合，致力于在**同一技术体系**下提供 **ERP、OA、CRM、MES** 等核心企业应用。

我们相信：企业软件不应该是一座座数据孤岛。**Unify** 即“统一”——统一数据、统一流程、统一体验，让业务真正协同起来。

---

## 🎯 使命

> 打破企业应用的数据壁垒，让每一家中小企业都能拥有**统一、开放、自主可控**的业务系统。

---

## 🧩 核心项目（规划中）

| 项目 | 代号 | 状态 | 简介 |
|------|------|------|------|
| **ERP** | `Fusion` | 🚧 开发中 | 融合进销存、财务、生产，企业资源的核心引擎 |
| **OA** | `Flow` | 📝 规划中 | 流程审批、考勤、文档协同，让办公行云流水 |
| **CRM** | `Engage` | 📝 规划中 | 客户互动、销售漏斗、售后服务，提升客户粘性 |
| **MES** | `Forge` | 📝 规划中 | 制造执行、车间数据采集、质量追溯，锻造精益生产 |
| **基础底座** | `Core` | ✅ 已完成 | 统一用户权限、组织架构、低代码表单引擎 |

> 所有项目共享同一套**基础资料**（物料、客户、供应商、会计科目等），实现开箱即用的数据互通。

---

## ✨ 特色

- 🔗 **天然集成**：ERP 的采购订单可直接生成 OA 的审批流，CRM 的合同可自动同步至 ERP 的销售模块。
- 🎨 **业务友好**：减少专业术语，提供业务视角的导航和帮助提示。
- 🧩 **模块化可插拔**：按需安装，小型企业只用进销存，大型企业可启用全链条。
- 🌱 **开源且开放**：API 优先设计，方便与第三方系统对接（如小程序、电商平台）。
- 🔐 **统一安全**：单点登录、细粒度权限控制，一套账号走遍所有模块。

---

## 🚀 快速开始

### 1. 体验演示环境
> 演示地址：即将开放

### 2. 本地部署（Docker 推荐）
```bash
# 克隆基础底座
git clone https://github.com/unify-biz-hub/core.git
cd core

# 使用 docker-compose 一键启动
docker-compose up -d
