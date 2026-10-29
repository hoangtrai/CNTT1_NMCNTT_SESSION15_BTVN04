
# Phần 1. Thiết lập Hybrid Workflow : 
  **1. Sự cố mất file khi hỏng ổ cứng :**
- sự cố này không thể sảy ra 
- Vì nhờ cơ chế Auto Sync, mọi thay đổi trên file cục bộ  đều được tự động đồng bộ ngầm lên Cloud ngay lập tức

**2. 3 bước thiết lập Auto Sync :**
- **bước 1 :** Tải và cài đặt ứng dụng đồng bộ đám mây
- **bước 2 :** Chọn và cấu hình thư mục làm việc của dự án 
- **bước 2 :** Kiểm tra biểu tượng trạng thái tích xanh trên các file để xác nhận tiến trình đồng bộ

**3. thao tác khôi phục dữ liệu đã học :**
```Mở file trên nền tảng Cloud -> Chọn version history -> Chọn mốc thời gian 10 phút trước -> Nhấn restore```

**4. sai lầm :** 
- Đồng bộ cả thư mục **node_modules**
- Chứa phim 4K giải trí trong thư mục dự án đồng bộ
- cách sử lý : Loại trừ thư mục **node_modules** , không đưa các tệp giải trí cá nhân  vào thư mục làm việc của dự án
# Phần 2. Phân quyền chia sẻ an toàn : 
**1. Mức quyền và Phạm vi chia sẻ phù hợp nhất :**
|file|mức quyền|phạm vi chia sẻ|giải thích|
|-|-|-|-|
|`BaoCao_CuoiKy_SmartCampus.docx` gửi giảng viên|Viewer|Restricted|Cho phép giảng viên đọc/chấm điểm|
|`Slide_BaoCao.pptx` cho 5 thành viên nhóm|Editor|Restricted|Cả nhóm cần cùng nhau chỉnh sửa, hoàn thiện|
|`GopY_BanNhap.docx` gửi anh khóa trên|Commenter|Restricted|cho phép nhận xét, góp ý trực tiếp trên văn bản mà không có quyền sửa đổi nội dung|
|`ThongTin_CaNhan_NhomVien.xlsx`|Restricted|Restricted|Chứa dữ liệu định danh cá nhân, không mở quyền rộng để tránh rò rỉ thông tin|

**2. Quy tắc Cờ Đỏ Bảo mật và giải thích :** 
```không bao giờ kết hợp phạm vi mở rộng công khai  với quyền chỉnh sửa cao đối với các tài liệu chứa dữ liệu nhạy cảm```

**3. 2 thao tác trong cửa sổ Settings :**
- chọn chặn người chỉnh sửa thay đổi quyền truy cập hoặc chia sẻ thêm người khác
- chọn vô hiệu hóa tùy chọn tải xuống, in và sao chép đối với người xem/nhận xét 
# Phần 3.  Tổ chức giao tiếp nhóm chuẩn doanh nghiệp : 
**1. 3 vấn đề đang gặp :** 
- **No-Hello :** Nhắn câu chào cụt lủn thay vì đi thẳng vào vấn đề cần hỗ trợ. 
- **Noise & Off-topic :** Trôi tin nhắn
- Spam @all giờ khuya & Thiếu phân luồng

**2. 2 tên Channel/Topic** : 
- project-smartcampus
- general-chat


**3. Viết lại tin nhắn đầu tiên của `Lan`:**
```Chào mọi người, hiện tại mình đang vướng phần xử lý logic API đăng nhập ở file main.js . Bạn nào có kinh nghiệm phần này hỗ trợ mình với ạ . Cảm ơn mọi người!```
**4. Viết lại tin nhắn `@all`** 
```Chào @Nam và @Hoa, mai là deadline nộp báo cáo cuối kỳ rồi, phần nội dung phân tích của 2 bạn hiện chưa thấy cập nhật lên thư mục chung. Hai bạn hoàn thiện sớm và báo lại giúp mình nhé!```
# Phần 4. Thông báo tổng hợp : 
Chào mọi người, mình đã hoàn thành việc chuẩn hóa không gian làm việc trên Cloud Workspace của nhóm:

1.  Đã thiết lập và bật **Auto Sync** toàn bộ thư mục dự án `D:\Project` để bảo vệ dữ liệu
2.  Đã chia sẻ file `BaoCao_CuoiKy_SmartCampus.docx` cho Giảng viên hướng dẫn dưới dạng **Viewer / Restricted**
    
3. `@Nam` và `@Hoa` lưu ý hoàn thiện gấp phần nội dung báo cáo còn thiếu nhé 
