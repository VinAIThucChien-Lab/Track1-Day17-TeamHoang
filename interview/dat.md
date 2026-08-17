# BẢN GHI PHỎNG VẤN CÁ NHÂN (INTERVIEW RECORD)

> **Học phần:** Track 1 - Day 17: Finding and Validating Pain Points
> **Case nghiên cứu:** Case A — AI Tutor: Diagnostic Refresher
> **Chủ đề phỏng vấn:** Khảo sát hành vi, rào cản và cách xử lý thực tế của người học khi học trên lớp/đọc slide có phần chưa hiểu, muốn hỏi giáo viên nhưng không đủ thời gian hoặc hỏi bạn bè nhưng không được giải đáp.

---

## 1. THÔNG TIN BUỔI PHỎNG VẤN

* **Người thực hiện phỏng vấn (Interviewer):** Nguyễn Đức Đạt
* **Mã học viên (Interviewer ID):** `2A202601728`
* **Tên người tham gia (Interviewee):** Nguyễn Việt Hải
* **Tiêu chí tuyển:** Học viên tham gia lớp học (trực tiếp hoặc online), trong vòng 7 ngày gần đây đã gặp tình trạng không hiểu một phần slide/bài giảng trên lớp, muốn hỏi giáo viên/bạn bè nhưng gặp rào cản và phải tự xoay sở.
* **Đúng tiêu chí tuyển:** [x] Có  /  [ ] Không
* **Thời lượng phỏng vấn:** 15 phút (Đúng quy định luyện phỏng vấn 15 phút của Lab)
* **Đã được người tham gia đồng ý ghi âm (Consent):** [x] Có (Đã xin phép trước khi ghi âm và cam kết chỉ dùng nội bộ phục vụ bài học)
* **File hoặc link ghi âm:** Xem chi tiết tại 

---

## 2. NỘI DUNG GHI CHÉP PHỎNG VẤN (FACTS & EVIDENCE)

### 2.1. Câu chuyện gần nhất (Bối cảnh và mục tiêu của user)

* **Bối cảnh & Thời gian cụ thể:** Buổi sáng thứ Ba tuần trước, trong ca học trên lớp từ 8h00 đến 11h30 (lớp học trực tiếp có khoảng 45 học viên).
* **Bài học / Khái niệm:** Khóa học Machine Learning cơ bản — Bài giảng về *Thuật toán Phân loại và Hàm mất mát (Loss Function & Gradient Descent Optimization)*.
* **Mục tiêu của user lúc đó (JTBD):** Đang theo dõi bài giảng của giảng viên đến slide số 20 (công thức biến đổi đạo hàm cập nhật trọng số). User cần hiểu rõ ý nghĩa bước đệm logic giữa 2 dòng công thức để có thể theo kịp phần lý thuyết phía sau và hoàn thành bài thực hành (Hands-on Lab) code trực tiếp trên máy vào cuối buổi học.

---

### 2.2. Hành vi thực tế đã diễn ra (Facts theo trình tự thời gian)

