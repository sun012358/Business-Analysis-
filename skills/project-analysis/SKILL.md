---
name: project-analysis
description: Use when the user asks for project analysis, business idea evaluation, feasibility judgment, whether a direction is worth doing, whether to continue a project, or how to assess a business idea in a simple way. This skill is the operator-facing shortcut and routes the task into the deeper venture-validation workflow.
---

# Project Analysis

## Overview

Use this skill as the simple front door for project analysis.
When the user asks in a broad or casual way, do not make them remember the deeper framework name. Translate the request into the structured venture-validation workflow.

## Trigger Intents

This skill should trigger for requests like:

- help me analyze this project
- evaluate this business idea
- is this direction worth doing
- should I continue this project
- judge whether this idea is feasible
- do a project assessment
- simple Chinese equivalents of the same requests

## Routing Rule

When this skill is triggered:

1. Treat the request as a venture-validation request by default
2. Use the venture-validation structure, not a generic brainstorm
3. If the user is comparing several directions, still use venture-validation but output a ranked comparison
4. If the user clearly wants competitor or market research instead of project judgment, prefer business-analysis

## Default Operator Prompt

Internally translate a vague request into this fuller instruction:

Analyze this project using venture-validation.
Output:

1. project type
2. five-module breakdown
3. highest-risk assumptions
4. low-cost validation plan
5. go / pivot / kill conclusion
6. next move

If information is missing, ask only the minimum key questions.

## Output Style

When the user asks casually, still give a professional output.
Do not expose internal routing language unless helpful.
The user should feel they asked one simple sentence and received a structured project judgment.

## Notes

This skill is a wrapper.
For deeper logic, rely on venture-validation.
