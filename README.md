# 🏆 SUMO GAMES - Triệu Phú Tri Thức

> *Trò chơi đố vui kiến thức dành riêng cho các bạn nhỏ tiểu học - vừa học vừa chơi, vừa vui vừa có thưởng!*

---

## 💌 Câu chuyện về Sumo Games

**Sumo Games** ra đời từ mong muốn xây dựng một không gian học tập sáng tạo, nơi kiến thức trở thành một hành trình khám phá đầy thú vị cho các bạn nhỏ.

### 🤖 Hiện thực hóa ý tưởng bằng sức mạnh AI

Dù không phải là lập trình viên, mình đã hiện thực hóa ý tưởng này bằng cách tối ưu các câu lệnh (prompt) để phối hợp cùng trợ lý AI (**Gemini và Claude**).

* **Tốc độ thực thi:** Nhờ khả năng của AI, phiên bản ban đầu được hoàn thiện chỉ trong khoảng **một giờ đồng hồ** từ khi có ý tưởng tới khi game có thể chơi được.
* **Sự tỉ mỉ:** Sau đó, mình dành thêm một tuần vào thời gian rảnh để trau chuốt giao diện, tối ưu các tương tác và xây dựng cơ cấu phần thưởng, nhằm mang lại một sản phẩm hoàn thiện nhất trong khả năng của mình dành cho các con (do các trợ lý AI phiên bản miễn phí giới hạn số lượng yêu cầu trong một khoảng thời gian).

### 👧👦 Những "Chuyên gia kiểm định" đầu tiên

Trong quá trình phát triển, **Su và Mo** chính là những người thẩm định quan trọng nhất. Những phản hồi hồn nhiên của hai con đã trở thành nguồn cảm hứng giúp nảy sinh thêm nhiều ý tưởng mới để hoàn thiện trò chơi như hiện tại.

### 📚 Nội dung trải rộng - Phù hợp mọi học sinh tiểu học

Nội dung câu hỏi trải rộng trên nhiều lĩnh vực kiến thức - từ khoa học, lịch sử, địa lý đến văn hóa, nghệ thuật và kỹ năng sống - được biên soạn phù hợp với học sinh tiểu học tại Việt Nam. Bên cạnh đó, một phần nội dung còn được cá nhân hóa thêm bằng cách lồng ghép các chi tiết từ những cuốn sách, bộ truyện hay bộ phim mà các con yêu thích - giúp việc học trở nên thân quen và thú vị hơn.

> **Lưu ý:** Vì ngân hàng câu hỏi được tạo hoàn toàn bởi AI, đôi khi sẽ có những sự trùng lặp nhất định, hoặc nội dung câu hỏi/đáp án chưa hoàn toàn chính xác.

### ✨ Tính tùy biến - Điểm chạm khác biệt

Điểm thú vị của Sumo Games nằm ở **sự linh hoạt và tính tùy biến cao** - điều mà những trò chơi có sẵn trên các kho ứng dụng lớn thường khó đáp ứng được. Các bậc phụ huynh hoàn toàn có thể tự điều chỉnh nội dung câu hỏi và phần thưởng theo hướng dẫn kèm theo để phù hợp nhất với phong cách của từng gia đình.

❤️ **Hy vọng Sumo Games sẽ là người bạn đồng hành thú vị, mang lại những giây phút vừa học vừa chơi thật ý nghĩa cho các con!**

---

## 🎮 Tính năng chính

