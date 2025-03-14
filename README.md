# PTUD-GK-DE-2

## Thông tin cá nhân  
- **Họ và Tên:**  Nguyễn Khải
- **Mã số sinh viên:** 20025651

## Giới thiệu dự án  
Đây là ứng dụng quản lý công việc được xây dựng bằng Flask, cho phép người dùng theo dõi và quản lý các task với tính năng upload avatar và thông báo task quá hạn.. 

### Tính năng chính  
- User có thể tạo tài khoản, đăng nhập
- User có thể tạo, chỉnh sửa và xóa công việc  
- User có thể upload ảnh đại diện  
- Admin có quyền quản lý công việc của tất cả user  
- Hiển thị số công việc trễ hạn 

## Yêu Cầu Hệ Thống

- Python 3.8 trở lên
- pip
- Git

## Hướng Dẫn Cài Đặt

### 1. Chuẩn Bị Môi Trường

 Cài đặt Python:
   - Truy cập [python.org](https://www.python.org/downloads/)
   - Tải và cài đặt Python phiên bản mới nhất

### 2. Tải Mã Nguồn

1. Tạo thư mục cho project:
   ```bash
   mkdir task-manager
   cd task-manager
   ```

2. Clone repository:
   ```bash
   git clone https://github.com/KhaiNguy3n/ptud-gk-de-2
   cd ptud-gk-de-2
   ```

### 3. Tạo Môi Trường Ảo

1. Tạo môi trường ảo:
   ```bash
   python -m venv venv
   ```

2. Kích hoạt môi trường ảo:
   ```bash
   venv\Scripts\activate
   ```

### 4. Cài Đặt Các Thư Viện

1. Cài đặt các package cần thiết:
   ```bash
   pip install -r requirements.txt
   ```

### 5. Khởi Tạo Database

1. Mở Python shell trong môi trường ảo:
   ```bash
   python
   ```

2. Tạo database:
   ```python
   from app import db
   db.create_all()
   exit()
   ```

### 6. Chạy Ứng Dụng

1. Khởi động server:
   ```bash
   python app.py
   ```

2. Truy cập ứng dụng:
   - Mở trình duyệt web
   - Truy cập địa chỉ: http://localhost:5000

### 7. Sử Dụng Ứng Dụng

1. Đăng ký tài khoản mới:
   - Click vào "Register"
   - Điền thông tin tài khoản
   - Đăng ký

2. Đăng nhập:
   - Nhập username và password
   - Click "Login"

3. Quản lý task:
   - Thêm task mới
   - Upload avatar
   - Theo dõi task quá hạn
   - Cập nhật trạng thái task


