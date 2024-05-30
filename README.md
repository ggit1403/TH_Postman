# TH_Postman
BÁO CÁO BÀI TẬP THỰC HÀNH KIỂM THỬ VỚI POSTMAN ĐỖ HOÀNG GIANG - 21012054

  Giới thiệu Postman Postman là một công cụ mạnh mẽ dùng để phát triển và kiểm thử API. Nó cung cấp một giao diện thân thiện và dễ sử dụng cho phép các nhà phát triển gửi yêu cầu HTTP, xem phản hồi và thực hiện các kiểm thử API một cách hiệu quả. Postman được sử dụng rộng rãi trong cộng đồng phát triển phần mềm nhờ vào tính năng phong phú và khả năng hỗ trợ nhiều phương thức HTTP.
  
Các tính năng chính của Postman:

  - Gửi các yêu cầu HTTP: Hỗ trợ tất cả các phương thức HTTP như GET, POST, PUT, DELETE, PATCH, và OPTIONS.
  - Xem phản hồi: Postman cho phép bạn xem phản hồi.expand_more Bạn có thể xem mã trạng thái HTTP, header, body và nội dung phản hồi.expand_more
  - Chạy thử nghiệm tự động (Tests): Viết các kịch bản kiểm thử bằng JavaScript để tự động kiểm tra phản hồi của API.
  - Tích hợp CI/CD: Tích hợp với các công cụ CI/CD để tự động kiểm thử trong quy trình phát triển phần mềm.

Kiểm thử API cơ bản
    Kiểm thử API GET: URL: https://reqres.in/api/users/2 Mô tả: Lấy thông tin người dùng với ID là 2 Kết quả:
![1](https://github.com/ggit1403/TH_Postman/assets/96821807/93c2b583-e1a0-493f-bc6e-3f43586f4d1b)

    Kiểm thử API POST: URL: https://reqres.in/api/users Mô tả: Tạo một người dùng mới. Dữ liệu (Body): { "name": "giang", "age": 20 } Kết quả:
![2](https://github.com/ggit1403/TH_Postman/assets/96821807/3a0b8f20-4c71-4d48-b51c-67fa0d4d8ef7)

    Kiểm thử API PUT: URL: https://reqres.in/api/users/2 Mô tả: Cập nhật thông tin người dùng với ID là 2. Dữ liệu (Body): { "name": "giang", "age": 20 } Kết quả:
![3](https://github.com/ggit1403/TH_Postman/assets/96821807/68175340-bbea-49f5-aa04-d41e78c83d9f)

    Kiểm thử API DELETE: URL: https://reqres.in/api/users/2 Mô tả: Xóa người dùng với ID là 2. Kết quả:
    ![4](https://github.com/ggit1403/TH_Postman/assets/96821807/13bb47b3-dc0e-4ffd-9441-317d85dadfcc)

