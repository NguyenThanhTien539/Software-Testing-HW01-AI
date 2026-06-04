# Prompt Log – Requirement 3

## Prompt R3-01 – Generate Physical Product Test Cases

**Thời gian:** [ĐIỀN GIỜ THẬT BẠN CHẠY PROMPT R3-01]  
**Công cụ:** ChatGPT  
**Requirement:** Requirement 3 – Physical Product Testing  
**Artifact:** AI-generated physical product test cases for ASIA Pedestal Fan A16007-XV0

## Prompt

Tôi đang làm bài Software Testing HW01 – Requirement 3: Test cases for ONE physical product.

Thiết bị tôi chọn là một quạt lửng gia dụng.

Thông tin thiết bị:

- Product type: Quạt lửng / pedestal fan
- Brand: ASIA
- Manufacturer: Công ty Cổ phần Quạt Việt Nam
- Model: A16007-XV0
- Manufacturing date: 20.11.2017
- Year: 2017
- Serial number: 29\*\*\*\*2
- Power supply: 220V – 50Hz
- Rated power: 45W
- Blade diameter: 400mm
- Control type: Physical push buttons on fan base
- Speed levels: 0 / 1 / 2 / 3
- Oscillation: Có nút/cần cơ phía sau đầu quạt để bật/tắt quay trái phải

Yêu cầu:
Hãy thiết kế 15 test cases cho thiết bị vật lý này.

Mỗi test case phải có đầy đủ các cột:

1. Test Case ID
2. Objective
3. Input
4. Steps
5. Expected Result
6. Actual Result
7. Verdict

Lưu ý:

- Đây là thiết bị vật lý thật, không phải phần mềm.
- Test cases cần bao gồm chức năng cơ bản, usability, safety, reliability và một số edge cases.
- Actual Result và Verdict có thể để trống hoặc ghi “To be executed” vì tôi sẽ chạy thật trên thiết bị sau.
- Không cần viết quá dài, nhưng mỗi test case phải đủ rõ để tôi có thể thực hiện và quay video.
- Trả lời bằng tiếng Việt.

## AI Output

## Requirement 3 – Test Cases for Physical Product: ASIA Pedestal Fan A16007-XV0

