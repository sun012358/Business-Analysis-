# Business Analysis Skills Pack

[English README](README.md)
[安装说明](INSTALL.zh-CN.md)

一套适合商业判断、项目分析和创业验证的公开 skill 包。

目前包含 3 个可复用 skill：

- `project-analysis`：项目分析快捷入口
- `venture-validation`：创业验证与 Go / Pivot / Kill 判断
- `business-analysis`：更广义的商业分析、竞品分析和方向判断

## 适合谁用

这套 skill 适合：

- 想判断一个项目值不值得做的创业者
- 想比较多个方向的小团队
- 想拆解竞品和商业模式的运营者
- 想沉淀自己商业分析方法论的使用者

## 仓库结构

```text
skills/
  business-analysis/
  project-analysis/
  venture-validation/
```

每个 skill 都包含自己的 `SKILL.md`，部分 skill 还包含配套参考文件。

## 包含的 Skill

### 1. `project-analysis`

这是一个简单入口，适合平时随手调用。

示例：

```text
请调用 project-analysis，帮我分析这个项目。
```

它会把宽泛的“项目分析”请求路由到更深一层的 `venture-validation`。

### 2. `venture-validation`

适合用来做结构化创业判断，包括：

- 五模块拆解
- 最高风险假设
- 低成本验证方案
- Go / Pivot / Kill 结论

示例：

```text
请调用 venture-validation，按五模块拆解这个项目，识别最高风险假设，并给出低成本验证方案和 Go/Pivot/Kill 结论。
```

### 3. `business-analysis`

适合更广义的商业分析，比如：

- 赛道是否值得做
- 竞品如何赚钱
- 哪一层值得模仿
- 多个方向如何排序

示例：

```text
请调用 business-analysis，判断这个方向值不值得进入。
```

## 安装方式

把 `skills/` 下面的 skill 文件夹复制到你的 Codex skills 目录里。

典型目录：

```text
$CODEX_HOME/skills/
```

复制完成后，目录结构类似：

```text
$CODEX_HOME/skills/business-analysis
$CODEX_HOME/skills/project-analysis
$CODEX_HOME/skills/venture-validation
```

## 推荐用法

### 简单入口

```text
请调用 project-analysis，帮我分析这个项目。
```

### 深度创业验证

```text
请调用 venture-validation，并输出：
1. 项目类型
2. 五模块拆解
3. 最高风险假设
4. 低成本验证方案
5. Go / Pivot / Kill 结论
```

### 更广义商业判断

```text
请调用 business-analysis，并告诉我：
1. 这个业务大概率怎么赚钱
2. 哪一层值得抄
3. 哪一层不值得抄
4. 是否适合 2-3 人团队
```

## 说明

- 这个公开仓库不包含私有案例库、私有判断偏好和私有方法论笔记。
- 当前仓库使用 `MIT License`，方便别人学习、复用和二次改造。
- 如果你后续有私有增强版，建议继续单独维护，不要和公开层混在一起。
