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

🟢 ทดสอบ Products API (MongoDB)
1. ดึงข้อมูล products ทั้งหมด

GET http://localhost:3000/api/products
<img width="1314" height="709" alt="image" src="https://github.com/user-attachments/assets/46a6d218-ca33-4e42-a905-0bb02feaf6d3" />
<img width="407" height="422" alt="image" src="https://github.com/user-attachments/assets/3abd2179-1b2b-488e-93d4-9f3f12bf0684" />


2. เพิ่ม product ใหม่

POST http://localhost:3000/api/products
<img width="1307" height="610" alt="image" src="https://github.com/user-attachments/assets/e22c7045-b81f-4e7c-9ee4-e82f329e88c9" />
<img width="245" height="114" alt="image" src="https://github.com/user-attachments/assets/1724978e-11a9-49c1-a47d-fff581c9931e" />

3. เพิ่ม product อีกตัว

POST http://localhost:3000/api/products
<img width="1302" height="583" alt="image" src="https://github.com/user-attachments/assets/33267ba3-89d6-4538-8911-f24c0d21598b" />
<img width="237" height="116" alt="image" src="https://github.com/user-attachments/assets/88ced05f-4990-475b-b038-538c50721dbb" />

4. ดึงข้อมูล product ตาม ID

GET http://localhost:3000/api/products/ObjectId_ที่ได้จาก_response
GET http://localhost:3000/api/products/68c0eb709ac2538b36cebea6
<img width="1307" height="579" alt="image" src="https://github.com/user-attachments/assets/96b688ed-0f7d-408c-8a3b-05d82617f175" />

5. อัพเดท product

PUT http://localhost:3000/api/products/ObjectId_ที่ได้จาก_response
PUT http://localhost:3000/api/products/68c0eb709ac2538b36cebea6
<img width="1312" height="579" alt="image" src="https://github.com/user-attachments/assets/a8162728-4842-4876-ab00-c6b84e7a03bd" />
<img width="738" height="56" alt="image" src="https://github.com/user-attachments/assets/52162b05-3a99-41a0-a4ed-4059693cd498" />

6. ลบ product

DELETE http://localhost:3000/api/products/ObjectId_ที่ได้จาก_response
DELETE http://localhost:3000/api/products/68c0eb709ac2538b36cebea6
<img width="1306" height="489" alt="image" src="https://github.com/user-attachments/assets/44357158-c98d-4b6e-be5d-11f73c20d004" />
<img width="424" height="35" alt="image" src="https://github.com/user-attachments/assets/aafbe483-4a7f-4965-9512-01f5dac2aacf" />
<img width="415" height="107" alt="image" src="https://github.com/user-attachments/assets/9fdb1fe9-64ed-4116-a812-d14ce7aedb46" />

