# PROMPT: LẬP KẾ HOẠCH TÀI CHÍNH CÁ NHÂN BẰNG CHAIN-OF-THOUGHT

**1. Context (Bối cảnh):**

Tôi muốn lập kế hoạch tài chính cá nhân hàng tháng dựa trên thu nhập, chi phí cố định, các khoản nợ và mục tiêu tiết kiệm.

**2. Request (Yêu cầu):**

Hãy lập kế hoạch phân bổ ngân sách hợp lý, đảm bảo trả nợ đúng hạn, tiết kiệm tối thiểu 20% và duy trì quỹ dự phòng.

**3. Reasoning (Quy trình xử lý):**

Hãy suy nghĩ từng bước một và tính toán chi tiết trước khi đưa ra quyết định. Thực hiện các bước:

- Bước 1: Tính thu nhập sau thuế và trừ chi phí cố định.
- Bước 2: Tính tổng các khoản nợ và phân bổ tiền trả nợ tối thiểu.
- Bước 3: Trích lập tiết kiệm ít nhất 20% thu nhập.
- Bước 4: Phân bổ số tiền còn lại theo quy tắc 50/30/20 cải tiến, ưu tiên nhu cầu thiết yếu, mong muốn cá nhân và quỹ dự phòng.

**4. Output (Định dạng đầu ra):**

Trình bày kết quả thành 2 phần:

- Phần 1: Các bước tính toán logic, nêu công thức và số liệu trung gian.
- Phần 2: Bảng Markdown gồm các cột: Hạng mục, Số tiền, Tỷ lệ %, Ghi chú.

**5. Constraints (Ràng buộc):**

- Hiển thị đầy đủ các phép tính cộng, trừ, nhân, chia.
- Không tự ý bỏ qua dữ liệu hoặc giả định khi chưa có căn cứ.
- Tổng tỷ lệ phân bổ ngân sách phải chính xác 100%.
- Nếu thu nhập không đủ trả nợ và tiết kiệm, phải cảnh báo và đề xuất điều chỉnh.
- Không sử dụng Python, Pydantic hay công cụ lập trình; chỉ sử dụng suy luận và tính toán logic.
- Kiểm tra lại tổng số tiền và tỷ lệ phần trăm trước khi xuất kết quả.

**6. Input (Dữ liệu đầu vào):**

- Thu nhập hàng tháng: [Nhập số tiền]
- Thuế và các khoản khấu trừ: [Nhập số tiền]
- Chi phí cố định: [Nhập số tiền]
- Các khoản nợ và hạn thanh toán: [Nhập chi tiết]
- Mục tiêu tiết kiệm: [Nhập tỷ lệ hoặc số tiền]
- Quỹ dự phòng hiện có: [Nhập số tiền]
