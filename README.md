<div align="center">

# 国关因果构建 Skill

忠于《国际关系研究实用方法》第五章“构建因果解释”的 Codex skill  
帮助你把一个国关研究选题整理成清楚、具体、非模板化的因果解释

[![Codex Skill](https://img.shields.io/badge/Codex-Skill-2563eb)](./SKILL.md)
[![Chapter](https://img.shields.io/badge/Chapter-第五章%20构建因果解释-047857)](#第五章知识结构)
[![Language](https://img.shields.io/badge/Language-中文-b91c1c)](#)
[![Focus](https://img.shields.io/badge/Focus-因果机制与因果假设-6d28d9)](#这个-skill-能帮你做什么)

</div>

---

## 这个 Skill 是什么

这是一个给 **Codex** 使用的本地 skill，主题是国际关系研究中的 **因果解释构建**。

它不是泛化的“论文写作助手”，也不是“研究设计大全”。它专门围绕《国际关系研究实用方法》第五章“构建因果解释”，帮助你处理这些问题：

- 什么是因果关系？
- 原因、结果和变量如何界定？
- 如何用因果图表达变量关系？
- 构建因果解释需要满足哪些原则？
- 如何构建反事实？
- 如何追踪因果机制？
- 如何提出因果假设？
- 遇到经验反常时如何修改因果假设？

---

## 这个 Skill 能帮你做什么

| 任务 | 它会怎么帮你 |
|---|---|
| 构建因果解释 | 根据你的具体选题，识别原因、结果、机制和适用范围 |
| 拆分变量关系 | 区分自变量、因变量、中介变量、调节变量、混杂变量、碰撞变量 |
| 识别国内变量角色 | 判断国内变量是中介、调节、独立原因，还是只是背景条件 |
| 生成因果机制 | 先识别选题特殊性，再构建机制，避免机械套模板 |
| 检查因果假设 | 看假设是否明确、具体、可检验、非同义反复 |
| 修正研究假设 | 当经验事实不支持假设时，检查测量、限界条件和机制问题 |

---

## 安装方式

下面给两种安装方式。你如果是零基础，推荐先看 **方式一**。

### 方式一：用 Git 一键安装

适合：电脑上已经安装 Git，或者愿意先安装 Git 的用户。

#### Windows

打开 PowerShell，复制下面这一整段运行：

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\skills" | Out-Null
git clone https://github.com/Y02-26/guoguan-yinguo-goujian.git "$env:USERPROFILE\.codex\skills\guoguan-yinguo-goujian"
```

#### macOS / Linux

打开 Terminal，复制下面这一整段运行：

```bash
mkdir -p ~/.codex/skills
git clone https://github.com/Y02-26/guoguan-yinguo-goujian.git ~/.codex/skills/guoguan-yinguo-goujian
```

安装后，重启 Codex 或开启一个新对话，让 Codex 重新读取本地 skills。

### 方式二：不用 Git，手动安装

适合：完全不熟悉命令行的用户。

1. 打开仓库页面：  
   [https://github.com/Y02-26/guoguan-yinguo-goujian](https://github.com/Y02-26/guoguan-yinguo-goujian)

2. 点击绿色的 `Code` 按钮。

3. 点击 `Download ZIP`。

4. 解压下载的压缩包。

5. 把解压后的文件夹重命名为：

```text
guoguan-yinguo-goujian
```

6. 把这个文件夹放到 Codex 的 skills 目录：

Windows:

```text
C:\Users\你的用户名\.codex\skills\
```

macOS / Linux:

```text
~/.codex/skills/
```

最终路径应该像这样：

Windows:

```text
C:\Users\你的用户名\.codex\skills\guoguan-yinguo-goujian\SKILL.md
```

macOS / Linux:

```text
~/.codex/skills/guoguan-yinguo-goujian/SKILL.md
```

安装后，重启 Codex 或开启一个新对话。

---

## 如何确认安装成功

在 Codex 里新开一个对话，输入：

```text
Use $guoguan-yinguo-goujian 帮我说明这个 skill 是做什么的。
```

如果 Codex 能围绕“构建因果解释”回答，并提到第五章、因果关系、变量、反事实、因果机制、因果假设等内容，说明安装成功。

如果没有触发，可以检查：

- 文件夹名字是否是 `guoguan-yinguo-goujian`。
- 文件夹里是否有 `SKILL.md`。
- 是否放在 `.codex/skills/` 目录下。
- 是否重启了 Codex 或开启了新对话。

---

## 第一次怎么用

你可以直接把选题发给 Codex，例如：

```text
Use $guoguan-yinguo-goujian
我的选题是：安全依赖如何影响小国外交选择。
请帮我构建一个因果解释，不要套模板，要先分析这个选题的特殊性。
```

也可以让它检查已有想法：

```text
Use $guoguan-yinguo-goujian
我的假设是：安全依赖越高，小国越倾向于追随大国政策。
请检查它是否符合第五章对因果假设的要求。
```

或者让它帮你补机制：

```text
Use $guoguan-yinguo-goujian
我已经有原因 X 和结果 Y，但中间机制说不清楚。
X 是国际组织指标排名，Y 是国家政策改革。
请帮我构建一个具体的因果机制。
```

---

## 第五章知识结构

| 模块 | 第五章中的核心问题 | 知识库文件 |
|---|---|---|
| 因果关系 | 规律性、反事实、机制性因果分别强调什么？ | [causal-relations.md](./references/causal-relations.md) |
| 变量与因果图 | 自变量、因变量、中介变量、混杂变量、碰撞变量如何区分？ | [variables-and-causal-diagrams.md](./references/variables-and-causal-diagrams.md) |
| 中介/调节辨析 | 国内变量什么时候是中介变量，什么时候是调节变量？ | [mediator-vs-moderator.md](./references/mediator-vs-moderator.md) |
| 构建原则 | 时序性、相关性、排除虚假相关/伪相关，以及反事实或机制原则 | [explanation-principles.md](./references/explanation-principles.md) |
| 反事实与机制 | 如何用反事实和因果机制加强因果推断？ | [counterfactuals-and-mechanisms.md](./references/counterfactuals-and-mechanisms.md) |
| 因果假设 | 因果解释如何转化为可检验的因果假设？ | [causal-hypotheses.md](./references/causal-hypotheses.md) |
| 假设修正 | 经验事实不支持假设时如何处理？ | [hypothesis-revision.md](./references/hypothesis-revision.md) |
| 章节例子 | 第五章中可辨认的例子与方法表如何辅助理解？ | [chapter-examples.md](./references/chapter-examples.md) |
| 模板 | 只作为检查和格式化工具，不负责生成统一机制 | [templates.md](./references/templates.md) |

---

## 重要原则：避免模板化

这个 skill 已经加入反模板化规则。

它在生成因果机制前，应先判断：

- 这个选题的具体结果是什么？
- 关键行为主体或实体是谁？
- 议题领域是什么？
- 历史和制度情境是什么？
- 变化发生在信念、激励、能力、信息、合法性还是约束上？
- 这个选题和另一个相似选题有什么不同？

所以，A 选题和 B 选题不应该因为用了同一个 skill 就得到同一个机制。模板只用于最后检查有没有缺项，而不是决定机制内容。

---

## 这个 Skill 不做什么

为保持忠于第五章，本 skill 不默认承诺：

- 自动完成文献综述。
- 自动检索真实文献。
- 自动设计完整统计模型。
- 把“竞争性解释 R”“范围条件 S”当作原书术语。
- 把案例研究、过程追踪、定量检验包装成超出第五章的完整方法论系统。

如果需要这些内容，可以在第五章框架之上另行扩展。

---

## 更新方式

如果你是用 Git 安装的，以后想更新到最新版：

Windows PowerShell:

```powershell
cd "$env:USERPROFILE\.codex\skills\guoguan-yinguo-goujian"
git pull
```

macOS / Linux:

```bash
cd ~/.codex/skills/guoguan-yinguo-goujian
git pull
```

如果你是手动下载 ZIP 安装的，重新下载新版 ZIP，替换旧文件夹即可。

---

## 来源与说明

本知识库根据用户提供的《国际关系研究实用方法》第五章 PDF 片段整理。由于该 PDF 的文本层存在 OCR 与编码噪声，本仓库采用“忠于章节结构和概念”的改写方式，不提供逐字转录。

在第五章框架之上，本版补充吸收冯伟（2024）《不是所有的国内变量都是中介变量——新古典现实主义理论的中介变量与调节变量辨析》的核心辨析，用来加强“中介变量、调节变量、国内变量角色”的识别。该补充只服务于因果解释中的变量判断，不把本 skill 扩展成新古典现实主义专门 skill。

如需精确页码、原文引用或正式引文，请回到原书核对。