| Tính năng | Mô tả |
|-----------|-------|
| 🧠 Ngân hàng câu hỏi | Hỗ trợ Tiếng Việt + English, tùy chỉnh dễ dàng |
| 🎁 Hệ thống phần thưởng | 5 mốc PT (PT1–PT5) theo tỉ lệ đúng, có lịch giờ |
| 🏆 Bảng xếp hạng | Lưu lịch sử, xem chi tiết theo người chơi |
| 🎒 Túi quà | Tích lũy voucher, đổi quà theo nhóm |
| ⏱️ Đếm giờ | Đồng hồ 20 giây mỗi câu, trừ điểm khi sai liên tiếp |
| 🌐 Đa ngôn ngữ | Câu hỏi tiếng Anh xen kẽ tự động (~10%) |
| 📱 Responsive | Hoạt động trên mọi thiết bị, điều chỉnh độ phân giải |
| 💾 Sao lưu & Khôi phục | Export/Import toàn bộ dữ liệu dạng file `.txt` |
| 🔄 Chống lặp câu hỏi | Ghi nhớ 60% câu đã dùng, ưu tiên câu chưa xuất hiện |
| 🎯 Hiển thị cấp độ | Cấp độ Dễ/Khó hiển thị ngay trên màn hình chơi |

---

## 🚀 Cách chạy

Sumo Games là một file HTML đơn - **không cần cài đặt, không cần server**.

```bash
# Chỉ cần mở file index.html trên trình duyệt:
# → Nhấp đôi vào file index.html
# → Hoặc kéo thả vào Chrome / Safari / Edge
```

**Hoặc deploy lên GitHub Pages miễn phí:**

1. Fork repo này
2. Vào **Settings → Pages → Source → main branch**
3. Truy cập tại `https://[username].github.io/[repo-name]/`

---

## 📁 Cấu trúc thư mục

```
sumo-games/
├── index.html         ← File game chính (chạy trực tiếp)
├── README.md          ← File này
└── questions/         ← (Tùy chọn) Chứa các file câu hỏi JSON
    ├── VIE_bank.json
    └── ENG_bank.json
```

---

## 🎮 Hướng dẫn chơi

1. Nhập **tên người chơi**
2. Chọn **số câu hỏi**: 25 / 30 / 35 câu
3. Chọn **cấp độ**: Dễ hoặc Khó *(ảnh hưởng ngưỡng nhận thưởng, không thay đổi độ khó câu hỏi)*
4. Bấm **🚀 Bắt Đầu Chơi**
5. Mỗi câu hỏi có **20 giây** để trả lời - chọn 1 trong 3 đáp án A / B / C
6. Màn hình chơi hiển thị: **Cấp độ · Điểm · Đúng · Sai**

### Hệ thống điểm

| Hành động | Điểm |
|-----------|------|
| Trả lời đúng | +10 điểm |
| Trả lời sai hoặc hết giờ | 0 điểm |
| Sai 3 câu liên tiếp | −10 điểm |

---

## 🛠️ Tùy chỉnh nội dung

### Bước 1 - Truy cập trang Cài Đặt

Từ màn hình chính → nhấn **⚙️ Cài Đặt** → nhập mã PIN (`1234` mặc định).

### Bước 2 - Tải lên câu hỏi (tab 📚 Câu Hỏi)

Nhấn vào ô **VIE** hoặc **ENG** để tải file JSON câu hỏi lên. Có thể tải nhiều file cùng lúc - hệ thống tự động gộp.

### Bước 3 - Tải lên phần thưởng (tab 🎁 Phần Thưởng)

Nhấn **"+ Tải file Phần Thưởng"** và chọn các file PT1.json → PT5.json. Tên file phải chứa `PT1`, `PT2`, `PT3`, `PT4` hoặc `PT5`.

### Bước 4 - Sao lưu & Khôi phục (tab 💾 Dữ Liệu)

| Chức năng | Mô tả |
|-----------|-------|
| 📥 Tải file sao lưu (.txt) | Export toàn bộ dữ liệu (điểm số, voucher, câu hỏi) ra file `.txt` |
| 📤 Khôi phục từ file | Import file `.txt` đã sao lưu - **ghi đè toàn bộ dữ liệu hiện tại** |

> ⚠️ **Lưu ý:** Khôi phục dữ liệu sẽ xóa toàn bộ dữ liệu hiện tại và tải lại trang. Nên sao lưu trước khi thực hiện.

---

## 🏆 Hệ thống phần thưởng & Túi quà

### Ngưỡng nhận thưởng theo cấp độ

