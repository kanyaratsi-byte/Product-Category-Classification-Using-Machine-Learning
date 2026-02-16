# Product-Category-Classification-Using-Machine-Learning
# Objective
- พัฒนาโมเดล Machine Learning เพื่อจำแนก “หมวดสินค้า (Multi-class)” โดยกำหนด Target เป็นคอลัมน์ category และประเมิน/ปรับแต่งโมเดลแบบเบา ๆ พร้อมตีความผล (Feature Importance)
# Dataset
- ไฟล์ customer_shopping_data.csv เป็นข้อมูลธุรกรรมการซื้อ (เช่น เพศ อายุ จำนวน ราคา วิธีชำระเงิน ศูนย์การค้า) โดยมีหมวดสินค้า 8 คลาส (Clothing, Cosmetics, Food & Beverage, Toys, Shoes, Souvenir, Technology, Books)
# Models Used
- KNN
- Decision Tree
- Random Forest
# Results
- KNN = 0.6415
- Decision Tree = 1.0
- Random Forest = 0.98175
# Key Insight
- ตัวแปร price มีอิทธิพลสูงมากต่อการจำแนกหมวดสินค้า (Feature Importance ของ RF: price 0.826487 สูงเด่น)
# Dataset
- เนื่องจากข้อจำกัดด้านขนาดไฟล์ ชุดข้อมูลจึงไม่ได้ถูกอัปโหลดไปยังที่เก็บข้อมูลนี้
- คุณสามารถดาวน์โหลดได้ที่นี่: [ดาวน์โหลดชุดข้อมูล]
https://drive.google.com/file/d/1BuQTlzNb10RmgJbPzrAJeaLd5nKKQhIK/view?usp=drive_link
