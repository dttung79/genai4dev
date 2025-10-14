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
- **`lecture05/`**: Code thực hành cho Buổi 5 - RAG (Retrieval-Augmented Generation)
- **`lecture06/`**: Code thực hành cho Buổi 6 - Fine-tuning với Gemini API
- **`lecture07/`**: Code thực hành cho Buổi 7 - MCP (Model Context Protocol)
- **`lecture08/`**: Code thực hành cho Buổi 8 - AI Agents

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

## Chi tiết Code thực hành theo từng Lecture

### 🚀 **Lecture 02 - Lập trình Gen AI với Gemini API**
**Thư mục**: `/code/lecture02/`

Làm quen với Gemini API từ cơ bản đến nâng cao, bao gồm stateless và stateful conversations.

**Files chính**:
- **`tut01_hello_gemini.py`**: First steps với Gemini API
  - Setup API key và authentication
  - Gửi request đơn giản và nhận response
  - Error handling cơ bản

- **`tut02_stateless_chat.py`**: Stateless conversation
  - Mỗi request độc lập, không nhớ context
  - Phù hợp cho single-turn Q&A
  - Performance cao, ít memory

- **`tut03_stateful_chat.py`**: Stateful conversation với memory
  - Duy trì context qua nhiều turns
  - Chat history management
  - Multi-turn conversation flows

- **`tut04_system_prompt.py`**: System prompt để định hình behavior
  - Role-based AI assistants (teacher, coder, analyst)
  - Prompt engineering techniques
  - Personality và tone control

**Công nghệ sử dụng**: Google Gemini API, Python requests, JSON handling

### 🎨 **Lecture 03 - Multimedia trong Gemini API**
**Thư mục**: `/code/lecture03/`

Xử lý và phân tích nội dung đa phương tiện với Gemini API.

**Files chính**:
- **`tut01_image_analysis.py`**: Phân tích hình ảnh
  - Upload và process images
  - Image description và object detection
  - Visual question answering
  - OCR (text extraction from images)

- **`tut02_audio_processing.py`**: Xử lý âm thanh
  - Audio transcription
  - Speech-to-text conversion
  - Audio content analysis
  - Multi-language support

- **`tut03_document_upload.py`**: Upload và xử lý tài liệu
  - PDF text extraction
  - Document Q&A
  - Multi-page document analysis
  - File format support (PDF, DOCX, TXT)

- **`tut04_multimodal_combo.py`**: Kết hợp nhiều loại media
  - Image + text analysis
  - Audio + visual processing
  - Cross-modal understanding
  - Complex multimodal queries

**Thư mục hỗ trợ**:
- **`samples/`**: Ảnh, audio, document mẫu cho testing
- **`uploads/`**: Temporary folder cho user uploads

**Công nghệ sử dụng**: Gemini Vision API, Audio API, File API, PIL/Pillow, PyPDF2

### ⚡ **Lecture 04 - Các khái niệm nâng cao**
**Thư mục**: `/code/lecture04/`

Kỹ thuật nâng cao với Gemini API: Code Execution, Function Calling, và Caching.

**Files chính**:
- **`tut01_code_execution.py`**: Code Execution trong Gemini
  - Dynamic code generation và execution
  - Python code runner trong AI responses
  - Mathematical computations
  - Data analysis và visualization
  - Security considerations

- **`tut02_function_calling.py`**: Function Calling mechanism
  - Define custom functions cho AI
  - Weather API integration
  - Database queries through functions
  - External service integration
  - Function schemas và validation

- **`tut03_caching.py`**: Context Caching để tối ưu performance
  - Cache large documents/contexts
  - Reduce API costs và latency
  - Cache expiration management
  - Cost optimization strategies

- **`tut04_advanced_combo.py`**: Kết hợp các tính năng nâng cao
  - Function calling + code execution
  - Cached contexts với dynamic functions
  - Complex workflow automation
  - Real-world integration examples

**Functions mẫu**:
- **`functions/weather.py`**: Weather API integration
- **`functions/database.py`**: Database query functions
- **`functions/calculator.py`**: Advanced mathematical operations
- **`functions/utils.py`**: Utility functions cho các tutorials

**Công nghệ sử dụng**: 
- Gemini Advanced API features
- External APIs (weather, databases)
- JSON schema validation
- Caching mechanisms
- Dynamic code execution

### 📚 **Lecture 05 - RAG (Retrieval-Augmented Generation)**
**Thư mục**: `/code/lecture05/`

Hệ thống chatbot PDF hoàn chỉnh sử dụng embeddings và tìm kiếm vector semantic.

**Files chính**:
- **`extract_text.py`**: Trích xuất text từ file PDF và DOCX
- **`create_embeddings.py`**: Tạo embeddings và FAISS indices cho tìm kiếm semantic
- **`chat_txt_gemini.py`**: Ứng dụng Streamlit chatbot chính với text-to-speech
- **`requirements.txt`**: Dependencies cho dự án RAG
- **`README.md`**: Hướng dẫn chi tiết setup và sử dụng

