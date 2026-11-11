# Development roadmap

[Product overview](../README.md) · [AI research workflow](ai-research.md) · [中文路线图](#中文路线图)

**Status: functional prototype, active development. Updated 11 November 2026.**

## Implemented in the development application

- Company financial research with statement comparisons, cash-flow analysis and dated source records.
- Debt and relationship views covering repricing, maturities, investments, lending and guarantees.
- Policy-rate scenarios connecting capital expenditure, operating cash, funding and earnings.
- FOMC company analysis and historical policy-event comparisons, with a separate ExtraTrees share-return model.
- AI company assessment, industry and competitive research, two-path quarterly revenue forecasting and guidance comparison.
- A shared report structure for the website, HTML export and Word download.
- Bloomberg-assisted supply-chain workbook generation and import.
- Trading 212 CFD activity import and transaction review.
- Chinese and English interfaces.

## Current work: product and research refinement

- Improve the consistency of financial periods, debt terms and research-output validation across company cases.
- Refine the narrative flow between business evidence, forecast assumptions and the final investment view.
- Make the most decision-relevant calculations and explanations easier to find.

## Next milestone: portable application release

- Standardize runtime dependencies and installation across supported operating systems.
- Provide a first-run setup with user-supplied API credentials and model configuration.
- Add a sample-data mode and reproducible examples for initial exploration.
- Make Excel and Word generation independent of the development machine's bundled components.
- Publish installation documentation, a versioned release and the selected software license.

## Following milestone: reusable company-research skill

- Package the established research workflow with an explicit invocation, input contract and output format.
- Document data access and calculation-tool dependencies.
- Supply worked examples and checks covering multiple business models.
- Reuse the same analytical method in the Lab and the skill entry point.

The public repository currently presents the product and research design. Release milestones will be recorded here as the distributable packages become available.

---

## 中文路线图

**状态：可运行原型，持续开发中。更新于 2026 年 11 月 11 日。**

### 开发版已实现

公司财务与现金流分析、债务期限与关联关系、利率与融资情景、FOMC 公司推演、历史事件与 ExtraTrees 模型、AI 公司评估、两条季度收入预测路径、网页及 HTML/Word 报告、Bloomberg 供应链导入、Trading 212 交易复盘，以及中英文界面。

### 正在完善

提高跨公司财报期间、债务条款与研究结果的处理一致性；改善业务证据、预测假设与投资判断之间的衔接；优化关键计算和解释的展示。

### 下一阶段：独立安装与版本发布

统一运行依赖，提供首次配置与示例数据体验，使 Excel、Word 生成功能可以独立安装；补充可复现案例、安装说明、版本发布及软件许可证。

### 后续阶段：公司研究 Agent Skill

封装明确的调用方式、输入输出、数据与工具依赖，提供多种业务模式的示例与检查，并与 Lab 共用研究方法。

本仓库当前展示产品及研究设计，后续软件与 Skill 发布进展将在此更新。
