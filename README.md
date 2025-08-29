# Đánh Giá Sprint
+ Đánh giá các user story của Sprint ngày 22 tháng 8 năm 2025

  OK
# Nhiệm vụ Sprint thứ 2:
## User Story 1:
Những điểm chính đã đề cập:

- Thẻ PHP: Mã PHP được đặt trong các thẻ <?php ... ?>, và = ?> dùng để in nhanh.
- Biến: Biến trong PHP bắt đầu với ký tự $, theo sau là tên biến.
- Câu lệnh & dấu chấm phẩy: Các câu lệnh PHP kết thúc bằng dấu ; để báo hiệu kết thúc một chỉ thị.
- Kiểu dữ liệu: PHP hỗ trợ nhiều kiểu dữ liệu như chuỗi, số nguyên, boolean, mảng và đối tượng.
- Cấu trúc điều khiển: Đã tìm hiểu về if-else, vòng lặp (for, while, foreach) và switch.
- Hàm: Hàm được định nghĩa bằng từ khóa function, tên hàm và dấu ngoặc để nhận tham số.

Ví dụ:
```php
<?php
$say = "hello";
```

```php
<?php
namespace App\Http\Controllers;

use Illuminate\Http\Request;

class testController extends Controller
{
    public function index(){
        $Duong = "Hello world";
        echo $Duong;
        return view('testView');
    }
}
}
```

Kết quả đánh giá: User story đã hoàn thành thành công. Tất cả các yếu tố quan trọng về cú pháp PHP như biến, toán tử, vòng lặp và cấu trúc điều khiển đều được hiểu rõ.


# Môi trường kiểm thử
## User Story 2:

Kiểm soát lập trình PHP  
Mục tiêu của user story này là khám phá cách PHP quản lý luồng chương trình, bao gồm vòng lặp, câu điều kiện và kiểm soát hàm.

Những điểm chính đã đề cập:

- Câu lệnh If: Dùng để thực thi mã theo điều kiện.
- Switch Case: Cho phép phân nhánh nhiều chiều.
- Vòng lặp: Đã tìm hiểu các vòng lặp for, while, foreach để thực hiện các tác vụ lặp lại.
- Break & Continue: Hai từ khóa này giúp kiểm soát luồng của vòng lặp, với break thoát khỏi vòng lặp và continue chuyển sang lần lặp tiếp theo.
- Gọi hàm: Hàm được dùng để chia nhỏ mã thành các phần có thể tái sử dụng, với return để trả về giá trị.

Kết quả đánh giá: Nhiệm vụ đã hoàn thành thành công. Tất cả các khái niệm về cấu trúc điều khiển của PHP đều được trình bày rõ ràng, và đã hiểu cách quản lý luồng điều khiển trong PHP.

Ví dụ:
```php
<?php
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    $name = $_POST["name"];
    echo "Xin chào, " . htmlspecialchars($name) . "!";
}
?>

<form method="post">
    Nhập tên của bạn: <input type="text" name="name">
    <input type="submit" value="Gửi">
</form>
```

## User Story 3:
Phương thức  
User story này tập trung vào việc hiểu các phương thức trong PHP, đặc biệt quan trọng khi lập trình hướng đối tượng.

Những điểm chính đã đề cập:

- Định nghĩa phương thức: Phương thức là các hàm được khai báo trong lớp, dùng để định nghĩa hành vi cho object.
- Public, Private, Protected: PHP hỗ trợ các phạm vi truy cập cho phương thức, giúp kiểm soát việc truy cập hoặc giới hạn chức năng.
- Phương thức tĩnh: Phương thức thuộc về lớp, không thuộc về đối tượng cụ thể.
- Hàm khởi tạo và hủy: Các phương thức đặc biệt dùng để khởi tạo (__construct) và giải phóng (__destruct) object.
- Gọi phương thức: Phương thức được gọi thông qua đối tượng hoặc tên lớp (nếu là tĩnh).

Kết quả đánh giá: User story đã hoàn thành thành công. Các khái niệm về phương thức, phạm vi truy cập và phương thức tĩnh đều được nắm vững.

## User Story 4:
PHP trong phát triển ứng dụng web  
User story này nhấn mạnh vai trò của PHP trong bối cảnh phát triển ứng dụng web.

Những điểm chính đã đề cập:

- Sinh nội dung động: PHP được dùng phổ biến để tạo trang web động bằng cách nhúng mã PHP vào HTML.
- Tương tác với cơ sở dữ liệu: PHP dễ dàng kết nối với MySQL (hoặc các database khác) để thực hiện các thao tác CRUD (Thêm, Đọc, Sửa, Xóa).
- Session và Cookie: PHP quản lý session và cookie, rất cần thiết để duy trì trạng thái người dùng giữa các lần truy cập trang.
- Xử lý form: PHP thường dùng để xử lý dữ liệu form gửi qua phương thức GET hoặc POST, bao gồm cả kiểm tra và lưu vào database.
- Bảo mật: PHP có các hàm hỗ trợ bảo mật như lọc đầu vào, chống SQL injection và dùng prepared statement.
- Framework: Công cụ như Laravel giúp phát triển PHP hiệu quả hơn với các tính năng như routing, middleware và ORM (Eloquent).

Kết quả đánh giá: User story đã hoàn thành thành công. Vai trò của PHP trong phát triển web đã được hiểu rõ, bao gồm khả năng tạo trang động, tương tác database và quản lý session.
