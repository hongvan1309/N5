---
name: japanese-n5-lesson-creator
description: Tạo bài giảng tiếng Nhật N5 hàng tuần theo giáo trình Minna no Nihongo. Dùng skill này khi giáo viên muốn tạo bài giảng tuần mới, soạn tài liệu N5, tạo bài tập tiếng Nhật N5, hoặc bất kỳ yêu cầu nào liên quan đến giảng dạy tiếng Nhật N5 theo Minna no Nihongo. Kích hoạt ngay cả khi người dùng chỉ nói "tạo bài tuần X", "soạn bài N5", hoặc "bài giảng tuần này".
---

# Skill: Tạo Bài Giảng Tiếng Nhật N5 (Minna no Nihongo)

## Mục tiêu
Tạo bài giảng tiếng Nhật N5 hoàn chỉnh, chuẩn format, theo từng tuần dựa trên giáo trình **Minna no Nihongo (みんなの日本語) Sơ cấp 1**.

## Cấu trúc Syllabus (25 tuần)

| Tuần | Bài (課) | Chủ đề |
|------|----------|--------|
| 1 | Bài 1 | Giới thiệu bản thân (自己紹介) |
| 2 | Bài 2 | Đồ vật xung quanh (これ・それ・あれ) |
| 3 | Bài 3 | Địa điểm (ここ・そこ・あそこ) |
| 4 | Bài 4 | Thời gian & số (時間・数字) |
| 5 | Bài 5 | Mua sắm (買い物) |
| 6 | Bài 6 | Ngày tháng & hoạt động hàng ngày |
| 7 | Bài 7 | Động từ cơ bản (行く・来る・帰る) |
| 8 | Bài 8 | Động từ nhóm 1 & 2 |
| 9 | Bài 9 | Tính từ い・な |
| 10 | Bài 10 | Gia đình (家族) |
| 11 | Bài 11 | Muốn làm gì (〜たい) |
| 12 | Bài 12 | Mời & đề nghị (〜ませんか) |
| 13 | Bài 13 | Đang làm gì (〜ています) |
| 14 | Bài 14 | Gọi điện & liên lạc |
| 15 | Bài 15 | Thể て (動詞て形) |
| 16 | Bài 16 | Cho & nhận (あげる・もらう・くれる) |
| 17 | Bài 17 | Thể た - Quá khứ |
| 18 | Bài 18 | Kinh nghiệm (〜たことがある) |
| 19 | Bài 19 | Thể ない |
| 20 | Bài 20 | Quy tắc & cấm đoán (〜てはいけない) |
| 21 | Bài 21 | Khả năng (〜ことができる) |
| 22 | Bài 22 | Điều kiện (〜と) |
| 23 | Bài 23 | Trước/Sau khi (〜前に・〜てから) |
| 24 | Bài 24 | Thể ngắn (普通形) |
| 25 | Bài 25 | Ôn tập & tổng kết |

---

## Quy trình tạo bài giảng

### Bước 1 — Xác định tuần
Nhận từ người dùng: số tuần (1–25). Nếu không rõ, hỏi lại.

### Bước 2 — Tra cứu nội dung bài tương ứng
Dựa vào bảng syllabus ở trên để xác định bài học (課) và chủ đề.

### Bước 3 — Tạo file Markdown theo template dưới đây

---

## Template Bài Giảng (Markdown)

```markdown
# 📘 Bài Giảng Tuần [X] — [Chủ đề]
**Giáo trình:** みんなの日本語 Bài [N]
**Cấp độ:** N5
**Thời lượng gợi ý:** 90 phút

---

## 1. 単語 — Từ Vựng

| STT | Từ | Kanji | Romaji | Nghĩa |
|-----|----|-------|--------|-------|
| 1 | [từ] | [kanji] | [romaji] | [nghĩa tiếng Việt] |
...

> 💡 **Mẹo ghi nhớ:** [Gợi ý liên tưởng hoặc mnemonic]

---

## 2. 文法 — Ngữ Pháp

### Mẫu câu [N]: [Cấu trúc]

**Cấu trúc:** `[công thức ngữ pháp]`

**Giải thích:** [Giải thích ngắn gọn bằng tiếng Việt]

**Ví dụ:**
- 🇯🇵 [Câu tiếng Nhật]
- 🇻🇳 [Nghĩa tiếng Việt]

---

## 3. 会話 — Hội Thoại Mẫu

**Tình huống:** [Mô tả ngắn tình huống hội thoại]

```
A: [câu 1 tiếng Nhật]
   ([romaji])
   → [nghĩa tiếng Việt]

B: [câu 2 tiếng Nhật]
   ([romaji])
   → [nghĩa tiếng Việt]
```

---

## 4. 漢字 — Kanji Tuần Này

| Kanji | Âm on | Âm kun | Nghĩa | Ví dụ |
|-------|-------|--------|-------|-------|
| [字] | [on] | [kun] | [nghĩa] | [từ ví dụ] |

> ✍️ **Thứ tự nét:** [Mô tả hoặc ghi chú thứ tự viết]

---

## 5. 練習 — Bài Tập

### Bài 1: Điền vào chỗ trống
1. ___________________
2. ___________________

### Bài 2: Dịch sang tiếng Nhật
1. [Câu tiếng Việt] → ___________________
2. [Câu tiếng Việt] → ___________________

### Bài 3: Trả lời câu hỏi
1. [Câu hỏi]?
   → ___________________

### 📝 Đáp án
<details>
<summary>Xem đáp án</summary>

**Bài 1:** 1. [đáp án] 2. [đáp án]
**Bài 2:** 1. [đáp án] 2. [đáp án]
**Bài 3:** 1. [đáp án]

</details>

---

## 6. 文化ノート — Ghi Chú Văn Hóa Nhật

> 🎌 **[Tiêu đề chủ đề văn hóa]**
>
> [Đoạn văn ngắn 3–5 câu giới thiệu nét văn hóa Nhật liên quan đến bài học, viết bằng tiếng Việt, dễ hiểu, có tính thực tế.]

---

## 📌 Tóm Tắt Bài Học

- **Từ vựng mới:** [số] từ
- **Ngữ pháp:** [tên mẫu câu]
- **Kanji:** [danh sách kanji]
- **Bài tập về nhà:** [Gợi ý bài tập tự luyện]

---
*Bài giảng được soạn bởi [Tên giáo viên] — Lớp tiếng Nhật N5*
```

---

## Lưu ý khi tạo nội dung

- **Từ vựng:** Chọn 8–15 từ trọng tâm của bài, ưu tiên từ xuất hiện trong hội thoại mẫu Minna no Nihongo
- **Ngữ pháp:** Giải thích bằng tiếng Việt, dùng ví dụ gần gũi với học sinh Việt Nam
- **Hội thoại:** Bám sát hội thoại trong sách, có thể mở rộng nhẹ
- **Kanji:** Chọn 3–5 kanji phù hợp cấp N5, ưu tiên kanji xuất hiện trong từ vựng bài
- **Bài tập:** Tối thiểu 3 dạng bài, có đáp án kèm theo (dùng `<details>` để ẩn)
- **Văn hóa:** Liên kết với chủ đề bài học, thực tế và thú vị

## Tên file output
```
tuan-[XX]-bai-[N]-[chu-de].md
```
Ví dụ: `tuan-01-bai-1-gioi-thieu.md`
