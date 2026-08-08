# SPEC SẢN PHẨM: ENGLISH QUEST MOVERS

**Phiên bản:** 1.0 - Các quyết định nền tảng đã được chủ sản phẩm phê duyệt  
**Ngày:** 08/08/2026  
**Chủ sản phẩm:** Người dùng no-code  
**Nhóm thực hiện:** 2 tài khoản Codex cộng tác qua GitHub  
**Tài liệu tham chiếu:** *Get Ready for Movers, 2nd Edition - Student's Book* (120 trang)

> **Quyết định đã chốt:** Sản phẩm giữ tên **English Quest Movers**, dùng giọng Anh-Mỹ, phát triển nội dung theo đúng thứ tự Unit 1 → Unit 12 và đồng bộ tiến trình nhiều thiết bị qua tài khoản do phụ huynh quản lý.

## 1. Mục tiêu của sản phẩm

Tạo một website học tiếng Anh thân thiện cho học sinh lớp 3 và người học có trình độ tương đương Cambridge A1 Movers. Sản phẩm biến nội dung học theo unit thành các phiên học ngắn, trực quan, có âm thanh, trò chơi và tiến trình hằng ngày.

Sản phẩm cần giúp người học:

- Học và ôn khoảng 5 từ trọng tâm trong mỗi unit bằng flashcard.
- Hiểu cấu trúc ngữ pháp qua công thức ngắn, ví dụ mới và hình minh họa.
- Luyện từ vựng và ngữ pháp bằng bài kiểm tra dạng trò chơi từ 5 đến 10 câu.
- Có động lực quay lại mỗi ngày nhờ chuỗi học tập, điểm và thanh tiến trình.
- Sử dụng được trên điện thoại, máy tính bảng và máy tính mà không cần kiến thức kỹ thuật.

### 1.1 Chỉ số thành công đề xuất

- Ít nhất 80% người dùng thử có thể tự bắt đầu một bài học mà không cần người lớn hướng dẫn.
- Ít nhất 70% người dùng thử hoàn thành trọn một unit trong lần sử dụng đầu tiên.
- Thời gian tải trang chính dưới 3 giây trên kết nối 4G phổ biến.
- Không có lỗi chặn luồng học trong ba trình duyệt chính: Chrome, Safari và Edge.
- 100% từ vựng phát được âm thanh hoặc có cơ chế đọc dự phòng.
- 100% câu hỏi có đáp án, phản hồi đúng/sai và lời giải ngắn.

## 2. Đối tượng sử dụng

### 2.1 Người học chính

- Học sinh khoảng 8-9 tuổi.
- Người mới học tiếng Anh có trình độ tương đương A1 Movers.
- Đọc được câu tiếng Việt ngắn; hiểu hướng dẫn tiếng Anh đơn giản.
- Thường sử dụng điện thoại hoặc máy tính bảng bằng thao tác chạm.

### 2.2 Người hỗ trợ

- Phụ huynh tạo tài khoản bằng email, tạo hồ sơ học sinh bằng biệt danh và quản lý việc đăng nhập trên thiết bị mới.
- Giáo viên có thể mở trang và học cùng học sinh, nhưng chưa có tài khoản lớp học hoặc trang quản trị riêng trong MVP.

### 2.3 Nguyên tắc thiết kế cho trẻ em

- Mỗi màn hình chỉ có một hành động chính rõ ràng.
- Câu ngắn, cỡ chữ lớn, nút bấm tối thiểu 44 x 44 px.
- Không có quảng cáo, liên kết lạ, chat công khai hoặc nội dung do trẻ tự đăng.
- Không dùng hình phạt gây áp lực khi trả lời sai hoặc mất chuỗi học tập.
- Phản hồi sai theo hướng khuyến khích: “Gần đúng rồi! Thử lại nhé.”

## 3. Phạm vi phát triển

### 3.1 MVP - Bắt buộc

- Trang chủ với ba mục: Từ vựng, Ngữ pháp, Trò chơi kiểm tra.
- Danh sách unit và trạng thái hoàn thành của từng unit.
- Flashcard theo unit, mặc định 5 từ trọng tâm mỗi unit.
- Hình minh họa nguyên bản và âm thanh cho từng từ.
- Bài ngữ pháp theo unit: công thức, giải thích tiếng Việt ngắn, ví dụ và minh họa.
- Bài kiểm tra 5-10 câu, phối hợp nhiều lựa chọn, điền chỗ trống và nối cặp.
- Điểm, thanh tiến trình và chuỗi học tập hằng ngày.
- Đồng bộ tiến trình giữa nhiều thiết bị bằng Supabase; local storage/IndexedDB là bộ nhớ đệm khi mạng yếu hoặc tạm mất kết nối.
- Giao diện đáp ứng cho điện thoại, máy tính bảng và máy tính.
- Đợt MVP đầu tiên gồm Unit 1, Unit 2 và Unit 3; sau đó phát hành Unit 4 → Unit 12 theo đúng thứ tự, không bỏ cóc unit.
- Đăng nhập phụ huynh bằng email magic link; học sinh chỉ dùng biệt danh/avatar, không nhập email riêng.

### 3.2 Mở rộng sau MVP

- Mở rộng nội dung từ Unit 4 đến Unit 12 theo thứ tự.
- Bảng điều khiển giáo viên, lớp học, giao bài và báo cáo.
- Đọc câu mẫu trọn câu, ghi âm và so sánh phát âm.
- Chế độ ôn theo thuật toán lặp lại ngắt quãng.
- Huy hiệu, avatar và cửa hàng phần thưởng không dùng tiền thật.
- Hoạt động nghe nâng cao theo định dạng Movers.

### 3.3 Ngoài phạm vi hiện tại

- Thanh toán, quảng cáo, chat, bảng xếp hạng công khai.
- Cho trẻ tải ảnh, nhập tên đầy đủ, email, số điện thoại hoặc địa chỉ.
- Sao chép nguyên trang, tranh minh họa, audio hoặc bài tập từ sách tham chiếu.
- Ứng dụng native trên App Store/Google Play.
- Trí tuệ nhân tạo hội thoại trực tiếp với trẻ em.

## 4. Cấu trúc nội dung 12 unit

Mỗi unit dùng cùng một khuôn: 5 flashcard, 1-2 điểm ngữ pháp chính, tối thiểu 10 câu trong ngân hàng câu hỏi và 1 bài kiểm tra ngẫu nhiên 5-10 câu. Danh sách dưới đây là phạm vi nội dung khởi tạo, được chọn lọc từ chủ đề của sách thay vì sao chép toàn bộ bài tập.

| Unit | Chủ đề | 5 từ trọng tâm cho flashcard | Ngữ pháp trọng tâm | Trò chơi phù hợp |
|---|---|---|---|---|
| 1 | At the park | laugh, hide, climb, skip, roller skates | So sánh hơn/nhất; `be good at + noun/V-ing`; mệnh đề quan hệ who/that/where | Chọn tranh, nối từ-tranh, chọn dạng tính từ |
| 2 | A busy week | homework, website, shopping, weekend, practise | Trạng từ tần suất; `like + V-ing`; `Shall I...?` và `How/What about...?` | Sắp xếp lịch tuần, điền always/usually/never |
| 3 | In the town | library, market, hospital, station, supermarket | Quá khứ đơn; was/were; giới từ vị trí | Tìm địa điểm, chọn giới từ, sửa câu quá khứ |
| 4 | At home | laptop, blanket, toothbrush, helmet, downstairs | Quá khứ đơn động từ có quy tắc và bất quy tắc | Memory cards, điền động từ, chọn phòng đúng |
| 5 | Let's go on holiday! | ticket, balcony, cinema, lift, swimming pool | Mệnh đề quan hệ với nơi chốn; tân ngữ gián tiếp; mẫu đề nghị/đề xuất | Ghép nơi-mô tả, chọn câu có nghĩa tương đương |
| 6 | My favourite book | pirate, treasure, jungle, exciting, boring | So sánh hơn/nhất; all/both/one/most | Xếp hạng sách, chọn tính từ, điền dạng so sánh |
| 7 | This is my family | aunt, uncle, cousin, moustache, curly | `could/couldn't`; trạng từ chỉ cách thức | Cây gia đình, đúng/sai, đổi adjective thành adverb |
| 8 | What's for lunch? | pasta, sandwich, vegetable, lemonade, bowl | Danh từ đếm được/không đếm được; some/any; much/many; have got to/had to | Phân loại đồ ăn, kéo thả vào giỏ, điền lượng từ |
| 9 | Do you like animals? | dolphin, kangaroo, panda, parrot, penguin | must/mustn't; giới từ chuyển động; why/because | Luật ở sở thú, đường đi của con vật, chọn lý do |
| 10 | The weather | cloud, rainbow, snow, wind, sunny | Giới từ thời gian in/on/at; diễn đạt thời tiết hiện tại/quá khứ | Dự báo tuần, nối biểu tượng, điền in/on/at |
| 11 | What's the matter? | headache, toothache, cough, temperature, shoulder | `need + noun`; `need + to + V`; ôn so sánh tính từ | Chọn lời khuyên, ghép triệu chứng, điền need |
| 12 | In the countryside | mountain, river, waterfall, forest, tractor | Đại từ bất định someone/something/no one/nothing; mệnh đề `when`; ôn quá khứ | Bản đồ nông thôn, điền từ bất định, kể lại chuyến đi |

### 4.1 Quy tắc biên soạn nội dung

