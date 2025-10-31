PHẦN I: CÀI MQTT
CÁCH 1:
Cài Mosquitto Broker trên Hassio
Vào Settings/ Add-ons/Add-ón Stores chọn Mosquito Broker
<img width="417" height="356" alt="image" src="https://github.com/user-attachments/assets/7dc6384e-6429-44ea-8b99-60c36de47f70" />

 
Chọn Configuration
Phần loggin
- username: home
  password: home1234
Thay thông tin loggin và password theo ý bạn.
  
CHÚ Ý: Các thông tin này phải khớp với thông tin cài đặt MQTT trên remote
Nhấn “Save”,  rồi “Start” 

Cài đặt MQTT trên Integrations của HASS:
Vào Settings/ Devices & Services
 
Chọn “Add integration” => MQTT => Configure
 
Phần Broker: nhập địa chỉ IP của HASS
username và password: Nhập chính xác như thông số đã đặt trong remote và Mosquitto Broker

 
CÁCH 2:
THAM KHẢO YOUTUBE CHO HASS TRÊN NASS
https://www.youtube.com/watch?v=2zsUGM1acYc

PHẦN 2: CÀI SAMBA SHARE
Cần cài Addin này trong mục addin và nhấn khởi động và thiết lập các thông số mật khẩu user liên quan để sau đó dùng user/pass này truy cập bộ nhớ để copy thư mục: tasmota IR
Tham khảo video và tìm cá video tương tự trên Youtube: https://drive.google.com/file/d/10D8-xoP71_rJf4BHF3YH1I4P_dlBJrH1/view?usp=drive_link

