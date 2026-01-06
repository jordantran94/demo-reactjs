---
trigger: always_on
---

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