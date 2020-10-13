![chsv_logo](https://www.img.in.th/images/e4313f5d47a3b321b52926793e2f1958.png)

## [INT353 & INT450 Information Technology Project]
#### Web Application for Shipping within King Mongkut's University of Technology Thonburi with a radius of less than 1 kilometer (เว็บแอปพลิเคชันสำหรับการจัดส่งสินค้าภายในมหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี ด้วยระยะทางรัศมีไม่เกิน 1 กิโลเมตร)
[click to Chern Savoey Website](https://chernsavoey.herokuapp.com/)

### Start to Project

```
 git clone https://github.com/pakbungnatchanon/SeniorProject2020
```
```
 cd SeniorProject2020
```
```
 npm install
```
```
 npm run start
```
> App running on port 8080 | [http://localhost:8080/](http://localhost:8080/)


### รายชื่อสมาชิก
* นายคณาเดช  คงสมบัติ รหัสนักศึกษา 60130500027 
   * [natchanon.ksbb@mail.kmutt.ac.th](natchanon.ksbb@mail.kmutt.ac.th) | [GitHub : kndpakbung](https://github.com/kndpakbung)
* นางสาวรวินท์  หวังวิศวาวิทย์ รหัสนักศึกษา 60130500076 
   * [ravin.wang@mail.kmutt.ac.th](ravin.wang@mail.kmutt.ac.th) | [GitHub : variin](https://github.com/variin)
* นางสาวสิริรัตน์  ตันธนาวิภาส รหัสนักศึกษา 60130500096 
   * [sirirat.t@mail.kmutt.ac.th](sirirat.t@mail.kmutt.ac.th) | [GitHub : Pomsirirat](https://github.com/Pomsirirat)

### อาจารย์ที่ปรึกษา
1.	ดร. ตุลย์ ไตรยสรรค์ (อาจารย์ที่ปรึกษาหลัก)
2.	ดร. วิชัย เอี่ยมสินวัฒนา (อาจารย์ที่ปรึกษาร่วม)

### Background and Problem Statement
ความสะดวกสบายถือเป็นสิ่งหนึ่งในการดำรงชีวิตในปัจจุบัน ไม่ว่าจะเป็นในเรื่องของการรับประทานอาหารหรือการส่งของ ทางคณะผู้จัดทำจึงได้เล็งเห็นถึงปัญหาที่เกิดขึ้น เนื่องจากแต่ละคนมีปัญหาความไม่สะดวกที่แตกต่างกัน เช่น นักศึกษากำลังเรียน อาจารย์กำลังทำการสอนหนังสือ บุคลากรติดภาระงาน สถานที่ที่ต้องไปซื้ออาหารมีระยะทางไกลจากจุดที่อยู่ในตอนนั้น ระหว่างทางที่ไปแดดร้อน อีกทั้งยังต้องใช้เวลาอย่างคุ้มค่าเพื่อไปเรียนหรือทำการสอนหากต้องเดินไปต่อคิวเพื่อซื้ออาหารหรือเครื่องดื่ม อาจจะไม่ทันเวลาได้ ทั้งหมดที่กล่าวมานี้ถือเป็นตัวอย่างปัญหาที่ก่อให้เกิดความไม่สะดวกในการเดินไปซื้ออาหารหรือเครื่องดื่มบริเวณมหาวิทยาลัย  
หากสั่งบริการธุรกิจส่งอาหาร (Food Delivery) แบบที่มีอยู่ในปัจจุบันก็จะมีราคาค่าส่งที่สูง และมีแค่เพียงร้านค้าต่าง ๆ จากภายนอกมหาวิทยาลัย จึงมีความไม่สะดวกหากต้องการใช้เวลาที่รวดเร็ว เพราะร้านอาหารอยู่ไกลจากมหาวิทยาลัย อาจจะเป็นสาเหตุหนึ่งที่ทำให้ต้องรอเป็นระยะเวลานาน 
ทางคณะผู้จัดทำจึงรวบรวมปัญหาที่เกิดขึ้นทั้งหมดมาวิเคราะห์ และตั้งเป้าหมายว่า จะอำนวยความสะดวกให้กับนักเรียนนักศึกษา อาจารย์ และบุคลากรภายในมหาวิทยาลัยในการจัดส่งอาหาร เครื่องดื่ม หรือเอกสาร ในรูปแบบ Business to Customer (B2C) และ Customer to Customer (C2C) โดยผู้ส่งจะเป็นนักศึกษาหรือบุคลกรภายในมหาวิทยาลัย ซึ่งถือเป็นรายได้เสริมเล็ก ๆ จากเวลาว่างที่มีอยู่
หากสามารถพัฒนาเว็บแอปพลิเคชันได้สำเร็จลุล่วง จะถือเป็นการสนับสนุนในเรื่องของ E – Commerce ในนามมหาวิทยาลัย ที่ใช้ภายในมหาวิทยาลัย รวมถึงเป็นการสร้าง Sharing Economy ซึ่งรายได้ที่ได้มานั้นเกิดจากการพึ่งพากันของคนภายในมหาวิทยาลัย และยังช่วยในการแก้ไขปัญหาและอำนวยความสะดวกให้กับนักศึกษา อาจารย์และบุคลภายในมหาวิทยาลัยอีกด้วย

### Objectives
1.	เพื่อเพิ่มความสะดวกสบายให้แก่นักศึกษา อาจารย์ บุคลากร และร้านค้าภายในมหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี
2.	เพื่อสร้างรายได้ในยุคดิจิทัลให้แก่บุคลากรภายในมหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี ที่เป็นผู้ให้บริการ โดยที่ผู้ให้บริการจะไม่เสียค่าธรรมเนียมใด ๆ
3.	ส่งเสริม Sharing Economy ซึ่งเป็นการสร้างรายได้จากการพึ่งพากันแก่นักศึกษา อาจารย์ บุคลากร และร้านค้าภายในมหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี
4.	ส่งเสริมให้นักศึกษา อาจารย์ บุคลากรสร้างรายได้ด้วยวิธีการเดินออกกำลังกาย

###	ภาพรวมระบบ 
เป็นเว็บแอปพลิเคชันที่ช่วยอำนวยความสะดวกสบายในการจัดส่งสินค้า เช่น อาหาร หรือเครื่องดื่มภายในมหาวิทยาลัย โดยทั้งนักศึกษา อาจารย์ และบุคลากรในมหาวิทยาลัย สามารถเป็นได้ทั้งผู้ให้บริการและผู้รับบริการ
### จุดเด่นของงาน 
เป็นช่องทางส่งเสริมการซื้อขายภายในมหาวิทยาลัย ให้มีความคล่องตัว อีกทั้งยังเพิ่มความสะดวกสบายให้ผู้ใช้มากยิ่งขึ้น และยังเป็นการสร้างรายได้ให้กับนักศึกษา อาจารย์ หรือบุคลากรที่เป็นผู้ให้บริการอีกด้วย
### กลุ่มเป้าหมาย
นักศึกษา อาจารย์ บุคลากร และร้านค้าภายในมหาวิทยาลัยเทคโนโลยีพระจอมเกล้าธนบุรี
### ฟังก์ชันการทำงาน
* การสั่ง – รับรายการอาหาร 
*	การติดตามสถานะการส่งจากผู้ให้บริการ
*	การแช็ตเพื่อให้ผู้ให้บริการและผู้รับบริการสื่อสารกัน
*	ช่องทางการชำระเงินให้กับผู้ให้บริการ

### Tools and Techniques
* node.js
* express.js
* bootstrap
* bcyptjs
* passport.js ang OAUTH
* firebase cloud firestore
* heroku
* google cloud
* google maps API
