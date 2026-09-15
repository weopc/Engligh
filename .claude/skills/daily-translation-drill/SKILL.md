---
name: daily-translation-drill
description: Use when the user wants a Vietnamese→English translation exercise to activate language they already know passively — trigger on "bài dịch", "translation drill", "cho tôi đoạn văn tiếng việt", "đưa đoạn văn tôi dịch", "luyện dịch", "bài tập dịch hôm nay", "drill day 8", "ôn lỗi cũ", or when the user pastes a translation and asks for grading. Also use when the user says they know words but can't use them fluently in speech.
---

# Daily Translation Drill — VN → EN

A daily reverse-translation exercise for **a Vietnamese intermediate tech lead** doing the 30-day program. The learner's problem is **not vocabulary knowledge — it's activation**: they recognise words but can't produce them, because they translate word-by-word from Vietnamese.

## What you produce: a real speech, not a list of sentences

The exercise is **one continuous Vietnamese monologue the learner could actually deliver out loud** — the same thing as Part 1 of a lesson, but in Vietnamese for them to translate. Prose in paragraphs. **Never a numbered list of sentences.**

A numbered list is a grammar worksheet: the learner translates 25 unrelated fragments, gets 25 verdicts, and still can't hold a conversation. A real monologue forces them to carry a thought across sentences, link ideas, and keep a consistent voice — which is what actually breaks when they speak.

### Constraint 1 (dominant) — realism

The passage must pass all four:

1. **Would a real person say this out loud to a colleague or friend?** Read it aloud in Vietnamese. If any sentence sounds like a textbook, rewrite it.
2. **Is it specific?** Real names, real times, real numbers, real small annoyances. *"Thứ Ba mạng rớt ba lần giữa buổi demo với khách"* — not *"Đôi khi tôi gặp vấn đề kỹ thuật."*
3. **Does it have a shape?** situation → complication → what I did → what I realised. A story, not a topic summary.
4. **Is every sentence there for a reason of its own?** If a sentence exists only to host a grammar item, cut it or fold the item into a sentence that already earns its place.

Natural Vietnamese means natural: contractions, filler (*thật ra, kiểu như, nói thật là*), asides, a joke, an unfinished thought. Written-formal Vietnamese produces written-formal English.

### Constraint 2 — seed the target language

Inside that realistic passage, place 15–20 target items from the relevant lessons. For each, aim for a Vietnamese phrasing where **a word-for-word translation lands somewhere wrong or awkward**, but the target English item fits perfectly:

> VN: *"Cái ghế cũ rẻ hơn nhiều nhưng về lâu dài thì không đáng."*
> Literal path: ❌ *cheaper much … not deserve* → forces the learner to reach for ✅ **far cheaper** + **it wasn't worth it in the long run**.

**Order of operations:** decide the target items → decide the real situation → write the passage as a story → check each target landed naturally. Not: write 20 trap sentences and glue them together.

**When the two constraints conflict, realism wins.** Drop the item, keep the passage speakable. Hitting 20 items in a passage no human would utter teaches the learner to produce English no human would utter.

## Non-negotiables

- **Prose, not a numbered list.** The passage is delivered as paragraphs. Label paragraphs `¶1 … ¶N` for reference during grading, but never number or split individual sentences.
- **Never put English in the exercise.** No translation, no hidden/collapsed answer block, no per-sentence hints. Seeing English destroys the drill. The word bank is the only English allowed, and it must not map items to any location in the passage.
- **Stay inside the learner's known vocabulary.** Only use items from days they have already completed. The problem is *using*, not *knowing more*. Never introduce new words in a drill.
- **The passage must be brand new every time.** Never reuse, translate back, paraphrase, or reshuffle a speech from `lessons/Day-XX-*.md` — not Part 1, not Part 5, not a previous drill. The learner has already read those; translating a passage whose English original they've seen tests recall, not production. Mine the lesson files for **which items to target**, then invent a situation that does not appear in them.
- **Grade before revealing.** The model answer comes only after the learner's attempt has been graded, and only when they ask.

### Inventing a fresh situation

Same target language, different life. Before writing, pick a situation that differs from the lesson's on at least two axes: **who** is talking to whom, **where** it happens, and **what goes wrong**. Day 8's lesson speech is a tech lead asking colleagues for things at the office → a valid drill instead: renting a flat and negotiating with the landlord · a parent asking the school for a favour · a customer at a phone shop · a Sunday trip where someone forgot the tickets.

Rotate the setting across drills — work, home, street, shop, family, travel, health, phone call. Log the scenario each time (see the log section) and **never repeat a scenario within 10 drills**.

---

## Choosing the content

1. **Which day?**
   - User names one ("day 5", "drill day 12") → use that.
   - User says `ôn lỗi cũ` → build the whole drill from the recurring-errors list in the log (see below), ignoring day structure.
   - Otherwise → read `english-30day-progress.md` in the working directory for the current day.
