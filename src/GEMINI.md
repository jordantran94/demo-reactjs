# BỐI CẢNH DỰ ÁN – REACTJS

Tài liệu này định nghĩa **toàn bộ bối cảnh, quy tắc và tiêu chuẩn**
cho mọi AI (Gemini / Antigravity) khi làm việc với dự án này.

---

## 1. TỔNG QUAN DỰ ÁN

Loại dự án: Ứng dụng Web Frontend  
Công nghệ sử dụng:
- React 18+
- TypeScript
- Vite / CRA / Next.js (tùy dự án)
- Chuẩn ES2022+
- CSS Modules / Tailwind / Styled Components (tùy chọn)

Định hướng kiến trúc:
- Component-driven
- Tổ chức theo feature
- Phân tách rõ trách nhiệm

Mục tiêu:
- Dễ bảo trì
- Dễ mở rộng
- Sẵn sàng production
- Dễ test

---

## 2. TIÊU CHUẨN CODE

### Ngôn ngữ
- Luôn sử dụng **TypeScript**
- Bật strict mode
- Không dùng `any` (trừ khi được yêu cầu rõ ràng)

### Quy tắc React
- Chỉ dùng **Function Component**
- Dùng Hook, không dùng class
- 1 component = 1 trách nhiệm
- Không đặt logic nghiệp vụ trực tiếp trong JSX
- Ưu tiên composition hơn inheritance

### Quy tắc đặt tên file
- Component: `PascalCase.tsx`
- Hook: `useSomething.ts`
- Utils: `camelCase.ts`
- Hằng số: `UPPER_SNAKE_CASE.ts`

### Import
- Ưu tiên absolute import
- Thứ tự import:
  1. Thư viện ngoài
  2. Module nội bộ
  3. Style / asset

---

## 3. CẤU TRÚC THƯ MỤC

Ví dụ:

