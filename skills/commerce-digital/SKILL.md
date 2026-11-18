---
name: commerce-digital
description: "COMMERCE DIGITAL — dijital ticaret ve ürün psikolojisi kütüphanesinin ana girişi. Beş kitaptan (Hooked, Influence, Thinking Fast and Slow, Akıldışı Ama Öngörülebilir, Alchemy) çıkarılmış beş uzman becerinin yönlendiricisi ve ortak etik/yasal çerçevesi. Bir dönüşüm, retention, fiyatlandırma, onboarding, bildirim, iptal akışı, deneyim tasarımı veya kullanıcı davranışı problemi geldiğinde ÖNCE bunu çağır — doğru kitaba yönlendirir ve birden fazlasını birlikte kullanmanı sağlar. Triggers: commerce digital, dijital ticaret, kullanıcı psikolojisi, davranışsal tasarım, behavioral design, dönüşüm, CRO, retention, churn, fiyatlandırma, onboarding, ikna, nudge, karanlık desen, dark pattern, growth."
---

<!-- argument-hint: [problem tanımı, kitap adı veya konu] -->

# COMMERCE DIGITAL
### Dijital Ticaret ve Ürün Psikolojisi Kütüphanesi

**Amaç**: Bir probleme yönelik çözümü, insan psikolojisinin gerçek çalışma biçimine göre tasarlamak — kullanıcıyı ürünü daha çok ve daha derinlemesine kullanmaya yöneltmek.
**Kapsam**: Beş kitap, beş uzman beceri, ortak bir etik ve yasal çerçeve.
**Üretim**: 2026-09-12

---

## Kütüphane

| Beceri | Kitap | Ne için |
|---|---|---|
| [[commerce-digital-hooked]] | **Hooked** — Nir Eyal | **Alışkanlık ve retention.** Kanca Modeli, tetikleyici, değişken ödül, yatırım, habit testing |
| [[commerce-digital-cialdini]] | **Influence** — Robert Cialdini | **İkna ve dönüşüm.** Altı ilke: karşılıklılık, tutarlılık, sosyal kanıt, sevme, otorite, kıtlık |
| [[commerce-digital-kahneman]] | **Thinking, Fast and Slow** — Daniel Kahneman | **Karar mimarisi.** Sistem 1/2, çapa, çerçeveleme, kayıp kaçınma, varsayılan, zirve-son. **Ayrıca: kendi veri ve tahmin disiplinin** |
| [[commerce-digital-ariely]] | **Akıldışı Ama Öngörülebilir** — Dan Ariely | **Fiyatlandırma ve teklif.** Tuzak seçenek, BEDAVA!, sosyal/piyasa normları, sahiplik, plasebo fiyat |
| [[commerce-digital-sutherland]] | **Alchemy** — Rory Sutherland ⚠️ *kısmi kaynak* | **Sezgiye aykırı çözüm.** Psiko-mantık, kelebek etkisi avı, aşırı rasyonalizme karşı denge |

> ⚠️ **Sutherland becerisi kısmi kaynağa dayanır** (yayıncı örneği, 21 sayfa). Merkez tez ve yöntem tam; 1–7. bölümler yok. Detay: o becerinin `kitap-haritasi.md` dosyası.

---

## Problem → Kitap Yönlendirici

