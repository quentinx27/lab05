# lab05

## Point: 1

### Point: 1.2 

- download linux MSL
  
![462639749_1125256001803045_1165160604047265856_n](https://github.com/user-attachments/assets/ab949084-2adc-4b46-b19d-d25331453688)

### Point:  1.3

- ติดตั้งเสร็จแล้วรอ restart
  
![462566928_1642551763004856_8665693952908403923_n](https://github.com/user-attachments/assets/00be2bf2-c404-4531-9a15-59cee518dd37)

### Point:  1.4

- สร้าง Username & password
  
![462558932_3435356486771721_4802501103814210261_n](https://github.com/user-attachments/assets/bb9cc8db-0e9f-447b-91f0-d06dd3125238)

### Point:  1.5

- ใช้งานได้แล้ว
  
![462581203_1415052096119206_3909431758853972472_n](https://github.com/user-attachments/assets/c2c7e006-f437-4bc3-8fdc-54669c822f0c)

## Point: 2

### Point:  2.1 - 2.2

![462575366_3976860145924579_710532576739828145_n](https://github.com/user-attachments/assets/a34453eb-0099-495d-9514-b2bd0baefaf9)

### Point:  2.3

1. cd .
  ```   
คำอธิบาย: . หมายถึง ไดเรกทอรีปัจจุบัน (current directory)

ผลลัพธ์: ไม่มีการเปลี่ยนแปลงตำแหน่ง (ยังอยู่ในไดเรกทอรีเดิม)
 ``` 
2. cd ..
 ``` 
คำอธิบาย: .. หมายถึง ไดเรกทอรีระดับบน (parent directory)

ผลลัพธ์: จะย้ายไปยังไดเรกทอรีที่อยู่เหนือไดเรกทอรีปัจจุบัน
 ``` 
3. cd ~
 ``` 
คำอธิบาย: ~ หมายถึง ไดเรกทอรีบ้านของผู้ใช้ (home directory) ซึ่งเป็นตำแหน่งเริ่มต้นของผู้ใช้งาน

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /home/<username> (ในกรณีนี้คือ /home/tonnoon2005)
 ``` 
4. cd /
 ```    
คำอธิบาย: / หมายถึง root directory หรือโฟลเดอร์ราก ซึ่งเป็นตำแหน่งสูงสุดในโครงสร้างของไฟล์ระบบ

ผลลัพธ์: จะย้ายไปยังไดเรกทอรี /
 ``` 
5. cd $
 ```   
คำอธิบาย: $ ไม่มีความหมายในบริบทของคำสั่ง cd (มันอาจหมายถึงการเรียกตัวแปรใน shell แต่ต้องตามด้วยชื่อของตัวแปร เช่น $HOME)

ผลลัพธ์: `ระบบแจ้งว่า "No such file or directory" เนื่องจากไม่มีไฟล์หรือไดเรกทอรีชื่อ $`
 ``` 
สรุป

cd . : อยู่ในไดเรกทอรีเดิม

cd .. : ถอยกลับไปยังไดเรกทอรีแม่

cd ~ : กลับไปยังไดเรกทอรีบ้านของผู้ใช้

cd / : ไปยังไดเรกทอรีรากของระบบ

cd $ : ใช้ผิด เพราะ $ ต้องตามด้วยตัวแปรที่ถูกต้อง เช่น $HOME

### Point: 2.4
  
![image](https://github.com/user-attachments/assets/362ffda0-4f5a-4768-9013-1fb362caf82e)

## Point: 3

### Point: 3.1

![image](https://github.com/user-attachments/assets/fca93aa2-596b-4505-8a54-53da4bdd85b0)

### Point: 3.2

![image](https://github.com/user-attachments/assets/c9c46ddc-4128-4fa9-baa7-9b656f6aa27e)

![image](https://github.com/user-attachments/assets/eee94a7a-e1ba-448b-ab83-9ced96d68c16)

### Point: 3.3

ls: Lists the contents of a directory in a simple format (files and directories only, without details).

ls -alt:

 ```
-a: Shows all files, including hidden files (those starting with a .).
-l: Provides a detailed list (permissions, ownership, size, etc.).
-t: Sorts the list by modification time, showing the most recently modified files first.
 ```
### Point: 3.4

![image](https://github.com/user-attachments/assets/3b7752c3-35f0-4993-9738-f82e8cae4aa4)

### Point: 3.5 - 3.6

![image](https://github.com/user-attachments/assets/ed560a62-8384-4aba-a59a-d86874e68169)

### Point: 3.7 - 3.10

![image](https://github.com/user-attachments/assets/0f46c365-0302-4530-bd69-d5cc6715bdfc)

![image](https://github.com/user-attachments/assets/b4f2e8df-9407-4395-8c77-4f2041391fa8)

## Point: 4

### Point: 4.1

![image](https://github.com/user-attachments/assets/a4ad5a76-4f09-47e5-8709-6fbb45053749)

![image](https://github.com/user-attachments/assets/297dd36c-0f24-4c3a-9bd0-d95f19b8ec21)

![image](https://github.com/user-attachments/assets/5f694194-0948-44d4-a947-f5e9458de420)

### Point: 4.2

![image](https://github.com/user-attachments/assets/c88e0ada-6c38-4f9e-abe8-d662e3d9e6ee)

### Point: 4.3

![image](https://github.com/user-attachments/assets/8cf58e69-1e6b-4dc7-b893-ba254924c5cd)

wc name.csv: Stands for "word count". It outputs:
```
Number of lines,
Number of words,
Number of characters in the file.
```

### Point: 4.4

![image](https://github.com/user-attachments/assets/a4993735-7d1d-4d90-bfcc-46718b3ef84d)

### Point: 4.5

cat: Displays the full content immediately.

more: Paginates the content for better readability in large files.

head: Displays the start of the file (first 10 lines).

tail: Displays the end of the file (last 10 lines).

wc: Counts lines, words, and characters; use -l to count only lines.

## Point: 5

### Point: 5.2

![image](https://github.com/user-attachments/assets/9e246a2d-608f-436c-abf8-23173ed1334f)

### Point: 5.3

![image](https://github.com/user-attachments/assets/c91d4ba3-0ac5-4229-8671-3155ae56ffd1)

### Point: 5.4 - 5.5

![image](https://github.com/user-attachments/assets/a12e1024-994b-4247-8621-84c2a4f8a2dd)

### Point: 5.6


- 5.1 What is an environment variable?

คำตอบ: Environment Variable คือค่าที่กำหนดไว้ในระบบปฏิบัติการเพื่อเก็บข้อมูลที่เกี่ยวข้องกับการตั้งค่าของโปรแกรมและระบบ ตัวแปรเหล่านี้ช่วยให้กระบวนการ (process) และโปรแกรมสามารถแชร์ข้อมูลที่สำคัญร่วมกันได้ เช่น:
```
PATH: กำหนดไดเรกทอรีสำหรับการค้นหาโปรแกรม
HOME: โฟลเดอร์บ้านของผู้ใช้งาน
USER: ชื่อผู้ใช้ที่ล็อกอินในระบบ
```
ตัวแปรเหล่านี้ถูกจัดเก็บเป็นคู่ key=value และสามารถเรียกดูได้ด้วยคำสั่ง เช่น printenv หรือ env


- 5.2 What does the command echo $PATH output and what does it mean?

คำตอบ: คำสั่ง echo $PATH ใช้สำหรับแสดงค่าของ Environment Variable ที่ชื่อ PATH ซึ่งเป็นรายการของไดเรกทอรีที่ระบบจะค้นหาเมื่อคุณพิมพ์คำสั่ง ตัวอย่างผลลัพธ์:

javascript
```
/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
```
ความหมาย:

แต่ละไดเรกทอรีใน PATH คั่นด้วย :

เมื่อคุณรันคำสั่ง เช่น ls ระบบจะค้นหาไฟล์ที่ชื่อ ls ในไดเรกทอรีเหล่านี้ตามลำดับ


- 5.3 What does the man which explain about the which command?

คำตอบ: 
```
คำสั่ง man which แสดงคู่มือของคำสั่ง which ซึ่งใช้สำหรับค้นหา absolute path ของคำสั่งหรือโปรแกรม
```

- 5.4 What is the absolute path of the ls command?
  
คำตอบ: ใช้คำสั่ง:
```
which ls

ผลลัพธ์: /bin/ls

Absolute Path ของ ls: /bin/ls
```
- 5.5 What is the absolute path of the man command?
  
คำตอบ: ใช้คำสั่ง:
```
which man

ผลลัพธ์: /usr/bin/man

Absolute Path ของ man: /usr/bin/man

```

## Point: 6

### Point: 6.1

![image](https://github.com/user-attachments/assets/600670ec-b73f-4cd0-bd6f-80799a685f66)

### Point: 6.2

![image](https://github.com/user-attachments/assets/09cc79f9-7830-4c5b-aa84-ff58410ce403)

### Point: 6.3





