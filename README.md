# แนวทางการทำงาน ESP32 hello_world cook book
## 1. ระบุตัวอย่างที่ใช้ว่าเอามาจากตัวอย่างไหน
เลือกโปรเจค hello_world จาก show examples แล้วกด create
![image](https://github.com/user-attachments/assets/6bc2b934-056a-4906-a37e-dd3d41e2e5b6)

## 2. ระบุว่าจะแก้ไขตรงไหนบ้าง เพื่ออะไร
สามารถแก้ไขที่ฟังก์ชัน app_main ได้ printf("Hello world!\n"); หรือกำหนดฟังก์ชันให้แสดงข้อความแล้วเรียกใช้ผ่าน main ให้มาแสดงที่ terminal
![image](https://github.com/user-attachments/assets/56bd793e-f8a9-4742-aac7-3001cdc6ba38)

## 3. แสดงขั้นตอนการทำ project
เพิ่มฟังก์ชัน test ให้แสดงข้อความ hello world ที่ terminal ทุกๆ 1 วิและเรียกใช้งานฟังก์ชัน test ที่ main(จะลบออกให้หมดก็ได้เหลือแค่เรียกใช้งานฟังก์ชัน จะแสดงข้อความ ทุกๆ 1 วิ)
![image](https://github.com/user-attachments/assets/252b13bf-6825-4f35-9b9d-a7a349924f12)

## 4.แสดงผลการทำ project

![image](https://github.com/user-attachments/assets/309551d6-bafb-44f1-99fa-0240c4116558)

## 5.สรุปผลการทำ project
โปรเจคนี้เป็นโปรเจคพื้นฐานสำหรับผู้เริ่มต้น เน้นการสร้าง Task พื้นฐาน โดยให้แสดงออกมาทาง terminal/ Serial Monitor
