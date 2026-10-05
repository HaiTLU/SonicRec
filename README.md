# SonicRec: bản cài

Kho này chỉ giữ bản cài mới nhất của ứng dụng SonicRec: ghi âm cuộc họp và soạn biên bản (Trường Đại học Thăng Long). Ứng dụng đã cài đọc kho này để tự báo khi có bản mới. Mã nguồn không nằm ở đây.

Bản mới nhất: **v2.10**, ngày 5/10/2026.

1. Nút Kiểm tra trước buổi họp thay nút Thử micro: ghi thử 5 giây, nghe lại tiếng mình, máy báo micro to hay nhỏ.
2. Mở ứng dụng là máy tự xem ổ đĩa còn chỗ, Online đã đăng nhập chưa, Offline có mô hình chép lời chưa; chỉ báo khi có chỗ cần xem.
3. Thẻ mới Sổ việc: gom việc được giao ở mọi cuộc họp đã xong, lọc theo người và hạn, đánh dấu Xong, việc quá hạn chữ đỏ.
4. Bảng Tên riêng ở thẻ Cài đặt: ghi đúng tên người, tên đơn vị một lần, máy tự sửa khi chép lời và soạn biên bản.

Cài lần đầu cho máy mới (gói đầy đủ, mang sẵn mọi thứ, cài khoảng một phút và không cần mạng):

- Máy Windows: [CaiDat-SonicRec-Windows-DayDu-v2.10.exe](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Windows-DayDu-v2.10.exe)
- Máy Mac chip Apple (M1 trở lên): [CaiDat-SonicRec-MacChipM-DayDu-v2.10.zip](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-MacChipM-DayDu-v2.10.zip)

Gói nhỏ dưới đây cài cần mạng nên lâu hơn; máy Mac chip Intel dùng gói nhỏ:

- Máy Mac: [CaiDat-SonicRec-Mac-v2.10.zip](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Mac-v2.10.zip)
- Máy Windows: [CaiDat-SonicRec-Windows-v2.10.exe](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Windows-v2.10.exe)

Máy đã cài thì không cần tải tay: ứng dụng tự báo có bản mới và hỏi trước khi cài.
Riêng máy cài trước khi có tên v1 (thẻ Cài đặt hiện mã 7 ký tự, không có chữ v) chưa tự báo được: tải tay bản mới nhất một lần, các lần sau tự báo.

Tệp `ban-moi.json` và thư mục `ban-cai/` do lệnh `dong_goi.py --xuat-ban` viết, đừng sửa tay.
