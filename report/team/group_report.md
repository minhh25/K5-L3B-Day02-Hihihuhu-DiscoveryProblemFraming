# Báo cáo nhóm — Day 02 Discovery & Problem Framing

> Bản chung của nhóm, viết trên repo do nhóm trưởng fork. Không copy file này sang repo cá nhân.
> Template chi tiết và prompt mẫu: [docs/01-worksheet.md](../../docs/01-worksheet.md). Bài mẫu: [docs/02-deliverable-example.md](../../docs/02-deliverable-example.md).

## 1. Thông tin nhóm

- Tên nhóm: **Hihihuhu**
- Thành viên: Hải, Minh, Bảo, Hùng; thông tin đầy đủ xem `TEAM.md`.
- Candidate problem được chọn (1 câu): **Candidate Performance Marketer của Hùng — Khi đến kỳ báo cáo, người phụ trách performance marketing muốn tổng hợp chi phí từ 9 tài khoản quảng cáo (TKQC) và đối chiếu doanh thu CRM theo 3 chi nhánh, để tính nhất quán %CPQC và ROAS phục vụ đánh giá hiệu quả quảng cáo.**
- Quyết định cuối: **Not Yet** — ưu tiên hướng **Rule**, cần xác minh dữ liệu, cách tính và baseline trước khi pilot; chưa có cơ sở triển khai AI.

---

## 2. Hội tụ nhóm (CP3)

### 2.1. Pitch

|   # | Người đưa ra | Candidate (Job Story ngắn)                                                                                                                           | Actor                                    | Bottleneck                                                                                                    | Câu hỏi phản biện nhận được (ai hỏi)                                                                                                                                                                                        |
| --: | ------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Hải          | Khi nộp CV, tôi muốn thể hiện kinh nghiệm phù hợp với JD rõ ràng, để hồ sơ được xem xét đúng năng lực.                                               | Ứng viên                                 | Viết lại kinh nghiệm và căn chỉnh format: 60 phút theo pitch.                                                 | Minh: Thêm từ khóa để vượt ATS khi không có kỹ năng thật có làm giảm chất lượng tuyển dụng? Các vòng sau vẫn kiểm tra chuyên môn, thêm từ khóa không thay thế năng lực.                                                     |
|   2 | Hải          | Khi làm bài test tuyển dụng, tôi muốn hiểu bối cảnh ngành và xác định hướng làm, để không mất thời gian mò mẫm.                                      | Ứng viên                                 | Tìm insight thị trường và hướng đi ban đầu: 3 giờ theo pitch.                                                 | Hùng: Nếu không giải quyết thì hậu quả lớn nhất là gì? Trả lời: ứng viên khó định hướng và điều chỉnh bản thân phù hợp vị trí.                                                                                              |
|   3 | Hải          | Khi chuẩn bị phỏng vấn, tôi muốn hiểu thông tin và văn hóa công ty, để chuẩn bị phù hợp.                                                             | Ứng viên                                 | Thu thập thông tin nhiều nguồn và kiểm tra phản ánh tiêu cực: 3 giờ theo pitch.                               | Bảo: Lấy thông tin văn hóa từ đâu khi nhiều công ty không công bố? Trả lời: tham khảo thông tin chia sẻ công khai; chưa có bằng chứng xác nhận văn hóa của công ty cụ thể.                                                  |
|   4 | Minh         | Khi ứng viên nộp technical test, tôi muốn xác minh năng lực thực tế, để tránh đánh giá chỉ dựa vào bài nộp.                                          | HR Recruiter, Tech Lead, Hiring Manager  | Kiểm tra lại tư duy và khả năng giải thích; Excel chưa ghi thời gian.                                         | Hải: Nếu ứng viên dùng AI nhưng vẫn hiểu và giải thích được thì sao? Trả lời: dùng công cụ hỗ trợ không phải vấn đề; cần kiểm tra khả năng hiểu và vận dụng.                                                                |
|   5 | Minh         | Khi ứng viên đã nhận offer nhưng chưa đi làm, tôi muốn làm rõ sớm các trở ngại, để hạn chế gián đoạn tuyển dụng.                                     | HR Recruiter, ứng viên, Hiring Manager   | Chưa biết ứng viên đổi ý cho tới khi họ thông báo hoặc không nhận việc; chưa có thời gian đo.                 | Hải hỏi cách nhận biết khi ứng viên có thể nhận offer khác; Hùng hỏi hậu quả; Bảo hỏi rủi ro nếu giải pháp sai. Trả lời: không dự đoán chắc cam kết; tập trung vướng mắc có thể kiểm chứng, tránh đánh giá thiếu công bằng. |
|   6 | Minh         | Khi nhận yêu cầu tuyển dụng, tôi muốn thống nhất kỹ năng, kinh nghiệm và ngân sách, để không tìm theo tiêu chí thiếu khả thi hoặc thay đổi liên tục. | HR Recruiter, Hiring Manager, HR Manager | Trao đổi và sửa JD nhiều lần; Excel chưa ghi số lần hoặc thời gian.                                           | Hải: Thông tin chưa rõ hay Hiring Manager thay đổi nhu cầu? Trả lời: cần tách hai nguyên nhân và kiểm chứng nguyên nhân chính.                                                                                              |
|   7 | Bảo          | Khi chuẩn bị meetup thứ Sáu sau nhiều thay đổi được merge, tôi muốn biết thay đổi nào đáng trình bày kèm nguồn, để báo cáo chính xác.                | EM/Tech Lead phụ trách báo cáo thay đổi  | Đọc mô tả/diff: khoảng 40 phút/lần; tổng quy trình khoảng 170 phút/tuần theo pitch.                           | Minh: Thế nào là thay đổi đáng báo cáo; mọi PR có giá trị với người dùng không? Trả lời: cần tiêu chí từ quy trình review và báo cáo của Tech Lead.                                                                         |
|   8 | Bảo          | Khi ticket/email đến đầu ngày, tôi muốn phân loại và chuyển đúng người, để xử lý việc gấp trước.                                                     | CS trực phân loại                        | Khoảng 1,5 phút/ticket, 12% chuyển nhóm sai, 1.500 ticket/tháng theo pitch.                                   | Hải hỏi sai số và trách nhiệm khi bỏ sót ticket khẩn; Hùng hỏi vấn đề cốt lõi và hậu quả. cần baseline, tiêu chí chất lượng rõ và fallback; chưa có kết quả hệ thống mới.                                                   |
|   9 | Bảo          | Khi vừa họp xong, tôi muốn ghi rõ biên bản, quyết định và việc cần làm kèm người phụ trách, để không bỏ sót.                                         | Người chủ trì họp, PM/Lead               | Viết biên bản/action item: khoảng 25 phút/cuộc, 15 cuộc/tuần theo pitch.                                      | Minh: Phân biệt đề xuất đang tranh luận với quyết định chính thức thế nào? Trả lời: ghi lại rồi review nội dung; vẫn cần người chủ trì xác nhận quyết định.                                                                 |
|  10 | Hùng         | Khi tới kỳ báo cáo, tôi muốn gom chi phí TKQC và đối chiếu CRM theo chi nhánh, để tính %CPQC/ROAS nhất quán.                                         | Performance Marketer                     | Tự mở 9 TKQC và đối chiếu CRM theo 3 chi nhánh: khoảng 45 phút/lần, 2 lần/tuần, tổng 90 phút/tuần theo pitch. | Hải: AI có giải quyết độ trễ và sai tracking của dữ liệu gốc hay chỉ cộng trừ nhanh hơn? Trả lời của Hùng trong Excel: chất lượng data pipeline nằm ngoài phạm vi bước AI.                                                  |
|  11 | Hùng         | Khi cần biết đơn tới từ nguồn nào, tôi muốn đối chiếu hội thoại CSKH với đơn CRM, để xác định kênh và nhân viên tạo đơn.                             | Performance Marketer, nhân viên CSKH     | Dò số điện thoại giữa 2 hệ thống: khoảng 5 phút/đơn, 20 đơn/tuần, tổng 100 phút/tuần theo pitch.              | Bảo hỏi làm rõ yêu cầu. vấn đề cốt lõi là dữ liệu bị phân mảnh.                                                                                                                                                             |
|  12 | Hùng         | Khi kiểm tra hiệu suất hôm trước, tôi muốn nhận biết chiến dịch có chỉ số chi phí vượt ngưỡng, để kịp xem xét điều chỉnh.                            | Performance Marketer                     | Tự tính %CPQC cho 9 TKQC: khoảng 15 phút/ngày làm việc, tổng 75 phút/tuần theo pitch.                         | Chưa có phản biện                                                                                                                                                                                                           |

