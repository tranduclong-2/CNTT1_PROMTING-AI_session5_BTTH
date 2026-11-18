# LẬP KẾ HOẠCH TÀI CHÍNH CÁ NHÂN BẰNG CoT

**1. Context (Bối cảnh):**

Tôi là một người đang đi làm, có thu nhập hàng tháng không ổn định và một số khoản nợ cần thanh toán. Tôi muốn quản lý tài chính để đảm bảo chi tiêu, trả nợ và tiết kiệm.

**2. Request (Yêu cầu):**

Hãy lập kế hoạch tài chính hàng tháng, tối ưu hóa dòng tiền, đảm bảo trả nợ đúng hạn, tiết kiệm tối thiểu 20% và xây dựng quỹ dự phòng.

**3. Input (Dữ liệu đầu vào):**

- Thu nhập tháng này: 15.000.000 VNĐ.
- Thuế và khấu trừ: 1.000.000 VNĐ.
- Chi phí cố định: 4.000.000 VNĐ.
- Nợ ngân hàng: 2.000.000 VNĐ/tháng.
- Nợ cá nhân: 1.000.000 VNĐ/tháng.
- Mục tiêu tiết kiệm: 20% thu nhập sau thuế.
- Quỹ dự phòng hiện có: 2.000.000 VNĐ.

**4. Reasoning (Quy trình xử lý):**

Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định.

- Bước 1: Tính thu nhập sau thuế và trừ chi phí cố định.
- Bước 2: Tính tổng tiền trả nợ tối thiểu.
- Bước 3: Trích lập khoản tiết kiệm tối thiểu 20% thu nhập sau thuế.
- Bước 4: Phân bổ số tiền còn lại theo quy tắc 50/30/20 cải tiến, gồm nhu cầu thiết yếu, mong muốn cá nhân và quỹ dự phòng.

**5. Output (Đầu ra):**

Trình bày thành hai phần:

- Phần 1: Các bước tính toán logic, công thức và số liệu trung gian.
- Phần 2: Bảng Markdown gồm các cột: Hạng mục, Số tiền, Tỷ lệ %, Ghi chú.

**6. Constraints (Ràng buộc):**

- Hiển thị đầy đủ các phép tính cộng, trừ, nhân, chia.
- Không bỏ sót khoản thu nhập, chi phí hoặc khoản nợ.
- Tổng ngân sách phải bằng 100% thu nhập.
- Nếu ngân sách không đủ, phải cảnh báo và đề xuất điều chỉnh.
- Không sử dụng Python, Pydantic hay công cụ lập trình.
- Kiểm tra lại số tiền và tỷ lệ phần trăm trước khi xuất kết quả.

1. Bảng dữ liệu đầu vào

| Hạng mục | Số tiền |
|---|---:|
| Thu nhập hàng tháng | 15.000.000 VNĐ |
| Thuế và khấu trừ | 1.000.000 VNĐ |
| Chi phí cố định | 4.000.000 VNĐ |
| Nợ ngân hàng | 2.000.000 VNĐ |
| Nợ cá nhân | 1.000.000 VNĐ |
| Mục tiêu tiết kiệm | 20% |
| Quỹ dự phòng hiện có | 2.000.000 VNĐ |

2. Phần 1: Nhật ký tính toán (Reasoning Steps)
Bước 1: Tính thu nhập khả dụng
- Thu nhập sau thuế: 15.000.000 - 1.000.000 = 14.000.000 VNĐ.
- Sau chi phí cố định: 14.000.000 - 4.000.000 = 10.000.000 VNĐ.
Bước 2: Phân bổ trả nợ
- Tổng nợ: 2.000.000 + 1.000.000 = 3.000.000 VNĐ.
- Số tiền còn lại: 10.000.000 - 3.000.000 = 7.000.000 VNĐ.
Bước 3: Trích lập tiết kiệm
- Tiết kiệm: 14.000.000 × 20% = 2.800.000 VNĐ.
- Số tiền còn lại: 7.000.000 - 2.800.000 = 4.200.000 VNĐ.

3. Bảng phân bổ theo quy tắc 50/30/20

| Hạng mục | Tỷ lệ | Công thức | Số tiền |
|---|---:|---|---:|
| Nhu cầu thiết yếu | 50% | 4.200.000 × 50% | 2.100.000 VNĐ |
| Mong muốn cá nhân | 30% | 4.200.000 × 30% | 1.260.000 VNĐ |
| Quỹ dự phòng | 20% | 4.200.000 × 20% | 840.000 VNĐ |
| **Tổng cộng** | **100%** | | **4.200.000 VNĐ** |

4. Bảng phân bổ ngân sách cuối cùng

| Hạng mục | Số tiền (VNĐ) | Tỷ lệ % | Ghi chú |
|---|---:|---:|---|
| Thuế và khấu trừ | 1.000.000 | 6,67% | Khoản bắt buộc |
| Chi phí cố định | 4.000.000 | 26,67% | Tiền nhà, điện nước |
| Trả nợ ngân hàng | 2.000.000 | 13,33% | Thanh toán đúng hạn |
| Trả nợ cá nhân | 1.000.000 | 6,67% | Thanh toán đúng hạn |
| Tiết kiệm | 2.800.000 | 18,67% | 20% thu nhập sau thuế |
| Nhu cầu thiết yếu | 2.100.000 | 14,00% | Ăn uống, đi lại |
| Mong muốn cá nhân | 1.260.000 | 8,40% | Giải trí, mua sắm |
| Quỹ dự phòng | 840.000 | 5,60% | Chi phí khẩn cấp |
| **Tổng cộng** | **15.000.000** | **100,00%** | **Cân đối ngân sách** |
