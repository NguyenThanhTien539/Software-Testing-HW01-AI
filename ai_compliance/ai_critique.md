# AI Critique

AI hữu ích trong bài homework này với vai trò hỗ trợ tạo bản nháp, gợi ý checklist và phát hiện một số điểm còn thiếu. Tuy nhiên, AI chưa đủ đáng tin cậy để dùng như nguồn thông tin cuối cùng.

Đối với **Requirement 1**, AI giúp rà soát bảng thị trường việc làm, nhưng không thể tự xác minh ảnh chụp màn hình, tên tài khoản, mức lương, ngày đăng hoặc việc một job có thật sự yêu cầu AI/LLM hay không. Các thông tin này vẫn phải được kiểm tra thủ công từ source và screenshot.

Đối với **Requirement 2**, AI giải thích 20 lỗi phần mềm khá rõ, nhưng đôi khi suy luận nguyên nhân hoặc hậu quả vượt quá nội dung nguồn xác nhận. Vì vậy, tôi phải đối chiếu lại với source links và chỉnh các claim chưa chắc chắn thành tác động hoặc nguyên nhân có thể.

Đối với **Requirement 3**, AI tạo được bộ test case ban đầu cho quạt, nhưng bỏ sót các edge case thực tế như cản nhẹ chuyển động quay, nhấn đồng thời hai nút tốc độ và kiểm tra độ ổn định sau khi điều chỉnh độ cao hoặc góc nghiêng. AI cũng không thể biết actual result, verdict hoặc defect thật.

Đối với **mindmap**, AI bao quát được vai trò và công cụ QA/QC phổ biến, nhưng chưa nhấn mạnh đủ risk-based testing, domain knowledge và sự khác biệt giữa automation testing và AI-assisted testing.

Bài học chính là AI phù hợp nhất cho brainstorming, drafting và checklist review. AI không nên thay thế việc xác minh nguồn, kiểm thử trên thiết bị thật hoặc phán đoán chuyên môn của tester.
