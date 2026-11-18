---
name: commerce-digital-kahneman
description: "Daniel Kahneman'ın \"Thinking, Fast and Slow\" kitabından çıkarılmış uygulama kılavuzu. Fiyat çapası kurmak, kayıp/kazanç çerçevelemesi yazmak, varsayılan (default) tasarlamak, deneyim akışını (onboarding, iptal, destek) zirve-son kuralına göre kurgulamak, A/B testi ve veri yorumunu regresyon/küçük sayılar yanılgısına karşı denetlemek, ekip tahminlerini planlama yanılgısından korumak gerektiğinde kullan. Triggers: Kahneman, bilişsel önyargı, cognitive bias, Sistem 1, Sistem 2, çerçeveleme, framing, çapa, anchoring, kayıp kaçınma, loss aversion, beklenti teorisi, prospect theory, sahiplik etkisi, endowment, zirve-son, peak-end, WYSIATI, planlama yanılgısı, zihinsel muhasebe, varsayılan, default, nudge."
---

<!-- argument-hint: [önyargı adı, konu veya bölüm numarası] -->

# Thinking, Fast and Slow — Hızlı ve Yavaş Düşünme
**Yazar**: Daniel Kahneman | **Kaynak kitap**: 5 kısım, 38 bölüm | **Bu beceri**: 11 tematik bölüm | **Üretim**: 2026-09-12
**Commerce Digital serisi** — kardeş beceriler: [[commerce-digital-hooked]], [[commerce-digital-cialdini]], [[commerce-digital-ariely]], [[commerce-digital-sutherland]]

> **Yapı notu**: Kitabın 38 bölümü, ticari uygulanabilirliğe göre 11 tematik dosyada kümelenmiştir. Her dosya hangi kaynak bölümleri kapsadığını başlığında belirtir.

## Bu Beceriyi Nasıl Kullanırım

- **Argümansız** — İki sistem, WYSIATI ve ticari olarak en yüksek getirili altı önyargıyı yükler
- **Önyargı ile** — `çapa`, `kayıp kaçınma`, `zirve-son`, `çerçeveleme` de
- **Denetim modu** — "bu fiyatlandırma sayfasını önyargı açısından denetle" veya "bu A/B test sonucunu değerlendir" de; [cheatsheet.md](cheatsheet.md) kullanılır
- **Kendi kararını denetlemek için** — "bu tahmini planlama yanılgısına karşı kontrol et"

---

## Çekirdek Çerçeve: İki Sistem

| | **Sistem 1** | **Sistem 2** |
|---|---|---|
| Çalışma biçimi | Otomatik, hızlı, çabasız, istemsiz | Yavaş, çabalı, seçici dikkat gerektirir |
| Ne yapar | Sezgi, izlenim, duygu, örüntü tanıma, çağrışım | Hesap, karşılaştırma, kural uygulama, öz-denetim |
| Zayıflığı | Sistematik ve **öngörülebilir** hatalar | **Tembel** — Sistem 1'in önerisini çoğunlukla onaylar |
| Kim karar verir | Kararların çoğu | Sadece Sistem 1 zorlandığında |

**Ticari çıkarım**: Kullanıcıların kararlarının çoğu Sistem 1'de alınır. Ürün tasarımının işi Sistem 2'yi ikna etmek değil — **Sistem 1'in gördüğü sahneyi düzenlemektir.**

### İki kritik meta-ilke

**1. WYSIATI — "What You See Is All There Is"** (Gördüğün her şeydir)
Sistem 1, eldeki bilgiyle tutarlı bir hikâye kurar ve **eksik bilgiyi hesaba katmaz**. Güvenin kaynağı bilginin *miktarı* değil, kurulan hikâyenin *tutarlılığıdır*.
→ **Az ve tutarlı bilgi, çok ve çelişkili bilgiden daha ikna edicidir.** (Ve bu yüzden tehlikelidir.)

**2. Yerine Koyma (Substitution)**
Zor bir soru sorulduğunda Sistem 1 sessizce **daha kolay bir soruyla değiştirir** ve onu yanıtlar.
- "Bu yazılım şirketimize uygun mu?" → "Bu web sitesi bana güven veriyor mu?"
- "Bu yatırım iyi mi?" → "Bu şirketi seviyor muyum?" (**duygu sezgiseli / affect heuristic**)
→ Kullanıcın senin sorduğun soruyu yanıtlamıyor; **yerine koyduğu kolay soruyu** yanıtlıyor. O soruyu tasarla.

