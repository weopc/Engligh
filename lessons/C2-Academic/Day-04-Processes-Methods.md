# 📅 Day 4 — Describing Processes & Methods

🎯 **Target grammar:** Passive voice for objective method (agentless passive, passive with *by*, present vs past passive, modal passive) · sequence & staging language (*following which, at which point, once … has been done*). Register: measured spoken academic prose.
*Cuối buổi bạn sẽ nói được: trình bày một quy trình/phương pháp một cách khách quan, trung tính, đúng kiểu học thuật — nói rõ "cái gì được làm", không cần nói "ai làm".*

> **Quy ước:** **in đậm** = ngữ pháp / mẫu câu · *in nghiêng* = phrase/idiom/vocab đáng học (giải nghĩa hết ở Part 2, kèm IPA). Từ cơ bản để trơn.

---

## 🗣️ Part 1 — The Speech *(đọc to 1–2 lần)*

> I want to walk through how a typical evaluation of a software rollout *is conducted*, because the method matters just as much as the result. What I'll describe is a fairly *standardised procedure* — the sort of thing that **is carried out** in most engineering organisations, whether or not it's written down.
>
> First, a *baseline* **is established**. Before any change is introduced, the current behaviour of the system **is measured** — response times, error rates, and so on — so that later comparisons *rest on* something solid. This baseline data **is then recorded** and set aside. *Crucially*, nothing else **is altered** at this stage; the aim is simply to *capture* the system *as it stands*.
>
> Once the baseline **has been established**, the change itself **is introduced**, typically to a small subset of users. This stage **is often referred to** as a *staged rollout*. The new behaviour **is monitored** closely, **following which** the two datasets — before and after — **are compared**. *At no point* is the change released to everyone at once; that would make the effect impossible *to isolate*.
>
> The comparison itself **is performed** using a small number of agreed metrics. Where a difference **is observed**, it **must be checked** against the baseline before any conclusion **is drawn**. It's worth stressing that a difference, on its own, **is not treated** as proof; it **has to be interpreted** *with care*, and it **may well be** explained by something unrelated. This is the point **at which** *rigour* either holds or *breaks down*.
>
> The findings **are then documented** in a short report, which **is circulated** to the team. Any decision to *proceed* **is made** collectively, **following which** the change either **is rolled out** in full or **is rolled back**. Where it **is rolled back**, the reasons **are logged** so that the same *pitfall* **can be avoided** later. Nothing here **is left** to memory; the whole process **is designed** to be *reproducible*.
>
> I should add a *caveat*. No method **is applied** in a *vacuum*. Deadlines *press*, and steps **are sometimes skipped** *under pressure* — I'd be the first to admit it. But the value of a method like this lies precisely in the fact that, when it **is followed** properly, the result **can be trusted** by someone who wasn't in the room. That, *ultimately*, is what *distinguishes* a method from a habit: a method **can be described**, **can be repeated**, and **can be scrutinised** by others. A habit simply happens.
>
> So when I'm asked how we know a change worked, my answer is rarely a single number. It's the process — the sequence of steps **by which** that number **was produced**. Get the method right, and the findings *tend to* look after themselves.

### 📖 Bản dịch

