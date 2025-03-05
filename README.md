# thongbao

## Mô tả
Ứng dụng Android sử dụng timer 30s để lấy dữ liệu từ API tại `http://10.0.2.2:5000/last_id` và hiển thị thông báo khi có tin nhắn mới.

## Hướng dẫn cài đặt
1. Chạy API:
   - Di chuyển đến thư mục `api/`.
   - Chạy `python app.py`.
2. Chạy ứng dụng Android:
   - Mở dự án trong Android Studio.
   - Chạy trên emulator.

## Màn hình demo
![Màn hình Android]![z6375684589027_752beb2c9056945cc8c102642824a7d6](https://github.com/user-attachments/assets/cc3318c4-8d57-4bdf-bd25-f5898ad7276e)
![Nhận thông báo từ API]![z6375684589280_5a2e41fc26736b4e9e388074336d7ff6](https://github.com/user-attachments/assets/7b128568-ac21-492a-ba0b-2b7593d9c0e4)
![Màn hình Web API]![z6375412386794_c90618d7c705fdab16e225cef7c54253](https://github.com/user-attachments/assets/3d4c41e6-ded4-4bee-b338-453bec41b892)


## Yêu cầu
- Việt app Android sử dụng timer 30s/lần lấy dữ liệu từ `http://10.0.2.2:5000/last_id`.
- Lấy dữ liệu `last_id` và tải tin nhắn từ `http://10.0.2.2:5000/get_id?id={last_id}`.
- Push code lên GitHub và thêm màn hình vào README.md.

## Lí do
- Vì em truy cập vào đường link API nhưng đã bị chặn hoặc khóa em không thể truy cập được vào nên em đã tự tạo một API mới tương tự để làm lại bài thông báo.
  
