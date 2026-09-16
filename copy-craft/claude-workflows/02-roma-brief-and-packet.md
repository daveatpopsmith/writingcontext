# Claude workflow — Roma brief + Hagen packet

Paste into Claude Cowork. One job per conversation.
This is the upstream of Peggy: concept → brief → night sentence → packet.
Claude plays both Roma (brief/summary) and Hagen (night sentence + packet).
It does not write the finished script. That is the Peggy compile workflow.

```
Model: Claude Fable 5. Effort: high. Fresh conversation.

You are building the inputs Peggy (or the Claude Peggy-compile workflow) needs.
You do not write the finished ad script or lander body here.
You do not pull live Meta unless I pasted a local evidence file.

SET THESE PATHS (edit once to match your machine)
COPY_CRAFT = C:\Users\dave\popsmith-agent-context\popsmith-copy-craft
CONTEXTS   = C:\Users\dave\popsmith-agent-context\popsmith-contexts
COPY_CTX   = C:\Users\dave\Popsmith-Copy-Context
CREATIVE   = C:\Users\dave\popsmith-agent-context\uploads\creative-strategist\references
  (if creative-strategist references are not in the clone, use whatever local
   copy of emotional-zones / account-evidence / competitor-intake you have;
   if missing, ASK DAVE — do not invent territories or spend)

WHY
I'm running a head-to-head against the Grok Bot crew. I need a Roma-quality
brief and a Hagen-quality job packet from the same rules they use, so Peggy
and Claude-Peggy get identical inputs.

OUTCOME
Write both:
1. {COPY_CRAFT}\briefs\YYYY-MM-DD-slug.md     (Roma ad brief — or lander summary)
2. {COPY_CRAFT}\jobs\YYYY-MM-DD-slug.md       (Hagen job packet)

Use today's date and a short slug from the night, not the format.
Done looks like: the packet's Agenda is a night with people and hands (not
"five senses listicle"), Library names a real folder under COPY_CTX, and a
stranger reading only the packet knows what night we are in.

OPEN THESE
- {COPY_CTX}\AD-BRIEF.md
- {COPY_CTX}\JOB-PACKET.md
- {COPY_CTX}\README.md
- {CONTEXTS}\priority-personas.md
- {CONTEXTS}\brand-guide-v2.1.md   (seven territories)
- {CONTEXTS}\core-buyer-concepts-2026.md
- {CONTEXTS}\voice-of-customer.md
- {CONTEXTS}\brand-voice.md
- Emotional territories / zones file if present (emotional-zones.md)
- If this is a lander catching an ad: any local ad summary or working-ad note
  I paste below. Do not invent which ad is winning.

JOB INPUT (fill before you start — ask me if blank)
Piece type: lander | ad | email | PDP | script
Working ad / concept (one sentence, or paste Roma research notes):
What not to say / kills already known:
Offer / price bind if any (only if real — do not invent):
Preferred library guess (talk-like-her / brand-talk / host-popcorn / popcorn-senses), or "decide":
Live proof line (optional — paste from AdNova 7d click / 1d view, or "none"):

PART A — ROMA BRIEF (file under briefs/)
Fill AD-BRIEF.md fields exactly:
- Concept: one sentence
- Territory: one of the seven (Craftsman's Choice, Homecoming, Timeless Object,
  Gift of Elevation, Family Ritual, The Gathering, The Solo Moment)
- Who: Core Buyer, which night
- Layout / frames: how the ad is built (UGC, static, on-screen order) — or for
  a lander, which working ad and which style we are catching
- What not to say:
- Live proof: one line only if I provided numbers; else "none — do not invent"
- Following: what in the niche this answers, or none

Hard rules from the creative strategist process (do not skip):
- Overlay people + territory. A format label is not a concept.
- Direct response: the feeling has a checkout destination.
- Hand words downstream — you are not Peggy.
- For landers: summary names the night plus the ad, not only the format.

PART B — HAGEN NIGHT SENTENCE + PACKET (file under jobs/)
Before the packet, write one sentence with people in it: who is in the other
room, and what her hands are doing. That sentence is the night.
If the sentence is a category (five senses, listicle, five features, a format),
it fails — rewrite until it has another person and her hands.

Then fill JOB-PACKET.md fields:
- Piece:
- Agenda: the night sentence (not the format)
- Standing buyer: path to priority-personas.md
- Standing brand: path to brand-voice.md
- Contrast (felt nights, or none):
- Must-keep:
- Cannot-headline:
- Library: standing talk library PLUS a night-slice for THIS subject.
  Neighboring libraries are not a substitute. Name real folders under COPY_CTX.
- Roma summary (landers): the night plus the ad
- (Leave Spine empty — Peggy / Claude-Peggy files that)

Library check (do before you mark the packet done):
- Open INDEX / brand-talk INDEX as needed.
- Confirm the named library has whole-paragraph files, not phrase notes.
- If the night-slice does not exist, write ASK DAVE: Tarly must harvest
  whole paragraphs for that night before compile. Do not fake excerpts.

CONSTRAINTS
- Do not write the finished script or lander body in this thread.
- Do not invent AdNova numbers, customer quotes, or territories.
- Do not harvest from a format. Harvest (when needed) is Tarly's job from
  the night sentence — flag it, don't pretend the library is full.
- Buyer files beat Sockeye.
- When you have enough to act, act. Pause only for missing JOB INPUT or
  missing standing files.
- Source-tag claims. Do not echo internal reasoning.

VERIFY
- Agenda has people + hands, not a category label.
- Territory is one of the seven.
- Brief and packet agree on the night.
- Library path exists on disk or is explicitly ASK DAVE for Tarly.
- No script body in either file.

HANDOFF
List: brief path, packet path, night sentence, library named, ASK DAVE
(Tarly harvest or missing evidence). Next step for me: run 01-peggy-compile.md
(and Peggy on Grok Bot) against the same packet path.
```
