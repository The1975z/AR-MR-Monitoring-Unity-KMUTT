**AR/MR Monitoring Unity KMUTT**:

---

# AR/MR Monitoring Unity KMUTT

![AR/MR Monitoring](https://rac.thairobotics.org/wp-content/uploads/2023/10/11-1024x576.png)

## ที่มาและความสำคัญ
**AR/MR Monitoring** เป็นระบบที่นำเทคโนโลยีความจริงเสริม (AR) และความจริงผสม (MR) มาประยุกต์ใช้เพื่อการควบคุมและตรวจสอบเครื่องจักรและกระบวนการในอุตสาหกรรม โดยสามารถทำงานร่วมกับโครงสร้างพื้นฐานของโรงงานได้ เช่น การสตรีมข้อมูลแบบเรียลไทม์จากระบบต่างๆ ไม่ว่าจะเป็น **PLC**, **MES**, **ERP**, **SCADA** หรือระบบบันทึกประวัติข้อมูล รวมถึงข้อมูลจากเครื่องจักรต่างๆ ได้แบบเรียลไทม์ ทำให้การตรวจสอบและการควบคุมสามารถทำได้อย่างสะดวกและมีประสิทธิภาพมากยิ่งขึ้น

![AR/MR Monitoring](https://rac.thairobotics.org/wp-content/uploads/2023/10/10-2-1024x576.png)

## รายละเอียดโปรเจ็ค
โปรเจ็คนี้พัฒนาขึ้นโดย Talent Development ในโครงการ **Robotics, AI, and Coding (RAC)** KMUTT: มหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี (มจธ.) โดยใช้ **Unity** เป็นเครื่องมือหลักในการพัฒนาสภาพแวดล้อมเสมือนเพื่อการควบคุมและการตรวจสอบเครื่องจักรในรูปแบบ AR/MR

### การทำงานของระบบ
- **การควบคุมแขนกล**: ใช้ **DOBOT** ในการควบคุมแขนกลผ่าน **MQTT** และ **TCP** เพื่อส่งข้อมูลระหว่างอุปกรณ์ต่างๆ ในระบบ
- **การสตรีมข้อมูล**: ระบบสามารถสตรีมข้อมูลแบบเรียลไทม์จากแหล่งข้อมูลต่างๆ ทั้ง PLC, MES, ERP, SCADA และแหล่งข้อมูลเครื่องจักรอื่นๆ
- **การนำเสนอข้อมูลแบบ Overlay**: AR/MR ช่วยให้สามารถนำเสนอข้อมูลซ้อนทับกับเครื่องจักรที่กำลังใช้งาน ทำให้ผู้ควบคุมสามารถเห็นข้อมูลที่สำคัญในขณะที่ใช้งานเครื่องจักร
- **การเชื่อมต่อกับระบบ IoT**: ระบบนี้ใช้การส่งข้อมูลผ่าน IoT ซึ่งสามารถนำไปต่อยอดในการควบคุมและตรวจสอบกระบวนการผลิตในอุตสาหกรรมแบบอัตโนมัติได้

## เทคโนโลยีที่ใช้
- **Unity**: พัฒนาโปรเจ็คเพื่อการแสดงผล AR/MR และเชื่อมต่อกับอุปกรณ์ภายนอก C#
- **DOBOT**: แขนกลที่ใช้ในโปรเจ็คสำหรับการควบคุมผ่าน MQTT และ TCP
- **MQTT & TCP**: โปรโตคอลที่ใช้สำหรับการรับส่งข้อมูลแบบเรียลไทม์ระหว่างอุปกรณ์
- **AR/MR Integration**: เทคโนโลยีความจริงเสริมและความจริงผสมเพื่อการนำเสนอข้อมูลที่ซ้อนทับกับโลกจริง

## เป้าหมาย
ด้วยเทคโนโลยี AR/MR ที่สามารถช่วยให้เห็นข้อมูลสำคัญขณะควบคุมเครื่องจักร โปรเจ็คนี้จึงตั้งเป้าเพื่อเป็นต้นแบบสำหรับการใช้งาน AR/MR Monitoring ในอุตสาหกรรม เพิ่มประสิทธิภาพในการควบคุมและตรวจสอบการทำงานของเครื่องจักร และสามารถต่อยอดให้เป็นระบบควบคุมผ่าน IoT ที่สะดวกและมีประสิทธิภาพ