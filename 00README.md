# masterproject
Subject : PREDICTING STOCK PRICE DIRECTION USING TEXT CLASSIFICATION AND SENTIMENT ANALYSIS ON STOCK NEWS

เรื่อง     : การทำนายทิศทางราคาหุ้นด้วยการจำแนกข้อความและอารมณ์จากข่าวหุ้น

Created Date : 02 June 2020

Created By   : Woranun S.
  
  
***นิยามเนื้อหา***

1. ในโฟลเดอร์ masterproject จะแบ่งออกเป็น 12 พาร์ทย่อย โดย 6 พาร์ท จะเป็นโค้ดสำหรับการทำนายทิศทางราคาหุ้นจาก 6 อัลกอริทึม และ 6 พาร์ท สำหรับชุดข้อมูลหัวข้อข่าวในปี 2018 และ 2019 ที่ได้ผ่านการสุ่มหยิบข้อมูลพาร์ทละ 1,000 ข่าว

2. โค้ดทั้ง 6 พาร์ท จะแบ่งจากอัลกอริทึมที่ใช้สำหรับการทำนายทิศทางราคาหุ้น จะประกอบไปด้วย Naive Bayes, Decision Tree, Random Forest, Support Vector Machine, Neural Network แบบหนึ่งชั้นซ่อน และ Neural Network แบบหลายชั้นซ่อน

3. โค้ดการทำนายทิศทางราคาหุ้นทั้ง 6 อัลกอริทึม จะถูกแบ่งออกสำหรับชุดช้อมูลที่มีคุณลักษณะที่แตกต่างกันทั้ง 3 แบบ ดังนี้

4. ชุดข้อมูลที่ 1 และ 4 จะประกอบไปด้วย ชุดหัวข้อข่าว และ Class(Change, Nochange)

5. ชุดข้อมูลที่ 2 และ 5 จะประกอบไปด้วย ชุดหัวข้อข่าว, ค่าความรู้สึกในชั้วบวก ขั้วลบ และขั้วกลาง(-1, 0, 1) และ ป้ายกำกับ(Change, Nochange)

6. ชุดข้อมูลที่ 3 และ 6 จะประกอบไปด้วย ชุดหัวข้อข่าว, ค่าความรู้สึกในชั้วบวก ขั้วลบ และขั้วกลาง(-1, 0, 1) และ ป้ายกำกับ(Change, Nochange) ซึ่งแบ่งออกเป็น 3 Clusters
