# Convolutional Neural Network

* **mnist_lasagne.py**
  * CNN for hand written digit recognition (MNIST)
  * This is the same code as the Lasagne MNIST example with a few slight modifications

* **mnist_nolearn.py**
  * CNN for hand written digit recognition (MNIST)
  * Uses the nolearn package as a wrapper around lasagne and theano for learning diagnostics

* Tôi sẽ sử dụng cơ sở dữ liệu MNIST gồm các chữ số viết tay mà bạn có thể tìm thấy ở : http://yann.lecun.com/exdb/mnist/ . 
* Cơ sở dữ liệu MNIST chứa các hình ảnh tỷ lệ xám có kích thước 28 × 28 (pixel), mỗi hình chứa một số viết tay từ 0-9 (đã bao gồm). Mục tiêu: đưa ra một hình ảnh duy nhất, làm thế nào để chúng ta xây dựng một mô hình có thể nhận ra chính xác số lượng được hiển thị?
* Chỉ với 5 epoch (khoảng 2 phút đào tạo trên GPU), có được độ chính xác phân loại bộ kiểm tra là 98,85%. Nếu đào tạo hơn 50 epochs, có thể đạt được độ chính xác phân loại là 99,6%.
* CNN có thể tìm hiểu cấu trúc hình ảnh của hình ảnh và học cách xác định các tính năng phân biệt số này với số khác. Ý tưởng này có thể được mở rộng thành hình ảnh màu khá dễ dàng (ví dụ với bộ dữ liệu CIFAR-10 ) hoặc thậm chí các đầu vào không dựa trên hình ảnh miễn là có một số cấu trúc không gian vốn có trong đầu vào.
* Link kham khảo : https://github.com/sho-87/python-machine-learning/blob/master/CNN/mnist_lasagne.py
