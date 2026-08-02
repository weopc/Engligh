# 📅 Day 21 — Problems, Cause–Effect & Solutions · *WEEK 3 REVIEW*

🎯 **Target grammar:** Cause–effect / result / purpose linkers — **because / since / as / due to / because of** (nguyên nhân) · **so / so … that / therefore / as a result / consequently** (kết quả) · **to + V / in order to / so that** (mục đích).
🔁 **Ôn Week 3:** passive voice (Day 15) · relative clauses (Day 16) · conditionals (Day 19) — lồng vào quanh trục nhân–quả.
*Cuối buổi bạn sẽ nói được: nêu một vấn đề, giải thích nguyên nhân và hậu quả của nó, rồi đề xuất cách khắc phục — nối ý mạch lạc như người bản xứ.*

> **Quy ước:** **in đậm** = ngữ pháp / mẫu câu (hôm nay: **linker nhân–quả** + ôn **passive/conditional/relative**) · *in nghiêng* = phrase/idiom/collocation đáng học (giải nghĩa hết ở Part 2, kèm IPA). Từ cơ bản để trơn.

---

## 🗣️ Part 1 — The Speech *(đọc to 1–2 lần)*

> Let me walk you through a problem we ran into last week — what caused it, what it led to, and how we finally sorted it out.
>
> So, last Monday our client's website went down for about an hour. **It went down because** one of our servers *ran out* of memory. **The reason it happened was that** a background job, **which** nobody had touched in months, suddenly started *eating up* resources. **Since** we hadn't set up proper alerts, we didn't notice until customers started complaining. **As a result**, orders couldn't be processed for a while, **so** the client *lost a fair bit of* revenue.
>
> And **because** the site was down during a sale, the timing couldn't have been worse. The client was frustrated, and *rightly so* — **when** you're paying for a service, you expect it to just work. **Due to** the outage, we **had to** send an apology and offer some credit, **which** stung a bit. That said, being upfront *paid off*: **because** we were honest about the cause, the client actually trusted us more afterwards.
>
> **The root cause was** a *memory leak*. **Because** the code **had been written** years ago by someone **who** had already left the company, no one really understood it. **Due to** that lack of documentation, it took us hours just to *track down* the problem. **If we'd had** better monitoring, **we would have caught** it much sooner — but that's *water under the bridge* now.
>
> Here's how we tackled it. First, the server **was restarted** **so that** the site could come back up straight away. Then the faulty job **was disabled** **in order to** stop it from crashing again. **We did that so that** the client wouldn't lose any more orders while we investigated. **Therefore**, within an hour, everything **was running** normally again.
>
> But a quick fix isn't a real fix. **The reason we dug deeper was** we didn't want it to happen again. **So**, over the next two days, we **rewrote** the job **so that** it releases memory properly. We also **set up** alerts **to** catch this kind of thing early. **As a result of** those changes, the system is far more stable now. **That's why** I always say: don't just *treat the symptom* — *treat the cause*.
>
> **Since** every problem is a lesson, we ran a *post-mortem*, **which** is basically a meeting **where** the whole team talks through what went wrong. The engineer **whose** job it was to watch the servers wasn't to blame — **the real issue was that** our process had a gap. **Consequently**, we agreed on a new rule: **if** anything critical **changes**, an alert **has to be set up** first.
>
> *Thanks to* that experience, the team is much sharper now. **The problem with** *firefighting* all the time is that you never *get ahead of* things. **Because of** this incident, we've started doing regular reviews **so that** small issues get caught before they *blow up*. **What we could do** next is automate the whole thing, **so** nobody has to check manually.
>
> **At the end of the day**, most problems *come down to* one of two things: either something wasn't set up properly, or nobody was watching. **So** my advice is simple — **since** you can't prevent every issue, at least make sure that **when** something breaks, you find out fast, **so that** you can *nip it in the bud* before it turns into a real headache.

### 📖 Bản dịch