- Từ và chủ điểm có thể bám chủ đề sách, nhưng ví dụ, câu hỏi, hình và audio phải được tạo mới.
- Mỗi từ có: từ tiếng Anh, nghĩa tiếng Việt, loại từ, phiên âm đơn giản/IPA nếu có, audio, ảnh, câu mẫu mới và alt text.
- Mỗi điểm ngữ pháp có: tên, công thức, giải thích tiếng Việt, ít nhất 2 trường hợp, 2-4 ví dụ mới và lỗi thường gặp.
- Mỗi câu hỏi có lời giải thích tối đa 2 câu, đủ để trẻ hiểu vì sao đáp án đúng.
- Tránh câu có kiến thức văn hóa hoặc từ vựng ngoài A1 nếu không giải thích.

## 5. Kiến trúc thông tin và màn hình

### 5.1 Sơ đồ điều hướng

```text
Trang chủ
├── Tiếp tục học
├── Từ vựng
│   └── Danh sách unit → Flashcard → Kết quả
├── Ngữ pháp
│   └── Danh sách unit → Bài ngữ pháp → Mini practice
├── Trò chơi
│   └── Chọn unit → 5-10 câu → Kết quả/Làm lại
└── Tiến trình
    └── Điểm, chuỗi ngày, unit đã hoàn thành
```

### 5.2 Đường dẫn đề xuất

- `/` - Trang chủ.
- `/learn` - Danh sách 12 unit.
- `/learn/[unit]/vocabulary` - Flashcard.
- `/learn/[unit]/grammar` - Bài ngữ pháp.
- `/learn/[unit]/quiz` - Bài kiểm tra.
- `/progress` - Tiến trình cá nhân trên thiết bị.
- `/about` - Giới thiệu, nguồn tham chiếu, quyền riêng tư và thông tin bản quyền.

### 5.3 Trang chủ

**Thành phần bắt buộc:**

- Lời chào ngắn và linh vật.
- Thẻ “Tiếp tục học” dẫn đến bước chưa hoàn thành gần nhất.
- Ba nút lớn: Từ vựng, Ngữ pháp, Trò chơi.
- Chuỗi hiện tại, tổng điểm và tiến trình tổng.
- Danh sách unit dạng thẻ; unit chưa mở vẫn có thể xem, không khóa cứng.

**Tiêu chí nghiệm thu:**

- Trẻ tìm thấy một trong ba mục học trong tối đa 5 giây.
- Không có hơn 6 lựa chọn chính trong vùng nhìn đầu tiên trên điện thoại.
- Trạng thái tiến trình không biến mất sau khi tải lại trang.

## 6. Đặc tả tính năng

### 6.1 Flashcard từ vựng

**Mặt trước:** ảnh minh họa, từ tiếng Anh, nút loa.  
**Mặt sau:** nghĩa tiếng Việt, loại từ, câu mẫu, nút phát lại và hai nút “Cần ôn”/“Đã nhớ”.

**Hành vi:**

1. Khi mở bài, hiển thị tiến độ `1/5`.
2. Chạm thẻ hoặc nhấn Enter/Space để lật.
3. Chạm loa để phát audio; không tự phát khi tải trang.
4. Sau khi đánh dấu đủ 5 từ, hiển thị kết quả và cộng điểm lần đầu.
5. Người học có thể học lại; lần học lại không cộng lại điểm hoàn thành chính.

**Tiêu chí nghiệm thu:**

- Mỗi thẻ có ảnh, alt text và audio hoặc giọng đọc dự phòng.
- Có thể hoàn thành toàn bộ bằng bàn phím.
- Nếu audio lỗi, nút loa báo “Chưa phát được, thử lại nhé” và ứng dụng không bị treo.

### 6.2 Bài ngữ pháp

Mỗi bài gồm:

- Mục tiêu “Sau bài này, em có thể...”.
- Hộp công thức tổng quát.
- Các trường hợp sử dụng dưới dạng thẻ ngắn.
- 2-4 câu mẫu mới, tô màu phần cấu trúc cần chú ý.
- Ít nhất một hình minh họa có ý nghĩa học tập.
- Mini practice 3 câu, phản hồi ngay sau mỗi câu.

**Quy tắc hiển thị:** Không đưa toàn bộ bảng ngữ pháp lên một màn hình nhỏ. Chia thành các khối có nút “Tiếp theo”.

### 6.3 Bài kiểm tra dạng trò chơi

**Cấu hình mặc định:**

- Ngân hàng tối thiểu 10 câu/unit.
- Mỗi lượt lấy ngẫu nhiên 7 câu, tối thiểu 2 câu từ vựng và 2 câu ngữ pháp.
- Số câu cho phép: 5-10; không lặp một câu trong cùng lượt.
- Đạt khi đúng từ 60%; “Xuất sắc” khi đúng 100%.

**Các loại câu MVP:**

1. `multiple_choice`: một đáp án đúng trong 3-4 lựa chọn.
2. `fill_blank`: nhập hoặc chọn từ để điền; bỏ qua khác biệt hoa/thường và khoảng trắng đầu/cuối.
3. `matching`: nối tối đa 5 cặp bằng chạm-chạm; không bắt buộc kéo thả.

