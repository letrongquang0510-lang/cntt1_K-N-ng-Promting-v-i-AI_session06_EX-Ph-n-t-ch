# yêu cầu

## Bước 1: Đề xuất 2 prompt mẫu

### Giải pháp 1: Đơn giản, ngắn gọn
Dùng phương pháp Feynman dạy tôi khái niệm đệ quy đơn giản, đặt 1 câu hỏi kiểm tra và dùng Rubric chấm điểm câu trả lời của tôi.

### Giải pháp 2: Chi tiết, có ràng buộc
Bạn là gia sư dạy lập trình theo phương pháp Feynman cho chủ đề Đệ quy . Thực hiện đúng thứ tự, không làm gộp:
1. Giải thích Đệ quy bằng ví dụ đời thường (<120 từ, không dùng code).
2. Đặt 1 câu hỏi yêu cầu tôi tự diễn đạt lại, sau đó dừng lại chờ tôi trả lời (không tự trả lời hộ).
3. Sau khi tôi trả lời, chấm thang 10 theo Rubric:
   - Đúng bản chất hàm tự gọi lại chính nó (4đ)
   - Nêu được điều kiện dừng / base case (4đ)
   - Diễn đạt dễ hiểu, không sao chép máy móc (2đ)
- Quy tắc biên: Nếu tôi trả lời lạc đề hoặc bỏ trống, không chấm điểm mà chỉ gợi ý ngắn để thử lại.

## Bước 2: Bảng so sánh Trade-off

| Tiêu chí | Giải pháp 1 (Đơn giản) | Giải pháp 2 (Chi tiết) |
| :--- | :--- | :--- |
| Độ dễ hiểu | Cao | Trung bình |
| Tốn token | Ít | Nhiều hơn |
| Chặn lỗi biên | Trung bình | Cực tốt |

## Bước 3: Lựa chọn và chạy thử

### Phương án tối ưu: Giải pháp 2
- Lý do : Ép AI dừng chờ người học tự diễn đạt (đúng tinh thần Feynman), giữ thang điểm Rubric ổn định qua các lần chạy và xử lý được tình huống trả lời lạc đề. Mức tốn token chênh lệch thấp hơn nhiều so với giá trị kiểm soát lỗi.
<img width="983" height="592" alt="image" src="https://github.com/user-attachments/assets/085a4442-19f1-4eb5-880f-f9a920c790f5" />
