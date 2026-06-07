## Danh sách lỗi phần mềm

### Defect 01 – Chatbot của Air Canada cung cấp sai thông tin hoàn tiền

**Nguồn tham khảo:** https://www.theguardian.com/world/2024/feb/16/air-canada-chatbot-lawsuit  
**Năm công bố:** 2024  
**Hệ thống:** Chatbot chăm sóc khách hàng của Air Canada  
**Tổ chức/Công ty:** Air Canada  
**Loại lỗi:** AI misinformation
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng :** Cao

**Mô tả lỗi:**  
Chatbot của Air Canada cung cấp thông tin sai về chính sách hoàn tiền vé trong trường hợp thân nhân qua đời. Khách hàng dựa vào câu trả lời của chatbot để mua vé và sau đó yêu cầu hoàn tiền, nhưng Air Canada từ chối vì chính sách chính thức không cho phép xử lý theo cách chatbot đã nói.

**Hậu quả:**  
Khách hàng bị thiệt hại tài chính và Air Canada bị yêu cầu bồi thường. Sự cố cũng làm giảm niềm tin vào chatbot chăm sóc khách hàng, đặc biệt khi chatbot trả lời như thể thông tin là chính xác.

**Cách khắc phục:**  
Chatbot cần được liên kết chặt với nguồn chính sách chính thức, có cơ chế kiểm tra độ tin cậy của câu trả lời và chuyển các câu hỏi nhạy cảm như hoàn tiền, bảo hiểm, pháp lý hoặc khiếu nại sang nhân viên hỗ trợ. Với các câu trả lời liên quan đến chính sách, chatbot nên trích dẫn nguồn chính thức hoặc hiển thị cảnh báo yêu cầu người dùng xác nhận lại.

**AI bias/hallucination khi giải thích lỗi:**  
Khi giải thích lỗi này, AI nói rằng chatbot “có thể được huấn luyện hoặc cấu hình chưa đầy đủ về chính sách hoàn tiền”. Đây là một nguyên nhân có thể hợp lý, nhưng nguồn tham khảo chỉ xác nhận chatbot cung cấp thông tin sai và Air Canada phải chịu trách nhiệm với thông tin đó. Nguồn không chứng minh trực tiếp nguyên nhân kỹ thuật là lỗi huấn luyện, lỗi cấu hình hay lỗi cập nhật dữ liệu. Vì vậy, phần này được xem là suy diễn của AI.

---

### Defect 02 – ChatGPT tạo án lệ giả trong vụ Mata v. Avianca

**Nguồn tham khảo:** https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1:2022cv01461/575368/54/  
**Năm công bố:** 2023  
**Hệ thống:** ChatGPT được dùng để hỗ trợ nghiên cứu pháp lý  
**Tổ chức/Công ty:** Vụ kiện Mata v. Avianca  
**Loại lỗi:** LLM hallucination  
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng:** Cao

**Mô tả lỗi:**  
Một số luật sư sử dụng ChatGPT để hỗ trợ nghiên cứu pháp lý. ChatGPT đã tạo ra các án lệ và trích dẫn pháp lý không tồn tại, nhưng các thông tin đó lại được đưa vào tài liệu nộp cho tòa án.

**Hậu quả:**  
Các luật sư bị xử phạt, uy tín nghề nghiệp bị ảnh hưởng và vụ việc trở thành ví dụ nổi bật về rủi ro khi dùng AI trong lĩnh vực pháp lý mà không kiểm chứng. Nó cũng cho thấy output của LLM có thể nghe rất thuyết phục nhưng vẫn sai sự thật.

**Cách khắc phục:**  
Không sử dụng kết quả AI như nguồn pháp lý cuối cùng. Tất cả án lệ, trích dẫn và lập luận pháp lý do AI gợi ý phải được kiểm tra bằng cơ sở dữ liệu pháp lý chính thức. Công cụ AI trong lĩnh vực pháp lý cần có cơ chế citation verification, confidence warning và yêu cầu human review bắt buộc.

**AI bias/hallucination khi giải thích lỗi:**  
AI giải thích đúng rằng ChatGPT đã tạo ra các án lệ và trích dẫn pháp lý không có thật. Tuy nhiên, AI viết rằng lỗi này “có thể ảnh hưởng đến quyền lợi của các bên và quá trình xét xử”. Đây là nhận định suy rộng, vì nguồn chính tập trung vào việc luật sư nộp citation giả và bị sanction, không chứng minh trực tiếp rằng quyền lợi của các bên trong vụ kiện đã bị thay đổi.

