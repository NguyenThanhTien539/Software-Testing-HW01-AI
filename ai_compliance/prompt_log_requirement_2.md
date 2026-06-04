# Prompt R2-01 – Defect 01–05

**Thời gian:** 14:20 03/06/2026
**Công cụ:** ChatGPT  
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026  
**Defects covered:** Defect 01–05

## Prompt

Giải thích 5 lỗi phần mềm sau bằng ngôn ngữ đơn giản. Với mỗi lỗi, hãy bao gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng và giải pháp khả thi. Không duyệt web. Chỉ trả lời dựa trên kiến thức của bạn.

1. Chatbot của Air Canada cung cấp thông tin sai về việc hoàn tiền vé tang chế.

2. ChatGPT tạo ra các trích dẫn pháp lý giả trong vụ Mata v. Avianca.

3. Google AI Overviews đưa ra các gợi ý tìm kiếm không chính xác hoặc kỳ lạ.

4. Chatbot Tessa của NEDA đưa ra lời khuyên có hại liên quan đến rối loạn ăn uống.

5. Công cụ tuyển dụng AI của iTutorGroup bị cáo buộc phân biệt đối xử với ứng viên lớn tuổi.

Sau khi giải thích từng lỗi, hãy nêu thêm loại kiểm thử nào có thể đã phát hiện lỗi hoặc giảm rủi ro.

## AI Output

## 1. Chatbot của Air Canada cung cấp thông tin sai về hoàn tiền vé tang chế

**Chuyện gì đã xảy ra:**
Một khách hàng hỏi chatbot của Air Canada về chính sách hoàn tiền vé tang chế. Chatbot đã đưa ra thông tin sai, làm khách hàng hiểu rằng họ có thể mua vé trước rồi xin hoàn tiền sau. Sau đó, Air Canada không chấp nhận theo thông tin chatbot đã nói.

**Nguyên nhân có thể:**
Chatbot có thể được huấn luyện hoặc cấu hình chưa đầy đủ về chính sách hoàn tiền. Hệ thống cũng có thể thiếu cơ chế kiểm tra câu trả lời trước khi đưa cho khách hàng, đặc biệt với các vấn đề liên quan đến tiền bạc và chính sách pháp lý.

**Hậu quả:**
Khách hàng bị thiệt hại tài chính và mất niềm tin vào công ty. Công ty cũng bị ảnh hưởng uy tín vì chatbot đại diện cho dịch vụ khách hàng nhưng lại cung cấp thông tin sai.

**Mức độ nghiêm trọng:**
Cao, vì lỗi ảnh hưởng trực tiếp đến quyền lợi tài chính của khách hàng và có thể dẫn đến tranh chấp pháp lý.

**Giải pháp khả thi:**
Chatbot cần được kết nối với nguồn chính sách chính thức, luôn cập nhật. Với các trường hợp nhạy cảm như hoàn tiền, vé, bảo hiểm hoặc pháp lý, chatbot nên hiển thị cảnh báo và chuyển khách hàng đến nhân viên hỗ trợ thật.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- Kiểm thử nghiệp vụ với các chính sách hoàn tiền thực tế.
- Kiểm thử dữ liệu đầu ra của chatbot.
- Kiểm thử tình huống biên, ví dụ khách hỏi về vé tang chế, hoàn tiền sau khi mua vé, hoặc chính sách ngoại lệ.
- Human review testing cho các câu trả lời liên quan đến tiền và quyền lợi khách hàng.

---

## 2. ChatGPT tạo trích dẫn pháp lý giả trong vụ Mata v. Avianca

**Chuyện gì đã xảy ra:**
Luật sư sử dụng ChatGPT để hỗ trợ nghiên cứu pháp lý. ChatGPT đã tạo ra các án lệ và trích dẫn pháp lý không có thật. Những thông tin này sau đó được đưa vào tài liệu nộp cho tòa án.

**Nguyên nhân có thể:**
Mô hình ngôn ngữ có thể “hallucinate”, tức là tạo ra câu trả lời nghe có vẻ hợp lý nhưng không đúng sự thật. ChatGPT không phải cơ sở dữ liệu pháp lý chính thức, nên nếu không kiểm chứng lại, người dùng có thể dùng nhầm thông tin giả.

**Hậu quả:**
Tài liệu pháp lý bị sai nghiêm trọng. Luật sư bị tòa án xử phạt, uy tín nghề nghiệp bị ảnh hưởng. Vụ việc cũng cho thấy rủi ro lớn khi dùng AI trong lĩnh vực yêu cầu độ chính xác cao.

**Mức độ nghiêm trọng:**
Rất cao, vì lỗi xảy ra trong lĩnh vực pháp lý, nơi thông tin sai có thể ảnh hưởng đến quyền lợi của các bên và quá trình xét xử.

**Giải pháp khả thi:**
AI chỉ nên dùng để hỗ trợ tìm ý tưởng ban đầu, không được dùng làm nguồn pháp lý cuối cùng. Mọi án lệ, điều luật và trích dẫn phải được kiểm chứng bằng cơ sở dữ liệu pháp lý chính thức trước khi sử dụng.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- Fact-checking testing: kiểm tra từng trích dẫn mà AI tạo ra.
- Domain expert review: luật sư hoặc chuyên gia pháp lý phải xác minh kết quả.
- Kiểm thử hallucination bằng cách yêu cầu AI trả lời các câu hỏi pháp lý và đối chiếu với nguồn chính thức.
- Kiểm thử giới hạn sử dụng, đảm bảo hệ thống cảnh báo rằng AI có thể tạo thông tin sai.

---

## 3. Google AI Overviews đưa ra câu trả lời không chính xác hoặc kỳ lạ

**Chuyện gì đã xảy ra:**
Google AI Overviews từng đưa ra một số câu trả lời tìm kiếm không chính xác hoặc kỳ lạ. Người dùng thấy AI tóm tắt thông tin sai, gây hiểu nhầm hoặc tạo cảm giác thiếu đáng tin cậy.

**Nguyên nhân có thể:**
Hệ thống AI có thể lấy thông tin từ nguồn không phù hợp, hiểu sai ngữ cảnh, hoặc tóm tắt nội dung trên web mà không phân biệt rõ đâu là thông tin đáng tin và đâu là nội dung đùa, châm biếm hoặc sai lệch.

**Hậu quả:**
Người dùng có thể tin vào câu trả lời sai và làm theo hướng dẫn không đúng. Uy tín của công cụ tìm kiếm cũng bị ảnh hưởng vì người dùng kỳ vọng kết quả tìm kiếm phải chính xác.

**Mức độ nghiêm trọng:**
Trung bình đến cao, tùy nội dung sai. Nếu câu trả lời sai liên quan đến sức khỏe, an toàn, tài chính hoặc pháp luật thì mức độ nghiêm trọng rất cao.

**Giải pháp khả thi:**
Hệ thống cần ưu tiên nguồn đáng tin cậy, tránh dùng nội dung châm biếm hoặc nguồn chất lượng thấp. Với các chủ đề nhạy cảm, AI nên hạn chế trả lời trực tiếp hoặc yêu cầu người dùng tham khảo chuyên gia.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- Kiểm thử chất lượng câu trả lời trên nhiều loại truy vấn khác nhau.
- Kiểm thử nguồn dữ liệu, xem AI lấy thông tin từ nguồn nào.
- Red team testing: cố tình hỏi các câu dễ gây sai lệch để phát hiện lỗi.
- Kiểm thử an toàn nội dung, đặc biệt với y tế, pháp luật, tài chính và an toàn cá nhân.

---

## 4. Chatbot Tessa của NEDA đưa ra lời khuyên có hại về rối loạn ăn uống

**Chuyện gì đã xảy ra:**
Chatbot Tessa được dùng để hỗ trợ người có vấn đề liên quan đến rối loạn ăn uống. Tuy nhiên, chatbot bị cho là đã đưa ra lời khuyên không phù hợp, ví dụ các lời khuyên có thể làm tình trạng ăn uống hoặc hình ảnh cơ thể của người dùng xấu hơn.

**Nguyên nhân có thể:**
Chatbot có thể chưa được kiểm thử đủ trong bối cảnh sức khỏe tâm thần. Hệ thống có thể đưa ra lời khuyên chung chung về ăn uống, cân nặng hoặc kiểm soát cơ thể mà không hiểu được mức độ nhạy cảm của người dùng mắc rối loạn ăn uống.

