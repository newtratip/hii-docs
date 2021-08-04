# กระบวนการขอซื้อขอจ้าง (Purchase Request)

**เอกสารนี้สำหรับ ::** หัวหน้าเจ้าหน้าที่พัสดุ (Procurement Head)

## ตรวจสอบเอกสาร

**Menu ::** Purchase > Orders > Purchase Requests

1. ค้นหารายการ Purchase Request เพื่อทำการตรวจสอบ
      1. ลบตัวกรองเดิม (My requests)
      2. กรองหา Custom Filter ด้วย Substate = To Verify
      3. ระบบจะแสดงรายการที่รอการตรวจสอบ

    ![](img/1_pr_to_verify.png)

2. อนุมัติการตรวจสอบเอกสาร (Verify)
      1. เลือก Purchase Request ที่ต้องการอนุมัติ
      2. ถ้าเรียบร้อย กดปุ่ม Verify สถานะ Substate เปลี่ยนเป็น Verified (อนุมัติแล้ว)

    ![](img/1_pr_verify_document.png)

    !!! Note
        - ถ้าไม่เรียบร้อย กดปุ่ม Reject เพื่อปฏิเสธคำขอ

3. หลังจาก Verify ระบบ จะ Request Validation ให้อัตโนมัติ เพื่อขออนุมัติงบประมาณ

    ขั้นตอนนี้จะส่งเอกสารไปยังผู้ที่เกี่ยวข้องกับการอนุมัติวงเงินตามอำนาจหน้าที่ ซึ่งบุคคลที่เกี่ยวข้องตามตารางอนุมัติจะทำหน้าการอนุมัติ (หรือปฏิเสธ) หากเอกสารได้รับการอนุมัติจากคนสุดท้ายแล้ว สถานะของเอกสารจะเปลี่ยน State = Approved

End.

---------------------------------------------

## มอบหมายงานให้เจ้าหน้าที่พัสดุ

**Menu ::** Purchase > Orders > Purchase Requests

1. ค้นหารายการ Purchase Request ที่ยังไม่มีเจ้าหน้าที่รับผิดชอบ
      1. ลบตัวกรองเดิม (My requests)
      2. เลือกตัวกรอง To Assign Representative
      3. ระบบจะแสดงรายการที่ยังไม่มีผู้รับผิดชอบ

    ![](img/1_pr_to_assign.png)

2. เลือกรายการที่ต้องการเพื่อทำการมอบหมายงาน
      1. กดปุ่ม Edit
      2. เลือก Purchase Responsible และกด Save

    ![](img/1_pr_assign_to_pr_manager.png)

End.