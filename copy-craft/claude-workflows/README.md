# Claude head-to-head vs Peggy

Dave 2026-09-03. Run the same writing job on Claude Cowork and on Peggy. Judge which draft ships.

## What you need on disk (same sources Peggy reads)

Claude must see the **same files**, not a summary of them.

1. Clone the private offsite repo (or pull if you already have it):
   - `https://github.com/daveatpopsmith/popsmith-agent-context`
   - Branch `main` → `popsmith-copy-craft/`, `popsmith-contexts/`
   - Branch `shared` → checkout `copy-context/` (or copy that folder from Drive)
2. Drive mirror (authoritative for talk libraries):
   - Google Drive → Popsmith → **Copy context**
   - On-box path for the crew: `/home/box/shared/copy-context/`
3. Put the cloned folders next to each other so the paths in the two workflow prompts resolve. If your local root is different, search-replace the root once at the top of each prompt.

Suggested local layout for Cowork / Claude Code:

```
C:\Users\dave\Popsmith-AI-Test\   (existing Cowork workspace — git pull first)
C:\Users\dave\popsmith-agent-context\   (clone of the GitHub repo, main)
C:\Users\dave\popsmith-agent-context-shared\   (same repo, shared branch) 
  OR sync Drive "Copy context" to C:\Users\dave\Popsmith-Copy-Context\
```

Then set in each prompt:

```
COPY_CRAFT = C:\Users\dave\popsmith-agent-context\popsmith-copy-craft
CONTEXTS   = C:\Users\dave\popsmith-agent-context\popsmith-contexts
COPY_CTX   = C:\Users\dave\Popsmith-Copy-Context   (or ...\popsmith-agent-context-shared\copy-context)
```

## Shootout order

1. Paste **[02-roma-brief-and-packet.md](02-roma-brief-and-packet.md)** into a **fresh** Claude Fable 5 Cowork thread. Fill the JOB INPUT at the top. Get a filled brief + packet.
2. Do **not** edit the packet to favor either side. Save it as one file both sides will use.
3. Paste **[01-peggy-compile.md](01-peggy-compile.md)** into a **second** fresh Claude thread. Point it at that packet path.
4. Run the same packet through Peggy on Grok Bot (Hagen → Peggy) with no extra coaching.
5. Blind yourself: label drafts A/B, score on kitchen-island (warmth, prose, one 45-year-old woman), cohesion, anti-AI, and whether a stranger can see the night. Your rewrite is still the ship if neither clears the bar.

## What Claude must not do

- Pull live AdNova / Meta / Shopify. Use only what is already in the brief/packet.
- Invent buyer facts. If a standing file is missing, stop.
- Paste library paragraphs into the draft.
- Call The Popper a pot unless you already wrote pot on that page.

## Files in this folder

| File | Role |
|---|---|
| `01-peggy-compile.md` | Paste-ready Claude workflow = Peggy's compile |
| `02-roma-brief-and-packet.md` | Paste-ready Claude workflow = Roma brief + Hagen packet |
| `README.md` | This shootout guide |
