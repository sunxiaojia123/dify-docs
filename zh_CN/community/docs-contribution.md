# 为 Dify 文档做出贡献

Dify 帮助文档是一个[开源项目](https://github.com/langgenius/dify-docs)，我们欢迎任何形式的贡献。如果你在阅读文档时发现任何问题，亦或是想要为动手写作，贡献自己的一份力量，欢迎你在 Github 上提交 issue 或者直接发起 pull request，我们将尽快处理你的请求。

## 如何提交贡献

我们将文档问题分为以下几类：

- 内容勘误（错别字 / 内容不正确）
- 内容缺失（需要补充新的内容）

### 内容勘误

如果你在阅读某篇文档的时候发现存在内容错误，或者想要修改部分内容，请点击文档页面右侧目录栏内的 **“在 Github 上编辑”** 按钮，使用 Github 内置的在线编辑器修改文件，然后提交 pull request 并简单描述本次修改行为。标题格式请使用 `Fix: Update xxx`，我们将在收到请求后进行 review，无误后将合并你的修改。

![](../../img/zh-docs-contribution.png)

当然，你也可以在 [Issues 页](https://github.com/langgenius/dify-docs/issues)贴上文档链接，并简单描述需要修改的内容。收到反馈后将尽快处理。

### 内容缺失

如果你想要提交新的文档至代码仓库中，请遵循以下步骤：

1. 拉取代码仓库

使用 Git 拉取代码仓库至本地：

```bash
git clone https://github.com/langgenius/dify-docs.git
```

> 你也可以使用 Github 在线代码编辑器，在合适的目录内提交新的 md 文件。

2. 找到对应的文档目录并提交文件

例如，你想要提交第三方工具的使用文档，请在 `/guides/tools/tool-configuration/` 目录内提交新的 md 文件（建议提供中英双语内容）。

3. 提交 pull request

提交 pull request 时，请使用 `Docs: add xxx` 的格式，并在描述栏内简单说明文档的大致内容，我们在收到请求后进行 review，无误后将合并你的修改。

## 获取帮助

如果你在贡献过程中遇到困难或者有任何问题，可以通过相关的 GitHub 问题提出你的疑问，或者加入我们的 [Discord](https://discord.gg/AhzKf7dNgk) 进行快速交流。