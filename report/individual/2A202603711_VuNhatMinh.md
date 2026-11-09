# Báo cáo cá nhân — 2A202603711_VuNhatMinh

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Vũ Nhật Minh
- MSSV: 2A202603711
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm: L3A5AE
- Link repo nhóm: https://github.com/kuro2908/K5-L3A-DAY02-L3A5AE-DiscoveryProblemFraming

---

## 2. Scan problem (CP1)

Lăng kính: **Lặp lại** · **Tốn thời gian** · **Cần đọc, tổng hợp nhiều thông tin** · **Pain từ người khác**.

| # | Lăng kính | Job Story: Khi… tôi muốn… để… | Ai chịu ảnh hưởng? | Dấu hiệu thật (thời gian, tần suất, số người, bằng chứng) |
|---:|---|---|---|---|
| 1 | Lặp lại | Khi bắt đầu mỗi buổi sáng, tôi muốn thấy hết việc cần làm và các deadline trong ngày ở một chỗ, để sắp xếp thời gian hợp lý và không bỏ sót việc nào | Tôi; gián tiếp: thành viên nhóm phải chịu hậu quả khi tôi trễ deadline hoặc bỏ sót việc | Khoảng 30 phút mỗi sáng; vẫn bỏ lỡ những việc không có trong mail hoặc lịch, tháng này đã lỡ gần 10 việc |
| 2 | Tốn thời gian | Khi nhóm cần họp hoặc làm việc chung, tôi muốn biết nhanh khung giờ mà mọi thành viên đều rảnh, để chốt lịch mà không phải hỏi qua hỏi lại nhiều lần | Toàn bộ thành viên nhóm | Khoảng 1 tiếng mỗi tuần để xếp lịch họp và lịch làm việc cho khớp; có tranh cãi khi có người vắng mặt |
| 3 | Cần đọc, tổng hợp nhiều thông tin | Khi có model, công cụ mới hoặc thay đổi về giá và quy định của dịch vụ tôi đang dùng, tôi muốn biết sớm thay đổi nào ảnh hưởng tới việc mình đang làm, để không bị lỗi hay phát sinh chi phí ngoài dự kiến | Tôi; gián tiếp: thành viên nhóm cùng dự án | Từng bị lỗi khi demo vì gọi model sau khi nhà cung cấp đã đổi giá, lỗi khiến bài thuyết trình bị trừ điểm, tốn thêm 10 đô chi phí api, mất thêm 1 ngày để fix lại giá dịch vụ |
| 4 | Pain từ người khác | Khi người nhà cần mua đồ công nghệ (ví dụ điện thoại), họ muốn biết món nào hợp với nhu cầu và túi tiền của mình, để chọn được mà không phải hỏi nhiều người và đọc quá nhiều bài review | Người cần mua; người được hỏi ý kiến (tôi) | Tôi mất 3 ngày tư vấn cho người nhà mua điện thoại; cuối cùng họ chọn mua lại điện thoại của người quen |
| 5 | Tốn thời gian | Khi cần tìm một địa điểm dịch vụ gần mình (quán ăn, chỗ gửi xe…), tôi muốn biết chắc nơi đó còn hoạt động và có thứ mình cần, để không phải đến nơi rồi mới phát hiện sai | Tôi và người đi cùng; người bị hỏi đường | Tìm trên Google Maps, đến nơi thì cửa hàng đã đóng cửa từ lâu |
| 6 | Lặp lại | Khi nhóm nhận một bài hoặc dự án mới, tôi muốn chia việc và đặt deadline phù hợp với năng lực từng người, để việc được chia đều và không ai bỏ sót thông tin quan trọng | Toàn bộ thành viên nhóm | Có tranh cãi khi chia việc; việc giao không hợp năng lực, không đồng đều, chia việc mất 30 phút mỗi lần họp, tầm 4 lần 1 tuần |
| 7 | Pain từ người khác | Khi nhận nhiều bài nộp cùng lúc, người chấm muốn kiểm tra được tiến độ và chất lượng của từng bài, để bài nào cũng được chấm và nhận góp ý | Người chấm bài; người nộp bài | Nhiều người không được chấm điểm, không nhận được comment hay review, giáo viên chỉ nhận xét được bài của 1,2 nhóm tiêu biểu, những sinh viên khác không biết mình làm đúng hay sai |
| 8 | Pain từ người khác | Khi trình bày ý tưởng trước người đánh giá, người trình bày muốn người nghe hiểu đúng bức tranh toàn cảnh, để ý tưởng không bị đánh giá sai | Người trình bày; người đánh giá | Ý tưởng bị reject và bị đánh giá thấp vì người nghe hiểu sai |

