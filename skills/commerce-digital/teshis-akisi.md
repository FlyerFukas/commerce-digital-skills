# Commerce Digital — Teşhis Protokolü

Bir kullanıcı davranışı problemi geldiğinde sırayla uygula.

---

## Adım 0 — Problemi Doğru Yere Koy

Önce **huninin neresinde** olduğunu belirle. Yanlış aşamaya doğru çözüm uygulamak en yaygın hatadır.

| Belirti | Aşama | Ana kitap |
|---|---|---|
| Trafik yok | Edinim | cialdini, sutherland |
| Trafik var, kayıt yok | Dönüşüm | cialdini, kahneman, ariely |
| Kayıt var, kullanım yok | Aktivasyon | hooked (ch03), kahneman (ch11) |
| Kullanıyor, geri gelmiyor | Retention | hooked ⭐ |
| Geliyor, ödemiyor | Monetizasyon | ariely ⭐ |
| Ödüyor, bırakıyor | Churn | kahneman ch11 ⭐, ariely ch08 |

---

## Adım 1 — Kendi Verini Denetle (atlama)

**Herhangi bir çözüm önermeden önce**, problemin gerçek olduğundan emin ol.

- [ ] **Küçük sayılar yasası**: Bu sonuç kaç kullanıcıdan geliyor? Örneklem önceden hesaplandı mı? ([[commerce-digital-kahneman]] ch06)
- [ ] **Ortalama regresyon**: Bu metrik bir uç değerden mi geliyor? Kontrol grubu var mı?
- [ ] **Taban oran**: Bu üründe/kategoride tipik değer ne? Bu gerçekten anormal mi?
- [ ] **WYSIATI**: Hangi metrikler raporlanmadı? Ne bilmiyorum?
- [ ] **Erişilebilirlik**: Bu problem, son yaşanan canlı bir olay yüzünden mi gündemde? ([[commerce-digital-kahneman]] ch05)
- [ ] **Sıra etkisi**: Ekip görüşleri eşzamanlı ve bağımsız mı toplandı? ([[commerce-digital-ariely]] ch13)

> **Kahneman'ın uyarısı**: Sistem 1, rastgele dalgalanmaya bile nedensel bir hikâye uydurur. Hikâyeyi kurmadan önce veriyi denetle.

---

## Adım 2 — Mekanizmayı Bul (hangi kitap?)

Belirtiyi mekanizmaya çevir:

```
Kullanıcı ne YAPMIYOR ve NEDEN yapmıyor olabilir?
│
├── Farkında değil / hatırlamıyor
│     → TETİKLEYİCİ eksik → hooked ch02
│
├── Yapmak istiyor ama zor geliyor
│     → YETENEK eksik → hooked ch03 (6 basitlik unsuru)
│                      → kahneman ch02 (bilişsel akıcılık)
│
├── Kolay ama istemiyor
│     → MOTİVASYON eksik → hooked ch03 (3 temel motivatör)
│                        → cialdini (hangi ilke uygun?)
│
├── Güvenmiyor
│     → cialdini ch04 (sosyal kanıt), ch06 (otorite)
│     → kahneman ch02 (akıcılık), ch03 (hale etkisi)
│
├── Değeri görmüyor / pahalı buluyor
│     → ariely ch01 (izafiyet/tuzak), ch02 (çapa), ch10 (plasebo fiyat)
│     → cialdini ch01 (kontrast)
│     → kahneman ch04 (çapa), ch10 (çerçeveleme)
│
├── Erteliyor
│     → ariely ch06 (araç + öneri)
│     → cialdini ch07 (kıtlık — GERÇEKse)
│     → kahneman ch09 (kesinlik etkisi: garanti, iade)
│
├── Karar veremiyor
│     → ariely ch08 (seçenek azalt), ch01 (tuzak ile yönlendir)
│     → kahneman ch10 (varsayılan sun)
│
├── Bir kez yapıyor, tekrarlamıyor
│     → hooked ch04 (değişken ödül), ch05 (yatırım)
│
├── Sıkılıyor
│     → hooked ch04 (sonlu → sonsuz değişkenlik)
│
├── Geçiş yapıyor
│     → hooked ch05 (depolanan değer yok)
│
├── Öfkeli terk ediyor
│     → hooked ch04 / cialdini ch07 (ÖZERKLİK İHLALİ)
│     → kahneman ch08 (kayıp olarak hissedilen bir değişiklik)
│
└── Hiçbiri uymuyor / mantıklı çözümler tükendi
      → sutherland (bulaşık makinesi testi: bu problem mantığa dayanıklı mı?)
```

