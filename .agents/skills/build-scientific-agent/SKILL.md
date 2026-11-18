---
name: build-scientific-agent
description: "Generate or revise a scientific project's controlled agent and AI-use documents from a policy worksheet and reported human decisions."
---

# Build the controlled scientific agent

Read the [toolkit instructions](../../../AGENTS.md), [builder guide](../../../AI/AGENTS.md) and [project-packet guide](../../../AI/README.md). Use the working worksheet and subsequent human clarifications as evidence; use the [scientific-agent template](../../../AI/AGENTS.template.md) as the starting structure.

## Translate decisions into operational rules

- Reconcile the actual answers by exact activity ID and status, retaining scope, conditions, human responsibilities, authority and unresolved cases. Preserve the complete decision register rather than listing only allowed activities.
- A provisional packet may contain explicit unknowns or labelled proposals. Do not convert them into permissions, invented defaults or claims of shared adoption.
- Keep the builder's broad preparation autonomy separate from the generated agent's scientific permissions. The generated agent asks when a relevant `?` arises and cannot change its own permissions to unblock a task.
- Make tool/skill access, underlying scientific activities and external operations distinct. An approved skill cannot authorise a prohibited or unresolved operation; record the agreed skill inventory and maintenance rules.
- Generate one canonical project `AGENTS.md`, incorporating the designated decision register by reference with its location, version and adoption status. Any `WORKFLOW` is a derived human-readable summary with no independent permissions. A `CLAUDE.md` bridge loads the same policy rather than duplicating or relaxing it; include it in an adopted packet only if adopted, or label it as a proposal in a draft.
- Instantiate the documentation in a separate project location, normally `AI/generated/<project>/`. Follow the adopted W22 file selection and layout for adopted output; drafts may contain clearly labelled proposed files, layouts and alternatives. Retain required decision and evidence information in the designated records. Update filenames and links together and omit references to unselected outputs from adopted packets. Keep the reusable templates blank.
- Populate the initial activity row only for actual packet creation. Distinguish observed use from human reports; keep unknown dates, models and first-effect hashes explicit. In the generated AGENTS.md and any derived WORKFLOW, specify that if W15 uses hashes, new effects remain PENDING and earlier records are completed with their verified original SHA during the next otherwise-needed authorised AI-prepared commit, within its scope. Do not require a dedicated metadata commit or immediate post-commit edits to chase the new SHA. Derive disclosure text from evidence, not from the permission list.

## Check the packet

Check agreement-to-rule consistency, unresolved conditions, relative links, instruction bridges and actual setup facts. Generate the rule that scientific-agent execution or installation requires AGENTS.md, its designated register and any WORKFLOW to align with the same adopted version: a divergence stops the affected action until reconciliation under the adopted human authority and amendment procedure, without silently selecting the broader rule or changing permissions. Separately authorised independent work may continue. The builder may correct draft inconsistencies and propose amendments without claiming adoption. Keep changes proportionate to human review. Report the packet's status and remaining adoption-critical decisions without claiming manuscript integration or disclosure approval.

Use the [integration guide](../../../INTEGRATION.md) only when installation into the separate manuscript project is requested within its actual authority.
