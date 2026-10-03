# ดาวเด่นบัวหลวง 101 — PR Website

โครงสร้างสำหรับ GitHub Pages แยก HTML / CSS / JS / JSON เพื่อให้ทีมอัปเดตข้อมูลได้ง่าย

## โครงสร้าง
- `index.html` หน้าแรก
- `pages/` หน้าโครงการ ผู้เข้าร่วม กิจกรรม ข่าวสาร ติดต่อ และโปรไฟล์ผู้เข้าร่วม
- `css/style.css` สไตล์หลัก
- `js/main.js` JavaScript หลัก
- `data/participants.json` ข้อมูลผู้เข้าร่วม
- `data/institutions.json` ข้อมูลสถาบัน
- `data/activities.json` ข้อมูลกิจกรรม

## เพิ่มผู้เข้าร่วม
แก้ `data/participants.json` โดยใช้ schema ที่อยู่ท้ายไฟล์ จากนั้น GitHub Pages จะโหลดข้อมูลและสร้างการค้นหา/กรองให้อัตโนมัติ

> อย่าใส่ข้อมูลส่วนบุคคลที่ยังไม่ได้รับอนุญาตให้เผยแพร่

## GitHub Pages
อัปโหลดทั้งโฟลเดอร์ขึ้น repository แล้วเปิด Settings → Pages → Deploy from branch → เลือก `main` และ `/ (root)`
