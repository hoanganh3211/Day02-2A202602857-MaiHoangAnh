# 03 — Individual Reflection

> Viết bằng lời của bạn (Phase 7 trong `01-worksheet.md`). Có thể dùng AI gợi ý câu hỏi tự soi, không dùng AI viết thay. 8-12 câu, có chuyện cụ thể.

## Thông tin cá nhân

- Họ và tên: Mai Hoàng Anh
- Mã học viên: 2A202602857
- Nhóm: Nửa dưới giữa lớp
- Candidate problem nhóm chọn: Sinh viên IT gặp khó khăn trong việc định hướng nghề nghiệp

---

## 1. Tôi đã tham gia vào phần nào?

Ghi việc cụ thể + kết quả cụ thể. Không ghi chung chung kiểu "tham gia thảo luận".

| Hoạt động | Tôi đã làm gì? (việc cụ thể) | Kết quả / ảnh hưởng tới nhóm |
|---|---|---|
| Scan cá nhân | Lên danh sách 10 vấn đề liên quan đến việc theo dõi calo, khó khăn tính toán bữa ăn ngoài và lên thực đơn giảm cân. | Cung cấp các vấn đề thiết thực về mảng sức khỏe, ăn uống để nhóm có đa dạng góc nhìn, kèm số liệu cụ thể. |
| Pitch Problem Card | Trình bày bài toán "Theo dõi calo đồ ăn ngoài tiệm bằng AI Vision & LLM" và các bottleneck trong quá trình tự log tay. | Đưa ra một use-case tiềm năng cho nhóm, có workflow rõ ràng và AI giải quyết đúng bottleneck (ước lượng định lượng bằng mắt). |
| Challenge bài của bạn khác |Phân tích xem vấn đề "Sinh viên IT gặp khó khăn trong việc định hướng nghề nghiệp" có thể giải quyết bằng Agent không. | Chỉ ra được các vấn đề của sinh viên, các hướng tiếp cận khác nhau và các bottleneck trong quá trình giải quyết vấn đề. |
| Gom trùng / cluster | Tham gia phân loại và nhóm các vấn đề tương đồng của các thành viên. | Giúp nhóm thu hẹp phạm vi các vấn đề tiềm năng tập trung vào mảng định hướng nghề nghiệp IT. |
| Chọn candidate problem | Thảo luận và thống nhất chốt bài toán "Sinh viên IT gặp khó khăn trong việc định hướng nghề nghiệp". | Xác định được hướng đi chính thức và tập trung cho các bước tiếp theo của nhóm. |
| Validation / research | Tìm hiểu và phân tích các giải pháp hiện có (CareerExplorer, Roadmap.sh). Chỉ ra khoảng trống (đánh giá tĩnh, trắc nghiệm dài, không giúp tìm ngách ban đầu). | Nhận diện cơ hội cho nhóm: Xây dựng AI đóng vai trò tư vấn tiền đề giúp sinh viên khám phá ngách chuyên sâu trước khi sinh lộ trình. |
| Workflow nhóm | Hỗ trợ xác định bottleneck ở bước "Tự đánh giá năng lực & đối chiếu thị trường". | Góp phần xây dựng Future workflow, đưa AI vào bước xử lý bottleneck, và giữ human boundary (mentor) ở cuối. |
| Problem Statement | Đóng góp ý tưởng tinh chỉnh v0 lên v1, vạch ranh giới rõ ràng cho Boundary của AI (chỉ phân tích, không tự quyết). | Giúp nhóm hoàn thiện PS v1 với Success Metric thực tế (đo thời gian) và boundary rõ ràng, ngăn chặn AI bịa data. |
| Rule / Workflow / Agent | Cùng nhóm đánh giá ma trận độ phù hợp, phân tích bài toán có độ phức tạp và độ mơ hồ cao. | Thống nhất chọn Agent vì cần AI tự lấy dữ liệu đa nguồn và xử lý đa nhánh thay vì dùng Rule/Workflow thuần. |
| Decision | Thảo luận về điều kiện Go/No-Go dựa trên tính khả thi của dữ liệu đầu vào. | Đồng thuận chọn "Go" với quy mô pilot nhỏ, dùng form input tĩnh để kiểm chứng nhanh (không cần external API). |

