Dự Án Quản Lý Kho Hàng (Warehouse Management System)
Dự án website Quản Lý Kho Hàng được xây dựng trên nền tảng ASP.NET Core MVC. Hệ thống giúp tối ưu hóa việc theo dõi hàng hóa, quản lý nhập xuất kho và kiểm soát tồn kho một cách hiệu quả cho doanh nghiệp.

Tính năng chính
Quản lý sản phẩm: Thêm, sửa, xóa và tìm kiếm thông tin hàng hóa.

Quản lý danh mục: Phân loại sản phẩm theo nhóm.

Quản lý nhập/xuất: Theo dõi lịch sử thay đổi số lượng hàng trong kho.

Khu vực quản trị (Admin Area): Giao diện riêng biệt dành cho người quản lý để cấu hình hệ thống.

Bảo mật: Tích hợp xác thực người dùng và bảo mật API.

Tìm kiếm nâng cao: Bộ lọc tìm kiếm thông minh giúp tra cứu hàng hóa nhanh chóng.

Công nghệ sử dụng
Backend: ASP.NET Core MVC (.NET 6/7/8)

Database: SQL Server (sử dụng Entity Framework Core)

Frontend: HTML5, CSS3, JavaScript, Bootstrap

Pattern: Repository Pattern (giúp code sạch và dễ bảo trì)

Cấu trúc thư mục nổi bật
/Areas/Admin: Chứa các controller và view dành riêng cho quản trị viên.

/Controllers: Điều hướng logic xử lý của website.

/Models: Định nghĩa cấu trúc dữ liệu và các thực thể (Entity).

/Views: Giao diện hiển thị cho người dùng.

/Repository: Lớp xử lý logic dữ liệu (giúp tách biệt giữa Controller và Database).

/Migrations: Lưu trữ lịch sử thay đổi cấu trúc Database.

Hướng dẫn cài đặt
Clone dự án:

Bash
git clone https://github.com/bduytuan244/QuanLyKhoHang.git
Cấu hình Database: Mở file appsettings.json và cập nhật chuỗi kết nối (Connection String) phù hợp với SQL Server của bạn:

JSON
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=QuanLyKhoHang;Trusted_Connection=True;"
}
Cập nhật Database: Mở Package Manager Console trong Visual Studio và chạy lệnh:

PowerShell
Update-Database
Chạy dự án: Nhấn F5 hoặc nút Start trong Visual Studio.

Nhật ký cập nhật (Recent Updates)
them bao mat api: Tăng cường bảo mật cho các cổng kết nối dữ liệu.

them chuc nang lay hang: Bổ sung tính năng điều chuyển/xuất kho.

add_search: Tích hợp bộ tìm kiếm sản phẩm.

sửa layout_final: Tối ưu hóa giao diện người dùng.

Người thực hiện: bduytuan

Liên hệ: bdtuan244@gmail.com
