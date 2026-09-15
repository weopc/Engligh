---
name: ielts-reading-practice
description: Use when the user wants IELTS-style reading comprehension practice — trigger on "ielts passage", "bài đọc", "luyện đọc", "reading practice", "cho tôi bài đọc", "passage mới", "chấm bài đọc", "T/F/NG", "matching headings", or when the user pastes answers to a reading exercise for grading. Also use when the user wants to practise reading dense English quickly or asks about IELTS Reading question types.
---

# IELTS Reading Practice — General Training

Reading-comprehension practice for **a Vietnamese tech lead (~B2)** who is **not sitting the exam** — the IELTS format is used as a **precision-reading trainer**, not as exam prep.

## Learner profile — read this before generating anything

| | |
|---|---|
| Format | **General Training** — workplace notices, policies, job ads, light articles. *(Not Academic.)* |
| Target | **Band 6.5–7** |
| Goal | đọc-hiểu tiếng Anh dày/trừu tượng nhanh hơn — **không thi** |
| Question types | full IELTS set, rotating |

### 🎯 The real target: his worst error

His single most persistent error across 10+ translation-drill rounds is **"bỏ mất chi tiết"** — he reads for gist, then drops subjects, numbers, and qualifiers. See `translation-drill-log.md`.

**IELTS Reading question types are precision-reading exercises.** `True/False/NOT GIVEN` and gap-fill punish gist-reading directly. So:

- Weight **T/F/NG** and **completion** types more heavily than Matching Headings *(headings reward gist, which he already does)*.
- In every grading pass, when an answer is wrong, show **the exact line** that held the answer and **which word** he skipped.
- That "which word did you skip" line is the highest-value output of this skill. Never omit it.

---

## Non-negotiables

- **Original passages only.** Never reproduce real IELTS test material. Write fresh text each time.
- **Every answer must be findable in the passage.** No outside knowledge, no inference beyond what the text states. If an answer requires knowing something not in the text, the question is broken — rewrite it.
- **Never put answers in the exercise.** No answer key, no hidden block, no hints that name the paragraph. Grade only after he submits.
- **The passage must be brand new every time.** Vary topic and text type; log what's been used and don't repeat a topic within 10 sessions.
- **Word limits must be satisfiable.** If the answer key needs 4 words and the instruction says "NO MORE THAN THREE WORDS", the question is broken.

---

## Choosing content

1. Read `ielts-reading-log.md` (working directory) for: current level, question types with lowest accuracy, topics already used.
2. Pick a **text type** not used in the last 10 sessions (see rotation list below).
3. Pick **2–3 question types**, weighted toward the ones with lowest accuracy in the log. Always include at least one of `T/F/NG` or a completion type.
4. Default difficulty: **band 6.5–7**. Raise only when accuracy exceeds 85% for two sessions running.

### Text-type rotation (General Training)

**Section 1 — "social survival":** notices · timetables · service ads · membership rules · library/gym info · rental listings
**Section 2 — "workplace survival":** staff handbook extracts · job descriptions · contract clauses · training material · HR policy · onboarding guides · health-and-safety notices
**Section 3 — general interest:** magazine-style article on a non-specialist topic *(history of an everyday object, a workplace trend, a study about habits, urban planning, remote work)*

💡 Section 2 texts are the most useful for this learner — they mirror the English he actually reads at work. Favour them, but don't use them exclusively.

---

## MODE 1 — Ra đề (generate the exercise)

Default unit: **one passage, 500–800 words, 13–14 questions, 2–3 question types, ~18–20 minutes.**
`ngắn hơn` → 300–400 words, 8 questions · `dài hơn` → 900–1000 words, 18 questions

### Output shape

**# 📖 Reading Practice — #N**
Header: **Loại:** [Section 1/2/3 · text type] · **Dạng câu hỏi:** [list] · **Độ khó:** band 6.5–7 · **Thời gian:** 20 phút
One rules blockquote in Vietnamese: bấm giờ, không tra từ điển trong lúc làm, viết đáp án theo số, **và cảnh báo giới hạn từ nếu có**.

