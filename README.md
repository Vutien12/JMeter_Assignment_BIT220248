Báo cáo kiểm thử hiệu năng bằng JMeter
Thông tin sinh viên
Họ tên: Vũ Văn Tiến
MSSV: BIT220248

Website được kiểm thử: https://vnexpress.net

Mô tả kịch bản kiểm thử
Kịch bản 1: Cơ bản
Số lượng người dùng: 18 (10 + 48 % 10 = 18)

Hành vi: Gửi yêu cầu GET đến https://vnexpress.net

Loop Count: 5

Kịch bản 2: Tải nặng
Số lượng người dùng: 58 (50 + 48 % 20 = 58)

Ramp-up Period: 30 giây

Hành vi: Gửi yêu cầu GET đến https://vnexpress.net và một trang con (https://vnexpress.net/giai-tri)

Kịch bản 3: Tùy chỉnh
Số lượng người dùng: 23 (20 + 48 % 15 = 23)

Thời gian chạy: 60 giây

Hành vi: Gửi yêu cầu GET đến https://vnexpress.net/the-thao và https://vnexpress.net/kinh-doanh

Kết quả kiểm thử
Kịch bản 1
Response Time trung bình: 100 ms

Throughput: 3.70 requests/giây

Error Rate: 0.00%

Kịch bản 2
Response Time trung bình:

Trang chủ: 130 ms

Trang con: 124 ms

Throughput:

Trang chủ: 1.96 requests/giây

Trang con: 1.95 requests/giây

Error Rate: 0.00%

Kịch bản 3
Response Time trung bình: 124 ms (trung bình 2 trang 2.2 và 2.1)

Throughput: 2.0 requests/giây

Error Rate: 0.00%

Nhận xét
Website phản hồi ổn định và không có lỗi ở cả ba kịch bản (0.00% Error Rate).

Response Time trung bình thấp (dao động từ 100–130 ms), chứng tỏ website có hiệu năng tốt.

Throughput phù hợp với tải người dùng ở từng kịch bản.

Kịch bản 1 (ít người dùng) cho thấy phản hồi nhanh nhất, trong khi kịch bản 3 cũng duy trì hiệu năng tốt dù thời gian chạy dài hơn.
