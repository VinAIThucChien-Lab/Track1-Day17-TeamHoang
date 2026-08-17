# Báo cáo lab: Finding and Validating Pain Points (Day 17)

---

## 1. Thông tin cá nhân và nhóm

* **Tên nhóm:** Team Hoang
* **Danh sách thành viên:**
  * Nguyễn Đức Đạt - 2A202601728
  * Kiều Hồng Phong - 2A202601020
  * Đỗ Duy Đức - 2A202602019
* **Case đã chọn:** Case A — AI Tutor: Diagnostic Refresher
  * *Mô tả solution directive:* Thêm nút "Tôi vẫn chưa hiểu" vào bài học. Khi bấm, AI Tutor sử dụng nội dung bài hiện tại, câu trả lời gần đây và lịch sử học tập để đặt 2–3 câu hỏi chẩn đoán ngắn, chọn khái niệm nền để ôn lại, tạo phần giải thích ngắn rồi đưa học viên trở về bài đang học.

---

## 2. Problem hypothesis brief (Kết quả chặng 1 của nhóm)

### 2.1. Capability trung tính (Gỡ bỏ UI và AI)
* **Directive gốc:** Thêm nút "Tôi vẫn chưa hiểu" $\rightarrow$ AI chẩn đoán 2-3 câu ngắn $\rightarrow$ Ôn lại khái niệm nền $\rightarrow$ Quay lại bài học.
* **Capability trung tính:** Khả năng xác định nhanh lỗ hổng kiến thức tiên quyết và cung cấp giải thích bổ trợ đúng ngữ cảnh môn học ngay tại thời điểm người học bị nghẽn đà tiếp thu.

### 2.2. Chuỗi thay đổi kỳ vọng (Change chain)
$$\text{Output của team} \longrightarrow \text{User nhận thức điều gì?} \longrightarrow \text{Hành vi nào thay đổi?} \longrightarrow \text{Outcome đạt được}$$

* **Output của team:** Cung cấp phần giải thích ngắn gọn, đúng trọng tâm và đúng ngữ cảnh bài học ngay lập tức khi học viên gặp bế tắc.
* **Nhận thức thay đổi:** Học viên nhận biết chính xác mình đang bị hổng khái niệm nền tảng nào thay vì cảm thấy mơ hồ bài này khó hiểu.
* **Hành vi thay đổi:** Dành 2-3 phút đọc lướt giải thích bổ trợ và tiếp tục học ngay, thay vì mở 10 tab Google hoặc ChatGPT tra cứu lan man hoặc nản lòng đóng máy đi ngủ.
* **Outcome kỳ vọng:** Duy trì dòng suy nghĩ liền mạch khi tự học ban đêm, không bị đứt mạch tư duy, hoàn thành bài học đúng hạn và tự tin vượt qua bài kiểm tra.

### 2.3. Actor trọng tâm
* **Đối tượng điều tra:** Học viên tự học online ngoài giờ hoặc ban đêm.
* **Lý do chọn:** Là người trực tiếp trải nghiệm rào cản, chịu tổn thất lớn nhất về thời gian mò mẫm và là người đưa ra quyết định bỏ học hay tiếp tục.

### 2.4. Situation và Jobs-to-be-Done (JTBD)
* **Mô tả situation và job:**
  > Khi đang tự học bài mới vào ban đêm và gặp phải đoạn slide dài, cô đọng nhưng thiếu diễn giải ví dụ, học viên đang cố hiểu được ý nghĩa khái niệm để làm bài tập bằng cách tự copy từ khóa tra cứu trên Google hoặc ChatGPT bên ngoài.
* **JTBD hypothesis:**
  > Khi tự học ngoài giờ và gặp phải nội dung khó hiểu trong bài giảng, tôi muốn nhanh chóng làm rõ bản chất khái niệm đúng theo ngữ cảnh môn học mà không cần chờ người trợ giúp, để có thể tiếp tục học liền mạch và hoàn thành bài học đúng hạn.

### 2.5. Hai giả thuyết pain cạnh tranh (Pain A vs Pain B)
* **Pain hypothesis A (Giả thuyết rào cản ngữ cảnh và thiếu hỗ trợ tức thì trong đêm):**
  > Khi tự học bài mới vào ban đêm, học viên gặp khó khăn trong việc hiểu bài vì không có ai để hỏi ngay lúc đó và khi tự tìm kiếm bên ngoài (Google hoặc ChatGPT) thì thông tin quá lan man, không khớp với ngữ cảnh môn học, dẫn đến mất 45-60 phút mò mẫm vô ích, đứt mạch tư duy và nản lòng bỏ dở bài học.
* **Pain hypothesis B (Giả thuyết rào cản trình bày tài liệu và nhảy cóc kiến thức):**
  > Khi tự học bài mới, học viên gặp khó khăn trong việc nắm bắt kiến thức vì slide bài giảng quá dài nhưng chỉ toàn gạch đầu dòng cô đọng, thiếu ví dụ minh họa và thiếu diễn giải bước đệm, dẫn đến đọc đi đọc lại nhiều lần vẫn không hiểu, không biết mình đang bị hổng ở bước nào.