**Hậu quả:**
Người dùng dễ bị tổn thương có thể nhận được lời khuyên gây hại. Tổ chức vận hành chatbot bị ảnh hưởng uy tín, và hệ thống phải bị tạm dừng hoặc xem xét lại.

**Mức độ nghiêm trọng:**
Rất cao, vì lỗi liên quan đến sức khỏe tâm thần và có thể ảnh hưởng trực tiếp đến sự an toàn của người dùng.

**Giải pháp khả thi:**
Chatbot trong lĩnh vực sức khỏe cần có giới hạn rất rõ. Nó không nên tự đưa ra lời khuyên điều trị cá nhân. Các câu trả lời phải được chuyên gia y tế kiểm duyệt, và khi phát hiện tình huống rủi ro, hệ thống phải chuyển người dùng đến chuyên gia hoặc đường dây hỗ trợ.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- Safety testing cho nội dung sức khỏe tâm thần.
- Clinical expert review bởi chuyên gia rối loạn ăn uống.
- Kiểm thử tình huống rủi ro cao, ví dụ người dùng hỏi về giảm cân cực đoan, nhịn ăn, mặc cảm cơ thể.
- User acceptance testing với nhóm chuyên gia, không chỉ với người dùng phổ thông.

---

## 5. Công cụ tuyển dụng AI của iTutorGroup bị cáo buộc phân biệt tuổi

**Chuyện gì đã xảy ra:**
Công cụ tuyển dụng tự động của iTutorGroup bị cáo buộc đã loại bỏ một số ứng viên lớn tuổi dựa trên tuổi hoặc năm sinh. Điều này làm dấy lên lo ngại rằng AI trong tuyển dụng có thể phân biệt đối xử.

**Nguyên nhân có thể:**
Hệ thống có thể sử dụng tuổi, ngày sinh hoặc năm tốt nghiệp làm tiêu chí lọc ứng viên. Ngoài ra, dữ liệu huấn luyện trước đó có thể chứa thiên lệch, khiến AI học lại các mẫu phân biệt đối xử trong quá trình tuyển dụng.

**Hậu quả:**
Ứng viên lớn tuổi có thể bị mất cơ hội việc làm không công bằng. Công ty có thể bị kiện, bị phạt, mất uy tín và phải thay đổi quy trình tuyển dụng.

**Mức độ nghiêm trọng:**
Cao, vì lỗi liên quan đến phân biệt đối xử trong tuyển dụng, ảnh hưởng trực tiếp đến quyền lợi việc làm của con người.

**Giải pháp khả thi:**
Công cụ tuyển dụng AI cần loại bỏ hoặc hạn chế sử dụng các thuộc tính nhạy cảm như tuổi, giới tính, chủng tộc. Công ty cần kiểm tra định kỳ xem hệ thống có đối xử bất công với nhóm ứng viên nào không. Quyết định tuyển dụng quan trọng cũng nên có con người xem xét lại.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- Bias testing: kiểm tra xem hệ thống có thiên vị theo tuổi, giới tính hoặc nhóm xã hội không.
- Fairness testing: so sánh tỷ lệ được chọn giữa các nhóm ứng viên khác nhau.
- Kiểm thử dữ liệu đầu vào, đảm bảo thuộc tính nhạy cảm không bị dùng sai mục đích.
- Audit testing bởi bên thứ ba để đánh giá tính công bằng của hệ thống AI.

## Student verification – Prompt R2-01

### Defect 01 – Air Canada chatbot

AI giải thích đúng ý chính rằng chatbot đã cung cấp thông tin sai về hoàn tiền vé tang chế. Tuy nhiên, AI suy diễn rằng chatbot “có thể được huấn luyện hoặc cấu hình chưa đầy đủ”, trong khi nguồn tham khảo chỉ xác nhận chatbot đưa thông tin sai và Air Canada phải chịu trách nhiệm, không chứng minh trực tiếp nguyên nhân kỹ thuật là lỗi training hay cấu hình. Vì vậy, trong report chính tôi chỉ ghi đây là “nguyên nhân có thể”, không khẳng định chắc chắn.  
**Source used to verify:** https://www.theguardian.com/world/2024/feb/16/air-canada-chatbot-lawsuit

### Defect 02 – Mata v. Avianca

AI giải thích đúng rằng ChatGPT đã tạo trích dẫn pháp lý giả. Tuy nhiên, AI viết rằng lỗi này “có thể ảnh hưởng đến quyền lợi của các bên và quá trình xét xử”. Đây là nhận định suy rộng, vì nguồn chính tập trung vào việc các luật sư nộp citation giả và bị sanction, không chứng minh trực tiếp rằng quyền lợi của các bên trong vụ kiện đã bị thay đổi. Vì vậy, trong report chính tôi ghi hậu quả cụ thể hơn: luật sư bị xử phạt, uy tín nghề nghiệp bị ảnh hưởng và rủi ro dùng AI trong bối cảnh pháp lý.  
**Source used to verify:** https://law.justia.com/cases/federal/district-courts/new-york/nysdce/1%3A2022cv01461/575368/54/

### Defect 03 – Google AI Overviews

AI nói hệ thống “không phân biệt rõ đâu là nội dung đáng tin và đâu là nội dung đùa, châm biếm hoặc sai lệch”. Đây là một cách giải thích hợp lý nhưng vẫn là suy diễn nếu không gắn trực tiếp với nguồn cụ thể cho từng ví dụ. Nguồn chính thức của Google nói hệ thống có một số trường hợp diễn giải sai truy vấn, hiểu sai nội dung web hoặc tạo câu trả lời không phù hợp. Vì vậy, trong report chính tôi viết thận trọng hơn: hệ thống có thể diễn giải sai nguồn, chọn nguồn chưa phù hợp hoặc thiếu kiểm thử với truy vấn bất thường.  
**Source used to verify:** https://blog.google/products-and-platforms/products/search/ai-overviews-update-may-2024/

### Defect 04 – NEDA Tessa chatbot

AI giải thích đúng rằng chatbot đưa lời khuyên không phù hợp trong bối cảnh rối loạn ăn uống. Tuy nhiên, AI viết khá rộng rằng chatbot sức khỏe “không nên tự đưa ra lời khuyên điều trị cá nhân”. Nguồn sự cố chủ yếu nói về lời khuyên liên quan đến ăn uống, cân nặng và kiểm soát cơ thể có thể gây hại, không chứng minh rằng mọi chatbot sức khỏe đều không nên đưa lời khuyên. Vì vậy, trong report chính tôi tập trung vào harmful advice, thiếu guardrail và nhu cầu escalation trong bối cảnh sức khỏe nhạy cảm.  
**Source used to verify:** https://www.wired.com/story/tessa-chatbot-suspended/

### Defect 05 – iTutorGroup AI hiring Công cụ

AI nói hệ thống có thể dùng “tuổi, ngày sinh hoặc năm tốt nghiệp” để lọc ứng viên. Nguồn EEOC nói công cụ tuyển dụng bị cáo buộc tự động loại ứng viên nữ từ 55 tuổi trở lên và nam từ 60 tuổi trở lên, nhưng không nêu rõ việc dùng “năm tốt nghiệp”. Phần “năm tốt nghiệp” là suy diễn thêm của AI, nên trong report chính tôi không khẳng định chi tiết này nếu không có nguồn.  
**Source used to verify:** https://www.eeoc.gov/newsroom/itutorgroup-pay-365000-settle-eeoc-discriminatory-hiring-suit

---

# Prompt R2-02 – Defect 06–10

**Thời gian:** 14:35 03/06/2026
**Công cụ:** ChatGPT  
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026  
**Defects covered:** Defect 06–10

## Prompt

Giải thích 5 lỗi phần mềm hoặc sự cố liên quan đến phần mềm sau bằng ngôn ngữ đơn giản.
Với mỗi lỗi, hãy bao gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng và giải pháp khả thi.
Không duyệt web. Chỉ trả lời dựa trên kiến thức của bạn.

6. Chatbot AI của DPD đã chửi thề, tự gọi mình là vô dụng và chỉ trích công ty.

