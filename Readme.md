# Reusable AI rewriting instructions

The following is an application of the principles above, rather than an additional passage from the book. Use it with this file attached or available to the assistant.

## Full prompt

```text
Rewrite the article below using the principles in economist-writing-style.md,
which summarises Part I of Writing with Style: The Economist Guide.

Audience: intelligent general readers without assumed specialist knowledge.
Output language: English unless I explicitly request another language.
Length: use the space the argument requires; cut repetition and padding rather
than important substance. Follow any length constraint I supply separately.

Preserve meaning and evidence:
- Keep the author's intended purpose, core claims and substantive position.
- Preserve material facts, names, dates, figures, units, source attribution,
  distinctions and necessary qualifications.
- Keep facts, allegations, interpretations, estimates and predictions distinct.
- Do not add reporting, invented scenes, quotations, statistics or causal links.
- Do not infer a missing actor, motive, baseline or mechanism merely because it
  would produce a stronger sentence.
- Preserve quotations verbatim, or convert them into clearly attributed
  paraphrases without quotation marks.
- If a material ambiguity or apparent factual error cannot be resolved from
  the supplied material, flag it briefly rather than silently guessing.

Make the prose clear and concrete:
- Prefer familiar words, concrete nouns and precise verbs.
- Recover actions buried in abstract nouns; make agency clear when known.
- Replace jargon with plain language where the meaning is unchanged. Explain
  indispensable terms and minimise the reader's burden of remembering acronyms.
- Prefer active voice, while retaining useful passives for focus and flow.
- Keep subjects and verbs close; split nested sentences; vary sentence length.
- Retain small words and qualifications that prevent ambiguity.

Improve structure and pace:
- Identify the main point and give each paragraph a clear contribution to it.
- Reorder material where it improves comprehension without altering emphasis
  or meaning unfairly.
- Make transitions and logical relationships explicit.
- Move briskly through simple points; give difficult ideas the explanation
  supported by the source material.
- Use an opening and ending suited to the article. Do not impose a stock
  anecdote, paradox, dramatic hook or punchline.

Keep the voice measured and fresh:
- Be conversational but professional, direct but proportionate to the evidence.
- Remove inflated praise, euphemisms, clichés, journalese and empty hedging.
- Preserve warranted uncertainty and the strongest relevant opposing arguments.
- Use imagery or wit only when accurate, natural and useful.
- Avoid forced synonyms, gratuitous cultural references and mixed metaphors.
- Do not introduce political positions merely to imitate a publication's voice.

Handle numbers carefully:
- Choose the figures that explain the argument and avoid dense numerical prose.
- Preserve definitions, precision and material numerical distinctions.
- Clarify scale and comparisons using only information available in the source.
- Check percentages versus percentage points, stocks versus flows, nominal
  versus real values, time periods and statistical claims.
- Never strengthen an association into a causal claim.

Before output, review structure, evidence, pace, sentences and wording, then
proofread. Return the rewritten article without commentary on routine edits.
If unresolved issues could change its meaning, add a short "Editorial queries"
list after the article. Do not claim to have independently verified facts unless
that verification was actually performed.

Article:
[PASTE THE ARTICLE HERE]
```

## Short invocation

> Rewrite the following article in an Economist-style voice using the attached `economist-writing-style.md`. Write in English. Preserve the facts, intended argument and necessary uncertainty; improve structure, clarity, precision and economy. Output the article, followed only by any essential unresolved editorial queries.
