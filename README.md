# 📝 Bộ Soạn Thảo & Chuyển Đổi Markdown / LaTeX / Mermaid Dùng Cho Word & Docs

Một công cụ web mạnh mẽ, tinh gọn và chuyên nghiệp giúp chuyển đổi câu trả lời từ các trợ lý AI (**Gemini, ChatGPT, Claude, DeepSeek...**) chứa công thức Toán học (**LaTeX/MathJax**), sơ đồ lưu đồ (**Mermaid**), bảng biểu và mã nguồn thành định dạng tương thích hoàn hảo để dán trực tiếp vào **Microsoft Word** và **Google Docs**.

> **Tác giả:** Dương Tấn Chánh  
> **Nền tảng:** Web Single-Page Application (Hỗ trợ chạy Offline 100%, không phụ thuộc mạng).

---

## ✨ Tính Năng Nổi Bật

### 1. 📐 Xử Lý Công Thức Toán Học (LaTeX / MathJax) Chuyên Biệt
* **Dán vào Microsoft Word:** Tự động chuyển đổi công thức Toán học sang định dạng **MathML Native (`<math>`)**. Khi dán vào Word, công thức sẽ trở thành **Word Equation gốc**, cho phép chỉnh sửa trực tiếp, thay đổi ký hiệu toán học dễ dàng.
* **Dán vào Google Docs:** Tự động raster hóa công thức Toán sang **ảnh PNG 2x Retina** siêu nét, căn chỉnh trục dọc `-0.5ex` và đệm khoảng cách cứng `\u00A0` chống dính sát chữ, đảm bảo công thức nằm ngay ngắn, thẳng hàng với văn bản.

### 2. 🔤 Tùy Chọn Phông Chữ Linh Hoạt Cho Tài Liệu Xuất
* Khi bấm sao chép cho Word hoặc Google Docs, hệ thống mở hộp thoại trực quan cho phép bạn chọn 1 trong **4 phông chữ chuẩn văn bản**:
  1. **Times New Roman** *(Chuẩn văn bản hành chính & báo cáo học thuật)*
  2. **Arial** *(Hiện đại, rõ ràng, dễ đọc)*
  3. **Roboto** *(Chuẩn phông chữ Google Docs)*
  4. **Noto Sans** *(Đa ngôn ngữ quốc tế)*
* Toàn bộ đoạn văn, tiêu đề, bảng biểu và khối code sẽ tự động đồng bộ theo đúng phông chữ được chọn.

### 3. 📊 Hỗ Trợ Sơ Đồ Quy Trình & Lưu Đồ (Mermaid)
* Nhận diện và vẽ trực tiếp các sơ đồ dạng Flowchart, Sequence, Class... viết bằng cú pháp Mermaid.
* Tự động chuyển đổi sơ đồ thành **ảnh PNG chất lượng cao (Retina)** khi sao chép sang Word / Docs.

### 4. 💻 Tô Màu Mã Nguồn (Syntax Highlight) Đồng Bộ 100%
* Tự động nhận diện ngôn ngữ và tô màu cú pháp lập trình (Python, C++, Java, JS, HTML, v.v.).
* Cỡ chữ khối code tự động kế thừa `1em` (bằng chính xác 100% cỡ chữ Body), đảm bảo tài liệu văn bản luôn đồng nhất và thẩm mỹ.
* Bảng màu code hiển thị trên Web như thế nào thì khi dán vào Word/Docs sẽ giữ nguyên y hệt như vậy.

### 5. 📑 Bảng Biểu Chuẩn Quy Cách Văn Bản
* Viền bảng cố định chuẩn **`0.75pt solid #000000`** phẳng phiu, sắc nét.
* Nhận diện và bảo toàn chuẩn xác thuộc tính căn lề từng cột: **Căn trái (`:---`)**, **Căn giữa (`:---:`)**, **Căn phải (`---:`)**.
* Căn chỉnh bám từ trên xuống dưới (`vertical-align: top;`), giúp các dòng đầu tiên giữa các cột luôn thẳng hàng tự nhiên.

### 6. 📁 Nhập & Xuất Tập Tin Đa Dạng
* **3 phương thức nạp dữ liệu:**
  1. Bấm nút **"Mở File"** để chọn tập tin `.md` hoặc `.txt`.
  2. **Kéo thả tập tin** trực tiếp vào trang web (có overlay trực quan chống nhấp nháy).
  3. **Dán tập tin (`Ctrl + V`)** đã sao chép từ máy tính.
* **Xuất tập tin:** Tải bài viết về máy dưới dạng `.md` hoặc trang web độc lập `.html`.
* **In ấn / Xuất PDF:** Tích hợp nút **"In"** gọi trực tiếp lệnh in của trình duyệt nhẹ nhàng, tiện lợi.

