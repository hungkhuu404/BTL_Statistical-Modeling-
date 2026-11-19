# contracts.md — Quy ước và giao diện

Cập nhật: 2026-11-19 18:48 (Asia/Ho_Chi_Minh). Chưa có module hay dữ liệu thật nên phần lớn là **CHƯA XÁC ĐỊNH**; không bịa giao diện để lấp chỗ trống.

## 1. Quy ước tái lập (theo đề bài)

| Mục | Quy ước |
|---|---|
| Random seed | Mọi bước có yếu tố ngẫu nhiên (mô phỏng, lấy mẫu lại, chia tập, khởi tạo) phải đặt seed. Giá trị seed dùng chung: **CHƯA XÁC ĐỊNH** (nhóm chọn một số, ghi ở đây, dùng ở mọi nơi) |
| Dữ liệu gốc | `data/raw/` chỉ thêm, không sửa tại chỗ |
| Dữ liệu đã xử lý | `data/processed/`, do mã sinh ra, không sửa tay |
| Hình/bảng cho báo cáo | Sinh bằng mã; hình lưu ở `report/figures/` |
| Mã trong báo cáo | Dán dạng văn bản, không ảnh chụp màn hình |
| Mã hóa/đường dẫn | UTF-8; đường dẫn tính từ gốc repo, không hard-code đường dẫn tuyệt đối của máy |

Cách kiểm chứng: chạy lại mã từ `data/raw/` trên máy khác và so khớp bảng/hình chính. Lệnh chạy: CHƯA XÁC ĐỊNH.

## 2. Bộ dữ liệu

Mỗi bộ dữ liệu cần một mục (chưa có thông tin, điền khi nhận dữ liệu — T-003):

| Trường | Giá trị |
|---|---|
| Tên file / bài giảng liên quan | CHƯA XÁC ĐỊNH |
| Nguồn, link, thời điểm tải | CHƯA XÁC ĐỊNH |
| Đơn vị quan sát, biến đáp ứng, biến giải thích | CHƯA XÁC ĐỊNH |
| Kiểu dữ liệu, đơn vị đo, múi giờ nếu có thời gian | CHƯA XÁC ĐỊNH |
| Bước làm sạch và file đầu ra ở `data/processed/` | CHƯA XÁC ĐỊNH |

## 3. Giao diện giữa module (`src/`)

CHƯA XÁC ĐỊNH — chưa có module. Khi thêm, ghi: tên hàm/module, đầu vào/đầu ra và kiểu, owner, consumer, lỗi và retry nếu có, điều kiện tương thích và cách kiểm chứng. Stub được phép dùng chỉ trong lúc phát triển và phải thay bằng cài đặt thật trước khi số liệu vào báo cáo.

## 4. Cấu hình và secret

- Chưa có biến cấu hình. Dự án không cần secret theo thông tin hiện có. Nếu sau này cần: ghi tên biến (không ghi giá trị), đặt mẫu giả trong `.env.example`.
- Thứ tự ưu tiên nạp cấu hình: CHƯA XÁC ĐỊNH.