* **Giả thuyết nhóm chọn kiểm chứng:** Pain hypothesis A.
* **Lý do chọn:** Đánh trúng ba điểm nghẽn thực tế nhất của học viên gồm: tự học ban đêm khi không có mentor hoặc trợ giảng, sự cô độc khi tự học, và việc bị ngợp thông tin phân tán khi tự tra cứu ngoài.

### 2.6. Evidence map (Bản đồ bằng chứng cần tìm)

| Cần kiểm tra | Evidence làm nhóm tin hơn (Positive) | Evidence làm nhóm bác bỏ hoặc làm yếu giả thuyết (Negative) |
| :--- | :--- | :--- |
| **Situation có thật** | User kể được chính xác bài học và khái niệm bị tắc trong 7 ngày qua (môn nào, slide mấy, lúc mấy giờ đêm). | User nói chung chung: lâu rồi mình không tự học đêm, thường mình thấy slide cũng dễ hiểu. |
| **Pain có ý nghĩa** | Bực bội thực sự, stress vì mất 30-60 phút tra cứu nhưng vẫn không hiểu bài. | Coi như chuyện nhỏ, lướt qua luôn không bận tâm, sáng hôm sau hỏi nhẹ là xong. |
| **Workaround tồn tại** | Đã thử nhiều cách: chụp ảnh gửi nhóm bạn, mở 5-10 tab Google, hỏi ChatGPT nhưng câu trả lời quá hàn lâm hoặc lạc đề. | Không làm gì cả, để trống bài tập hoặc đi ngủ mà không thấy áy náy. |
| **Consequence tồn tại** | Bị trễ deadline nộp bài, rớt quiz, mất chuỗi học tập, nản lòng muốn drop khóa. | Vẫn làm được bài tập bình thường, không ảnh hưởng kết quả hay tiến độ. |
| **Pattern có lặp** | Tình trạng tắc nghẽn lặp lại ở hầu hết các bài học mang tính kỹ thuật hoặc trừu tượng cao. | Chỉ bị đúng một lần duy nhất do hôm đó mệt hoặc mất tập trung. |

### 2.7. Chốt problem hypothesis mang sang chặng 2
> Học viên tự học online vào ban đêm khi gặp slide dài chứa khái niệm mới thường bị nghẽn đà tiếp thu vì không có người hỗ trợ tức thì, và khi tự tra cứu bên ngoài thì bị ngợp thông tin lan man không đúng ngữ cảnh môn học, dẫn đến mất nhiều thời gian mò mẫm, ức chế và dễ bỏ dở bài học.

* **Điều gì phải đúng để giả thuyết đứng vững:**
  1. Khung giờ tự học đêm là thời điểm học viên học nhiều nhưng thiếu sự hỗ trợ nhất.
  2. Việc tự tra Google hoặc ChatGPT hiện tại tạo ra rào cản lệch ngữ cảnh hoặc ngợp thông tin, tốn trên 20-30 phút.
  3. Học viên thực sự có hành vi bỏ dở bài học do bế tắc nhận thức.
* **Điều gì có thể khiến nhóm sửa hoặc bác bỏ giả thuyết:**
  1. Học viên thấy Google hoặc ChatGPT giải thích cực kỳ chuẩn xác, nhanh chóng và khớp hoàn toàn ngữ cảnh môn học.
  2. Rào cản thực sự nằm ở lỗi slide hoặc âm thanh chứ không phải do thiếu diễn giải khái niệm nền.

### 2.8. Solution parking lot (Tạm cất solution directive ban đầu)

```
[PROBLEM ĐƯỢC CHỌN]                      [SOLUTION OPTIONS ĐƯỢC BRAINSTORM]
                                         ┌───────────────────────────────────────────────┐
                                      1  │ [AI] Nút "Tôi chưa hiểu" chẩn đoán 2 câu      │
                                         └───────────────────────────────────────────────┘
                                         ┌───────────────────────────────────────────────┐
                                      2  │ [AI] Chatbot context-aware giải đáp trực tiếp │
                                         │      ngay trên đoạn slide đang mở             │
                                         └───────────────────────────────────────────────┘
Tự học đêm, không ai hỏi, ───────►       ┌───────────────────────────────────────────────┐
slide thiếu giải thích,               3  │ [Non-AI] Bổ sung mục "Thuật ngữ & Ví dụ thực  │
tra mạng bị lan man                      │          tế" (Glossary) ghim kèm từng slide   │
                                         └───────────────────────────────────────────────┘
                                         ┌───────────────────────────────────────────────┐
                                      4  │ [Non-AI] Tạo form "Câu hỏi ẩn danh" cuối bài  │
                                         │          cam kết TA trả lời trước 9h sáng mai │
                                         └───────────────────────────────────────────────┘
                                         ┌───────────────────────────────────────────────┐
                                      5  │ [Non-AI] Thêm video ngắn 1-2 phút giải thích  │
                                         │          bước đệm cho các slide khó           │
                                         └───────────────────────────────────────────────┘
```