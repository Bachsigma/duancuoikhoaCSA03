# Phân tích kết quả học tập (dữ liệu mô phỏng)

## Mục đích và lưu ý

Dự án minh họa cách làm sạch, thống kê, trực quan hóa và xây dựng mô hình hồi quy với điểm số giả lập. Dữ liệu có 40 hồ sơ tổng hợp, không thuộc về học sinh thật và không chứa tên, trường hoặc thông tin nhận dạng.

Các nhóm kết quả trong dự án nhằm mô tả dữ liệu và gợi ý chủ đề cần hỗ trợ, không phải đánh giá năng lực hay dán nhãn cá nhân. Ngưỡng phân loại là ví dụ minh họa, không thay thế quy định chính thức của trường. Nếu sử dụng dữ liệu thực, cần có sự cho phép phù hợp, giới hạn quyền truy cập, bảo vệ hồ sơ học tập và không công bố dữ liệu nhận dạng.

## Mô tả cột

- `record_id`: mã giả lập, không định danh người thật.
- `grade_level`: khối lớp (10, 11 hoặc 12).
- `math_score`, `literature_score`, `english_score`, `science_score`: điểm môn học trên thang 10.
- `attendance_pct`: tỷ lệ tham dự giả lập, phần trăm.
- `study_hours_per_day`: số giờ tự học trung bình mỗi ngày, giả lập.
- `homework_completion_pct`: tỷ lệ hoàn thành bài tập giả lập, phần trăm.
- `average_score`: điểm trung bình bốn môn, tính trong bước làm sạch.
- `learning_support_group`: nhóm mô tả kết quả: `Cần hỗ trợ` (<5), `Đang tiến bộ` (5 đến dưới 8), `Vững kiến thức` (từ 8 trở lên).

## Câu hỏi thống kê

1. Điểm trung bình chung của mẫu là bao nhiêu?
2. Tỷ lệ hồ sơ ở từng nhóm kết quả là bao nhiêu?
3. Môn nào có điểm trung bình cao nhất/thấp nhất?
4. Điểm trung bình có khác nhau giữa các khối lớp không?
5. Mức độ tham dự, tự học và hoàn thành bài tập liên hệ thế nào với điểm trung bình?
6. Các hồ sơ thuộc nhóm cần hỗ trợ có điểm môn nào thấp hơn tương đối?

## Câu hỏi thảo luận và giới hạn

1. Ngoài điểm số, bối cảnh nào cần tìm hiểu trước khi đề xuất hỗ trợ học tập?
2. Giáo viên có thể dùng kết quả tổng hợp để điều chỉnh bài giảng ra sao mà không làm học sinh bị gắn nhãn?
3. Mẫu giả lập có thể khác dữ liệu trường/lớp thực tế như thế nào?
4. Vì sao hồi quy và tương quan không chứng minh việc học nhiều hơn là nguyên nhân duy nhất làm điểm tăng?

Dữ liệu được tạo cho mục đích học tập, không đại diện cho học sinh hay trường học cụ thể. Không dùng mô hình để xếp loại, kỷ luật, tuyển chọn hoặc đưa ra quyết định giáo dục về cá nhân. Kết quả phân tích chỉ nên dùng để thực hành thống kê và thảo luận hỗ trợ học tập một cách có trách nhiệm.
