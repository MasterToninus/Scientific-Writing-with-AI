# Scientific Writing with AI

*An agentic template for building a shared AGENTS.md for collaborative scientific writing.*

**Working draft.** This public toolkit supports discussion and preparation of collaboration-specific AI policies. Its options and examples are not a statement of the maintainer's own AI practices or an endorsement of every activity in the catalogue. Completed project worksheets and generated collaboration packets remain separate from the reusable templates.

Use a broadly autonomous AI to help collaborators discuss their boundaries, explore options and turn their decisions into a precise scientific-writing agent. The builder can research, draft, revise, automate and use the tools available in its user's environment. The resulting agent follows the detailed permissions adopted for the scientific project.

**GOAL:** help Human1 and Human2 define the shared context governing their AI chats or repository assistant before using that workflow on a manuscript.

This toolkit supports new and ongoing mathematical and mathematical-physics writing projects. It contains a preparation workflow, a fillable decision catalogue, a policy-building agent and templates for the scientific project's instructions and AI-use documentation. **The collaborators' preliminary discussion is still to take place:** no earlier collaboration's choices are assumed to apply.

## Broad builder, controlled research agent

| Role | Instructions | Operating model |
| --- | --- | --- |
| Policy builder | Root [AGENTS.md](AGENTS.md), with the working guide in [AI/AGENTS.md](AI/AGENTS.md) | Broad autonomy within the user's task, environment and governing instructions; no extra toolkit gate for every preparation step |
| Scientific project agent | Generated from [AI/AGENTS.template.md](AI/AGENTS.template.md) | Precise permissions, conditions, exclusions, review duties and escalation rules agreed by the collaborators |

An unanswered question about the future research agent does not stop the builder from exploring options or preparing a provisional draft. It does prevent that proposed permission from being presented as an adopted rule or used to justify an unapproved manuscript action. Humans choose the boundaries; the builder makes them clear, consistent and usable.

**Human prompts: any language. Files: English by default.** Both the builder and the generated scientific agent can converse in your preferred language. They write files in English unless you explicitly request another language for particular files or passages; writing a prompt in another language does not itself change the output-file language. README files remain English unless your request specifically includes them.

## Codex, Claude and portable skills

The repository uses one policy: [AGENTS.md](AGENTS.md) and the builder guide it references. [CLAUDE.md](CLAUDE.md) imports those same files for Claude Code. Keep the uppercase filenames exactly as written, including on case-sensitive systems.

Three [repository skills](SKILLS.md) support preparation, generation and integration. Their canonical procedures live in `.agents/skills/`; `.claude/skills/` contains small adapters pointing to the same procedures. No symbolic links or machine-specific paths are required. The text workflow is portable across Windows, macOS and Linux; available tools and instruction discovery still depend on the actual application. A plain chat or a desktop mode without repository discovery needs explicit loading, as described in the skills guide.

The builder can select useful skills freely within its current task and environment. The generated scientific agent has separate, precise skill permissions agreed through I23/I24/W23. A skill never supplies missing scientific authority.

### Use a skill

Open this repository as the assistant's working project. Select the procedure and add your goal to the request:

| Goal | Skill | Example task |
| --- | --- | --- |
| Prepare a collaboration's discussion | `prepare-ai-policy` | Prepare our decision worksheet and ask focused questions. |
| Turn decisions into a draft project packet | `build-scientific-agent` | Draft the agent and documentation from our recorded decisions. |
| Install an adopted packet in a manuscript project | `integrate-scientific-policy` | Integrate our adopted policy without changing the manuscript. |

In Codex, invoke `$skill-name`; in Claude Code, invoke `/skill-name`, replacing `skill-name` with the name above and appending your task. You may also ask in ordinary language and let the assistant select a relevant skill. If discovery is unavailable, ask it to read [SKILLS.md](SKILLS.md) and the linked canonical procedure. Actual access and action permissions still apply; naming a skill does not approve a policy or an upload.

## How to use the toolkit

1. Open this repository in your AI environment and have it read the root `AGENTS.md` and `AI/AGENTS.md`. Verify how that environment actually receives instructions; the filename alone is not a loading guarantee.
2. Ask the builder to help you prepare a new collaboration. It can start immediately, choose useful research and drafting steps, and work from a private copy of the [decision worksheet](preparation/DECISION_WORKSHEET.template.md).
3. Human1 and Human2 discuss the relevant choices. The builder can clarify trade-offs, propose alternatives and maintain the record. Individual preferences remain separate from shared agreements; unanswered choices stay `?`.
4. Use the [AI templates](AI/README.md) to develop the project packet. A provisional version can be drafted early; adoption requires the actual agreement and access scope, not merely a complete-looking document.
5. If repository access is selected, follow the [integration guide](INTEGRATION.md) to introduce the adopted instructions into the existing project. The first integration concerns policy and documentation; source-level adaptations follow as separate tasks.

This is a flexible workflow, not a sequence of approvals for routine builder operations. The [preparation guide](preparation/README.md) explains how to keep the human discussion focused.

Example request, which you may give in any language:

> Help us prepare the AI-use policy for a new scientific collaboration. Human1 and Human2 have not yet agreed their boundaries. Use your available capabilities to research and draft useful options, ask focused questions when our decisions are needed, and keep proposed permissions distinct from adopted ones. Maintain the project artifacts in English.

## Repository layout

