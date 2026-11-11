# Aun_QA

เครื่องมือและสื่อบรรยายด้าน OBE และ AUN-QA ของ อ.ดร.วราวุฒิ นาคบุญนำ เผยแพร่ด้วย GitHub Pages

| ไฟล์ | เนื้อหา |
|---|---|
| `index.html` | หน้าแรก |
| `OBE-Alignment-Tool.html` | เครื่องมือตรวจความสอดคล้อง PLO, CLO การสอน และการวัดผล |
| `bizinno.html` + `bizinno_data.json` + `bizinno_courses_2-2569.json` + `bizinno_programs.json` + `bizinno_students_2-2569.json` + `bizinno_status_2-2569.json` + `bizinno_mko7.json` + `bizinno_staff.json` | หน้าเดี่ยวสำหรับผู้ประเมิน AUN-QA หลักสูตร BizInno (บธ.ม./ปร.ด.) แท็บตามเกณฑ์ 1–8 ไม่มีลิงก์ไปหน้าอื่น · ข้อมูลนิสิตเป็นตัวเลขรวมเท่านั้น (นับจากทะเบียนในเครื่อง ไฟล์ดิบไม่อยู่ใน repo) ตัวเลขสรุปเท่านั้น · ภาพรวมหลักสูตรสร้างจาก มคอ.2 ด้วย QA vault `50_Tools/mko2_to_web.py` (ตัดเลขประจำตัวประชาชน) · ข้อมูลรายวิชาสร้างจาก มคอ.3 ด้วย `50_Tools/mko3_to_web.py` (ไม่ระบุชื่อผู้สอน) · ร่างตัวชี้วัดอยู่ใน QA vault `30_Projects/AUN-QA/ร่างตัวชี้วัด_Dashboard_เกณฑ์8_BizInno_2569.md` |
| `OBE-Lecture-Interactive.html` | สไลด์บรรยาย OBE จาก Graduate Profile สู่ PLO และ CLO |

ย้ายมาจาก repository `academic-web-teaching` เมื่อ 10 พ.ย. 2569 (ฉบับเดียวกับที่เคยเผยแพร่)

repository นี้เป็นสาธารณะ ห้ามใส่ SAR ของหลักสูตรหรือคณะ เอกสารประเมิน เอกสารอบรม หรือข้อมูลส่วนบุคคล ไฟล์ต้นฉบับงาน QA อยู่ที่ `/Volumes/ResearchLab/AunQa_EdPEx` (ไม่เผยแพร่)

อัปเดตข้อมูลหน้า bizinno ทุกภาค: ดับเบิลคลิก `อัปเดตหน้าAUN.command` ใน QA vault (`/Volumes/ResearchLab/AunQa_EdPEx/ObsidianVault_QA`) แล้ว push · ข้อมูลแต่ละภาคเก็บแยกไฟล์ตามภาค