**Dấu tay rõ nhất của tôi trong artifact cuối (1-2 câu):**

```text
Dấu tay rõ nét nhất của tôi nằm ở phần Research và định vị sản phẩm. Tôi đã giúp nhóm tìm ra "khoảng trống" của thị trường và chốt được hướng đi khác biệt: dùng AI làm bước tư vấn tiền đề để khám phá ngách IT chuyên sâu trước khi sinh ra lộ trình học tập.
```

---

## 2. Bảng dùng AI (mỗi dòng 1 phase có dùng AI — 2 cột cuối bắt buộc)

| Phase | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai / hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| Scan | Cung cấp bối cảnh (người quan tâm sức khỏe, lười log calo) để tạo 10 problems theo 4 lăng kính. | Đưa ra các problems chi tiết về nhập tay, ước lượng calo món ngoài và các bottleneck cụ thể. | Gen ra vài ý quá chung chung như "muốn sống khỏe nhưng lười" hoặc "tập thể dục mệt mỏi". | Lược bỏ các ý không gắn với quy trình (workflow) hay task cụ thể có thể tối ưu bằng AI. |
| Problem Card | Dùng AI phản biện Problem Card #1 (Theo dõi calo đồ ăn ngoài tiệm). | Chỉ ra được điểm yếu của AI Vision: dễ sai số lớn với các món hầm/xào, đồ ăn bị che khuất, topping giống nhau. | Không đưa ra giải pháp xử lý hoàn hảo cho phần sai số của AI Vision. | Bổ sung bước "User review & Prompt thêm" để user có thể sửa hoặc thêm text (VD: "nhiều béo") trước khi chốt. |
| Workflow | Đưa prompt mô tả luồng sinh viên tự định hướng để AI vẽ nháp sơ đồ workflow. | Dựng cấu trúc các bước (từ bối rối -> tìm kiếm -> chọn đại -> nản) rất nhanh chóng. | AI không xác định đúng bottleneck, lại cho rằng bottleneck ở khâu "tìm tài liệu học" thay vì "không biết hợp ngách nào". | Đẩy trọng tâm bottleneck về khâu "khám phá ngách" và đặt Human boundary tại bước chốt ngách. |
| Research | Dùng AI tìm hiểu và tóm tắt tính năng của các tool định hướng (Roadmap.sh, CareerExplorer). | Liệt kê nhanh phương pháp đánh giá (Big 5, Holland Code) của từng nền tảng. | AI khen các tool quá mức mà không tự chỉ ra được khoảng trống (gap) khi áp dụng cho sinh viên IT. | Tự phân tích và chốt lại khoảng trống: các tool đòi hỏi user phải tự biết ngách trước, tạo cơ hội cho nhóm. |
| Problem Statement | Cung cấp dữ liệu nhóm đã chốt để AI viết nháp bản PS v0 (Actor, Bottleneck, Metric...). | Hành văn trau chuốt, chia field rõ ràng, giúp tóm tắt bài toán vào 1 câu súc tích. | Phần Success Metric AI đưa ra các con số ảo tưởng, không thể đo lường trong phạm vi môn học (VD: 100% có việc). | Sửa lại Metric thực tế: "Giảm thời gian tìm hiểu ngách xuống 30 phút, 70% user chốt được 1 ngách". |
| Rule / Workflow / Agent | Hỏi AI so sánh xem bài toán này phù hợp với mức nào và yêu cầu trả lời 5 câu hỏi chốt. | Phân tích rất sắc bén lý do vì sao Rule (if-else) và Workflow tĩnh sẽ thất bại với logic tư vấn nghề nghiệp. | AI vẽ ra viễn cảnh Agent quá phức tạp, tự động apply CV hoặc đăng ký khóa học giùm sinh viên. | Thu hẹp scope lại: Agent chỉ dừng ở mức phỏng vấn, tư vấn và recommend ngách để đảm bảo khả năng thực thi. |
| Decision | `Không dùng` | `Không dùng` | `Không dùng` | Đây là quyết định chiến lược (Go/No-go) dựa trên năng lực thật của nhóm và độ khả thi, nên nhóm tự họp và chốt, không phụ thuộc AI. |

