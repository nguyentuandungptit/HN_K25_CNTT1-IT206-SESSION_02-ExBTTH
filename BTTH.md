# Kế hoạch vận hành Agile cho dự án GreenMart

## 1. Lý do chọn Agile thay vì Waterfall

### Khó khăn của Waterfall khi yêu cầu thay đổi
Mô hình Waterfall yêu cầu khảo sát và đóng băng toàn bộ yêu cầu ngay từ đầu dự án. Với chuỗi 30 siêu thị GreenMart đang mở rộng sang bán hàng đa kênh, hành vi mua sắm của khách hàng và quy trình vận hành kho quầy thực tế thay đổi liên tục. Nếu áp dụng Waterfall, việc chốt cứng tài liệu ban đầu sẽ biến mọi thay đổi phát sinh thành sự cố kế hoạch, đòi hỏi thủ tục phê duyệt phức tạp, gây lãng phí chi phí sửa chữa và khiến sản phẩm cuối cùng dễ bị lệch khỏi nhu cầu vận hành thực tế.

### Cách tinh thần Agile khắc phục khó khăn
Agile chia nhỏ dự án thành các chu kỳ ngắn và chấp nhận sự thay đổi như một phần tự nhiên của quá trình phát triển. Khách hàng được trực tiếp trải nghiệm phần mềm chạy được sau mỗi vòng lặp ngắn để góp ý kịp thời. Nhờ vậy, đội ngũ TechViet có thể linh hoạt điều chỉnh danh sách tính năng theo phản hồi thực tế mà không phải đập bỏ và làm lại các cấu trúc hệ thống lớn.

### Kết luận
Dự án GreenMart mang đặc thù chuyển đổi số bán lẻ với nhiều biến số thị trường chưa thể xác định trọn vẹn ngay từ đầu. Áp dụng Agile là lựa chọn phù hợp để giảm thiểu rủi ro đầu tư, duy trì tiến độ bàn giao đều đặn và đảm bảo sản phẩm đáp ứng sát sao nhu cầu của 30 siêu thị.

---

## 2. Nguyên tắc làm việc theo 4 giá trị Agile

| Thói quen cũ của đội | Giá trị Agile bị đi ngược | Đề xuất cách làm mới phù hợp |
| :--- | :--- | :--- |
| Cả đội chỉ trao đổi qua bình luận trên phần mềm, gần như không họp trực tiếp. | **Cá nhân và sự tương tác** hơn là quy trình và công cụ | Duy trì trao đổi trực tiếp hoặc họp nhanh ngắn gọn hằng ngày (Daily Scrum 15 phút) để giải quyết vướng mắc nhanh chóng. Công cụ phần mềm chỉ dùng để lưu trữ trạng thái thẻ việc, không thay thế cho đối thoại trực tiếp. |
| Viết tài liệu đặc tả rất chi tiết trước, chỉ trình diễn sản phẩm một lần ở cuối dự án. | **Phần mềm chạy tốt** hơn là tài liệu đầy đủ | Giữ tài liệu ở mức vừa đủ (dạng User Story và tiêu chí chấp nhận cụ thể). Tập trung nguồn lực để hoàn thành phần mềm chạy được, bàn giao và kiểm nghiệm thực tế sau mỗi chu kỳ Sprint. |
| Hợp đồng tính phí và bắt chờ 2 tuần phê duyệt mỗi khi khách muốn đổi yêu cầu. | **Hợp tác với khách hàng** hơn là đàm phán hợp đồng | Product Owner chủ động làm việc định kỳ với GreenMart để lắng nghe phản hồi và thỏa thuận đưa các yêu cầu mới vào Product Backlog một cách minh bạch, loại bỏ các thủ tục phê duyệt hành chính kéo dài. |
| Khi thực tế khác với kế hoạch, đội vẫn làm đúng theo kế hoạch đã duyệt ban đầu. | **Phản hồi với thay đổi** hơn là bám sát kế hoạch | Đội ngũ định kỳ rà soát và điều chỉnh kế hoạch sau mỗi Sprint. Sẵn sàng thay đổi thứ tự ưu tiên của các tính năng để kịp thời phục vụ mục tiêu kinh doanh mới nhất của chuỗi siêu thị. |

---

## 3. Khung Scrum

### Độ dài Sprint cố định
Đội thống nhất chọn độ dài Sprint cố định là **2 tuần** (chia giai đoạn 6 tuần đầu thành đúng 3 Sprint trọn vẹn).