### 7. 🚀 Trải Nghiệm Người Dùng (UX/UI) Thông Minh
* **Giao diện chia đôi màn hình:** Soạn thảo bên trái - Xem trước trực tiếp (Live Preview) tức thì bên phải.
* **Phóng to độc lập:** Hỗ trợ phóng to toàn màn hình riêng cho khung Soạn Thảo hoặc khung Kết Quả.
* **Nút Xoá / Mẫu thông minh:** Tự động chuyển đổi trạng thái: Ô trống $\rightarrow$ hiện nút *Nạp Mẫu*, Có chữ $\rightarrow$ hiện nút *Xoá* (kèm xác nhận 2 bước chống bấm nhầm và tự động cuộn lên đầu trang).
* **Tự động lưu nháp:** Lưu liên tục vào `localStorage`, không lo mất bài khi vô tình tải lại trang.

---

## 🛠️ Hướng Dẫn Sử Dụng Nhanh

### Bước 1: Soạn thảo hoặc Dán nội dung
* Dán nội dung nhận được từ trợ lý AI (ChatGPT/Gemini) vào khung **Soạn Thảo** ở cột bên trái.
* **Công thức cùng dòng (Inline):** Đặt giữa cặp dấu `$...$` (Ví dụ: `$E = mc^2$`).
* **Công thức dạng khối (Display):** Đặt giữa cặp dấu `$$...$$` trên dòng riêng:
  ```latex
  $$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$
  ```
* **Sơ đồ Mermaid:** Đặt trong khối mã ```` ```mermaid ````:
  ```mermaid
  flowchart TD
      A([Bắt đầu]) --> B[/Nhập số nguyên n/]
      B --> C{n chia hết cho 2?}
      C -- Đúng --> D[\In ra: n là số chẵn\]
      C -- Sai --> E[\In ra: n là số lẻ\]
      D --> F([Kết thúc])
      E --> F([Kết thúc])
  ```

### Bước 2: Sao chép sang Word hoặc Google Docs
1. Nhấn nút **"Chép"** ở thanh công cụ cột Kết Quả.
2. Chọn định dạng:
   * **1. Markdown:** Sao chép mã nguồn Markdown thô.
   * **2. Google Docs (Ảnh PNG):** Chép dạng ảnh nét cao cho Google Docs.
   * **3. MS Word (Công thức gốc):** Chép dạng công thức toán chỉnh sửa được cho Word.
3. Nếu chọn Word hoặc Docs, tiếp tục nhấp chọn **Phông chữ** mong muốn (*Times New Roman, Arial, Roboto, Noto Sans*).
4. Mở Microsoft Word hoặc Google Docs và nhấn **`Ctrl + V`** (hoặc `Cmd + V` trên Mac) để dán.

### Bước 3: Quản lý tập tin & In ấn
* Bấm nút **Mở File** (biểu tượng thư mục) để mở file từ máy tính.
* Bấm nút **Tải File** (biểu tượng tải xuống) để lưu file `.md` hoặc `.html`.
* Bấm nút **In** (biểu tượng máy in) để in tài liệu ra giấy hoặc lưu thành file PDF.
* Bấm nút **Xoá** (biểu tượng thùng rác) để làm sạch nội dung bắt đầu bài viết mới.

---

## 🎨 Quy Chuẩn Thiết Kế & Bảng Màu

| Thành phần | Mã màu / Kích thước | Ghi chú |
| :--- | :--- | :--- |
| **Màu giao diện chính** | `#009911` | Xanh lá chuẩn |
| **Màu nút bấm** | `#0077CC` (Chữ/Icon: `#FFFFFF`) | Nền xanh dương, chữ trắng |
| **Nền khối Code** | `#F0F0F0` | Xám sáng nhẹ dịu mắt |
| **Ghi chú Code** | `#969696` | Màu ghi xám nghiêng |
| **Viền giao diện** | `2px solid #A5A5A5` | Khung viền sắc nét |
| **Viền Bảng biểu** | `0.75pt solid #000000` | Chuẩn viền văn bản in ấn |
| **Cỡ chữ Body** | `1.0rem` | Nhỏ gọn, tinh tế |

---

## 👤 Thông Tin Tác Giả & Bản Quyền

* **Tác giả:** Dương Tấn Chánh
* **Mã nguồn:** Thiết kế theo chuẩn Single-page sạch, Vanilla JS thuần, tối ưu hóa bộ nhớ, không rò rỉ RAM và hoạt động bền bỉ trên mọi thiết bị máy tính và điện thoại di động.