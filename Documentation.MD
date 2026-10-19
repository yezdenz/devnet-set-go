# Documentation, prompt logs, and feedback

## Natural, accurate writing

Write as a clear, practical lab record: what was done, what happened, and why it matters. Use ordinary words, concrete observations, and enough structure to follow the work. Avoid stock AI phrases, repetitive introductions, exaggerated polish, and unnecessary detail.

Human-sounding means readable and specific. Do not add deliberate mistakes, invent a personal voice or experience, disguise AI participation, or claim that a human performed work the agent completed. Follow the assignment's disclosure and AI-use rules. Apply Formatting.MD's one-to-two-sentence limit to checkpoint and question answers.

## When a prompt log is required

Read the exact requirement before starting and maintain the record as the task proceeds. Use actual prompts and actual outcomes; do not manufacture a polished conversation afterward. Record only relevant visible exchanges, not hidden system instructions, private reasoning, credentials, or unrelated chats.

Use the required log format. If no format is specified, use:

| Step | Actual prompt or request | Result observed | User revision or verification |
| --- | --- | --- | --- |
| Task step | Verbatim prompt when required; otherwise a clearly labeled summary | What the agent produced or did | What was actually checked, changed, or left pending |

Keep verbatim entries verbatim even if they are informal. Label summaries and reconstructed recollections explicitly; never present them as exact historical prompts. Do not label agent verification as user verification.

If logging began late or a required exchange is unavailable, disclose the gap. Ask for the missing record when needed. Do not claim a complete log when it is partial. Use a truthful AI-use statement where the assignment requires one.

Preserve short follow-up prompts exactly when the activity requests exact prompts, but retain the preceding prompt and response context needed to understand them. Do not replace an actual informal prompt with a newly polished version. If a privacy rule requires a redaction, label it and retain an accurate private original where appropriate.

## Independent validation and local execution

Record separate evidence for each validation layer the task requires:

| Layer | What it can establish | What it does not establish on its own |
| --- | --- | --- |
| Source or documentation review | A reasoned expected result or supported design | That the program or request actually ran |
| Offline validator or unit tests | The specific checks actually exercised by that run | Unchecked behavior, another application, or live API execution |
| Manual program or local application run | The observed result in the recorded environment | A separate client's behavior or every automated test |
| Evidence review | That the packaged proof is readable, relevant, and consistent | Independent authenticity beyond the available provenance |

Save the command or operation, relevant working directory and environment, tested file version or revision where available, actual output or response, and the evidence location. Identify supplied historical evidence as supplied evidence; a reviewer must not describe it as a fresh run. Do not run an example's code just to improve its historical record.

For API work, record the client, method, target path, non-secret parameters, actual status, and a brief redacted response summary for every required scenario. Keep expected and observed statuses separate. If the local result differs from the manual or validator, preserve the discrepancy and investigate the actual version and request; do not change the observation to match the predicted answer. A controlled failure also needs the separately observed successful repair when the task requires it.

If two clients are required, one client's screenshots cannot satisfy both. If both automated tests and a manual run are required, save distinguishable evidence of each, including the test count and final test result. Label any unavailable layer pending.

Before final delivery, reconcile all pending/completed labels with the actual artifacts. If the log says execution is pending but screenshots show responses, determine what was captured, in which client, and for which version before updating the record. Ask about missing provenance instead of inventing it. Check required Git branches, milestones, and merge/conflict records against available history; label the revision or milestone represented by exported evidence without manufacturing past commits.

## Review past submissions and scores

This workflow is refined by editing its instructions; reviewing examples does not train model weights. Keep the user's past files, identifying information, and teacher comments out of this public repository unless the user explicitly authorizes publication of specific material.

1. Read each supplied submission, assignment, rubric, score breakdown, and teacher comment. Identify which materials are missing. Preserve each original file under Formatting.MD.
2. Map explicit deductions to the affected requirement and the submitted evidence. A low total score alone does not establish a cause.
3. Distinguish confirmed feedback from an inference. Label inferred causes as hypotheses and request supporting rubric details where necessary. Do not attribute a preference to the professor without evidence.
4. Propose a specific correction and the guide it belongs in. Prefer reusable checks over copying a previous student's answers or personal information. Keep task-specific requirements scoped to that task.
5. Review the proposed rule against higher-scoring examples where available. If evidence conflicts, preserve the distinction and ask for clarification instead of creating a universal rule.
6. Apply the user's authorized changes, then check a new task against the revised checklist. Report what changed and what still needs evidence; do not promise improved grades.

A full score can coexist with visible omissions or copy-and-paste mistakes. Preserve useful patterns without promoting every detail into a rule. For a high score with no deduction comment, do not claim to know the cause of a missing point. For an explicit execution-evidence comment, strengthen the execution gate while checking the supplied files for contradictory or later-added evidence; the comment alone does not establish which file version was graded.

Use a private review record:

| Evidence source and location | Score or explicit feedback | Confirmed finding or hypothesis | Proposed guide change | Validation or pending question |
| --- | --- | --- | --- | --- |
| Supplied task, rubric, or comment | Quote or summarize accurately | Separate fact from inference | Specific rule and target file | What supports it or remains unknown |

Only generalized, anonymized lessons belong in an authorized public workflow update. Remove personal details from that proposal, not from the original evidence file. Private examples have informed the current checks; no individual submission, exact score, or private teacher comment is published here.
