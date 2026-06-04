# Prompt R1-01 – Review Requirement 1 Job Market Table

**Thời gian:** 09:20 04/06/2026
**Công cụ:** ChatGPT

## Prompt

Tôi đang làm Requirement 1 cho bài Software Testing HW01.

Yêu cầu của Requirement 1:

- Tìm 10 tin tuyển dụng QA/QC được đăng trong vòng 60 ngày trước ngày nộp.
- Có ít nhất 3 vị trí yêu cầu hoặc nhắc đến AI / LLM / automation-AI / AI-assisted testing.
- Mỗi tin tuyển dụng phải có: source link, dated screenshot, job description, required skills, salary.
- Mỗi tin cần có phần AI Impact Analysis.
- Screenshot cần có thông tin tài khoản cá nhân/account name nếu nền tảng yêu cầu đăng nhập.

Dưới đây là nội dung file [job_market_table.md](../requirement_1_jobs/job_market_table.md) của tôi:

Hãy kiểm tra giúp tôi:

1. Report đã có đủ 10 job QA/QC chưa?
2. Có ít nhất 3 job liên quan AI / LLM / automation-AI / AI-assisted testing chưa?
3. Mỗi job đã có đủ source link, ngày đăng hoặc hạn tuyển, job description, required skills, salary và AI Impact Analysis chưa?
4. Có job nào bị phân loại AI-related quá mức không? Ví dụ job chỉ có automation testing nhưng tôi ghi như thể có LLM/GenAI.
5. Có job nào thiếu thông tin quan trọng không?
6. Có lỗi trình bày Markdown nào nên sửa không?
7. Hãy liệt kê các điểm có thể khiến tôi bị trừ điểm.
8. Hãy đề xuất cách sửa ngắn gọn cho từng lỗi.

Lưu ý:

- Không cần viết lại toàn bộ report.
- Chỉ review theo checklist.
- Nếu thông tin nào không có trong nội dung tôi cung cấp, hãy ghi “chưa xác nhận được”, không tự bịa.
- Trả lời bằng tiếng Việt.

## AI Output

Mình review theo đúng checklist, không duyệt web, chỉ dựa trên file job_market_table.md bạn cung cấp.

Kết luận nhanh

Report của bạn gần đủ Requirement 1, nhưng vẫn có vài điểm dễ bị trừ:

| Mục kiểm tra                                       | Trạng thái                              |
| -------------------------------------------------- | --------------------------------------- |
| Đủ 10 job QA/QC                                    | Đạt                                     |
| Ít nhất 3 job liên quan AI/LLM/AI-assisted testing | Đạt                                     |
| Có source link                                     | Đạt                                     |
| Có job description                                 | Đạt                                     |
| Có required skills                                 | Đạt                                     |
| Có salary                                          | Tạm đạt                                 |
| Có AI Impact Analysis                              | Đạt                                     |
| Có dated screenshot                                | Chưa xác nhận được                      |
| Screenshot có account name nếu cần login           | Chưa xác nhận được                      |
| Có job bị gán AI quá mức không                     | Có thể có: Job 07 cần viết cẩn thận hơn |

## 1. Report đã có đủ 10 job QA/QC chưa?

Có, đã đủ 10 job.

File có từ Job 01 đến Job 10, đều là các vị trí QA/QC/Tester như Lead QA/QC Software Tester, Software QA Engineer, AI QC, Senior QA Engineer, QA Engineer, QC Engineer, Tester, Manual Tester Leader.

=> Mục này đạt.

## 2. Có ít nhất 3 job liên quan AI / LLM / automation-AI / AI-assisted testing chưa?

Có, đạt yêu cầu.

Trong file, bạn đang đánh dấu các job liên quan AI gồm:

| Job    | Đánh giá                                                  |
| ------ | --------------------------------------------------------- |
| Job 01 | Có AI-driven testing                                      |
| Job 02 | Có AI-first mindset, AI/LLM/Agentic AI Công cụs           |
| Job 03 | AI QC, kiểm thử AI-powered agent                          |
| Job 04 | AI-Augmented Quality Engineering, GPT/Claude, Mabl/Testim |
| Job 05 | Có AI-assisted testing                                    |
| Job 07 | Có Machine Learning features/workflows                    |

Bạn có ít nhất 5 job AI-related khá rõ: Job 01–05. Job 07 cũng có thể tính nếu tin gốc thật sự nói về ML-related features/workflows.

=> Mục này đạt.

## 3. Mỗi job đã có đủ source link, ngày đăng/hạn tuyển, job description, required skills, salary, AI Impact Analysis chưa?

Gần đủ, nhưng có vài điểm cần chỉnh.