2. **Main day** = that day's grammar. This carries ~60% of the sentences.
3. **Review days** = pick 2 **already-completed** days, favouring (a) days that appear in the recurring-errors list, then (b) older days over recent ones. These carry ~40%.
4. Read the actual lesson files — `lessons/Day-XX-*.md` — to pull the real templates/phrases/vocab the user was taught. Read `.claude/skills/daily-english-program/references/curriculum.md` only when the lesson file for that day doesn't exist yet.
5. Always print the split in the header: *"Chính: Day 8 · Ôn: Day 3, Day 5"*.

Read only the files you need. Don't preload all 30 lessons.

---

## MODE 1 — Ra đề (generate the exercise)

Default length: **400–550 Vietnamese words in 5–7 paragraphs** (~30 min to translate). `ngắn hơn` → 200–280 words, 3–4 paragraphs · `dài hơn` → 600–750 words.

Output exactly this shape:

**# 🗣️ Bài nói — Day N**
Header: **Chính:** Day N (grammar) · **Ôn:** Day X, Day Y
One line setting the scene in Vietnamese — who is talking, to whom, about what. *"Bạn đang kể cho một người bạn về tuần vừa rồi ở công ty."* This matters: a monologue with no audience produces flat English.
Then a rules blockquote: dịch cả bài, giữ nguyên giọng kể (đừng dịch trang trọng hơn bản tiếng Việt), không mở file bài học, và *"bài này gài 15–20 cụm bạn đã học — dịch từng chữ sẽ ra câu sai."*

**## 🇻🇳 Bài nói**
The passage itself — **continuous prose in paragraphs**, blockquoted, each paragraph tagged `¶1`, `¶2`… A real person telling a real story. First person, spoken register, everyday work-or-life situation matching the day's theme. **No sentence numbering. No bullet points. No ⚠️ marks inside the passage** — flagging traps in place tells the learner exactly where to slow down, which is not how speaking works.

**## 🧰 Word bank**
A flat, shuffled list of the target English items — grammar frames, phrases, collocations — separated by `·`. **Never indicate where any item belongs.** Never gloss them in Vietnamese (they already learned the meaning; this is a retrieval test).

**## ⚠️ Bẫy chính**
A table of the 3–5 deadliest traps: `| ¶ | Bẫy | Nhớ gì |`. Point at a paragraph, name the trap, give the rule in one line — but **never** quote the Vietnamese sentence and **never** give the English answer. Paragraph-level is deliberately vague: the learner has to find the trap themselves. Prioritise traps with real consequences (e.g. `don't have to` vs `mustn't`) and traps from the recurring-errors log.

Close with: *"dịch cả bài, đừng bỏ đoạn nào"* + a nudge to **read the Vietnamese aloud once first** so they translate the spoken version, not the written one + a note that grading comes first, model answer after.

### Trap types worth weaving in

| Trap | Vietnamese instinct that causes it |
|---|---|
| Word order in indirect questions | tiếng Việt không đổi trật tự từ |
| `don't have to` vs `mustn't` | cả hai đều là "không phải/không được" |
| V-ing vs to-V vs bare V after a verb | tiếng Việt động từ không đổi dạng |
| Present perfect vs past simple | "đã" dùng cho cả hai |
| Preposition inside a fixed phrase | *miss out **of*** thay vì *on* |
| Missing article (a/an/the) | tiếng Việt không có mạo từ |
| `very` + comparative | *rất* và *nhiều* dùng lẫn nhau |
| Politeness by sentence length | tiếng Việt lịch sự bằng từ đệm (ạ, nhé) |
| Verb agreement / plural -s, -ed endings | không có biến đổi hình thái |
| `there is/are` vs `have` | "nhà tôi **có** hai phòng" |

---

## MODE 2 — Chấm bài (grade the learner's translation)

Triggered when the user pastes their translation. Work **paragraph by paragraph** (`¶1`, `¶2`…), and flag any paragraph or sentence they skipped.

For each paragraph:
1. Quote back only the sentences that need work — don't reprint correct sentences, it buries the signal.
2. Verdict per sentence: ✅ (đúng & tự nhiên) · 🟡 (đúng nghĩa nhưng gượng / lỗi nhỏ) · ❌ (sai).
3. For every 🟡 and ❌: the natural version + **name the thinking error**. That label is what makes the drill compound. Use consistent labels:

`dịch từng chữ` · `sai dạng động từ` · `sai giới từ` · `thiếu mạo từ` · `sai thì` · `trật tự từ` · `sai sắc thái` · `từ sách vở` *(đúng nghĩa nhưng không ai nói thế)* · `thiếu -s/-ed`

