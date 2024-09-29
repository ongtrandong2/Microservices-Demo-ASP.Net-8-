# Mango_Microservices
## Cách chạy source

### Yêu Cầu
  ASP.Net Core 8
  SSMS ( SQL Server Manage System)
#### Bước 1:
  Clone project: open cmd > git clone https://github.com/ongtrandong2/Microservices-Demo-ASP.Net-8-.git
#### Bước 2:
  Khởi Tạo Database như hình (Bỏ BusinessObject):
  ![image](https://github.com/user-attachments/assets/d890608a-b397-4662-9d67-e97fa5c15b5a)
#### Bước 3:
  Seed dữ liệu:
  vào Package Manager Console > Chạy lệnh Update-Database
  ![image](https://github.com/user-attachments/assets/3ae16f89-ba88-4e76-8c54-3402d7e7df6d)
#### Bước 4:
  Configure Startup 
  ![image](https://github.com/user-attachments/assets/a15f8242-715b-4040-b45c-42403e123b5c)
  ![image](https://github.com/user-attachments/assets/2d0b18f8-6294-44a8-9b32-f4399c5a38ca)
#### Bước 5:
  Chạy Project và tận hưởng
  
## Ứng Dụng MicroServices
Gồm 5 user services mỗi service ứng với 1 feature:
 - Product: Thông tin sản phẩm
 - Order: Quản lí thông tin đơn hàng
 - Coupon: Quản lí mã giảm giá
 - Cart: Quản lí giỏ hàng
 - Authentication: Đăng nhập đăng kí có mã hóa bằng JWT 
![image](https://github.com/user-attachments/assets/c842127b-8411-42df-8d7b-2d0c44e4e027)
