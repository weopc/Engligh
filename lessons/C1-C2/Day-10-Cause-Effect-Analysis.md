# 📅 Day 10 — Cause-Effect Analysis

🎯 **Target grammar:** Causal verbs & phrases — direction matters: *effect ← cause* (**stems from, is driven by, is a byproduct of, can be traced back to**) vs *cause → effect* (**gives rise to, leads to, brings about**) vs *chain / knock-on effects* (**has a knock-on effect, sets off, which, in turn, …**).
*Cuối buổi bạn sẽ nói được: phân tích nguyên nhân — hệ quả một cách mạch lạc, chuyên nghiệp, tách được đâu là gốc rễ, đâu là hệ quả dây chuyền.*

> **Quy ước:** **in đậm** = ngữ pháp / mẫu câu · *in nghiêng* = phrase/idiom/vocab đáng học (giải nghĩa hết ở Part 2, kèm IPA). Từ cơ bản để trơn.

---

## 🗣️ Part 1 — The Speech *(đọc to 1–2 lần)*

> I want to talk about something every consultant eventually has to reckon with: why projects go wrong — and, more importantly, how to trace a problem back to its actual source rather than the nearest symptom.
>
> When a delivery starts to *slip*, the instinct is to blame whatever's closest. A missed deadline gets *pinned on* the developers; a buggy release gets *pinned on* QA. But more often than not, the real issue **stems from** a decision taken months earlier — usually a scope that was never properly *nailed down*. What looks like a technical failure frequently **is driven by** an organisational one. In other words, the *root cause* and the visible symptom are rarely the same thing.
>
> Take technical debt. Most people treat it as a coding problem, but I'd argue it **is a byproduct of** pressure — the pressure to ship fast, to *cut corners*, to keep a client happy who wants everything yesterday. Each shortcut looks *harmless* in isolation. The trouble is that these shortcuts **compound**. One rushed module **gives rise to** a fragile dependency, which **in turn** makes the next feature harder to build, and that **has a knock-on effect** on the entire roadmap. Before you know it, a small compromise **has snowballed into** a systemic problem.
>
> This is why I'm wary of *quick fixes*. A quick fix treats the symptom; it very rarely **addresses the underlying cause**. Worse, it can **set off** a whole chain of unintended consequences. You patch one thing, and three weeks later something *seemingly unrelated* breaks. The two are connected — you just couldn't see the thread at the time.
>
> So how do I approach it? I try to keep asking "why" until the answers stop changing. If a release keeps failing, the first "why" gives you a symptom. The second gives you a process gap. The third, more often than not, **can be traced back to** how the team was set up in the first place — under-resourced, or *pulled in too many directions*. That final layer is where the *leverage* is. Fix things there and the effects **ripple outward** on their own.
>
> There's a *flip side* to this, though. You can over-analyse. Not every problem **is rooted in** some deep structural flaw — sometimes a bug is just a bug. Part of the skill is knowing when a cause is worth *chasing down* and when you're *overthinking it*. Experience is largely learning to tell the two apart.
>
> The way I'd sum it up is this: effects are loud and causes are quiet. The symptom shouts at you — the deadline, the outage, the *frustrated* client. The cause sits underneath, saying nothing. If you only ever react to what's shouting, you'll be *firefighting* forever. The real value we add as leaders is going quiet enough to hear the cause — and having the discipline to fix *that*, even when everyone's pointing at the noise.

### 📖 Bản dịch

