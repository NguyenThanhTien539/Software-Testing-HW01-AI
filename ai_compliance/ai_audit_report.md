# AI Audit Report

## 1. AI Audit Entries

## AI Audit Entry 01 – Prompt R1-01: Review Requirement 1 Job Market Table

### (1) Prompt + công cụ

**Công cụ:** ChatGPT
**Timestamp:** 09:20 04/06/2026
**Requirement:** Requirement 1 – QA/QC Job Market 2026+
**Artifact:** AI review cho file [job_market_table.md](../requirement_1_jobs/job_market_table.md)

**Prompt:**
Xem chi tiết trong [prompt_log.md](./prompt_log.md), Prompt R1-01.

Prompt yêu cầu AI kiểm tra file Requirement 1 theo checklist: có đủ 10 job QA/QC hay chưa, có ít nhất 3 job liên quan AI/LLM/automation-AI hay chưa, mỗi job có source link, dated screenshot, job description, required skills, salary và AI Impact Analysis hay chưa. Prompt cũng yêu cầu AI chỉ ra các phần có thể bị overclaim về AI, thiếu thông tin hoặc lỗi trình bày Markdown.

### (2) AI output

Full AI output được lưu trong [prompt_log.md](./prompt_log.md), Prompt R1-01.

Tóm tắt output:

- AI xác nhận report có đủ 10 job QA/QC.
- AI xác nhận report có ít nhất 3 job liên quan AI/LLM/AI-assisted testing.
- AI chỉ ra rủi ro về dated screenshot, account name trong screenshot, salary chưa rõ ở một số job và Job 07 có thể bị phân loại AI-related hơi rộng.
- AI đề xuất thêm ngày chụp screenshot, làm rõ Job 07 là AI/ML-related chứ không phải LLM/GenAI, chuẩn hóa salary và sửa vài lỗi Markdown nhỏ.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI output hữu ích để rà checklist, nhưng chưa thể xem là hoàn chỉnh vì AI không trực tiếp kiểm tra được ảnh screenshot thật, account name trong ảnh, hoặc việc ảnh có thể hiện ngày/hạn tuyển hay không. AI cũng chỉ ra Job 07 có thể bị hiểu quá mức nếu ghi như job yêu cầu LLM/GenAI, trong khi nội dung job chủ yếu liên quan đến automation testing và kiểm thử ML-related features/workflows. Vì Requirement 1 yêu cầu screenshot có account name và job phải có bằng chứng trong vòng 60 ngày, phần này cần sinh viên tự kiểm tra lại bằng ảnh và source link.

### (5) Student fix

Tôi sử dụng AI output như checklist rà soát, không copy trực tiếp vào report.

Các chỉnh sửa/thao tác kiểm tra:

- Kiểm tra toàn bộ screenshots trong `requirement_1_jobs/screenshots/` để đảm bảo có job title, company, salary/date/deadline và account name nếu nền tảng yêu cầu.
- Chỉnh Job 07 theo hướng AI/ML-related, không ghi như job yêu cầu trực tiếp LLM/GenAI.
- Không khẳng định job yêu cầu AI/LLM nếu source không thể hiện trực tiếp AI, LLM, AI-assisted testing, AI-powered tools hoặc ML-related testing.

---

## AI Audit Entry 02 – Prompt R2-01: Defect 01–05

### (1) Prompt + công cụ

**Công cụ:** ChatGPT
**Timestamp:** 14:20 03/06/2026
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026
**Artifact:** AI-generated explanation cho Defect 01–05

**Prompt:**
Xem chi tiết trong [prompt_log.md](./prompt_log.md), Prompt R2-01.

Prompt yêu cầu AI giải thích 5 lỗi phần mềm bằng ngôn ngữ đơn giản, gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng, giải pháp khả thi và loại kiểm thử có thể phát hiện hoặc giảm rủi ro.

Các defect được xử lý:

