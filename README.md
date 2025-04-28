# Ransomware-Detection-Using-Spark-MLlib
Dự án "Ransomware Detection Using Spark MLlib" tập trung vào việc phát hiện các cuộc tấn công ransomware trong hệ thống lưu trữ thông qua các phương pháp học máy. Mục tiêu chính của dự án là xây dựng một mô hình học máy sử dụng Spark MLlib để phân tích và phát hiện hành vi của ransomware qua các đặc điểm hệ thống như CPU, RAM, hoạt động I/O, và các thông số khác. Dự án sử dụng bộ dữ liệu RANSAP – một bộ dữ liệu chứa thông tin về các cuộc tấn công ransomware, giúp mô phỏng và phân tích các hành vi của ransomware trong môi trường hệ thống lưu trữ.

Các tính năng chính của dự án:

Sử dụng Spark MLlib để xây dựng mô hình học máy:

Dự án áp dụng Spark MLlib, thư viện học máy của Apache Spark, để triển khai các mô hình phân loại nhằm phát hiện ransomware. Spark MLlib có khả năng xử lý lượng dữ liệu lớn và phân tán, là công cụ lý tưởng cho việc phân tích và phát hiện các cuộc tấn công ransomware.

Phân tích dữ liệu từ bộ dữ liệu RANSAP:

Dữ liệu CPU và RAM: Dự án sử dụng dữ liệu từ bộ RANSAP để phân tích các chỉ số về CPU, bộ nhớ RAM và các đặc điểm hệ thống khác. Những hành vi bất thường trong việc sử dụng tài nguyên hệ thống sẽ được sử dụng để nhận diện ransomware.

Hoạt động I/O và các thông số khác: Các dữ liệu liên quan đến các hoạt động I/O, thay đổi đột ngột trong quá trình đọc/ghi dữ liệu và các chỉ số khác trong hệ thống có thể là những dấu hiệu của một cuộc tấn công ransomware.

Ứng dụng thuật toán phân loại để phát hiện ransomware:

Các thuật toán phân loại, chẳng hạn như Decision Trees, Random Forests, Support Vector Machines (SVM), và Logistic Regression, được áp dụng để phân tích các mẫu hành vi của ransomware trong dữ liệu RANSAP.

Mô hình học máy sẽ được huấn luyện để nhận diện và phân loại các cuộc tấn công ransomware dựa trên các dấu hiệu hành vi có trong dữ liệu.

Đánh giá hiệu suất mô hình và so sánh với các phương pháp khác:

Các chỉ số đánh giá mô hình như Precision, Recall, F1-score, và Accuracy sẽ được sử dụng để đánh giá độ chính xác của các mô hình phân loại.

Dự án sẽ so sánh các mô hình học máy được xây dựng từ Spark MLlib với các phương pháp phát hiện ransomware truyền thống hoặc các mô hình học máy khác để tìm ra phương pháp hiệu quả nhất.

Tích hợp các phương pháp học sâu (Deep Learning):

Dự án có thể thử nghiệm các mô hình học sâu, như Neural Networks, để kiểm tra hiệu quả của chúng trong việc phát hiện các cuộc tấn công ransomware, đặc biệt trong các tình huống khó phát hiện hơn.

Phát hiện hành vi ransomware dựa trên dữ liệu thời gian thực:

Mô hình có thể được triển khai trong môi trường giám sát thời gian thực, nơi nó sẽ liên tục phân tích và phát hiện các dấu hiệu của ransomware ngay khi chúng xuất hiện.

Cải thiện khả năng phát hiện và giảm thiểu sai sót (False Positives):

Các phương pháp tối ưu hóa sẽ được sử dụng để giảm thiểu số lượng cảnh báo sai (false positives), giúp mô hình phát hiện ransomware một cách chính xác mà không gây ảnh hưởng đến hiệu suất hệ thống.

