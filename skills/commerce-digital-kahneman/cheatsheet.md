# Thinking, Fast and Slow — Karar Kuralları ve Denetim

## Sayılar ve Eşikler

| Bulgu | Değer | Bölüm |
|---|---|---|
| **Çapalama endeksi — tipik** | **%55** | ch04 |
| Çapalama endeksi — profesyonel emlakçı | %41 | ch04 |
| Çapalama endeksi — deneyimsiz öğrenci | %48 | ch04 |
| **Kayıp kaçınma oranı** | **1.5 – 2.5** | ch08 |
| Sahiplik etkisi — kupa deneyi | Satış fiyatı ≈ alış fiyatının **2 katı** | ch08 |
| Sahiplik etkisi — Duke bileti | ~2.400 $ vs ~175 $ (**~14 kat**) | ch08 |
| Campbell çorbası — "en fazla 12" tabelası | 3,5 → **7 kutu** (2 kat) | ch04 |
| Soğuk el — daha uzun/daha acılı epizodu seçenler | **%80** | ch11 |
| Küçük işletme 5 yıl hayatta kalma — gerçek | **~%35** | ch07 |
| Girişimcilerin kendi tahmini | ortalama %60; **%81'i %70+ veriyor**; %33'ü "sıfır risk" | ch07 |
| Yatırım danışmanı performansı — yıllar arası korelasyon | **0,01** (≈ sıfır) | ch07 |
| Meehl — formül vs. uzman karşılaştırması | ~200 çalışma; formül **yener veya eşitler** | ch07 |
| Organ bağışı — opt-in vs opt-out | Düşük vs **≈%100** | ch10 |
| Kahneman'ın müfredat projesi | Tahmin 2 yıl → gerçek **8 yıl**; referans sınıfta hiçbiri 7 yıldan az sürmedi, %40'ı bitmedi | ch07 |

---

## Karar Kuralları

| Durum | Yap | Neden |
|---|---|---|
| Landing page'de 12 özellik var | **3'e indir** | WYSIATI: az ve tutarlı > çok ve nüanslı |
| Kullanıcı "fiyat/performansa bakıyorum" diyor | Davranışa bak; yerine koyduğu soruyu bul | Yerine koyma — söylenen kriter gerçek kriter değil |
| Kaydırıcı/plan varsayılanı belirliyorum | **Tipik kullanımı** yansıt, maksimumu değil | Varsayılan = çapa + referans noktası; suistimali karanlık desen |
| Rıza/izin kutusu tasarlıyorum | **Varsayılan kapalı** | KVKK/GDPR açık rıza; DSA m.25 |
| Zam yapacağım | Referans noktasını yeniden kur + mevcut müşteriye kazanç ver | Kayıp kaçınma 1.5–2.5 |
| Kota/özellik azaltacağım | **Erken duyur, gerekçe ver, telafi sun** | Kayıp + tepkisellik birlikte; en riskli değişiklik türü |
| İptal akışı tasarlıyorum | **Kolay ve sıcak** yap | Zirve-son: son anı tüm deneyimi belirler; ayrıca yasal yön bu tarafta |
| Uzun bekleme süresi var, kısaltamıyorum | **Bitişi iyileştir** | Süre ihmali |
| Onboarding'i tasarlıyorum | Erken bir gerçek "aha" zirvesi + net bir son ekran | Zirve-son |
| Pakete zayıf bir özellik ekleyeceğim | **Ekleme** | Ortalama etkisi: toplamı artırır, değeri düşürür |
| Kullanıcıdan 10 fayda saymasını isteyeceğim | 3 iste | Akıcılık > sayı (12 örnek etkisi) |
| İstatistik iletiyorum | **Nedensel cümleye çevir** | Taban oran ihmali; nedensel taban oran ihmal edilmez |
| Metin okunması zor | Kontrastı ve dili düzelt | Akıcılık → algılanan doğruluk |
| Geri alınamaz işlem onayı | **Akıcılığı kasten düşür** (yazdır, ek adım) | Zorlanma Sistem 2'yi devreye sokar |
| Yüksek algılanan risk | İade/garanti ekle | Kesinlik etkisi |
| Kaybeden bir ürün hattım var | **Önceden yazılmış çıkış kriteri** uygula | Dörtlü örüntü sağ üst: ekip risk arayan moda girer |
| "Bu kadar yatırdık, bırakamayız" duyuyorum | Soruyu değiştir: "bugün sıfırdan başlasak yapar mıydık?" | Batık maliyet |
| Büyük bir karar veriyorum | **Premortem çalıştır** | Şüpheye meşru zemin verir |
| Süre/maliyet tahmini yapıyorum | **Dış görüş**: referans sınıfın medyanından başla | Planlama yanılgısı |
| İşe alıyorum / tedarikçi seçiyorum | 6 kriter, ayrı ayrı puanla, toplamı al | Meehl; genel izlenim kurma |
| Yöneticiyi değerlendiriyorum | **Karar kalitesine** göre, sonuca göre değil | Sonuç yanlılığı + dar çerçeveleme |

