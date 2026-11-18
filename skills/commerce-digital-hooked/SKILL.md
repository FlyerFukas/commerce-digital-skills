---
name: commerce-digital-hooked
description: "Nir Eyal'in \"Hooked: Alışkanlık Oluşturan Ürünler Nasıl Oluşturulur\" kitabından çıkarılmış uygulama kılavuzu. Kullanıcı alışkanlığı tasarlamak, retention/DAU artırmak, onboarding ve bildirim stratejisi kurmak, tetikleyici-eylem-değişken ödül-yatırım (Hook Model) döngüsü kurgulamak, habit testing yapmak veya bir ürünün neden tekrar kullanılmadığını teşhis etmek gerektiğinde kullan. Triggers: kanca modeli, hook model, alışkanlık, habit-forming, retention, engagement, bildirim, onboarding, değişken ödül, variable reward, B=MAT, Fogg."
---

<!-- argument-hint: [konu, framework adı veya bölüm numarası] -->

# Hooked — Alışkanlık Oluşturan Ürünler Nasıl Oluşturulur?
**Yazar**: Nir Eyal (Ryan Hoover ile) | **Bölüm**: 8 | **Kaynak**: Türkçe tam metin | **Üretim**: 2026-09-12
**Commerce Digital serisi** — kardeş beceriler: [[commerce-digital-cialdini]], [[commerce-digital-kahneman]], [[commerce-digital-ariely]], [[commerce-digital-sutherland]]

## Bu Beceriyi Nasıl Kullanırım

- **Argümansız** — Kanca Modeli'nin dört aşamasını ve teşhis sorularını yükler
- **Konu ile** — `tetikleyici`, `değişken ödül`, `yatırım`, `onboarding`, `bildirim`, `etik` de; ilgili bölüm dosyası okunur
- **Bölüm ile** — `ch04` gibi; o bölüm yüklenir
- **Teşhis modu** — "ürünüm tekrar kullanılmıyor" de; [cheatsheet.md](cheatsheet.md) teşhis ağacı çalıştırılır

---

## Çekirdek Çerçeve: Kanca Modeli (Hook Model)

Dört aşamalı bir döngü. Her tam tur, kullanıcının sorununu senin çözümüne biraz daha bağlar.
**Döngü sayısı arttıkça alışkanlık güçlenir.** Tek seferlik dönüşüm değil, ardışık döngü tasarlıyorsun.

```
TETİKLEYİCİ → EYLEM → DEĞİŞKEN ÖDÜL → YATIRIM ─┐
      ↑                                          │
      └──────── (sonraki tetikleyiciyi yükler) ──┘
```

### 1. Tetikleyici (Trigger) — davranışın bujisi
- **Harici tetikleyici**: Kullanıcının çevresine yerleştirilen, "bir sonraki adımda ne yap" bilgisini taşıyan uyaran.
  Dört tür: **Ücretli** (reklam — yeni kullanıcı için, retention için sürdürülemez) · **Kazanılmış** (basın, viral, App Store öne çıkarma — kısa ömürlü) · **İlişki** (davet, paylaşım, ağızdan ağıza — viral hiper büyüme) · **Sahipli** (uygulama ikonu, push, e-posta bülteni — **tek tekrar-etkileşim motoru**, çünkü sadece kullanıcı izin verdiyse görünür).
- **Dahili tetikleyici**: Kullanıcının hafızasında kodlanmış çağrışım. Görülmez, duyulmaz — zihinde otomatik doğar.
  **Çoğu dahili tetikleyici olumsuz duygudur**: can sıkıntısı, yalnızlık, hayal kırıklığı, kafa karışıklığı, kararsızlık, FOMO. Bunlar "acı" değil **kaşıntıdır** — tatmin edilene kadar rahatsızlık veren his.
- **Hedef**: Harici tetikleyicilerden dahili tetikleyicilere geçiş. Alışkanlık oluştuğunda push'a ihtiyaç kalmaz.
- **Bulma yöntemi**: **5 Neden Yöntemi** (Toyota / Taiichi Ohno). Duyguya ulaşana kadar "neden?" sor — genellikle 5. nedende çıkar.

### 2. Eylem (Action) — ödül beklentisiyle yapılan en basit davranış
**Fogg Davranış Modeli: B = MAT** — Davranış = Motivasyon × Yetenek × Tetikleyici, üçü **aynı anda ve yeterli derecede**.
Biri eksikse kullanıcı "Eylem Çizgisi"ni geçmez.

- **Üç Temel Motivatör** (her biri iki yönlü kaldıraç): haz arama / acıdan kaçınma · umut arama / korkudan kaçınma · sosyal kabul arama / reddedilmeden kaçınma.
- **Basitliğin altı unsuru** (Yetenek): **Zaman · Para · Fiziksel Çaba · Beyin Döngüleri · Sosyal Sapkınlık · Rutin Olmama**.
- **KURAL: Her zaman yetenekle başla, motivasyonla değil.** Motivasyon artırmak pahalı ve yavaş; sürtünme azaltmak en yüksek ROI'li müdahale. Kullanıcının *o andaki en kıt kaynağını* bul ve orayı düzelt.

