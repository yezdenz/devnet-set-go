# Documentation, prompt logs, and feedback

## Natural, accurate writing

Write as a clear, practical lab record: what was done, what happened, and why it matters. Use ordinary words, concrete observations, and enough structure to follow the work. Avoid stock AI phrases, repetitive introductions, exaggerated polish, and unnecessary detail.

Human-sounding means readable and specific. Do not add deliberate mistakes, invent a personal voice or experience, disguise AI participation, or claim that a human performed work the agent completed. Follow the assignment's disclosure and AI-use rules. Apply Formatting.MD's one-to-two-sentence limit to checkpoint and question answers.

For documentation inside a Word worksheet, follow [Word.MD](Word.MD) and its existing structure instead of generating a new report layout. Add required records and proof sections without removing any original part. Reflection and essay answers use black font only within their answer text; preserve the worksheet's other font colors.

## When a prompt log is required

Read the exact requirement before starting and maintain the record as the task proceeds. Use actual prompts and actual outcomes; do not manufacture a polished conversation afterward. Record only relevant visible exchanges, not hidden system instructions, private reasoning, credentials, or unrelated chats.

### Keep administrative chat out of the technical log

Do not use a broad delegation message such as "do everything for me", an access approval, a greeting, or a request to edit this workflow as a technical prompt entry. Keep those messages in the private coordination record. The submitted technical log should address the actual debugging, request design, data parsing, source verification, or other technical assistance involved.

When an exact prompt is required, quote an actual relevant technical prompt. Do not transform a general delegation request into an invented user conversation. If only a broad request exists and the activity permits summaries, write a clearly labeled task-focused summary of the assistance actually provided. For example: "Summary of assistance: reviewed the collection request and identified which local responses needed checking." This describes the work without pretending that the user typed a different prompt.

Where the task requires a full transcript, preserve the available raw record privately and identify a selected technical excerpt as an excerpt. Do not call a filtered or incomplete log a complete transcript. Missing required exact exchanges remain an explicit gap rather than being replaced with fictional quotes.

### Use a natural technical record

Follow the worksheet's existing log labels and layout. Use short, ordinary sentences about the specific issue, the AI's suggestion, the decision, and the check. State a concrete reason for Accept, Modify, or Reject only when that decision actually occurred; do not invent a student decision or a rejected suggestion merely to fill a row.

Separate exact quotes from summaries. Summaries may be rewritten for clarity without adding events or changing who did the work. Keep casual original wording in exact prompt fields. Avoid repeated scripted phrases, deliberately inserted mistakes, unnecessary polish, or a false account of independent work.

Use the required log format. If no format is specified, use:

| Step | Technical prompt or labeled summary | AI suggestion | Decision and reason | Validation |
| --- | --- | --- | --- | --- |
| Task step | Actual quote if required, otherwise an accurate summary of assistance | What the AI suggested | Actual decision and who made it, or not recorded | Actual check and evidence location, or pending |

Keep verbatim entries verbatim even if they are informal. Label summaries and reconstructed recollections explicitly; never present them as exact historical prompts. Do not label agent verification as user verification.

If logging began late or a required exchange is unavailable, disclose the gap. Ask for the missing record when needed. Do not claim a complete log when it is partial. Use a truthful AI-use statement where the assignment requires one.

Preserve short follow-up prompts exactly when the activity requests exact prompts, but retain the preceding prompt and response context needed to understand them. Do not replace an actual informal prompt with a newly polished version. If a privacy rule requires a redaction, label it and retain an accurate private original where appropriate.

### Fictional examples are for testing only

When the user requests an invented interaction for testing, create a natural example labeled **Fictional test scenario**. Keep that label attached when copying or exporting the example. Simulated prompts, decisions, and outcomes are not historical records, actual student work, or execution evidence. Do not insert an invented scenario into a real submission as an actual interaction log.

The following example illustrates a local API exercise. It contains no real interaction history, credentials, screenshots, or executed results.

#### Fictional test scenario: local API request review

**Entry 1: list the records**

- **Invented prompt:** "I need to list the books in the local simulator. Is GET /api/v1/books the right request, and what should I check after sending it?"
- **Invented AI suggestion:** Use the collection GET, then check the status and returned book list against the local API documentation.
- **Invented decision:** Accept the request design, then check it in both required clients.
- **Simulated check:** This example assumes both clients returned the documented result; no requests were actually sent for this example.

**Entry 2: check a suggestion**

- **Invented prompt:** "The AI suggested 204 for a successful delete, but my activity expects 200. Which one should I put in the plan?"
- **Invented AI suggestion:** Keep the activity's expected value in the plan and record the actual local response separately; investigate any difference.
- **Invented decision:** Modify the generic suggestion because the task has a specific expected status.
- **Simulated check:** The example imagines a comparison with the supplied activity and an observed 200 response; it is not proof of a local run.

**Entry 3: troubleshoot authentication**

- **Invented prompt:** "The request without a key failed. How do I check the cause and retry it without putting the key in my log?"
- **Invented AI suggestion:** Record the actual error, compare it with the local documentation, restore the valid key only in the client, and check the retry.
- **Invented decision:** Accept the troubleshooting steps and keep secret values out of the evidence.
- **Simulated check:** The example assumes a failed request followed by a successful retry, with separate redacted evidence for each; no such evidence is created or claimed here.

### Keep permission questions separate

Follow [Authorization.MD](Authorization.MD) for task-wide consent. Do not interrupt the task with permission questions for each log entry, routine edit, or already authorized validation step. Collect genuinely missing input in one request where possible and keep administrative consent out of the technical log.

## Independent validation and local execution

Use [Validation.MD](Validation.MD) to perform required checks and [Evidence.MD](Evidence.MD) to record and reconcile their proof. Link log entries to that private register rather than keeping a competing completion checklist. Apply [Submission.MD](Submission.MD) before the final handoff.

In the narrative, separate expected behavior, observed behavior, and the conclusion supported by the evidence. Identify supplied historical evidence as supplied evidence; do not describe it as a fresh run. Attribute checks to the person or agent who actually performed them. A technical explanation or AI recommendation is not execution evidence.

Keep prompt records and validation records aligned. A decision reason must explain its own suggestion, and its linked evidence must support that decision. If the report, screenshots, and log disagree, resolve the mismatch through Evidence.MD before describing the requirement as verified.

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