| Job    | Nhận xét                                                                                                                                                     |
| ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Job 01 | Đủ link, ngày đăng, lương, mô tả, kỹ năng, AI Impact. Nhưng “còn hạn 9 ngày” nên cần ghi thêm ngày chụp screenshot để chứng minh.                            |
| Job 02 | Đủ.                                                                                                                                                          |
| Job 03 | Đủ, nhưng salary là “Competitive remuneration / Không công khai”. Nên ghi rõ là Salary: Not disclosed / Không công khai.                                     |
| Job 04 | Đủ.                                                                                                                                                          |
| Job 05 | Đủ.                                                                                                                                                          |
| Job 06 | Đủ.                                                                                                                                                          |
| Job 07 | Có “Posted 1 month ago”, nhưng nên ghi thêm ngày chụp screenshot vì “1 month ago” là tương đối.                                                              |
| Job 08 | Có deadline nhưng không có ngày đăng. Bạn ghi “Ngày đăng không hiển thị”, ổn, nhưng cần dùng hạn nộp + ngày chụp screenshot để chứng minh nằm trong 60 ngày. |
| Job 09 | Có hạn nộp nhưng không có ngày đăng. Cần bổ sung ngày chụp screenshot.                                                                                       |
| Job 10 | Có hạn nộp nhưng không có ngày đăng. Cần bổ sung ngày chụp screenshot.                                                                                       |

=> Nội dung chính đạt, nhưng phần dated screenshot / bằng chứng trong vòng 60 ngày còn yếu nếu trong ảnh không thể hiện ngày chụp.

## 4. Có job nào bị phân loại AI-related quá mức không?

Có thể có 1 job cần cẩn thận: Job 07.

Job 07 bạn ghi là:

> “Có — liên quan đến Automation Testing và kiểm thử Machine Learning features/workflows”

Cách ghi này không sai nếu tin gốc thật sự có ML-related features/workflows. Tuy nhiên, bạn không nên viết Job 07 như thể nó yêu cầu LLM/GenAI/ChatGPT, vì trong phần bạn đưa chỉ thấy liên quan đến Machine Learning workflows/features, không phải LLM.

Cách sửa an toàn hơn:

> Có liên quan AI/ML ở mức gián tiếp: job có nhắc đến kiểm thử Machine Learning workflows hoặc ML-related features, nhưng không yêu cầu trực tiếp LLM/GenAI Công cụs.

Job 05 cũng cần kiểm tra lại ảnh gốc. Nếu tin tuyển dụng thật sự có chữ AI-assisted testing Công cụs or techniques thì ổn. Nếu đó là phần bạn tự diễn giải từ automation testing thì sẽ bị xem là gán AI quá mức.

## 5. Có job nào thiếu thông tin quan trọng không?

Có vài điểm “chưa chắc bị sai”, nhưng nên bổ sung để an toàn:

### Thiếu hoặc chưa xác nhận được ngày chụp screenshot

Requirement nói cần dated screenshot. Trong markdown, bạn có ảnh như:

```md
![Top](screenshots/job_01_top.png)
```

nhưng từ nội dung markdown hiện tại chưa xác nhận được ảnh có ngày chụp hay không, và cũng chưa xác nhận được ảnh có account name hay không.

Cách sửa: dưới mỗi job thêm dòng:

```md
**Ngày chụp screenshot:** 04/06/2026  
**Thông tin tài khoản hiển thị trong screenshot:** Có / Không yêu cầu đăng nhập / Chưa áp dụng
```

### Job 08, 09, 10 thiếu ngày đăng

Bạn có deadline, nhưng không có ngày đăng. Nếu đề bắt buộc “đăng trong vòng 60 ngày”, chỉ deadline có thể chưa đủ mạnh.

Cách sửa:

```md
**Ngày đăng:** Không hiển thị trên TopCV  
**Hạn nộp:** 26/06/2026  
**Ngày chụp screenshot:** 04/06/2026  
**Ghi chú:** Dùng hạn nộp và trạng thái tin còn hoạt động làm bằng chứng bổ sung.
```

### Job 03 salary chưa rõ

Bạn ghi “Competitive remuneration / Không công khai mức cụ thể”. Vẫn chấp nhận được, nhưng nên chuẩn hóa thành:

```md
**Lương:** Không công khai / Competitive remuneration
```

## 6. Có lỗi trình bày Markdown nào nên sửa không?

Có một vài lỗi nhỏ nên sửa:

### Lỗi 1: Job 08 thiếu dòng phân cách trước Job 09

Sau phần AI Impact của Job 08, bạn chuyển thẳng sang:

```md
### Job 09 – Tester (QA/QC) - Lĩnh Vực Tài Chính
```

Nên thêm:

```md
---
```

để đồng bộ với các job khác.

### Lỗi 2: Một số chỗ thiếu dòng trống trước “Minh chứng ảnh chụp”

