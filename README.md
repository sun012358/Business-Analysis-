# Business Analysis Skills Pack

A small public skill pack for commercial judgment and venture validation in Codex-style workflows.

[简体中文版说明](README.zh-CN.md)
[Install Guide](INSTALL.md)

This repository contains three reusable skills:

- `project-analysis`: a simple front-door skill for quick project analysis
- `venture-validation`: a structured startup and business validation skill
- `business-analysis`: a broader commercial judgment skill for projects, competitors, markets, and copyability

## Who This Is For

This pack is useful for:

- founders exploring new ideas
- small teams comparing business directions
- operators doing competitor teardown
- creators building reusable business-analysis workflows

## Repository Structure

```text
skills/
  business-analysis/
  project-analysis/
  venture-validation/
```

Each skill includes its own `SKILL.md` file and supporting references when needed.

## Included Skills

### 1. `project-analysis`

Use this when you want a simple operator-facing shortcut.

Example:

```text
Please call project-analysis and analyze this project.
```

This wrapper routes broad project-analysis requests into the deeper `venture-validation` workflow.

### 2. `venture-validation`

Use this when you want structured venture judgment:

- five-module breakdown
- highest-risk assumptions
- low-cost validation tests
- go / pivot / kill conclusion

Example:

```text
Please call venture-validation, break down this project by five modules, identify the highest-risk assumptions, and give me low-cost validation plans plus a go/pivot/kill conclusion.
```

### 3. `business-analysis`

Use this when you want broader commercial analysis:

- market judgment
- competitor analysis
- business-model breakdown
- copyability judgment
- ranking several opportunities

Example:

```text
Please call business-analysis and evaluate whether this niche is worth entering.
```

## Install

Copy the skill folders under `skills/` into your Codex skills directory.

For a fuller setup guide, see [INSTALL.md](INSTALL.md).

Typical local target:

```text
$CODEX_HOME/skills/
```

After copying, you should have something like:

```text
$CODEX_HOME/skills/business-analysis
$CODEX_HOME/skills/project-analysis
$CODEX_HOME/skills/venture-validation
```

## Suggested Usage

### Simple entry

```text
Please call project-analysis and help me analyze this project.
```

### Deeper validation

```text
Please call venture-validation and output:
1. project type
2. five-module breakdown
3. highest-risk assumptions
4. low-cost validation plan
5. go / pivot / kill conclusion
```

### Broader business judgment

```text
Please call business-analysis and tell me:
1. how this business likely makes money
2. what is worth copying
3. what is not worth copying
4. whether it fits a 2-3 person team
```

## Notes

- This public repository intentionally excludes private notes, private heuristics, and private case libraries.
- This repository uses the MIT License.
- If you want other people to install directly from GitHub later, you can keep this repository as a clean public layer and maintain your private extensions in a separate private repo.
