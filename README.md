PHẦN I: CÀI MQTT
CÁCH 1:
Cài Mosquitto Broker trên Hassio
Vào Settings/ Add-ons/Add-ón Stores chọn Mosquito Broker
 <img width="624" height="351" alt="image" src="https://github.com/user-attachments/assets/da7d21e0-c8d5-4d02-ad19-54bfa97fb6ad" />
 
Chọn Configuration
Phần loggin
- username: home
  password: home1234
Thay thông tin loggin và password theo ý bạn.
  <img width="624" height="371" alt="image" src="https://github.com/user-attachments/assets/23668e7b-4fc1-4b70-a588-2c82f95ec2a0" />
  
CHÚ Ý: Các thông tin này phải khớp với thông tin cài đặt MQTT trên remote
Nhấn “Save”,  rồi “Start” 

Cài đặt MQTT trên Integrations của HASS:
Vào Settings/ Devices & Services
 <img width="624" height="425" alt="image" src="https://github.com/user-attachments/assets/f6138cae-c0de-4c15-92a9-97ae7d5eeb66" />
 
Chọn “Add integration” => MQTT => Configure
 <img width="578" height="585" alt="image" src="https://github.com/user-attachments/assets/c4c2deba-d9f0-4a5c-aafd-cef4979a68a4" />
 
Phần Broker: nhập địa chỉ IP của HASS
username và password: Nhập chính xác như thông số đã đặt trong remote và Mosquitto Broker
<img width="624" height="535" alt="image" src="https://github.com/user-attachments/assets/420bd8da-960c-465e-8dfb-0b2f0a2cc403" />

CÁCH 2:
THAM KHẢO YOUTUBE CHO HASS TRÊN NASS
https://www.youtube.com/watch?v=2zsUGM1acYc

PHẦN 2: CÀI SAMBA SHARE
Cần cài Addin này trong mục addin và nhấn khởi động và thiết lập các thông số mật khẩu user liên quan để sau đó dùng user/pass này truy cập bộ nhớ để copy thư mục: tasmota IR
Tham khảo video và tìm cá video tương tự trên Youtube: https://drive.google.com/file/d/10D8-xoP71_rJf4BHF3YH1I4P_dlBJrH1/view?usp=drive_link