---

### Defect 03 – Google AI Overviews đưa ra gợi ý tìm kiếm không chính xác

**Nguồn tham khảo:** https://blog.google/products-and-platforms/products/search/ai-overviews-update-may-2024/  
**Năm công bố:** 2024  
**Hệ thống:** Google Search AI Overviews  
**Tổ chức/Công ty:** Google  
**Loại lỗi:** AI hallucination / inaccurate information retrieval  
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng:** Cao

**Mô tả lỗi:**  
Google AI Overviews từng tạo ra một số câu trả lời không chính xác hoặc kỳ lạ cho truy vấn tìm kiếm. Các ví dụ lan truyền trên mạng cho thấy AI có thể tổng hợp sai hoặc hiểu sai nội dung từ web, dẫn đến thông tin không đáng tin cậy được hiển thị trực tiếp trong kết quả tìm kiếm.

**Hậu quả:**  
Người dùng có thể nhận thông tin sai ngay từ trang kết quả tìm kiếm, đặc biệt nguy hiểm nếu câu hỏi liên quan đến sức khỏe, an toàn hoặc quyết định quan trọng. Sự cố cũng gây tranh luận về độ tin cậy của AI trong công cụ tìm kiếm.

**Cách khắc phục:**  
Cần cải thiện cơ chế chọn nguồn, lọc nội dung châm biếm hoặc kém tin cậy, kiểm thử factuality trên nhiều nhóm truy vấn, bổ sung guardrail cho chủ đề nhạy cảm và cho phép người dùng kiểm tra nguồn gốc câu trả lời. Các câu trả lời AI nên ưu tiên nguồn có thẩm quyền thay vì chỉ tổng hợp nội dung phổ biến.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói rằng hệ thống “không phân biệt rõ đâu là thông tin đáng tin và đâu là nội dung đùa, châm biếm hoặc sai lệch”. Đây là cách giải thích hợp lý, nhưng nếu không gắn với từng ví dụ cụ thể thì vẫn là suy diễn. Nguồn chính thức của Google chủ yếu nói hệ thống có một số trường hợp diễn giải sai truy vấn, hiểu sai nội dung web hoặc tạo câu trả lời không phù hợp. Vì vậy, hệ thống có thể diễn giải sai nguồn, chọn nguồn chưa phù hợp hoặc thiếu kiểm thử với các truy vấn bất thường.

---

### Defect 04 – Chatbot Tessa của NEDA đưa ra lời khuyên có hại về rối loạn ăn uống

**Nguồn tham khảo:** https://www.wired.com/story/tessa-chatbot-suspended/  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** Tessa chatbot  
**Tổ chức/Công ty:** National Eating Disorders Association  
**Loại lỗi:** AI safety failure  
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Chatbot Tessa được dùng để hỗ trợ người có vấn đề liên quan đến rối loạn ăn uống. Tuy nhiên, chatbot bị báo cáo là đưa ra lời khuyên có thể gây hại, chẳng hạn liên quan đến giảm cân, cắt giảm calories hoặc kiểm soát cân nặng không phù hợp với người đang gặp rối loạn ăn uống.

**Hậu quả:**  
Người dùng dễ bị tổn thương có thể bị ảnh hưởng xấu về sức khỏe tâm lý và hành vi ăn uống. Chatbot bị tạm dừng, đồng thời sự cố làm dấy lên lo ngại về việc thay thế hoặc hỗ trợ dịch vụ sức khỏe bằng chatbot AI chưa đủ an toàn.

**Cách khắc phục:**  
Các chatbot trong lĩnh vực sức khỏe cần được kiểm thử an toàn bởi chuyên gia, có guardrail cho nội dung nguy hiểm, phát hiện dấu hiệu khủng hoảng và chuyển tiếp sang chuyên gia khi cần. Không nên để chatbot đưa lời khuyên cá nhân hóa về chế độ ăn, cân nặng hoặc điều trị nếu chưa có kiểm duyệt chuyên môn.

**AI bias/hallucination khi giải thích lỗi:**  
AI giải thích đúng rằng chatbot Tessa đưa ra lời khuyên không phù hợp trong bối cảnh rối loạn ăn uống. Tuy nhiên, AI viết khá rộng rằng chatbot sức khỏe “không nên tự đưa ra lời khuyên điều trị cá nhân”. Nguồn sự cố chủ yếu nói về lời khuyên liên quan đến ăn uống, cân nặng và kiểm soát cơ thể có thể gây hại, không chứng minh rằng mọi chatbot sức khỏe đều không nên đưa ra lời khuyên.

