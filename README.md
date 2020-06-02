# masterproject
CODING FOR PREDICTING STOCK PRICE DIRECTION USING TEXT CLASSIFICATION AND SENTIMENT ANALYSIS ON STOCK NEWS
เรื่อง การทำนายทิศทางราคาหุ้นด้วยการจำแนกข้อความและอารมณ์จากข่าวหุ้น
       
วิธีใช้
1. ในโฟลเดอร์ masterproject จะแบ่งออกเป็น 9 พาร์ทย่อย โดย 6 พาร์ท จะเป็นโค้ดสำหรับการทำนายทิศทางราคาหุ้น และ 3 พาร์ท สำหรับชุดข้อมูลที่มีคุณลักษณะที่แตกต่างกัน 
2. โค้ดสำหรับการทำนายทิศทางราคาหุ้นทั้ง 6 พาร์ท จะแบ่งออกเป็น 3 ส่วนย่อย สำหรับการทำนายทิศทางราคาหุ้นด้วยชุดช้อมูลที่ 1, 2 และ 3
3. โค้ดทั้ง 6 พาร์ท จะแบ่งจากอัลกอริทึมที่ใช้สำหรับการทำนายทิศทางราคาหุ้น จะประกอบไปด้วย Naive Bayes, Decision Tree, Random Forest, Support Vector Machine, Neural Network แบบ 1 Layer และ Neural Network แบบ Multi-Layer
3. ชุดข้อมูลที่ 1 จะประกอบไปด้วย ชุดหัวข้อข่าว และ Class(Change, Nochange)
4. ชุดข้อมูลที่ 2 จะประกอบไปด้วย ชุดหัวข้อข่าว, ค่าความรู้สึกในชั้วบวก ขั้วลบ และขั้วกลาง(-1, 0, 1) และ Class(Change, Nochange)
5. ชุดข้อมูลที่ 3 จะประกอบไปด้วย ชุดหัวข้อข่าว, ค่าความรู้สึกในชั้วบวก ขั้วลบ และขั้วกลาง(-1, 0, 1) และ Class(Change, Nochange) ซึ่งแบ่งออกเป็น 3 Clusters
