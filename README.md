# 📝 Ứng Dụng Chuyển Đổi Markdown & LaTeX Sang Word / Docs

Ứng dụng web công cụ hiệu năng cao chạy hoàn toàn offline, giúp biên dịch nội dung văn bản định dạng Markdown kết hợp công thức toán học LaTeX phức tạp sang định dạng tương thích để sao chép chuẩn xác vào Microsoft Word hoặc Google Docs mà không bị lỗi font hay dính chữ.

---

## ✨ Tính Năng Nổi Bật

* **Đồng bộ tự động thông minh:** Tự động tối ưu hoá và bổ sung bộ lọc `\displaystyle` cho toàn bộ các công thức toán học (cả dạng cùng dòng - Inline và dạng khối tách dòng - Block Math) giúp hiển thị công thức trực quan, sắc nét.

* **Sao chép đa định dạng nâng cao:** Tích hợp hộp thoại tuỳ chọn sao chép chuyên dụng giải quyết triệt để bài toán định dạng:

* **Microsoft Word:** Xuất công thức dưới dạng mã MathML gốc, tự động nhận diện thành *Word Equation* kèm đệm khoảng trắng không ngắt (`\u00A0`) chống dính chữ.

* **Google Docs:** Chuyển đổi các ký tự toán học thành dạng hình ảnh PNG độ nét cao (nhân hệ số scale 3x) giữ nguyên tỷ lệ hiển thị.

* **Markdown:** Sao chép chuỗi mã nguồn thô nhanh chóng.

* **Giao diện đối xứng hoàn mỹ:** Thiết kế khung nhìn kép (Split View) song song giữa màn hình soạn thảo và kết quả. Hỗ trợ chế độ phóng to/thu nhỏ độc lập cho từng phân khu và bộ giao diện Responsive tối ưu cho cả máy tính lẫn điện thoại.

* **Tự động lưu bản nháp:** Cơ chế ghi nhớ thông minh tự động lưu lại nội dung đang gõ vào bộ nhớ trình duyệt trình tự theo chu kỳ 1 phút một lần để phòng tránh mất mát dữ liệu khi lỡ tay đóng tab hoặc tải lại trang.

* **Kéo thả nhập file:** Hỗ trợ nạp nhanh nội dung văn bản bằng cách kéo và thả trực tiếp các tệp tin có định dạng `.md` hoặc `.txt` vào vùng làm việc.

---

## 🛠️ Hướng Dẫn Sử Dụng

* **Soạn thảo dữ liệu:** Nhập trực tiếp nội dung Markdown kết hợp các công thức toán học vào khung **Soạn Thảo** ở bên trái. Sử dụng dấu `$` cho công thức cùng dòng (Ví dụ: `$E=mc^2$`) và `$$` cho công thức khối (Block).

* **Quản lý file:**
* Nhấp chọn nút **Xóa** để xóa toàn bộ nội dung (Nhấn lần 2 để xác nhận xóa vĩnh viễn bản nháp).

* Nhấp chọn nút **Tải File** để tải bài viết về máy tính dưới dạng file nguồn `.md` hoặc file trang web đóng gói `.html` (Đã được xử lý tự động gỡ bỏ chữ ẩn và tối ưu thuộc tính in ấn `@media print`).

* **Sao chép kết quả:** Nhấp chọn nút **Chép KQ** (Copy) ở thanh công cụ bên phải, lựa chọn định dạng đích mong muốn (**MS Word** hoặc **Google Docs**) rồi mở ứng dụng văn phòng của bạn lên và nhấn tổ hợp phím `Ctrl + V` để dán trực tiếp.

---

## 📝 Thông Tin Phát Triển

* **Tác giả:** Dương Tấn Chánh

* **Công nghệ tích hợp:** HTML5, CSS3 (Flexbox & Custom Split Grid), JavaScript Thuần (Vanilla JS), tích hợp bộ thư viện phân rã mã nguồn mở `Marked` (Xử lý Markdown) và `MathJax 3` (Xử lý SVG Toán học).