> Tôi muốn trình bày cách một cuộc đánh giá điển hình cho một đợt triển khai phần mềm được tiến hành, bởi phương pháp cũng quan trọng chẳng kém gì kết quả. Cái tôi sắp mô tả là một quy trình khá chuẩn hoá — kiểu quy trình được thực hiện ở hầu hết các tổ chức kỹ thuật, dù có được ghi ra thành văn bản hay không.
>
> Đầu tiên, một mốc chuẩn (baseline) được thiết lập. Trước khi có bất kỳ thay đổi nào, hành vi hiện tại của hệ thống được đo đạc — thời gian phản hồi, tỷ lệ lỗi, v.v. — để những so sánh về sau dựa trên một cái gì đó vững chắc. Dữ liệu baseline này sau đó được ghi lại và để riêng. Điều then chốt là ở giai đoạn này không có gì khác bị thay đổi; mục tiêu chỉ đơn giản là ghi nhận hệ thống ở trạng thái hiện tại.
>
> Một khi baseline đã được thiết lập, bản thân thay đổi mới được đưa vào, thường là cho một nhóm nhỏ người dùng. Giai đoạn này thường được gọi là triển khai theo từng đợt (staged rollout). Hành vi mới được theo dõi sát sao, sau đó hai tập dữ liệu — trước và sau — được đem ra so sánh. Không có thời điểm nào thay đổi được phát hành cho tất cả mọi người cùng lúc; làm vậy sẽ khiến không thể tách bạch được tác động.
>
> Việc so sánh được thực hiện dựa trên một số ít chỉ số đã được thống nhất. Ở đâu quan sát thấy sự khác biệt, nó phải được đối chiếu với baseline trước khi rút ra bất kỳ kết luận nào. Cần nhấn mạnh rằng một sự khác biệt, tự thân nó, không được coi là bằng chứng; nó phải được diễn giải một cách cẩn trọng, và rất có thể được giải thích bởi một yếu tố chẳng liên quan. Đây chính là điểm mà tại đó sự chặt chẽ hoặc là được giữ vững, hoặc là sụp đổ.
>
> Các phát hiện sau đó được ghi lại trong một báo cáo ngắn, rồi được gửi cho cả nhóm. Bất kỳ quyết định tiến hành nào cũng được đưa ra một cách tập thể, sau đó thay đổi hoặc được triển khai toàn bộ, hoặc bị thu hồi. Ở đâu nó bị thu hồi, lý do được ghi lại để cùng một cạm bẫy có thể được tránh về sau. Ở đây không có gì được phó mặc cho trí nhớ; toàn bộ quy trình được thiết kế để có thể tái lập.
>
> Tôi nên nói thêm một lưu ý. Không phương pháp nào được áp dụng trong chân không. Deadline thì luôn ép, và các bước đôi khi bị bỏ qua dưới áp lực — tôi là người thừa nhận điều đó đầu tiên. Nhưng giá trị của một phương pháp như thế này nằm chính ở chỗ: khi nó được tuân thủ đúng cách, kết quả có thể được tin tưởng bởi một người thậm chí không có mặt lúc đó. Đó, xét cho cùng, là cái phân biệt một phương pháp với một thói quen: một phương pháp có thể được mô tả, có thể được lặp lại, và có thể được người khác soi xét. Còn thói quen thì chỉ đơn giản là xảy ra.
>
> Nên khi có ai hỏi tôi làm sao biết một thay đổi có tác dụng, câu trả lời của tôi hiếm khi là một con số duy nhất. Đó là quy trình — chuỗi các bước mà nhờ đó con số ấy được tạo ra. Làm đúng phương pháp, thì các phát hiện có xu hướng tự lo cho chính chúng.

---

## 🔍 Part 2 — Analysis

*(giải nghĩa hết mọi mục được highlight ở trên)*

### Grammar

**Agentless passive** — bỏ chủ thể vì "ai làm" không quan trọng / đã hiển nhiên (đây là xương sống của văn phong học thuật)
- *"the current behaviour of the system **is measured**"*
- *"the findings **are then documented** … **are circulated** to the team"*
- ⚠️ Tiếng Việt hay nói "chúng tôi đo…", "team ghi lại…". Học thuật tiếng Anh cắt "chúng tôi/team" đi: **is measured**, **are documented**. Đừng dịch "chúng tôi" thành *we* — chuyển thẳng sang bị động.

**Passive with *by*** — chỉ giữ chủ thể khi chủ thể mới là thông tin đáng chú ý
- *"the result **can be trusted by** someone who wasn't in the room"*
- *"the sequence of steps **by which** that number **was produced**"*
- ⚠️ Chỉ thêm *by + tác nhân* khi tác nhân thực sự mang thông tin. Thừa *by us / by the team* ở mọi câu là dấu hiệu văn chưa "học thuật".

