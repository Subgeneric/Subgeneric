# THUYẾT MINH DỰ ÁN KHỞI NGHIỆP
## SUBGENERIC — Bộ công cụ Hóa học tương tác dành cho học sinh Việt Nam

> **Bản dự thảo phục vụ hồ sơ cuộc thi.** Trước khi nộp, nhóm cần điền các mục trong ngoặc vuông, xác minh thông tin nhóm và bổ sung minh chứng khảo sát người dùng. Không trình bày các giả định dưới đây như kết quả khảo sát đã thực hiện.

## 1. Thông tin chung

- **Tên dự án:** Subgeneric
- **Lĩnh vực:** Giáo dục, công nghệ số và công cụ hỗ trợ học tập
- **Đơn vị/nhóm phát triển:** Nhóm học sinh Trường THCS và THPT Trần Đại Nghĩa
- **Đại diện nhóm:** [Họ tên trưởng nhóm]
- **Thành viên:** [Họ tên và phần việc của từng thành viên; tối đa theo thể lệ cuộc thi]
- **Giáo viên hướng dẫn:** [Họ tên, chức vụ/đơn vị]
- **Website demo:** https://subgeneric.github.io/Subgeneric/ [Kiểm tra lại URL triển khai trước khi nộp]
- **Mã nguồn:** https://github.com/Subgeneric/Subgeneric

## 2. Tóm tắt dự án

Subgeneric là bộ công cụ Hóa học tương tác do học sinh phát triển, hướng đến việc giúp học sinh Việt Nam học và luyện tập Hóa học thông qua thao tác trực tiếp với các bài toán và mô phỏng trực quan. Phiên bản hiện tại gồm trang tính toán phản ứng hóa học với các chức năng cân bằng phương trình, tính khối lượng mol, tính toán theo phương trình, xác định chất giới hạn và hiệu suất phản ứng; cùng mô phỏng chuẩn độ acid–base với burette, bình tam giác, lựa chọn dung dịch và chất chỉ thị, theo dõi thể tích dung dịch đã thêm và điểm tương đương.

Dự án bắt đầu từ một vấn đề học tập dễ gặp: nhiều nội dung Hóa học vừa đòi hỏi tính toán nhiều bước, vừa khó hình dung nếu chỉ đọc công thức hoặc xem hình tĩnh. Subgeneric gom các công cụ liên quan vào một nơi, cho phép người học thử dữ liệu, quan sát kết quả và tự kiểm tra cách làm. Hiện sản phẩm ở giai đoạn demo; bước tiếp theo là thử nghiệm với người học, thu thập phản hồi, cải thiện độ chính xác và khả năng sử dụng, rồi mới quyết định lộ trình mở rộng và mô hình doanh thu phù hợp.

## 3. Vấn đề và nhu cầu

### 3.1. Vấn đề cần giải quyết

- **Khoảng cách giữa công thức và hình dung:** Một số nội dung như chuẩn độ acid–base, điểm tương đương hoặc sự thay đổi màu chất chỉ thị khó hình dung nếu chỉ học qua văn bản.
- **Nhiều bước tính toán:** Cân bằng phương trình, đổi giữa mol và khối lượng, tính lượng chất, chất giới hạn và hiệu suất đòi hỏi người học theo dõi nhiều bước.
- **Công cụ học tập phân tán:** Người học có thể phải chuyển giữa nhiều trang hoặc tự tính thủ công để kiểm tra kết quả.
- **Nhu cầu tự học:** Học sinh cần công cụ có thể dùng ngoài giờ học để thử ví dụ, kiểm tra hiểu biết và ôn tập theo tốc độ của mình.

Đây là những vấn đề nhóm đặt ra để kiểm chứng, không phải kết luận từ khảo sát định lượng. Nhóm cần bổ sung minh chứng thực tế trước khi nộp: [số học sinh/giáo viên được hỏi], [thời gian khảo sát], [câu hỏi khảo sát], [kết quả nổi bật] và [trích dẫn phản hồi đã được cho phép sử dụng].

### 3.2. Người dùng mục tiêu

