# 中文创作者指南

**我们推荐你直接使用英文来制作实验或挑战**，而不是先使用中文写好后再翻译。

这不需要你很流利的英文表达能力，差不多匹配大学四六级的英文读写能力，基本能够读懂相应技术的英文官方文档即可。

你可以借助一些工具来开始你的第一步。

## 翻译工具

[DeepL](https://www.deepl.com/translator) 是我们最推荐的翻译工具。经过我们的测试，在大多数情况下，它比你知道的其他翻译工具都要准确。

你可以使用网页版，或者 [下载桌面版本](https://www.deepl.com/zh/app/)，完全免费。

一般情况下，**翻译工具可以帮助开始第一句话，这往往也是最艰难的。**

## AI 补全

GitHub Copilot 是 GitHub 推出的一个 AI 代码补全工具，它可以帮助你完成代码的编写。与此同时，它也支持英文文本的补全，帮助你更快速的写下去。

你可以在 [GitHub Copilot](https://copilot.github.com/) 上体验它。目前 GitHub Copilot 提供 2 个月的试用，之后需要付费 100 USD/年。

如果你能够和 GitHub Copilot 形成默契，那么你将会拥有一个非常强大的工具。我们也会持续分享一些 GitHub Copilot 的使用心得和模式。

如果你觉得 GitHub Copilot 的费用较高，**也可以使用** [**CodeGeeX**](https://marketplace.visualstudio.com/items?itemName=aminer.codegeex)**，它完全免费**，功能和 GitHub Copilot 相似。具体的体验可能有一些区别，我们没有做过严格的对比测试，你也可以向我们反馈体验。

{% hint style="info" %}
你现在看到的这篇内容，其中 50% 是由 GitHub Copilot 自动补全的。😏
{% endhint %}

## 语法校验

我们强烈推荐（要求）你在转写完英文实验/挑战内容后，使用 [Grammarly](https://www.grammarly.com/) 校验语法。Grammarly 是一个在线的语法校验工具，你可以在 [Grammarly](https://www.grammarly.com/) 上注册账号，然后在浏览器中安装插件，即可使用。

Grammarly 有免费版和付费版，免费版可以满足你的日常使用。

鼓足勇气开始你的第一步吧，相信你尝试制作一个实验或挑战后，你会发现这并不是那么难。

## 试写说明

所有的新晋作者都需要先完成内容试写。

### 试写目标

1. 至少完成一组配套的 Lab/Challenge，包含 1 个 Lab 和 1 个 Challenge，需要包含多个 steps。
2. 提交的试写 Lab 和 Challenge 是最好是配套的。[参考说明](labs-and-challenges.md#more-details)。

> 这里再说明一下 lab/challenge 的相同点和不同点：你可以简单理解，lab 和 challenge 唯一的区别就是内容表述方式，和 `index.json` 中有一个 `type` 进行区分。二者在组织结构，所需要素上基本一致，包括 `verify` 脚本等。对于相同的 Skills，你可以把 lab 当作 guided mode 学习模式，而 challenge 则是 challenge mode。相当于一个把答案融在了步骤中，用户跟着学。另一个只有目标，用户需要自己搞定。这也就是为什么推荐大家选好一组 skills 之后，二者搭配来写，同时提供给我们。

### 试写要求

- 试写 Lab/Challenge 包含的 Skills 需要从我们提供的 Skill Tree 中选择。单个 Lab/Challenge 包含的 Skills 尽可能属于同一个 Skills Group。
- Fork 试写仓库，通过 PR 提交试写内容到仓库中。
  - 试写仓库（推荐）：[https://github.com/huhuhang/labex-trial](https://github.com/huhuhang/labex-trial)
  - 国内镜像：[https://gitee.com/huhuhang/labex-trial](https://gitee.com/huhuhang/labex-trial)
- 环境测试和截图可以暂时使用：[https://www.lanqiao.cn/courses/16516/](https://www.lanqiao.cn/courses/16516/)
- 请严格遵循本指南的其他要求和规定。

### 常见问题

{% hint style="info" %}
以下列出试写作者的常见问题，请注意避免。
{% endhint %}

1. 全文提交前，请【务必】使用 Grammarly 检查拼写和语法。大部分作者都有拼写错误的问题，其实可以及早发现。我们提供了高级版账号供大家使用，可以在试写群内索取。
2. 内容制作时，尽量不要用 test，demo 这类关键词，感觉有点草率。可以给例子取一个大名。
3. 两段挨着特别紧的句子，最好变化一下英文句式，否则看起来比较乏味。例如每个段落都以 Let's 开头，或者都以 We 开头，这样看起来比较单调。
4. 多阅读和学习一些外网相同技术方向的英文内容，学习一些地道的句式和持续进步。包括我们的竞品 Educative，Codecademy 等。大家在制作内容是，推荐先去外网寻找一些优质案例。多看一些别人写的内容，站在「巨人」的肩膀上生产内容，能让你的内容质量更好并且更快。目前因为我们选择的方向和知识点都很成熟了，互联网上应该有很多优质内容沉淀。但是，参考不等于抄袭，请大家务必把握好。**同样作为内容创作者，我们对于抄袭的态度是零容忍。**
5. 一些分本次 lab/challenge 关心的 skills，尤其是准备步骤，请合理利用 `setup.sh` 启动脚本。避免内容涉及 Skills 被扩大化，跑题等。
