# Hướng Dẫn Đóng Góp cho Make Low-code Website

Cảm ơn bạn đã quan tâm đến việc đóng góp cho MLCW (Make Low-code Website)! Chúng tôi rất hoan nghênh sự tham gia của bạn. Dưới đây là một số hướng dẫn để giúp bạn bắt đầu.

## Mục Lục

1. [Quy tắc chung](#quy-tắc-chung)
2. [Cách tạo Issue](#cách-tạo-issue)
3. [Quy trình tạo Pull Request](#quy-trình-tạo-pull-request)Application
4. [Tiêu chuẩn mã nguồn](#tiêu-chuẩn-mã-nguồn)
5. [Kiểm thử và chất lượng mã](#kiểm-thử-và-chất-lượng-mã)
6. [Thông tin liên lạc](#thông-tin-liên-lạc)

## Quy tắc chung

- Hãy lịch sự và tôn trọng người khác.
- Trước khi bắt đầu làm việc trên một tính năng hoặc sửa lỗi, hãy kiểm tra xem có ai đang làm việc trên vấn đề đó hay không.
- Luôn luôn thảo luận với nhóm hoặc mở một Issue để đề xuất trước khi bắt đầu phát triển tính năng mới.

## Cách tạo Issue

- Nếu bạn phát hiện ra lỗi hoặc có ý tưởng cho tính năng mới, hãy tạo một Issue mới.
- Trong Issue, vui lòng mô tả chi tiết vấn đề hoặc đề xuất của bạn:
  - **Mô tả ngắn gọn:** Tóm tắt vấn đề hoặc đề xuất của bạn.
  - **Các bước để tái tạo lỗi:** Cung cấp hướng dẫn chi tiết để tái tạo lỗi nếu có.
  - **Môi trường:** Liệt kê thông tin về hệ điều hành, trình duyệt, phiên bản phần mềm...
  - **Ảnh chụp màn hình:** Đính kèm ảnh chụp màn hình hoặc video nếu có thể.

## Quy trình tạo Pull Request

1. **Fork** dự án này và clone repository về máy tính của bạn.
   
   ```bash
   git clone https://github.com/username/[repo-name].git
 
2. Tạo một nhánh mới cho tính năng hoặc sửa lỗi bạn đang làm:

  ```bash
  git checkout -b feature/ten-tinh-nang

3. Thực hiện các thay đổi và commit thường xuyên với thông điệp rõ ràng:

  ```bash
  git commit -m "[#issue-number] Mô tả ngắn gọn về thay đổi"

4. Push nhánh của bạn lên GitHub:

  ```bash
  git push origin feature/ten-tinh-nang

5. Tạo Pull Request từ nhánh của bạn vào nhánh main của repository này:
        Giải thích rõ ràng mục đích của Pull Request.
        Liên kết đến Issue liên quan (nếu có).

6. Kiểm tra lại Pull Request để đảm bảo không có xung đột và tuân thủ các tiêu chuẩn mã nguồn.

## Tiêu chuẩn mã nguồn

    Định dạng mã: Sử dụng 4 dấu cách cho mỗi lần thụt đầu dòng.
    Tên biến và hàm: Sử dụng tiếng Anh và tuân theo quy tắc camelCase (ví dụ: myFunctionName).
    Tài liệu: Thêm tài liệu vào các hàm và phương thức quan trọng.
    Kiểm tra lỗi: Đảm bảo tất cả các đoạn mã đều được kiểm tra lỗi và xử lý ngoại lệ.

## Kiểm thử và chất lượng mã

    Chạy các bài kiểm thử tự động (nếu có) trước khi tạo Pull Request.
    Đảm bảo mã của bạn không phá vỡ các bài kiểm thử hiện có.
    Nếu bạn thêm tính năng mới, vui lòng thêm kiểm thử tương ứng.

## Thông tin liên lạc

Nếu bạn có bất kỳ câu hỏi nào, vui lòng liên hệ với chúng tôi qua ducminhhoangkhmt2@gmail.com hoặc tham gia vào kênh [Discord/Slack] của chúng tôi.

Cảm ơn bạn đã đóng góp cho MLCWMLCW!!
