# THƯ VIỆN OPEN-CV
Là thư viện bao gồm các chức năng, tiện ích phục vụ cho việc xử lý ảnh được viết trên C++ và Python, Java,... Một số chức năng mà Open-CV cung cấp

* Xử lý ảnh cơ bản: xoay, lật, resize, vẽ lên ảnh, làm mờ, mài ảnh  ..vv...v
* Thao tác với Video: cap hình ảnh, lưu video, vẽ lên video
* Phát hiện vật thể: Tìm ảnh con trong ảnh mẫu, xác định vật thể trong ảnh, xác định góc, viền, cạnh của vật thể, phân khúc hình ảnh, ..v...v
* Truy vết vật thể: Truy vết vật thể di động
* Phân loại và xác định vật thể với YOLO
* Phát hiện khuôn mặt 
* Machine learning cơ bản


Từ đó , OpenCV được ứng dụng trong rất nhiều lĩnh vực như:  phân tích hình ảnh y tế, xe tự hành, các hệ thống nhận diện và giám sát,...

## CÁC MODULE CỦA OPEN-CV
Các chức năng của Open-Cv được phân chia vào các module chính

1. Nhóm xử lý và hiển thị ảnh, video, I/O (Image and Video)
* Image File Reading and Writing : đọc và ghi ảnh
* Core Funtionality : module bao gồm các chức năng tính toán, làm việc với mảng và các cấu trúc dữ liệu cơ bản
* Image Processing (imgproc) : module xử lý hình ảnh gồm cả lọc hình ảnh tuyến tính và phi tuyến (linear and non-linear image filtering), phép biến đổi hình học (chỉnh size, afin và warp phối cảnh, ánh xạ lại dựa trên bảng chung), chuyển đổi không gian màu, biểu đồ.
* Video I/O : đọc ghi video
* High-Level GUI (highgui): giao diện giao tiếp ui đơn giản


2. Nhóm phát hiện vật thể (Object Detection)
* Video Analysis (video): module phân tích video bao gồm các tính năng ước tính chuyển động, tách nền, và các thuật toán theo dõi vật thể.
* Tracking APIs
* Face Analysis: Nhận diện khuôn mặt cơ bản
* Object Detection (objdetect): phát hiện các đối tượng và mô phỏng của các hàm được định nghĩa sẵn – predefined classes
* 2D Feature Framwork (features2d): phát hiện các đặc tính nổi bật của bộ nhận diện, bộ truy xuất thông số, thông số đối chọi.

3. Nhóm thuật toán hình học và thi giác máy tính: (Computer Visiom)
* Computational Photography
* Image Stitching
* Camera Calibration and 3D reconstruction (calib3d): thuật toán hình học đa chiều cơ bản, hiệu chuẩn máy ảnh single và stereo, dự đoán kiểu dáng của đối tượng, thuật toán thư tín âm thanh nổi và các yếu tố tái tạo 3D.

4. Nhóm machine learning (Machine Learning)
* Machine Learning (ml) : modun với các thuật toán machine
* Clustering and Search and Multi-Dimensional Space (flann): Thuật toán phân cụm, tìm kiếm trên không gian đa chiều
* Deep Neural Network Module
Ngoài ra còn 1 số mo đun sẽ được bổ sung trong quá trình tìm hiểu