> Để tôi kể cho bạn nghe một vấn đề bọn tôi gặp tuần trước — nguyên nhân là gì, nó dẫn tới cái gì, và bọn tôi xử lý ra sao.
>
> Thứ Hai tuần trước, website của khách hàng bị sập khoảng một tiếng. Nó sập vì một máy chủ của bọn tôi hết bộ nhớ. Lý do là một tác vụ nền, cái mà chẳng ai đụng tới suốt mấy tháng, tự dưng bắt đầu ngốn tài nguyên. Vì bọn tôi chưa cài cảnh báo tử tế, nên không phát hiện ra cho tới khi khách bắt đầu than phiền. Hậu quả là đơn hàng không xử lý được một lúc, nên khách mất kha khá doanh thu.
>
> Và vì trang bị sập ngay đợt sale, thời điểm không thể tệ hơn. Khách bực, mà đúng là phải bực — khi bạn trả tiền cho một dịch vụ, bạn mong nó cứ thế chạy được. Do sự cố, bọn tôi phải gửi lời xin lỗi và bù cho họ ít tín dụng, hơi xót. Nhưng nói vậy thôi, sự thẳng thắn lại có kết quả tốt: vì bọn tôi trung thực về nguyên nhân, khách hóa ra còn tin tưởng bọn tôi hơn sau đó.
>
> Nguyên nhân gốc là rò rỉ bộ nhớ. Vì đoạn code được viết từ nhiều năm trước bởi một người đã rời công ty, nên chẳng ai thật sự hiểu nó. Do thiếu tài liệu, bọn tôi mất mấy tiếng chỉ để truy ra vấn đề. Giá mà bọn tôi có hệ thống giám sát tốt hơn thì đã phát hiện sớm hơn nhiều rồi — nhưng chuyện đó qua rồi.
>
> Đây là cách bọn tôi xử lý. Đầu tiên, máy chủ được khởi động lại để trang có thể chạy lại ngay. Rồi tác vụ lỗi bị vô hiệu hóa nhằm chặn nó sập lần nữa. Bọn tôi làm vậy để khách không mất thêm đơn nào trong lúc điều tra. Nhờ đó, trong vòng một tiếng, mọi thứ chạy lại bình thường.
>
> Nhưng vá tạm không phải là sửa thật. Lý do bọn tôi đào sâu hơn là vì không muốn nó tái diễn. Nên trong hai ngày sau đó, bọn tôi viết lại tác vụ để nó giải phóng bộ nhớ đúng cách. Bọn tôi cũng cài cảnh báo để bắt sớm loại sự cố này. Nhờ những thay đổi đó, hệ thống giờ ổn định hơn hẳn. Đó là lý do tôi luôn nói: đừng chỉ chữa triệu chứng — hãy chữa tận gốc.
>
> Vì mỗi vấn đề là một bài học, bọn tôi tổ chức một buổi rút kinh nghiệm, tức là một cuộc họp mà cả nhóm cùng mổ xẻ xem đã sai ở đâu. Anh kỹ sư mà nhiệm vụ là theo dõi máy chủ không đáng bị trách — vấn đề thật sự là quy trình của bọn tôi có lỗ hổng. Vì thế, bọn tôi thống nhất một quy tắc mới: nếu có gì quan trọng thay đổi, phải cài cảnh báo trước.
>
> Nhờ trải nghiệm đó, cả nhóm giờ nhạy bén hơn nhiều. Cái dở của việc suốt ngày chữa cháy là bạn chẳng bao giờ đi trước được vấn đề. Vì vụ việc này, bọn tôi bắt đầu rà soát định kỳ để bắt các lỗi nhỏ trước khi chúng bùng lên. Việc tiếp theo bọn tôi có thể làm là tự động hóa toàn bộ, để không ai phải kiểm tra thủ công.
>
> Suy cho cùng, phần lớn vấn đề quy về một trong hai thứ: hoặc cái gì đó không được cài đặt đúng, hoặc chẳng ai canh chừng. Nên lời khuyên của tôi đơn giản thôi — vì bạn không thể ngăn mọi sự cố, thì ít nhất hãy đảm bảo khi có gì hỏng, bạn biết ngay, để dập nó từ trong trứng trước khi nó thành chuyện đau đầu thực sự.

---

## 🔍 Part 2 — Analysis

*(giải nghĩa hết mọi mục được highlight ở trên)*

### Grammar

