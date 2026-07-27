# 一人公司办公系统 (Solo Office)

一个面向一人公司/独立创业者的轻量级办公管理系统，涵盖项目管理、财务、客户、日程等核心业务场景。

## 页面概览

| 页面 | 说明 |
| --- | --- |
| 工作台 (Dashboard) | KPI 仪表盘 + 收入/项目趋势图表 |
| 项目管理 (Projects) | 四条业务线看板管理 + 工作流详情 |
| 财务概览 (Finance) | 收支统计、月度趋势、分类占比 |
| 客户管理 (Clients) | 客户列表、搜索过滤、状态管理 |
| 日程安排 (Schedule) | 日历视图 + 待办任务列表 |
| 工作流 (Workflows) | 外贸客户开发详细步骤 + 邮箱自动化 |

## 四条业务线

1. **toB 服饰外贸** — 开发客户 → 背调客户 → 联系/跟进客户 → 交付
2. **小红书运营** — 种草带货赛道全流程
3. **抖音韩漫短视频** — 动漫连续剧剪辑发布
4. **数据分析** — 数据采集、清洗、建模、报告

## 邮箱自动化

外贸「联系/跟进客户」阶段内置邮件自动化能力：
- AI 生成单封或批量邮件
- 在线审核、编辑邮件内容
- 单封/批量发送
- 邮件模板库管理

## 技术栈

- 纯静态 HTML + Tailwind CSS (CDN)
- Lucide Icons
- Chart.js（数据可视化）
- 语义化 Design Token 配色系统

## 设计风格

商务质感 — 深海军蓝主色 (`#1F3F7A`)，克制圆角，边框主导的静态卡片面，240px 侧边栏 + 64px 顶栏布局。

## 本地运行

直接用浏览器打开任意 `pages/*.html` 文件即可，无需构建步骤。

## 项目结构

```
one-person-office/
├── pages/
│   ├── dashboard.html      # 工作台
│   ├── projects.html       # 项目管理
│   ├── finance.html        # 财务概览
│   ├── clients.html        # 客户管理
│   ├── schedule.html       # 日程安排
│   └── workflows.html      # 工作流详情
├── partials/
│   └── project-shell.html  # 共享侧边栏/顶栏
├── colors_and_type.css     # Design Token 配色
└── one-person-office.design # 设计画布文件
```