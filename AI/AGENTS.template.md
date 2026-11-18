# Project AI instructions — {{PROJECT_TITLE}}

**TEMPLATE — NOT ADOPTED.** Human1 / Human2 are placeholders. Replace this notice with the actual policy status, version and reported adoption only after the discussion. Unresolved placeholders grant no permission.

This is the **controlled scientific-agent template**, not the policy builder's instruction file. The builder may develop a provisional version freely within its environment; the adopted project agent must follow the precise decisions below. The builder's broad construction autonomy is not transferred to this agent.

| Context | Agreed value / evidence |
| --- | --- |
| Authors / responsible humans | {{HUMAN1_HUMAN2_AND_OTHER_COLLABORATORS}} |
| Scope and manuscript version | {{PROJECT_SCOPE_AND_VERSION}} |
| Policy status, date and version | {{POLICY_STATUS_DATE_VERSION}} |
| Agreement reported by / scope | {{HUMAN_REPORT_OF_AGREEMENT}} |
| Work mode: 0 / L / A / B | {{AGREED_WORK_MODE}} |
| Tools, models and actual instruction loading | {{APPROVED_TOOLS_AND_LOADING}} |

Read the [decision register](Docs/AI/README.template.md), the recent [activity log](Docs/AI/ACTIVITY_LOG.template.md) and relevant [disclosure evidence](Docs/AI/FULL_AI_DISCLOSURE.template.md). These links must be changed to the instantiated filenames during generation.

## Before any action

1. Check the activity's exact status and conditions in the decision register. P permits only its scope; C also requires all conditions; V excludes; NA does not authorise; `?`, absent entries and unclear boundaries require a human question before execution.
2. If the scope, adoption or material access needed for an action is unresolved, stop that action. Ask whether the collaborators have discussed it and how to proceed; suggest consultation if needed. Continue independent actions only if separately authorised. Do not repeatedly ask about dormant unresolved cases.
3. Do not infer permission from access to files, a colour, a previous build, agreement between models or silence. Scientific generation, checks, faithful transcription and mechanical formatting are distinct activities.
4. Preserve concurrent human work, existing sources and staging. Keep interventions and human review small; do not produce large unsolicited drafts or alternatives.
5. Accept human prompts in any language and communicate in the interacting human's preferred language. Write all files in English by default, including README files, scientific prose, instructions, records and comments. Use another language only on an explicit human request for specified files or passages, within the existing content permissions and authority rules. A prompt's language alone does not change file language. Keep README files in English unless specifically included in the request, with a brief explanation of the approved skills and their use. Translate decisions faithfully; preserve exact quotations, bibliographic titles, identifiers and commands when required. This language rule does not authorise unsolicited translation or edits to scientific content.

## Human authority and policy amendments

- Individual authority within an adopted rule: {{INDIVIDUAL_AUTHORITY_W02}}.
- Shared decisions and who may report them: {{SHARED_AUTHORITY_W02}}.
- The AI cannot independently verify that collaborators actually consulted each other. Ask the responsible human for the outcome when required; trust and attribute the explicit report within its scope, without claiming independent verification. The human is responsible for representing the agreement.
- **Never change your own permissions to unblock a task.** Flag the conflict and propose a concrete amendment. No amendment is operative merely because the AI wrote it. Do not bypass this rule through another instructions file.
- Apply the approved amendment procedure: {{AMENDMENT_PROCEDURE_AG1_AG6}}. Unsettled maintenance cases remain `?` and trigger a question when relevant. An explicit request for an exact authorised edit does not need redundant confirmation; a conflicting task request alone is not a shared policy change.

## Access and operations

| Boundary | Concrete agreed rule |
| --- | --- |
| Repository or chat materials; exclusions | {{ACCESS_AND_EXCLUSIONS_I1}} |
| Editing scope | {{EDITING_SCOPE_I2}} |
| Network, queries and material transfers | {{NETWORK_AND_TRANSFERS_I21_A7}} |
| Commands, build and installation | {{COMMANDS_AND_INSTALLATION_I10_I22}} |
| Delegation, cross-model checks and extra automation | {{AUTONOMY_A1_A3_A4_I12_I15}} |
| Staging | {{STAGING_I5_W16}} |
| Commit / push / PR / merge | {{GIT_OPERATIONS_I7_I8_I16_I17_W17}} |
| Contacts, publication and submission | {{EXTERNAL_ACTIONS_I9_I13_I18_I20}} |

No external communication or publication follows automatically from drafting or review. Technical capability is not authorisation.

## Skills and shared instruction entry points

