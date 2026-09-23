# 🛡️ Scrawny Thai Ads Filterlist

> รวมรายการกฎ Adblocker สำหรับบล็อกแบนเนอร์โฆษณา, ป้ายลอย (Sticky Banner), เว็บพนัน, และลิงก์ย่อครอบลิงก์ (Shortlink Redirects) บนเว็บอ่านการ์ตูน/มังงะและสตรีมมิ่งไทย อัปเดตอัตโนมัติทุก 12 ชั่วโมง

[![Auto Scan & Push](https://github.com/scrawnysatyr/scrawny-thai-ads-auto/actions/workflows/update_filterlist.yml/badge.svg)](https://github.com/scrawnysatyr/scrawny-thai-ads-auto/actions)
![GitHub last commit](https://img.shields.io/github/last-commit/scrawnysatyr/scrawny-thai-ads-rules?color=blue)
![Format](https://img.shields.io/badge/Format-uBlock%20%7C%20AdGuard%20%7C%20Brave-green)

---

## 🌐 ลิงก์ Raw Filterlist (สำหรับนำไป Subscribe)

คัดลอกลิงก์ด้านล่างนี้ไปใส่ในโปรแกรม Adblocker ของคุณ:

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

### 2. 🟩 AdGuard (Extension & Desktop)
1. เปิด **AdGuard Settings** (การตั้งค่า)
2. ไปที่เมนู **"Filters" (ตัวกรอง)** ด้านซ้าย
3. เลือก **"Custom" (กำหนดเอง)** -> คลิกปุ่ม **"Add custom filter" (เพิ่มตัวกรองที่กำหนดเอง)**
4. ในช่อง URL ให้วางลิงก์:
   ```text
   https://raw.githubusercontent.com/scrawnysatyr/scrawny-thai-ads-rules/main/adblock_filterlist.txt
   ```
5. ตั้งชื่อ เช่น `Scrawny Thai Ads` แล้วกด **Next / Add**

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

## ✨ จุดเด่นของ Filterlist นี้
- 📌 **Sticky First**: จัดลำดับกฎบล็อกป้ายลอย/แถบโฆษณาติดขอบจอ (Floating & Sticky Banners) ไว้บนสุดของแต่ละโดเมนเสมอ ไม่ให้บังเนื้อหา
- 🎯 **Target URL-Based Hiding**: ลบรูปภาพแบนเนอร์และกล่องโฆษณาตามปลายทางของลิงก์ ไม่ทิ้งช่องว่างหรือรูปกากบาทเสีย
- 🔗 **Shortlink & Redirect Resolution**: สแกนตรวจจับลิงก์ย่อภายนอก (`ibit.ly`, `t.ly`, `cutt.ly`, etc.) และระบบ Redirect ภายในเว็บที่ส่งต่อไปยังเว็บพนัน
- 📅 **Grouped by Domain & Date**: แยกหมวดหมู่ตามโดเมนและวันที่ตรวจพบอย่างเป็นระเบียบ
- 🤖 **Auto-Updated**: รันสแกนและอัปเดตกฎใหม่ทุก 12 ชั่วโมงผ่าน [scrawny-thai-ads-auto](https://github.com/scrawnysatyr/scrawny-thai-ads-auto)
