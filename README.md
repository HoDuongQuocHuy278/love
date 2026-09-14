# Website kỷ niệm 1 năm

Trang này là website tĩnh, có thể chạy trực tiếp trên GitHub Pages mà không cần cài đặt hay build.

## Thêm nhạc

1. Chép các file MP3 vào thư mục `assets`.
2. Đặt tên lần lượt là `nhac-1.mp3`, `nhac-2.mp3`, `nhac-3.mp3`.
3. Nếu chỉ dùng một hoặc hai bài, xóa các dòng không dùng trong biến `MUSIC_PLAYLIST` ở cuối `index.html`.
4. Có thể đổi tên hiển thị của bài hát trong cùng biến đó.

Trình duyệt chặn website tự phát nhạc khi chưa có tương tác. Trang đã xử lý bằng cách bắt đầu phát ngay lần chạm/bấm phím đầu tiên; người xem cũng có thể dùng nút phát ở góc trên bên phải.

## Đưa lên GitHub Pages

1. Tạo một repository mới trên GitHub.
2. Tải toàn bộ nội dung thư mục này lên nhánh `main`, giữ nguyên `index.html` ở thư mục gốc.
3. Vào **Settings → Pages**.
4. Trong **Build and deployment**, chọn **Deploy from a branch**.
5. Chọn nhánh `main`, thư mục `/(root)`, rồi bấm **Save**.

Sau khi GitHub hoàn tất triển khai, trang sẽ có địa chỉ dạng:

`https://TEN_GITHUB.github.io/TEN_REPOSITORY/`

## Lưu ý

- Tất cả đường dẫn tài nguyên nội bộ đều bắt đầu bằng `./`, nên hoạt động đúng khi GitHub Pages đặt trang trong thư mục repository.
- GitHub không nhận một file lớn hơn 100 MB. Nên nén mỗi bài MP3 còn khoảng 3–10 MB để trang tải nhanh trên điện thoại.
- Nếu tên file có dấu hoặc khoảng trắng, hãy đổi sang tên ngắn không dấu để tránh lỗi đường dẫn.
- Mật khẩu hiện tại là `123456` và có thể đổi trong hằng số `PASSWORD` ở cuối `index.html`.
- Hai ảnh mẫu hiện dùng link Unsplash. Muốn ổn định hoàn toàn, hãy chép ảnh vào `assets` và đổi `src` thành `./assets/ten-anh.jpg`.
