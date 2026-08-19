# Catalog of AI Writing Tells

Compiled from Wikipedia's "Signs of AI writing" and "Signs of AI-generated comments" project pages, the jph00 LLM-writing gist, and 2025-2026 detection guides. Use in Sweep mode: find each pattern, rewrite the sentence around it (never just swap the word).

No single hit proves anything. The fingerprint is cumulative: three or four categories co-occurring is what readers notice. Watchlists drift as models change; treat them as detectors, not a forever ban list. Context still wins. "Underscore" as a literal underline is fine. "Robust" next to a named mechanism is fine.

## 1. Vocabulary blacklist

Rewrite the sentence when these appear as decoration. Plain alternatives in parentheses.

**Verbs:** delve (look at), dive into, leverage (use), foster (build), harness, unlock, unleash, unveil, empower, elevate, streamline (simplify), optimise, bolster, garner, showcase (show), underscore (show, stress), highlight (as a verb of significance), illuminate, facilitate (help), navigate (a non-physical thing), embark, ensure (make sure, or delete), utilize (use), boasts (has), encompass, cultivate, demystify, resonate, align with, captivate, revolutionize, orchestrate (organize), reimagine (redesign), exemplify (show)

**Adjectives:** crucial, pivotal, vital, key (as pure emphasis), seamless, robust (outside a named engineering property), cutting-edge, groundbreaking, transformative, revolutionary, game-changing, dynamic, multifaceted, comprehensive, meticulous, intricate, vibrant, rich (heritage/history/tapestry), profound, enduring, invaluable, unparalleled, holistic, scalable (outside actual engineering), future-ready, ever-evolving, fast-paced, significant (as filler), notable, renowned, stunning, breathtaking, must-see/must-visit, world-class, state-of-the-art, nuanced (as filler)

**Nouns and metaphors:** landscape (non-literal), realm, tapestry, journey (non-literal), beacon, symphony, testament, game-changer, paradigm shift, synergy, ecosystem (non-literal), roadmap (non-literal), treasure trove, myriad, plethora, insights (unearned), stakeholders (when "people" works), interplay, intricacies, cornerstone

**Transitions and throat-clearers:** moreover, furthermore, additionally, consequently, thus, hence, notably, importantly, subsequently, "on the other hand" (repeated), "at the same time" (repeated), "at its core", "in essence", "fundamentally" (as an opener), "here's why", "here's why it matters". Human alternatives: also, plus, but, so, and often nothing at all; good sentences connect by content.

## 2. Stock phrases

- "It's important to note/remember/consider that..."
- "It's worth noting/mentioning that..."
- "In today's fast-paced / ever-evolving / digital world..."
- "In the modern landscape of..."
- "plays a crucial/vital/significant/key role in..."
- "stands as / serves as / is a testament to..."
- "marks/represents a significant shift/milestone/turning point"
- "key turning point", "watershed moment", "indelible mark", "deeply rooted"
- "continues to captivate", "leaves a lasting impact/legacy", "enduring legacy"
- "solidifies its position/reputation as..."
- "commitment to excellence/innovation"
- "nestled in", "in the heart of", "natural beauty", "diverse array of"
- "valuable insights", "actionable insights"
- "a wide range of", "a variety of" (as filler before a list)
- "when it comes to..."
- "at the end of the day..."
- "the fact of the matter is..."
- "needless to say..."
- "generally speaking", "while it is true that", "it goes without saying"
- "aims to" (repeated hedge)
- "no discussion would be complete without..."
- "whether you're a X or a Y..." (fake-audience construction)
- "while X, Y is also important" (hedged symmetry; keep only for a real branch with different next steps)
- "from X to Y" (fake-range construction: "from startups to enterprises")
- "look no further"
- "let's dive in", "let's get started", "without further ado"
- "we're excited/thrilled/delighted to announce"
- "here's the kicker", "that's only half the story", "real talk", "let's be honest" (fake-casual hooks)

## 3. Openers and closers