> Tôi muốn nói về một điều mà bất kỳ người tư vấn nào rồi cũng phải đối mặt: tại sao các dự án đi sai hướng — và quan trọng hơn, làm sao truy ngược một vấn đề về đúng gốc rễ của nó thay vì cái triệu chứng gần nhất.
>
> Khi một dự án bắt đầu trễ tiến độ, phản xạ là đổ lỗi cho cái gì gần nhất. Trễ deadline thì đổ cho lập trình viên; bản build lỗi thì đổ cho QA. Nhưng phần lớn thời gian, vấn đề thật sự bắt nguồn từ một quyết định đưa ra từ mấy tháng trước — thường là một phạm vi công việc chưa bao giờ được chốt cho rõ ràng. Cái trông có vẻ là lỗi kỹ thuật thường thực chất lại do một lỗi tổ chức gây ra. Nói cách khác, nguyên nhân gốc và triệu chứng nhìn thấy hiếm khi là cùng một thứ.
>
> Lấy nợ kỹ thuật làm ví dụ. Đa số coi nó là vấn đề code, nhưng tôi cho rằng nó là hệ quả phụ của áp lực — áp lực phải giao nhanh, phải cắt xén, phải làm hài lòng một khách hàng muốn mọi thứ ngay hôm qua. Mỗi lần đi tắt trông có vẻ vô hại khi đứng riêng. Vấn đề là những lần đi tắt đó tích lũy dồn lại. Một module làm vội sinh ra một dependency mong manh, cái đó đến lượt nó lại khiến tính năng tiếp theo khó làm hơn, và điều đó tạo hiệu ứng dây chuyền lên toàn bộ lộ trình. Chưa kịp nhận ra thì một sự nhượng bộ nhỏ đã phình thành một vấn đề mang tính hệ thống.
>
> Đây chính là lý do tôi cảnh giác với các giải pháp chắp vá. Giải pháp chắp vá xử lý triệu chứng; nó rất hiếm khi giải quyết được nguyên nhân bên dưới. Tệ hơn, nó có thể kích hoạt cả một chuỗi hệ quả ngoài ý muốn. Bạn vá một chỗ, và ba tuần sau một thứ tưởng chừng chẳng liên quan lại hỏng. Hai cái đó có liên hệ với nhau — chỉ là lúc đó bạn không thấy được sợi dây nối.
>
> Vậy tôi tiếp cận thế nào? Tôi cứ hỏi "tại sao" cho tới khi các câu trả lời không đổi nữa. Nếu một bản release cứ hỏng, chữ "tại sao" đầu tiên cho bạn một triệu chứng. Cái thứ hai cho bạn một lỗ hổng quy trình. Cái thứ ba, phần lớn thời gian, có thể truy ngược về việc đội ngũ được tổ chức thế nào ngay từ đầu — thiếu nguồn lực, hoặc bị kéo đi quá nhiều hướng. Cái lớp cuối cùng đó mới là nơi có đòn bẩy. Sửa ở đó thì các hệ quả sẽ tự lan ra.
>
> Tuy vậy cũng có mặt trái. Bạn có thể phân tích quá đà. Không phải vấn đề nào cũng bắt rễ từ một khiếm khuyết cấu trúc sâu xa nào đó — đôi khi một cái bug chỉ là một cái bug. Một phần của kỹ năng là biết khi nào một nguyên nhân đáng để truy đuổi và khi nào bạn đang nghĩ quá nhiều. Kinh nghiệm phần lớn là học cách phân biệt hai điều đó.
>
> Cách tôi tóm lại là thế này: hệ quả thì ồn ào còn nguyên nhân thì im lặng. Triệu chứng gào vào mặt bạn — cái deadline, sự cố sập hệ thống, ông khách hàng bực bội. Nguyên nhân nằm bên dưới, chẳng nói gì. Nếu bạn chỉ luôn phản ứng với cái đang gào, bạn sẽ đi chữa cháy mãi mãi. Giá trị thật mà chúng ta tạo ra với tư cách người lãnh đạo là đủ tĩnh lặng để nghe được nguyên nhân — và có kỷ luật để sửa chính cái đó, ngay cả khi mọi người đang chỉ tay vào chỗ ồn ào.

---

## 🔍 Part 2 — Analysis

*(giải nghĩa hết mọi mục được highlight ở trên)*

### Grammar — Causal language, split by DIRECTION

> **1. Effect ← Cause** (chủ ngữ là HỆ QUẢ, chỉ ngược về nguyên nhân)
> - *"the real issue **stems from** a decision taken months earlier"*
> - *"it **is a byproduct of** pressure"* · *"the third **can be traced back to** how the team was set up"* · *"not every problem **is rooted in** some deep structural flaw"*
> - ⚠️ **stem from / result from** KHÔNG có bị động: nói *"the issue stems from…"*, KHÔNG nói ~~"is stemmed from"~~. Ngược lại **is driven by / is rooted in / is a byproduct of** thì LUÔN ở dạng bị động (có *is + by/of*).

