# **Lab 01 - Handwritten Digit Recognition**
## **Thành Viên**
- Đỗ Minh Khôi - 21521007
- Trương Hồ Phước Thịnh - 21522629
## **Dataset**
- MNIST (Modified National Institute of Standards and Technology database)
## **Test Set**
- Bao gồm: 90 tấm ảnh, 10 tấm mỗi class, tổng cộng có 10 class từ số 0-9</a>
## **Các cải thiện để tăng accuracy**
- Tăng độ phức tạp của mạng bằng cách thêm 2 lớp convolution 2D để mạng có thể trích xuất được các đặc trưng phức tạp hơn và thêm các lớp DropOut để có thể giảm overfit, cũng như có thể tăng được kích thước của ảnh đầu vào từ (28, 28) như bộ dataset ban đầu lên (50, 50)
- Thêm bước khử nhiễu ảnh đầu vào trước khi dự đoán để tăng hiệu suất dự đoán của mô hình
## **Accuracy Hiện Tại**
- Accurracy: 87.778% trên tổng 90 tấm ảnh test
## **References**
- https://docs.opencv.org/4.x/d9/d61/tutorial_py_morphological_ops.html
