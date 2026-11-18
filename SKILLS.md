# Skills and shared instructions

Skills package reusable procedures. `AGENTS.md` and the [builder guide](AI/AGENTS.md) define the toolkit's operating context; a skill supplies focused guidance for a particular task. Selecting a skill does not grant file access, approve an external action or change a scientific project's permissions.

## Included procedures

| Skill | Use it for | Canonical procedure |
| --- | --- | --- |
| `prepare-ai-policy` | Preparing the discussion and maintaining a collaboration's decision worksheet | [SKILL.md](.agents/skills/prepare-ai-policy/SKILL.md) |
| `build-scientific-agent` | Turning reported decisions into the controlled project agent and documentation | [SKILL.md](.agents/skills/build-scientific-agent/SKILL.md) |
| `integrate-scientific-policy` | Introducing an adopted packet into an existing manuscript repository | [SKILL.md](.agents/skills/integrate-scientific-policy/SKILL.md) |

These skills belong to the policy-building toolkit. The builder can also use other available skills when they help the current task and are permitted by its environment. This list is not a tool allowlist. Ordinary preparation retains the builder's broad autonomy.

## Codex and Claude Code

The maintained procedures live under `.agents/skills/<name>/SKILL.md`. The corresponding files under `.claude/skills/<name>/SKILL.md` contain matching discovery metadata and a relative link to the canonical procedure. They do not maintain a second copy of the workflow.

| Environment | Repository entry | Explicit invocation |
| --- | --- | --- |
| Codex | `.agents/skills/<name>/SKILL.md` | `$prepare-ai-policy`, `$build-scientific-agent`, `$integrate-scientific-policy` |
| Claude Code | `.claude/skills/<name>/SKILL.md` | `/prepare-ai-policy`, `/build-scientific-agent`, `/integrate-scientific-policy` |
| Another assistant with file access | Supply the canonical procedure and its linked project context | Ask in ordinary language to read and follow the relevant file |

Automatic selection remains enabled under the host's ordinary behaviour. Explicit invocation is useful when the desired workflow is known; it is not an additional approval requirement. Users may write requests in any language. Both agents write files in English by default; another language requires an explicit request for identified files or passages. A prompt's language alone does not change file language. README files remain English unless explicitly included in the request.

Open the repository as the working project and verify the relevant skill is discoverable in the actual assistant. If discovery is unavailable, supply the canonical skill and linked instructions manually. Do not claim that every Claude desktop mode, plain chat, connector or other client scans local repository skills. Desktop chat and Claude Code are distinct interfaces; verify the mode being used.

The root `CLAUDE.md` is a bridge to the same canonical instructions used by Codex. Maintain substantive rules in their canonical files, not in separate platform-specific copies. See [Claude's instruction-loading documentation](https://code.claude.com/docs/en/memory) for the supported `@path` import syntax.

## Portable repository layout

The procedures are Markdown with standard `name` and `description` frontmatter. Relative links, consistent filename casing and ordinary files allow the toolkit to travel between Windows, macOS and Linux without symlinks, global installs or a required shell script.

Keep the whole repository together, including the hidden `.agents` and `.claude` directories. The small Claude adapters and the canonical procedures refer to toolkit resources outside their own skill folders: they are **repository-scoped**, not standalone skill-upload bundles. If a particular service requires a self-contained upload, prepare that service's package separately and verify which resources it can access.

Portability of the files does not establish that a particular host loaded or obeyed them. Check discovery and instruction loading in the environment actually used. These files do not configure host permissions, hooks, credentials or automatic jobs.

## Controlled skills in the scientific project

The worksheet's skill-use and maintenance decisions configure the future scientific agent. Record the approved skill, source/version or local revision, purpose, invocation rules, required tools and review authority in the adopted project documentation.

A project skill implements an authorised procedure; it cannot create a permission or bypass a `?`. Its installation, update and underlying actions follow the project's actual policy. Changes affecting permissions follow the agreed amendment process. A reported human acceptance is not an independent verification of scientific correctness.

Do not automatically install these builder skills in a manuscript repository. Generate or select project-specific skills only when the agreement and setup task call for them. Record actual skill-assisted activities proportionately in the existing log, identifying the relevant skill/revision when needed to reconstruct the work; a skill name is not a model identity.

## Maintaining this library

Edit the canonical `SKILL.md` for workflow changes. If its name or description changes, update the matching Claude adapter. Check that relative links resolve and both frontmatter blocks match. Keep adapters thin and preserve the distinction between preparation freedom and scientific permissions.

Sources checked on **2026-11-18**: [OpenAI skill format and repository discovery](https://learn.chatgpt.com/docs/build-skills), [Claude Code skills and invocation](https://code.claude.com/docs/en/skills), and [Claude Code instruction files and imports](https://code.claude.com/docs/en/memory). These document host mechanisms; successful loading in the user's installed version still requires an actual check.
