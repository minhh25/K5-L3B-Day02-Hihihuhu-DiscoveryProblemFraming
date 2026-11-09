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
| 1 | Cần đọc, tổng hợp nhiều thông tin | Khi tới kỳ báo cáo hiệu suất quảng cáo, tôi muốn gom chi phí TKQC (Facebook Ads) từ nhiều tài khoản/chi nhánh và đối chiếu với doanh số trên CRM, để tính đúng %CPQC/ROAS theo từng chi nhánh | Bản thân tôi (performance marketer), quản lý chi nhánh | Tháng 11/2026: 9 TKQC đang chạy trên 3 chi nhánh (TEAM A 1 TKQC, TEAM B 3 TKQC, TEAM C 5 TKQC), tổng CPQC 113.195.941đ, %CPQC 22,55%/834 triệu doanh số — phải tự đọc dashboard và bấm quét lại dữ liệu để ra được con số này (dữ liệu thật quan sát 09/11/2026, xem `report/assets/cp1-tkqc-snapshot.md`) |
| 2 | Tốn thời gian | Khi cần biết đơn hàng trên CRM đến từ nguồn quảng cáo nào, tôi muốn đối chiếu hội thoại chăm sóc khách hàng với đơn hàng trên CRM mà không phải dò tay từng SĐT, để biết nhân viên/kênh nào mang đơn thật | Bản thân tôi, nhân viên chăm sóc KH | Dashboard công ty cho thấy đây từng là bài toán phải tự xây công cụ riêng để giải (đối chiếu Pancake ↔ CRM) vì dò tay không đủ chính xác; tab "Page" hiện quản lý 84 page cùng lúc |
| 3 | Pain từ người khác | Khi quản lý TKQC theo từng nhân viên đứng tên tài khoản quảng cáo, tôi muốn biết ai đang tiêu bao nhiêu và ra đơn bao nhiêu, để đánh giá hiệu suất từng người mà không phải hỏi lại từng nhân viên | Nhân viên chạy ads, quản lý | 9 nhân viên marketing đang đứng tên 9 TKQC (xem bảng "Tổng CPQC theo NV Marketing" tháng 11/2026), chi phí mỗi người lệch rất xa nhau (từ 277.209đ đến 42.826.646đ) nên không nhìn tổng mà hỏi riêng từng người sẽ rất mất thời gian |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi phát hiện số liệu báo cáo "có vẻ sai" (ví dụ doanh số/chi phí lệch bất thường), tôi muốn truy ngược được field dữ liệu gốc trên CRM (số thô vs số đã qua báo cáo tổng hợp tự quy đổi) để biết lỗi nằm ở đâu, để không báo cáo sai cho sếp/đối tác | Bản thân tôi, người đọc báo cáo (sếp, đối tác) | Quan sát thật 09/11/2026: lần quét chi tiêu Facebook gần nhất (05/10/2026) báo "gán được 100%, 23 TKQC lỗi" — tức gần 1/4 tổng số TKQC từng bị gán sai nguồn chi phí, phải tự phát hiện qua dòng cảnh báo này chứ hệ thống không tự chặn báo cáo sai |
| 5 | Tốn thời gian | Khi cần theo dõi nhiều trang Facebook/TKQC cùng lúc cho nhiều chi nhánh, tôi muốn có một nơi tổng hợp thay vì mở từng trang quảng cáo riêng lẻ, để không bỏ sót trang nào đang chạy kém hiệu quả | Bản thân tôi | Đang quản lý 84 page Facebook cùng lúc (xem tab "Page" 09/11/2026); lần quét Business Manager gần nhất là 21/09/2026 — lệch gần 7 tuần so với hiện tại, nghĩa là nếu không tự bấm quét lại thì dữ liệu xem được đã cũ |
| 6 | Lặp lại | Khi mỗi sáng kiểm tra hiệu suất quảng cáo hôm trước, tôi muốn biết ngay chiến dịch nào đang lỗ (CPQC vượt ngưỡng) mà không phải tự tính tay từng chiến dịch, để tắt/điều chỉnh kịp thời | Bản thân tôi | Kỳ 01/11–09/11/2026 dashboard báo "Chưa có chi tiêu Facebook" vì chưa ai bấm quét — nghĩa là nếu không chủ động mỗi sáng, dữ liệu để quyết định tắt/giữ chiến dịch sẽ bị trống hoàn toàn, không có cảnh báo tự động nào nhắc |
| 7 | Cần đọc, tổng hợp nhiều thông tin | Khi cuối tháng tổng kết hiệu suất cho quản lý, tôi muốn gộp số liệu nhiều tuần/nhiều chi nhánh thành một bản so sánh xu hướng, để thấy chi nhánh nào đang xuống | Bản thân tôi, quản lý | Tab Tổng quan tháng 11/2026 cho thấy %CPQC đã giảm 48,07% so với kỳ liền trước — phải tự đọc nhiều mục nhỏ (CPQC, DS Chốt, DS Resale, DS Chuyển, AOV, DS Hoàn/Hủy) rồi mới ghép lại thành 1 nhận định xu hướng cho quản lý |
| 8 | Pain từ người khác | Khi nhân viên chạy ads báo "tài khoản bị khoá/die" đột xuất, tôi muốn biết ngay nguyên nhân và tài khoản thay thế khả dụng, để không gián đoạn chiến dịch đang lên đơn tốt | Nhân viên chạy ads, bản thân tôi | [ĐIỀN: ? lần/tháng tài khoản bị khoá, mất ? phút/lần xử lý — chưa quan sát được qua dashboard, cần tự nhớ lại số lần thực tế] |
| 9 | Tốn thời gian | Khi khách hàng nhắn tin qua nhiều kênh (Facebook, Zalo, Tiktok), tôi muốn biết tin nhắn nào thuộc khách đã từng mua hàng, để ưu tiên chăm sóc đúng nhóm khách tiềm năng cao | Nhân viên chăm sóc KH, bản thân tôi | [ĐIỀN: ? tin nhắn/ngày phải tự tra cứu chéo, mất ? phút/lần — chưa quan sát được qua dashboard, cần tự ước lượng từ công việc CSKH thực tế] |
| 10 | Pain từ người khác | Khi sếp hỏi đột xuất "tuần này chi nhánh X lãi hay lỗ", tôi muốn trả lời được ngay trong vài phút, để không phải nói "để em kiểm tra lại gửi sau" | Bản thân tôi, quản lý/sếp | [ĐIỀN: ? lần/tháng bị hỏi đột xuất, trung bình mất ? phút mới trả lời được — chưa quan sát được qua dashboard, cần tự nhớ lại tần suất thật] |

