(Do api tại nơi em theo học đang dùng http nên deploy lên các trang hỗ trợ Free như gh-pages, vercel, netlify sẽ bị tình trạng cors dẫn đến không connect được do đa phần đều dùng https nên em xin phép quay video up lên youtube để giới thiệu dự án ạ)

Dự án đặt vé xem phim 
(Tài khoản: mrxadmin - mật khẩu: mrxadmin)
(Api: http://movieapi.cyberlearn.vn/swagger/index.html)

Phân tích giao diện để tổ chức thư mục
Phân tích chức năng từ đó xác định các component cho dự án
Cài đặt 1 số thư viện cần thiết (React UI, HOC router, Animation)
Cài đặt môi trường cho redux và redux thunk
Tổ chức các lớp đối tượng + services
Tổ chức các templates cho dự án
Css chủ yếu qua tailwind css

+) Phía User Front End
Xây dựng chức năng đăng ký đăng nhập
+ Sử dụng thư viện useFormik để xử lý các input
+ Sử dụng thư viện useTranslation để hỗ trợ 2 ngôn ngữ Anh - Việt

Xây dựng Modal User với thông tin người dùng đã đăng nhập
+ Cho phép người dùng trực tiếp thay đổi các thông tin cá nhân
+ Xem lịch sử đặt vé

Xây dựng Carousel với dữ liệu từ API được cung cấp
+ Tính năng xem trailer từ Youtube

Xây dựng trang chủ thực hiện chức năng load danh sách các phim từ api qua thư viện MultipleRowSlick
+ Trang chi tiết của từng phim khi người dùng chọn vào phim

Xây dựng chức năng load danh sách các rạp phim và lịch chiếu
+ Tính năng đặt vé

Xây dựng trang đặt vé
+ Load sẵn các ghế đã được đặt và các phân loại ghế
+ Tính tổng tiền và cho phép đặt vé
+ Tính năng real time nhiều người đặt chổ trên cùng màn hình
+ Tính năng load lịch sử mua vé


- Phía quản trị
Xây dựng tính năng quản lý danh sách các phim và quản lý các người dùng đã đăng ký
+ Thêm phim/người dùng mới
+ Chỉnh sửa 
+ Xóa phim/người dùng
+ Tạo lịch chiếu/người dùng mới 

