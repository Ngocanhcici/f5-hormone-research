# QUY TẮC TỔ CHỨC HỆ THỐNG (DAC MASTER RULES)

Tài liệu này là bộ quy chuẩn chung để áp dụng cấu trúc DAC vào dự án này.

## 1. Cấu trúc thư mục Cốt lõi (Root Structure)
Mọi dự án phải tuân thủ 3 trụ cột thông tin chính:
- **A_REQUIREMENTS**: Định nghĩa giá trị và kỳ vọng (Cái gì? Tại sao? Cho ai?).
- **B_SYSTEM_DESIGN**: Định nghĩa giải pháp và tiêu chuẩn (Làm thế nào? Thẩm mỹ? Chất lượng?).
- **C_IMPLEMENTATION**: Định nghĩa thực thi thực tế (Code? Quy trình? Triển khai?).

## 2. Quy tắc đặt tên & Thứ tự (Order Logic)
- **Số thứ tự là bắt buộc**: Mọi file quan trọng phải bắt đầu bằng `[Phase][Số]_` (Ví dụ: `A2_`, `B1_`).
- **Tính kế thừa**: Nội dung của Phase sau phải luôn tham chiếu và tuân thủ các Standards đã đặt ra ở Phase trước.

## 3. Quy chuẩn Nội dung File (Content Template)
Mỗi file tài liệu nên trả lời được 3 câu hỏi:
1. **Context (Bối cảnh)**: Tại sao tài liệu này tồn tại?
2. **Logic/Standard (Tiêu chuẩn)**: Các quy tắc, triết lý đằng sau là gì?
3. **Outputs (Kết quả)**: Đầu ra cụ thể cho bước tiếp theo?