Các Job Story được biên tập gọn, giữ mục đích của bản pitch. Riêng #1 bỏ cách diễn đạt “khớp từ khóa tự động” khỏi phần problem; #12 tách chỉ số quảng cáo khỏi kết luận lợi nhuận.

### 2.2. Cluster

| Cluster                                       | Các candidate  | Pattern chung                                                                                  |
| --------------------------------------------- | -------------- | ---------------------------------------------------------------------------------------------- |
| A — Chuẩn bị ứng tuyển và thống nhất tiêu chí | #1, #2, #3, #6 | Thiếu thông tin có căn cứ hoặc tiêu chí rõ để chuẩn bị, tìm kiếm và đánh giá đúng.             |
| B — Xác minh và theo dõi tuyển dụng           | #4, #5         | Khó xác minh năng lực hoặc các trở ngại của ứng viên từ dữ liệu hiện có; dễ suy đoán quá mức.  |
| C — Tổng hợp thông tin và việc cần làm        | #7, #9         | Thông tin nhiều, cần lọc ý quan trọng và xác nhận kết luận trước khi báo cáo.                  |
| D — Phân loại và chuyển xử lý                 | #8             | Nhiều đầu vào cần phân nhóm, xác định mức ưu tiên và chuyển đúng người.                        |
| E — Đối chiếu dữ liệu hiệu quả quảng cáo      | #10, #11, #12  | Chi phí, doanh thu và nguồn đơn phân tán; mất thời gian đối chiếu trước khi đánh giá hiệu quả. |

### 2.3. Opportunity Solution Tree rút gọn

Gốc là **1 outcome**. Nhánh là **opportunity** (nhu cầu, pain), không phải tính năng hay công cụ.

```text
OUTCOME: Giảm thời gian chuẩn bị một báo cáo quảng cáo của 3 chi nhánh
        từ khoảng 45 xuống không quá 30 phút, vẫn đối soát được số liệu.
        (45 phút: ước lượng trong pitch; 30 phút: target đề xuất.)
├── Opportunity A: Chi phí nằm ở 9 TKQC, phải mở và lấy số từng nguồn.
├── Opportunity B: Chi phí và doanh thu CRM chưa được đối chiếu cùng kỳ,
│                 cùng chi nhánh và cùng quy tắc ghi nhận doanh thu.
└── Opportunity C: Mất công cộng số, tính chỉ số và truy lại nguồn khi lệch.
```

Những ý đã gạch bỏ vì là solution đội lốt opportunity:

- “Dashboard tự động cho mọi chi nhánh”: là giải pháp, không phải nhu cầu.
- “Agent tự tìm chiến dịch lỗ rồi tắt quảng cáo”: là giải pháp, mở rộng sang hành động ngân sách ngoài phạm vi #10.
- “AI sửa dữ liệu tracking sai”: là đề xuất chưa có cơ sở; dữ liệu sai phải được phát hiện và chuyển người phụ trách xử lý.

### 2.4. Chấm điểm shortlist (1–5)

| Candidate                                              | Actor rõ | Quy trình rõ | Pain có bằng chứng | Impact đo được | Vừa sức lab | So sánh được No AI/Rule/Workflow/Agent | Nhóm hiểu domain |      Tổng |
| ------------------------------------------------------ | -------: | -----------: | -----------------: | -------------: | ----------: | -------------------------------------: | ---------------: | --------: |
| #10 — Hùng: Báo cáo chi phí quảng cáo/CRM đa chi nhánh |        5 |            5 |                  2 |              5 |           5 |                                      4 |                3 | **29/35** |
| #7 — Bảo: Tổng hợp thay đổi phần mềm trước meetup      |        5 |            4 |                  2 |              4 |           4 |                                      5 |                3 | **27/35** |
| #6 — Minh: Thống nhất yêu cầu tuyển dụng/JD            |        5 |            4 |                  1 |              3 |           5 |                                      3 |                3 | **24/35** |

Điểm là **đánh giá đề xuất**, không phải kết quả bỏ phiếu đã ghi nhận. “Pain có bằng chứng” chỉ đạt 2 ở #10/#7 vì có ước lượng trong pitch nhưng chưa có log; #6 đạt 1 vì chưa có cả tần suất/thời gian. “Nhóm hiểu domain” tạm để 3 do Excel thể hiện khả năng trao đổi về case, chưa chứng minh cả nhóm có trải nghiệm nghề nghiệp tương ứng. #10 có đầu ra số học rõ nên dễ đo và thử trong phạm vi nhỏ; chưa cho điểm tối đa ở khả năng so sánh 4 mức vì nhu cầu AI chưa rõ.

**Candidate được chọn:** **#10 — Candidate Performance Marketer của Hùng: tổng hợp chi phí 9 TKQC, đối chiếu CRM theo 3 chi nhánh để tính %CPQC/ROAS.** Đây là lựa chọn theo yêu cầu của người học, đồng thời đứng đầu bảng điểm đề xuất.

**Vì sao chọn:** Actor cụ thể; có tần suất 2 lần/tuần và mức thời gian 45 phút/lần trong pitch; đầu vào và kết quả có thể kiểm tra bằng phép tính. Có thể thử trên bản xuất dữ liệu được phép sử dụng, không cần thay đổi hệ thống đang chạy. Phản biện của Hải cũng xác định rõ ranh giới giữa tổng hợp báo cáo và sửa tracking.

**Vì sao loại các candidate còn lại:**

- #7 cần thống nhất “đáng báo cáo” theo đánh giá của Tech Lead; khó chấm chất lượng nếu chưa có bộ ví dụ đã duyệt.
- #6 đáng kiểm chứng nhưng chưa có baseline về số vòng sửa JD hoặc thời gian kéo dài; nguyên nhân có thể là yêu cầu thay đổi chứ không phải thiếu rõ ràng.
- #11 của Hùng để vòng sau vì cần quy tắc quy nguồn đơn và đối chiếu dữ liệu khách hàng; không gộp bài toán attribution vào phép cộng báo cáo.
- #12 của Hùng để vòng sau vì nhận biết “lỗ” và quyết định tắt quảng cáo cần thêm chi phí ngoài quảng cáo, độ trễ chuyển đổi và người duyệt.

---

## 3. Kiểm chứng + research giải pháp đã có (CP4)

### 3.1. Assumption Map

|   # | Giả định                                                                                              | Loại (Value / Usability / Feasibility / Viability) | Quan trọng (1–5) | Đã có bằng chứng (1–5) | Kiểm chứng trước?                                                                                                                                                                                                                             |
| --: | ----------------------------------------------------------------------------------------------------- | -------------------------------------------------- | ---------------: | ---------------------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|   1 | Báo cáo thực sự mất khoảng 45 phút/lần, 2 lần/tuần; đối chiếu số liệu là việc lặp lại đáng cải thiện. | Value                                              |                5 |                      3 | Có — đo lại ít nhất 2 kỳ báo cáo. Đã có quan sát trực tiếp 1 kỳ (xem snapshot dưới) xác nhận có thao tác tay lặp lại; chưa đo đủ 2 kỳ để chốt baseline thời gian.                                                                             |
|   2 | Có thể xuất đủ dữ liệu chi phí của 9 TKQC và doanh thu CRM được phép sử dụng.                         | Feasibility                                        |                5 |                      3 | Có — kiểm file mẫu và quyền truy cập trước. Snapshot 09/11/2026 đã xác nhận đúng 9 TKQC (1+3+5 theo 3 chi nhánh) và tổng CPQC khớp giữa 2 tab, nhưng mới quan sát trên dashboard, chưa thử xuất file thật để dùng cho Rule.                   |
|   3 | Có quy tắc gán chi phí, doanh thu về 3 chi nhánh và quy tắc ghi nhận doanh thu thống nhất.            | Feasibility                                        |                5 |                      1 | Có — thiếu quy tắc thì chưa tính chỉ số. Snapshot xác nhận có mapping TKQC→chi nhánh trên dashboard, nhưng quy tắc ghi nhận doanh thu CRM (đơn hoàn/hủy, thuộc kỳ nào) vẫn chưa xác nhận.                                                     |
|   4 | Nguồn dữ liệu có mốc cập nhật và cách chốt kỳ đủ rõ để đối soát dù có độ trễ.                         | Feasibility                                        |                5 |                      3 | Có — phản biện của Hải đã nêu rủi ro; nay có log thật củng cố: dòng trạng thái "23 TKQC lỗi" và "Business Manager quét lần cuối lệch ~7 tuần" trong snapshot 09/11/2026 là bằng chứng độ trễ/sai tracking có thật, không còn chỉ là suy đoán. |
|   5 | Marketer kiểm tra và sửa được báo cáo theo mẫu trong tối đa 30 phút/lần, gồm cả lấy dữ liệu.          | Usability                                          |                4 |                      1 | Có — thử thao tác trên cùng bộ dữ liệu với cách cũ.                                                                                                                                                                                           |
|   6 | Đơn vị cho phép xử lý bản xuất dữ liệu; có người phụ trách và chi phí vận hành được chấp nhận.        | Viability                                          |                5 |                      1 | Có — xác nhận trước mọi pilot trên dữ liệu thật.                                                                                                                                                                                              |