> **2. Cause → Effect** (chủ ngữ là NGUYÊN NHÂN, đẩy tới hệ quả)
> - *"One rushed module **gives rise to** a fragile dependency"*
> - *"it can **set off** a whole chain of unintended consequences"*
> - ⚠️ Sau **give rise to / lead to** phải là DANH TỪ hoặc V-ing, không phải nguyên mẫu: *"leads to confusion / to failing"*, KHÔNG ~~"leads to fail"~~. Người Việt hay quên chữ *to* này.

> **3. Chain / knock-on effects** (hệ quả dây chuyền, nối tiếp)
> - *"which **in turn** makes the next feature harder"* · *"that **has a knock-on effect** on the entire roadmap"*
> - *"a small compromise **has snowballed into** a systemic problem"* · *"the effects **ripple outward** on their own"*
> - ⚠️ **which / that in turn** phải nối vào cả mệnh đề trước (dùng dấu phẩy + which), không tách thành câu cụt: *"…a fragile dependency, which in turn makes…"* — đây là relative clause chỉ hệ quả, không phải câu mới.

### Sentence templates

- **X stems from Y** = X bắt nguồn từ Y → *The delay stems from unclear requirements.*
- **X is (largely) driven by Y** = X (phần lớn) do Y thúc đẩy → *Burnout is largely driven by unrealistic timelines.*
- **X gives rise to Y, which in turn Z** = X sinh ra Y, cái mà đến lượt nó lại Z → *One outage gives rise to alerts, which in turn overload the on-call engineer.*
- **X has a knock-on effect on Y** = X gây hiệu ứng dây chuyền lên Y → *A late API has a knock-on effect on every downstream team.*
- **X can be traced back to Y** = X có thể truy ngược về Y → *Most of our incidents can be traced back to config drift.*
- **What looks like X is (often) really Y** = Cái trông như X thật ra (thường) là Y → *What looks like a people problem is often really a process problem.*

### Phrases & idioms

**slip** /slɪp/ = trễ tiến độ, tuột lịch (nói về deadline/dự án) `[tự thân]`
- The timeline started to slip in the second sprint.
- We can't let the release date slip again.

**pin (sth) on (sb)** /pɪn ɒn/ = đổ lỗi cho ai `[tách]`
- Don't pin the outage on the new hire.
- The failure got pinned on the wrong team.

**nail (sth) down** /neɪl daʊn/ = chốt chắc, làm rõ ràng dứt khoát `[tách]`
- We need to nail down the scope before we quote.
- Let's nail the requirements down first.

**cut corners** /kʌt ˈkɔːnəz/ = làm ẩu, cắt xén để tiết kiệm thời gian/chi phí
- They cut corners on testing and paid for it later.
- We never cut corners on security.

**snowball into** /ˈsnəʊbɔːl ˈɪntə/ = phình to dần thành (chuyện lớn) `[không tách]`
- A tiny bug snowballed into a full outage.
- Small delays snowball into missed quarters.

**set off** /set ɒf/ = kích hoạt, châm ngòi (một chuỗi sự việc) `[tách]`
- One bad deploy set off a cascade of failures.
- That comment set off a long debate.

**quick fix** /kwɪk fɪks/ = giải pháp chắp vá, vá tạm
- There's no quick fix for tech debt.
- We slapped a quick fix on it for now.

**address the underlying cause** /əˈdres ðə ˌʌndəˈlaɪɪŋ kɔːz/ = xử lý nguyên nhân sâu xa
- A retro should address the underlying cause, not the symptom.
- We finally addressed the underlying cause of the churn.

**ripple outward** /ˈrɪpl ˈaʊtwəd/ = lan tỏa ra (như gợn sóng)
- One good decision ripples outward across the org.
- The morale boost rippled outward to the whole team.

**chase (sth) down** /tʃeɪs daʊn/ = truy tìm, lần theo cho ra `[tách]`
- I spent all day chasing down the root cause.
- Chase the dependency down before you refactor.

**the flip side** /ðə flɪp saɪd/ = mặt trái, khía cạnh ngược lại
- The flip side of speed is fragility.
- On the flip side, less process means more freedom.

