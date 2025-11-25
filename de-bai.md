# [Bài tập] Hệ thống quản lý đơn hàng Thương mại điện tử

 

## 1. Mục tiêu
Vận dụng mô hình thực thể – quan hệ (ER) để mô tả nghiệp vụ mua bán online
Phân biệt rõ mối quan hệ 1–n và n–n trong tình huống thực tế
Chuẩn hóa sơ đồ để tránh dư thừa dữ liệu
 

## 2. Mô tả
Một trang web bán hàng trực tuyến cần quản lý thông tin về:

Khách hàng (Customer): mã khách hàng, họ tên, email, số điện thoại, địa chỉ
Sản phẩm (Product): mã sản phẩm, tên sản phẩm, giá, mô tả, loại hàng
Đơn hàng (Order): mã đơn, ngày đặt hàng, tổng tiền, trạng thái
Chi tiết đơn hàng (OrderDetail): số lượng, đơn giá tại thời điểm mua
Nhân viên (Staff): mã nhân viên, họ tên, vị trí, ngày vào làm
 

Yêu cầu:

- Xác định các thực thể và thuộc tính chính

- Xác định mối quan hệ giữa các thực thể, ví dụ:

- Khách hàng đặt nhiều đơn hàng

  - Một đơn hàng chứa nhiều sản phẩm

  - Nhân viên xử lý đơn hàng

- Vẽ sơ đồ ERD thể hiện các thực thể, mối quan hệ, và ràng buộc (1–n, n–n)

- Ghi chú khóa chính (PK), khóa ngoại (FK) rõ ràng trong sơ đồ
 

## 3. Đánh giá
Để hoàn thành bài thực hành, học viên cần:

Đưa mã nguồn lên GitHub.
Dán link của repository lên phần nộp bài trên hệ thống.
