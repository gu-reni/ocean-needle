<p align="center">
  <b>大海捞针</b>
  <br>
  从互联网的各处，捞起与 AI、开源与计算机有关的好东西。
  <br>
  每周三捞一次，每月 29 号汇总一期，一期最多 15 条。
  <br><br>
  <a href="https://github.com/gu-reni/ocean-needle/stargazers"><img src="https://img.shields.io/github/stars/gu-reni/ocean-needle.svg?style=popout-square" alt="GitHub stars"></a>
  <a href="https://github.com/gu-reni/ocean-needle/issues"><img src="https://img.shields.io/github/issues/gu-reni/ocean-needle.svg?style=popout-square" alt="GitHub issues"></a>
</p>

## 简介

大海捞针持续从 **GitHub、各大 Skill 目录站、中文 AI 社区与行业资讯源** 搜集与 **AI Skill、大模型、Agent、开源项目、计算机** 有关的内容与软件，按月整理成刊。

- **每周三**捞取一次，捞到的东西不与之前重复（靠一份去重台账保证）
- **每月 29 号**汇总一期，按类别编排
- **每期最多 15 条** —— 宁少而精，不为凑数降低标准
- 报告同时提供 **Markdown 原件** 与 **可直接阅读的网页版**

## 内容

| :card_index: | :jack_o_lantern: | :beer: | :fish_cake: | :octocat: |
| ------- | ----- | ------------ | ------ | --------- |
| [第 01 期](/reports/01.md) | [第 02 期](/reports/02.md) | | | |

> 点期号看 Markdown 原件；想直接在浏览器里读，把链接末尾的 `.md` 换成 `.html`。

## 每期的编排

报告按类别分节，每条包含 **项目名、仓库地址、一段说明、星数与最近推送时间**：

| 分类 | 收录什么 |
|---|---|
| **AI Skill** | 能给 AI 助手加新能力的技能包与技能集 |
| **Skill 仓库** | 成体系的技能库、技能管理与聚合项目 |
| **开源项目** | 值得关注的新项目、工具与平台 |
| **Windows 软件** | 桌面端实用软件 |
| **插件与桌面布局** | 系统定制、界面美化、效率增强 |

此外每期会附 **「一条不推荐的」** —— 挑一个看起来热闹、实际不成熟或已停更的项目，说明**为什么不推荐**。选材不只看星数。

## 怎么挑的

三条标准，缺一不可：

1. **能用上** —— 装完就能解决一个真实问题，不是概念演示
2. **还在动** —— 仓库近期有提交，不是停在几个月前的半成品
3. **说得清** —— 值得写 2-3 句具体的适用场景，而不是一句「很好用」

**星数与最近推送时间均通过 GitHub API 实时查询**，不凭印象填写、不采信搜索摘要里的转述数字。部分条目会带**安全风险与依赖漏洞**标注。

## 目录结构

| 路径 | 说明 |
|---|---|
| `reports/NN.md` | 第 NN 期报告（Markdown 原件） |
| `reports/NN.html` | 第 NN 期报告（渲染后的网页） |
| `state/seen.tsv` | 去重台账：已收录条目的唯一键 |
| `scripts/report-header.html` | 网页渲染用的样式模板 |
