# Sao Khuê Pens · POS

Ứng dụng bán hàng (POS) chạy trên trình duyệt cho Sao Khuê Pens. Giao diện tiếng Việt, tiền tệ VND, dùng được trên nhiều thiết bị cùng lúc.

A browser-based point-of-sale app for Sao Khuê Pens, a pen shop selling in Vietnam. School project.

## Tính năng

- **Bán hàng**: chọn sản phẩm theo danh mục, tìm kiếm, giỏ hàng, giảm giá (₫ hoặc %), thông tin khách hàng
- **Thanh toán**: tiền mặt (tính tiền thừa), chuyển khoản (hiện thông tin tài khoản và nội dung CK), thẻ
- **Hóa đơn**: xem trên màn hình, sao chép để gửi qua Zalo/Messenger
- **Đơn hàng**: lọc theo ngày, tìm kiếm, hủy đơn (hoàn kho), sao chép CSV sang Excel
- **Sản phẩm & tồn kho**: thêm, sửa, xóa, điều chỉnh tồn kho, nhập hàng loạt từ Excel
- **Báo cáo**: doanh thu, số đơn, giá trị trung bình, lợi nhuận gộp, theo giờ/ngày, theo hình thức thanh toán, theo nhân viên, sản phẩm bán chạy, sắp hết hàng
- **Chốt ca**: đối chiếu tiền mặt trong két với doanh thu ca
- **Cài đặt**: thông tin cửa hàng, tài khoản ngân hàng, lời chào cuối hóa đơn

## Phân quyền

- **Contributor**: bán hàng, chốt ca
- **Editor / Owner**: quản lý sản phẩm, hủy đơn, cài đặt

## Công nghệ

Một file `index.html` duy nhất (HTML, CSS, JavaScript thuần). Dữ liệu dùng chung giữa các thiết bị được lưu qua cơ sở dữ liệu của Claude artifacts, nên ứng dụng chạy đầy đủ khi mở từ đường link claude.ai.

## Nhập sản phẩm từ Excel

Sao chép các cột theo thứ tự sau và dán vào màn hình **Sản phẩm → Nhập từ Excel**:

| Tên | Danh mục | Giá bán | Giá vốn | Tồn kho | SKU |
|---|---|---|---|---|---|
| Pilot Custom 74 | Bút máy | 3.200.000 | 2.500.000 | 5 | PL-C74 |