Ví dụ Job 04 và Job 10 có link xong sát với heading ảnh. Nên thêm một dòng trống để Markdown đẹp hơn:

```md
**Link:** ...

**Minh chứng ảnh chụp:**
```

### Lỗi 3: Không thống nhất dấu gạch trong tiêu đề

Bạn dùng cả:

```md
### Job 05 — QA Engineer
```

và:

```md
### Job 06 – QC Engineer
```

Không nghiêm trọng, nhưng nên thống nhất dùng một kiểu, ví dụ dấu –.

### Lỗi 4: “upto” nên sửa thành “up to”

Ở Job 09:

```md
Thỏa thuận, upto 20 triệu VND
```

nên sửa thành:

```md
Thỏa thuận, up to 20 triệu VND
```

hoặc tiếng Việt:

```md
Thỏa thuận, lên đến 20 triệu VND
```

## 7. Các điểm có thể khiến bị trừ điểm

Các điểm rủi ro chính:

1. Không chứng minh rõ screenshot có ngày chụp. File chỉ liệt kê đường dẫn ảnh, chưa thấy ngày chụp trong markdown.
2. Không chứng minh screenshot có account name. Requirement yêu cầu account name nếu nền tảng cần đăng nhập, đặc biệt là LinkedIn/ITviec/TopCV có thể cần tài khoản.
3. Job 08, 09, 10 không có ngày đăng, chỉ có hạn nộp. Có thể bị hỏi: làm sao chứng minh tin được đăng trong vòng 60 ngày?
4. Job 07 có thể bị xem là AI-related hơi rộng. Nếu tin chỉ nói automation testing hoặc ML feature testing, không nên gọi là LLM/GenAI.
5. Salary của Job 03 không có số cụ thể. Không hẳn sai, nhưng nên ghi rõ “không công khai” để tránh bị xem là thiếu.
6. Chưa có bảng tổng hợp checklist. Report có danh sách chi tiết, nhưng nên thêm bảng tổng hợp 10 job để giảng viên dễ kiểm.

## 8. Đề xuất sửa ngắn gọn cho từng lỗi

| Vấn đề                         | Cách sửa ngắn                                                                        |
| ------------------------------ | ------------------------------------------------------------------------------------ |
| Chưa rõ dated screenshot       | Thêm dòng Ngày chụp screenshot: 04/06/2026 cho từng job                              |
| Chưa rõ account name           | Thêm dòng Account name hiển thị trong screenshot: Có / Không áp dụng                 |
| Job 08, 09, 10 thiếu ngày đăng | Ghi rõ Ngày đăng: Không hiển thị; Hạn nộp: ...; ngày chụp screenshot: ...            |
| Job 07 AI-related hơi rộng     | Đổi thành “AI/ML-related ở mức gián tiếp, không phải LLM/GenAI”                      |
| Job 03 salary không cụ thể     | Ghi “Không công khai / Competitive remuneration”                                     |
| Markdown thiếu phân cách       | Thêm `---` trước Job 09                                                              |
| Tiêu đề chưa thống nhất        | Dùng cùng một kiểu dấu – cho tất cả job                                              |
| Thiếu bảng tổng hợp            | Thêm bảng gồm: Job, Company, Platform, Date/Deadline, Salary, AI-related, Screenshot |

## Kết luận cuối

Report hiện tại đạt phần lõi của Requirement 1: đủ 10 job, đủ ít nhất 3 job AI-related, mỗi job đều có link, mô tả, kỹ năng, lương và AI Impact Analysis. Phần cần sửa nhất là bằng chứng ảnh chụp: phải làm rõ ngày chụp screenshot và account name nếu nền tảng yêu cầu đăng nhập. Ngoài ra, nên chỉnh Job 07 để không bị hiểu là bạn đang phóng đại automation/ML thành LLM/GenAI.

## Student verification – Prompt R1-01

Tôi đã đối chiếu lại output của AI với file `job_market_table.md`, source links và screenshots trong folder `requirement_1_jobs/screenshots`.

Kết quả kiểm tra:

- Report có đủ 10 job QA/QC.
- Report có ít nhất 3 job liên quan AI / LLM / automation-AI / AI-assisted testing.
- Mỗi job có source link, job description, required skills, salary hoặc ghi rõ không công khai/thỏa thuận, và AI Impact Analysis.
- Tôi cần kiểm tra lại screenshots để đảm bảo ảnh có title, company, salary/date/deadline và account name nếu nền tảng yêu cầu.
- Tôi chỉnh lại Job 07 để tránh hiểu nhầm rằng job yêu cầu LLM/GenAI, vì job này chủ yếu liên quan đến automation testing và kiểm thử ML-related features/workflows.
- Tôi dùng nhận xét của AI như checklist rà soát, không tự động đưa vào report nếu không có bằng chứng từ source hoặc screenshot.
