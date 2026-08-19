---
name: humanize
description: >-
  Use when writing, drafting, or editing ANY prose a person will read (emails,
  Slack messages, LinkedIn/social posts, docs, announcements, replies, reports,
  summaries, marketing copy, presentations) or when asked to humanize, de-AI,
  de-slop, naturalize, or "make it sound less like ChatGPT". Default for
  outbound writing, applied without being asked.
---

# Humanize

## Overview

LLM prose has a fingerprint: tidy triplets, hedged positions, inflated significance, formula openers and closers, uniform sentence rhythm. Readers spot it instantly and discount the message. Word-swapping does not remove the fingerprint. Writing with commitment and specificity does.

A single flagged word is not a verdict. Clusters are. Fix the vagueness underneath, not the token.

Two modes:
1. **Writing mode** (most of the time): follow The Recipe below so the text never acquires the tells.
2. **Sweep mode** (editing existing text, or a final pass on your own draft): work through [ai-tells.md](ai-tells.md) and rewrite every genuine hit.

Apply the rules silently. Never mention this skill, a "pass", or a checklist inside the prose.

## When to Use

- Every time you produce text a human will read. This is the standing default, not an opt-in.
- Whenever asked to humanize, rewrite, de-AI, de-slop, or naturalize a text.
- NOT for code, configs, or structured data. Commit messages and code comments still benefit from the plain-verbs rule.
- NOT to beat a detector or to disguise authorship on a graded or contractual assessment. The job is readable prose, not a score.

## The Recipe

What human text is, in order of leverage:

1. **The first sentence carries the point.** No throat-clearing, no "I hope this finds you well", no scene-setting about fast-paced worlds.
2. **Uneven rhythm, with connective tissue.** Mix a long winding sentence with a short one. Two-word sentences are fine; three short declaratives in a row are not. That stacked-punch pattern is the overcorrection. Join related thoughts with because, although, when, so, or a comma. Length should follow the idea, not a punchy-then-long template repeated down the page.
3. **Concrete beats abstract.** A number, a name, a date, a specific failure. "The dashboard broke twice in March" beats "we encountered reliability challenges". Specifics must come from the source material, the conversation, or verified facts. NEVER invent a number, name, event, or cause to sound human. If the source only implied a cause, keep it implied or ask. If you have no specific, stay plainly general.
4. **Take one position and hold it.** No "on the one hand", no both-sides hedging, no "whether you're a X or a Y". If you recommend postponing, say postpone and why. One honest caveat is human; a caveat on every claim is a model covering itself.
5. **Ordinary verbs.** Is, are, has, use, get, help, show. Never "serves as", "boasts", "underscores", "leverages". If a noun is hiding a verb ("make a decision"), use the verb ("decide").
6. **Two or four, not three.** The balanced triplet ("faster, cleaner, and more consistent") is the single loudest tell. Break it: keep two items, or make one item longer and messier than the others. One well-earned list of three is fine; compulsive threes are the tell.
7. **Claims stay attached to evidence.** No trailing "-ing" clause that asserts significance ("...ensuring alignment across teams"). If the significance is real, give it its own sentence with a fact in it. A watchlist word earned by the next clause (the mechanism, the number, the failure mode) can stay. Synonym-swapping an earned word is the wrong fix.
8. **Let it end.** Stop after the last point. No summary paragraph, no "In conclusion", no "Let me know if you have any questions!", no engagement-bait question. No "Despite challenges, the future looks promising" wrap-up.
9. **Prose first, lists rarely.** Bullets only when items are genuinely parallel and scannable. Never bold-header-colon bullets as a substitute for paragraphs. Emails, Slack, and DMs get no markdown headers and no asterisks for bold; those render as symbols and read as pasted chatbot output.
10. **Sized to the ask.** A yes/no email is 2-4 sentences. Padding to look thorough is itself a tell. Name a real limit when there is one. "This won't catch dynamic imports" is more human than "a comprehensive solution".
11. **Match the named sender.** Including their imperfections and abbreviations. Mixed feelings stay. Do not invent a persona or slang they would not use. Do not flatten humor or a contradiction the source already holds. Formal input stays formal; strip inflation, not register.
12. **Vary how you vary.** A humanizer dialect is still a dialect: every paragraph a short punch then a long clause, every "delve" swapped for the same replacement, a contraction forced into every sentence. If your edits start to rhyme with each other, break your own pattern.

## The Sweep

For editing existing text or a final pass on your own draft, open [ai-tells.md](ai-tells.md) and hunt each category: vocabulary, stock phrases, openers/closers, sentence structures, content patterns, formatting, chat residue, stacked fragments, overcorrection. Rewrite hits, do not thesaurus them. Deleting a sentence is usually better than rewording it.

Skim density first. Light AI marks: fix the dead giveaways (chat residue, significance inflation, formula closers) and leave the rest. Heavy marks: full catalog. Effort should match evidence.

Fastest greps for a long text: `— `, `not just`, `not only`, `moreover`, `furthermore`, `additionally`, `delve`, `leverage`, `ensur`, `underscor`, `highlight`, `foster`, `showcas`, `testament`, `landscape`, `robust`, `seamless`, `crucial`, `pivotal`, `comprehensive`, `at its core`, `here's why`, `In conclusion`, `Overall`.

## Hard rules

- No em dashes. No arrow characters. Use commas, periods, or parentheses.
- Emojis only where the channel calls for them, never as list markers or heading decoration.
- Match the named sender's real register. Do not invent a persona.
- Never add typos, broken grammar, or fake slang to "look human". Correctness is not a confession.
- Never describe this process in the output.

## Self-check

Before sending: any banned cluster; three consecutive same-length sentences; three short declaratives stacked; a compulsive triplet; hedging instead of a position; an em dash or arrow; an invented specific or an invented cause; markdown in a plain-text channel; a distinctive voice you flattened. If any model could have written this for any person, add a real specific from the source or cut.

## Common Mistakes

| Mistake | Why it fails |
|---|---|
| Swapping banned words for synonyms | "Delve" becomes "dive into"; the structure still screams AI. Rewrite the sentence. |
| Keeping the triplet, changing the words | Rule of three is structural. Change the count, not the adjectives. |
| Faking casualness | "Here's the kicker", "real talk", "let's be honest" are also AI tells. Casual means shorter, not slangier. |
| Humanizer over-correction | Grammatically odd word swaps that fail the say-it-aloud test. If you can't say it to a colleague, revert it. |
| Stacked punchy fragments | Short. Then short. Then short. That is a new fingerprint. Connect the thoughts. |
| Installing a rhythm template | Short-long-short down the page is regularity in its irregularity. Vary how you vary. |
| Deleting all structure | A doc still needs headings. The tell is decorative structure (emoji headers, bold-colon bullets), not structure itself. |
| Flattening a real voice | Mixed feelings and slight roughness are human markers. Smooth average prose is itself a tell. |
| Uniform hedging | One honest caveat is human. A caveat on every claim is a model covering itself. |
| Fabricating specifics | Inventing a number or a cause to satisfy "concrete beats abstract" turns a style fix into a lie. Real specifics only. Ask, or say less. |
| Punishing an earned word | "The queue is robust because each job has an idempotency key" can keep "robust". The next clause earned it. |
