# 12 oylik FullStack dasturlash kursi

Noldan boshlovchilar uchun o'zbek tilida yozilgan FullStack dasturlash kursi sayti. Frontend (HTML, CSS, JavaScript, React, Next.js) dan backend (PHP, MySQL, Laravel) va real loyihagacha, jami **12 oy, 12 modul, 144 dars**.

Darslar sodda tilda, lekin chuqur tushuntiriladi va har bir mavzu kod misollari bilan beriladi.

## Kurs rejasi

| Modul | Oy    | Mavzu                            | Holati       |
| ----- | ----- | -------------------------------- | ------------ |
| 1     | 1-oy  | HTML & CSS                       | ✅ Tayyor    |
| 2     | 2-oy  | Advanced CSS & UI Foundations    | ✅ Tayyor    |
| 3     | 3-oy  | JavaScript Fundamentals          | 🚧 Tez orada |
| 4     | 4-oy  | Advanced JavaScript + TypeScript | 🚧 Tez orada |
| 5     | 5-oy  | React.js                         | 🚧 Tez orada |
| 6     | 6-oy  | Next.js                          | 🚧 Tez orada |
| 7     | 7-oy  | PHP Asoslari                     | 🚧 Tez orada |
| 8     | 8-oy  | MySQL & Database Design          | 🚧 Tez orada |
| 9     | 9-oy  | Laravel Fundamentals             | 🚧 Tez orada |
| 10    | 10-oy | Advanced Laravel                 | 🚧 Tez orada |
| 11    | 11-oy | Git & GitHub + Backend Project   | 🚧 Tez orada |
| 12    | 12-oy | Yakuniy loyiha + WordPress bonus | 🚧 Tez orada |

## Kurs kimlar uchun?

- Dasturlashni noldan o'rganmoqchi bo'lganlar
- Frontend yoki backend yo'nalishini tanlamoqchi bo'lganlar
- Real loyihalar orqali portfolio yig'moqchi bo'lganlar

Oldindan hech qanday bilim talab qilinmaydi. Faqat kompyuter va o'rganishga xohish yetarli.

## Loyiha tuzilmasi

```
kurs/
├── index.html      # Mundarija (barcha modullar)
├── modul-01.html   # HTML & CSS
├── modul-02.html   # Advanced CSS & UI Foundations
├── ...
├── modul-12.html   # Yakuniy loyiha + WordPress
├── style.css       # Umumiy uslublar
└── README.md
```

Har bir modul alohida HTML sahifa. Sayt oddiy HTML va CSS dan iborat, hech qanday kutubxona yoki build jarayoni kerak emas.

## Ishga tushirish

```bash
git clone https://github.com/mirrrjr/web.git
cd web
```

Keyin `index.html` faylini brauzerda oching. Yoki lokal server bilan:

```bash
python3 -m http.server 8000
# brauzerda: http://localhost:8000
```

## GitHub Pages orqali joylash

1. Repozitoriyning **Settings → Pages** bo'limiga kiring.
2. **Source** da `main` branch va `/ (root)` ni tanlang.
3. Bir necha daqiqadan keyin sayt `https://mirrrjr.github.io/web/` manzilida ochiladi.

## Yangi modul qo'shish

1. Tegishli `modul-XX.html` faylini oching.
2. Mavzular ro'yxatini darslar bilan almashtiring. `modul-01.html` dagi tuzilmadan namuna oling:
    - dars sarlavhasi (`<h2>`),
    - sodda tushuntirish (`<p>`),
    - kod misoli (`<pre><code>`).
3. `index.html` dagi modul kartochkasidan "soon" classini olib tashlang.

## Hissa qo'shish

Xato topsangiz yoki tushuntirishni yaxshilash mumkin bo'lsa, **Issue** oching yoki **Pull Request** yuboring. Iltimos, matnlarni standart o'zbek lotin alifbosida (sh, ch, o', g') yozing.

## Muallif

**mirrrjr** — [GitHub](https://github.com/mirrrjr)
