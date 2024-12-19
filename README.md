# LAB05

![2](https://github.com/user-attachments/assets/80fa8543-e3c9-48d4-ad71-c72dca480bd3)

ข้อ 2 
  - cd (folder name) (เข้าไปที่ directory ของ folder name)
  - cd . (directory อยู่ที่เดิม home/time)
  - cd .. (directory กลับไปที่ home)
  - cd ~ (directory กลับไปที่ home/time)
  - cd / (directory กลับไปที่เริ่มต้น /)
  - cd $ (ไม่ได้ตั้ง variable ไว้เลยไม่ขึ้น)
  - pwd (ระบุตำแหน่งของ directory)
  - mkdir (name) (สร้าง folder)

![3 1   3 2](https://github.com/user-attachments/assets/17c2d7d4-60f5-4776-a07c-e72d30b2944c)

ข้อ 3.1 & 3.2

![3 3](https://github.com/user-attachments/assets/f0a75678-a8c2-4ff9-85dc-705cf591fdaa)

ข้อ 3.3 
  -  ls (ใช้เพื่อแสดงไฟล์ทั้งหมดภายใน folder หรือการใช่คำสั่ง list)

  ls -alt:

  -  -a: แสดงไฟล์ทั้งหมด รวมถึงไฟล์ซ่อน
  -  -l: แสดงรายละเอียดไฟล์ (สิทธิ์, เจ้าของ, ขนาด, วันที่)
  -  -t: เรียงลำดับตามวันที่แก้ไขล่าสุด (ใหม่สุดอยู่บนสุด)
  -  ls แสดงรายการธรรมดา ส่วน ls -alt แสดงรายละเอียดไฟล์ทั้งหมด เรียงตามการแก้ไขล่าสุด.

![3 4](https://github.com/user-attachments/assets/e5545c17-264b-4661-be5f-20f1a5e4d98f)

ข้อ 3.4
  -  mv (เปลี่ยนชื่อไฟล์)

 ![3 5](https://github.com/user-attachments/assets/5611039e-ffcf-40ba-a703-4750c07c2fa0)

 ข้อ 3.5
 
  ls -lh
  
  -  แสดงรายการไฟล์/โฟลเดอร์ในรูปแบบอ่านง่าย
  -  ขนาดไฟล์แสดงเป็น KB, MB, GB แทนการใช้หน่วยเป็นไบต์

  du -h
  
  -  แสดงขนาดพื้นที่ดิสก์ที่ไฟล์/โฟลเดอร์ใช้จริง
  -  ใช้ดูขนาดรวมของโฟลเดอร์ทั้งหมด

![3 7 - 3 10](https://github.com/user-attachments/assets/682232e9-76ed-4a20-aab3-fda66645ae31)

ข้อ 3.7-3.10

  -  chmod 400 คือคำสั่งเปลี่ยนสิทธิ์การเข้าถึงไฟล์หรือโฟลเดอร์ในระบบ Unix/Linux โดยให้สิทธิ์เฉพาะผู้เป็นเจ้าของไฟล์ในการ อ่าน (read) ไฟล์เท่านั้น
  -  rm (remove)

![4 1](https://github.com/user-attachments/assets/4bae0d3a-87bc-4509-8203-e7eaec79416a)


![4 1_2](https://github.com/user-attachments/assets/0d721d20-db56-4346-bf3c-0d6e5980a013)


ข้อ 4.1
  -  cat (ย่อมาจาก concatenate) เป็นคำสั่งในระบบ Unix/Linux ที่ใช้สำหรับจัดการไฟล์ข้อความ เช่น การดูเนื้อหาของไฟล์ รวมไฟล์ และสร้างไฟล์ใหม่

![4 2](https://github.com/user-attachments/assets/118fb153-4dca-4369-9911-34303d8da17b)

ข้อ 4.2 
  -  head และ tail เป็นคำสั่งในระบบ Unix/Linux ที่ใช้สำหรับดูเนื้อหาบางส่วนของไฟล์ข้อความ:

  -  head ใช้แสดง บรรทัดแรกๆ ของไฟล์ (ค่าเริ่มต้นคือ 10 บรรทัดแรก)

  -  tail ใช้แสดง บรรทัดท้ายๆ ของไฟล์ (ค่าเริ่มต้นคือ 10 บรรทัดท้าย)

![4 3](https://github.com/user-attachments/assets/2d52b92e-3d42-4809-947f-d54fdb1ba5ae)

ข้อ 4.3 
  -  wc (ย่อมาจาก Word Count) เป็นคำสั่งใน Unix/Linux ที่ใช้สำหรับนับข้อมูลในไฟล์ข้อความ เช่น บรรทัด (lines), คำ (words), และอักขระ (characters/bytes)

![4 4](https://github.com/user-attachments/assets/6e0517cd-1480-46fd-958c-ac9453296f4c)

ข้อ 4.4
  -  -l คือเอาเฉพาะ line

![5 2](https://github.com/user-attachments/assets/50072fc7-7602-4ec2-9488-0917e4c6daf8)

ข้อ 5.2
  -  echo $PATH แสดงค่าของตัวแปร PATH ซึ่งเป็นรายการของไดเรกทอรีที่แยกด้วย : ที่ Shell จะค้นหาไฟล์คำสั่งหรือโปรแกรม

![5 3](https://github.com/user-attachments/assets/d084c078-f01d-46e9-ad51-0b5b90e4fcb2)

ข่อ 5.3 

  man which
  
  -  which: which ใช้สำหรับค้นหา absolute path ของคำสั่งหรือโปรแกรมที่อยู่ในระบบ โดยอ้างอิงจากตัวแปร PATH

![5 4-5 5](https://github.com/user-attachments/assets/adbc7618-8b46-4d7c-b102-7ac342298214)

ข้อ 5.4-5.5

  -  which ls: ใช้ตรวจสอบว่าไฟล์คำสั่ง ls (list files) อยู่ใน directory
  -  which man: ใช้ตรวจสอบว่าไฟล์คำสั่ง man (manual pages) อยู่ใน directory

![6 1](https://github.com/user-attachments/assets/17398262-eef1-478e-a836-64c86ab0155a)

ข้อ 6.1

  -  ifconfig คือคำสั่งในระบบปฏิบัติการ Linux หรือ Unix ที่ใช้สำหรับดูและปรับแต่งการตั้งค่าของเครือข่าย เช่น การแสดงข้อมูลของ IP address, network interfaces, หรือการตั้งค่าอื่นๆ ที่เกี่ยวข้องกับการเชื่อมต่อเครือข่าย.

![6 2](https://github.com/user-attachments/assets/fe12ac3b-0ab8-401f-b788-69c4b8af5c0e)

ข้อ 6.2

  -  nslookup www.google.com ใช้สำหรับตรวจสอบข้อมูล DNS (Domain Name System) ของโดเมน www.google.com โดยจะคืนค่า IP address ที่เชื่อมโยงกับโดเมนนั้น ๆ

![6 3](https://github.com/user-attachments/assets/8ef5a1f4-0e06-4078-904d-8b79450fc27e)


![6 3_2](https://github.com/user-attachments/assets/640e0762-e18c-4002-8267-73f2e75ba7e3)


ข้อ 6.3

  - ping www.google.com ใช้สำหรับทดสอบการเชื่อมต่อเครือข่ายระหว่างคอมพิวเตอร์ของคุณกับเซิร์ฟเวอร์ของ www.google.com โดยการส่งแพ็กเก็ตข้อมูลไปยังเซิร์ฟเวอร์นั้น และรอรับการตอบกลับ
ผลลัพธ์ของคำสั่ง ping จะบอกเวลาในการรับส่งข้อมูล (latency) หรือเวลาที่ใช้ในการส่งแพ็กเก็ตข้อมูลจากคอมพิวเตอร์ของคุณไปยังเซิร์ฟเวอร์และกลับมา

  - traceroute คือเครื่องมือที่ใช้ในการตรวจสอบเส้นทางการส่งข้อมูลระหว่างคอมพิวเตอร์ของคุณกับปลายทาง (เช่น เซิร์ฟเวอร์ หรือเว็บไซต์) โดยแสดงเส้นทางที่แพ็กเก็ตข้อมูลเดินทางผ่านในเครือข่าย 

![6 4](https://github.com/user-attachments/assets/4617646e-03b8-4bc6-9a3b-dcd1c1e0b59a)

ข้อ 6.4

  -  netstat -n ใช้ในการแสดงสถานะการเชื่อมต่อเครือข่ายบนเครื่องคอมพิวเตอร์ของคุณ โดยแสดงหมายเลข IP และพอร์ตที่เชื่อมต่ออยู่ในรูปแบบตัวเลข

![7 1](https://github.com/user-attachments/assets/0322c8b0-bd4d-426e-8113-c1061bf8f27c)

ข้อ 7.1

  -  top ในระบบปฏิบัติการ Linux ใช้สำหรับแสดงข้อมูลเกี่ยวกับกระบวนการ (processes) ที่กำลังทำงานอยู่ในระบบ โดยแสดงรายละเอียดของการใช้ทรัพยากรต่างๆ เช่น CPU, หน่วยความจำ (RAM), และการใช้งานของโปรเซสต่างๆ ในเวลาจริง

![7 2](https://github.com/user-attachments/assets/873ba970-bc18-4ecf-b91f-e0c6033579ce)

ข้อ 7.2

  -  htop คือเครื่องมือที่ใช้ในการแสดงข้อมูลเกี่ยวกับกระบวนการ (processes) ในระบบปฏิบัติการ Linux แบบกราฟิก (ตัวอักษร) ที่ดีกว่า top ในหลายๆ ด้าน เช่น ความสะดวกในการใช้งานและความสามารถในการโต้ตอบ
