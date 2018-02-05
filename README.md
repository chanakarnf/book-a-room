
#  Book A Room

**เขียนโปรแกรมสําหรับคํานวนราคาค่าใช้จ่ายสําหรับการจองห้องพักในรีสอร์ท โดยที่**
 > * ห้องพัก Standard Room ราคา 850  บาท/คืน
 > * ห้องพัก Delux Room    ราคา 1,050 บาท/คืน
 > * ห้องพัก Suite Room   ราคา 1,500 บาท/คืน
 - โดย 1 ห้องจะได้รับคูปองอาหารเช้า 2 ใบ(ค่าคูปองอาหารเช้าใบละ 200 บาท)

 **หมายเหตุ:**  
- ถ้าพัก 5 ห้องหรือ 5 คืนจะได้รับส่วนลด 20% จากราคาค่าใช้จ่ายทั้งหมด
- ถ้าพัก 7 ห้องหรือ7 คืน จะได้รับส่วนลด 30% จากราคาค่าใช้จ่ายทั้งหมด

# ข้อมูลเข้า
1. ให้ระบุจํานวนของห้องพักและแบบที่ต้องการ
2. ให้ระบุจํานวนคืนที่ต้องการพัก
3. ให้แสดงจํานวนคูปองอาหารที่ได้รับ
4. ให้ระบุจํานวนคูปองอาหารเช้าที่ต้องการเพิ่ม

# ข้อมูลออก
1. แสดงราคาค่าใช้จ่ายทั้งหมด
2. แสดงราคาค่าใช้จ่ายที่ต้องชําระมัดจํา 60% จากราคาค่าใช้จ่ายทั้งหมด
3. แสดงราคาค่าใช้จ่ายคงเหลือที่ต้องจ่ายเมื่อเข้าพัก



**ตัวอย่าง Input\Output**

```
Booking
~~~~~~~~~~~~~~~~~~~~~~~~~~
Standard Room 850 baht. (0=no): 1
Delux Room 1,050 baht. (0=no): 1
Suite Room 1,500 baht.(0=no): 0
For how many nights? 2
You have 8 breakfast coupons
Do you want extra breakfast coupons? (0=no) 2
Total amount due is 4200 Baht.
You have to pay deposit 1680 baht.
Then you need to pay 2520 baht for remaining balance later.
```
---
```
Booking
~~~~~~~~~~~~~~~~~~~~~~~~~~
Standard Room 850 baht. (0=no): 2
Delux Room 1,050 baht. (0=no): 0
Suite Room 1,500 baht.(0=no): 0
For how many nights? 1
You have 4 breakfast coupons
Do you want extra breakfast coupons? (0=no) 0
Total amount due is 1700 Baht.
You have to pay deposit 680 baht.
Then you need to pay 1020 baht for remaining balance later.
```


