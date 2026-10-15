# QUẢN LÝ ĐIỂM SINH VIÊN - STREAMLIT

Ứng dụng sử dụng đúng danh sách và điểm trong tệp `Nam30_pythonproject.pdf.pdf` bạn đã gửi.

## Các tệp
- `app.py`: mã nguồn Web App.
- `requirements.txt`: thư viện cần cài.
- `README.md`: hướng dẫn chạy và triển khai.

## Chạy trên máy tính
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Đưa lên GitHub và Streamlit Community Cloud
1. Tạo repository mới trên https://github.com/
2. Tải `app.py` và `requirements.txt` lên repository.
3. Vào https://share.streamlit.io/ và đăng nhập bằng GitHub.
4. Chọn Create app, repository vừa tạo, branch `main`, main file path `app.py`.
5. Nhấn Deploy và chờ ứng dụng chạy.
6. Sao chép URL ứng dụng sau khi triển khai thành công.

## Dữ liệu và công thức
Danh sách sinh viên, điểm chuyên cần, giữa kỳ và cuối kỳ được nhập theo notebook trong PDF:
- Nguyễn Thị Lan
- Phan Bình
- Lê Thị Chi
- Nguyễn Văn Dũng
- Phan Thị Hà
- Bùi Lan
- Đinh Minh
- Lê Văn Nam
- Nguyễn Đức Phúc
- Nguyễn Thu Trang

Điểm tổng kết = 20% × Chuyên cần + 30% × Giữa kỳ + 50% × Cuối kỳ.

Xếp loại:
- Điểm >= 8.5: Giỏi
- 7.0 <= Điểm < 8.5: Khá
- 5.0 <= Điểm < 7.0: Trung bình
- Điểm < 5.0: Yếu

Người tạo ứng dụng: Lê Văn Nam - MSSV 067208003476.
