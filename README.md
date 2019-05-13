# Convolutional Neural Network

* **mnist_lasagne.py**
  * CNN for hand written digit recognition (MNIST)
  * This is the same code as the Lasagne MNIST example with a few slight modifications

* **mnist_nolearn.py**
  * CNN for hand written digit recognition (MNIST)
  * Uses the nolearn package as a wrapper around lasagne and theano for learning diagnostics

* Tôi sẽ sử dụng cơ sở dữ liệu MNIST gồm các chữ số viết tay mà bạn có thể tìm thấy ở :http://yann.lecun.com/exdb/mnist/ . 
* Cơ sở dữ liệu MNIST chứa các hình ảnh tỷ lệ xám có kích thước 28 × 28 (pixel), mỗi hình chứa một số viết tay từ 0-9 (đã bao gồm). Mục tiêu: đưa ra một hình ảnh duy nhất, làm thế nào để chúng ta xây dựng một mô hình có thể nhận ra chính xác số lượng được hiển thị?