### 3. Değişken Ödül (Variable Reward) — kancayı geri bildirim döngüsünden ayıran şey
Öngörülebilir ödül arzu yaratmaz (buzdolabı ışığı). **Değişkenlik**, nucleus accumbens'i **ödülün kendisinde değil, beklentisinde** aktive eder (Knutson). Bizi iten, ödülün verdiği his değil, **özlemi hafifletme ihtiyacıdır**.

Üç tür (bir üründe birden fazlası olabilir — e-posta üçünü birden kullanır):
- **Kabilenin Ödülleri** — sosyal: kabul, onay, statü, dahil olma. (Beğeni, yorum, oy, rozet, Onur Puanı)
- **Avın Ödülleri** — kaynak/bilgi arayışı. (Feed, sonsuz kaydırma, slot makinesi, arama sonuçları)
- **Benliğin Ödülleri** — içsel: ustalık, yetkinlik, tamamlama. (Seviye atlama, inbox zero, ilerleme çubuğu)

**Üç kritik uyarı:**
1. **Ödül, kullanıcının gerçek kaşıntısıyla eşleşmeli.** Mahalo para verdi ve öldü; Quora sosyal onay verdi ve büyüdü. Oyunlaştırma tek başına bir şey kurtarmaz.
2. **Özerkliği koru.** Özerklik tehdit edilince "tepkisellik" (reactance) doğar ve kullanıcı isyan eder (Quora "views" fiyaskosu, MyFitnessPal → "MyFitnessPain"). "Ama kabul etmekte ya da reddetmekte özgürsünüz" ifadesi 42 çalışmalık meta-analizde "evet" oranını **ikiye katlıyor**.
3. **Sonlu vs. Sonsuz Değişkenlik.** Sonlu değişkenlik zamanla öngörülebilir olur ve ölür (FarmVille, Zynga'nın %80 değer kaybı; bitmiş bir dizi). Sonsuz değişkenlik kullanıcı üretimli içerikten/başkalarının davranışından gelir (World of Warcraft, YouTube, Dribbble). İçerik **tüketimi** sonlu, içerik **üretimi** sonsuzdur.

### 4. Yatırım (Investment) — kullanıcının işi yaptığı yer
Eylem Aşaması'nın tersine **sürtünmeyi kasten artırır**. Anlık tatmin değil, **gelecekteki ödül beklentisi**.
**ZAMANLAMA KRİTİK: yatırımı ödülden SONRA iste, önce değil.**

Neden işe yarar — üç psikolojik eğilim:
- **IKEA Etkisi** — emeğimize mantıksız değer biçeriz. Origami deneyi: yapanlar kendi eserlerine **5 kat** fazla değer verdi.
- **Geçmiş davranışla tutarlılık** — küçük taahhüt büyüğünü açar. Tabela deneyi: %17 → **%76**.
- **Bilişsel uyumsuzluktan kaçınma** — harcadığımız zamanı haklı çıkarmak için tercihimizi değiştiririz (rasyonalizasyon).

**Depolanan Değer** (geçmeyi zorlaştırır): İçerik · Veri · Takipçiler · İtibar · Beceri.
**Sonraki Tetikleyiciyi Yükleme**: Yatırım, gelecekteki harici tetikleyiciyi kurar (Any.do takvim izni → toplantı sonrası bildirim).

---

## Alışkanlık Bölgesi ve Strateji Eşiği

Bir davranışın alışkanlığa dönüşmesi iki eksene bağlı: **Sıklık** × **Algılanan Fayda**.
- Yeterince sık olmayan davranış, faydası ne olursa olsun **asla** otomatikleşmez.
- Asgari faydalı bir davranış bile, sadece sık olduğu için alışkanlık olabilir.
- Google = yüksek sıklık / düşük göreli fayda. Amazon = düşük sıklık / çok yüksek algılanan fayda. İkisi de Alışkanlık Bölgesi'nde.
- **Gourville kuralı**: Yeni ürün, yerleşik alışkanlığı kırmak için sadece daha iyi değil **9 kat daha iyi** olmalı.

**Vitamin mi Ağrı Kesici mi?** Cevap: **ikisi de**. Alışkanlık yaratan ürünler vitamin gibi başlar (olsa güzel), alışkanlık kurulduktan sonra ağrı kesiciye dönüşür — çünkü **alışkanlık, eylemi yapmamanın biraz acı vermesidir**.

**Alışkanlığın iş değeri**: ↑ CLTV · ↑ fiyatlandırma esnekliği (Buffett/Munger) · süper güçlendirilmiş büyüme (Viral Döngü Süresi: 2 günden 1 güne inince 20 günde 20.470 → 20.000.000 kullanıcı) · keskinleşmiş rekabet avantajı.

---

## Etik Sınır: Manipülasyon Matrisi

İki soru: **(1) Bu ürünü kendim kullanır mıydım? (2) Kullanıcıların hayatını maddi olarak iyileştirir mi?**

| | Kendim kullanırım | Kullanmam |
|---|---|---|
| **Hayatı iyileştirir** | **Kolaylaştırıcı** — en yüksek başarı şansı | **Seyyar Satıcı** — empati yok, genellikle başarısız |
| **İyileştirmez** | **Şovmen** — başarılı olabilir, kalıcı güç yok | **Satıcı (sömürü)** — en düşük şans, ahlaken tehlikeli |

Soruları yanıtlarken kıvranıyor ve gerekçelendirme ihtiyacı duyuyorsan **DUR — başarısız oldun**.
Matris "kandırabilir miyim?"e değil, **"kandırmaya çalışmalı mıyım?"a** cevap verir.
Ayrıntı + güncel yasal çerçeve (AB DSA karanlık desen yasağı, KVKK): [chapters/ch06-manipulasyon-matrisi.md](chapters/ch06-manipulasyon-matrisi.md)

---

## Bölüm Dizini

| # | Başlık | Temel Çerçeveler |
|---|--------|------------------|
| ch01 | Alışkanlık Bölgesi | Alışkanlık Bölgesi, Vitamin/Ağrı Kesici, Gourville 9x, CLTV |
| ch02 | Tetikleyici | Harici/Dahili tetikleyici, 4 harici tür, 5 Neden Yöntemi |
| ch03 | Eylem | B=MAT, Üç Temel Motivatör, Basitliğin 6 Unsuru, sezgisel yöntemler |
| ch04 | Değişken Ödül | Kabile/Av/Benlik, sonlu-sonsuz değişkenlik, özerklik & tepkisellik |
| ch05 | Yatırım | IKEA Etkisi, depolanan değer, sonraki tetikleyiciyi yükleme |
| ch06 | Bununla Ne Yapacaksın? | Manipülasyon Matrisi, karanlık desenler, yasal sınırlar |
| ch07 | Vaka: İncil Uygulaması | Kanca'nın uçtan uca uygulanması |
| ch08 | Alışkanlık Testi | Tanımla-Kodla-Değiştir, Alışkanlık Yolu, %5 kuralı, fırsat avı |

## Konu Dizini

- **%5 kuralı** → ch08 · **5 Neden Yöntemi** → ch02 · **Alışkanlık Bölgesi** → ch01
- **Alışkanlık Yolu** → ch08 · **Arayüz değişikliği** → ch08 · **Av ödülleri** → ch04
- **B=MAT / Fogg** → ch03 · **Bağışlanan ilerleme** → ch03 · **Beceri (depolanan değer)** → ch05
- **Benlik ödülleri** → ch04 · **Bildirim/push** → ch02, ch05 · **Bilişsel uyumsuzluk** → ch05
- **Çerçeveleme** → ch03 · **Dahili tetikleyici** → ch02 · **Demirleme (anchoring)** → ch03
- **Değişken ödül** → ch04 · **Etik / Manipülasyon Matrisi** → ch06 · **FOMO** → ch02
- **Freemium** → ch01 · **Gourville 9x** → ch01 · **IKEA Etkisi** → ch05
- **İtibar** → ch05 · **Kabile ödülleri** → ch04 · **Karanlık desen** → ch02, ch06
- **Kıtlık etkisi** → ch03 · **Kohort analizi** → ch08 · **Onboarding** → ch03, ch05, ch08
- **Oyunlaştırma (sınırları)** → ch04 · **Özerklik / tepkisellik** → ch04 · **Retention** → ch01, ch08
- **Sahipli tetikleyici** → ch02 · **Sonsuz kaydırma** → ch03, ch04 · **Sonlu değişkenlik** → ch04
- **Takipçi** → ch05 · **Viral Döngü Süresi** → ch01 · **Vitamin/Ağrı Kesici** → ch01
- **Yatırım zamanlaması** → ch05

## Destek Dosyaları

- [patterns.md](patterns.md) — uygulanabilir ürün desenleri (ne zaman, nasıl, ödünleşimler)
- [cheatsheet.md](cheatsheet.md) — karar kuralları, teşhis ağacı, eşik değerler
- [glossary.md](glossary.md) — tüm terimler

## Kapsam ve Sınırlar

Bu beceri kitabın içeriğini kapsar. Kitap 2014 tarihlidir: Kanca Modeli hâlâ geçerlidir ama
**yasal ortam değişti** — AB Dijital Hizmetler Yasası m.25 karanlık desenleri yasaklıyor, KVKK
açık rıza istiyor. ch06'daki güncel sınırları oku. Bilişsel önyargıların derinliği için
[[commerce-digital-kahneman]] ve [[commerce-digital-ariely]], ikna taktikleri için
[[commerce-digital-cialdini]] becerilerine geç.
