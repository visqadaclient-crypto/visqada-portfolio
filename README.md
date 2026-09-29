# Portfolio (Mograph / Mood Edit)

เว็บ portfolio แบบไฟล์เดียว ใช้กับ GitHub Pages ได้ทันที

## วิธีขึ้นเว็บ
1. สร้าง repository ใหม่บน GitHub (ตั้งเป็น Public)
2. อัปโหลดไฟล์ทั้งหมดในโฟลเดอร์นี้ (index.html, .nojekyll, images/)
3. ไปที่ Settings → Pages → Source เลือก "Deploy from a branch"
4. เลือก branch `main` และโฟลเดอร์ `/ (root)` แล้วกด Save
5. รอ 1-2 นาที เว็บจะอยู่ที่ https://ชื่อผู้ใช้.github.io/ชื่อ-repo/
   (ถ้าตั้งชื่อ repo เป็น `ชื่อผู้ใช้.github.io` เว็บจะอยู่ที่ https://ชื่อผู้ใช้.github.io/)

## วิธีเพิ่มผลงาน
เปิด index.html แล้วแก้อาร์เรย์ `WORKS` ใกล้ท้ายไฟล์:

    {title:"ชื่อผลงาน", type:"Mograph", year:"2026", url:"https://youtu.be/xxxx", thumb:"images/work1.jpg"}

- วางรูปปกในโฟลเดอร์ `images/`
- `url` คือลิงก์วิดีโอ (YouTube, Vimeo ฯลฯ) ถ้าใส่ จะมีปุ่ม Watch ตอนชี้เมาส์
- ค้นหาคำว่า "Your Name" เพื่อเปลี่ยนเป็นชื่อจริง และแก้ลิงก์โซเชียลใน footer
