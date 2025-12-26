# C-REWARDS: Strategic Loyalty & Engagement Ecosystem Proposal
**Prepared by:** Digitalmedia Outsource Solution Co.,Ltd. (DOS)
**Date:** December 25, 2025

---

## 1. Executive Summary (บทสรุปผู้บริหาร)
**C-REWARDS** ไม่ใช่เพียงแอปพลิเคชันสะสมแต้ม แต่คือ **"Gamified Experience Platform"** ที่เชื่อมโยงความสัมพันธ์ระหว่างสโมสรฟุตบอล (Client), พันธมิตรทางธุรกิจ (Partners), และแฟนคลับ (Users) ผ่านกลไก Mission-based Engagement

เป้าหมายสำคัญคือการสร้าง Ecosystem ที่ยั่งยืน โดยเปลี่ยนกิจกรรมของแฟนคลับให้เป็นมูลค่า (Value) ผ่านเทคโนโลยีที่มีความแม่นยำสูง (Precision Location) และระบบความปลอดภัยที่รัดกุม (Fraud Protection) ภายใต้งบประมาณและการแบ่งเฟสที่ชัดเจน เพื่อบริหารความเสี่ยงและวัดผล ROI ได้จริง

---

## 2. Strategic Context & Constraints (บริบทและข้อจำกัดเชิงกลยุทธ์)

### 2.1 The "White Label" Strategy
* **Core Restriction:** ห้ามใช้ชื่อ, โลโก้, หรือสีประจำสโมสร (Chonburi FC) ภายในแพลตฟอร์มอย่างเด็ดขาด
* **Objective:** เพื่อความเป็นสากลและเปิดกว้างในการขยายฐาน User หรือ Partner ที่อาจมีความละเอียดอ่อนเรื่องความเป็นอริของสโมสรฟุตบอล แต่ยังคงสิทธิประโยชน์ในการเข้าถึง Asset ของสโมสรได้ (เช่น สนามซ้อม, ที่นั่ง VIP)

