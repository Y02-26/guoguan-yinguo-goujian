<div align="center">

# 国关因果构建 Skill

面向国际关系与政治学研究的因果解释构建知识库  
从研究困惑到变量、机制、假设、反事实与过程追踪

[![Skill](https://img.shields.io/badge/Codex-Skill-2563eb)](./SKILL.md)
[![Language](https://img.shields.io/badge/Language-中文研究写作-b91c1c)](#)
[![Method](https://img.shields.io/badge/Method-Causal%20Explanation-047857)](#)
[![License](https://img.shields.io/badge/Use-Research%20Assistant-6d28d9)](#)

</div>

---

## 这是什么

**国关因果构建 Skill** 是一个为科研写作和研究设计准备的 Codex skill。它把《国际关系研究实用方法》中“构建因果解释”相关内容整理成可复用的知识库，帮助你把一个模糊的研究兴趣推进为可以检验、可以写进论文的因果解释。

它尤其适合处理这些问题：

- 我的研究问题到底要解释什么现象？
- 自变量、因变量、中介变量、调节条件、混杂变量怎么区分？
- 如何从“X 影响 Y”推进到真正的因果机制？
- 怎样提出主假设、机制假设、范围条件假设和竞争假设？
- 案例研究中如何构造反事实、做过程追踪和比较案例？
- 当经验事实不支持假设时，如何修改而不是硬凑？

---

## 核心用途

这个 skill 的重点很集中：**帮助你构建一个完整、清楚、可被检验的因果解释**。它不替代完整的方法论训练，也不包办案例研究、统计检验或文献检索；它主要服务于理论框架中最关键的那一步：把“某因素可能有影响”推进为“为什么、如何、在什么条件下产生影响”。

| 环节 | 它帮助你明确什么 | 常见产出 |
|---|---|---|
| 因果问题定位 | 要解释的结果 Y 是什么，研究困惑在哪里 | 研究问题与因变量表述 |
| 因果要素拆分 | 原因 X、结果 Y、机制 M、范围条件 S、竞争解释 R | 因果解释框架 |
| 机制链条搭建 | X 如何一步步生成 Y，而不是只停留在相关性 | 分步骤机制链 |
| 假设表达 | 如何把解释写成可讨论、可检验的命题 | 主假设与机制假设 |
| 解释完整性检查 | 是否缺少时序、机制、范围或竞争解释 | 修改建议与检查清单 |

---

## 知识库结构

```text
guoguan-yinguo-goujian/
├── SKILL.md
├── agents/
│   └── openai.yaml
└── references/
    ├── knowledge-map.md
    ├── causal-relations-and-variables.md
    ├── building-causal-explanations.md
    ├── mechanisms-and-hypotheses.md
    ├── counterfactuals-and-case-methods.md
    ├── hypothesis-revision.md
    └── templates-and-checklists.md
```

### 主要文件

| 文件 | 用途 |
|---|---|
| [SKILL.md](./SKILL.md) | Skill 入口，定义触发场景、工作流和知识库导航 |
| [knowledge-map.md](./references/knowledge-map.md) | 总览章节结构、使用方式和来源说明 |
| [causal-relations-and-variables.md](./references/causal-relations-and-variables.md) | 因果关系、变量角色和因果图 |
| [building-causal-explanations.md](./references/building-causal-explanations.md) | 构建因果解释的原则与常见错误 |
| [mechanisms-and-hypotheses.md](./references/mechanisms-and-hypotheses.md) | 因果机制、假设形式和可观察含义 |
| [counterfactuals-and-case-methods.md](./references/counterfactuals-and-case-methods.md) | 反事实、案例比较和过程追踪 |
| [hypothesis-revision.md](./references/hypothesis-revision.md) | 经验异常与假设修正策略 |
| [templates-and-checklists.md](./references/templates-and-checklists.md) | 研究设计模板、检查表和写作脚手架 |

---

## 推荐使用方式

在 Codex 中调用这个 skill 时，可以直接给出你的研究主题、案例或论文设想。例如：

```text
Use $guoguan-yinguo-goujian 帮我把“东盟国家为何在中美竞争中采取不同对冲策略”构造成一个因果解释。
```

```text
Use $guoguan-yinguo-goujian 检查我的假设：安全依赖越高，小国越倾向于追随大国政策。
```

```text
Use $guoguan-yinguo-goujian 为“国际组织指标排名如何影响国家政策改革”设计因果机制和过程追踪证据表。
```

---

## 适合谁用

- 国际关系、政治学、区域国别研究方向的本科生、硕士生、博士生
- 正在写开题报告、课程论文、毕业论文或期刊论文的研究者
- 需要把文献综述转化为理论框架的人
- 想提升因果推断、案例研究、过程追踪能力的人
- 需要快速诊断研究设计漏洞的人

---

## 来源说明

本知识库基于用户提供的《国际关系研究实用方法》相关 PDF 片段整理，重点吸收“构建因果解释”章节的方法论内容，并将其改写为 Codex 可调用的科研工作流。

注意：

- 这是面向研究辅助的整理和转化，不是原书逐字转录。
- 原始 PDF 存在 OCR 和编码噪声，精确页码、引文和原文表述请回到原书核对。
- 本 skill 不会自动生成真实文献引用；如需文献综述，应另行提供文献材料或使用检索工具。


---

<div align="center">

把一个“我觉得有关系”的直觉，推进成一个能被检验、能被反驳、也能写进论文的因果解释。

</div>
