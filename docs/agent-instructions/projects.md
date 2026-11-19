# projects.md — Định nghĩa dự án

Cập nhật: 2026-11-19 18:48 (Asia/Ho_Chi_Minh). Mục chưa có căn cứ ghi **CHƯA XÁC ĐỊNH**.

## 1. Dự án

- Là gì: Bài tập lớn môn Mô hình thống kê (học phần "Statistical Modeling"), làm theo nhóm.
- Cho ai: giảng viên môn học (tên: CHƯA XÁC ĐỊNH).
- Vấn đề: dùng Python để minh họa và kiểm chứng có hệ thống toàn bộ nội dung lý thuyết của **hai cặp bài giảng** nhóm chọn, trên **6 bộ dữ liệu** giảng viên cung cấp (3 bộ cho mỗi bài giảng), kèm phân tích và diễn giải thống kê. Không cần phương pháp mới ngoài học phần.
- Trọng tâm chấm: hiểu đúng bản chất kết quả lý thuyết; triển khai đúng bằng Python; kiểm chứng trên dữ liệu thật; diễn giải; nhận xét độ phù hợp lý thuyết – mô hình – dữ liệu.

## 2. Lựa chọn nội dung (phải đăng ký với giảng viên)

Nhóm chọn **hai** trong sáu cặp bài giảng: 1+2, 3+4, 5+6, 7+9, 8+10, 11+12.

| Mục | Giá trị |
|---|---|
| Cặp bài giảng thứ nhất | CHƯA XÁC ĐỊNH |
| Cặp bài giảng thứ hai | CHƯA XÁC ĐỊNH |
| 3 bộ dữ liệu cặp thứ nhất | CHƯA XÁC ĐỊNH |
| 3 bộ dữ liệu cặp thứ hai | CHƯA XÁC ĐỊNH |
| Đã đăng ký nhóm + nội dung trong link của giảng viên | CHƯA XÁC ĐỊNH |

Quy định của giảng viên: nhóm không có nhóm được duyệt hoặc không đăng ký nội dung nhận **0 điểm toàn bộ bài tập lớn**. Mọi thay đổi thành viên/nội dung/thông tin phải trao đổi **trực tiếp với giảng viên trong giờ học, không gửi email**. Không tự thay bộ dữ liệu quy định khi chưa được giảng viên đồng ý.

Ghi chú: tài liệu môn trong `A. DOCS` (ngoài workspace này) có chương 1–8; ánh xạ "bài giảng 1–12" sang chương **CHƯA XÁC ĐỊNH**.

## 3. Đầu vào, đầu ra, luồng chính

- Đầu vào: 6 bộ dữ liệu giảng viên cung cấp (nguồn/link: CHƯA XÁC ĐỊNH) → `data/raw/`.
- Luồng: dữ liệu thô → làm sạch/EDA (`data/processed/`) → kiểm chứng từng nội dung lý thuyết (mã Python) → bảng/hình → diễn giải → báo cáo.
- Đầu ra: bộ nộp ở mục 5.
- Với mỗi nội dung lý thuyết, báo cáo phải có: lý thuyết cần kiểm chứng; cách triển khai; mã Python; kết quả tính toán; phân tích và diễn giải; nhận xét (thực nghiệm có khớp lý thuyết không, nếu lệch thì giải thích). Với giả thiết mô hình, chẩn đoán, so sánh mô hình, đánh giá sai số, suy luận, kiểm định phù hợp: làm đầy đủ nếu bài giảng đã trình bày.

## 4. Tiêu chí hoàn thành (kiểm chứng được)

1. Đã đăng ký nhóm và hai cặp bài giảng với giảng viên (có bằng chứng, vd. ảnh/ghi nhận của thành viên đã gặp giảng viên).
2. Danh sách nội dung lý thuyết cần kiểm chứng của mỗi cặp đã lập (mục 4.2 báo cáo) và mỗi mục đều có kết quả trên **cả 3** bộ dữ liệu của cặp đó.
3. Mọi bảng/hình/kết quả mô hình trong báo cáo tái lập được bằng cách chạy mã trong repo từ dữ liệu trong `data/raw/` (có seed cố định).
4. Mỗi kết quả có diễn giải thống kê và liên hệ lý thuyết; không có kết quả "trần".
5. Báo cáo đủ các mục 4.1–4.9 của đề (xem mục 5).
6. Bộ nộp đủ file, đúng định dạng, đã nộp LMS trước hạn; bản in đã nộp tại lớp.

## 5. Sản phẩm phải nộp (theo thông báo của giảng viên)

