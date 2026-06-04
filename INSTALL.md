# Installing Alex Hormozi Coach

Two ways to install, depending on how you use Claude. Pick the one that matches you.

---

## Option A — Claude desktop app (Cowork) ✅ easiest

1. On this repo's main page, click the file **`alex-hormozi-coach.skill`**.
2. On the file page, click the **Download** button (or the download icon) to save it.
3. Open the **Claude desktop app**.
4. Drag the `alex-hormozi-coach.skill` file into a chat (or open it), then click **Save skill**.
5. Done. Start a chat and say `coach me` — Claude loads the skill automatically.

> The `.skill` file is just a zipped bundle of everything in the `alex-hormozi-coach/` folder. You don't need to unzip anything yourself.

---

## Option B — Claude Code (CLI / terminal)

```bash
# 1. Clone this repo
git clone https://github.com/mahanaicoach/alex-hormozi-coach.git

# 2. Copy the skill folder into your Claude Code skills directory
cp -r alex-hormozi-coach/alex-hormozi-coach ~/.claude/skills/
```

Claude Code discovers skills in `~/.claude/skills/` on the next run.

> Copy the inner `alex-hormozi-coach/` folder (the one containing `SKILL.md`) — not the repo root.
> Skills can also live project-level in `.claude/skills/` inside a specific project.

---

## Verify it's working

Open a chat and say:

```
coach me on my business
```

If the skill is installed, Claude opens in character — *"Rock and roll. Tell me about the business — what do you sell, how much you make?"* — and asks one question at a time. If it doesn't, double-check the install step above, or be explicit: *"use the alex-hormozi-coach skill."*

---

## Troubleshooting

| Problem | Fix |
|---|---|
| Claude doesn't trigger the skill | Re-check the save/copy step. Try: *"use the alex-hormozi-coach skill on my business."* |
| It dumps a wall of advice instead of asking questions | Tell it *"one question at a time"* — the interactive loop is the whole method |
| It asks about churn/CAC when I have no business yet | Say you have no customers yet — it should route you to the first-customers playbook |
| It opens with a disclaimer | By design it shouldn't; if it does, just answer the first question and it'll stay in voice |

---

Want more builds like this? → [@mahanaicoach](https://instagram.com/mahanaicoach)