1. Chatbot của Air Canada cung cấp sai thông tin hoàn tiền vé tang chế.
2. ChatGPT tạo trích dẫn pháp lý giả trong vụ Mata v. Avianca.
3. Google AI Overviews đưa ra gợi ý tìm kiếm không chính xác hoặc kỳ lạ.
4. Chatbot Tessa của NEDA đưa ra lời khuyên có hại liên quan đến rối loạn ăn uống.
5. Công cụ tuyển dụng AI của iTutorGroup bị cáo buộc phân biệt tuổi.

### (2) AI output

AI output được lưu trong [prompt_log.md](./prompt_log.md), Prompt R2-01.

Tóm tắt output:

- AI giải thích rõ 5 defect đầu.
- AI đưa ra nguyên nhân có thể, hậu quả, mức độ nghiêm trọng, giải pháp và loại kiểm thử phù hợp.
- AI đề xuất các loại kiểm thử như fact-checking testing, bias testing, safety testing, domain expert review và human review testing.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI output hữu ích nhưng có một số suy diễn chưa được nguồn xác nhận trực tiếp. Với Defect 01, AI suy đoán chatbot có thể được huấn luyện hoặc cấu hình chưa đầy đủ, trong khi source chỉ xác nhận chatbot đưa thông tin sai. Với Defect 02, AI nói lỗi có thể ảnh hưởng đến quyền lợi của các bên và quá trình xét xử, nhưng source chính tập trung vào việc luật sư nộp citation giả và bị sanction. Với Defect 05, AI nhắc đến “năm tốt nghiệp” như một yếu tố lọc ứng viên, nhưng source EEOC không nêu chi tiết này.

### (5) Student fix

Tôi đã đối chiếu từng phần với source link và sửa lại report theo hướng thận trọng hơn:

- Defect 01: Chỉ ghi lỗi training/cấu hình là “nguyên nhân có thể”, không khẳng định là nguyên nhân chính thức.
- Defect 02: Tập trung vào hậu quả đã được xác nhận: luật sư bị xử phạt và uy tín nghề nghiệp bị ảnh hưởng.
- Defect 03: Ghi hệ thống có thể diễn giải sai nguồn hoặc thiếu kiểm thử với truy vấn bất thường, không khẳng định root cause cụ thể nếu source không nói rõ.
- Defect 04: Tập trung vào harmful advice trong bối cảnh rối loạn ăn uống, không kết luận rộng cho mọi chatbot sức khỏe.
- Defect 05: Không dùng chi tiết “năm tốt nghiệp” trong report chính vì source không xác nhận.

---

## AI Audit Entry 03 – Prompt R2-02: Defect 06–10

### (1) Prompt + công cụ

**Công cụ:** ChatGPT
**Timestamp:** 14:35 03/06/2026
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026
**Artifact:** AI-generated explanation cho Defect 06–10

**Prompt:**
Xem chi tiết trong [prompt_log.md](./prompt_log.md), Prompt R2-02.

Prompt yêu cầu AI giải thích 5 lỗi phần mềm hoặc sự cố liên quan đến phần mềm bằng ngôn ngữ đơn giản, gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng, giải pháp khả thi và loại kiểm thử có thể phát hiện hoặc giảm rủi ro.

Các defect được xử lý: 6. Chatbot AI của DPD chửi thề, tự gọi mình là vô dụng và chỉ trích công ty. 7. McDonald’s kết thúc thử nghiệm AI drive-thru với IBM sau vấn đề độ chính xác đơn hàng. 8. Bản cập nhật CrowdStrike Falcon khiến máy Windows crash trên toàn cầu. 9. AT&T gặp outage toàn quốc sau thay đổi mạng có lỗi cấu hình. 10. FAA NOTAM outage làm gián đoạn các chuyến bay nội địa tại Hoa Kỳ.

### (2) AI output

Full AI output được lưu trong [prompt_log.md](./prompt_log.md), Prompt R2-02.