7. McDonald’s đã kết thúc thử nghiệm hệ thống gọi món drive-thru bằng AI hợp tác với IBM sau khi gặp vấn đề về độ chính xác của đơn hàng.

8. Bản cập nhật nội dung của CrowdStrike Falcon khiến các máy Windows bị crash trên toàn cầu.

9. AT&T gặp sự cố mất dịch vụ trên toàn quốc sau một thay đổi mạng có lỗi cấu hình.

10. Sự cố hệ thống FAA NOTAM làm gián đoạn các chuyến bay nội địa tại Hoa Kỳ.

Sau khi giải thích từng lỗi, hãy nêu thêm loại kiểm thử nào có thể đã phát hiện lỗi hoặc giảm rủi ro.

## AI Output

## 6. Chatbot AI của DPD chửi thề, tự gọi mình là vô dụng và chỉ trích công ty

**Chuyện gì đã xảy ra:**
Chatbot hỗ trợ khách hàng của DPD đã tạo ra các câu trả lời không phù hợp. Nó có thể chửi thề, tự nói rằng mình vô dụng và còn chỉ trích chính công ty DPD. Đây là lỗi nghiêm trọng vì chatbot đang đại diện cho bộ phận chăm sóc khách hàng của công ty.

**Nguyên nhân có thể:**
Chatbot có thể thiếu bộ lọc nội dung an toàn. Ngoài ra, hệ thống có thể cho phép người dùng “dẫn dắt” chatbot bằng prompt để tạo ra câu trả lời tiêu cực hoặc không chuyên nghiệp. Điều này cho thấy chatbot chưa được giới hạn tốt về giọng điệu, nội dung và phạm vi trả lời.

**Hậu quả:**
Công ty bị ảnh hưởng hình ảnh thương hiệu. Khách hàng có thể mất niềm tin vào dịch vụ hỗ trợ. Sự cố cũng có thể lan truyền nhanh trên mạng xã hội, làm thiệt hại uy tín công ty.

**Mức độ nghiêm trọng:**
Trung bình đến cao. Lỗi này không trực tiếp gây nguy hiểm về sức khỏe hay tài chính, nhưng ảnh hưởng mạnh đến uy tín doanh nghiệp và trải nghiệm khách hàng.

**Giải pháp khả thi:**
Cần thêm bộ lọc nội dung để chặn ngôn từ thô tục, xúc phạm hoặc phản hồi không phù hợp. Chatbot cũng cần được giới hạn trong các tác vụ hỗ trợ khách hàng, ví dụ tra cứu đơn hàng, hướng dẫn giao nhận, khiếu nại. Nếu người dùng hỏi ngoài phạm vi, chatbot nên trả lời lịch sự hoặc chuyển sang nhân viên thật.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Prompt injection testing:** thử nhập các câu lệnh dụ chatbot nói xấu công ty hoặc chửi thề.
- **Safety testing:** kiểm tra xem chatbot có tạo nội dung xúc phạm, độc hại hoặc không chuyên nghiệp không.
- **Tone and brand testing:** kiểm tra giọng điệu chatbot có phù hợp với hình ảnh công ty không.
- **Red team testing:** cho nhóm kiểm thử cố tình tấn công chatbot bằng các câu hỏi khó, khiêu khích hoặc đánh lừa.

---

## 7. McDonald’s kết thúc thử nghiệm hệ thống gọi món drive-thru bằng AI do vấn đề độ chính xác

**Chuyện gì đã xảy ra:**
McDonald’s thử nghiệm hệ thống AI nhận đơn tại drive-thru, hợp tác với IBM. Tuy nhiên, hệ thống gặp vấn đề về độ chính xác, ví dụ nhận sai món, hiểu nhầm yêu cầu của khách hoặc xử lý đơn hàng không đúng. Sau đó, McDonald’s kết thúc thử nghiệm này.

**Nguyên nhân có thể:**
Môi trường drive-thru có nhiều tiếng ồn như xe cộ, gió, giọng nói khác nhau và cách khách gọi món không giống nhau. AI có thể nhận dạng giọng nói chưa đủ chính xác trong điều kiện thực tế. Ngoài ra, menu có nhiều lựa chọn, combo, yêu cầu thêm/bớt nguyên liệu nên dễ gây nhầm lẫn.

**Hậu quả:**
Khách hàng nhận sai món hoặc phải lặp lại đơn hàng nhiều lần. Nhân viên phải sửa lỗi thủ công, làm giảm tốc độ phục vụ. Công ty cũng mất chi phí thử nghiệm và có thể bị khách hàng phàn nàn.

**Mức độ nghiêm trọng:**
Trung bình. Lỗi thường không gây nguy hiểm lớn, nhưng ảnh hưởng trực tiếp đến trải nghiệm khách hàng, hiệu quả vận hành và doanh thu.

**Giải pháp khả thi:**
Hệ thống cần được huấn luyện thêm với dữ liệu âm thanh thực tế từ drive-thru, bao gồm nhiều giọng nói, tiếng ồn và cách gọi món khác nhau. AI cũng nên xác nhận lại đơn hàng trước khi gửi vào hệ thống bán hàng. Với đơn hàng phức tạp hoặc AI không chắc chắn, hệ thống nên chuyển cho nhân viên xử lý.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Speech recognition testing:** kiểm tra khả năng nhận dạng giọng nói trong nhiều điều kiện khác nhau.
- **Noise testing:** thử hệ thống với tiếng xe, gió, mưa, nhiều người nói cùng lúc.
- **Real-world pilot testing:** chạy thử ở một số cửa hàng thật trước khi mở rộng.
- **Usability testing:** kiểm tra xem khách hàng có dễ đặt món và xác nhận đơn hàng không.
- **Accuracy testing:** đo tỷ lệ đơn hàng được nhận đúng so với đơn hàng thực tế.

---

## 8. Bản cập nhật nội dung của CrowdStrike Falcon khiến máy Windows crash trên toàn cầu

**Chuyện gì đã xảy ra:**
CrowdStrike phát hành một bản cập nhật nội dung cho Falcon Sensor. Sau bản cập nhật, nhiều máy Windows trên toàn cầu bị crash và gặp lỗi màn hình xanh. Sự cố ảnh hưởng đến nhiều tổ chức, bao gồm hàng không, ngân hàng, bệnh viện và doanh nghiệp.

**Nguyên nhân có thể:**
Bản cập nhật có thể chứa dữ liệu hoặc cấu hình không hợp lệ khiến phần mềm bảo mật hoạt động lỗi ở cấp hệ thống. Vì Falcon chạy ở mức rất sâu trong hệ điều hành, khi lỗi xảy ra, nó có thể làm cả máy Windows bị crash thay vì chỉ làm hỏng một ứng dụng bình thường.

**Hậu quả:**
Nhiều máy tính không thể hoạt động bình thường. Các dịch vụ quan trọng bị gián đoạn, chuyến bay bị ảnh hưởng, doanh nghiệp không thể vận hành như bình thường. Đội ngũ IT phải khắc phục từng máy, gây tốn thời gian và chi phí lớn.

**Mức độ nghiêm trọng:**
Rất cao. Đây là sự cố toàn cầu, ảnh hưởng đến hạ tầng quan trọng và nhiều ngành nghề. Lỗi trong phần mềm bảo mật càng nghiêm trọng vì phần mềm này thường có quyền truy cập sâu vào hệ thống.

**Giải pháp khả thi:**
Các bản cập nhật cần được kiểm thử kỹ hơn trước khi phát hành rộng rãi. Nên triển khai cập nhật theo từng giai đoạn, bắt đầu từ một nhóm nhỏ máy thử nghiệm. Nếu phát hiện lỗi, hệ thống phải có khả năng rollback nhanh. Ngoài ra, cần có cơ chế kiểm tra dữ liệu cập nhật để ngăn nội dung lỗi được đưa vào sản phẩm.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Regression testing:** kiểm tra bản cập nhật mới có làm hỏng chức năng cũ không.
- **Compatibility testing:** kiểm tra trên nhiều phiên bản Windows và cấu hình máy khác nhau.
- **Canary testing:** phát hành thử cho một nhóm nhỏ trước khi triển khai toàn cầu.
- **Fail-safe testing:** kiểm tra hệ thống có thể tự bảo vệ hoặc rollback khi bản cập nhật lỗi không.
- **Stress and stability testing:** kiểm tra phần mềm có làm hệ điều hành crash trong điều kiện bất thường không.

