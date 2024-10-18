# MKE-M16 Blynk Gate Wifi IoT Module

## Giới thiệu

Với các mạch vi điều khiển không có chức năng Wifi nhưng lại quá quen thuộc với bạn như Arduino Uno, Arduino Mega 2560, Microbit,...thì việc xây dựng các ứng dụng IoT trở nên thật khó khăn. MKE-M16 Blynk Gate Wifi IoT Module giúp bạn giải quyết vấn đề này chỉ với vài bước thiết lập đơn giản, bạn đã có thể kết nối Wifi và xây dựng các ứng dụng IoT trên nền tảng Blynk đã quá nổi tiếng và quen thuộc hiện nay.

MKE-M16 Blynk Gate Wifi IoT Module được MakerLab.vn nghiên cứu và phát triển giúp các bạn DIY các thiết bị IoT nhanh và dễ dàng trên nền tảng Blynk, module có hai cách sử dụng là hoạt động độc lập bằng chính các chân GPIO có trên mạch hoặc hết hợp với các mạch vi điều khiển (như Arduino, Microbit,...) qua giao tiếp I2C.

MKE-M16 Blynk Gate Wifi IoT Module thuộc hệ sinh thái phần cứng Robotics MakerEdu nên có thể sử dụng trực tiếp an toàn với các mạch điều khiển trung tâm ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....với chuẩn kết nối Connector XH2.54 thông dụng.

## Thông số kỹ thuật

- Model: MKE-M16
- IC chính: ESP8266
- Sử dụng chuẩn Wifi băng tần: 2.4Ghz
- Tương thích với nền tảng Blynk.
- Điện áp hoạt động: 5VDC
- Dòng điện tiêu thụ khi hoạt động:
- Chuẩn giao tiếp: I2C / GPIO
- Điện áp giao tiếp: TTL 3.3VDC / 5VDC
- Sử dụng trực tiếp an toàn với các board mạch giao tiếp ở cả hai mức điện áp 3.3VDC và 5VDC như: Arduino, Raspberry Pi, Jetson Nano, Micro:bit,....
- Bổ sung thêm các thiết kế ổn định, chống nhiễu.
- Chuẩn kết nối: connector XH2.54 4Pins
- Thuộc hệ sinh thái phần cứng Robotics MakerEdu, tương thích tốt nhất khi sử dụng với các mạch điều khiển trung tâm của MakerEdu và MakerEdu Shield.

## Hình ảnh sản phẩm

![MKE_S01](/image/MKE_S01_2.jpg)

![MKE_S01](/image/MKE_S01_3.jpg)

## Kích thước sản phẩm

![MKE_S01](/image/MKE_S01_4.JPG)

## Các chân tín hiệu

- GND:	Chân cấp nguồn âm 0VDC
- 5V:	Chân cấp nguồn dương 5VDC
- TRIG:	Chân tín hiệu ngõ vào Trigger (Input: 3.3~5VDC)
- ECHO:	Chân tín hiệu ngõ ra Echo (Output: 3.3VDC)

## Hướng dẫn sử dụng

### Các thiết bị sử dụng trong bài hướng dẫn:

#### Chế độ độc lập:
- [Mạch MakerEdu Creator (Arduino Uno Compatible)](https://www.makerlab.vn/creator)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)
#### Chế độ kết hợp:
- [Mạch Vietduino Uno (Arduino Uno Compatible)](https://www.makerlab.vn/vuno)
- [Mạch MakerEdu Shield for Vietduino](https://www.makerlab.vn/vietduinosd)
### Hướng dẫn lập trình với mBlock (kéo thả khối)
- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device "MakerEdu Creator" by MakerEduVN
- Thêm Extension "Upload Mode Broadcast" by mBlock Official
- Thêm Extension "MakerEdu Hardware" by MakerEduVN
- Mở [chương trình mẫu tại đây](/mBlock5), kết nối mạch và nạp chương trình.

[![Ciaobot mblock](/image/mblock.png)](https://www.youtube.com/watch?v=fWIyjU7ekBY)


## Hỗ trợ và liên hệ:

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)
