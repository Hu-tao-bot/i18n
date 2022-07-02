## วิธีการ Pull เพื่อให้เรานำภาษานี้เข้าสู่บอทของเรา
ในขั้นตอนนี้เป็นสิ่งสำคัญในการ Pull เพื่อทางเรานั้นจะทำการอัพภาษานี้เข้าสู่บอทของเรา

## 1. การตั้งชื่อ File
ในการตั้งชื่อ File นั้นจะต้องไปเป็นตามของ [BCP 47 Code](https://en.wikipedia.org/wiki/IETF_language_tag#List_of_subtags) 
ใน Subtag เพื่อให้ทางเรานั้นสะดวกในการอัพขึ้นบอท Hu tao โดยให้ตั้งชื่อ File ดังนี้ (โดยส่วนนี้จะอ้างอิงกับ [Discord developer locals](https://discord.com/developers/docs/reference#locales))

|             ภาษา          | ชื่อไฟล์ที่ต้องตั้ง |
|---------------------------|------------|
|  Danish                   |   da       |
|  German                   |   de       |
|  English, UK              |   en-gb    |
|  English, US              |   en-us    |
|  English, ES              |   en-es    |
|  French	                |   fr       |
|  Croatian                 |   hr       |
|  Italian                  |   it       |
|  Lithuanian               |   lt       |
|  Hungarian                |   hu       |
|  Dutch                    |   nl       |
|  Norwegian                |   no       |
|  Polish                   |   pl       |
|  Portuguese, Brazilian    |   pt-br    |
|  Romanian, Romania        |   ro       |
|  Finnish                  |   fi       |
|  Swedish                  |   sv-se    |
|  Vietnamese               |   vi       |
|  Turkish                  |   tr       |
|  Czech                    |   cs       |
|  Greek                    |   el       |
|  Bulgarian                |   bg       |
|  Russian                  |   ru       |
|  Ukrainian                |   uk       |
|  Hindi                    |   hi       |
|  Thai                     |   th       |
|  Chinese, China           |   zh-cn    |
|  Japanese                 |   ja       |
|  Chinese, Taiwan          |   zh-tw    |
|  Korean                   |   ko       |

และนามสกุล File นั้นจะต้อง `.yaml` เพื่อความสะดวกในการอัพขึ้นบอทของพวกเรา

## 2. อัพขึ้น Pull request
ในการอัพขึ้น Pull request นั้น จำเป็นต้องเขียนข้อมูลในเพิ่มเติมดังนี้
- แปลภาษาอะไร
- แปลให้กับอะไร (interaction, commands)
- เครดิตผู้แปล