---

### Defect 05 – Công cụ tuyển dụng tự động của iTutorGroup bị cáo buộc phân biệt tuổi

**Nguồn tham khảo:** https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** Automated hiring / AI-powered hiring software  
**Tổ chức/Công ty:** iTutorGroup  
**Loại lỗi:** AI bias / discriminatory automated decision  
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng:** Cao

**Mô tả lỗi:**  
iTutorGroup bị EEOC kiện vì phần mềm tuyển dụng tự động bị cáo buộc đã tự động loại bỏ ứng viên lớn tuổi. Vấn đề nằm ở việc hệ thống đưa ra quyết định tuyển dụng dựa trên tiêu chí dẫn đến phân biệt tuổi.

**Hậu quả:**  
Ứng viên có thể bị loại không công bằng, công ty phải dàn xếp 365.000 USD và vụ việc trở thành ví dụ quan trọng về rủi ro pháp lý của AI/automation trong tuyển dụng.

**Cách khắc phục:**  
Hệ thống tuyển dụng tự động cần kiểm thử fairness theo độ tuổi, giới tính và các nhóm được bảo vệ bởi pháp luật. Cần có audit log, human review, giải thích quyết định, kiểm tra adverse impact và loại bỏ rule gây phân biệt đối xử.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói hệ thống có thể dùng “tuổi, ngày sinh hoặc năm tốt nghiệp” để lọc ứng viên. Nguồn EEOC nói công cụ tuyển dụng bị cáo buộc tự động loại ứng viên nữ từ 55 tuổi trở lên và nam từ 60 tuổi trở lên, nhưng không nêu rõ việc dùng “năm tốt nghiệp”. Vì vậy, phần “năm tốt nghiệp” là suy diễn thêm của AI.

---

### Defect 06 – Chatbot DPD chửi thề và chỉ trích công ty

**Nguồn tham khảo:** https://www.theguardian.com/technology/2024/jan/20/dpd-ai-chatbot-swears-calls-itself-useless-and-criticises-firm  
**Năm công bố:** 2024  
**Hệ thống/Sản phẩm:** Chatbot chăm sóc khách hàng của DPD  
**Tổ chức/Công ty:** DPD  
**Loại lỗi:** AI chatbot behavior failure / prompt manipulation  
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng:** Medium

**Mô tả lỗi:**  
Chatbot AI của DPD tạo ra phản hồi không phù hợp, bao gồm chửi thề, gọi chính nó là vô dụng và chỉ trích công ty. Sự cố được người dùng chia sẻ công khai và trở thành ví dụ về chatbot hướng khách hàng thiếu kiểm soát hành vi.

**Hậu quả:**  
DPD bị ảnh hưởng uy tín thương hiệu, người dùng mất niềm tin vào chatbot và công ty phải tắt một phần hệ thống AI để xử lý sự cố.

**Cách khắc phục:**  
Cần bổ sung guardrail về brand safety, kiểm thử prompt injection, kiểm thử phản hồi trong tình huống người dùng tức giận, kiểm duyệt nội dung đầu ra và giới hạn phạm vi trả lời của chatbot. Hệ thống cũng nên có fallback sang nhân viên khi không giải quyết được yêu cầu.

**AI bias/hallucination khi giải thích lỗi:**  
AI giải thích đúng rằng chatbot DPD đã tạo phản hồi không phù hợp. Tuy nhiên, AI suy diễn nguyên nhân là chatbot “thiếu bộ lọc nội dung an toàn” hoặc bị “prompt injection”. Nguồn báo chí cho thấy người dùng có thể dẫn dắt chatbot tạo nội dung không phù hợp, nhưng không chứng minh đầy đủ nguyên nhân kỹ thuật bên trong hệ thống.

---

### Defect 07 – Hệ thống AI drive-thru của McDonald’s nhận đơn sai

**Nguồn tham khảo:** https://apnews.com/article/mcdonalds-ai-drive-thru-ibm-bebc898363f2d550e1a0cd3c682fa234  
**Năm công bố:** 2024  
**Hệ thống/Sản phẩm:** AI-powered drive-thru ordering system  
**Tổ chức/Công ty:** McDonald’s / IBM  
**Loại lỗi:** AI speech recognition / order processing failure  
**Liên quan AI/LLM:** Có  
**Mức độ nghiêm trọng:** Medium

**Mô tả lỗi:**  
McDonald’s kết thúc thử nghiệm hệ thống AI nhận đơn tại drive-thru do các vấn đề về độ chính xác đơn hàng. Hệ thống có thể hiểu sai lời nói, món ăn, yêu cầu thay đổi hoặc bối cảnh nhiều tiếng ồn.