| Mốc | Mức độ | Cấp độ Dễ | Cấp độ Khó |
|-----|--------|-----------|------------|
| PT5 | 🏆 Hoàn hảo | ≥ 92% | ≥ 96% |
| PT4 | 🌟 Xuất sắc | ≥ 81% | ≥ 86% |
| PT3 | 😎 Tốt | ≥ 71% | ≥ 76% |
| PT2 | 💪 Cố gắng | ≥ 60% | ≥ 60% |
| PT1 | 🤗 Chưa đạt | < 60% | < 60% |

### Các mục trong Túi Quà

| Mục | Loại phần thưởng | Nhận diện từ `title` |
|-----|-----------------|----------------------|
| 🌟 Quà Đặc Biệt | Quà vật lý nguyên chiếc | Tier PT4/PT5, không chứa thời gian, không có "yêu cầu" |
| 🧩 Quà Ghép Mảnh | Quà tích lũy từng phần | `title` dạng `"1/X tên_quà"` hoặc `"Một phần X ..."` |
| ▶️ Voucher Thời Gian | Thời gian hoạt động/giải trí | `title` chứa số + `phút/giây`, tier PT4/PT5 |
| 🎪 Quà Vui Vẻ | Quà vui hoặc yêu cầu nhỏ | Tier PT1/PT2, hoặc PT4/PT5 có từ `"yêu cầu"` |
| ✅ Quà Đã Nhận | Lịch sử đổi quà | Tự động sau khi đổi bất kỳ loại nào |

> **Lưu ý:** Tier PT3 → phần thưởng tự động vào **Quà Đã Nhận** ngay khi kết thúc.

### Quy tắc đổi quà

- **Quà Đặc Biệt & Quà Ghép Mảnh:** Tối đa **1 lần/ngày**. Có popup xác nhận *"Con chắc chắn muốn đổi quà này chứ?"* trước khi đổi.
- **Voucher Thời Gian & Quà Vui Vẻ (thời gian):** Tick chọn nhiều voucher, gộp tổng thời gian.
  - Giới hạn thiết bị điện tử (YouTube/Netflix/TV...): **30 phút/ngày thường**, **60 phút/cuối tuần**
  - Giới hạn voucher Bố/Mẹ: **6 lần/ngày**
  - Chỉ được gộp voucher **cùng loại** trong một lần đổi
- **Hạn sử dụng:** Tất cả voucher hết hạn sau **90 ngày**. Cảnh báo khi còn 7 / 5 / 3 / 1 ngày.

### Popup "Quà Đã Nhận"

Bấm vào tên quà trong mục Quà Đã Nhận sẽ hiện:

> *"Bạn đã nhận quà vào **14:30** giờ, ngày **16/04/2026** từ gói **Quà Ghép Mảnh** (Cấp độ: **Dễ**)."*

---

## 📝 Hướng dẫn tạo Ngân hàng Câu hỏi

### Prompt sử dụng với AI (Claude / Gemini / ChatGPT)

Sao chép prompt bên dưới, điền vào phần được đánh dấu `[...]`, rồi gửi cho AI:

```
Bạn là một chuyên gia biên soạn nội dung giáo dục tiểu học nhiều năm kinh nghiệm.
Hãy tạo 200 câu hỏi trắc nghiệm đố vui bằng tiếng [Việt / Anh] cho học sinh tiểu học.

CHỦ ĐỀ: [Chọn 3–4 chủ đề từ danh sách bên dưới]

TIÊU CHUẨN NỘI DUNG:
- Đối tượng: Học sinh lớp 2 đến lớp 5 tại Việt Nam (ngôn ngữ chuẩn, dễ hiểu).
- Phong cách: Vui nhộn, hài hước, không bạo lực, không nội dung nhạy cảm.
- Cấu trúc: Mỗi câu có 3 đáp án (A, B, C). Đáp án đúng phải nằm ngẫu nhiên
  ở các vị trí, không tập trung vào một chữ cái nhất định.

YÊU CẦU KỸ THUẬT:
- Không trùng lặp nội dung đã tạo ở các phần trước.
- Trả về DUY NHẤT một mảng JSON, không có văn bản giải thích hay Markdown.

ĐỊNH DẠNG JSON:
[
  {
    "id": [Số thứ tự tiếp nối],
    "question": "Nội dung câu hỏi?",
    "answers": ["Đáp án A", "Đáp án B", "Đáp án C"],
    "correct": [0 cho A | 1 cho B | 2 cho C],
    "category": "Tên chủ đề"
  }
]
```