```
Problem ne?
│
├── KULLANICI GELMİYOR (edinim)
│     → cialdini (ikna, güven sinyalleri, sosyal kanıt)
│     → sutherland (mantıklı mesaj tükendiyse, sezgiye aykırıyı test et)
│
├── KULLANICI GELİYOR AMA DÖNÜŞMÜYOR
│     → cialdini (ch01 kontrast, ch04 sosyal kanıt, ch06 otorite, ch07 kıtlık)
│     → kahneman (ch02 akıcılık, ch03 WYSIATI, ch04 çapa, ch10 çerçeveleme/varsayılan)
│     → ariely (ch01 tuzak seçenek, ch03 BEDAVA!)
│
├── FİYAT / PAKET SORUNU
│     → ariely ⭐ (ch01, ch02, ch03, ch10) — bu kitabın asıl alanı
│     → kahneman (ch04 çapa, ch08 kayıp kaçınma, ch10 çerçeveleme)
│     → cialdini (ch01 kontrast ilkesi)
│
├── DÖNÜŞÜYOR AMA GERİ GELMİYOR (retention)
│     → hooked ⭐ (Kanca Modeli'nin tamamı) — bu kitabın asıl alanı
│     → kahneman (ch11 zirve-son: onboarding, destek, iptal akışları)
│
├── ONBOARDING / AKTİVASYON
│     → hooked (ch03 B=MAT, ch05 yatırım, ch08 Alışkanlık Yolu)
│     → cialdini (ch03 mikro-taahhüt merdiveni)
│     → kahneman (ch11 erken "aha" zirvesi)
│
├── CHURN / İPTAL
│     → kahneman ⭐ (ch11 zirve-son: son anı her şeyi belirler)
│     → ariely (ch08 "dondur" seçeneği, ch06 erteleme)
│     → hooked (ch05 depolanan değer)
│
├── KULLANICI KATKISI / TOPLULUK / REFERANS
│     → ariely ⭐ (ch04 sosyal vs. piyasa normları — "ya anlamlı para ya hiç para")
│     → hooked (ch04 kabile ödülleri)
│     → cialdini (ch05 Tupperware yapısı)
│
├── DENEY SONUCU / VERİ YORUMU / TAHMİN
│     → kahneman ⭐ (ch06 küçük sayılar + regresyon, ch07 dış görüş + premortem)
│     → ariely (ch13 sıra etkisi — bağımsız yargıyı eşzamanlı topla)
│
├── MANTIKLI ÇÖZÜMLER TÜKENDİ
│     → sutherland ⭐ (bulaşık makinesi testi, kelebek etkisi avı, tersini test et)
│
└── "BU TASARIM ETİK Mİ / YASAL MI?"
      → Aşağıdaki ortak çerçeve + hooked ch06 (Manipülasyon Matrisi)
```

---

## Beş Kitabın Birleşik Haritası

Aynı mekanizma farklı kitaplarda farklı adlarla anlatılıyor. Bir konuda derinleşirken bu tabloyu kullan:

| Mekanizma | Hooked | Cialdini | Kahneman | Ariely | Sutherland |
|---|---|---|---|---|---|
| **Otomatik/hızlı düşünme** | Alışkanlık | Click-whirr, tetikleyici özellik | Sistem 1 | — | Psiko-mantık |
| **Referans noktası / karşılaştırma** | Kıtlık etkisi, çerçeveleme (ch03) | Kontrast İlkesi (ch01) | Çapa (ch04), referans noktası (ch08) | İzafiyet (ch01), keyfi tutarlılık (ch02) | Bağlam |
| **Kayıp > kazanç** | — | Kıtlık, tepkisellik (ch07) | Kayıp kaçınma 1.5–2.5 (ch08) | BEDAVA! (ch03), sahiplik (ch07) | — |
| **Sahiplik / emek** | Yatırım, depolanan değer (ch05) | Taahhüt ve tutarlılık (ch03) | Sahiplik etkisi (ch08) | IKEA etkisi, sanal sahiplik (ch07) | — |
| **Sosyal onay** | Kabile ödülleri (ch04) | Sosyal kanıt (ch04), Sevme (ch05) | — | Sosyal normlar (ch04) | — |
| **Otorite / güven sinyali** | — | Otorite (ch06) | Hale etkisi (ch03), akıcılık (ch02) | Plasebo fiyat (ch10) | Sinyalleme *(kaynakta yok)* |
| **Beklenti deneyimi değiştirir** | Çerçeveleme, şarap fMRI (ch03) | Pahalı = iyi (ch01) | Priming (ch01), akıcılık (ch02) | Beklentiler (ch09), fiyatın gücü (ch10) | Algılanan değer, kaliteli zarf |
| **Değişkenlik / belirsizlik** | Değişken ödül (ch04) | — | Karar ağırlıkları (ch09) | — | Öngörülebilir olma |
| **Özerklik ihlali → direnç** | Tepkisellik, "ama sen özgürsün" (ch04) | Psikolojik tepkisellik (ch07) | — | Kapıları açık tutmak (ch08) | — |
| **Varsayılan gücü** | Sahipli tetikleyici (ch02) | — | Varsayılan (ch10) ⭐ | Erteleme, ön-taahhüt (ch06) | — |
| **Zirve ve son** | Değişken ödül zirveleri | Öğle Yemeği Tekniği (ch05) | Zirve-son + süre ihmali (ch11) ⭐ | — | — |
| **Az > çok** | Tek CTA (ch02) | — | WYSIATI (ch03), "az çoktur" (ch10) | Kapıları açık tutmak (ch08) | Önemsiz olmaya cesaret |
| **Etik sınır** | Manipülasyon Matrisi (ch06) ⭐ | Sahte tetikleyici (ch08) | Varsayılanın yasal sınırı (ch10) | Deneme tuzağı, jeton ekonomisi | — |

