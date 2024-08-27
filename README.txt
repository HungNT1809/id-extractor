Project: Trích xuất dữ liệu Căn cước công dân Việt Nam.

1. Giới thiệu
Đây là ứng dụng web hỗ trợ việc trích xuất thông tin từ Căn cước công dân của công dân Việt Nam.

2. Cách cài đặt
Tệp tin requirements.txt chứa các thư viện cần thiết và phiên bản tương ứng với mỗi thư viện. Có thể cài đặt bằng lệnh:
	pip install -r requirements.txt
hoặc build thông qua Docker (https://www.docker.com/) bằng lệnh:
	docker build -t <app_name> 

3. Cách sử dụng
Nếu sử dụng Python, thực thi lệnh sau:
	python run.py
Nếu sử dụng Docker, thực thi lệnh sau:
	docker run -p 8080:8080 <app_name>

4. Hướng phát triển
- Cải thiện các tính năng eKYC.
- Tăng tốc độ nhận dạng (bằng cách sử dụng mô hình YOLO mới hơn...)
- Tăng độ chính xác của văn bản nhận dạng được.
- Cải thiện khả năng nhận dạng CCCD trong các điều kiện ánh sáng khác nhau...

Lưu ý quan trọng: do thư mục database chứa cơ sở dữ liệu cần thiết cho phần mềm có dung lượng lớn nên em không nén vào file tải lên qldt. Thay vào đó, em đã tải lên github cá nhân và đính kèm đường dẫn đến github vào phần phụ lục của báo cáo ĐATN. 