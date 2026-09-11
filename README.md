# Harness Design Skills

Claude Code custom skills for designing agent "harness" workspaces (project structures agents operate inside), plus a Cartesian-method review skill.

## Skills included

- **cartesian-review** — Reviews a document, design, or plan through 5 Cartesian lenses (enumeration, evidence, synthesis, analysis, methodical doubt) to reach actionable conclusions.
- **harness-designer-coding** — Meta-skill for designing a harness structure (Planner → Generator → Evaluator loop) so a coding agent can reliably generate, test, and deploy code.
- **harness-designer-workspace** — Same Planner → Generator → Evaluator meta-skill, applied to designing a harness for any domain's project workspace (not just code).
- **harness-starter-coding** — Beginner-friendly starter for a coding-domain harness (web app / API / mobile / data-AI). Clones a validated exemplar template instead of free-form design.
- **harness-starter-workspace** — Beginner-friendly starter for a workspace-domain harness (analysis / planning / docs / research). Clones a validated exemplar template instead of free-form design.

## Install

Copy the skill folder(s) you want into `~/.claude/skills/` (Claude Code) or your agent's skills directory.

```bash
git clone https://github.com/kkh2114/harness-design-skills.git
cp -R harness-design-skills/<skill-name> ~/.claude/skills/
```
