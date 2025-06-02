# 面试羊 🐑 - 一站式面试准备平台

> 让面试准备变得简单而高效 ✨
> 
> 本项目学习改造自开源项目 [面试鸭](https://github.com/liyupi/mianshiya-next)

## 📚 项目简介

面试阳是一个基于 Next.js 服务端渲染 + Spring Boot + Redis + MySQL + Elasticsearch 的面试刷题平台。管理员可以创建题库、题目和题解；用户可以注册登录、分词检索题目、在线刷题并查看刷题记录日历图。

## 🚀 技术栈

### 前端技术
- ⚡️ React 18 框架
- 🎨 Next.js 服务端渲染
- 🔄 Redux 状态管理
- 📱 Ant Design 组件库
- 📝 富文本编辑器组件
- 🛠️ 前端工程化：ESLint + Prettier + TypeScript
- 🔌 OpenAPI 前端代码生成

### 后端技术
- 🍃 Java Spring Boot 框架 + Maven 多模块构建
- 📊 MySQL 数据库 + MyBatis-Plus 框架 + MyBatis X
- 🔥 Redis 分布式缓存 + Caffeine 本地缓存
- 🔒 Redission 分布式锁 + BitMap + BloomFilter
- 🔍 Elasticsearch 搜索引擎
- 💾 Druid 数据库连接池 + 并发编程
- 🔐 Sa-Token 权限控制
- ⚡️ HotKey 热点探测
- 🚦 Sentinel 流量控制
- ⚙️ Nacos 配置中心
- 🚀 多角度项目优化：性能、安全性、可用性

## ✨ 主要功能

- 📝 在线刷题
  - 题目分类浏览
  - 题目搜索
  - 题目收藏
  - 题目难度标记
- 📊 刷题日历
  - 每日刷题记录
  - 刷题统计
  - 刷题进度追踪

## 🛠️ 快速开始

### 前端启动
```bash
cd mianshiyang-frontend
npm install
npm run dev
```

### 后端启动
```bash
cd mianshiyang-backend
mvn spring-boot:run
```

## 📝 项目结构

```
mianshiyang/
├── mianshiyang-frontend/    # 前端项目
└── mianshiyang-backend/     # 后端项目
```