**Present vs past passive** — hiện tại đơn bị động = quy trình chung, luôn đúng; quá khứ bị động = một lần cụ thể đã xảy ra
- Present (quy trình): *"a baseline **is established**"*, *"the change **is introduced**"*
- Past (một lần cụ thể): *"the number **was produced**"*
- ⚠️ Khi mô tả *phương pháp nói chung* → dùng **hiện tại bị động** (is done), KHÔNG phải quá khứ. Chỉ dùng quá khứ khi kể một lần thực nghiệm đã diễn ra.

**Modal passive** — *must/can/may/has to + be + V3*: diễn đạt bắt buộc, khả năng, cho phép ở thể bị động
- *"it **must be checked** against the baseline"*
- *"the same pitfall **can be avoided**"*, *"it **may well be** explained by something unrelated"*
- ⚠️ Trật tự cố định: modal + **be** + V3. Lỗi phổ biến: bỏ mất *be* (*must checked* ❌ → *must be checked* ✅).

### Sentence templates

- **[N] is/are carried out by [means/agent]** = … được tiến hành bằng/bởi… → *The survey is carried out online.*
- **Once [N] has been [V3], [clause]** = Một khi … đã được…, thì… → *Once the data has been cleaned, it is analysed.*
- **Following which, [N] is/are [V3]** = Sau đó, … được… → *The samples are labelled, following which they are stored.*
- **This is the point at which [clause]** = Đây là thời điểm mà tại đó… → *This is the point at which errors tend to appear.*
- **[N] must be [V3] before any [N] is [V3]** = … phải được… trước khi bất kỳ … nào được… → *The result must be verified before any claim is made.*

### Phrases & idioms

**rest on** /rest ɒn/ = dựa trên, đặt nền tảng trên `[không tách]`
- The argument rests on one key assumption.
- Later comparisons rest on the baseline.

**break down** /breɪk daʊn/ = sụp đổ, đổ vỡ (ở đây: sự chặt chẽ mất đi) `[tự thân]`
- This is where rigour breaks down.
- The negotiation broke down completely.

**look after themselves** /lʊk ˈɑːftə/ = tự lo liệu được, không cần can thiệp thêm `[không tách]`
- Get the method right and the findings tend to look after themselves.

**as it stands** /əz ɪt ˈstændz/ = ở trạng thái hiện tại, y như bây giờ
- We captured the system as it stands.
- As it stands, the data isn't conclusive.

**with care** /wɪð keə/ = một cách cẩn trọng
- These figures must be interpreted with care.

**under pressure** /ˈʌndə ˈpreʃə/ = dưới áp lực
- Steps are sometimes skipped under pressure.

**in a vacuum** /ɪn ə ˈvækjuːm/ = trong sự tách biệt, không có bối cảnh xung quanh
- No method is applied in a vacuum.

### Vocabs & collocations

