# HE_THONG_PHUN_NUOC_TU_DONG_IOT_HCMUS

****************************************** VIDEO DEMO*****************************************

https://www.youtube.com/watch?v=mGog2_89G6g&ab_channel=PhuocDinh

I. GIẢNG VIÊN HƯỚNG DẪN :
- CAO XUÂN NAM
- ĐẶNG HOÀI THƯƠNG

II. THÀNH VIÊN NHÓM
- 20127287 Đinh Cao Hồng Phước
- 20127546 Võ Thanh Lâm 
- 20127561 Nguyễn Hoài Mẫn 

III. NGUỒN GỐC Ý TƯỞNG
- Tên sản phẩm: hệ thống phun nước tự động điều khiển bằng cảm biến nhiệt độ.
- Nguồn gốc ý tưởng: hiện nay, sự nóng lên toàn cầu là một trong những vấn đề lớn 
mà con người phải đối mặt, nhưng phần lớn nguyên nhân là do con người gây ra. 
Việc trái đất nóng lên gây đã ảnh hưởng rất lớn đến sức khỏe và đời sống của mỗi 
người. Chính vì thế, nhiều hộ gia đình đã tìm đến các giải pháp để bảo vệ sức khỏe 
của gia đình mình, một trong những phương án khá phổ biến là sử dụng máy điều 
hòa. Tuy nhiên, sử dụng máy điều hòa cũng có nhiều hạn chế: máy điều hòa sẽ làm 
cho da bị khô, bụi bặm theo đó sẽ bám vào các vật dụng trong gia đình, làm không 
gian phòng nhà bạn trở nên ngột ngạt, phạm vi hoạt động của máy lạnh khá hạn chế, 
đặc biệt gia đình có người già và trẻ nhỏ thì sẽ dễ mắc phải các căn bệnh về đường 
hô hấp, việc sử dụng máy điều hòa ở các công xưởng,các trang trại sẽ tốn một mức 
chi phí khổng lồ về việc lắp đặt, tiêu thụ điện và quan trọng nhất là sử dụng máy 
điều hòa làm việc nóng lên toàn cầu trở nên nhanh hơn. Vì thế sản phẩm được tạo ra 
với mong muốn giúp giảm thiểu sự nóng lên toàn cầu, cải thiện đời sống sinh hoạt 
của người dân, phù hợp với thu nhập của đại đa số hộ gia đình và phạm vi hoạt động 
khá rộng sử dụng cho toàn bộ ngôi nhà.

IV. MÔ TẢ SẢN PHẨM
1. Mô tả chức năng của toàn hệ thống: 
- Sử dụng mạch ESP 8266 kèm theo chức năng kết nối wifi để điều khiển hệ
thống một cách tự động, hoặc người dùng có thể tự điều khiển hệ thống theo 
cách thủ công.
- Cảm ứng nhiệt độ được lắp đặt ở trong nhà với khả năng tự đo nhiệt độ, tính 
toán và thực hiện việc phun nước tự động theo mức nhiệt độ tối đa hoặc tối 
thiểu đã cài đặt trước đó. Khi nhiệt độ tăng cao quá mức mà người dùng thiết 
lập thì thiết bị sẽ bật máy bơm làm mát hoặc khi nhiệt độ thấp dưới mức quy 
định thì tắt máy bơm. Việc điều khiển này có thể được thực hiện thông qua 
các nút bấm trên thiết bị hoặc website.
- Khi bật máy bơm hoạt động để làm mát, đèn led sẽ sáng, gửi thông báo lên 
web, ngược lại khi máy bơm tắt thì đèn led cũng sẽ tắt.
- Thiết bị sẽ có 3 nút nhấn: Một nút nguồn để bật tắt máy bơm và hai nút để
cài đặt mức nhiệt độ tối đa, tối thiểu để hệ thống hoạt động tự động.
- Các thông tin như trạng thái hoạt động của thiết bị, các mức nhiệt độ tối đa, 
tối thiểu mà người dùng thiết lập, nhiệt độ hiện tại mà cảm biến nhiệt độ đo 
được sẽ được thể hiện trên trang web. Người dùng cũng có thể can thiệp vào 
hoạt động của hệ thống thông qua web bằng các thao tác như: Bật tắt máy 
bơm, điều chỉnh mức nhiệt độ tối đa, tối thiểu.
- Nhiệt độ đo được của cảm biến, lịch sử đăng nhập, đăng xuất của người dùng 
trên trang web sẽ được lưu trữ trên MongoDB cloud để người dùng theo dõi.
- Hệ thống có thêm chức năng gửi cảnh báo về cho người dùng khi nhiệt độ
quá cao
hoạt động của hệ thống thông qua web bằng các thao tác như: Bật tắt máy 
bơm, điều chỉnh mức nhiệt độ tối đa, tối thiểu.
- Nhiệt độ đo được của cảm biến, lịch sử đăng nhập, đăng xuất của người dùng 
trên trang web sẽ được lưu trữ trên MongoDB cloud để người dùng theo dõi.
- Hệ thống có thêm chức năng gửi cảnh báo về cho người dùng khi nhiệt độ
quá cao
hoạt động của hệ thống thông qua web bằng các thao tác như: Bật tắt máy 
bơm, điều chỉnh mức nhiệt độ tối đa, tối thiểu.
- Nhiệt độ đo được của cảm biến, lịch sử đăng nhập, đăng xuất của người dùng 
trên trang web sẽ được lưu trữ trên MongoDB cloud để người dùng theo dõi.
- Hệ thống có thêm chức năng gửi cảnh báo về cho người dùng khi nhiệt độ
quá cao