---

## Ticari Olarak En Yüksek Getirili Altı Mekanizma

### 1. Çapalama (Anchoring) — ch04
Herhangi bir sayı, sonraki tahmini kendine çeker. **Rastgele ve açıkça anlamsız sayılar bile çalışır.**
- **Çapalama endeksi** = (tahmin farkı / çapa farkı). Tipik değer **%55**.
- Emlakçı deneyi: Gerçek bir evi değerleyen **profesyonel emlakçılarda %41**; hiç deneyimi olmayan işletme öğrencilerinde **%48**. Tek fark: öğrenciler etkilendiklerini kabul etti, profesyoneller inkâr etti.
- **Campbell çorbası deneyi** (Sioux City): Rafta "kişi başı en fazla 12 adet" yazarken alışveriş yapanlar ortalama **7 kutu**, sınır yokken bunun **yarısı** kadar aldı.

### 2. Kayıp Kaçınma (Loss Aversion) — ch08
**Kayıplar kazançlardan daha büyük görünür.** Kayıp kaçınma oranı deneylerde tipik olarak **1.5 – 2.5** aralığında.
→ 100 TL kaybetme riskini dengelemek için çoğu insanın istediği kazanç: ~200 TL.
→ Aynı teklifi "kazan" yerine "kaybetme" olarak çerçevelemek, davranış üzerinde ~2x etki farkı yaratır.

### 3. Çerçeveleme (Framing) — ch10
Mantıken **aynı** olan iki ifade farklı tercihler üretir. "%90 hayatta kalma oranı" ile "%10 ölüm oranı" aynı bilgidir, aynı kararı üretmez.

### 4. Varsayılanlar (Defaults) — ch10
Varsayılan seçenek, referans noktasını belirler ve ondan sapmak **kayıp** gibi hissedilir. Organ bağışı örneği: opt-in ülkelerde katılım oranı düşük, opt-out ülkelerde neredeyse %100 — mevzuat metni değil, **hangi kutunun önceden işaretli olduğu** belirliyor.

### 5. Zirve-Son Kuralı + Süre İhmali — ch11
**Bir deneyimin hatırlanan değeri, zirve anı ile son anının ortalamasıdır. Süre neredeyse hiç sayılmaz.**
- Soğuk el deneyi: 90 saniyelik (son 30 saniyesi hafifçe daha ılık) deneyimi tekrar etmeyi seçenler, 60 saniyelik olanı değil — acının azaldığını bildirenlerin **%80'i** daha uzun ve toplamda daha acılı olanı seçti.
→ **Deneyimin toplam kalitesi değil, zirvesi ve bitişi hatırlanır ve kararı belirler.**

### 6. Bilişsel Akıcılık (Cognitive Ease) — ch02
İşlemesi kolay olan şey **daha doğru, daha tanıdık, daha hoş ve daha güvenilir** hissettirir.
- Zihinsel rahatlık hâlinde: iyi ruh hâli, gördüğünü sevme, duyduğuna inanma, sezgiye güvenme, **yüzeysel düşünme**.
- Zihinsel zorlanma hâlinde: uyanık ve şüpheci olma, daha çok çaba, **daha az hata** — ama daha az sezgisel ve yaratıcı.
→ Kötü yazı tipi, silik renk, karmaşık dil = kullanıcıyı Sistem 2'ye iter, güveni düşürür.
→ **Tersi de doğru**: Bir şeyin dikkatlice okunmasını istiyorsan (yasal metin, riskli işlem onayı) **akıcılığı kasten azalt**.

---

## Bölüm Dizini

