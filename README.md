# Competitor Intelligence Hub

竞品智能监控报告仓库 —— 女性健康 / AI 保健品 / 肠道微生物组赛道

## 📁 仓库结构

```
.
├── reports/
│   ├── daily/           # 每日竞品简报
│   ├── weekly/          # 每周深度报告
│   └── special/         # 专题调研报告
├── raw-data/            # 原始监控数据
├── summaries/           # 趋势汇总分析
├── config/              # 监控配置
└── README.md
```

## 🎯 监控范围

### 女性健康赛道
- 女性益生菌（阴道健康、孕期支持）
- PMS / 经期管理产品
- 更年期 / HRT 补充剂
- 女性定制维生素

### AI 保健品赛道
- AI 营养师 / 健康教练 App
- 个性化补充剂推荐系统
- 智能健康数据分析

### 肠道微生物组赛道
- 微生物组检测 + AI 分析
- 精准益生菌方案
- 肠-脑轴健康产品

### 直接竞品公司
- Seed Health
- Pendulum Therapeutics
- Viome
- Ritual
- Care/of
- Persona Nutrition
- Flore
- Elo Health
- 等 38+ 个性化补充剂初创

## 📊 数据来源

- 公开新闻 / 融资公告
- 产品发布动态
- 社交媒体监控
- 行业报告摘录

## ⏱️ 更新频率

| 类型 | 频率 | 自动化 |
|------|------|--------|
| 每日简报 | 每天 9:00 + 16:00 | ✅ Cron |
| 每周深度 | 每周一 9:00 | ✅ Cron |
| 专题报告 | 按需触发 | 手动 |

## 🤖 自动化系统

由 Hermes Agent (PM Agent) 驱动：
- 定时搜索竞品动态
- 生成结构化报告
- 自动提交到本仓库
- Telegram 同步推送

---

**Maintained by:** PM Agent (@Hermes)  
**Organization:** Hermes-marovole  
**Last Updated:** 2026-04-23
