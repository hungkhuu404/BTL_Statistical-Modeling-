# Memory.md — Trạng thái làm việc chung

Cập nhật: 2026-11-19 18:48 (Asia/Ho_Chi_Minh) bởi agent Claude Code theo yêu cầu của người dùng phiên (danh tính GitHub: CHƯA XÁC ĐỊNH).
Đây là trạng thái chung của dự án, không phải bộ nhớ tự động riêng của agent. Đầu phiên: đối chiếu với `git status`/`git log`, đừng chỉ tin bản ghi này.

## Tác vụ

| ID | Owner | Trạng thái | Điều kiện hoàn tất |
|---|---|---|---|
| T-000 Dựng scaffold + tài liệu + remote | agent (phiên 2026-11-19) | Đã tạo, kiểm tra; commit + push theo lệnh người dùng (xem `git log origin/main` để biết đã lên chưa) | Commit có trên `origin/main` |
| T-001 Đăng ký nhóm và hai cặp bài giảng với giảng viên (trực tiếp tại lớp, không email) | CHƯA XÁC ĐỊNH | Chưa biết (không có bằng chứng) | Có xác nhận từ giảng viên; điền `projects.md` mục 2 |
| T-003 Nhận 6 bộ dữ liệu, đặt vào `data/raw/` và ghi nguồn | CHƯA XÁC ĐỊNH | Chờ T-001 | File có trong `data/raw/`; nguồn ghi trong `docs/contracts.md` |
| T-004 Chọn định dạng báo cáo (Word/LaTeX) và dựng bộ khung `report/` | CHƯA XÁC ĐỊNH | Mở | Quyết định ghi ở `docs/Research_log.md` |
| T-005 Chốt Python, thư viện, lock file, tạo môi trường thật | CHƯA XÁC ĐỊNH | Chờ T-001 (thư viện phụ thuộc nội dung bài giảng) | Cài từ lock + import thử thành công; cập nhật README |

## Trạng thái kiểm chứng

- Đã kiểm: cấu trúc thư mục, Git ở gốc `B. BTL/`, remote `origin`, quy tắc ignore (xem handoff/ báo cáo setup khi có).
- Chưa kiểm/chưa có: toàn bộ phần ứng dụng — chưa có mã, dữ liệu, test, môi trường, báo cáo.

## Branch/commit

- Branch: `main`. Remote `origin`: `https://github.com/hungkhuu404/BTL_Statistical-Modeling-.git` (đã fetch 2026-11-19: remote chưa có branch nào). Hash commit: xem `git log`.

## Process/job đang chạy

- Không có.

## Việc cần theo dõi (chỉ ghi để theo dõi — **chưa tạo lịch/nhắc trong công cụ nào**)

- Hạn nộp bản mềm: Thứ hai 30/11/2026 trước 12:00 (Asia/Ho_Chi_Minh); bản cứng trong 5 phút đầu buổi học cùng ngày. Owner nhắc: CHƯA XÁC ĐỊNH.
- Markdown không tự nhắc giờ khi không có agent hoạt động.

## Liên kết

- Quy tắc: `AGENTS.md`. Định nghĩa dự án: `docs/agent-instructions/projects.md`. Ngoại lệ: `docs/agent-instructions/Override_log.md` (hiện chưa có). Quyết định thiết kế: `docs/Research_log.md`. Handoff: `docs/handoff/` (hiện chưa có).