**Hậu quả:**  
Đơn hàng sai làm giảm trải nghiệm khách hàng, tăng thời gian xử lý, tạo thêm việc cho nhân viên và làm giảm niềm tin vào tự động hóa bằng giọng nói trong môi trường thực tế.

**Cách khắc phục:**  
Cần kiểm thử voice AI với nhiều giọng địa phương, tiếng ồn, trẻ em nói, nhiều người nói cùng lúc, thay đổi đơn giữa chừng và các order phức tạp. Hệ thống cần xác nhận lại đơn trước khi gửi, có confidence threshold và chuyển sang nhân viên khi không chắc chắn.

**AI bias/hallucination khi giải thích lỗi:**  
AI nêu các nguyên nhân như tiếng ồn, gió, nhiều giọng nói và menu phức tạp. Đây là các nguyên nhân hợp lý đối với hệ thống voice AI trong môi trường drive-thru, nhưng nguồn AP chủ yếu nói McDonald’s kết thúc thử nghiệm sau các vấn đề về độ chính xác đơn hàng, không chứng minh chi tiết từng nguyên nhân kỹ thuật đó.

---

### Defect 08 – Bản cập nhật CrowdStrike Falcon làm Windows crash diện rộng

**Nguồn tham khảo:** https://www.crowdstrike.com/en-us/blog/falcon-content-update-preliminary-post-incident-report/  
**Năm công bố:** 2024  
**Hệ thống/Sản phẩm:** CrowdStrike Falcon Sensor  
**Tổ chức/Công ty:** CrowdStrike  
**Loại lỗi:** Faulty content update / reliability defect  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Một bản cập nhật nội dung Rapid Response Content của CrowdStrike Falcon gây lỗi crash trên các máy Windows bị ảnh hưởng. Do Falcon là phần mềm bảo mật endpoint được triển khai rộng, lỗi nhanh chóng gây gián đoạn quy mô lớn.

**Hậu quả:**  
Nhiều doanh nghiệp, sân bay, bệnh viện, ngân hàng và dịch vụ công bị gián đoạn. Người dùng không thể sử dụng máy Windows bình thường, gây thiệt hại vận hành nghiêm trọng.

**Cách khắc phục:**  
Cần tăng cường validation trước phát hành, canary deployment, staged rollout, rollback nhanh, kiểm thử tương thích trên môi trường giống production và bổ sung cơ chế phát hiện lỗi sau triển khai.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói bản cập nhật “có thể chứa dữ liệu hoặc cấu hình không hợp lệ”. Nhận định này gần với bản chất sự cố, nhưng vẫn chưa đủ chính xác. Nguồn CrowdStrike mô tả sự cố liên quan đến content update và Channel File 291, không chỉ là “cấu hình” chung chung.

---

### Defect 09 – Sự cố mạng diện rộng của AT&T do lỗi thay đổi cấu hình

**Nguồn tham khảo:** https://docs.fcc.gov/public/attachments/DOC-404150A1.pdf  
**Năm công bố:** 2024  
**Hệ thống/Sản phẩm:** Mạng không dây AT&T  
**Tổ chức/Công ty:** AT&T  
**Loại lỗi:** Configuration error / network reliability failure  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
AT&T gặp sự cố mạng diện rộng làm gián đoạn dịch vụ thoại và dữ liệu. Báo cáo của FCC liên hệ sự cố với lỗi cấu hình thiết bị trong quá trình thay đổi mạng.

**Hậu quả:**  
Người dùng bị mất dịch vụ, nhiều cuộc gọi bị chặn và một số cuộc gọi khẩn cấp 911 bị ảnh hưởng. Sự cố cho thấy rủi ro lớn của thay đổi cấu hình production trên hạ tầng viễn thông.

**Cách khắc phục:**  
Cần cải thiện quy trình change management, kiểm thử cấu hình trước triển khai, rollout theo vùng, giám sát real-time, rollback nhanh và đánh giá rủi ro với dịch vụ khẩn cấp trước khi thay đổi mạng.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói sự cố làm khách hàng không thể “gọi điện, nhắn tin hoặc sử dụng dữ liệu di động”. Nguồn FCC tập trung vào ảnh hưởng tới voice, data và các cuộc gọi 911; phần “nhắn tin” không phải điểm chính được nguồn nhấn mạnh. Đây là suy diễn mở rộng từ outage di động nói chung.

---

