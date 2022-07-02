# โครงสร้างของ i18n
THAI | [ENG](../docs/README_LANG_EN.md)
----
```
\lang
|
|---\interaction
|   |
|   |- th.yaml
|   |- en-us.yaml
|   |- ...
|
|----\commands
|   |
|   |- th.yaml
|   |- en-us.yaml
|   |- ...
|
|- i18n.yaml
```
- [interaction](./interaction/) : เป็น Folder สำหรับแสดงหน้า Embed เช่น ข้อมูลตัวละคร, ข้อมูลโลก, ข้อผิดพลาด และอื่น ๆ 
- [commands](./commands/) : เป็น Folder สำหรับแสดง Slash command ว่าคำสั่งนี้ไว้ทำอะไร **(Discord ยังไม่เปิดบริการนี้)**
- [i18n.yaml](./i18n.yaml) : เป็น File สำหรับแสดงภาษาที่สามารถใช้งานได้ ณ ตอนนี้