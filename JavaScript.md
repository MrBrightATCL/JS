// *trước khi học javascript hãy học html và css

// tài liệu học
// web: https://developer.mozilla.org/en-US/docs/Web/JavaScript
// Youtube:
// Tiếng Việt:
// https://www.youtube.com/playlist?list=PLPt6-BtUI22pYwpfmkP4EuJkf6GRe63KU
// Tiếng Anh:
// https://www.youtube.com/watch?v=lfmg-EJ8gm4&t=21s

// cách thực hành
// mở một tab mới trên google nhấn F12 hoặc Ctrl + Shift + J

// CƠ BẢN VỀ JAVASCRIPT
// 1.hàm [ alert ] 
// được sử dụng để hiển thị thông báo dạng popup trên trình duyệt người dùng
// ví dụ:
alert ("nội dung");

// 2.hàm [ console.log ]
// là một hàm được sử dụng để xuất thông tin ra màn hình điều khiển ( console ) của trình duyệt
// được sử dụng để hiển thị thông tin debug, giúp phát hiện và sửa lỗi trong mã nguồn
// ví dụ:
console.log("nội dung");

// 3.Multi line console
// thực hiện câu lệnh - phím Enter
// chỉ xuống hàng, không thực hiện câu lệnh - phím Shift + Enter
// nhược điểm là nếu quên nhấn Shift, toàn bộ câu lệnh trước đó sẽ được thực hiện

// 4.Running JavaScript Snippets
// https://www.youtube.com/watch?v=3VPQ8cb3ixQ&list=PLPt6-BtUI22pYwpfmkP4EuJkf6GRe63KU&index=4
// tua đến phút thứ 5:00
// có thể code thoải mái rồi mới chạy code

// 5.Clear console
// Trong trường hợp console có quá nhiều lệnh hoặc muốn dọn console ta sử dụng các cách sau
// 5A. chuột phải - chọn clear console
// 5B. Ctrl + L 

// CÁCH THÊM JAVASCRIPT VÀO HTML
// 6. Thêm JS vào HTML
// 6A. Internal
// đặt trực tiếp code js vào trong cặp thẻ <script> và đặt trước thẻ đóng thẻ body HTML
// Ví dụ:
```html
<body>
    <!-- các thành phần khác của HTML -->
    <!-- đoạn mã js đặt trước thẻ đóng thẻ body -->
    <script>
        // code JavaScript ở đây
        alert("Nội dung");
    </script>
</body>
```
// nhược điểm là làm file html trở nên dài và khó quản lý khi code js nhiều

// 6B.External - Ưu tiên sử dụng cách này
// đặt code js vào một file riêng với phần mở rộng .js
// sau đó sử dụng thẻ <script> để liên kết file js vào trong file html
// Ví dụ:
```html
<body>
    <!-- các thành phần khác của HTML -->
    <script src="./main.js"></script>
</body>
```
// ưu điểm là giúp tách biệt giữa HTML và JavaScript, dễ bảo trì và quản lý khi code js nhiều
// tìm hiểu chi tiết hơn:
// https://www.youtube.com/watch?v=nYiRE8YCVAo&list=PLPt6-BtUI22pYwpfmkP4EuJkf6GRe63KU&index=5
// tua đến phút thứ 2:50

// Khai báo và khởi tạo biến trong JavaScript
// Đặt vấn đề
// 7.Hàm prompt()
// được sử dụng để hiển thị một hộp thoại yêu cầu người dùng nhập dữ liệu
// ví dụ:
prompt("Nhập nội dung:");
// Nhấn Ctrl + / để tạo ghi chú một dòng
/*
ghi chú nhiều dòng
dòng 1
dòng 2
dòng 3
*/
 
 // Biến và khai báo biến
 // Khái niệm: Biến là một ô nhớ trong một bộ nhớ được đặt tên và sử dụng để lưu trữ dữ liệu
 // 3 từ khóa để khai báo biến ( var, let, const )
 // 