# CSSAdminPanel Phiên bản 1 - Sử dụng để tạo thiết kế giao diện quản trị.
## Hướng Dẫn Sử Dụng
Để kết hợp kiểu CSS tùy chỉnh vào dự án của bạn, hãy làm theo bước đơn giản sau:

- Liên kết tệp CSS `index.css`.
- **Không cần liên kết tệp CSS của Bootstrap** (Phiên bản tôi sử dụng `Bootstrap.v5.3.3`) vì tôi đã kết nối chúng.
- Cần liên kết JS của Bootstrap và sử dụng như bình thường.

## Các Phần Mở Rộng

| Class mặc định | Class kèm theo | Mô tả |
|----------------|--------------------|------|
| `.card`        | `.card-custom-box` & `.hrt-custom-box` | Màu viền trên |
| |`.primary` `.secondary` `.success` `.warning` `.danger` `.info` | Lựa chọn màu |

```html
<div class="card card-custom-box hrt-custom-box primary">
    <div class="card-body">
        Lorem ipsum dolor sit amet consectetur, adipisicing elit. Facilis corrupti nostrum quaerat
    </div>
</div>

```

## Nhật Ký Thay Đổi

Phần này cung cấp cái nhìn tổng quan về các cập nhật và sửa đổi được thực hiện cho dự án.

- **02/06/2024**: Tải lên ban đầu. Dự án chưa ổn định và có thể cần cải thiện thêm.

Vui lòng đề xuất bất kỳ thay đổi hoặc cải tiến nào có thể được thực hiện cho dự án.