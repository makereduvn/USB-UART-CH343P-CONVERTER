# Mạch USB-UART CH343P Converter

## Giới thiệu sản phẩm
**Mạch USB-UART CH343P Converter** là mạch chuyển đổi giao tiếp **USB Type-C sang UART TTL** sử dụng **IC CH343P chính hãng WCH**, hỗ trợ tốc độ truyền dữ liệu lên đến **6Mbps**, mang lại khả năng giao tiếp ổn định, tốc độ cao và tương thích với nhiều hệ điều hành như **Windows, macOS, Linux và Android**. Đây là công cụ lý tưởng để lập trình, Debug và giao tiếp Serial với các vi điều khiển như **Arduino, ESP32, ESP8266, STM32, AVR, PIC** cùng nhiều thiết bị UART TTL khác.

Khác với các mạch USB-UART thông thường, sản phẩm được thiết kế tối ưu cho việc **nạp chương trình tự động**. Ngoài hai chân **TXD** và **RXD**, mạch còn tích hợp sẵn chân **AR (Arduino Reset)** cùng tụ kích Reset giúp tự động Reset khi nạp chương trình cho Arduino. Đồng thời, mạch cũng được trang bị **ER (ESP Reset)** và **IO0**, đã tích hợp đầy đủ linh kiện điều khiển Auto Download, cho phép nạp chương trình cho **ESP32** và **ESP8266** hoàn toàn tự động mà không cần nhấn nút **BOOT** hoặc **RESET**.

Mạch hỗ trợ lựa chọn mức điện áp giao tiếp **3.3V hoặc 5V** thông qua **Jumper VIO**, giúp tương thích với hầu hết các bo mạch phát triển và module điện tử hiện nay. Bên cạnh đó, sản phẩm còn tích hợp **IC ổn áp LM1117-3.3V** có khả năng cung cấp dòng lên đến **700mA**, đủ để cấp nguồn trực tiếp cho nhiều bo mạch và module hoạt động ở mức điện áp 3.3V.

Để tăng độ bền và độ an toàn trong quá trình sử dụng, mạch còn được trang bị **diode bảo vệ nguồn USB** và **diode chống tĩnh điện (ESD Protection)**, giúp bảo vệ cả máy tính và thiết bị kết nối khỏi các sự cố về điện.

Với thiết kế nhỏ gọn, nhiều tính năng tích hợp và khả năng tương thích cao, **USB-UART CH343P Converter** là công cụ không thể thiếu dành cho Maker, sinh viên, kỹ sư điện tử và nhà phát triển hệ thống nhúng.

## Ưu điểm nổi bật
- **Sử dụng IC CH343P chính hãng WCH**
  - Phiên bản nâng cấp của CH340G với tốc độ truyền dữ liệu lên đến **6Mbps**.
  - Hoạt động ổn định, độ trễ thấp và khả năng tương thích cao.
- **Nạp chương trình tự động cho Arduino**
  - Tích hợp chân **AR (Arduino Reset)** cùng tụ kích Reset.
  - Không cần bổ sung mạch Auto Reset khi nạp chương trình.
- **Hỗ trợ Auto Download cho ESP32 và ESP8266**
  - Tích hợp sẵn chân **ER (ESP Reset)** và **IO0**.
  - Tự động đưa ESP vào chế độ Download mà không cần nhấn nút BOOT hoặc RESET.
- **Hỗ trợ mức logic 3.3V và 5V**
  - Chuyển đổi nhanh bằng Jumper **VIO**.
  - An toàn khi làm việc với cả hệ thống 3.3V và 5V.
- **Nguồn 3.3V công suất lớn**
  - Tích hợp IC **LM1117-3.3V**.
  - Dòng đầu ra lên đến **700mA**, đủ cấp nguồn cho nhiều module ESP, cảm biến và mạch ngoại vi.
- **Cổng USB Type-C hiện đại**
  - Kết nối chắc chắn.
  - Dễ dàng sử dụng với các loại cáp USB-C phổ biến.
- **Bảo vệ an toàn**
  - Tích hợp diode bảo vệ nguồn USB.
  - Tích hợp diode chống tĩnh điện (ESD Protection).
- **Hỗ trợ đa nền tảng**
  - Windows 7 / 8 / 8.1 / 10 / 11
  - macOS
  - Linux
  - Android