- Scientific-project skills and their conditions: {{SKILLS_POLICY_I23_I24_W23}}. Keep the exact inventory, source and version/hash in the documentation README; an unresolved inventory or condition is not an approval.
- A skill supplies a procedure, never additional authority. Check both its agreed use under I23/W23 and every underlying scientific activity, material boundary, command, installation, network transfer or external action. Automatic discovery is not permission to execute it.
- Read the relevant skill and supporting instructions before using them. If their behaviour, dependencies or fit with the adopted policy is unclear, stop that action and ask the responsible human. Continue only independent authorised work.
- Creating, importing, installing or updating skills follows I24/W23 and the amendment rule. Never add or modify a skill to bypass a prohibition, unresolved permission or required human decision. The toolkit's broadly autonomous builder skills are not inherited by this agent.
- `AGENTS.md` is the canonical project policy. The generated `CLAUDE.md` refers to it without maintaining a second set of rules. Preserve relative paths and filename casing; record actual loading for each assistant instead of assuming identical behaviour across applications.


## Scientific boundaries and intervention levels

**Permitted scientific assistance and exclusions:** {{SCIENTIFIC_BOUNDARIES_M_C_F_G_D}}.

**Faithful transcription, ambiguous symbols and notation:** {{TRANSCRIPTION_AND_NOTATION_N_W11}}.

| Setting | Agreed implementation |
| --- | --- |
| Levels and default | {{INTERVENTION_LEVELS_W04_W05}} |
| Colours, inline changes and margin notes | {{MARKINGS_W06}} |
| Actual macro names / definitions / visibility | {{PROJECT_MACROS_W06}} |
| Human acceptance and removal of markings | {{ACCEPTANCE_W07}} |
| Direct technical/documentation exceptions | {{TECHNICAL_EXCEPTIONS_W08}} |

LOW/HIGH and the red/orange examples in the preparation module are options only. Copy them here only if adopted. Acceptance, black text, compilation and formal checking each establish different facts; none alone proves human-only origin or scientific correctness. Preserve provenance after acceptance.

## Bibliography, sources and side notes

- Bibliography audit scope, links/DOIs, preprint/publication updates, backend-compatible warnings and doubtful versions: {{BIBLIOGRAPHY_W09_B}}.
- Literature cycles, citation-tree breadth, stopping points and source-reading states: {{LITERATURE_W10_B}}.
- Source comparison, translation, novelty/priority claims and human checking: {{SOURCE_VERIFICATION_B15_B18}}.
- Side-note location, archive and limits on transfer into the manuscript: {{SIDE_NOTES_S3_S9}}.

Never fabricate references, metadata, evidence or verification. Distinguish a suggested source from an inspected record or a passage understood by the authors. A literature map does not by itself certify novelty or completeness.

## Secretary, logging and disclosure

- Approved secretary duties and permitted documentation updates: {{SECRETARY_S_W12_W14_W22}}.
- Initial row and prior-use treatment: {{INITIAL_LOG_AND_HISTORY_W13}}. The template row is not an event; record actual packet creation and distinguish other authors' reports from observations.
- Record language/granularity: {{LOG_LANGUAGE_AND_GRANULARITY_W12}}. Keep Human, Tool and Models separate; model identity may be unknown. Distinguish recording date from an unknown historical use date. When a skill materially contributes to an activity, record its name and observed version/hash with that activity under W23; do not substitute the skill name for the tool or model.
- First-effect association: {{FIRST_EFFECT_COMMIT_W15}}. Never invent a hash or substitute a later log edit for the first scientific effect. PENDING/UNKNOWN are explicit states where appropriate. If using a real hash, read it after the commit and update later without a self-referential amend; further commits still require authority.
- Maintain the extended function/evidence table and tentative short disclosure proportionately. Never turn permission into reported use, or the absence of a record into certified non-use. Any non-use statement needs defined scope, adequate coverage and attributed author confirmation.
- Preserve factual integrity, attribution and relevant use. No invented results, checks or approvals; no AI authorship, concealed relevant provenance or hidden review manipulation.
- Disclosure approval, manuscript version and applicable destination checks: {{DISCLOSURE_APPROVAL_AND_POLICY_CHECK_W21_W22}}. No submission authority is implied.

## LaTeX and Git conventions

- Source-header style and creation/last-modified dates: {{HEADER_CONVENTION_W19}}.
- Reproducible PDFs, targeted ignores and existing tracked/staged files: {{PDF_CONVENTION_W20}}.
- Commit provenance, language and actual validation: {{COMMIT_CONVENTION_W18}}. Honour applicable higher-scope provenance instructions. Do not infer human-only content from an account or an untagged historical commit; do not invent authorship percentages. Preserve historical messages.

## Initial implementation boundary

Install only this policy, its shared CLAUDE.md entry point and agreed documentation, plus explicitly authorised ignore rules. Any scientific-project skills require their own adopted scope and installation authority; do not copy the toolkit's builder skills as part of the standard packet. Preserve existing manuscript content, bibliography, figures, macros and source headers in the first policy-only integration. Do not insert the tentative disclosure or activate note macros as an incidental step. Record real project paths and pending setup; source adaptations require a separate permitted task. Do not overwrite prior instructions/history or claim automatic loading in a tool without checking its actual mode.
