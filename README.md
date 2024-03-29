# OpenKB Plugin for KidBrightIDE

ปลั๊กอินเสริม เพิ่มบล็อกเกี่ยวกับบอร์ด OpenKB ในโปรแกรม KidBrightIDE

## การติดตั้ง

ดาวน์โหลดไฟล์ปลั๊กอินจากหน้า releases จะได้ไฟล์ OpenKB.Plugin.for.KidBrightIDE.Vx.x.zip

### กรณีติดตั้งโปรแกรม KidBrightIDE ด้วยไฟล์ .exe

 1. เปิดโปรแกรม KidBrightIDE กด Plugins > Install Plugins
 2. เลือกไฟล์ปลั๊กอิน (OpenKB.Plugin.for.KidBrightIDE.Vx.x.zip) ที่ดาวน์โหลดไว้
 3. โปรแกรม KidBrightIDE จะปิดแล้วเปิดใหม่ บล็อกใหม่จะอยู่ในเมนู OpenKB

### กรณีติดตั้งด้วย Gitlab

 1. คลายไฟล์ OpenKB.Plugin.for.KidBrightIDE.Vx.x.zip ออกมาด้วยโปรแกรม WinRAR หรือ 7-zip จะได้โฟลเดอร์ openkb
 2. ย้ายโฟลเดอร์ openkb ไปไว้ในโฟลเดอร์ plugins ซึ่งจะอยู่ในโฟลเดอร์ kbide ณ ที่ ๆ สั่ง Clone มา
 5. เปิดโปรแกรม KidBrightIDE ขึ้นมา จะมีเมนู OpenKB เพิ่มขึ้นมา
 
## การใช้งาน
 
 ปลั๊กอินนี้ มีบล็อกให้เลือกใช้งานในเมนู OpenKB ดังนี้

### บล็อกอ่านค่าดิจิทัล

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกอ่านค่าดิจิทัล](https://www.img.in.th/images/8308365051e3252c0f8ca72f74c417fd.png) | ![digital read](https://www.img.in.th/images/a0d25099e1eacfab73061f62382bd188.png) |ฃ

ใช้อ่านค่าดิจิทัลจากช่อง IN1 IN2 DAC1 18 19 23 และ 17 โดยบล็อกจะให้ค่าเป็นตัวเลข 0 หรือ 1

### บล็อกเขียนค่าดิจิทัล

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกเขียนค่าดิจิทัล](https://www.img.in.th/images/96fd5e46e2660a13541d18c727659a68.png) | ![digital write](https://www.img.in.th/images/68b9d66dee3e531d12e61d0fa650e722.png) |

ใช้เขียนค่าดิจิทัลไปที่ช่อง OUT1 OUT2 DAC1 18 19 23 และ 17 โดยบล็อกจะรับค่าเป็นตัวเลขจำนวนเต็ม 0 หรือ 1

### บล็อกอ่านค่าแอนะล็อก

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกอ่านค่าแอนะล็อก](https://sv1.picz.in.th/images/2019/10/22/gWjvVN.png) | ![analog read](https://www.img.in.th/images/7d2ba4941374c5cb62b1b43dd3c1f639.png) |

ใช้อ่านค่าแอนะล็อกจากช่อง IN1 IN2 IN3 และ IN4 โดยบล็อกจะให้ค่าเป็นตัวเลข 0 ถึง 4095 (12 บิต)

### บล็อกเขียนค่าแอนะล็อก

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกเขียนค่าแอนะล็อก](https://sv1.picz.in.th/images/2019/10/22/gWjLiQ.png) | ![analog write](https://www.img.in.th/images/2919c91f1eeff2d87458607cf1c54bf2.png) |

ใช้สร้างสัญญาณ PWM ที่ช่อง OUT1 OUT2 DAC1 18 19 23 และ 17 โดยบล็อกจะรับค่าเป็นตัวเลขจำนวนเต็ม 0 ถึง 1023

### บล็อกควบคุมเซอร์โวมอเตอร์

| บล็อกภาษาไทย | บล็อกภาษาอังกฤษ |
|--|--|
| ![บล็อกควบคุมเซอร์โวมอเตอร์](https://www.img.in.th/images/62d148d75138fa9a6622c331bcb0151b.png) | ![servo](https://www.img.in.th/images/48b6915526a71ede7efd85371b7069b7.png) |

ใช้ควบคุมองศาการหมุนของเซอร์โวมอเตอร์ที่ช่อง OUT1 OUT2 DAC1 18 19 23 และ 17 บล็อกจะรับค่าเป็นตัวเลขจำนวนเต็ม 0 ถึง 179 (หน่วยองศา)
