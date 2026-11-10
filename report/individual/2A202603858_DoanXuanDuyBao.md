# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Đoàn Xuân Duy Bảo
- MSSV: 2A202603858
- Email trường (không bắt buộc, repo có thể để public): 26ai.baodxd@vinuni.edu.vn
- Tên nhóm: Hihihuhu
- Link repo nhóm:https://github.com/minhh25/K5-L3B-Day02-Hihihuhu-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật (cách kiểm chứng → số ước tính) |
|---|---|---|---|---|
| 1 | Cần đọc, tổng hợp | Khi tới sáng thứ Sáu trước meetup công ty mà agent đã merge hàng trăm thay đổi trong tuần, tôi muốn thấy ngay thay đổi nào thực sự đáng nói, kèm giải thích dễ hiểu và link nguồn, để trình bày chính xác cho cả công ty mà không phải đọc từng PR | EM/tech lead phụ trách phần "tuần này ship gì", leadership và cả công ty dự meetup | Bấm giờ 2 tuần + đếm PR (baseline hiện là ước tính, chưa đo): ~170 phút/tuần/người, ~150-300 PR/tuần, chỉ ~15-25% đáng nói; so với danh sách chuẩn tech lead gắn nhãn tay thì ~20-30% thay đổi quan trọng bị bỏ sót |
| 2 | Lặp lại | Khi nhân sự mới vào làm đầu tuần và cần xin quyền hệ thống, đăng ký nghỉ phép, công tác phí, tôi muốn có câu trả lời đúng theo quy trình hiện hành, để không phải hỏi lại HR/IT trong tuần đầu | Nhân sự mới (30 ngày đầu), HR và IT trực helpdesk | Đếm kênh helpdesk nội bộ 1 tháng: ~120 câu hỏi/tuần, ~60% là câu trùng (~70 câu); ~12 phút/câu (người hỏi + người trả lời) ≈ 24 giờ/tuần; mỗi người mới hỏi 15-20 câu trong tuần đầu |
| 3 | Tốn thời gian | Khi chuẩn bị họp planning thứ Hai và cần nhớ "tại sao chốt phương án này hồi quý trước", tôi muốn thấy ngay quyết định và lý do gốc, để không phải họp lại hay làm lại việc đã quyết | 5 PM/lead chuẩn bị planning, người mới nhận bàn giao | Bấm giờ 2 tuần: ~45 phút/PM/tuần lục lại Slack, Docs, Jira (≈ 15 giờ/tháng cho 5 PM); ~3 lần/tháng phải thảo luận lại chủ đề đã quyết × 5 người × 30 phút ≈ 7,5 giờ/tháng |
| 4 | Tốn thời gian | Khi nhận hợp đồng/NDA/điều khoản từ đối tác, tôi muốn biết điều khoản nào lệch chuẩn công ty, để ký nhanh mà không bỏ sót rủi ro | Pháp chế, sales, quản lý | Đo từ lúc nhận đến lúc phản hồi: ~3 ngày làm việc, 2-3 vòng sửa/văn bản; ~5 văn bản/tuần (~20/tháng), ~3 giờ công/văn bản |
| 5 | Cần đọc, tổng hợp | Khi ticket/email khách hàng đổ về đầu ngày, tôi muốn mỗi ticket được phân loại, gán mức ưu tiên và gửi đúng người, để xử lý đúng việc gấp trước | CS, team kỹ thuật, khách hàng | ~1.500 ticket/tháng, ~12% bị chuyển nhóm sau lần gán đầu; thời gian phản hồi đầu tiên ~4 giờ |
| 6 | Cần đọc, tổng hợp | Khi cuối tháng cần chốt khách hàng đang phàn nàn điều gì, tôi muốn có tổng hợp chủ đề từ ticket, survey, review và call, để đưa vào roadmap có bằng chứng | Product, CS, lãnh đạo | Báo cáo VoC hiện tại: 1 người mất ~20 giờ/chu kỳ, chỉ phủ ~2/5 nguồn (~40%), 2 chu kỳ/tháng |
| 7 | Cần đọc, tổng hợp | Khi vừa họp xong 45 phút, tôi muốn có biên bản, quyết định và việc cần làm kèm người phụ trách và hạn, để không phải ngồi viết lại và không ai quên việc | Người chủ trì, người tham dự | Soạn biên bản ~25 phút/cuộc họp, ~15 cuộc/tuần; sau 1 tuần chỉ còn ~50% action item được theo dõi |
| 8 | Pain từ người khác | Khi nhận task trong sprint planning đầu tuần mà mô tả mơ hồ, tôi muốn thấy rõ mục tiêu, tiêu chí xong và hạn chót, để làm ngay mà không phải nhắn hỏi lại PM | 8 dev/designer của một squad, PM | Đếm tin nhắn hỏi lại trong Slack/Jira 2 sprint: ~3 tin/người/ngày (~15 phút/người/ngày ≈ 10 giờ/tuần cho cả squad); ~40% ticket thiếu tiêu chí hoàn thành; ~10-15% task bị làm lại do hiểu sai |