**Nếu có dùng AI để gợi ý thêm:** Mình dùng AI (Claude) đọc lại README một dự án dashboard báo cáo Sale-Marketing mình đang tự xây để gợi ý 11 problem trên bám sát công việc performance marketing thật của mình (đối chiếu nguồn đơn, quy đổi tiền tệ THB/VND, theo dõi TKQC đa chi nhánh/nhân viên, xử lý sự cố tài khoản quảng cáo, chăm sóc khách đa kênh). Mình giữ lại toàn bộ 11 ý vì đây đúng là các việc mình đang tự làm/tự xây công cụ để giải quyết, không phải AI bịa ra. Mình bỏ không dùng các ý quá chung chung kiểu "cần một trợ lý AI toàn năng quản lý marketing" vì đó là solution trá hình, không mô tả đúng một bước nghẽn cụ thể. Các ô "dấu hiệu thật" mình sẽ tự điền số liệu chính xác (mất bao lâu, tần suất) từ công việc thực tế của mình trước khi nộp.

-

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Tiêu chí chọn (theo docs/01-worksheet.md CP2)

Actor rõ · Quy trình vẽ được · Bottleneck là 1 bước cụ thể · Impact đo được · So sánh được 4 mức AI · Vừa sức 1 buổi lab.

| # | Problem | Actor rõ | Quy trình vẽ được | Bottleneck cụ thể | Impact đo được | So sánh 4 mức | Vừa sức lab | Tổng |
|---:|---|---:|---:|---:|---:|---:|---:|---:|
| 1 | Tổng hợp báo cáo hiệu suất quảng cáo đa chi nhánh | 5 | 5 | 4 | 5 | 5 | 5 | **29** |
| 2 | Đối chiếu nguồn đơn qua hội thoại CSKH | 4 | 4 | 4 | 4 | 4 | 3 | 23 |
| 3 | Theo dõi hiệu suất/chi tiêu từng nhân viên TKQC | 3 | 3 | 2 | 3 | 3 | 4 | 18 |
| 4 | Truy ngược lỗi số liệu báo cáo | 4 | 3 | 3 | 4 | 3 | 3 | 20 |
| 5 | Theo dõi nhiều page/TKQC đa chi nhánh | 4 | 3 | 3 | 3 | 4 | 4 | 21 |
| 6 | Rà soát chiến dịch lỗ mỗi sáng | 5 | 5 | 5 | 4 | 4 | 5 | **28** |
| 7 | Tổng hợp báo cáo tháng đa chi nhánh | 4 | 4 | 3 | 4 | 3 | 3 | 21 |
| 8 | Xử lý sự cố tài khoản quảng cáo bị khoá | 3 | 2 | 3 | 3 | 2 | 3 | 16 |
| 9 | Tra cứu chéo khách hàng đa kênh | 3 | 3 | 3 | 3 | 3 | 3 | 18 |
| 10 | Trả lời nhanh câu hỏi đột xuất của sếp | 3 | 2 | 2 | 2 | 2 | 3 | 14 |

