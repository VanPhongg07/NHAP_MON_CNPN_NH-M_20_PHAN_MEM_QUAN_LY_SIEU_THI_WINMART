# Hệ Thống Quản Lý Siêu Thị WinMart (WinMart Management System)

## 1. Tầm nhìn sản phẩm (Product Vision)
Dành cho ban quản lý và nhân viên chuỗi bán lẻ, **Hệ thống Quản lý Siêu thị WinMart** là phần mềm quản lý vận hành nội bộ được xây dựng bằng Python, giúp tự động hóa toàn diện quy trình nhập - xuất kho, thanh toán tại quầy thu ngân (POS) và thống kê doanh thu theo thời gian thực, khắc phục triệt để tình trạng thất thoát hàng hóa, sai lệch tồn kho và nâng cao tốc độ phục vụ khách hàng.

---

## 2. Thông tin thành viên nhóm (Nhóm 16)

> **Hướng dẫn thành viên:**  
> Mỗi thành viên cập nhật mã nguồn mới nhất (`git pull origin main`), rẽ nhánh riêng `feature/add-my-info`, điền thông tin cá nhân của mình vào bảng dưới đây rồi tạo Pull Request.

| STT | Họ và tên | Mã sinh viên | Vai trò trong dự án | Nhánh đảm nhiệm | Tài khoản GitHub |
| :-: | :--- | :-: | :--- | :--- | :--- |
| 1 | Lê Văn Phong | 25S1020078 | Scrum Master | `[tên nhánh]` | [@VanPhongg07](https://github.com/VanPhongg07) |
| 2 | [Vi Kim Quang] | 25S1020085 | [Nhiệm vụ] | `[tên nhánh]` | [@quangvi27](https://github.com/quangvi27) |
| 3 | [Họ và tên TV 3] | 25S10200 | [Nhiệm vụ] | `[tên nhánh]` | [@username_tv3](https://github.com/) |
| 4 | [Họ và tên TV 4] | 25S10200 | [Nhiệm vụ] | `[tên nhánh]` | [@username_tv4](https://github.com/) |
| 5 | [Họ và tên TV 5] | 25S10200 | [Nhiệm vụ] | `[tên nhánh]` | [@username_tv5](https://github.com/) |
| 6 | [Họ và tên TV 6] | 25S10200 | [Nhiệm vụ] | `[tên nhánh]` | [@username_tv6](https://github.com/) |

---

## 3. Kiến trúc kỹ thuật (Tech Stack)
* **Ngôn ngữ phát triển:** Python 3.10+
* **Framework / Giao diện:** PyQt / Tkinter (Desktop App) hoặc Django / FastAPI (Web backend)
* **Cơ sở dữ liệu:** SQLite / PostgreSQL
* **Quản trị dự án & Mã nguồn:** Agile/Scrum, Gitflow cơ bản, GitHub Projects & Issues

---

## 4. Hướng dẫn cài đặt và chạy thử (Local Setup)

```bash
# 1. Clone repository về máy
git clone [https://github.com/trvst-hata/NHAPMON_CNPM_NHOM-16_THRIFTSHOP.git](https://github.com/trvst-hata/NHAPMON_CNPM_NHOM-16_THRIFTSHOP.git)

# 2. Di chuyển vào thư mục dự án
cd NHAPMON_CNPM_NHOM-16_THRIFTSHOP

# 3. Tạo môi trường ảo (Virtual Environment)
python -m venv venv

# Kích hoạt môi trường ảo:
# Trên Windows:
venv\Scripts\activate
# Trên macOS/Linux:
source venv/bin/activate

# 4. Cài đặt các thư viện cần thiết
pip install -r requirements.txt

# 5. Khởi chạy ứng dụng
python main.py
