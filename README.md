# Lab_9-Software_Testing
Selenium là bộ công cụ kiểm thử tự động (Automation Testing Framework) mã nguồn mở phổ biến nhất hiện nay, chuyên dùng để tự động hóa các tương tác trên ứng dụng Web.
Selenium cho phép lập trình viên và kiểm thử viên (QA/Tester) viết kịch bản giả lập toàn bộ hành vi của người dùng thực tế trên trình duyệt — từ việc click nút, nhập dữ liệu form, chọn menu đến điều hướng trang và kiểm tra các phần tử giao diện (DOM). Công cụ này hỗ trợ đa dạng trình duyệt phổ biến (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari) và tích hợp mượt mà với nhiều ngôn ngữ lập trình như Python, Java, C#, JavaScript, giúp nâng cao độ chính xác, tiết kiệm thời gian kiểm thử hồi năng (Regression Testing) và tối ưu hóa quy trình phát triển phần mềm.
## 2. Danh sách Kịch bản Kiểm thử (Test Cases)

| STT | Mã TC | Tên kịch bản | Mô tả chi tiết | Kết quả mong đợi |
| :---: | :---: | :--- | :--- | :--- |
| 1 | **TC01** | Đăng nhập hệ thống | Nhập tài khoản `standard_user` & password `secret_sauce` | Đăng nhập thành công, chuyển tới trang `inventory.html` |
| 2 | **TC02** | Lọc/Sắp xếp sản phẩm | Chọn bộ lọc sắp xếp giá từ thấp đến cao (Price: Low to High) | Danh sách sản phẩm hiển thị theo thứ tự giá tăng dần |
| 3 | **TC03** | Thêm vào giỏ hàng | Click nút "Add to cart" sản phẩm Sauce Labs Backpack | Badge biểu tượng giỏ hàng cập nhật số lượng là **1** |
| 4 | **TC04** | Kiểm tra giỏ hàng | Click biểu tượng giỏ hàng trên Header | Chuyển tới `cart.html`, hiển thị đúng sản phẩm đã chọn |
| 5 | **TC05** | Đăng xuất hệ thống | Mở Sidebar Menu và nhấn chọn "Logout" | Đăng xuất thành công, quay về màn hình Login |
