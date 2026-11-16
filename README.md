# SonicRec: bản cài

Kho này chỉ giữ bản cài mới nhất của ứng dụng SonicRec: ghi âm cuộc họp và soạn biên bản (Trường Đại học Thăng Long). Ứng dụng đã cài đọc kho này để tự báo khi có bản mới. Mã nguồn không nằm ở đây.

Giấy phép: SonicRec là phần mềm bản quyền, bảo lưu mọi quyền (tệp `LICENSE`). Gói đầy đủ mang sẵn ffmpeg theo GPL v3: xem `NOTICE-ffmpeg.md` và `GPL-3.0.txt`.

Bản mới nhất: **v2.21**, ngày 16/11/2026.

1. Khi tài khoản Google chính hết lượt hoặc bị từ chối tạo sổ mới, máy tự chuyển sang tài khoản dự phòng và báo rõ đã hết lượt, thay cho câu "Có lỗi khi xử lý".
2. Sửa lỗi bấm Làm lại ở cuộc họp có chọn thêm Tóm tắt hoặc Việc cần làm bị báo lỗi.
3. Được chọn thư mục Google Drive, OneDrive làm nơi lưu cuộc họp; máy hiện cảnh báo để xác nhận trước.

Cài lần đầu cho máy mới (gói đầy đủ, mang sẵn mọi thứ, cài khoảng một phút và không cần mạng):

- Máy Windows: [CaiDat-SonicRec-Windows-DayDu-v2.21.exe](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Windows-DayDu-v2.21.exe)
- Máy Mac chip Apple (M1 trở lên): [CaiDat-SonicRec-MacChipM-DayDu-v2.21.zip](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-MacChipM-DayDu-v2.21.zip)

Gói nhỏ dưới đây cài cần mạng nên lâu hơn; máy Mac chip Intel dùng gói nhỏ:

- Máy Mac: [CaiDat-SonicRec-Mac-v2.21.zip](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Mac-v2.21.zip)
- Máy Windows: [CaiDat-SonicRec-Windows-v2.21.exe](https://raw.githubusercontent.com/HaiTLU/sonicrec/main/ban-cai/CaiDat-SonicRec-Windows-v2.21.exe)

Máy đã cài thì không cần tải tay: ứng dụng tự báo có bản mới và hỏi trước khi cài.
Riêng máy cài trước khi có tên v1 (thẻ Cài đặt hiện mã 7 ký tự, không có chữ v) chưa tự báo được: tải tay bản mới nhất một lần, các lần sau tự báo.

Tệp `ban-moi.json` và thư mục `ban-cai/` do lệnh `dong_goi.py --xuat-ban` viết, đừng sửa tay.