**## Passage**
The text itself. Paragraphs labelled **A, B, C…** *(needed for Matching Information/Headings, and useful for locating answers during grading anyway — always label)*. Natural English at band 6.5–7: mixed sentence length, some subordination, a few less-common words in context. No Vietnamese, no glosses.

**## Questions**
Numbered continuously (1, 2, 3 …) across all question types, like the real exam. Each type gets its own instruction block, worded exactly as IELTS does:

> **Questions 1–6**
> Do the following statements agree with the information given in the passage?
> Write **TRUE** if the statement agrees with the information · **FALSE** if the statement contradicts the information · **NOT GIVEN** if there is no information on this

> **Questions 7–10**
> Complete the sentences below. Choose **NO MORE THAN TWO WORDS** from the passage for each answer.

Close with: instruction to submit answers by number, and a note that grading comes with the exact source line for each item.

### ⚠️ Question-writing quality checklist — run before emitting

| Check | Why |
|---|---|
| Every answer has **one** locatable line in the passage | ambiguous answers make grading meaningless |
| `TRUE` items **paraphrase** the text, don't copy it | copying tests nothing |
| `FALSE` items **contradict** the text, not merely differ | most common authoring error |
| `NOT GIVEN` items are **genuinely absent** — not inferable, not implied | second most common authoring error |
| Completion answers are **taken verbatim** from the passage | IELTS requires exact words |
| Completion answers **fit the stated word limit** | a broken instruction wastes his time |
| Question order roughly follows passage order *(except Matching)* | matches real exam behaviour |
| No question answerable from general knowledge alone | it must test reading |

**The NOT GIVEN test:** ask *"could a careful reader argue this is true or false from the text?"* If yes, it's not NOT GIVEN — rewrite it. `NOT GIVEN` means the text is **silent** on it.

---

## MODE 2 — Chấm bài (grade)

Triggered when he submits answers. Grade **every question**, and flag any skipped.

For each question, one row:

| # | Đáp án của bạn | Đúng | Dòng trong bài |
|---|---|---|---|

- ✅ / ❌ per item.
- **`Dòng trong bài` is mandatory for every question, right and wrong alike** — quote the exact sentence (or the few words) that holds the answer, with its paragraph letter. This is what trains scanning.

Then, for **each wrong answer**, add a short explanation with this structure:

> **Q4 — bạn chọn FALSE, đáp án là NOT GIVEN**
> Đoạn C nói: *"[quote]"*
> Bài **không nói gì** về [X] — nó chỉ nói [Y]. Bạn suy ra từ kiến thức bên ngoài.
> 👉 **Chữ bạn bỏ qua:** [từ/cụm cụ thể]

That last line — **"chữ bạn bỏ qua"** — is the point of the whole exercise. Name the specific word (a quantifier, a modal, a time marker, a negation) he skipped. If the error wasn't a skipped word, say what the actual reasoning error was.

Then:
- **Điểm:** `X / N` + **% chính xác**
- **Theo dạng câu hỏi:** accuracy broken down by type — this is the actionable number, more than the total
- **Lỗi hệ thống:** the 1–2 reading behaviours that repeat *(e.g. suy diễn ngoài bài · bỏ qua từ chỉ lượng · không để ý `only/all/some` · vượt giới hạn từ)*
- **Từ vựng:** only the words that **blocked comprehension** — 5–8 max, with IPA and Vietnamese gloss. Skip words he clearly understood from context. Apply the same skip-known-words rule as the other skills.

Do not pad the vocabulary list. He has an explicit instruction in `3-MONTH-ROADMAP.md` to stop collecting new words; only list what actually stopped him.

## MODE 3 — Đọc to & kể lại *(optional, on request)*

If he asks (`đọc to`, `kể lại`, `retell`), add after grading:
1. Pick the **2 densest paragraphs** — the ones with the most subordination.
2. He reads them aloud, then closes the file and retells the whole passage in ~90 seconds, recorded.
3. Grade the retelling for: did he keep the **main claim**, the **numbers**, and the **qualifiers** *(some/most/only/not all)*? Dropping qualifiers is the same error as in the translation drills — name it when it happens.

This mode converts a reading exercise into speaking reps, serving the roadmap's 55%-speaking target.

---

## The log

Maintain `ielts-reading-log.md` in the working directory:

