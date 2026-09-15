# 📅 Workplace Practice — Sprint Review · Daily Standup · Tech Problem

🎯 **Mục tiêu:** dùng tối đa phrase bank của bạn (`common_phases.md` + `common_sentences.md`) vào 3 tình huống công sở thật: **PM tổng kết sprint**, **daily standup**, **thảo luận sự cố kỹ thuật**.

> **Quy ước:** **in đậm** = cụm lấy từ phrase bank của bạn (có nguồn ở cuối mỗi bài) · *in nghiêng* = từ/cụm MỚI, chưa có trong file của bạn (giải nghĩa kèm IPA).

---

## 🗣️ Bài 1 — PM tổng kết sprint (đóng vai PM)

*Tình huống: bạn là PM, họp cuối sprint, điểm qua từng ticket — cái nào xong, cái nào **spill over** sang sprint sau.*

> Alright everyone, **let's go over** the sprint board before **we wrap up**.
>
> Ticket one, the SSO integration — that's done. We **carried it out** exactly as planned, and it's already been **signed off on** by QA.
>
> Ticket two, the CMS migration — **we've hit a bit of a snag** with a legacy data issue. **We're still looking into** the root cause, so this one's going to *spill over* into next sprint.
>
> Ticket three, the dashboard — we **ruled** that **out** for this sprint entirely. The client **pushed back** the deadline, so we're moving it to next sprint instead.
>
> Ticket four, the caching bug — **it's pretty much done — just** a final review **left**. **Who's owning** the final sign-off? … Great, **let's put a deadline on** that — end of day tomorrow.
>
> As for the reporting ticket, **we called** it **off**. Turns out it was a duplicate of ticket four, so no need to **carry** that one **forward**.
>
> **So, to summarize, the next steps are**: the CMS migration and the dashboard both *spill over* to next sprint. Everything else wraps up today.
>
> Before **we reconvene**, **I want to flag** one risk — if the CMS issue isn't resolved soon, **this might delay** the whole migration timeline. **I'll follow up with** the team on that individually.
>
> Overall, **so far, so good** this sprint. Thanks, everyone, for **carrying** this **out**. **Let's reconvene** Monday for planning.

### 🆕 Từ mới (chưa có trong file của bạn)

**spill over (into [sprint/period])** /spɪl ˈəʊvə/ = tràn/dồn sang (kỳ sau) — dùng khi 1 ticket/task chưa xong kịp trong sprint này và phải chuyển tiếp sang sprint sau.
- This ticket will spill over into next sprint.
- A lot of work spilled over because of the outage.
> ⚠️ Khác với **"move to next sprint"** (chủ động dời) — *spill over* mang nghĩa **bị động, ngoài ý muốn** (không kịp xong).

### 🔍 Nguồn các cụm đã dùng

**common_sentences.md — Phần 2:** `let's go over` (2.6, biến thể "go over") · `let's wrap up` / `carrying this out` → *wrap up* (Nhóm 2, phrasal) · `so, to summarize, the next steps are…` (2.13) · `who's owning [N]?` (2.13) · `let's put a deadline on [N]` (2.13) · `let's reconvene` (2.13) · `I want to flag [N]` (2.11) · `this might delay [N]` (2.11) · `so far, so good` (2.10) · `it's pretty much done — just [remaining bit]` (2.10) · `I'll follow up with [name]` (2.9)

**common_phases.md (phrasal verbs):** `carry out` (Nhóm 5) · `sign off on` (Nhóm 7) · `look into` (Nhóm 1) · `rule out` (Nhóm 4) · `push back` (Nhóm 2 — nghĩa "lùi lịch", ở đây client là chủ ngữ) · `call off` (Nhóm 2) · `carry forward` (biến thể của carry out/carry over — mang nghĩa "chuyển tiếp") · `go over` (Nhóm 3)

---

## 🗣️ Bài 2 — Daily Standup (giống format hằng ngày)

*Tình huống: standup buổi sáng, cập nhật ngắn gọn — hôm qua, hôm nay, blocker.*

> Morning, everyone — **how's it going**? Let's **dive in**, **we've got a lot to get through**.
>
> **Yesterday I worked on** the caching bug fix. **I came across** a strange edge case, but **I figured it out** by the end of the day, and **it's in review** now.
>
> **Today I'm picking up** the dashboard ticket. **I'll go through** the requirements first, then **set up** a local test environment.
>
> **I'm blocked on** one thing — I'm still waiting on API access from the platform team. **I'll reach out to** them again this morning. Other than that, **no blockers on my end**.
>
> One more thing — **just to keep you posted**, **we're on track to** finish the migration by Friday. **It should be done by EOD** Thursday, barring surprises.
>
> That's it from me. **Let's touch base** again this afternoon if anything comes up.

### 🔍 Nguồn các cụm đã dùng

**common_sentences.md:** `how's it going?` (1.1) · `let's dive in` (2.1) · `we've got a lot to get through` (2.1) · `yesterday I worked on [N]` (2.2) · `it's in review` (2.2) · `today I'm picking up [N]` (2.2) · `I'm blocked on [N]` (2.2) · `no blockers on my end` (2.2) · `just to keep you posted` (2.10) · `we're on track to [V]` (2.10) · `it should be done by EOD` (2.2)

