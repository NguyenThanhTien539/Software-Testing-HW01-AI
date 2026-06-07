# Bài tập HW01 Môn Kiểm thử Phần mềm – Bài tập có hỗ trợ bởi AI

**Sinh viên:** Nguyễn Thanh Tiến
**MSSV:** 23127539
**Môn học:** Kiểm thử Phần mềm
**Bài tập:** HW01 – Việc làm QA/QC, Lỗi phần mềm, Kiểm thử sản phẩm vật lý

## Tổng quan

Kho lưu trữ này chứa các tài liệu và minh chứng cho bài tập HW01 môn Kiểm thử Phần mềm. Nội dung bài tập tập trung vào:

- Phân tích thị trường việc làm QA/QC từ năm 2026 trở đi.
- Các lỗi phần mềm công khai trong giai đoạn 2022–2026.
- Thiết kế và thực thi test case cho một sản phẩm vật lý thực tế.
- Tài liệu hóa quá trình hợp tác với AI, bao gồm nhật ký prompt, báo cáo kiểm toán, phần phản biện, biểu mẫu khai báo sử dụng AI và danh sách kiểm tra quyền riêng tư.
- G9.1 sơ đồ tư duy về vai trò QA/QC, gồm phiên bản do AI tạo và phiên bản đã được sinh viên chỉnh sửa.

## Báo cáo chính

- [Báo cáo chính](report/main_report.md)
- [Tự đánh giá](report/self_assessment.md)

## Yêu cầu 1 – Thị trường việc làm QA/QC 2026+

- [Bảng thị trường việc làm](requirement_1_jobs/job_market_table.md)
- Ảnh chụp màn hình: `requirement_1_jobs/screenshots/`

Tóm tắt:

- 10 tin tuyển dụng QA/QC.
- Có ít nhất 3 vị trí liên quan đến AI/LLM/AI-assisted/automation-AI.
- Mỗi tin tuyển dụng bao gồm đường dẫn nguồn, thông tin công việc, kỹ năng yêu cầu, thông tin lương, ảnh chụp màn hình và phân tích tác động của AI.

## Yêu cầu 2 – 20 lỗi phần mềm giai đoạn 2022–2026

- [Báo cáo lỗi phần mềm](requirement_2_defects/software_defects_2022_2026.md)

Tóm tắt:

- 20 lỗi phần mềm hoặc sự cố công khai trong giai đoạn 2022–2026.
- Có ít nhất 5 lỗi liên quan đến AI/LLM.
- Mỗi lỗi bao gồm đường dẫn nguồn, mô tả, mức độ nghiêm trọng, hậu quả, giải pháp và một nhận xét về thiên kiến hoặc ảo giác của AI.

## Yêu cầu 3 – Kiểm thử sản phẩm vật lý

Sản phẩm được chọn: **Quạt đứng ASIA A16007-XV0**

- [Thông tin sản phẩm](requirement_3_physical_product/product_info.md)
- [Test case và nhật ký lỗi](requirement_3_physical_product/test_cases.md)
- [Tóm tắt test case bằng Excel](requirement_3_physical_product/test_cases_summary.xlsx)
- [Các trường hợp biên AI đã bỏ sót](requirement_3_physical_product/ai_missed_edge_cases.md)
- [Liên kết video](requirement_3_physical_product/videos/video_links.md)
- Ảnh thiết bị kèm thẻ sinh viên: `requirement_3_physical_product/device_photo/`
- Ảnh chụp GitHub issue: `requirement_3_physical_product/github_issues/`
- Minh chứng hội thoại với AI: `requirement_3_physical_product/ai_evidence/`

Tóm tắt:

- Đã thiết kế 15 test case.
- Đã thực thi 15 test case.
- 13 test case đạt, 2 test case không đạt.
- 1 lỗi đã được xác nhận: `DEF-01`.
- 5 video thực thi kiểm thử.
- 3 trường hợp biên bị AI bỏ sót đã được sinh viên bổ sung.

## G9.1 – Sơ đồ tư duy về vai trò QA/QC

- [Sơ đồ tư duy QA/QC do AI tạo](mindmap/ai_generated_qaqc_mindmap.md)
- [Sơ đồ tư duy QA/QC đã chỉnh sửa](mindmap/corrected_qaqc_mindmap.md)
- [Các lỗi của AI trong sơ đồ tư duy](mindmap/mindmap_ai_mistakes.md)

Sơ đồ tư duy đã chỉnh sửa bổ sung kiểm thử dựa trên rủi ro, tách biệt kiểm thử tự động với kiểm thử có hỗ trợ AI, đồng thời bổ sung kiến thức miền và việc xác minh đầu ra của AI.

## Tuân thủ sử dụng AI

- [Báo cáo kiểm toán AI](ai_compliance/ai_audit_report.md)
- [Phản biện việc sử dụng AI](ai_compliance/ai_critique.md)
- [AI-03 Biểu mẫu khai báo sử dụng AI](ai_compliance/AI-03_AI_Use_Disclosure_Form.md)
- [AI-05 Danh sách kiểm tra quyền riêng tư và sử dụng AI có trách nhiệm](ai_compliance/AI-05_Privacy_Responsible_AI_Use_Checklist.md)
- [Mục lục nhật ký prompt](ai_compliance/prompt_log.md)
- [Nhật ký prompt Yêu cầu 1](ai_compliance/prompt_log_requirement_1.md)
- [Nhật ký prompt Yêu cầu 2](ai_compliance/prompt_log_requirement_2.md)
- [Nhật ký prompt Yêu cầu 3](ai_compliance/prompt_log_requirement_3.md)
- [Nhật ký prompt sơ đồ tư duy](ai_compliance/prompt_log_mindmap.md)

## Cấu trúc kho lưu trữ

```text
.
├── ai_compliance/
├── mindmap/
├── report/
├── requirement_1_jobs/
├── requirement_2_defects/
├── requirement_3_physical_product/
├── 2026.HW01.Jobs.Defects.PhysicalProduct_En.pdf
└── README.md
```

## Ghi chú

- Đề bài gốc được đính kèm với tên tệp `2026.HW01.Jobs.Defects.PhysicalProduct_En.pdf`.
- Báo cáo cuối cùng nên được xuất từ `report/main_report.md` sang PDF trước khi nộp lên Moodle.
- Cần nộp kèm liên kết GitHub repository cùng với báo cáo cuối cùng.
