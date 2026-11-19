# Codebase_map.md — Bản đồ codebase

Kiểm tra lần cuối: 2026-11-19 18:48 (Asia/Ho_Chi_Minh). Commit đối chiếu: commit scaffold đầu tiên (xem `git log`).
Bản đồ chỉ để định hướng; khi sửa code luôn kiểm tra nguồn thực tế.

## Thư mục

| Đường dẫn (từ gốc repo = `B. BTL/`) | Trách nhiệm | Trạng thái |
|---|---|---|
| `AGENTS.md`, `CLAUDE.md` | Quy tắc chung (`CLAUDE.md` chỉ import `@AGENTS.md`) | Có |
| `README.md` | Hướng dẫn cho người mới | Có |
| `docs/agent-instructions/` | `projects.md`, `Memory.md`, `Codebase_map.md`, `Override_log.md` | Có |
| `docs/handoff/` | Snapshot bàn giao `github-author_YYYY-MM-DD_HHmm.md` | Trống (chỉ `.gitkeep`) |
| `docs/Research_log.md`, `docs/contracts.md` | Nhật ký quyết định; quy ước dữ liệu/seed/giao diện module | Có |
| `src/` | Mã Python tái dùng (nạp dữ liệu, làm sạch, hàm kiểm chứng từng nội dung lý thuyết) | Trống |
| `notebooks/` | Notebook `.ipynb` chạy phân tích/kiểm chứng theo từng cặp bài giảng | Trống |
| `tests/` | Test cho mã trong `src/` | Trống |
| `data/raw/` | 6 bộ dữ liệu gốc do giảng viên cung cấp (chỉ thêm, không sửa) | Trống |
| `data/processed/` | Dữ liệu sau làm sạch/tiền xử lý do mã sinh ra | Trống |
| `report/` , `report/figures/` | Nguồn báo cáo (`.docx`/`.tex`), PDF, hình | Trống (chỉ `.gitkeep`) |

Cùng thư mục nhưng bị `.gitignore` chặn (không vào Git): `private/` (ghi chú riêng, điều phối), `runtime/` (venv, cache, temp, logs), `archive/` (bản nộp, sao lưu).

## Entrypoint và luồng dữ liệu

- Entrypoint: **CHƯA XÁC ĐỊNH** (chưa có mã).
- Luồng dự kiến: `data/raw/` → làm sạch → `data/processed/` → kiểm chứng (`src/`, `notebooks/`) → hình/bảng → `report/`. Chi tiết quy ước: `docs/contracts.md`.

## Cấu hình, test, logic chính

- Cấu hình: chưa có. Test: `tests/` (trống). Logic chính: chưa có.