**Thư mục hỗ trợ**:
- **`docs/`**: Chứa file PDF/DOCX input (curriculum, quy chế, etc.)
- **`chunks/`**: Text chunks đã được xử lý
- **`bins/`**: FAISS index files
- **`.streamlit/`**: Config Streamlit và template secrets

**Công nghệ sử dụng**: FAISS, sentence-transformers, Streamlit, Google Gemini API, text-to-speech

### 🎯 **Lecture 06 - Fine-tuning với Gemini API**
**Thư mục**: `/code/lecture06/`

Fine-tuning model Gemini để chuyên biệt hóa cho nhiệm vụ phân loại sentiment phim.

**Files chính**:
- **`tutorial01.ipynb`**: Jupyter notebook hoàn chỉnh về fine-tuning process
- **`IMDB_cleaned.csv`**: Dataset IMDB reviews đã được làm sạch
- **`my_movie_sentiment_model/`**: Model đã được fine-tuned

**Nội dung tutorial**:
- **Part 1**: Hiểu về Fine-tuning (khái niệm, so sánh pre-trained vs fine-tuned)
- **Part 2**: Quy trình Fine-tuning (chuẩn bị data, training, evaluation)
- **Part 3**: Thực hành với Gemini API (setup, training job, testing)
- **Part 4**: So sánh performance trước và sau fine-tuning

**Dataset**: 50,000 IMDB movie reviews với sentiment labels (positive/negative)

### 🔌 **Lecture 07 - MCP (Model Context Protocol)**
**Thư mục**: `/code/lecture07/`

Triển khai MCP servers để mở rộng khả năng của AI models thông qua external tools.

**Files chính**:
- **`tut01_file_mcp.py`**: File Manager MCP Server
  - Đọc nội dung file text
  - Liệt kê thư mục
  - Ghi file trong workspace được phép
  - Quản lý file system thông qua MCP protocol

- **`tut02_mysql_mcp.py`**: MySQL Database MCP Server
  - Kết nối và query MySQL database
  - Thực thi SQL commands an toàn
  - Quản lý database schema
  - Trả về kết quả structured data

**Khái niệm MCP**:
- Protocol chuẩn để AI models giao tiếp với external systems
- Server-client architecture
- Tool exposure và execution
- Context management

### 🤖 **Lecture 08 - AI Agents**
**Thư mục**: `/code/lecture08/`

Xây dựng hệ thống AI agents thông minh với khả năng collaboration và guardrails.

**Files chính**:
- **`tut01_hello_agent.py`**: Agent cơ bản
  - Tạo agent đơn giản với OpenAI API
  - Chạy synchronous agent
  - Agent với instructions chuyên biệt (poet agent)

- **`tut02_3agents.py`**: Hệ thống multi-agent phức tạp
  - **Guardrail Agent**: Kiểm tra input có phải homework không
  - **Triage Agent**: Phân loại và điều hướng câu hỏi
  - **Math Tutor Agent**: Chuyên gia toán học
  - **History Tutor Agent**: Chuyên gia lịch sử
  - Async processing và error handling
  - Interactive Q&A session với exit commands

**Tính năng nâng cao**:
- Input guardrails để bảo mật
- Agent handoffs và routing
- Structured output với Pydantic
- Exception handling cho tripwires
- Interactive conversation flow

**Kiến trúc agents**: Guardrail → Triage → Specialist Agents → User

### 📁 `/slides`

## Quy trình sử dụng

1. **Lập kế hoạch**: Tham khảo `outline_program.txt` cho roadmap tổng thể (8 buổi học)
2. **Tạo outline chi tiết**: Sử dụng `prompt_outline.txt` với AI
3. **Tạo slides**: Sau khi có outline, sử dụng `prompt_lecture.md` với AI và templates
4. **Thực hành lập trình**: 
   - **Buổi 2-4**: Gemini API cơ bản đến nâng cao
   - **Buổi 5**: RAG với embeddings và vector search
   - **Buổi 6**: Fine-tuning models với Jupyter notebooks
   - **Buổi 7**: MCP servers cho external tool integration
   - **Buổi 8**: Multi-agent systems với guardrails
5. **Khắc phục lỗi**: Tham khảo `common_errors.md` khi gặp vấn đề kỹ thuật
6. **Demo và Q&A**: Sử dụng code trong thư mục `/code` để demo cho sinh viên

## Công nghệ sử dụng

- **Frontend**: HTML5, CSS3, JavaScript (vanilla), Streamlit
- **Backend**: Python với Gemini API, OpenAI API
- **AI/ML Libraries**: 
  - sentence-transformers (embeddings)
  - FAISS (vector search)
  - scikit-learn (machine learning)
  - agents (multi-agent systems)
- **Data Processing**: 
  - PyPDF2, python-docx (document extraction)
  - pandas, numpy (data manipulation)
  - RecursiveCharacterTextSplitter (text chunking)
- **Database**: MySQL with MCP protocol
- **Development Tools**: 
  - Jupyter Notebooks (interactive development)
  - MCP (Model Context Protocol)
  - text-to-speech libraries
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