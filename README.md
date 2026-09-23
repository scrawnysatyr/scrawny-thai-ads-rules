# 🛡️ Thai Ads Blocker Filterlist (ตัวกรองบล็อกโฆษณาไทย)

> **Thai Adblock Filterlist** — รายการกฎสำหรับบล็อกโฆษณาไทย แบนเนอร์เว็บพนัน ป้ายลอยติดขอบจอ (Sticky Banner) และลิงก์ย่อครอบลิงก์ (Shortlinks/Redirects) บนเว็บอ่านการ์ตูน มังงะ ดูอนิเมะ และเว็บดูหนัง รองรับ **uBlock Origin**, **AdGuard**, และ **Brave Shields** อัปเดตอัตโนมัติ

![Adblock](https://img.shields.io/badge/Adblock-uBlock%20%7C%20AdGuard%20%7C%20Brave-green?style=flat-square)
![Updated](https://img.shields.io/badge/Update-Every%2012%20Hours-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-orange?style=flat-square)

---

## 🌐 ลิงก์ Raw Filterlist (นำลิงก์นี้ไปใส่ในโปรแกรม)

คัดลอกลิงก์ด้านล่างนี้ไปใส่ใน Adblocker ของคุณ:

```text
https://raw.githubusercontent.com/scrawnysatyr/scrawny-thai-ads-rules/main/adblock_filterlist.txt
```

---

## 📖 วิธีติดตั้งและใช้งานใน Adblocker ยอดนิยม

### 1. 🟥 uBlock Origin (แนะนำที่สุด ⭐)
1. คลิกที่ไอคอน **uBlock Origin** ในเบราว์เซอร์ -> คลิกไอคอนรูป **ฟันเฟือง (Open the dashboard)**
2. ไปที่แถบ **"Filter lists" (รายการตัวกรอง)** ด้านบน
3. เลื่อนลงมาล่างสุดที่หัวข้อ **"Custom" (กำหนดเอง)**
4. ติ๊กถูกที่ช่อง **"Import..." (นำเข้า...)**
5. วางลิงก์ Raw ลงในช่องข้อความ:
   ```text
   https://raw.githubusercontent.com/scrawnysatyr/scrawny-thai-ads-rules/main/adblock_filterlist.txt
   ```
6. กดปุ่มสีส้ม **"Apply changes" (นำการเปลี่ยนแปลงไปใช้)** ด้านบน

---

### 2. 🟩 AdGuard (Extension, Windows & Android App)
1. เปิด **AdGuard Settings** (การตั้งค่า)
2. ไปที่เมนู **"Filters" (ตัวกรอง)** ด้านซ้าย
3. เลือก **"Custom" (กำหนดเอง)** -> คลิกปุ่ม **"Add custom filter" (เพิ่มตัวกรองที่กำหนดเอง)**
4. ในช่อง URL ให้วางลิงก์:
   ```text
   https://raw.githubusercontent.com/scrawnysatyr/scrawny-thai-ads-rules/main/adblock_filterlist.txt
   ```
5. ตั้งชื่อ เช่น `Thai Ads Blocker` แล้วกด **Next / Add**

---

### 3. 🦁 Brave Browser (Brave Shields)
1. พิมพ์ที่แถบ URL ของเบราว์เซอร์: `brave://settings/shields/filters` แล้วกด Enter
2. เลื่อนลงมาล่างสุดที่หัวข้อ **"Add custom filter lists" (เพิ่มรายการตัวกรองที่กำหนดเอง)**
3. วางลิงก์ Raw:
   ```text
   https://raw.githubusercontent.com/scrawnysatyr/scrawny-thai-ads-rules/main/adblock_filterlist.txt
   ```
4. กดปุ่ม **"Add" (เพิ่ม)**

---

### 4. 🔴 Adblock Plus (ABP)
1. เปิดการตั้งค่า **Adblock Plus Settings**
2. ไปที่แถบ **"Advanced" (ขั้นสูง)**
3. เลื่อนลงมาที่หัวข้อ **"Filter lists"** -> คลิก **"Add a new filter list"**
4. วางลิงก์ Raw แล้วกด **"Add a filter list"**

---

## 💬 ขอเพิ่มเว็บไซต์ / รายงานโฆษณาที่ยังไม่ถูกบล็อก (Request & Feedback)

หากคุณพบเว็บไซต์การ์ตูน/มังงะ/สตรีมมิ่งที่ยังมีโฆษณา หรือต้องการขอให้เพิ่มเว็บไซต์ใหม่เข้ามาในระบบ สามารถแจ้งได้ง่ายๆ ผ่าน **GitHub Issues**:

👉 **[คลิกที่นี่เพื่อเปิด Issue แจ้งขอเพิ่มเว็บ / รายงานโฆษณา](https://github.com/scrawnysatyr/scrawny-thai-ads-rules/issues/new)**

### ข้อมูลที่แนะนำในการแจ้ง:
- **ลิงก์หน้าเว็บ (URL)** ที่พบโฆษณา
- **ประเภทของโฆษณา** เช่น แบนเนอร์เว็บพนัน, ป้ายลอยติดขอบจอด้านล่าง, หรือคลิกแล้วเด้งไปเว็บอื่น
