<div align="center">

# 📞 Ichki (built-in) qo'ng'iroq yozuvini yoqish

**Android 9+ da Google ilovalarga qo'ng'iroq ovozini yozishni taqiqlagan.**
Lekin telefonning **o'z** yozib olish funksiyasini yoqib olsak — ikkala tomon ovozi
toza yoziladi. Quyida buni **Samsung**, **Xiaomi** va **Huawei/Honor** da
qanday qilish ko'rsatilgan.

![Samsung](https://img.shields.io/badge/Samsung-SamFW_Tool-1428A0?style=flat-square)
![Xiaomi](https://img.shields.io/badge/Xiaomi-Dialer_o'rnatish-FF6900?style=flat-square)
![Huawei](https://img.shields.io/badge/Huawei_/_Honor-APK_modul-CF0A2C?style=flat-square)

</div>

---

## 📖 Mundarija

- [Nega bu kerak?](#-nega-bu-kerak)
- [1-qadam: avval tekshiring](#-1-qadam-avval-tekshiring)
- [🔵 Samsung uchun](#-samsung-uchun)
- [🟠 Xiaomi / Redmi / POCO uchun](#-xiaomi--redmi--poco-uchun)
- [🔴 Huawei / Honor uchun](#-huawei--honor-uchun)
- [✅ Yoqilganini qanday bilamiz?](#-yoqilganini-qanday-bilamiz)
- [❓ Muammolar va yechimlar](#-muammolar-va-yechimlar)

---

## 🔍 Nega bu kerak?

Telefonda qo'ng'iroq ikki xil yo'l bilan yozilishi mumkin:

| Yo'l | Kim yozadi | Natija |
|:--|:--|:--|
| 🥇 **Ichki yozuv** | Telefonning **o'zi** (ishlab chiqaruvchi funksiyasi) | ✅ **Ikkala tomon ovozi toza** |
| 🥈 **Mikrofon yozuvi** | Bizning ilova (zaxira usul) | ⚠️ O'z ovozingiz aniq, mijoz **past** eshitiladi |

Ilova ikkalasini ham qiladi va **ichki yozuvni ustun qo'yadi**. Ya'ni ichki
yozuvni yoqsangiz — sifat avtomatik ravishda eng yaxshisiga o'tadi, ilovada
qo'shimcha hech narsa sozlash **shart emas**.

> [!NOTE]
> Ichki yozuv ko'p mamlakatlarda (MDH, Yevropa, AQSh) **zavoddan o'chirilgan**.
> U Hindiston, Indoneziya, Tailand, Vetnam kabi mintaqalar uchun ochiq.
> Shuning uchun quyidagi usullar telefonning **mintaqa sozlamasini** o'zgartiradi.

---

## 🧪 1-qadam: avval tekshiring

Balki telefoningizda bu funksiya allaqachon bordir. Tekshirish 30 soniya:

1. **Telefon** (qo'ng'iroq 📞 belgisi) ilovasini oching
2. **Sozlamalar** ga kiring (yuqori burchakdagi ⋮ yoki ⚙️ tugma)
3. **"Qo'ng'iroqni yozib olish"** (*Call recording / Record calls*) bandini qidiring
4. Bor bo'lsa → **"Avtomatik yozib olish"** ni yoqing

| Natija | Nima qilish |
|:--|:--|
| ✅ Bunday band **bor** | Yoqing — tamom! Boshqa hech narsa kerak emas |
| ❌ Bunday band **yo'q** | Pastdagi o'z brendingiz bo'yicha yo'riqnomaga o'ting |

> [!TIP]
> Avval ilovaning o'z mikrofon yozuvini ham sinab ko'ring — ba'zi telefonlarda
> u ham yetarlicha yaxshi chiqadi va hech narsa o'zgartirish kerak bo'lmaydi.

---

# 🔵 Samsung uchun

Samsung telefonlarida yozib olish funksiyasi **bor**, lekin mintaqaga qarab
o'chirilgan. Uni **SamFW Tool** dasturi orqali yoqamiz.

### 🎬 Video yo'riqnoma

<div align="center">

[![SamFW Tool video](https://img.youtube.com/vi/l0N7QM6uCYc/hqdefault.jpg)](https://youtu.be/l0N7QM6uCYc?t=85)

**[▶️ Videoni ochish](https://youtu.be/l0N7QM6uCYc?t=85)** *(1:25 dan boshlanadi)*

</div>

### 🧰 Nima kerak

- 💻 **Windows kompyuter**
- 🔌 **USB kabel** (ma'lumot uzatadigan, faqat quvvatlash uchun emas)
- 📥 **SamFW Tool** — 👉 **[samfw.com/blog/samfwtool](https://samfw.com/blog/samfwtool)**

> [!WARNING]
> **Avval telefondagi muhim ma'lumotlarni zaxiralang (backup)!**
> Ba'zi hollarda mintaqani o'zgartirish telefonni **zavod holatiga qaytaradi**
> — barcha rasm, kontakt va ilovalar o'chib ketishi mumkin.

### 📋 Bosqichma-bosqich

<details open>
<summary><b>1️⃣ Telefonni tayyorlash — Ishlab chiquvchi rejimi</b></summary>

<br>

1. **Sozlamalar** → **Telefon haqida** → **Dasturiy ta'minot ma'lumoti**
2. **"Yig'ish raqami"** (*Build number*) ustiga **7 marta** ketma-ket bosing
3. "Siz endi ishlab chiquvchisiz" degan xabar chiqadi
4. **Sozlamalar** → **Ishlab chiquvchi parametrlari** ga kiring
5. **USB orqali nosozliklarni tuzatish** (*USB debugging*) — **yoqing** ✅

</details>

<details open>
<summary><b>2️⃣ SamFW Tool ni o'rnatish</b></summary>

<br>

1. [samfw.com/blog/samfwtool](https://samfw.com/blog/samfwtool) saytiga kiring
2. Dasturni yuklab oling va kompyuterga o'rnating
3. Dasturni **administrator nomidan** ishga tushiring
4. Telefonni USB kabel bilan ulang
5. Telefonda **"USB debugging'ga ruxsat berilsinmi?"** so'ralsa — **Ruxsat berish**

</details>

<details open>
<summary><b>3️⃣ Mintaqani (CSC) o'zgartirish</b></summary>

<br>

1. Dasturda **ADB** bo'limiga o'ting
2. **`Get list supported CSC`** tugmasini bosing
3. Chiqqan ro'yxatdan **yozib olishga ruxsat beruvchi** mintaqani tanlang:

| Kod | Mintaqa |
|:--:|:--|
| **INS** | 🇮🇳 Hindiston |
| **XID** | 🇮🇩 Indoneziya |
| **THL** | 🇹🇭 Tailand |
| **XXV** | 🇻🇳 Vetnam |
| **SEK**, **ILO** | Boshqa mos mintaqalar |

4. Tanlangan mintaqani o'rnating va telefonni **qayta ishga tushiring**

</details>

<details>
<summary><b>⚠️ Agar ro'yxatda bu kodlar chiqmasa</b></summary>

<br>

Demak telefoningiz oddiy usul bilan mintaqani almashtira olmaydi. Variantlar:

- 🔧 **Proshivka (majburiy flash)** — kerakli mintaqa proshivkasini to'liq
  o'rnatish. Bu murakkabroq va telefon **albatta tozalanadi**
- 👨‍🔧 **Mutaxassisga topshirish** — servis markazlar bu xizmatni ko'rsatadi
- 📱 **Android GO** modellari va ba'zi eski modellarda bu **umuman imkonsiz**

</details>

### 🏁 Yakuniy qadam

Mintaqa o'zgargandan so'ng:

1. **Telefon** ilovasi → **Sozlamalar** → **Qo'ng'iroqni yozib olish**
2. **"Avtomatik yozib olish"** ni **yoqing** ✅
3. Bitta sinov qo'ng'irog'i qiling va ilovada tinglab ko'ring

---

# 🟠 Xiaomi / Redmi / POCO uchun

Xiaomi da usul **boshqacha** — mintaqani o'zgartirish shart emas. Kompyuter
orqali maxsus **Dialer (Telefon) ilovasi** o'rnatiladi va u yozib olishni ochadi.

> [!IMPORTANT]
> Ichki yozuv **barcha** Xiaomi modellarida yo'q. **Mi A1, Mi A2, Mi A3** va
> **Android GO** modellarida umuman yo'q — ularda faqat mikrofon yozuvi ishlaydi.

### 🧰 Nima kerak

- 💻 **Windows kompyuter**
- 🔌 **USB kabel**
- 📥 **Arxiv fayl** — 👉 **[Yuklab olish](https://t.me/c/3177623007/75)**

> [!NOTE]
> Yuklab olish havolasi **yopiq Telegram kanalida**. Ochilmasa —
> qo'llab-quvvatlash xizmatiga murojaat qiling, fayl yuboriladi.

### 📋 Bosqichma-bosqich

<details open>
<summary><b>1️⃣ Ishlab chiquvchi rejimini yoqish</b></summary>

<br>

1. **Sozlamalar** → **Telefon haqida**
2. **"MIUI versiyasi"** (yoki *HyperOS versiyasi*) ustiga **7 marta** bosing
3. "Siz endi ishlab chiquvchisiz" xabari chiqadi

</details>

<details open>
<summary><b>2️⃣ Kerakli 2 ta sozlamani yoqish</b></summary>

<br>

**Sozlamalar** → **Qo'shimcha sozlamalar** → **Ishlab chiquvchi parametrlari**:

| Sozlama | Holati |
|:--|:--:|
| **USB orqali nosozliklarni tuzatish** (*USB debugging*) | ✅ Yoqilsin |
| **USB orqali ilovalarni o'rnatish** (*Install via USB*) | ✅ Yoqilsin |

> 💡 *"Install via USB"* ni yoqishda Mi-akkauntga kirish va SIM-karta talab
> qilinishi mumkin — bu normal holat, tizim talabi.

</details>

<details open>
<summary><b>3️⃣ Faylni ishga tushirish</b></summary>

<br>

1. Arxivni kompyuterga **yuklab oling**
2. Arxivni **oching** (*Extract / Ochish* — WinRAR yoki 7-Zip orqali)
3. Telefonni USB kabel bilan kompyuterga ulang
4. Ichidagi **`Install_Xiaomi_Dialer.bat`** faylini **ikki marta bosing**
5. Qora oyna (buyruqlar oynasi) ochiladi — **yopmang**, tugashini kuting
6. Telefonda so'rov chiqsa — **Ruxsat berish** / **O'rnatish** ni bosing

</details>

### 🏁 Yakuniy qadam

1. Telefonni **qayta ishga tushiring**
2. **Telefon** ilovasi → **⋮ menyu** → **Sozlamalar** → **Qo'ng'iroqni yozib olish**
3. **"Avtomatik yozib olish"** ni **yoqing** ✅

---

# 🔴 Huawei / Honor uchun

Huawei va Honor telefonlarida (Android 9 dan boshlab) yozib olish moduli
**o'chirilgan**, lekin uni **qayta o'rnatib** yoqish mumkin. Kompyuter kerak emas —
hammasi telefonning o'zida bajariladi.

> [!CAUTION]
> **Faqat o'z versiyangizga mos modulni o'rnating!**
> Noto'g'ri modul yo **o'rnatilmaydi**, yoki o'rnatiladi-yu — telefon
> **noto'g'ri ishlay boshlaydi**. Xato o'rnatilgan bo'lsa: avval uni
> **o'chirib tashlang**, keyin to'g'ri versiyasini o'rnating.

### 1️⃣ Avval versiyangizni aniqlang

**Sozlamalar** → **Telefon haqida** bo'limidan **ikkita** raqamni yozib oling:

| Nima qidiriladi | Qayerda |
|:--|:--|
| **Android versiyasi** | *Android versiyasi* qatori |
| **EMUI** (Huawei) yoki **Magic UI** (Honor) versiyasi | *EMUI versiyasi* / *Magic UI versiyasi* qatori |

> 💡 Huawei da qobiq **EMUI**, Honor da esa **Magic UI** deb ataladi —
> ular bir-biriga mos keladi (EMUI 11 ≈ Magic UI 4.0).

### 2️⃣ Modulni yuklab oling

<div align="center">

| Versiyangiz | Yuklab olish |
|:--|:--:|
| **EMUI 10 / 10.1** *(Magic UI 3.0–3.1)* | **[⬇️ CallRecording 10.1.0](https://www.mediafire.com/file/jfsfu7gf958a32r/CallRecording_10.1.0.apk)** |
| **EMUI 11** *(Magic UI 4.0)* | **[⬇️ CallRecorder EMUI 11](https://www.mediafire.com/file/6ijyld7yz2g7koz/Huawei+CallRecorder+EMUI+11.apk)** |
| **EMUI 12** — 1-variant | **[⬇️ HwCallRecorder 12.0.0.109](https://www.mediafire.com/file/nugzvusdb64s1bb/HwCallRecorder+12.0.0.109_HuaweiAilesi.apk/file)** |
| **EMUI 12** — 2-variant | **[⬇️ CallRecorder EMUI 12](https://www.mediafire.com/file/44jr1hfb3zwszfc/CallRecorder+EMUI+12.apk/file)** |
| **EMUI 13 / 14** | **[⬇️ EMUI13 CallRecorder](https://www.mediafire.com/file/c5zlcdpb6mafqen/EMUI13_CallRecorder.apk/file)** |

</div>

> [!TIP]
> **EMUI 12 uchun ikkita variant bor.** Birinchisi o'rnatilmasa yoki
> ishlamasa — uni o'chirib, **ikkinchisini** sinab ko'ring.
> **EMUI 14** uchun alohida modul yo'q — EMUI 13 niki sinaladi.

> [!NOTE]
> **Android 9**, **Honor Android 12** va **Honor Android 13/14** uchun modullar
> alohida bo'ladi — ular yuqoridagi ro'yxatda yo'q. Kerak bo'lsa
> qo'llab-quvvatlash xizmatidan so'rang.

### 3️⃣ O'rnating

<details open>
<summary><b>O'rnatish bosqichlari</b></summary>

<br>

1. Havoladan **APK faylni telefonga** yuklab oling
2. **Fayllar** ilovasidan yuklangan faylni toping va **bosing**
3. *"Noma'lum manbalardan o'rnatishga ruxsat berilmagan"* chiqsa —
   **Sozlamalar** ga o'ting va brauzer/fayl menejeriga **ruxsat bering**
4. **O'rnatish** tugmasini bosing va tugashini kuting

</details>

### 4️⃣ ⚠️ Ruxsatlarni bering — BU QADAM SHART

> [!IMPORTANT]
> Modul o'rnatilgani bilan **ishlamaydi**, agar unga ruxsatlar berilmasa!
> Bu eng ko'p o'tkazib yuboriladigan qadam.

1. **Sozlamalar** → **Ilovalar** → **Ilovalar** ro'yxati
2. Ro'yxatdan **`Recorder`** (yoki *Qo'ng'iroqlarni yozib olish* / *Запись звонков*) ni toping
3. Uni bosing → **Ruxsatlar** (*Права*)
4. **Berilmagan barcha ruxsatlarni yoqing** ✅ (mikrofon, xotira, telefon, kontaktlar)

### 5️⃣ Yozib olishni yoqing

1. Telefonni **qayta ishga tushiring**
2. **Telefon** ilovasi → **Sozlamalar** → **Qo'ng'iroqlarni yozib olish**
3. **"Avtomatik"** rejimini yoqing ✅

> Honor Android 13 va undan yuqorisida bu menyu **bo'lmasligi** mumkin —
> pastdagi eslatmaga qarang.

---

### 🟡 Honor egalari uchun alohida eslatmalar

<details>
<summary><b>Honor + Android 13 / 14</b></summary>

<br>

Ishlab chiqaruvchi **avtomatik** yozib olishni cheklab qo'ygan — yozuv har
safar **tugma bilan qo'lda** boshlanadi. Modul o'rnatilgach ruxsatlarni
berishni **unutmang** (4-qadam). Avtomatik rejimni ochish uchun qo'shimcha
amallar kerak bo'ladi — qo'llab-quvvatlashga murojaat qiling.

</details>

<details>
<summary><b>Honor + Android 15 — tavsiya etilmaydi ❌</b></summary>

<br>

- Avtomatik yozib olish **cheklangan** — faqat qo'lda tugma orqali
- Aylanma yo'llar bor, lekin **barqaror ishlashi kafolatlanmaydi**
- Telefon **suhbatdoshni yozuv haqida ogohlantirishi** mumkin va buni
  **o'chirib bo'lmaydi**

**Xulosa:** ish uchun Android 15 li Honor telefonini olmaslikni tavsiya qilamiz.

**Avval tekshiring:** qo'ng'iroq qiling va ekranga qarang — **to'lqin
belgisiga o'xshash yozib olish tugmasi** bormi? Bo'lsa, modul allaqachon
o'rnatilgan, qayta o'rnatish shart emas.

</details>

<details>
<summary><b>Android GO modellari</b></summary>

<br>

Android GO versiyasidagi Huawei/Honor telefonlari uchun yozib olish moduli
**umuman mavjud emas**. Bunday telefonlarda faqat mikrofon yozuvi ishlaydi.

</details>

---

## ✅ Yoqilganini qanday bilamiz?

1. Istalgan raqamga **sinov qo'ng'irog'i** qiling, **10–15 soniya** gaplashing
2. Qo'ng'iroqni tugatib, **bir daqiqa kuting** (telefon faylni saqlaydi)
3. Ilovada o'sha qo'ng'iroqni oching va **yozuvni tinglang**

| Eshitilayotgani | Ma'nosi |
|:--|:--|
| 🔊 **Ikkala ovoz ham toza** | 🎉 Ichki yozuv ishlayapti — muvaffaqiyat! |
| 🔉 Faqat **o'z ovozingiz** aniq | Mikrofon yozuvi ishlayapti — ichki yozuv hali yoqilmagan |
| 🔇 Ovoz **yo'q** | Ruxsatlarni tekshiring, keyin qo'llab-quvvatlashga yozing |

> [!TIP]
> Ilovada alohida "ichki yozuvdan foydalanish" tugmasini bosish **kerak emas** —
> ilova ichki yozuvni topsa, **o'zi avtomatik** o'shani tanlaydi.

---

## ❓ Muammolar va yechimlar

<details>
<summary><b>Kompyuter telefonni ko'rmayapti</b></summary>

<br>

- Kabelni almashtiring — ba'zi kabellar **faqat quvvat** uzatadi
- Telefon ekranida USB rejimini **"Fayl uzatish (MTP)"** ga o'zgartiring
- USB debugging **yoqilganini** qayta tekshiring
- Boshqa USB portga ulang (kompyuterning orqa portlari ishonchliroq)

</details>

<details>
<summary><b>Yozuv bor, lekin ilova uni topmayapti</b></summary>

<br>

- Ilovaga **"Barcha fayllarga kirish"** (All files access) ruxsati berilganini
  tekshiring — ichki yozuvni **o'qish uchun shart**
- Ilova sozlamalaridan **"Telefon yozuvlari papkasi"** ni qo'lda ko'rsating
- Telefonda yozuv haqiqatan saqlanayotganini tekshiring — **Fayllar** ilovasi:

| Brend | Papka |
|:--|:--|
| Samsung | `Recordings/Call` |
| Xiaomi | `MIUI/sound_recorder/call_rec` |
| Huawei / Honor | `Sounds/CallRecord` |

</details>

<details>
<summary><b>Huawei: modul o'rnatildi, lekin yozib olish ishlamayapti</b></summary>

<br>

1. **Ruxsatlarni tekshiring** — 90% hollarda sabab shu:
   **Sozlamalar** → **Ilovalar** → `Recorder` → **Ruxsatlar** → hammasini yoqing
2. **Versiya mos kelmagan bo'lishi mumkin** — EMUI versiyangizni qayta
   tekshiring va boshqa variantni sinang (EMUI 12 uchun 2 ta fayl bor)
3. Modulni **o'chirib**, telefonni qayta yoqib, **qaytadan** o'rnating

</details>

<details>
<summary><b>Avtomatik yozib olish menyusi bor, lekin ilova yozuvni ololmayapti</b></summary>

<br>

Ba'zi modellarda yozuv telefon xotirasining **yopiq** joyiga saqlanadi va
ilovalar u yerga kira olmaydi. Bu holda:

- Yozib olish rejimini **"Barcha qo'ng'iroqlar"** ga o'zgartiring
- Yordam bermasa — mintaqani o'zgartirish kerak bo'ladi (Samsung bo'limi)

</details>

<details>
<summary><b>Telefon yangilangandan keyin ishlamay qoldi</b></summary>

<br>

Tizim yangilanishi mintaqa sozlamasini **qaytarib yuborishi** mumkin.
Yo'riqnomani **qaytadan** bajaring. Ish telefonlarida avtomatik
yangilanishni o'chirib qo'yish tavsiya etiladi.

</details>

---

<div align="center">

> [!CAUTION]
> **Bu amallarni o'z mas'uliyatingiz ostida bajarasiz.** Mintaqa o'zgartirish
> va tashqi fayl o'rnatish — telefon kafolatiga ta'sir qilishi yoki
> ma'lumotlar yo'qolishiga olib kelishi mumkin. Ishonchingiz komil bo'lmasa,
> mutaxassisga murojaat qiling.
>
> ⚖️ Qo'ng'iroqni yozib olishda **mahalliy qonunchilikka** rioya qiling —
> ko'p mamlakatlarda suhbatdoshni ogohlantirish talab etiladi.

**Savolingiz bormi?** Qo'llab-quvvatlash xizmatiga murojaat qiling —
telefon **modeli**, **Android versiyasi** va **muammo tavsifi** ni yuboring.

</div>
