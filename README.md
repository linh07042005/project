# Hệ Thống Quản Lý Sức Khỏe Cộng Đồng (Community Health Management System - CHMS)

Hệ thống hỗ trợ quản lý thông tin sức khỏe, hồ sơ y tế và theo dõi các chỉ số sức khỏe cộng đồng, phục vụ cho việc phân tích và báo cáo nghiệp vụ y tế.

---

##  Tổng quan dự án
- **Tên dự án:** Hệ thống quản lý sức khỏe cộng đồng (CHMS)
- **Mục tiêu:** Tự động hóa quy trình quản lý hồ sơ sức khỏe, hỗ trợ tra cứu, theo dõi và báo cáo dữ liệu y tế cộng đồng một cách nhanh chóng, chính xác.
- **Đối tượng sử dụng:** Cán bộ y tế, Quản trị viên hệ thống, Người dân / Bệnh nhân.

---

##  Công nghệ & Công cụ sử dụng
- **Language / Framework:** Python, PyQt (Qt Designer) - Thiết kế giao diện ứng dụng Desktop (GUI)
- **Database:** SQL / MySQL - Quản trị và lưu trữ cơ sở dữ liệu y tế
- **System Analysis & Design:** Astah Professional (Thiết kế sơ đồ Use Case, DFD, ERD, Sequence Diagram)
- **Tools:** VS Code / PyCharm, Git & GitHub

---

##  Tính năng chính
1. **Quản lý Hồ sơ Y tế (CRUD):** Thêm, sửa, xóa và cập nhật thông tin sức khỏe cá nhân/hộ gia đình.
2. **Tra cứu & Tìm kiếm:** Tra cứu lịch sử khám bệnh, chỉ số sức khỏe và thông tin tiêm chủng.
3. **Phân tích & Báo cáo:** Xuất báo cáo thống kê tình hình sức khỏe cộng đồng theo định kỳ.
4. **Phân quyền người dùng:** Đăng nhập, phân quyền truy cập giữa Cán bộ y tế và Admin.

---

## 📂 Cấu trúc thư mục dự án
```text
├── qt designer/          # File thiết kế giao diện UI (.ui)
├── CHMS_Chuong2.astah    # File thiết kế sơ đồ hệ thống (Use Case, DFD, ERD)
├── src/                  # Mã nguồn xử lý logic Python (.py)
└── docs/                 # Slide báo cáo & Tài liệu mô tả hệ thống (.pptx)