**Cause linkers `[nguyên nhân]`** — trả lời "Tại sao?" · *because / since / as* + **mệnh đề** (S + V); *due to / because of* + **danh từ**
- *"It went down **because** one of our servers ran out of memory."* (because + mệnh đề)
- *"**Since** we hadn't set up alerts, we didn't notice."* (since = vì, đầu câu)
- *"**Due to** the outage, we had to apologise."* / *"**Because of** this incident, we've started…"* (+ danh từ)
- ⚠️ **because** đi với mệnh đề, **because of / due to** đi với danh từ. Người Việt hay nói ~~"because of it happened"~~ → sai; phải *"because it happened"* HOẶC *"because of it"*.

**Result linkers `[kết quả]`** — trả lời "Rồi sao?" · *so / so … that / therefore / as a result / consequently / that's why*
- *"…**so** the client lost a fair bit of revenue."* (so = nên, nối 2 mệnh đề)
- *"**As a result**, orders couldn't be processed."* / *"**As a result of** those changes, the system is stable."*
- *"**Therefore**, everything was running normally."* / *"**Consequently**, we agreed on a new rule."* (trang trọng, thường đứng đầu câu + dấu phẩy)
- ⚠️ *therefore / as a result / consequently* KHÔNG nối 2 mệnh đề bằng dấu phẩy như *so*. Viết: *"…memory. **Therefore**, we…"* (chấm rồi mới therefore), KHÔNG *"…memory, therefore we…"*.

**Purpose linkers `[mục đích]`** — trả lời "Để làm gì?" · *to + V / in order to + V / so that + S + can/will/would*
- *"We set up alerts **to** catch this early."* (to + V — gọn nhất)
- *"The job was disabled **in order to** stop it crashing."* (in order to — trang trọng hơn)
- *"…**so that** it releases memory properly."* / *"…**so that** the client wouldn't lose orders."* (so that + cả mệnh đề)
- ⚠️ Đừng dịch "để" thành ~~"for + V-ing"~~: "để bắt lỗi" là *"**to** catch"*, KHÔNG ~~"for catching"~~. Dùng *for + N* (for safety) nhưng *to + V* (to catch).

**🔁 Ôn Week 3 — Passive · Conditional · Relative** *(lồng quanh trục nhân–quả)*
- **Passive** (Day 15) — khi tác nhân không quan trọng: *"the server **was restarted**"*, *"the code **had been written** years ago"*, *"an alert **has to be set up** first."*
- **Conditional** (Day 19 + 3rd cond): *"**If we'd had** better monitoring, **we would have caught** it sooner"* (điều kiện loại 3, tiếc nuối quá khứ) · *"**If** anything critical **changes**, an alert has to be set up"* (loại 1, quy tắc).
- **Relative clause** (Day 16): *"a job, **which** nobody had touched"* · *"someone **who** had left"* · *"a meeting **where** the team talks"* · *"the engineer **whose** job it was."*

### Sentence templates