**Phản hồi:**

- Đúng: hiệu ứng ngắn, âm thanh có thể tắt và lời khen đa dạng.
- Sai: hiển thị đáp án đúng và giải thích; cho phép tiếp tục, không bắt làm lại ngay.
- Cuối bài: điểm, số câu đúng, chủ điểm cần ôn và nút “Học lại phần yếu”.

### 6.4 Điểm và tiến trình

| Hoạt động | Điểm lần đầu | Điều kiện |
|---|---:|---|
| Hoàn thành 5 flashcard | 10 | Đã mở mặt sau và chọn trạng thái cho đủ 5 từ |
| Hoàn thành bài ngữ pháp | 10 | Đã xem các phần và làm 3 câu mini practice |
| Hoàn thành quiz | 20 | Hoàn tất 5-10 câu |
| Thưởng quiz hoàn hảo | 5 | Đúng 100% trong lượt đầu của ngày |
| Ôn lại | 0 điểm chính | Vẫn ghi nhận số lần luyện, không tạo điểm vô hạn |

**Tiến trình unit:**

- Từ vựng: 35%.
- Ngữ pháp: 30%.
- Quiz: 35%.
- Unit hoàn thành khi cả ba mục đạt trạng thái hoàn thành.

**Tiến trình tổng:** Trung bình phần trăm hoàn thành của các unit đã phát hành. Không tính unit chưa có nội dung.

### 6.5 Chuỗi học tập hằng ngày

- Một “ngày học” theo múi giờ `Asia/Ho_Chi_Minh`, từ 00:00 đến 23:59.
- Chuỗi tăng 1 khi hoàn thành ít nhất một trong ba hoạt động: flashcard, ngữ pháp hoặc quiz.
- Nhiều hoạt động trong cùng ngày không tăng thêm chuỗi.
- Bỏ lỡ một ngày thì chuỗi về 0, nhưng màn hình dùng lời nhắc nhẹ nhàng và vẫn giữ kỷ lục tốt nhất.
- MVP chưa có “đóng băng chuỗi”.
- Dữ liệu tối thiểu: ngày học gần nhất, chuỗi hiện tại, chuỗi tốt nhất và lịch sử 30 ngày.

### 6.6 Âm thanh và hình ảnh

- Mỗi từ có một tệp MP3/OGG ngắn, phát âm rõ và thống nhất giọng Anh-Mỹ.
- Tên tệp: `unit-01-laugh.mp3`, chỉ dùng chữ thường và dấu gạch ngang.
- Web Speech API chỉ là phương án dự phòng khi tệp audio không tải được.
- Hình là ảnh/illustration mới, giấy phép rõ ràng; ưu tiên WebP, kích thước hiển thị tối đa 1200 px.
- Không cắt ảnh trực tiếp từ PDF tham chiếu để đưa lên website.
- Mỗi hình có alt text mô tả nội dung, không lặp nguyên từ nếu alt text làm lộ đáp án trò chơi.

### 6.7 Cài đặt tối thiểu

- Bật/tắt âm hiệu ứng; audio từ vựng vẫn phát khi người học chủ động bấm.
- Chọn cỡ chữ: mặc định/lớn.
- Nút “Xóa tiến trình trên thiết bị” cần hộp xác nhận hai bước.

## 7. Hệ thống giao diện

### 7.1 Phong cách

- Tươi sáng, vui vẻ, không quá nhiều chi tiết chuyển động.
- Các khối bo góc lớn, đổ bóng nhẹ, khoảng trắng rộng.
- Linh vật xuất hiện ở trang chủ, kết quả và thông báo chuỗi ngày.
- Ảnh minh họa nhất quán theo phong cách vector mềm, nhân vật đa dạng và thân thiện.

### 7.2 Bảng màu đề xuất

| Vai trò | Màu | Mã |
|---|---|---|
| Chính | Xanh lá tươi | `#36B86A` |
| Phụ | Xanh da trời | `#4DA8F7` |
| Nhấn | Vàng nắng | `#FFC83D` |
| Thành công | Xanh đậm | `#168A4A` |
| Cảnh báo nhẹ | Cam | `#F59E42` |
| Lỗi | Đỏ dịu | `#D94A4A` |
| Nền | Kem rất nhạt | `#FFFDF5` |
| Chữ chính | Xanh than | `#17324D` |

Mọi cặp màu chữ/nền phải đạt WCAG AA. Không dùng màu làm tín hiệu đúng/sai duy nhất; luôn kèm biểu tượng và chữ.

### 7.3 Typography và chuyển động

- Font đề xuất: `Nunito` cho tiêu đề, `Inter` hoặc `Arial` cho nội dung.
- Cỡ chữ nội dung tối thiểu 16 px; câu hỏi 18-22 px.
- Tôn trọng cài đặt `prefers-reduced-motion`.
- Hiệu ứng lật thẻ và ăn điểm dưới 400 ms; không nhấp nháy.