**Openers to kill:**
- "I hope this email finds you well."
- "I trust this message finds you..."
- "Thank you for reaching out."
- "Thanks for flagging this." (as a reflex; fine when the flag genuinely helped)
- "Great question!" and any other compliment-the-prompt opener
- "As a [role], I..." (real people just say the thing)
- "In this article/post, we will explore..."
- "Have you ever wondered..."
- "Picture this:" / "Imagine a world where..."

**Closers to kill:**
- "In conclusion", "In summary", "Overall", "To sum up", "Ultimately" (paragraph-starting)
- Restating the whole text in the final paragraph (school-essay recap)
- "Let me know if you have any questions!"
- "I hope this helps!"
- "Don't hesitate to reach out."
- "Happy to jump on a call" / "happy to discuss further" (as a reflex closer; keep it only if a call is genuinely the next step)
- "Moving forward, I will..." / "I am committed to..."
- "Despite these challenges, X continues to thrive" / "Looking ahead, X will play an increasingly pivotal role"
- Engagement bait: "Curious how others have handled this", "What's your experience?", "Thoughts?", "Agree?"
- Aphorism landings: "X is never just about Y, it's about Z", "Migrations aren't infrastructure projects, they're trust projects"

## 4. Sentence structures

- **Rule of three.** Balanced triplets of adjectives, phrases, or clauses ("faster turnaround, fewer errors, and more consistency"). The single most reliable tell. Fix by cutting to two, expanding to a messy four, or making one item much longer than the others. One earned three-part list is not a crime; compulsive threes are.
- **Negative parallelism.** "Not just X, but Y", "Not only... but also...", "It's not about X, it's about Y", "No X. No Y. Just Z." Reads as manufactured profundity. State the positive claim directly.
- **"X rather than Y"** used repeatedly to sound judicious.
- **Trailing present-participle clauses.** "...highlighting the importance of...", "...ensuring alignment...", "...reflecting a broader trend...", "...underscoring its commitment to...". These bolt unearned analysis onto facts. Delete, or make the claim its own sentence with evidence.
- **Copula avoidance.** "serves as", "stands as", "functions as", "operates as", "represents a", "features", "offers", "maintains" where "is/are/has" belongs.
- **Nominalizations.** "make a decision", "provide assistance", "conduct an analysis". Use the verb: decide, help, analyze.
- **Uniform sentence length.** Every sentence 15-20 words, same subject-verb-object shape. Low burstiness. Break it deliberately.
- **Parataxis / stacked fragments.** Short sentence. Then another. Then another. After a humanizer pass this is the new fingerprint. Connect related thoughts (because, although, when) instead of chopping everything into punches.
- **Identical paragraph template.** Topic sentence, explanation, example, transition. Start some paragraphs with the example. Let some be one sentence. Skip the transition.
- **Perfect paragraph symmetry.** Every paragraph 3-4 sentences, every section the same length, intro-body-conclusion for a Slack message.
- **Elegant variation.** Refusing to repeat a word, cycling synonyms ("the tool... the platform... the solution... the system"). Humans just repeat the word.
- **Em dash overuse.** Multiple em dashes per paragraph doing the job of commas or parentheses. (House rule here: zero em dashes.)
- **Front-loaded hedges.** "While there are many factors to consider...", "Although opinions differ...". Cut to the claim.

## 5. Content patterns

- **Inflated significance.** Generic statements about legacy, broader trends, or importance attached to mundane facts. If the significance is real, prove it with a specific.
- **Both-sidesing.** Presenting every view without taking one. Humans writing to a colleague have a position.
- **Vague attribution / weasel wording.** "Industry reports suggest", "Experts argue", "Observers have cited", "Some critics argue", "widely regarded as". Name the source or drop the claim.
- **Overgeneralization from one source.** "Several publications noted..." when one did.
- **Notability padding.** Lists of outlets that mentioned the subject, "maintains an active social media presence", "garnered significant coverage". Cite once if it matters; do not editorialize about how famous the coverage makes it.
- **Superficial comprehensiveness.** Covering every angle thinly instead of one angle well. A human expert goes deep on what matters and ignores the rest.
- **Hollow empathy.** "As a business owner, you know how hard it is to..." Fake shared experience with no specifics.
- **Generic "imagine" scenarios.** Hypotheticals with no real detail where a concrete example belongs.
- **Outline-shaped conclusions.** "Despite these challenges, X is well positioned to..." Speculative future-outlook paragraphs. Challenges and Future Prospects as a closing pair.
- **Padding to length.** Saying in 300 words what the ask needed in 50. Answer-shaped padding is a tell on its own.
- **Every claim hedged.** "may", "might", "could potentially", "arguably" sprinkled everywhere. Keep one honest caveat where uncertainty is real.
- **Invented causation.** Asserting why something happened, or where the time went, when the source only stated that it happened. Soft inference reads human and still misleads. Hedge it as a reading, or cut it back to the stated fact.
- **Cheerleading.** Corporate pep with no friction. Name the frustrating part when it is real and sourced.

