# GenAI4Dev - Khóa học Generative AI cho Phát triển Phần mềm

Dự án này chứa tài liệu, code mẫu và slides cho khóa học "Generative AI trong Phát triển Phần mềm" tại Greenwich Vietnam.

## Cấu trúc dự án

### 📁 `/code`
Chứa các file code Python thực hành cho từng buổi học:
- **`utils.py`**: Các hàm tiện ích chung được sử dụng trong toàn bộ khóa học
- **`long_prompt.txt`**: File chứa các prompt dài để test và thực hành
- **`lecture02/`**: Code thực hành cho Buổi 2 - Lập trình với Gemini API
- **`lecture03/`**: Code thực hành cho Buổi 3 - Multimedia trong Gemini API  
- **`lecture04/`**: Code thực hành cho Buổi 4 - Các khái niệm nâng cao

### 📁 `/slides`
Chứa tài liệu slides và các file hỗ trợ cho việc tạo bài giảng.

## Files quan trọng trong `/slides`

### 📄 `common_errors.md`
**Mục đích**: Tài liệu tổng hợp các lỗi thường gặp khi làm việc với Greenwich Presentation Template và cách khắc phục.

**Nội dung chính**:
- Lỗi về định vị footer (Footer Positioning Issues)
- Vấn đề với navigation buttons
- Lỗi hiển thị list items
- Vấn đề về layout và responsive design
- Các giải pháp cụ thể với code CSS chi tiết

**Đối tượng sử dụng**: Giảng viên và người phát triển slides cần khắc phục lỗi kỹ thuật.

### 📄 `outline_program.txt`
**Mục đích**: Kế hoạch tổng thể của khóa học, chia thành 8 buổi học.

**Nội dung chính**:
- **Buổi 1**: Giới thiệu Gen AI trong phát triển phần mềm
- **Buổi 2**: Lập trình Gen AI với Gemini API (stateless, stateful, system prompt)
- **Buổi 3**: Multimedia trong Gemini API (ảnh, audio, upload tài liệu)
- **Buổi 4**: Khái niệm nâng cao (Code Execution, Function Calling, Caching)
- **Buổi 5**: RAG cơ bản
- **Buổi 6**: Fine-tuning
- **Buổi 7**: MCP (Model Context Protocol)
- **Buổi 8**: Agent

**Đối tượng sử dụng**: Giảng viên để lập kế hoạch giảng dạy và sinh viên nắm được roadmap khóa học.

### 📄 `prompt_lecture.md`
**Mục đích**: Hướng dẫn chi tiết cho AI (ChatGPT/Claude) để tạo slides bài giảng theo đúng format và yêu cầu.

**Nội dung chính**:
- **Critical Success Factors**: Các yếu tố quan trọng phải tuân thủ
  - Content Accuracy: Không được rút gọn hay tóm tắt nội dung
  - Template Compliance: Phải tuân thủ đúng template có sẵn
  - Systematic Workflow: Quy trình làm việc có hệ thống
- **Content Requirements**: Yêu cầu về nội dung (tiếng Anh, dựa trên outline.md)
- **Template Selection**: Hướng dẫn chọn template phù hợp cho từng loại slide

**Đối tượng sử dụng**: AI assistants được sử dụng để tự động tạo slides.

### 📄 `prompt_outline.txt`  
**Mục đích**: Prompt cụ thể để AI tạo outline chi tiết cho từng buổi học.

**Nội dung chính**:
- Hướng dẫn soạn outline cho Buổi 2 (Gemini API cơ bản)
- Hướng dẫn soạn outline cho Buổi 3 (Multimedia)
- Hướng dẫn soạn outline cho Buổi 4 (Khái niệm nâng cao)
- Các link tài liệu tham khảo từ Google AI
- Yêu cầu không hiển thị toàn bộ code mà chỉ phần quan trọng

**Đối tượng sử dụng**: AI assistants để tạo outline chi tiết cho bài giảng.

### 📄 `template-prompt.txt`
**Mục đích**: Prompt ban đầu để AI tạo ra bộ template slide cho toàn bộ khóa học. Đây chỉ là prompt đầu tiên, để ra được bộ template hoàn chỉnh, còn phải chỉnh sửa thêm rất nhiều lần.

**Nội dung chính**:
- Yêu cầu tạo tài liệu trình chiếu dạng web
- Các loại trang: bìa, mục lục, 4 template nội dung khác nhau, trang cảm ơn
- Định dạng 16:9 và responsive
- Màu sắc chủ đạo: cam, xanh nước biển, trắng, xanh đen
- Logo Greenwich xuất hiện ở các trang quan trọng

