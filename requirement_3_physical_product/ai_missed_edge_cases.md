# Các trường hợp biên mà AI đã bỏ sót

## 1. Bằng chứng

Ảnh chụp màn hình các test case do AI tạo được lưu tại:

- `ai_evidence/ai_prompt_test_cases_01_04.png`
- `ai_evidence/ai_prompt_test_cases_05_08.png`
- `ai_evidence/ai_prompt_test_cases_09_12.png`
- `ai_evidence/ai_prompt_test_cases_13_15.png`

AI đã tạo 15 test case cho quạt lửng ASIA A16007-XV0. Trong kết quả do AI tạo, các trường hợp biên là:

- AI TC-13: Chuyển tốc độ nhanh liên tục
- AI TC-14: Mất điện khi quạt đang chạy
- AI TC-15: Bật/tắt oscillation khi quạt đang chạy

Sau khi xem xét kết quả của AI, tôi nhận thấy AI không tạo ra ba trường sau. Các test case này đã được sinh viên bổ sung vào bộ test case cuối cùng:

- TC-13: Cản nhẹ chuyển động quay trái phải
- TC-14: Nhấn đồng thời hai nút tốc độ
- TC-15: Kiểm tra quạt sau khi điều chỉnh độ cao hoặc góc nghiêng

---

## 2. Trường hợp biên bị bỏ sót 01 – Cản nhẹ chuyển động quay trái phải

**Mã test case:** TC-13

**Trường hợp biên do sinh viên bổ sung:**
Cản nhẹ phần thân ngoài của quạt khi đầu quạt đang quay trái phải, không chạm vào cánh quạt.

**Bằng chứng cho thấy AI đã bỏ sót:**
AI có tạo test case về việc bật/tắt chế độ quay trái phải khi quạt đang chạy, nhưng AI không tạo test case kiểm tra tình huống đầu quạt bị cản nhẹ khi đang quay trái phải.

**Lý do AI bỏ sót:**
AI chủ yếu tập trung vào chức năng bình thường của chế độ quay trái phải, ví dụ như bật/tắt chế độ quay và quan sát xem đầu quạt có quay đều hay không. AI không xét đến các tình huống vật lý thực tế, chẳng hạn như đầu quạt có thể bị cản bởi đồ vật gần đó, tường, rèm cửa hoặc do người dùng vô tình chạm vào thân quạt.

**Vì sao trường hợp biên này quan trọng:**
Trường hợp này quan trọng vì có thể giúp phát hiện tình trạng kẹt cơ khí, tiếng kêu bất thường, áp lực lên motor quay trái phải, nguy cơ quạt bị nghiêng đổ hoặc cơ chế quay không thể tự trở lại bình thường sau khi bị cản.

---

## 3. Trường hợp biên bị bỏ sót 02 – Nhấn đồng thời hai nút tốc độ

**Mã test case:** TC-14

**Trường hợp biên do sinh viên bổ sung:**
Nhấn gần như đồng thời hai nút tốc độ, ví dụ nút 1 và nút 2 hoặc nút 2 và nút 3.

**Bằng chứng cho thấy AI đã bỏ sót:**
AI có tạo test case về việc chuyển tốc độ nhanh liên tục, nhưng AI không tạo test case kiểm tra trường hợp người dùng nhấn đồng thời hai nút tốc độ.

**Lý do AI bỏ sót:**
AI giả định người dùng thao tác theo trình tự bình thường, tức là nhấn từng nút một. Tuy nhiên, với quạt sử dụng nút bấm cơ, người dùng có thể vô tình nhấn hai nút gần như cùng lúc, đặc biệt khi thao tác nhanh hoặc khi nút bấm đã cũ.

**Vì sao trường hợp biên này quan trọng:**
Trường hợp này giúp kiểm tra cơ chế nút bấm có bị kẹt ở hai trạng thái cùng lúc hay không, quạt có chạy sai tốc độ hay không, và có phát sinh tiếng động hoặc hành vi không ổn định hay không.

---

## 4. Trường hợp biên bị bỏ sót 03 – Kiểm tra quạt sau khi điều chỉnh độ cao hoặc góc nghiêng

**Mã test case:** TC-15

**Trường hợp biên do sinh viên bổ sung:**
Điều chỉnh độ cao thân quạt hoặc góc nghiêng đầu quạt, sau đó bật quạt ở tốc độ mạnh nhất để kiểm tra độ ổn định.

**Bằng chứng cho thấy AI đã bỏ sót:**
AI không tạo test case nào liên quan đến việc điều chỉnh độ cao thân quạt hoặc góc nghiêng đầu quạt trước khi cho quạt hoạt động.

**Lý do AI bỏ sót:**
AI tập trung vào các chức năng điện và vận hành như bật/tắt, các mức tốc độ, tiếng ồn, quay trái phải, độ ổn định, an toàn lồng quạt, dây điện, chạy liên tục, chuyển tốc độ nhanh, mất điện và bật/tắt chế độ quay trái phải khi quạt đang chạy. Tuy nhiên, AI đã bỏ sót một đặc điểm cơ khí quan trọng của quạt lửng, đó là thân quạt và đầu quạt có thể điều chỉnh được.

**Vì sao trường hợp biên này quan trọng:**
Nếu khớp điều chỉnh hoặc chốt giữ không chắc chắn, quạt có thể bị tụt thân, tụt đầu quạt, rung mạnh hoặc mất ổn định khi chạy ở tốc độ cao. Trường hợp này giúp đánh giá mức độ an toàn khi sử dụng sau khi người dùng thay đổi cấu hình vật lý của quạt.
