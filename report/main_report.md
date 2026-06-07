# Báo cáo chính HW01 – Kiểm thử phần mềm

**Họ tên:** Nguyễn Thanh Tiến
**Mã số sinh viên:** 23127539  
**Môn học:** Kiểm thử phần mềm  
**Bài tập:** HW01 – Việc làm QA/QC, lỗi phần mềm, kiểm thử sản phẩm vật lý  
**Công cụ AI đã sử dụng:** ChatGPT
**Điểm tự đánh giá:** 100/100

---

## 1. Yêu cầu 1 – Thị trường việc làm QA/QC 2026+

Báo cáo Yêu cầu 1 phân tích 10 tin tuyển dụng QA/QC được đăng trong khoảng thời gian yêu cầu. Báo cáo bao gồm liên kết nguồn, ảnh chụp màn hình, mức lương hoặc tình trạng công bố lương, mô tả công việc, kỹ năng yêu cầu và phần phân tích tác động của AI cho từng tin tuyển dụng.

Có ít nhất 3 vị trí liên quan đến AI, LLM, tự động hóa kết hợp AI, kiểm thử có AI hỗ trợ hoặc kiểm thử liên quan đến AI/ML. Trong bảng cuối cùng, một số công việc đề cập rõ đến kiểm thử dựa trên AI, tư duy ưu tiên AI, AI QC, kỹ thuật chất lượng được tăng cường bởi AI hoặc kiểm thử có AI hỗ trợ.

**Sản phẩm chính:**

- [Bảng thị trường việc làm Yêu cầu 1](../requirement_1_jobs/job_market_table.md)

**Minh chứng:**

- Ảnh chụp màn hình tin tuyển dụng được lưu trong `requirement_1_jobs/screenshots/`.

---

## 2. Yêu cầu 2 – 20 lỗi phần mềm giai đoạn 2022–2026

Báo cáo Yêu cầu 2 ghi nhận 20 lỗi phần mềm công khai hoặc sự cố liên quan đến phần mềm từ năm 2022 đến năm 2026. Có ít nhất 5 lỗi liên quan đến hành vi của AI/LLM, chẳng hạn như ảo giác AI, thông tin sai lệch, lời khuyên chatbot gây hại, thiên lệch hoặc quyết định tự động không đáng tin cậy.

Mỗi mục lỗi bao gồm:

- Liên kết nguồn.
- Năm và hệ thống/sản phẩm bị ảnh hưởng.
- Mô tả.
- Mức độ nghiêm trọng.
- Hậu quả.
- Giải pháp đề xuất.
- Một vấn đề về thiên lệch/ảo giác AI được phát hiện khi AI giải thích lỗi đó.

Báo cáo bao gồm đúng 20 quan sát về thiên lệch/ảo giác AI, mỗi lỗi có một quan sát.

**Sản phẩm chính:**

- [Lỗi phần mềm 2022–2026](../requirement_2_defects/software_defects_2022_2026.md)

---

## 3. Yêu cầu 3 – Kiểm thử sản phẩm vật lý

Sản phẩm vật lý được chọn là **quạt lửng ASIA A16007-XV0**. Báo cáo bao gồm thông tin sản phẩm, ảnh thiết bị thật có thẻ sinh viên trong cùng khung hình, 15 test case, kết quả thực thi thực tế, nhật ký lỗi, liên kết video, minh chứng GitHub issue và phân tích các trường hợp biên mà AI đã bỏ sót.

### 3.1 Thông tin sản phẩm

| Mục                  | Giá trị                       |
| -------------------- | ----------------------------- |
| Sản phẩm             | Quạt lửng ASIA A16007-XV0     |
| Loại sản phẩm        | Quạt lửng                     |
| Nhà sản xuất         | Công ty Cổ phần Quạt Việt Nam |
| Ngày sản xuất        | 20.11.2017                    |
| Năm                  | 2017                          |
| Số sê-ri             | 29\*\*\*\*2                   |
| Nguồn điện           | 220V – 50Hz                   |
| Công suất định mức   | 45W                           |
| Đường kính cánh quạt | 400mm                         |
| Kiểu điều khiển      | Nút nhấn vật lý 0 / 1 / 2 / 3 |