1. **9h15 — Gặp rào cản trên lớp:** Giảng viên chiếu đến slide 20 và giảng lướt qua bước biến đổi đạo hàm trong vòng chưa đầy 1 phút để kịp giáo trình. User đọc trên slide thấy công thức nhảy cóc, không hiểu tại sao xuất hiện thành phần trừ lùi $(h_\theta(x) - y)$. User định giơ tay hỏi nhưng thấy lớp đang trôi theo mạch bài giảng và giảng viên đang nói nhanh, sợ ngắt quãng tiết học của cả lớp và ngại hỏi câu cơ bản nên hạ tay xuống.
2. **9h30 — Giờ giải lao (Tìm cách hỏi giáo viên):** Đến giờ nghỉ giải lao 10 phút, user chạy xuống bàn giảng viên định hỏi lại chỗ slide 20. Tuy nhiên, có 3-4 bạn khác cũng đang vây quanh hỏi thầy về bài tập lớn và đồ án. User đứng chờ khoảng 5 phút nhưng thầy chưa trả lời xong cho bạn trước thì chuông báo hết giờ giải lao, thầy phải quay lại bục giảng bắt đầu tiết tiếp theo nên user không kịp hỏi.
3. **9h45 — Hỏi bạn bè xung quanh:** Quay về chỗ ngồi, user quay sang thì thầm hỏi bạn ngồi cạnh: *"Ê, đoạn slide 20 lúc nãy chỗ đạo hàm sao ra được thế kia ấy nhỉ?"*. Bạn ngồi cạnh lắc đầu: *"Đoạn đấy tao cũng đang lú đây, thầy lướt nhanh quá tao chưa kịp ghi lại"*. User quay xuống hỏi tiếp bạn bàn dưới thì bạn trả lời mơ hồ: *"Hình như áp dụng công thức bài trước hay sao á, tí về tra mạng xem sao chứ giờ tao cũng chịu"*.
4. **10h30 — Bế tắc khi làm bài thực hành tại lớp:** Cả lớp chuyển sang phần Hands-on Lab code bài tập thực hành. Do không hiểu bản chất bước biến đổi ở slide 20, user không biết cách truyền tham số và viết hàm cập nhật trọng số trong code. Định vẫy tay gọi Trợ giảng (TA), nhưng lúc đó bạn TA đang phải hỗ trợ xử lý lỗi môi trường/cài thư viện cho các bạn ở dãy bàn bên kia.
5. **11h30 — Hết giờ học và bỏ dở:** Hết buổi học, bài lab thực hành trên lớp mới hoàn thành được 30%. User đành lưu file dở dang và xin nộp bù bài tập về nhà sau.
6. **20h00 — Về nhà tự xoay sở:** Buổi tối mở lại slide tự đọc, mở ChatGPT và Google tra cứu. Do ChatGPT giải thích ra công thức toán học tổng quát dài 6 trang và dùng ký hiệu khác với slide của thầy, user mất gần 1.5 tiếng đọc tài liệu bên ngoài đến hơn 22h đêm mới hiểu được tạm thời để code xong bài lab.

---

### 2.3. Khó khăn gặp phải và cách chữa cháy (Workarounds)

* **Điểm nghẽn cốt lõi (Core Barrier):**
  * **Thiếu thời gian tương tác trên lớp:** Tiến độ bài giảng quá nhanh, thời lượng tiết học có hạn, tỷ lệ học viên/giảng viên đông khiến giảng viên không thể dừng lại giải thích cặn kẽ cho từng cá nhân.
  * **Rào cản tâm lý xã hội (Social/Classroom Friction):** Tâm lý e ngại ngắt lời giảng viên, sợ bị coi là "hỏi câu ngớ ngẩn/cơ bản" trước mặt cả lớp.
  * **Mạng lưới hỗ trợ tức thì (Peer Support) bị tê liệt:** Bạn bè xung quanh cũng gặp tình trạng "nghẽn nhận thức" tương tự nên không thể hỗ trợ chéo cho nhau.
* **Các Workarounds đã sử dụng:**
  1. *Workaround 1 (Tranh thủ giờ giải lao hỏi thầy):* Chờ đợi nhưng thất bại do đông người và hết giờ nghỉ giải lao.
  2. *Workaround 2 (Hỏi bạn bè xung quanh):* Hỏi 2 bạn cùng lớp $\rightarrow$ Nhận lại sự mơ hồ, phỏng đoán hoặc sự đồng cảm "tao cũng chưa hiểu".
  3. *Workaround 3 (Chờ Trợ giảng trên lớp):* Tìm TA trong giờ thực hành $\rightarrow$ Bị nghẽn do TA quá tải hỗ trợ lỗi kỹ thuật cho nhiều học viên khác.
  4. *Workaround 4 (Về nhà tự tra cứu Google/ChatGPT):* Mở tab tìm kiếm và prompt hỏi AI sau giờ học $\rightarrow$ Mất nhiều thời gian lọc tài liệu, giải thích lệch ngữ cảnh bài học trên lớp.
* **Mức độ hiệu quả của Workaround:** Rất thấp (~25 - 30%), hoàn toàn bỏ lỡ "thời điểm vàng" để hiểu bài và làm bài thực hành ngay tại lớp.

---

### 2.4. Hậu quả hoặc chi phí thực tế (Cost & Consequence)