### Lý do lựa chọn gắn với 3 trụ cột Scrum
- **Minh bạch (Transparency):** Nhịp 2 tuần giúp toàn bộ tiến độ, các vướng mắc kỹ thuật và trạng thái công việc hiển thị rõ ràng trên bảng Scrum và mã nguồn thực tế mà không bị che giấu.
- **Thanh tra (Inspection):** Cứ sau 2 tuần, đại diện GreenMart được trực tiếp kiểm nghiệm bản phần mềm chạy được tại sự kiện Sprint Review để đánh giá tính đúng đắn của các tính năng bán hàng.
- **Thích nghi (Adaptation):** Những góp ý từ buổi Sprint Review và bài học rút ra từ buổi Sprint Retrospective được chuyển hóa thành các điều chỉnh cụ thể cho Product Backlog và quy trình làm việc ngay trong Sprint tiếp theo.

### Lý do chọn Scrum thay vì tiếp tục Waterfall
Scrum cung cấp khung thời gian cố định rõ ràng, vừa giúp đội duy trì nhịp làm việc ổn định và kỷ luật, vừa tạo ra các điểm dừng định kỳ để thích ứng nhanh với những thay đổi trong mô hình bán hàng đa kênh của GreenMart.

---

## 4. Phân vai Scrum Team

Đội dự án gồm 6 thành viên TechViet với trách nhiệm cụ thể như sau:

### Product Owner (Long)
- **Được quyết định:** Thứ tự ưu tiên và nội dung các hạng mục trên Product Backlog; xác định tiêu chí chấp nhận cho từng tính năng; quyết định nghiệm thu bản tăng trưởng sản phẩm (Increment) ở cuối mỗi Sprint.
- **Không được quyết định:** Giải pháp kiến trúc kỹ thuật, lựa chọn công nghệ, ước lượng thời gian lập trình hoặc giao việc cụ thể cho từng thành viên trong nhóm phát triển.

### Scrum Master (Hoa)
- **Được quyết định:** Cách thức tổ chức và điều phối các sự kiện Scrum; phương pháp tháo gỡ khó khăn và rào cản quy trình; hướng dẫn đội tuân thủ đúng nguyên tắc Agile và Scrum.
- **Không được quyết định:** Thứ tự ưu tiên của các tính năng trên Product Backlog, không quản lý nhân sự hay giao việc như quản lý dự án truyền thống.

### Nhóm phát triển (An, Bình, Chi là Developers; Dung là Tester)
- **Được quyết định:** Giải pháp kỹ thuật, cách thức triển khai mã nguồn, phương pháp kiểm thử, tự phân bổ công việc trong Sprint Backlog và cam kết khối lượng công việc hoàn thành theo Định nghĩa hoàn thành (Definition of Done).
- **Không được quyết định:** Tự ý đổi thứ tự ưu tiên trên Product Backlog hoặc cắt giảm yêu cầu nghiệp vụ của Product Owner mà chưa có sự đồng thuận.

---

## 5. Artifacts và Lịch sự kiện

### 5.1. Product Backlog cho 6 tuần đầu (Sắp xếp theo thứ tự ưu tiên)

1. **PBI-01: Tìm kiếm sản phẩm theo danh mục và định vị siêu thị gần nhất còn hàng.**
   *Lý do:* Nền tảng cốt lõi của bán hàng đa kênh. Khách hàng phải tìm thấy sản phẩm và biết siêu thị nào có sẵn hàng trước khi thực hiện các bước mua sắm.
2. **PBI-02: Xem chi tiết sản phẩm, giá bán khuyến mãi và quản lý giỏ hàng online.**
   *Lý do:* Cho phép người dùng thu thập các món hàng cần mua và tính toán sơ bộ chi phí đơn hàng.
3. **PBI-03: Đặt hàng đa kênh và lựa chọn hình thức nhận hàng (giao tận nhà hoặc nhận tại quầy siêu thị).**
   *Lý do:* Hoàn thiện luồng đặt hàng trực tuyến, kết nối trải nghiệm mua online với hệ thống 30 siêu thị vật lý.
4. **PBI-04: Tích hợp thanh toán trực tuyến qua cổng VNPAY, thẻ ngân hàng và lựa chọn thanh toán khi nhận hàng (COD).**
   *Lý do:* Đảm bảo luồng giao dịch tài chính thông suốt và đa dạng hóa hình thức trả tiền cho khách hàng.
5. **PBI-05: Đồng bộ dữ liệu tồn kho thời gian thực giữa website bán hàng và hệ thống quản trị tại từng siêu thị.**
   *Lý do:* Ngăn chặn rủi ro khách đặt mua sản phẩm nhưng tại siêu thị thực tế đã hết hàng.
6. **PBI-06: Tra cứu lịch sử đơn hàng và nhận thông báo trạng thái vận chuyển qua SMS hoặc email.**
   *Lý do:* Tăng cường trải nghiệm khách hàng sau mua và giảm tải cho bộ phận chăm sóc khách hàng.