| Test Case ID | Objective                                         | Input                                                    | Steps                                                                                                                                                         | Expected Result                                                                                                                                           | Actual Result  | Verdict        |
| ------------ | ------------------------------------------------- | -------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | -------------- |
| TC-01        | Kiểm tra quạt bật được ở tốc độ 1                 | Cắm điện 220V, nhấn nút số 1                             | 1. Đặt quạt trên nền phẳng. 2. Cắm điện. 3. Nhấn nút số 1. 4. Quan sát cánh quạt và luồng gió.                                                                | Quạt khởi động bình thường, cánh quay ổn định, có gió nhẹ, không có tiếng kêu bất thường.                                                                 | To be executed | To be executed |
| TC-02        | Kiểm tra quạt bật được ở tốc độ 2                 | Cắm điện 220V, nhấn nút số 2                             | 1. Cắm điện. 2. Nhấn nút số 2. 3. So sánh luồng gió với tốc độ 1.                                                                                             | Quạt chạy ở tốc độ trung bình, gió mạnh hơn tốc độ 1, không rung lắc bất thường.                                                                          | To be executed | To be executed |
| TC-03        | Kiểm tra quạt bật được ở tốc độ 3                 | Cắm điện 220V, nhấn nút số 3                             | 1. Cắm điện. 2. Nhấn nút số 3. 3. Quan sát tốc độ quay, độ rung và tiếng ồn.                                                                                  | Quạt chạy ở tốc độ cao nhất, gió mạnh nhất, thân quạt vẫn ổn định, không có mùi khét hoặc tiếng kêu lạ.                                                   | To be executed | To be executed |
| TC-04        | Kiểm tra nút 0 có tắt quạt đúng không             | Quạt đang chạy, nhấn nút 0                               | 1. Bật quạt ở tốc độ 2. 2. Nhấn nút 0. 3. Quan sát cánh quạt dừng lại.                                                                                        | Quạt ngừng cấp gió, cánh quạt giảm tốc rồi dừng, không còn hoạt động sau khi nhấn nút 0.                                                                  | To be executed | To be executed |
| TC-05        | Kiểm tra chuyển đổi giữa các mức tốc độ           | Nhấn lần lượt 1 → 2 → 3 → 1 → 0                          | 1. Bật quạt tốc độ 1. 2. Chuyển sang tốc độ 2. 3. Chuyển sang tốc độ 3. 4. Quay lại tốc độ 1. 5. Nhấn nút 0.                                                  | Quạt thay đổi tốc độ đúng theo nút được nhấn, không bị kẹt nút, không tắt đột ngột, không có tiếng động bất thường.                                       | To be executed | To be executed |
| TC-06        | Kiểm tra chức năng quay trái phải                 | Cần/nút oscillation phía sau đầu quạt                    | 1. Bật quạt ở tốc độ 2. 2. Bật cần quay trái phải. 3. Quan sát đầu quạt trong 1–2 phút.                                                                       | Đầu quạt quay trái phải đều, không bị giật, không kẹt, không phát ra tiếng kêu bất thường.                                                                | To be executed | To be executed |
| TC-07        | Kiểm tra tắt chức năng quay trái phải             | Cần/nút oscillation phía sau đầu quạt                    | 1. Bật quạt và bật chế độ quay trái phải. 2. Sau khi quạt đang quay, tắt cần oscillation. 3. Quan sát đầu quạt.                                               | Đầu quạt dừng quay trái phải và giữ hướng cố định, cánh quạt vẫn tiếp tục chạy bình thường.                                                               | To be executed | To be executed |
| TC-08        | Kiểm tra độ ổn định của thân quạt khi chạy mạnh   | Tốc độ 3                                                 | 1. Đặt quạt trên nền phẳng. 2. Bật tốc độ 3. 3. Quan sát thân, chân đế và đầu quạt trong 2 phút.                                                              | Quạt không bị nghiêng, không tự dịch chuyển, không rung quá mạnh, chân đế giữ thăng bằng tốt.                                                             | To be executed | To be executed |
| TC-09        | Kiểm tra tiếng ồn ở các mức tốc độ                | Tốc độ 1, 2, 3                                           | 1. Bật lần lượt tốc độ 1, 2, 3. 2. Lắng nghe tiếng motor, tiếng cánh và tiếng rung. 3. Ghi nhận mức tiếng ồn bất thường nếu có.                               | Tiếng ồn tăng dần theo tốc độ nhưng không có tiếng cạ cánh, tiếng rè, tiếng lạch cạch hoặc tiếng motor bất thường.                                        | To be executed | To be executed |
| TC-10        | Kiểm tra an toàn lồng quạt/cánh quạt              | Quan sát lồng bảo vệ khi quạt chạy                       | 1. Bật quạt tốc độ 2. 2. Quan sát lồng trước và lồng sau. 3. Kiểm tra bằng mắt xem lồng có lỏng, méo hoặc quá hở không. Không đưa tay vào lồng khi quạt chạy. | Lồng quạt chắc chắn, không rung lắc mạnh, không chạm vào cánh quạt, bảo vệ người dùng khỏi tiếp xúc trực tiếp với cánh.                                   | To be executed | To be executed |
| TC-11        | Kiểm tra dây điện và phích cắm khi sử dụng        | Cắm điện và chạy quạt                                    | 1. Kiểm tra dây điện/phích cắm bằng mắt trước khi bật. 2. Bật quạt tốc độ 2 trong 10–15 phút. 3. Tắt quạt và kiểm tra xem dây/phích có nóng bất thường không. | Dây điện và phích cắm không bị hở, không phát nhiệt bất thường, không có mùi khét.                                                                        | To be executed | To be executed |
| TC-12        | Kiểm tra độ tin cậy khi chạy liên tục ngắn hạn    | Chạy quạt 15–30 phút                                     | 1. Bật quạt tốc độ 2 hoặc 3. 2. Để quạt chạy liên tục 15–30 phút. 3. Quan sát gió, tiếng ồn, rung lắc và mùi bất thường.                                      | Quạt tiếp tục chạy ổn định, không tự tắt, không giảm tốc bất thường, không có mùi khét, không quá nóng.                                                   | To be executed | To be executed |
| TC-13        | Edge case: Chuyển tốc độ nhanh liên tục           | Nhấn nhanh 1 → 2 → 3 → 0 nhiều lần                       | 1. Cắm điện. 2. Nhấn nhanh các nút 1, 2, 3, 0 trong khoảng 5–10 giây. 3. Quan sát phản ứng của quạt.                                                          | Quạt không bị kẹt nút, không chạy sai tốc độ, không phát ra tiếng bất thường, cuối cùng phản ứng đúng theo nút đang được chọn.                            | To be executed | To be executed |
| TC-14        | Edge case: Mất điện khi quạt đang chạy            | Tắt nguồn bằng công tắc ổ cắm hoặc rút phích cắm an toàn | 1. Bật quạt tốc độ 2. 2. Ngắt nguồn điện bằng công tắc ổ cắm hoặc rút phích cắm an toàn. 3. Chờ 10 giây. 4. Cấp điện lại.                                     | Khi mất điện, quạt dừng hoạt động. Khi có điện lại, quạt chỉ chạy lại nếu nút tốc độ vẫn đang được nhấn; không phát sinh tia lửa, mùi khét hoặc tiếng lạ. | To be executed | To be executed |
| TC-15        | Edge case: Bật/tắt oscillation khi quạt đang chạy | Cần/nút quay trái phải phía sau đầu quạt                 | 1. Bật quạt tốc độ 2. 2. Bật oscillation. 3. Khi đầu quạt đang quay, tắt oscillation. 4. Bật lại oscillation. 5. Quan sát cơ chế quay.                        | Chức năng quay trái phải bật/tắt được bình thường khi quạt đang chạy, không bị kẹt, không có tiếng kêu lớn, không làm quạt dừng đột ngột.                 | To be executed | To be executed |

## Student verification – Prompt R3-01

Sau khi kiểm tra AI Output, tôi phát hiện AI chỉ tạo các edge cases sau:

- AI TC-13: Chuyển tốc độ nhanh liên tục.
- AI TC-14: Mất điện khi quạt đang chạy.
- AI TC-15: Bật/tắt oscillation khi quạt đang chạy.

Tuy nhiên, AI không tạo ra 3 edge cases sau. Đây là các edge cases tôi tự bổ sung vào test suite cuối cùng:

- Final TC-13: Cản nhẹ chuyển động quay trái phải.
- Final TC-14: Nhấn đồng thời hai nút tốc độ.
- Final TC-15: Kiểm tra quạt sau khi điều chỉnh độ cao hoặc góc nghiêng.

Ba edge cases này được giải thích chi tiết trong file:

`requirement_3_physical_product/ai_missed_edge_cases.md`
