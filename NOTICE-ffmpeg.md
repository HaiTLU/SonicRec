# Thông báo về ffmpeg

Các gói cài "Đầy đủ" (tên có chữ `DayDu`) trong thư mục `ban-cai/` mang sẵn chương trình ffmpeg (qua gói Python imageio-ffmpeg 0.6.0) để SonicRec ghi âm. SonicRec chạy ffmpeg như một chương trình riêng qua dòng lệnh, không liên kết thư viện ffmpeg vào mã SonicRec.

Bản ffmpeg đã kiểm (Linux, 7.0.2-static, dựng bởi johnvansickle.com) được dựng với `--enable-gpl --enable-version3`, gồm libx264, libx265, libxvid, nên theo GNU General Public License phiên bản 3 (tệp `GPL-3.0.txt`). Bản Mac (v7.1) và Windows (v7.1) cùng gói chưa kiểm cấu hình, được coi là cũng theo GPL cho tới khi kiểm xong.

Bản quyền ffmpeg thuộc các tác giả của dự án FFmpeg (https://ffmpeg.org). SonicRec không phải là sản phẩm của dự án FFmpeg và dự án không bảo trợ SonicRec.

## Mã nguồn tương ứng (GPL v3, mục 6)

Mã nguồn tương ứng của ffmpeg đi kèm các gói trên lấy được tại:

- Mã nguồn ffmpeg 7.0.2 và 7.1: https://ffmpeg.org/releases/ (tệp `ffmpeg-7.0.2.tar.xz`, `ffmpeg-7.1.tar.xz`).
- Mã nguồn các thư viện bên trong bản dựng Linux: https://johnvansickle.com/ffmpeg/ (mục source code của bản 7.0.2).
- Mã nguồn bản Mac và Windows do imageio-ffmpeg đóng gói: theo mã nguồn của nhà dựng ghi trong gói imageio-ffmpeg 0.6.0 (https://github.com/imageio/imageio-ffmpeg).

Lời hứa bằng văn bản: trong thời hạn ít nhất ba năm kể từ ngày phát hành mỗi bản cài, ai đã nhận bản cài có thể yêu cầu mã nguồn tương ứng đúng bản đã đóng gói bằng cách mở issue ở kho HaiTLU/SonicRec; chi phí chỉ là chi phí sao chép.

Bạn có quyền sao chép, sửa và phân phối lại riêng chương trình ffmpeg theo GPL v3, kể cả tệp ffmpeg trích từ bản cài. Giấy phép của SonicRec (tệp `LICENSE`) không hạn chế quyền đó.