Tóm tắt output:

- AI giải thích rõ 5 sự cố.
- AI đề xuất các nguyên nhân có thể và các loại kiểm thử như prompt injection testing, speech recognition testing, regression testing, canary testing, configuration testing, disaster recovery testing và data integrity testing.
- AI nhận diện đúng mức độ nghiêm trọng cao của các sự cố hạ tầng quy mô lớn.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI output hữu ích nhưng có một số chi tiết suy diễn. Với Defect 06, AI cho rằng sự cố DPD có thể do thiếu content filter hoặc prompt injection, trong khi bài báo không xác nhận đầy đủ nguyên nhân kỹ thuật bên trong. Với Defect 07, AI nêu tiếng ồn, giọng nói, gió và menu phức tạp là nguyên nhân, nhưng source AP chủ yếu xác nhận vấn đề độ chính xác và việc McDonald’s kết thúc thử nghiệm. Với Defect 09, AI nói outage ảnh hưởng đến nhắn tin, trong khi FCC tập trung vào voice, data và 911. Với Defect 10, AI suy đoán hệ thống dự phòng không hoạt động tốt, nhưng FAA chủ yếu nói về damaged database file và không có bằng chứng cyberattack.

### (5) Student fix

Tôi sửa report để tách rõ thông tin đã được source xác nhận và giả thuyết:

- Defect 06: Ghi weak guardrails/prompt manipulation là nguyên nhân có thể, không khẳng định chắc chắn.
- Defect 07: Dùng tiếng ồn, giọng nói và order phức tạp như test scenarios, không coi là root cause chính thức.
- Defect 08: Mô tả sự cố là content update/Channel File 291 validation issue thay vì chỉ nói “bad configuration”.
- Defect 09: Tập trung vào ảnh hưởng voice, data và emergency services theo source, không nhấn mạnh texting nếu source không nêu rõ.
- Defect 10: Dùng backup/failover/recovery như bài học kiểm thử, không khẳng định là nguyên nhân chính thức.

---

## AI Audit Entry 04 – Prompt R2-03: Defect 11–15

### (1) Prompt + công cụ

**Công cụ:** ChatGPT
**Timestamp:** 14:50 03/06/2026
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026
**Artifact:** AI-generated explanation cho Defect 11–15

**Prompt:**
Xem chi tiết trong [prompt_log.md](./prompt_log.md), Prompt R2-03.

Prompt yêu cầu AI giải thích 5 lỗi phần mềm hoặc sự cố liên quan đến phần mềm bằng ngôn ngữ đơn giản, gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng, giải pháp khả thi và loại kiểm thử có thể phát hiện hoặc giảm rủi ro.

Các defect được xử lý: 11. Toyota dừng sản xuất tại Nhật Bản vì hệ thống đặt hàng linh kiện/phụ tùng bị lỗi. 12. MOVEit Transfer có lỗ hổng SQL injection CVE-2023-34362. 13. XZ Utils 5.6.0 và 5.6.1 bị ảnh hưởng bởi backdoor CVE-2024-3094. 14. Optus outage toàn quốc sau routine software upgrade và thay đổi routing information. 15. Cloudflare outage ngày 18/11/2025 do vấn đề kích thước feature file.

### (2) AI output

Full AI output được lưu trong [prompt_log.md](./prompt_log.md), Prompt R2-03.

Tóm tắt output:

