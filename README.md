# SDS by Google Appsheet
สร้างระบบ Application ผ่าน Google Appsheet สำหรับใช้ในการรับออร์เดอร์ คำนวณค่าใช้จ่ายตามส่วนลดจากร้านค้า และเก็บข้อมูลเข้าสู่ระบบ

## 📄 โครงสร้างระบบ
- Google Appsheet
- Google Sheet
- Looker Studio Overview

---

# 📦 Feature ทั้งหมด

---
🏰 AUTH PAGE
### 🔸 Login
- เข้าสู่ระบบด้วย Username และ Password
- รอบรับการตรวจสอบสิทธิ์ ADMIN กับ USER

---

🏰 SALE PAGE
- ระบบบันทึกข้อมูลผ่าน Google Appsheet 
### 🔸 Homepage
- แสดงรายการออร์เดอร์ที่จดบันทึกทั้งหมด
- รองรับการสั่งออร์เดอร์

### 🔸 Order
- รองรับการเลือกบริษัท เช่น SMOOTH E, KISS OF BEAUTY
- รองรับการเลือกร้านค้าที่ต้องการสั่งออร์เดอร์
- รองรับการเพิ่มสินค้า
- รองรับการคำนวณตามส่วนลด ตามร้านค้า เช่น ร้านที่ 1 มีส่วนลด 25% + 3% + 0% และร้านที่ 2 มีส่วนลด 25% + 0% + 0%
- รองรับการอัพโหลดรูปภาพ call card

### 🔸 Order Detail
- แสดงรายละเอียดออร์เดอร์ เช่น บริษัทที่สั่งซื้อ, ร้านค้า, รายการสินค้า
- รองรับการเพิ่ม และแก้ไขรายการสินค้าในออร์เดอร์
- รองรับการยืนยันการชำระเงิน

---

🏰 ADMIN PAGE
- ระบบเก็บข้อมูลบน Google Sheet
### 🔸 User Management Page
- จัดการข้อมูลสมาชิก
### 🔸 Customer Management Page
- จัดการข้อมูลร้านค้าที่ต้องการสั่งซื้อสินค้า
### 🔸 Order Management Page
- จัดการออร์เดอร์ที่สั่งเข้ามา
### 🔸 Order Details Management Page
- จัดการรายการสินค้าของแต่ละออร์เดอร์
### 🔸 Products Management Page
- จัดการรายการสินค้าของแต่ละแบรนด์
### 🔸 Products Rate Management Page
- จัดการเรทราคา ตามจำนวนสินค้าที่สั่งซื้อ

---

🏰 Reports
- ระบบออก Report ผ่าน Looker Studio Overview โดยใช้ข้อมูล Google Sheet
- รองรับการออกใบคำสั่งซื้อของร้านค้า

---

## 🖼️ UI Preview

### 🔸 Login Page
### 🔸 Homepage
### 🔸 Order Page
### 🔸 Order Detail Page
### 🔸 Payment Page
### 🔸 User Management Page
### 🔸 Order Management Page
### 🔸 User Management Page
### 🔸 Report By Looker Studio Overview