Giả định nhóm kiểm chứng trong buổi này: **#2 và #4 đã có bằng chứng quan sát trực tiếp một phần** (xem snapshot 09/11/2026 ở mục 3.2), #1/#3/#5/#6 vẫn chưa kiểm. Ưu tiên đề xuất tiếp theo là #3 và #6, vì nếu không thống nhất quy tắc ghi nhận doanh thu hoặc chưa có quyền dùng dữ liệu thì chưa thể lập báo cáo đúng; sau đó đo lại #1 cho đủ 2 kỳ và thử #5.

### 3.2. Kiểm chứng

Cách đã dùng: **(a)** đọc bảng pitch và phản biện trong Excel; **(b)** Hùng tự quan sát trực tiếp dashboard báo cáo Sale–Marketing nội bộ đang dùng thật trong công việc, ghi lại thành snapshot có số liệu cụ thể — xem [`report/assets/cp1-tkqc-snapshot.md`](../assets/cp1-tkqc-snapshot.md), quan sát lúc 09/11/2026, kỳ xem tháng 11/2026; **(c)** phỏng vấn 3 người theo bảng dưới (Người 1 tháng 9/2026, Người 2 và Người 3 ngày 15/10/2026) — bằng chứng hành vi/log có thật, mạnh hơn ước lượng trong pitch. Sheet `CP4` trong Excel nguồn vẫn trống.

Interview snapshot — 1 bảng chung, mỗi cột 1 người:

| Trường                                                 | Người 1 (thật)                                                                                                                                | Người 2 (thật)                                                                                                                | Người 3 (thật)                                                               |
| ------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------- |
| Vai trò (không ghi tên thật)                           | Performance Marketer 1                                                                                                                        | Performance Marketer 2, công ty khác cùng ngành                                                                               | Nhân viên CSKH/CRM, phụ trách nhập đơn theo chi nhánh                        |
| Nơi làm việc / quy mô                                  | Công ty (cùng ngành/quy mô với case của Hùng; không định danh cụ thể)                                                                         | doanh nghiệp bán lẻ ~5-10 TKQC, 2-3 chi nhánh                                                                                 | cùng công ty với Người 1, bộ phận CSKH                                       |
| Thời điểm hỏi                                          | Tháng 9/2026 — _cần ghi rõ ngày cụ thể hơn nếu nhớ được_                                                                                      | 15/10/2026                                                                                                                    | 15/10/2026 (cùng buổi với Người 2)                                           |
| Hình thức hỏi                                          | Chat                                                                                                                                          | gọi điện 15 phút                                                                                                              | hỏi trực tiếp                                                                |
| Lần báo cáo gần nhất: đã mở những nguồn nào?           | Nguồn trực tiếp từ CRM, TKQC                                                                                                                  | Ads Manager của 2 nền tảng + file Excel CRM xuất tay                                                                          | không trực tiếp làm báo cáo, chỉ nhập đơn vào CRM                            |
| Bước nào lâu nhất, mất bao lâu?                        | So khớp thông tin giữa các bảng dữ liệu — _chưa có số phút cụ thể_                                                                            | lọc trùng đơn giữa 2 nền tảng, ước lượng ~20 phút/lần theo lời kể                                                             | tra lại số điện thoại khách khi đơn thiếu nguồn, ~5 phút/đơn theo lời kể     |
| Lần lệch số gần nhất: đã xử lý ra sao?                 | Chấp nhận sai số — _câu trả lời ở mức chính sách chung, chưa phải 1 sự việc cụ thể_                                                           | tháng trước lệch ~8%, đã báo quản lý và làm lại thủ công, chưa có quy trình chuẩn                                             | không nhớ rõ trường hợp cụ thể, chỉ nói chung "hay bị thiếu thông tin nguồn" |
| Công cụ đang dùng đã giải được phần nào, còn thiếu gì? | Thiếu khả năng breakdown cụ thể theo từng chi nhánh, ngày, nhân viên                                                                          | Excel + công thức tay; thiếu tự động đối chiếu theo chi nhánh                                                                 | CRM có tìm theo SĐT nhưng không liên kết sẵn với dữ liệu quảng cáo           |
| Câu nói đáng nhớ nhất (nguyên văn)                     | _Chưa có — bổ sung nếu nhớ lại được_                                                                                                          | "Tháng nào làm báo cáo tôi cũng phải mở 4-5 tab cùng lúc."                                                                    | "Nhiều đơn không biết từ đâu ra, đành ghi 'không rõ nguồn'."                 |
| Tín hiệu xác nhận pain (hành vi/cam kết đã xảy ra)     | Đã yêu cầu Hùng xây dashboard báo cáo để tổng hợp thông tin                                                                                   | Đã từng tự viết macro Excel để đỡ phải gộp tay                                                                                | Đã đề xuất với quản lý thêm cột "nguồn đơn" bắt buộc khi nhập CRM            |
| Tín hiệu phản bác                                      | _Chưa có_                                                                                                                                     | "Cũng không mất nhiều thời gian lắm, 20 phút là bình thường."                                                                 | không có pain rõ, vì không phải người trực tiếp làm báo cáo                  |
| Insight / opportunity rút ra                           | Không có cách tự xem breakdown chi phí/doanh thu theo chi nhánh, ngày, nhân viên — phải chờ người khác tổng hợp thủ công mới thấy đủ chi tiết | lọc trùng đơn giữa nhiều nền tảng tốn thời gian hơn bước cộng số thuần                                                        | thiếu nguồn đơn ngay từ lúc nhập CRM, không chỉ ở bước tổng hợp cuối kỳ      |

Tổng hợp:

| Nguồn                                                   |                                           Số người / số mẫu | Tín hiệu xác nhận                                                                                            | Tín hiệu phản bác                                                                                                                                                                                                                                                |
| ------------------------------------------------------- | ----------------------------------------------------------: | ------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Sheet `Trang tính1`, B11:F11                            |                     1 candidate và phần phản biện tương ứng | Có mô tả actor, quy mô 9 TKQC/3 chi nhánh, ước lượng 45 phút/lần và tần suất.                                | Hải nêu độ trễ và sai tracking; Hùng xác định đây là vấn đề dữ liệu nguồn ngoài phạm vi bước AI. Đây là phản biện trong pitch, chưa phải quan sát ngoài nhóm.                                                                                                    |
| `cp1-tkqc-snapshot.md` (quan sát trực tiếp, 09/11/2026) | 1 người (Hùng), 1 kỳ, dữ liệu thật trên dashboard đang dùng | Xác nhận đúng 9 TKQC/3 chi nhánh, %CPQC thật 22,55%, và 3 thao tác tay bắt buộc mới ra được số liệu đúng kỳ. | "23 TKQC lỗi" gán sai nguồn chi phí ở lần quét gần nhất (~1/4 tổng số), và mốc quét Business Manager lệch ~7 tuần — cho thấy rủi ro Feasibility #4 là có thật, không chỉ suy đoán. Vẫn là quan sát của 1 người trong nhóm, không phải bằng chứng từ người ngoài. |
| Sheet `CP4`                                             |                                                   0 bản ghi | Sheet gốc trong Excel nguồn vẫn trống; thay vào đó nhóm dùng bảng interview snapshot dưới đây làm bằng chứng CP4.                                                           | Không áp dụng.                                                                                               |
| Interview snapshot — Người 1/2/3 (mục 3.2, Người 1 tháng 9/2026, Người 2–3 ngày 15/10/2026) | 3 người ngoài nhóm (2 Performance Marketer, 1 nhân viên CSKH/CRM) | Cả 3 người đều có ít nhất 1 tín hiệu hành vi/cam kết đã xảy ra (dashboard, macro Excel, đề xuất thêm cột "nguồn đơn"); Người 2 nêu cụ thể 1 lần lệch số ~8% đã xử lý thủ công. | Người 2: "Cũng không mất nhiều thời gian lắm, 20 phút là bình thường" — phản bác mức độ nghiêm trọng của pain. Người 3 không có pain rõ vì không trực tiếp làm báo cáo — cho thấy pain tập trung ở vai trò Performance Marketer, không lan rộng sang CSKH. |