* **Thời gian lãng phí:** Tốn thêm gần 90 phút buổi tối ở nhà chỉ để tự mò mẫm một đoạn kiến thức đáng lẽ chỉ cần 3-5 phút giải thích trên lớp.
* **Hiệu ứng gãy đổ dây chuyền (Snowball Effect):** Việc bị nghẽn ở slide 20 lúc 9h15 khiến user bị "mất kết nối" (disengaged) toàn bộ 1.5 tiếng học lý thuyết và thực hành tiếp theo của buổi học, ngồi nghe giảng như "vịt nghe sấm".
* **Hậu quả trực tiếp:** Không hoàn thành bài lab thực hành đúng hạn trên lớp, phải xin gia hạn nộp bù bài tập về nhà.
* **Tác động tâm lý:** Cảm giác tự ti, lo lắng vì thấy các bạn khác vẫn làm bài, sợ mình bị tụt hậu so với tiến độ chung của lớp; ức chế vì bỏ thời gian đi học trên lớp nhưng vẫn phải về nhà tự học lại từ đầu.

---

### 2.5. Điều bất ngờ, trái giả thuyết hoặc exact quotes

* **Exact Quotes đắt giá từ người tham gia:**

  > *"Lúc thầy giảng lướt qua đoạn slide đó, mình nhìn quanh thấy mấy bạn cứ gật gù nhìn màn hình, tưởng mọi người hiểu hết rồi nên ngại không dám giơ tay ngắt lời thầy. Đến giờ giải lao chạy lên định hỏi thì các bạn bu quanh bàn thầy đông quá, chưa kịp mở lời thì chuông đã reo vào tiết mới."*
  >

  > *"Quay sang hỏi thằng bạn bên cạnh thì nó bảo: 'Tao cũng đang chịu chết, thấy thầy lướt qua nhanh như một cơn gió'. Cảm giác lúc đó bị 'rơi' khỏi bài giảng luôn, những slide phía sau thầy nói gì mình cũng không thể load nổi vào đầu nữa."*
  >
* **Phát hiện bất ngờ & Trái ngược giả thuyết ban đầu (Counter-Hypothesis Evidence):**

  1. *Về rào cản tâm lý phòng học (Classroom Social Barrier):* Giả thuyết ban đầu nghĩ rằng học viên không hỏi là do lười hoặc không chủ động. Thực tế học viên **rất muốn hỏi** (đã định giơ tay, đã chạy lên bàn thầy giờ giải lao, đã quay sang hỏi 2 bạn), nhưng bị chặn lại bởi rào cản thời gian tiết học và tâm lý sợ làm gián đoạn lớp học đông người.
  2. *Về sự thất bại của giải pháp hỏi bạn bè (Peer Help Breakdown):* Trong các lớp học kỹ thuật, việc hỏi bạn cùng bàn thường không hiệu quả vì khi gặp một slide trừu tượng, phần lớn học viên đều bị nghẽn cùng một lúc. Câu trả lời của bạn bè thường là phỏng đoán thiếu chính xác, càng làm học viên thêm hoang mang.
  3. *Tác động dây chuyền nghiêm trọng:* Không hiểu một slide nền tảng ở đầu buổi học sẽ vô hiệu hóa hoàn toàn giá trị của toàn bộ thời gian học còn lại trên lớp.

---

## 3. TỰ ĐÁNH GIÁ VÀ RÚT KINH NGHIỆM CỦA NGƯỜI PHỎNG VẤN (INTERVIEWER REFLECTION)

* **Kỹ thuật phỏng vấn đã thực hiện tốt:**

  * Khởi đầu bằng câu hỏi mở chuẩn xác: *"Kể mình nghe về lần gần nhất bạn ngồi học trên lớp gặp một slide khó hiểu mà không kịp hỏi giáo viên hoặc bạn bè?"*.
  * Đào sâu vào diễn biến tâm lý và hành động cụ thể tại từng thời điểm trên lớp (lúc thầy giảng, lúc giờ giải lao, lúc hỏi bạn bè, lúc làm bài thực hành).
  * Không hề gợi ý hay nhắc đến giải pháp AI, tập trung hoàn toàn vào rào cản giao tiếp và hậu quả thực tế của người học.
* **Điểm cần cải thiện cho các lần phỏng vấn tiếp theo:**

  * Cần hỏi sâu hơn về cách học viên ghi chú lại những điểm chưa hiểu trên slide ngay lúc đó (ví dụ: có đánh dấu sao, chụp ảnh màn hình hay ghi chú gì vào vở/laptop không).
  * Cần kiểm soát thời gian tốt hơn ở phần người được phỏng vấn kể về các môn học khác để giữ câu chuyện bám sát sự kiện cụ thể trong 7 ngày gần nhất.
