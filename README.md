# CSSAdminPanel Phiên bản 1 - Sử dụng để tạo thiết kế giao diện Quản Trị.
## Hướng Dẫn Sử Dụng
Để kết hợp kiểu CSS tùy chỉnh vào dự án của bạn, hãy làm theo bước đơn giản sau:

- Liên kết tệp CSS (`index.css`).
- Không cần liên kết tệp **CSS** của Bootstrap (Đang sử dụng phiên bản `Bootstrap.v5.3.3`) vì tôi đã kết nối chúng.
- Cần liên kết JS của Bootstrap và sử dụng như bình thường.

## Mở Rộng

| Class mặc định | Class kèm theo | Mô tả |
|----------------|--------------------|------|
| `.card`        | `.card-custom-box` & `.hrt-custom-box` | Tạo viền màu phần Top |
- Thêm màu sắc khác `.dark` `.success` `.warning` `.danger` `.info`

```html
<div class="card card-custom-box hrt-custom-box dark">
    <div class="card-body">
        <div class="d-flex align-items-top">
            <div class="me-3">
                <span class="avatar bg-dark">
                    <i class="bi bi-person-fill"></i>
                </span>
            </div>
            <div class="flex-fill">
                <p class="card-title">Thành viên đăng ký</p>
                <h5 class="card-text">100</h5>
                <span class="badge bg-dark">New!</span>
            </div>
        </div>
    </div>
</div>
```

## Nhật Ký Thay Đổi

Phần này cung cấp cái nhìn tổng quan về các cập nhật và sửa đổi được thực hiện cho dự án.

- **02/06/2024**: Tải lên ban đầu. Dự án chưa ổn định và có thể cần cải thiện thêm.

Vui lòng đề xuất bất kỳ thay đổi hoặc cải tiến nào có thể được thực hiện cho dự án.