### Defect 10 – Sự cố FAA NOTAM làm gián đoạn các chuyến bay tại Mỹ

**Nguồn tham khảo:** https://www.faa.gov/newsroom/faa-notam-statement  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** FAA NOTAM system  
**Tổ chức/Công ty:** Federal Aviation Administration  
**Loại lỗi:** Data/database reliability failure  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Hệ thống NOTAM của FAA gặp sự cố, làm ảnh hưởng đến việc cung cấp thông báo an toàn bay cho phi công và dẫn đến việc tạm dừng nhiều chuyến bay nội địa tại Mỹ.

**Hậu quả:**  
Hàng nghìn chuyến bay bị trì hoãn hoặc hủy, gây ảnh hưởng lớn đến hành khách, hãng hàng không và hệ thống giao thông hàng không quốc gia.

**Cách khắc phục:**  
Hệ thống trọng yếu cần kiểm thử backup/restore, failover, disaster recovery, data integrity và monitoring. Cần có kiến trúc dự phòng tốt hơn để một lỗi dữ liệu không làm gián đoạn toàn bộ hệ thống.

**AI bias/hallucination khi giải thích lỗi:**  
AI nêu rằng “hệ thống dự phòng không hoạt động tốt” có thể là nguyên nhân. Nguồn FAA ban đầu nói outage được truy vết đến damaged database file và không có bằng chứng cyberattack, nhưng không kết luận chi tiết rằng hệ thống dự phòng không hoạt động tốt.

---

### Defect 11 – Toyota dừng nhà máy do lỗi hệ thống đặt linh kiện

**Nguồn tham khảo:** https://global.toyota/en/newsroom/corporate/39732568.html  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** Hệ thống xử lý đặt linh kiện / production order system  
**Tổ chức/Công ty:** Toyota  
**Loại lỗi:** Availability failure / storage capacity issue  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Cao

**Mô tả lỗi:**  
Toyota tạm dừng sản xuất tại nhiều nhà máy ở Nhật Bản do hệ thống xử lý đặt linh kiện bị sự cố. Toyota cho biết sự cố liên quan đến việc một số server xử lý parts orders không khả dụng và lỗi phát sinh sau quá trình bảo trì dữ liệu.

**Hậu quả:**  
Hoạt động sản xuất bị gián đoạn, ảnh hưởng đến dây chuyền cung ứng, sản lượng và kế hoạch kinh doanh.

**Cách khắc phục:**  
Cần kiểm thử maintenance procedure, kiểm tra dung lượng đĩa trước khi chạy tác vụ dữ liệu, thiết kế HA/failover cho hệ thống đặt linh kiện và giám sát dung lượng/cảnh báo sớm.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói nguyên nhân có thể là “lỗi máy chủ, lỗi xử lý dữ liệu hoặc vấn đề tài nguyên hệ thống”. Cách giải thích này đúng hướng nhưng còn quá chung. Nguồn Toyota cụ thể hơn: sự cố liên quan đến một số server xử lý đặt hàng linh kiện không khả dụng và có yếu tố thiếu dung lượng lưu trữ sau bảo trì.

---

### Defect 12 – Lỗ hổng SQL Injection trong MOVEit Transfer

**Nguồn tham khảo:** https://nvd.nist.gov/vuln/detail/CVE-2023-34362  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** MOVEit Transfer  
**Tổ chức/Công ty:** Progress Software  
**Loại lỗi:** SQL Injection vulnerability  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
MOVEit Transfer có lỗ hổng SQL Injection cho phép attacker chưa xác thực có thể truy cập cơ sở dữ liệu của ứng dụng trong các phiên bản bị ảnh hưởng.

**Hậu quả:**  
Lỗ hổng bị khai thác rộng rãi, dẫn đến rò rỉ dữ liệu tại nhiều tổ chức. Đây là ví dụ nghiêm trọng về lỗi input validation và query handling trong phần mềm truyền file nhạy cảm.

**Cách khắc phục:**  
Cần cập nhật bản vá của nhà cung cấp, sử dụng parameterized queries, kiểm thử SQL Injection, security code review, WAF rule tạm thời và giám sát dấu hiệu truy cập bất thường.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói attacker có thể “truy cập hoặc thao túng cơ sở dữ liệu”. Với SQL injection, điều này có thể đúng về mặt kỹ thuật, nhưng nguồn NVD mô tả chính là SQL injection có thể cho phép attacker chưa xác thực truy cập database MOVEit. Phần “thao túng” cần được viết thận trọng nếu nguồn không nêu rõ.

---

