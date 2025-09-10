# engse203-lab6

การทดสอบด้วย Postman
🔵 ทดสอบ Students API (MS SQL)
1. Health Check

GET http://localhost:3000/
<img width="1315" height="508" alt="image" src="https://github.com/user-attachments/assets/3c411b09-68db-4a98-bf92-9983f98ab998" />

2. ดึงข้อมูลนักเรียนทั้งหมด

GET http://localhost:3000/api/students
<img width="1320" height="524" alt="image" src="https://github.com/user-attachments/assets/3f45c731-9e0f-425d-afb6-12fe8d3431b9" />

3. เพิ่มนักเรียนใหม่

POST http://localhost:3000/api/students
<img width="1277" height="388" alt="image" src="https://github.com/user-attachments/assets/fbf7a662-4076-4a89-94fc-d9beabcdc209" />

4. ดึงข้อมูลนักเรียนตาม ID

GET http://localhost:3000/api/students/1
<img width="771" height="493" alt="image" src="https://github.com/user-attachments/assets/d6616058-cb92-447d-b079-2e5afadc1771" />

5. อัพเดทข้อมูลนักเรียน

PUT http://localhost:3000/api/students/1
<img width="931" height="513" alt="image" src="https://github.com/user-attachments/assets/b20d86bc-8083-42d5-8a86-ff002e3e0d3c" />
<img width="275" height="119" alt="image" src="https://github.com/user-attachments/assets/706741dd-f1ba-455b-87e8-725a8df6989a" />

6. ลบนักเรียน

DELETE http://localhost:3000/api/students/1
<img width="841" height="318" alt="image" src="https://github.com/user-attachments/assets/138cbb03-a01f-4914-91c4-e0d2a49ee1e9" />
<img width="275" height="148" alt="image" src="https://github.com/user-attachments/assets/9144836d-bd2f-43d8-b5e3-f0c1b526f839" />

