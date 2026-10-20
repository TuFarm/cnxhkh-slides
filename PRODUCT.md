# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users
Primary: Nhóm 4 (môn Chủ nghĩa xã hội khoa học, Trường Đại học Quốc tế, ĐHQG-HCM) trình bày trên lớp. Người xem là giảng viên chấm điểm và các bạn cùng lớp, ngồi trong phòng học, xem slide chiếu qua máy chiếu. Người trình bày điều khiển bằng phím mũi tên hoặc Space.

## Product Purpose
Một bài thuyết trình HTML toàn màn hình trả lời câu hỏi cốt lõi: "Vì sao Nhà nước XHCN là kiểu nhà nước mới, khác về chất so với các kiểu nhà nước bóc lột trong lịch sử?" Nội dung đi theo 6 phần: nguồn gốc & khái niệm, bản chất toàn diện, dân chủ XHCN & nhà nước XHCN, đối chiếu lịch sử, hệ thống chức năng, vận dụng thực tiễn; sau đó là kết luận và sơ đồ tư duy.

Thành công gồm bốn điều, ngang hàng nhau:
- được giảng viên cho điểm cao (đúng, đủ, chặt chẽ theo giáo trình);
- tạo ấn tượng và khác biệt so với các nhóm khác;
- trình bày trơn tru: chuyển slide, sơ đồ tư duy và hiệu ứng chạy ổn định, không lỗi giữa chừng;
- người nghe dễ theo dõi: đọc được từ cuối lớp, mạch logic 6 phần rõ ràng.

## Operating Context
- Chiếu trên máy chiếu trong lớp học; chữ phải đọc được từ cuối phòng.
- Điều hướng bằng bàn phím (mũi tên trái/phải, Space); slide sơ đồ tư duy dùng Escape để quay lại toàn cảnh.
- Mỗi slide có ghi chú thuyết trình (`.notes`) là lời dẫn của người nói.
- Bản đã xuất bản tại tufarm.github.io/cnxhkh-slides, có mã QR trên slide bìa (`img2/qr.png`).

## Capabilities and Constraints
- Toàn bộ slide nằm trong một file tĩnh `index.html` (CSS/JS viết sẵn trong file), ảnh nằm ở `img2/`. Không có build step.
- Có 15 slide: bìa, câu hỏi mở đầu/cấu trúc, nội dung các phần 1–6, kết luận, sơ đồ tư duy tương tác (desktop: dùng camera để phóng to vào từng nhánh; điện thoại: accordion), slide kết.
- **Câu chữ nội dung phải giữ nguyên.** Định nghĩa giáo trình, trích dẫn Lênin, bảng so sánh 7 tiêu chí, 6 đặc trưng Nhà nước pháp quyền, ghi chú thuyết trình đều đã bám giáo trình. Được phép sửa cách trình bày, không được đổi chữ, rút gọn hay thêm ý.

## Brand Commitments
- Định danh: Trường Đại học Quốc tế, ĐHQG-HCM; môn Chủ nghĩa xã hội khoa học; Nhóm 4.
- Giọng văn: học thuật, trang trọng, bám thuật ngữ giáo trình (ví dụ "Kính thưa thầy cô và các bạn").

## Evidence on Hand
- Ảnh minh họa trong `img2/`: Quốc hội, hội trường, các mốc 1871/1917/1945/1976, bầu cử, nhà máy, nông thôn mới, Văn Miếu, tiếp xúc cử tri, đối nội/đối ngoại, Lênin, Hiến pháp.
- Mã QR dẫn tới bản đã xuất bản: `img2/qr.png`.
- Không có nguồn hay số liệu nào ngoài giáo trình; không được bịa thêm.

## Product Principles
1. Nội dung giáo trình là bất khả xâm phạm: thiết kế phục vụ văn bản, không bao giờ sửa văn bản.
2. Đọc được trên máy chiếu là sàn chất lượng: kích thước, độ tương phản và mật độ chữ phải chịu được phòng sáng và khoảng cách xa.
3. Ổn định khi trình bày quan trọng hơn hiệu ứng: mọi chuyển động và tương tác phải chạy chắc chắn bằng bàn phím.
4. Mạch 6 phần phải luôn rõ: người nghe luôn biết mình đang ở phần nào.
5. Khác biệt nhưng nghiêm túc: tạo ấn tượng trong khuôn khổ trang trọng của một bài học thuật.