**Nhóm đã sửa problem thế nào sau kiểm chứng:** Sau khi có snapshot thật và 3 interview, nhóm xác nhận thêm rằng bottleneck không chỉ là "đối chiếu dữ liệu" (ước lượng 15 phút) mà còn gồm việc phát hiện dữ liệu sai/thiếu trước khi đối chiếu được (ví dụ 23/9 TKQC từng bị gán sai nguồn chi phí ở snapshot, và lệch ~8% một lần theo lời Người 2) — rủi ro Feasibility trong mục 8.1 vẫn giữ mức Cao vì đây mới là quan sát 1 kỳ và 1 lần lệch số, chưa đủ để đổi mức rủi ro. Tín hiệu phản bác của Người 2 (20 phút là bình thường) cho thấy mức độ nghiêm trọng của pain có thể khác nhau giữa các đơn vị — nhóm giữ nguyên ước lượng 45 phút của Hùng làm baseline riêng cho case này, không gộp chung với số liệu của Người 2. **Điều chỉnh bản nháp từ phản biện trong Excel:** thu hẹp về tổng hợp/đối soát số liệu được cung cấp; phát hiện dữ liệu thiếu hoặc chưa đồng bộ thay vì kỳ vọng AI tự sửa tracking. Không bao gồm suy đoán nguồn đơn, kết luận lợi nhuận, tự tắt chiến dịch hoặc thay ngân sách.

### 3.3. Research giải pháp đã có