- **The reason (why) [clause] was that [clause]** = Lý do (mà)… là vì… → *The reason it failed was that no one tested it.*
- **The issue / root cause was [N/that-clause]** = Vấn đề / nguyên nhân gốc là… → *The root cause was a config error.*
- **As a result of [N], [clause]** = Do/nhờ…, nên… → *As a result of the delay, we missed the deadline.*
- **…so that [S + can/won't/would] [V]** = …để [ai đó] có thể / không phải… → *I labelled it so that everyone can find it.*
- **The problem with [N/V-ing] is that [clause]** = Cái dở của… là… → *The problem with rushing is that you miss things.*
- **What we could do is [V]** = Việc mình có thể làm là… → *What we could do is add a backup.*

### Phrases & idioms

### run out (of) /rʌn aʊt/ = hết (tài nguyên/bộ nhớ) `[không tách]`
- The server ran out of memory. / We've run out of time.

### eat up /iːt ʌp/ = ngốn, chiếm hết (tài nguyên/thời gian) `[tách]`
- The job was eating up resources. / Meetings eat up my whole day.

### track down /træk daʊn/ = truy ra, lần ra (nguồn gốc) `[tách]`
- It took hours to track down the bug. / We finally tracked it down.

### pay off /peɪ ɒf/ = mang lại kết quả tốt, đáng công `[tự thân]`
- Being honest paid off. / All that testing paid off.

### get ahead of /ɡet əˈhed əv/ = đi trước, chủ động chặn trước (vấn đề) `[không tách]`
- We need to get ahead of these issues. / You can't get ahead of it by firefighting.

### blow up /bləʊ ʌp/ = bùng lên, phình thành chuyện lớn `[tự thân]`
- Small bugs blow up if you ignore them. / It blew up into a real crisis.

### come down to /kʌm daʊn tuː/ = quy về, cốt ở `[không tách]`
- It all comes down to monitoring. / Most problems come down to process.

### treat the symptom (not the cause) /triːt ðə ˈsɪmptəm/ = chữa triệu chứng (chứ không chữa gốc)
- A restart just treats the symptom. / Don't treat the symptom — treat the cause.

### water under the bridge /ˈwɔːtər ˈʌndə ðə brɪdʒ/ = chuyện đã qua, bỏ qua đi
- We lost a day, but that's water under the bridge now.

### nip (sth) in the bud /nɪp ɪn ðə bʌd/ = dập tắt từ trong trứng, chặn sớm
- Catch it early and nip it in the bud. / We nipped the issue in the bud.

### rightly so /ˈraɪtli səʊ/ = và đúng là nên vậy, quả có lý
- The client was upset, and rightly so.

### at the end of the day /ət ði end əv ðə deɪ/ = suy cho cùng, nói gì thì nói
- At the end of the day, it comes down to people.

### Vocabs & collocations

- **the root cause** /ðə ruːt kɔːz/ (n phr) = nguyên nhân gốc rễ → *We need to find the root cause, not just patch it.*
- **an outage** /ən ˈaʊtɪdʒ/ (n) = sự cố ngừng dịch vụ, sập hệ thống → *The outage lasted an hour.*
- **a memory leak** /ə ˈmeməri liːk/ (n phr) = rò rỉ bộ nhớ → *A memory leak crashed the server.*
- **a post-mortem** /ə pəʊst ˈmɔːtəm/ (n) = buổi mổ xẻ / rút kinh nghiệm sau sự cố → *We ran a post-mortem the next day.*
- **firefighting** /ˈfaɪəfaɪtɪŋ/ (n) = việc chữa cháy, xử lý sự cố gấp liên tục → *We're always firefighting instead of planning.*
- **lose a fair bit of [N]** /feə bɪt/ (collocation) = mất kha khá… → *They lost a fair bit of revenue.*

---

## 🧠 Part 3 — Think Like an American

**1. Tách bạch 3 câu hỏi: "Tại sao? / Rồi sao? / Để làm gì?"**
Người bản xứ dựng một câu chuyện vấn đề theo đúng 3 nhịp này, và mỗi nhịp có bộ linker riêng. 🧠 Đừng dùng "so" cho tất cả.
- **Tại sao** (nguyên nhân) → *because / since / due to*.
- **Rồi sao** (kết quả) → *so / as a result / therefore*.
- **Để làm gì** (mục đích) → *to / so that*.
Nói được ba tầng này là câu chuyện của bạn nghe "có logic" ngay.

**2. "Vì" trong tiếng Việt tách làm hai trong tiếng Anh: + mệnh đề hay + danh từ?**
Đây là bẫy kinh điển. 🧠 Sau nó là cả một mệnh đề (có chủ ngữ + động từ) → **because / since**. Sau nó chỉ là một danh từ → **because of / due to**.
- "Vì trời mưa" (mệnh đề) → **"because it rained"**.
- "Vì mưa" (danh từ) → **"because of the rain / due to the rain"**.

**3. "Để" gần như luôn là "to + V", không phải "for + V-ing".**
Lỗi người Việt hay mắc nhất về mục đích. 🧠 "Tôi làm X để đạt Y" → **"I do X to get Y"**.
- "Tôi ghi chú lại để nhớ" → ✅ **"I write it down to remember"**, ❌ ~~"for remember / for remembering"~~.
- Chỉ dùng *for + N*: **"for safety", "for backup"**.

**4. Khi review Week 3: passive để giấu tác nhân, relative để gộp câu.**
🧠 Thay vì "someone restarted the server" (ai làm không quan trọng) → **"the server was restarted"**. Thay vì hai câu cụt "We ran a post-mortem. It's a meeting where…" → gộp bằng relative: **"a post-mortem, which is a meeting where…"**. Nghe trưởng thành, không lặp.

> 🎯 Tip vàng: khi trình bày sự cố ở công ty, cấu trúc "vàng" của tech lead là bốn nhịp — **Problem → Cause → Impact → Fix**: *"The site went down (**problem**) **because** a job leaked memory (**cause**), **so** orders failed (**impact**). We restarted it and rewrote the job **so that** it won't recur (**fix**)."* Nhớ khung này là bạn báo cáo bug bằng tiếng Anh cực gọn và chuyên nghiệp.

---

## ➕ Part 4 — Expansion *(mới, không có trong bài)*

### Sentence templates

- **It all stems from [N]** 🔵 = Tất cả bắt nguồn từ… → *It all stems from a lack of testing.*
- **This led to [N] / led to [S] [V-ing]** 🟢 = Điều này dẫn tới… → *The bug led to us losing data.*
- **[N] is to blame for [N]** 🔵 = … là thủ phạm của… → *A config error is to blame for the crash.*
- **The knock-on effect was [N]** 🟣 = Hệ quả dây chuyền là… → *The knock-on effect was a full outage.*
- **We ended up [V-ing] because [clause]** 🟢 = Bọn tôi rốt cuộc… vì… → *We ended up rolling back because it broke everything.*
- **The whole point of [N] is to [V]** 🔵 = Toàn bộ mục đích của… là để… → *The whole point of alerts is to warn us early.*
- **If it weren't for [N], [clause]** 🟣 = Nếu không nhờ/vì…, thì… → *If it weren't for the backup, we'd have lost everything.*
- **That's precisely why [clause]** 🔵 = Đó chính xác là lý do… → *That's precisely why we automated it.*
- **The best way to prevent [N] is to [V]** 🟢 = Cách tốt nhất để ngăn… là… → *The best way to prevent this is to test early.*
- **On the off chance (that) [clause]** 🟣 = Phòng khi/lỡ mà… → *We kept a backup on the off chance it failed.*

### Phrases & idioms

### iron out /ˈaɪən aʊt/ 🔵 = xử lý/gỡ nốt (những trục trặc còn lại) `[tách]`
- We still need to iron out a few bugs.

### sort out /sɔːt aʊt/ 🟢 = giải quyết ổn thỏa `[tách]`
- We sorted the issue out in an hour.

### get to the bottom of /ˈbɒtəm/ 🔵 = tìm cho ra ngọn ngành `[không tách]`
- I want to get to the bottom of this crash.

### snowball /ˈsnəʊbɔːl/ 🟣 = phình to như quả cầu tuyết, ngày càng nghiêm trọng
- A tiny bug can snowball into an outage.

### a knock-on effect /nɒk ɒn ɪˈfekt/ 🟣 = hiệu ứng dây chuyền
- The delay had a knock-on effect on the whole release.

### a quick fix /kwɪk fɪks/ 🔵 = giải pháp vá tạm
- A quick fix won't hold for long.

### a stopgap /ˈstɒpɡæp/ 🟣 = biện pháp chắp vá tạm thời
- It's just a stopgap until the real fix.

### buy some time /baɪ sʌm taɪm/ 🔵 = câu giờ, kéo dài thời gian
- Restarting bought us some time to investigate.

### back to square one /bæk tə skweə wʌn/ 🟣 = quay về vạch xuất phát
- The patch failed, so we're back to square one.

### the last straw /ðə lɑːst strɔː/ 🟣 = giọt nước tràn ly
- The third outage was the last straw.

### Vocabs & collocations

- **a workaround** /ə ˈwɜːkəraʊnd/ (n) 🔵 = giải pháp lách tạm thời → *We used a workaround for now.*
- **a bottleneck** /ə ˈbɒtlnek/ (n) 🔵 = nút thắt cổ chai, điểm nghẽn → *The database is the bottleneck.*
- **a workaround vs. a fix** — **a fix** /fɪks/ (n) 🟢 = bản sửa thật sự → *We shipped a proper fix.*
- **downtime** /ˈdaʊntaɪm/ (n) 🔵 = thời gian ngừng hoạt động → *We kept downtime to a minimum.*
- **root-cause analysis** /ruːt kɔːz əˈnæləsɪs/ (n phr) 🔵 = phân tích nguyên nhân gốc → *We did a root-cause analysis.*
- **a recurring issue** /rɪˈkɜːrɪŋ/ (adj+n) 🔵 = vấn đề lặp đi lặp lại → *This is a recurring issue.*
- **preventable** /prɪˈventəbl/ (adj) 🔵 = có thể phòng tránh được → *The whole thing was preventable.*
- **a mitigation** /ˌmɪtɪˈɡeɪʃn/ (n) 🟣 = biện pháp giảm nhẹ → *We put a mitigation in place.*
- **culprit** /ˈkʌlprɪt/ (n) 🟣 = thủ phạm (nguyên nhân) → *The culprit was an old script.*
- **fault-tolerant** /fɔːlt ˈtɒlərənt/ (adj) 🟣 = có khả năng chịu lỗi → *We made the system more fault-tolerant.*

---

## 🎙️ Part 5 — Other Speeches *(cùng grammar, khác tình huống — đọc thêm)*

### Speech B — Why my morning commute keeps going wrong (an everyday problem)

> Let me tell you why I've started leaving the house earlier. **Because** the metro **is being upgraded**, half the lines are shut, **so** the trains are packed. **Due to** the crowds, I often can't get on the first one, **which** means I'm late. **As a result**, I've missed two standups this month.
>
> **The real reason** it stresses me out **is that** my day starts badly. **Since** I hate rushing, I've changed my routine **in order to** get ahead of it. **If** it **rains**, I leave even earlier, **because** the roads get worse. I've also started cycling part of the way **so that** I don't rely on one line. **Thanks to** that, my mornings are far calmer.
>
> **The problem with** blaming the metro **is that** it doesn't help me. **So** I've focused on what I can control. **At the end of the day**, most of my stress *came down to* poor planning, not bad luck. **What I could do** next is work from home on the worst days, **so** I skip the commute entirely. A small change, but it *nipped the whole thing in the bud*.

### Speech C — A recurring bug and how we finally killed it

> We had a bug **that** drove the whole team crazy. Every few days, the app **would crash** for no clear reason. **Because** it happened randomly, it was almost impossible to *track down*. **Since** we couldn't reproduce it, we kept *treating the symptom* — a restart here, a patch there — but it always came back.
>
> **The turning point was** when an engineer, **whose** curiosity saved us, noticed a pattern. **It turned out** the crash **was triggered** by a rare input, **which** nobody had tested. **Because of** that one clue, we finally *got to the bottom of it*. **If we'd logged** the inputs from the start, **we'd have found** it months earlier — but *that's water under the bridge*.
>
> We rewrote the code **so that** bad input **is rejected** safely, and we added tests **in order to** catch it next time. **As a result**, the app hasn't crashed since. **The lesson** was clear: **since** random bugs never fix themselves, you have to dig for the *root cause*. Otherwise a small *glitch* just *snowballs*, and one day it becomes *the last straw*.

---

## 🎤 Your turn

1. **Đọc to** Part 1 (và Speech B/C) → nhờ coach chấm phát âm & độ trôi chảy (Mode 5). Chú ý âm cuối trong *caused, restarted, disabled* và ngữ điệu ngắt sau *Therefore, / As a result,*.
2. **Kể một vấn đề thật** (ở công ty hoặc đời thường) theo khung **Problem → Cause → Impact → Fix**: nêu vấn đề, dùng linker nguyên nhân (*because/since/due to*), linker kết quả (*so/as a result/therefore*), và linker mục đích (*to/so that*) cho phần khắc phục. Lồng ít nhất **1 câu passive**, **1 câu conditional**, **1 relative clause** (ôn Week 3). Dùng ≥5 item ở Part 2/4.

→ Xong nói **"next"** để qua Day 22 (Opinions with nuance — Week 4), hoặc **"review"** để luyện lại Day 21.