**Nếu có dùng AI để gợi ý thêm:** ý nào AI gợi ý mà bạn giữ lại, ý nào bỏ và vì sao.

- AI gợi ý case giống case 1 trong đề bài, tôi thay bằng case khác từ trải nghiệm cá nhân

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Chuẩn bị nội dung meetup tuần khi agent dev merge quá nhanh (#1 mới) | Actor rõ, nhịp tuần cố định, pain thật và mới (con người không theo kịp tốc độ agent), vẽ được quy trình, so sánh được 4 phương án | Baseline mới là ước tính, chưa bấm giờ; Rule (PR template + label) có thể giải quyết phần lớn mà không cần AI |
| 2 | Phân loại ticket (#5) | Có dữ liệu lịch sử trong hệ thống ticket nên đo được độ chính xác ngay; so sánh được cả 4 phương án | Rule theo từ khóa có thể đã đủ tốt; chưa rõ chất lượng nhãn lịch sử (12% chuyển nhóm có phải nhãn sai không) |
| 3 | Biên bản họp (#7) | Pain thật, dễ đo (25 phút/cuộc, 15 cuộc/tuần), tự dựng được lab nhỏ với vài bản ghi cuộc họp | Chất lượng nhận dạng tiếng Việt trong họp; nội dung họp có thể nhạy cảm; nhiều sản phẩm có sẵn |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi tới sáng thứ Sáu trước meetup công ty lúc 15h và agent đã merge hàng trăm thay đổi trong tuần, tôi muốn thấy ngay thay đổi nào thực sự đáng nói, kèm giải thích dễ hiểu và link nguồn, để trình bày chính xác cho cả công ty mà không phải đọc từng PR |
| Actor | EM/tech lead phụ trách phần "tuần này team đã ship gì" tại meetup công ty (một người cụ thể, chọn khi chạy lab) |
| Thời điểm / bối cảnh | Sáng thứ Sáu, trước meetup 15h; các team dùng agent phát triển tự động, ~150-300 PR/tuần, chỉ khoảng 15-25% (~30-60 PR) đáng đưa lên meetup |
| Quy trình hiện tại (3–7 bước) | 1. Mở danh sách PR/commit đã merge trong tuần → 2. Lọc PR đáng nói (bỏ chore, refactor, bot) → 3. Đọc mô tả/diff để hiểu thay đổi làm gì → 4. Hỏi lại owner/agent trên Slack "cái này ảnh hưởng ai?" → 5. Gom theo tính năng/sản phẩm → 6. Viết nội dung cho người không chuyên kỹ thuật → 7. Review với EM, kiểm tra không sót và không sai |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, đọc để hiểu thay đổi: ~40 phút/lần, vì PR do agent tạo thường có mô tả ngắn hoặc thiếu ngữ cảnh. Bước 4 (chờ trả lời, ~30 phút) là điểm rò rỉ thứ hai |
| Impact (nếu không giải thì sao) | ~170 phút/tuần/người; 3 team ≈ 510 phút/tuần (~8,5 giờ). Rủi ro: bỏ sót thay đổi quan trọng (ước ~20-30%), trình bày sai làm leadership hiểu lầm, càng lâu càng mất khả năng theo dõi sản phẩm |
| Success metric (baseline → target) | Thời gian chuẩn bị từ 170 phút xuống ≤60 phút. Độ phủ thay đổi quan trọng ≥90% so với danh sách chuẩn do tech lead gắn nhãn tay trong 2 tuần. Lỗi sai sự thật = 0 (mọi dòng đều có link PR). Số câu hỏi lại tại meetup không tăng |
| Phương án không dùng AI | Bắt buộc PR template (tác động, có hướng tới người dùng hay không, nhãn "demo-worthy") áp dụng cả cho agent; release notes tự sinh theo nhãn/conventional commits; dashboard PR theo nhãn. Có thể giảm bước 1, 2, 5 mà chưa cần AI |
| Giả thuyết về AI (nếu có) | Workflow: mỗi PR merge được tóm tắt 2 câu, phân loại (hướng tới người dùng / nội bộ / hạ tầng), gom theo chủ đề vào bản digest nháp có link PR; người duyệt chọn mục đưa lên meetup. Agent chỉ dùng cho PR mơ hồ (tự đọc thêm ngữ cảnh, hỏi owner) |
| Cảm nhận nhanh | Workflow (Rule làm đối chứng, Agent chỉ cho PR mơ hồ) |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~170 phút/tuần (ước tính, cần bấm giờ)

[1 Mở danh sách PR: 10'] → [2 Lọc PR đáng nói: 25']
→ [3 Đọc mô tả/diff: 40'] ← BOTTLENECK → [4 Hỏi lại owner/agent, chờ: 30']
→ [5 Gom theo chủ đề: 20'] → [6 Viết nội dung cho meetup: 30']
→ [7 Review + kiểm tra sót/sai: 15']
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi ticket/email khách hàng đổ về đầu ngày, tôi muốn mỗi ticket được phân loại, gán mức ưu tiên và gửi đúng người, để xử lý việc gấp trước và không phải chuyển nhóm lại |
| Actor | CS trực phân loại đầu ngày (một người cụ thể, chọn khi chạy lab) |
| Thời điểm / bối cảnh | Đầu ngày làm việc, ticket/email tồn qua đêm đổ về cùng lúc; ~1.500 ticket/tháng; CS phải đọc từng ticket rồi gán nhóm xử lý và mức ưu tiên |
| Quy trình hiện tại (3–7 bước) | 1. Mở hộp ticket/email mới → 2. Đọc nội dung từng ticket → 3. Xác định loại (lỗi kỹ thuật, thanh toán, hỏi thông tin...) → 4. Gán mức ưu tiên → 5. Chuyển đúng nhóm xử lý → 6. Nhóm nhận thấy sai nhóm thì chuyển lại (~12%) |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-4, đọc và gán nhóm/mức ưu tiên: ~1,5 phút/ticket (ước tính, chưa bấm giờ). Phần chuyển nhóm sai ~12% làm thời gian phản hồi đầu tiên kéo dài (~4 giờ) |
| Impact (nếu không giải thì sao) | Ticket gấp bị xử lý muộn vì lẫn trong hàng đợi; ~12% ticket đi vòng qua nhóm sai; khách chờ lâu, CS dành hàng giờ mỗi sáng cho việc phân loại lặp lại |
| Success metric (baseline → target) | Thời gian phân loại: 1,5 phút → dưới 20 giây/ticket (có người duyệt). Tỷ lệ chuyển nhóm sai: 12% → dưới 6%. Ticket gấp không bị gán thấp hơn mức thật: 0 ca trong mẫu kiểm |
| Phương án không dùng AI | Rule theo từ khóa/kênh gửi/biểu mẫu bắt buộc chọn loại ticket; tách hộp thư theo nhóm xử lý; checklist mức ưu tiên cho CS |
| Giả thuyết về AI (nếu có) | Rule lọc trước các ticket rõ ràng; AI gợi ý nhóm + mức ưu tiên cho ticket còn lại kèm độ tin cậy; ticket độ tin cậy thấp hoặc có dấu hiệu khẩn đi thẳng cho CS. CS duyệt trước khi chuyển |
| Cảm nhận nhanh | Rule, rồi Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~1,5 phút/ticket × ~1.500 ticket/tháng (ước tính, cần bấm giờ)

[1 Mở hộp ticket mới: 2'/lượt] → [2 Đọc nội dung từng ticket: ~1']
→ [3 Xác định loại + mức ưu tiên: ~30"] ← BOTTLENECK
→ [4 Chuyển nhóm xử lý: ~10"]
→ [5 Nhóm nhận, phát hiện sai nhóm, chuyển lại: ~12% ticket] ← BOTTLENECK
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi vừa họp xong 45 phút, tôi muốn có biên bản, quyết định và việc cần làm kèm người phụ trách và hạn, để không phải ngồi viết lại và không ai quên việc |
| Actor | Người chủ trì họp (PM/lead) |
| Thời điểm / bối cảnh | Ngay sau cuộc họp; ~15 cuộc/tuần; nội dung có cả ý kiến tranh luận chưa chốt lẫn quyết định chính thức |
| Quy trình hiện tại (3–7 bước) | 1. Vừa họp vừa ghi chú rời rạc → 2. Họp xong, đọc lại ghi chú/nhớ lại → 3. Tách quyết định khỏi ý kiến đang tranh luận → 4. Viết biên bản và liệt kê action item (người phụ trách, hạn) → 5. Gửi người tham dự → 6. Một tuần sau mới nhắc việc, nhiều action item đã bị quên |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 2-4, viết biên bản và action item: ~25 phút/cuộc (ước tính, chưa bấm giờ). Bước 6, không có cơ chế theo dõi nên sau 1 tuần chỉ còn ~50% action item được theo dõi |
| Impact (nếu không giải thì sao) | ~25 phút × 15 cuộc ≈ 6 giờ/tuần cho người chủ trì; action item bị quên, họp lại để nhắc lại việc đã chốt |
| Success metric (baseline → target) | Thời gian soạn biên bản: 25 → dưới 8 phút/cuộc (chỉ còn review). Action item còn theo dõi sau 1 tuần: 50% → ≥80%. Quyết định ghi sai (đề xuất bị ghi thành quyết định): 0 ca trong mẫu kiểm |
| Phương án không dùng AI | Mẫu biên bản cố định (quyết định / action item / chưa chốt); chỉ định người ghi chép luân phiên; nhắc việc bằng checklist trong công cụ quản lý công việc |
| Giả thuyết về AI (nếu có) | Phase 1: ghi lại cuộc họp và tóm tắt theo mẫu (quyết định / action item / chưa chốt). Phase 2: tự review để lọc nội dung rác, off-topic. Người chủ trì xác nhận quyết định trước khi gửi |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — ~25 phút/cuộc × ~15 cuộc/tuần (ước tính, cần bấm giờ)

[1 Vừa họp vừa ghi chú rời: trong họp] → [2 Đọc lại, nhớ lại ghi chú: 8']
→ [3 Tách quyết định khỏi ý kiến tranh luận: 7'] ← BOTTLENECK
→ [4 Viết biên bản + action item (người, hạn): 8'] ← BOTTLENECK
→ [5 Gửi người tham dự: 2'] → [6 Sau 1 tuần chỉ còn ~50% action item được theo dõi]
```

### AI phản biện 3 card (chỉ nêu điểm yếu)

| Câu hỏi | Card #1: Thay đổi đáng nói trước meetup | Card #2: Phân loại ticket | Card #3: Biên bản họp |
|---|---|---|---|
| 1. Actor đủ cụ thể chưa? | "EM/tech lead" là vai trò, chưa phải một người; mỗi team có thể làm khác nhau, hoặc không ai làm đều đặn | "CS trực" là vai trò; mỗi ca trực có thể phân loại theo thói quen riêng, chưa rõ ai chịu trách nhiệm khi gán sai | "PM/lead" quá rộng; kiểu cuộc họp (ra quyết định, brainstorm, báo cáo tiến độ) khác nhau nhiều, chưa chọn một loại cụ thể |
| 2. Quy trình có thật không? | 7 bước và số phút dựng từ giả định; chưa biết người đó có thực sự đọc diff hay chỉ đọc tiêu đề PR | 1,5 phút/ticket là trung bình ước tính; ticket ngắn và ticket dài chắc chắn khác xa, chưa bấm giờ theo loại | 25 phút/cuộc chưa phân biệt cuộc 15 phút với cuộc 90 phút; nhiều người thực tế chỉ ghi vài dòng, không viết biên bản đầy đủ |
| 3. Bottleneck có phải một bước cụ thể? | Bước 3 (đọc) và bước 4 (chờ người khác) khó tách; AI tóm tắt không rút ngắn thời gian chờ; nếu mô tả PR do agent viết kém thì AI tóm tắt cũng sai | Đọc, xác định loại và gán ưu tiên là một thao tác liền mạch, khó tách; phần chuyển nhóm lại (12%) có thể do quy tắc phân nhóm mơ hồ chứ không phải do CS đọc chậm | Tách "quyết định" khỏi "ý kiến" là phán đoán ngữ cảnh, khó tách khỏi bước viết; thiếu theo dõi sau họp là vấn đề hành vi, biên bản nhanh hơn cũng chưa chắc có người làm theo |
| 4. Metric đo được không? | "Độ phủ" cần danh sách chuẩn gắn nhãn tay, tốn công; "đáng nói" là phán đoán chủ quan; baseline 170 phút chưa bấm giờ | Cần nhãn chuẩn để tính sai số; chưa rõ 12% chuyển nhóm có phải nhãn sai thật hay chỉ là thay đổi hợp lý; "ticket gấp không bị hạ mức" khó đo khi ca gấp hiếm | "Action item còn theo dõi sau 1 tuần" cần định nghĩa thế nào là còn theo dõi; "quyết định ghi sai" cần người chấm lại từng cuộc họp, tốn công |
| 5. Sửa quy trình hoặc rule đã đủ chưa? | PR template + nhãn + release notes tự sinh bắt agent ghi tác động ngay lúc tạo PR có thể giải quyết gần hết, và rẻ hơn | Biểu mẫu bắt buộc chọn loại ticket, tách hộp thư theo nhóm và rule từ khóa có thể giảm phần lớn sai nhóm mà chưa cần AI | Mẫu biên bản cố định, người ghi chép luân phiên và nhắc việc trong công cụ quản lý công việc có thể đủ cho họp nhỏ |
| 6. Có nhảy sang AI quá sớm không? | Gốc vấn đề là agent tạo thay đổi nhanh hơn khả năng theo dõi; thêm một lớp AI đọc output của AI có nguy cơ sai chồng sai mà không ai phát hiện | Chưa có số liệu rule từ khóa đạt bao nhiêu trước khi thêm AI; ticket khách dùng từ lóng, sai chính tả, mô tả lan man nên AI cũng dễ gán sai, và gán nhầm ticket khẩn thành thường có hậu quả lớn | Chưa thử mẫu biên bản thủ công; ghi âm cuộc họp có thể vướng nội dung nhạy cảm, và nhận dạng tiếng Việt trong họp nhiều người chưa kiểm chứng |
| 7. Sản phẩm trên thị trường có giải tốt hơn không? | Công cụ tóm tắt PR và release notes tự sinh (ví dụ của GitHub, các công cụ review code, Jira/Linear) có thể đã làm phần lớn; cần xem lại hiện trạng trước khi tự xây | Công cụ helpdesk (Zendesk, Freshdesk...) đã có phân loại và định tuyến tự động; cần xem lại tính năng sẵn có trước khi tự xây | Nhiều sản phẩm ghi biên bản và rút action item sẵn có (công cụ họp online, ghi chép AI); cần so sánh trước khi tự xây |

### Điều chỉnh sau phản biện

| Card | Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|---|
| #1 | Baseline là ước tính, chưa bấm giờ | Đồng ý | Bấm giờ thật 2 tuần và đếm số PR; chọn một người cụ thể làm actor |
| #1 | Rule (PR template + nhãn) có thể đủ | Đồng ý | Thử phương án Rule trước làm đối chứng; đưa yêu cầu "ghi tác động" vào PR template cho cả agent |
| #1 | AI tóm tắt có thể sai chồng sai | Đồng ý | Quy tắc: mọi dòng trong digest phải có link PR, không có link thì không đưa vào; người duyệt trước khi trình bày |
| #1 | Gợi ý để agent tự soạn và tự trình bày/gửi nội dung | Không đồng ý | Giữ "người chọn và duyệt nội dung" làm ranh giới |
| #1 | Độ phủ khó đo | Đồng ý một phần | Tech lead gắn nhãn tay danh sách chuẩn trong 2 tuần đầu để làm mốc so sánh |
| #2 | Rule từ khóa/biểu mẫu có thể đủ, chưa cần AI | Đồng ý | Thử Rule trước làm đối chứng; chỉ thêm AI cho phần ticket Rule không phân loại được |
| #2 | Gán nhầm ticket khẩn thành thường có hậu quả lớn | Đồng ý | Ticket độ tin cậy thấp hoặc có dấu hiệu khẩn đi thẳng cho CS; AI không tự chuyển nhóm, CS duyệt; đặt fallback về phân loại tay |
| #2 | 12% chuyển nhóm chưa rõ là nhãn sai hay thay đổi hợp lý | Đồng ý | Lấy mẫu ticket cũ, CS gắn nhãn chuẩn, đo sai số và baseline trước khi đặt ngưỡng dưới 6% |
| #3 | Khó phân biệt đề xuất đang tranh luận với quyết định chính thức | Đồng ý | Chia 2 phase: ghi lại rồi review lọc nội dung rác; mục "chưa chốt" tách riêng; người chủ trì xác nhận quyết định trước khi gửi |
| #3 | Mẫu biên bản và nhắc việc có thể đủ cho họp nhỏ | Đồng ý một phần | Thử mẫu cố định trước làm đối chứng; chỉ xét AI cho cuộc họp dài, nhiều người |
| #3 | Ghi âm cuộc họp có thể vướng nội dung nhạy cảm | Đồng ý | Chỉ dùng cho cuộc họp được cho phép ghi; không đưa nội dung họp thật lên repo |
| #3 | Gợi ý để AI tự gửi biên bản và giao việc | Không đồng ý | Giữ người chủ trì duyệt và gửi làm ranh giới |

---


## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch 3 chủ đề sau khi narrow down từ list 8 case scan ban đầu | Được chấp nhận: 2 (Card 1, 2), Cần xem xét: 1 (Card 3)|
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: cho problem #3 của Hải: Văn hóa công ty lấy từ đâu khi không quá nhiều công ty publish vấn đề này; cho problem #2 của Minh: nếu khi apply giải pháp thì rủi ro lớn nhất khi fail là gì; problem #3 của Hùng: hỏi làm rõ yêu cầu| Các thành viên chỉnh sửa và làm rõ các vấn đề proposed |
| Nhận phản biện | Câu hỏi tôi nhận được: Card #1: Minh: Làm sao xác định một thay đổi đáng báo cáo? Có phải mọi PR được merge đều có giá trị với người dùng không => Trả lời: cần có insights từ quy trình review và báo cáo cụ thể của tech lead, Card #2: Hải : Khách hàng hay dùng từ lóng, viết sai chính tả, mô tả lan man. AI có cam kết sai số thấp hơn 12% hiện tại? Nếu AI gán sai ticket "cháy nhà" thành "bình thường" thì hậu quả ai chịu? Card #3: Minh: Nếu cuộc họp có nhiều ý kiến tranh luận nhưng chưa đi đến thống nhất, làm sao phân biệt một đề xuất với quyết định chính thức? | Tôi đã sửa gì: Card #1: cần có insights từ quy trình review và báo cáo cụ thể của tech lead; Card #2: làm rõ lại + xem xét tính cần thiết của giải pháp cho vấn đề + cần xem xét ngưỡng baseline và performance của hệ thống để độ chính xác là một thông số transparent và có thể setup fallback; Card 3: giải pháp sẽ bao gồm 2 phase: phase 1 - ghi lại, phase 2 - tự review để lọc nội dung rác, off topic |
| Gom cluster / cây OST | Cùng team thống nhất: gom 12 candidate thành 5 cluster (A–E), #7/#9 của tôi ở cluster C, #8 ở cluster D; rút OST về 1 outcome, 3 opportunity, gạch các ý là solution đội lốt opportunity (dashboard tự động, agent tự tắt quảng cáo, AI sửa tracking) | Cây OST bám vào #10 của Hùng |
| Chọn candidate problem | Tham gia chấm shortlist 1–5 trên 7 tiêu chí; #7 của tôi đạt 27/35, đứng thứ 2 sau #10 của Hùng (29/35); #7 thua vì "đáng báo cáo" phụ thuộc đánh giá của Tech Lead, chưa có bộ ví dụ đã duyệt | Nhóm chọn #10 (Performance Marketer, 9 TKQC/3 chi nhánh, %CPQC/ROAS); tôi đồng ý vì đúng bảng điểm và đầu ra số học dễ kiểm tra |
| Kiểm chứng / research | Tham gia Assumption Map (6 giả định), snapshot dashboard 09/11/2026, 3 interview và research SUMIFS, Looker Studio blends, Supermetrics | Xác nhận 9 TKQC/3 chi nhánh; phát hiện "23 TKQC lỗi", mốc quét lệch ~7 tuần; Người 2 phản bác "20 phút là bình thường" nên giữ 45 phút làm baseline riêng của case |
| Quy trình nhóm | Scan, Deep assess; cùng vẽ quy trình hiện tại 5 bước (tổng 45 phút/lần, bottleneck bước 3 đối chiếu) và quy trình tương lai hướng Rule (30 phút/lần) | Thời gian từng bước mới là phân rã minh họa, chưa bấm giờ |
| Problem Statement | Cùng viết v0 rồi v1; v1 thêm điều kiện có bản xuất, đối soát tổng, truy nguồn, quy tắc mẫu số, boundary không ghi ngược/không tự quy nguồn đơn/không kết luận lợi nhuận; 5 tiêu chí đánh giá đầu ra của Rule | Xử lý lỗ hổng "nhanh nhưng sai" của v0 |
| Mức can thiệp AI | Cùng đặt bài vào ô độ mơ hồ thấp × độ phức tạp cao, so sánh No AI/Rule/Workflow/Agent | Chọn Rule, không có điểm can thiệp AI; Agent không chọn vì chưa có bằng chứng cần mức tự chủ đó |
| Quyết định | Cùng đánh giá 4 rủi ro (Value TB, Usability TB, Feasibility Cao, Viability Cao) và đồng ý kết luận | Not Yet cho pilot trên dữ liệu thật; ưu tiên Rule; có ngưỡng dừng và danh sách việc kiểm chứng trước khi Go |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | Khám phá quy trình và suggest vấn đề| Ở phần đưa ra 1 số quy trình làm việc của các role | Suggest case quá giống bài mẫu| Thay thế case|
| CP2 Problem Card | Dùng AI phản biện 3 Problem Card (7 câu hỏi: actor, quy trình, bottleneck, metric, rule đủ chưa, nhảy sang AI quá sớm, sản phẩm có sẵn) | Chỉ ra điểm yếu về baseline chưa bấm giờ, Rule/biểu mẫu có thể đủ, nguy cơ AI sai chồng sai | Một số điểm yếu chung chung, chưa gắn với dữ liệu thật của từng case | Chọn điểm yếu đồng ý (thêm đối chứng Rule, fallback, người duyệt), giữ ranh giới không cho AI tự soạn/gửi/chuyển nhóm |
| CP4 Research | Không dùng | Không | Không | Không |
| CP5 Quy trình | Nhóm dùng AI hỗ trợ biên tập quy trình hiện tại/tương lai của nhóm | Giúp tách rõ bước nào Rule, bước nào con người, thêm phương án quay về | Thời gian từng bước chỉ là phân rã minh họa, chưa có số đo thật | Nhóm ghi rõ "minh họa, chưa bấm giờ" và giữ yêu cầu đo lại 2 kỳ |
| CP5–6 Problem Statement | Nhóm dùng AI phản biện Problem Statement v0 | Chỉ ra v0 chỉ có mục tiêu thời gian nên báo cáo nhanh nhưng lệch số vẫn "đạt" | Đề xuất ban đầu chưa nêu mẫu số %CPQC/ROAS | Nhóm đồng ý bổ sung đối soát tổng, truy nguồn, quy tắc mẫu số vào v1 |
| CP6 Mức can thiệp / quyết định | Nhóm dùng AI so sánh 4 mức can thiệp | Giúp thấy Rule đủ cho phép cộng và tính tỷ lệ | Dễ nghiêng về hướng thêm AI khi chưa có nhu cầu xác nhận | Nhóm chọn Rule, không đưa AI vào, kết luận Not Yet |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

Nghe bài của Hải, Minh và Hùng, tôi thấy phần lớn pain thật ra nằm ở dữ liệu bị phân mảnh và quy tắc chưa thống nhất, không nằm ở việc thiếu một công cụ. Case của Hùng cho thấy rõ nhất: 9 tài khoản quảng cáo cộng CRM của 3 chi nhánh, bước khó là đối chiếu đúng kỳ, đúng chi nhánh chứ không phải cộng số. Tôi cũng nhận ra cách hỏi của các bạn (hậu quả lớn nhất là gì, rủi ro nếu giải pháp sai) buộc người pitch phải nói được bằng chứng thay vì chỉ kể cảm giác.

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

Có. Khi dựng cây OST, nhóm viết ra các ý như "dashboard tự động cho mọi chi nhánh", "agent tự tìm chiến dịch lỗ rồi tắt quảng cáo", "AI sửa dữ liệu tracking sai". Cả ba đều là giải pháp đội lốt nhu cầu. Nhóm nhận ra khi kiểm lại xem nhánh nào mô tả pain và nhánh nào mô tả công cụ, rồi gạch bỏ và ghi lý do vào báo cáo. Opportunity còn lại chỉ nói về việc phải mở 9 nguồn, chưa đối chiếu cùng kỳ/chi nhánh và mất công cộng, truy nguồn khi lệch.

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

Có, ở card #3 (biên bản họp). Minh hỏi làm sao phân biệt một đề xuất với quyết định chính thức khi cuộc họp còn tranh luận. Ban đầu tôi nghĩ AI ghi lại hết là đủ. Sau câu hỏi đó tôi chia giải pháp thành 2 phase: phase 1 chỉ ghi lại, phase 2 tự review để lọc nội dung rác, off-topic, và vẫn cần người chủ trì xác nhận quyết định. Với card #2, câu hỏi của Hải về sai số dưới 12% và hậu quả khi gán nhầm ticket "cháy nhà" làm tôi thêm baseline, ngưỡng hiệu năng và fallback.

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

Có hai điều. Thứ nhất, snapshot dashboard của Hùng cho thấy "23 TKQC lỗi" gán sai nguồn chi phí và mốc quét Business Manager lệch khoảng 7 tuần, tức dữ liệu nguồn có vấn đề thật, không chỉ là suy đoán từ phản biện. Thứ hai, Người 2 nói "20 phút là bình thường", trái với 45 phút trong pitch. Điều này cho thấy mức độ pain khác nhau giữa các đơn vị, nên nhóm giữ 45 phút làm baseline riêng của case thay vì gộp số.

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

Khó nhất là ghi đúng điều đã biết và điều mới chỉ ước lượng. Gần như mọi con số thời gian (45 phút, 15/5/15/7/3) đều từ pitch hoặc phân rã minh họa, chưa bấm giờ, nên mỗi lần viết Impact hay Success Metric tôi phải gắn nhãn "ước lượng" và nêu cách đo lại. Khó thứ hai là định nghĩa mẫu số của %CPQC và ROAS; nếu không chốt thì metric "30 phút" đạt nhưng số vẫn có thể sai.

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

Tôi sẽ bấm giờ thật cho case của mình trước buổi pitch, vì card #1 thua vòng chọn một phần do baseline 170 phút chưa đo và "đáng nói" chưa có bộ ví dụ chuẩn. Tôi cũng sẽ phản biện mạnh hơn ở hai điểm của case được chọn: mức tiết kiệm mục tiêu chỉ 30 phút/tuần so với công duy trì Rule và quyền dùng dữ liệu, và việc mới chỉ có 3 interview với Người 2 đã phản bác mức độ pain.

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

Problem: Performance Marketer phải gom chi phí từ 9 TKQC và đối chiếu doanh thu CRM của 3 chi nhánh để tính %CPQC và ROAS, ước lượng 45 phút/lần, 2 lần/tuần. Quy trình hiện tại gồm 5 bước, nghẽn ở đối chiếu kỳ/chi nhánh; quy trình tương lai để con người lấy dữ liệu, xử lý ngoại lệ và duyệt, còn Rule kiểm schema, mapping và tính chỉ số. Metric: từ khoảng 45 xuống tối đa 30 phút/lần, kèm đủ 9 TKQC, tổng tiền khớp bản xuất, mọi ngoại lệ được xử lý trước khi duyệt. Boundary: không ghi ngược vào TKQC/CRM, không sửa tracking, không tự quy nguồn đơn, không kết luận lợi nhuận hay chỉnh ngân sách; thiếu căn cứ thì ROAS ghi "chưa đủ dữ liệu". Mức can thiệp: Rule, không có điểm can thiệp AI, vì đây là số học theo quy tắc. Quyết định: Not Yet, vì Feasibility và Viability còn Cao (chưa có bản xuất hợp lệ, quy tắc doanh thu và quyền dùng dữ liệu), cần đo baseline 2 kỳ và phỏng vấn thêm trước khi pilot.

---

## 7. Tài liệu tham khảo

- Báo cáo nhóm: [report/team/group_report.md](../team/group_report.md)
- Snapshot dashboard TKQC: [report/assets/cp1-tkqc-snapshot.md](../assets/cp1-tkqc-snapshot.md)
- [Google Sheets — SUMIFS](https://support.google.com/docs/answer/3238496?hl=en)
- [Google — How blends work](https://docs.cloud.google.com/data-studio/how-blends-work)
- [Supermetrics — Google Sheets](https://docs.supermetrics.com/docs/google-sheets)