---

## A/B Test ve Veri Denetim Listesi

Her test sonucu için sırayla:

- [ ] **Örneklem büyüklüğü önceden hesaplandı mı?** Yoksa küçük sayılar yasası riski — küçük n uç sonuç üretir
- [ ] **Etki büyüklüğü, bu üründeki tipik etkilerin kaç katı?** Aykırı derecede büyükse şüphelen
- [ ] **Bu varyant neden test edildi?** "En kötü performans gösterdiği için" ise **ortalamaya regresyon** iyileşmenin bir kısmını açıklar
- [ ] **Kontrol grubu var mı?** Kontrolsüz önce–sonra = regresyonu etki sanmak
- [ ] **Süre tam haftalık döngüleri kapsıyor mu?** Hafta içi/hafta sonu profil farkı
- [ ] **Hangi metrikler raporlanmadı?** (WYSIATI) Aktivasyon arttı ama retention ne oldu?
- [ ] **Taban oran ne?** Bu üründe geçmiş benzer testlerin dağılımı
- [ ] **Sezgisel tahmini geri çek**: taban oranın ve kanıtın tanısal değerinin oranında (bölüm 18 yöntemi)
- [ ] **Nedensel hikâye kurmadan önce dur**: Sistem 1, rastgele dalgalanmaya neden uydurur

---

## Ürün ve Pazarlama Denetim Listesi

**Fiyat ve teklif**
- [ ] Referans/üstü çizili fiyat gerçekten uygulanmış mı? (TKHK 6502, AB Omnibus)
- [ ] Toplam tutar ödeme öncesi net görünüyor mu?
- [ ] Alternatif ölçü birimi (aylık/yıllık) erişilebilir mi?
- [ ] Çapa olarak kullanılan premium plan gerçek bir seçenek mi?

**Varsayılanlar**
- [ ] Rıza gerektiren her kutu kapalı mı?
- [ ] Varsayılan plan/miktar tipik kullanımı mı yansıtıyor?
- [ ] Varsayılandan sapmak kolay mı?

**Akış (zirve-son)**
- [ ] Onboarding'de kullanıcının **kendi verisiyle** bir "aha" anı var mı?
- [ ] Satın alma onayı sıcak ve net mi?
- [ ] Destek kapanışında çözümün özeti var mı?
- [ ] **İptal akışı kolay ve saygılı mı?**
- [ ] Kesinti/hata bildiriminin **son cümlesi** iyi mi?

**Mesaj**
- [ ] Ana sayfada 3'ten fazla ana fayda var mı? (varsa azalt)
- [ ] Zayıf referans/örnek ortalamayı düşürüyor mu?
- [ ] Metin kontrastı ve dili akıcı mı?
- [ ] Yasal/koşul metni okunabilir mi? (okunmaz kılmak karanlık desen)
- [ ] Risk ve fayda **aynı formatta** mı sunuluyor? (oran/sıklık asimetrisi yok)

**Geri alınabilirlik**
- [ ] Undo / iade / iptal vaadi gerçek mi?
- [ ] Geri alınamaz işlemlerde kasten sürtünme var mı?

---

## Hangi Önyargı? — Hızlı Teşhis

| Belirti | Muhtemel mekanizma | Bölüm |
|---|---|---|
| "Fiyatımız yüksek değil ama pahalı algılanıyor" | Çapa yok veya yanlış çapa | ch04 |
| "Kullanıcı özellikleri okuyor ama dönüşmüyor" | Yerine konan soru yanıtlanmıyor | ch03 |
| "Çok özellik ekledik ama memnuniyet düştü" | Ortalama etkisi / "az çoktur" | ch10, ch11 |
| "Kullanıcı denemeyi seviyor ama ödemiyor" | Referans noktası ücretsizde kurulmuş | ch08 |
| "Zam sonrası orantısız tepki" | Kayıp kaçınma + tepkisellik | ch08 |
| "İptal edenler geri dönmüyor" | Zirve-son: son anı kötü | ch11 |
| "Yeni özellik kullanılmıyor" | Varsayılan yanlış yönde | ch10 |
| "Testlerimiz tekrarlanmıyor" | Küçük sayılar + regresyon | ch06 |
| "Projelerimiz hep gecikiyor" | Planlama yanılgısı / iç görüş | ch07 |
| "Kaybeden projeyi kapatamıyoruz" | Batık maliyet + dörtlü örüntü sağ üst | ch09, ch10 |
| "Ekip riskten kaçınıyor" | Dar çerçeveleme + sonuç yanlılığı | ch09, ch07 |
| "Satış sonrası pişmanlık ve churn yüksek" | Odaklanma yanılsaması ile satış | ch11 |
| "Kriz beklenenden büyüdü" | Erişilebilirlik çığı | ch05 |
| "Güvenlik endişesi veriyle geçmiyor" | Uzman–halk risk tanımı farkı | ch05 |
