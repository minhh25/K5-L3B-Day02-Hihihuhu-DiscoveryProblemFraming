# Báo cáo cá nhân — 2A202603882_vutienhung

> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).

**Nhân vật:** Vũ Tiến Hùng, performance marketer phụ trách quảng cáo Facebook (TKQC) đa chi nhánh cho một nhãn hàng tiêu dùng bán sang thị trường Thái Lan. Công việc hằng ngày: theo dõi chi phí quảng cáo trên nhiều tài khoản/trang Facebook, đối chiếu với doanh số bán hàng trên CRM để tính hiệu quả quảng cáo (%CPQC/ROAS) theo từng chi nhánh và từng nhân viên đứng tên tài khoản quảng cáo, báo cáo cho quản lý. Doanh số ghi nhận bằng THB (khách Thái trả), chi phí quảng cáo trả bằng VND (agency Việt Nam) — hai đồng tiền không trộn lẫn được nếu không quy đổi đúng tỷ giá theo ngày.

## 1. Thông tin học viên

- Họ tên: Vũ Tiến Hùng
- MSSV: 2A202603882
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: Hihihuhu
- Link repo nhóm: https://github.com/minhh25/K5-L3B-Day02-Hihihuhu-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi tới kỳ báo cáo hiệu suất quảng cáo, tôi muốn gom chi phí TKQC (Facebook Ads) từ nhiều tài khoản/chi nhánh và đối chiếu với doanh số trên CRM, để tính đúng %CPQC/ROAS theo từng chi nhánh | Bản thân tôi (performance marketer), quản lý chi nhánh | [ĐIỀN: ? TKQC đang chạy, mất ? phút/lần tổng hợp, ? lần/tuần] |
| 2 | Tốn thời gian | Khi cần biết đơn hàng trên CRM đến từ nguồn quảng cáo nào, tôi muốn đối chiếu hội thoại chăm sóc khách hàng với đơn hàng trên CRM mà không phải dò tay từng SĐT, để biết nhân viên/kênh nào mang đơn thật | Bản thân tôi, nhân viên chăm sóc KH | [ĐIỀN: trước đây match_rate dò tay thấp (~13-25%), mất ? phút/đơn đối chiếu tay] |
| 3 | Pain từ người khác | Khi quản lý TKQC theo từng nhân viên đứng tên tài khoản quảng cáo, tôi muốn biết ai đang tiêu bao nhiêu và ra đơn bao nhiêu, để đánh giá hiệu suất từng người mà không phải hỏi lại từng nhân viên | Nhân viên chạy ads, quản lý | [ĐIỀN: ? nhân viên đang quản lý TKQC, tần suất phải hỏi lại thủ công] |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi phát hiện số liệu báo cáo "có vẻ sai" (ví dụ doanh số/chi phí lệch bất thường), tôi muốn truy ngược được field dữ liệu gốc trên CRM (số thô vs số đã qua báo cáo tổng hợp tự quy đổi) để biết lỗi nằm ở đâu, để không báo cáo sai cho sếp/đối tác | Bản thân tôi, người đọc báo cáo (sếp, đối tác) | [ĐIỀN: từng phát hiện sai lệch % cụ thể bao nhiêu, mất ? giờ để truy ra nguyên nhân] |
| 5 | Tốn thời gian | Khi cần theo dõi nhiều trang Facebook/TKQC cùng lúc cho nhiều chi nhánh, tôi muốn có một nơi tổng hợp thay vì mở từng trang quảng cáo riêng lẻ, để không bỏ sót trang nào đang chạy kém hiệu quả | Bản thân tôi | [ĐIỀN: đang quản lý ? page/TKQC, mất ? phút kiểm tra thủ công mỗi ngày] |
| 6 | Lặp lại | Khi mỗi sáng kiểm tra hiệu suất quảng cáo hôm trước, tôi muốn biết ngay chiến dịch nào đang lỗ (CPQC vượt ngưỡng) mà không phải tự tính tay từng chiến dịch, để tắt/điều chỉnh kịp thời | Bản thân tôi | [ĐIỀN: ? chiến dịch đang chạy song song, mất ? phút rà tay mỗi sáng] |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi cuối tháng tổng kết hiệu suất cho quản lý, tôi muốn gộp số liệu nhiều tuần/nhiều chi nhánh thành một bản so sánh xu hướng, để thấy chi nhánh nào đang xuống | Bản thân tôi, quản lý | [ĐIỀN: mất ? giờ làm báo cáo tháng, ? nguồn dữ liệu phải gộp] |
| 8 | Pain từ người khác | Khi nhân viên chạy ads báo "tài khoản bị khoá/die" đột xuất, tôi muốn biết ngay nguyên nhân và tài khoản thay thế khả dụng, để không gián đoạn chiến dịch đang lên đơn tốt | Nhân viên chạy ads, bản thân tôi | [ĐIỀN: ? lần/tháng tài khoản bị khoá, mất ? phút/lần xử lý] |
| 9 | Tốn thời gian | Khi khách hàng nhắn tin qua nhiều kênh (Facebook, Zalo, Tiktok), tôi muốn biết tin nhắn nào thuộc khách đã từng mua hàng, để ưu tiên chăm sóc đúng nhóm khách tiềm năng cao | Nhân viên chăm sóc KH, bản thân tôi | [ĐIỀN: ? tin nhắn/ngày phải tự tra cứu chéo, mất ? phút/lần] |
| 10 | Pain từ người khác | Khi sếp hỏi đột xuất "tuần này chi nhánh X lãi hay lỗ", tôi muốn trả lời được ngay trong vài phút, để không phải nói "để em kiểm tra lại gửi sau" | Bản thân tôi, quản lý/sếp | [ĐIỀN: ? lần/tháng bị hỏi đột xuất, trung bình mất ? phút mới trả lời được] |

