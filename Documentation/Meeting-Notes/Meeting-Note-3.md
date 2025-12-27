# Meeting Note 3

## 1. General Updates
- **Project Name Change**: เปลี่ยนชื่อโครงการจาก "C-REWARDS" เป็น **"The Trophy"**

## 2. Implementation Strategy
- **1.3 Implementation Approach**:
    - **Customer's Proposed Phase**:
        1. MVP
        2. Automation / Scaling
        3. Ecosystem Expansion
    - **Our Approach (Mapping)**:
        - เพิ่มช่วง **POC (Proof of Concept)** ก่อนเริ่ม MVP เพื่อทดสอบความเป็นไปได้
        - รวม "Automation / Scaling" และ "Ecosystem Expansion" ของลูกค้า เข้าไว้ใน Phase **"Full-Scale Ecosystem"** ของเรา
    - **Rationale & Action**:
        - อธิบายให้ลูกค้าเข้าใจถึงความจำเป็นของ POC
        - ชี้แจงการ Mapping Phase เพื่อแสดงให้เห็นว่าเราเข้าใจ Requirement ของเขา (We read their docs) และเพื่อลดงานแก้เอกสารทั้งหมดโดยไม่จำเป็น

## 3. Technical & Functional Requirements
- **Wallet Definition ("Trophy Wallet")**:
    - นิยามการทำงานของ **"Awards Point"** ให้ชัดเจนว่าทำหน้าที่เป็น Wallet ตามนิยาม "Trophy Wallet" ที่ลูกค้าต้องการได้อย่างไร (Action: หาจุดเชื่อมโยงและอธิบายเพิ่มในเอกสาร)
- **Point Transfer Feature**:
    - **Requirement**: เพิ่มฟีเจอร์โอนคะแนนเพื่อเชื่อมต่อ ecosystem
    - **Scope**: รองรับทั้ง Inbound และ Outbound (รับเข้า/โอนออก) กับ Partner ต่างๆ (Loyalty Programs, Credit Cards)
- **QR System**:
    - **Recommend**: ใช้ระบบ **Hybrid QR Earn & Redeem** เพื่อความรวดเร็วในการใช้งาน
    - **Reference**: รายละเอียดศึกษาได้จาก Analysis ที่ทำไว้ใน `Deliverables/Research/QR-Code-Flow-Comparison-Analysis.md`

## 4. Issues & Proposals (Points to Discuss/Argue)
- **Verification Method (AI vs Staff)**:
    - **Customer Request**: ใช้ AI ตรวจจับวัตถุจากภาพถ่ายตามสถานที่
    - **Our Proposal**: ใช้ **Staff ของ Partner** หน้างานในการตรวจสอบร่วมด้วย
    - **Argument**:
        - Cost-efficiency: ประหยัดงบประมาณการพัฒนาและ Maintenance AI
        - Engagement: สร้างปฏิสัมพันธ์ (Human Touch) ระหว่าง Partner กับ End User ได้ดีกว่า
- **Authentication (Login Method)**:
    - **Customer Request**: เบอร์มือถือ หรือ Social Login
    - **Our Proposal**: **เบอร์มือถือ (Mobile Number)** อย่างเดียว
    - **Argument**:
        - Security & Standard: ความปลอดภัยและความเป็นระเบียบของข้อมูลสมาชิก
    - **Mitigation**: เพิ่มระบบ **"เปลี่ยนเบอร์มือถือ (Change Mobile Number)"** เพื่อลดความกังวลกรณีลูกค้าเปลี่ยนเบอร์

## 5. Rejected/Concerned Features
- **Send Points to Friends**:
    - **Status**: **Concern**
    - **Reason**: อาจส่งผลกระทบต่อเสถียรภาพของ **Point Economy** (การหมุนเวียนและมูลค่าของแต้ม)
- **In-App Marketplace (Buy items for Quests)**:
    - **Status**: **Disagree**
    - **Reason**: การซื้อไอเท็มช่วยเล่น (e.g., ซื้อเพื่อให้ทำ Quest ง่ายขึ้น) จะทำให้เกิดระบบ **Pay-to-Win** ซึ่งอาจลดความน่าสนใจของ Campaign
-- Log -- 
สรุปการแก้ไขตาม Meeting Note 3:

✅ เปลี่ยนชื่อ: C-REWARDS → The Trophy ทั้งเอกสาร
✅ Phase Mapping: เพิ่ม section อธิบายการ map phase ของลูกค้า (MVP → Automation/Scaling → Ecosystem) กับ phase ของเรา พร้อมเหตุผลที่แนะนำ POC
✅ Trophy Wallet: เพิ่มคำอธิบาย Awards Points ว่าทำงานเป็น Wallet พร้อมระบบ Point Transfer (Inbound/Outbound)
✅ QR System: แนะนำ Hybrid QR Earn & Redeem พร้อมอ้างอิง analysis ที่มีอยู่
✅ Authentication: อธิบายว่าใช้เบอร์มือถืออย่างเดียว พร้อมเหตุผลและเพิ่มฟีเจอร์ "Change Mobile Number"
✅ Photo Verification: แนะนำใช้ Partner Staff แทน AI พร้อมเหตุผล (cost, human touch)
✅ Concerns: เพิ่ม Note: (ตัวเอียง) สำหรับ:
Send Points to Friends (กังวลเรื่อง point economy)
In-App Marketplace (ไม่เห็นด้วยเพราะเป็น Pay-to-Win)
Point Transfer (เตือนเรื่อง economic controls)
POC necessity (แนะนำทำก่อน MVP)
เนื้อหาส่วนใหญ่ยังคงเดิม แก้เฉพาะจุดที่มีคอมเม้นต์ครับ พร้อมส่งลูกค้าได้เลย!

เข้าใจครับ! ไฟล์ Deliverables/Proposal-V2.md พร้อมส่งลูกค้าแล้ว ✅

สิ่งที่ทำเสร็จ:

✅ เปลี่ยนชื่อโครงการเป็น "The Trophy"
✅ เพิ่ม Phase Mapping อธิบายความสัมพันธ์ระหหว่าง phase ลูกค้ากับของเรา
✅ เพิ่ม Trophy Wallet และ Point Transfer (Inbound/Outbound)
✅ แนะนำ Hybrid QR System
✅ อธิบาย Mobile Number Authentication + Change Number feature
✅ แนะนำ Staff Verification แทน AI
✅ ใส่ Note: สำหรับ concerns ทั้งหมด