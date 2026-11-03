# Little Wave Heroes 🎮

เกมต่อสู้อัตโนมัติแบบ Wave RPG บนเว็บ (HTML/CSS/JavaScript)

## เปิดผ่าน GitHub Pages
1. สร้าง GitHub repository ใหม่ (Public) เช่น `little-wave-heroes`
2. อัปโหลด `index.html` จาก ZIP นี้ไว้ที่ **root** ของ repository (ไม่ต้องอัปโหลด ZIP ทั้งก้อน) แล้ว Commit changes
3. ไปที่ **Settings → Pages → Build and deployment** เลือก **Deploy from a branch** / **main** / **/(root)** แล้ว Save
4. เมื่อ GitHub Pages เผยแพร่แล้ว เข้า `https://USERNAME.github.io/little-wave-heroes/` (เปลี่ยน USERNAME เป็นชื่อ GitHub จริง)

## ระบบเซฟ
- เกมบันทึกอัตโนมัติใน `localStorage` ของเว็บไซต์นี้ทุก 5 วินาที เมื่อซื้อของ เคลียร์เวฟ และเมื่อสลับแท็บ/ปิดหน้าเว็บ
- กลับมาเปิด URL **เดิมในเบราว์เซอร์และโปรไฟล์เดิม** จะเล่นต่อได้ (เริ่มเวฟปัจจุบันใหม่ แต่คงเหรียญ เลเวล อุปกรณ์ และอัปเกรด)
- การเปิดด้วย `file://` กับ GitHub Pages จะใช้ที่เก็บเซฟคนละที่กัน
- เซฟไม่ซิงค์ข้ามเครื่อง/เบราว์เซอร์อัตโนมัติ: เข้าแท็บ **ฮีโร่** กด **ดาวน์โหลดเซฟ** แล้วในอีกเครื่องกด **โหลดเซฟ** เลือก JSON
- หากล้างข้อมูลเว็บไซต์หรือใช้โหมดไม่ระบุตัวตนอาจทำให้เซฟหาย จึงควรสำรองไฟล์ JSON

ไม่ต้องติดตั้ง Node.js, Python หรือแพ็กเกจใด ๆ
