# CP1 — Snapshot dữ liệu thật từ dashboard nội bộ (09/11/2026)

> Nguồn: dashboard báo cáo Sale-Marketing nội bộ do mình tự xây, dùng cho công việc performance marketing thật.
> Tên công ty/sản phẩm, SĐT, họ tên đầy đủ nhân viên đã được ẩn/thay bằng mã vai trò theo RULES.md mục 5.
> Số liệu quan sát trực tiếp trên giao diện lúc 09/11/2026, kỳ xem: tháng 11/2026 (01/11–30/11/2026).

## Tab Tổng quan

| Chỉ số | Giá trị |
|---|---|
| CPQC (chi phí quảng cáo) | 113.195.941 đ |
| Tổng DS Chốt | 834 triệu đ (277 đơn) |
| %CPQC | 22,55% (giảm 48,07% so với kỳ liền trước) |
| AOV | 3 triệu đ |

## Tab TKQC (tài khoản quảng cáo)

- Tổng **9 TKQC** đang chạy, mỗi TKQC gắn 1 nhân viên marketing, tổng CPQC 113.195.941đ khớp đúng với tab Tổng quan.
- Phân theo chi nhánh: TEAM A — 1/1 TKQC đã đối chiếu, 1 nhân viên, 42.826.646đ · TEAM B — 3/3 TKQC đã đối chiếu, 3 nhân viên, 40.636.862đ · TEAM C — 3/5 TKQC đã đối chiếu, 5 nhân viên, 29.732.433đ.
- Chi phí giữa các nhân viên lệch rất xa: thấp nhất 277.209đ, cao nhất 42.826.646đ (gấp ~154 lần).

## Tab Page

- Tổng **84 page Facebook** đang theo dõi (84 khớp CRM, 0 khớp Pancake, 0 lệch tên).
- Dòng trạng thái: "Business Manager quét lần cuối: 14:16 21/09/2026" — lệch gần 7 tuần so với thời điểm xem (09/11/2026).
- Dòng trạng thái: "Chi tiêu FB quét 15:19 05/10/2026: gán được 100%, **23 TKQC lỗi**" — khoảng 1/4 tổng TKQC từng bị gán sai nguồn chi phí ở lần quét gần nhất.
- Dòng cảnh báo: "Chưa có chi tiêu Facebook cho 01/11/2026 – 09/11/2026" — phải bấm nút "Quét chi tiêu Facebook" thủ công mới có số liệu kỳ hiện tại, hệ thống không tự động cập nhật theo lịch.

## Nhận xét rút ra cho CP1

- Có **3 chỗ cần thao tác tay bắt buộc** mới ra được số liệu đúng kỳ: (1) bấm "Quét Business Manager", (2) bấm "Quét chi tiêu Facebook", (3) tự kiểm tra dòng cảnh báo "X TKQC lỗi" để biết số liệu có đáng tin không trước khi báo cáo.
- Đây là bằng chứng thật cho các problem #1, #4, #5, #6, #7 trong bảng scan CP1 — không phải ước lượng, mà quan sát trực tiếp trên dashboard đang dùng thật.
