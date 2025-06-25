# Doctruyen

Ứng dụng web để đọc truyện, tiểu thuyết, và truyện tranh trực tuyến. Doctruyen cung cấp giao diện thân thiện cho người đọc để khám phá và thưởng thức nội dung.

## Tính năng

- Hệ thống xác thực người dùng
- Duyệt truyện theo danh mục
- Đánh dấu truyện yêu thích
- Chức năng tìm kiếm

## Cài đặt

```bash
# Sao chép kho lưu trữ
git clone https://github.com/yourusername/doctruyen.git

# Di chuyển đến thư mục dự án
cd doctruyen

# Cài đặt các phụ thuộc
composer install
npm install

# Sao chép tệp môi trường
cp .env.example .env

# Tạo khóa ứng dụng
php artisan key:generate

# Cấu hình cơ sở dữ liệu trong tệp .env
# Sau đó chạy migrations
php artisan migrate

# Biên dịch tài nguyên
npm run dev
```

## Sử dụng

```bash
# Khởi động máy chủ phát triển cục bộ
php artisan serve
```

Truy cập `http://localhost:8000` trong trình duyệt của bạn để sử dụng ứng dụng.

## Công nghệ

- Laravel
- MySQL
- Vue.js/React (Framework Frontend)
- Tailwind CSS

## Hình ảnh trang web
![z6741004117801_6898ff5e5c40571b48b601218de62850](https://github.com/user-attachments/assets/18567df9-7374-4b5a-90f6-417a8b2c60f9)
### Đăng nhập 
### Giao diện người dùng
![z6741005156135_fcbbbe608cf6bd72a03a4e6a412e2543](https://github.com/user-attachments/assets/9442682c-dd46-47bc-a0a5-f5cf6d46f221)
![z6741005410068_2048ddfccad1eb3cc8bde240a5c5623e](https://github.com/user-attachments/assets/34de1574-55e3-450f-9ffe-3faefe62f179)
![z6741005612901_9b708361f89b0ec57c8479d081bb5eb4](https://github.com/user-attachments/assets/3bdcef13-8f93-499a-beba-86800f48a40d)
### Giao diện admin
![Screenshot 2025-02-27 174040](https://github.com/user-attachments/assets/2948ba40-4249-47ca-b2f4-d6c945ac1b1f)
![Screenshot_27-2-2025_175258_127 0 0 1](https://github.com/user-attachments/assets/9c007704-fd32-4422-b17a-37c170fdd5d9)



### 

## Giấy phép

Phân phối theo Giấy phép MIT. Xem `LICENSE` để biết thêm thông tin.

