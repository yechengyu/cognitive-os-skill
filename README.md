# Cognitive OS Skill

> 创始人认知操作系统 — 一套基于实业经营实践蒸馏的决策框架，封装为 Claude Code Skill。

## 这是什么

一位连锁零售创始人基于数年经营实践，从日志、决策记录、口播稿、团队协作中蒸馏出的认知操作系统。包含：

- **1 个底层认知**：贝叶斯式思维
- **6 条精益原则**：行知合一 / 持续改善 / 率先垂范 / 三现主义 / 凡事彻底 / 人是目的
- **16 个心智模型**：从"资源有限，限制并行"到"组织流程须与外部环境同步迭代"
- **30 条决策启发式**：覆盖数据判断、执行节奏、团队协作、精益改善、定价选品等
- **表达 DNA**：场景先行、反常识反转、结论收束
- **6 条反模式**：禁止自嗨、禁止完美主义、禁止沉默吞错等

蒸馏方法论来自 [nuwa-skill](https://github.com/alchaincyf/nuwa-skill)。

## 安装

将 `SKILL.md` 复制到你项目的 `.claude/skills/cognitive-os/` 目录下：

```bash
# 在你的项目根目录下
mkdir -p .claude/skills/cognitive-os
curl -o .claude/skills/cognitive-os/SKILL.md \
  https://raw.githubusercontent.com/<your-org>/cognitive-os-skill/main/SKILL.md
```

或者直接克隆：

```bash
git clone https://github.com/<your-org>/cognitive-os-skill.git
cp cognitive-os-skill/SKILL.md <your-project>/.claude/skills/cognitive-os/SKILL.md
```

## 使用

安装后，在 Claude Code 对话中使用以下触发词：

- "用认知框架分析一下这个问题"
- "帮我看这个决策有没有漏洞"
- "挑战一下我的逻辑"
- "用创始人视角看看这个方案"
- "认知操作系统"

Skill 激活后，AI 会根据你的具体问题挑选最相关的 2-3 个模型/启发式来分析，而不是一次性搬出所有框架。

## 适用场景

- 经营决策分析（定价、选品、渠道策略）
- 团队管理与协作规范设计
- AI 工具使用策略与边界判断
- 数据分析口径审查
- 精益改善与流程优化
- 方案评审与假设挑战

## 定制

这套框架来自连锁零售/实业经营场景。如果你的业务不同，建议：

1. 保留底层认知（贝叶斯思维）和通用模型（M1-M8, M14-M15）
2. 根据自己的行业调整决策启发式中的具体规则
3. 用自己的真实案例替换示例
4. 定期做增量蒸馏（建议每季度一次），用新的实践证据更新框架

## License

MIT