### Defect 13 – Backdoor trong XZ Utils gây rủi ro chuỗi cung ứng phần mềm

**Nguồn tham khảo:** https://www.cisa.gov/news-events/alerts/2024/03/29/reported-supply-chain-compromise-affecting-xz-utils-data-compression-library-cve-2024-3094  
**Năm công bố:** 2024  
**Hệ thống/Sản phẩm:** XZ Utils  
**Tổ chức/Công ty:** Open-source software ecosystem  
**Loại lỗi:** Supply-chain compromise / malicious backdoor  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Mã độc/backdoor được phát hiện trong XZ Utils phiên bản 5.6.0 và 5.6.1. Vì XZ Utils là thành phần mã nguồn mở có thể được dùng trong nhiều hệ thống Linux, sự cố tạo rủi ro nghiêm trọng cho chuỗi cung ứng phần mềm.

**Hậu quả:**  
Nếu được triển khai rộng, backdoor có thể tạo điều kiện cho truy cập trái phép vào hệ thống. Sự cố làm tăng lo ngại về bảo mật mã nguồn mở và quy trình review dependency.

**Cách khắc phục:**  
Cần downgrade hoặc cập nhật sang phiên bản an toàn theo khuyến cáo, kiểm tra hệ thống bị ảnh hưởng, xác minh integrity của dependency, dùng reproducible builds, review code độc lập và giám sát bất thường trong dự án mã nguồn mở.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói mã độc được đưa vào “thông qua contributor mới hoặc quá trình phát hành”. Đây là suy diễn thêm nếu chỉ dựa trên nguồn CISA, vì CISA chủ yếu xác nhận có mã độc trong XZ Utils 5.6.0 và 5.6.1, không trình bày đầy đủ chi tiết về contributor hay toàn bộ quá trình tấn công. Kết luận hợp lý hơn là mã độc xuất hiện trong các phiên bản phát hành bị ảnh hưởng, còn cách đưa mã độc vào cần nguồn điều tra cụ thể hơn.

---

### Defect 14 – Sự cố Optus sau bản nâng cấp phần mềm định kỳ

**Nguồn tham khảo:** https://www.abc.net.au/news/2023-11-13/optus-identifies-cause-of-nationwide-outage-software-upgrade/103099902  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** Hạ tầng mạng Optus  
**Tổ chức/Công ty:** Optus  
**Loại lỗi:** Network outage / routing change failure  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Optus gặp sự cố mạng toàn quốc sau một bản nâng cấp phần mềm định kỳ. Vấn đề liên quan đến thay đổi routing information sau upgrade, làm nhiều dịch vụ bị gián đoạn.

**Hậu quả:**  
Hàng triệu khách hàng bị ảnh hưởng, bao gồm cá nhân, doanh nghiệp và một số dịch vụ khẩn cấp. Sự cố cho thấy rủi ro của thay đổi mạng quy mô lớn nếu không có rollback và kiểm thử đầy đủ.

**Cách khắc phục:**  
Cần simulation testing trước khi nâng cấp, staged rollout, giám sát real-time, rollback procedure, kiểm thử route propagation và đánh giá tác động lên dịch vụ khẩn cấp.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói thiết bị mạng có thể “nhận quá nhiều hoặc nhận thông tin định tuyến không phù hợp”. Đây là một giải thích kỹ thuật hợp lý, nhưng đi sâu hơn mức nguồn cung cấp. Nguồn về sự cố Optus mô tả nguyên nhân liên quan đến thay đổi routing information sau software upgrade.

---

### Defect 15 – Sự cố Cloudflare do lỗi feature file trong Bot Management

**Nguồn tham khảo:** https://blog.cloudflare.com/18-november-2025-outage/  
**Năm công bố:** 2025  
**Hệ thống/Sản phẩm:** Cloudflare services / Bot Management  
**Tổ chức/Công ty:** Cloudflare  
**Loại lỗi:** Configuration generation defect / reliability failure  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Cao

**Mô tả lỗi:**  
Cloudflare gặp sự cố dịch vụ vào ngày 18/11/2025. Theo postmortem của Cloudflare, sự cố bắt nguồn từ thay đổi permission trong hệ thống database, làm feature file dùng bởi Bot Management có nhiều entry hơn dự kiến và tăng kích thước, sau đó lan ra toàn mạng.

**Hậu quả:**  
Một số dịch vụ và website phụ thuộc vào Cloudflare bị ảnh hưởng. Sự cố làm nổi bật rủi ro khi một file cấu hình được sinh tự động có thể ảnh hưởng đến hạ tầng quy mô lớn.

