# Claude Code 状态词词典：英文含义、中文翻译与梗来源

**Claude Code Spinner Verbs in Chinese: meanings, translations and origins**

Claude Code 干活时，终端里转圈的图标旁边会滚动显示 `Clauding`、`Schlepping`、`Flibbertigibbeting`、`Reticulating` 这类英文单词。它们叫 **spinner verbs（状态词）**，是随机抽取的趣味动词，用来表示「正在处理中」，和当前任务的具体内容无关。

本仓库把这些状态词逐个整理成中文词典，每个词包含四列：

| 列 | 内容 |
| --- | --- |
| 单词 | Claude Code 里显示的英文原词 |
| 原始含义 | 这个英文单词在词典里的本义 |
| 趣味含义 | 放在 AI 写代码的场景里，Claude 的潜台词 |
| 梗来源 / 文化分类 | 词源、出处或所属文化，比如烹饪、爵士乐、科幻、程序员 meme |

共收录 **187 个**状态词。完整词典见 **[spinner-verbs-zh.md](./spinner-verbs-zh.md)**。

## 常见问题

### Claude Code 里的 Clauding 是什么意思？

Clauding 是用 Claude 的名字造的词，意思是「像 Claude 一样干活」，属于 Anthropic 的自家品牌梗。

### Reticulating splines 是什么梗？

出自游戏《模拟城市 2000》的加载画面。那句是故意写的假进度提示语，后来成了程序员圈的经典 meme。

### Flibbertigibbeting 是什么意思？

本义是「轻浮、话多」，Flibbertigibbet 是莎士比亚《李尔王》里一个恶魔的名字。

### Schlepping 是什么意思？

来自意第绪语，意思是拖着笨重的东西走，放在这里就是「扛着一堆依赖在跑」。

### 状态词显示的是 Claude 正在做的事吗？

不是。状态词随机出现，只表示 Claude 还在工作，和它正在处理的具体任务没有关系。

### 可以改成自己喜欢的状态词吗？

可以。在 `~/.claude/settings.json` 里加上 `spinnerVerbs` 配置：

```json
{
  "spinnerVerbs": {
    "mode": "append",
    "verbs": ["摸鱼中", "炼丹中", "Pondering my orb"]
  }
}
```

- `append`：在内置状态词的基础上追加你自己的词。
- `replace`：只用你自己的词，不再显示内置状态词。

## 速览：几个最有代表性的梗

| 状态词 | 一句话解释 |
| --- | --- |
| Clauding | Claude 本尊在 Clauding，自家品牌梗 |
| Reticulating | 《模拟城市 2000》的假进度语 Reticulating splines |
| Pondering | 2021 年的网络梗 pondering my orb |
| Cooking | 烹饪，加上 "let him cook" 梗 |
| Recombobulating | discombobulate 的反向造词，美国密尔沃基机场真有一块 Recombobulation Area 指示牌 |
| Vibing | Z 世代俚语，感觉对了就干 |
| Wrangling | Data Wrangling，对乱数据进行清洗 |
| Herding | 出自老话 herding cats，赶着一群 agent 干活 |

## 关于本词典

- 词表以 Claude Code 内置的状态词为准。不同版本的内置词表会有增减，如果发现缺词或新词，欢迎提 Issue 或 PR。
- 「趣味含义」一列是带调侃色彩的意译，不是官方解释。
- 「梗来源」一列整理了常见的词源和文化出处，有不同说法的欢迎补充。

## English summary

Claude Code shows playful **spinner verbs** such as *Clauding*, *Schlepping*, *Flibbertigibbeting* and *Reticulating* while it works. This repo is a Chinese dictionary of 187 Claude Code spinner verbs, giving each word's literal meaning, a Chinese translation, its humorous meaning in an AI coding context, and the meme or cultural origin behind it. See [spinner-verbs-zh.md](./spinner-verbs-zh.md).

Keywords: Claude Code spinner verbs, Claude Code thinking words, Claude Code loading words meaning, Claude Code 状态词, Claude Code 思考词, Claude Code 加载词是什么意思, spinnerVerbs, Anthropic, AI coding.
