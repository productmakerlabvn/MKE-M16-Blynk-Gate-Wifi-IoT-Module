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

#### Arduino:
- [Mạch Vietduino Uno (Arduino Uno Compatible)](https://www.makerlab.vn/vuno)
- [Mạch MakerEdu Shield for Vietduino](https://www.makerlab.vn/vietduinosd)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

#### mBlock:

- [Mạch MakerEdu Creator (Arduino Uno Compatible)](https://www.makerlab.vn/creator)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

#### Micro:bit:

- [Mạch Micro:bit V2](https://hshop.vn/products/kit-hoc-lap-trinh-stem-cho-tre-em-micro-bit-v2) hoặc các phiên bản tương thích.
- [Mạch MakerEdu Shield for Micro:bit](https://www.makerlab.vn/microbitsd)
- [Mạch màn hình MKE-M07 LCD1602 I2C Display Module](https://www.makerlab.vn/mkem07)

### Hướng dẫn sử dụng với Arduino (Code C)
[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt bộ thư viện Arduino cơ bản.](https://github.com/makerlabvn/Arduino-Vietduino)
- Tải và cài đặt [phần mềm Arduino tại đây.](https://www.arduino.cc/en/software)
- Trong Tools / Library Manager, tìm và cài đặt bộ thư viện tổng hợp "MAKERLABVN" by MakerLab.vn
- Mở chương trình mẫu "MKE_S01_Ultrasonic_LCD_Serial.ino" tại File / Examples / MAKERLABVN / Sensor / MKE_S01_Ultrasonic hoặc [tải chương trình mẫu tại đây](/arduino)
- Chọn board là Arduino Uno (mạch Vietduino Uno tương thích với Arduino Uno), chọn đúng cổng COM Port của mạch và tiến hành nạp chương trình.
- Kết nối mạch Vietduino Uno với MakerEdu Shield, kết nối cảm biến tại cổng [D12,13] và màn hình LCD vào cổng [I2C] trên MakerEdu Shield, cấp nguồn qua cổng USB của Vietduino Uno để thấy chương trình hoạt động.

### Hướng dẫn lập trình với mBlock (kéo thả khối)
[Hướng dẫn cài đặt phần mềm, nạp chương trình, cài đặt Extension mBlock cơ bản.](https://github.com/makerlabvn/mBlock-MakerEdu-Creator)
- Tải và cài đặt phần mềm mBlock 5 ([Windows](https://www.mediafire.com/file/ma55iajd7glwmbo/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Windows.zip/file) / [Mac Intel](https://www.mediafire.com/file/pjfngy6d7ktb55f/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_Intel.zip/file) / [Mac M1M2](https://www.mediafire.com/file/mfdkgpgnpa7uv2s/%255BMakerLab.vn%255D_mBlock_V5.4.3_for_Mac_M1M2.zip/file))
- Thêm Device "MakerEdu Creator" by MakerEduVN
- Thêm Extension "Upload Mode Broadcast" by mBlock Official
- Thêm Extension "MakerEdu Hardware" by MakerEduVN
- Mở [chương trình mẫu tại đây](/mBlock5), kết nối MakerEdu Creator với máy tính và nạp chương trình.
- Kết nối cảm biến với cổng [D3,D2] và màn hình LCD vào cổng [I2C] trên MakerEdu Creator, cấp nguồn qua cổng USB của MakerEdu Creator để thấy chương trình hoạt động.


### Hướng dẫn lập trình với Micro:bit (kéo thả khối)
[Hướng dẫn nạp chương trình, cài đặt Extension Micro:bit cơ bản.](https://github.com/makerlabvn/MakeCode-microbit)
- Khởi động phần mềm MakeCode tại: [https://makecode.microbit.org/](https://makecode.microbit.org/)
- Chọn My Projects / Import / Import URL theo đường link của chương trình mẫu: [https://github.com/devmakerlabvn/makecode-mke-s01-ultrasonic-distance-sensor](https://github.com/devmakerlabvn/makecode-mke-s01-ultrasonic-distance-sensor)
- Kết nối Micro:bit với máy tính và nạp chương trình.
- Kết nối mạch Micro:bit với MakerEdu Shield, kết nối cảm biến tại cổng [P0+P1] và màn hình LCD vào cổng [I2C] trên MakerEdu Shield, **cấp nguồn qua cổng USB của MakerEdu Shield** để thấy chương trình hoạt động.

## Hỗ trợ và liên hệ:

- Website: [https://www.makerlab.vn/](https://www.makerlab.vn/)
- Facebook: [https://www.facebook.com/makerlabvn](https://www.facebook.com/makerlabvn)

## Nhà phân phối

- Các bạn có thể mua sản phẩm của MakerLab tại các [Nhà Phân Phối.](https://www.makerlab.vn/distributor/)
