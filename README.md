# AI-Flow-Development

## Giới thiệu

AI-Flow-Development là một phương pháp thiết lập cho các dự án sử dụng AI để code 100%. Phương pháp này giúp bạn tổ chức và quản lý hiệu quả quá trình phát triển phần mềm với sự hỗ trợ của các công cụ AI.

## Cấu trúc dự án

Mỗi nền tảng sẽ có một thư mục riêng, nhưng chúng đều có chung một kiến trúc bao gồm 4 file chính:

1. **GOLDEN_RULE.md** - Lời giới thiệu và hướng dẫn cho AI
2. **PLANNING.md** - Kế hoạch phát triển dự án
3. **TASK.md** - Danh sách nhiệm vụ
4. **README.md** - Hướng dẫn sử dụng

## Chi tiết các file

### GOLDEN_RULE.md

File này chứa:

- Lời giới thiệu cho AI
- Hướng dẫn AI những việc cần làm trước khi bắt đầu một nhiệm vụ mới
- Những điều cần lưu ý trong quá trình làm việc
- Các nguyên tắc và tiêu chuẩn code

### PLANNING.md

File này dùng để lên kế hoạch cho dự án, bao gồm:

- Các tính năng cần có
- Các thành phần của dự án
- Các công nghệ sẽ sử dụng
- Cấu trúc thư mục của dự án
- Kiến trúc hệ thống

### TASK.md

File này để ghi lại:

- Các nhiệm vụ cần làm
- Các nhiệm vụ đã hoàn thành
- Các nhiệm vụ phát hiện trong quá trình làm việc
- Thông tin về ngày tháng và người thực hiện nhiệm vụ
- Mức độ ưu tiên và trạng thái của từng nhiệm vụ

### README.md

File này chứa hướng dẫn sử dụng cho dự án:

- Thông tin về cách cài đặt
- Cách chạy dự án
- Các công nghệ đã sử dụng
- Trạng thái phát triển hiện tại của dự án
- Cách đóng góp vào dự án (nếu có)

## Cách sử dụng

### Bắt đầu một dự án mới

1. **Sao chép template thích hợp**: Trước khi bắt đầu một dự án, bạn có thể copy các file từ thư mục tương ứng với nền tảng bạn dự định sử dụng.

2. **Tạo mới với AI**: Trường hợp không có template phù hợp, bạn có thể nhờ AI nhìn vào một thư mục bất kỳ và tạo ra các file tương ứng với nền tảng bạn dự định sử dụng.

Ví dụ một prompt có thể sử dụng:

```
Hãy đọc các file trong thư mục html-typescript và tạo ra các file GOLDEN_RULE.md, PLANNING.md, TASK.md, README.md cho dự án này.
Dự án này là một game đối kháng, sử dụng Typescript, Tailwind CSS.
```

### Thiết lập GOLDEN_RULE cho AI agent

Sau khi có các file cần thiết, bạn cần copy nội dung của GOLDEN_RULE.md vào phần cấu hình của AI agent bạn sử dụng:

- **GitHub Copilot**: Copy vào file `.github/copilot-instructions.md`
- **Cline**: Copy vào file `.clinerules`
- **Cursor**: Copy vào thư mục `.cursor/rules`

Việc này giúp AI agent hiểu rõ những việc cần làm và cách thức thực hiện.

### Quy trình làm việc

1. **Thiết lập GOLDEN_RULE** cho AI agent như hướng dẫn ở trên.

2. **Review PLANNING.md và TASK.md** để xem xét các nhiệm vụ cần làm và định hướng dự án.

3. **Làm việc với AI**: Đừng vội code bất cứ thứ gì, bạn cần chắc chắn về định hướng, các nhiệm vụ cần làm và cách thức thực hiện. Nếu có gì không đúng, hãy yêu cầu AI cập nhật.

4. **Thực hiện nhiệm vụ**: Sau khi đã thống nhất được Planning và Task, hãy bắt đầu hoặc tiếp tục các công việc bằng cách yêu cầu AI thực hiện một nhiệm vụ trong file TASK.md. Ví dụ prompt: `Hãy thực hiện các nhiệm vụ trong mục Project Setup`.

5. **Đảm bảo chạy test**: AI thường có xu hướng trốn tránh việc chạy test, nhưng đây là vấn đề rất quan trọng để đảm bảo chất lượng dự án. Hãy theo dõi và chắc chắn rằng AI đã chạy test và tất cả test đã pass. Nếu chưa chạy, hãy yêu cầu AI chạy test.

6. **Cập nhật tiến độ**: Khi mọi việc đã ổn thỏa, đừng quên yêu cầu AI cập nhật file TASK.md để bạn có thể tiện theo dõi tiến độ dự án.

7. **Phát triển tính năng mới**: Khi bạn cần phát triển tính năng mới, hãy thảo luận với AI để cập nhật Planning và Task trước khi bắt đầu thực hiện.

8. **Cộng tác hiệu quả**: Làm việc với AI như với một người cộng sự hoặc cấp dưới. Cung cấp phản hồi rõ ràng và chi tiết để AI hiểu đúng nhu cầu của bạn.

## Lợi ích

- Tổ chức dự án một cách có hệ thống
- Tối ưu hóa hiệu quả làm việc với AI
- Dễ dàng theo dõi tiến độ và quản lý nhiệm vụ
- Tạo ra mã nguồn chất lượng cao với sự hỗ trợ của AI
- Giảm thiểu thời gian và công sức phát triển

## Đóng góp

Nếu bạn có ý tưởng cải thiện phương pháp này, hãy tạo pull request hoặc mở issue để thảo luận.
