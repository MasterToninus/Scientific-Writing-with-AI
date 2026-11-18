# AI documentation — {{PROJECT_TITLE}}

**TEMPLATE — populate from the reported agreement.** Authors: {{HUMAN1_HUMAN2_AND_OTHER_COLLABORATORS}}. Status/date/version: {{POLICY_STATUS_DATE_VERSION}}. No placeholder is evidence of adoption.

| File | Purpose |
| --- | --- |
| [AGENTS.template.md](../../AGENTS.template.md) | Project operating instructions, instantiated from the agreement |
| [CLAUDE.template.md](../../CLAUDE.template.md) | Optional Claude entry point referring to the same canonical policy |
| [README.template.md](README.template.md) | Guide, decision register and actual setup |
| [ACTIVITY_LOG.template.md](ACTIVITY_LOG.template.md) | Dated actual uses, with Human / Tool / Models separate |
| [FULL_AI_DISCLOSURE.template.md](FULL_AI_DISCLOSURE.template.md) | Exact functions, evidence, history limits and scoped claims |
| [TENTATIVE_AI_DISCLOSURE.template.tex](TENTATIVE_AI_DISCLOSURE.template.tex) | Short proposed disclosure, subject to author approval |
| [WORKFLOW.template.md](WORKFLOW.template.md) | Optional, non-normative human-readable summary of the adopted workflow |

**Generation instruction (W22):** this table proposes a layout, not an adopted file set. Provisional drafts may retain clearly labelled proposed outputs. In an adopted packet, retain only the agreed outputs; omit rows and references for outputs not adopted and update paths for the actual layout. Remove `.template` from output filenames, retained links and any adopted Claude import. If the decision register is placed elsewhere, identify its sole location in `AGENTS.md` and update dependent references without dropping decisions. The preparation worksheet stays in its agreed location; do not duplicate confidential preparation material into a public repository by default.

## Language and use of project skills

Human prompts may use any language. The scientific agent writes files in English by default unless explicitly asked to use another language for specified files or passages, within the adopted content permissions and authority rules. The language of a prompt alone does not change file language. Keep this README in English unless the explicit request includes it.

Choose only a project skill whose use and underlying actions are authorised in the inventory below. In Codex, use `$skill-name`; in Claude Code, use `/skill-name`, replacing `skill-name` with its actual name and adding the task and relevant materials. If the host cannot discover it, ask the assistant to read its approved `SKILL.md` and project instructions before the task. An unresolved I23/I24/W23 condition requires a human decision before the affected action. The toolkit's preparation/generation skills are not inherited by this project.

## Decision register

`AGENTS.md` is the canonical project policy and incorporates the designated decision register by reference. The register holds the exact IDs, statuses, conditions, human responsibilities and decision authority. Any adopted `WORKFLOW.md` is a derived, non-normative summary and grants no independent permissions. Keep these documents aligned with the same adopted version. If they diverge, stop the affected action pending reconciliation under the adopted authority and amendment procedure; do not automatically choose the broader rule or rewrite permissions. Independent authorised work may continue.

P = permitted within its recorded scope with ordinary human review as specified in the decision register; C = conditional; V = excluded; ? = unresolved; NA = not applicable, not a permission. An incomplete C is not executable. Any omitted or ambiguous activity remains unresolved.

**Generation instruction:** replace the row below with every activity row from the completed worksheet (193 base activities), plus W01–W23 and AG1–AG6. Preserve ID, meaning, status, conditions, human responsibility and reported agreement. Keep X1–X8 as integrity safeguards, not permissions. Do not import the choices of another collaboration.

| ID | Activity / decision | Status | Conditions, human checks and responsibility | Agreement / source of decision and authority |
| --- | --- | --- | --- | --- |
| {{DECISION_ID}} | {{ACTIVITY_OR_SETTING}} | ? | {{CONDITIONS_OR_UNRESOLVED_POINT}} | {{HUMAN_REPORT_DATE_SCOPE}} |

## Record logic

- Agreed language and granularity: {{LOG_LANGUAGE_AND_GRANULARITY_W12}}.
- Initial record and prior-use treatment: {{INITIAL_LOG_AND_HISTORY_W13}}.
- Evidence retained and responsible human: {{EVIDENCE_RULE_W14}}.
- First-effect commit convention: {{FIRST_EFFECT_COMMIT_W15}}.
- Staging and authorisation: {{STAGING_AND_GIT_W16_W17}}.

The supplied log layout uses one dated English table row per coherent activity. Adopt or adapt it only as agreed. Dates, human identity, tool name and model identity are distinct. Report external uses as attributed statements; do not infer them from Git accounts or model availability.

If using first-effect hashes, use the verified full hash of the first commit carrying the recorded effects. Before it exists use PENDING; untraced history is UNKNOWN with a reason. Its own commit hash cannot be inserted into that same commit without changing it; complete the record later within an authorised operation. A documentation-import hash does not identify untraced earlier manuscript edits.

## Skills inventory and conditions

**Agreed rule:** {{SKILLS_POLICY_I23_I24_W23}}. Replace the row below with the actual adopted inventory, an explicit decision not to use skills, or a precise unresolved question. Merely naming a skill does not authorise it.

| Skill / source | Version or hash | Permitted activity IDs / materials | Invocation mode | Scripts, tools and network dependencies | Decision / authority |
| --- | --- | --- | --- | --- | --- |
| {{SKILL_NAME_SOURCE_OR_UNRESOLVED}} | {{VERSION_HASH_OR_UNKNOWN}} | {{PERMITTED_SCOPE_OR_UNRESOLVED}} | {{AUTOMATIC_MANUAL_OR_UNRESOLVED}} | {{DEPENDENCIES_OR_NONE_OR_UNRESOLVED}} | {{I23_I24_W23_DECISION_AND_AUTHORITY}} |

Skill procedures remain subordinate to the adopted policy and the governing environment. Installation or an update is distinct from permission to use the skill and from permission for its underlying task. Follow the agreed amendment rule when scope or dependencies change. Do not inherit the toolkit builder's skills or autonomy.

When a skill materially contributes, add its name and observed version/hash to the relevant activity record, retaining separate Human, Tool and Models fields. Its availability is not evidence of use; its use alone does not establish acceptance, verification or a particular publisher disclosure requirement.


## Actual setup and pending facts

| Item | Verified value / pending question |
| --- | --- |
| Repository / branch / baseline manuscript version | {{REPOSITORY_BASELINE}} |
| Main source / build command / installed tools | {{MAIN_AND_BUILD}} |
| Marking macros / bibliography backend | {{MACROS_AND_BIBLIOGRAPHY_BACKEND}} |
| Side-note location / excluded paths | {{SIDE_NOTES_AND_EXCLUSIONS}} |
| Tools and actual instruction loading, including any adopted Claude entry point | {{APPROVED_TOOLS_AND_LOADING}} |
| Target venues and verified policy scope/date | {{DESTINATIONS_AND_SOURCE_CHECKS}} |
| Account/material settings requiring confirmation | {{MATERIAL_AND_ACCOUNT_LIMITS}} |

Do not claim successful integration, source audit, compilation, approval or current policy compliance from the existence of these files. For a concrete `?`, stop the affected action and ask the responsible human under the agreed authority rule. For unrelated dormant cases, keep the question pending without repeatedly reopening it.