### 📋 Danh sách chủ đề gợi ý

**Tiếng Việt:**

| # | Chủ đề |
|---|--------|
| 1 | Bảo vệ Môi trường |
| 2 | Giải trí & Nghệ thuật |
| 3 | Khoa học phổ thông |
| 4 | Khoa học và Lịch sử |
| 5 | Kỹ năng sinh tồn và sơ cứu |
| 6 | Lịch sử các đồ vật quanh em |
| 7 | Lịch sử và Địa lý thế giới |
| 8 | Sách khoa học và phiêu lưu + Sách thiếu nhi |
| 9 | Thế giới Số & Công nghệ |
| 10 | Thể thao & Sức khỏe |
| 11 | Tự nhiên và Xã hội |
| 12 | Văn hóa & Ẩm thực Việt Nam |
| 13 | Địa lý và Toán thường thức |
| 14 | Đố mẹo & Chơi chữ |

**English:**

| # | Topic |
|---|-------|
| 1 | My Family |
| 2 | My Pets & Animals |
| 3 | Seasons & Weather |
| 4 | Tet Holiday / Mid-Autumn Festival |
| 5 | Summer Vacation in Vietnam |
| 6 | General Science / Astronomy / Geography |
| 7 | School Life (Supplies, Subjects) |
| 8 | Food & Drinks (Fruits, International Food) |
| 9 | Sports & Hobbies |
| 10 | Daily Life & Health (Body, Jobs, Healthy Habits) |
| 11 | Transport & Signs (Road Safety, Public Signs) |

### 💡 Mẹo tạo câu hỏi hiệu quả

* **Tạo nhiều phần:** Nếu AI giới hạn output, yêu cầu "tạo tiếp 200 câu, bắt đầu từ id [số tiếp theo]" - câu hỏi không bị trùng vì AI nhớ context.
* **Ghép nhiều file:** Tải lên nhiều file JSON cùng lúc - game tự gộp tất cả.
* **Kiểm tra chất lượng:** Dùng thêm prompt "kiểm tra và loại bỏ các câu trùng lặp về nội dung" trước khi tải lên.

---

## 🎁 Hướng dẫn tạo file Phần thưởng (PT1–PT5)

### Cấu trúc file JSON

Mỗi file PT là một object JSON với mảng `rewards`:

```json
{
  "rewards": [
    {
      "emoji": "🎉",
      "title": "Tiêu đề ngắn, hiển thị TO và đậm",
      "message": "Nội dung lời nhận xét đầy đủ, rõ ràng, không tối nghĩa. Có thể dài vài dòng.",
      "schedules": [
        { "type": "weekday", "from": "06:00", "to": "22:30" },
        { "type": "weekend", "from": "07:00", "to": "22:00" }
      ]
    }
  ]
}
```

**Giải thích các trường:**

| Trường | Bắt buộc | Mô tả |
|--------|----------|-------|
| `emoji` | Có | Biểu tượng hiển thị kèm tiêu đề và trong Túi Quà |
| `title` | Có | Tên phần thưởng ngắn gọn - **dùng để phân loại vào Túi Quà** |
| `message` | Có | Nội dung chi tiết gửi đến người chơi |
| `schedules` | Có | Danh sách khung thời gian áp dụng |
| `schedules[].type` | Có | `"weekday"` (T2–T6) hoặc `"weekend"` (T7–CN) |
| `schedules[].from` | Có | Giờ bắt đầu (định dạng `"HH:MM"`) |
| `schedules[].to` | Có | Giờ kết thúc (định dạng `"HH:MM"`) |

> **Quan trọng:** Phần thưởng chỉ xuất hiện đúng khung giờ đã định nghĩa. Nếu không có lịch nào khớp, hệ thống sẽ không hiển thị phần thưởng đó. Mảng `schedules` rỗng `[]` = hiển thị mọi lúc.

