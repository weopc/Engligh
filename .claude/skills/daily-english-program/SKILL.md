---
name: daily-english-program
description: A self-contained 30-day English fluency program that takes a Vietnamese intermediate learner (a tech lead at an Optimizely consultancy) up to advanced. Each day is speech-first with 5 parts: (1) a rich speech on an everyday life-or-work topic packed with the day's target grammar, templates and idioms; (2) Analysis of what's in the speech (grammar split by sub-type, sentence templates, phrases & idioms, vocab & collocations — skipping words the learner already uses); (3) Think Like an American mindset tips (in Vietnamese) to stop translating and think in English; (4) Expansion with new templates/phrases/vocab tagged by level; (5) extra speeches for more reps — so after one month the user can hold their own on almost any daily topic. Use whenever the user wants their daily English lesson, to start/continue the program, or to practice a specific day/theme. Trigger on phrases like "bài học hôm nay", "daily lesson", "Day 5", "next day", "tiếp tục lộ trình", "lộ trình 30 ngày", "start the program", "luyện tiếng anh hôm nay", "học nói hôm nay". This skill DESIGNS and DELIVERS the curriculum itself — it does NOT depend on the user's common_phases.md / common_sentences.md (those are optional extra drills at most). Pairs with workplace-english-coach: this skill teaches the day; the coach (Mode 5) grades the user's spoken delivery.
---

# Daily English Program — 30 Days, Intermediate → Advanced

A structured, self-contained month-long program for **a Vietnamese intermediate tech lead** who wants to reach **advanced fluency** and be able to talk about **any everyday topic**. This skill owns its own curriculum (see `references/curriculum.md`) — it does **not** rely on any external phrase file.

## The goal (and how the month gets there)

By Day 30 the user should be able to **speak for ~2 minutes on any everyday life-or-work topic**, using accurate grammar and natural phrasing. **Topics stay basic and practical** (routine, home, food, shopping, health, plans, family, hobbies, weather, and everyday work situations — job, tasks, meetings, colleagues, problems). No abstract/advanced subject matter. What rises is the **grammar & phrasing sophistication** — the grammar spine progresses B1 → C1, one new structure layered each day — so the user says *the same basic things* more accurately and more naturally over time. Mastering the transferable **functions + structures** (not memorising topics) is what lets them handle anything that comes up.

**Weekly arc:**
- **Week 1 (Days 1–7) — Foundations:** present systems, routines, describing, basic past narration. *(B1 → B1+)*
- **Week 2 (Days 8–14) — Social & narrative:** requests, experiences, plans, hypotheticals, regrets, reported speech. *(B1+ → B2)*
- **Week 3 (Days 15–21) — Explaining & reasoning:** passive, relative clauses, deduction, discourse markers, concession, problems/solutions. *(B2)*
- **Week 4 (Days 22–30) — Nuance & fluency:** emphasis (cleft/inversion), hedging, wishes, advanced conditionals, idioms, spontaneous speech. *(B2 → C1)*

Days 7, 14, 21, 28 fold in review of the preceding block. Day 30 is a spontaneous **capstone**.

## Running a session

1. **Figure out which day.** In order of priority:
   - If the user names a day/theme ("Day 12", "conditionals day", "the travel one") → do that.
   - Else read the progress file `english-30day-progress.md` in the user's working directory (English workspace) to find the current day.
   - If no progress file exists → this is Day 1. Briefly say you're starting the program and create the progress file.
   - If the user says **"next"** → advance to current+1.
2. **Read `references/curriculum.md`** and pull the spec for that day (theme, function, grammar focus, vocab theme, signature frames).
3. **Expand the skeleton into a full, fresh package** using the output structure below. The curriculum gives the skeleton; you generate the fleshed-out content each time so it stays lively and can adapt to the user.
4. **Update the progress file** when the user finishes (marks a day done or moves on).

Only read the ONE reference file you need. Don't preload anything else.

## Daily package — output structure (5 parts, speech-first)

The lesson is **speech-first**: the speech is the heart; everything else is derived from it. **Build Part 1 first**, deliberately seeding it with the day's target grammar/templates/idioms, then mine it for Parts 2-4. Follow the **language rule** and **bucket rules** below in every part.

**📅 Day N — [Topic]**
One line in Vietnamese: the situation + *"Cuối buổi bạn sẽ nói được: …"* (can-do goal) + name today's **target grammar** (from the curriculum).

**🗣️ Part 1 — The Speech** (centerpiece, ~500–700 words, read aloud)
A long, natural monologue on the topic the user reads aloud. Deliberately **load it with the day's target language, used many times in real context**:
- the day's **grammar structure** — appears repeatedly (and split naturally across its sub-types, e.g. simple *and* continuous),
- **key sentence templates / frames**,
- **several idioms / collocations**,
- plus a backbone of **high-frequency "core" everyday words** — not to teach them, but so the user *activates* them by saying them (this is where the ~1000 basic words get recycled).
**Marking = a teaching contract.** How you highlight the speech decides what Part 2 must explain:
- **Bold** = the day's grammar structures & sentence templates (these illustrate the target pattern).
- _Italics_ = every teachable lexical item — phrases, idioms, phrasal verbs, collocations, and notable vocab.
- **Leave basic words the user already uses PLAIN** (unmarked) — don't italicise *cook, dinner, coffee, meeting*. Marking them would oblige you to explain them, which wastes time.
- **Rule:** anything you italicise, you MUST explain in Part 2 — and everything in Part 2 comes from the speech. 1:1, nothing highlighted is left unexplained.