## 8. Mô hình dữ liệu nội dung và tiến trình

Nội dung học được lưu trong các tệp JSON/TypeScript theo unit để hai tài khoản Codex có thể làm độc lập và tránh sửa chung một tệp lớn.

### 8.1 Cấu trúc Unit

```json
{
  "id": "unit-01",
  "number": 1,
  "slug": "at-the-park",
  "title": "At the park",
  "status": "published",
  "vocabulary": [],
  "grammarLessons": [],
  "questionBank": []
}
```

### 8.2 Cấu trúc VocabularyItem

```json
{
  "id": "u01-laugh",
  "word": "laugh",
  "partOfSpeech": "verb",
  "meaningVi": "cười",
  "ipa": "/lɑːf/",
  "example": "The children laugh at the funny hat.",
  "exampleVi": "Các bạn nhỏ cười vì chiếc mũ ngộ nghĩnh.",
  "imageSrc": "/images/unit-01/laugh.webp",
  "imageAlt": "Three children laughing together in a park",
  "audioSrc": "/audio/unit-01-laugh.mp3"
}
```

### 8.3 Cấu trúc GrammarLesson

```json
{
  "id": "u01-comparatives",
  "title": "Comparative adjectives",
  "goalVi": "So sánh hai người hoặc hai vật.",
  "formula": "A + be + adjective-er + than + B",
  "cases": [
    {
      "label": "Tính từ ngắn",
      "noteVi": "Thêm -er vào tính từ.",
      "examples": ["The red kite is bigger than the blue kite."]
    }
  ],
  "commonMistakes": ["Không dùng more và -er cùng lúc."],
  "practiceQuestionIds": ["u01-g-001", "u01-g-002", "u01-g-003"]
}
```

### 8.4 Cấu trúc Question

```json
{
  "id": "u01-v-001",
  "unitId": "unit-01",
  "skill": "vocabulary",
  "type": "multiple_choice",
  "prompt": "Which word means ‘cười’?",
  "options": ["laugh", "hide", "climb"],
  "answer": "laugh",
  "explanationVi": "Laugh có nghĩa là cười.",
  "difficulty": 1,
  "imageSrc": null
}
```

### 8.5 Cấu trúc dữ liệu tiến trình đồng bộ

```json
{
  "schemaVersion": 1,
  "ownerId": "parent-auth-user-id",
  "learnerProfileId": "learner-profile-id",
  "totalPoints": 40,
  "currentStreak": 2,
  "bestStreak": 4,
  "lastActiveDate": "2026-08-08",
  "activityDates": ["2026-08-07", "2026-08-08"],
  "updatedAt": "2026-08-08T10:30:00+07:00",
  "units": {
    "unit-01": {
      "vocabularyCompleted": true,
      "grammarCompleted": true,
      "quizCompleted": true,
      "bestQuizPercent": 86
    }
  }
}
```

## 9. Kiến trúc kỹ thuật đề xuất

### 9.1 Stack MVP

- **Frontend:** Next.js + TypeScript.
- **Giao diện:** Tailwind CSS và component nội bộ đơn giản.
- **Nội dung:** JSON/TypeScript trong repository, một tệp cho mỗi unit.
- **Tài khoản và cơ sở dữ liệu:** Supabase Auth + Postgres + Row Level Security.
- **Tiến trình:** đồng bộ lên Supabase; local storage/IndexedDB giữ bản đệm và hàng đợi thay đổi khi offline.
- **Kiểm thử:** Vitest/React Testing Library cho logic; Playwright cho luồng chính.
- **Triển khai:** Vercel kết nối GitHub, có preview cho từng pull request.
- **Theo dõi lỗi:** Chỉ log lỗi kỹ thuật ẩn danh; không gửi tên, câu trả lời tự do hay dữ liệu nhận dạng trẻ em.

### 9.2 Mô hình tài khoản an toàn cho trẻ

- Phụ huynh đăng nhập bằng email magic link; không cần ghi nhớ mật khẩu.
- Phụ huynh tạo một hoặc nhiều hồ sơ học sinh bằng biệt danh và avatar có sẵn.
- Học sinh không cung cấp email, họ tên đầy đủ, ngày sinh, ảnh cá nhân hoặc thông tin liên hệ.
- Trên thiết bị mới, phụ huynh đăng nhập rồi chọn hồ sơ học sinh cần dùng.
- Mọi bảng dữ liệu tiến trình bật Row Level Security để một tài khoản chỉ đọc/ghi hồ sơ thuộc quyền sở hữu của mình.

### 9.3 Quy tắc đồng bộ nhiều thiết bị

