note:
สีพื้นหลัง bg-neutral-200
หัวข้อใหญ่ text-4xl font-bold text-neutral-600
เส้นขอบ border-b border-gray-200
ตัวอักษรp text-neutral-500

---

update news: (?)
เบราว์เซอร์สมัยใหม่ (Chrome, Safari, Edge) มีนโยบายความเป็นส่วนตัวที่ "ห้ามวิดีโอที่มีเสียงเล่นอัตโนมัติ" เพื่อไม่ให้ผู้ใช้งานตกใจ
:: ต้องใส่ Attribute muted (ปิดเสียง) และ loop (เล่นวน) เข้าไปคู่กับ autoplay

---

## Tailwind

---

**flex** : ค่าเริ่มต้น flex เรียกใช้คำสั่งตลอด (defult:แนวนอน)

- flex-col เรียงแนวตั้ง
- flex-row เรียงแนวนอน

---

**p** : padding ดันตัวเองข้างในให้ห่างจากกรอบ | **m** : margin ดันคนอื่นข้างนอกกรอบให้ออกไป

- p (4 ด้าน) / px (ซ้าย,ขวา) / py (บน,ล่าง) / pt, pr, pb, pl
- m (4 ด้าน) / mx (ซ้าย,ขวา) / my (บน,ล่าง) / mt, mr, mb, ml

---

**gap** : เว้นระยะห่างของ content ข้างใน

---

**border** : เส้นขอบ

- border-b ทำเส้นขอบล่าง

---

**h** : height ความสูง | **w** : width ดันคนอื่นข้างนอกกรอบให้ออกไป

- w-full ช่วยให้ element กางออกเต็มพื้นที่ container
- h-8 / h-[50%] / h-[20px]

---

**text** : ปรับขนาด, สี ของ text | **font** : ปรับฟ้อนต์, ความหนา

- text-xl / text-base / text-gray-500
- font-bold / font-normal

---

**grid** : สร้างตาราง

- grid ประกาศใช้
- grid-cols-1 เรียกใช้ 1 คอลัมม์
- md:grid-cols-3 desktop เรียกใช้ 3 คอลัมม์
