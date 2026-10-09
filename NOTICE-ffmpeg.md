# Thông báo về ffmpeg

Các gói cài "Đầy đủ" (tên có chữ `DayDu`) trong thư mục `ban-cai/` mang sẵn chương trình ffmpeg (qua gói Python imageio-ffmpeg 0.6.0) để SonicRec ghi âm. SonicRec chạy ffmpeg như một chương trình riêng qua dòng lệnh, không liên kết thư viện ffmpeg vào mã SonicRec.

Cấu hình dựng của ba bản ffmpeg đã kiểm, đọc từ chuỗi cấu hình ghi trong chính tệp (7/10/2026; đọc, không chạy tệp ở Mac và Windows):

| Nền | Bản ffmpeg | Cấu hình | Giấy phép |
|---|---|---|---|
| Mac chip Apple | 7.1 (tệp `ffmpeg-macos-aarch64-v7.1`) | `--enable-gpl`, gồm libx264 và libx265, không có `--enable-version3` | GPL phiên bản 2 trở lên |
| Windows | 7.1 (tệp `ffmpeg-win-x86_64-v7.1.exe`) | `--enable-gpl --enable-version3`, gồm libx264 và libx265 | GPL phiên bản 3 |
| Linux (bản dựng thử) | 7.0.2-static, johnvansickle.com | `--enable-gpl --enable-version3`, gồm libx264, libx265, libxvid | GPL phiên bản 3 |

Cả ba đều theo GNU General Public License, không phải LGPL. SonicRec phát hành phần ffmpeg theo các điều khoản của GPL phiên bản 3 (tệp `GPL-3.0.txt`); bản Mac cho phép chọn phiên bản 3 vì ghi "phiên bản 2 trở lên".

Bản quyền ffmpeg thuộc các tác giả của dự án FFmpeg (https://ffmpeg.org). SonicRec không phải là sản phẩm của dự án FFmpeg và dự án không bảo trợ SonicRec.

## Mã nguồn tương ứng (GPL v3, mục 6)

Mã nguồn tương ứng của ffmpeg đi kèm các gói trên lấy được tại:

- Mã nguồn ffmpeg 7.0.2 và 7.1: https://ffmpeg.org/releases/ (tệp `ffmpeg-7.0.2.tar.xz`, `ffmpeg-7.1.tar.xz`).
- Mã nguồn các thư viện bên trong bản dựng Linux: https://johnvansickle.com/ffmpeg/ (mục source code của bản 7.0.2).
- Mã nguồn bản Mac và Windows do imageio-ffmpeg đóng gói: theo mã nguồn của nhà dựng ghi trong gói imageio-ffmpeg 0.6.0 (https://github.com/imageio/imageio-ffmpeg). Chưa xác minh nhà dựng cụ thể của hai tệp này và nơi họ đặt mã nguồn các thư viện bên trong (libx264, libx265...); phải xác minh trước khi coi lời hứa dưới đây là đủ.

Lời hứa bằng văn bản: trong thời hạn ít nhất ba năm kể từ ngày phát hành mỗi bản cài, ai đã nhận bản cài có thể yêu cầu mã nguồn tương ứng đúng bản đã đóng gói bằng cách mở issue ở kho HaiTLU/SonicRec; chi phí chỉ là chi phí sao chép.

Bạn có quyền sao chép, sửa và phân phối lại riêng chương trình ffmpeg theo GPL v3, kể cả tệp ffmpeg trích từ bản cài. Giấy phép của SonicRec (tệp `LICENSE`) không hạn chế quyền đó.