- Dùng Claude để chuyển các dòng sang đúng dạng Job Story và bỏ chữ "AI" ở dòng #3; nội dung và số liệu là của tôi.

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Khi bắt đầu mỗi buổi sáng, tôi muốn thấy hết việc cần làm và các deadline trong ngày ở một chỗ, để sắp xếp thời gian hợp lý và không bỏ sót việc nào | Vấn đề nghiêm trọng, có thể ảnh hưởng đến toàn bộ công việc của cả ngày | Không biết có phải vấn đề mọi người đều gặp không |
| 2 | Khi có model, công cụ mới hoặc thay đổi về giá và quy định của dịch vụ tôi đang dùng, tôi muốn biết sớm thay đổi nào ảnh hưởng tới việc mình đang làm, để không bị lỗi hay phát sinh chi phí ngoài dự kiến | Vấn đề ảnh hưởng đến chi phí và khả năng hoạt động của ứng dụng, cũng như dễ bị bỏ qua và mất thông tin | Khả năng tiếp cận thông tin của từng người là khác nhau, cũng như có nhiều dịch vụ không cần update thông tin quá nhiều |
| 3 | Khi nhóm nhận một bài hoặc dự án mới, tôi muốn chia việc và đặt deadline phù hợp với năng lực từng người, để việc được chia đều và không ai bỏ sót thông tin quan trọng | Vấn đề đau đầu của mọi nhóm, đặc biệt là với các nhóm mới quen, chưa hiểu rõ năng lực của nhau | khả năng xử lý còn phụ thuộc vào ý thức và mong muốn của từng cá nhân |

### Problem Card #1

| Trường | Nội dung |
|---|---|
| Job Story | Khi bắt đầu mỗi buổi sáng, tôi muốn thấy hết việc cần làm và các deadline trong ngày ở một chỗ, để sắp xếp thời gian hợp lý và không bỏ sót việc nào |
| Actor | Tôi, người tự gom việc từ 4 nguồn mỗi sáng trước giờ làm; gián tiếp: 4 thành viên nhóm khi tôi trễ hoặc bỏ sót việc |
| Thời điểm / bối cảnh | 8h30 sáng hàng ngày, trước khi vào làm 30p |
| Quy trình hiện tại (3–7 bước) | 1. Kiểm tra mail - 2. Kiểm tra Kanban của nhóm - 3. Kiểm tra tin nhắn zalo, messenger - 4. Kiểm tra lịch note - 5. Tổng hợp và sắp xếp việc cần làm cũng như thời gian |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 5, mất tầm 15p, dễ bỏ qua nhiều vấn đề |
| Impact (nếu không giải thì sao) | 3 tiếng để giải quyết vấn đề, 4 người bị ảnh hưởng, gần đây trễ mất 2 lần |
| Success metric (baseline → target) | Thời gian gom việc: 30 → 10 phút/sáng; số việc bị lỡ: ~10 → dưới 2 việc/tháng; đo bằng bấm giờ mỗi sáng và đếm việc bị lỡ trong 2 tuần |
| Phương án không dùng AI | Ghi note kỹ hơn trong lịch, yêu cầu các thành viên phải ghi vắn tắt vào một khung chat riêng về các task |
| Giả thuyết về AI (nếu có) | Tổng hợp thông tin từ nhiều nguồn, sắp xếp độ quan trọng và ước lượng thời gian hoàn thành |
| Cảm nhận nhanh | Agent |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 30 phút mỗi sáng (8h30, trước giờ làm)

