
<p align="center">
  <img src="static/logo.jpg" alt="132-Maktab logo" width="180"/>
</p>

<h1 align="center">132-Maktab-Test-Tizimi</h1>

---

## 🎯 Loyiha haqida

Ushbu tizim maktab o‘quvchilari uchun onlayn testlarni o‘tkazish va natijalarni ko‘rish imkonini beradi.  
Admin DOCX fayl orqali testlarni yuklaydi, tizim esa to‘g‘ri javoblarni `*` belgisi orqali avtomatik aniqlaydi.

---

## 🔐 Admin ma’lumotlari

- Login: **Murodullayev**  
- Parol: **MMI1029**

Admin:
- Testlarni DOCX formatda yuklaydi  
- Test uchun vaqt belgilaydi  
- O‘quvchilar natijalarini ko‘radi  
- O‘quvchi qayta kirishini ruxsat beradi yoki to‘sadi  

---

## 👨‍🎓 O‘quvchi imkoniyatlari

- Ism va familiyasini kiritadi  
- Sinfni tanlaydi (5A dan 11B gacha)  
- Testni boshlaydi  
- Natijani yakunda ekranda ko‘radi  
- Vaqt tugashidan oldin testni yakunlashi mumkin  

---

## 📄 Test fayli formati

DOCX fayl quyidagi shaklda bo‘ladi:

```
1. HTML tili nima?
A) Dasturlash tili
*B) Belgilash tili
C) Brauzer
D) Tarmoq protokoli
```

`*` belgisi — to‘g‘ri javobni bildiradi.

---

## 🧩 Tizim tuzilmasi

```
132-Maktab-Test-Tizimi/
│
├── 132-Maktab_test.py
├── requirements.txt
├── README_132-Maktab-Test.md
│
├── static/
│   └── logo.jpg
│
└── templates/
    ├── login.html
    ├── start.html
    ├── test.html
    ├── natija.html
    └── admin.html
```

---

## 🚀 Render orqali ishga tushirish

Quyidagi tugmani bosib, loyihani **Render**’da avtomatik ishga tushiring:

<p align="center">
  <a href="https://render.com/deploy?repo=https://github.com/YOUR_USERNAME/132-Maktab-Test-Tizimi">
    <img src="https://render.com/images/deploy-to-render-button.svg" alt="Deploy to Render"/>
  </a>
</p>

---

## ⚙️ Render sozlamalari

- **Build Command:** `pip install -r requirements.txt`  
- **Start Command:** `python 132-Maktab_test.py`  
- **Port:** 5000  

Tizim ishga tushgach, saytingiz manzili quyidagicha bo‘ladi:  
👉 https://132-maktab-test.onrender.com (yoki Render bergan domen)

---

## 💡 Foydali eslatmalar

- DOCX test faylini `testlar/` papkasiga joylashtiring.  
- Har bir sinf uchun alohida test yuklash mumkin (masalan, `5A.docx`, `11B.docx`).  
- Tizim avtomatik natijalarni `data/` papkasida saqlaydi.  
- Parol va sozlamalarni `132-Maktab_test.py` ichida o‘zgartirish mumkin.  

---

<p align="center">📘 Tizim muallifi: <b>Murodullayev</b></p>
