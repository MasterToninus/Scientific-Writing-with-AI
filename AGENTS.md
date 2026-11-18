# Scientific Writing with AI — toolkit entry point

This repository helps an AI **build** a collaboration-specific scientific-writing agent. The builder and the resulting research agent have deliberately different operating models.

Read [AI/AGENTS.md](AI/AGENTS.md) for the builder's working instructions. They apply to policy construction throughout this toolkit, including preparation, research, drafting, template maintenance and validation.

## Broad autonomy for the builder

Use the capabilities, tools and permissions available in the user's environment to complete the requested work proactively. This toolkit adds no separate tool allowlist or approval gate for routine preparation. Choose the workflow, investigate, draft, revise, automate and delegate as useful within the user's task and the governing environment instructions.

The future collaboration's unresolved permissions do **not** restrict the builder's preparatory work. A `?` about AI literature research in the future paper, for example, does not prevent the builder from researching AI policies. Draft alternatives and provisional project instructions while decisions are pending; label proposals accurately rather than treating them as adopted rules.

Actual decisions still belong to the humans. Broad construction autonomy does not establish an agreement, fabricate evidence, or expand the scope of a separate manuscript task. The user's instructions and environment remain the authority for access, external actions and consequential operations. The maintainer explicitly authorised this generic toolkit to be public at https://github.com/MasterToninus/Scientific-Writing-with-AI on 2026-11-18. This applies only to the reusable toolkit; private project worksheets, generated packets and manuscript materials remain outside its upload scope. Any later visibility change requires an explicit instruction.

## Language

Accept human prompts in any language and communicate in the human's preferred language. **Write all files in English by default**, including README files, instructions, worksheets, documentation, prompts, prose, comments and maintenance records. Use another language only when the human explicitly requests it for identified files or passages; apply that exception only to the requested scope. The language of a prompt alone is not a request to change the language of files.

Keep README files in English unless an explicit request specifically includes them, and explain briefly how to use the skills relevant to that directory. Translate decisions faithfully. Preserve exact source quotations, bibliographic titles, identifiers and commands where fidelity requires it; this language rule does not authorise unsolicited translation or changes to existing scientific content. Generate the scientific agent with this same language default and scoped-exception rule. Claude entry points and skill adapters inherit it from the canonical instructions.

## Keep the roles separate

- `AI/AGENTS.md` is the active, broadly autonomous **builder** guide.
- `AI/AGENTS.template.md` is inert source material for the **controlled scientific agent**. Its detailed permissions become operative only in the adopted project-specific output.
- Keep reusable templates neutral: Human1/Human2, blank approvals and unresolved collaboration choices. Store completed project copies separately.
- Never mistake template text or a proposal for instructions governing the builder. Conversely, do not transfer the builder's broad autonomy into the generated scientific policy.

## Skills and tool entry points

Use relevant repository skills from [SKILLS.md](SKILLS.md), or other skills available in the user's environment, when they help the requested task. Skills provide reusable procedures; they do not add permission gates to routine builder work or override the actual task/environment. Automatic selection remains available, as does an explicit request. The future research agent's unresolved skill choices do not constrain this builder.

Keep substantive procedures in `.agents/skills/`. The corresponding `.claude/skills/` files are thin discovery adapters referring to those canonical procedures. Keep their names and descriptions aligned. `CLAUDE.md` imports these same canonical agent instructions; do not maintain a separate Claude policy.

Keep paths relative, exact filename casing, UTF-8 text and platform-neutral instructions. Do not require symlinks, a Windows drive path, a particular shell or a global skill installation. Check actual host loading before claiming activation; a desktop/chat interface may need explicit instruction loading. The generated scientific agent and any project skills remain governed by the collaboration's adopted policy.

## Repository conventions

- Preserve existing work and meaningful provenance. Follow the user's actual task scope for Git operations; a documentation edit does not itself authorise unrelated commits or uploads. For this toolkit, use the explicitly authorised public GitHub destination and verify it before a requested upload. Do not infer publication authority for a scientific project or private working copies.
- New commit messages use `[AI] ` for predominantly generated content (approximately 90%), `[AI-Human] ` for human–AI collaboration, and no tag only for human-authored content. Classify the changes, not the Git account; preserve historical messages and do not invent percentages. Use concise technical English and report actual validation.
- Do not stage a PDF when its generating LaTeX sources are present. Use targeted ignore rules and preserve existing tracking/staging until any conflict is resolved with the user.
- Keep the two-date comment header in toolkit LaTeX sources. Template fields remain explicit placeholders; actual files use verified creation history and the latest real edit date, never invented dates.
- Validate the files you change, preserve the full decision catalogue, and keep the README's maintenance record factual. Source and project examples must not introduce invented usage, approval or verification claims.
