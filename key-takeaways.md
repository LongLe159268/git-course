# VCS(version control system)
## Là hệ thống quản lý các phiên bản
- Local: lưu ở máy cá nhân
- Centralize: lưu ở một máy
chủ tập trung.
- Distributed: lưu ở nhiều
máy khác nhau (GitHub)
### GIT và GITHUB 
**1.GIT**
- Là một phần mềm
- Cài trên máy local
- Là công cụ quản lý phiên bản, đưa file vào Git repository

**2.GITHUB**
- Là một dịch vụ web
- Host trên website
- Là công cụ có giao diện
- Là nơi để upload Git repository

**GIT - there states**
- Working directory
- Staging Area
- Repository

**GIT - key takeaways**

**git init: Khởi tạo thư mục được quản lý bởi Git**

- Sau khi cài đặt xong, cần cấu hình git:
1. Cho 1 repo
- git config user.name “name”
- git config user.email “email”
2. Cho toàn bộ máy tính
- git config --global user.name“user”
- git config --global user.email“email”

**git add or git add .**
- Thêm file vào vùng staging area
**git status để kiểm tra**
- Kiểm tra xem file đã được chỉnh sửa hay như nào
**git commit -m"message"**
1. Đưa file lên repo kèm theo 1 thông điệp
- Thông điệp theo 1 quy tắc chung: feat,chore,fix

**git log**
- Kiểm tra lịch sử commit

**git push origin <nhánh của bạn>**

# JavaScript
**1. Tạo thư mục lesson-2/javascript**
- Mở bằng VS Code: code .
- Tạo file: 01-hello.js
- Ghi vào dòng: console.log(“Hello World!”);
- Chạy lệnh: node lesson-2/javascript/01-hello.js

**2. Variable(biến) dùng để lưu trữ giá trị, có thể thay đổi đc**
- Khai báo: var <ten_bien> = <gia_tri>;
- Khai báo: let <ten_bien> = <gia_tri>; (chỉ nên dùng let vì var rất dễ nhầm)

**3. Constant: Hằng số dùng để lưu trữ các giá trị không thể thay đổi**
- Khai báo: const <name> = <value>

**4. Data types**
- Có 8 kiểu dữ liệu nhưng chỉ chú ý đến String, Number, Boolean
- Khai báo: let or const <name> = <value>

**5. Comparison operator (toán tử so sánh)**
- Dùng để so sánh giữa 2 biến với nhau
- Các toán tử so sánh: <,>,==,===,!=,!==,>=,<=

**6.Unary operator (toán tử một ngôi)**
- Dùng để tăng hoặc giảm giá trị
- i++ bằng với i=i+1
- i-- bằng với i=i-1

**7. Conditional = điều kiện, dùng để kiểm tra có nên thực hiện một đoạn logic không.**
- Cú pháp: if (<điều kiện>) { // code }. Nếu điều kiện đúng, sẽ chạy đoạn code

**8. Loop: Dùng để thực hiện một đoạn logic một số lần nhất định**
- Cú pháp: for(<khởi tạo>; <điều kiện dừng>; <điều kiện tăng>) { // code }.

# GIT (Undo things)

1. Xem lịch sử commit: **git log**
2. Thay đổi commit message: **git commit --amend**
- Gõ i -> vào chế độ insert
- Gõ esc để thoát insert
- Gõ :wq -> write and quit
3. Đưa từ vùng staging về working directory: **git restore --staged 'file'**
4. Đưa từ vùng repository về working directory (Uncommit): **git reset HEAD~1 (undo 1 commit)**

# Branching model
1. Branch = nhánh
- Dùng branch để tạo ra một vùng làm việc mới, không ảnh hưởng tới vùng làm việc đã ổn định.
2. Tạo branch: **git branch <ten_nhanh>**,
**git checkout <ten_nhanh>**, **git checkout -b <ten_nhanh>**
# .gitignore file
- .gitignore = GitIgnore = Bỏ qua, Dùng để bỏ qua các file không cần git theo dõi.
- Ignore file: <file_name>
- Ignore folder: <folder_name>/
# JAVASCRIPT
## 1. Javascript Conventions
- Tên file: abcd-abcd
- Tên biến: tenBien
- Tên class: TenClass
## 2. Formatted console.log
- console.log('my name í long')
- console.log("my name í long")

- let name = "long";
- console.log(`Toi la ${name}`);
- console.log("Toi ten la " + name + "")
## 3. **OBJECT: đối tượng, dùng để lưu trữ tập hợp các giá trị vào cùng một biến hoặc hằng số**
### Khai báo:
let/const <ten_object> = {<thuoc_tinh>: <gia_tri>...}
Trong đó:
- <thuoc_tinh>: giống quy tắc đặt tên
biến
- <gia_tri>: có kiểu giống biến, hoặc
là 1 object khác.
### Vidu:
- let user = {"name": "Long","age": 22,"email": "longle159268@gmail.com"}
- const product = {"name": "Laptop","price": 100,"isWindow": "true",“manufacturer”: {“name”: “DELL”,“year”: 2024}
### Sử dụng
- console.log("name = " + user.name);
- console.log("manufacturer name = " + product.manufacturer.name);
- console.log(“price = “, product[“price”]);
### Gán lại
- user.age = 28
- product[“manufacturer”][“year”] = 2025
### Logical operator
- && : cả 2 vế của mệnh đề đều đúng
- || : một trong 2 vế đúng
- ! : đảo ngược lại giá trị của mệnh đề
### Array (Mảng)
1. Tạo mảng
- Khai báo
- Sử dụng
2. Truy xuất mảng
- Độ dài mảng: length
- Lấy phần tử theo index: [0], [1], [2]
### Function (Hàm)
- hàm là đoạn code được đặt tên và có thể tái sử dụng, thực hiện 1 nhiệm vụ hoặc 1 tính toán cụ thể.
### Phạm vi của biến, var và let
- Global
- Scope: {}
### == và !=
- So sánh kiểu “lỏng lẻo”
- Convert giá trị về kiểu “lớn hơn”

===: so sánh tuyệt đối
### Điều kiện nâng cao: if...else, if...else if, switch...case
- if... else
- if ... else if ... if
- switch ... case default
- for...in
- foreach
- for...of

- Đối với array
- Đối với object
### Vòng lặp nâng cao: break and continue
- break
- continue