---

## Adım 3 — Çözümü Kur

Seçtiğin kitabın **patterns.md** dosyasını aç ve uygun deseni al. Sonra:

1. **Zıt yönü de düşün** (Sutherland 1. kural): Çözümün tersi de işe yarayabilir mi?
2. **Kelebek etkisi ekle**: Test listesine, mantıklı gerekçesi olmayan en az bir küçük değişken koy.
3. **Zirve ve sonu tasarla** (Kahneman ch11): Bu akışın zirvesi ne, sonu ne?
4. **Özerkliği kontrol et** (Hooked ch04): Kullanıcı kendini zorlanmış hissedecek mi?
5. **Depolanan değer üretiyor mu?** (Hooked ch05)

---

## Adım 4 — Etik ve Yasal Kapı

**Sevkten önce zorunlu.** [SKILL.md](SKILL.md)'deki kontrol listesini çalıştır. Kısaca:

| Test | Kaynak |
|---|---|
| Sinyalin altında gerçek bir olgu var mı? | Cialdini |
| Kullanıcı üretim biçimini bilse kandırılmış hisseder mi? | Cialdini |
| Bu ürünü kendim kullanır mıydım? Gerekçelendirme ihtiyacı duydum mu? | Eyal |
| Kullanıcı soğuk hâlde de bu kararı onaylar mıydı? | Ariely |
| Kara listedeki desenlerden biri var mı? | Ortak çerçeve |

**Herhangi biri kırmızıysa tasarımı değiştir — "ama dönüşümü artırıyor" bir savunma değil.**

---

## Adım 5 — Test Et, Sezgine Güvenme

Ariely'nin kapanış tavsiyesi ve Kahneman'ın ch06–ch07 disiplini birleşince:

- [ ] Örneklem büyüklüğü **önceden** hesaplandı mı?
- [ ] Tam haftalık döngüleri kapsıyor mu?
- [ ] Kontrol grubu var mı?
- [ ] Etki büyüklüğü, bu üründeki tipik etkilerin kaç katı? (Aykırıysa şüphelen)
- [ ] Aktivasyonun yanında **retention** da ölçülüyor mu?
- [ ] Sonucu **taban orana doğru geri çektin** mi? (Kahneman ch06, bölüm 18 yöntemi)

> **Bu kütüphanedeki her bulgu, deneylerin çoğu ABD üniversite öğrencileriyle yapılmış çalışmalara dayanır.** Etki yönü büyük olasılıkla aynıdır; **büyüklüğü ve bazen yönü** (Ariely'nin Hong Kong sıra deneyi) kültüre göre değişir. **Kendi kullanıcı tabanında doğrula.**

---

## Adım 6 — Tahmin Yapacaksan Dış Görüş

Herhangi bir süre, maliyet veya etki tahmini için ([[commerce-digital-kahneman]] ch07):

1. **Referans sınıfı tanımla** — bu ekipte, benzer kapsamda, son N benzer iş
2. **Dağılımı çıkar** — medyan, aralık, iptal oranı
3. **Taban tahmin = medyan**
4. **Ayarlama yap** — sadece bu vakanın gerçekten farklı olduğunu gösterebilirsen, ve **küçük tut**
5. **Premortem çalıştır** — "Bir yıl sonra bu felaket oldu. Neden?"

---

## Hızlı Referans: Hangi Kitabın "Sahibi" Olduğu Konular

| Konu | Sahibi | Neden |
|---|---|---|
| Alışkanlık, retention, bildirim | **hooked** | Kanca Modeli'nin tamamı |
| Dönüşüm kopyası, güven sinyalleri | **cialdini** | Altı ilke |
| Fiyat, paket, BEDAVA, freemium | **ariely** | Deneylerin çoğu bu alanda |
| Varsayılan, çerçeveleme, akış tasarımı | **kahneman** | Karar mimarisi |
| **Kendi veri ve tahmin disiplinin** | **kahneman** | ch06, ch07 |
| Deneyim akışı (zirve-son) | **kahneman** | ch11 |
| Sosyal/gönüllü katkı | **ariely** | ch04 |
| Sezgiye aykırı fikir üretimi | **sutherland** | Kitabın tamamı |
| Etik sınır | **hooked ch06** + ortak çerçeve | Manipülasyon Matrisi |
