# Python Modullar bilan Ishlash - Amaliy Mashqlar

Bu mashqlarni bajarishda siz modullarni yaratishni va ulardan import qilishni o'rganasiz.

---

## 📌 Mashq 1: Matematik Operatsiyalar

**Vazifa:** `matematik.py` nomli modul yarating.

### matematik.py modulida bo'lishi kerak funksiyalar:
1. `qoshish(a, b)` - ikkita sonni qo'shadi
2. `ayirish(a, b)` - ikkita sonni ayiradi
3. `kopaytirish(a, b)` - ikkita sonni ko'paytiradi
4. `bolish(a, b)` - bo'ladi (nolga bo'linish holatini tekshiring)
5. `daraja(a, b)` - a ni b darajaga ko'taradi
6. `faktorial(n)` - n ning faktoriali

### main.py da qiling:
- `import matematik` yordamida modulni import qiling
- Barcha funksiyalarni sinab ko'ring
- `from matematik import qoshish, ayirish` ko'rinishida ham import qiling
- `import matematik as mat` shaklida ham import qiling

**Kutilayotgan natija:**
```
10 + 5 = 15
10 - 5 = 5
2^8 = 256
5! = 120
```

---

## 📌 Mashq 2: Matn Bilan Ishlash

**Vazifa:** `matnlar.py` nomli modul yarating.

### matnlar.py modulida bo'lishi kerak funksiyalar:
1. `katta_harf(matn)` - matnni katta harfga o'giradi
2. `kichik_harf(matn)` - matnni kichik harfga o'giradi
3. `teskari(matn)` - matnni teskari qiladi
4. `sozlar_soni(matn)` - matndagi so'zlar sonini qaytaradi
5. `unli_harflar_soni(matn)` - unli harflar sonini sanaydi
6. `palindrom_tekshir(matn)` - palindrom ekanligini tekshiradi

### main.py da qiling:
- Modulni import qiling
- Har bir funksiyani test qiling

**Test uchun matnlar:**
- "Salom Dunyo"
- "Python dasturlash tili"
- "radar" (palindrom)

---

## 📌 Mashq 3: Ro'yxat Operatsiyalari

**Vazifa:** `royxat.py` nomli modul yarating.

### royxat.py modulida bo'lishi kerak funksiyalar:
1. `max_qiymat(royxat)` - eng katta elementni topadi
2. `min_qiymat(royxat)` - eng kichik elementni topadi
3. `ortacha(royxat)` - o'rtacha qiymatni hisoblaydi
4. `juft_sonlar(royxat)` - faqat juft sonlarni qaytaradi
5. `toq_sonlar(royxat)` - faqat toq sonlarni qaytaradi
6. `saralash_osish(royxat)` - o'sish tartibida saralaydi
7. `saralash_kamayish(royxat)` - kamayish tartibida saralaydi
8. `dublikatlarni_olib_tashlash(royxat)` - takrorlanuvchilarni o'chiradi

### main.py da qiling:
- Modulni import qiling
- Turli ro'yxatlar yarating va funksiyalarni test qiling

**Test ro'yxati:**
```
sonlar = [5, 12, 3, 8, 15, 3, 9, 12, 7]
```

---

## 📌 Mashq 4: Valyuta Konvertori

**Vazifa:** `valyuta.py` nomli modul yarating.

### valyuta.py modulida:
- Valyuta kurslari lug'atini yarating (masalan: USD, EUR, RUB)
- Quyidagi funksiyalarni yozing:

1. `usd_to_uzs(miqdor)` - dollarni so'mga aylantiradi
2. `uzs_to_usd(miqdor)` - so'mni dollarga aylantiradi
3. `eur_to_uzs(miqdor)` - yevroni so'mga aylantiradi
4. `uzs_to_eur(miqdor)` - so'mni yevroga aylantiradi
5. `konvert(miqdor, dan, ga)` - universal konvertor funksiyasi

### main.py da qiling:
- Foydalanuvchidan summa va valyuta turini so'rang
- Konvertatsiya natijasini ko'rsating

**Misol kurslar:**
- 1 USD = 12,500 UZS
- 1 EUR = 13,500 UZS
- 1 RUB = 130 UZS

---

## 📌 Mashq 5: Geometrik Shakllar

**Vazifa:** `geometriya.py` nomli modul yarating.

### geometriya.py modulida bo'lishi kerak funksiyalar:

**Doira uchun:**
1. `doira_yuza(radius)` - doira yuzasi
2. `doira_perimetr(radius)` - doira perimetri

**To'rtburchak uchun:**
3. `tortburchak_yuza(uzunlik, kenglik)` - yuza
4. `tortburchak_perimetr(uzunlik, kenglik)` - perimetr

**Uchburchak uchun:**
5. `uchburchak_yuza(asos, balandlik)` - yuza
6. `uchburchak_perimetr(a, b, c)` - perimetr

**Kvadrat uchun:**
7. `kvadrat_yuza(tomon)` - yuza
8. `kvadrat_perimetr(tomon)` - perimetr

