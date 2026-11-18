# Integrating an agreement into an existing mathematical writing project

**Goal:** add the adopted instructions and documentation while preserving the draft, its history and existing human work. Initial integration covers policy/docs and any specifically authorised ignore rules. Applying the resulting policy to scientific sources is a separate task.

The [construction agent](AI/AGENTS.md) can prepare, research and refine the packet autonomously within its user's environment. The restrictions in this guide apply when adopting and installing the generated scientific agent into a manuscript project. They do not turn unresolved scientific-policy choices into limits on independent preparation work.

The reusable prompts below are in English. Both the builder and scientific agent accept human prompts in any language and write files in English by default unless another language is explicitly requested for specified files or passages. A prompt's language alone does not change file language; README files stay English unless the request specifically includes them.

## 1. Before installation

- Use an **instantiated and adopted** packet, not an unresolved copy of `AI/AGENTS.template.md`. A provisional packet may be drafted and reviewed earlier.
- Establish mode B, material access, initialisation operations and the authority rule. If mode A was chosen, use the agreed context in chat without installing an agent with repository access.
- Identify the local repository, branch, manuscript version and applicable instructions. Respect material exclusions when inspecting the project.
- Inspect local edits, untracked files and staging. Preserve unrelated work and existing documentation. Do not automatically stash, reset or rewrite history to make integration easier.
- Establish whether the requested operation is import only, import and staging, or also commit/push. A request may authorise several operations together; do not ask again for authority already supplied.

## 2. Prepare the seven project files

Instantiate the [templates](AI/README.md) in a private working location and rename them:

```text
<manuscript repository>/
├── AGENTS.md
├── CLAUDE.md                       # refers to the same project policy
└── Docs/AI/
    ├── README.md
    ├── ACTIVITY_LOG.md
    ├── FULL_AI_DISCLOSURE.md
    ├── TENTATIVE_AI_DISCLOSURE.tex
    └── WORKFLOW.md
```

Remove `.template` from internal links and from the CLAUDE.md import as well; the final bridge imports `@AGENTS.md`. The output README should retain all decisions and conditions, not only permitted activities. Some `?` entries may remain unresolved; essential setup such as material access cannot become an implicit permission through an unfilled placeholder.

Do not import the entire toolkit, its construction-agent instructions, private worksheets, chats, service prompts or delivery ZIPs into the manuscript repository. If it already contains `AGENTS.md`, AI documentation or an activity log, compare and reconcile compatible material. Preserve real history and refer substantive policy conflicts to the humans.

## 3. Initial integration: policy and documentation only

1. Inspect the main source, macros and configuration within the agreed material access to identify dependencies and record necessary setup facts. Preserve the existing prose, statements, proofs, bibliography, figures, macros, colours and source headers during this initial operation.
2. Import or reconcile the seven files. The manuscript agent is generated from the collaboration's agreement; it is not the toolkit's permissive construction agent. Do not insert the tentative disclosure into the manuscript yet.
3. Where authorised through W20/I5, add targeted ignore rules for PDFs reproducible from repository sources. Do not ignore every PDF indiscriminately. `.gitignore` does not untrack existing files: flag that case and agree how to handle it without deleting local files or disturbing human staging.
4. Check links, correspondence with the reported answers, C conditions and handling of `?` entries. The initial creation record must describe an actual event; unknown historical dates, models or commits remain explicit.
5. If the disclosure is standalone and compilation is in scope, check it using the available tools. Successful compilation of the toolkit template does not establish success in the target project. Handle required installations or build changes according to the actual project permissions and environment.
6. Inspect the final diff against the initial state: this first integration must introduce no scientific-content changes. Stage only the authorised changes, preserving unrelated hunks and index entries.

## 4. Verify how assistants receive the policy

For each tool, record its actual interface/mode, instructions supplied and method of checking instruction loading. Use root `AGENTS.md` as the canonical project policy and root `CLAUDE.md` as a short bridge importing `@AGENTS.md`. Reconcile an existing bridge instead of overwriting other project context. Keep these exact uppercase names, relative paths and UTF-8 text so the packet remains portable across Windows, macOS and Linux.

Claude Code supports file imports in CLAUDE.md; this does not establish automatic loading in every Claude desktop/chat mode. For any host without repository instruction discovery, supply the canonical policy explicitly through that host's supported mechanism. Verify the actual mode before reporting success.

