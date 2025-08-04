**รหัสโครงงาน:** 67-1_13_pps-r1

**ชื่อโครงงาน (ไทย):** ระบบแนะนำอัตโนมัติสำหรับการหางานโดยใช้เทคนิคการประมวลผล
 ภาษาธรรมชาติ 

**Project Title (Eng):** Recommendation System for Job Finding using Natural Language 
Processing Techniques

**อาจารย์ที่ปรึกษาโครงงาน:** ผศ.ดร.ปกป้อง ส่องเมือง

**ผู้จัดทำโครงงาน:**
1. นายภัทรพล ทองยอดแก้ว  6409682579  pattarapol.ton@dome.tu.ac.th
   
Manual / Instructions for the project starts here !
#  ติดตั้ง vscode และ Git
   1. ติดตั้ง Visual Studio Code
   2. ติดตั้ง Python 3.8+ ใน Visual Studio Code
   3. ติดตั้ง Jupyter Extension สำหรับ VS Code
   4. VS Code + Jupyter Extension for VS Code
   5. ติดตั้ง git ผ่านลิงค์ https://git-scm.com/downloads/win
#  วิธีการติดตั้งและตั้งค่าไฟล์โปรเจค (bash)
1. Clone โปรเจกต์จาก GitHub
   1. กดปุ่มสีเขียวในหน้า Github โปรเจคผมแล้วกดคัดลอกลิงค์บน Clone using web URL
   2. เปิด Visual Studio Code
   3. Ctrl+Shift+P จากนั้นพิมพ์ "Git: Clone" กด enter
   4. Ctrl+V เพื่อ paste ลิงค์ clone แล้วกด enter
   5. เลือก directory ที่จะติดตั้งโปรเจคนี้ แล้วกด enter
2. ติดตั้ง dependencies (ดูทั้งหมดใน requirements.txt)เช่น pandas, numpy, scikit-learn, sentence-transformers, tqdm, etc.
   1. เปิด terminal โดยไปที่ขีด 3 ขีดซ้ายบนของ vscode> Terminal> New Terminal
   2. จากนั้น Run "pip install -r requirements.txt"
 
# วิธีการใช้งานโปรแกรม
1. 📁 โครงสร้างไฟล์ข้อมูล
โค้ดทั้งหมดจะอยู่ในไฟล์โน้ตบุ๊กนี้: Notebooks/ ซึ่งจะประกอบไปด้วย "final_RS_Doc2Vec.ipynb", "final_RS_SBERT.ipynb", "final_RS_TF-IDF.ipynb"
ภายในโน้ตบุ๊กจะมีการโหลดข้อมูลจากไฟล์: Data/ ซึ่งจะประกอบไปด้วย "course_data.xlsx" และ "job_data.xlsx"

*โปรดตรวจสอบว่าโฟลเดอร์ data/ อยู่ในตำแหน่งที่ถูกต้องสัมพัทธ์กับไฟล์โน้ตบุ๊ก เมื่อเปิดใช้งานผ่าน VS Code*

2. ▶️ วิธีการใช้งานโปรแกรม

2.1 เปิด VS Code

2.2 เปิดโฟลเดอร์โปรเจกต์ชื่อ 2567-2-cs403-final-submission-67-1_13_pps-r1

2.3 เปิดโฟลเดอร์ Notebooks แล้วเปิดไฟล์: เช่น "final_RS_SBERT.ipynb"
   รันแต่ละเซลล์ในโน้ตบุ๊กตามลำดับ เพื่อดูผลลัพธ์:
   
   #1 โปรแกรมโหลดข้อมูลรายวิชาและตำแหน่งงานและ embed ข้อมูล
   
   #2 ระบบประมวลผลความเหมาะสมระหว่างโปรไฟล์นักศึกษากับคำอธิบายงาน
   
   #3 แนะนำรายวิชาที่ควรเรียนเพิ่มเติม เพื่อเพิ่มโอกาสในการสมัครงาน

2.4 ใน ipynb ของแต่ละโมเดลสามารถเปลี่ยนข้อมูลใน learner profile ได้

   #1 เปลี่ยน desired_job เป็นอาชีพที่ต้องการ

   #2 เปลี่ยน courses_completed ให้มีคอร์สที่เคยเรียน
   
**รูปภาพ Directory tree ของโปรแกรมงาน**

![image](https://github.com/user-attachments/assets/451d3047-07fa-4e3b-85df-bf521aa3143e)