**firefighting** /ˈfaɪəfaɪtɪŋ/ = chữa cháy (liên tục xử lý sự cố gấp)
- We're stuck firefighting instead of building.
- Constant firefighting is a symptom, not a strategy.

### Vocabs & collocations

- **root cause** /ruːt kɔːz/ (n phr) = nguyên nhân gốc rễ → *A good post-mortem finds the root cause.*
- **compound** /kəmˈpaʊnd/ (v) = tích lũy dồn, làm trầm trọng thêm → *Each delay compounds the next.* ⚠️ Động từ nhấn âm 2 /kəmˈpaʊnd/, danh từ nhấn âm 1 /ˈkɒmpaʊnd/.
- **harmless** /ˈhɑːmləs/ (adj) = vô hại → *Each shortcut looks harmless in isolation.*
- **seemingly unrelated** /ˈsiːmɪŋli ˌʌnrɪˈleɪtɪd/ (adj phr) = tưởng như không liên quan → *A seemingly unrelated change broke it.*
- **leverage** /ˈliːvərɪdʒ/ (n) = đòn bẩy, điểm tác động tạo hiệu quả lớn → *That's where the leverage is.* ⚠️ RP đọc /ˈliːv-/ (li:), không phải /lev-/.
- **pulled in too many directions** /pʊld ɪn tuː ˈmeni dɪˈrekʃnz/ (phr) = bị kéo đi quá nhiều hướng, quá tải đa nhiệm → *The team was pulled in too many directions.*
- **overthink (it)** /ˌəʊvəˈθɪŋk/ (v) = nghĩ quá nhiều, phức tạp hóa → *Sometimes a bug is just a bug — don't overthink it.*
- **frustrated** /frʌˈstreɪtɪd/ (adj) = bực bội, bức xúc → *a frustrated client on the call.* ⚠️ RP nhấn âm 2: /frʌˈstreɪtɪd/.

---

## 🧠 Part 3 — Think Like an American

**1. Chọn động từ theo HƯỚNG, đừng dịch máy chữ "do / gây ra".**
Tiếng Việt hầu như chỉ có "do", "gây ra", "dẫn đến" cho mọi tình huống. Tiếng Anh chuyên nghiệp phân biệt rất rõ ai là chủ ngữ:
- Nếu bạn bắt đầu câu bằng **HỆ QUẢ** → dùng động từ "nhìn ngược": *The delay* **stems from / is driven by / can be traced back to** *…*
- Nếu bạn bắt đầu bằng **NGUYÊN NHÂN** → dùng động từ "đẩy tới": *Unclear scope* **leads to / gives rise to** *delay.*
🧠 Trước khi nói, hỏi: "Chủ ngữ của mình là cái nguyên nhân hay cái hậu quả?" Câu trả lời quyết định động từ.

**2. Đừng nói "A gây ra B, B gây ra C, C gây ra D" thành 3 câu rời.**
Người bản xứ nối thành MỘT chuỗi mượt bằng *which, in turn, …*:
- Vietnamese instinct → ❌ *"The bug caused an alert. The alert caused overload. The overload caused a mistake."*
- ✅ *"The bug set off an alert, which in turn overloaded the engineer, and that led to a mistake."*
Một hơi, một mạch — đó là dấu hiệu C1→C2.

**3. Tách "triệu chứng" khỏi "nguyên nhân" ngay trong đầu.**
Người phân tích giỏi luôn nói được: *"That's the symptom; the root cause is underneath."* Tập phản xạ cặp **symptom ↔ root cause** thay vì chỉ nói "vấn đề". Đây là tư duy, không phải từ vựng — nói được cặp này là bạn đang nghĩ như một consultant.

**4. Cẩn thận với bị động của causal verbs.**
🧠 Nhớ 2 nhóm: nhóm *"is + V-ed + by"* (**is driven by, is rooted in, is caused by**) LUÔN bị động; nhóm *stem from / result from / arise from* KHÔNG bao giờ bị động. Nói ~~"is stemmed from"~~ là lỗi kinh điển của người Việt — nghe rất sai.

> 🎯 Tip vàng: khi phân tích một vấn đề, mở đầu bằng câu tách tầng: *"On the surface it looks like X, but it really stems from Y — and that has a knock-on effect on Z."* Chỉ một câu mà thể hiện đủ 3 tầng: bề mặt → gốc rễ → hệ quả dây chuyền. Đó là câu "signature" của người nói C2 khi phân tích nhân-quả.

