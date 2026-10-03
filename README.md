# SonicRec: bản cài

Kho này chỉ giữ bản cài mới nhất của ứng dụng SonicRec: ghi âm cuộc họp và soạn biên bản (Trường Đại học Thăng Long). Ứng dụng đã cài đọc kho này để tự báo khi có bản mới. Mã nguồn không nằm ở đây.

Bản mới nhất: **v2.2**, ngày 3/10/2026. Bản 2.2: Mẫu cuộc họp và Nhận dạng giọng nói tách thành hai thẻ riêng cho dễ tìm. Màn đang ghi gọn hơn, chủ trì tự nói câu thông báo đầu buổi (xem mục 2.2 hướng dẫn sử dụng). Hộp Ngữ cảnh thêm ô chọn Gửi lên mạng hay Không gửi lên mạng; bấm Lưu là máy đưa ngữ cảnh lên sổ ngay, hộp còn mở thì máy chờ rồi mới gửi đoạn đầu. Danh sách cuộc họp đã ghi thêm ô tìm và bộ lọc. Mã kích hoạt chắc hơn trước việc chỉnh lùi đồng hồ.

Cài lần đầu cho máy mới (gói đầy đủ, mang sẵn mọi thứ, cài khoảng một phút và không cần mạng):

- Máy Windows: [CaiDat-SonicRec-Windows-DayDu-v2.2.exe](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Windows-DayDu-v2.2.exe)
- Máy Mac chip Apple (M1 trở lên): [CaiDat-SonicRec-MacChipM-DayDu-v2.2.zip](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-MacChipM-DayDu-v2.2.zip)

Gói nhỏ dưới đây cài cần mạng nên lâu hơn; máy Mac chip Intel dùng gói nhỏ:

- Máy Mac: [CaiDat-SonicRec-Mac-v2.2.zip](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Mac-v2.2.zip)
- Máy Windows: [CaiDat-SonicRec-Windows-v2.2.exe](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Windows-v2.2.exe)

Máy đã cài thì không cần tải tay: ứng dụng tự báo có bản mới và hỏi trước khi cài.
Riêng máy cài trước khi có tên v1 (thẻ Cài đặt hiện mã 7 ký tự, không có chữ v) chưa tự báo được: tải tay bản mới nhất một lần, các lần sau tự báo.

Tệp `ban-moi.json` và thư mục `ban-cai/` do lệnh `dong_goi.py --xuat-ban` viết, đừng sửa tay.
