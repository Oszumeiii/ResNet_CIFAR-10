# ResNet_CIFAR-10
Using Pytorch to define ResNet architecture and Using basic numpy define ResNet

## Mục tiêu

- Huấn luyện và đánh giá mô hình ResNet trên dữ liệu CIFAR-10.
- So sánh các biến thể khác nhau của ResNet.
- Cung cấp mã nguồn và hướng dẫn chi tiết để tái tạo kết quả.

## Yêu cầu

- Python 3.x
- Các thư viện: numpy, matplotlib, torch hoặc tensorflow (tùy vào triển khai)
- CUDA (nếu sử dụng GPU)

## Cách sử dụng

1. Cài đặt các thư viện cần thiết:
    ```bash
    pip install -r requirements.txt
    ```
2. Chạy huấn luyện mô hình:
    ```bash
    python train.py
    ```
3. Đánh giá mô hình:
    ```bash
    python evaluate.py
    ```

## Cấu trúc thư mục

- `models/` - Định nghĩa các kiến trúc ResNet.
- `data/` - Xử lý và tải dữ liệu CIFAR-10.
- `train.py` - Script huấn luyện mô hình.
- `evaluate.py` - Script đánh giá mô hình.
- `utils/` - Các tiện ích hỗ trợ.

## Tham khảo

- [Bài báo gốc về ResNet (He et al., 2015)](https://arxiv.org/abs/1512.03385)
- [CIFAR-10 dataset](https://www.cs.toronto.edu/~kriz/cifar.html)