---

## ➕ Part 4 — Expansion *(mới, không có trong bài)*

### Sentence templates

- **X is largely a function of Y** 🔵 = X phần lớn phụ thuộc vào / là hàm của Y → *Delivery speed is largely a function of clarity, not effort.*
- **There's a direct correlation between X and Y** 🔵 = Có mối tương quan trực tiếp giữa X và Y → *There's a direct correlation between rushed specs and rework.*
- **X, if anything, only makes Y worse** 🟣 = X, nếu có, chỉ càng làm Y tệ hơn → *Adding people, if anything, only makes onboarding worse.*
- **It's no coincidence that X** 🔵 = Không phải ngẫu nhiên mà X → *It's no coincidence that the outages spiked after the layoffs.*
- **X paves the way for Y** 🟣 = X mở đường cho Y → *A clear roadmap paves the way for faster decisions.*
- **Left unchecked, X will [V]** 🟣 = Nếu không kiểm soát, X sẽ… → *Left unchecked, tech debt will grind everything to a halt.*
- **X is symptomatic of Y** 🟣 = X là biểu hiện của Y → *Missed standups are symptomatic of a disengaged team.*
- **The knock-on effect of X is that Y** 🔵 = Hệ quả dây chuyền của X là Y → *The knock-on effect of a late API is that every team stalls.*
- **You can draw a straight line from X to Y** 🟣 = Có thể vạch một đường thẳng từ X tới Y → *You can draw a straight line from poor onboarding to early churn.*
- **X sows the seeds of Y** 🟣 = X gieo mầm cho Y → *Overpromising sows the seeds of client distrust.*

### Phrases & idioms

**a vicious circle** /ə ˈvɪʃəs ˈsɜːkl/ 🔵 = vòng luẩn quẩn (càng xấu càng xấu)
- Firefighting creates more debt — it's a vicious circle.

**a domino effect** /ə ˈdɒmɪnəʊ ɪˈfekt/ 🔵 = hiệu ứng domino
- One resignation triggered a domino effect.

**the tip of the iceberg** /ðə tɪp əv ði ˈaɪsbɜːɡ/ 🔵 = phần nổi của tảng băng
- That bug is just the tip of the iceberg.

**boil down to** /bɔɪl daʊn tuː/ 🔵 = quy về, tựu trung là `[không tách]`
- It all boils down to unclear ownership.

**get to the bottom of** /ɡet tə ðə ˈbɒtəm əv/ 🔵 = tìm ra tận gốc
- We need to get to the bottom of these failures.

**a slippery slope** /ə ˈslɪpəri sləʊp/ 🟣 = con dốc trơn trượt (một bước dẫn tới trượt dài)
- Skipping reviews is a slippery slope.

**come home to roost** /kʌm həʊm tə ruːst/ 🟣 = hậu quả (của lỗi cũ) quay lại đòi nợ
- Those shortcuts have come home to roost.

**a knock-on** /ə ˈnɒk ɒn/ 🔵 = (n) hệ quả kéo theo (dùng như danh từ)
- There's always a knock-on when priorities shift.

**paper over the cracks** /ˈpeɪpər əʊvə ðə kræks/ 🟣 = che đậy vấn đề tạm bợ
- This release just papers over the cracks.

**nip (sth) in the bud** /nɪp ɪn ðə bʌd/ 🟣 = dập tắt từ trong trứng `[tách]`
- We nipped the scope creep in the bud.

### Vocabs & collocations