**Sản phẩm liên quan đến thông tin sản phẩm:**

- [Thông tin sản phẩm](../requirement_3_physical_product/product_info.md)

### 3.2 Tóm tắt thực thi kiểm thử

| Chỉ số                                              | Giá trị |
| --------------------------------------------------- | ------: |
| Tổng số test case đã thiết kế                       |      15 |
| Tổng số test case đã thực thi                       |      15 |
| Số test case đạt                                    |      13 |
| Số test case không đạt                              |       2 |
| Số lỗi đã xác nhận                                  |       1 |
| Số lượng minh chứng video                           |       5 |
| Số trường hợp biên AI bỏ sót được sinh viên bổ sung |       3 |

**Các sản phẩm chính:**

- [Test case kiểm thử sản phẩm vật lý](../requirement_3_physical_product/test_cases.md)
- [Tóm tắt test case bằng Excel](../requirement_3_physical_product/test_cases_summary.xlsx)
- [Liên kết video](../requirement_3_physical_product/videos/video_links.md)
- [Ảnh thiết bị với thẻ sinh viên](../requirement_3_physical_product/device_photo/device_with_student_id.jpg)
- [Ảnh chụp màn hình GitHub Issues](../requirement_3_physical_product/github_issues/issues_page_with_username.png)

### 3.3 Tóm tắt lỗi

| Mã lỗi | Mô tả                                                  | Test case liên quan | Mức độ nghiêm trọng | Độ ưu tiên | Trạng thái |
| ------ | ------------------------------------------------------ | ------------------- | ------------------- | ---------- | ---------- |
| DEF-01 | Quạt phát ra tiếng cọt kẹt lớn khi đứng yên ở tốc độ 3 | TC-03, TC-09        | Trung bình          | Trung bình | Đang mở    |

### 3.4 Các trường hợp biên AI bỏ sót

AI đã tạo một bộ ban đầu gồm 15 test case kiểm thử sản phẩm vật lý, nhưng đã bỏ sót một số trường hợp biên thực tế liên quan đến việc sử dụng cơ học ngoài đời thật. Bộ test cuối cùng bổ sung:

- TC-13: Cản nhẹ chuyển động quay trái phải.
- TC-14: Nhấn đồng thời hai nút tốc độ.
- TC-15: Kiểm tra quạt sau khi điều chỉnh độ cao hoặc góc nghiêng.

**Minh chứng và giải thích:**

- [Các trường hợp biên AI bỏ sót](../requirement_3_physical_product/ai_missed_edge_cases.md)
- Ảnh chụp màn hình cuộc trò chuyện với AI được lưu trong `requirement_3_physical_product/ai_evidence/`.

---

## 4. G9.1 – Sơ đồ tư duy về vai trò QA/QC

Đối với G9.1, AI được sử dụng để tạo sơ đồ tư duy ban đầu về vai trò QA/QC cho thị trường việc làm 2026+. Sau đó, sinh viên xem xét sơ đồ tư duy do AI tạo và xác định ba vấn đề:

1. AI chưa nhấn mạnh đủ về kiểm thử dựa trên rủi ro.
2. AI chưa tách biệt rõ giữa kiểm thử tự động và kiểm thử có AI hỗ trợ.
3. AI chưa đưa vào đủ kiến thức miền nghiệp vụ.

Sơ đồ tư duy đã chỉnh sửa bổ sung kiểm thử dựa trên rủi ro, tách kiểm thử tự động khỏi kiểm thử có AI hỗ trợ, đồng thời bổ sung kiến thức miền nghiệp vụ, chiến lược kiểm thử, quản lý kiểm thử và xác minh đầu ra của AI.

**Các sản phẩm sơ đồ tư duy:**

