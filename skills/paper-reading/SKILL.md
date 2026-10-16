---
name: paper-reading
description: Read a scientific paper collaboratively through its figure-by-figure argument, evaluate questions and comments, assess the contribution and evidence, and maintain evolving learning notes and transferable writing lessons. Use for close reading and paper-quality discussions; use paper-writing for composing a manuscript.
---

# Collaborative paper reading

The outcome is understanding how the paper earns its claims and what the reader can learn for their own research and writing. Follow one paper per chat unless the user requests comparison.

## Start with the paper's logic

1. Inspect the source, main figures, captions, relevant text, and any supplement needed for the current claim. For PDFs, use the available PDF-reading workflow and visually inspect relevant figures; extracted text can corrupt axes, equations, and panel labels.
2. Read existing project learning records if present. Default to `reading-notes/learning-profile.md` and `reading-notes/<doi-or-short-id>.md`, relative to the project root. Use a stable DOI-derived identifier and record the source location and access limits.
3. For a new paper, first explain the scientific problem, the competing explanations or unmet need, and the central contribution in plain language. Define only the concepts needed to follow this argument.
4. Give an overview of all main figures before a technical deep dive. For each figure, distinguish **what it shows**, **what inference it supports**, **why the argument needs it**, and **what question leads to the next figure**. A compact table is useful; expand panels when their roles differ.
5. Summarize the dependency between the figures. Publication order is an explanatory choice, not necessarily experimental chronology or a proven causal chain. If only part of the source is available, scope the map to inspected material and identify the missing parts.

Do not substitute an abstract summary, a list of techniques, or an isolated technical explanation for the initial figure-based argument. On later turns, refer to the existing map and answer the current question directly. If the user remains confused, simplify and rebuild the relevant connection before adding detail.

## Explain a figure at the right level

- Orient the reader to the sample, intervention, controls, axes, normalization, and actual measured quantity before interpreting a trend.
- State the observed result separately from the authors' explanation and from our own interpretation. Trace important claims to verified figure panels, pages, equations, or tables.
- Explain why this observable is informative and what a competing explanation would predict. Identify the assumption that connects measurement to mechanism.
- Use the removal test: if this figure were absent, which claim would lose support or which alternative would remain unresolved? A context figure can be useful without independently proving a mechanism.
- For complementary methods, compare the observable, scale, sensitivity, and ambiguity. Explain the missing information supplied by the second method. Do not equate a proxy with the property of interest, or a correlation length with a physical object size without justification.
- Treat normalized trends, absolute yields, model-dependent parameters, and direct observations as distinct. Report useful numbers with units and uncertainty when available.
- For causal claims, check whether the comparison changes multiple factors at once. Do not infer a uniquely established microscopic mechanism from a confounded comparison or a null result.

## Discuss questions and comments

Answer the user at their current level of understanding. Evaluate a comment as supported, partly supported, unsupported, contradicted, or still open, with a concrete reason. Correct it respectfully and offer a more precise formulation when useful.

Separate author claims, observed data, established background, and our hypotheses. Verify external facts and prior-work comparisons using primary sources when needed. Do not infer novelty, editorial decisions, or universal validity from venue prestige.

## Evaluate quality and extract writing lessons

Use [the evaluation framework](references/evaluation-framework.md) for a whole-paper assessment, a claim about top-tier merit, or a research/writing lesson. Start with the most consequential scientific advance and the evidence that discriminates it from alternatives. Scale the assessment to the user's question; do not append a complete rubric to every reply.

Assess the contribution in the field and at the time of publication. Separate the authors' novelty framing from independently verified prior art. Identify the strongest supported contribution, the weakest inferential link, and the limits of generalization. A journal's decision is not known unless direct evidence of that decision is available.

Translate a useful result into an actionable writing or design lesson: what evidence to plan, why a figure belongs, how to order claims, or where wording must be narrower. Explain the conditions under which the lesson applies. Never prescribe the source paper's technique list or figure order as a universal template.

## Maintain the learning record and both skills

The user authorizes local notes and incremental method updates during substantive reading discussions. Use [the reading-note template](references/reading-note-template.md) as a starting structure; preserve existing useful notes and use the actual project date.

- Update the paper note after a substantive exchange: the question/comment in the user's own terms, our assessment, source anchors, explanation attempted, remaining uncertainty, and a transferable lesson when one is justified.
- Track confusion using `open`, `explained-awaiting-confirmation`, `revisit`, and `user-confirmed-understanding`. Do not mark something understood because an answer was sent, time passed, or the user moved on. A user-confirmed status needs explicit confirmation or a demonstrated correct restatement; record which.
- Update the cross-paper learning profile only with explicit preferences or recurring, evidence-backed needs. Label a tentative inference as tentative. Do not invent knowledge gaps or a fixed learner identity from one question.
- Distinguish scientific uncertainty, access limitations, and reader confusion. They need different next steps.
- On a process correction or a demonstrated reusable lesson, make a narrow improvement to this skill and, when relevant, `paper-writing`. For companion updates, locate its actual source; do not guess paths or overwrite an unrelated skill. Record the reason in the paper note. Do not modify the companion if it is absent.
- Keep paper-specific results and personal learning history out of reusable skill instructions. Skills hold methods; notes hold the paper and the conversation. Improve both methods when warranted rather than forcing an edit after every turn.
- Follow project instructions about canonical sources and installation. If there is a source checkout plus installed copies, edit the canonical sources and synchronize them using that project's documented process. Validate materially changed skills with the available skill validator.

## Done for the current exchange

The user can locate the current question in the paper's argument, distinguish the observation from the inference, and see why the relevant figure or method is needed. Notes reflect the actual state of the discussion, including unresolved confusion. The response remains useful on its own; file updates do not replace the explanation in chat.