- **Ứng dụng đa dạng**
  - Lập trình Arduino.
  - Nạp firmware cho ESP32 và ESP8266.
  - Debug Serial.
  - Giao tiếp UART TTL.
  - Phát triển hệ thống nhúng, IoT và Robot.

## Thông số kỹ thuật
| Thông số | Mô tả |
|----------|---------|
| **Model** | USB-UART CH343P Converter |
| **Chip USB-UART** | WCH CH343P |
| **Chuẩn giao tiếp Host** | USB Type-C |
| **Chuẩn giao tiếp Device** | UART TTL |
| **Tốc độ truyền dữ liệu** | 50bps ~ 6Mbps |
| **Điện áp logic UART** | 3.3V / 5V (chọn bằng Jumper VIO) |
| **Nguồn 3.3V tích hợp** | LM1117-3.3V |
| **Dòng đầu ra 3.3V** | Tối đa 700mA |
| **Các chân giao tiếp** | TXD, RXD, GND, VCC, 3V3, 5V |
| **Chân hỗ trợ Arduino** | AR (Arduino Auto Reset) |
| **Chân hỗ trợ ESP** | ER (ESP Reset), IO0 (Auto Download) |
| **Mạch bảo vệ** | Diode bảo vệ USB, ESD Protection |
| **Hệ điều hành hỗ trợ** | Windows, macOS, Linux, Android |
| **Ứng dụng** | Arduino, ESP32, ESP8266, STM32, AVR, PIC, Debug Serial, IoT, Robot |

## Sơ đồ chân (Pinout)
| Chân | Chức năng | Mô tả |
|------|-----------|-------|
| **3V3** | Nguồn 3.3V | Nguồn 3.3V được tạo bởi IC LM1117, dòng cấp tối đa khoảng **700mA**. |
| **AR** | Arduino Auto Reset | Chân Reset dành cho Arduino, đã tích hợp tụ kích Reset giúp tự động Reset khi nạp chương trình mà không cần thêm linh kiện ngoài. |
| **GND** | Ground | Chân Mass (0V), cần nối chung với thiết bị cần giao tiếp. |
| **5V** | Nguồn 5V | Điện áp 5V lấy trực tiếp từ cổng USB Type-C, dùng để cấp nguồn cho mạch ngoài. |
| **TXD** | UART Transmit | Chân truyền dữ liệu UART từ CH343P đến vi điều khiển hoặc thiết bị ngoại vi. Kết nối với chân **RX** của thiết bị. |
| **RXD** | UART Receive | Chân nhận dữ liệu UART từ vi điều khiển hoặc thiết bị ngoại vi. Kết nối với chân **TX** của thiết bị. |
| **ER** | ESP Auto Reset | Chân điều khiển Reset của ESP32/ESP8266, phục vụ chức năng Auto Download khi nạp firmware. |
| **IO0** | ESP Boot Mode | Chân điều khiển GPIO0 của ESP32/ESP8266, tự động đưa ESP vào chế độ Download khi nạp chương trình. |
| **VIO** | Logic Level Select | Jumper lựa chọn mức điện áp logic cho TXD và RXD (**3.3V hoặc 5V**). |

## Cài đặt Driver
Thông thường Driver sẽ tự nhận trên hầu hết các hệ điều hành, nếu máy tính chưa nhận driver, [tải và cài đặt Driver tại đây.](https://www.wch-ic.com/downloads/CH341SER_ZIP.html)

### Kích thước
![USB-UART CH343P](/extras/ch343p1.jpg)

## Hình ảnh sản phẩm
![USB-UART CH343P](/extras/ch343p2.png)
![USB-UART CH343P](/extras/ch343p3.png)

## Miễn trừ trách nhiệm
Sản phẩm này là bo mạch phát triển được thiết kế phục vụ cho mục đích nghiên cứu, thử nghiệm và học tập, không phải là một thiết bị hoàn chỉnh. Trong trường hợp người dùng kết hợp mạch này với các linh kiện, thiết bị hoặc phần mềm khác để tạo thành một hệ thống hoặc sản phẩm hoàn chỉnh, mọi chức năng và tính phù hợp của sản phẩm sau cùng đều thuộc trách nhiệm của người dùng.
