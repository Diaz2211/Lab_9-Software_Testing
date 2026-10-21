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

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/2d32d8c5-f286-44f3-b8b6-9ecf96899d81" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/11110278-1513-4951-b43f-41fa9a0df828" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a7883dda-c8c7-482d-9cc2-5cdc91e5a082" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/34f70ca1-c2d9-47ef-a2c2-1fe89ab08afc" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/ef929a91-68b9-47fb-be0c-a8d06ff480ac" />
<img width="542" height="257" alt="image" src="https://github.com/user-attachments/assets/47a80bf8-260d-4856-85de-08f5f40a80e6" />
