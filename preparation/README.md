# Preparing the agreement

**Starting point:** Human1 and Human2 have yet to discuss the boundaries for their scientific collaboration. The worksheet contains no previously agreed project permissions.

The [construction agent](../AI/AGENTS.md) has broad autonomy to help build the agreement using the capabilities allowed by the user's environment and current instructions. It may research, organise, draft, revise and prepare complete provisional documents without waiting for every scientific-policy question to be answered. Those unanswered questions constrain the future scientific agent, not the builder's authorised preparation work.

Accept human prompts in any language and discuss them in the human's preferred language. Write files in English by default, translating decisions faithfully; another language requires an explicit request for the affected files or passages. README files stay English unless specifically included in that request.

## A flexible workflow

This is a useful route through the work, not a mandatory approval gate before every preparation step. The builder can combine, revisit or work ahead on stages while keeping proposals distinct from adopted decisions.

| Stage | Human decisions and AI preparation | Result |
| --- | --- | --- |
| 1. Preparation | Copy the worksheet into a private workspace; identify the project, participants and AI assistance used in preparation | A project worksheet without invented decisions |
| 2. Discussion | Establish goals, work mode, scientific boundaries and materials; consider relevant activities | Individual preferences separated from shared choices |
| 3. Clarification | Review the answers, identify gaps or contradictions and ask focused questions | Decisions with conditions; remaining `?` entries explicit |
| 4. Confirmation | Establish who may authorise an activity or change a rule; record the reported agreement and its scope | Adoption status attributed to the responsible human |
| 5. Drafting and generation | Develop provisional instructions as useful; finalise the project packet from adopted answers | A precise project agent and documentation in the proposed or adopted W22 layout, with an optional Claude entry point, or a context for chat-only work |
| 6. Review and integration | Check concrete scenarios; follow INTEGRATION.md once repository access and adoption are agreed | Initial integration limited to policy and documentation |
| 7. Actual project use | Record activities, retained outputs and checks; ask when an unresolved case becomes relevant | An evidence-based disclosure that can be updated |

Use [DECISION_WORKSHEET.template.md](DECISION_WORKSHEET.template.md). A private working copy can live at `preparation/sessions/<project>/DECISIONS.md` (ignored by Git). Generated packets can live at `AI/generated/<project>/`. Keep collaboration-specific answers out of the reusable master template.

## Running the discussion

1. Record context and preferences, then choose 0 / L / A / B or leave the choice unresolved.
2. Start with the activities that matter to the collaboration. Secretary duties, language, notes, bibliography and scientific boundaries are useful starting points. The full catalogue remains available; its 193 activities are not 193 mandatory questions for one call.
3. Use P / C / V / ? / NA. For C, specify at least the activity boundary, materials, human checks and responsible person. Missing conditions do not confer permission on the scientific agent.
4. Decide groups of IDs when useful, with explicit exceptions. Do not infer one permission from another: translation does not authorise new proofs; file access does not authorise push.
5. Complete the W and AG fields relevant to the intended work. Proposed colours, logging formats and Git conventions are options rather than adopted defaults. For scientific-project skills, discuss I23/I24/W23 separately from permission for the underlying tasks and dependencies.
6. Summarise agreements, limits, deferred questions and adoption status. There is no need to reopen every `?` immediately.

The builder cannot independently establish that collaborators actually consulted each other. When shared agreement is needed, ask the responsible human to report the outcome and attribute it as their statement. Keep review manageable through focused questions and clear proposals; let the builder do the preparation work rather than asking humans to approve every routine step.

To start, invoke `$prepare-ai-policy` in Codex or `/prepare-ai-policy` in Claude Code, then describe the collaborators, project and current discussion. Ask it to maintain a private worksheet copy and help with the next relevant decisions. A normal-language request can also select the skill; if discovery is unavailable, ask the assistant to read the procedure linked from [SKILLS.md](../SKILLS.md).

Use `build-scientific-agent` when you want a provisional or adopted packet from those records. These builder procedures stay within the current task and environment and are not installed into the scientific project by default; any project skills need a tailored scope and the collaborators' decision.

## Reusable clarification prompt

> Read this working copy and the toolkit instructions. Work autonomously within the capabilities and permissions of my environment to help us build a precise agreement. Distinguish personal preferences, reported agreements, proposals, missing conditions and contradictions. Accept my prompts in any language and discuss with me in my preferred language. Keep files in English unless I explicitly request another language for specified files or passages. Ask one to three focused questions at a time when human decisions are needed. I may report an agreement already reached or leave an item `?`. You may continue independent research, drafting and preparation, including a complete provisional agent; do not invent adoption or turn unresolved choices into permissions for the scientific agent.

## From provisional draft to adopted project agent

A complete draft may be prepared before all choices are settled. Label proposals and unresolved fields clearly. Before adopting or installing the scientific agent, establish the following for the actions it is intended to perform:

- Participants, roles and the scope of the collaboration are identified.
- AI assistance already used in preparation is recorded separately from manuscript work, even if the project selects mode 0 or L.
- Work mode and accessible materials are agreed; mode B also needs a defined repository scope and the operations needed for initial documentation.
- Activities being activated have an explicit status and complete conditions. Other activities remain `?` and unavailable to the scientific agent until resolved.
- The authority rule and reported adoption are explicit. Adoption of instructions and approval of a disclosure for submission are separate events.

If an adoption requirement is missing, keep the project agent provisional. This does not prevent the builder from improving the draft, exploring options or carrying out other preparation allowed by its user's environment.

## Mapping answers to instructions

| Worksheet material | Destination |
| --- | --- |
| Context, mode, tools and materials | Scope and access in project AGENTS.md; setup in README |
| Complete activity catalogue, conditions and exceptions | Decision register in README; operating rules in project AGENTS.md |
| W01–W23 and AG1–AG6 | Intervention levels, secretary duties, Git, skills and policy maintenance |
| Observed uses and retrospective human reports | ACTIVITY_LOG and FULL_AI_DISCLOSURE with evidence types separated |
| Reconciled evidence and final approval | Short proposed TENTATIVE_AI_DISCLOSURE.tex |
| Adopted procedure and boundaries | A concise WORKFLOW for the authors |

Publisher references in the worksheet are starting points to check for the relevant role and destination. Do not transfer a journal's rule to another destination, or a reviewer rule to authors' work, without establishing its applicability.