**Cách khắc phục:**  
Cần kiểm thử boundary cho file cấu hình, giới hạn kích thước, validation trước khi phân phối, rollout từng bước, rollback tự động và monitoring cho dữ liệu cấu hình bất thường.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói người dùng có thể gặp “website chậm hoặc không hoạt động”. Phần “không hoạt động” phù hợp với sự cố Cloudflare, nhưng “website chậm” là suy diễn thêm nếu nguồn không xác nhận trực tiếp. Ngoài ra, AI mô tả nguyên nhân chung là “feature file vượt giới hạn”, trong khi nguồn chính thức giải thích cụ thể hơn rằng file tăng lớn hơn dự kiến và vượt giới hạn kích thước. Kết luận hợp lý hơn là AI đã đơn giản hóa nguyên nhân kỹ thuật và thêm biểu hiện phía người dùng chưa được xác nhận rõ.

---

### Defect 16 – Lỗ hổng OGNL Injection trong Atlassian Confluence

**Nguồn tham khảo:** https://nvd.nist.gov/vuln/detail/CVE-2022-26134  
**Năm công bố:** 2022  
**Hệ thống/Sản phẩm:** Atlassian Confluence Server/Data Center  
**Tổ chức/Công ty:** Atlassian  
**Loại lỗi:** OGNL Injection / Remote Code Execution  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Atlassian Confluence có lỗ hổng OGNL Injection cho phép attacker chưa xác thực thực thi mã tùy ý trên Confluence Server hoặc Data Center bị ảnh hưởng.

**Hậu quả:**  
Máy chủ Confluence có thể bị chiếm quyền, dữ liệu nội bộ bị đánh cắp, bị cài malware hoặc trở thành điểm vào cho tấn công hệ thống doanh nghiệp.

**Cách khắc phục:**  
Cần cập nhật phiên bản đã vá, hạn chế truy cập internet vào Confluence, dùng WAF rule tạm thời, kiểm tra dấu hiệu compromise và thực hiện security review sau khi vá.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói attacker có thể “sửa đổi tài liệu, cài mã độc hoặc dùng máy chủ làm điểm tấn công tiếp theo”. Đây là các hậu quả có thể xảy ra khi RCE bị khai thác, nhưng nguồn NVD chỉ mô tả khả năng thực thi arbitrary code từ xa, không xác nhận các hậu quả cụ thể này trong từng vụ khai thác.

---

### Defect 17 – Lỗ hổng Spring4Shell trong Spring Framework

**Nguồn tham khảo:** https://nvd.nist.gov/vuln/detail/CVE-2022-22965  
**Năm công bố:** 2022  
**Hệ thống/Sản phẩm:** Spring Framework  
**Tổ chức/Công ty:** VMware / Spring  
**Loại lỗi:** Remote Code Execution via data binding  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Spring Framework có lỗ hổng RCE liên quan đến data binding trong một số điều kiện triển khai nhất định, đặc biệt với Spring MVC/WebFlux chạy trên JDK 9+ và cấu hình phù hợp để khai thác.

**Hậu quả:**  
Ứng dụng web bị ảnh hưởng có thể bị attacker thực thi mã từ xa, dẫn đến chiếm quyền máy chủ hoặc rò rỉ dữ liệu.

**Cách khắc phục:**  
Cần cập nhật Spring Framework/Spring Boot lên phiên bản đã vá, kiểm tra cấu hình triển khai, giảm bề mặt tấn công, dùng WAF rule tạm thời và dependency scanning trong CI/CD.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói attacker có thể “cài web shell, đánh cắp dữ liệu, thay đổi dữ liệu”. Đây là hậu quả khả dĩ của một lỗ hổng RCE, nhưng nguồn NVD chủ yếu mô tả điều kiện và bản chất lỗ hổng data binding dẫn đến RCE. AI đang mở rộng hậu quả theo kiến thức chung.

---

### Defect 18 – Lỗ hổng Text4Shell trong Apache Commons Text

**Nguồn tham khảo:** https://nvd.nist.gov/vuln/detail/CVE-2022-42889  
**Năm công bố:** 2022  
**Hệ thống/Sản phẩm:** Apache Commons Text  
**Tổ chức/Công ty:** Apache Software Foundation  
**Loại lỗi:** Unsafe interpolation / potential code execution or remote contact  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Cao

**Mô tả lỗi:**  
Apache Commons Text có lỗ hổng liên quan đến variable interpolation. Một số lookup mặc định trong các phiên bản bị ảnh hưởng có thể dẫn đến hành vi nguy hiểm như liên hệ server từ xa hoặc thực thi mã tùy theo cách ứng dụng sử dụng thư viện.

