# Ratchagitja.md

แปลงราชกิจจานุเบกษา ให้เป็นรูปแบบที่คอมพิวเตอร์อ่านและประมวลผลต่อได้ง่ายขึ้น

![Ratchagitja Midjourney Cover](/data/assets/cover.jpg)

## Rules

- แปลงตรงตามตัวอักษร
- ตัวเลขไทยทั้งหมดแปลงเป็นเลขอารบิก (ใช้ [UnSarabun](https://github.com/narze/unsarabun.js) ช่วยได้)
- มี Metadata ที่จำเป็น (ใช้ [YAML Frontmatter](https://markdoc.dev/docs/frontmatter))
  - วัน/เดือน/ปี ที่ประกาศ (ปีเป็น พ.ศ.)
  - หมวด เลขเล่ม เลขตอน
  - PDF URL อ้างอิง
  - อื่นๆ (ถ้ามี)
- ตัดข้อมูลที่ไม่จำเป็นออกไป เช่น หัวกระดาษ (Page Header)

## หมายเหตุ

ถ้ามีข้อมูลที่แปลงเป็นตัวอักษรไม่ได้ เช่น รูปภาพ หรือ ตารางข้อมูลที่มีขนาดใหญ่มาก ให้เขียนเป็นหมายเหตุเอาไว้ก่อน แล้วจะแก้ไขให้เป็น Markdown หรือ HTML ต่อไป

## Contribution

- เลือกราชกิจจานุเบกษาจากเว็บไซต์ https://ratchakitcha.soc.go.th แปลงเป็น Markdown หรือ txt แล้วเปิด Pull Request
- สร้าง Issue เพื่อเสนอแนะ หรือ แจ้งปัญหา
- ช่วยกันตรวจสอบความถูกต้องของข้อมูลใน Pull Request
