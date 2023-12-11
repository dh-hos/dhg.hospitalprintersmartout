### HospitalPrinterSmartOut - Thông tin cập nhật

<div align="center" style="font-size:xx-small">(✨: Chức năng mới,🐛: Chỉnh lỗi, #️⃣: Giải quyết công việc) </div>

-  #️⃣: https://github.com/dh-hos/dhg.hospitalprinter/issues/54 [OK]
-  ✨: Bổ sung chức năng chọn tivi để thể hiện thông tin ra tivi [OK]

-  #️⃣: https://github.com/dh-hos/dhg.hospitalprinter/issues/73 [OK]
-  🐛: Fix lỗi không thể hiện được form thể hiện số thứ tự bệnh nhân ra tivi [OK]

-  ✨: Thêm parameter donvi (Diễn giải quầy phát thuốc) thể hiện form in ra tivi ![](../MoTaThayDoi/Outtv/ThemPara-donvi-01.png)![](../MoTaThayDoi/Outtv/ThemPara-donvi-02.png) [OK]
>
- ✨: Bổ sung chức năng in phiếu đối với bệnh nhân ưu tiên (BV Quận 12). Mặc định Printer hoặc HospitalPrinterSmartOut sẽ lấy mã đơn vị sẽ theo `kho cấp phát`, đối tượng ưu tiên của kho này sẽ được ghép chuỗi `".uutien"` phía sau. Để cấu hình thể hiện đối tượng ưu tiên phải cấu hình thêm `madonvi.config` trong thư mục cài đặt (nếu không có tập tin `madonvi.config` này thì chương trình sẽ lấy mặc định theo kho cấp phát). ![Alt text](../MoTaThayDoi/Outtv/madonvi-config-00.png)![Alt text](../MoTaThayDoi/Outtv/madonvi-config-01.png)![Alt text](../MoTaThayDoi/Outtv/madonvi-config-02.png) [OK]