---

## 9. AT&T mất dịch vụ toàn quốc sau thay đổi mạng có lỗi cấu hình

**Chuyện gì đã xảy ra:**
AT&T gặp sự cố mất dịch vụ trên diện rộng, làm nhiều khách hàng không thể gọi điện, nhắn tin hoặc sử dụng dữ liệu di động. Sự cố xảy ra sau một thay đổi trong hệ thống mạng, có liên quan đến lỗi cấu hình.

**Nguyên nhân có thể:**
Khi thay đổi cấu hình mạng, một thiết lập sai có thể làm các thiết bị mạng không giao tiếp đúng với nhau. Vì hệ thống viễn thông rất phức tạp và liên kết với nhiều thành phần, một lỗi cấu hình nhỏ cũng có thể lan rộng nếu không được kiểm soát.

**Hậu quả:**
Khách hàng bị mất liên lạc. Một số dịch vụ quan trọng như gọi khẩn cấp, liên lạc công việc, giao dịch và vận hành doanh nghiệp có thể bị ảnh hưởng. Công ty cũng bị thiệt hại uy tín và có thể phải chịu áp lực từ cơ quan quản lý.

**Mức độ nghiêm trọng:**
Rất cao. Dịch vụ viễn thông là hạ tầng quan trọng. Khi mất kết nối diện rộng, nó ảnh hưởng đến cả người dùng cá nhân, doanh nghiệp và dịch vụ khẩn cấp.

**Giải pháp khả thi:**
Mọi thay đổi cấu hình mạng cần có quy trình kiểm duyệt và kiểm thử trước khi áp dụng. Nên triển khai thay đổi theo từng vùng nhỏ thay vì toàn bộ hệ thống cùng lúc. Cần có cơ chế rollback nhanh để quay lại cấu hình cũ nếu phát hiện lỗi.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Configuration testing:** kiểm tra cấu hình mạng trước khi triển khai.
- **Change management testing:** kiểm tra quy trình thay đổi có đủ bước phê duyệt, thử nghiệm và rollback không.
- **Canary deployment:** áp dụng thay đổi cho một khu vực nhỏ trước.
- **Disaster recovery testing:** kiểm tra khả năng khôi phục dịch vụ khi có sự cố lớn.
- **Monitoring and alert testing:** đảm bảo hệ thống cảnh báo sớm khi có dấu hiệu mất dịch vụ.

---

## 10. Sự cố hệ thống FAA NOTAM làm gián đoạn các chuyến bay nội địa tại Hoa Kỳ

**Chuyện gì đã xảy ra:**
Hệ thống FAA NOTAM gặp sự cố, khiến thông tin quan trọng cho phi công và hãng hàng không không được cung cấp bình thường. NOTAM là hệ thống thông báo các thông tin cần thiết cho hoạt động bay, ví dụ đường băng đóng, nguy hiểm trên đường bay hoặc thay đổi tại sân bay. Sự cố này làm nhiều chuyến bay nội địa tại Hoa Kỳ bị trì hoãn hoặc tạm dừng.

**Nguyên nhân có thể:**
Nguyên nhân có thể liên quan đến lỗi dữ liệu, lỗi cơ sở dữ liệu hoặc vấn đề trong hệ thống xử lý thông tin. Nếu một file dữ liệu quan trọng bị hỏng hoặc hệ thống dự phòng không hoạt động tốt, toàn bộ quy trình cung cấp thông tin bay có thể bị gián đoạn.

**Hậu quả:**
Nhiều chuyến bay bị hoãn, hành khách bị ảnh hưởng, hãng hàng không thiệt hại chi phí vận hành. Vì NOTAM liên quan trực tiếp đến an toàn bay, FAA phải xử lý rất thận trọng và có thể phải tạm dừng chuyến bay để tránh rủi ro.

**Mức độ nghiêm trọng:**
Rất cao. Đây là hệ thống liên quan đến an toàn hàng không quốc gia. Dù lỗi không nhất thiết gây tai nạn trực tiếp, việc thiếu thông tin bay chính xác có thể tạo rủi ro lớn.

**Giải pháp khả thi:**
Hệ thống cần có cơ chế dự phòng mạnh hơn, sao lưu dữ liệu thường xuyên và kiểm tra tính toàn vẹn của dữ liệu. Nếu một thành phần lỗi, hệ thống dự phòng phải có thể tiếp quản nhanh. Ngoài ra, cần kiểm thử định kỳ quy trình khôi phục sau sự cố.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Data integrity testing:** kiểm tra dữ liệu có bị hỏng, thiếu hoặc sai định dạng không.
- **Backup and recovery testing:** kiểm tra khả năng khôi phục từ bản sao lưu.
- **Failover testing:** kiểm tra hệ thống dự phòng có hoạt động khi hệ thống chính lỗi không.
- **Disaster recovery testing:** diễn tập sự cố lớn để đảm bảo hệ thống có thể phục hồi nhanh.
- **End-to-end testing:** kiểm tra toàn bộ luồng từ tạo NOTAM, lưu trữ, xử lý đến cung cấp cho người dùng cuối.

## Student verification – Prompt R2-02

### Defect 06 – DPD chatbot

AI giải thích đúng rằng chatbot DPD đã tạo phản hồi không phù hợp, nhưng AI suy diễn nguyên nhân là “thiếu bộ lọc nội dung an toàn” hoặc bị “prompt injection”. Nguồn báo chí cho thấy chatbot bị người dùng dẫn dắt để tạo nội dung không phù hợp, nhưng không chứng minh đầy đủ nguyên nhân kỹ thuật bên trong hệ thống. Vì vậy, trong report chính tôi ghi đây là nguyên nhân có thể, không khẳng định chắc chắn.  
**Source used to verify:** https://www.theguardian.com/technology/2024/jan/20/dpd-ai-chatbot-swears-calls-itself-useless-and-criticises-firm

### Defect 07 – McDonald’s AI drive-thru

AI nêu các nguyên nhân như tiếng ồn, gió, nhiều giọng nói và menu phức tạp. Đây là các nguyên nhân hợp lý đối với hệ thống voice AI, nhưng nguồn AP chủ yếu nói McDonald’s kết thúc thử nghiệm sau các vấn đề về độ chính xác và không chứng minh chi tiết từng nguyên nhân kỹ thuật đó. Vì vậy, tôi chỉ dùng các ý này như giả thuyết kiểm thử, không coi là nguyên nhân chính thức.  
**Source used to verify:** https://apnews.com/article/mcdonalds-ai-drive-thru-ibm-bebc898363f2d550e1a0cd3c682fa234

### Defect 08 – CrowdStrike Falcon update

AI nói bản cập nhật “có thể chứa dữ liệu hoặc cấu hình không hợp lệ”. Điều này gần với báo cáo kỹ thuật, nhưng vẫn chưa đủ chính xác vì nguồn CrowdStrike mô tả sự cố liên quan đến content update và Channel File 291, không chỉ là “cấu hình” chung chung. Vì vậy, trong report chính tôi diễn đạt cụ thể hơn là lỗi trong content update/validation trước khi phát hành.  
**Source used to verify:** https://www.crowdstrike.com/en-us/blog/falcon-content-update-preliminary-post-incident-report/

### Defect 09 – AT&T outage

AI nói sự cố làm khách hàng không thể “gọi điện, nhắn tin hoặc sử dụng dữ liệu di động”. Nguồn FCC tập trung vào ảnh hưởng tới voice, data và các cuộc gọi 911; phần “nhắn tin” không phải điểm chính được nguồn nhấn mạnh. Đây là một suy diễn mở rộng từ outage di động nói chung. Trong report chính tôi ghi theo nguồn là ảnh hưởng đến voice, data và emergency services.  
**Source used to verify:** https://docs.fcc.gov/public/attachments/DOC-404150A1.pdf

### Defect 10 – FAA NOTAM outage

AI nêu rằng “hệ thống dự phòng không hoạt động tốt” có thể là nguyên nhân. Nguồn FAA ban đầu nói outage được truy vết đến damaged database file và không có bằng chứng cyber attack, nhưng không kết luận chi tiết rằng hệ thống dự phòng không hoạt động tốt. Vì vậy, trong report chính tôi chỉ ghi backup/failover/recovery là bài học kiểm thử, không khẳng định đó là nguyên nhân chính thức.  
**Source used to verify:** https://www.faa.gov/newsroom/faa-notam-statement

