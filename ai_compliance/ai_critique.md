# AI Critique

AI hữu ích trong bài homework này với vai trò là công cụ hỗ trợ tạo bản nháp ban đầu, nhưng chưa đủ đáng tin cậy để được sử dụng như nguồn thông tin cuối cùng.

Đối với **Requirement 1**, AI hỗ trợ xem lại bảng thị trường việc làm và chỉ ra một số rủi ro liên quan đến checklist. Tuy nhiên, AI không thể tự xác minh các ảnh chụp màn hình thực tế, tên tài khoản, mức lương, ngày đăng tuyển hoặc việc một công việc có thật sự yêu cầu kỹ năng AI/LLM hay không.

Đối với **Requirement 2**, AI giải thích rõ ràng 20 lỗi phần mềm, nhưng đôi khi mở rộng nội dung vượt quá bằng chứng từ các đường dẫn nguồn. Ví dụ, AI có thể suy luận nguyên nhân gốc rễ hoặc hậu quả có khả năng xảy ra về mặt kỹ thuật, nhưng những suy luận đó không phải lúc nào cũng được xác nhận trực tiếp bởi nguồn được trích dẫn.

Đối với **Requirement 3**, AI tạo được một bộ test case khả dụng cho thiết bị vật lý, nhưng vẫn bỏ sót các edge case quan trọng trong thực tế, chẳng hạn như cản nhẹ chuyển động quay trái phải của quạt, nhấn đồng thời hai nút tốc độ cơ học, và kiểm tra độ ổn định sau khi điều chỉnh độ cao hoặc góc nghiêng. AI cũng không thể biết kết quả kiểm thử thật của quạt, vì vậy các verdict cuối cùng và defect log phải do sinh viên tự hoàn thiện.

Đối với phần **mindmap**, AI bao quát được các vai trò và công cụ QA/QC phổ biến, nhưng chưa nhấn mạnh đầy đủ kiểm thử dựa trên rủi ro, kiến thức nghiệp vụ và sự khác biệt giữa automation testing và AI-assisted testing.