**Chọn top 3: #1, #6, #2** — điểm cao nhất, mỗi problem thuộc một pattern khác nhau (tổng hợp số liệu định kỳ / cảnh báo theo ngưỡng hằng ngày / đối chiếu dữ liệu đa nguồn), tránh chọn 3 problem na ná nhau.

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Tổng hợp báo cáo hiệu suất quảng cáo đa chi nhánh (#1) | Quy trình lặp lại định kỳ, actor rõ (chính mình), có baseline đo được, impact tính ra tiền/thời gian rõ ràng | "Đủ tốt" của phần nhận định/diễn giải số liệu đo thế nào ngoài thời gian? |
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
| Job Story | Khi cần biết đơn hàng trên CRM đến từ nguồn quảng cáo nào, tôi (performance marketer) muốn đối chiếu hội thoại chăm sóc khách hàng với đơn hàng trên CRM mà không phải dò tay từng số điện thoại, để biết nhân viên/kênh nào mang đơn thật |
| Actor | Actor chính: Performance marketer (người cần kết quả đối chiếu để ra quyết định ngân sách/đánh giá hiệu suất). Actor phụ: nhân viên chăm sóc khách hàng (người giữ dữ liệu hội thoại) |
| Thời điểm / bối cảnh | Khi phân tích hiệu quả theo kênh/nhân viên, thường vào cuối tuần hoặc khi có nghi ngờ số liệu nguồn đơn sai |
| Quy trình hiện tại (3–7 bước) | 1. Xuất danh sách đơn hàng từ CRM · 2. Xuất danh sách hội thoại từ công cụ chăm sóc khách hàng · 3. Dò tay số điện thoại khách giữa 2 danh sách · 4. Đánh dấu đơn khớp được nguồn/nhân viên · 5. Tổng hợp tỉ lệ khớp theo kênh |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, dò tay từng số điện thoại — **chưa đo thật**, cần tự bấm giờ tối thiểu 5-10 đơn trước khi chốt số, không dùng số đoán |
| Impact (nếu không giải thì sao) | Không biết chính xác kênh/nhân viên nào mang lại đơn thật → phân bổ ngân sách quảng cáo sai, đánh giá hiệu suất nhân viên không công bằng. Rủi ro phụ: nếu không có quyền truy cập đầy đủ dữ liệu hội thoại CSKH, phạm vi phải thu hẹp lại chỉ dùng SĐT đã có sẵn trong hệ thống (Rule), không mở rộng đọc nội dung hội thoại |
| Success metric (baseline → target) | Tỉ lệ đơn khớp được nguồn: **baseline chưa đo**, cần đo thật trước khi vào CP4; target tạm đặt tăng thêm tối thiểu 20 điểm % so với baseline đo được |
| Phương án không dùng AI | Rule: khớp tự động theo số điện thoại sạch có sẵn trong cả 2 hệ thống (không cần suy đoán) — đây là phương án mặc định, không cần đọc nội dung hội thoại nên không vướng rủi ro quyền truy cập |
| Giả thuyết về AI (nếu có) | AI chỉ xét thêm cho phần KHÔNG khớp được bằng Rule (SĐT không trùng trực tiếp) — mức rủi ro cao hơn, output phải được người kiểm tra lại trước khi dùng, không tự động tin |
| Cảm nhận nhanh | Rule (mặc định); Workflow chỉ khi cần xử lý thêm phần không khớp bằng Rule |

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

- Card số: 2 — Đối chiếu nguồn đơn hàng qua hội thoại CSKH
- Vì sao: đây là pain ảnh hưởng tới nhiều người nhất (không chỉ mình mà cả nhân viên CSKH và quản lý), có impact rõ ràng tới việc phân bổ ngân sách quảng cáo và đánh giá hiệu suất nhân viên công bằng hay không
- Câu hỏi muốn nhóm phản biện: Nếu không có quyền truy cập đầy đủ dữ liệu hội thoại CSKH (giới hạn bảo mật dữ liệu khách hàng), candidate này có còn khả thi trong phạm vi 1 buổi lab không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Baseline vẫn còn placeholder "[ĐIỀN: ? phút/đơn]" ở cả Bottleneck và Success metric — chưa có số thật nào, không thể đưa ra pitch với baseline rỗng | Đồng ý | Sửa Bottleneck và Success metric: bỏ dấu "?" mơ hồ, ghi rõ đây là số **chưa đo**, cần tự bấm giờ thật tối thiểu 5-10 đơn trước khi chốt số, không được đoán |
| Actor ghi "Performance marketer + nhân viên chăm sóc khách hàng" nhưng Job Story viết từ góc nhìn một người ("tôi cần biết...") — không rõ actor CHÍNH là ai, dễ gây nhầm lẫn khi vẽ quy trình ở CP5 | Đồng ý | Làm rõ actor chính là performance marketer (người cần kết quả đối chiếu để ra quyết định ngân sách); nhân viên CSKH là actor phụ (người giữ dữ liệu hội thoại, không trực tiếp hưởng lợi từ việc đối chiếu) |
| "Cảm nhận nhanh" chọn Rule, nhưng "Giả thuyết về AI" lại nói cần AI khi SĐT không khớp — hai ý này chưa rõ ranh giới (boundary): khi nào dừng ở Rule, khi nào mới cần thêm AI | Đồng ý | Thêm ghi chú: mặc định chạy Rule (khớp SĐT trực tiếp); chỉ xét thêm AI cho phần KHÔNG khớp được bằng Rule, và phải coi đây là phần rủi ro cao hơn, cần review tay trước khi dùng kết quả |
| Dữ liệu hội thoại CSKH chứa SĐT khách hàng (PII) — card chưa nhắc gì tới rủi ro quyền truy cập/bảo mật, trong khi đây đã được chính người viết (mình) ghi là "điều còn chưa chắc" ở bảng chọn top 3 | Đồng ý một phần | Thêm vào "Impact": nếu không giải được bài toán quyền truy cập dữ liệu hội thoại, candidate này có thể phải thu hẹp phạm vi (chỉ dùng dữ liệu nội bộ sẵn có, không mở rộng ra nguồn hội thoại mới) — chưa coi đây là lý do loại bỏ candidate, vì Rule (khớp SĐT) không cần đọc nội dung hội thoại, chỉ cần SĐT đã có sẵn trong hệ thống |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | Pitch lần lượt cả 3 card theo thứ tự Card 2 (đối chiếu nguồn đơn), Card 1 (tổng hợp báo cáo quảng cáo), Card 3 (rà soát chiến dịch lỗ mỗi sáng) | Cả 3 card được nhóm ghi nhận |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt (dùng chung cho cả 3 bài của Hải/Minh/Báo): "Nếu vấn đề này không được giải quyết thì hậu quả lớn nhất là gì?" | [ĐIỀN: câu trả lời/thay đổi cụ thể của từng bạn sau câu hỏi này — ghi riêng cho Hải, Minh, Báo] |
| Nhận phản biện | Câu hỏi tôi nhận được: nhóm hỏi sâu thêm về bản chất của từng vấn đề trong 3 card. Riêng Hải hỏi cho Card #1 (Tổng hợp báo cáo hiệu suất quảng cáo đa chi nhánh): *"Dữ liệu TKQC và CRM thường có độ trễ (delay) hoặc sai số tracking. AI có giải quyết được sự sai lệch dữ liệu gốc này không, hay chỉ giúp cộng trừ nhanh hơn?"* | Tôi đã sửa gì: (1) Từ việc trả lời riêng lẻ từng câu hỏi, tôi nhận ra cả 3 card đều cùng một gốc — **phân mảnh dữ liệu** (dữ liệu bị chia nhỏ ở nhiều nền tảng, nhiều công ty/tài khoản quảng cáo khác nhau, không nằm chung một chỗ). Tôi tóm gọn lại pattern này để trình bày rõ hơn thay vì để 3 card rời rạc. (2) Trả lời Hải: đây là vấn đề chất lượng dữ liệu đầu vào (data pipeline) — nằm ngoài phạm vi (boundary) của bước AI; AI chỉ xử lý số đã có sẵn, không tự phát hiện/sửa được độ trễ hay sai tracking ở tầng dữ liệu gốc |
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
