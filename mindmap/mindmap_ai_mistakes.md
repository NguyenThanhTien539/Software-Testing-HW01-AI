# Các lỗi trong Mindmap do AI tạo

## Tổng quan

File này ghi lại ba vấn đề được phát hiện trong mindmap về vai trò QA/QC do AI tạo.

Mindmap gốc do AI tạo:

- `mindmap/ai_generated_qaqc_mindmap.md`

Mindmap đã được chỉnh sửa:

- `mindmap/corrected_qaqc_mindmap.md`

---

## Lỗi 01 – AI chưa nhấn mạnh đủ về kiểm thử dựa trên rủi ro

**Lỗi của AI:**
Mindmap do AI tạo có đề cập đến các hoạt động kiểm thử phổ biến như functional testing, regression testing, API testing và security testing, nhưng chưa nhấn mạnh rõ vai trò của kiểm thử dựa trên rủi ro.

**Vì sao đây là vấn đề:**
Trong công việc QA/QC thực tế, tester không thể kiểm thử mọi chức năng với cùng một mức độ ưu tiên. Tester cần xác định các chức năng có rủi ro cao, các luồng nghiệp vụ quan trọng, luồng thanh toán, xác thực, nguy cơ mất dữ liệu và những khu vực ảnh hưởng nhiều nhất đến người dùng.

**Phần sinh viên đã chỉnh sửa:**
Tôi đã bổ sung **Risk-based Testing** vào nhánh **Test Strategy and Management** trong mindmap đã chỉnh sửa.

---

## Lỗi 02 – AI gộp automation testing và AI-assisted testing quá chung chung

**Lỗi của AI:**
Mindmap do AI tạo có đề cập đến automation testing và sự hỗ trợ của AI, nhưng chưa tách rõ kiểm thử tự động truyền thống và kiểm thử có AI hỗ trợ.

**Vì sao đây là vấn đề:**
Automation testing là việc sử dụng script và công cụ như Selenium, Playwright, Cypress, JUnit hoặc Postman để thực thi kiểm thử tự động. Trong khi đó, AI-assisted testing là việc sử dụng AI để hỗ trợ các công việc như tạo ý tưởng test, tạo dữ liệu test, tóm tắt bug report hoặc phát hiện các edge case bị bỏ sót. Hai khái niệm này có liên quan nhưng không giống nhau.

**Phần sinh viên đã chỉnh sửa:**
Tôi đã tách **Automation Testing** và **AI-assisted Testing** thành hai nhánh riêng biệt trong mindmap đã chỉnh sửa.

---

## Lỗi 03 – AI chưa đưa đủ kiến thức nghiệp vụ

**Lỗi của AI:**
Mindmap do AI tạo tập trung nhiều vào kỹ thuật kiểm thử và công cụ, nhưng chưa đề cập đầy đủ đến kiến thức nghiệp vụ.

**Vì sao đây là vấn đề:**
Kỹ sư QA/QC cần hiểu lĩnh vực nghiệp vụ để thiết kế test case có ý nghĩa. Việc kiểm thử các hệ thống tài chính, thương mại điện tử, y tế, giáo dục hoặc logistics đều yêu cầu hiểu quy tắc nghiệp vụ, luồng người dùng, ràng buộc dữ liệu và các yêu cầu tuân thủ.

**Phần sinh viên đã chỉnh sửa:**
Tôi đã bổ sung nhánh **Domain Knowledge**, bao gồm business rules, user workflows, data validation rules, industry-specific constraints và compliance requirements.

---

## Kết luận của sinh viên

Mindmap do AI tạo hữu ích như một bản nháp ban đầu, nhưng vẫn chưa hoàn chỉnh. Mindmap này chủ yếu tập trung vào các loại kiểm thử phổ biến và công cụ. Sau khi xem xét, tôi đã bổ sung các phần còn thiếu như risk-based testing, tách rõ hơn giữa automation testing và AI-assisted testing, đồng thời thêm domain knowledge. Những chỉnh sửa này giúp mindmap cuối cùng thực tế hơn đối với vai trò QA/QC trong giai đoạn 2026+.