- **Nhóm chính:** Học sinh THCS và THPT đang học các chủ đề Hóa học phù hợp với chương trình của mình.
- **Nhóm sử dụng hỗ trợ:** Giáo viên có thể dùng công cụ để minh họa một số phép tính hoặc hiện tượng trong giờ học.
- **Người ảnh hưởng đến quyết định sử dụng:** Giáo viên, phụ huynh, câu lạc bộ học tập và nhà trường.

Trong giai đoạn đầu, nhóm ưu tiên học sinh có nhu cầu tự học và luyện tập. Phạm vi bài học cụ thể cần được đối chiếu với chương trình hiện hành và kiểm thử cùng giáo viên bộ môn.

## 4. Giải pháp và sản phẩm

### 4.1. Bộ công cụ phản ứng và tính toán

Trang **Phản ứng và tính toán** hiện có bốn nhóm chức năng:

1. **Cân bằng phương trình hóa học:** Nhập phương trình và nhận hệ số cân bằng.
2. **Khối lượng mol và phần trăm khối lượng:** Nhập công thức hóa học để tính khối lượng mol và phần trăm khối lượng của các nguyên tố.
3. **Tính toán theo phương trình hóa học:** Dựa vào phương trình và lượng chất đã biết để tính lượng chất liên quan.
4. **Chất giới hạn và hiệu suất phản ứng:** So sánh lượng chất phản ứng, xác định chất giới hạn, tính lượng sản phẩm lý thuyết và có thể tính hiệu suất khi nhập khối lượng sản phẩm thực tế.

### 4.2. Mô phỏng chuẩn độ acid–base

Trang mô phỏng biểu diễn burette phía trên bình tam giác. Người dùng có thể chọn acid, nồng độ và thể tích acid, nồng độ NaOH, chất chỉ thị, thêm dung dịch theo từng lượng hoặc chạy tự động, đồng thời quan sát màu dung dịch và các thông số như thể tích đã thêm, pH và thể tích tại điểm tương đương.

Mô phỏng phục vụ học tập và giải thích khái niệm; **không thay thế thí nghiệm thực tế, hướng dẫn của giáo viên hoặc quy trình an toàn phòng thí nghiệm**.

### 4.3. Trải nghiệm sử dụng

- Website dùng tiếng Việt và bố cục tập trung vào từng công cụ.
- Có chế độ sáng/tối để người dùng lựa chọn.
- Các trang công cụ liên kết với trang chủ để người dùng chuyển đổi giữa tính toán và mô phỏng.
- Người dùng có thể gửi góp ý qua biểu mẫu: https://forms.gle/YhbTJZdVpVYnKRgr7

## 5. Giá trị mang lại và điểm khác biệt

Subgeneric hướng đến bốn giá trị chính:

- **Tương tác thay vì chỉ đọc:** Người học tự nhập dữ liệu và quan sát kết quả.
- **Kết hợp tính toán và mô phỏng:** Nhiều thao tác tính toán phản ứng và mô phỏng chuẩn độ được tổ chức trong cùng một website.
- **Tiếp cận thuận tiện:** Có thể truy cập qua trình duyệt mà không cần cài ứng dụng riêng, tùy vào thiết bị và kết nối Internet.
- **Phát triển theo phản hồi:** Dự án có kênh góp ý để ưu tiên cải thiện dựa trên nhu cầu thực tế.

Điểm khác biệt của dự án không nên được tuyên bố là “đầu tiên” hoặc “duy nhất” nếu chưa có phân tích đối thủ. Cách diễn đạt phù hợp ở giai đoạn hiện tại là: **Subgeneric thử nghiệm một trải nghiệm học Hóa bằng tiếng Việt, kết hợp bộ công cụ tính toán phản ứng với mô phỏng chuẩn độ trong một website gọn nhẹ.**

## 6. Mức độ hoàn thiện và kế hoạch phát triển

### 6.1. Trạng thái hiện tại

- Đã có website demo và mã nguồn công khai.
- Đã triển khai các công cụ tính toán phản ứng và mô phỏng chuẩn độ nêu ở Mục 4.
- Đã có giao diện tiếng Việt, điều hướng giữa các trang và chế độ sáng/tối.
- Đã có biểu mẫu tiếp nhận góp ý.

