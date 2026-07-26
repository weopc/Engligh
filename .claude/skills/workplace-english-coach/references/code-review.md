# Code Review & Technical Discussion

Code review English has its own register: **terse, specific, friendly**. The bar is high because written comments outlive the conversation — they get re-read for years.

## PR / code review comments

### Suggesting a change (the workhorse phrases)
- **"Consider extracting this into a separate method — it'd be easier to test."**
- **"Small nit: could we rename `data` to something more specific like `userProfile`?"** — "nit" signals low-stakes
- **"What about using [pattern X] here? It'd handle the null case more cleanly."**
- **"This works, but I'd lean toward [alternative] because …"**

### Asking instead of telling (preferred default)
- **"Is there a reason we're not using [existing utility]?"** — discovers context you might lack
- **"How does this behave when [edge case]?"** — surfaces gaps without accusing
- **"What's the thinking behind [choice]?"** — neutral curiosity

### Flagging severity clearly (very useful for Vietnamese speakers)
Adopt these labels — they're widespread in Western engineering culture and remove ambiguity:

- **"nit:"** — minor, take or leave (style, naming)
- **"suggestion:"** — worth considering, not blocking
- **"question:"** — asking for context, not requesting change
- **"blocking:"** or **"⚠️ this needs to change before merge:"** — must-fix
- **"praise:"** or **"👍"** — call out good work (don't skip!)

This signaling solves a huge problem: junior devs often can't tell which comments are mandatory.

### Disagreeing technically
- **"I'd push back on this — [reason]. Curious what you think."** — invites discussion
- **"I see the appeal, but I'd avoid this approach because [concrete consequence]."**
- **"Have you considered [alternative]? I think it handles [edge case] better."**
- **"Strong disagree on this one — let's chat?"** — escalates to sync, fine when written debate isn't working

### Approving / praising
Don't just hit approve silently. A line of context goes a long way:

- **"LGTM 🚀"** — fine for trivial PRs
- **"Nice — clean separation between the validator and the service. Approved."**
- **"This is much cleaner than what we had. Approved."**
- **"Love the test coverage here."**

### Responding to your own PR getting reviewed
- **"Good point — updated."** — short and clean
- **"You're right, I missed that. Fixed in latest commit."**
- **"I went a different direction on this — [explanation]. Open to changing if you feel strongly."** — pushes back without confrontation
- **"Hmm, I want to think about this one more — let me come back to it tomorrow."** — totally fine

## Technical disagreement in conversation / Slack

### Disagreeing with a peer's design
- **"I'm not sold on this approach — can we talk through it?"**
- **"My concern with [their idea] is [specific risk]."** — concrete, not vague
- **"I'd argue for [your idea] because [reason]. But I might be missing something — what's driving your preference?"**

### Disagreeing with a senior engineer / architect
- **"I want to challenge this respectfully — [your concern]. Help me understand why we're not going with [alternative]?"**
- **"Genuinely asking, not pushing back: what's the trade-off we're making here?"**

### When the discussion is going in circles
- **"I think we're talking past each other — let me restate where I'm at: [your position]."**
- **"Can we step back? What problem are we actually solving?"**
- **"Should we just pick one and revisit in 2 weeks?"** — sometimes the right move

## Asking technical questions

### Asking without sounding lost
- **"Quick question — [specific question]."** — "quick" lowers stakes
- **"I want to make sure I understand the [system / pattern]: is X what's happening here, or am I off?"**
- **"What am I missing?"** — confident question, not self-deprecating
- **"I've been staring at this for an hour — fresh eyes welcome."** — natural Slack ask for help

### Documenting what you tried (huge upgrade for help requests)
- **"I tried A and B but hit [specific error]. Anyone seen this before?"**
- **"Repro: [steps]. Expected: X. Actual: Y. Already checked [Z]."** — instant-respect formatting

## Standup / planning context

(For dedicated standup phrases see `standup.md`.)

### Estimating
- **"Rough estimate, 2-3 days — I'll know more after the spike."**
- **"I'd say a week, with a caveat: [unknown]."**
- **"Hard to estimate until we [investigate X] — can I spike it for a day and come back?"**

### Pushing back on tight timelines
- **"That's tight. To hit that, we'd need to cut [scope item] — is that OK?"**
- **"I can hit that date, but quality will suffer. Want me to flag what we'd skip?"**

## Phrases to *retire*

- ❌ "Please change to X." → ✅ "Consider changing to X." / "Could we change to X?"
- ❌ "This is wrong." → ✅ "I think this might break when [scenario]."
- ❌ "Why did you do it this way?" (sounds aggressive in text) → ✅ "What was the thinking here?"
- ❌ "Maybe…" prefixing every suggestion (over-hedging) → state the suggestion, then add caveats if needed