| # | Sản phẩm | Vị trí trong repo (đề xuất) | Ghi chú |
|---|---|---|---|
| 1 | 01 file Word hoặc LaTeX (`.docx`/`.tex`) | `report/` | Chọn định dạng: CHƯA XÁC ĐỊNH |
| 2 | 01 file PDF | `report/` | |
| 3 | Mã nguồn Python `.py` và/hoặc `.ipynb` | `src/`, `notebooks/` | Có chú thích, tên biến rõ, đặt seed |
| 4 | Dữ liệu đã dùng, kèm bản đã làm sạch | `data/raw/`, `data/processed/` | |
| 5 | 01 file ZIP ảnh nếu báo cáo dùng file hình riêng | từ `report/figures/` | Chỉ mục 5 được ZIP; **không** ZIP các mục 1–4 |
| 6 | Bản in (bản cứng) | — | Không bìa nhựa, không dán băng keo |

Cấu trúc báo cáo tối thiểu: 4.1 Thông tin chung; 4.2 Tóm tắt nội dung lý thuyết cần kiểm chứng; 4.3 Mô tả và xử lý dữ liệu; 4.4 Kiểm chứng cặp thứ nhất; 4.5 Kiểm chứng cặp thứ hai; 4.6 So sánh và thảo luận; 4.7 Kết luận; 4.8 Đóng góp của từng thành viên; 4.9 Mục lục, nguồn dữ liệu, tài liệu tham khảo.

## 6. Điều kiện, hạn nộp và nguồn đề

- Hạn nộp bản mềm (LMS): **Thứ hai 30/11/2026, trước 12:00** (Asia/Ho_Chi_Minh).
- Hạn nộp bản cứng: Thứ hai 30/11/2026, trong 5 phút đầu buổi học (giờ học: CHƯA XÁC ĐỊNH).
- Nguồn đề: thông báo của giảng viên do thành viên dán vào phiên setup ngày 2026-11-19; không có URL/file gốc nên chưa đối chiếu được với văn bản chính thức. Đối chiếu lại với LMS: CHƯA XÁC ĐỊNH.
- Quy định dùng AI/công cụ hỗ trợ: đề không nêu. CHƯA XÁC ĐỊNH — nhóm cần xác nhận với giảng viên nếu dùng coding agent cho phần nộp.

## 7. Tính năng: bắt buộc / nên có / có thể cắt

- Bắt buộc: toàn bộ yêu cầu ở mục 3–5 trên 6 bộ dữ liệu.
- Nên có: kiểm tra giả thiết/chẩn đoán đầy đủ cho mọi mô hình; phần so sánh liên bộ dữ liệu (4.6) có số liệu dẫn chứng.
- Có thể cắt: biểu đồ/EDA không phục vụ trực tiếp kiểm chứng (đề yêu cầu tránh dàn trải).

## 8. Nhóm và quyền

- Nhóm tối đa 5 thành viên. Dự án này không ghi danh sách thành viên/leader trong tài liệu (quyết định của người dùng 2026-11-19); đóng góp từng người ghi ở mục 4.8 của báo cáo.
- Quyền agent trong phiên 2026-11-19: dựng cấu trúc, `git init` tại gốc workspace `B. BTL/`, thêm remote `origin`, commit và push nhánh `main` lên `origin` (người dùng cho phép khi yêu cầu "sửa lại xong thì push"; chỉ áp dụng cho lần này). Chưa cấp: nộp bài, push lần sau.

## 9. Giai đoạn hiện tại

- Giai đoạn: **chuẩn bị** (mới dựng scaffold, chưa chọn nội dung, chưa có dữ liệu).
- Chuyển giai đoạn theo quyết định của nhóm (người dùng phiên), ghi vào mục này và `docs/Research_log.md`.

## 10. Stack và giới hạn

- Ngôn ngữ: Python (đề yêu cầu). Phiên bản dự án: CHƯA XÁC ĐỊNH (máy setup có Python 3.13.3, chỉ là thông tin máy này).
- Thư viện, package manager, lock file: CHƯA XÁC ĐỊNH (phụ thuộc cặp bài giảng được chọn).
- Báo cáo: Word hoặc LaTeX — CHƯA XÁC ĐỊNH.
- Ngân sách/dịch vụ có phí: không có theo thông tin hiện có.

## 11. Nguồn có thẩm quyền

- Quy tắc chung: `AGENTS.md`. Trạng thái: `docs/agent-instructions/Memory.md`. Ngoại lệ: `docs/agent-instructions/Override_log.md`.
- Checkout có thẩm quyền: nhánh `main` của remote `origin` = `https://github.com/hungkhuu404/BTL_Statistical-Modeling-.git`.
- Revision đã công bố: xem `git log origin/main` (commit đầu tiên là scaffold ngày 2026-11-19; không ghi hash vào file để khỏi tạo commit chỉ để sửa hash).
- Coordinator quản lý cập nhật trạng thái chung: người dùng phiên; worker gửi kết quả/handoff để tổng hợp.
