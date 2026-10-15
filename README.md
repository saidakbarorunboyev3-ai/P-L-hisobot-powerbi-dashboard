# Foyda va zarar (P&L) hisoboti — Power BI Dashboard

Ushbu loyoya korxonaning moliyaviy ko'rsatkichlarini tahlil qilish, daromad va xarajatlar dinamikasini kuzatish hamda reja bajarilishini nazorat qilish uchun Power BI dasturida ishlab chiqilgan zamonaviy interaktiv hisobot (Dashboard) hisoblanadi.

---

## 📊 Loyiha tuzilishi va sahifalar

Hisobot ikki asosiy qismdan (sahifadan) iborat bo'lib, ular bir-biri bilan o'zaro bog'langan:

### 1. Asosiy Sahifa (Umumiy tahlil va KPI'lar)
* **Maqsad:** Rahbariyat va tahlilchilar uchun asosiy moliyaviy ko'rsatkichlarni bir qarashda tushunishni ta'minlash.
* **Tarkibi:**
  * **KPI Kartochkalari:** Daromad, Yalpi foyda, EBIT (operatsion foyda), Sof foyda va Sof marja ko'rsatkichlari ularning reja bo'yicha foizli og'ishlari bilan.
  * **Oylik dinamika grafigi:** Daromadning faktik va rejalashtirilgan ko'rsatkichlari oyma-oy taqsimoti.
  * **Qo'shimcha vizuallar:** Daromad mahsulotlar ulushi (Donut chart), operatsion xarajatlar tuzilmasi va regionlar kesimidagi sof foyda taqsimoti.

### 2. Ikkinchi Sahifa (P&L Matritsasi / Batafsil jadval)
* **Maqsad:** Moliyaviy hisobotning barcha moddalari bo'yicha batafsil raqamli ma'lumotlarni ko'rish.
* **Tarkibi:**
  * Daromad, sotilgan mahsulot tannarxi, yalpi foyda, operatsion xarajatlar, foiz xarajatlari va soliqlar kesimida *Fakt*, *Reja*, *Farq (absolyut)* hamda *Farq (%)* ko'rsatkichlari.
  * Shartli formatlash (conditional formatting) yordamida rejadan ortib ketgan yoki kamomad bo'lgan qismlarning qizil/ko'k ranglarda yaqqol ajratib ko'rsatilishi.

---

## 🛠 Texnik xususiyatlar va vositalar
* **Asbob:** Power BI Desktop
* **Ma'lumotlar bazasi va manbalari:** Excel / SQL asosidagi moliyaviy ma'lumotlar.
* **Dizayn uslubi:** Minimalizm, zamonaviy karta bloki va foydalanuvchiga qulay (User-Friendly) interfeys.

---

## 🚀 Loyihani qanday ishga tushirish kerak?
1. Repozitoriyadagi `.pbix` kengaytirgichli faylni yuklab oling.
2. Kompyuteringizda **Power BI Desktop** dasturini oching.
3. Faylni dastur orqali ochib, o'z ma'lumotlar bazangizga moslab ma'lumotlarni yangilang (`Refresh`).