Then, across the whole passage:
- **Điểm:** `X / N` where N = total sentences (1 điểm ✅, 0.5 🟡, 0 ❌ hoặc bỏ trống).
- **Độ trôi chảy của cả bài** — this is the part a numbered drill can't grade, so don't skip it: does their English hold together as one speech? Check linking between sentences, pronoun/tense consistency across paragraphs, whether the register stayed spoken, and whether they lost the speaker's voice. Name the single biggest fluency problem and show one paragraph rewritten to fix it.
- **Lỗi hệ thống:** the 2–3 patterns that repeat, each with a fix drill. A learner making the same error 4 times has one problem, not four.
- **Retake:** re-ask only the ❌ sentences and skipped parts, as bare Vietnamese, no hints. Do this **before** offering the model answer.

Do not soften. If a sentence is grammatical but no native speaker would say it, that is 🟡 with `từ sách vở` — say so plainly and give the upgrade.

## MODE 3 — Đáp án (model answer)

Only after grading. The whole passage as **one continuous English speech** — same paragraphs, same `¶` tags, blockquoted — that reads like a real person talking, with **bold on every target item** so the learner can see the frames they were supposed to reach for. No commentary between sentences; it has to be readable aloud end to end. Then 2–3 lines on where their version diverged most from the model, and one sentence they should steal outright.

---

## The log (the part that makes this compound)

Maintain `translation-drill-log.md` in the working directory:

```markdown
# Translation Drill — Log

## Recurring errors (bài sau sẽ gài lại)
- [ ] thiếu mạo từ trước danh từ đếm được — sai 4 lần (D5, D6, D8)
- [ ] `miss out of` → `miss out on` — sai 2 lần
- [x] `very` + comparative — đã sửa, 3 bài liên tiếp không sai

## History
| Date | Chính | Ôn | Tình huống | Điểm | Lỗi nổi bật |
|---|---|---|---|---|---|
| 2026-08-04 | Day 8 | D5, D6 | thuê nhà · thương lượng với chủ nhà | 19.5/25 | trật tự câu hỏi gián tiếp, thiếu mạo từ |
```

Rules for the log:
- After every grading, add the history row — **including the scenario** — and update recurring errors with a count.
- Before writing a new drill, read the `Tình huống` column and pick something absent from the last 10 rows.
- An error graduates to `[x]` only after **3 consecutive drills with no recurrence**. Then stop seeding it.
- Every new drill must deliberately re-seed **at least 2** open recurring errors. Say nothing about which ones — the learner shouldn't know where the trap is.
- Create the file on first grading if it doesn't exist.

Without this log the skill is just a random sentence generator. The log is what turns it into targeted practice.

---

## Variations

| User says | Do |
|---|---|
| `day 12` / `drill day 3` | that day as Chính |
| `random` | any completed day, 2 random review days |
| `ôn lỗi cũ` | every sentence targets an open recurring error; ignore day structure |
| `ngắn hơn` / `dài hơn` | 200–280 / 600–750 words |
| `bài khác` | same day, same targets, **completely different scenario** |
| `hội thoại` | same mechanic, but render as a 2-person dialogue (`A:` / `B:`) instead of a monologue |
| `đáp án` | Mode 3 — but refuse if the attempt hasn't been graded yet; offer to grade first |
| `khó hơn` | keep the same items, but write the Vietnamese further from English structure (more idiomatic VN → harder to reach the English frame) |

## Common mistakes when running this skill

- **Emitting a numbered list of sentences.** That's a grammar worksheet. The output is a speech in paragraphs, always.
- **Reusing the lesson's speech in Vietnamese.** The most tempting shortcut and the most useless drill — the learner has read that English already. Invent a new situation every time.
- **Writing the Vietnamese first, then hunting for targets.** Produces filler. Go targets → situation → story → check the targets landed.
- **Letting the traps deform the prose.** A passage stuffed with 20 items but unspeakable teaches unspeakable English. Realism wins; drop items.
- **Marking traps inside the passage.** ⚠️ in the text tells the learner where to be careful. Real speech gives no warnings. Keep hints at paragraph level in the trap table only.
- **Glossing the word bank in Vietnamese.** Turns a retrieval test into a matching exercise.
- **Using vocabulary from days not yet covered.** The learner then fails for the wrong reason and learns nothing about activation.
- **Giving the model answer alongside the exercise** because the learner asks for it upfront. Grade first — always.
- **Praising a sentence that's merely grammatical.** `local people` is correct but `the locals` is what people say. Mark it 🟡 and upgrade it.
- **Grading only sentence-by-sentence.** The whole point of a passage is cohesion — always grade flow across paragraphs too.
- **Skipping the log update.** Then tomorrow's drill repeats yesterday's mistakes and yesterday's scenario by accident instead of on purpose.