**Đối tượng sử dụng**: AI assistants trong giai đoạn khởi tạo dự án để tạo template system.

## 📁 `/slides/templates`
**Mục đích**: Bộ template HTML/CSS/JS chuẩn cho việc tạo slides bài giảng.

### Các template có sẵn:

#### 🎨 **Template cơ bản**
- **`cover.html`**: Template trang bìa với logo Greenwich, tiêu đề khóa học và thông tin giảng viên
- **`table-of-contents.html`**: Template trang mục lục liệt kê các chủ đề chính
- **`thank-you.html`**: Template trang cảm ơn và Q&A

#### 📝 **Template nội dung**
- **`template1-text-list.html`**: Danh sách text đơn giản (4-6 bullet points)
- **`template2-text-image.html`**: Panel trái text, panel phải ảnh minh họa
- **`template3-image-text.html`**: Panel trái ảnh, panel phải text
- **`template4-image-focus.html`**: Ảnh lớn ở giữa với text mô tả bên dưới
- **`template5-code.html`**: Template đặc biệt cho code với syntax highlighting
- **`template6-text-list-2-levels.html`**: Danh sách text 2 cấp độ với dynamic font sizing

#### 🔧 **Files hỗ trợ**
- **`styles.css`**: File CSS chính định nghĩa toàn bộ giao diện
- **`presentation.js`**: JavaScript điều khiển navigation và animations
- **`index.html`**: File chính để điều hướng giữa các slides
- **`images/`**: Thư mục chứa logo và ảnh minh họa

### Đặc điểm kỹ thuật
- **Responsive Design**: Tự động điều chỉnh cho ratio 16:9
- **Animation System**: Các hiệu ứng slide-in, fade-in
- **Navigation**: Buttons để chuyển slide trước/sau
- **Dynamic Sizing**: Font tự động điều chỉnh theo số lượng nội dung
- **Color Scheme**: Cam (#FF6B35), xanh nước biển (#007BFF), trắng, xanh đen

## Quy trình sử dụng

1. **Lập kế hoạch**: Tham khảo `outline_program.txt` cho roadmap tổng thể
2. **Tạo outline chi tiết**: Sử dụng `prompt_outline.txt` với AI
3. **Tạo slides**: Sau khi có outline, sử dụng `prompt_lecture.md` với AI và templates
4. **Khắc phục lỗi**: Tham khảo `common_errors.md` khi gặp vấn đề kỹ thuật. Nếu phát sinh lỗi nào hay gặp mà chưa có trong tài liệu, hãy bổ sung vào để hoàn thiện hơn.
5. **Thực hành**: Sử dụng code trong thư mục `/code` để demo

## Công nghệ sử dụng

- **Frontend**: HTML5, CSS3, JavaScript (vanilla)
- **Backend**: Python với Gemini API
- **Styling**: Custom CSS framework với responsive design
- **Animation**: CSS animations và transitions

## 🤝 Hướng dẫn Collaboration cho Giảng viên

### Để sử dụng tài liệu này:

1. **Fork repository**: Tạo một bản copy của repo về GitHub account của bạn
2. **Clone repository**: Clone repo đã fork về máy local để sử dụng
   ```bash
   git clone https://github.com/[your-username]/genai4dev.git
   ```

### Để đóng góp cải thiện tài liệu:

1. **Tạo branch mới** từ main branch:
   ```bash
   git checkout -b feature/your-improvement-name
   ```

2. **Thực hiện thay đổi**: Sửa lỗi, bổ sung nội dung, cải thiện code

3. **Commit changes**:
   ```bash
   git add .
   git commit -m "Mô tả chi tiết thay đổi của bạn"
   ```

4. **Push branch** lên GitHub:
   ```bash
   git push origin feature/your-improvement-name
   ```

5. **Tạo Pull Request**: Từ GitHub interface, tạo Pull Request từ branch của bạn về main branch của repo gốc

6. **Review và merge**: Tôi sẽ review và merge các thay đổi hữu ích

### Các loại đóng góp được khuyến khích:

- ✅ Sửa lỗi trong code hoặc slides
- ✅ Bổ sung ví dụ thực tế
- ✅ Cải thiện documentation
- ✅ Thêm câu hỏi thường gặp
- ✅ Cập nhật công nghệ mới
- ✅ Dịch thuật và localization

### Liên hệ:
📧 Email: [tungdt27@fe.edu.vn] để thảo luận về các thay đổi lớn trước khi thực hiện

---

**Tác giả**: Doan Trung Tung, PhD, Greenwich Vietnam  
**Mục đích**: Khóa học Generative AI cho sinh viên ngành Công nghệ Thông tin