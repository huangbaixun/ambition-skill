# Ambition Skill: Altitude · Depth · Range

English | [简体中文](README.md)

Turn a vague request to “do better” into a task with a clear outcome, concrete methods, and verifiable evidence. Use it to review plans, conduct research, shape products, and improve deliverables.

## Source

The methodology comes from **Felix Rieseberg**’s article [How to be more ambitious: A tutorial for humans with models](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/), published on **October 13, 2026**.

This repository adapts the article into a Chinese-language workflow. It is not an official skill released by the author or a word-for-word translation. Read the original article for its full argument and examples. This README provides English documentation; the instructions in `SKILL.md` remain primarily in Chinese.

## The Original Framework and This Skill’s Scope

| Dimension | Meaning | How this skill applies it |
|---|---|---|
| Speed | Complete the same work in less time | Acknowledged as context, not developed as a separate workflow |
| Altitude | Trace an individual task back to its intended outcome | Reconsider the goal and propose deliverables at a higher level |
| Depth | Work with raw materials, professional tools, and underlying problems | Challenge assumptions and specify independent validation |
| Range | Bring in methods and techniques from other fields | Identify the concrete actions and tools each field contributes |

The article identifies all four dimensions but focuses on the last three, treating Speed as already well established. This skill follows that scope; it does not imply that speed is unimportant or requires no method.

## How This Repository Turns the Framework into a Workflow

The following six steps, the number of levels, and the output template are this skill’s structured adaptation. They are not a universal procedure prescribed by the article.

1. **Restate the task:** Confirm what is being reviewed.
2. **Choose dimensions:** Select one to three relevant dimensions and explain why.
3. **Build a progression:** Propose two to three increasingly ambitious levels for each dimension, with prompts ready to use.
4. **List prerequisites:** Identify gaps in data, tools, permissions, and the working environment.
5. **Specify an outside judge:** Define success through tests, independent calculations, held-out datasets, or measurements.
6. **Recommend a route:** Choose a level that can be started and evaluated.

The outside judge should match the claim. Software tests can check implementation logic; predictions about physical equipment also need independent operating conditions or field data. This distinction is application guidance added by this repository.

Keep review and execution separate: confirm execution that has not been authorized, and proceed along the recommended route when authorization already exists. Clearly label exploratory work when evidence is insufficient.

## Usage Examples

These prompts are examples provided by this repository, not quotations from the article.

**Review an existing plan**

> Use ambition to review this plan. Distinguish implemented capabilities, evidence gaps, and exploratory directions. Provide a progression of options, prerequisites, and independent acceptance criteria.

**Go deeper on a task**

> Use ambition’s Depth dimension to review this analysis. Identify which raw data we should revisit, which assumptions need challenging, and how to validate the conclusions using independent data.

**Bring in other disciplines**

> Use ambition’s Range dimension to review this product. For each useful discipline, specify concrete actions, tools, outputs, and validation methods. Recommend the combination worth trying first.

## Files and Installation

- [`SKILL.md`](SKILL.md): Instructions, workflow, and prompts loaded by the AI assistant, primarily in Chinese.
- [`README.md`](README.md): Chinese documentation covering provenance, scope, adaptation, and usage.
- `README-en.md`: English documentation.
- This repository contains no project-specific code, operational data, or project review results.

Place this directory at `~/.codex/skills/ambition/` for Codex or `~/.copilot/skills/ambition/` for GitHub Copilot, keeping `SKILL.md` at the directory root. Explicitly ask “Use ambition to …” in your conversation to request this method.

## Attribution and Licensing Boundaries

The underlying concepts are attributed to the original author. The six-step workflow, output template, and usage examples above are this skill’s organization and adaptation. This documentation does not reproduce the full article or imply endorsement by its author or the author’s employer.

The original skill directory did not include a license, and this repository does not grant an additional open-source license. Attribution alone does not grant permission to republish or relicense the original article.