[1 Kiểm tra mail: _'] → [2 Kiểm tra Kanban nhóm: _'] → [3 Đọc Zalo, Messenger: _']
→ [4 Xem lịch, note: _'] → [5 Tổng hợp + sắp xếp việc và thời gian: 15'] ← BOTTLENECK

(Bước 1–4 cộng lại khoảng 15'; tổng khoảng 30')
```

### Problem Card #2

| Trường | Nội dung |
|---|---|
| Job Story | Khi có model, công cụ mới hoặc thay đổi về giá và quy định của dịch vụ tôi đang dùng, tôi muốn biết sớm thay đổi nào ảnh hưởng tới việc mình đang làm, để không bị lỗi hay phát sinh chi phí ngoài dự kiến |
| Actor | Toàn bộ thành viên trong nhóm |
| Thời điểm / bối cảnh | 10h sáng mỗi ngày, phải kiểm tra thông tin cảu tất cả các service và nhà cung cấp dịch vụ |
| Quy trình hiện tại (3–7 bước) | 1. Mở trang tin, blog của từng nhà cung cấp - 2. Kiểm tra bảng giá và changelog API - 3. Đối chiếu với các service đang dùng trong dự án - 4. Bàn bạc hướng xử lý với nhóm |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 1: mở và đọc tin từ từng nhà cung cấp, chiếm phần lớn trong hơn 1 tiếng mỗi ngày |
| Impact (nếu không giải thì sao) | Nếu bỏ qua sẽ dễ bị miss thông tin, không kịp sửa lỗi khi delivery sản phẩm. Lần gần nhất: lỗi khi demo vì nhà cung cấp đổi giá, bài thuyết trình bị trừ điểm, tốn thêm 10 đô chi phí API, mất 1 ngày để fix |
| Success metric (baseline → target) | Giảm từ 1 tiếng xuống 10p để research |
| Phương án không dùng AI | Tổng hợp 1 checklist các nhà cung cấp, giao công việc cho 1 người chuyên theo dõi nội dung; bật cảnh báo ngân sách (billing alert) của nhà cung cấp; đăng ký nhận email changelog để thay đổi tự gửi về (mức Rule) |
| Giả thuyết về AI (nếu có) | Một agent theo dõi các news update và đưa ra các gợi ý chỉnh sửa nhanh |
| Cảm nhận nhanh | Workflow |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — hơn 1 tiếng mỗi ngày (10h sáng)

[1 Mở trang tin, blog từng nhà cung cấp: _'] ← BOTTLENECK → [2 Kiểm tra bảng giá, changelog API: _']
→ [3 Đối chiếu với service đang dùng: _'] → [4 Bàn bạc hướng xử lý với nhóm: _']
```

### Problem Card #3

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhóm nhận một bài hoặc dự án mới, tôi muốn chia việc và đặt deadline phù hợp với năng lực từng người, để việc được chia đều và không ai bỏ sót thông tin quan trọng |
| Actor | Tôi và đồng đội trong nhóm |
| Thời điểm / bối cảnh | Đầu mỗi project, trong mỗi buổi họp |
| Quy trình hiện tại (3–7 bước) | 1. Đọc yêu cầu của bài/dự án - 2. Tách thành các đầu việc - 3. Hỏi khả năng và thời gian rảnh của từng người - 4. Thảo luận để phân công - 5. Đặt deadline và ghi lại lên Kanban hoặc nhóm chat |
| Bottleneck (bước nào, mất bao nhiêu phút) | Bước 3, hỏi khả năng và lịch rảnh của từng người: [bổ sung: _ phút]; vì thiếu thông tin này nên bước 4 kéo dài, hay tranh cãi và giao việc không hợp năng lực |
| Impact (nếu không giải thì sao) | Khoảng 30 phút mỗi lần × 4 lần/tuần ≈ 2 tiếng họp mỗi tuần cho cả nhóm; việc chia không đều, không hợp năng lực, dễ bỏ sót thông tin quan trọng |
| Success metric (baseline → target) | Metric chính: số việc phải giao lại vì không hợp năng lực: [bổ sung: baseline] → [bổ sung: target] mỗi dự án. Metric phụ: thời gian chia việc 30 → 15 phút/lần |
| Phương án không dùng AI | Bảng kỹ năng và khung giờ rảnh của từng người, điền một lần; người chia việc chuẩn bị bản nháp phân công trước buổi họp, buổi họp chỉ để chốt; template chia việc cố định |
| Giả thuyết về AI (nếu có) | AI đọc yêu cầu bài, đề xuất cách tách đầu việc và ước lượng thời gian; nhóm vẫn tự quyết ai làm việc gì |
| Cảm nhận nhanh | No AI |

Quy trình nháp hiện tại:

```text
HIỆN TẠI — khoảng 30 phút mỗi lần, khoảng 4 lần mỗi tuần

[1 Đọc yêu cầu: _'] → [2 Tách đầu việc: _'] → [3 Hỏi khả năng, lịch rảnh: _'] ← BOTTLENECK
→ [4 Thảo luận phân công: _'] → [5 Ghi deadline lên Kanban/chat: _']
```

### Card muốn pitch nhất

- Card số: 1
- Vì sao: Có số liệu rõ nhất (khoảng 30 phút mỗi sáng, gần 10 việc bị lỡ trong tháng), quy trình 5 bước vẽ được, và nhiều người làm việc nhóm có thể cũng gặp.
- Câu hỏi muốn nhóm phản biện: Mỗi sáng các bạn mất bao lâu để biết hôm nay phải làm gì, và tháng này có việc nào bị lỡ vì nó nằm ở một kênh mình không kịp xem không?

### AI đã phản biện card thế nào

AI (Claude) đóng vai PM hoài nghi, phản biện cả 3 card:

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card #1: Actor "tôi và các thành viên trong nhóm" còn mơ hồ; ai thực sự làm 5 bước này mỗi sáng? | Đồng ý | Sửa Actor thành người tự gom việc mỗi sáng (tôi), tách riêng 4 thành viên nhóm là người bị ảnh hưởng gián tiếp |
| Card #1: Số liệu chưa khớp. CP1 ghi 30 phút/sáng, card ghi bottleneck 15 phút; 15 phút còn lại nằm ở bước nào? | Không đồng ý | Giữ nguyên. Lý do: [tự ghi] |
| Card #1: Metric "không cần bị miss task" chưa đo được; nên dùng baseline "~10 việc bị lỡ/tháng" từ CP1 | Đồng ý | Đổi metric thành: 30 → 10 phút/sáng; việc bị lỡ ~10 → dưới 2/tháng; đo bằng bấm giờ và đếm trong 2 tuần |
| Card #1: Chọn "Agent" có thể là nhảy sang AI quá sớm; gom từ 4 nguồn có thể chỉ cần Rule hoặc Workflow | Không đồng ý | Giữ cảm nhận Agent. Lý do: [tự ghi] |
| Card #2: Mâu thuẫn với CP1. CP1 kể một sự cố, card lại nói kiểm tra hơn 1 tiếng mỗi ngày; baseline này có thật không? | Không đồng ý | Giữ baseline hơn 1 tiếng mỗi ngày. Lý do: [tự ghi] |
| Card #2: Quy trình mới có 2 bước, chưa đủ 3–7 bước; Impact chưa có số dù CP1 có ($10, 1 ngày fix) | Đồng ý | Tách quy trình thành 4 bước; thêm vào Impact sự cố gần nhất: bị trừ điểm thuyết trình, tốn thêm 10 đô API, mất 1 ngày fix |
| Card #2: Chưa xét phương án Rule như cảnh báo ngân sách/billing alert hoặc đăng ký changelog | Đồng ý | Thêm billing alert và đăng ký email changelog vào phương án không dùng AI |
| Card #3: Bottleneck thật có thể là bước 3 (thiếu thông tin về năng lực, lịch rảnh), không phải bước 4 | Đồng ý | Chuyển bottleneck sang bước 3; bước 4 kéo dài là hệ quả của việc thiếu thông tin ở bước 3 |
| Card #3: Metric chỉ đo thời gian, trong khi pain chính là chia không đều, không hợp năng lực | Đồng ý | Đặt số việc phải giao lại làm metric chính, thời gian chia việc thành metric phụ |
| Card #3: Đây chủ yếu là vấn đề đồng thuận giữa người với người; AI có thật sự giúp được không? | Đồng ý | Đổi cảm nhận nhanh thành No AI; ưu tiên bảng kỹ năng và lịch rảnh, chuẩn bị nháp phân công trước buổi họp |

---

## 4. Tôi đã tham gia phần nào (CP3 → CP7)

| Hoạt động | Tôi đã làm gì? | Kết quả / ảnh hưởng tới bài nhóm |
|---|---|---|
| Pitch Problem Card | | |
| Phản biện bài của bạn khác | Câu hỏi tôi đã đặt: | |
| Nhận phản biện | Câu hỏi tôi nhận được: | Tôi đã sửa gì: |
| Gom cluster / cây OST | | |
| Chọn candidate problem | | |
| Kiểm chứng / research | | |
| Quy trình nhóm | | |
| Problem Statement | | |
| Mức can thiệp AI | | |
| Quyết định | | |

---

## 5. Dùng AI

| Checkpoint | Tôi dùng AI để làm gì? | AI hữu ích ở đâu? | AI sai hoặc hời hợt ở đâu? | Tôi sửa gì bằng nhận định của mình? |
|---|---|---|---|---|
| CP1 Scan | | | | |
| CP2 Problem Card | Nhờ Claude đóng vai PM hoài nghi phản biện 3 card; soạn nháp card #3 và khung quy trình nháp từ dữ liệu CP1 của tôi | Chỉ ra số liệu không khớp giữa CP1 và card, metric chưa đo được, chọn Agent quá sớm | AI không biết số phút thật từng bước nên để trống; quy trình card #3 là phỏng đoán theo mô tả của tôi | [tự điền: những gì bạn đã kiểm lại và sửa] |
| CP4 Research | | | | |
| CP5 Quy trình | | | | |
| CP5–6 Problem Statement | | | | |
| CP6 Mức can thiệp / quyết định | | | | |

---

## 6. Reflection (CP7)

Trả lời bằng trải nghiệm thật của bạn, tối thiểu 200 từ cho các câu 6.1–6.6 (không tính 6.7, câu này được chấm riêng ở tiêu chí C5). **Không dùng AI để viết thay.**

**6.1. Tôi học được gì khi nghe top 3 problems của các bạn khác?**

**6.2. Nhóm có lúc nào bị "solution-first" (nghĩ giải pháp trước khi hiểu vấn đề) không? Lúc đó nhóm nhận ra và xử lý thế nào?**

**6.3. Tôi có đổi ý sau khi bị phản biện không? Kể một lần cụ thể.**

**6.4. Kết quả kiểm chứng (phỏng vấn/survey/research) có làm tôi bất ngờ không? Điều gì?**

**6.5. Điều khó nhất khi viết Problem Statement là gì?**

**6.6. Nếu làm lại, tôi sẽ đổi gì? Tôi sẽ phản biện nhóm mạnh hơn ở điểm nào?**

**6.7. Hiểu bài:** giải thích bằng 5–8 câu, không nhìn tài liệu, chuỗi *problem → quy trình → metric → boundary → mức can thiệp AI → quyết định* của bài nhóm mình.

---

## 7. Tài liệu tham khảo

-