- AI giải thích từng defect và đưa ra nguyên nhân có thể, hậu quả, severity và solution.
- AI đề xuất các loại kiểm thử phù hợp như system integration testing, backup and recovery testing, SQL injection testing, penetration testing, supply-chain security testing, reproducible build testing, network configuration testing, canary deployment và boundary testing.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI output nhìn chung hữu ích nhưng còn khái quát hóa hoặc đơn giản hóa một số chi tiết. Với Defect 11, AI nói chung là lỗi server hoặc resource issue, trong khi Toyota nêu cụ thể hơn về một số server không khả dụng và vấn đề disk space sau bảo trì. Với Defect 12, AI nói attacker có thể thao túng database, nhưng NVD chủ yếu mô tả việc attacker chưa xác thực có thể truy cập database MOVEit. Với Defect 13, AI nhắc đến contributor hoặc quá trình phát hành, trong khi CISA alert xác nhận các phiên bản XZ Utils bị ảnh hưởng nhưng không trình bày đầy đủ quá trình điều tra contributor. Với Defect 15, AI nói website có thể chậm, nhưng source Cloudflare tập trung vào service failure và feature file issue.

### (5) Student fix

Tôi chỉnh report để bám sát source hơn:

- Defect 11: Bổ sung chi tiết từ Toyota về server không khả dụng và disk-space/storage issue sau bảo trì.
- Defect 12: Dùng cách viết “truy cập database trái phép” và “nguy cơ rò rỉ dữ liệu”, không khẳng định chắc chắn việc thao túng dữ liệu.
- Defect 13: Mô tả đây là supply-chain compromise, không khẳng định chi tiết contributor nếu không có source điều tra riêng.
- Defect 14: Ghi sự cố liên quan routing information changes sau software upgrade, không giải thích quá sâu về cơ chế bên trong thiết bị mạng.
- Defect 15: Ghi rõ hơn nguyên nhân theo Cloudflare: feature file tăng kích thước lớn hơn dự kiến và vượt giới hạn, thay vì chỉ nói chung chung là file vượt giới hạn.

---

## AI Audit Entry 05 – Prompt R2-04: Defect 16–20

### (1) Prompt + công cụ

**Công cụ:** ChatGPT
**Timestamp:** 15:05 03/06/2026
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026
**Artifact:** AI-generated explanation cho Defect 16–20

**Prompt:**
Xem chi tiết trong [prompt_log.md](./prompt_log.md), Prompt R2-04.

Prompt yêu cầu AI giải thích 5 lỗi phần mềm hoặc lỗ hổng bảo mật bằng ngôn ngữ đơn giản, gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng, giải pháp khả thi và loại kiểm thử có thể phát hiện hoặc giảm rủi ro.

Các defect được xử lý: 16. Atlassian Confluence OGNL injection CVE-2022-26134. 17. Spring4Shell remote code execution CVE-2022-22965. 18. Apache Commons Text Text4Shell CVE-2022-42889. 19. Cisco IOS XE Web UI privilege escalation CVE-2023-20198. 20. CitrixBleed sensitive information disclosure CVE-2023-4966.

### (2) AI output

Full AI output được lưu trong [prompt_log.md](./prompt_log.md), Prompt R2-04.

Tóm tắt output:

- AI giải thích các lỗ hổng bằng ngôn ngữ dễ hiểu.
- AI đưa ra nguyên nhân có thể, hậu quả, severity, solution và các loại security testing liên quan.
- AI đề xuất các loại kiểm thử như injection testing, penetration testing, dependency scanning, SAST, DAST, access control testing, fuzz testing và memory safety testing.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI output có ích về mặt kỹ thuật nhưng mở rộng hậu quả vượt quá điều nguồn chính xác nhận trực tiếp. Với Defect 16, AI nói attacker có thể sửa tài liệu, cài malware hoặc dùng server làm pivot point; NVD chủ yếu xác nhận unauthenticated remote code execution. Với Defect 17, AI nói attacker có thể cài web shell và đánh cắp dữ liệu; đây là hậu quả có thể xảy ra với RCE nhưng không phải sự kiện được NVD xác nhận cụ thể. Với Defect 18, AI nhắc đến information leakage, trong khi NVD tập trung vào unsafe interpolation, possible arbitrary code execution và remote contact. Với Defect 19, AI nói attacker có thể theo dõi traffic, nhưng CISA chủ yếu nói về privilege escalation và attacker đạt quyền cao. Với Defect 20, AI nói attacker có thể đi sâu vào mạng nội bộ, trong khi NVD xác nhận sensitive information disclosure nhưng không mô tả lateral movement.

