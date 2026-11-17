# DocDee PDF

**โปรแกรม PDF ภาษาไทยฟรี** โดย [Supakor.Studio](https://supakor-studio.github.io)

อ่าน รวม แยก แก้ไขข้อความ เซ็นเอกสาร และสแกนเป็นข้อความ (OCR) ภาษาไทยที่อ่านเลขไทยได้ รองรับฟอนต์ Sarabun และวันที่แบบ พ.ศ. ทำงานในเครื่องของคุณ ไม่ส่งไฟล์ขึ้นอินเทอร์เน็ต

## ดาวน์โหลด

👉 **[ดาวน์โหลดรุ่นล่าสุด](https://github.com/supakor-studio/DocDee-releases/releases/latest)**

| ไฟล์ | ใช้เมื่อ |
|---|---|
| `DocDee-PDF-<รุ่น>-windows-x64.msi` | ติดตั้งตามปกติ (แนะนำ) |
| `DocDee-PDF-<รุ่น>-windows-x64-portable.zip` | ใช้แบบไม่ต้องติดตั้ง แตกไฟล์แล้วเปิด `DocDee.exe` |

ต้องการ Windows 10 หรือ 11 (64 บิต)

## วิธีติดตั้ง

1. ดาวน์โหลดไฟล์ `.msi` แล้วดับเบิลคลิก
2. ถ้า Windows ขึ้นหน้าจอสีน้ำเงิน **"Windows protected your PC"** ให้กด **More info** แล้วกด **Run anyway**
   ที่ขึ้นแบบนี้เพราะตัวติดตั้งยังไม่ได้ลงลายเซ็นดิจิทัลจากผู้ออกใบรับรอง ไม่ได้แปลว่าไฟล์มีไวรัส
   ตรวจว่าไฟล์ไม่ถูกแก้ไขได้ด้วยค่า SHA-256 ในหน้ารุ่นนั้นๆ (`Get-FileHash ชื่อไฟล์` ใน PowerShell)
3. ทำตามขั้นตอนของตัวติดตั้งจนเสร็จ
4. อยากให้เปิดไฟล์ PDF ด้วย DocDee ทุกครั้ง: เปิด DocDee ▸ การตั้งค่า ▸ ทั่วไป ▸ โปรแกรมเปิด PDF หลัก ▸ **เปิดการตั้งค่าแอปเริ่มต้น** แล้วเลือก DocDee PDF ให้ไฟล์ .pdf

📖 คู่มือแบบมีภาพประกอบ: [วิธีติดตั้ง DocDee PDF ด้วยไฟล์ .msi](https://supakor-studio.github.io/install-docdee.html)

## พบปัญหา / ติดต่อ

- ในโปรแกรม: เมนู **วิธีใช้ ▸ แจ้งปัญหา…**
- แชทเพจ Facebook: [m.me/Supakor.Studio](https://m.me/Supakor.Studio)
- อีเมล: supakor.studio@gmail.com

## ความเป็นส่วนตัว

[นโยบายความเป็นส่วนตัวของ DocDee PDF](https://supakor-studio.github.io/privacy-docdee.html)

## สัญญาอนุญาต

DocDee PDF พัฒนาต่อยอดจาก [PdfCraft](https://github.com/storytold/pdfcraft) ซึ่งเป็นซอฟต์แวร์โอเพนซอร์ส
(MIT OR Apache-2.0) ข้อความสัญญาอนุญาตและประกาศของทุกส่วนประกอบ (รวมถึง Tesseract OCR, ฟอนต์
และไลบรารีต่างๆ) อยู่ในโฟลเดอร์ที่ติดตั้งโปรแกรม

ชื่อ DocDee, ไอคอนโปรแกรม และโลโก้ Supakor.Studio เป็นเครื่องหมายการค้าของ Supakor.Studio
สงวนสิทธิ์ทั้งหมด

---

repo นี้มีไว้สำหรับไฟล์ติดตั้งเท่านั้น
