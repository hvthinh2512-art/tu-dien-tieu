# Từ điển Tiếng Tiều

Website tra từ tiếng Triều Châu (Tiều): tra theo chữ Hán, phiên âm chuẩn, phiên âm bồi, nghĩa tiếng Việt hoặc tiếng Phổ Thông.

Toàn bộ dữ liệu nằm trong file **`tu-dien.xlsx`**. Website đọc thẳng file này, nên muốn bổ sung từ thì chỉ cần thay file.

## Cập nhật từ điển

1. Sửa file Excel trên máy, hoặc bấm **Xuất Excel** trên trang biên soạn ở claude.ai.
2. Đổi tên file thành đúng `tu-dien.xlsx`.
3. Trên GitHub, mở kho này, bấm **Add file → Upload files**, kéo file vào rồi bấm **Commit changes**.
4. Đợi khoảng 1–2 phút, rồi tải lại website.

## Cấu trúc cột trong file Excel

Dòng đầu là tiêu đề. Các cột lần lượt là:

Mục lục · Tiếng Tiều · Phiên âm chuẩn · Phiên âm đã đổi dấu · Phiên âm bồi đã đổi dấu · (cột F: phiên âm bồi gốc) · Nghĩa tiếng Việt 1 · Nghĩa tiếng Việt 2 · Tiếng Trung Phổ Thông · Từ loại · Lượng từ · Ví dụ tiếng Tiều · Phiên âm bồi ví dụ · Dịch nghĩa ví dụ · Ví dụ bằng tiếng Phổ Thông · Xem thêm · Ghi chú

- Trong câu ví dụ, dùng `~` để thay cho từ chính.
- Website đọc mọi sheet trong file. Dòng không có chữ Hán, phiên âm hay nghĩa sẽ bị bỏ qua.