- **conduct** /kənˈdʌkt/ (v) = tiến hành (nghiên cứu/đánh giá) → *The evaluation is conducted quarterly.* ⚠️ trọng âm động từ rơi vào âm 2: con-**DUCT**; danh từ **CON**-duct.
- **standardised procedure** /ˈstændədaɪzd prəˈsiːdʒə/ (n phr) = quy trình chuẩn hoá → *This follows a standardised procedure.*
- **baseline** /ˈbeɪslaɪn/ (n) = mốc/giá trị chuẩn để so sánh → *We measure against a baseline.*
- **capture** /ˈkæptʃə/ (v) = ghi nhận, nắm bắt (dữ liệu/trạng thái) → *The tool captures every request.*
- **isolate** /ˈaɪsəleɪt/ (v) = tách riêng, cô lập (để phân tích tác động) → *It's hard to isolate the cause.* ⚠️ /ˈaɪ-/ chứ không phải /ˈɪ-/.
- **rigour** /ˈrɪɡə/ (n) = sự chặt chẽ, nghiêm ngặt (học thuật) → *The study lacks methodological rigour.* ⚠️ Anh-Anh viết *rigour*, Anh-Mỹ *rigor*.
- **reproducible** /ˌriːprəˈdjuːsəbl/ (adj) = có thể tái lập → *The results must be reproducible.*
- **caveat** /ˈkæviæt/ (n) = lời lưu ý, điều cần thận trọng → *I'd add one caveat.*
- **pitfall** /ˈpɪtfɔːl/ (n) = cạm bẫy, lỗi dễ mắc → *A common pitfall is over-fitting.*
- **crucially** /ˈkruːʃəli/ (adv) = một cách then chốt → *Crucially, nothing else changed.*
- **ultimately** /ˈʌltɪmətli/ (adv) = xét cho cùng, sau chót → *Ultimately, the method is what matters.*
- **distinguish** /dɪˈstɪŋɡwɪʃ/ (v) = phân biệt → *This distinguishes a method from a habit.*
- **tend to** /tend tuː/ (v phr) = có xu hướng → *Errors tend to appear late.*
- **proceed** /prəˈsiːd/ (v) = tiến hành, tiếp tục → *The decision to proceed is made collectively.* ⚠️ /prəˈsiːd/ — khác *precede* /prɪˈsiːd/ (đứng trước).

---

## 🧠 Part 3 — Think Like an American

**1. Bị động học thuật = "chuyển tiêu điểm từ NGƯỜI sang VIỆC".**
Đây là cú lật tư duy quan trọng nhất hôm nay. Tiếng Việt (và tiếng Anh đời thường) lấy *con người* làm chủ ngữ: "Chúng tôi đo hệ thống", "Team ghi lại kết quả". Văn học thuật lấy *bản thân việc/dữ liệu* làm chủ ngữ, vì ai làm thường không quan trọng bằng cái gì được làm.
- Bản năng tiếng Việt: "Chúng tôi thu thập dữ liệu" → ❌ *We collect the data* (nghe như báo cáo cá nhân) → ✅ *The data is collected*.
- 🧠 Trước mỗi câu mô tả quy trình, tự hỏi: *"Việc gì được làm?"* rồi lấy CHÍNH VIỆC ĐÓ làm chủ ngữ. Người thực hiện biến mất trừ khi họ đáng nhắc tên.

**2. Đừng lạm dụng bị động — nó là công cụ, không phải bộ lọc.**
Người mới học hay nghĩ "học thuật = bị động toàn bộ". Sai. Người bản xứ trộn: bị động cho *các bước quy trình*, chủ động cho *lập luận/quan điểm của mình* ("I want to walk through…", "I should add a caveat"). 🧠 Quy tắc ngón tay cái: **quy trình → bị động; ý kiến/định hướng của người nói → chủ động.**

**3. "Sequence" nói bằng khớp nối, không bằng "and then… and then…".**
Tiếng Việt kể tuần tự rất mộc: "rồi… rồi… sau đó…". Học thuật nâng cấp bằng các khớp nối trang trọng: *following which, once … has been done, at which point, this is then subjected to.* 🧠 Thay phản xạ "and then" bằng một trong các cụm này — câu lập tức "lên đô".
- "Đo xong rồi so sánh" → ❌ *We measure and then we compare* → ✅ *The data is measured, following which the two sets are compared.*

**4. Hiện tại đơn bị động = "quy trình luôn đúng", không phải chuyện quá khứ.**
Khi mô tả *cách làm nói chung*, người bản xứ dùng hiện tại (*is carried out*), như một chân lý lặp lại. Đừng vì "kể lại" mà tự động lùi về quá khứ. 🧠 Hỏi: *"Đây là cách LÚC NÀO cũng làm, hay là một lần CỤ THỂ đã xảy ra?"* → luôn làm = hiện tại; một lần = quá khứ.

