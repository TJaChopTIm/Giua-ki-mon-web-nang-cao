# Thông tin về Tác giả
Mã sinh viên: 22010327
Họ tên: Vũ Đức Nguyên

# LINK VIDEOS DEMO: https://youtu.be/_bIHPfqpUSg

# Giới Thiệu

Trang web bán hàng được phát triển sử dụng Laravel và PHP nhằm cung cấp một nền tảng mua sắm trực tuyến hiệu quả. Hệ thống bao gồm hai vai trò truy cập chính: Khách hàng và Quản trị viên (Admin).

# Chức Năng

1. Khách Hàng

-Duyệt danh mục sản phẩm theo loại.

-Lọc sản phẩm theo danh mục.

-Thêm sản phẩm vào giỏ hàng.

-Tiến hành thanh toán.

2. Quản Trị Viên (Admin)

-Quản lý danh mục sản phẩm.

-Thêm, xóa, chỉnh sửa thông tin sản phẩm.

-Quản lý tài khoản người dùng và nhân viên.


# Công Nghệ Sử Dụng

Backend: Laravel (PHP Framework)

Frontend: Blade Template Engine, HTML, CSS, JavaScript

Cơ Sở Dữ Liệu: MySQL

Thư Viện Bên Thứ Ba: Bootstrap, jQuery

# Hướng dẫn cách sử dụng dự án
#Lưu ý : trang web sự dụng php 7.4 - 8.0 nên nếu php phiên bản mới hơn sẽ không hỗ trợ
## Step 1: Clone source dự án
Thực thi câu lệnh sau:
```
git clone https://github.com/TJaChopTIm/Giua-ki-mon-web-nang-cao.git
```

## Step 2: Khởi tạo, kết nối database
Hiệu chỉnh file .env
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=ecomerce
DB_USERNAME=root
DB_PASSWORD=
```

## Step 3: Tạo database, thực hiện migrate
- Tạo database <ecomerce>, chuẩn bảng mã `utf8mb4_unicode_ci`
- Thực thi câu lệnh khởi tạo cấu trúc bảng
```
php artisan migrate
```

## Step 4: tạo dữ liệu mẫu
- Thực thi câu lệnh
```
php artisan db:seed
```

## Step 5: chạy máy ảo trên local
- Thực thi câu lệnh
```
php artisan serve
```

## Step 6: thông tin tài khoản truy cập hệ thống
Tài khoản Admin:
nhanvien@gmail.com / 123456

Tài khoản Khách hàng:
khachhang@gmail.com / 123456

- Nếu là tài khoản nhân viên thì hệ thống sẽ tự động chuyển vào trang quản lý