2. Các ưu điểm của hệ thống:
- Tiết kiệm điện năng.
- Chi phí lắp đặt và vận hành thấp.
- Hệ thống lắp đặt đơn giản.
- Bảo trì hệ thống đơn giản.
- Phạm vi hoạt động khá rộng.
- Hệ thống hoạt động tự động.
- Hệ thống hoạt động êm ái.
- Tạo độ ẩm, giảm nhiệt độ môi trường và làm dịu không khí trong ngôi nhà.
- Giảm thiểu được thời gian và công sức làm mát theo cách thủ công.
- Bảo vệ môi trường, giảm thiểu sự nóng lên toàn cầu.

3. Các nhược điểm của hệ thống:
- Hệ thống đầu phun hay bị tắc nghẽn. Vì vậy, sắm thêm một bộ lọc là quan 
trọng và cần được kiểm tra thường xuyên.
- Tốc độ làm mát của hệ thống khá chậm.

4. Phương hướng cải tiến cho thiết bị: 
- Hệ thống có thể lắp đặt thêm chức năng phun sương bên trong căn nhà, kèm 
theo các chế độ phun sương sát khuẩn, lọc không khí, phun khử mùi.
Hệ thống phun nước tự động 20CLC05 – Nhóm 8 4 - Lắp đặt thêm hệ thống năng lượng mặt trời để cung cấp điện cho toàn hệ
thống.
- Lắp đặt thêm cảm biến đo mực nước. Tự động bơm nước vào bể chứa khi 
gần hết nước.
- Lắp đặt thêm hệ thống rèm che nắng, tự động kéo màn che lại khi có nắng 
gắt, nâng cao hiệu xuất hoạt động cho hệ thống phun nước.

5. Hướng dẫn sử dụng:
a. Trên thiết bị: 
- Bật/tắt máy bơm: ấn vào nút power.
- Setting nhiệt độ để kích hoạt máy bơm:
+ Ấn cùng lúc hai nút “+” và “-”.
+ Nếu không muốn điều chỉnh nhiệt độ: ấn cùng lúc hai nút “+” và “-”.
+ Nếu muốn điều chỉnh nhiệt độ: ấn nút “power”, con trỏ sẽ nhấp 
nháy đến dòng setting max lúc này ta có thể setting max, khi ấn lần kế
tiếp con trỏ sẽ nhấp nháy đến dòng setting min lúc này ta có thể setting 
min, ấn lần thứ 3 con trỏ sẽ mất, lúc này để thoát setting và up giá trị
min max vừa set ta sẽ ấn cùng lúc hai nút “+” và “-”, nếu muốn set lại 
thì ấn nút power.
Chú ý: chế độ auto là chế độ mà thiệt bị sẽ tự hoạt động (a), chế độ này sẽ bật 
máy bơm khi nhiệt độ hiện tại lớn hơn max đến khi nhiệt độ nhỏ hơn min. Chế độ unauto là chế độ mà thiết bị sẽ hoạt động bán tự động, chế độ unauto kích 
hoạt khi nhiệt độ đang nhỏ hơn min mà người dùng bật máy bơm hoặc nhiệt 
độ lớn hơn max mà người dùng tắt máy bơm, chế độ này sẽ chuyển sang auto 
khi ta ấn nút power cho máy bơm hoạt động đúng theo cơ chế hoạt động của 
auto, nhưng chế độ này tự chuyển sang auto khi nhiệt độ nhỏ hơn khoảng giới 
hạn lim hoặc lớn hơn giới hạn max để tránh trường hợp khi người dùng quên 
chỉnh lại chế độ auto.
Hệ thống phun nước tự động 20CLC05 – Nhóm 8 5
b. Trên node red: 
- Thể hiện trạng thái hoạt động của thiết bị để người dùng có thể tùy chỉnh:
+ Trạng thái hoạt động của máy bơm: Bật/tắt máy bơm.
+ Cài đặt lại các thông tin như nhiệt độ tối đa/tối thiểu để hệ thống hoạt 
động tự động.