```text
Scientific-Writing-with-AI/
├── README.md
├── AGENTS.md                       # canonical toolkit entry point
├── CLAUDE.md                       # imports the same instructions
├── SKILLS.md                       # use and portability of repository skills
├── .gitattributes                  # portable text line endings
├── .agents/skills/                 # three canonical skill procedures
├── .claude/skills/                 # Claude discovery adapters
├── INTEGRATION.md                  # adoption in an existing project
├── LICENSE                         # licence retained from GitHub
├── .gitignore
├── preparation/
│   ├── README.md
│   └── DECISION_WORKSHEET.template.md
└── AI/
    ├── AGENTS.md                   # active, broadly autonomous builder
    ├── README.md
    ├── AGENTS.template.md          # controlled scientific-agent template
    ├── CLAUDE.template.md          # bridge to the generated project policy
    └── Docs/AI/
        ├── README.template.md
        ├── ACTIVITY_LOG.template.md
        ├── FULL_AI_DISCLOSURE.template.md
        ├── TENTATIVE_AI_DISCLOSURE.template.tex
        └── WORKFLOW.template.md
```

Human1 and Human2 are placeholders; add collaborators as needed. Tools, models, venues, file access, mathematical assistance, markings and Git operations are choices to discuss. The catalogue retains **193 activities, 8 integrity safeguards and 6 agent-maintenance questions**, with 23 workflow settings. Listing an activity does not permit it in the scientific project.

Completed worksheets may live in `preparation/sessions/<project>/`; generated project packets may live in `AI/generated/<project>/`. These private working directories are ignored by Git. Keep the master templates reusable and keep private project material out of toolkit uploads, including uploads to a private remote.

## What the process keeps distinct

- Permission, actual use, output acceptance and scientific verification.
- AI assistance in policy preparation and later AI assistance on the manuscript, including when the project chooses to exclude the latter.
- Observed activity and human reports about uses outside the current session.
- A provisional proposal, a reported agreement, an adopted policy and approval of a disclosure for submission.
- The collaboration's choices and applicable journal, preprint-server or institutional requirements. Catalogue links are research starting points, not current compliance certificates.

The builder generates a project-specific agent together with a readable workflow, activity log and full/short disclosure templates. Those records must reflect real evidence; they are not filled with the history of an earlier paper.

## Toolkit maintenance

The maintainer explicitly authorised public hosting at [MasterToninus/Scientific-Writing-with-AI](https://github.com/MasterToninus/Scientific-Writing-with-AI). The repository includes the [GNU General Public License v3.0](LICENSE), selected when the GitHub repository was created. Public hosting of this generic toolkit does not authorise publication of private collaboration records, generated project packets or manuscript materials. Further Git operations and changes to visibility remain subject to the actual task instructions.

New toolkit commit messages use `[AI]` for predominantly generated content (approximately 90%), `[AI-Human]` for human–AI collaboration, and no tag only for human-authored content. This convention describes provenance, not permission to commit or publish. Respect actual task authority and preserve historical messages.

| Date | Toolkit maintenance / evidence | Scope and limits |
| --- | --- | --- |
| 2026-11-10 | AI-assisted generalisation of a prior policy-design workflow; a read-only assistant checked catalogue counts and possible inherited assumptions. | Documentation/template work only. Human1/Human2 are future-collaboration placeholders, not reports of their AI use or agreement. No manuscript repository was modified in creating this kit. |
| 2026-11-10 | Converted repository documentation and the decision catalogue to English; separated the broadly autonomous builder in AI/AGENTS.md from the controlled scientific-agent template. | Requested toolkit revision. Users may interact in their preferred language; no scientific permission or collaboration decision was adopted by this change. |
| 2026-11-10 | Prepared private GitHub settings, an upload procedure and an initial commit-message proposal. | Working draft, not a public policy statement. The available browser required sign-in; no remote, commit or upload was created during this preparation. |
| 2026-11-10 | Prepared the complete toolkit for ZIP transfer to another computer and documented Git initialisation after extraction. | All toolkit files are included; the internal .git directory is excluded. At that time, transfer to another computer was planned. |
| 2026-11-18 | Moved the local working copy out of OneDrive into the maintainer's GitHub workspace; compared every file hash and Git status before removing the original. | File contents and Git state were preserved. No commit or remote operation was performed. |
| 2026-11-18 | Added repository skills, shared Codex/Claude instruction entry points and portable paths; extended the undecided scientific-policy catalogue with skill governance. | Builder procedures and future scientific permissions remain separate. Host-specific runtime loading must be checked in the actual application. |
| 2026-11-18 | Clarified the shared language rule: human prompts in any language, files in English unless another language is explicitly requested for a specified scope. Added concise skill-use guidance to all README artifacts. | The builder and generated scientific agent share the rule; Claude imports it. Scientific permissions, adoption status and Git authority are unchanged. |
| 2026-11-18 | Removed the dedicated GitHub setup guide and its README references at the maintainer's request. | The initial upload checklist is supplied in the conversation; private-hosting intent is unchanged. |
| 2026-11-18 | The maintainer explicitly confirmed public hosting and requested the initial toolkit commit and push to the named GitHub repository. | This supersedes the earlier private-hosting preference for the generic toolkit only. The existing initial GitHub commit and its GPL-3.0 licence are retained; private collaboration records remain excluded. |
| 2026-11-18 | Aligned configurable packet layouts and optional bridges; corrected activity mapping, review requirements and disclosure drafting rules. Clarified AGENTS.md as the canonical policy incorporating the decision register, with WORKFLOW as a derived summary and explicit handling of divergences. | Toolkit maintenance only. Master decisions remain unresolved; no collaboration policy or disclosure was adopted. The edited LaTeX template compiled in a separate scratch directory. |
| 2026-11-18 | Applied deferred first-effect SHA completion to both the toolkit agent and the generated project agent, with matching generation instructions and workflow summary. | New effects remain PENDING; the next otherwise-needed authorised AI-prepared commit records eligible earlier effects' verified original SHA. No dedicated metadata commit or immediate post-commit hash update is permitted. W15 remains unresolved in the reusable worksheet; existing Git authority is unchanged. |