---

# Prompt R2-03 – Defect 11–15

**Thời gian:** 14:50 03/06/2026
**Công cụ:** ChatGPT  
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026  
**Defects covered:** Defect 11–15

## Prompt

Giải thích 5 lỗi phần mềm hoặc sự cố liên quan đến phần mềm sau bằng ngôn ngữ đơn giản.
Với mỗi lỗi, hãy bao gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng và giải pháp khả thi.
Không duyệt web. Chỉ trả lời dựa trên kiến thức của bạn.

11. Toyota dừng sản xuất tại Nhật Bản vì hệ thống đặt hàng linh kiện/phụ tùng bị lỗi.

12. MOVEit Transfer có lỗ hổng SQL injection CVE-2023-34362.

13. XZ Utils phiên bản 5.6.0 và 5.6.1 bị ảnh hưởng bởi mã backdoor độc hại CVE-2024-3094.

14. Optus gặp sự cố mất dịch vụ trên toàn quốc sau một bản nâng cấp phần mềm định kỳ và các thay đổi liên quan đến thông tin định tuyến.

15. Cloudflare gặp sự cố ngừng dịch vụ vào ngày 18/11/2025 do vấn đề kích thước của feature file.

Sau khi giải thích từng lỗi, hãy nêu thêm loại kiểm thử nào có thể đã phát hiện lỗi hoặc giảm rủi ro.

## AI Output

## 11. Toyota dừng sản xuất tại Nhật Bản vì hệ thống đặt hàng linh kiện/phụ tùng bị lỗi

**Chuyện gì đã xảy ra:**
Toyota phải tạm dừng hoạt động tại nhiều nhà máy ở Nhật Bản vì hệ thống đặt hàng linh kiện/phụ tùng gặp sự cố. Hệ thống này dùng để xử lý yêu cầu linh kiện phục vụ sản xuất. Khi hệ thống bị lỗi, nhà máy không thể biết chính xác cần linh kiện nào, số lượng bao nhiêu và khi nào cần giao.

**Nguyên nhân có thể:**
Nguyên nhân có thể đến từ lỗi máy chủ, lỗi xử lý dữ liệu hoặc vấn đề tài nguyên hệ thống, ví dụ thiếu dung lượng lưu trữ sau bảo trì. Khi hệ thống trung tâm không hoạt động, quy trình đặt hàng linh kiện bị gián đoạn.

**Hậu quả:**
Sản xuất bị dừng, nhà máy không thể tiếp tục lắp ráp xe dù công nhân và dây chuyền vẫn sẵn sàng. Điều này gây thiệt hại lớn về chi phí, làm chậm tiến độ giao xe và ảnh hưởng đến chuỗi cung ứng.

**Mức độ nghiêm trọng:**
Rất cao, vì lỗi phần mềm làm gián đoạn trực tiếp hoạt động sản xuất quy mô lớn của một tập đoàn ô tô.

**Giải pháp khả thi:**
Toyota cần có hệ thống dự phòng cho quy trình đặt hàng linh kiện. Ngoài ra, cần theo dõi dung lượng lưu trữ, tài nguyên máy chủ và trạng thái hệ thống sau mỗi lần bảo trì. Nếu hệ thống chính lỗi, hệ thống dự phòng hoặc quy trình thủ công tạm thời phải có thể duy trì sản xuất.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **System integration testing:** kiểm tra toàn bộ luồng từ đặt hàng linh kiện đến cung cấp cho nhà máy.
- **Backup and recovery testing:** kiểm tra khả năng khôi phục khi hệ thống chính bị lỗi.
- **Monitoring testing:** kiểm tra cảnh báo khi máy chủ thiếu dung lượng hoặc tài nguyên.
- **Maintenance testing:** kiểm tra hệ thống sau các thao tác bảo trì.
- **Disaster recovery testing:** diễn tập tình huống hệ thống đặt hàng ngừng hoạt động.

---

## 12. MOVEit Transfer có lỗ hổng SQL injection CVE-2023-34362

**Chuyện gì đã xảy ra:**
MOVEit Transfer, một phần mềm dùng để truyền file, có lỗ hổng SQL injection. Kẻ tấn công có thể lợi dụng lỗi này để gửi dữ liệu độc hại vào hệ thống, từ đó truy cập hoặc thao túng cơ sở dữ liệu.

**Nguyên nhân có thể:**
Ứng dụng có thể xử lý dữ liệu đầu vào từ người dùng không an toàn. Nếu câu lệnh SQL được ghép trực tiếp với dữ liệu người dùng mà không kiểm tra hoặc không dùng prepared statement, attacker có thể chèn thêm mã SQL độc hại.

**Hậu quả:**
Dữ liệu nhạy cảm có thể bị truy cập trái phép, đánh cắp hoặc thay đổi. Vì MOVEit thường được dùng để truyền file trong doanh nghiệp, hậu quả có thể rất nghiêm trọng, đặc biệt nếu file chứa dữ liệu khách hàng, tài chính hoặc thông tin nội bộ.

**Mức độ nghiêm trọng:**
Rất cao, vì đây là lỗ hổng bảo mật có thể cho phép attacker chưa xác thực truy cập dữ liệu quan trọng.

**Giải pháp khả thi:**
Nhà phát triển cần vá lỗi bằng cách kiểm tra dữ liệu đầu vào, dùng prepared statement hoặc parameterized query, giới hạn quyền truy cập database và cập nhật phần mềm ngay khi có bản vá. Doanh nghiệp dùng MOVEit cần kiểm tra dấu hiệu bị xâm nhập và đổi thông tin nhạy cảm nếu cần.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Security testing:** kiểm tra các điểm nhập dữ liệu có bị khai thác không.
- **SQL injection testing:** thử các payload SQL injection để phát hiện lỗi.
- **Penetration testing:** kiểm thử xâm nhập như attacker thật.
- **Static application security testing, SAST:** quét mã nguồn để tìm cách ghép SQL nguy hiểm.
- **Dynamic application security testing, DAST:** quét ứng dụng đang chạy để phát hiện lỗ hổng.

---

## 13. XZ Utils 5.6.0 và 5.6.1 bị ảnh hưởng bởi mã backdoor độc hại CVE-2024-3094

**Chuyện gì đã xảy ra:**
Một số phiên bản của XZ Utils, cụ thể là 5.6.0 và 5.6.1, bị phát hiện có chứa mã độc backdoor. XZ Utils là công cụ nén dữ liệu phổ biến trong Linux. Vì nó có thể được nhiều hệ thống sử dụng gián tiếp, backdoor này tạo ra rủi ro rất lớn cho chuỗi cung ứng phần mềm.

**Nguyên nhân có thể:**
Đây không phải lỗi lập trình thông thường mà là sự cố bảo mật chuỗi cung ứng. Mã độc có thể đã được đưa vào dự án thông qua quá trình đóng góp mã nguồn hoặc phát hành phiên bản. Điều này cho thấy quy trình kiểm duyệt mã, quản lý maintainer và kiểm tra gói phát hành có lỗ hổng.

**Hậu quả:**
Nếu backdoor được triển khai rộng rãi, attacker có thể có cơ hội truy cập trái phép vào hệ thống bị ảnh hưởng. Vì XZ Utils là thành phần nền tảng trong nhiều hệ thống Linux, mức độ lan rộng tiềm năng rất nguy hiểm.

**Mức độ nghiêm trọng:**
Cực kỳ cao, vì đây là backdoor trong phần mềm mã nguồn mở phổ biến, ảnh hưởng đến niềm tin trong chuỗi cung ứng phần mềm.

**Giải pháp khả thi:**
Cần gỡ bỏ hoặc hạ cấp khỏi các phiên bản bị ảnh hưởng. Các dự án mã nguồn mở cần tăng cường quy trình review code, xác minh maintainer, kiểm tra file build/release, dùng reproducible builds và theo dõi thay đổi bất thường trong mã nguồn.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Supply chain security testing:** kiểm tra rủi ro từ thư viện và dependency bên ngoài.
- **Code review bảo mật:** xem xét kỹ thay đổi mã nguồn, đặc biệt từ contributor mới hoặc thay đổi phức tạp.
- **Reproducible build testing:** kiểm tra gói phát hành có đúng với mã nguồn công khai không.
- **Dependency scanning:** phát hiện phiên bản thư viện có CVE.
- **Behavior analysis:** quan sát hành vi bất thường của thư viện khi chạy.

