# NhanDangChuVietTay

1. Cấu trúc thư mục dự án
   ├── data/ # Dữ liệu ảnh, nhãn
   │ ├── train/ # Ảnh train
   │ ├── val/ # Ảnh validation
   │ └── labels.txt # Danh sách tên ảnh + nhãn
   ├── src/ # Mã nguồn
   │ ├── model.py # Mô hình CRNN
   │ ├── dataset.py # Tải và xử lý dữ liệu
   │ ├── train.py # File huấn luyện
   │ ├── utils.py # Hàm tiện ích (decode, metrics,...)
   │ └── predict.py # Dự đoán chữ từ ảnh
   ├── requirements.txt # Danh sách thư viện cần cài
   └── README.md # Mô tả dự án