| # | Başlık | Kaynak bölümler | Temel kavramlar |
|---|--------|---|---|
| ch01 | İki Sistem | 1–4 | Sistem 1/2, dikkat ve çaba, tembel denetleyici, çağrışımsal makine, priming |
| ch02 | Bilişsel Akıcılık | 5–6 | Akıcılık, tanıdıklık yanılsaması, doğruluk yanılsaması, normlar ve sürprizler |
| ch03 | WYSIATI ve Yerine Koyma | 7–9 | Sonuca atlama makinesi, hale etkisi, duygu sezgiseli, yoğunluk eşleştirme |
| ch04 | Çapalar | 11 | Çapalama endeksi, ayarlama, priming olarak çapa, pazarlık |
| ch05 | Erişilebilirlik ve Duygu | 12–13 | Availability, availability cascade, risk politikası, uzman-halk uçurumu |
| ch06 | İstatistik Körlüğü | 10, 14–18 | Küçük sayılar yasası, taban oran, Linda, ortalamaya regresyon, sezgisel tahmini evcilleştirme |
| ch07 | Aşırı Güven ve Anlatı | 19–24 | Anlama yanılsaması, geçerlilik yanılsaması, formüller, dış görüş, planlama yanılgısı |
| ch08 | Beklenti Teorisi ve Kayıp Kaçınma | 25–28 | Referans noktası, azalan duyarlılık, kayıp kaçınma, sahiplik etkisi, negatiflik üstünlüğü |
| ch09 | Karar Ağırlıkları | 29–31 | Olasılık/kesinlik etkisi, dörtlü örüntü, nadir olaylar, dar çerçeveleme, risk politikası |
| ch10 | Zihinsel Muhasebe ve Çerçeveleme | 32–34 | Zihinsel hesaplar, disposition etkisi, batık maliyet, pişmanlık, tercih tersinmesi, varsayılanlar |
| ch11 | İki Benlik ve Zirve-Son | 35–38 | Deneyimleyen/hatırlayan benlik, zirve-son, süre ihmali, odaklanma yanılsaması |

## Konu Dizini

- **Availability cascade** → ch05 · **Batık maliyet** → ch10 · **Beklenti teorisi** → ch08
- **Bilişsel akıcılık** → ch02 · **Çapalama** → ch04 · **Çerçeveleme** → ch10
- **Dar çerçeveleme (narrow framing)** → ch09 · **Dış görüş (outside view)** → ch07
- **Dörtlü örüntü (fourfold pattern)** → ch09 · **Duygu sezgiseli (affect heuristic)** → ch03, ch05
- **Erişilebilirlik (availability)** → ch05 · **Geçerlilik yanılsaması** → ch07
- **Hale etkisi** → ch03 · **İkame / Yerine koyma** → ch03 · **Kayıp kaçınma** → ch08
- **Kesinlik etkisi** → ch09 · **Küçük sayılar yasası** → ch06 · **Odaklanma yanılsaması** → ch11
- **Olasılık etkisi** → ch09 · **Ortalamaya regresyon** → ch06 · **Payda ihmali** → ch09
- **Pişmanlık** → ch10 · **Planlama yanılgısı** → ch07 · **Premortem** → ch07
- **Priming** → ch01 · **Referans noktası** → ch08 · **Risk politikası** → ch09
- **Sahiplik etkisi (endowment)** → ch08 · **Süre ihmali** → ch11 · **Sistem 1 / Sistem 2** → ch01
- **Taban oran (base rate)** → ch06 · **Tembel denetleyici** → ch01 · **Tercih tersinmesi** → ch10
- **Varsayılan (default)** → ch10 · **WYSIATI** → ch03 · **Zihinsel muhasebe** → ch10
- **Zirve-son kuralı** → ch11

## Destek Dosyaları

- [patterns.md](patterns.md) — ürün ve pazarlamada uygulanabilir desenler
- [cheatsheet.md](cheatsheet.md) — karar kuralları, eşik değerler, denetim listeleri
- [glossary.md](glossary.md) — tüm terimler

## Kapsam ve Sınırlar

Kahneman'ın kitabı bir **etki aracı değil, bir teşhis aracıdır**. Kitap önyargıları "nasıl sömürülür" diye değil, "nasıl fark edilir" diye anlatır. Bu beceri her iki yönü de içerir — ama iki uyarı:
1. **Kendi kararlarına da uygula.** Kitabın en değerli kısmı ticari uygulamalar değil, ch06 ve ch07'deki **veri yorumlama ve tahmin disiplini**dir. A/B test sonuçlarını küçük sayılar yasası ve regresyon açısından denetlemeden kabul etme.
2. **Önyargıyı sömürmek ile hizalamak farklıdır.** Aynı çapalama mekanizması hem adil fiyat iletişimi hem de aldatıcı fiyat için kullanılabilir. Sınır için [[commerce-digital]] etik çerçevesine ve ch06'daki AB DSA notlarına bak.