**Nếu có dùng AI để gợi ý thêm:** Mình dùng AI (Claude) đọc lại README một dự án dashboard báo cáo Sale-Marketing mình đang tự xây để gợi ý 11 problem trên bám sát công việc performance marketing thật của mình (đối chiếu nguồn đơn, quy đổi tiền tệ THB/VND, theo dõi TKQC đa chi nhánh/nhân viên, xử lý sự cố tài khoản quảng cáo, chăm sóc khách đa kênh). Mình giữ lại toàn bộ 11 ý vì đây đúng là các việc mình đang tự làm/tự xây công cụ để giải quyết, không phải AI bịa ra. Mình bỏ không dùng các ý quá chung chung kiểu "cần một trợ lý AI toàn năng quản lý marketing" vì đó là solution trá hình, không mô tả đúng một bước nghẽn cụ thể. Các ô "dấu hiệu thật" mình sẽ tự điền số liệu chính xác (mất bao lâu, tần suất) từ công việc thực tế của mình trước khi nộp.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp chi phí TKQC đa chi nhánh đối chiếu CRM (#1) | Quy trình lặp lại định kỳ, actor rõ (chính mình), có baseline đo được, impact tính ra tiền/thời gian rõ ràng | "Đủ tốt" của phần nhận định/diễn giải số liệu đo thế nào ngoài thời gian? |
| 2 | Đối chiếu hội thoại CSKH với đơn CRM để biết nguồn (#2) | Pain thật, ảnh hưởng tới nhiều người (CSKH, quản lý), có số liệu match_rate cụ thể để so sánh trước/sau | Có đủ quyền truy cập dữ liệu hội thoại CSKH ở mọi kênh không; phạm vi dễ phình to |
| 3 | Rà soát chiến dịch lỗ mỗi sáng (#6) | Việc lặp lại hằng ngày, bottleneck rất cụ thể (tính tay CPQC từng chiến dịch), dễ đặt ngưỡng cảnh báo rõ | Ngưỡng "lỗ" nên tính theo CPQC tuyệt đối hay theo %CPQC/doanh thu? |

### Problem Card #1 — Tổng hợp báo cáo hiệu suất quảng cáo đa chi nhánh

| Trường | Nội dung |
|---|---|
| Job Story | Khi tới kỳ báo cáo hiệu suất quảng cáo, tôi muốn gom chi phí TKQC từ nhiều tài khoản/chi nhánh và đối chiếu với doanh số trên CRM, để tính đúng %CPQC/ROAS theo từng chi nhánh |
| Actor | Performance marketer phụ trách TKQC đa chi nhánh |
| Thời điểm / bối cảnh | Cuối mỗi tuần/mỗi tháng, trước khi báo cáo cho quản lý |
| Quy trình hiện tại (3–7 bước) | 1. Mở từng tài khoản quảng cáo lấy số chi phí · 2. Xuất số doanh thu từ CRM theo từng chi nhánh · 3. Quy đổi đơn vị tiền nếu khác nhau · 4. Dán vào bảng tính tổng hợp · 5. Tính %CPQC/ROAS từng chi nhánh · 6. Viết nhận định (chi nhánh nào hiệu quả/kém) · 7. Gửi báo cáo |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1+2, tự tay mở từng tài khoản/chi nhánh để lấy số — [ĐIỀN: mất ? phút] |
| Impact (nếu không giải thì sao) | Báo cáo chậm, quyết định tắt/tăng ngân sách chiến dịch bị trễ, có thể tốn thêm chi phí quảng cáo không hiệu quả trong lúc chờ tổng hợp xong |
| Success metric (baseline → target) | Thời gian tổng hợp từ [ĐIỀN: ? phút] xuống còn dưới [ĐIỀN: mục tiêu], đo bằng tự bấm giờ 2 tuần liên tiếp |
| Phương án không dùng AI | Rule/script tự lấy số từ API quảng cáo + CRM đổ vào một bảng cố định, không cần AI |
| Giả thuyết về AI (nếu có) | AI soạn nháp phần nhận định (chi nhánh nào đáng chú ý, vì sao) từ số liệu đã gom sẵn |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI

[1 Lấy chi phí từng TKQC] → [2 Lấy doanh thu CRM theo chi nhánh] → [3 Quy đổi tiền nếu cần]
→ [4 Dán vào bảng tổng hợp] → [5 Tính %CPQC/ROAS] → [6 Viết nhận định] ← có thể là bước nghẽn thứ 2
→ [7 Gửi báo cáo]

BOTTLENECK chính: bước 1-2 (thao tác tay trên nhiều nguồn)
```

### Problem Card #2 — Đối chiếu nguồn đơn hàng qua hội thoại CSKH

| Trường | Nội dung |
|---|---|
| Job Story | Khi cần biết đơn hàng trên CRM đến từ nguồn quảng cáo nào, tôi muốn đối chiếu hội thoại chăm sóc khách hàng với đơn hàng trên CRM mà không phải dò tay từng số điện thoại, để biết nhân viên/kênh nào mang đơn thật |
| Actor | Performance marketer + nhân viên chăm sóc khách hàng |
| Thời điểm / bối cảnh | Khi phân tích hiệu quả theo kênh/nhân viên, thường vào cuối tuần hoặc khi có nghi ngờ số liệu nguồn đơn sai |
| Quy trình hiện tại (3–7 bước) | 1. Xuất danh sách đơn hàng từ CRM · 2. Xuất danh sách hội thoại từ công cụ chăm sóc khách hàng · 3. Dò tay số điện thoại khách giữa 2 danh sách · 4. Đánh dấu đơn khớp được nguồn/nhân viên · 5. Tổng hợp tỉ lệ khớp theo kênh |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, dò tay từng số điện thoại — [ĐIỀN: mất ? phút/đơn, match_rate dò tay thấp] |
| Impact (nếu không giải thì sao) | Không biết chính xác kênh/nhân viên nào mang lại đơn thật → phân bổ ngân sách quảng cáo sai, đánh giá hiệu suất nhân viên không công bằng |
| Success metric (baseline → target) | Tỉ lệ đơn khớp được nguồn tăng từ [ĐIỀN: baseline %] lên [ĐIỀN: target %], thời gian đối chiếu giảm từ [ĐIỀN] xuống [ĐIỀN] |
| Phương án không dùng AI | Rule: khớp tự động theo số điện thoại sạch có sẵn trong cả 2 hệ thống (không cần suy đoán) |
| Giả thuyết về AI (nếu có) | AI chỉ dùng khi số điện thoại không khớp trực tiếp, cần suy luận từ nội dung hội thoại — mức rủi ro cao hơn Rule thuần |
| Cảm nhận nhanh | Rule, có thể nâng Workflow nếu cần suy luận thêm |

Quy trình nháp hiện tại:

```text
HIỆN TẠI

[1 Xuất đơn CRM] → [2 Xuất hội thoại CSKH] → [3 Dò tay SĐT] ← BOTTLENECK
→ [4 Đánh dấu khớp nguồn/NV] → [5 Tổng hợp tỉ lệ khớp theo kênh]
```

### Problem Card #3 — Rà soát chiến dịch lỗ mỗi sáng

| Trường | Nội dung |
|---|---|
| Job Story | Khi mỗi sáng kiểm tra hiệu suất quảng cáo hôm trước, tôi muốn biết ngay chiến dịch nào đang lỗ (CPQC vượt ngưỡng) mà không phải tự tính tay từng chiến dịch, để tắt/điều chỉnh kịp thời |
| Actor | Performance marketer |
| Thời điểm / bối cảnh | Mỗi sáng, đầu giờ làm việc, trước khi quyết định điều chỉnh ngân sách trong ngày |
| Quy trình hiện tại (3–7 bước) | 1. Mở từng tài khoản quảng cáo xem chi phí hôm qua · 2. Mở CRM xem doanh thu tương ứng theo chiến dịch/chi nhánh · 3. Tự tính %CPQC từng chiến dịch · 4. So với ngưỡng chấp nhận được trong đầu · 5. Quyết định tắt/giữ/tăng ngân sách |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1-3, tính tay %CPQC từng chiến dịch mỗi sáng — [ĐIỀN: ? chiến dịch, mất ? phút] |
| Impact (nếu không giải thì sao) | Phát hiện chiến dịch lỗ muộn → tốn thêm ngân sách quảng cáo không hiệu quả thêm 1 ngày |
| Success metric (baseline → target) | Thời gian rà soát mỗi sáng từ [ĐIỀN] xuống dưới [ĐIỀN], số chiến dịch lỗ bị phát hiện muộn giảm |
| Phương án không dùng AI | Rule: đặt ngưỡng %CPQC cố định, script tự tính và highlight chiến dịch vượt ngưỡng mỗi sáng |
| Giả thuyết về AI (nếu có) | Không cần AI cho bước tính toán (đây là phép tính xác định, Rule đủ); AI chỉ có thể hỗ trợ gợi ý nguyên nhân lỗ nếu muốn mở rộng |
| Cảm nhận nhanh | Rule |

Quy trình nháp hiện tại:

```text
HIỆN TẠI

[1 Xem chi phí từng TKQC] → [2 Xem doanh thu CRM theo chiến dịch] → [3 Tính tay %CPQC] ← BOTTLENECK
→ [4 So ngưỡng trong đầu] → [5 Quyết định tắt/giữ/tăng]
```

### Card muốn pitch nhất

- Card số: 1 — Tổng hợp báo cáo hiệu suất quảng cáo đa chi nhánh
- Vì sao: đây là công việc định kỳ tốn nhiều thời gian nhất, ảnh hưởng trực tiếp tới tốc độ ra quyết định ngân sách quảng cáo, và đã có baseline/impact rõ ràng để đo
- Câu hỏi muốn nhóm phản biện: Phần "viết nhận định" trong báo cáo có thực sự cần AI không, hay chỉ cần dashboard số liệu là quản lý đã tự đọc hiểu được?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| | | |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | | | | |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
