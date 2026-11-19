# BTL Mô hình thống kê

Bài tập lớn nhóm môn Mô hình thống kê: dùng Python kiểm chứng lý thuyết của hai cặp bài giảng trên 6 bộ dữ liệu (3 bộ cho mỗi bài giảng). Trạng thái: **mới dựng khung, chưa có mã/dữ liệu**; cặp bài giảng chưa chọn.

## Hạn và sản phẩm nộp (theo thông báo của giảng viên)

- Bản mềm (LMS): **30/11/2026 trước 12:00**. Bản in: trong 5 phút đầu buổi học cùng ngày (không bìa nhựa, không dán băng keo).
- Nộp: 1 file `.docx`/`.tex`, 1 file `.pdf`, mã `.py`/`.ipynb`, dữ liệu đã dùng (cả bản đã làm sạch), 1 ZIP hình nếu có. Chỉ hình được ZIP.
- Mọi kết quả trong báo cáo phải tái lập được từ mã, có random seed, và có diễn giải thống kê.

## Cấu trúc

- `src/`, `notebooks/`, `tests/` — mã Python, notebook, test.
- `data/raw/` — dữ liệu gốc của giảng viên (chỉ thêm, không sửa); `data/processed/` — dữ liệu đã làm sạch.
- `report/` — báo cáo (Word/LaTeX + PDF), `report/figures/` — hình.
- `private/`, `runtime/`, `archive/` — cục bộ, bị `.gitignore` chặn, không vào Git.

## Môi trường và chạy

Chưa chọn thư viện nên **chưa có lock file, chưa có lệnh chạy/test**. Khi chốt sẽ ghi vào đây lệnh đã kiểm chứng. Gợi ý hướng làm (**chưa kiểm chứng**): tạo venv trong `runtime\venv`, cài thư viện theo file lock, rồi chạy notebook/script.

## Quy ước Git

- Commit mang tên tài khoản GitHub của người làm; không có coding agent trong author/co-author.
- Nhánh `main` của remote `origin` là bản chung.
