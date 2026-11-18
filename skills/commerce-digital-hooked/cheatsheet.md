# Hooked — Karar Kuralları ve Teşhis

## Teşhis Ağacı: "Kullanıcılar geri dönmüyor"

```
Kullanıcı hiç geri dönmüyor mu, yoksa bir süre sonra mı bırakıyor?
│
├── HİÇ DÖNMÜYOR
│   ├── Sahipli tetikleyicin var mı? (ikon, push izni, e-posta opt-in)
│   │     YOK → Önce onu kur. Ücretli tetikleyiciyle retention satın alınmaz.
│   │     VAR → Tetikleyici zamanlaması dahili tetikleyiciyle hizalı mı? (ch02)
│   └── Dahili tetikleyiciyi tanımladın mı? (5 Neden ile duyguya indin mi?)
│         HAYIR → ch02'ye git. Özellik diliyle değil, duygu diliyle tanımla.
│
├── BİR-İKİ KEZ KULLANIP BIRAKIYOR
│   ├── B=MAT hangisi eksik?
│   │     Tetikleyici yok → net CTA / bildirim
│   │     Yetenek düşük → 6 basitlik unsurundan en kıt kaynağı bul (ch03)
│   │     Motivasyon düşük → EN SON buraya yatırım yap
│   └── Ödül kaşıntıyla eşleşiyor mu? (Mahalo testi)
│         HAYIR → Oyunlaştırma eklemek işe yaramaz. Ödül türünü değiştir. (ch04)
│
├── BİR SÜRE KULLANIP SIKILIYOR
│   └── SONLU DEĞİŞKENLİK. İçerik tüketimi mi üretimi mi?
│         Tüketim → ya içerik boru hattı finanse et (stüdyo modeli)
│                   ya kullanıcı üretimine / çok oyunculuya geç (ch04)
│
├── KULLANIYOR AMA GEÇİŞ YAPIYOR
│   └── Depolanan değer yok. İçerik/Veri/Takipçi/İtibar/Beceri — hiçbiri yoksa
│         ürün klonlanabilir. En az birini kur. (ch05)
│
└── ÖFKELİ TERK / ŞİKÂYET
      └── ÖZERKLİK İHLALİ. Kullanıcıyı bilgilendirmeden dahil ettiğin bir şey var mı?
            Quora "views" deseni. Geri al, opt-in yap, açıkla. (ch04, ch06)
```

---

## Karar Kuralları

| Durum | Yap | Neden |
|---|---|---|
| Motivasyon mu yetenek mi artırayım? | **Her zaman yetenekle başla** | Motivasyon artırmak pahalı ve yavaş; kullanıcı eğitici metni okumaz |
| Kullanıcı yatırım yapmıyor | **Daha az iste**, ödülden sonra iste | B=MAT Yatırım Aşaması'nda da geçerli |
| Ödül işe yaramıyor | Para ekleme — **ödül türünü** kaşıntıyla eşleştir | Mahalo (para) öldü, Quora (sosyal onay) büyüdü |
| Etkileşim zamanla düşüyor | Sonlu → sonsuz değişkenliğe geç | FarmVille/Zynga %80 değer kaybı |
| Rakip bizden %20 iyi, korkayım mı? | Hayır — **9x eşiği** var | Gourville; QWERTY hâlâ ayakta |
| Biz rakipten %20 iyiyiz, geçer miyiz? | Hayır. Ya 9x ol ya davranış değişikliği maliyetini sıfırla | Aynı kural sana da işliyor |
| Bildirim göndersem kullanıcı kızar mı? | **Test et**, varsayma | YouVersion Noel testi: tam tersi oldu |
| Yeni özellik gizlilik etkiliyor | **Opt-in**, önce duyur | Quora isyanı + KVKK/GDPR zorunluluğu |
| Kullanıcının istediği ile senin istediğin ayrışıyor | Veriyle çöz (Alışkanlık Yolu), metinle ikna etmeye çalışma | Twitter: kullanıcılar arama istedi, takip alışkanlık kurdu |

---

## Eşik Değerler ve Sayılar