**common_phases.md:** `come across` (Nhóm 4) · `figure out` (Nhóm 1) · `go through` (Nhóm 7) · `set up` (Nhóm 1) · `reach out to` (Nhóm 7) · `touch base` (Nhóm 7)

---

## 🗣️ Bài 3 — Thảo luận sự cố kỹ thuật (tech problem)

*Tình huống: bạn là tech lead, giải thích sự cố cho team/stakeholder, đưa trade-off, và ra khuyến nghị.*

> Okay, **let me walk you through** what happened. Yesterday around 2 p.m., the production server **broke down** for about fifteen minutes.
>
> **Here's what I'm thinking** happened: we **came across** a memory leak after the last deploy. **We're looking into it, but** we don't have the root cause **yet**.
>
> **There's a risk that** this could happen again if we don't **deal with** it properly. **I'd be cautious about** just restarting the server and calling it fixed — **that's a fair point, but we need to weigh** the long-term risk.
>
> **The trade-off here is**: we could **roll out** a quick patch today, which **holds up** better short-term but doesn't fix the root cause. Or we spend two more days and **rule out** the memory leak completely.
>
> **My recommendation would be** to **roll out** the quick patch now to stop the bleeding, then **carry out** a proper fix next sprint. **Let's not over-engineer this** under pressure.
>
> **Correct me if I'm wrong, but** I think everyone's aligned on that? … Great. **I'll own this** — **I'll get back to you by EOD** with a written postmortem.
>
> **The bottom line is**: the system is stable now, we have a short-term fix ready, and a real fix planned. **Let's not make this a blocker** for tomorrow's release.

### 🔍 Nguồn các cụm đã dùng

**common_sentences.md — Phần 2 & 4:** `can you walk me through [N]?` (2.6, đảo thành "let me walk you through") · `here's what I'm thinking` (4.4) · `we're looking into it, but no root cause yet` (2.11) · `there's a risk that…` (2.11) · `I'd be cautious about [N]` (4.1) · `that's a fair point, but we need to weigh [N]` (4.1) · `the trade-off here is [N]` (4.1) · `my recommendation would be [N]` (4.1) · `let's not over-engineer this` (4.4) · `correct me if I'm wrong, but…` (2.5) · `I'll own this` (4.4) · `I'll get back to you on [N] by [time]` (2.8) · `the bottom line is…` (4.4) · `let's not make this a blocker` (4.5)

**common_phases.md:** `break down` (Nhóm 4) · `come across` (Nhóm 4) · `deal with` (Nhóm 4) · `roll out` (Nhóm 5) · `hold up` (Nhóm 4, dùng ở dạng "holds up" = chịu được/đứng vững — nghĩa mở rộng của "làm chậm trễ") · `rule out` (Nhóm 4) · `carry out` (Nhóm 5)

---

## 🧠 Think Like an American — mindset khi dùng phrase bank ở công sở

**1. Cụm "đắt giá" (Phần 4) chỉ dùng khi CẦN — không phải câu nào cũng nhét.**
Bài 3 dùng nhiều cụm Phần 4 vì đây là tình huống có **rủi ro & cần thẩm quyền** (giải trình sự cố). Bài 2 (standup) gần như không dùng cụm Phần 4 nào — vì standup là *báo cáo*, không phải *bảo vệ quan điểm*. 🧠 Tự hỏi: "Mình đang chỉ báo cáo, hay đang cần thể hiện mình kiểm soát tình huống?" → báo cáo thường → Phần 2; tình huống nhạy cảm → Phần 4.

**2. "Công nhận trước, phản đối sau" — không bao giờ vào thẳng "no".**
Bài 3: *"That's a fair point, but we need to weigh…"* — luôn có nhịp: nhận → rồi mới đưa góc nhìn khác. Đây là khác biệt lớn nhất so với phản xạ tiếng Việt (hay nói thẳng "không được đâu").

**3. Kết thúc bằng HÀNH ĐỘNG, không phải câu hỏi mở.**
Cả 3 bài đều kết bằng: ai làm gì, khi nào (*"I'll get back to you by EOD"*, *"let's reconvene Monday"*). 🧠 Người bản xứ không kết thúc cuộc họp bằng "OK vậy thôi nhé" — luôn chốt **next step + deadline + người phụ trách**.

**4. "spill over" vs "push back" vs "move" — chọn đúng động từ theo AI chủ động.**
- **spill over** = tự nó tràn sang (bị động, ngoài ý muốn).
- **push back** = CHỦ ĐỘNG dời lịch (có người quyết định lùi).
- **move up** = dời SỚM hơn (ngược lại hoàn toàn với push back).
→ Chọn sai động từ này sẽ đổi cả sắc thái "ai đang kiểm soát tình huống".

---

## 🎤 Your turn

1. **Đọc to** cả 3 bài → nhờ coach chấm phát âm & độ trôi chảy (Mode 5).
2. Chọn **1 trong 3 tình huống**, kể lại bằng tình huống thật ở công ty bạn (ticket thật, sự cố thật), cố dùng **≥8 cụm** từ phrase bank.
3. Thử đổi bài 3 sang tình huống bạn phải **present cho client** (thay vì team nội bộ) — chỉnh cụm nào cho formal hơn?

Muốn mình chấm phần đọc, hay tạo thêm bài 4 (vd: 1:1 với sếp, hoặc code review) theo đúng format này?
