# 🏢 ระบบจัดการห้องพักรายเดือน (Monthly Room Management System)

ระบบสำหรับบริหารจัดการหอพักและอพาร์ตเมนต์แบบครบวงจร ครอบคลุมตั้งแต่การจัดการข้อมูลห้องพัก การทำสัญญาเช่า การจดมิเตอร์น้ำ-ไฟ และการออกใบแจ้งหนี้ประจำเดือน

---

## 👥 2.1 ทีมงานและบทบาทหน้าที่ (Team Members & Roles)
1. **[ชื่อ-นามสกุล 1]** (รหัสนักศึกษา: [...]) 
   - **Role:** Project Manager & QA
   - **หน้าที่:** จัดการ Trello, ควบคุม GitHub Branch, ตรวจสอบ Test Case และเขียนเอกสาร README
2. **[ชื่อ-นามสกุล 2]** (รหัสนักศึกษา: [...])
   - **Role:** System Analyst & Backend Developer
   - **หน้าที่:** ออกแบบ ER Diagram, พัฒนาระบบ API สำหรับ [ระบุส่วนที่ทำ เช่น ระบบ Login, จัดการห้องพัก]
3. **[ชื่อ-นามสกุล 3]** (รหัสนักศึกษา: [...])
   - **Role:** Backend Developer
   - **หน้าที่:** พัฒนาระบบ API สำหรับ [ระบุส่วนที่ทำ เช่น ระบบคำนวณบิลค่าน้ำ-ไฟ, แดชบอร์ด]
4. **[ชื่อ-นามสกุล 4]** (รหัสนักศึกษา: [...])
   - **Role:** UX/UI Designer & Frontend Developer
   - **หน้าที่:** ออกแบบ Figma และเขียนโค้ดหน้าจอ [ระบุหน้า เช่น Login, หน้าแดชบอร์ด, หน้ารายการห้องพัก]
5. **[ชื่อ-นามสกุล 5]** (รหัสนักศึกษา: [...])
   - **Role:** Frontend Developer
   - **หน้าที่:** เขียนโค้ดหน้าจอ [ระบุหน้า เช่น หน้าทำสัญญาเช่า, หน้าจดมิเตอร์, หน้าใบแจ้งหนี้]

---

## 📑 2.2 เอกสารความต้องการของระบบ (SRS)
- **SRS ทั้งหมดของระบบ:** [ใส่ลิงก์ Google Drive หรือแนบไฟล์ PDF ของ SRS 1.2]
- **ขอบเขตที่พัฒนาในโปรเจกต์นี้:**
  - พัฒนาระบบจัดการผู้ใช้งาน (Login/Logout)
  - พัฒนาระบบ CRUD ห้องพักและผู้เช่า
  - พัฒนาระบบทำสัญญาเช่าและย้ายออก
  - พัฒนาระบบจดมิเตอร์และคำนวณใบแจ้งหนี้ (Billing)

---

## 🎨 2.3 ผลงานการออกแบบ (System Design)

### 1. System Architecture
[แทรกรูปภาพ System Architecture (เช่น โครงสร้าง Client-Server / MVC)]

### 2. Use Case Diagram
[แทรกรูปภาพ Use Case Diagram]
- **Actors:** Admin (ผู้ดูแลระบบ), Tenant (ผู้เช่า)

### 3. Activity Diagram
[แทรกรูปภาพ Activity Diagram เช่น โฟลว์การออกบิล หรือ โฟลว์การทำสัญญาเช่า]

### 4. ER Diagram
[แทรกรูปภาพ ER Diagram ที่เพื่อนวาดจาก Data Dictionary]

### 5. User Flow
[แทรกรูปภาพ หรือ ลิงก์ไปยัง User Flow]

### 6. UX/UI Design
- **Figma Design:** [ใส่ลิงก์ Figma]
- [แทรกภาพ Screenshot หน้าจอหลักๆ ของระบบ 2-3 ภาพ]

### 7. API End-Points
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| `POST` | `/api/auth/login` | เข้าสู่ระบบและรับ Token |
| `GET` | `/api/rooms` | ดึงข้อมูลรายการห้องพักทั้งหมด |
| `POST` | `/api/billing/calculate` | คำนวณบิลค่าน้ำ-ไฟประจำเดือน |
*(ดู API ทั้งหมดได้ในไฟล์ API_Documentation.pdf)*

---

## 🛠️ 2.4 Tech Stack & Tools

- **Frontend:** HTML5, CSS3, Bootstrap 5 / TailwindCSS, JavaScript
- **Backend:** Python (Django Framework)
- **Database:** SQLite / PostgreSQL
- **Design:** Figma, Draw.io (สำหรับ Diagrams)
- **Project Management:** Trello, GitHub, Git

---

## 🧪 2.5 Test Case และผลการทดสอบ (Testing)
- **Test Cases:** [ใส่ลิงก์ Google Sheets ตาราง Test Case ทั้ง 23 ข้อที่เราทำไว้]
- **API Testing:** ทำการทดสอบ API ด้วย Postman [แนบลิงก์รูปภาพผลการยิง Postman ถ้ามี]
- **ผลการทดสอบเบื้องต้น:** ฟังก์ชันหลัก (Critical & High Priority) จำนวน 12 ข้อ ผ่านการทดสอบ (Pass) 100% 

---

## 🚀 2.6 การ Deploy (Deployment)
- **Live URL (Frontend/System):** [ใส่ลิงก์เว็บไซต์ที่ออนไลน์จริง ถ้าเอาขึ้น Vercel หรือ PythonAnywhere]
- **API Base URL:** [ใส่ลิงก์เซิร์ฟเวอร์หลังบ้าน]
