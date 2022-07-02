# Interaction 
THAI | [ENG](../../docs/README_INTERACTION_EN.md)
----
Interaction เป็นส่วนสำหรับการแสดงข้อมูลหน้า Embed เช่น ข้อมูลตัวละคร, ข้อมูลโลก, ข้อผิดพลาด และอื่น ๆ

## ความหมายของคีย์
```
- info: ข้อมูลเกี่ยวกับบอท
- login: ตรวจสอบสถานะเข้าสู่ระบบ
- profile: ดูข้อมูล Profile
- help: คำสั่งช่วยเหลือ
- realtime: ดูข้อมูล Realtime ของ Resin, คำขอประจำวัน, การออกสำรวจ, Realm Currency และอื่น ๆ อีกมากมาย
- redeemcode: แลกรหัสเพื่อรับไอเทม
- summary:
    - info: ดูภาพรวมข้อมูล (จำนวนวันใช้งาน ความสำเร็จ, ตัวละคร, อื่น ๆ)
    - world: ดูข้อมูลสำรวจโลกกว้าง
    - teapot: ดูข้อมูลกานํ้าชา (Serenitea Pot)
- abyss:
    - info: ดูข้อมูล Abyss รอบนี้
    - floor: ดูข้อมูล Abyss ของชั้นนั้น
- characters:
    - list: ดูรายชื่อตัวละคร
    - info: ดูข้อมูลของตัวละครของคุณ
- wish:
    - list: ดูข้อมูลกิจกรรมอธิษฐานทั้งหมด
- daily:
    - auto-cliam-opened: เปิดรับรางวัลเช็คอินของวันนี้อัตโนมัติ
    - auto-cliam-closed: ปิดรับรางวัลเช็คอินของวันนี้อัตโนมัติ
    - daily-month: ดูข้อมูลการรับรางวัลเช็คอินของเดือนนี้
    - daily-cliamed: รับรางวัลเช็คอินของวันนี้สมบูรณ์
```

## ความหมายของคีย์ข้อผิดพลาด
```
- LOGIN_REQUIRED: จำเป็นต้องเข้าสู่ระบบ
- USER_NOT_PUBLIC: ฟังชั่นนี้ยังไม่ได้ถูกเปิดใช้งาน
- DATA_NOT_FOUND: ไม่พบข้อมูล
- ABYSS_FLOOR_USER_NOT_FOUND: ไม่พบชั้นของ Abyss รอบนี้
- ABYSS_FLOOR_RANGE_ERROR: เลือกช่วงห้อง Abyss ไม่ถูกต้อง
- CHARACTERS_NOT_FOUND: ไม่พบตัวละคร
- RATE_LIMIT: ใช่คำสั่งถี่เกินกำหนด
- REDEEM_INVALID: แลกรหัสไม่สำเร็จ
- REDEEM_CLAIMED: รหัสนี้ถูกใช้งานแล้ว
- REDEEM_COOLDOWN: ใช้งานระบบแลกรหัสบ่อยเกินไป
- REDEEM_EXCEPTION: AR. ตํ่าเกินไป
- REDEEM_LOGIN_REQUIRED: ไม่ได้เปิดฟังชั่นแลกรหัส
- COMMAND_NOT_SUPPORT: คำสั่งไม่รองรับ Login ด้วยวิธี UID และ Hoyolab ID
- GACHA_NOT_FOUND: ไม่พบตู้อษิฐาน
- DAILY_ALREADY_CLAIMED: ได้ถูกเช็คอินแล้ว
- UNKNOW_ERROR: ไม่ทราบข้อผิดพลาด
```