```markdown
# IELTS Reading — Log

## Độ chính xác theo dạng câu hỏi
| Dạng | Đã làm | Đúng | % | Trạng thái |
|---|---|---|---|---|
| True/False/Not Given | 18 | 11 | 61% | 🔴 yếu nhất |
| Sentence Completion | 12 | 10 | 83% | 🟢 |
| Matching Headings | 8 | 7 | 88% | 🟢 |
| Matching Information | 6 | 3 | 50% | 🔴 |

## Hành vi đọc cần sửa
- [ ] 🔴 suy diễn ngoài bài ở câu NOT GIVEN — 5 lần
- [ ] 🔴 bỏ qua từ chỉ lượng (some / most / only / all) — 4 lần
- [ ] 🟠 vượt giới hạn từ ở completion — 2 lần

## Lịch sử
| Ngày | Loại bài | Chủ đề | Dạng câu hỏi | Điểm | Ghi chú |
|---|---|---|---|---|---|
| 2026-09-09 | Section 2 | nội quy nhân viên | T/F/NG · completion | 10/13 (77%) | sai cả 3 câu NOT GIVEN |
```

Rules:
- Update after **every** grading: the per-type table, the behaviour list, and a history row **including topic** (for rotation).
- A reading behaviour closes only after **3 consecutive sessions** without recurrence.
- Every new exercise must include the question type with the **lowest accuracy**.
- Create the file on first grading if absent.

Without the per-type table this skill is just random reading. The table is what makes each session target the actual weakness.

---

## Variations

| User says | Do |
|---|---|
| `passage mới` / `bài mới` | new exercise, new topic |
| `ngắn hơn` / `dài hơn` | 300–400 / 900–1000 words |
| `khó hơn` | raise to band 7.5–8 · denser syntax, more abstract vocabulary |
| `chỉ T/F/NG` | one question type only, 12–14 items — use when that type is the open weakness |
| `chủ đề công việc` | Section 2 text type |
| `đọc to` / `kể lại` | Mode 3 after grading |
| `giải thích câu N` | full walk-through of one item: where the answer is, why the distractors fail |
| `đáp án` | refuse until he has submitted; offer to grade instead |

---

## Teaching notes per question type

Use these when explaining wrong answers — they are the actual skills being trained.

**True / False / NOT GIVEN**
- `FALSE` = the text says the **opposite**. `NOT GIVEN` = the text **says nothing**.
- The trap is always a qualifier: `all` vs `most`, `always` vs `often`, `will` vs `may`, `is` vs `is likely to`.
- If he has to reason to reach the answer, it's NOT GIVEN.

**Yes / No / NOT GIVEN** — same, but about the **writer's opinion**, not facts.

**Sentence / Summary / Note Completion**
- Words must come **verbatim** from the passage — no changing form, no synonyms.
- Check grammar fit: the answer has to make the sentence grammatical.
- Watch the word limit; hyphenated words count as one, numbers count as one.

**Matching Headings**
- Answer is the **main idea** of the paragraph, not a detail that appears in it.
- The commonest trap is a heading that matches one sentence but not the paragraph.

**Matching Information (which paragraph contains…)**
- Questions are **not** in passage order. Scan for the specific detail, not the topic.

**Multiple Choice**
- Distractors are usually true statements that don't answer the question asked.

**Short Answer**
- Word limit applies. Answer must be lifted from the text.

---

## Common mistakes when running this skill

- **Writing NOT GIVEN items that are actually inferable.** The single biggest quality failure. Run the NOT GIVEN test on every one.
- **Writing FALSE items that are really NOT GIVEN.** The statement must contradict, not merely go beyond.
- **Omitting the source line during grading.** Then he learns his score and nothing else.
- **Skipping the "chữ bạn bỏ qua" line.** That line is the entire pedagogical value.
- **Reproducing real IELTS material.** Always write original text.
- **Listing 20 vocabulary items.** He has an explicit instruction to stop hoarding words — list only what blocked comprehension.
- **Reporting a band score off a single passage.** One passage is not a test. Report **% per question type**; mention band only as rough orientation, and say it's xấp xỉ.
- **Ignoring the log.** Then the weak question type never gets targeted and the same errors repeat.
