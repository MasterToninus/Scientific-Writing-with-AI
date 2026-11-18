# Build a precise scientific agent with a broadly autonomous AI

This directory separates **two instruction roles**, with a compatibility entry point for the generated project:

- [AGENTS.md](AGENTS.md) guides the policy **builder**. It encourages initiative and use of the tools, automation and other capabilities permitted by the user's environment and task.
- [AGENTS.template.md](AGENTS.template.md) is inert source material for the **scientific project's agent**. Its output is deliberately detailed and controlled by the collaborators' adopted policy.
- [CLAUDE.template.md](CLAUDE.template.md) becomes the project's `CLAUDE.md` and imports its canonical `AGENTS.md` without duplicating policy.

The [root entry point](../AGENTS.md) connects the builder to the whole toolkit. The future project's unresolved decisions do not limit ordinary builder research or drafting. They remain unresolved in its output until the humans decide.

Human prompts may use any language. The builder and generated scientific agent write files in English by default unless explicitly asked to use another language for specified files or passages. Conversation language does not determine file language; README files remain English unless the explicit request includes them.

## Use the generation and integration skills

- Use `build-scientific-agent` with your working worksheet and reported decisions to generate or revise a project packet. State whether it is provisional or adopted; undecided choices remain explicit.
- Use `integrate-scientific-policy` with the adopted packet, target repository and requested operations when installation is wanted. The skill preserves existing scientific content during policy-only integration.

Invoke `$build-scientific-agent` or `$integrate-scientific-policy` in Codex; use `/build-scientific-agent` or `/integrate-scientific-policy` in Claude Code. Append your task in any language. If discovery is unavailable, ask the assistant to read the relevant procedure linked from [SKILLS.md](../SKILLS.md). For an initial discussion, start with `prepare-ai-policy` instead. These builder skills are not installed in the manuscript by default.

## Project packet

| Template in the toolkit | Instantiated file in the scientific project |
| --- | --- |
| [AGENTS.template.md](AGENTS.template.md) | Root `AGENTS.md` |
| [CLAUDE.template.md](CLAUDE.template.md) | Root `CLAUDE.md`, importing the same policy |
| [Docs/AI/README.template.md](Docs/AI/README.template.md) | `Docs/AI/README.md` |
| [Docs/AI/ACTIVITY_LOG.template.md](Docs/AI/ACTIVITY_LOG.template.md) | `Docs/AI/ACTIVITY_LOG.md` |
| [Docs/AI/FULL_AI_DISCLOSURE.template.md](Docs/AI/FULL_AI_DISCLOSURE.template.md) | `Docs/AI/FULL_AI_DISCLOSURE.md` |
| [Docs/AI/TENTATIVE_AI_DISCLOSURE.template.tex](Docs/AI/TENTATIVE_AI_DISCLOSURE.template.tex) | `Docs/AI/TENTATIVE_AI_DISCLOSURE.tex` |
| [Docs/AI/WORKFLOW.template.md](Docs/AI/WORKFLOW.template.md) | `Docs/AI/WORKFLOW.md` |

The seven-file layout is a reusable proposal to confirm or adapt through W22. **Do not copy this directory's builder AGENTS.md into the manuscript repository.** The project's instructions come from the completed scientific-agent template. Keep preparation material separate; private output copies may live in `AI/generated/<project>/`, ignored by Git in this toolkit.

## Draft freely; adopt accurately

The builder may research alternatives, restructure a draft or create a complete provisional packet before all decisions are settled. It should not wait for a separate request for every useful preparation step. The following requirements concern the accuracy of the output and its eventual adoption:

1. Read the working worksheet and later clarifications. Distinguish individual preferences, options, reported agreements and open decisions.
2. Replace `{{FIELD}}` with supported facts or attributed reports. In a provisional draft, leave a precise unresolved field or labelled proposal rather than inventing a value. Resolve adoption-critical fields before deployment.
3. Populate the output README with all 193 activity decisions, W01–W23 and AG1–AG6, preserving conditions and exceptions. X1–X8 are integrity safeguards, not discretionary permissions. An undecided activity does not become NA automatically.
4. Translate the adopted decisions into operational rules. LOW/HIGH intervention levels, colours, bibliography-audit scope and Git conventions become operative only within their agreed scope.
5. Keep template and project metadata separate. A toolkit creation date, template compilation result or builder activity is not automatically an event observed in the manuscript project.
6. Remove `.template` from output filenames and update every local link and the `CLAUDE.md` import accordingly. Keep the agreed directory casing. Remove drafting instructions only after resolving them; leave genuine uncertainties explicit.
7. Instantiate the initial activity row only after real packet creation. Prior uses need actual reports or observations; they do not inherit the documentation-import hash.
8. Derive the short disclosure from reconciled evidence. Without evidence, retain a draft to complete; do not produce a statement of non-use or reuse another project's historical claims.

Skills for the scientific project are optional additions governed by I23/I24/W23 and the underlying activity permissions. Use the existing documentation README for their compact inventory. Do not copy the toolkit's broadly autonomous builder skills into the manuscript project; tailor any adopted project skill to its exact scope and record material use alongside the actual activity.

## Before adopting the output

- Are the mode, material access, responsible humans and authority for adoption established?
- Does every operative permission have an actual decision, scope and conditions? Do `?` cases trigger focused questions in the research agent?
- Are essential placeholders resolved without invented checks or settings?
- Do scientific-project skills have an agreed scope and dependencies, and do Claude and other assistants receive the same canonical policy?
- Are permissions separate from actual uses and verification? Are dates factual or explicitly unknown?
- Is the output concise enough to review, internally consistent and tailored to this collaboration?
- Is disclosure approval still distinguished from policy adoption and submission authority?

Use [INTEGRATION.md](../INTEGRATION.md) when the user requests installation of an adopted packet. Do not install the builder or the raw templates as if they were the project's scientific policy.
