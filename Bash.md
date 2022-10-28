1. Cấu trúc file bash
  - Dòng đâu tiên và bắt buộc với một file bash với đuôi mở rộng là .sh ( trên Linux ) hoặc .bat trên Window ) là câu lệnh này
 2. Các biến trong file bash:
  - Có 2 kiểu biến trong file bash

Setting a value for a variable.
Reading the value for a variable.
Đơn giản khi chúng ta cần tham chiều và để đọc giá trị của biên đó thì ta dùng Reading the value với cú pháp thêm dấu $ trước tên biến Khi chúng ta muốn gán giá trị cho biến thì ta dùng Setting a value chỉ cần bỏ dấu $ đằng trước đi là được

Một số biến của hệ thống như :

$0- Tên của file  Bash script.
$1 - $9 - lần lượt là các đối số truyền vào cho file Bash script.
$# - Số lượng các  arguments chúng ta truyền vào cho file the Bash script.
$@ - Tất cả các đối số cung cấp cho file  Bash script.
$? - Trạng thái của câu lệnh thực hiện gần nhất ( 0 -> true , 1 -> false ) 
$$ - ID của script hiện tại .
