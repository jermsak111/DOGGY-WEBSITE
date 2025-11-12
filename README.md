# DOGGY CAFE — Smile Doggy CAFÉ

เว็บไซต์สาธิตสำหรับ DOGGY CAFE (โปรเจค Front-end แบบ Static)
ออกแบบเพื่อเป็นหน้า Landing Page สำหรับคาเฟ่ที่รองรับน้องหมา มีเมนู รูปภาพ กิจกรรม และตะกร้าสินค้าแบบ Off-canvas

---

## ✨ ภาพรวมโปรเจค
- ชื่อโปรเจค: DOGGY-WEBSITE (Smile Doggy CAFÉ)
- ประเภท: Static website (HTML / CSS / JS)
- จุดประสงค์: โชว์หน้าเว็บหลักของคาเฟ่สุนัข พร้อมเมนู รายการข่าว และตะกร้าสินค้าแบบ sidebar

---

## คุณสมบัติเด่น
- หน้า Landing page สวยงาม พร้อม Hero section
- เมนูอาหาร/เครื่องดื่ม ตัวอย่างรายการยอดนิยม
- ส่วนข่าวสาร และรีวิว (carousel)
- Off-canvas sidebar เป็น CART (เปิด/ปิด ด้วย JavaScript)
- รองรับการแสดงผลบนมือถือ (responsive ด้วย CSS media queries)
- ใช้ Font จาก Google, icon fonts และ plugin หลายตัว (owl-carousel, magnific-popup ฯลฯ)

---

## โครงสร้างไฟล์หลัก (ตัวอย่าง)
- index.html — หน้าแรก (Hero, เมนู, CART sidebar)
- css/ — ไฟล์สไตล์หลัก (style.css และ plugin ต่าง ๆ)
- js/ — ไฟล์สคริปต์ (main.js และ library)
- images/ — รูปภาพทั้งหมด (background, เมนู, ทีม ฯลฯ)
- (ไฟล์อื่น ๆ เช่น about.html, menu-*.html, gallery.html ตามโฟลเดอร์ในโปรเจค)

---

## การรันโปรเจค (แบบง่าย — ไม่ต้องติดตั้งเซิร์ฟเวอร์)
โดยไฟล์เป็น static HTML สามารถเปิดในเบราว์เซอร์โดยตรง:
1. เปิดไฟล์ `c:\Users\few71\PycharmProjects\DOGGY-WEBSITE\index.html` ด้วยเบราว์เซอร์
หรือ รันเซิร์ฟเวอร์แบบชั่วคราวในโฟลเดอร์โปรเจค:
- ถ้าติดตั้ง Python:
  - Python 3: เปิด terminal ที่โฟลเดอร์โปรเจค แล้วรัน:
    ```
    python -m http.server 8000
    ```
  - เปิดเบราว์เซอร์ที่: http://localhost:8000
- หากใช้ VSCode ให้ติดตั้ง Live Server แล้วคลิก "Go Live"

---

## การแก้ไขและพัฒนา
- UI & Styles: แก้ไฟล์ในโฟลเดอร์ `css/` (เช่น `style.css`)
- Behavior (JS): แก้ใน `js/main.js` และไฟล์สคริปต์อื่น ๆ
- รูปภาพ: วางที่โฟลเดอร์ `images/` แล้วอ้างอิงใน HTML
- หากเพิ่มหน้าหรือเมนู ให้สร้างไฟล์ .html ใหม่และอัพเดตรายการใน navbar

---

## เพิ่มสิ่งที่ควรทำถัดไป (Recommendations)
- เปลี่ยนตะกร้า (cart) ให้เก็บรายการแบบไดนามิกด้วย LocalStorage/JS
- เชื่อมกับ backend (API) เพื่อเก็บคำสั่งซื้อจริง (เช่น Node/Express, Firebase)
- ปรับปรุงการเข้าถึง (accessibility) เพิ่ม alt attributes, ARIA roles
- เพิ่ม unit tests / E2E tests หากต้องการทำ production

---

## วิธีมีส่วนร่วม (Contributing)
1. Fork โปรเจค
2. สร้าง branch ใหม่ (feature/xxx)
3. ทำการแก้ไขและทดสอบ
4. เปิด Pull Request พร้อมคำอธิบายการเปลี่ยนแปลง

---

## ใบอนุญาต (License)
- ใส่ใบอนุญาตที่ต้องการ เช่น MIT, Apache หรือ ระบุ "สำหรับการศึกษา/สาธิต" ถ้าไม่มีข้อกำหนดพิเศษ

---

## ติดต่อ
- ผู้พัฒนา: ทีม DOGGY CAFE
- อีเมลตัวอย่าง: kmutnb@email.kmutnb.ac.th

---

ขอบคุณที่ใช้โปรเจคนี้! 🐶☕