### 2.2 Value Proposition (คุณค่าที่ส่งมอบ)
* **For Users:** ประสบการณ์ Exclusive ที่เงินซื้อไม่ได้ (Money-can't-buy experiences) เช่น ดูการฝึกซ้อม, ส่วนลดที่จอดรถ
* **For Partners:** Traffic และยอดขายที่เพิ่มขึ้นจากฐานแฟนคลับ (เช่น ร้านล้างรถ) พร้อมระบบตรวจสอบ ROI
* **For Client:** Data-driven Engagement และรายได้ช่องทางใหม่จากการบริหารสิทธิประโยชน์

---

## 3. Solution Architecture (สถาปัตยกรรมระบบ)

ระบบจะพัฒนาด้วย **Flutter** เพื่อประสิทธิภาพสูงสุดแบบ Cross-Platform (iOS/Android) โดยแบ่งเป็น 3 ส่วนหลัก:

### 3.1 Customer Application (Super App for Fans)
* **Mission Center:** ศูนย์รวมภารกิจเก็บแต้ม
    * Location-based: เช็คอินสถานที่ (ใช้ KML/Polygon เพื่อความแม่นยำระดับสูง ไม่ใช่แค่ Radius)
    * Action-based: ถ่ายรูปคู่กับบุคคลที่กำหนด (Staff)
* **Reward Redemption:** แลกของรางวัล, สิทธิ์เข้าพื้นที่ VIP, คูปองส่วนลด Partner
* **Tiering System:** ระดับสมาชิกเพื่อรับสิทธิพิเศษที่แตกต่างกัน

### 3.2 Partner Application (Service & Verification)
* **Validation Tool:** เครื่องมือสำหรับ Staff หรือ Partner ในการตรวจสอบ User
* **QR Scanner:** สแกนเพื่อมอบแต้ม หรือตัดแต้ม (Redeem)
* **Mission Verifier:** ยืนยันภารกิจถ่ายรูป หรือการเข้าใช้บริการ

### 3.3 Admin Console (Central Command)
* **Dashboard:** ภาพรวม Real-time, User Active, Points Circulation
* **Mission & Polygon Manager:** เครื่องมือวาดพื้นที่ (Geofencing) และกำหนดเงื่อนไขภารกิจ
* **Fraud Detection:** ระบบตรวจจับความผิดปกติ (จะกล่าวถึงในหัวข้อ 5)

---

## 4. Implementation Roadmap & Budgeting (แผนงานและงบประมาณ)

แบ่งการพัฒนาออกเป็น 3 ระยะ เพื่อลดความเสี่ยงและเริ่มใช้งานได้จริงโดยเร็ว

| Phase | Description | Key Deliverables | Est. Budget (THB) |
| :--- | :--- | :--- | :--- |
| **Phase 1: POC** | **Proof of Concept** | ระบบต้นแบบเพื่อทดสอบความเป็นไปได้ของ Core Feature (Location Check-in, Basic Point Logic) | **1,000,000** |
| **Phase 2: MVP** | **Production Grade (Phase 1)** | ระบบใช้งานจริงฟีเจอร์หลัก (Core Missions, Partner App Basic, Security L1) รองรับ User เริ่มต้น | **3,000,000 - 5,000,000** |
| **Phase 3: Full** | **Full Scale Ecosystem** | ฟีเจอร์ครบสมบูรณ์ (Complex Missions, Advanced Fraud AI, Full Partner Integration, Polygon Tools) | **~10,000,000** |

---

## 5. Risk Management & Governance (การบริหารความเสี่ยงและธรรมาภิบาล)

### 5.1 Fraud Prevention (การป้องกันการโกง)
ระบบต้องออกแบบเพื่อปิดช่องโหว่ทั้งจาก User และ Partner:
* **Anti-Gaming Mechanics:** ป้องกันการปั๊มแต้ม (Spamming check-ins) หรือการใช้ Location ปลอม (Mock Location)
* **Partner Audit:** ตรวจสอบพฤติกรรมการแจกแต้มของ Partner (เช่น แจกแต้มเกินลิมิตต่อวัน หรือแจกให้ User เดิมซ้ำๆ ผิดปกติ)
* **User Validation:** ใช้ Staff/Partner App เป็นตัวกลางยืนยัน (Human Validation) ในภารกิจที่ซับซ้อน เช่น การถ่ายรูป

### 5.2 Economic Control (การควบคุมระบบเศรษฐศาสตร์)
* **Point Expiry:** กำหนดอายุของแต้มเพื่อกระตุ้นการใช้จ่าย (Burn rate) และลดภาระหนี้สินทางบัญชี (Point Liability)
* **Inflation Management:** ควบคุมปริมาณแต้มในระบบให้สมดุลกับของรางวัลที่มี

---

## 6. Business Ecosystem & ROI (โมเดลธุรกิจและผลตอบแทน)
* **Partner Acquisition Strategy:**
    * นำเสนอ Benefit ให้ Partner ชัดเจน (เช่น ร้านล้างรถได้ลูกค้าเพิ่มจาก User ที่มาใช้แต้มแลกส่วนลด)
    * ระบบคำนวณ ROI ให้ Partner เห็นว่าการแจกแต้ม (Cost) คุ้มค่ากับ Traffic ที่ได้รับ (Gain)
* **Operational Cost Reduction:**
    * ลดต้นทุนการจัดการสิทธิประโยชน์แบบ Manual
    * แก้ปัญหาที่จอดรถ หรือสิทธิ์ VIP ด้วยระบบ Digital Validation ที่แม่นยำ

---

**Next Steps:**
1.  ยืนยันขอบเขตงาน (Scope) ของ Phase 1 (POC)
2.  จัดทำ Workshop เพื่อออกแบบ User Journey และกำหนด Fraud Logic เบื้องต้น
3.  เริ่มดำเนินการออกแบบ Wireframe และ System Architecture