### (5) Student fix

Tôi sửa report để ghi các hậu quả này là tác động tiềm năng, không phải sự kiện đã được xác nhận:

- Defect 16: Ghi tác động chính là arbitrary code execution và nguy cơ server compromise.
- Defect 17: Giữ web shell/data theft như hậu quả có thể có của RCE, không ghi như sự kiện chắc chắn.
- Defect 18: Tập trung vào unsafe interpolation, remote contact và khả năng code execution tùy cách ứng dụng sử dụng thư viện.
- Defect 19: Tập trung vào privilege escalation và nguy cơ attacker kiểm soát thiết bị mạng.
- Defect 20: Tập trung vào sensitive information/session exposure và nguy cơ truy cập trái phép, không khẳng định attacker chắc chắn di chuyển sâu trong mạng nội bộ.

---

---

## AI Audit Entry 06 – Prompt R3-01: Generate Physical Product Test Cases

### (1) Prompt + công cụ

**Công cụ:** ChatGPT  
**Timestamp:** [ĐIỀN GIỜ THẬT BẠN CHẠY PROMPT R3-01]  
**Requirement:** Requirement 3 – Physical Product Testing  
**Artifact:** AI-generated test cases cho quạt lửng ASIA A16007-XV0

**Prompt:**  
Xem chi tiết trong [prompt_log_requirement_3.md](./prompt_log_requirement_3.md), Prompt R3-01.

Prompt yêu cầu AI thiết kế 15 test cases cho quạt lửng ASIA A16007-XV0, gồm Test Case ID, Objective, Input, Steps, Expected Result, Actual Result và Verdict. Prompt cũng yêu cầu test cases bao gồm functional test, usability test, safety test, reliability test và một số edge cases.

### (2) AI output

Full AI output được lưu trong [prompt_log_requirement_3.md](./prompt_log_requirement_3.md), Prompt R3-01.

Tóm tắt output:

- AI tạo 15 test cases cho quạt lửng ASIA A16007-XV0.
- AI bao phủ các chức năng cơ bản như bật/tắt, tốc độ 1/2/3, quay trái phải, tiếng ồn, độ ổn định, an toàn lồng quạt, dây điện/phích cắm và chạy liên tục.
- AI tạo 3 edge cases: chuyển tốc độ nhanh liên tục, mất điện khi quạt đang chạy, và bật/tắt oscillation khi quạt đang chạy.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI output hữu ích để tạo test cases ban đầu, nhưng chưa hoàn chỉnh vì AI bỏ sót một số edge cases vật lý quan trọng. Cụ thể, AI không tạo ra các test cases về cản nhẹ chuyển động quay trái phải, nhấn đồng thời hai nút tốc độ, và kiểm tra độ ổn định sau khi điều chỉnh độ cao hoặc góc nghiêng. Đây là các tình huống thực tế có thể xảy ra với quạt lửng dùng nút cơ và cơ chế điều chỉnh vật lý.

Ngoài ra, AI chưa biết kết quả thực tế sau khi test trên thiết bị thật, nên các cột Actual Result và Verdict chỉ ở trạng thái “To be executed”. Sinh viên phải tự chạy test, ghi kết quả thực tế, xác định Pass/Fail và ghi defect nếu có.

### (5) Student fix

Tôi đã chạy test trên thiết bị thật và cập nhật lại file `test_cases.md` với kết quả thực tế.

Các chỉnh sửa/thao tác kiểm tra:

- Bổ sung 3 edge cases AI không tạo ra:
  - TC-13: Cản nhẹ chuyển động quay trái phải.
  - TC-14: Nhấn đồng thời hai nút tốc độ.
  - TC-15: Kiểm tra quạt sau khi điều chỉnh độ cao hoặc góc nghiêng.