- [Sơ đồ tư duy QA/QC do AI tạo](../mindmap/ai_generated_qaqc_mindmap.md)
- [Sơ đồ tư duy QA/QC đã chỉnh sửa](../mindmap/corrected_qaqc_mindmap.md)
- [Các lỗi của AI trong sơ đồ tư duy](../mindmap/mindmap_ai_mistakes.md)

---

## 5. Báo cáo kiểm toán AI

Báo cáo kiểm toán AI tuân theo cấu trúc 5 phần bắt buộc cho mỗi sản phẩm được tạo với sự hỗ trợ của AI:

1. Prompt + công cụ.
2. Đầu ra của AI.
3. Nhận định.
4. Lý do.
5. Phần sinh viên chỉnh sửa.

Báo cáo kiểm toán 7 sản phẩm có sự hỗ trợ của AI:

| Mục | Sản phẩm                                       | Nhận định       |
| --- | ---------------------------------------------- | --------------- |
| 01  | Đánh giá thị trường việc làm ở Yêu cầu 1       | CHƯA HOÀN CHỈNH |
| 02  | Các lỗi trong Yêu cầu 2, lỗi 01–05             | CHƯA HOÀN CHỈNH |
| 03  | Các lỗi trong Yêu cầu 2, lỗi 06–10             | CHƯA HOÀN CHỈNH |
| 04  | Các lỗi trong Yêu cầu 2, lỗi 11–15             | CHƯA HOÀN CHỈNH |
| 05  | Các lỗi trong Yêu cầu 2, lỗi 16–20             | CHƯA HOÀN CHỈNH |
| 06  | Test case kiểm thử sản phẩm vật lý ở Yêu cầu 3 | CHƯA HOÀN CHỈNH |
| 07  | Sơ đồ tư duy vai trò QA/QC G9.1                | CHƯA HOÀN CHỈNH |

AI hữu ích trong việc soạn thảo, rà soát checklist và tạo ý tưởng. Tuy nhiên, mọi đầu ra của AI đều cần được sinh viên xác minh, chỉnh sửa và kiểm tra nguồn.

**Sản phẩm kiểm toán AI:**

- [Báo cáo kiểm toán AI](../ai_compliance/ai_audit_report.md)

---

## 6. Bài phê bình AI

**Sản phẩm chính:**

- [Bài phê bình AI 200–300 từ](../ai_compliance/ai_critique.md)

Bài phê bình AI tóm tắt cách sử dụng AI trong HW01, gồm các phần AI hỗ trợ tốt, các hạn chế còn tồn tại và những nội dung em phải tự kiểm chứng hoặc chỉnh sửa. Nội dung nhấn mạnh rằng AI chỉ được dùng để hỗ trợ tạo nháp và gợi ý, còn kết quả cuối cùng phải dựa trên nguồn đáng tin cậy, minh chứng thực tế và đánh giá của sinh viên.

---

## 7. Công bố bắt buộc

Test case, phần giải thích lỗi, phần rà soát checklist và sơ đồ tư duy vai trò QA/QC ban đầu được tạo hoặc rà soát với sự hỗ trợ của ChatGPT. Em đã xem xét và chỉnh sửa phần phân tích thị trường việc làm ở Yêu cầu 1, phần giải thích lỗi ở Yêu cầu 2, test case kiểm thử sản phẩm vật lý ở Yêu cầu 3 và sơ đồ tư duy G9.1 trước khi đưa vào bài nộp cuối cùng.

Đối với Yêu cầu 3, AI đã tạo một bộ ban đầu gồm 15 test case kiểm thử sản phẩm vật lý cho quạt lửng ASIA A16007-XV0. Em đã thực thi các bài kiểm thử trên thiết bị thật, điền kết quả thực tế và nhận định đạt/không đạt, ghi lại minh chứng video, ghi nhận lỗi đã phát hiện và bổ sung các trường hợp biên mà AI bỏ sót: cản nhẹ chuyển động quay, nhấn đồng thời hai nút tốc độ và kiểm tra độ ổn định sau khi điều chỉnh độ cao hoặc góc nghiêng.

