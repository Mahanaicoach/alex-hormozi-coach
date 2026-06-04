<div align="center">
  <img src="assets/cover.png" alt="Alex Hormozi Coach — Clarity. Confidence. Scale." width="280">
</div>

# Alex Hormozi Coach 📞

**A free Claude skill from [Mahan AI](https://instagram.com/mahanaicoach).**

Turn Claude into a no-fluff business coach that runs your business through the **Alex Hormozi hotline method**: numbers first, find the *real* constraint, prove it with live math, prescribe the smallest high-leverage move, then ask *"what's stopping you?"*

It's **interactive by default** — one question at a time, just like a real call. You tell it what you sell and how much you make; it triages you into the right stage and coaches from there.

> 👋 Built and given away by **Mahan AI**. If this is useful, follow [@mahanaicoach](https://instagram.com/mahanaicoach) for more AI builds.

---

## ⚡ Quick start (60 seconds)

1. **Download** [`alex-hormozi-coach.skill`](alex-hormozi-coach.skill) from this repo. *(Click the file → the **Download** button.)*
2. **Open it** in the Claude desktop app (Cowork) and click **Save skill**.
3. In any chat, just say:

```
coach me on my business
```

That's it — you don't have to name the skill. Claude picks it up and opens with *"Rock and roll. Tell me about the business — what do you sell, how much you make?"*

Using **Claude Code** instead? See [INSTALL.md](INSTALL.md) for the folder-copy method.

📖 **Want the deep dive?** [GUIDE.md](GUIDE.md) explains exactly how it works and how to get the most out of every session.

---

## How it coaches you

It places you in one of four stages and runs the matching playbook — never giving a profitable-business answer to someone with no business yet:

| Stage | You are… | It focuses on… |
|---|---|---|
| **0** | No business / no revenue yet | Getting your first 5 customers (Core Four, free offers, warm outreach) |
| **1** | Have an offer, shaky revenue | Building a **Grand Slam Offer** — pricing, guarantees, naming |
| **2** | Running & profitable | The full **diagnostic loop** → money model (most callers land here) |
| **3** | Profitable but plateaued | **More** — volume, the real constraint, parallel machines |

Underneath every stage runs the same loop:

1. **Distrust the stated problem** — it's a symptom, pull the thread to the real constraint
2. **Call the shot** — say the hypothesis out loud
3. **Prove it with math** — CAC, LTV, margin, 30-day cash, payback, in round numbers, live
4. **Smallest change first** — the cheapest high-leverage move, as "thing one, thing two, thing three"
5. **Close with "what's stopping you?"**

It carries the benchmarks in its head — LTGP:CAC ≥ 3:1, recover CAC in 30 days, <2%/month churn, 60-second speed-to-lead — so it knows instantly when a number is fixable, not fine.

---

## What makes it different

Most "AI business advice" is a generic wall of bullet points. This skill holds a method:

- **One question at a time.** The back-and-forth *is* the coaching — each answer sharpens the next question.
- **Numbers before advice.** For anyone with revenue, the math finds the real constraint instead of the stated one.
- **Stage-matched.** A router prevents the #1 failure mode: scaling advice for someone with zero customers.
- **In voice.** Short sentences. Round numbers. Blunt but warm. Conversational — never a "Summary" report.
- **Honest guardrails.** No earnings promises, no legal/tax/investment advice, stays in lane, and never pretends to literally *be* Alex Hormozi.

---

## What's inside (the skill's brain)

| File | What it does |
|---|---|
| [`SKILL.md`](alex-hormozi-coach/SKILL.md) | The session runner — how to triage and coach |
| [`FLOW-0-router.md`](alex-hormozi-coach/FLOW-0-router.md) | Triage + adaptive intake (always read first) |
| [`FLOW-1`–`FLOW-4`](alex-hormozi-coach/) | One runnable playbook per stage |
| [`VOICE.md`](alex-hormozi-coach/VOICE.md) | The fidelity layer — phrase bank, voice laws, worked transcripts |
| [`BENCHMARKS.md`](alex-hormozi-coach/BENCHMARKS.md) | What "good" looks like, missing-data handling, guardrails |
| [`COACHING-FRAMEWORK.md`](alex-hormozi-coach/COACHING-FRAMEWORK.md) | The 8-step loop + mental-model library |
| [`REF-leads / offers / money-models`](alex-hormozi-coach/) | Deep extractions of the $100M books' mechanics |

It uses **progressive disclosure** — Claude only loads the file for the stage you're in, so it stays fast.

---

## Usage examples

```
coach me — I run a mobile dog grooming business, about $600K/year but I can't hire groomers that stick
```

```
help with my offer, nobody's buying
```

```
I want to start a podcast editing business but I've never had a client
```

```
I'm profitable but stuck. how do I scale?
```

---

## Disclaimer

This is an **independent, fan-made coaching skill** built on the publicly published frameworks from Alex Hormozi's `$100M Offers`, `$100M Leads`, and `$100M Money Models`. It is **not affiliated with, endorsed by, or created by Alex Hormozi or Acquisition.com**, and it does not claim to be him. It channels his frameworks and style for educational coaching only.

Results vary — most people do nothing with good advice. Nothing here is an earnings claim, or legal, tax, financial, or investment advice. Run big financial moves by a professional.

---

## License

MIT — see [LICENSE](LICENSE). Use it, fork it, ship it.

---

<div align="center">

**Made by Mahan AI** · Follow for more AI builds → [@mahanaicoach](https://instagram.com/mahanaicoach)

</div>
