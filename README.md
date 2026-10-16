# Ôn tập Tin học 12 — Trắc nghiệm tương tác

Trang web tương tác giúp ôn tập và kiểm tra kiến thức **Tin học 12 (Kết nối tri thức)** — Bài kiểm tra thường xuyên Lần 1.

## Tính năng

- **45 câu hỏi** trong ngân hàng đề:
  - Phần I: **30 câu trắc nghiệm** nhiều lựa chọn (A–D)
  - Phần II: **15 câu trắc nghiệm Đúng/Sai** (mỗi câu 4 ý a, b, c, d)
- **2 chế độ làm bài:**
  - 📖 **Luyện tập** — hiện đáp án đúng ngay sau khi chọn
  - 📝 **Kiểm tra** — chọn hết rồi nộp bài, chấm điểm theo thang 10
- **Chấm điểm tự động** theo quy chuẩn Bộ GD&ĐT cho câu Đúng/Sai (1 ý = 0.1đ, 2 ý = 0.25đ, 3 ý = 0.5đ, 4 ý = 1.0đ).
- **Thanh tiến độ** theo dõi số câu đã trả lời.
- **Highlight đáp án** đúng/sai sau khi làm.
- Giao diện responsive, chạy hoàn toàn phía client (không cần server).

## Nội dung chủ đề

| Chủ đề | Trắc nghiệm | Đúng/Sai |
|--------|:-:|:-:|
| Chủ đề 1: Khái niệm & đặc trưng của AI | 10 | 5 |
| Chủ đề 2: Ứng dụng & đạo đức trong AI | 10 | 5 |
| Chủ đề 3: Thiết bị & hạ tầng mạng máy tính | 10 | 5 |

## Cách dùng

### Chạy trực tiếp
Mở file `index.html` bằng trình duyệt bất kỳ.

### Chạy local server (khuyến nghị)
```bash
# Python 3
python -m http.server 8000

# hoặc Node.js
npx serve .
```
Rồi truy cập `http://localhost:8000`.

## Triển khai lên GitHub Pages

1. Push code lên repository GitHub.
2. Vào **Settings → Pages**.
3. Ở mục **Source**, chọn nhánh `main` và thư mục `/ (root)`.
4. Lưu lại — trang sẽ có tại `https://<username>.github.io/<repo>/`.

## Cấu trúc

```
.
├── index.html        # Trang quiz Tin học 12 (UI + logic)
├── questions.js      # Ngân hàng 45 câu hỏi Tin học
├── lichsu12/         # Trang quiz Lịch sử 12 (Bài 1, 2, 3)
│   ├── index.html    # UI + logic chọn bài, chấm điểm
│   └── data.js       # Ngân hàng 114 câu trắc nghiệm Lịch sử
├── tin12-bai456/     # Tài liệu ôn Tin học 12 Bài 4, 5, 6 (mẹo phân tích + 45 câu thực hành)
└── README.md
```

## Ôn tập Lịch sử 12 (Bài 1, 2, 3)

Trang `lichsu12/` là bộ **114 câu trắc nghiệm** Lịch sử 12 (Kết nối tri thức):

| Bài | Số câu |
|-----|:-:|
| Bài 1 — Liên hợp quốc | 34 |
| Bài 2 — Trật tự thế giới trong Chiến tranh lạnh | 45 |
| Bài 3 — Trật tự thế giới sau Chiến tranh lạnh | 35 |

**Tính năng:** chọn bài để ôn · chọn đáp án A–D · nộp bài chấm điểm thang 10 · hiện/ẩn đáp án · có phần câu hỏi riêng về **mốc thời gian**.

Truy cập: `https://kiokuxd.github.io/test/lichsu12/`

## Ôn tập Tin học 12 — Bài 4, 5, 6 (mẹo nhận biết nhanh + thực hành)

Trang `tin12-bai456/` gồm 2 phần trong cùng 1 file:

- 🎯 **Mẹo ôn nhanh** — thống kê tính tự động trên chính 3 đề, **mỗi mẹo đều kèm phần “Cách nhận ra” ngoại lệ**: chọn **câu dài nhất** (22/30, đồng hạng 24/30 — kèm cách nhận ra 6 câu ngoại lệ) · loại phương án có **từ cực đoan** (15/18 lần sai — kèm 3 ngoại lệ vẫn đúng và quy tắc phân biệt) · Đúng/Sai **mặc định ĐÚNG** (44/60 — kèm 6 dạng bẫy để tìm ra ý SAI) · mỗi câu Đ/S có **3 ĐÚNG – 1 SAI** (14/15 câu — kèm bảng tra toàn bộ 16 ý SAI).
- 📝 **45 câu thực hành** (30 trắc nghiệm + 15 Đúng/Sai) của Bài 4 — Giao thức mạng, Bài 5 — Thực hành chia sẻ tài nguyên trên mạng, Bài 6 — Giao tiếp và ứng xử trong không gian mạng. Chọn bài · 2 chế độ Luyện tập / Kiểm tra · chấm điểm thang 10.

Không dùng mẹo dựa vào **vị trí** đáp án (A/B/C/D hay ý a/b/c/d) vì đề có thể đảo thứ tự — chỉ giữ mẹo dựa vào **nội dung**, kèm hướng dẫn nhận biết ngoại lệ dựa trên chính lời giải của đề.

Truy cập: `https://kiokuxd.github.io/test/tin12-bai456/`

## Ghi chú

Dữ liệu câu hỏi được trích xuất và tổng hợp từ ngân hàng đề trực tuyến, phục vụ mục đích học tập.
