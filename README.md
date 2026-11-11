# 19.11 — Chuyên Hạ Long · V6 Midnight Celestial

Bản thiết kế mobile-first, ưu tiên đầy đủ trải nghiệm trên điện thoại.

## Điểm chính
- Giữ cấu trúc nội dung 36 lớp và 36 thư từ dữ liệu V5 (`data.js`).
- Giữ khu vực video nổi bật ở đầu trang; chưa gắn video vì chờ tệp chính thức.
- Ba màu nhận diện: Khối 10 Ice Cyan, Khối 11 Emerald, Khối 12 Amber Gold.
- Tìm kiếm, lọc khối, mở ngẫu nhiên.
- Hộp thư dạng bottom-sheet trên điện thoại, đánh máy theo nhịp câu, có tốc độ, tạm dừng, đọc ngay và âm thanh bật/tắt.
- Nền vũ trụ tối, mạch sáng tiết chế, phản hồi chạm.
- Điều hướng nhanh ở cạnh dưới trên điện thoại; giao diện desktop giản lược.

## Chạy thử
Mở `index.html` bằng trình duyệt hoặc triển khai toàn bộ thư mục lên GitHub Pages.

## Thêm video sau
Đặt video vào `media/`, sau đó cấu hình `src` cho `#memoryPlayer` trong `index.html` hoặc thêm cấu hình video khi chốt tệp chính thức. Hiện trạng thái video chờ được giữ nguyên.

## Lưu ý
`data.js` được sao chép nguyên trạng từ V5, không chỉnh sửa câu chữ, emoji hay thứ tự dữ liệu. V6 chưa được xác nhận kiểm thử trên thiết bị thật; cần kiểm tra thêm trên iOS/Android trước khi phát hành.
