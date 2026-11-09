Đề bài / Yêu cầu
1. Mục tiêu
Xây dựng quy trình Troubleshooting nội bộ giúp nhóm làm việc hiệu quả, tránh hỏi trùng lặp.
2. Vấn đề
Nhóm Startup của bạn thường xuyên gặp các lỗi vặt về môi trường làm việc (Docker, Port conflict).
Mỗi lần gặp lỗi, các thành viên lại nhắn tin loạn xạ vào nhóm chat khiến thông tin bị trôi.
4. Yêu cầu đầu ra
Thiết kế kiến trúc
•	Xây dựng một mẫu Bug Report Template dựa trên 4 mảnh ghép (Context, Expected, Actual, Log) để các thành viên bắt buộc phải điền trước khi hỏi.
Context (Bối cảnh): Hệ điều hành gì? (Ví dụ: Windows 11); Công cụ nào? (Ví dụ: Docker Desktop v4.2).
Expected (Kết quả mong muốn): Hệ thống đáng lẽ phải hoạt động ra sao? (Ví dụ: Container chạy thành công trên port 8080).
Actual (Kết quả thực tế): Lỗi gì đang xảy ra? (Ví dụ: Báo lỗi trùng cổng port, container tự động dừng).
Log (Nhật ký lỗi): Đoạn mã báo lỗi copy từ Terminal/Console (Ví dụ: Error starting userland proxy: bind: address already in use).
Sản phẩm hoàn chỉnh
•	Đề xuất một quy trình 3 bước tra cứu bắt buộc (Googling ➔ Community Search ➔ AI Translation) để thành viên tự xử lý 80% vấn đề trước khi nhờ hỗ trợ.
Bước 1: Googling (Tìm kiếm chung): Copy trực tiếp mã lỗi từ phần Log dán vào Google để tìm nhanh các bài hướng dẫn sửa lỗi phổ biến.
Bước 2: Community Search (Tìm kiếm cộng đồng): Vào thẳng thanh tìm kiếm của StackOverflow hoặc GitHub Issues của Docker để tìm các trường hợp tương tự đã được cộng đồng xử lý thành công.
Bước 3: AI Translation (Dịch & Phân tích bằng AI): Dán đoạn log lỗi vào ChatGPT/Claude kèm câu lệnh: "Dịch, giải thích nguyên nhân lỗi này và đưa ra 3 bước khắc phục nhanh".
