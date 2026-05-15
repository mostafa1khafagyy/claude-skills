# claude-skills
Custom Claude skills for multi-project solo founders. Free.
# Claude Skills by Khufu Systems

Custom Claude skills I built for my own workflow, released free for anyone running multi-project work with Claude.

---

## session-handoff

Claude forgets after about 20 messages. This skill fixes that.

Type `session handoff` in any chat and Claude generates a structured continuation document — tagged by project, scoped to what actually changed in *this* chat (not your whole life), with a literal next-step command. Paste it into a fresh session and pick up exactly where you left off.

**Download:** [session-handoff.zip](https://github.com/mostafa1khafagyy/claude-skills/raw/main/session-handoff.zip)

### What it captures

Eight fields, nothing more:

1. **Project tag** — which venture / repo this belongs to
2. **Resume target** — Claude.ai chat or Claude Code session
3. **Session goal** — one sentence, what this chat was for
4. **Decisions made** — locked in today, not history
5. **Files touched** — exact paths, committed or not
6. **Exact next step** — literal command, literal path
7. **Blockers** — who or what you're waiting on
8. **Dead ends** — approaches ruled out, don't redo

### Why it's different

Most handoff approaches dump the whole world — your ventures, your stack, your working style, your goals — every single time. Bloated, redundant, ignored.

This one captures only the **session delta**: what changed in THIS chat that the next session needs. Claude already remembers the rest. Restating it is noise.

### Install (3 steps)

You'll need a Claude account (Free plan works) with **Code Execution** enabled. Turn it on at claude.ai → Settings → Capabilities → Code Execution.

1. Download `session-handoff.zip` (link above)
2. In Claude: profile icon → Settings → Capabilities → Skills → **Create skill** → upload the zip
3. Toggle it on

That's it. Active across all your chats.

### How to trigger it

Any of these phrases work — the skill triggers on natural language, not just one exact command:

- `session handoff`
- `this chat is getting too long`
- `I need to start a new chat`
- `before /compact` (Claude Code users)
- `summarise this for a new session`

### Hard rules baked in

- **Never pad.** Empty section = `N/A`. Honest sparse beats invented dense.
- **Never guess the next step.** If the chat ended mid-thought, the skill asks instead of fabricating.
- **One handoff = one project.** Mixed handoffs confuse the next session.

---

## Built by

Mostafa Khafagy — solo founder running 4 ventures with Claude as the operating layer.

- X: [@mostafakhafagyy](https://x.com/mostafakhafagyy)
- Web: [khufusystems.site](https://khufusystems.site)

If this saves you time, drop a star ⭐ — helps with distribution.

More skills coming. Built for my own workflow, shared because they might be yours too.
