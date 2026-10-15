# CHỌN KỸ THUẬT RETROSPECTIVE CHO NHÓM ÍT NGƯỜI DÁM NÓI — RikkeiAssist, Sprint 13

## Phần 1 — Hai phương án

Buổi họp 60 phút, chỉ có Scrum Team (7 người, không mời quản lý). Một thành viên chỉ dự 45 phút đầu nên các bước tạo Insight và chọn Improvement đều nằm trong 45 phút đầu. Ở cả hai phương án, thẻ được viết ẩn danh trước rồi mới dán lên bảng, vì có thành viên có thể không ghi vấn đề nhạy cảm nếu viết công khai ngay.

| Bước | Phương án A (Start–Stop–Continue) | Phương án B (4Ls) |
|---|---|---|
| **1. Mở đầu (0–5')** | Scrum Master nêu mục tiêu và quy tắc: mỗi thẻ một ý, mô tả hành vi, không nêu tên; xem nhanh Improvement cũ ("chạy Integration Test sớm" và các Improvement Sprint 12) chưa có kết quả. | Cùng quy tắc và cùng xem Improvement cũ; giới thiệu 4 cột: Liked (điều thích), Learned (điều học được), Lacked (điều còn thiếu), Longed for (điều mong muốn). |
| **2. Thu thập dữ liệu (5–20')** | Mỗi người viết thẻ ẩn danh vào 3 cột Start, Stop, Continue (5'); Scrum Master dán lên bảng chung, cả nhóm đọc. | Mỗi người viết thẻ ẩn danh vào 4 cột Liked, Learned, Lacked, Longed for (5'); dán lên bảng chung, cả nhóm đọc. Cột Learned có chỗ cho điều chưa hiểu rõ. |
| **3. Rút ra Insight (20–35')** | Gom thẻ thành Theme; với Theme nhiều thẻ nhất, hỏi "vì sao" để tìm nguyên nhân, đối chiếu với Data (O-01 đến O-04). | Gom thẻ thành Theme; dùng Lacked và Learned để tìm nguyên nhân gốc, dùng Liked (ví dụ Pairing xử lý lỗi nhanh) để biết điều nên giữ. |
| **4. Quyết định hành động (35–45')** | Nhóm bỏ phiếu chọn tối đa 2 Theme, chuyển các thẻ Start/Stop thành Improvement; Scrum Master hỗ trợ điều phối, không chọn thay nhóm. | Nhóm bỏ phiếu chọn tối đa 2 Theme, chuyển Lacked/Longed for thành Improvement; Scrum Master điều phối, không chọn thay nhóm. |
| **5. Kết thúc (45–60')** | Đọc lại Improvement, chốt người theo dõi, lúc kiểm tra, bằng chứng; chuyển phản hồi sản phẩm (O-05) cho Product Owner; mỗi người nói một câu về buổi họp. | Như A; thêm vòng chia sẻ ngắn về Learned, để người mới và người ít phát biểu nói về điều đã học và điều chưa rõ. |

---

## Phần 2 — So sánh

| Tiêu chí | Start–Stop–Continue | 4Ls | Dữ liệu làm căn cứ |
|---|---|---|---|
| **Tìm nguyên nhân và điều học được** | Trung bình: cho biết nên bắt đầu, dừng, tiếp tục gì, nhưng ít chỗ cho nguyên nhân và điều học được. | **Tốt hơn:** Lacked và Learned giúp lộ nguyên nhân và điều học được; Liked ghi nhận điều đang tốt. | Hai người muốn có thời gian nói về trải nghiệm và điều học được; O-01 (quyền đến Ngày 4, test bắt đầu Ngày 8), O-02 (quy tắc đổi chỉ qua tin nhắn riêng) và O-04 (người mới không hiểu từ "nghiêm trọng") đều cần tìm nguyên nhân; O-03 (Pairing 45 phút) cho thấy điều nên giữ. |
| **Chuyển thành hành động** | **Tốt hơn:** thẻ Start/Stop gần như là hành động sẵn. | Cần thêm bước chuyển từ Lacked/Longed for sang hành động, nên chậm hơn. | 5/7 người muốn buổi họp tập trung vào hành động; Improvement cũ chỉ được kiểm tra 2,1/5. |
| **Phù hợp thời lượng và thành viên mới** | Nhanh, ít cột, nhưng ít chỗ để người mới nói điều chưa hiểu. | Nhiều cột hơn nên cần quản lý thời gian; bù lại cột Learned/Lacked giúp người mới nêu điều chưa hiểu mà không phải hỏi trực tiếp. | 60 phút, một người chỉ dự 45 phút đầu; mức dễ nói thẳng 2,8/5 (2/7 chọn 1 hoặc 2); O-04 (không dám hỏi). |

---

## Phần 3 — Chọn và làm thử

**Phương án chọn: 4Ls.**

**Lý do:** Vấn đề của nhóm nằm ở nguyên nhân và điều học được: quyền môi trường thử nghiệm đến muộn, quy tắc đổi qua tin nhắn riêng, người mới không dám hỏi, Improvement cũ không được theo dõi. 4Ls thu đúng loại thông tin này và có chỗ cho người ít phát biểu. **Điều phải đánh đổi:** 4Ls chậm hơn tới hành động trong khi 5/7 người muốn hành động; nhóm bù bằng cách chỉ dành 10 phút cho bước quyết định, chọn tối đa 2 Improvement và hoàn tất trong 45 phút đầu.

### Ba thẻ mẫu (một ý, không nêu tên)

| Cột | Nội dung thẻ |
|---|---|
| Lacked | Quyền môi trường thử nghiệm của người kiểm thử chỉ có đủ từ Ngày 4. |
| Lacked | Thay đổi quy tắc chuyển người chỉ được gửi qua tin nhắn riêng, tài liệu chung không có. |
| Learned | Thuật ngữ "nghiêm trọng" chưa được giải thích nên có người không hiểu mà chưa dám hỏi. |

### Theme

**"Điều kiện làm việc và thông tin cần thiết chưa đến đúng người vào đúng lúc"** (gom 3 thẻ trên).

### Improvement

| Hành động | Người/nhóm theo dõi | Khi kiểm tra | Bằng chứng |
|---|---|---|---|
| Vào Ngày 1 của mỗi Sprint, nhóm rà một danh sách chuẩn bị gồm: quyền môi trường thử nghiệm của từng người, quy tắc chuyển người hiện hành trong tài liệu chung, và giải nghĩa thuật ngữ mới (bắt đầu với "nghiêm trọng"); mục nào chưa xong thì nêu tại Daily Scrum cùng ngày. Khi quy tắc đổi, cập nhật tài liệu chung trước khi áp dụng. Danh sách cũng ghi ngày bắt đầu Integration Test để theo dõi Improvement cũ. | Scrum Master phối hợp Khánh Vy (đề xuất để Scrum Team cùng thống nhất) | Ngày 1 của Sprint 14; xem lại tại Sprint Retrospective Sprint 14 | Danh sách chuẩn bị có xác nhận không muộn hơn Ngày 1; lịch sử phiên bản tài liệu quy tắc có ngày cập nhật trước ngày áp dụng; bảng thuật ngữ có mục "nghiêm trọng"; ngày bắt đầu Integration Test trong danh sách |

### Xử lý O-05

O-05 (Chủ cửa hàng hài lòng với nút báo câu trả lời sai; CSKH lo 3 ca khiếu nại bị chuyển muộn) là **phản hồi sản phẩm**, không phải chuyện cách làm việc. Phản hồi này được chuyển cho **Product Owner** để xem xét trong Product Backlog, không đưa vào bảng thẻ của Retrospective.
