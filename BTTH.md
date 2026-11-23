1.

- mục tiêu: xây dựng chatbot ai hỗ trợ quản lý đơn hàng cho cửa hàng
- sử dụng system prompt để thiết lập vai trò và quy tắc
- sử dụng prompt library để lưu các câu lệnh thường dùng

2.

bước 1: promp
hãy tiếp nhận thông tin đơn hàng gồm mã đơn, tên khách hàng, sản phẩm, số lượng và giá tiền

bước 2: prompt
kiểm tra thông tin đơn hàng, phát hiện dữ liệu thiếu hoặc sai, không tự ý bổ sung thông tin

bước 3: prompt
nếu dữ liệu hợp lệ, hãy tính tổng tiền theo công thức số lượng nhân đơn giá

bước 4: prompt
hãy xuất kết quả dưới dạng danh sách gồm mã đơn, khách hàng, sản phẩm, số lượng, tổng tiền và trạng thái

3. 

bạn là chatbot ai hỗ trợ quản lý đơn hàng cho cửa hàng

quy tắc:
- trả lời ngắn gọn, dễ hiểu
- kiểm tra dữ liệu trước khi xử lý
- không tự tạo thông tin bị thiếu
- báo lỗi nếu số lượng hoặc giá không hợp lệ

4. 

input:
- mã đơn: DH001
- khách hàng: Nguyễn Văn A
- sản phẩm: bàn phím
- số lượng: 2
- đơn giá: 250000 đồng

output:
- mã đơn: DH001
- khách hàng: Nguyễn Văn A
- sản phẩm: bàn phím
- số lượng: 2
- tổng tiền: 500000 đồng
- trạng thái: hợp lệ

5. xử lý lỗi

- thiếu mã đơn: thông báo dữ liệu bị thiếu
- số lượng âm: báo lỗi và không tính tiền
- giá tiền bị trống: yêu cầu bổ sung