- Ứng dụng ghi thay đổi vào bộ nhớ cục bộ trước để thao tác không bị chậm, sau đó đẩy lên Supabase khi có mạng.
- Trạng thái hoàn thành được gộp theo quy tắc “đã hoàn thành thắng chưa hoàn thành”; điểm quiz tốt nhất lấy giá trị cao hơn.
- Ngày hoạt động được hợp nhất không trùng lặp; chuỗi ngày được tính lại theo múi giờ `Asia/Ho_Chi_Minh`.
- Điểm không cộng bằng cách cộng hai tổng từ hai thiết bị. Điểm được suy ra từ sổ phần thưởng có khóa duy nhất `(learner_profile_id, activity_id, reward_type)` để tránh cộng hai lần.
- Khi xung đột chưa giải quyết được, bản ghi có `updated_at` mới hơn được giữ và sự kiện được ghi log kỹ thuật không chứa câu trả lời tự do.
- Khi mất mạng, hiển thị trạng thái “Đang lưu trên thiết bị”; khi đồng bộ xong hiển thị “Đã đồng bộ”.

### 9.4 Các bảng dữ liệu tối thiểu

- `parent_accounts`: do Supabase Auth quản lý.
- `learner_profiles`: biệt danh, avatar, owner ID và thời điểm tạo.
- `unit_progress`: trạng thái ba phần học và điểm quiz tốt nhất.
- `activity_days`: ngày có hoạt động theo hồ sơ học sinh.
- `reward_ledger`: phần thưởng đã cấp, dùng để chống cộng điểm lặp.
- `sync_events`: metadata kỹ thuật phục vụ xử lý lỗi; không lưu dữ liệu nhận dạng bổ sung.

## 10. Cấu trúc repository GitHub

```text
english-quest-movers/
├── .github/
│   ├── ISSUE_TEMPLATE/
│   └── pull_request_template.md
├── docs/
│   ├── SPEC.md
│   ├── CONTENT_GUIDE.md
│   └── DECISIONS.md
├── public/
│   ├── audio/
│   └── images/unit-XX/
├── src/
│   ├── app/
│   ├── components/
│   ├── content/units/unit-XX.ts
│   ├── features/auth/
│   ├── features/progress/
│   ├── features/sync/
│   ├── lib/
│   └── styles/
├── supabase/
│   ├── migrations/
│   └── seed.sql
├── tests/
│   ├── e2e/
│   └── unit/
└── README.md
```

## 11. Quy trình cộng tác cho 2 tài khoản Codex

### 11.1 Phân vai mặc định

**Tài khoản Codex A - Nền tảng và giao diện**

- Khởi tạo dự án, routing, design system và component.
- Xây flashcard, grammar viewer, quiz engine, progress/streak.
- Viết kiểm thử logic và kiểm thử luồng.

**Tài khoản Codex B - Nội dung và đảm bảo chất lượng**

- Tạo dữ liệu unit theo schema đã chốt.
- Chuẩn bị/kiểm tra ảnh, audio, alt text và lời giải.
- Kiểm tra chính tả, độ khó A1, responsive và accessibility.

Phân vai không cấm hỗ trợ chéo, nhưng mỗi issue chỉ có một người chịu trách nhiệm chính.

### 11.2 Quy tắc nhánh và pull request

- Nhánh chính: `main`, luôn ở trạng thái chạy được.
- Nhánh công việc: `feat/issue-123-flashcards`, `content/issue-124-unit-01`, `fix/issue-125-audio`.
- Không commit trực tiếp lên `main`.
- Mỗi pull request giải quyết một issue và nhỏ hơn khoảng 500 dòng thay đổi khi có thể.
- PR phải có: mô tả cho người no-code, ảnh/video trước-sau nếu đổi UI, cách kiểm tra và checklist.
- Người còn lại review; mọi kiểm thử tự động phải xanh trước khi merge.
- Dùng squash merge để lịch sử dễ đọc.

### 11.3 Tránh xung đột

- Không để hai tài khoản sửa cùng một tệp unit trong cùng thời điểm.
- Chia nội dung thành `unit-01.ts`, `unit-02.ts`... thay vì một tệp lớn.
- Ghi quyết định thay đổi phạm vi vào `docs/DECISIONS.md` trước khi đổi kiến trúc.
- Mỗi phiên làm việc bắt đầu bằng cập nhật `main` và đọc issue đang được giao.
- Nếu PR phụ thuộc PR khác, ghi rõ `Depends on #...`; không sao chép tạm code của nhau.

### 11.4 Trạng thái issue

`Backlog → Ready → In progress → In review → QA → Done`

Nhãn đề xuất: `area-ui`, `area-content`, `area-audio`, `area-progress`, `bug`, `accessibility`, `owner-a`, `owner-b`, `blocked`.

## 12. Kế hoạch triển khai

### Giai đoạn 0 - Khởi tạo (1-2 ngày)

- Tạo repository, bảo vệ `main`, template issue/PR và Vercel preview.
- Ghi nhận tên English Quest Movers, giọng Anh-Mỹ và thứ tự phát hành Unit 1 → Unit 12.
- Tạo dự án Supabase, biến môi trường, bảng dữ liệu và chính sách Row Level Security.
- Tạo schema nội dung và một unit giả để kiểm tra kỹ thuật.