### Phân loại tự động từ `title`

| Dạng `title` | Mục trong Túi Quà |
|-------------|-------------------|
| `"1/X tên_quà"` hoặc `"Một phần X ..."` | 🧩 Quà Ghép Mảnh |
| Chứa số + `phút/giây` + tier PT4/PT5 | ▶️ Voucher Thời Gian |
| Tier PT1/PT2 bất kỳ nội dung | 🎪 Quà Vui Vẻ |
| PT4/PT5 + `title`/`message` chứa "yêu cầu" | 🎪 Quà Vui Vẻ |
| PT4/PT5 không có thời gian | 🌟 Quà Đặc Biệt |
| Bất kỳ + tier PT3 | ✅ Quà Đã Nhận (ngay lập tức) |

### Biến động trong `message`

| Biến | Giá trị thay thế |
|------|-----------------|
| `{name}` | Tên người chơi |
| `{pct}` | % câu trả lời đúng |
| `{score}` | Tổng điểm |

### Prompt tạo file PT với AI

```
Tạo file phần thưởng cho game đố vui trẻ em theo cấu trúc JSON sau:

CẤU TRÚC:
{
  "rewards": [
    {
      "emoji": "🎉",
      "title": "Tiêu đề ngắn",
      "message": "Nội dung đầy đủ, vui vẻ, hài hước.",
      "schedules": [
        { "type": "weekday", "from": "HH:MM", "to": "HH:MM" },
        { "type": "weekend", "from": "HH:MM", "to": "HH:MM" }
      ]
    }
  ]
}

YÊU CẦU:
- Phong cách: Vui nhộn, hài hước, phù hợp trẻ 7-11 tuổi.
- Tạo riêng 5 file: PT1.json, PT2.json, PT3.json, PT4.json, PT5.json.
- Tên file phải chứa "PT1", "PT2"... để hệ thống nhận diện đúng.
- Đặt lịch giờ phù hợp (ví dụ: weekday sau giờ học, weekend cả ngày).

NỘI DUNG GỢI Ý:
[Dán nội dung phần thưởng của bạn vào đây]
```

### Ví dụ nội dung gợi ý theo từng mốc

**PT1 & PT2** - Động viên + hình phạt vui (ngày thường):

* `16:50–18:00`: Nhảy dây 20 cái / Ném 5 quả bóng vào rổ / Đu xà 30 giây / Nằm chống đẩy 10 cái / Nhảy lò cò từ bếp ra cửa / Ôn bài quyền Karate
* `19:00–22:30`: Bóp vai cho mẹ 3 phút / Kể chuyện cười cho bố mẹ / Kể chuyện ở trường hôm nay / Massage mặt cho bố 2 phút / Đọc 1 bài Razkid và gửi cho bố / Hút bụi đệm trước khi ngủ
* Cuối tuần: Random tất cả ở trên + dọn dẹp phòng / đổ rác các tầng

**PT3** - Phần thưởng nhỏ (ngày thường):

* `16:50–18:00`: Xin phép mở nhạc Youtube / Xem Youtube 5 phút / Chơi 2 lượt Badland
* `19:00–22:30`: Chơi 3 lượt Badland (nếu xong bài) / Đọc truyện 10 phút (nếu xong bài)
* Cuối tuần: Random tất cả ở trên

**PT4** - Phần thưởng vật chất nhỏ:

* `17:00–21:20`: Yêu cầu bố/mẹ đu xà 30 giây / Bố chống đẩy 10 cái / Bố cõng từ bếp ra cửa
* Cả ngày: Voucher tẩm quất 3 phút / 1/3 kem ốc quế / 1/3 truyện Doraemon/Conan / 1/3 chè cung đình Huế / 1/3 kem Merino / 1/8 voucher Jump Arena / Đọc truyện 5 phút
* Cuối tuần thêm: Xem Youtube 10 phút / Chơi bóng với bố 10 phút

**PT5** - Phần thưởng lớn:

* `17:00–21:00`: Chơi bóng với bố 20 phút / Bố cõng ra tới cây sấu / Bố chống đẩy 20 cái
* Cả ngày: 1 cây kem ốc quế / 1/2 truyện Doraemon/Conan / 1/2 chè cung đình Huế / Tẩm quất 5 phút / 1/6 voucher Jump Arena / 1/6 voucher ăn sáng Kelicious / 1/10 voucher Sushi
* Cuối tuần thêm: Xem Youtube/Netflix 20 phút / Đạp xe buổi sáng với bố

---

## ❓ Câu hỏi thường gặp

**Q: File game có cần kết nối internet không?**
A: Không cần - trừ việc tải font chữ Google Fonts (chỉ ảnh hưởng đến kiểu chữ, game vẫn chạy bình thường khi offline).

**Q: Dữ liệu được lưu ở đâu?**
A: Toàn bộ dữ liệu (câu hỏi, điểm số, voucher) lưu trong `localStorage` của trình duyệt - **không gửi lên server**. Dùng tính năng **Sao lưu** để không mất dữ liệu khi xóa cache.

**Q: Mã PIN mặc định là gì?**
A: `1234` - có thể đổi trong file HTML tại dòng `const ADMIN_PIN = "1234"`.

**Q: Tại sao câu hỏi tiếng Anh xuất hiện xen kẽ?**
A: Hệ thống tự trộn ~10% câu ENG vào bộ VIE để luyện ngoại ngữ. Nếu không muốn, không tải file ENG lên.

**Q: Voucher 1/x hoạt động thế nào?**
A: Mỗi lần đạt mốc phần thưởng, người chơi nhận 1 mảnh. Tích đủ số mảnh (ví dụ 3 mảnh `1/3`) là đổi được 1 phần quà. Hệ thống hiển thị tiến trình trong mục 🎒 **Túi Quà**.

**Q: Câu hỏi bị lặp lại nhiều khi chơi liên tiếp?**
A: Từ phiên bản 1.8.0, hệ thống chống lặp tự động ghi nhớ 60% câu đã dùng gần nhất và ưu tiên câu chưa xuất hiện. Để giảm lặp tối đa, hãy tải thêm câu hỏi qua tab Câu Hỏi trong Cài Đặt.

**Q: Sao lưu và khôi phục dữ liệu như thế nào?**
A: Vào **⚙️ Cài Đặt → tab 💾 Dữ Liệu**. Nhấn "Tải file sao lưu" để export ra file `.txt`. Để khôi phục, nhấn "Khôi phục từ file" và chọn file đã sao lưu - **lưu ý sẽ ghi đè toàn bộ dữ liệu hiện tại**.

---

## 📋 Changelog

| Version | Ngày | Thay đổi |
|---------|------|---------|
| **1.8.0** | 04/2026 | Hiển thị Cấp độ trên màn hình chơi; Popup xác nhận đổi voucher; Quà Đã Nhận lưu cấp độ; Chống lặp câu hỏi thông minh (60% FIFO); Sao lưu & khôi phục dữ liệu (.txt); Emoji từ file PT hiển thị trong Túi Quà; Checkbox cùng dòng tên quà |
| 1.7.1.0 | 04/2026 | Fix lỗi nút Xóa Bảng Xếp Hạng không hoạt động do `confirm()` bị chặn trên GitHub Pages |
| 1.7.0.0 | 04/2026 | Fix lỗi phần thưởng weekend xuất hiện vào ngày thường; thêm chống lặp reward |
| 1.6.8.6 | 04/2026 | Thêm hệ thống voucher thời gian, túi đồ người chơi, lịch sử game |

---

## 📄 License

Dự án này không dành cho mục đích thương mại - được xây dựng từ tình yêu thương dành cho các con. Tự do sử dụng và tùy chỉnh cho mục đích cá nhân/gia đình.

---

<div align="center">

❤️ 💛 ❤️ 💛 ❤️

**Made with ❤️ by Papa Bự - From Papa with Love**

*Pavel.Hai@gmail.com*

</div>
