# AutomatedLineNotify1
Automated Line Notify via Google Calendar

## โปรเจคส่วนตัวใช้กับกลุ่มรุ่นคณะเภสัชจุฬาฯ เป็นบอทแจ้งเตือนตามข้อความที่ระบุไว้ใน description และตามเวลาที่กำหนดไว้ ตัวอย่างดังภาพด้านล่าง

![image](https://user-images.githubusercontent.com/82520836/206361304-533954b8-2604-4995-a620-de24dcf7d897.png)
![image](https://user-images.githubusercontent.com/82520836/206361071-943b9349-d9e5-4cda-a92d-7f5365718ca0.png)

โค้ดเก็บอยู่ใน main ใน repo นี้

จำเป็นต้องใช้ public link ของ gg calendar และ line notify token จึงจะสามารถใช้งานได้

ใช้ **appscripts** เป็นตัวรันโค้ดตามเวลาที่กำหนด โดยตั้ง trigger ดังตัวอย่างด้านล่าง

![image](https://user-images.githubusercontent.com/82520836/206361426-5dc9d1b5-e334-4f33-8e1d-f0c171ae03cd.png)
![image](https://user-images.githubusercontent.com/82520836/206361445-7d7716a8-884b-4560-bff4-f9cc610aaaf3.png)
![image](https://user-images.githubusercontent.com/82520836/206361481-c3e9dac3-ad81-4245-a7d1-a78e844a2395.png)

**หมายเหตุ:** ถ้าจำไม่ผิด แอคที่ใช้รัน appscripts จะต้อง access calendar นั้น ๆ ได้ด้วยจึงจะสามารถใช้งานได้

**limitation**: บางครั้งบอทจะพิมพ์เป็นภาษา html แต่น่าจะเป็นข้อจำกัดของ google calendar มากกว่า / โค้ดจะค่อนข้างรก ต้องขออภัยด้วยครับ

สามารถ contribute ได้นะครับ เพราะอยากเห็นเหมือนกันว่าจะสามารถพัฒนาต่อไปได้อย่างไรบ้าง จบการศึกษาอาจจะมาทำต่อ เพราะอันนี้ทำไว้ตั้งแต่ตอนปี 3-4 ขอบคุณครับ
