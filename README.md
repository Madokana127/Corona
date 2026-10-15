# Corona（日冕）

一部长篇小说，设定于 2666 年。三人共创。

仓库本体是一个 [Obsidian](https://obsidian.md) 库——全部内容以 Markdown 笔记存放。

## 当前状态

- 创作进行中：设定与文稿在逐步整理、补齐
- 主仓 `main` 分支为最新版

## 库里的东西

| 文件 | 说明 |
| --- | --- |
| `IDEA.md` | 灵感速记 |
| `设定.md` | 世界观与设定集 |

之后会增加更多条目，尽量一页一个主题。

## 怎么参与

协作方式：**在主仓开分支 → 提 Pull Request → 合并**。`main` 已开启分支保护——所有变更必须经 PR，禁止直推、强推与删除，对三个人一律适用。

### 0. 准备

- 只读浏览：什么都不用装，在 GitHub 网页上看即可
- 想动笔：需要 [Git](https://git-scm.com/) 与 [Obsidian](https://obsidian.md/)（免费）
- 你的账号已加入本库协作者——直接在主仓操作即可，**不需要 fork**

### 1. 克隆主仓

```bash
git clone https://github.com/Madokana127/Corona.git
cd Corona
```

### 2. 用 Obsidian 打开

Obsidian →「打开文件夹作为库」→ 选择克隆下来的 `Corona` 文件夹。

### 3. 动笔前，切一个自己的分支

```bash
git checkout main
git pull
git checkout -b cyla/环参数     # 分支名随意——写清「谁/做什么」，短一点就好
```

### 4. 写作与提交

在 Obsidian 里正常写，写完提交并推送自己的分支：

```bash
git add -A
git commit -m "改动说明"
git push -u origin cyla/环参数
```

### 5. 提 PR 并合并

在 GitHub 上，从你的分支向 `main` 发起 **Pull Request**，看一遍内容后点 **Merge**。
（当前设置：不需要他人批准，但必须走 PR——直推 `main` 会被拦下。）

没做过的话，见 [GitHub 官方文档：创建拉取请求](https://docs.github.com/zh/pull-requests/how-tos/create-pull-requests/creating-a-pull-request)。

### 6. 收尾：回到最新状态

```bash
git checkout main
git pull
```

> 不想敲命令行：在 Obsidian 中安装社区插件 **Git**（[Vinzent03/obsidian-git](https://github.com/Vinzent03/obsidian-git)），Commit / Pull / Push 都能在界面里完成；开 PR 与合并仍在 GitHub 网页上。

## 约定

- 用 Markdown 写，中文文件名没问题
- `.obsidian/` 是各人的本地配置（界面布局、插件等），不入库——按各自的习惯用即可
- 提交信息写清楚「改了什么」即可，不讲究格式
- 移动或重命名文件前先说一声——Obsidian 的 `[[双链]]` 跟着文件名走，改名会让链接断开

## 常见问题

**不想装环境，只想改一点？**

小改动可以直接在 GitHub 网页上编辑文件——提交时选「创建新分支并启动拉取请求」即可（直接提交到 `main` 会被保护规则拦下）。

## 联系

- 主理人：[@Madokana127](https://github.com/Madokana127)
- 共创伙伴：[@EndlessCylA](https://github.com/EndlessCylA)、[@Sluranare](https://github.com/Sluranare)
- 有想法或疑问：[Issues](https://github.com/Madokana127/Corona/issues) 或直接找我们

---

本仓库内容为三人共创作品，未经允许请勿转载或引用。