Skills for the scientific project require the adopted I23/I24/W23 choices, including source/revision, permitted scope, invocation and change authority. The toolkit's skills are for building policies; do not install them in the paper as a side effect. Where separately agreed, create tailored project skills and host adapters which refer to the adopted scientific policy. Native discovery in Codex uses `.agents/skills/`; Claude Code uses `.claude/skills/`. Keep one substantive procedure and thin adapters if supporting both, and test referenced paths in each actual host. Procedures and scripts cannot expand the underlying scientific, access, network or Git permissions. See [SKILLS.md](SKILLS.md) for the toolkit's pattern and primary sources.

A short check is to ask the assistant to identify its scope, one C condition and the required response to a `?`, citing the relevant local rule. This can expose loading problems but does not certify every future action. Keep the check within the project's approved material and service boundaries.

## 5. Commits, activity-log hashes and publication

- When authorised, create an initial commit limited to policy/docs and relevant ignore rules. Apply the governing provenance convention and use a concise English message describing scope, changes and actual checks. Exclude reproducible PDFs and unrelated work.
- The first-effect commit hash is known only after that commit exists. Use PENDING beforehand, then inspect the real commit and update the record. Do not try to embed a commit's own hash into itself through amend.
- If the two-date convention was adopted, derive creation from the source's first introduction into the relevant Git history, tracing renames, and update last-modified to the actual edit date. Do not copy the toolkit's dates as the target project's dates.
- A second commit completing only these metadata needs authority, which may already be included in the initial request. It does not require an endless sequence of new activity records: complete the relevant row while preserving its first-effect association.
- Before push, inspect the remote, branch and **all** outgoing commits. Unrelated earlier commits, divergence or an ambiguous destination require a human decision. Force-push, public visibility, PRs, merges and submission are not implied by a policy-documentation request.

## 6. After integration

A separate task may apply permitted source changes such as annotation macros, source-header conventions, refactoring or a bibliography audit. Each action follows the adopted scientific agent's precise permissions and intervention level. Record new activities and checks actually performed; revisit the policy when a concrete case requires it.

## Prompt 1 — adapt, then request integration

Fill the bracketed fields before use. This is a reusable request template, not an authorisation already given. Users may issue an equivalent request in their preferred language.

```text
GOAL: integrate the adopted AI policy into the existing repository without changing pre-existing scientific content.

Repository: [path]. Instantiated packet: [path].
Adopted agreement: [version/date, person reporting it and scope].
Authorised mode/access: [B and limits].
Operations authorised now: [import / staging and applicable files].

Read the applicable instructions and inspect Git state. Integrate only the generated AGENTS.md, its CLAUDE.md bridge and the five Docs/AI documents, reconciling existing files without erasing history. Do not import the preparation toolkit or its construction agent. Essential setup placeholders must be resolved; scientific activities marked ? remain unavailable.

Update only policy/docs and specifically authorised ignore rules. Preserve the existing manuscript, bibliography, figures, macros and source headers; do not insert the disclosure yet. Establish the permitted setup facts, check consistency, links, the activity log and disclosure compilation where in scope. Verify how each assistant receives the instructions and follow the target project's permissions for tool-specific setup or installations.

Preserve unrelated changes and staging. The initial record must describe actual work; retain earlier-use statements as attributed reports. Report completed checks, integration status and any concrete questions. Do not commit or push under this prompt.
```

## Prompt 2 — adapt, then request commit/push

Use after integration and once the Git operations have been decided. Select the tag from actual provenance; approval alone does not establish authorship.

```text
GOAL: record the introduction of the AI policy while excluding all changes to pre-existing scientific content.

I authorise [commit / commit and push] for the policy/docs and approved ignore changes. Repository/branch/remote: [verified values]. Authority for a possible second commit limited to activity-log hashes/source dates: [yes/no].

Recheck actual status and diffs; isolate the authorised changes without altering unrelated work or staging. Exclude reproducible PDFs, preparatory documents, chats, ZIPs and scientific-content changes. If the scope cannot be separated safely, ask about the concrete conflict.

Use the applicable provenance tag and an English message such as:
[TAG] docs: introduce the agreed AI-assisted writing workflow
- Add the shared project instructions and AI-use documentation.
- Record agreed permissions, review rules and unresolved decisions.
- Preserve all pre-existing scientific content.
- Validation: [checks actually performed].

Inspect the created commit, obtain the real first-effect hash and complete the log; if adopted, resolve source dates from the relevant history. Do not rewrite history. Make a second commit limited to these metadata only if authorised above; otherwise report the local metadata update awaiting commitment.

Before an authorised push, check the destination and every outgoing commit. Ask if it would include unrelated work or require resolving divergence; no implicit force-push, merge or PR. Report hashes, destination, actual outcome and remaining local work. Do not repeat generic approval questions for operations already authorised; stop on concrete unresolved issues.
```
