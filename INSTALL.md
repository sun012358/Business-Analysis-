# Install Guide

[简体中文版安装说明](INSTALL.zh-CN.md)

## What You Will Install

This repository ships three skills:

- `project-analysis`
- `venture-validation`
- `business-analysis`

You only need to copy these skill folders into your local Codex skills directory.

## Option 1: Install from GitHub ZIP

1. Open the repository on GitHub
2. Click `Code`
3. Click `Download ZIP`
4. Unzip the repository locally
5. Copy the folders under `skills/` into your local Codex skills directory

## Option 2: Install with Git

```bash
git clone https://github.com/sun012358/Business-Analysis-.git
```

Then copy the folders under `skills/` into your local Codex skills directory.

## Target Directory

Typical target:

```text
$CODEX_HOME/skills/
```

After copying, your structure should look like:

```text
$CODEX_HOME/skills/business-analysis
$CODEX_HOME/skills/project-analysis
$CODEX_HOME/skills/venture-validation
```

## Quick Install Example

If you already downloaded this repository, the practical action is:

1. Open the downloaded folder
2. Open `skills/`
3. Copy:
   - `business-analysis`
   - `project-analysis`
   - `venture-validation`
4. Paste them into your local `$CODEX_HOME/skills/`

## How To Check Installation

After installation, try prompts like:

```text
Please call project-analysis and help me analyze this project.
```

```text
Please call venture-validation and evaluate whether this project should go, pivot, or kill.
```

```text
Please call business-analysis and judge whether this niche is worth entering.
```

If your environment recognizes these skills, installation is complete.

## Updating Later

When this repository gets updated:

1. Download the latest ZIP again or pull the latest changes with Git
2. Replace the local skill folders with the updated ones

## Notes

- This repository is a public layer only.
- Private frameworks, private notes, and private case libraries are intentionally excluded.
- If you want to customize the skills for your own work, copy them locally first and extend them in your own private version.