Nhóm cần kiểm thử lại tất cả chức năng trước khi nộp và lưu minh chứng: ảnh chụp màn hình, video thao tác, danh sách ca kiểm thử và lỗi đã xử lý. Không nên tuyên bố đã được kiểm định độc lập hoặc đã chứng minh hiệu quả học tập nếu chưa có bằng chứng.

### 6.2. Lộ trình đề xuất

| Giai đoạn | Công việc | Kết quả cần đo |
|---|---|---|
| 1. Kiểm thử demo | Kiểm tra các trường hợp tính toán, giao diện trên điện thoại/máy tính và lỗi nhập liệu | Danh sách ca kiểm thử, tỷ lệ ca đạt, lỗi nghiêm trọng đã xử lý |
| 2. Thử nghiệm người dùng | Mời học sinh và giáo viên dùng thử theo nhiệm vụ cụ thể; lấy phản hồi tự nguyện | Số người tham gia, tỷ lệ hoàn thành nhiệm vụ, vấn đề được ghi nhận |
| 3. Cải tiến nội dung | Sửa lỗi, bổ sung giải thích từng bước và ví dụ theo chủ đề ưu tiên | Số lỗi được sửa, số bài/chủ đề được bổ sung |
| 4. Thử nghiệm mô hình duy trì | So sánh nhu cầu đối với phiên bản miễn phí, gói trường học hoặc tài trợ | Phản hồi về mức sẵn lòng sử dụng/trả phí; chi phí vận hành ước tính |
| 5. Mở rộng có kiểm soát | Chỉ phát triển thêm khi có nhu cầu và nguồn lực phù hợp | Mức sử dụng lặp lại, mức hài lòng và chi phí duy trì |

Các chỉ tiêu định lượng cần được nhóm chốt sau khi xác định thời gian, nhân lực và cách đo. Không điền số mục tiêu như thể đã đạt được.

## 7. Mô hình kinh doanh và tính bền vững

Trong giai đoạn demo, ưu tiên là xác minh nhu cầu và độ tin cậy của sản phẩm, không đặt doanh thu chưa kiểm chứng làm trọng tâm. Các hướng có thể thử nghiệm gồm:

1. **Mô hình miễn phí cơ bản:** Giữ các công cụ cốt lõi miễn phí để giảm rào cản tiếp cận.
2. **Gói nâng cao (nếu có nhu cầu):** Bộ bài luyện tập có lời giải từng bước, lưu tiến độ hoặc bộ nội dung theo chủ đề.
3. **Gói dành cho trường/lớp:** Tài liệu và công cụ hỗ trợ giáo viên triển khai bài học, chỉ xây dựng sau khi phỏng vấn và thử nghiệm với giáo viên.
4. **Tài trợ hoặc hợp tác giáo dục:** Hợp tác với câu lạc bộ, trường học hoặc tổ chức phù hợp để hỗ trợ chi phí phát triển.

Đây là các giả thuyết kinh doanh cần kiểm chứng, chưa phải nguồn doanh thu hiện có. Nhóm cần đánh giá khả năng chi trả, chi phí bảo trì, lưu trữ, tên miền, phát triển nội dung và hỗ trợ người dùng trước khi chọn phương án.

## 8. Kế hoạch tiếp cận người dùng

- Thử nghiệm ban đầu trong phạm vi học sinh và giáo viên có thể tiếp cận thông qua nhóm dự án và nhà trường, với sự đồng ý phù hợp.
- Chia sẻ video ngắn minh họa một nhiệm vụ cụ thể, chẳng hạn cân bằng phương trình hoặc quan sát chuẩn độ.
- Đặt đường dẫn và mã QR tới website demo trong tài liệu giới thiệu.
- Thu thập phản hồi bằng biểu mẫu ngắn, không yêu cầu thông tin cá nhân không cần thiết.
- Dùng kết quả thử nghiệm để cải thiện sản phẩm trước khi mở rộng.

## 9. Nguồn lực, phân công và rủi ro

### 9.1. Phân công nhóm