### 5.2. Kế hoạch cho Sprint 1

- **Mục tiêu Sprint 1 (Sprint Goal):** Khách hàng có thể tìm kiếm sản phẩm theo siêu thị GreenMart gần nhất và thêm sản phẩm vào giỏ hàng thành công.
- **Sprint Backlog của Sprint 1:**
  1. Thiết kế cơ sở dữ liệu và API tìm kiếm sản phẩm theo vị trí siêu thị.
  2. Xây dựng giao diện tìm kiếm và bộ lọc sản phẩm trên nền tảng web.
  3. Xây dựng API và giao diện quản lý giỏ hàng (thêm, sửa số lượng, xóa món hàng).
  4. Viết kịch bản kiểm thử tự động cho luồng tìm kiếm và giỏ hàng.
  5. Kiểm thử chức năng và kiểm thử hiệu năng cho các API mới.
- **Bản tăng trưởng (Increment) mong đợi cuối Sprint 1:**
  Một module phần mềm chạy được trên môi trường thử nghiệm (staging), cho phép người dùng mở ứng dụng, tìm kiếm sản phẩm tại một siêu thị cụ thể và thêm vào giỏ hàng mà không gặp lỗi kỹ thuật, đáp ứng đầy đủ Định nghĩa hoàn thành (code đã review nội bộ, kiểm thử đạt yêu cầu).

### 5.3. Lịch 5 sự kiện của một Sprint (Chu kỳ 2 tuần)

1. **Sprint Planning:** Diễn ra vào sáng Thứ Hai đầu Sprint (khoảng 3 đến 4 giờ). Toàn đội cùng chốt Sprint Goal, chọn các hạng mục từ Product Backlog đưa vào Sprint Backlog và phân rã công việc kỹ thuật.
2. **Daily Scrum:** Diễn ra mỗi sáng từ Thứ Ba đến Thứ Sáu, cố định 15 phút vào 9:00 sáng. Các thành viên nhóm phát triển đồng bộ tiến độ, chia sẻ dự định trong ngày và phát hiện sớm các trở ngại kỹ thuật.
3. **Sprint (Thời gian thực thi):** Diễn ra liên tục trong 2 tuần (10 ngày làm việc). Nhóm phát triển tự chủ lập trình, kiểm thử và tích hợp liên tục để tạo ra bản tăng trưởng đạt chuẩn.
4. **Sprint Review:** Diễn ra vào chiều Thứ Sáu cuối Sprint (khoảng 1.5 đến 2 giờ). Đội trình diễn bản tăng trưởng chạy được cho đại diện GreenMart xem, tiếp nhận phản hồi thực tế và cập nhật lại Product Backlog.
5. **Sprint Retrospective:** Diễn ra ngay sau buổi Sprint Review vào chiều Thứ Sáu cuối Sprint (khoảng 1 giờ). Toàn đội cùng nhìn lại cách phối hợp, quy trình làm việc và công cụ, thống nhất ít nhất một hành động cải tiến cụ thể cho Sprint kế tiếp.

---

## 6. Xử lý tình huống thay đổi

### Tình huống 1: Giữa Sprint, khách GreenMart muốn đổi thứ tự ưu tiên (làm tính năng đặt hàng online trước)
- **Cách tiếp nhận:** Long (Product Owner) trực tiếp trao đổi với GreenMart để ghi nhận và làm rõ yêu cầu. Long đưa yêu cầu này vào Product Backlog và xếp lên vị trí ưu tiên hàng đầu cho Sprint tiếp theo.
- **Bảo vệ Sprint hiện tại:** Đội ngũ TechViet tiếp tục giữ vững kế hoạch của Sprint 1 để hoàn thành mục tiêu Sprint Goal đã cam kết, không làm gián đoạn công việc đang dở. Tính năng đặt hàng online sẽ được đưa vào lựa chọn chính thức tại buổi Sprint Planning của Sprint 2.

### Tình huống 2: Đến buổi Sprint Review, một tính năng vẫn chưa hoàn thành
- **Cách xử lý khi trình diễn:** Đội không trình diễn tính năng chưa hoàn thành hoặc chưa đạt Định nghĩa hoàn thành cho đại diện GreenMart xem để giữ vững tính minh bạch. Đội thẳng thắn thông báo về phần việc chưa xong kèm lý do kỹ thuật ngắn gọn.
- **Xử lý sau buổi họp:** Phần việc chưa hoàn thành được chuyển ngược về Product Backlog để Product Owner đánh giá lại độ ưu tiên. Trong buổi Sprint Retrospective ngay sau đó, cả đội cùng tìm hiểu nguyên nhân gốc rễ để điều chỉnh lại năng lực cam kết trong các Sprint sau.
