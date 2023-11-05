# Yulgang Crystal
โปรแกรมนี้จัดทำขึ้นมาเพื่อช่วยให้การเปลี่ยนลูกแก้ววิญญาณโดยไม่ต้องมาคอยเปลี่ยนเอง

✅ รองรับลูกแก้วระดับ ล่าง กลาง สูง\
✅ รองรับหลายหน้าจอ\
✅ สามารถข้ามบางหน้าจอไปได้ ถ้าไม่ต้องการ\
✅ ตั้งค่าหน่วงเวลาได้\
✅ แจ้งเตือนทาง Line Notify สำหรับลูกแก้วหมด หน้าจอหาย\
<br/>
<br/>
![image](https://github.com/meawmuay/yulgang-crystal/assets/50597818/290a57dc-11e6-42a1-9037-eedd006de163)

## เริ่มต้นใช้งาน

โปรแกรมนี้เขียนด้วยโปรแกรม Visual Studio 2022 และใช้ .NET Framework เวอร์ชั่น 6.0 เป็นอย่างต่ำ
### ดาวน์โหลด
[Yulgang Crystal Version 1.0.0](https://github.com/meawmuay/yulgang-crystal/releases/download/v1.0.0/Yulgang.Crystal.rar "Yulgang Crystal Latest Version")

### ติดตั้ง
ตัวโปรแกรมไม่มีความจำเป็นต้องติด แต่หากคุณยังไม่ได้ลง .NET Framework เวอร์ชั่น 6.0 หรือมากกว่า ดาวน์โหลดได้จากลิงก์ด้านล่าง

[Microsoft .NET Framework 6.0 (Web Installer)](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-aspnetcore-6.0.24-windows-x64-installer "Microsoft .NET Framework 6.0 (Web Installer)")

### วิธีใช้งาน
1. เปิดไฟล์ Yulgang Crystal.exe เพื่อเข้าใช้งาน
2. จะเจอหน้าต่าง คีย์ของโปรแกรม ให้ Copy Key ของคุณ ส่งให้ที่ https://www.facebook.com/messages/t/100000798267952
3. หลังจากได้ คีย์แล้วให้เอามาใส่ในช่อง Key ใช้งานโปรแกรม แล้วกดเปิดการใช้งาน
4. ตัวโปรแกรมจะมีให้คุณตั้งค่าหน่วงเวลา คุณสามารถเลือกได้
5. หลังจากนั้นให้กด โหลดข้อมูลเกม แล้วจะพบรายการจอเกมขวามือ หากคุณไม่ได้ใช้โปรแกรมช่วย Login คุณต้องเดาสุ่มเอาว่าจอไหนคือรายการไหน\
   ![image](https://github.com/meawmuay/yulgang-crystal/assets/50597818/79d11a48-ab93-45f4-b0fb-1745872e81f3)
6. สามารถ ติ๊กถูกออกได้ หากไม่ต้องการให้โปรแกรมทำงานที่จอนั้น
7. หลังจากนั้นให้กดเริ่มทำงาน โปรแกรมจะดึงจอเกมขึ้นมาเองและขยับเมาส์เอง

### การตั้งค่า Line Notify
1. ไปที่ https://notify-bot.line.me/th/ ที่ด้านขวามือให้เลือก เข้าสู่ระบบ\
   ![image](https://github.com/meawmuay/yulgang-crystal/assets/50597818/18026902-ac92-4075-8fc9-7ec91cb361d6)
2. หลังจากนั้น เลือก QR Code Login แล้วใช้มือถือถ่าย QR Code จากแอปไลน์
3. เมื่อเข้าสู่ระบบแล้วให้ไปที่ https://notify-bot.line.me/my/
4. เลื่อนลงมาจะเจอปุ่มที่ชื่อว่า Gererate Token หรือ สร้าง Token\
   ![image](https://github.com/meawmuay/yulgang-crystal/assets/50597818/c75e53b7-3119-4093-8669-a9b8ecd569c1)
5. ให้กรอกชื่อ Token เช่น Yulgang
6. ถัดมาให้ เลือก ไลน์ของเรา จะอยู่อันบนสุด แล้วกดสร้าง ก็จะได้ Token มา
7. ให้เอาไปใส่ที่โปรแกรม ตั้งค่า Token\
   ![image](https://github.com/meawmuay/yulgang-crystal/assets/50597818/5a86dd18-040d-4cdd-b73d-65069e7d81ea)
8. แล้วกดปุ่ม ทดสอบ หลังจากได้รับแจ้งเตือนแล้ว ให้กดปุ่มบันทึก
9. การแจ้งเตือนไลน์จะทำงานต่อหน้าจอ 1 ครั้งเท่านั้นไม่แจ้งเตือนซ้ำจนกว่าจะเริ่มโปรแกรมใหม่ เช่น มีหน้าจอ A ลูกแก้วผลึกหมด ก็จะมีการแจ้งเตือนทางไลน์ แล้วหลังจากนั้นโปรแกรมวนมาเช็คว่าหมดอีก ก็จะไม่แจ้งเตือนอีกแล้วจนกว่าจะเริ่มโปรแกรมใหม่อีกครั้ง




### หมายเหตุ
ทำไมถึงขึ้นตามรายการด้านล่างนี้
- Publisher : Unknown ในขณะที่เปิดโปรแกรม [(ตัวอย่าง)](https://i.imgur.com/peSlQDG.png "(ตัวอย่าง)")
- ตอนดาวน์โหลดเสร็จ บราวเซอร์แจ้งว่า "ไฟล์นี้ไม่ได้มีการดาวน์โหลดเป็นที่แพร่หลายและอาจเป็นอันตราย" หรือ "This file is not commonly downloaded and may be dangerous." [(ตัวอย่าง)](https://i.imgur.com/FkxEtZs.png "(ตัวอย่าง)")

เนื่องมาจาก ตัวโปรแกรมไม่ได้ Publish ด้วย Code Signing Certificate (จำเป็นต้องซื้อและยืนยันตัวตน) และตัวโปรแกรมต้องการสิทธิ์ Administrator เพื่อเข้าถึงฟังก์ชั่นตามด้านล่างนี้จาก Library user32.dll
- FindWindow
- SetWindowTextA
- GetForegroundWindow
- GetWindowText
