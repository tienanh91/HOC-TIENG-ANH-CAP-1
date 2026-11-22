# 🎬 AI Film Studio

Phần mềm tạo phim hoạt hình bằng AI, chạy ngay trong trình duyệt: mở `index.html` bằng Chrome hoặc Edge.

- Viết ý tưởng → AI (Claude, nếu có khóa API) hoặc bộ mẫu có sẵn viết kịch bản nhiều cảnh.
- Sửa từng cảnh: lời dẫn, bối cảnh, nhân vật emoji, chuyển động, máy quay, ảnh minh họa AI hoặc ảnh tự tải lên, file ghi âm lời đọc.
- Xem thử có giọng đọc và nhạc nền tự sinh; xuất video `.webm` (16:9, 9:16, 1:1).
- Lưu / mở dự án dạng `.json`.

Lưu ý: giọng đọc của trình duyệt không ghi được vào video; muốn có giọng trong video, hãy gắn file ghi âm cho từng cảnh.

## 🌐 Việt hóa video (`viet-hoa.html`)
Chuyển video nước ngoài (của bạn hoặc có giấy phép) sang tiếng Việt:
1. Chọn video → nhập phụ đề gốc (.srt/.vtt) hoặc để AI Whisper chép lời ngay trong trình duyệt.
2. Dịch sang tiếng Việt bằng Claude (cần khóa API) hoặc tự gõ.
3. Sửa từng câu, chỉnh thời gian, bật phụ đề song ngữ.
4. Gắn file lồng tiếng Việt (tùy chọn), chỉnh âm lượng tiếng gốc.
5. Xuất video có phụ đề tiếng Việt (.webm) hoặc chỉ file phụ đề .srt/.vtt.
