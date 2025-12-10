# Environment Monitoring PCB Project
## Descriptions:
HCMUT251-TKHTN-TN01-BTL
Bài tập lớn môn Thiết kế Hệ thống Nhúng (EE3003)
### GVHD: Bùi Quốc Bảo
### Members: 
1. Nguyễn Anh Duy Trác - MSSV: 2313524
2. Phan Đình Đạt - MSSV: 2310684

## Overview
### Hệ thống giám sát môi trường
Hệ thống theo dõi các chỉ số môi trường như: Nhiệt độ (Temperature), Độ ẩm (Humidity), Ánh sáng (Light), và liên tục cập nhật các chỉ số lên màn hình LCD. Hệ thống cung cấp phản hồi về thị giác (LEDs) và thính giác (buzzer) để biểu thị trạng thái cho người dùng.

## System Specifications 
1. Sử dụng nguồn vào 5V DC cấp vào DC Socket hoặc USB Port.
2. Môi trường hoạt động ổn định: phòng lab (0–50 °C, 20–85% RH, không ngưng tụ).
3. Hệ thống có 2 chế độ hoạt động: View (mặc định) và Adjust (điều chỉnh).

## Chế độ hoạt động (Operation) 
1. **View (hiển thị):** Khi Switch ON: Màn hình LCD hiển thị tại một chỉ số môi trường và ngưỡng cảnh báo đã được thiết lập. Người dùng sử dụng 2 nút nhấn NEXT và PREV để thay đổi chỉ số hiện tại.
2. **Adjust (chỉnh ngưỡng):** Gạt Swich OFF: Trạng thái thay đổi ngưỡng của giá trị hiện tại.
- Sử dụng 2 Nút INC và DEC để tăng giảm giá trị ngưỡng với độ phân giải 0.1 đơn vị.
- Gạt Switch về ON để xác nhận Ngưỡng mong muốn.

## LEDs và Buzzer 
### LED Indicators
Hệ thống có 3 đèn LED báo khi có một chỉ số môi trường vượt mức đã xác định
- **LED 1 (RED Led):** Báo hiệu Nhiệt độ (Temperature).
- **LED 2 (BLUE Led):** Báo hiệu Độ ẩm (Humidity).
- **LED 3 (Yellow Led:)** Báo hiệu Ánh sáng (Light).

### Buzzer
Buzzer phát ra âm thanh báo trong hướng phát 10cm để báo hiệu 1 trong 3 chỉ số đã vượt ngưỡng xác định.

