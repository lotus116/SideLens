---
name: sidelens
description: Provide an independent second perspective when repeated work yields no new evidence, recurring user dissatisfaction remains unresolved, or a consequential plan rests on a questionable premise. Also use when explicitly asked to review the direction or shared assumptions. Ordinary iteration that produces new evidence does not by itself call for review.
---

# SideLens · 旁见

Improve the next decision in a human–AI collaboration. Review both parties' assumptions; do not reward disagreement or manufacture a deeper problem. A supported decision to continue is a useful result.

## Decide whether to review

Honor explicit requests. For proactive use, look for a concrete discrepancy before interrupting: repeated investment without learning, recurring dissatisfaction, a mismatch between the proposed success measure and the user's desired outcome, or a consequential choice resting on an unexamined premise. Progress can look smooth and still warrant a brief challenge.

At a natural decision boundary, ask what was learned and why it supports the next commitment. This is a lightweight check, not a requirement to delegate every stage. Avoid turn-count triggers. Do not repeat an already-addressed concern without new evidence, changed stakes, or a user request.

## Prepare evidence

Recover the current desired outcome, explicit constraints, provisional methods, and subsequent user-authorized changes from available sources. Keep source references or short exact excerpts. Treat inferred motives as hypotheses, never confirmed requirements. Do not require an interview or a new requirements document when the existing request suffices.

Give the reviewer:
- The pending decision and scope of this review.
- Relevant user statements, including later changes.
- Observed results and actions, with locations of authorized original materials.
- Known missing evidence and earlier review dispositions, if any.
- The main agent's interpretation, separately labeled as interpretation.

Avoid a leading assignment such as “explain why our RL approach needs more tuning.” Include evidence that could undermine the main agent's framing. Do not claim a complete history when only a summary is available.

## Obtain an independent assessment

Use one fresh-context subagent when delegation is available and permitted. Have it read [reviewer.md](references/reviewer.md) and the evidence packet. Prefer not to inherit the full main-agent conversation; retain access to relevant original materials. Tell the user if only same-agent reflection is possible. A new context reduces anchoring but does not guarantee independent reasoning.

The reviewer investigates and advises; it does not change business files, user goals, or configuration, and does not delegate recursively. These are behavior instructions, not a separate permission sandbox. Bound investigation to the pending decision: pursue a missing source only if it could materially change the assessment, and return uncertainty when further investigation is not worthwhile.

## Return to the main task

For a material finding, convey the strongest concern in the user's language, usually in a short paragraph: what may be wrong, the evidence, why it changes the next step, and the smallest useful check or question. Usually one finding suffices. Do not fill mandatory “deep insight” slots.

Allow a speculative perspective if it has a concrete basis and meaningful implications. Label it tentative, offer an alternative explanation, and make it easy for the user to reject. Do not silently rewrite the goal from it.

The main agent states whether it accepts, defers, or rejects a material recommendation and why; preserve the concern's original meaning even when rejecting it. Continue authorized work. A reversible check within existing scope can proceed without a new permission request. A change to explicit goals or constraints needs the user's decision; silence supplies no additional authorization. Continue unaffected work while that decision is pending.

For proactive checks with no material finding, continue without a user-facing review ceremony. For an explicit request, briefly say no intervention is supported and name the key reason or evidence limitation.

Keep a compact review disposition in the task's existing notes or conversation: concern, evidence, action, and what would reopen it. Do not introduce a database or silently persist private conversation excerpts outside the task. If a suggested check is performed, distinguish the observed result from the reviewer's original prediction. Adoption alone is not evidence of usefulness.