| Công cụ / case / pattern                                          | Link                                                                                                                                                                                                  | Giải bước nào trong quy trình?                                                             | Điểm mạnh                                                                      | Khoảng trống / rủi ro                                                                                                                                 | Bài học cho nhóm                                                                                                            |
| ----------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------- |
| Google Sheets — SUMIFS và mẫu đối soát                            | [Tài liệu SUMIFS của Google](https://support.google.com/docs/answer/3238496?hl=en)                                                                                                                    | Bước 4 hiện tại: cộng chi phí/doanh thu theo nhiều điều kiện, như kỳ báo cáo và chi nhánh. | Hàm cộng theo điều kiện có tài liệu chính thức; có thể dùng trong hướng Rule.  | Công thức không tự cung cấp dữ liệu thiếu hay quyết định cách quy nguồn doanh thu. Phải chuẩn hóa vùng dữ liệu và tiêu chí trước.                     | Thử mẫu bảng tính trước; không cần mô hình ngôn ngữ để thực hiện số học.                                                    |
| Looker Studio / Data Studio — kết hợp nguồn dữ liệu               | [Google: How blends work](https://docs.cloud.google.com/data-studio/how-blends-work)                                                                                                                  | Kết hợp dữ liệu ở bước 3–4 và hiển thị báo cáo sau đối soát.                               | Tài liệu chính thức mô tả kết hợp nguồn theo trường liên kết và các kiểu join. | Cần chọn trường ghép và mức tổng hợp đúng. Với 9 TKQC, đề xuất chuẩn hóa về bảng chi phí chung trước; chưa xác minh các connector thực tế của đơn vị. | Chỉ dùng dashboard sau khi thống nhất khóa chi nhánh/kỳ và quy tắc tổng hợp; không coi dashboard là cách sửa dữ liệu nguồn. |
| Supermetrics for Google Sheets — nạp dữ liệu và làm mới theo lịch | [Hướng dẫn Google Sheets](https://docs.supermetrics.com/docs/google-sheets), [Scheduled refresh](https://docs.supermetrics.com/v1/docs/how-to-create-and-manage-scheduled-refreshes-in-google-sheets) | Có thể hỗ trợ bước 1 nếu nguồn quảng cáo thực tế có connector và tài khoản được cấp quyền. | Có tài liệu chính thức về kết nối nguồn và làm mới báo cáo theo lịch.          | Chưa kiểm được nền tảng của 9 TKQC, CRM, quyền truy cập hoặc gói dịch vụ phù hợp. Không khẳng định công cụ hỗ trợ sẵn CRM của case.                   | Là lựa chọn khảo sát tiếp nếu lấy dữ liệu thủ công vẫn chiếm nhiều thời gian; chưa cần mua hay tích hợp để làm lab.         |

Các trang trên đã được mở kiểm tra ngày **09/11/2026**. Khả năng công cụ lấy từ tài liệu chính thức; nhận định “phù hợp với case” là phân tích đề xuất, chưa phải kết quả sử dụng tại đơn vị của Hùng.

---

## 4. Quy trình trước/sau (CP5)

### 4.1. Quy trình hiện tại

Sơ đồ (ASCII, Mermaid hoặc link ảnh trong `report/assets/`):

```text
HIỆN TẠI — MÔ HÌNH CẦN HÙNG XÁC NHẬN

[1 Mở và lấy chi phí từ 9 TKQC: 15 phút]
→ [2 Lấy doanh thu từ CRM: 5 phút]
→ [3 Đối chiếu kỳ, chi nhánh và dữ liệu thiếu/trùng: 15 phút] ← BOTTLENECK
→ [4 Cộng số liệu và tính %CPQC/ROAS: 7 phút]
→ [5 Kiểm tra, hoàn thiện và gửi báo cáo: 3 phút]

TỔNG: 45 phút/lần × 2 lần/tuần = 90 phút/tuần.
45 phút/lần và 2 lần/tuần: ước lượng ghi trong pitch.
Thời gian từng bước: phân rã minh họa, chưa được bấm giờ.
```

| Bước | Actor                                                           | Input                                                         | Output                                                                            | Thời gian / tần suất              | Ghi chú                                                                             |
| ---: | --------------------------------------------------------------- | ------------------------------------------------------------- | --------------------------------------------------------------------------------- | --------------------------------- | ----------------------------------------------------------------------------------- |
|    1 | Performance Marketer                                            | Quyền xem 9 TKQC, kỳ báo cáo cần lấy                          | Bản xuất chi phí có account/campaign ID, kỳ và mốc lấy dữ liệu                    | 15 phút/lần, 2 lần/tuần; minh họa | Chưa biết các tài khoản thuộc nền tảng nào và có xuất cùng định dạng không.         |
|    2 | Performance Marketer/người được cấp quyền CRM                   | Bộ lọc kỳ, trạng thái đơn và chi nhánh                        | Bản xuất doanh thu có mã bản ghi, chi nhánh, trạng thái và thông tin nguồn nếu có | 5 phút/lần; minh họa              | Cần xác định cách ghi nhận doanh thu, đơn hoàn/hủy và dữ liệu được phép sử dụng.    |
|    3 | Performance Marketer                                            | Hai bản xuất, danh mục đối chiếu chi nhánh và quy tắc chốt kỳ | Dữ liệu đã gắn chi nhánh, danh sách thiếu/trùng/lệch kỳ cần xử lý                 | 15 phút/lần; minh họa             | Bottleneck giả định của phần đối soát; không mặc định mỗi chi nhánh có đúng 3 TKQC. |
|    4 | Performance Marketer                                            | Dữ liệu đủ điều kiện tổng hợp và định nghĩa chỉ số            | Chi phí, doanh thu và chỉ số theo từng chi nhánh/toàn kỳ                          | 7 phút/lần; minh họa              | Tổng hợp hai nguồn riêng trước khi ghép; không nhân chi phí theo từng dòng đơn CRM. |
|    5 | Performance Marketer; người nhận báo cáo theo phân công thực tế | Bảng tổng hợp, dữ liệu gốc và danh sách ngoại lệ              | Báo cáo đã kiểm, ghi rõ phần chưa đủ dữ liệu                                      | 3 phút/lần; minh họa              | Chưa xác định vai trò người duyệt ngoài marketer; cần nhóm xác nhận.                |

**Bottleneck chính:** Bước 3 — đối chiếu dữ liệu cùng kỳ và đúng chi nhánh, tạm phân bổ 15 phút/lần. Bước lấy chi phí cũng dự kiến mất 15 phút; cần đo hai bước riêng để xác định nút thắt thực tế. Excel chỉ ghi tổng 45 phút cho cả việc mở TKQC và đối chiếu CRM, không chứng minh bước 3 đã là bước nghẽn lớn nhất.

**Định nghĩa chỉ số đề xuất để xác nhận với Hùng trước khi dùng:** Gọi C là chi phí quảng cáo của kỳ/chi nhánh, R là doanh thu CRM hợp lệ của cùng kỳ/chi nhánh và A là phần doanh thu đã được quy thuộc quảng cáo theo quy tắc được đơn vị chấp nhận. Khi đó `%CPQC = C / R × 100%`, còn `ROAS = A / C`. Đây là quy ước đề xuất vì Excel chưa nêu mẫu số; không tự dùng toàn bộ doanh thu chi nhánh làm doanh thu quảng cáo. Nếu đơn vị định nghĩa %CPQC theo doanh thu quy thuộc quảng cáo, phải đổi rõ R thành A trong đặc tả. Thiếu căn cứ xác định A thì ghi ROAS “chưa đủ dữ liệu”. Mẫu số bằng 0 hoặc thiếu dữ liệu thì không xuất tỷ lệ như một số hợp lệ. Không suy ra lợi nhuận từ hai chỉ số này.

### 4.2. Quy trình tương lai

Ghi rõ bước nào **Rule**, bước nào **AI**, bước nào **con người**, **boundary** ở đâu, **phương án quay về** khi AI sai.

```text
TƯƠNG LAI — HƯỚNG RULE, TARGET ĐỀ XUẤT 30 PHÚT/LẦN

[1 CON NGƯỜI lấy 9 bản xuất quảng cáo + CRM và nạp vào mẫu: 20 phút]
→ [2 RULE kiểm schema, kỳ, mốc cập nhật, trùng và mapping chi nhánh: 1 phút]
→ [3 CON NGƯỜI xử lý ngoại lệ / xác nhận bản ghi chưa rõ: 3 phút]
→ [4 RULE tổng hợp từng nguồn, ghép đúng mức và tính chỉ số: 1 phút]
→ [5 CON NGƯỜI đối soát tổng, duyệt và gửi báo cáo: 5 phút]

TỔNG KỲ VỌNG: 30 phút/lần × 2 lần/tuần = 60 phút/tuần.
Chưa có đo thử; mọi thời gian tương lai là mục tiêu thiết kế.
Giữ 20 phút lấy dữ liệu như mô hình hiện tại, chưa giả định đã có API/connector.

AI: không có bước xử lý bằng AI trong phương án chọn.
BOUNDARY: chỉ đọc bản xuất được cấp phép; không sửa dữ liệu CRM/TKQC,
không tự quy nguồn đơn, không tự gửi báo cáo hoặc điều chỉnh quảng cáo.
Thiếu file/khóa ghép/mốc cập nhật không đạt yêu cầu thì dừng tính phần bị ảnh hưởng,
ghi ngoại lệ cho marketer kiểm; không bù số hoặc tự điền bằng suy đoán.

PHƯƠNG ÁN QUAY VỀ: lỗi rule, schema hoặc đối soát không khớp thì dừng gửi,
dùng cách đối chiếu thủ công của kỳ đó, giữ bản xuất và ghi lại nguyên nhân.
Dữ liệu nguồn sai hoặc chưa đồng bộ phải chuyển người phụ trách xử lý.
```

Mẫu dự kiến gồm bảng chi phí, bảng doanh thu, danh mục đối chiếu chi nhánh và bảng ngoại lệ. Chi phí được cộng theo kỳ/chi nhánh độc lập với số đơn; doanh thu được kiểm trùng theo mã bản ghi đã thống nhất, xử lý trạng thái đơn và tổng hợp riêng trước khi ghép. Giữ dữ liệu chưa map trong danh sách ngoại lệ thay vì bỏ âm thầm. Mốc chốt kỳ, múi giờ, tiền tệ, cách tính thuế/hoàn hủy và ngưỡng dữ liệu đủ mới phải được xác nhận trước pilot; không mặc định các nguồn đã giống nhau.

### 4.3. Before / after

| Chỉ số               |                                                             Trước |                                         Sau (kỳ vọng) | Ghi chú                                                                                                                  |
| -------------------- | ----------------------------------------------------------------: | ----------------------------------------------------: | ------------------------------------------------------------------------------------------------------------------------ |
| Số bước              |                                                                 5 |                                                     5 | Hai mô hình chi tiết đều là đề xuất, chưa được quan sát trực tiếp.                                                       |
| Tổng thời gian       |                                  Khoảng 45 phút/lần; 90 phút/tuần |                   Không quá 30 phút/lần; 60 phút/tuần | Tiết kiệm kỳ vọng 15 phút/lần, 30 phút/tuần nếu tần suất giữ nguyên. Cùng phạm vi: lấy đủ dữ liệu đến duyệt/gửi báo cáo. |
| Số bước thủ công     |                                                               5/5 |                                                   3/5 | Con người vẫn lấy dữ liệu, xử lý ngoại lệ, duyệt/gửi; 2 bước còn lại dùng Rule.                                          |
| Bottleneck chính     | Đối chiếu chi nhánh/kỳ: tạm 15 phút; lấy dữ liệu cũng tạm 15 phút |                  Lấy bản xuất và nạp mẫu: tạm 20 phút | Cần đo để biết có nên khảo sát connector; không thêm AI để xử lý phần lấy số.                                            |
| Rủi ro mới phát sinh |                            Sao chép/đối chiếu thủ công có thể sai | Mapping hoặc công thức sai có thể lan sang nhiều dòng | Kiểm tổng từng nguồn, chặn ngoại lệ, kiểm lại bằng cách tính độc lập và giữ bản xuất.                                    |

---

## 5. Problem Statement v0 (CP5)

| Trường                                                                     | Nội dung                                                                                                                                                                                                                                                                                                         |
| -------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                                                  | Performance Marketer phụ trách báo cáo chi phí quảng cáo từ 9 TKQC và doanh thu CRM của 3 chi nhánh, theo candidate của Hùng.                                                                                                                                                                                    |
| **Quy trình**                                                              | Hai lần/tuần: lấy số từ các TKQC, lấy doanh thu CRM, đối chiếu kỳ/chi nhánh, tổng hợp và tính %CPQC/ROAS, kiểm tra rồi gửi báo cáo.                                                                                                                                                                              |
| **Bottleneck**                                                             | Phải đối chiếu dữ liệu phân tán trước khi tổng hợp; bước đối chiếu tạm 15 phút trong mô hình, cần đo riêng với thời gian lấy dữ liệu.                                                                                                                                                                            |
| **Impact**                                                                 | Pitch ước lượng khoảng 45 phút/lần, tổng 90 phút/tuần cho một người. Có nguy cơ báo cáo thiếu hoặc lệch số khi ghép sai kỳ/chi nhánh; chưa có tỷ lệ lỗi hay thiệt hại đã xác minh.                                                                                                                               |
| **Success Metric** (baseline → target, cách đo)                            | Từ khoảng 45 xuống không quá 30 phút/lần, cùng phạm vi từ lấy dữ liệu đến báo cáo đã duyệt. Đo lại ít nhất 2 kỳ theo cách hiện tại để xác lập baseline; sau khi đủ điều kiện, ghi thời gian từng bước trong 4 kỳ báo cáo của pilot 2 tuần. Target 30 phút là đề xuất và phải xem lại nếu baseline đo khác pitch. |
| **Boundary** (AI không được làm gì; khi nào cần con người kiểm tra — HITL) | Chỉ tổng hợp bản xuất được phép sử dụng; không tự sửa tracking, quy nguồn đơn chưa rõ hoặc điều chỉnh quảng cáo. Nếu cân nhắc AI về sau, AI không được tự tạo số, gửi báo cáo hoặc quyết định ngân sách. Marketer phải kiểm số liệu và ngoại lệ trước khi gửi.                                                   |

Phản biện nhận được (từ AI hoặc nhóm khác) và nhóm có đồng ý không:

- **Phản biện có trong Excel (Hải):** dữ liệu TKQC và CRM có độ trễ hoặc sai tracking thì AI không thể được mặc định là cách sửa dữ liệu gốc. Hùng đã trả lời đây là vấn đề data pipeline ngoài phạm vi bước AI. Bản nháp giữ ranh giới đó, thêm kiểm tra mốc cập nhật và chuyển ngoại lệ cho người phụ trách.
- **Phản biện AI khi biên tập:** v0 chỉ đặt mục tiêu thời gian thì báo cáo nhanh nhưng lệch số vẫn có thể được coi là đạt. Đề xuất sửa v1: thêm đối soát tổng, truy nguồn, quy tắc mẫu số và kiểm đủ 9 TKQC/3 chi nhánh. Nhóm đã đồng ý với đề xuất này; v1 ở mục 7 phản ánh đúng các bổ sung trên.

---

## 6. Mức can thiệp AI (CP6)

### 6.1. Ma trận độ mơ hồ × độ phức tạp

Bài của nhóm nằm ở ô: **Độ mơ hồ thấp × độ phức tạp cao về số nguồn và số bước**, với điều kiện quy tắc ghi nhận doanh thu, gán chi nhánh và chốt kỳ đã thống nhất.

Vì sao: Có 9 TKQC cộng CRM, nhiều bước lấy/kiểm/ghép số nối tiếp. Tuy vậy, cộng số và tính tỷ lệ có kết quả kiểm tra được, không cần sinh nhiều cách diễn giải. Những điểm chưa rõ về dữ liệu phải được người phụ trách chốt thành quy tắc trước, thay vì giao AI suy đoán. Nhiều nguồn chưa phải lý do chọn Agent.

### 6.2. So sánh 4 mức

| Mức                       | Phương án cho bài của nhóm                                                                                | Đủ khi nào                                                                                    | Rủi ro                                                                           | Chọn?                                                          |
| ------------------------- | --------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------- | -------------------------------------------------------------- |
| **No AI** (sửa quy trình) | Dùng chung mẫu, checklist nguồn, quy định chốt kỳ và danh mục chi nhánh; người dùng tự đối chiếu và tính. | Khối lượng nhỏ hoặc chuẩn hóa quy trình đã đạt target.                                        | Vẫn lặp thao tác đối chiếu/cộng số; hiệu quả thực tế chưa được đo.               | Là phương án nền và đối chứng trước khi tự động hóa.           |
| **Rule**                  | Mẫu bảng tính kiểm dữ liệu, tra danh mục chi nhánh, cộng số theo điều kiện và tính tỷ lệ; marketer duyệt. | Các trường dữ liệu và quy tắc đã rõ, có bản xuất và quyền sử dụng.                            | Mapping/công thức sai hoặc nguồn đổi schema; cần kiểm đối soát và fallback.      | **Ưu tiên đề xuất**, sau khi vượt điều kiện dữ liệu.           |
| **Workflow**              | Các bước định sẵn lấy số bằng Rule, thêm AI viết nhận định từ báo cáo đã đối soát, rồi người duyệt.       | Chỉ khi kiểm chứng thêm nhu cầu viết nhận định tốn thời gian mà Rule chưa đáp ứng.            | AI có thể suy diễn nguyên nhân hoặc bịa nhận định; thêm chi phí kiểm.            | Chưa chọn; candidate hiện tại tập trung gom số và tính chỉ số. |
| **Agent**                 | AI tự chọn nguồn, truy vấn, phân tích và đề xuất hành động nhiều vòng.                                    | Chỉ cân nhắc nếu có nhu cầu thực sự không định trước được bước xử lý và kiểm soát được quyền. | Phạm vi truy cập rộng, khó kiểm toán; nguy cơ sửa hoặc dùng số sai để hành động. | Không chọn; chưa có bằng chứng cần mức tự chủ này.             |

**Mức chọn:** **Rule** — phương án thiết kế ưu tiên, chưa phải hệ thống đã triển khai. Toàn bộ luồng tự động hóa không có mô hình AI nên gọi là Rule theo định nghĩa của lab.

**Vì sao không chọn mức đơn giản hơn:** Mẫu/checklist giúp thống nhất cách làm nhưng vẫn để người dùng lặp phép cộng và đối chiếu ở mỗi kỳ. Rule là phần bổ sung nhỏ có thể kiểm tra độc lập cho các thao tác đó. Tuy nhiên, chưa có phép đo chứng minh No AI không đủ; pilot phải so sánh mẫu thủ công đã chuẩn hóa với cùng mẫu có Rule. Nếu No AI đã đạt target với chất lượng tương đương và ít công duy trì hơn, chọn No AI. Chưa có nhu cầu đã xác nhận để nâng lên Workflow/Agent.

### 6.3. AI Canvas rút gọn

| Thành phần                                                        | Nội dung                                                                                                                                     |
| ----------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| **Prediction** — AI dự đoán / tạo ra gì?                          | Không áp dụng: chọn Rule, không có bước AI dự đoán hoặc sinh nội dung.                                                                       |
| **Judgment** — con người cân nhắc, quyết định gì?                 | Marketer/người phụ trách xác nhận quy tắc chỉ số, xử lý ngoại lệ và duyệt báo cáo. Đây là trách nhiệm vận hành Rule, không phải AI judgment. |
| **Action** — hành động cuối cùng là gì, ai làm?                   | Marketer gửi báo cáo đã duyệt; điều chỉnh quảng cáo là quyết định riêng ngoài phạm vi.                                                       |
| **Outcome** — đo kết quả bằng gì?                                 | Phút/báo cáo, độ khớp tổng tiền và chỉ số, số ngoại lệ được phát hiện trước khi gửi.                                                         |
| **Input** — AI cần dữ liệu đầu vào gì mỗi lần chạy? Có sẵn không? | AI không nhận dữ liệu. Rule cần bản xuất 9 TKQC, CRM, danh mục chi nhánh, kỳ/mốc cập nhật và quy tắc chỉ số; hiện chưa được cung cấp.        |
| **Feedback** — lấy phản hồi ở đâu để cải thiện?                   | Log đối soát, dòng marketer sửa và thời gian từng bước để sửa quy tắc; không dùng để huấn luyện AI.                                          |

Theo hướng dẫn CP6, AI Canvas không bắt buộc với Rule; bảng được giữ để đúng cấu trúc mẫu và làm rõ phần không áp dụng. Nhu cầu chính là tính số theo quy tắc cố định, chưa cần năng lực dự đoán hoặc tạo nội dung.

### 6.4. Hai câu hỏi của Google PAIR

- Người dùng muốn **được hỗ trợ (augment)** hay **giao hẳn việc (automate)**? Bằng chứng: Không áp dụng như một kết luận về AI vì chọn Rule. Phương án đề xuất tự động hóa tính toán, giữ con người duyệt; Excel chưa có interview xác nhận mức tự động hóa người dùng muốn.
- AI sai kiểu nào tệ hơn, **báo nhầm** hay **bỏ sót**? Vì sao, và thiết kế đã xử lý thế nào: Không có đầu ra AI để so sánh. Với Rule, bỏ sót TKQC hoặc gán sai chi nhánh đều có thể làm báo cáo lệch; thiết kế phải kiểm đủ nguồn, chặn ngoại lệ và đối soát tổng, chưa có bằng chứng để xếp một kiểu lỗi nguy hiểm hơn trong mọi tình huống.

---

## 7. Problem Statement v1 + tiêu chí đánh giá (CP6)

| Trường                                          | Nội dung                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| ----------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Actor**                                       | Performance Marketer báo cáo cho 3 chi nhánh từ 9 TKQC và CRM, trong trường hợp có bản xuất hợp lệ, danh mục chi nhánh và quy tắc ghi nhận doanh thu đã được xác nhận.                                                                                                                                                                                                                                                                                                |
| **Quy trình**                                   | Lấy bản xuất → Rule kiểm/đối chiếu danh mục → marketer xử lý ngoại lệ → Rule tổng hợp và tính chỉ số → marketer đối soát, duyệt và gửi.                                                                                                                                                                                                                                                                                                                               |
| **Bottleneck**                                  | Đối chiếu thủ công các nguồn trước khi tính số; thời gian phân rã chưa được đo. Phần lấy dữ liệu vẫn giữ thủ công trong pilot ban đầu.                                                                                                                                                                                                                                                                                                                                |
| **Impact**                                      | Ước lượng trong pitch: 45 phút/lần × 2 lần/tuần = 90 phút/tuần. Mục tiêu thiết kế 30 phút/lần tương ứng tiết kiệm 30 phút/tuần, chưa phải hiệu quả đã chứng minh.                                                                                                                                                                                                                                                                                                     |
| **Success Metric** (baseline → target, cách đo) | Sau khi đo baseline ít nhất 2 kỳ, thử 4 báo cáo trong 2 tuần: mỗi báo cáo không quá 30 phút trong cùng phạm vi lấy dữ liệu đến gửi; đủ 9 TKQC và trạng thái đủ/thiếu của cả 3 chi nhánh; tổng chi phí/doanh thu khớp bản xuất đã lọc theo quy tắc, chỉ cho phép sai số hiển thị do làm tròn đã thống nhất; mọi ngoại lệ phải hiển thị và được xử lý/ghi chú trước khi duyệt. Đối chiếu cùng bộ dữ liệu với cách tính độc lập; các chỉ số chất lượng chưa có baseline. |
| **Boundary**                                    | Không ghi ngược vào TKQC/CRM, không sửa tracking hoặc tự gán nguồn đơn, không kết luận lợi nhuận/tự điều chỉnh ngân sách. Chỉ dùng bản xuất được cấp phép; không đưa dữ liệu khách hàng lên repo. Báo cáo phải có mốc dữ liệu và người duyệt; thiếu căn cứ attribution thì ROAS ghi “chưa đủ dữ liệu”.                                                                                                                                                                |
| **AI intervention point**                       | **Không có** — việc tổng hợp, kiểm tra và tính tỷ lệ xử lý theo quy tắc; chưa có nhu cầu AI đã được kiểm chứng.                                                                                                                                                                                                                                                                                                                                                       |
| **Mức chọn**                                    | **Rule**, có điều kiện dữ liệu và đối soát trước khi sử dụng.                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Rủi ro & người kiểm tra**                     | Sai mapping, lệch kỳ/tiền tệ, tính trùng, nguồn chưa cập nhật hoặc mẫu số không hợp lệ. Marketer kiểm tổng và ngoại lệ mỗi kỳ; người phụ trách CRM/dữ liệu xác nhận quy tắc doanh thu. Phân công nhân sự thực tế cần được xác nhận.                                                                                                                                                                                                                                   |

**Thay đổi so với v0 và lý do:**

| Trường         | v0                                       | v1                                                                                                      | Vì sao đổi                                                                                                   |
| -------------- | ---------------------------------------- | ------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------ |
| Actor/phạm vi  | Marketer báo cáo 9 TKQC/3 chi nhánh      | Bổ sung điều kiện có bản xuất và quy tắc đã xác nhận                                                    | Tránh thiết kế dựa trên giả định dữ liệu đã sẵn sàng.                                                        |
| Success Metric | Thời gian khoảng 45 → tối đa 30 phút/lần | Giữ target, thêm đủ nguồn, đối soát tổng, truy ngoại lệ và phép đo cùng dữ liệu                         | Xử lý lỗ hổng “nhanh nhưng sai”; chất lượng phải đạt trước khi dùng báo cáo.                                 |
| Boundary       | Không sửa tracking hoặc tự hành động     | Thêm không ghi ngược, không suy nguồn đơn, không thay doanh thu quy thuộc quảng cáo bằng doanh thu tổng | Bảo đảm chỉ số có ý nghĩa và tránh lan phạm vi sang attribution/quyết định ngân sách.                        |
| Mức can thiệp  | Chưa chỉ định trong v0                   | Rule, không có AI intervention point                                                                    | Research và phân tích cho thấy đầu ra hiện tại là số học theo quy tắc; chưa có bằng chứng cần sinh nội dung. |

**Tiêu chí đánh giá đầu ra của AI (3–5 tiêu chí):**

Vì chọn **Rule**, áp dụng bảng này cho **đầu ra báo cáo và kiểm tra của Rule**, theo hướng dẫn CP6; không chấm một đầu ra AI giả định.

|   # | Tiêu chí                            | Đạt khi                                                                                                                                                                                   | Không đạt khi                                                                                                      |
| --: | ----------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------ |
|   1 | Đủ nguồn và đúng kỳ                 | Xác nhận đủ 9 TKQC; hiển thị trạng thái của 3 chi nhánh, kỳ, tiền tệ và mốc lấy dữ liệu; nguồn chưa đạt điều kiện bị đánh dấu.                                                            | Bỏ nguồn, trộn kỳ/tiền tệ hoặc dùng dữ liệu chưa đạt mốc chốt mà không cảnh báo.                                   |
|   2 | Đối soát tổng và tránh nhân bản     | Tổng tiền khớp bản xuất sau lọc theo quy tắc; bản ghi trùng được xử lý; chi phí không bị nhân theo số đơn CRM.                                                                            | Lệch tổng ngoài quy tắc làm tròn hiển thị hoặc cộng trùng khi ghép.                                                |
|   3 | Đúng công thức và phạm vi doanh thu | %CPQC và ROAS dùng định nghĩa đã chốt; tổng tỷ lệ tính từ tổng tử/mẫu số, không lấy trung bình tỷ lệ chi nhánh; mẫu số 0/thiếu được báo không hợp lệ; thiếu attribution không có ROAS số. | Đảo công thức, bình quân tỷ lệ không có trọng số, chia cho 0 hoặc dùng doanh thu tổng làm ROAS khi chưa có căn cứ. |
|   4 | Truy nguồn và chặn ngoại lệ         | Mỗi số tổng truy được về bản xuất/kỳ và quy tắc; mọi mapping thiếu, trạng thái đơn chưa rõ hoặc số liệu lệch được liệt kê để người duyệt xử lý.                                           | Tự điền dữ liệu thiếu, âm thầm bỏ bản ghi hoặc không tìm được nguồn khi kiểm lại.                                  |
|   5 | Thời gian và người duyệt            | Không quá 30 phút/báo cáo trong 4 kỳ pilot, cùng phạm vi với baseline; marketer hoàn tất kiểm tra trước khi gửi.                                                                          | Vượt target hoặc gửi khi chưa kiểm; báo cáo nhanh nhưng không đạt các tiêu chí 1–4 vẫn không đạt.                  |

---

## 8. Quyết định (CP6)

### 8.1. Bốn rủi ro

| Rủi ro          | Câu hỏi                                                           | Mức độ rủi ro (Thấp = an toàn / TB / Cao = nguy hiểm) | Lý do / bằng chứng                                                                                                                                                               |
| --------------- | ----------------------------------------------------------------- | ----------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Value**       | Người dùng có thật sự cần và sẽ dùng không?                       | **TB**                                                | Pitch có actor và ước lượng 90 phút/tuần, chưa có kiểm chứng ngoài nhóm. Tiết kiệm mục tiêu chỉ 30 phút/tuần nên cần so với công duy trì, không mặc định đáng đầu tư tích hợp.   |
| **Usability**   | Người dùng có dùng được, có hiểu và sửa được đầu ra của AI không? | **TB**                                                | Chọn Rule, người dùng sẽ kiểm bảng số và ngoại lệ. Chưa thử xem marketer có hiểu công thức và xử lý ngoại lệ trong target không.                                                 |
| **Feasibility** | Có đủ dữ liệu, công cụ, kỹ năng để làm không?                     | **Cao**                                               | Chưa có bản xuất, sơ đồ trường, mapping chi nhánh, quy tắc doanh thu hoặc mốc chốt kỳ. Có tài liệu công cụ nhưng chưa chứng minh dùng được trên case thực tế.                    |
| **Viability**   | Có hợp chi phí, pháp lý, quy định tổ chức không? Ai vận hành?     | **Cao**                                               | Chưa xác nhận quyền dùng dữ liệu CRM/TKQC, người duy trì hay chi phí được chấp nhận. Đề xuất bản xuất tối thiểu không có định danh khách hàng; không đăng dữ liệu thật vào repo. |

### 8.2. Kết luận

**Quyết định:** **Not Yet** cho triển khai/pilot trên dữ liệu thật. Candidate vẫn được chọn để tiếp tục kiểm chứng; hướng ưu tiên là **Rule**, không triển khai AI ở giai đoạn này.

**Lý do:** Có nhu cầu mô tả cụ thể và cách thử nhỏ, nhưng hai rủi ro Cao về dữ liệu và quyền vận hành chưa được giải quyết. Sheet CP4 không có bằng chứng để kết luận pain đã được xác nhận hoặc giải pháp đã đủ điều kiện Go.

**Nếu Go — pilot nhỏ nhất:** Chỉ bắt đầu sau khi được phép sử dụng dữ liệu và chốt quy tắc. Dùng một mẫu bảng tính trên bản xuất của đủ 9 TKQC và CRM của 3 chi nhánh; không tích hợp ghi ngược và không xây Agent. Đo ít nhất 2 báo cáo theo cách cũ, sau đó chạy song song cách cũ và Rule trên cùng dữ liệu cho 4 báo cáo trong 2 tuần. Ghi riêng thời gian lấy dữ liệu, xử lý và duyệt. Marketer đối soát trước khi dùng; target là tối đa 30 phút/lần với toàn bộ tiêu chí chất lượng đạt. Đây là kế hoạch, chưa phải pilot đã thực hiện.

**Nếu Not Yet — cần kiểm chứng gì trước:**

- Phỏng vấn 2–3 người ngoài nhóm có trải nghiệm làm báo cáo tương tự; tìm cả trường hợp công cụ hiện tại đã đủ hoặc thời gian rất ngắn.
- Xác nhận người phụ trách và quyền sử dụng bản xuất; chỉ giữ trường tối thiểu cần thiết, không sao chép thông tin định danh khách hàng vào repo.
- Kiểm tra bản xuất thật đã được phép dùng: đủ 9 TKQC, cấu trúc CRM, danh mục chi nhánh, dữ liệu trùng/hoàn/hủy, tiền tệ và múi giờ.
- Chốt định nghĩa %CPQC/ROAS, doanh thu quy thuộc quảng cáo, quy tắc ngày ghi nhận và mốc chốt dữ liệu; trường hợp chưa quy nguồn được phải ghi rõ giới hạn.
- Đo baseline ít nhất 2 kỳ; xác nhận chi phí duy trì có phù hợp với lợi ích dự kiến. Chỉ chuyển Go khi không còn rủi ro Cao và có người nhận trách nhiệm đối soát.

**Nếu No-Go — nên làm gì thay AI:** Nếu không lấy được dữ liệu hợp lệ, không được cấp phép hoặc lợi ích không đủ bù công duy trì, dừng tự động hóa; dùng mẫu báo cáo, checklist đủ nguồn và lịch chốt số thủ công. Nếu No AI đã đạt mục tiêu thì giữ cách đó. Nếu Rule đạt mục tiêu thì vận hành Rule, không bổ sung AI chỉ để tăng mức tự động hóa.

**Ngưỡng dừng** (nếu sau … mà … thì quay về …):

- Nếu bất kỳ báo cáo nào sai tổng tiền/công thức ngoài quy tắc làm tròn đã thống nhất, bỏ sót nguồn hoặc có ngoại lệ chưa giải quyết ảnh hưởng chỉ số: dừng gửi báo cáo đó, quay về đối soát thủ công và sửa nguyên nhân trước lần chạy tiếp.
- Nếu sau 4 kỳ pilot, thời gian trung bình không giảm ít nhất 15 phút/lần so với baseline đo thật, hoặc có từ 2 kỳ trở lên vượt 30 phút/lần: chưa mở rộng; xem lại nút thắt, so với mẫu No AI rồi quyết định giữ cách đơn giản hơn.
- Nếu quyền sử dụng dữ liệu bị rút hoặc chưa xác định được người chịu trách nhiệm đối soát: dừng pilot ngay, quay về quy trình được đơn vị cho phép.

---

## 9. Hạn chế và hướng tiếp theo

- Sheet CP4 trong Excel nguồn vẫn trống; nhóm đã bổ sung 1 quan sát trực tiếp thật (`cp1-tkqc-snapshot.md`, 09/11/2026, của chính Hùng) và 3 interview người ngoài nhóm (mục 3.2, Người 1 tháng 9/2026, Người 2–3 ngày 15/10/2026), có ít nhất 1 tín hiệu phản bác (Người 2: "20 phút là bình thường"; Người 3: không có pain rõ). Mẫu vẫn nhỏ (3 người) nên chưa đủ để coi là đã kiểm chứng rộng; nếu mở pilot cần phỏng vấn thêm.
- 45 phút/lần, 2 lần/tuần, 9 TKQC và 3 chi nhánh là thông tin trong pitch của Hùng; snapshot 09/11/2026 đã xác nhận đúng số 9 TKQC/3 chi nhánh và %CPQC thật trên dashboard, nhưng thời gian từng bước (15/5/15/7/3 phút) và toàn bộ thời gian tương lai vẫn là minh họa/target đề xuất, chưa bấm giờ thật.
- Điểm shortlist, lựa chọn thiết kế và đề xuất sửa v1 từ phản biện AI (mục 5) đã được nhóm xác nhận là quyết định chung. `TEAM.md` hiện vẫn chưa điền thông tin thành viên, phân công checkpoint và phần đóng góp cá nhân của từng người — **cần điền trước khi nộp**, vì thiếu nội dung này khiến phần nhóm bị 0 điểm theo RUBRIC.md.
- Chưa biết nền tảng quảng cáo, CRM, cách phân bổ tài khoản cho chi nhánh và cách ghi nhận doanh thu. Không thể khẳng định connector sẵn có hoặc dữ liệu đã đủ tính ROAS.
- Ưu tiên hoàn thiện định nghĩa chỉ số, mapping và bằng chứng thời gian trước khi làm dashboard. Các candidate quy nguồn đơn (#11) và phát hiện chiến dịch cần điều chỉnh (#12) chỉ xem xét ở vòng sau.
- Nội dung Excel được dùng làm dữ liệu nguồn; bài mẫu chỉ dùng để đối chiếu cấu trúc. Các đề xuất do AI hỗ trợ cần người học tự đánh giá, chỉnh và giải thích được trước khi nộp; không dùng chúng thay phần thảo luận và kiểm chứng thật.

## 10. Tài liệu tham khảo

- **Tài liệu nguồn:** `CP Nhóm Lab Day 02.xlsx` do học viên cung cấp; sheet `Trang tính1`, B2:F13 chứa 12 candidate và phản biện; B11:F11 là candidate báo cáo của Hùng. Sheet `CP4` không có dữ liệu. File nguồn nằm ngoài repo tại thời điểm biên tập.
- **Bằng chứng quan sát trực tiếp:** [`report/assets/cp1-tkqc-snapshot.md`](../assets/cp1-tkqc-snapshot.md) — snapshot dashboard Sale–Marketing nội bộ thật do Hùng tự xây, quan sát 09/11/2026, dùng ở mục 3.1 và 3.2.
- **Bằng chứng phỏng vấn:** 3 interview người ngoài nhóm — Người 1 (tháng 9/2026), Người 2 và Người 3 (15/10/2026); chi tiết trong bảng interview snapshot ở mục 3.2, không có file riêng.
- **Hướng dẫn và mẫu trong repo:** [RULES.md](../../RULES.md), [CHECKPOINTS.md](../../CHECKPOINTS.md), [Worksheet](../../docs/01-worksheet.md), [Bài làm mẫu](../../docs/02-deliverable-example.md), [RUBRIC.md](../../RUBRIC.md).
- **Bài mẫu bổ sung do học viên cung cấp:** `02-deliverable-example.md` trong thư mục Downloads; dùng tham khảo cách tổ chức báo cáo, không dùng số liệu hoặc interview của nhân vật PM làm bằng chứng cho case Performance Marketer.
- **Nguồn công cụ chính thức**, đã mở ngày 09/11/2026: [Google Sheets — SUMIFS](https://support.google.com/docs/answer/3238496?hl=en), [Google — How blends work](https://docs.cloud.google.com/data-studio/how-blends-work), [Supermetrics — Google Sheets](https://docs.supermetrics.com/docs/google-sheets), [Supermetrics — Scheduled refresh](https://docs.supermetrics.com/v1/docs/how-to-create-and-manage-scheduled-refreshes-in-google-sheets). Các claim cụ thể và giới hạn áp dụng nằm tại mục 3.3.