It must read like a real person talking — natural rhythm, contractions, personal detail — NOT a list of examples. Recycle earlier days' structures too (spiral). Keep the topic basic/everyday (life or work).

After the English speech, add a **📖 Bản dịch** block: the full Vietnamese translation of the Part 1 speech, blockquoted. Put it *below* the complete English speech (never interleaved) so the user reads the English aloud first for immersion, then checks meaning. Translate naturally (idiomatic Vietnamese, not word-for-word) and do NOT carry over the bold/italic marks. **This block applies to Part 1 only** — Part 5 speeches stay English-only.

**🔍 Part 2 — Analysis** (explain what's IN the speech)

**Coverage guarantee:** explain **every highlighted item** from the speech — no exceptions. Each _italicised_ phrase/idiom/phrasal verb → the Phrases & Idioms bucket; each _italicised_ vocab/collocation → the Vocabs & Collocations bucket; the **bolded** grammar instances → explained collectively in the Grammar block (not one-by-one). If it's highlighted in Part 1, it appears in Part 2.

- **Grammar — split by sub-type.** Give each form of the day's structure its OWN labelled block, with **1-2 sentences quoted from the speech** + ⚠️ 1 Vietnamese→English trap. Example layout:
  > **Present simple** — habits / facts
  > - *"I **usually get up** at six."*
  >
  > **Present continuous** — now / temporary
  > - *"Right now **I'm sitting** here."*
- **Sentence templates** — the frames used, with slot notation. Format:
  > **Do you think you could [V] by [time]?** = Bạn nghĩ mình có thể … trước [lúc]?
  > → *Do you think you could finish it by Friday?*
- **Phrases & idioms** — fixed expressions, idioms & phrasal verbs used. Format (**IPA** after the phrase; phrasal verbs marked `[tách]`/`[không tách]`/`[tự thân]`):
  > ### bring up /brɪŋ ʌp/ = nêu ra (vấn đề) `[tách]`
  > - I'd like to bring up a concern.
  > - She brought up a good point in the meeting.
- **Vocabs & collocations** — notable words/collocations used, **with IPA + part of speech**. Format:
  > **swamped** /swɒmpt/ (adj) = ngập việc → *I'm swamped this week.*

  ⚠️ **Skip words the user already actively uses.** Only list items worth the time: collocations, phrasal verbs, idioms, non-obvious usage, and upgrades. The 1-question test: *"Would an intermediate speaker produce this word themselves when speaking?"* → **Yes** = leave it in the speech, don't list it (e.g. *cook, dinner, meeting*). → **No / only recognises it** = list it (e.g. *swamped, catch up on*).

**🧠 Part 3 — Think Like an American** (in Vietnamese — the differentiator, invest here)
Teach *how to think* for this structure/topic so the user stops translating from Vietnamese: thinking in **chunks not word-by-word**, English word-order habits, the "default" way a native frames the idea, what Vietnamese logic to drop. Give **contrast examples** in the form *Vietnamese instinct → ❌ literal English → ✅ natural English*, plus 2-4 concrete thinking tips. Written in Vietnamese (it's coaching on mindset), but the English phrases inside stay English. Never skip or shortchange this section.

**➕ Part 4 — Expansion** (NEW language, NOT in the speech — this is where range grows)
Same three buckets as Part 2, but all-new items. **Internal minimums per day** (authoring targets — **do NOT print the counts in the output**; use plain headers like "Sentence templates", never "Sentence templates (≥10)"): 10 sentence templates · 10 phrases & idioms · 10 vocabs & collocations. Same formats as Part 2, same skip-known-words rule. **Never repeat a Part 2 item.** Tag each item by level:
- 🟢 *core* (nền, phải chắc) · 🔵 *upgrade* (nâng cấp, nghe hay hơn) · 🟣 *native* (idiom/collocation, nghe bản xứ).

**🎙️ Part 5 — Other Speeches** (1-2 more, same grammar/topic family, different situation)
Additional full speeches (~500–700 words each, like Part 1) on the same grammar and topic family but a **different scenario**, applying the Part 3 mindset. **Speech + bold/italic target language only — NO breakdown** (Parts 2-4 already taught the language; these are extra immersion + reading-aloud reps).

**🎤 Your turn** (light practice — end here)
1. Read Part 1 (and Part 5) aloud → hand off to `workplace-english-coach` **Mode 5** for grading.
2. Retell it in your own words using the target grammar + ≥5 items from Parts 2/4.
Then: *"Xong Day N rồi nói 'next' để qua Day N+1, hoặc 'review' để ôn lại."*

### Language rule
English by default. **Vietnamese ONLY for:** (a) the meaning/gloss of templates, phrases, idioms, vocab & collocations (format `English = nghĩa tiếng Việt`), (b) the whole of Part 3 (Think Like an American), and (c) the **📖 Bản dịch** block under Part 1 (a full Vietnamese translation of the Part 1 speech only). Everything else — speeches themselves, example sentences, headings — is English. E.g. `I have no idea = Tôi không biết`.

### Bucket rules (one item → one bucket, no duplication)
- **Sentence template** = a reusable frame with slots `[V]/[N]/[time]` → goes under Grammar.
- **Phrase / idiom** = fixed expression, idiom, or **phrasal verb** (`[tách]`/`[không tách]`/`[tự thân]`) → Phrases & Idioms.
- **Vocab / collocation** = single word or word-pairing, tagged with part of speech → Vocabs & Collocations.
- A given item appears in exactly ONE bucket (e.g. *bring up* is a phrasal verb → always Phrases, never Vocab).

## Design rules

- **Common over clever.** Everything must be language the user will actually say. No literary/rare vocabulary. Advanced ≠ obscure — it means precise, nuanced, and natural.
- **One new grammar structure per day**, but **recycle** older ones inside every new speech so nothing is learned once and dropped. Spiral, don't silo.
- **Push register up week by week.** Same idea, more sophisticated phrasing as the month progresses.
- **Everything is for speaking.** Short sentences, natural rhythm, contractions. If it's awkward to say out loud, rewrite it.
- **Bilingual scaffolding:** explanations/glosses in Vietnamese, English content in English. Explain *nuance* and *why*, don't translate every word.
- **Speech-first pedagogy.** The speech is the heart — build Part 1 first, seed it with the target language, then derive Parts 2-4 from it, and give more reps in Part 5. Learning happens by reading the rich speeches aloud, then understanding every piece.
- **Think Like an American (Part 3) is the differentiator.** It's what moves the user from "translating Vietnamese in their head" to "thinking in English." Never skip or shortchange it — it's the most valuable part of the day. Keep it in Vietnamese.
- **Activate, don't re-teach.** The user already knows most basic/core words passively — those live in the speeches to be *spoken* (activated), never on the vocab lists. Lists carry only what genuinely adds value (collocations, phrasal verbs, idioms, non-obvious usage, upgrades). Apply the skip-known-words test everywhere.
- **Every item needs a sentence example.** In Parts 2 & 4, no bare definitions — always show the word/phrase inside a natural English sentence.
- **Every vocab word, collocation, phrase & idiom carries an IPA transcription** (between slashes, right after the item) so the user knows how to say it. Use standard IPA and show word stress (ˈ) on multi-syllable words, e.g. **productive** /prəˈdʌktɪv/. Sentence templates don't need IPA (they're frames), but do gloss any tricky word inside them. When a word is a known Vietnamese-speaker pronunciation trap (final consonants, -ed/-s endings, /θ/ /ð/, word stress), add a short ⚠️ pronunciation note.
- **Hit the Part 4 minimums** every day: 10 templates, 10 phrases/idioms, 10 vocab — all new, all tagged 🟢🔵🟣. Don't print the counts.
- **Keep it scannable.** Bold grammar/templates, italics for idioms; blockquote the speeches. It's a full lesson (multiple speeches + analysis) — keep Parts 2-4 entries tight (1-3 lines each) so the volume stays readable.
- **Don't fabricate facts/stats** for topical themes — keep general or use clearly-marked placeholders.
- The user's `common_phases.md` / `common_sentences.md` (if present in the workspace) may be used as **optional extra drill material** only — never as the curriculum backbone, and never assume they're complete.

## Progress tracking

Maintain `english-30day-progress.md` in the user's English workspace. Simple format:

```
# 30-Day English Program — Progress
Current day: 6
Started: 2026-07-18

- [x] Day 1 — Daily routine & lifestyle
- [x] Day 2 — Home & neighborhood
- [ ] Day 3 — Food, cooking & eating out
...
```

Read it to resume; check off + bump "Current day" when a day is completed. If it doesn't exist, create it seeded from the curriculum's 30 titles.

## Variations the user can ask for

- **"Just grammar" / "chỉ grammar hôm nay"** → deliver only the grammar focus + drills.
- **"More vocab" / "thêm từ"** → expand the vocab set with 10 more + example sentences.
- **"Harder / easier"** → shift the model speech and phrasing up or down one CEFR notch (keep the day's grammar).
- **"Weekly review"** → synthesize the past 7 days: mixed drill + one speech pulling structures from all of them.
- **"Reschedule / I skipped days"** → re-anchor from the progress file; never scold, just resume.
- **"Full plan" / "xem cả lộ trình"** → show the 30-day overview table from `references/curriculum.md`.
