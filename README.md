# Tạo môi trường ảo

# Cài chứng chỉ cho phiên bản Python đang sử dụng (nếu chưa có)
/Applications/Python\ 3.x/Install\ Certificates.command

# Cài đặt các thư viện cần thiết cho dự án
pip install -r requirements.txt

# Chạy API
uvicorn aws_api:app --reload

# Lấy dữ liệu cho ba vị trí
Hà Nội: 105.85, 21.03
TP.HCM: 106.7, 10.76
Huế: 107.6, 16.47
http://127.0.0.1:8000/weather?lons=105.85,106.7,107.6&lats=21.03,10.76,16.47&start_year=2025&end_year=2025

# Thông tin về Nasa Power
Hướng dẫn: https://power.larc.nasa.gov/docs/tutorials/service-data-request/aws/
Tham số, tên biến (mục Parameters): https://power.larc.nasa.gov/data-access-viewer/