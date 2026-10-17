# App stretch for Relax
1. สร้างโปรเจกต์ Supabase → รัน `schema.sql` → Auth > Providers > Email (ปิด "Confirm email" ถ้าไม่ต้องการยืนยัน)
2. ใส่ `SUPABASE_URL` และ `SUPABASE_ANON_KEY` ใน `index.html`
3. Push ขึ้น GitHub → Settings > Pages > Deploy from branch (main / root) (ต้องเป็น HTTPS เพื่อใช้กล้อง)
4. ตั้ง Admin ด้วย SQL บรรทัดท้ายไฟล์ schema.sql
