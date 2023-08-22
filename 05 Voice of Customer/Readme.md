# Voice of Customer โดยใช้ Python ใช้ขั้นตอนต่างๆ ดังนี้

[Open in Colab](https://colab.research.google.com/drive/1zog8ClTN5TWm2HnWX-Rg4BPYfyYfO2AP?usp=sharing)

**1. Installing libraries:**
ก่อนที่เราจะเริ่มต้นพัฒนาโค้ดเราจำเป็นต้องติดตั้งไลบรารีที่จำเป็น ในที่นี้อาจเป็น pythainlp, gensim, pandas, numpy, matplotlib เป็นต้น โดยคำสั่งจะมีลักษณะเช่น

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%201.png)

**2. Importing libraries and data:**
เราจำเป็นต้องนำเข้าไลบรารีและข้อมูลที่จะนำมาประมวลผล

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%202.png)

**3. Tokenize words with pythainlp:**
ใช้ pythainlp เพื่อทำการตัดคำของข้อความ Voice of Customer

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%203.png)

**4. Creating dictionary:**
สร้างพจนานุกรมคำที่ใช้ในการสร้างโมเดล LDA

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%204.png)

**5. Topic modeling using LDA:**
ทำการโมเดลหัวข้อด้วย Latent Dirichlet Allocation (LDA)

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%205.png)

**6. Visualizing results:**
แสดงผลลัพธ์ของโมเดล LDA ด้วยกราฟ

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%206.png)

**7. Predict Topics:**
ทำการพยากรณ์หัวข้อของข้อความ

![Alt Text](https://github.com/JumpNatchanon/MADT8101-Customer-Analytics/blob/bf4354b374e02a38e9aa1bf61f35482b087f6f84/05%20Voice%20of%20Customer/Pictures/NLP%207.png)

## การใช้ Natural Language Processing (NLP) เพื่อวิเคราะห์และประมวลผลข้อมูล Voice of Customer (VoC) มีประโยชน์มากมายสำหรับธุรกิจและองค์กรต่างๆ ดังนี้
* **เข้าใจความคิดเห็นของลูกค้า**: VoC ช่วยให้คุณเข้าใจว่าลูกค้ามีความคิดเห็นเกี่ยวกับผลิตภัณฑ์หรือบริการของคุณอย่างไร ช่วยในการตรวจสอบว่าสิ่งที่คุณกำลังนำเสนอไปถูกต้องตามความต้องการของลูกค้าหรือไม่

* **ค้นหาแนวทางการพัฒนา:** การวิเคราะห์ VoC ช่วยให้คุณรู้ว่าลูกค้าต้องการอะไรเพิ่มเติมหรือปรับปรุงในผลิตภัณฑ์หรือบริการ เป็นแนวทางในการพัฒนาและปรับปรุง

* **การดูแลลูกค้า:** การเข้าใจในความคิดเห็นของลูกค้าช่วยให้คุณสามารถดูแลลูกค้าได้ดีขึ้น วางแผนกลยุทธ์ในการตอบรับและแก้ไขปัญหาที่เกิดขึ้น

* **การสร้างความพึงพอใจ:** การรับฟังและตอบสนองต่อความคิดเห็นของลูกค้าช่วยในการสร้างความพึงพอใจและความภักดีในผลิตภัณฑ์หรือบริการของคุณ

* **การวิเคราะห์เทรนด์:** การใช้ NLP เพื่อวิเคราะห์ VoC ช่วยในการระบุแนวโน้มและแนวทางที่กำลังเกิดขึ้นในความคิดเห็นของลูกค้า เช่น หัวข้อที่ถูกพูดถึงบ่อยๆ

* **ปรับกลยุทธ์การตลาด:** การวิเคราะห์ความคิดเห็นของลูกค้าช่วยในการปรับแผนกลยุทธ์การตลาด เช่น การปรับเปลี่ยนข้อความโฆษณาหรือการติดต่อลูกค้า

* **การเปรียบเทียบกับคู่แข่ง:** การวิเคราะห์ VoC ช่วยในการเปรียบเทียบความคิดเห็นของลูกค้ากับคู่แข่ง เพื่อค้นหาจุดเด่นและจุดอ่อนของผลิตภัณฑ์หรือบริการ

* **การดำเนินการตามกฎหมาย:** การตรวจสอบความคิดเห็นของลูกค้าสามารถช่วยในการตรวจสอบการปฏิบัติตามกฎหมาย หากมีการรายงานปัญหาหรือข้อร้องเรียน

* **การวิเคราะห์สัญญาณก่อนเกิดปัญหา:** การวิเคราะห์ VoC ช่วยในการตรวจหาสัญญาณที่บ่งชี้ถึงปัญหาที่อาจเกิดขึ้นในอนาคต ช่วยในการเตรียมความพร้อมและป้องกันปัญหา

โดยรวมแล้ว การใช้ NLP ในการวิเคราะห์ Voice of Customer ช่วยให้ธุรกิจสามารถปรับปรุงผลิตภัณฑ์หรือบริการให้ตรงกับความต้องการของลูกค้าได้อย่างมีประสิทธิภาพและเติบโตได้ดีขึ้นในอนาคต.
