# Akıldışı Ama Öngörülebilir — Karar Kuralları ve Denetim

## Deney Sayıları

| Bulgu | Rakam | Bölüm |
|---|---|---|
| **Economist tuzak seçenek** | Tuzak var: 16/0/**84** · Tuzak yok: **68**/32 | ch01 |
| **Çikolata — BEDAVA!** | 15¢/1¢: %73/%27 · 14¢/**bedava**: %31/**%69** | ch03 |
| Sıfır olmayan indirim (2¢→1¢, 27¢→26¢) | **Hiçbir etki yok** | ch03 |
| **Sosyal norm — daire sürükleme** | 5 $: **159** · 50¢: **101** · hiçbir şey: **168** | ch04 |
| **Hediye — daire sürükleme** | Snickers: 162 · Godiva: 169 · hiçbir şey: 168 | ch04 |
| **Fiyatlı hediye** ("50 sentlik Snickers") | 50 sent ile **aynı** (piyasa normuna geçer) | ch04 |
| **Erteleme — üç sınıf** | Dayatılan tarih: **en iyi** · Hiç tarih: **en kötü** · Kendi seçimi: ortada | ch06 |
| **Sahiplik — Duke bileti** | Satıcı ~**2.400 $** vs alıcı ~**175 $** (~14 kat); **hiç satış olmadı** | ch07 |
| **Plasebo fiyat — Veladone** | 2,50 $: **neredeyse tümü** rahatlama · 10 sent: **sadece yarısı** | ch10 |
| **Iowa soğuk algınlığı** | Liste fiyatı (13 kişi) **çok daha iyi sonuç** vs indirimli (16 kişi) | ch10 |
| **On Emir — hile** | Hile yok: 3,1 · Kitap listesi: **4,1 (%33 fazla)** · On Emir: **~3 (hile sıfır)** | ch11 |
| **Buzdolabı — kola vs para** | 6 kola: **72 saatte yok** · 6 dolar: **hiç el sürülmedi** | ch12 |
| **Sıra etkisi** | Sesli sıra: çeşitlilik ↑, **memnuniyet ↓** | ch13 |

---

## Karar Kuralları

| Durum | Yap | Neden |
|---|---|---|
| Fiyat tablosu kuruyorum | Üç plan; hedefi **ortaya**; tuzak ekle | Economist / TV satıcısı Sam |
| Kargo ücreti belirliyorum | **Ya sıfır ya normal fiyat** | Amazon Fransa: 1 frank görmezden gelindi |
| Eşik belirliyorum | Ortalama sepetin **biraz üstü** | Kullanıcı ek ürünle kargodan kurtulur |
| Ürünü ilk kez fiyatlandırıyorum | **Yüksek başla** | İlk fiyat kalıcı çapa; aşağı inmek kolay, yukarı çıkmak kayıp |
| Rakip kategoriden kaçmak istiyorum | **Karşılaştırmayı imkânsız kıl** | Starbucks deseni — isim değişikliği yetmez |
| Freemium başlatacağım | Üç gizli maliyeti oku (ch02, ch03, ch10) | Sıfır çapası + BEDAVA bağımlılığı + **gerçekten düşük fayda** |
| Kullanıcı katkısı istiyorum | **Ya anlamlı para ya hiç para** | 50¢ (101) < hiçbir şey (168) |
| Hediye veriyorum | **Fiyatını yazma** | Fiyatlı hediye piyasa normuna geçer, etkisi sıfırlanır |
| Deneme süresi tasarlıyorum | Yenileme tarihi ve tutarını **önceden, açıkça** bildir | Deneme meşru, gizlenen yenileme değil (TKHK 6502, DSA m.25) |
| Onboarding'e adım ekleyeceğim | **Anlamlıysa ekle** — IKEA etkisi sahiplik üretir | Anlamsız zorluk terk üretir |
| Kullanıcı hedef belirliyor | Araç ver **+ iyi aralık öner** | Üç sınıf: kendi seçimi ortada kaldı, öneri yoktu |
| İndirim düşünüyorum | **Çift maliyeti hesapla**: marj + plasebo etkisi | Veladone: fiyat düşünce etki de düştü |
| Suistimali önlemek istiyorum | Ahlaki hatırlatıcı, işlemin **başında** | On Emir: hile sıfırlandı |
| Jeton/puan ekonomisi kuruyorum | **TL karşılığını göster** | Nakitten uzaklaşma suistimali artırır |
| Ekip tahmini/oylama alıyorum | **Eşzamanlı ve gizli** topla | Sıra etkisi hem çeşitliliği hem memnuniyeti bozar |
| Kendi ürünümü fiyatlandırıyorum | **Dışarıdan değerleme al** | Sahiplik etkisi seni de vurur (14 kat) |
| Olumsuz bilgi vereceğim | Kararı etkiliyorsa **kararın önüne** | Sirkeli bira: önceden bilgi deneyimi değiştirir |
| Kullanıcı karar veremiyor | Seçenek azalt + varsayılan sun | Kapı deneyi: açık kapı tutma maliyeti |
| İptal talebi geldi | "Dondur" seçeneği sun | Kapı açık tutma isteği — meşru ve kullanıcı lehine |

---

## Fiyatlandırma Sayfası Denetim Listesi

**Yapı**
- [ ] Üç (veya dört) seçenek var mı? Hedeflenen plan ortada mı?
- [ ] Tuzak seçenek **gerçek bir ürün** mü, satın alınabilir mi?
- [ ] En pahalı plan gerçek ve makul mü? (Abartılırsa tüm tablo güvenilmez görünür)
- [ ] Yüksek fiyatlı bir kalem var mı? (İkinci en pahalıyı satar)

**Fiyat gösterimi**
- [ ] Üstü çizili fiyat **gerçekten uygulanmış** mı? (TKHK 6502, Fiyat Etiketi Yönetmeliği, AB Omnibus — son 30 gündeki en düşük fiyat)
- [ ] Aylık gösteriyorsan **yıllık toplam** da görünüyor mu?
- [ ] Toplam tutar ödeme öncesi net mi? (gizli maliyet yok)
- [ ] Kargo ücreti ve eşik **ilk adımda** görünüyor mu?

**BEDAVA!**
- [ ] "Neredeyse bedava" bir kalem var mı? (Ya sıfırla ya normal fiyata çek)
- [ ] Ücretsiz deneme varsa yenileme tarihi ve tutarı **önceden ve açıkça** bildiriliyor mu?
- [ ] İptal, üyelik kadar kolay mı?
- [ ] "Bedava" eklenti, kullanıcıyı gerçekten istediği üründen vazgeçiriyor mu?

**Beklenti**
- [ ] Ücretsiz katmanda beklenti fiyat dışı sinyallerle kuruluyor mu?
- [ ] Vaat, ürünün gerçekten teslim edebileceği düzeyde mi? (Aşırı vaat deneyimi kötüleştirir)
- [ ] Kararı etkileyen bilgilerin hepsi kararın önünde mi?

**Normlar**
- [ ] Kullanıcı katkısı için **küçük para** veriliyor mu? (Ya kaldır ya anlamlı yap)
- [ ] Hediyenin **fiyatı yazılı** mı? (Yazma)
- [ ] "Aile/topluluk" dili kullanılıyorsa operasyon buna uyuyor mu?

**Suistimal ve dürüstlük**
- [ ] Riskli akışlarda ahlaki hatırlatıcı **başta** mı?
- [ ] Jeton/puan sisteminde TL karşılığı görünüyor mu?
- [ ] Çocuklara yönelik üründe sanal para ekonomisi var mı? (Yüksek düzenleyici risk)

---

## Hangi Mekanizma? — Hızlı Teşhis

| Belirti | Mekanizma | Bölüm |
|---|---|---|
| "Kullanıcılar hep en ucuz planı seçiyor" | Tuzak yok veya yanlış kurulmuş | ch01 |
| "Fiyatı yükseltemiyoruz" | İlk fiyat çapası çok düşük kuruldu | ch02 |
| "Ücretsizden ücretliye geçiş çok düşük" | Sıfır çapası + BEDAVA bağımlılığı | ch02, ch03 |
| "Ücretsiz kullanıcılar memnun değil" | Plasebo kaybı — beklenti düşük, deneyim gerçekten düşük | ch10 |
| "Sepet ortalaması düşük" | Ücretsiz kargo eşiği yok veya yanlış | ch03 |
| "Referans programı işlemiyor" | Küçük para — en kötü bölge | ch04 |
| "Sadakat hediyesi etki etmiyor" | Fiyatı yazılı — piyasa normuna geçmiş | ch04 |
| "Kullanıcı başlıyor ama bitirmiyor" | Yapı yok (Ariely'nin 2. sınıfı) | ch06 |
| "Denemeden ücretliye geçiş iyi ama iade yüksek" | Deneme tuzağı + sıcak hâl satışı | ch05, ch07 |
| "Ürünümüz alıcılar için bizim düşündüğümüz kadar değerli değil" | **Kendi sahiplik etkin** | ch07 |
| "Kullanıcı plan seçemiyor" | Çok seçenek + kapı açık tutma isteği | ch08 |
| "Ürün iyi ama yorumlar kötü" | Beklenti yanlış kuruldu (aşırı vaat) | ch09 |
| "İndirim sonrası memnuniyet düştü" | Plasebo etkisi zayıfladı | ch10 |
| "Promosyon/iade suistimali yüksek" | Ahlaki hatırlatıcı yok | ch11 |
| "Sanal para ekonomisinde şikâyet çok" | Nakitten uzaklaşma | ch12 |
| "Ekip tahminleri hep birbirine benziyor" | Sıra etkisi — açıkta toplanıyor | ch13 |
