# Claude's habits (run on everything Claude writes)

Dave, 2026-09-29. Claude reaches for the same devices by default. Any one of them is fine once. Used out of habit, they are what makes a page read as AI. This list exists so the edit can find them. Lines marked (2027 plan) are ones Claude actually wrote into the 2027 Creative and Offer Plan before Dave killed them.

Groups A to C are shapes. A search will not find them, so read for them. Groups D and E are words and marks, and a search finds those.

## A. Sentence shapes

1. **Verdict line.** A short summary built on a metaphor or an abstraction, with no number or named thing in it. "The off-season has a ceiling." "We make ads when they can win." (2027 plan) Fix: write the fact. "Off-season Meta ROAS has stayed at 1.8 to 1.9 for two years."
2. **Contrast frame.** "X, not Y." "It's not X, it's Y." "X rather than Y." "Less about X, more about Y." "X isn't the problem. Y is." Claude invents a wrong idea so it can knock it down. Fix: say Y. Keep a contrast only when the reader really believes X.
3. **Negation setup.** "This isn't a discount. It's a reason to buy." "No X. No Y. Just Z." Fix: say what it is.
4. **Colon reveal.** "The result: 400 creatives." "Here's what matters: timing." A colon used as a drumroll before the point. Fix: write the sentence. "That comes to about 400 creatives a year." Colons are fine before a list.
5. **Question, then answer.** "Why does this matter? Because..." "The result?" Fix: state it.
6. **Tricolon by default.** Three adjectives, three clauses, three bullets, three reasons, every time. Fix: use the real count. Two is fine. Four is fine.
7. **Mirrored pair.** "Q4 finds the winners and January proves them." "Volume is cheap. Hits are expensive." Two halves built to echo each other, which reads as a slogan. Fix: say what happens in each period, with the rule or the number.
8. **Punch coda.** A long sentence, then two to four words restating it. "Q4 holds." "That's the whole plan." "It works." (2027 plan) Fix: cut it. If it carries a fact, fold the fact into the sentence before.
9. **Abstraction as the actor.** An idea, a season or a dataset doing a human verb. "Q4 finds." "The season sets the number." "The data tells us." "Price honesty converts." Fix: make the person or the measured thing the subject. "Ads that ran 3.0+ in December..." "We launch..." A real actor is fine: an ad converts, a buyer waits.
10. **This/That summary opener.** "That holds only if..." "This means..." A sentence that opens by pointing back at the whole last idea. One per section is fine. A run of them is a bot. Fix: name the thing. "Buyers keep paying full price only if..."
11. **"The real X", "the key X", "the one thing".** "The real risk is the off-season." Fix: drop the adjective and say the risk.
12. **Throat-clearing opener.** "Here's the thing." "It's worth noting that." "Importantly," "Crucially," "Notably," "The bottom line is," "In short," "Put simply," "Ultimately," "At its core." Fix: delete it. The sentence stands without it.
13. **Cute personal verdict.** "hasn't earned the word winner yet." (2027 plan) Wordplay on a label nobody asked to be played with. Fix: "is a candidate until it passes $5k and 50 purchases."

## B. Paragraph and list shapes

14. **Verdict, proof, verdict again.** The paragraph opens with the conclusion, gives the evidence, then restates the conclusion. Fix: open with the number. Cut the restatement.
15. **One-line dramatic paragraph.** Fix: join it to the paragraph it belongs to.
16. **Closing summary.** "In short..." "So the plan is..." at the end of a section or a reply. Fix: cut it. The reader just read it.
17. **Labels promoted to slogans.** A plain bold label ("Constraint.") rewritten as a statement ("The off-season has a ceiling."). Fix: keep the author's label, or make the lead-in carry its number.
18. **Symmetry.** Every bullet the same length, every section the same number of bullets, every bullet opening with the same word. Fix: let the content set the length. Parallel openings only for a real checklist.

## C. Borrowed metaphors

Claude borrows from engineering, sport and finance to sound decisive. Each word is fine when it is literal. As a metaphor it is a tell:

ceiling, floor, lever, engine, fuel, drive, unlock, runway, headwind, tailwind, north star, moat, flywheel, playbook, bench, muscle, guardrail, lens, landscape, ecosystem, signal and noise, move the needle, table stakes, heavy lifting, load-bearing, double down, lean in, win (as in "ads that win"), land/lands, sit/sits ("the risk sits"), hold/holds ("Q4 holds"), carry ("the line carries"), earn ("hasn't earned"), shape ("a shape, not a promise"), the story ("the story here is").

Dave's own named terms stay where he uses them: engine, stabilizer, graveyard, bench, stop rule, levers, price honesty. Claude does not add new ones. Fix: use the literal verb. Is, was, ran at, returned, stayed, grew, fell, stopped.

## D. Words

genuinely, truly, really, actually, deeply, incredibly, quietly, simply, just, essentially, fundamentally, arguably, notably, crucially, importantly, ultimately, robust, crucial, pivotal, nuanced, seamless, holistic, leverage, streamline, navigate, foster, delve, dive in, resonate, showcase, underscore, testament, speaks to, a nod to, tapestry, realm, intricate, meticulous, vibrant, elevate, curated, journey. Fix: delete the intensifier. Swap the rest for the plain word.

## E. Punctuation and typography

Em dashes (one per piece at most). Semicolons. Colons used as reveals. "=", "vs" or arrows in prose. Scare quotes around made-up labels. Bold scattered mid-sentence for emphasis. Exclamation marks in business writing.

## F. Chat replies to Dave

The same rules apply. Also: don't restate his request back to him, don't end with a summary or a list of offers, and don't open with "Great question" or "You're right". Admit a mistake in one line and fix it.

## The check (every piece, after the draft)

1. Search for group D words and group E marks:
   `grep -niE "\b(genuinely|truly|really|actually|deeply|incredibly|quietly|simply|essentially|fundamentally|arguably|notably|crucially|importantly|ultimately|robust|crucial|pivotal|nuanced|seamless|holistic|leverage|streamline|navigate|foster|delve|resonate|showcase|underscore|testament|elevate|curated|ceiling|lever|unlock|runway|flywheel|playbook|landscape|real (risk|problem|question|issue)|the key)\b|;|—| not [a-z]+[.,]|rather than|here's|worth noting" draft.txt`
2. Read every sentence that has no number, date, name or named object in it. It either makes a claim a reader could check, or it goes.
3. Read the first and last sentence of every paragraph. Verdict lines, codas and summaries are usually there.
4. Read the bold text on its own, top to bottom. If it reads like a deck of slogans, rewrite it.
