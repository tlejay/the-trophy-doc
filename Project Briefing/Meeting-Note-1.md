# Feedback 25-Dec 2025, 19:30 

# C-REWARDS: Gamified Loyalty & Engagement Ecosystem
## Professional Project Proposal
ให้ตัดคำว่า Professional ออกไป 

## Executive Summary (บทสรุปผู้บริหาร)
หัวข้อไม่ต้องมีวงเล็บภาษาไทย 

### The Opportunity
เวลาใช้รูปประโยค "This is not..., it is a... " มันดูเป็น AI Generated เกินไปหน่อย ฝากปรับให้ด้วย 

## 2. Solution Architecture & Technical Design
ยืนยันแล้วว่าใช้ Lalavel (ตัด Node.js ทิ้งไป)
ฐานข้อมูลจะใช้ Postgresql + Mongo (ผสมกัน) 
และจะใช้ GCP (ไม่ใช่ AWS)

### 3.3 Phase 3: Full-Scale Ecosystem
ตัด In-app chat and community features และ Augmented reality (AR) missions (experimental) ทิ้ง

### 5.1 Fraud Prevention Strategy
- **Photo Verification:** Human review + AI image analysis for mission photos
ตัด AI image analysis ทิ้งเลยเดี๋ยวจะส่งมอบไม่ได้

# ข้อกำหนดเพิ่มเติม 
- Exclusions ของ POC Phase เพิ่มให้ชัดเจนไปด้วยว่ามันไม่รวมการ Publish ขึ้น APP Store/Play Store 
- Success Criteria ของ MVP และ Full มี Dependencies คือมันต้องล้อไปกับงบประมาณและแผนการตลาด (DOS ไม่ได้ทำ Marketing และจะออกแบบระบบให้รองรับการทำ Digital Marketing)
- เพิ่มฟีเจอร์ Pay with Point ใน Full-Scale Ecosystem ไปด้วย หลักการคือให้ Partner ออกส่วนลดแบบ Real-time และ Redeem แบบ Realtime (ไม่ได้ส่วนลดที่ตั้งไว้ล่วงหน้า แต่จการใช้ฟีเจอร์นี้มันร่วมทุกสินค้าและบริการของ Partner) 
- สิ่งที่ Feedback ไปนั้นอาจจะเกี่ยวกับส่วนอื่นๆในเอกสารด้วย ก่อนแก้ไข จะต้องรีวิวทั้งเอกสารว่ามีจัดไหนบ้างที่สัมพันธ์กัน 
- อับเดท Document Control ด้วย 
v1.1 Review by Jakapong(TLE)  
v1.2 Update from Feedback by DOS Team (ถ้าคุณแก้ไขเสร็จเรียบร้อยแล้ว)
- โปรเจคนี้จะไม่ใช้ Firebase เลย, Realtime Database = Pusher, Push Notification = Onesignal
- ตัดเรื่อง Offline-capable ทิ้งไปเลยเพราะเรื่องนี้ทำยากมาก 