## 6. Formatting tells

- Bold-header-colon bullets ("**Speed**: the new pipeline is...") as a substitute for prose
- Bullets for content that should be a sentence or two
- Emoji as list markers, emoji before headings, decorative emoji in professional docs
- Title Case In Every Heading (sentence case reads more human in most contexts)
- A "Conclusion" or "Final Thoughts" section on anything shorter than an essay
- Bolding every occurrence of key terms, key-takeaway style
- Horizontal rules as decoration between short sections
- Tables used decoratively for content that isn't tabular
- Curly "smart" quotes in contexts where everything else uses straight quotes
- Skipped heading levels (h2 straight to h4)
- Uniform bullet grammar: every bullet exactly one sentence with the same shape
- Markdown headers, bold, or asterisk-emphasis in emails, Slack, DMs, or SMS. In those channels, write plain sentences.

## 7. Chat residue and meta text

Instant giveaways; these mean the text was pasted straight out of a chatbot:

- "As an AI language model...", "As of my last knowledge update...", "my training data"
- "Certainly! Here's a..." / "Sure! Below is..." / "Great question!"
- "I hope this helps!"
- Leftover placeholders: "[Your Name]", "[Company]", "[insert date]"
- Citation artifacts: "contentReference", "oaicite", "turn0search0", ":contentReference", "[cite: 1]", "attached_file", stray "+1" markers
- Knowledge-cutoff disclaimers or refusal fragments
- Prompt echoes: restating the instruction inside the output ("Here is a 100-word LinkedIn post about...")
- Abrupt mid-sentence cutoffs
- Apologizing for or defending the text within the text
- Mentioning a style guide, a "humanize pass", or "as per the guidelines" inside the prose

## 8. Detection heuristics (how readers and tools spot it)

- **Cumulation.** One "crucial" is nothing; "crucial" + a triplet + "moreover" + an em dash in one paragraph is a verdict.
- **Burstiness.** Humans vary sentence length a lot; models don't. Detectors literally measure this.
- **Perplexity.** Model text picks the most probable next word; human text surprises. Concrete specifics (names, numbers, dates, small mess) raise perplexity naturally.
- **The anyone test.** If any model could have written this for any person, it still has no voice. A real specific from the source, or a real limit, is the fix.
- **The pub test.** Read it aloud. If you wouldn't say the sentence to a colleague at a pub, rewrite it.
- **The delete test.** If a sentence can be deleted and nothing is lost, it was padding. AI pads; delete freely.
- **Voice check.** Would the named sender actually type this? Match their real register (see house rules in SKILL.md), including their imperfections.

## 9. Do not "fix" these

Over-editing is the failure mode that replaces one fingerprint with a smoother one.

These are weak signals in isolation. Leave them unless they recur or cluster:

- Perfect grammar. Never add errors to look human.
- One passive sentence, one topic sentence, one well-earned three-part list.
- Formal register, when the audience is actually formal.
- Common connective tissue: however, therefore, for example. The tell is mechanical overuse of moreover / furthermore, not the existence of a transition.
- Curly quotes from a word processor. Normalize only to match the surrounding document.

Preserve these when the source already has them. Removing one is worse than leaving a mild tell:

- Real numbers, names, dates, and ugly details
- Mixed or contradictory feelings
- Self-corrections and asides ("or rather", "scratch that")
- Mild repetition for emphasis
- A distinctive idiolect, slang, or trade vocabulary the sender actually uses
- An unhedged opinion the source already holds