> Nếu phase nào không dùng AI, ghi `Không dùng` và vì sao tự làm.

---

## 3. Reflection câu hỏi mở

Chọn 3-4 câu trong 6 câu dưới để viết thành đoạn 8-12 câu (không trả lời bullet 1 dòng):
- Tôi học được gì khi nghe top 3 problems của các bạn khác?
- Nhóm có lúc nào bị solution-first, đòi làm Agent cho ngầu không?
- Tôi có thay đổi ý kiến sau khi bị challenge không, vì sao đổi?
- Tôi đóng góp gì thật sự vào artifact cuối, phần nào có dấu tay của tôi?
- Điều khó nhất khi viết Problem Statement là gì, metric hay boundary?
- Nếu làm lại, tôi sẽ challenge nhóm mạnh hơn ở điểm nào?

**Reflection:**

```text
Ban đầu, tôi mang đến nhóm bài toán về theo dõi calo đồ ăn ngoài tiệm, nhưng sau khi nghe top 3 problems của các bạn khác, tôi nhận ra bài toán định hướng nghề nghiệp cho sinh viên IT có độ nhức nhối và tác động lớn hơn nhiều. Trong giai đoạn đầu thảo luận, đã có lúc nhóm rơi vào bẫy "solution-first" khi định xây dựng một Agent cực kỳ phức tạp, có khả năng tự động apply CV hay đăng ký khóa học giùm sinh viên chỉ để sản phẩm trông "ngầu" và AI hơn. Tuy nhiên, sau khi bị challenge gay gắt về tính khả thi cũng như rủi ro khi giao toàn quyền quyết định cho máy, tôi đã thay đổi hoàn toàn góc nhìn. Tôi nhận ra chúng ta cần lùi lại một bước để giải quyết vấn đề gốc rễ: sinh viên thực chất chưa hề biết bản thân phù hợp với ngách nào. Từ nhận định đó, tôi đã đóng góp trực tiếp vào artifact cuối của nhóm thông qua phần Research và định vị sản phẩm. Khi phân tích các công cụ hiện tại như Roadmap.sh hay CareerExplorer, tôi chỉ ra một khoảng trống lớn là chúng đều giả định người dùng đã chốt được ngách nghề nghiệp. Đây chính là dấu tay rõ nét nhất của tôi: định vị AI Agent của nhóm trở thành một bước tư vấn tiền đề, đóng vai trò như một mentor giúp sinh viên khám phá bản thân trước khi sinh ra bất kỳ lộ trình nào. Nếu có cơ hội làm lại, tôi sẽ challenge nhóm mạnh hơn ở phần xác định Success Metric. Bởi lẽ, việc đo lường "hiệu quả tư vấn" hay "tỷ lệ chốt ngách" bằng AI vẫn còn khá mơ hồ, nhóm cần thu thập những con số baseline thực tế hơn từ thị trường để chứng minh Agent thực sự mang lại giá trị rõ ràng.
```

---

## 4. Tự kiểm cuối bài (check trước khi nộp repo)

- [x] [12đ] Cá nhân có 5+ problems + top 3 Problem Cards
- [x] [12đ] Tôi đã pitch rõ + challenge nhóm đúng trọng tâm (ghi ở bảng mục 1)
- [x] Nhóm có nhật ký hội tụ từ candidates về 1 bài
- [x] [15đ] Nhóm có workflow trước/sau
- [x] [20đ] Nhóm có PS v0/v1 với metric + boundary rõ
- [x] [15đ] Nhóm có so sánh No AI / Rule / Workflow / Agent
- [x] [10đ] Nhóm có Go / Not Yet / No-Go + lý do rõ
- [x] [10đ] Reflection này có vai trò thật + AI giúp/sai ở đâu + điều học được + nếu làm lại đổi gì
- [x] [6đ] Tôi tự giải thích được mạch problem → workflow → metric → boundary → độ phù hợp AI

