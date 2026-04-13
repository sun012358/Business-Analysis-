# 安装说明

[English Install Guide](INSTALL.md)

## 你会安装什么

这个仓库目前包含 3 个 skill：

- `project-analysis`
- `venture-validation`
- `business-analysis`

你需要做的，就是把这 3 个 skill 文件夹复制到你本地的 Codex skills 目录里。

## 方式一：从 GitHub 下载 ZIP

1. 打开 GitHub 仓库页面
2. 点击 `Code`
3. 点击 `Download ZIP`
4. 在本地解压
5. 打开解压后的仓库目录
6. 把 `skills/` 下面的 skill 文件夹复制到你本地的 Codex skills 目录中

## 方式二：使用 Git

```bash
git clone https://github.com/sun012358/Business-Analysis-.git
```

然后进入仓库目录，把 `skills/` 下的 skill 文件夹复制到你本地的 Codex skills 目录即可。

## 目标目录

通常目标目录是：

```text
$CODEX_HOME/skills/
```

复制完成后，目录结构应类似：

```text
$CODEX_HOME/skills/business-analysis
$CODEX_HOME/skills/project-analysis
$CODEX_HOME/skills/venture-validation
```

## 最简单的安装动作

如果你已经下载好仓库，直接按下面做：

1. 打开仓库目录
2. 打开 `skills/`
3. 复制这 3 个文件夹：
   - `business-analysis`
   - `project-analysis`
   - `venture-validation`
4. 粘贴到你本地的 `$CODEX_HOME/skills/`

## 如何确认安装成功

安装完成后，可以试着输入下面任意一句：

```text
请调用 project-analysis，帮我分析这个项目。
```

```text
请调用 venture-validation，判断这个项目应该 Go、Pivot 还是 Kill。
```

```text
请调用 business-analysis，判断这个方向值不值得进入。
```

如果环境能识别这些 skill，就说明安装成功了。

## 后续更新

以后如果仓库更新了：

1. 重新下载最新 ZIP，或用 Git 拉取最新版本
2. 用新版 skill 文件夹覆盖你本地旧版本

## 说明

- 这个仓库只包含公开层，不包含私有方法论、私有案例库和私有判断笔记。
- 如果你想做自己的增强版，建议先复制到本地，再基于自己的工作方式继续扩展。
