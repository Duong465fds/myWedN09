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
<img width="1559" height="181" alt="first exercise" src="https://github.com/user-attachments/assets/ed2e62fc-5328-4d6b-be92-a9dfbb5bee8f" />

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
# User Story 8: Model (Database)

## Mục tiêu
Trong thiết kế phần mềm, **Model** là phần chịu trách nhiệm biểu diễn và xử lý dữ liệu mà ứng dụng sử dụng. Model đóng vai trò là lớp kết nối giữa ứng dụng và cơ sở dữ liệu, giúp ánh xạ (mapping) các đối tượng trong mã nguồn thành các bảng trong hệ quản trị cơ sở dữ liệu quan hệ (Relational Database).  
Model đồng thời chịu trách nhiệm cho việc xác thực, xử lý logic nghiệp vụ và đảm bảo tính toàn vẹn của dữ liệu.

## Ví dụ trong hệ thống quản lý sức khỏe
Một **Doctor Model** đại diện cho thông tin của bác sĩ trong hệ thống. Mỗi bác sĩ có các thuộc tính mô tả thông tin cá nhân và chuyên môn, bao gồm:
- `doctor_id`: Mã định danh của bác sĩ (khóa chính)
- `name`: Họ tên bác sĩ
- `specialty`: Chuyên khoa
- `phone_number`: Số điện thoại
- `email`: Địa chỉ email
- `created_at`: Thời điểm tạo bản ghi
- `updated_at`: Thời điểm cập nhật bản ghi

---


## User Story 14:
## RESTful API là gì?

**RESTful API** (Representational State Transfer Application Programming Interface) là một kiểu kiến trúc xây dựng API phổ biến trong phát triển web hiện đại.

### Đặc điểm chính:
- **Giao tiếp qua HTTP:** Sử dụng các phương thức HTTP như GET (lấy dữ liệu), POST (tạo mới), PUT/PATCH (cập nhật), DELETE (xóa).
- **Stateless:** Mỗi request là độc lập, server không lưu trạng thái của client giữa các request.
- **Địa chỉ tài nguyên rõ ràng:** Mỗi tài nguyên (ví dụ: user, bài viết, sản phẩm, ...) đều có một URL duy nhất.
- **Định dạng dữ liệu:** Dữ liệu trao đổi thường ở dạng JSON hoặc XML.
- **Khả năng mở rộng và tích hợp:** API dễ bảo trì, phát triển thêm tính năng, tích hợp với các hệ thống khác.

### Ví dụ về các endpoint RESTful:
```
GET    /users         // Lấy danh sách người dùng
GET    /users/1       // Lấy thông tin người dùng có id=1
POST   /users         // Tạo người dùng mới
PUT    /users/1       // Cập nhật thông tin người dùng id=1
DELETE /users/1       // Xóa người dùng id=1
```

RESTful API giúp việc phát triển web, mobile, microservice trở nên dễ dàng, linh hoạt và chuẩn hóa hơn!


## code


```
namespace App\Http\Controllers;

use Illuminate\Http\Request;
use App\Models\Book;
class BookController extends Controller
{
  
   public function apiGetBooks(){
        $books = Book::all();
        $jsonBooks = json_decode($books);
        return response()->json($jsonBooks);
    } 
}

```
<img width="1920" height="999" alt="image" src="https://github.com/user-attachments/assets/027077d0-a7f5-4da6-8f8b-a27effca7193" />

## User Story 15:
## Giải thích về HTTP POST: Header, Body và Params

Khi gửi request HTTP POST (thường dùng với RESTful API), có 3 phần quan trọng:

---

### 1. POST Header

- Là các thông tin phụ trợ đi kèm request, mô tả kiểu dữ liệu, xác thực, v.v.
- Các header phổ biến:
  - `Content-Type`: Kiểu dữ liệu của body (ví dụ: `application/json`, `application/x-www-form-urlencoded`)
  - `Authorization`: Token xác thực (ví dụ: `Bearer <token>`)
  - `Accept`: Định dạng dữ liệu phản hồi mong muốn (ví dụ: `application/json`)

**Ví dụ:**
```
Content-Type: application/json
Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9...
```

---

### 2. POST Body

Là phần dữ liệu chính gửi lên server để xử lý.

#### a. JSON Body

- Định dạng dữ liệu kiểu JSON, thường dùng với API hiện đại.
- Header cần có: `Content-Type: application/json`
- **Ví dụ:**
  ```json
  {
    "username": "duong465fds",
    "password": "123456",
    "profile": {
      "age": 20,
      "email": "abc@example.com"
    }
  }
  ```

#### b. Input Form (Form Data)

Có hai kiểu phổ biến:

**application/x-www-form-urlencoded**
- Dữ liệu mã hóa dạng key=value, giống query string.
- Header: `Content-Type: application/x-www-form-urlencoded`
- **Ví dụ:**
  ```
  username=duong465fds&password=123456&email=abc%40example.com
  ```

**multipart/form-data**
- Dùng cho form có upload file.
- Header: `Content-Type: multipart/form-data; boundary=----WebKitFormBoundaryXYZ`
- **Ví dụ mô phỏng:**
  ```
  ------WebKitFormBoundaryXYZ
  Content-Disposition: form-data; name="username"

  duong465fds
  ------WebKitFormBoundaryXYZ
  Content-Disposition: form-data; name="avatar"; filename="me.jpg"
  Content-Type: image/jpeg

  [binary file data]
  ------WebKitFormBoundaryXYZ--
  ```

---

### 3. POST Params (Parameters)

- Là các tham số truyền lên server để xác định hoặc lọc dữ liệu.
- Có thể truyền qua:
  - **Query String:** trên URL, ví dụ: `POST /users?role=admin`
  - **Body Parameters:** nằm trong phần body (dạng JSON hoặc form-data).
  - **Path Parameters:** nằm trực tiếp trong URL, ví dụ: `/users/123`

**Ví dụ kết hợp:**

- URL: `POST /users?role=admin`
- Body:
  ```json
  {
    "username": "duong465fds",
    "password": "123456"
  }
  ```

---

### Tổng kết

- **POST header:** thông tin phụ trợ, định dạng, xác thực, v.v.
- **POST body:** dữ liệu chính gửi lên server (JSON, form-data,...)
- **POST params:** tham số truyền qua URL (query), path, hoặc trực tiếp trong body.

