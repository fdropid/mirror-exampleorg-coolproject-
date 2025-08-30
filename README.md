# route : https://github.com/fdropid/mirror-exampleorg-coolproject-/tree/acae256ca9f240c310e9baa9ed994d88e933396e
# Permanent link : /
แผ่นโกง Markdown
หัวข้อที่ 1
Markup :  # Heading 1 #

-OR-

Markup :  ============= (below H1 text)
หัวข้อที่ 2
Markup :  ## Heading 2 ##

-OR-

Markup: --------------- (below H2 text)
หัวข้อที่ 3
Markup :  ### Heading 3 ###
หัวข้อที่ 4
Markup :  #### Heading 4 ####
ข้อความทั่วไป

Markup :  Common text
ข้อความที่เน้น

Markup :  _Emphasized text_ or *Emphasized text*
ข้อความที่ขีดฆ่า

Markup :  ~~Strikethrough text~~
ข้อความที่แข็งแกร่ง

Markup :  __Strong text__ or **Strong text**
ข้อความที่เน้นหนัก

Markup :  ___Strong emphasized text___ or ***Strong emphasized text***
ลิงก์ชื่อและhttp://www.google.fr/หรือhttp://example.com/

Markup :  [Named Link](http://www.google.fr/ "Named link title") and http://www.google.fr/ or <http://example.com/>
หัวข้อ-1

Markup: [heading-1](#heading-1 "Goto heading-1")
ตารางแบบนี้ :

ส่วนหัวแรก	ส่วนหัวที่สอง
เซลล์เนื้อหา	เซลล์เนื้อหา
เซลล์เนื้อหา	เซลล์เนื้อหา
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell
การเพิ่มท่อ|ในเซลล์ :

ส่วนหัวแรก	ส่วนหัวที่สอง
เซลล์เนื้อหา	เซลล์เนื้อหา
เซลล์เนื้อหา	-
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  |  \| 
ตารางจัดชิดซ้าย ขวา และตรงกลาง

ส่วนหัวจัดชิดซ้าย	ส่วนหัวจัดชิดขวา	ส่วนหัวจัดกึ่งกลาง
เซลล์เนื้อหา	เซลล์เนื้อหา	เซลล์เนื้อหา
เซลล์เนื้อหา	เซลล์เนื้อหา	เซลล์เนื้อหา
Left aligned Header | Right aligned Header | Center aligned Header
| :--- | ---: | :---:
Content Cell  | Content Cell | Content Cell
Content Cell  | Content Cell | Content Cell
code()

Markup :  `code()`
    var specificLanguage_code = 
    {
        "data": {
            "lookedUpPlatform": 1,
            "query": "Kasabian+Test+Transmission",
            "lookedUpItem": {
                "name": "Test Transmission",
                "artist": "Kasabian",
                "album": "Kasabian",
                "picture": null,
                "link": "http://open.spotify.com/track/5jhJur5n4fasblLSCOcrTp"
            }
        }
    }
Markup : ```javascript
         ```
รายการหัวข้อย่อย
กระสุนซ้อนกัน
กระสุนย่อยซ้อนกัน ฯลฯ
รายการหัวข้อย่อย 2
 Markup : * Bullet list
              * Nested bullet
                  * Sub-nested bullet etc
          * Bullet list item 2

-OR-

 Markup : - Bullet list
              - Nested bullet
                  - Sub-nested bullet etc
          - Bullet list item 2 
รายการหมายเลข
รายการหมายเลขซ้อนกัน
ซึ่งมีหมายเลข
ซึ่งมีหมายเลข
 Markup : 1. A numbered list
              1. A nested numbered list
              2. Which is numbered
          2. Which is numbered
งานที่ยังไม่เสร็จสิ้น
งานที่เสร็จสมบูรณ์
 Markup : - [ ] An uncompleted task
          - [x] A completed task
งานที่ยังไม่เสร็จสิ้น
งานย่อย
 Markup : - [ ] An uncompleted task
              - [ ] A subtask
บล็อคโควต

บล็อกโควตแบบซ้อนกัน

Markup :  > Blockquote
          >> Nested Blockquote
เส้นแนวนอน :

Markup :  - - - -
รูปภาพพร้อม alt :

รูปภาพอื่นๆ

Markup : ![picture alt](http://via.placeholder.com/200x150 "Title is optional")
ข้อความพับได้:

ชื่อเรื่อง 1
ชื่อเรื่อง 2
Markup : <details>
           <summary>Title 1</summary>
           <p>Content 1 Content 1 Content 1 Content 1 Content 1</p>
         </details>
<h3>HTML</h3>
<p> Some HTML code here </p>
ลิงค์ไปยังส่วนที่เจาะจงของหน้า:

ไปที่ด้านบน

Markup : [text goes here](#section_name)
          section_title<a name="section_name"></a>    
ปุ่มลัด:

⌘F

⇧⌘F

Markup : <kbd>⌘F</kbd>
รายการปุ่มลัด:

สำคัญ	เครื่องหมาย
ตัวเลือก	⌥
ควบคุม	⌃
สั่งการ	⌘
กะ	⇧
แคปส์ล็อค	⇪
แท็บ	⇥
เอสซี	⎋
พลัง	⌽
กลับ	↩
ลบ	⌫
ขึ้น	↑
ลง	↓
ซ้าย	←
ขวา	→
อิโมจิ:

❗ ใช้ไอคอนอีโมจิเพื่อเพิ่มความสวยงามให้กับข้อความ 👍 ค้นหาโค้ดอีโมจิได้ที่emoji-cheat-sheet.com

Markup : Code appears between colons :EMOJICODE:

##
# Mirror repository

This repository is a GitHub mirror of an upstream repository. It is kept in sync using a GitHub Actions workflow that periodically clones the upstream repository with `--mirror` and pushes it to this repository.

Important:
- The workflow requires a secret `UPSTREAM_REPO` (or `UPSTREAM_TOKEN` + repo URL).
- The repository owner is `fdropid` (change as needed).
- Default branch: `main`
