# HCMUT251-TKHTN-TN01-BTL
## Descriptions:

Bài tập lớn môn Thiết kế Hệ thống Nhúng (EE3003)
### GVHD: Bùi Quốc Bảo
### Members: 
1. Nguyễn Anh Duy Trác - MSSV: 2313524
2. Phan Đình Đạt - MSSV: 2310684

## Overview
### Hệ thống giám sát môi trường
Hệ thống theo dõi các chỉ số môi trường như: Nhiệt độ (Temperature), Độ ẩm (Humidity), Ánh sáng (Light), và liên tục cập nhật các chỉ số lên màn hình LCD. Hệ thống cung cấp phản hồi về thị giác (LEDs) và thính giác (buzzer) để biểu thị trạng thái cho người dùng.

## System Specs 
1. Sử dụng nguồn vào 5V DC cấp vào DC Socket hoặc USB Port.
2. Môi trường hoạt động ổn định: phòng lab (0–50 °C, 20–85% RH, không ngưng tụ).
3. Hệ thống có 2 chế độ hoạt động: Manual (mặc định) và Automatic.

## Các chế độ hoạt động 
1. **Manual (thủ công):** Màn hình LCD hiển thị tại một chỉ số môi trường và ngưỡng cảnh báo đã được thiết lập (bằng software) và chỉ thay đổi khi người dùng nhấn Nút chuyển màn hình (Next/ Prev).
2. **Auto (tự động):** Màn hình LCD tự động chuyển màn hình hiện thị chỉ số môi trường sau mỗi chu kỳ nhất định (tối thiểu 3 giây và điều chỉnh bằng software). Khi đó 2 Nút chuyển màn hình (Next/ Prev) sẽ bị khóa.

## LEDs và Buzzer 
### LED Indicators
Hệ thống có 3 đèn LED báo khi có một chỉ số môi trường vượt mức đã xác định
- **LED 1 (RED Led):** Báo hiệu Nhiệt độ (Temperature).
- **LED 2 (BLUE Led):** Báo hiệu Độ ẩm (Humidity).
- **LED 3 (Yellow Led:)** Báo hiệu Ánh sáng (Light).

### Buzzer
Buzzer phát ra âm thanh báo trong hướng phát 10cm để báo hiệu 1 trong 3 chỉ số đã vượt ngưỡng xác định.