Báo cáo kiểm toán AI chi tiết được đính kèm trong Appendix A. Em xác nhận không sử dụng AI để tạo bất kỳ artifact nào thuộc nhóm bị cấm, bao gồm ảnh thiết bị với thẻ sinh viên, video thực thi có giọng nói thật, ảnh chụp màn hình tin tuyển dụng có tên tài khoản và ảnh chụp GitHub Issues có username.

**Các sản phẩm công bố và checklist:**

- [Biểu mẫu AI-03 Công bố sử dụng AI](../ai_compliance/AI-03_AI_Use_Disclosure_Form.md)
- [Checklist AI-05 về quyền riêng tư và sử dụng AI có trách nhiệm](../ai_compliance/AI-05_Privacy_Responsible_AI_Use_Checklist.md)

---

## 8. Nhật ký prompt

Toàn bộ nhật ký prompt được lưu trong thư mục `ai_compliance/`.

- [Mục lục nhật ký prompt](../ai_compliance/prompt_log.md)
- [Nhật ký prompt Yêu cầu 1](../ai_compliance/prompt_log_requirement_1.md)
- [Nhật ký prompt Yêu cầu 2](../ai_compliance/prompt_log_requirement_2.md)
- [Nhật ký prompt Yêu cầu 3](../ai_compliance/prompt_log_requirement_3.md)
- [Nhật ký prompt sơ đồ tư duy](../ai_compliance/prompt_log_mindmap.md)

---

## 9. Tự đánh giá

| STT           | Tiêu chí                                                                           | Điểm tối đa | Điểm tự đánh giá | Minh chứng / Ghi chú                                                                                                                                                                                                                                                                                                                    |
| ------------- | ---------------------------------------------------------------------------------- | ----------: | ---------------: | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1             | Thị trường việc làm QA/QC 2026+ (10 việc làm x 3 điểm + phân tích tác động của AI) |          40 |               40 | [Bảng thị trường việc làm](../requirement_1_jobs/job_market_table.md), [thư mục ảnh chụp màn hình](../requirement_1_jobs/screenshots/job_01_top.png)                                                                                                                                                                                    |
| 2             | Lỗi phần mềm giai đoạn 2022–2026 (20 lỗi)                                          |          20 |               20 | [Các lỗi phần mềm 2022–2026](../requirement_2_defects/software_defects_2022_2026.md)                                                                                                                                                                                                                                                    |
| 3             | Thiết kế kiểm thử sản phẩm vật lý (15 test case + 5 video)                         |          25 |               25 | [Test cases](../requirement_3_physical_product/test_cases.md), [link video](../requirement_3_physical_product/videos/video_links.md), [ảnh thiết bị](../requirement_3_physical_product/device_photo/device_with_student_id.jpg), [ảnh chụp GitHub issue](../requirement_3_physical_product/github_issues/issues_page_with_username.png) |
| AI-1          | Đã đính kèm [AI-02] Báo cáo kiểm toán AI theo cấu trúc 5 phần                      |           8 |                8 | [Báo cáo kiểm toán AI](../ai_compliance/ai_audit_report.md)                                                                                                                                                                                                                                                                             |
| AI-2          | Bài phê bình AI 200–300 từ + đã đính kèm [AI-03] Bản công bố sử dụng AI            |           4 |                4 | [Bài phê bình AI](../ai_compliance/ai_critique.md), [Biểu mẫu công bố sử dụng AI](../ai_compliance/AI-03_AI_Use_Disclosure_Form.md)                                                                                                                                                                                                     |
| AI-3          | [AI-05] Checklist đã ký + các minh chứng chống gian lận                            |           3 |                3 | [Checklist quyền riêng tư](../ai_compliance/AI-05_Privacy_Responsible_AI_Use_Checklist.md), [nhật ký prompt](../ai_compliance/prompt_log.md), [thư mục minh chứng AI R3](../requirement_3_physical_product/ai_evidence/)                                                                                                                   |
| **Tổng cộng** |                                                                                    |     **100** |          **100** |                                                                                                                                                                                                                                                                                                                                         |
