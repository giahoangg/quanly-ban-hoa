# ỨNG DỤNG QUẢN LÝ BÁN HOA

**Môn:** Nhập môn Kỹ thuật phần mềm  
**Bài:** LAB 8 – Quản lý Dự án  
**Đề tài:** Ứng dụng Quản lý Bán Hoa  
**Nhóm:** Flower 
**Thành viên:**  
| Họ tên | Vai trò | Công việc |
|--------|----------|-----------|
| Trương Khánh Quyên | Trưởng nhóm (Leader) | Tạo repo GitHub, viết README, quản lý tài liệu |
| Nguyễn Ngọc Anh Thư | Lập trình viên Frontend | Thiết kế giao diện HTML/CSS |
| Nhữ Mai Gia Hoàng | Lập trình viên Backend | phần xử lý chương trình, xử lý logic đơn hàng |
| Phạm Bảo Ngọc | Tester | Kiểm thử và viết test case |
| Nguyễn Thị Minh Thương | Báo cáo viên | Tổng hợp tiến độ, nộp bài và thuyết trình |

---

## MỤC TIÊU DỰ ÁN
- Quản lý danh mục sản phẩm hoa (hoa bó, hoa giỏ, hoa chậu, hoa sự kiện)
- Quản lý đơn hàng, tồn kho và doanh thu
- Hỗ trợ thao tác nhanh, dễ dùng cho nhân viên và quản lý cửa hàng

---

## CẤU TRÚC REPO
quanly-ban-hoa/
├── README.md
├── docs/
│ ├── LAB1_Nhom2.docx
│ ├── LAB8_plan.docx
│ └── progress_log.md
├── frontend/
│ ├── index.html
│ ├── css/style.css
├── backend/
│ ├── app.py
│ └── requirements.txt
└── database/
└── schema.sql

---

## CÁCH SỬ DỤNG GITHUB

### 1. Tạo repository
- Truy cập [https://github.com](https://github.com) → **New Repository**
- Đặt tên: `quanly-ban-hoa`
- Chọn “Public” + tick “Add a README file”  
- Nhấn **Create repository**

### 2. Tải tài liệu hoặc code lên
- Nhấn **Add file → Upload files**  
- Chọn các file (Word, PDF, HTML, CSS, v.v.)  
- Nhấn **Commit changes**

### 3. Tạo nhánh (branch)
- Nhấn vào chữ “main” → gõ tên nhánh, ví dụ:
  - `feature-frontend`
  - `feature-backend`
- Làm việc trong nhánh riêng → Sau đó **Pull Request → Merge vào main**

### 4. Quy tắc đặt commit message
| Loại commit | Ý nghĩa | Ví dụ |
|--------------|----------|--------|
| feat | Thêm tính năng mới | `feat: thêm trang tạo sản phẩm` |
| fix | Sửa lỗi | `fix: sửa lỗi giao diện` |
| docs | Cập nhật tài liệu | `docs: cập nhật README` |
| style | Thay đổi giao diện | `style: chỉnh màu và font` |

---

## NHẬT KÝ TIẾN ĐỘ (progress_log.md)

> File này sẽ được lưu tại thư mục `docs/progress_log.md`.

| Ngày | Công việc | Người thực hiện | Trạng thái |
|------|------------|------------------|-------------|
| 2025-10-10 | Tạo repository GitHub, thêm README.md |Trương Khánh Quyên | Hoàn thành |
| 2025-10-12 | Thiết kế giao diện HTML/CSS cơ bản | Nguyễn Ngọc Anh Thư | Đang thực hiện |
| 2025-10-14 | Tạo API backend Flask | Thành viên 3 | Nhữ Mai Gia Hoàng |
| 2025-10-16 | Kiểm thử và viết test case | Thành viên 4 | Phạm Bảo Ngọc |
| 2025-10-18 | Tổng hợp báo cáo và nộp bài | Thành viên 5 | Nguyễn Thị Minh Thương |

---

## LIÊN KẾT DỰ ÁN

- GitHub Repository: [https://github.com/giahoangg/quanly-ban-hoa](https://github.com/giahoangg/quanly-ban-hoa)
- Báo cáo LAB1: `docs/LAB1_Nhom2.docx`
- Báo cáo LAB8: `docs/LAB8_plan.docx`

---

## KẾT LUẬN

Sau khi thực hiện LAB 8, nhóm đã:
- Làm quen với việc sử dụng GitHub để quản lý tài liệu và tiến độ.  
- Biết cách tạo, phân nhánh, commit và merge trong môi trường nhóm.  
- Tổ chức dự án theo quy trình phần mềm cơ bản.  
- Nâng cao kỹ năng hợp tác và giao tiếp trong nhóm lập trình.  

---

## CẢM ƠN

Cảm ơn giảng viên đã hướng dẫn nhóm trong quá trình thực hiện môn học *Nhập môn Kỹ thuật phần mềm*.
