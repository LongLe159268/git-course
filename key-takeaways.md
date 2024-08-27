# VCS(version control system)
**Là hệ thống quản lý các phiên bản**
- Local: lưu ở máy cá nhân
- Centralize: lưu ở một máy
chủ tập trung.
- Distributed: lưu ở nhiều
máy khác nhau (GitHub)
# GIT và GITHUB 
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


Lan anh
# Version control system
### 1. Khái niệm 
- Version Control System (VCS): Hệ thống quản lý các phiên bản
### 2. Phân loại VCS:
- Local: lưu ở máy cá nhân
- Centralize: lưu ở một máy chủ tập trung
- Distributed: lưu ở nhiều
máy khác nhau (VD:Git)

# Git
### 1. Tổng quan về Git 
- Git được viết bởi Linus Torvalds, cha đẻ của Linux
- Git là từ viết sai chính
tả (có chủ đích) của get, do get đã được dùng rồi
- Dùng git do nhu cầu quản lý phiên bản và làm việc giữa nhiều người với nhau
### 2. So sánh Git & VCS
- Tính năng: Dễ dùng, nhiều tính năng vượt trội
- Chi phí: Free
- Phổ biến: Nhiều công ty sử dụng 
### 3. So sánh Git & Github 
#### **Git**
- Là một phần mềm
- Cài trên máy của bạn
- Là một commandline tool
- Là công cụ quản lý phiên bản,đưa file vào Git repository
- Có các tính năng của Version Control System
#### **GitHub**
- Là một dịch vụ web
- Host trên website
- Là công cụ có giao diện
- Là nơi để upload Git repository lên
- Có các tính năng của Version Control System và một số tính năng khác
### 4. Git - three states
- Working Directory: Các file mới hoặc file có thay đổi
- Staging Area: Các file đưa vào vùng chuẩn bị commit (tạo ra các phiên bản)
- Repository: Các commit
(phiên bản) 
### 5. Các lệnh thường dùng
- Add file vào Staging: git add <file 1> <file 2>
- Add tất cả file vào Staging: git add .
- Commit: git commit -m "massage" (VD: git commit -m"feat: add file test 1)
- Khởi tạo thư mục được quản lý bởi Git: git init
- Cấu hình git:
- **Cho 1 repo**
 - *git config user.name "<name">*
- *git config user.email "<email">*
- **Cho toàn bộ máy tính**
- *git config --global user.name “user”*
- *git config --global user.email “email”*
- Xem trạng thái file: git status (Màu xanh: vùng staging; Màu đỏ: vùng working directory)
- Kiểm tra lịch sử commit: git log
- Convention = Quy tắc: < type >: <short_description>

# Javascript
### 1. Tổng quan về Javascript 
- Là một ngôn ngữ lập trình
- Javascript
chạy được do browser engine support
- Chạy được trên máy tính không cần trình
duyệt, cần Node Js
- Run-time
### 2. Các câu lệnh
- Ghi vào dòng: console.log  (“HelloWorld!”);
- Chạy lệnh (chạy bằng Terminal): node < path > (VD: node lesson-2/javascript/01-hello.js)
### 3. Variable
- Variable = biến, dùng để lưu trữ giá trị,
có thể thay đổi giá trị được.
- Khai báo: var <tên biến> = <giá trị>;
- Khai báo: let <tên biến> = <giá trị>;
- --> *Var: phạm vi toàn cục (global), let: phạm vi trong cặp ngoặc {}*
- Gán lại: <tên biến> = <giá trị>;
### 4. Constant
- Constant = hằng số, Dùng để khai báo các giá trị không thể thay đổi. 
- Khai báo: const < name > = < value >;
- --> *Không gán lại được với hằng số*
### 5. Data type 
- Có 8 kiểu dữ liệu: String Number, Bigint, Boolean, Undefined, Null, Symbol, Object.
### 6. Comparison operator
- Dùng để so sánh giá trị giữa 2 biến với nhau. Kết quả sẽ trả về Boolean (true hoặc false).
- So sánh hơn kém: >, <
- So sánh bằng: ==, ===,!=, !==, >=, <=
### 7. Unary operator
- Toán tử một ngôi dùng để tăng hoặc giảm giá trị
- i++ bằng với i=i+1
- i-- bằng với i=i-1
### 8. Arithmetic operator
- Toán tử
số học: Dùng tính toán giá trị biểu thức
- Các phép toán: +, -, *, /
### 9. Conditional
- Conditional = điều kiện, dùng để kiểm tra có nên thực hiện một đoạn logic không
- Cú pháp: if (<điều kiện>) { // code }. Nếu
điều kiện đúng, sẽ chạy đoạn code
### 10. Loops
- Dùng để thực hiện một đoạn logic một
số lần nhất định
- Cú pháp: for(<khởi tạo>; <điều kiện dừng>; <điều kiện tăng>) {
// code }