**Hậu quả:**  
Ứng dụng dùng thư viện theo cách không an toàn có thể bị khai thác, ảnh hưởng đến bảo mật hệ thống hoặc gây rò rỉ thông tin.

**Cách khắc phục:**  
Cần nâng cấp Apache Commons Text lên phiên bản an toàn, tránh xử lý input không tin cậy bằng interpolation nguy hiểm, kiểm thử injection, dependency scanning và review code dùng thư viện.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói Text4Shell có thể làm “lộ thông tin” hoặc “thực thi mã”. Phần “thực thi mã” phù hợp với NVD trong một số điều kiện, nhưng “lộ thông tin” là suy diễn thêm và không phải trọng tâm chính của CVE.

---

### Defect 19 – Lỗ hổng Cisco IOS XE Web UI

**Nguồn tham khảo:** https://www.cisa.gov/guidance-addressing-cisco-ios-xe-web-ui-vulnerabilities  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** Cisco IOS XE Web UI  
**Tổ chức/Công ty:** Cisco  
**Loại lỗi:** Privilege escalation / exploited zero-day  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Cisco IOS XE Web UI có lỗ hổng cho phép attacker leo thang đặc quyền trên thiết bị bị ảnh hưởng. CISA cảnh báo về việc khai thác active/widespread đối với các lỗ hổng liên quan Web UI.

**Hậu quả:**  
Thiết bị mạng có thể bị chiếm quyền, attacker có thể tạo user cục bộ, thay đổi cấu hình, duy trì truy cập và ảnh hưởng đến hạ tầng mạng của tổ chức.

**Cách khắc phục:**  
Cần cập nhật bản vá, tắt Web UI nếu không cần thiết, không expose giao diện quản trị ra internet, kiểm tra user lạ, rà soát cấu hình và theo dõi dấu hiệu compromise.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói attacker có thể “theo dõi lưu lượng” sau khi chiếm quyền thiết bị. Đây là suy diễn hậu quả, vì nguồn CISA/NVD chủ yếu xác nhận lỗ hổng privilege escalation và khả năng attacker đạt quyền cao trên thiết bị, không mô tả trực tiếp việc theo dõi lưu lượng. Kết luận hợp lý hơn là lỗ hổng tạo nguy cơ attacker kiểm soát thiết bị ở mức cao và ảnh hưởng đến cấu hình hoặc hoạt động của thiết bị mạng.

---

### Defect 20 – Lỗ hổng CitrixBleed làm rò rỉ thông tin nhạy cảm

**Nguồn tham khảo:** https://nvd.nist.gov/vuln/detail/CVE-2023-4966  
**Năm công bố:** 2023  
**Hệ thống/Sản phẩm:** Citrix NetScaler ADC / NetScaler Gateway  
**Tổ chức/Công ty:** Citrix  
**Loại lỗi:** Sensitive information disclosure  
**Liên quan AI/LLM:** Không  
**Mức độ nghiêm trọng:** Critical

**Mô tả lỗi:**  
Citrix NetScaler ADC và NetScaler Gateway có lỗ hổng rò rỉ thông tin nhạy cảm khi cấu hình làm Gateway hoặc AAA virtual server. Lỗi này thường được gọi là CitrixBleed.

**Hậu quả:**  
Thông tin nhạy cảm, bao gồm dữ liệu liên quan phiên đăng nhập, có thể bị lộ. Attacker có thể lợi dụng để chiếm phiên hoặc truy cập trái phép vào hệ thống được bảo vệ.

**Cách khắc phục:**  
Cần cập nhật bản vá của Citrix, reset hoặc thu hồi session/token có nguy cơ bị lộ, kiểm tra log truy cập, giám sát hành vi bất thường và đảm bảo Gateway/AAA không còn chạy phiên bản bị ảnh hưởng.

**AI bias/hallucination khi giải thích lỗi:**  
AI nói attacker có thể “đi sâu vào mạng nội bộ”. Đây là suy rộng từ việc lỗ hổng có thể làm lộ session token hoặc thông tin nhạy cảm qua Citrix NetScaler ADC/Gateway. Nguồn NVD xác nhận đây là lỗi sensitive information disclosure, nhưng không mô tả cụ thể việc attacker di chuyển sâu trong mạng. Kết luận phù hợp hơn là lỗ hổng có thể làm lộ thông tin nhạy cảm/session token và tạo nguy cơ truy cập trái phép.
