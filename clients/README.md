# Client จาก SABA DEV (newkiss2582)

Client Windows และ Android ของ Lumivara Online พัฒนาโดย **SABA DEV** ([newkiss2582](https://github.com/newkiss2582))
และใช้เป็นรุ่นทางการตั้งแต่ 3 ตุลาคม 2026 โฟลเดอร์นี้เก็บสำเนาของ repo ต้นฉบับไว้ เผื่อต้นฉบับถูกย้ายหรือลบ

| โฟลเดอร์ | ต้นฉบับ | commit ที่คัดลอก |
| --- | --- | --- |
| [`windows/`](windows/) | [newkiss2582/Lumivara-Online-Client](https://github.com/newkiss2582/Lumivara-Online-Client) | `21361f9` |
| [`android/`](android/) | [newkiss2582/LumivaraOnline-APK](https://github.com/newkiss2582/LumivaraOnline-APK) | `104d0be` |

ทั้งสองโฟลเดอร์รวมเข้ามาพร้อมประวัติ commit ของต้นฉบับ (`git log -- clients/windows`)
ณ วันที่คัดลอก repo ต้นฉบับมีเฉพาะ README ส่วนโปรแกรมอยู่ในหน้า Releases เท่านั้น

## ตัวติดตั้งที่เก็บสำเนาไว้

ไฟล์ทุกไฟล์คัดลอกจาก Releases ของต้นฉบับแบบไม่แก้ไข (SHA-256 ตรงกับไฟล์ต้นฉบับ)

| Release ของเรา | Release ต้นฉบับ | ไฟล์ | SHA-256 |
| --- | --- | --- | --- |
| [`windows-v4.3.1`](https://github.com/Gamezxz/lumivara-online-downloads/releases/tag/windows-v4.3.1) | [`Lumivara-Online-4.3`](https://github.com/newkiss2582/Lumivara-Online-Client/releases/tag/Lumivara-Online-4.3) | `Lumivara-Online-4.3-Setup-x64.exe` | `1d78d8dbc96bb0359da189af9fc7cbbd5bc3d4050f81a72494639a7dbf1d5470` |
| | | `Lumivara-Online-4.3-Windows-x64.zip` | `cbb359463c4f124ac0bd7336b3712b7f711e5f68e79d68488c5ceda2ef367bbf` |
| [`android-v1.9.0`](https://github.com/Gamezxz/lumivara-online-downloads/releases/tag/android-v1.9.0) | [`android-v1.9.0`](https://github.com/newkiss2582/LumivaraOnline-APK/releases/tag/android-v1.9.0) | `Lumivara-Online-Android-1.9.apk` | `353a0b10ddfb1dc2eabef8db75020bd9d2a75c558fc8b973068a1deb4ee0e5a8` |

## ข้อมูลตัวโปรแกรม

**Windows 4.3.1** — Electron 44.5.1 โหลด `https://lumivaraonline.com/` ในหน้าต่างที่ปิด Node integration
และเปิด sandbox มีโหมด PiP, ซ่อนเกมลงถาดระบบ และเล่นต่อเมื่อย่อหน้าต่าง ข้อมูลเข้าสู่ระบบเก็บที่
`%APPDATA%\Lumivara Online` ยังไม่ได้เซ็น Authenticode

**Android 1.9.0** — package `com.lumivaraonline.floating`, versionName `1.9.0`, รองรับ Android 8.0 ขึ้นไป
ใช้ Android System WebView โหลด `https://lumivaraonline.com/`
ใบรับรองที่ใช้เซ็น APK: `CN=Lumivara Client Local Build`
SHA-256 `E7:B3:D1:FE:05:BC:D9:6A:6B:DC:15:48:65:31:00:78:6A:25:1E:2B:A1:F3:29:82:4E:75:63:3E:C8:8C:F7:1D`
APK รุ่นถัดไปต้องเซ็นด้วยใบรับรองเดียวกันจึงจะติดตั้งทับรุ่นนี้ได้