| Metrik | Değer | Kaynak/Bağlam |
|---|---|---|
| Alışılmış kullanıcı oranı — başlangıç ölçütü | **%5** | Alışkanlık Testi Adım 2. Altındaysan ürün veya hedef kullanıcı yanlış |
| Twitter devrilme noktası | **30 takip** | Erken dönem Alışkanlık Yolu |
| Gourville davranış değişikliği eşiği | **9x daha iyi** | Yeni ürünün yerleşik alışkanlığı kırması için |
| Patolojik kullanıcı oranı (en bağımlılık yapıcı teknolojide) | **~%1** | Slot makineleri, sektör tahmini |
| Bağışlanan ilerleme etkisi | Tamamlama **%82 daha yüksek** | Araba yıkama delikli kart deneyi |
| Tutarlılık — küçük taahhüt etkisi | %17 → **%76** | Bahçe tabelası deneyi |
| IKEA Etkisi | **5x** değerleme | Origami deneyi (Ariely, Norton, Mochon 2011) |
| "Ama sen özgürsün" | Uyum **2x** | 42 çalışma, 22.000+ katılımcı meta-analizi |
| Kayıt sonrası ödemeye dönüşüm (Evernote) | Ay 1: %0,5 → Ay 33: %11 → Ay 42: %26 | "Gülümseme grafiği" |
| Mobil uygulama tek-kullanım oranı (2010) | **%26** | Any.do'nun çözmeye çalıştığı problem |

---

## Sıklık Kalibrasyonu (Alışkanlık Testi Adım 1)

| Ürün tipi | Beklenen alışılmış sıklık |
|---|---|
| Sosyal ağ / mesajlaşma | Günde birden fazla |
| Arama / e-posta | Günde birden fazla |
| Okuma/ibadet/öğrenme planı | Günde 1 (kısa) |
| İçerik keşfi / pinboard | Günde–haftada birkaç |
| Film/restoran öneri | Haftada 1–2 |
| E-ticaret genel amaçlı | Haftada–ayda birkaç (düşük sıklık, **yüksek algılanan fayda** ile telafi) |
| Sigorta / tek seferlik işlem | **Alışkanlık hedefleme** — bu çerçeve uygulanmaz |

> Kural: Aşırı agresif tahmin sağlıklı bir ürünü başarısız gösterir. Benzer ürünlerin kamuya açık verisiyle kalibre et.

---

## Tetikleyici Seçim Matrisi

| Amaç | Tetikleyici türü | Not |
|---|---|---|
| Yeni kullanıcı edinme | Ücretli, Kazanılmış | Retention için sürdürülemez |
| Viral büyüme | İlişki | Karanlık desen sınırına dikkat |
| **Tekrar etkileşim / alışkanlık** | **Sahipli** | **Tek motor.** Opt-in zorunlu |
| Alışkanlık kurulduktan sonra | Dahili | Hedef durum — harici tetikleyiciye ihtiyaç kalmaz |

---

## Etik / Uyum Ön Kontrolü (sevkten önce)

- [ ] Bu ürünü kendim kullanır mıydım? (Gerekçelendirme ihtiyacı hissettim mi? → DUR)
- [ ] Kullanıcıların hayatını maddi olarak iyileştiriyor mu?
- [ ] Kullanıcıya açıkça anlatsam utanır mıydım?
- [ ] İptal etmek, üye olmak kadar kolay mı? (roach motel yok)
- [ ] Kıtlık/aciliyet beyanlarım **gerçek** mi? (sahte sayaç yok)
- [ ] Ret düğmem utandırıcı dil kullanıyor mu? (confirmshaming yok)
- [ ] Tüm maliyetler ilk adımda görünüyor mu? (gizli maliyet yok)
- [ ] Onay kutuları ön işaretli mi? (olmamalı — KVKK açık rıza)
- [ ] Ticari ileti için önceden onay ve İYS kaydı var mı? (6502 / Ticari İletişim Yönetmeliği)
- [ ] Aşırı/sağlıksız kullanımı tespit eden bir sinyalim var mı? Ne yapıyorum?
- [ ] Arayüzüm kullanıcının özgür ve bilinçli kararını bozuyor mu? (AB DSA m.25)
