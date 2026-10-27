# Bài kiểm tra Vật lí (GitHub Pages)

## Cấu trúc
```
index.html      <- trang chủ (không liệt kê đề, chỉ nhắc HS dùng link thầy gửi)
khoi10/         <- đề lớp 10 (.html)
khoi11/         <- đề lớp 11 (.html)
khoi12/         <- đề lớp 12 (.html)
.nojekyll       <- để GitHub Pages phục vụ file nguyên trạng
robots.txt      <- chặn công cụ tìm kiếm
```

## Đưa lên GitHub
1. Tạo repository mới trên github.com (vd: `bai-kiem-tra-vat-li`), để **Public** (GitHub Pages miễn phí cần repo public).
2. **Add file -> Upload files**, kéo thả toàn bộ nội dung thư mục này (kể cả `.nojekyll`), rồi **Commit changes**.
3. **Settings -> Pages**: Source = *Deploy from a branch*, Branch = **main**, thư mục **/(root)** -> **Save**.
4. Sau 1–2 phút, trang có địa chỉ: `https://<tên-tài-khoản>.github.io/<tên-repo>/`

## Thêm đề mới
- Chép file đề vào đúng thư mục khối, vd `khoi10/DE_1_KIEM_TRA_LI_10.html`.
- Đặt tên **không dấu, không khoảng trắng** (dùng `_` hoặc `-`) để link gọn, không lỗi.
- Link gửi học sinh: `https://<tên-tài-khoản>.github.io/<tên-repo>/khoi10/DE_1_KIEM_TRA_LI_10.html`
- Chưa đến giờ kiểm tra thì chưa gửi link (hoặc chưa upload file đề đó).

## Lưu ý
- Repo public thì ai có link đều mở được file đề; nếu đáp án nằm trong mã HTML, HS biết xem mã nguồn vẫn đọc được.