### Giai đoạn 1 - Khung trải nghiệm (3-5 ngày)

- Trang chủ, danh sách unit, điều hướng và design tokens.
- Flashcard hoạt động với dữ liệu mẫu.
- Đăng nhập phụ huynh, chọn hồ sơ học sinh và đồng bộ tiến trình online/offline.

### Giai đoạn 2 - Học và kiểm tra (4-7 ngày)

- Grammar viewer và ba loại câu hỏi.
- Điểm, tiến trình, streak và màn hình kết quả.
- Hoàn thiện nội dung theo thứ tự Unit 1, Unit 2, Unit 3.

### Giai đoạn 3 - QA với người học (2-4 ngày)

- Kiểm thử điện thoại/máy tính bảng/máy tính.
- Kiểm tra keyboard, screen reader cơ bản, màu sắc và reduced motion.
- Cho 3-5 học sinh dùng thử có người lớn quan sát; ghi lại điểm gây nhầm lẫn.

### Giai đoạn 4 - Mở rộng nội dung

- Phát hành lần lượt Unit 4, 5, 6, 7, 8, 9, 10, 11 và 12; mỗi unit là một PR nội dung độc lập.
- Không đổi quiz engine riêng cho từng unit; mọi biến thể phải đi qua loại câu hỏi dùng chung.

## 13. Backlog ưu tiên cho GitHub

| ID | Issue | Chủ trì | Ưu tiên | Điều kiện hoàn thành |
|---|---|---|---|---|
| EGM-001 | Khởi tạo Next.js, CI và Vercel preview | A | P0 | PR preview chạy, test mẫu xanh |
| EGM-002 | Tạo design tokens và layout responsive | A | P0 | 3 kích thước màn hình không tràn |
| EGM-003 | Tạo Supabase schema và Row Level Security | A | P0 | Kiểm thử chứng minh tài khoản A không đọc dữ liệu tài khoản B |
| EGM-004 | Đăng nhập magic link và hồ sơ học sinh | A | P0 | Phụ huynh đăng nhập và chọn hồ sơ trên thiết bị mới |
| EGM-005 | Chốt schema và validator cho unit | A+B | P0 | Dữ liệu lỗi làm CI thất bại rõ ràng |
| EGM-006 | Component flashcard có audio Anh-Mỹ | A | P0 | Keyboard, fallback audio, progress 1/5 |
| EGM-007 | Dữ liệu và media Unit 1 | B | P0 | 5 từ, grammar, 10 câu, media hợp lệ |
| EGM-008 | Grammar viewer + mini practice | A | P0 | Hoàn thành và ghi tiến trình đúng |
| EGM-009 | Quiz engine 3 dạng câu | A | P0 | Random không lặp, chấm điểm đúng |
| EGM-010 | Progress, points, streak và sync engine | A | P0 | Hai thiết bị hợp nhất đúng, không cộng điểm lặp |
| EGM-011 | Dữ liệu và media Unit 2 | B | P0 | Đạt content checklist |
| EGM-012 | Dữ liệu và media Unit 3 | B | P1 | Đạt content checklist |
| EGM-013 | E2E cho đăng nhập, hoàn thành unit và đồng bộ | A | P0 | Chạy tự động trên PR |
| EGM-014 | QA accessibility và responsive | B | P0 | Không còn lỗi P0/P1 |
| EGM-015 | Trang quyền riêng tư/bản quyền | B | P0 | Nêu dữ liệu tài khoản, đồng bộ và nguồn media |
| EGM-016 | Kiểm thử với 3-5 học sinh | Chủ SP | P1 | Có ghi chép và quyết định điều chỉnh |

## 14. Definition of Done

Một tính năng chỉ được coi là hoàn thành khi:

- Đáp ứng tiêu chí nghiệm thu trong issue và SPEC.
- Có trạng thái loading, empty và error phù hợp.
- Không làm mất tiến trình đã lưu từ schema hiện hành.
- Không tạo bản ghi điểm trùng khi cùng một hoạt động được đồng bộ từ hai thiết bị.
- Hoạt động ở chiều rộng 360 px, 768 px và 1280 px.
- Dùng được bằng bàn phím; focus nhìn thấy rõ.
- Không có lỗi console nghiêm trọng hoặc request media hỏng ngoài trường hợp fallback đã kiểm soát.
- Có kiểm thử phù hợp với rủi ro.
- PR có ảnh/clip minh họa nếu thay đổi giao diện.
- Người còn lại đã review và CI xanh.
- Nội dung không sao chép hình/bài tập/audio từ PDF tham chiếu.

## 15. Kịch bản nghiệm thu cấp sản phẩm

### Kịch bản A - Hoàn thành flashcard

Người học vào Unit 1, xem và nghe đủ 5 từ, đánh dấu từng từ rồi nhận 10 điểm. Tải lại trang vẫn thấy phần từ vựng đã hoàn thành và tổng điểm không bị cộng lần hai.

