# Research_log.md — Nhật ký quyết định

Mục cũ bị thay thế phải đánh dấu `[LỊCH SỬ]` hoặc `[ĐÃ BỊ THAY THẾ bởi RL-NNN]` và không được hiểu là chỉ dẫn hiện hành. Phiên bản cũ có giá trị xem trong lịch sử Git.

## RL-001 — Điều chỉnh khuôn setup hackathon sang bài tập lớn (2026-11-19)

- Trạng thái: hiện hành.
- Bối cảnh: khuôn workspace gốc viết cho hackathon; dự án này là bài tập lớn nhóm môn Mô hình thống kê, nộp báo cáo + mã + dữ liệu, không có sản phẩm triển khai.
- Giữ nguyên: thư mục `private/ runtime/ archive/` (git-ignored); bộ tài liệu `AGENTS.md`, `CLAUDE.md`, `docs/agent-instructions/*`, `Research_log.md`, `contracts.md`, handoff; giao thức `[override]`; ràng buộc commit chỉ có tác giả người.
- Bỏ: `private/heldout` và `private/assets` (không có held-out, tài sản riêng); `private/source-data` (dữ liệu do giảng viên cấp phải **nộp**, nên nằm trong `data/raw/` của repo); `runtime/worktrees`, `archive/checkpoints` (chưa có nhu cầu); `data/public` (đổi thành `data/raw` + `data/processed`); phần demo/deploy/thi đấu/gate.
- Thêm: `notebooks/`, `report/` + `report/figures/`; bảng sản phẩm nộp và tiêu chí hoàn thành bám thông báo của giảng viên (`projects.md` mục 4–5); quy ước dữ liệu/seed trong `contracts.md`.
- Không làm: launcher `run.ps1` và môi trường ảo (chưa chọn thư viện, chưa có lệnh chạy để kiểm chứng). Làm khi T-005 xong.

## RL-002 — Vị trí repo Git (2026-11-19)

- Trạng thái: hiện hành.
- Quyết định (người dùng, 2026-11-19): repo Git đặt ngay tại gốc `B. BTL/`; remote `origin` = `https://github.com/hungkhuu404/BTL_Statistical-Modeling-.git`. Bản đầu cùng ngày đặt repo ở `B. BTL/repository/` theo khuôn hackathon, **đã bị thay thế** bằng quyết định này.
- Lý do: workspace chỉ có một dự án, không cần lớp thư mục `repository/`. Người dùng chủ động chọn, khác khuôn gốc (khuôn cấm `git init` ở gốc workspace vì workspace thường chứa nhiều dự án).
- Hệ quả: `private/`, `runtime/`, `archive/` nằm cạnh mã nguồn nên phải được `.gitignore` chặn (đã có `/private/ /runtime/ /archive/`); kiểm bằng `git check-ignore`. Không được bỏ các dòng này.
- Bỏ khỏi tài liệu theo yêu cầu người dùng: danh sách thành viên và leader.
