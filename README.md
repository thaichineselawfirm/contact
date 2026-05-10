# Thai Chinese Law Firm — Contact Hub (Linktree-style)

หน้าเว็บรวมช่องทางติดต่อสำหรับ **Thai Chinese Law Firm Co., Ltd. (สำนักงานกฎหมายไทย-จีน · 泰中律所)**
Single-page · Static HTML · พร้อม Deploy บน GitHub Pages, Netlify, Vercel หรือ host อื่น ๆ ทันที

## Files
```
.
├── index.html         # หน้าเว็บทั้งหน้า (รวม CSS/JS ในไฟล์เดียว)
├── .nojekyll          # ปิด Jekyll ของ GitHub Pages (ไม่ต้องแก้)
├── README.md
└── assets/
    ├── logo.png       # โลโก้สำนักงาน
    ├── cover.jpg      # ภาพหน้าปก hero
    └── line-qr.png    # QR LINE สำรอง (ตัวจริงโหลดจาก qr-official.line.me)
```

## Features
- ดีไซน์พรีเมียม Navy + Gold เข้ากับโลโก้สำนักงาน
- รองรับ 3 ภาษา: ไทย / English / 中文 (สลับได้ที่มุมขวาบน)
- ปุ่ม Quick Action: โทร, LINE, WeChat (กดแล้ว copy ID อัตโนมัติ), Email
- การ์ดช่องทางติดต่อ 6 ช่อง: LINE, WeChat, Phone, Email, Facebook, TikTok
- LINE QR แบบสด (live) จาก `qr-official.line.me` + fallback ไปที่ `assets/line-qr.png`
- เวลาทำการ + บริการของเรา (4 หมวด)
- Floating LINE button + scroll reveal animation
- มือถือ/iPad/Desktop responsive ครบ
- SEO meta + Open Graph พร้อม

## Deploy บน GitHub Pages
1. สร้าง repo ใหม่ใน GitHub เช่นชื่อ `contact` หรือ `thaichineselawfirm`
2. อัปโหลดทุกไฟล์ในโฟลเดอร์นี้ขึ้นไปบน branch `main` (หรือใช้ `git push`)
3. ไปที่ **Settings → Pages**
   - Source: `Deploy from a branch`
   - Branch: `main` / Folder: `/ (root)`
4. รอประมาณ 1 นาที เว็บจะออนไลน์ที่ `https://<username>.github.io/<repo-name>/`

## ใช้ Custom Domain (ทางเลือก)
- เพิ่มไฟล์ `CNAME` ที่ root พร้อมโดเมน เช่น `contact.thaichineselawfirm.co.th`
- ตั้งค่า DNS ให้ชี้ CNAME → `<username>.github.io`

## แก้ไขข้อมูลติดต่อ
ทุกข้อมูลอยู่ใน `index.html` ค้นหาคำเหล่านี้แล้วแก้ได้เลย:
- เบอร์โทร: `065-431-6810` / `tel:0654316810`
- Email: `Aekarat@thaichineselawfirm.co.th`
- LINE: `https://lin.ee/9tULV0A` / `@thaichineselawfirm`
- WeChat: `Thailaw999`
- Facebook/TikTok: ค้นคำว่า `facebook.com` / `tiktok.com`

## เปลี่ยนคำแปล
ในไฟล์ `index.html` มีออบเจกต์ `I18N = { th, en, zh }` — แก้คำแปลในนั้นได้เลย

## Credits
© Thai Chinese Law Firm Co., Ltd. — สงวนลิขสิทธิ์