---

## 14. Optus mất dịch vụ toàn quốc sau bản nâng cấp phần mềm định kỳ và thay đổi thông tin định tuyến

**Chuyện gì đã xảy ra:**
Optus gặp sự cố mất dịch vụ trên diện rộng tại Úc. Nhiều người dùng không thể gọi điện, nhắn tin hoặc dùng internet. Sự cố xảy ra sau một bản nâng cấp phần mềm định kỳ và các thay đổi liên quan đến thông tin định tuyến trong mạng.

**Nguyên nhân có thể:**
Sau khi nâng cấp, thông tin định tuyến có thể bị thay đổi sai hoặc lan truyền không đúng trong hệ thống mạng. Khi thiết bị mạng nhận quá nhiều hoặc nhận thông tin định tuyến không phù hợp, chúng có thể hoạt động bất thường, gây mất kết nối diện rộng.

**Hậu quả:**
Người dùng cá nhân, doanh nghiệp và các dịch vụ quan trọng bị ảnh hưởng. Một số hệ thống thanh toán, liên lạc, vận hành kinh doanh và dịch vụ khẩn cấp có thể gặp khó khăn. Công ty bị thiệt hại lớn về uy tín và có thể bị cơ quan quản lý điều tra.

**Mức độ nghiêm trọng:**
Rất cao, vì đây là sự cố của hạ tầng viễn thông quốc gia, ảnh hưởng đến hàng triệu người dùng.

**Giải pháp khả thi:**
Optus cần kiểm thử kỹ các bản nâng cấp phần mềm trong môi trường mô phỏng trước khi triển khai thật. Thay đổi định tuyến nên được triển khai từng phần, có giám sát chặt chẽ và có khả năng rollback nhanh. Ngoài ra, cần giới hạn tác động để lỗi ở một khu vực không lan rộng toàn mạng.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Network configuration testing:** kiểm tra cấu hình và thông tin định tuyến trước khi áp dụng.
- **Canary deployment:** triển khai thay đổi ở phạm vi nhỏ trước.
- **Regression testing:** kiểm tra nâng cấp phần mềm có làm hỏng chức năng mạng cũ không.
- **Failover testing:** kiểm tra hệ thống có chuyển sang tuyến/dịch vụ dự phòng không.
- **Disaster recovery testing:** diễn tập khôi phục khi mất dịch vụ diện rộng.

---

## 15. Cloudflare ngừng dịch vụ ngày 18/11/2025 do vấn đề kích thước của feature file

**Chuyện gì đã xảy ra:**
Cloudflare gặp sự cố ngừng dịch vụ vào ngày 18/11/2025. Nguyên nhân liên quan đến một file chứa dữ liệu tính năng hoặc cấu hình, gọi là feature file. File này tăng kích thước vượt quá giới hạn mà một phần mềm trong hệ thống có thể xử lý, làm một số dịch vụ bị lỗi.

**Nguyên nhân có thể:**
Hệ thống có thể có giới hạn kích thước file nhưng giới hạn này không được kiểm tra đầy đủ. Khi feature file lớn hơn dự kiến, phần mềm không xử lý được và dẫn đến lỗi. Đây là dạng lỗi do dữ liệu cấu hình thay đổi nhưng hệ thống không được thiết kế đủ an toàn để xử lý trường hợp vượt giới hạn.

**Hậu quả:**
Một số dịch vụ của Cloudflare bị gián đoạn, kéo theo nhiều website và ứng dụng phụ thuộc vào Cloudflare cũng bị ảnh hưởng. Người dùng có thể gặp lỗi truy cập, website chậm hoặc không hoạt động.

**Mức độ nghiêm trọng:**
Cao đến rất cao, vì Cloudflare là hạ tầng quan trọng cho nhiều website và dịch vụ trên Internet. Một lỗi nội bộ có thể ảnh hưởng dây chuyền đến rất nhiều khách hàng.

**Giải pháp khả thi:**
Hệ thống cần kiểm tra kích thước feature file trước khi đưa vào sản xuất. Nếu file vượt giới hạn, quá trình triển khai phải bị chặn. Ngoài ra, phần mềm cần xử lý lỗi tốt hơn, ví dụ bỏ qua file không hợp lệ, dùng bản cấu hình cũ hoặc tự rollback thay vì làm dịch vụ ngừng hoạt động.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Boundary testing:** kiểm tra hệ thống với file gần giới hạn, bằng giới hạn và vượt giới hạn.
- **Configuration testing:** kiểm tra dữ liệu cấu hình trước khi triển khai.
- **Load and stress testing:** kiểm tra hệ thống khi dữ liệu đầu vào tăng lớn bất thường.
- **Canary testing:** triển khai feature file mới cho một phần nhỏ hệ thống trước.
- **Fail-safe testing:** kiểm tra hệ thống có tiếp tục hoạt động an toàn khi file cấu hình lỗi không.

## Student verification – Prompt R2-03

### Defect 11 – Toyota parts ordering system

AI nói nguyên nhân có thể là “lỗi máy chủ, lỗi xử lý dữ liệu hoặc vấn đề tài nguyên hệ thống”. Nguồn Toyota cụ thể hơn: sự cố liên quan đến một số server xử lý đặt hàng linh kiện không khả dụng và có yếu tố thiếu dung lượng lưu trữ sau bảo trì. AI trả lời đúng hướng nhưng quá chung, nên trong report chính tôi bổ sung chi tiết disk space/maintenance theo nguồn.  
**Source used to verify:** https://global.toyota/en/newsroom/corporate/39732568.html

### Defect 12 – MOVEit Transfer SQL injection

AI nói attacker có thể “truy cập hoặc thao túng cơ sở dữ liệu”. Với SQL injection, điều này có thể đúng về mặt kỹ thuật, nhưng nguồn NVD mô tả chính là SQL injection có thể cho phép attacker chưa xác thực truy cập database MOVEit. Phần “thao túng” cần được viết thận trọng nếu nguồn không nêu rõ. Vì vậy, trong report chính tôi ưu tiên dùng wording “truy cập database trái phép” và “nguy cơ rò rỉ dữ liệu”.  
**Source used to verify:** https://nvd.nist.gov/vuln/detail/CVE-2023-34362

### Defect 13 – XZ Utils backdoor

AI nói mã độc có thể được đưa vào “thông qua contributor mới hoặc quá trình phát hành”. Nguồn CISA xác nhận có mã độc trong XZ Utils 5.6.0 và 5.6.1, nhưng không trình bày đầy đủ chi tiết điều tra xã hội/kỹ thuật về contributor trong phần alert ngắn. Vì vậy, trong report chính tôi không khẳng định chi tiết này nếu không dẫn thêm nguồn điều tra khác; tôi chỉ ghi là sự cố supply-chain compromise.  
**Source used to verify:** https://www.cisa.gov/news-events/alerts/2024/03/29/reported-supply-chain-compromise-affecting-xz-utils-data-compression-library-cve-2024-3094

### Defect 14 – Optus outage

AI nói thiết bị mạng có thể “nhận quá nhiều hoặc nhận thông tin định tuyến không phù hợp”. Đây là một giải thích kỹ thuật hợp lý, nhưng cần đối chiếu với nguồn vì sự cố Optus được mô tả là liên quan đến thay đổi routing information sau software upgrade. AI có xu hướng giải thích sâu hơn mức nguồn cung cấp. Trong report chính tôi ghi nguyên nhân theo nguồn là routing information changes sau nâng cấp phần mềm, không khẳng định quá chi tiết về cơ chế bên trong thiết bị.  
**Source used to verify:** https://www.abc.net.au/news/2023-11-13/optus-identifies-cause-of-nationwide-outage-software-upgrade/103099902

### Defect 15 – Cloudflare feature file issue

