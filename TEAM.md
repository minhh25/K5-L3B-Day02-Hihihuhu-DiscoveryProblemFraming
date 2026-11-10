# Team — Hihihuhu

## Thông tin nhóm

- **Tên nhóm:** Hihihuhu
- **Lớp / bài lab:** K5 · L3B · Day 02 — Discovery & Problem Framing
- **Repo chung:** [K5-L3B-Day02-Hihihuhu-DiscoveryProblemFraming](https://github.com/minhh25/K5-L3B-Day02-Hihihuhu-DiscoveryProblemFraming)
- **Nhóm trưởng / đầu mối tổng hợp repo:** Nguyễn Đình Minh
- **Candidate problem nhóm chọn:** Khi đến kỳ báo cáo, Performance Marketer muốn tổng hợp chi phí từ 9 tài khoản quảng cáo (TKQC) và đối chiếu doanh thu CRM theo 3 chi nhánh, để tính nhất quán %CPQC và ROAS phục vụ đánh giá hiệu quả quảng cáo.
- **Mức can thiệp ưu tiên:** Rule — kiểm tra, đối chiếu và tính theo quy tắc; con người xử lý ngoại lệ, kiểm tra và gửi báo cáo. Không có điểm can thiệp AI trong phương án được chọn.
- **Quyết định cuối:** **Not Yet** cho pilot trên dữ liệu thật. Cần xác nhận quyền sử dụng dữ liệu, bản xuất hợp lệ, mapping, quy tắc chỉ số và baseline trước khi chuyển Go.
- **Báo cáo chung:** [report/team/group_report.md](report/team/group_report.md).

## Thành viên

| STT | Họ và tên | MSSV | Vai trò trong nhóm | Tài khoản GitHub |
|---:|---|---|---|---|
| 1 | Nguyễn Đình Minh | 2A202603867 | Điều phối hội tụ, tổng hợp báo cáo, phụ trách Problem Statement v0; phản biện tính xác thực và tiêu chí đánh giá. | [minhh25](https://github.com/minhh25) |
| 2 | Nguyễn Đình Vũ Hải | 2A202603820 | Phụ trách research và so sánh mức can thiệp; phản biện chất lượng dữ liệu và boundary. | [HaiVuuu](https://github.com/HaiVuuu) |
| 3 | Đoàn Xuân Duy Bảo | 2A202603858 | Phụ trách mô tả quy trình và hoàn thiện v1/eval; phản biện tiêu chí chất lượng, ngoại lệ và fallback. | [CapybaraSlayer96](https://github.com/CapybaraSlayer96) |
| 4 | Vũ Tiến Hùng | 2A202603882 | Phụ trách kiểm chứng và tổng hợp quyết định; cung cấp bối cảnh Performance Marketing, snapshot, sơ đồ và handoff. | [hungvueducation-hash](https://github.com/hungvueducation-hash) |

MSSV của Hải trong bảng dùng theo tên file báo cáo `2A202603820_NguyenDinhVuHai.md`; mục 1 bên trong file hiện ghi `2A202630820`, cần Hải đối chiếu lại thông tin chính thức.

## Phân công theo checkpoint

Phân công cho bản hoàn thiện gồm **8 đầu việc, mỗi người phụ trách chính 2 đầu việc**. Người chính tổng hợp và rà soát sản phẩm; cả bốn thành viên đều thảo luận, phản biện và hỗ trợ các phần của nhóm. Bảng này xác định trách nhiệm của bản hoàn thiện; dấu vết thực hiện đã có được dẫn riêng trong phần cá nhân bên dưới.

| Checkpoint / đầu việc | Người chính | Người hỗ trợ | Sản phẩm và trách nhiệm cụ thể |
|---|---|---|---|
| CP3 — Hội tụ nhóm | Minh | Hải, Bảo, Hùng | Tổng hợp 12 candidate, 5 cluster, OST và bảng shortlist; mỗi người tự pitch, đặt câu hỏi và cùng chốt lý do chọn/loại. Bảo hỗ trợ rà OST, Hải phản biện tiêu chí, Hùng làm rõ case được chọn. |
| CP4 — Kiểm chứng | Hùng | Minh, Hải, Bảo | Tổng hợp Assumption Map, snapshot dashboard và 3 interview đã ghi trong group report; phân biệt quan sát trong nhóm với phỏng vấn ngoài nhóm. Hải rà rủi ro dữ liệu, Bảo rà tín hiệu phản bác, Minh rà nguồn và cách diễn đạt bằng chứng. |
| CP4 — Research | Hải | Minh, Bảo, Hùng | Bảng SUMIFS, Looker Studio và Supermetrics, gồm bước được giải quyết và giới hạn áp dụng. Hùng đối chiếu nhu cầu thực tế; Bảo xem công cụ sẵn có/giới hạn; Minh tổng hợp vào báo cáo. |
| CP5 — Quy trình trước/sau | Bảo | Hùng, Minh, Hải | Rà quy trình hiện tại/tương lai, actor, input/output, thời gian, handoff và before/after. Hùng cung cấp sơ đồ và bối cảnh; Hải rà bước xử lý ngoại lệ; Minh rà tính nhất quán với mục tiêu và phạm vi đo. |
| CP5 — Problem Statement v0 | Minh | Hải, Bảo, Hùng | Sáu trường Actor, Quy trình, Bottleneck, Impact, Success Metric, Boundary. Hùng rà thông tin domain; Hải rà boundary; Bảo rà metric và điểm nghẽn. |
| CP6 — So sánh mức can thiệp | Hải | Bảo, Hùng, Minh | Ma trận mơ hồ × phức tạp và bảng No AI / Rule / Workflow / Agent; giải thích vì sao ưu tiên Rule, điều kiện No AI đủ dùng và lý do chưa cần AI. Bảo rà lập luận, Hùng rà tác vụ thực tế, Minh rà liên kết với v0/v1. |
| CP6 — Problem Statement v1 + eval | Bảo | Minh, Hải, Hùng | Bổ sung điều kiện đầu vào, 5 tiêu chí đánh giá Rule, người kiểm tra và bảng thay đổi v0 → v1. Minh hỗ trợ tổng hợp v1, Hải rà boundary, Hùng rà quy tắc chỉ số và khả năng đối soát. |
| CP6 — Quyết định | Hùng | Minh, Hải, Bảo | Tổng hợp 4 rủi ro, Not Yet, điều kiện chuyển Go, kế hoạch pilot và ngưỡng dừng. Minh rà kết luận, Hải rà Feasibility/Viability, Bảo rà giá trị so với công duy trì và phương án quay về. |

**Phần cá nhân CP1, CP2, CP7:** Mỗi thành viên phụ trách báo cáo mang tên mình, nhật ký dùng AI và việc nộp link repo trên LMS bằng tài khoản riêng. Đóng góp phần nhóm được tổng hợp từ các báo cáo hiện có và lịch sử commit; không dùng phân công để nhận thay hoạt động phỏng vấn hoặc quan sát của người khác.

## Cá nhân

### NguyenDinhMinh-2A202603867

**Phần việc phụ trách:**

- Chủ trì tổng hợp CP3 và Problem Statement v0 ở CP5; quản lý bản báo cáo chung và liên kết bài cá nhân với bài nhóm.
- Hỗ trợ research, quy trình, v1/eval và quyết định; rà cách phân biệt dữ kiện, ước lượng và target.

**Đóng góp cụ thể:**

- Pitch các vấn đề technical test, offer-to-joining và thống nhất JD, tương ứng candidate #4–#6. Candidate JD vào shortlist, đạt 24/35; nhóm chọn candidate #10 của Hùng, đạt 29/35.
- Hỏi Hải về tính xác thực khi thêm từ khóa vượt ATS; hỏi Bảo về tiêu chí thay đổi đáng báo cáo và cách phân biệt đề xuất với quyết định chính thức.
- Tiếp nhận phản biện của Hải/Hùng/Bảo, làm rõ đánh giá năng lực thay vì suy đoán dùng AI, và theo dõi trở ngại sau offer thay vì dự đoán cam kết.
- Tổng hợp, biên tập báo cáo nhóm từ phần hội tụ tới quy trình, Problem Statement và so sánh mức can thiệp; tiếp tục đối chiếu các bằng chứng do Hùng bổ sung.

**Bằng chứng:**

- [Báo cáo cá nhân Minh](report/individual/2A202603867_NguyenDinhMinh.md), mục 3–6.
- [Group report — pitch](report/team/group_report.md#21-pitch), các dòng #1, #4–#7, #9; mục 2.4, 5–8.


**Điều mình học được từ phần nhóm:**

- Chất lượng đánh giá cần tiêu chí và dẫn chứng cụ thể; việc dùng công cụ không tự chứng minh năng lực hoặc sự thiếu trung thực. Khi tổng hợp bài nhóm, phải giữ rõ phần đã quan sát, phần do người khác cung cấp và phần mới là giả thuyết thiết kế.

### NguyenDinhVuHai-2A202603820

**Phần việc phụ trách:**

- Chủ trì CP4 research và CP6 so sánh mức can thiệp; phản biện chất lượng dữ liệu, quyền sử dụng và boundary.
- Hỗ trợ hội tụ, Assumption Map, quy trình, Problem Statement và đánh giá rủi ro.

**Đóng góp cụ thể:**

- Pitch các vấn đề chuẩn bị CV, làm assignment và tìm hiểu công ty, tương ứng candidate #1–#3.
- Phản biện Minh về năng lực thật khi ứng viên dùng AI, khả năng nhận biết thay đổi sau offer và nguyên nhân JD đổi; hỏi Bảo về sai số định tuyến ticket và hậu quả bỏ sót việc khẩn.
- Hỏi Hùng liệu AI giải quyết được độ trễ/sai tracking hay chỉ tính nhanh hơn; đề xuất đưa rủi ro này vào Assumption Map, giữ xử lý ngoại lệ và giới hạn không sửa dữ liệu gốc.
- Theo nhật ký cá nhân, tham gia research công cụ, rà thời gian minh họa, bổ sung boundary và đồng thuận Rule/Not Yet.

**Bằng chứng:**

- [Báo cáo cá nhân Hải](report/individual/2A202603820_NguyenDinhVuHai.md), mục 4–6.
- [Group report — pitch](report/team/group_report.md#21-pitch), các dòng #1–#6, #8, #10; mục 3.1 và 4–8.


**Điều mình học được từ phần nhóm:**

- Cần kiểm tra chất lượng dữ liệu ngay từ đầu; công cụ tính nhanh không thay được quy tắc doanh thu, kỳ và mapping. Metric phải ràng buộc chất lượng, boundary phải nêu rõ ai xử lý ngoại lệ trước khi gửi báo cáo.

### DoanXuanDuyBao-2A202603858

**Phần việc phụ trách:**

- Chủ trì rà quy trình trước/sau ở CP5 và hoàn thiện v1/eval ở CP6.
- Hỗ trợ OST, shortlist, tín hiệu phản bác và so sánh mức can thiệp; kiểm tính rõ ràng của người duyệt, ngoại lệ và fallback.

**Đóng góp cụ thể:**

- Pitch các vấn đề tổng hợp thay đổi trước meetup, phân loại ticket và biên bản họp, tương ứng candidate #7–#9. Candidate meetup đạt 27/35 trong shortlist.
- Hỏi Hải về nguồn thông tin văn hóa công ty; hỏi Minh về rủi ro nếu giải pháp cho giai đoạn sau offer sai; hỏi làm rõ bài toán đối chiếu nguồn đơn của Hùng.
- Tiếp nhận câu hỏi của Minh về “đáng báo cáo” và “quyết định chính thức”, cùng câu hỏi của Hải về ticket khẩn; bổ sung tiêu chí, người xác nhận và phương án quay về.
- Theo nhật ký cá nhân, tham gia cluster/OST, shortlist, thảo luận bằng chứng, quy trình, v0 → v1, tiêu chí đánh giá và quyết định Not Yet.

**Bằng chứng:**

- [Báo cáo cá nhân Bảo](report/individual/2A202603858_DoanXuanDuyBao.md), mục 3–6.
- [Group report — pitch](report/team/group_report.md#21-pitch), các dòng #3, #5, #7–#9, #11; mục 2.2–2.4 và 4–8.


**Điều mình học được từ phần nhóm:**

- “Đáng báo cáo” hoặc “đã quyết định” phải có tiêu chí và người xác nhận. Với case nhóm, đo tốc độ phải đi cùng đủ nguồn, đối soát tổng và truy ngoại lệ; Rule chỉ đáng triển khai khi lợi ích đủ bù công chuẩn hóa/duy trì.

### VuTienHung-2A202603882

**Phần việc phụ trách:**

- Chủ trì CP4 kiểm chứng và tổng hợp quyết định CP6; cung cấp bối cảnh Performance Marketing cho candidate được chọn.
- Hỗ trợ research, quy trình, quy tắc chỉ số, rủi ro dữ liệu và điều kiện pilot; bổ sung sơ đồ và handoff.

**Đóng góp cụ thể:**

- Pitch báo cáo quảng cáo đa chi nhánh, đối chiếu nguồn đơn và rà hiệu suất chiến dịch, tương ứng candidate #10–#12; case #10 được chọn để đào sâu.
- Đặt câu hỏi về hậu quả nếu không giải quyết; trả lời phản biện của Hải bằng cách tách bài toán chất lượng dữ liệu nguồn khỏi bước tổng hợp báo cáo.
- Cung cấp snapshot dashboard quan sát ngày 09/11/2026, xác nhận quy mô 9 TKQC/3 chi nhánh và các cảnh báo cập nhật/lỗi cần kiểm tra; bổ sung interview ngoài nhóm ở mục 3.2 của group report.
- Cập nhật phần xác nhận quyết định v1; thêm ảnh quy trình và handoff vào quy trình hiện tại/tương lai. Các mốc thời gian phân rã và hiệu quả sau tự động hóa vẫn là minh họa/target, chưa phải kết quả pilot.

**Bằng chứng:**

- [Báo cáo cá nhân Hùng](report/individual/2A202603882_vutienhung.md), mục 2–4.
- [Snapshot dashboard](report/assets/cp1-tkqc-snapshot.md) và [ảnh quy trình hiện tại](report/assets/flow-chart.png).
- [Group report — kiểm chứng](report/team/group_report.md#32-kiểm-chứng), mục 3.2 và 4.1–4.2.


**Điều học được từ phần việc:**

- Dữ liệu phân mảnh cần được đối chiếu đúng kỳ, tiền tệ và chi nhánh trước khi tính tỷ lệ. Snapshot có cảnh báo giúp nhận diện rủi ro, nhưng cần bản xuất được phép dùng, quy tắc ghi nhận doanh thu và phép đo thực tế để quyết định pilot.

## Kết luận chung và bước tiếp theo

- Cả nhóm thống nhất tiếp tục kiểm chứng candidate #10, giữ **Rule** là hướng ưu tiên và **Not Yet** là trạng thái triển khai.
- Trước pilot: xác nhận quyền và người chịu trách nhiệm; kiểm bản xuất, mapping, kỳ/tiền tệ, quy tắc doanh thu và mẫu số; đo ít nhất 2 kỳ theo cách hiện tại.
- Sau khi đủ điều kiện: thử 4 báo cáo trong 2 tuần, so sánh trên cùng dữ liệu, target không quá 30 phút/báo cáo và đạt các tiêu chí chất lượng ở group report mục 7. Đây là kế hoạch, chưa phải thử nghiệm đã hoàn thành.
- Dừng gửi nếu sai tổng/công thức, thiếu nguồn hoặc còn ngoại lệ ảnh hưởng chỉ số; đối soát thủ công. Nếu sau 4 kỳ không giảm trung bình ít nhất 15 phút/lần hoặc có từ 2 kỳ vượt 30 phút thì chưa mở rộng; nếu quyền dữ liệu bị rút hoặc thiếu người chịu trách nhiệm thì dừng pilot ngay.