---

## Birleşik Kullanım: Bir Kanca Döngüsünü Beş Kitapla Kurmak

| Aşama | Hooked | Diğer kitaplardan katkı |
|---|---|---|
| **Tetikleyici** | Sahipli tetikleyici, 5 Neden | **Cialdini**: "çünkü" gerekçesi, tek CTA · **Kahneman**: bağlamsal zamanlama, akıcılık |
| **Eylem** | B=MAT, 6 basitlik unsuru | **Kahneman**: akıcılığı artır (ch02), varsayılanı ayarla (ch10) · **Ariely**: seçenek azalt (ch08) |
| **Değişken Ödül** | Kabile / Av / Benlik | **Cialdini**: sosyal kanıt segmentasyonu (ch04) · **Kahneman**: zirve tasarımı (ch11) |
| **Yatırım** | Ödülden sonra iste, depolanan değer | **Cialdini**: mikro-taahhüt, dört koşul (ch03) · **Ariely**: IKEA etkisi (ch07) · **Kahneman**: geri alınabilirlik (ch10) |
| **Döngü sonu** | Sonraki tetikleyiciyi yükle | **Kahneman**: **sonu iyi bitir** (ch11) — her döngü bir epizottur |

---

## ⚖️ ORTAK ETİK VE YASAL ÇERÇEVE

Bu kütüphanedeki her taktik, kullanıcı davranışını etkilemek için tasarlanmıştır. Bu meşrudur — **ama sınırı vardır.** Bu bölüm, beş kitabın ortak çizgisini ve 2026 itibarıyla geçerli düzenlemeleri birleştirir.

### Üç Kitabın Aynı Yere Varan Testi

| Kaynak | Test |
|---|---|
| **Eyal, Manipülasyon Matrisi** | (1) Bu ürünü kendim kullanır mıydım? (2) Kullanıcının hayatını maddi olarak iyileştirir mi? **Gerekçelendirme ihtiyacı hissediyorsan DUR.** |
| **Cialdini, Sonsöz** | Sinyalin altında **gerçek bir olgu** var mı? Kullanıcı sinyalin nasıl üretildiğini bilseydi kandırılmış hisseder miydi? |
| **Ariely, ch05 + ch11** | Kullanıcının **sıcak hâlde** verdiği kararı, **soğuk hâlde** de onaylar mıydı? |

**Üçü de aynı ayrımı yapıyor:**
> **Gerçek bir olguyu görünür kılmak = meşru.**
> **Olmayan bir olguyu var göstermek = sömürü.**

Kıtlık gerçekse göster. Otorite gerçekse belirt. Sosyal kanıt gerçekse sun. **Uydurma.**

### Yasal Çerçeve (Türkiye + AB, 2026)

