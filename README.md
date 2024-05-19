# VietNamese-Sign-Language

Nhận dạng ngôn ngữ ký hiệu Việt Nam dựa trên 2 hướng tiếp cận: Mediapipe + LSTM và Các mô hình CNN (VGG16, MobileNet, ResNet-50)  + LSTM

Dữ liệu: 250 dữ liệu video từ https://facundoq.github.io/datasets/lsa64/ với mục đích mô phỏng dữ liệu ngôn ngữ ký hiệu Việt Nam. Lý do: Việt Nam chưa có bộ dữ liệu công khai, đủ tốt để huấn luyện 


Đánh giá: 

1. Xét trên tập dữ liệu chưa tăng cường: Độ chính xác của Mediapipe cao hơn gấp đôi so với mô hình CNN

2. Xét trên tập dữ liệu tăng cường:

   - Độ chính xác với phương pháp Mediapipe + LSTM: 97%
   - Độ chính xác với phương pháp CNN + LSTM tốt nhất: 94%
  
Kết luận: 
- Ưu tiên phát triển theo hướng tiếp cận Mediapipe + LSTM
- Nghiên cứu phương pháp tăng cường dữ liệu sử dụng thuật toán di truyền


