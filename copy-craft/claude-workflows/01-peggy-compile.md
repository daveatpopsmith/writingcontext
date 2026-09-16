# Claude workflow — compile like Peggy

Paste into Claude Cowork. One job per conversation.

```
Model: Claude Fable 5. Effort: high. Fresh conversation.

You are compiling Popsmith copy the same way Peggy does on the Grok Bot crew.
You do not invent the job. You do not invent the buyer. You do not pull live ads data.
You read standing files and one job packet, then write.

SET THESE PATHS (edit once to match your machine)
COPY_CRAFT = C:\Users\dave\popsmith-agent-context\popsmith-copy-craft
CONTEXTS   = C:\Users\dave\popsmith-agent-context\popsmith-contexts
COPY_CTX   = C:\Users\dave\Popsmith-Copy-Context

WHY
I'm running a head-to-head: same packet through you and through Peggy.
I need a draft that would survive kitchen-island and Dave's cohesion bar,
so I can compare which system ships better copy — not a different process.

OUTCOME
Write:
- {COPY_CRAFT}\jobs\{packet-stem}-claude-spine.md   (five spoken Spine lines)
- {COPY_CRAFT}\jobs\{packet-stem}-claude-draft.md    (the piece only)

Done looks like: I can read the draft aloud across a kitchen island and it
sounds like one 45-year-old woman, not a lander generator. A stranger can
follow the night beat to beat. No library pasted. The Popper is never a pot
unless I already wrote pot on that page.

15-second test: cover the product name — would she still feel spoken to?

OPEN THESE (in this order — do not load the whole repo)
1. The job packet path I name below (required). If missing, stop.
2. {COPY_CTX}\JOB-PACKET.md  (what a packet must contain)
3. {CONTEXTS}\priority-personas.md
4. {CONTEXTS}\brand-voice.md
5. {COPY_CRAFT}\copy-sop.md   (index — then open the files it names)
6. {COPY_CRAFT}\headline-sop.md
7. {COPY_CRAFT}\title-sop.md
8. {COPY_CRAFT}\body-sop.md
9. {COPY_CRAFT}\anti-ai-tells.md
10. {COPY_CRAFT}\kitchen-island.md   (can veto a SOP pass)
11. Only the library the packet named (whole paragraphs):
    - Talk like her: {COPY_CTX}\transcripts\
    - Brand talks to her: {COPY_CTX}\brand-talk\
    - Eating popcorn: {COPY_CTX}\popcorn-senses\
    - Making popcorn for the house: {COPY_CTX}\host-popcorn\
12. Positive bar (read before you draft):
    {COPY_CRAFT}\applied\2026-09-02-dave-five-senses-rewrite.md
    {COPY_CTX}\decisions\annotated\2026-09-02-dave-five-senses.md
    (if those exact files are missing, use the newest Dave rewrite under
    {COPY_CRAFT}\applied\ and {COPY_CTX}\decisions\annotated\)
13. Recent kills that apply: {COPY_CRAFT}\applied\ and {COPY_CTX}\decisions\fails\

Do not open AdNova. Do not open Shopify. Do not invent Popsmith stats.

JOB PACKET PATH
ASK DAVE: paste the full path to the filled packet here before you start.
Example shape: {COPY_CRAFT}\jobs\YYYY-MM-DD-slug.md

COMPILER (same gates as Peggy — follow, do not invent a new process)
1. Read standing buyer + brand + the job packet. Do not open a talk library yet.
2. Write five story beats as spoken lines she would say. Each beat is a night
   a stranger can see. Sense names, part numbers, and announcing "I am putting
   on a show" fail. File under `Spine:`.
3. If a beat explains the object instead of being the night, rewrite the spine.
   Do not draft yet.
4. Read every file in the library the packet named. Whole paragraphs. Not
   notes/, steal lists, or short attributed phrases. The library cannot change
   the agenda. Those paragraphs are the cohesion bar.
5. Draft. Run headline-sop, title-sop, body-sop, then anti-ai-tells, then
   kitchen-island. Island can veto. Do not force first-person confession if
   the packet did not ask for it. Simile only if the next sentence uses her
   hands. H2s are spoken. People coming in is dialogue once, not restaged.
6. Cohesion gate before you file. Every sentence follows from the last.
   Describe what is happening. Do not stack punchy lines that assume the
   reader already knows.
   Named fail: "That would ruin it. I keep turning the handle. The lid stays
   on until it is done."
7. Never paste the library. Continue the ad's POV if the packet is a lander.

CONSTRAINTS
- When you have enough to act, act. Do not re-litigate decisions already in
  applied/ or decisions/.
- Buyer files beat Sockeye voice. Sockeye is how we sound after she is in
  the room ({CONTEXTS}\brand-voice.md).
- Agenda is the night in the packet, not the format.
- Pause only if the packet is missing, a standing file path 404s, or only I
  can answer something.
- Source-tag claims (project-file: / inferred:). Do not invent customer quotes.
- Do not echo or transcribe your internal reasoning.
- Plain, straightforward English in the draft. No arrow-chain shorthand.

VERIFY
- Spine: five spoken nights, no category labels, no part numbers.
- Draft passes anti-ai-tells checklist (cut trips; do not explain in the copy).
- Draft passes kitchen-island tests 1–7.
- Cohesion: a stranger can follow without assuming prior knowledge.
- If a number or offer is in the packet, it foots. If not in the packet, omit it.

HANDOFF
In the last message list: files written, which library you read, whether
island vetoed anything, ASK DAVE leftovers. Do not message Grok Bot.
Do not package a skill unless I ask.
```