- **causality** /kɔːˈzæləti/ (n) 🟣 = tính nhân quả, quan hệ nhân-quả → *We're confusing correlation with causality.*
- **a catalyst** /ə ˈkætəlɪst/ (n) 🔵 = chất xúc tác, yếu tố châm ngòi → *The reorg was a catalyst for change.*
- **a trigger** /ə ˈtrɪɡə/ (n) 🟢 = yếu tố kích hoạt → *The failed deploy was the trigger.*
- **a ripple effect** /ə ˈrɪpl ɪˈfekt/ (n phr) 🔵 = hiệu ứng lan tỏa → *Good documentation has a ripple effect.*
- **an unintended consequence** /ən ˌʌnɪnˈtendɪd ˈkɒnsɪkwəns/ (n phr) 🔵 = hệ quả ngoài ý muốn → *Every policy has unintended consequences.*
- **compounding** /kəmˈpaʊndɪŋ/ (adj) 🟣 = tích lũy dồn, lãi kép → *the compounding cost of neglect.*
- **a precursor (to)** /ə priːˈkɜːsə/ (n) 🟣 = dấu hiệu báo trước → *Missed deadlines are a precursor to burnout.*
- **systemic** /sɪˈstemɪk/ (adj) 🔵 = mang tính hệ thống → *This is a systemic issue, not a one-off.* ⚠️ /sɪˈstemɪk/, nhấn âm 2, không phải "systematic".
- **a bottleneck** /ə ˈbɒtlnek/ (n) 🔵 = nút thắt cổ chai → *Review is the real bottleneck.*
- **downstream** /ˌdaʊnˈstriːm/ (adj/adv) 🔵 = ở phía sau trong chuỗi (bị ảnh hưởng) → *This breaks everything downstream.*

---

## 🎙️ Part 5 — Other Speeches *(cùng grammar, khác tình huống — đọc thêm)*

### Speech B — Why good engineers quit

> Let me offer a slightly uncomfortable take: when a strong engineer resigns, the resignation letter is almost never the real story. The stated reason — *"a better offer"* — is the symptom. The *root cause* usually **stems from** something that built up quietly over months.
>
> In my experience, attrition **is driven by** a slow erosion of autonomy far more than by salary. Someone joins to build things; then process piles up, every decision needs three approvals, and their sense of ownership **is chipped away**. That frustration **compounds**. A missed promotion **gives rise to** resentment, which **in turn** kills discretionary effort, and that **has a knock-on effect** on the whole team's energy. By the time they quit, the decision **can be traced back to** a dozen small moments nobody logged.
>
> The tragedy is that most exits **are** entirely *preventable*. They're **a byproduct of** inattention, not malice. Managers **paper over the cracks** with a bonus, but a bonus is a *quick fix* — it doesn't **address the underlying cause**. If you want to **get to the bottom of** attrition, don't read the exit interview; read the six months before it. That's where the *thread* actually starts.
>
> So my advice is simple: treat disengagement as a *precursor*, not a surprise. Notice when someone goes quiet in reviews, when the *spark* fades. **Nip it in the bud.** Because once resignation is on the table, you're **firefighting** — and by then the cause has already done its damage.

### Speech C — Why our estimate was wrong (a post-mortem)

> I want to walk through why we *blew past* our estimate on the last project, because the honest answer is more interesting than "we were optimistic."
>
> On the surface, the overrun **looks like** a scoping error. And partly it was. But dig one layer down and the real issue **stems from** how we gathered requirements — over email, in fragments, with no single owner. That gap **gave rise to** a hundred small assumptions, each of which felt *harmless*. Then those assumptions **snowballed into** rework. One misread requirement **set off** a redesign, which **rippled outward** into testing, which **had a knock-on effect** on the launch date.
>
> Here's the part I'd flag: none of this **was** *systemic* bad luck. It **can be traced back to** a single decision — skipping the discovery workshop to *"save a week."* That's a textbook *slippery slope*. We saved a week upfront and lost a month downstream. Those shortcuts **came home to roost**.
>
> What I'd change is this. Next time we'll **nail down** scope in a room, with one owner, before a line of code is written. It's slower at the start, but it **paves the way for** a *predictable* delivery. The lesson, really, is the one we keep relearning: causes are quiet and cheap early; hideously expensive late.

---

## 🎤 Your turn

1. **Đọc to** Part 1 (và Speech B/C) → nhờ coach chấm phát âm & độ trôi chảy (Mode 5).
2. **Chọn một vấn đề thật ở dự án của bạn** rồi phân tích thành 3 tầng: *symptom → root cause → knock-on effect*, dùng ≥5 causal verb/phrase ở Part 2/4 và ít nhất một chuỗi *which, in turn, …*.

→ Xong nói **"next"** để qua Day 11 (What-if reasoning), hoặc **"review"** để luyện lại Day 10.
