# AI-03 – AI Use Disclosure Form

**Faculty of Information Technology (FIT) – Ho Chi Minh City University of Science (HCMUS)**  
**CS423 / CSC13003 – Software Testing (AI-augmented · 2026)**  
**AI POLICY · TEMPLATES — 2026 v1.0**

## AI Use Disclosure Form

Attach to assignments where AI was used in any permitted capacity.

Adapted from Med Kharbach, PhD (2026) — AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0.  
This adaptation is prepared for FIT@HCMUS – CS423 / CSC15003 Software Testing course.

---

## 1. Course & Student Info

| Field                 | Value                                       |
| --------------------- | ------------------------------------------- |
| Course                | CS423 / CSC13003 – Software Testing         |
| Assignment ID         | HW01                                        |
| Assignment Title      | Jobs, Defects, and Physical Product Testing |
| AI Use Category (1–5) | Category 03                                 |
| Date                  | 04/06/2026                                  |
| Student name          | Nguyen Thanh Tien                           |
| Student ID            | 23127539                                    |

---

## 2. Disclosure Questions

### 1. AI tool(s) used

List every AI tool used for this assignment, for example: ChatGPT, Claude, Gemini, GitHub Copilot, Cursor, etc.

**Answer:**

- ChatGPT

---

### 2. Stage(s) of the assignment where AI was used

Tick all that apply:

- [x] brainstorming
- [x] outlining
- [x] drafting
- [x] feedback
- [x] revision
- [ ] coding
- [ ] data analysis
- [x] visual design
- [ ] other: \***\*\*\*\*\***\_\_\***\*\*\*\*\***

---

### 3. Main prompts or tasks given to the AI

Paste the 2–3 most impactful prompts verbatim. For the full transcript, attach Appendix A (`prompt_log.md`).

**Prompt 1 – Requirement 1 Job Market Review**

```text
Tôi đang làm Requirement 1 cho bài Software Testing HW01.

Yêu cầu của Requirement 1:
- Tìm 10 tin tuyển dụng QA/QC được đăng trong vòng 60 ngày trước ngày nộp.
- Có ít nhất 3 vị trí yêu cầu hoặc nhắc đến AI / LLM / automation-AI / AI-assisted testing.
- Mỗi tin tuyển dụng phải có: source link, dated screenshot, job description, required skills, salary.
- Mỗi tin cần có phần AI Impact Analysis.
- Screenshot cần có thông tin tài khoản cá nhân/account name nếu nền tảng yêu cầu đăng nhập.

Hãy kiểm tra giúp tôi report đã đủ yêu cầu chưa, có job nào bị phân loại AI-related quá mức không, có thiếu thông tin quan trọng không, và có lỗi trình bày Markdown nào nên sửa không.
```

**Prompt 2 – Requirement 2 Software Defects Explanation**

```text
Giải thích các lỗi phần mềm hoặc sự cố liên quan đến phần mềm bằng ngôn ngữ đơn giản.
Với mỗi lỗi, hãy bao gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng và giải pháp khả thi.
Không duyệt web. Chỉ trả lời dựa trên kiến thức của bạn.
Sau khi giải thích từng lỗi, hãy nêu thêm loại kiểm thử nào có thể đã phát hiện lỗi hoặc giảm rủi ro.
```

**Prompt 3 – Requirement 3 Physical Product Test Cases**

```text
Tôi đang làm bài Software Testing HW01 – Requirement 3: Test cases for ONE physical product.

Thiết bị tôi chọn là quạt lửng ASIA A16007-XV0.
Hãy thiết kế 15 test cases cho thiết bị vật lý này.
Mỗi test case phải có đầy đủ các cột: Test Case ID, Objective, Input, Steps, Expected Result, Actual Result, Verdict.
Test cases cần bao gồm chức năng cơ bản, usability, safety, reliability và một số edge cases.
```

For the complete prompts and AI outputs, see:

- `ai_compliance/prompt_log.md`
- `ai_compliance/prompt_log_requirement_1.md`
- `ai_compliance/prompt_log_requirement_2.md`
- `ai_compliance/prompt_log_requirement_3.md`
- `ai_compliance/prompt_log_mindmap.md`

---

### 4. Specific parts of the work AI contributed to

Be specific.

**Answer:**

AI contributed to the following parts of the assignment:

- Requirement 1: AI helped review the QA/QC job market table, identify missing fields, and check whether AI-related job claims were overclaimed.
- Requirement 2: AI generated draft explanations for 20 software defects. The student verified the explanations using source links and rewrote unsupported claims.
- Requirement 3: AI generated an initial set of physical product test cases for the ASIA pedestal fan. The student executed the real tests, added actual results, found a defect, and added three AI-missed edge cases.
- Mindmap: AI generated the first QA/QC role mindmap. The student identified three mistakes or missing points and created a corrected version.

---

### 5. How I reviewed, revised, or verified the AI output

Describe your verification method.

**Answer:**

I reviewed and verified AI output using the following methods:

- For Requirement 1, I checked the job postings, screenshots, salary information, job descriptions, required skills, and AI-related requirements manually.
- For Requirement 2, I verified software defect information using source links such as official vendor reports, NVD/CISA entries, and reputable news sources.
- For Requirement 3, I executed the test cases on the real ASIA pedestal fan, recorded five execution videos, documented actual results, and logged a confirmed defect in GitHub Issues.
- For AI-missed edge cases, I compared the AI-generated test cases with my final test suite and documented three edge cases that AI did not generate.
- For the mindmap, I compared the AI-generated version with the corrected version and documented three issues: missing risk-based testing, unclear separation between automation testing and AI-assisted testing, and insufficient domain knowledge.
- I did not treat AI output as the final source of truth. All final content was reviewed and corrected before submission.

---

### 6. Citation

Software Testing uses the IEEE style.

**Citation examples:**

- OpenAI. (2026). ChatGPT [Large language model]. https://chatgpt.com

---

## 3. Statement of Honesty

By signing below, I confirm that the disclosure above is accurate and complete. I understand that undisclosed or false disclosure of AI use is treated as academic misconduct and may result in a 0 grade for the assignment and disciplinary referral.

## Signature

| Field                  | Value                               |
| ---------------------- | ----------------------------------- |
| Student name (printed) | Nguyen Thanh Tien                   |
| Student ID             | 23127539                            |
| Class / Cohort         | 23KTMP3                             |
| Course                 | CS423 / CSC13003 – Software Testing |
| Instructor             | Ho Tuan Thanh                       |
| Date                   | 04/06/2026                          |
| Signature              | Nguyen Thanh Tien                   |

---

## References

Kharbach, M. (2026). _AI Use Policy Templates for Higher Education_. CC BY-NC-SA 4.0.  
ISTQB Foundation Level Syllabus (latest version).  
Hardman, P. (2025). _A Post-AI Learning Taxonomy_.  
Fuster Rabella, M. (2025). _OECD Education Working Paper No. 338_.  
Perkins, M., Roe, J., & Furze, L. (2025). _AI Assessment Scale_.  
Anthropic. (2025). _Building reliable AI test agents — engineering blog_.  
DeepEval & Promptfoo documentation — testing frameworks for LLM systems.
