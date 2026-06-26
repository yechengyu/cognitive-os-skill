# 澄宇经营决策框架 (chengyu-perspective)

> 基于实业经营实践蒸馏的认知操作系统，封装为 Claude Code Skill。

## 这是什么

一套从日志、决策记录、团队协作中蒸馏出的经营决策框架，包含：

- **贝叶斯式思维**（底层认知）
- **精益六原则**：行知合一 / 持续改善 / 率先垂范 / 三现主义 / 凡事彻底 / 人是目的
- **16 个心智模型**：从"资源有限，限制并行"到"组织流程须与外部环境同步迭代"
- **28 条决策启发式**：覆盖数据判断、执行节奏、团队协作、精益改善、定价选品等
- **6 条反模式**：禁止自嗨、禁止完美主义、禁止沉默吞错等

## 安装

将 `SKILL.md` 复制到你项目的 `.claude/skills/chengyu-perspective/` 目录下：

```bash
mkdir -p .claude/skills/chengyu-perspective
curl -o .claude/skills/chengyu-perspective/SKILL.md \
  https://raw.githubusercontent.com/yechengyu/cognitive-os-skill/master/SKILL.md
```

## 使用

安装后，在 Claude Code 对话中说：

- "用澄宇的角度给个意见"
- "澄宇会怎么看这个方案"
- "叶总视角帮我审一下"
- "老板会 challenge 什么"
- "帮我用认知框架分析"
- "挑战一下我的逻辑"

Skill 激活后，AI 会根据具体问题挑选最相关的 2-3 个模型/启发式来分析，主动挑战你的逻辑漏洞。

## License

MIT
