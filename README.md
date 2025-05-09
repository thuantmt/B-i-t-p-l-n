# Dự án Thu Thập Dữ Liệu Báo VnExpress

Đây là một dự án Python dùng `Selenium`, `BeautifulSoup`, và `Pandas` để thu thập dữ liệu từ các chuyên mục trên trang báo [VnExpress](https://vnexpress.net), lưu thành file Excel và tự động chạy vào lúc **2 giờ sáng mỗi ngày**.

# Các chức năng chính

- Thu thập dữ liệu từ các chuyên mục: `Trang chủ`, `Thời sự`, `Thế giới`, `Kinh doanh`, `Giải trí`.
- Lưu thông tin: tiêu đề, mô tả, hình ảnh, nội dung chi tiết và link bài viết.
- Tự động mở trình duyệt Google Chrome để hiển thị trang web đang thu thập.
- Lên lịch tự động chạy lại lúc 2 giờ sáng hàng ngày bằng thư viện `schedule`.

# Yêu cầu hệ thống

- Python 3.8 trở lên
- Google Chrome đã cài đặt
- `chromedriver.exe` phù hợp với phiên bản Chrome (đặt đúng đường dẫn trong code)

# Cài đặt

# 1. Tải mã nguồn về
```bash
git clone https://github.com/your-username/vnexpress-crawler.git
cd vnexpress-crawler
