
# 🛠️ WORKFLOW: FIX BUG

## Mục tiêu
Xác định nguyên nhân gốc rễ và sửa bug an toàn, không phát sinh lỗi mới.

---

## Bước 1: Phân tích bug
Jules AI cần:
- Đọc kỹ mô tả lỗi
- Xác định:
  - Bug xảy ra khi nào?
  - Điều kiện tái hiện bug
  - Mức độ ảnh hưởng

❌ Không sửa khi chưa hiểu rõ bug

---

## Bước 2: Xác định nguyên nhân
- Kiểm tra:
  - Logic sai
  - Sai dependency hook
  - Async / race condition
  - State không đồng bộ
  - API response bất thường

---

## Bước 3: Đề xuất hướng sửa
- Mô tả ngắn gọn cách fix
- Đánh giá rủi ro
- Chọn giải pháp ít ảnh hưởng nhất

---

## Bước 4: Sửa bug
Khi sửa bug:
- Chỉ chỉnh đúng phần gây lỗi
- Không refactor lan man
- Giữ nguyên hành vi các phần khác

---

## Bước 5: Kiểm tra lại
- Kiểm tra bug đã hết chưa
- Kiểm tra side-effect
- Đảm bảo không tạo bug mới

---

## Output mong muốn
- Code đã fix
- Giải thích:
  - Nguyên nhân
  - Cách sửa