### main.py da qiling:
- Foydalanuvchiga shakl tanlash imkonini bering
- O'lchamlarni so'rang va natijani chiqaring

---

## 📌 Mashq 6: Talabalar Bazasi

**Vazifa:** `talabalar.py` nomli modul yarating.

### talabalar.py modulida:
- Talabalar ro'yxati (dictionary yoki class sifatida)
- Quyidagi funksiyalar:

1. `talaba_qoshish(ism, yosh, guruh, baholar)` - yangi talaba qo'shadi
2. `talaba_topish(ism)` - talabani topadi
3. `ortacha_baho(ism)` - talabaning o'rtacha bahosini hisoblaydi
4. `eng_yaxshi_talaba()` - eng yuqori o'rtacha bahoga ega talabani topadi
5. `guruh_boyicha(guruh)` - ma'lum guruhdagi talabalarni ko'rsatadi
6. `barcha_talabalar()` - barcha talabalarni chiqaradi

### main.py da qiling:
- Menu yarating (1-Qo'shish, 2-Qidirish, 3-Ko'rish, va h.k.)
- Foydalanuvchi bilan interaktiv ishlang

---

## 📌 Mashq 7: Kitobxona Tizimi (Kompleks Loyiha)

Bu vazifa bir nechta moduldan iborat bo'ladi:

### 1. kitob.py moduli:
- `Kitob` klassi yarating (nomi, muallif, yil, mavjud_nusxa)
- `kitob_qoshish()` funksiyasi
- `kitoblar_royxati()` funksiyasi

### 2. foydalanuvchi.py moduli:
- `Foydalanuvchi` klassi (ism, ID, olingan_kitoblar)
- `foydalanuvchi_qoshish()` funksiyasi
- `foydalanuvchilar_royxati()` funksiyasi

### 3. amaliyotlar.py moduli:
- `kitob_berish(foydalanuvchi_id, kitob_nomi)` - kitob berish
- `kitob_qaytarish(foydalanuvchi_id, kitob_nomi)` - kitob qaytarish
- `kimda_qaysi_kitob()` - qaysi foydalanuvchida qanday kitob borligini ko'rsatadi
- `statistika()` - umumiy statistikani chiqaradi

### 4. main.py:
- Barcha modullarni import qiling
- To'liq ishlaydigan kitobxona tizimini yarating
- Menu orqali boshqarish

---

## 📌 Mashq 8: Paket (Package) Yaratish

**Vazifa:** `matematik_paket` nomli papka yarating va uning ichida bir nechta modul yarating.

### Struktura:
```
matematik_paket/
    __init__.py
    asosiy.py (qo'shish, ayirish, ko'paytirish, bo'lish)
    qoshimcha.py (daraja, ildiz, logarifm)
    statistika.py (o'rtacha, mediana, moda)
```

### main.py da qiling:
- Paketdan turli modullarni import qiling:
  - `from matematik_paket import asosiy`
  - `from matematik_paket.qoshimcha import daraja`
  - `import matematik_paket.statistika as stat`

---

## 🎯 Qo'shimcha Vazifalar:

### Mashq 9: Maxsus Constants (O'zgarmaslar) Moduli
`constants.py` yarating:
- PI = 3.14159
- E = 2.71828
- LIGHT_SPEED = 299792458
- AVOGADRO = 6.022e23

Boshqa modullarda ishlatib ko'ring.

### Mashq 10: Yordamchi Funksiyalar Moduli
`utils.py` yarating:
- `is_email(text)` - email ekanligini tekshiradi
- `is_phone(text)` - telefon raqam ekanligini tekshiradi
- `format_sana(kun, oy, yil)` - sanani formatlaydi
- `random_parol(uzunlik)` - tasodifiy parol yaratadi

---

## 💡 Import Usullari (Eslatma):

```python
# 1. Butun modulni import qilish
import matematik
natija = matematik.qoshish(5, 3)

# 2. Faqat kerakli funksiyani import qilish
from matematik import qoshish
natija = qoshish(5, 3)

# 3. Bir nechta funksiyani import qilish
from matematik import qoshish, ayirish, kopaytirish

# 4. Alias (taxallus) bilan import qilish
import matematik as mat
natija = mat.qoshish(5, 3)

# 5. Funksiyaga alias berish
from matematik import faktorial as fact
natija = fact(5)

# 6. Hammasi import qilish (tavsiya etilmaydi)
from matematik import *
```

---

## ✅ Tekshirish Ro'yxati:

Har bir mashqni bajargandan so'ng tekshiring:
- [ ] Modul to'g'ri nomlangan (.py bilan tugaydi)
- [ ] Funksiyalar to'g'ri ishlayapti
- [ ] Import turli usullar bilan ishlayapti
- [ ] Docstring (izohlar) yozilgan
- [ ] Kod tartibli va tushunarli
- [ ] Xatoliklar to'g'ri ushlanmoqda (try-except)

**Omad va barakali dasturlash! 🚀**
