# กระบวนการขอซื้อขอจ้าง (Purchase Request)

**เอกสารนี้สำหรับ ::** ผู้ขอจัดซื้อจัดจ้าง (Employee)

## การสร้างใบขอซื้อจ้าง (Purchase Request:PR)

**Menu ::** Purchase Requests > Purchase Requests > Purchase Requests
      
![](img/1_pr_new.png)
    
1. กดปุ่ม Create เพื่อสร้าง Purchase Request ที่ Header เลือก/กรอกข้อมูลดังนี้
    1. Procurement Type: ประเภทของการซื้อ
        * ซื้อ/จ้าง/เช่า
        * จ้างที่ปรึกษา
        * จ้างก่อสร้าง
    2. Purchase Type: ระเบียบการ
        * จัดซื้อจัดจ้างผ่านพัสดุ
        * วงเงินเล็กน้อย
    3. Procurement Method: วิธีการจัดซื้อจัดจ้าง
        * เฉพาะเจาะจง
        * คัดเลือก
        * ประกาศเชิญชวนทั่วไป e-bidding
        * ประกาศเชิญชวนทั่วไป e-market
    4. Description: รายละเอียดของการจัดซื้อ
    5. Procurement Time: ระยะเวลาการดำเนินการ
    6. Total Cost: วงเงินรวม
    7. Creation Date: วันที่สร้างเอกสาร
    8. Created By: ผู้สร้างเอกสาร
    9. Requested By: ผู้ขอ (อาจไม่ใช่ผู้สร้างเอกสาร กรณีทำแทน)
    10. Purchase Representative: เจ้าพนักงานจัดซื้อจัดจ้างที่ได้รับมอบหมาย
    11. Verified By: ผู้ตรวจสอบเอกสาร (หัวหน้าเจ้าพนักงานจัดซื้อจัดจ้าง)
    12. Verified Date: วันที่ตรวจสอบเอกสาร
    13. Approved By: ผู้อนุมัติวงเงิน (คนสุดท้ายในลำดับการอนุมัติ)
    14. Approved Date: วันที่อนุมัติวงเงิน

2. แท็บ Product เพิ่มรายการที่ต้องการขอซื้อขอจ้าง โดยมีข้อมูลดังนี้
    1. Activity: เนื้องานที่ต้องการขอซื้อจ้าง
    2. Description: รายละเอียดเพิ่มเติมการขอซื้อจ้าง
    3. Quantity: จำนวนที่ต้องการ
    4. Analytic Account: ชื่อโครงการหรือชื่อหน่วยงานที่ต้องการใช้งบประมาณ
    5. Fund: ชื่อแหล่งทุนของโครงการหรือหน่วยงานที่ใช้งบประมาณ
    6. Analytic Tags: ข้อมูลกลุ่มงบประมาณ, แผนงาน, ประเภทงบประมาณ
    7. Requested Date: วันที่ต้องการ
    8. Estimated Cost: งบประมาณ

    ![](img/1_pr_product_line.png)

    <br/>

3. แท็บ Committee รายชื่อคณะกรรมการ เงื่อนไขเป็นไปตามจำนวนเงินรวม และข้อมูลการจัดซื้อจัดจ้างต่างๆ Procurement Type, Purchase type และ Procurement method ให้เพิ่มรายชื่อคณะกรรมการการจัดซื้อจัดจ้างและคณะกรรมการการตรวจรับ (Committee) ตาม พ.ร.บ. โดยมีข้อกำหนดดังต่อไปนี้

    ![](img/1_pr_committee.png)


    !!! Note
        - หากจำนวนคณะกรรมการไม่สอดคล้องกับเกณฑ์ พ.ร.บ. ระบบจะออกคำเตือนเมื่อกดปุ่ม Request Approval ดังตัวอย่างเช่น

        ![](img/1_pr_exception.png)

4. หากมีข้อมูลแนบเพื่อการพิจารณาสามารถเพิ่มได้ที่ รูปคลิป ด้านล่างของเอกสาร

    ![](img/1_pr_more_info.png)
    
    <br/>

5. กดปุ่ม Print - Purchase Request เพื่อตรวจสอบความถูกต้อง

    ![](img/1_pr_printout.png)

    <br/>

6. กดปุ่ม Request Approval เพื่อส่งเอกสาร Purchase Request นี้ไปยังฝ่ายพัสดุเพื่อตรวจทานและส่งอนุมัติการจัดซื้อจัดจ้างและการเบิกใช้งบประมาณต่อไป
      - Substate = To Verify
      - State = To be approved

    ![](img/1_pr_header.png)

End.
