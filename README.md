# TRẢ LỜI CÂU HỎI LÝ THUYẾT PHẦN COOKIE
### Câu hỏi:
1. Mục đích của Cookie là gì?
2. Cookie là công nghệ chỉ có trong Spring Boot. Đúng hay Sai?
3. Thuộc tính Expires/Max-Age tính bằng đơn vị gì? Ý nghĩa của nó là gì?
4. Thuộc tính Domain của Cookie có ý nghĩa gì?
5. Thuộc tính nào cho phép mã JavaScript ở client có thể đọc được giá trị của Cookie?
6.Thuộc tính Path có tác dụng như thế nào?
### Trả lời:
1. Tác dụng của Cookie
- Quản lý session: trạng thái đăng nhập, thông tin giỏ hàng,...
- Lưu thông tin cài đặt của người dùng: theme (dark mode hay light mode), ngôn ngữ (tiếng việt, tiếng anh), thông tin username/email trong mục bình luận,...
- Theo dõi và phân tích hành vi người dùng: các trang đã truy cập, truy cập bao nhiêu lần,...
2.  Sai, cookie được sử dụng rộng rãi trên các loại web trên internet bất kể loại language hay framework nào.
3. Thuộc tính Expires/Max-Age tính bằng giây tính thời gian mà cookie sống.
4. Thuộc tính Domain của Cookie chỉ ra tên miền, server nào sẽ nhận cookie này.
5. Thuộc tính HttpOnly là false cho phép mã JavaScript ở client có thể đọc được giá trị của Cookie.
6. Thuộc tính Path dùng để khai báo những đường dẫn bắt buộc trong URL để server gửi cookie xuống client.