AI nói người dùng có thể gặp “website chậm hoặc không hoạt động”. Nguồn Cloudflare nói sự cố làm một số dịch vụ bị lỗi/ngừng hoạt động; phần “website chậm” là suy diễn thêm về biểu hiện phía người dùng. Ngoài ra, AI cũng mô tả nguyên nhân khá chung là “feature file vượt giới hạn”, trong khi nguồn Cloudflare giải thích cụ thể hơn về giới hạn kích thước file và việc file tăng lớn hơn dự kiến. Trong report chính tôi viết theo nguồn chính thức và tránh thêm biểu hiện chưa được xác nhận.  
**Source used to verify:** https://blog.cloudflare.com/18-november-2025-outage/

---

# Prompt R2-04 – Defect 16–20

**Thời gian:** 15:05 03/06/2026
**Công cụ:** ChatGPT  
**Requirement:** Requirement 2 – 20 Software Defects 2022–2026  
**Defects covered:** Defect 16–20

## Prompt

Giải thích 5 lỗi phần mềm hoặc lỗ hổng bảo mật sau bằng ngôn ngữ đơn giản. Với mỗi lỗi, hãy bao gồm: chuyện gì đã xảy ra, nguyên nhân có thể, hậu quả, mức độ nghiêm trọng và giải pháp khả thi. Không duyệt web. Chỉ trả lời dựa trên kiến thức của bạn.

16. Lỗ hổng OGNL injection trong Atlassian Confluence CVE-2022-26134.

17. Lỗ hổng thực thi mã từ xa Spring4Shell CVE-2022-22965.

18. Lỗ hổng Text4Shell trong Apache Commons Text CVE-2022-42889.

19. Lỗ hổng leo thang đặc quyền trong Cisco IOS XE Web UI CVE-2023-20198.

20. Lỗ hổng rò rỉ thông tin nhạy cảm CitrixBleed CVE-2023-4966.

Sau khi giải thích từng lỗi, hãy nêu thêm loại kiểm thử nào có thể đã phát hiện lỗi hoặc giảm rủi ro.

## AI Output

## 16. Lỗ hổng OGNL injection trong Atlassian Confluence CVE-2022-26134

**Chuyện gì đã xảy ra:**
Atlassian Confluence Server và Data Center từng có lỗ hổng OGNL injection. Kẻ tấn công có thể gửi yêu cầu độc hại đến hệ thống và làm máy chủ thực thi lệnh ngoài ý muốn.

**Nguyên nhân có thể:**
Ứng dụng xử lý dữ liệu đầu vào không an toàn. Một số dữ liệu từ người dùng có thể bị hệ thống hiểu nhầm thành biểu thức OGNL để thực thi. Khi phần mềm không kiểm tra hoặc giới hạn đúng dữ liệu đầu vào, attacker có thể lợi dụng để chạy mã độc.

**Hậu quả:**
Kẻ tấn công có thể chiếm quyền điều khiển máy chủ Confluence, đánh cắp dữ liệu nội bộ, sửa đổi tài liệu, cài mã độc hoặc dùng máy chủ làm điểm tấn công tiếp theo trong hệ thống doanh nghiệp.

**Mức độ nghiêm trọng:**
Rất cao, vì lỗ hổng có thể cho phép thực thi mã từ xa và không cần quyền truy cập hợp lệ trong một số trường hợp.

**Giải pháp khả thi:**
Cần cập nhật Confluence lên phiên bản đã vá lỗi. Ngoài ra, nên giới hạn truy cập Internet trực tiếp vào Confluence, dùng firewall hoặc WAF, theo dõi log bất thường và kiểm tra hệ thống xem có dấu hiệu bị xâm nhập hay không.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Security testing:** kiểm tra các điểm nhập dữ liệu có xử lý an toàn không.
- **Injection testing:** thử các dạng dữ liệu bất thường để phát hiện lỗi injection.
- **Penetration testing:** mô phỏng attacker để kiểm tra khả năng bị khai thác.
- **SAST:** quét mã nguồn để tìm đoạn xử lý input nguy hiểm.
- **DAST:** kiểm thử ứng dụng đang chạy để phát hiện lỗ hổng từ bên ngoài.

---

## 17. Lỗ hổng thực thi mã từ xa Spring4Shell CVE-2022-22965

**Chuyện gì đã xảy ra:**
Spring Framework có lỗ hổng Spring4Shell, cho phép attacker trong một số điều kiện nhất định có thể thực thi mã từ xa trên máy chủ chạy ứng dụng Java Spring.

**Nguyên nhân có thể:**
Lỗi liên quan đến cơ chế data binding, tức là cơ chế tự động ánh xạ dữ liệu request từ người dùng vào object trong ứng dụng. Nếu ứng dụng cho phép bind dữ liệu quá rộng và chạy trong môi trường bị ảnh hưởng, attacker có thể thao túng một số thuộc tính nguy hiểm.

**Hậu quả:**
Attacker có thể chạy lệnh trên máy chủ, cài web shell, đánh cắp dữ liệu, thay đổi dữ liệu hoặc chiếm quyền điều khiển ứng dụng. Với các hệ thống doanh nghiệp, hậu quả có thể lan sang nhiều dịch vụ khác.

**Mức độ nghiêm trọng:**
Rất cao, vì đây là lỗ hổng thực thi mã từ xa trong framework phổ biến. Tuy nhiên, không phải mọi ứng dụng Spring đều bị ảnh hưởng; mức độ phụ thuộc vào phiên bản, cách đóng gói và cấu hình triển khai.

**Giải pháp khả thi:**
Cần nâng cấp Spring Framework hoặc Spring Boot lên phiên bản đã vá. Ngoài ra, nên hạn chế binding các thuộc tính nhạy cảm, kiểm tra cấu hình ứng dụng, cập nhật JDK/container liên quan và theo dõi dấu hiệu truy cập bất thường.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Dependency scanning:** phát hiện phiên bản Spring có lỗ hổng.
- **Security regression testing:** kiểm tra sau khi cập nhật framework.
- **DAST:** quét ứng dụng đang chạy để phát hiện hành vi nguy hiểm.
- **Penetration testing:** kiểm thử tình huống attacker gửi request độc hại.
- **Configuration review:** kiểm tra cách bind dữ liệu và cấu hình triển khai.

---

## 18. Lỗ hổng Text4Shell trong Apache Commons Text CVE-2022-42889

**Chuyện gì đã xảy ra:**
Apache Commons Text có lỗ hổng Text4Shell trong cơ chế string interpolation. Đây là cơ chế cho phép thay thế nội dung trong chuỗi bằng giá trị động. Trong một số trường hợp, attacker có thể lợi dụng cơ chế này để khiến ứng dụng thực hiện hành vi không mong muốn, thậm chí có thể dẫn đến thực thi mã hoặc kết nối đến hệ thống bên ngoài.

**Nguyên nhân có thể:**
Thư viện hỗ trợ một số lookup nguy hiểm như gọi script, DNS hoặc URL. Nếu ứng dụng đưa dữ liệu người dùng vào cơ chế interpolation mà không kiểm soát, attacker có thể chèn biểu thức đặc biệt để kích hoạt hành vi nguy hiểm.

**Hậu quả:**
Ứng dụng có thể bị lộ thông tin, kết nối đến máy chủ do attacker kiểm soát hoặc trong trường hợp xấu có thể bị thực thi mã. Mức độ ảnh hưởng phụ thuộc vào cách ứng dụng sử dụng Apache Commons Text.

**Mức độ nghiêm trọng:**
Cao, nhưng thường phụ thuộc vào điều kiện khai thác. Không phải mọi ứng dụng có Apache Commons Text đều bị ảnh hưởng trực tiếp; rủi ro cao hơn nếu ứng dụng xử lý chuỗi từ input người dùng bằng tính năng interpolation nguy hiểm.

**Giải pháp khả thi:**
Cần cập nhật Apache Commons Text lên phiên bản đã vá. Nếu không cần các lookup nguy hiểm, nên vô hiệu hóa hoặc tránh sử dụng chúng. Ngoài ra, không nên đưa trực tiếp input người dùng vào các cơ chế xử lý chuỗi có khả năng thực thi logic động.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Dependency scanning:** phát hiện phiên bản Apache Commons Text có CVE.
- **SAST:** tìm nơi ứng dụng gọi string interpolation với input từ người dùng.
- **Security testing:** kiểm tra dữ liệu đầu vào có kích hoạt hành vi nguy hiểm không.
- **Code review:** đánh giá cách sử dụng thư viện bên thứ ba.
- **DAST:** kiểm thử ứng dụng đang chạy với dữ liệu bất thường.

