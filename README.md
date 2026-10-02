# Lumivara Online — ดาวน์โหลดโปรแกรม

ตัวติดตั้งอย่างเป็นทางการของ **Lumivara Online** สำหรับ Windows, Android และ macOS
ทุกรุ่นโหลดเกมล่าสุดจาก [lumivaraonline.com](https://lumivaraonline.com/) และต้องเชื่อมต่ออินเทอร์เน็ต

## ดาวน์โหลด

| เครื่อง | รุ่น | ไฟล์ | ผู้พัฒนา |
| --- | --- | --- | --- |
| Windows 10/11 64-bit | 4.3.1 | [ตัวติดตั้ง `Lumivara-Online-4.3-Setup-x64.exe`](https://github.com/Gamezxz/lumivara-online-downloads/releases/download/windows-v4.3.1/Lumivara-Online-4.3-Setup-x64.exe) (159 MB)<br>[แบบ ZIP `Lumivara-Online-4.3-Windows-x64.zip`](https://github.com/Gamezxz/lumivara-online-downloads/releases/download/windows-v4.3.1/Lumivara-Online-4.3-Windows-x64.zip) (163 MB) | SABA DEV ([newkiss2582](https://github.com/newkiss2582)) |
| Android 8.0 ขึ้นไป | 1.9.0 | [`Lumivara-Online-Android-1.9.apk`](https://github.com/Gamezxz/lumivara-online-downloads/releases/download/android-v1.9.0/Lumivara-Online-Android-1.9.apk) (13.8 MB) | SABA DEV ([newkiss2582](https://github.com/newkiss2582)) |
| macOS Apple Silicon (M1 ขึ้นไป) | 0.1.0 | [`Lumivara.Online-0.1.0-arm64.dmg`](https://github.com/Gamezxz/lumivara-online-downloads/releases/download/v0.1.0/Lumivara.Online-0.1.0-arm64.dmg) (153 MB)<br>[แบบ ZIP `Lumivara.Online-0.1.0-arm64-mac.zip`](https://github.com/Gamezxz/lumivara-online-downloads/releases/download/v0.1.0/Lumivara.Online-0.1.0-arm64-mac.zip) (153 MB) | Lumivara Online |

ดูทุกรุ่นได้ที่หน้า [Releases](https://github.com/Gamezxz/lumivara-online-downloads/releases)

## Windows

โปรแกรมสำหรับ Windows 64-bit พร้อมโหมด Picture-in-Picture (PiP) และคีย์ลัดควบคุมหน้าต่าง

**ติดตั้ง:** ปิดเกมรุ่นเดิมก่อน เปิดไฟล์ `Setup.exe` เลือกโฟลเดอร์ติดตั้ง โปรแกรมจะสร้าง Shortcut บนเดสก์ท็อปให้
หรือใช้แบบ ZIP: แตกไฟล์ทั้งชุด แล้วเปิด `Lumivara Online.exe` ได้เลยโดยไม่ต้องติดตั้ง

| ปุ่ม | การใช้งาน |
| --- | --- |
| Ctrl+Shift+P | สลับ PiP / หน้าต่างปกติ |
| F11 หรือ Alt+Enter | สลับเต็มหน้าจอ |
| Esc | ออกจากเต็มหน้าจอ / กลับจาก PiP |
| F1 | แสดงวิธีใช้ |
| F8 | ซ่อนเกมลงถาดระบบและปิดเสียง |
| Ctrl+Shift+H | ซ่อนหรือเรียกกลับจากโปรแกรมอื่น |

ดับเบิลคลิกไอคอนเกมในถาดระบบเพื่อเรียกกลับได้เช่นกัน
โปรแกรมยังไม่ได้เซ็นลายเซ็นดิจิทัล จึงอาจมีคำเตือน Microsoft Defender SmartScreen หรือ Smart App Control ในช่วงแรก

## Android

ใช้ Android System WebView พร้อมโหมดเต็มจอแนวนอน หน้าต่างเกมขนาดเล็กที่ลากย้ายและปรับขนาดได้ ปุ่มลอย
เมนูแอปภาษาไทย/English และคลิปสอนติดตั้งในแอป (หน้าตั้งค่า → ▶ คลิปสอนติดตั้งและตั้งค่า)

1. ดาวน์โหลดไฟล์ `.apk`
2. เปิดไฟล์และอนุญาตการติดตั้งจากแหล่งนี้ หากระบบร้องขอ
3. เปิดแอป Lumivara Online แล้วอนุญาตการแสดงทับแอปอื่นเพื่อใช้หน้าต่างลอย
4. ตั้งค่าการแจ้งเตือนและแบตเตอรี่ตามคำแนะนำในแอป
5. เลือกเปิดเกมเต็มจอ หน้าต่างขนาดเล็ก หรือปุ่มลอย

หากมีแอปรุ่นเดิมอยู่แล้ว ให้ติดตั้งทับโดยไม่ถอนการติดตั้ง เพื่อเก็บข้อมูลเกมและบัญชี Guest เดิม
Google Login ในแอป Android ยังอยู่ระหว่างการทดลอง

## macOS

1. ดาวน์โหลดไฟล์ `.dmg`
2. เปิดไฟล์ แล้วลาก **Lumivara Online** ไปไว้ในโฟลเดอร์ Applications
3. เปิดเกมจาก Applications

แอป macOS เซ็นด้วย Developer ID และผ่าน Apple Notarization แล้ว

## ตรวจสอบไฟล์

ค่า SHA-256 ของทุกไฟล์อยู่ใน [`SHA256SUMS.txt`](SHA256SUMS.txt) และในแต่ละ Release

## เครดิต

Client สำหรับ Windows และ Android พัฒนาโดย **SABA DEV** ([newkiss2582](https://github.com/newkiss2582))
ต้นฉบับอยู่ที่ [Lumivara-Online-Client](https://github.com/newkiss2582/Lumivara-Online-Client) และ
[LumivaraOnline-APK](https://github.com/newkiss2582/LumivaraOnline-APK) — repo นี้เก็บสำเนาไว้ในโฟลเดอร์
[`clients/`](clients/) พร้อมตัวติดตั้งทุกไฟล์ใน Releases ดูรายละเอียดที่ [`clients/README.md`](clients/README.md)

Windows Portable รุ่น 0.1.0 เดิมของเรายังอยู่ใน Release [v0.1.0](https://github.com/Gamezxz/lumivara-online-downloads/releases/tag/v0.1.0)
แต่แนะนำให้ใช้ Client Windows รุ่น 4.3.1 แทน