III. Thiết kế 3D sản phẩm của nhóm
![image](https://user-images.githubusercontent.com/74586096/221396457-30e2e9e0-1719-4df6-8e6c-5bd908bc296c.png)
![image](https://user-images.githubusercontent.com/74586096/221396474-639ba57a-89e6-4d96-9794-2a1627f718df.png)
![image](https://user-images.githubusercontent.com/74586096/221396477-8862ee31-7bd5-49fb-8f2d-f8595410e744.png)
![image](https://user-images.githubusercontent.com/74586096/221396482-55592164-ec06-47df-9d07-4432f6c51711.png)

V. Sơ đồ truyền và nhận dữ liệu giữa các đối tượng trong hệ thống IoT
![image](https://user-images.githubusercontent.com/74586096/221396495-849a9a80-fe92-4e2a-beed-d0e296d8d714.png)

VI.Giao diện Web và mô tả các chức năng của Web
1. Trang login: 
- Link trang web: maybom.herokuapp.com
- Đăng nhập vào bảng điều khiển của hệ thống (mặc định tài khoản, mật khẩu 
là admin)
![image](https://user-images.githubusercontent.com/74586096/221396516-2ebfb9bf-d413-491f-8f7a-38c70ef819de.png)
2. Bảng điều khiển:
![image](https://user-images.githubusercontent.com/74586096/221396535-11923c65-4ebb-4ca5-b354-e58c59195d11.png)
![image](https://user-images.githubusercontent.com/74586096/221396542-2feae795-f1fc-4217-a9fa-5b1d4b5d7ac4.png)
![image](https://user-images.githubusercontent.com/74586096/221396549-05921c03-bab9-45a1-ac7d-b6802132a30f.png)

VII. Giải thích flow NodeRED
![image](https://user-images.githubusercontent.com/74586096/221396570-076a6894-4083-422e-974b-5f55ce69145a.png)
- max temp, min temp, current temp, pump, auto pump: Phân rã cụm thông tin nhận 
được từ dưới thiết bị thành từng thông tin riêng.
- set max, set max web, set min, set min web, set pump: Set thông tin vào các biến.
- myMongoDB MYDB: Gửi nhiệt độ hiện tại lên cloud.
- get change max web, get change pump web, get change min web và 3 node switch:
Chặn không cho trang web gửi thông tin liên tục về thiết bị mà chỉ gửi khi có sự thay 
các thông số trên web.
- get max web, send max web, get pump, send pump web, get min web, send min 
web, 20127546/send: Lấy thông tin, biến đổi thông tin và gửi lên 
test.mosquitto.org:1883.
- change auto pump: Điều chỉnh auto pump.
![image](https://user-images.githubusercontent.com/74586096/221396580-6ea1463a-cfdf-4423-bc4e-7e18a0b1e47e.png)
- set timer: set bộ đếm thời gian bằng 0 khi mới khởi động.
- set timer -=1: Sau mỗi phút thì timer sẽ giảm đi 1 và dừng lại khi timer bằng 0.
- switch, switch, http request: Gửi tin nhắn về điện thoại nếu nhiệt độ quá cao 
(≥ 30℃). Mỗi lần gửi cách nhau 30 phút.
- get change pump, get change max, get change min và 3 node switch: Chặn không 
cho set lại liên tục các thông số trên web, chỉ cho phép khi có thông tin từ thiết bị 
gửi lên web.
- set pump web, set max web, set min web: Set lại các biến dữ liệu trên web.
- myMongoDB MYDB: Gửi tình trạng máy bơm lên cloud.

VIII. Tài liệu tham khảo:

- https://drive.google.com/drive/folders/1xglLnX-R-1ZFUTqdpvq0tOl0EkZxNtQ?fbclid=IwAR31dMQ9FQb7EJT88A_6zhJv3FrtxU1QC6Q4YD2dEprn_ne
UxvOFWbHnLL8
- https://community.homey.app/t/node-red-a-widget-based-dashboard-working-withhomey-trough-mqtt/18798/432?page=22
- https://iot.busmap.vn/kham-pha-the-gioi-iot-voi-bsmart-bai-0/?fbclid=IwAR32SlbzPt1CGLe4xKp_5v3dP_AeJ1_VVLuAzM43aUfi7jIc8EWpmAOD02Y
- https://blog.unicloud.com.vn/iot/iot-wificonfig/?fbclid=IwAR16vdAb3zeFRLNQ_tm5dV4Dza22OIDIKSdRw6h39CE_TSky7gmqCIOAyA0
- https://vidieukhien.xyz/2018/03/25/esp8266-smartconfig-cau-hinh-wifi-cho-esp-bangdien-thoai-esp-touch-protocal-bai-4/?fbclid=IwAR11gCPLgWAy_ByQa3ziIktsdurDLjVoNyr6Iylm7sFJbG6UJPMOlrfiYiI