> 🎯 Tip vàng: Trong IELTS Writing Task 1 (process diagram) và mọi phần mô tả phương pháp, bị động agentless + khớp nối tuần tự là "công thức vàng". Một câu mẫu bạn nên thuộc lòng: *"Once X has been completed, Y is carried out, following which the results are recorded."* Đổi X/Y/Z là dùng được cho gần như mọi quy trình.

---

## ➕ Part 4 — Expansion *(mới, không có trong bài)*

### Sentence templates

- **[N] is subjected to [N]** 🔵 = … được đưa vào/chịu quá trình… → *Each sample is subjected to rigorous testing.*
- **Prior to [V-ing], [N] is [V3]** 🔵 = Trước khi…, … được… → *Prior to analysis, the data is normalised.*
- **[N] is undertaken with a view to [V-ing]** 🟣 = … được thực hiện nhằm mục đích… → *The study is undertaken with a view to reducing bias.*
- **The procedure can be broken down into [number] stages** 🟢 = Quy trình có thể chia thành … giai đoạn → *The procedure can be broken down into three stages.*
- **At which point, [N] is [V3]** 🔵 = Tại thời điểm đó, … được… → *The threshold is reached, at which point an alert is triggered.*
- **[N] is [V3] so as to [V]** 🔵 = … được… để mà… → *Variables are held constant so as to isolate the effect.*
- **In the first/next/final instance, [N] is [V3]** 🟣 = Ở bước đầu/kế/cuối, … được… → *In the first instance, the raw data is screened.*
- **[N] is derived from [N]** 🔵 = … được suy ra từ… → *The estimate is derived from historical data.*
- **Once [N] is in place, [clause]** 🟢 = Một khi … đã sẵn sàng, thì… → *Once the pipeline is in place, tests run automatically.*
- **[N] is calibrated/validated against [N]** 🟣 = … được hiệu chỉnh/kiểm chứng đối chiếu với… → *The model is validated against a hold-out set.*

### Phrases & idioms

**set out** /set aʊt/ 🔵 = trình bày/bố trí (một cách có hệ thống) `[tách]`
- The steps are set out in the appendix.

**carry out** /ˈkæri aʊt/ 🟢 = thực hiện, tiến hành `[tách]`
- The experiment was carried out over six weeks.

**account for** /əˈkaʊnt fɔː/ 🔵 = lý giải cho, chiếm tỷ lệ `[không tách]`
- This step accounts for most of the delay.

**rule out** /ruːl aʊt/ 🔵 = loại trừ (khả năng) `[tách]`
- We couldn't rule out measurement error.

**hold constant** /həʊld ˈkɒnstənt/ 🟣 = giữ cố định (một biến số)
- All other variables are held constant.

**by the same token** /baɪ ðə seɪm ˈtəʊkən/ 🟣 = cũng theo lẽ đó, tương tự như vậy
- By the same token, the method should apply elsewhere.

**step by step** /step baɪ step/ 🟢 = từng bước một
- The process is explained step by step.

**in turn** /ɪn tɜːn/ 🔵 = lần lượt; kéo theo đó
- Each stage feeds, in turn, into the next.

**from the outset** /frəm ðə ˈaʊtset/ 🟣 = ngay từ đầu
- The criteria were fixed from the outset.

**with hindsight** /wɪð ˈhaɪndsaɪt/ 🟣 = khi nhìn lại (mới thấy)
- With hindsight, an extra control was needed.

### Vocabs & collocations