| Thành viên | Vai trò | Công việc và minh chứng đóng góp |
|---|---|---|
| [Họ tên] | Trưởng nhóm/điều phối | [Điền nhiệm vụ thực tế] |
| [Họ tên] | Phát triển sản phẩm | [Điền nhiệm vụ thực tế] |
| [Họ tên] | Nội dung Hóa học/kiểm thử | [Điền nhiệm vụ thực tế] |
| [Họ tên] | Thiết kế/trải nghiệm người dùng | [Điền nhiệm vụ thực tế] |
| [Họ tên] | Khảo sát/truyền thông | [Điền nhiệm vụ thực tế] |

Chỉ giữ những vai trò phù hợp với số thành viên thật. Nếu một người đảm nhiệm nhiều việc, ghi đúng như thực tế. Bổ sung tên giáo viên hướng dẫn: [Họ tên].

### 9.2. Rủi ro và biện pháp giảm thiểu

- **Sai kết quả tính toán:** Tạo bộ ca kiểm thử với đáp án đối chiếu; nhờ giáo viên bộ môn rà soát các trường hợp quan trọng.
- **Mô phỏng gây hiểu nhầm:** Ghi rõ đây là mô hình học tập, nêu giả định và giới hạn; không khuyến khích thay thế thực nghiệm.
- **Thiếu bằng chứng nhu cầu:** Thực hiện khảo sát nhỏ có phương pháp rõ ràng, trình bày cả hạn chế và phản hồi trái chiều.
- **Khó duy trì khi nhóm bận học:** Viết tài liệu kỹ thuật, ghi lại quy trình triển khai và phân công người phụ trách từng phần.
- **Rủi ro dữ liệu cá nhân:** Hạn chế thu thập dữ liệu; không công khai thông tin nhận dạng của học sinh khi chưa được đồng ý phù hợp.

## 10. Tác động dự kiến và cách đánh giá

Dự án kỳ vọng giúp người học dễ thử nghiệm các phép tính Hóa học và hình dung một số quá trình thông qua tương tác. Đây là **tác động kỳ vọng**, chưa phải kết quả đã được chứng minh. Nhóm sẽ đánh giá bằng:

- Số người dùng thử và số người quay lại sử dụng.
- Tỷ lệ hoàn thành các nhiệm vụ thử nghiệm.
- Phản hồi về mức dễ sử dụng và mức hữu ích.
- So sánh kết quả trước/sau một nhiệm vụ học tập ngắn nếu thiết kế được cách đo phù hợp, có sự đồng ý cần thiết.
- Số lỗi được phát hiện và khắc phục trong các ca kiểm thử.

## 11. Kết luận

Subgeneric là một dự án phần mềm giáo dục đang ở giai đoạn demo, được xây dựng từ mong muốn làm cho việc học Hóa học trở nên trực quan và dễ tự luyện tập hơn. Sản phẩm đã có các công cụ tính toán phản ứng và mô phỏng chuẩn độ acid–base; bước tiếp theo là kiểm thử nghiêm túc, lắng nghe học sinh và giáo viên, cải thiện nội dung, đồng thời xác minh mô hình duy trì phù hợp. Nhóm mong muốn phát triển Subgeneric thành một công cụ học tập hữu ích, có trách nhiệm và có khả năng duy trì lâu dài.

---

## Danh sách bắt buộc hoàn thiện trước khi nộp

- [ ] Điền tên trưởng nhóm, thành viên, giáo viên hướng dẫn và phân công thật.
- [ ] Xác nhận đúng tên cuộc thi, mẫu biểu, thể lệ, giới hạn trang và yêu cầu định dạng.
- [ ] Kiểm tra URL website demo đang hoạt động.
- [ ] Thêm kết quả khảo sát thật; nếu chưa khảo sát, thực hiện khảo sát trước khi đưa ra kết luận về nhu cầu.
- [ ] Kiểm thử các công cụ và bổ sung ảnh minh chứng.
- [ ] Chốt mô hình kinh doanh dựa trên phản hồi, phân biệt rõ giả thuyết với kết quả thực tế.
- [ ] Rà soát thuật ngữ Hóa học với giáo viên hướng dẫn.
- [ ] Xuất PDF, kiểm tra số trang và lỗi hiển thị trước khi nộp.
