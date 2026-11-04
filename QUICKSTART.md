# Start your own team in 10 minutes

Four steps. No special click-paths — create a bot, paste a role description, talk to it.

## 1. Start with one Chief of Staff

Create a new bot. Open [`prompts/chief-of-staff.md`](prompts/chief-of-staff.md). Copy the **Role description** block into that bot. Replace every `<placeholder>` with your details.

This bot is the only one you talk to day to day. It routes work and reports back once.

## 2. Add a first specialist

Travel is a good first one. Create a second bot. Open [`prompts/travel.md`](prompts/travel.md). Paste its **Role description**, fill the placeholders, and connect the mail or calendar sources it needs.

Tell the Chief of Staff that Travel exists and what it owns. From then on, trip questions go to the Chief of Staff; it briefs Travel and brings you one answer.

## 3. Paste a role description from `prompts/`

Every file in [`prompts/`](prompts/) uses the same sections: Owns, Does not own, Source of truth, Needs approval for, Triggers, Outputs, Handoffs, Role description.

For a role that is not in the repo yet, copy [`prompts/_template.md`](prompts/_template.md), fill it in, and paste the role description into a new bot.

## 4. Begin with draft-only and the earned-autonomy ladder

Say this out loud in the first chat with each bot:

1. **Draft and ask.** The bot writes the draft. You approve the send, payment, post, or change.
2. **Offer standing permission.** After it has done the same reversible thing your way a few times, it asks: "OK if I just handle this kind of thing from now on?"
3. **Act and report.** Once you say yes for that kind, it does the work and tells you afterward.
4. **Still gated.** Payments, deletions, production changes, first messages to new people, and anything irreversible stay on a per-item yes until you grant that kind explicitly.

Trust is per kind of task, not a blanket for the bot.

## Next

- Read the [README](README.md) for the team shape, roster, and rules.
- Skim [`stories/`](stories/) if you want how each role earned its place.
- Cut before you add. If an existing bot only needs a new habit, give it that habit instead of a sibling.