### Kịch bản B - Học ngữ pháp

Người học xem công thức, ví dụ, hoàn thành 3 câu mini practice rồi nhận 10 điểm. Nếu trả lời sai vẫn tiếp tục được và có lời giải thích.

### Kịch bản C - Làm quiz

Hệ thống chọn ngẫu nhiên 7 câu, có cả từ vựng và ngữ pháp, không trùng. Kết quả chấm chính xác, lưu điểm tốt nhất và mở nút ôn phần yếu.

### Kịch bản D - Chuỗi ngày

Hoàn thành một hoạt động trong ngày làm chuỗi tăng đúng một lần. Hoàn thành thêm hoạt động không tăng lần nữa. Ngày hôm sau hoạt động tiếp thì chuỗi tăng; bỏ qua một ngày thì chuỗi hiện tại về 0 nhưng kỷ lục vẫn giữ.

### Kịch bản E - Media lỗi

Khi một MP3 hoặc ảnh không tải được, màn hình vẫn dùng được, có fallback rõ ràng và không mất câu trả lời/tiến trình.

### Kịch bản F - Đồng bộ nhiều thiết bị

Phụ huynh đăng nhập trên thiết bị thứ hai, chọn cùng hồ sơ học sinh và thấy tiến trình đã học. Nếu hai thiết bị cùng hoàn thành một hoạt động khi offline, sau khi có mạng hệ thống chỉ cấp điểm một lần, giữ trạng thái hoàn thành và điểm quiz tốt nhất.

## 16. Rủi ro và biện pháp giảm thiểu

| Rủi ro | Mức | Giảm thiểu |
|---|---|---|
| Sao chép nội dung/hình từ sách gây rủi ro bản quyền | Cao | Chỉ dùng sách làm khung chủ đề; tạo câu, hình và audio mới; lưu giấy phép media |
| Hai Codex sửa cùng tệp gây xung đột | Cao | Chia tệp theo unit/feature; issue có owner; PR nhỏ |
| Sai cấu hình quyền làm lộ tiến trình giữa các gia đình | Cao | Row Level Security, test chéo hai tài khoản và review migration bắt buộc |
| Xung đột đồng bộ làm cộng điểm hai lần | Cao | Reward ledger có khóa duy nhất; test đồng bộ hai thiết bị/offline |
| Phụ huynh không nhận được magic link | Trung bình | Nút gửi lại có giới hạn, thông báo kiểm tra spam và giữ tiến trình cục bộ tạm thời |
| Trò chơi kéo thả khó dùng trên mobile/accessibility | Trung bình | Matching bằng chạm-chạm; bàn phím là bắt buộc |
| Nội dung quá khó hoặc quá nhiều chữ | Trung bình | Giới hạn A1, câu ngắn, test với học sinh thật |
| Audio không nhất quán | Trung bình | Một giọng/giọng vùng thống nhất, chuẩn hóa âm lượng, fallback TTS |
| Điểm bị cộng vô hạn | Thấp | Điểm hoàn thành chỉ cấp một lần theo activity ID |

## 17. Quyết định chủ sản phẩm đã phê duyệt

| Nội dung | Quyết định | Ảnh hưởng chính |
|---|---|---|
| Thứ tự nội dung | Làm theo thứ tự Unit 1 → Unit 12 | MVP đầu tiên là Unit 1-3; các unit sau không phát hành vượt thứ tự |
| Giọng audio | Anh-Mỹ | Toàn bộ audio chính và fallback TTS dùng `en-US` |
| Đồng bộ | Có, ngay trong MVP | Bổ sung tài khoản phụ huynh, Supabase, RLS và xử lý offline/xung đột |
| Tên sản phẩm | English Quest Movers | Dùng thống nhất trong repository, giao diện và tài liệu |

## 18. Hạng mục còn mở nhưng không chặn phát triển

- Linh vật cụ thể: tạm dùng chú chim nhỏ khám phá cho đến khi có thiết kế thương hiệu.
- Trang báo cáo phụ huynh/giáo viên: để sau MVP; MVP chỉ có màn hình tiến trình học sinh.
- Quyền sử dụng media của sách: mặc định tạo hình, câu hỏi và audio mới để tránh phụ thuộc bản quyền.
- Tên miền: dùng Vercel preview cho đến khi nghiệm thu.
- Ngôn ngữ giao diện: hướng dẫn tiếng Việt ngắn, nội dung học bằng tiếng Anh.

Mọi thay đổi đối với bốn quyết định đã phê duyệt phải được ghi vào `docs/DECISIONS.md` trước khi triển khai.

---

**Ghi chú về nguồn:** Tài liệu tham chiếu được dùng để xác định chủ đề, mức độ và phạm vi ngôn ngữ. Website phải sử dụng câu ví dụ, câu hỏi, hình ảnh và âm thanh do dự án tự tạo hoặc có giấy phép phù hợp.
