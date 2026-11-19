# BTL Mô hình thống kê

Bài tập lớn nhóm môn Mô hình thống kê: dùng Python kiểm chứng lý thuyết của hai cặp bài giảng trên 6 bộ dữ liệu. Trạng thái: **mới dựng khung, chưa có mã/dữ liệu**.

## Bắt đầu

1. Đọc `AGENTS.md` (quy tắc chung; người và agent đều theo).
2. Đọc `docs/agent-instructions/projects.md` (đề bài, sản phẩm nộp, hạn) và `docs/agent-instructions/Memory.md` (ai đang làm gì).
3. Hạn nộp bản mềm: **30/11/2026 trước 12:00** (LMS); bản in trong 5 phút đầu buổi học.

## Cấu trúc

- `docs/` — tài liệu chung (`agent-instructions/`, `contracts.md`, `Research_log.md`, `handoff/`).
- `src/`, `notebooks/`, `tests/` — mã Python, notebook, test.
- `data/raw/` — dữ liệu gốc của giảng viên; `data/processed/` — dữ liệu đã làm sạch.
- `report/` — báo cáo (Word/LaTeX + PDF), `report/figures/` — hình.

Chi tiết: `docs/agent-instructions/Codebase_map.md`.

## Môi trường và chạy

Chưa chọn thư viện nên **chưa có lock file, chưa có lệnh chạy/test**. Khi chốt (task T-005) sẽ ghi vào đây lệnh đã kiểm chứng. Gợi ý hướng làm (**chưa kiểm chứng**): tạo venv trong `runtime\venv` (git-ignored), cài thư viện theo file lock, rồi chạy notebook/script.

## Dữ liệu, cấu hình, log

- Dữ liệu và quy ước: `data/`, `docs/contracts.md`. Chưa có cấu hình. Log chạy cục bộ (nếu có) ở `runtime\logs`, không commit.

## Quy ước Git

- Commit mang tên tài khoản GitHub của người làm; không có agent trong author/co-author.
- Nhánh `main` của remote `origin` là bản có thẩm quyền cho trạng thái chung.