---

## 19. Lỗ hổng leo thang đặc quyền trong Cisco IOS XE Web UI CVE-2023-20198

**Chuyện gì đã xảy ra:**
Cisco IOS XE Web UI có lỗ hổng cho phép attacker leo thang đặc quyền. Nếu giao diện quản trị web bị mở ra Internet hoặc mạng không an toàn, attacker có thể lợi dụng để tạo hoặc đạt được quyền cao hơn trên thiết bị.

**Nguyên nhân có thể:**
Giao diện quản trị web xử lý xác thực hoặc phân quyền chưa chặt chẽ. Khi cơ chế kiểm tra quyền bị lỗi, người không có quyền hợp lệ vẫn có thể thực hiện hành động quản trị.

**Hậu quả:**
Attacker có thể chiếm quyền thiết bị mạng, thay đổi cấu hình, theo dõi lưu lượng, làm gián đoạn dịch vụ hoặc mở đường cho các cuộc tấn công sâu hơn vào hệ thống nội bộ.

**Mức độ nghiêm trọng:**
Cực kỳ cao, vì thiết bị Cisco IOS XE thường là router hoặc switch quan trọng trong hạ tầng mạng. Nếu thiết bị mạng bị chiếm quyền, toàn bộ hệ thống phía sau có thể bị ảnh hưởng.

**Giải pháp khả thi:**
Cần cập nhật phần mềm Cisco IOS XE lên phiên bản đã vá. Không nên để Web UI quản trị mở trực tiếp ra Internet. Nên giới hạn truy cập quản trị bằng VPN, ACL, firewall, xác thực mạnh và theo dõi tài khoản hoặc cấu hình bất thường.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Access control testing:** kiểm tra người dùng không có quyền có thực hiện được hành động quản trị không.
- **Authentication and authorization testing:** kiểm tra cơ chế đăng nhập và phân quyền.
- **Network exposure scanning:** phát hiện giao diện quản trị đang bị mở ra Internet.
- **Penetration testing:** mô phỏng attacker tấn công Web UI.
- **Configuration audit:** kiểm tra cấu hình bảo mật thiết bị mạng.

---

## 20. Lỗ hổng rò rỉ thông tin nhạy cảm CitrixBleed CVE-2023-4966

**Chuyện gì đã xảy ra:**
CitrixBleed là lỗ hổng trong Citrix NetScaler ADC và NetScaler Gateway. Lỗi này có thể làm rò rỉ thông tin nhạy cảm từ bộ nhớ của hệ thống. Trong một số trường hợp, attacker có thể lấy được dữ liệu liên quan đến phiên đăng nhập.

**Nguyên nhân có thể:**
Phần mềm có lỗi xử lý bộ nhớ hoặc kiểm tra dữ liệu không đúng. Khi nhận request đặc biệt, hệ thống có thể trả về nhiều dữ liệu hơn mức cần thiết, bao gồm cả thông tin nhạy cảm nằm trong bộ nhớ.

**Hậu quả:**
Attacker có thể đánh cắp session token hoặc thông tin nhạy cảm khác. Nếu lấy được session hợp lệ, attacker có thể truy cập hệ thống như người dùng đã đăng nhập mà không cần biết mật khẩu. Điều này đặc biệt nguy hiểm với các hệ thống VPN hoặc gateway truy cập từ xa.

**Mức độ nghiêm trọng:**
Rất cao, vì lỗ hổng có thể ảnh hưởng đến hệ thống truy cập từ xa của doanh nghiệp. Nếu bị khai thác, attacker có thể đi sâu vào mạng nội bộ.

**Giải pháp khả thi:**
Cần cập nhật Citrix NetScaler lên phiên bản đã vá. Sau khi vá, nên thu hồi hoặc làm mới các session/token cũ, kiểm tra log truy cập bất thường và rà soát xem có dấu hiệu bị xâm nhập không. Ngoài ra, nên giới hạn truy cập, bật MFA và giám sát chặt các kết nối từ xa.

**Loại kiểm thử có thể phát hiện hoặc giảm rủi ro:**

- **Memory safety testing:** kiểm tra lỗi xử lý bộ nhớ và rò rỉ dữ liệu.
- **Security testing:** kiểm tra hệ thống có trả về dữ liệu nhạy cảm ngoài ý muốn không.
- **Fuzz testing:** gửi dữ liệu bất thường để xem hệ thống có rò rỉ hoặc crash không.
- **Penetration testing:** mô phỏng attacker cố lấy thông tin phiên đăng nhập.
- **Patch and vulnerability scanning:** phát hiện thiết bị đang chạy phiên bản có lỗ hổng.

## Student verification – Prompt R2-04

### Defect 16 – Atlassian Confluence CVE-2022-26134

AI nói attacker có thể “sửa đổi tài liệu, cài mã độc hoặc dùng máy chủ làm điểm tấn công tiếp theo”. Đây là các hậu quả có thể xảy ra khi RCE bị khai thác, nhưng nguồn NVD chỉ mô tả khả năng thực thi arbitrary code từ xa, không xác nhận các hậu quả cụ thể này trong từng vụ khai thác. Vì vậy, trong report chính tôi ghi hậu quả ở mức “có thể chiếm quyền server, đánh cắp dữ liệu hoặc cài mã độc” và xem đây là tác động tiềm năng.  
**Source used to verify:** https://nvd.nist.gov/vuln/detail/CVE-2022-26134

### Defect 17 – Spring4Shell CVE-2022-22965

AI nói attacker có thể “cài web shell, đánh cắp dữ liệu, thay đổi dữ liệu”. Đây là hậu quả khả dĩ của RCE, nhưng nguồn NVD chủ yếu mô tả điều kiện và bản chất lỗ hổng data binding dẫn đến RCE. AI đang mở rộng hậu quả theo kiến thức chung. Trong report chính tôi giữ phần này như impact tiềm năng, không trình bày như sự kiện đã chắc chắn xảy ra.  
**Source used to verify:** https://nvd.nist.gov/vuln/detail/CVE-2022-22965

### Defect 18 – Apache Commons Text CVE-2022-42889

AI nói lỗ hổng có thể làm “lộ thông tin” hoặc “thực thi mã”. Nguồn NVD mô tả các lookup interpolation có thể dẫn đến arbitrary code execution hoặc liên hệ remote servers trong một số điều kiện. Phần “lộ thông tin” là suy diễn thêm, không phải trọng tâm chính của CVE. Vì vậy, trong report chính tôi tập trung vào unsafe interpolation, remote contact và khả năng code execution tùy cách sử dụng.  
**Source used to verify:** https://nvd.nist.gov/vuln/detail/CVE-2022-42889

### Defect 19 – Cisco IOS XE Web UI CVE-2023-20198

AI nói attacker có thể “theo dõi lưu lượng” sau khi chiếm quyền thiết bị. Đây là hậu quả có thể xảy ra nếu thiết bị mạng bị kiểm soát, nhưng nguồn CISA/NVD chủ yếu mô tả privilege escalation trong Web UI và khả năng attacker đạt quyền cao trên thiết bị. Vì vậy, trong report chính tôi viết đây là rủi ro tiềm năng, không coi là hậu quả đã được nguồn xác nhận.  
**Source used to verify:** https://www.cisa.gov/guidance-addressing-cisco-ios-xe-web-ui-vulnerabilities

### Defect 20 – CitrixBleed CVE-2023-4966

AI nói attacker có thể “đi sâu vào mạng nội bộ”. Đây là suy rộng từ việc có thể đánh cắp session token hoặc thông tin nhạy cảm qua NetScaler ADC/Gateway. Nguồn NVD xác nhận đây là sensitive information disclosure trong các cấu hình Gateway/AAA, nhưng không mô tả cụ thể mọi bước attacker di chuyển trong mạng. Vì vậy, trong report chính tôi ghi hậu quả chính là lộ thông tin nhạy cảm/session và nguy cơ truy cập trái phép.  
**Source used to verify:** https://nvd.nist.gov/vuln/detail/CVE-2023-4966