| Düzenleme | Neyi kapsar |
|---|---|
| **AB Dijital Hizmetler Yasası (DSA) m.25** | Kullanıcıyı aldatan, manipüle eden veya özgür ve bilinçli kararını bozan arayüz tasarımını **doğrudan yasaklar** |
| **AB Dijital Piyasalar Yasası (DMA)** | Rıza akışlarında yönlendirici tasarım kısıtı |
| **KVKK / GDPR** | **Açık rıza.** Önceden işaretli kutu, "kabul"ün "ret"ten kolay olması, rızayı geri almanın zorlaştırılması = ihlal. Veri taşınabilirliği hakkı (GDPR m.20) |
| **TKHK 6502 + Ticari Reklam ve Haksız Ticari Uygulamalar Yönetmeliği** | Aldatıcı fiyat, sahte kıtlık, yanıltıcı beyan |
| **Fiyat Etiketi Yönetmeliği / AB Omnibus** | Üstü çizili "eski fiyat" **gerçekten uygulanmış** olmalı (AB'de: son 30 gündeki en düşük fiyat) |
| **Ticari İletişim Yönetmeliği / İYS** | Ticari elektronik ileti için **önceden onay**, her iletide kolay ret |
| **Mesafeli Sözleşmeler Yönetmeliği / AB Tüketici Hakları Direktifi** | Ön bilgilendirme; abonelik iptalinin üye olmak kadar kolay olması yönü |
| **Reklam Kurulu** | Influencer/affiliate ilişkisinin **açıkça belirtilmesi** zorunluluğu; sağlık beyanı kısıtları |

### Karanlık Desen Kara Listesi — Yapma

- **Roach motel** — Üyelik 1 tık, iptal 6 adım + telefon
- **Confirmshaming** — "Hayır, tasarruf etmek istemiyorum" tarzı utandıran ret düğmesi
- **Sahte kıtlık / sahte aciliyet** — Sürekli sıfırlanan geri sayım, uydurma stok sayısı, hiç bitmeyen "son gün"
- **Sahte sosyal kanıt** — Uydurma yorum, satın alınmış puan, sahte "şu an bakan kişi" sayacı
- **Sahte otorite** — Olmayan sertifika, uydurma basın amblemi, konuyla ilgisiz unvan
- **Sahte referans fiyat** — Hiç uygulanmamış "eski fiyat"
- **Gizli maliyet** — Kargo, vergi veya ücreti son adımda göstermek
- **Deneme tuzağı** — Ücretsiz deneme + gizlenmiş otomatik yenileme
- **Hayalet tuzak seçenek** — Satın alınamayan bir "plan"ı tablo doldurmak için listelemek
- **Ön işaretli onay kutuları** — KVKK açık rıza ihlali
- **Zorunlu sosyal yayma** — Kullanıcıyı kandırarak rehberine mesaj gönderttirmek
- **Yasal metni okunmaz kılmak** — Küçük punto, düşük kontrast, karmaşık dil: akıcılığı kasten düşürmek
- **Karar bilgisini kararın ardına ertelemek** — Ön bilgilendirme ihlali
- **Çocuklara yönelik jeton/sanal para ekonomisi** — En savunmasız hedefte en güçlü mekanizma

### Denetim Öncesi Kontrol Listesi

Sevkten önce:
- [ ] Her ikna sinyalinin altında **gerçek bir olgu** var mı?
- [ ] Kullanıcı sinyalin üretim biçimini bilse **kandırılmış hisseder miydi**?
- [ ] Bu ürünü **kendim kullanır mıydım**? (Gerekçelendirme ihtiyacı duydum mu?)
- [ ] Kullanıcının **soğuk hâlde** de onaylayacağı bir karar mı üretiyoruz?
- [ ] **İptal, üye olmak kadar kolay mı?**
- [ ] Rıza gerektiren tüm kutular **kapalı** mı?
- [ ] Toplam tutar, ödemeden **önce** net mi?
- [ ] Yasal/koşul metni **okunabilir** mi?
- [ ] Geri alınamaz işlemlerde **kasten sürtünme** var mı? (olmalı)
- [ ] Aşırı/sağlıksız kullanımı tespit eden bir sinyalimiz var mı? Ne yapıyoruz?
- [ ] Yukarıdaki kara listeden hiçbiri yok mu?

---

## Destek Dosyaları

- [teshis-akisi.md](teshis-akisi.md) — problemden çözüme adım adım teşhis protokolü
- [birlesik-sayilar.md](birlesik-sayilar.md) — beş kitaptaki tüm deneysel rakamlar tek tabloda

## Not

Bu kütüphane **hem saldırı hem savunma** olarak yazılmıştır. En yüksek getirili kısmı, çoğu okuyucunun beklediği yer değil — [[commerce-digital-kahneman]] ch06 ve ch07'deki **kendi veri yorumun ve tahmin disiplinin**. Kullanıcının önyargısını kullanmadan önce, kendi önyargını ölç.