- **methodology** /ˌmeθəˈdɒlədʒi/ (n) 🔵 = phương pháp luận → *The methodology is described in full.*
- **protocol** /ˈprəʊtəkɒl/ (n) 🔵 = quy trình chuẩn/giao thức → *We followed the standard protocol.*
- **systematic** /ˌsɪstəˈmætɪk/ (adj) 🔵 = có hệ thống → *a systematic review of the evidence.*
- **iterative** /ˈɪtərətɪv/ (adj) 🟣 = lặp đi lặp lại (theo vòng cải tiến) → *We take an iterative approach.*
- **replicate** /ˈreplɪkeɪt/ (v) 🟣 = tái lập, lặp lại (thí nghiệm) → *Other teams failed to replicate the result.*
- **parameter** /pəˈræmɪtə/ (n) 🔵 = tham số, thông số → *We tuned each parameter carefully.* ⚠️ trọng âm âm 2: pa-**RA**-me-ter.
- **variable** /ˈveəriəbl/ (n) 🟢 = biến số → *We controlled for one variable at a time.*
- **threshold** /ˈθreʃhəʊld/ (n) 🔵 = ngưỡng → *Once the threshold is exceeded, it flags.* ⚠️ /θ/ đầu từ + không đọc thành "trết-hôn".
- **incremental** /ˌɪŋkrəˈmentl/ (adj) 🔵 = tăng dần từng chút → *We ship incremental changes.*
- **preliminary** /prɪˈlɪmɪnəri/ (adj) 🔵 = sơ bộ, ban đầu → *These are preliminary findings.*
- **sequential** /sɪˈkwenʃl/ (adj) 🔵 = tuần tự, theo trình tự → *The steps are strictly sequential.*
- **implementation** /ˌɪmplɪmenˈteɪʃn/ (n) 🟢 = việc triển khai/hiện thực hoá → *Implementation is left to the team.*

---

## 🎙️ Part 5 — Other Speeches *(cùng grammar, khác tình huống — đọc thêm)*

### Speech B — How a hiring assessment is designed and run

> Let me describe how a fair hiring assessment **is designed**, because far too often the process **is thrown together** at the last minute. Ideally, the criteria **are agreed** before a single candidate **is seen**. Once those criteria **have been fixed**, a common task **is prepared** — the same task for everyone, so that performances **can be compared** on equal terms. Each submission **is then scored** independently by two reviewers, **following which** the two scores **are reconciled**. Where they diverge sharply, the case **is escalated** and **is discussed** openly, **at which point** a third opinion **may be sought**. *Crucially*, no candidate **is judged** against another in the room; each **is judged** against the fixed *rubric*. The scores **are recorded**, the reasoning **is written down**, and the decision **can later be defended** to anyone who asks. It isn't a *foolproof* system — bias **is never fully eliminated** — but when the steps **are followed**, the outcome **can at least be examined**. That, to me, is the whole point: a decision that **can be scrutinised** is a decision worth trusting.

### Speech C — How an incident is investigated after an outage

> When a system goes down, the temptation is to guess. A better approach is *disciplined*. First, the timeline **is reconstructed** from the logs — what happened, and in what order. Nothing **is assumed**; everything **is checked** against the record. Once the timeline **has been established**, the likely triggers **are identified**, **following which** each one **is either confirmed or ruled out**. The *root cause* **is not declared** until the failure **can be reproduced** on demand — if it can't be reproduced, it isn't understood. **At the point at which** the cause **is confirmed**, a fix **is proposed**, **is reviewed**, and only then **is deployed**. Afterwards, a short write-up **is circulated**, and the lessons **are folded** back into the process so the same failure **can be caught** earlier next time. Blame **is deliberately left out** of it; what **is examined** is the system, not the person. Handled this way, even a bad outage **can be turned into** something useful.

---

## 🎤 Your turn

1. **Đọc to** Part 1 (và Speech B/C) → nhờ coach chấm phát âm & độ trôi chảy (Mode 5). Chú ý các đuôi V3 bị động: *measure**d**, record**ed**, compar**ed*** — phát âm rõ /-t/, /-d/, /-ɪd/.
2. **Chọn một quy trình bạn biết rõ** (deploy, code review, onboarding…) và mô tả nó **hoàn toàn bằng bị động agentless + khớp nối tuần tự**, dùng ≥5 item ở Part 2/4. Tự bắt lỗi nếu lỡ tuồn *we* vào.

→ Xong nói **"next"** để qua Day 5 (Describing data, figures & trends), hoặc **"review"** để luyện lại Day 4.
