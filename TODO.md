# 🎯 TODO List - Team SMCS

## 🔴 High Priority
- [ ] Triển khai Middleware Queue để điều tiết request API cho toàn bộ bot.
- [ ] Tích hợp logic Exponential Backoff vào hàm gọi API để xử lý lỗi 429.
- [ ] Cấu hình lại `reserveTokensFloor` lên 20,000 cho @sen_marketting_bot để tránh tràn bộ nhớ.

## 🟡 Medium Priority
- [ ] Xây dựng bảng Failover Model chi tiết (Pro $\rightarrow$ Flash $\rightarrow$ Alternative).
- [ ] Tối ưu hóa luồng dữ liệu (Context Compression) cho các cuộc hội thoại dài.

## 🟢 Low Priority
- [ ] Cập nhật hướng dẫn vận hành cho team trong `TOOLS.md`.
- [ ] Rà soát lại logs định kỳ để phát hiện sớm các điểm nghẽn.
