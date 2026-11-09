# Báo cáo cá nhân — MSSV_HoTen

> Đổi tên file theo quy tắc `MSSV_HoTen.md`, ví dụ `20241234_NguyenVanAn.md` (MSSV trước, dấu `_`, họ tên viết liền không dấu). Sửa cả dòng tiêu đề phía trên cho khớp.
> Template chi tiết và prompt mẫu cho từng mục: [docs/01-worksheet.md](../../docs/01-worksheet.md).
> Mỗi thành viên một file trong `report/individual/` trên repo nhóm: copy template này thành file mới, điền, rồi commit bằng tài khoản GitHub của bạn. Không viết hộ người khác.

## 1. Thông tin học viên

- Họ tên: Nguyễn Trọng Phương Bách
- MSSV:2A202603716
- Email trường (không bắt buộc, repo có thể để public):
- Tên nhóm:L3A5AE
- Link repo nhóm:

---

## 2. Scan problem (CP1)

**Bối cảnh:** Sinh viên theo dõi thông tin học tập trên Discord, Facebook, Zalo và sắp xếp deadline.

| # | Lăng kính | Job Story | Ai chịu ảnh hưởng? | Dấu hiệu thật |
|---:|---|---|---|---|
| 1 | Tốn thời gian | Khi tin học tập nằm ở nhiều kênh, tôi muốn nắm các tin liên quan đến mình, để không phải đọc hết mọi nhóm. | Sinh viên | Mất 20 phút/ngày lọc tin trên Discord, Facebook và Zalo. |
| 2 | Cần đọc, tổng hợp nhiều thông tin | Khi thông báo cũ khác thông báo mới, tôi muốn biết bản nào còn đúng, để không làm theo yêu cầu cũ. | Sinh viên | 1 lần/tuần phải hỏi lại vì đọc nhầm thông báo cũ. |
| 3 | Lặp lại | Khi lịch học hoặc hạn nộp thay đổi, tôi muốn biết kịp thời, để sửa kế hoạch. | Sinh viên, nhóm học tập | Giả định: biết tin đổi hạn muộn 2 giờ sau khi thông báo được gửi. |
| 4 | Cần đọc, tổng hợp nhiều thông tin | Khi tổng hợp tin từ nhóm riêng, tôi muốn giữ kín nội dung cá nhân, để không lộ thông tin của thành viên. | Sinh viên, thành viên nhóm chat | Mất 5 phút/lần loại tin nhắn riêng trước khi chia sẻ bản tổng hợp. |
| 5 | Cần đọc, tổng hợp nhiều thông tin | Khi nhiều bài gần hạn, tôi muốn biết nên làm bài nào trước, để không trễ bài quan trọng. | Sinh viên | 3 bài đến hạn trong 2 ngày, trễ 1 bài do ưu tiên sai. |
| 6 | Lặp lại | Khi cùng một thông báo được gửi nhiều nơi, tôi muốn nhận ra tin trùng, để không ghi cùng một việc hai lần. | Sinh viên | 1 thông báo lặp ở 3 nhóm, mất 5 phút kiểm tra lại. |
| 7 | Pain từ người khác | Khi bạn cùng nhóm chờ phần việc của tôi, tôi muốn biết phần nào cần bàn giao hay thực hiện trước, để có thể phối hợp hiệu quả. | Sinh viên, bạn cùng nhóm | 2 bạn chờ 1 giờ vì chưa nhận được phần việc của tôi. |

**AI gợi ý thêm:** #6 (thông báo trùng) và #7 (thứ tự bàn giao trong nhóm) mở thêm góc nhìn; cần tự xác nhận bằng trường hợp thật trước khi giữ. Loại gợi ý “hệ thống AI tự động quản lý toàn bộ việc học” vì quá rộng và chốt giải pháp sớm(solution-first).

---

## 3. Top 3 Problem Cards + quy trình nháp (CP2)

### Bảng chọn top 3

| Rank | Problem | Vì sao chọn | Điều còn chưa chắc |
|---:|---|---|---|
| 1 | Lọc tin học tập nhiều kênh (#1) | Mất 20 phút/ngày; có thể thử với Discord, Facebook và Zalo. | Ghim thông báo và dùng bảng tổng hợp đã đủ chưa? |
| 2 | Xác định thông báo còn hiệu lực (#2) | Đọc nhầm tin cũ, phải hỏi lại 1 lần/tuần. | Ai xác nhận khi hai thông báo mâu thuẫn? |
| 3 | Ưu tiên bài gần hạn (#5) | Trễ 1 trong 3 bài đến hạn trong 2 ngày do ưu tiên sai. | Ngoài hạn nộp, cần xét khối lượng và mức quan trọng thế nào? |

### Problem Card #1 — Lọc tin học tập nhiều kênh

| Trường | Nội dung |
|---|---|
| Job Story | Khi tin học tập nằm ở nhiều kênh, tôi muốn nắm các tin liên quan đến mình, để không phải đọc hết mọi nhóm. |
| Actor | Sinh viên theo dõi thông báo lớp trên Discord, Facebook và Zalo. |
| Thời điểm / bối cảnh | Mỗi ngày, khi kiểm tra tin học tập trên 3 nền tảng. |
| Quy trình hiện tại | 1. Mở các nhóm - 2. Đọc và lọc tin liên quan - 3. Ghi việc cần làm và hạn nộp - 4. Kiểm tra lại nguồn. |
| Bottleneck | Bước 2, đọc và lọc tin trên 3 nền tảng: 12 phút/ngày. |
| Impact | Mất 20 phút/ngày để lọc tin, giảm thời gian làm bài. |
| Success metric | Giảm từ 20 xuống tối đa 10 phút/ngày. Bấm giờ trong 7 ngày; đối chiếu nguồn mỗi ngày để kiểm tra không bỏ sót thông báo liên quan. |
| Phương án không dùng AI | Ghim thông báo, tắt thông báo nhóm không liên quan và ghi việc vào một bảng chung. |
| Giả thuyết về AI | AI lọc và tóm tắt các thông báo sinh viên cung cấp, kèm nguồn; sinh viên kiểm tra trước khi ghi vào lịch. |
| Cảm nhận nhanh | Thử cách không dùng AI trước; cân nhắc Workflow nếu vẫn mất trên 10 phút/ngày. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 20 phút/ngày

[1 Mở các nhóm: 2'] -> [2 Đọc và lọc tin: 12' - BOTTLENECK]
-> [3 Ghi việc và hạn nộp: 4'] -> [4 Kiểm tra nguồn: 2']
```

### Problem Card #2 — Xác định thông báo còn hiệu lực

| Trường | Nội dung |
|---|---|
| Job Story | Khi thông báo cũ khác thông báo mới, tôi muốn biết bản nào còn đúng, để không làm theo yêu cầu cũ. |
| Actor | Sinh viên đọc thông báo; giảng viên hoặc người phụ trách lớp xác nhận thay đổi. |
| Thời điểm / bối cảnh | Khi hạn nộp hoặc yêu cầu của cùng một bài khác nhau giữa các thông báo. |
| Quy trình hiện tại | 1. Tìm thông báo đang dùng - 2. Tìm và đối chiếu bản cập nhật - 3. Hỏi người phụ trách khi chưa rõ - 4. Sửa ghi chú. |
| Bottleneck | Bước 2, tìm và đối chiếu nội dung, người gửi và thời điểm cập nhật: 5 phút/lần. |
| Impact | Đọc nhầm thông báo cũ, phải hỏi lại 1 lần/tuần; có thể làm theo yêu cầu đã đổi. |
| Success metric | Giảm số lần hỏi lại do đọc nhầm tin cũ từ 1 xuống 0 lần/tuần trong 2 tuần. Ghi từng lần hỏi và đối chiếu ghi chú với thông báo đã xác nhận. |
| Phương án không dùng AI | Giữ một bảng thông báo hiện hành, kèm nguồn và ngày cập nhật; người phụ trách đánh dấu bản thay thế. |
| Giả thuyết về AI | Chưa cần; khi nguồn mâu thuẫn, người phụ trách xác nhận bản còn hiệu lực. |
| Cảm nhận nhanh | Chưa cần dùng ngay AI - thống nhất nguồn và cách cập nhật trước. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 10 phút/lần, chưa tính thời gian chờ phản hồi

[1 Tìm thông báo đang dùng: 1'] -> [2 Tìm và đối chiếu bản cập nhật: 5' - BOTTLENECK]
-> [3 Hỏi người phụ trách khi chưa rõ: 3'] -> [4 Sửa ghi chú: 1']
```

### Problem Card #3 — Ưu tiên bài gần hạn

| Trường | Nội dung |
|---|---|
| Job Story | Khi nhiều bài gần hạn, tôi muốn biết nên làm bài nào trước, để không trễ bài quan trọng. |
| Actor | Sinh viên tự sắp xếp thứ tự làm bài. |
| Thời điểm / bối cảnh | Khi có 3 bài đến hạn trong 2 ngày. |
| Quy trình hiện tại | 1. Liệt kê bài và hạn nộp - 2. Ghi thời gian còn cần và mức quan trọng - 3. Chọn thứ tự làm - 4. Xếp lịch. |
| Bottleneck | Bước 3, cân nhắc hạn nộp, khối lượng và mức quan trọng để chọn thứ tự: 4 phút/lần, dễ ưu tiên sai. |
| Impact | Trễ 1 trong 3 bài đến hạn trong 2 ngày do ưu tiên sai. |
| Success metric | Giảm từ 1/3 xuống 0/3 bài trễ ở đợt tiếp theo có 3 bài đến hạn trong 2 ngày. Đối chiếu thời điểm nộp với hạn của từng bài. |
| Phương án không dùng AI | Bảng tính ghi hạn, thời gian còn cần và mức quan trọng; đánh dấu bài có nguy cơ trễ để xếp trước. |
| Giả thuyết về AI | Chưa cần; các tiêu chí đã có thể ghi và so sánh bằng bảng tính. |
| Cảm nhận nhanh | Dùng bảng tính đánh dấu nguy cơ trễ, sinh viên chốt thứ tự làm. |

Quy trình nháp hiện tại:

```text
HIỆN TẠI - 10 phút/lần xếp lịch cho 3 bài

[1 Liệt kê bài và hạn: 2'] -> [2 Ghi khối lượng và mức quan trọng: 2']
-> [3 Chọn thứ tự: 4' - BOTTLENECK] -> [4 Xếp lịch: 2']
```

### Card muốn pitch nhất

- Card số: 1 - lọc tin học tập nhiều kênh.
- Vì sao: mất 20 phút/ngày, bước đọc và lọc tin rõ, có thể đo trong 7 ngày.
- Câu hỏi muốn nhóm phản biện: Ghim thông báo và dùng một bảng tổng hợp có đủ giảm xuống 10 phút/ngày mà không bỏ sót tin không?

### AI đã phản biện card thế nào

| Điểm yếu AI chỉ ra | Đồng ý? | Đã sửa gì |
|---|---|---|
| Card 1: chỉ đo tốc độ có thể bỏ qua việc bỏ sót tin. | Có | Bổ sung đối chiếu nguồn mỗi ngày và điều kiện không bỏ sót thông báo liên quan. |
| Card 2: tin gửi sau chưa chắc là bản đúng. | Có | Đối chiếu cả độ tin cậy thông tin của người gửi, yêu cầu người phụ trách xác nhận khi nguồn mâu thuẫn. |
| Card 3: chỉ xếp theo hạn nộp chưa đủ. | Có | Ngoài thời gian trước khi bài tập hết hạn, cần quan tâm thêm tới mức quan trọng của các deadline trước khi chọn thứ tự. |

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
| CP1 Scan | Nhờ AI diễn đạt lại 5 ý, gợi ý #6–#7 và số liệu minh họa. | Viết ngắn theo Job Story. | Số liệu do AI đề xuất, chưa đo thực tế. | Ghi rõ số liệu giả định; cần tự xác nhận và thay bằng dấu hiệu thật trước khi nộp. |
| CP2 Problem Card | Viết lại 3 card từ CP1 và phản biện. | Làm rõ bước nghẽn, metric và phương án không AI. | Bản cũ nói về hành chính, không khớp CP1. | Thay bằng vấn đề học tập #1, #2, #5; thêm kiểm tra nguồn và tiêu chí ưu tiên bài. |
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