- Ghi rõ 5 test cases có video: TC-01, TC-03, TC-05, TC-13, TC-14.
- Cập nhật Actual Result và Verdict sau khi chạy test thật.
- Ghi nhận defect `DEF-01 – Quạt phát ra tiếng cọt kẹt lớn khi đứng yên ở tốc độ 3`.
- Tạo file `ai_missed_edge_cases.md` để giải thích vì sao AI bỏ sót 3 edge cases trên.

---

## AI Audit Entry 07 – Prompt M1-01: Generate QA/QC Role Mindmap

### (1) Prompt + công cụ

**Công cụ:** ChatGPT  
**Timestamp:** 14:13 04/06/2026  
**Requirement:** G9.1 – QA/QC Role Mindmap  
**Artifact:** AI-generated QA/QC role mindmap

**Prompt:**  
Xem chi tiết trong [prompt_log_mindmap.md](./prompt_log_mindmap.md), Prompt M1-01.

### (2) AI output

Full AI output được lưu trong [prompt_log_mindmap.md](./prompt_log_mindmap.md), Prompt M1-01.

Tóm tắt output:

- AI tạo mindmap ban đầu về vai trò QA/QC trong thị trường 2026+.
- Mindmap có các nhánh như công việc chính, loại kiểm thử phổ biến, kỹ năng kỹ thuật, công cụ, AI trong QA/QC, kỹ năng mềm và lộ trình nghề nghiệp.
- Mindmap có ích như bản nháp ban đầu nhưng vẫn thiếu một số nội dung quan trọng.

### (3) Verdict

**INCOMPLETE**

### (4) Reasoning

AI tạo được mindmap ban đầu về vai trò QA/QC, bao gồm nhiều nhánh quan trọng như manual testing, automation testing, API testing, performance testing, security testing và tools. Tuy nhiên, output chưa hoàn chỉnh vì AI chưa nhấn mạnh risk-based testing, chưa tách rõ automation testing và AI-assisted testing, và chưa thể hiện đầy đủ vai trò của domain knowledge trong công việc QA/QC thực tế.

### (5) Student fix

Tôi đã tạo bản corrected mindmap. Trong bản sửa, tôi bổ sung risk-based testing, tách riêng automation testing và AI-assisted testing, đồng thời thêm nhánh domain knowledge gồm business rules, user workflows, data validation rules, industry-specific constraints và compliance requirements.

---

## 3. AI Accuracy Summary

Tổng số AI-generated artifacts được audit: **7**

| Verdict    | Số lượng | Tỷ lệ |
| ---------- | -------: | ----: |
| VALID      |        0 |    0% |
| INCOMPLETE |        7 |  100% |
| INVALID    |        0 |    0% |

Tất cả output của AI đều hữu ích để tạo bản nháp, checklist, ý tưởng kiểm thử và phần giải thích ban đầu. Tuy nhiên, tất cả output đều cần kiểm chứng lại bởi sinh viên vì AI thường khái quát hóa, suy đoán nguyên nhân có thể hoặc mở rộng hậu quả vượt quá nội dung source xác nhận trực tiếp.

---

## 4. Khi nào nên dùng AI

AI nên được dùng để:

- Tạo bản nháp ban đầu.
- Gợi ý checklist.
- Gợi ý loại kiểm thử phù hợp.
- Tóm tắt rủi ro phổ biến.
- Rà soát xem report còn thiếu trường thông tin nào.

---

## 5. Khi nào không nên dùng AI

AI không nên được dùng như nguồn sự thật cuối cùng cho:

- Nguyên nhân chính xác của sự cố thực tế.
- Hậu quả pháp lý hoặc hậu quả chính thức.
- Salary, ngày đăng, hạn tuyển hoặc yêu cầu cụ thể của job posting.
- Việc screenshot có đạt anti-cheat requirement hay không.
- Việc một lỗ hổng đã bị khai thác theo cách cụ thể nào, nếu source không xác nhận.
