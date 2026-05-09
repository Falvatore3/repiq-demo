# RepIQ Demo

AI 健身训练助手 —— 交互式 HTML 原型（对标训记 App 架构）

## 在线预览

部署后访问：**https://falvatore3.github.io/repiq-demo/**

## 本地打开

```bash
open index.html
```

或用任意静态服务器：

```bash
python3 -m http.server 8080
# 访问 http://localhost:8080
```

## 功能覆盖

- 5 底部 Tab：训练 / 动作 / 历史 / 数据 / 我的
- 完整训练会话流程：选计划 → 打勾记录 → AI 建议下组 → 组间休息 → 总结
- 内置 AI 规则引擎（达标+RIR 高 → 加重；未达标 → 减重）
- 移动端优先，iOS safe-area 适配

## 项目状态

内部 Demo，用于产品验证与交互走查。详细 PRD 见主仓库。
