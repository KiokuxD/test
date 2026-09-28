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
├── index.html      # Trang web quiz tương tác (UI + logic)
├── questions.js    # Ngân hàng 45 câu hỏi (dữ liệu)
└── README.md
```

## Ghi chú

Dữ liệu câu hỏi được trích xuất từ ngân hàng đề trực tuyến, phục vụ mục đích học tập.
