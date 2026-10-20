# efficient-writing-secrets

> 把「他们说／我说」这套对话式写作方法，做成 Agent 可复用的技能包。

**来源**：《高效写作的秘密：从模型与动力机制到学术对话的写作法》——
（美）杰拉尔德·格拉福、凯茜·比肯施泰因著，姜昊骞译，天地出版社 2019。
英文原著 *They Say / I Say: A Rhetoric of Belonging*（第三版）。
用 [book-to-skill](https://github.com/virgiliojr94/book-to-skill) 生成。

## 它解决什么

写论证性文字时，绝大多数失败不是「没观点」，而是：

- 不知道自己在回应谁，读者也无从判断你的位置
- 归纳别人时歪曲了，或者写成「首先…接着…另外…」的罗列
- 引文往正文里一扔就不管，读者接不上
- 该有的让步、反对意见、意义说明全部缺席
- 句子之间没有连接，读者得自己猜

这个技能把这套技法拆成**可执行的检查表**：写之前三个必答问题，每段七件套检查，修订十步动线。

## 安装

```bash
# 装到任意支持 Agent Skills 的宿主
npx skills add https://github.com/lklbar666/efficient-writing-secrets --skill efficient-writing-secrets
```

或直接把本仓库根目录的 `SKILL.md` 与 `chapters/`、`references/` 放进你的技能目录。

## 目录

```
SKILL.md              主文档：核心框架 + 章节索引 + 主题索引
chapters/             17 章，每章含 Core Idea / 框架 / 概念 / 心智模型 / 反模式 / 实例 / 要点
glossary.md            术语表
patterns.md            12 个模式（何时用 / 怎么做 / 代价与边界）+ 反模式对照表
cheatsheet.md          速查：写前三问、表态选择、段落七件套、连接词功能表、修订十步
```

## 用法

- 「用 efficient-writing-secrets 帮我把这封邮件改成对话式写法」
- 「按这个技能检查一下我这段话：读者能分清哪个声音是我的吗？」
- 「efficient-writing-secrets 给我 ch08 的连接词功能表」

## 版权与出处

本仓库内容是**对原书方法的综合提炼**，**不包含原书原文摘录**。
原书版权归杰拉尔德·格拉福、凯茜·比肯施泰因与出版方所有。
引用格式：

> 高效写作的秘密：（美）杰拉尔德·格拉福、凯茜·比肯施泰因著，姜昊骞译。天地出版社，2019。
