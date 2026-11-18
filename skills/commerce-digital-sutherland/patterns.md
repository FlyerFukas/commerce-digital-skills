# Alchemy — Uygulanabilir Desenler

> Kapsam uyarısı: Bu desenler **giriş bölümünden** (s. 1–25) türetilmiştir. Kitabın 1–7. bölümleri kaynakta yok — bkz. kitap-haritasi.md.

---

## Problem Teşhisi

### Bulaşık Makinesi Testi — "Bu problem mantığa dayanıklı mı?"
**Ne zaman**: Uzun süredir çözülmemiş bir problemle karşılaştığında.
**Nasıl**: Sor — *"Bu problem, mantıklı yöntemlerle daha önce çözülebilir olsaydı, çözülmüş olmaz mıydı?"*
- **Evet** → Problem **mantığa dayanıklıdır** (logic-proof). Mantıklı çözüm arayışını bırak, psiko-mantığa geç.
- **Hayır** → Mantıklı çözüm hâlâ denenmemiştir. Önce onu dene.
**Rory'nin 11. kuralı**: *"Mantıklı bir cevap olsaydı, çoktan bulmuş olurduk."*
**Ödünleşim**: Bu test, her problemi "büyü gerektiren" ilan etmek için bahane olmamalı. Sutherland'ın kendi uyarısı: *"Hava trafik kontrolünün başında kavramsal sanatçı istemiyorum."*

### İki Neden Kuralı
**Ne zaman**: Bir kullanıcı davranışını anlamaya çalışırken.
**Nasıl**: Her davranış için **iki** neden ara:
1. **Görünür/beyan edilen mantıklı neden** (kullanıcının söylediği)
2. **Gizli/kriptik neden** (davranışı gerçekten yönlendiren)

Sutherland'ın testi: *"İnsanlar dişlerini neden fırçalar?"* Onaylı cevap: diş sağlığı. **Peki neden diş macunlarının %95'i nane aromalı?**
**Ödünleşim**: İkinci neden her zaman bulunmayabilir. Ama aramamak, onu göremeyeceğin anlamına gelir.

### Aptal Soru Üretme
**Ne zaman**: Bir ürün veya kategori üzerinde takılıp kaldığında.
**Nasıl**: Kurumsal ortamda "deli" görünecek soruları kasten yaz:
- "İnsanlar bu ürünü gerçekten ne için kullanıyor?"
- "Bu özelliği tamamen kaldırsak ne olur?"
- "Fiyatı iki katına çıkarsak kim alır ve neden?"
- "Bu kategoride kimsenin sormadığı soru ne?"
**Ödünleşim**: Bu sorular, güvenli bir alanda sorulmalı. Sutherland'ın notu: Reklam ajansları, "aptal soru sorup yine de terfi edebildiğin" son güvenli alanlardan biri — çoğu kurumsal ortam değil.

---

## Deney Tasarımı

### Kelebek Etkisi Avı
**Ne zaman**: A/B test backlog'u oluştururken.
**Nasıl**: Test listesinin **kasten bir bölümünü**, mantıklı gerekçesi olmayan değişkenlere ayır. Sutherland'ın zarf testinde işe yarayan üç değişken (elden teslim bilgisi, kâğıt kalitesi, zarf yönü), bir mantık insanının **test etmeyi düşünmeyeceği** değişkenlerdi. İşe yaramayan tek değişken **rasyonel olandı** (vergi iadesi bilgisi, bağışları %30'dan fazla düşürdü).
**Ödünleşim**: Bu testlerin çoğu başarısız olur. Ama başarılı olanların getirisi orantısız büyüktür (300 milyon $, 8 milyon £, dönüşümü ikiye katlayan dört kelime).
**Kurumsal engel**: Sutherland'ın kendi itirafı — "büyülü çözüm arama bütçesi" talep etmek zordur, çünkü iş gerekçesinin mantıklı görünmesi gerekir. **Çözüm**: Bu testleri ayrı bir bütçe kalemi olarak değil, mevcut test kapasitesinin sabit bir yüzdesi olarak konumlandır.

### Tersini de Test Et (1. kural)
**Ne zaman**: Bir hipotez işe yaramadığında.
**Nasıl**: *"İyi bir fikrin tersi de iyi bir fikir olabilir."*
- "Daha ucuz" işe yaramıyorsa → **daha pahalı** (Sutherland'ın fast-food örneği; [[commerce-digital-ariely]] ch10 plasebo fiyat)
- "Daha çok özellik" işe yaramıyorsa → **daha az** ([[commerce-digital-kahneman]] ch10 "az çoktur")
- "Daha fazla seçenek" işe yaramıyorsa → **daha az seçenek** ([[commerce-digital-ariely]] ch08)
- "Daha çok bilgi" işe yaramıyorsa → **daha az bilgi** ([[commerce-digital-kahneman]] ch03 WYSIATI)
**Ödünleşim**: Yok. Bu, ücretsiz bir hipotez üretme kuralıdır.

### Sezgiye Aykırı Olanı Test Et (8. kural)
**Ne zaman**: Rekabet avantajı ararken.
**Nasıl**: *"Sezgiye aykırı şeyleri test et — çünkü başka kimse etmeyecek."* Rakiplerin hepsi aynı mantıkla çalışıyorsa, mantıklı olmanın rekabetçi değeri sıfırdır (3. kural: *"Herkes mantıklı davranıyorsa, mantıklı olmak işe yaramaz."*).
**Ödünleşim**: Açıklaması zor, savunması zor. Ama tam bu yüzden rakip kopyalayamaz.

### Önce Keşfet, Sonra Açıkla (7. kural)
**Ne zaman**: "Neden işe yarayacağını açıklayamıyorsan test edemeyiz" itirazıyla karşılaştığında.
**Nasıl**: Aspirin **onlarca yıl** ağrı kesici olarak bilindi, nasıl çalıştığı çok sonra anlaşıldı. Bakelit, penisilin, mikrodalga, röntgen, radar, radyo — hepsi "tersten" keşfedildi. *"Gözleme dayanan iyi bir tahmin de bilimdir. Şanslı bir kaza da öyle."*
**Ödünleşim**: Açıklama olmadan ölçekleme risklidir. **Test et, çalışırsa ölçekle, paralel olarak nedenini araştır.**

---

## Değer ve Algı

### Algılanan Değeri Ürünü Değiştirmeden Artır
**Ne zaman**: Ürün maliyetini artırmadan değer artırmak istediğinde.
**Nasıl**: Zarf testinde **kaliteli kâğıt** hem bağışları hem **100 £+ büyük bağış sayısını** artırdı. Ürünün kendisi değişmedi.
Uygulama alanları: ambalaj, sunum, teslim deneyimi, tipografi, ses ve dil, fiziksel dokunuş noktaları.
**Ödünleşim**: Sahte kalite sinyali (görünüşte pahalı, içi boş) ilk kullanımda hayal kırıklığını büyütür ([[commerce-digital-ariely]] ch09 aşırı vaat).

### "Rasyonel Argüman" Riskini Kontrol Et
**Ne zaman**: Mesajına ekonomik/rasyonel bir gerekçe eklemeyi düşündüğünde.
**Nasıl**: Zarf testinde **tek rasyonel argüman** (vergi iadesi hatırlatması) bağışları **%30'dan fazla düşürdü** — ve bağış yapan kişi oranını da azalttı.
Olası mekanizma: Rasyonel gerekçe eklemek, davranışı **piyasa normuna** taşıyor ve duygusal/sosyal gerekçeyi bastırıyor ([[commerce-digital-ariely]] ch04).
**Ödünleşim**: Her rasyonel argüman zararlı değildir. **Ama varsayma — test et.**

### Bağlam Tasarımı
**Ne zaman**: Aynı ürünü farklı bir konuma taşımak istediğinde.
**Nasıl**: **Hendrick's cin**: Ürünü limon yerine **salatalıkla** servis etmeyi önerdi. Sonuç: (a) anında ayırt edilebilirlik (salience), (b) ABD'de "sofistike İngiliz" konumlandırması — çünkü Amerikalılar salatalıklı sandviçi bir İngiliz tuhaflığı olarak görür. Bir İngiliz için salatalık hiç İngiliz değildir; sadece sandviç yaptığımız bir şeydir.
**Ödünleşim**: Yok — bu, sıfır ürün maliyetiyle konumlandırma değişikliğidir.

### Ortalama İçin Tasarlama (2. kural)
**Ne zaman**: Kullanıcı araştırması ve persona tasarımında.
**Nasıl**: Ortalama kullanıcı yoktur. Uç ihtiyaçlar için tasarlamak, ortalamayı da kapsar; tersi doğru değildir.
**Ödünleşim**: Kaynak yoğun. Ama ortalamaya göre tasarlanan ürün kimseye tam uymaz.

---

## Karar Süreci

### Veriyi Tek Girdi Yapma
**Ne zaman**: Model veya veri temelli bir karar alırken.
**Nasıl**: Sutherland'ın uyarısı: *"Büyük verinin hepsi aynı yerden gelir — geçmişten."* Yeni bir kampanya tarzı, tek bir başıboş değişken veya bir "kara kuğu" olayı, en iyi kalibre edilmiş modeli kaosa sürükler.
**Pratik kural**: Her veri temelli kararda sor — *"Modelin dışında kalan, ama açıkça önemli olan ne var?"* (Sutherland'ın örneği: bir adayın spor salonlarını doldurması, diğerinin seyrek kalabalık çekmesi — modele girmedi.)
**Ödünleşim**: Bu, veriyi reddetmek değil; **tek girdi olmaktan çıkarmak**.

### "Hipotezi Ayrıcalıklandırma"ya Karşı
**Ne zaman**: Ekip bir teoride birleştiğinde.
**Nasıl**: Sutherland'ın suç soruşturması analojisi — *(kitaptaki uzun alıntı bu açık kopyada yok)* Buna **"privileging the hypothesis"** denir.
Amanda Knox davası örneği: İlk şüphe ("hırsızlık sahnelendi") o kadar sıkı tutuldu ki sonraki tüm çelişkili kanıt bastırıldı veya paylaşılmadı. Gerçek açıklama: Pencereyi kırmanın amacı **içeri girmek değil, gürültü yapıp kimsenin olmadığını anlamaktı** — kolay kaçış mesafesinden.
**Ödünleşim**: Yok. [[commerce-digital-kahneman]] ch07'deki **premortem** bunun operasyonel aracıdır.

### Tamamen Öngörülebilir Olma
**Ne zaman**: Fiyatlandırma, müzakere ve rekabet stratejisinde.
**Nasıl**: *"Tamamen öngörülebilirsen, insanlar seni hacklemeyi öğrenir."*
- Her ay aynı tarihte indirim → müşteri indirimi bekler, tam fiyattan almaz
- Her müzakerede aynı taviz sırası → karşı taraf son teklifini bilir
- Sürekli aynı promosyon mekaniği → suistimal kalıpları oluşur
**Ödünleşim**: Öngörülemezlik, güvenilirlikle çatışabilir. **Fiyatta ve kalitede öngörülebilir ol; promosyonda ve rekabet hamlelerinde olma.**

### Önemsiz Olmaya Cesaret Et (10. kural)
**Ne zaman**: Bir fikrin "yeterince stratejik değil" diye elenme riski olduğunda.
**Nasıl**: Sutherland'ın havayolu örneği — Yönetim kurulu üç saat boyunca 13 Airbus A350 mi 11 Boeing 787 mi (her biri ~150 milyon $) alınacağını tartışır. Toplantı sonunda önlerine, **uçak göstermeyen**, bunun yerine uçakta servis edilen salatalıklı sandviçe ve scone'lara odaklanan bir reklam kampanyası konur.
> Bu **non-sense**'tir. Ama insanların yaklaşık **%90'ı** hangi tip uçakla uçtuğunu veya jet motorunun nasıl çalıştığını bilmez — ve havayolunun güvenlik ve kalitesi hakkında **ikramlara gösterdiği özenden** çok şey çıkarır.
**Ödünleşim**: MBA mezunlarıyla dolu bir toplantıda savunması utanç verici. Ama *"bu sense-making takıntısı pahalıya patlayabilir."*

---

---

## Anti-Desenler

- **Her çözümün ikna edici bir gerekçesi olmasını şart koşmak**: Sutherland'ın açık saldırısı buna. "Mantıklı bir gerekçe olmadan test edilemez" kuralı, kelebek etkilerini keşfetmeyi imkânsızlaştırır.
- **Veriyi tek girdi yapmak**: *"Büyük verinin hepsi aynı yerden gelir — geçmişten."* Yeni bir kampanya tarzı, tek bir başıboş değişken veya bir "kara kuğu" olayı, en iyi kalibre edilmiş modeli kaosa sürükler.
- **Modelin dışındaki olguları görmezden gelmek**: Sutherland'ın 2016 ABD seçim örneği — bir adayın her yerde spor salonlarını doldurması, diğerinin seyrek kalabalık çekmesi modelin dışındaydı ve modele hiç girmedi.
- **Bağlamı önemsiz saymak**: Evrensel yasa kurmak için bağlamı yok saymak zorundasın — ama bağlam, insanların nasıl düşündüğünü ve davrandığını belirleyen **en önemli** değişkendir.
- **Tamamen öngörülebilir olmak**: *"Tamamen öngörülebilirsen, insanlar seni hacklemeyi öğrenir."* Fiyatlandırma, müzakere ve rekabet stratejisinde geçerli.
- **"Rasyonel argüman eklemek her zaman yardımcı olur" varsaymak**: Zarf testinde tek rasyonel değişken bağışları **%30'dan fazla düşürdü**. Ekleyeceksen test et.
- **Sutherland'ı rasyonelliğe karşı okumak**: Kitap mantığın sağlıklı kullanımlarına değil, **mantıksal aşırılığa** (logical overreach) saldırır.

## Ticari Uygulamalar — Özet Tablo

| İlke | Uygulama |
|---|---|
| **Kelebek etkisi avı** | En yüksek getirili testler, bir mantık insanının test etmeyi düşünmeyeceği küçük ve "önemsiz" değişkenlerdir |
| **Algılanan değer ≠ ürün maliyeti** | Kaliteli zarf, ambalaj, sunum — ürünü değiştirmeden değeri artırır ([[commerce-digital-ariely]] ch09, ch10) |
| **"Rasyonel" mesajın riski** | Rasyonel argüman eklemek, duygusal/sosyal gerekçeyi bastırabilir |
| **Non-sense'i savunabilmek** | "Reklamlarımızda daha çok ördek olsun" demek zordur, "fiyatı düşürelim" kolaydır — ama ikincisi çok daha kârlı olabilir |
| **Fiyatı yükselterek satış artırma** | [[commerce-digital-cialdini]] "pahalı = iyi", [[commerce-digital-ariely]] ch10 plasebo fiyat |
| **Bağlam tasarımı** | Hendrick's cin + salatalık: sıfır ürün maliyetiyle çifte konumlandırma |
| **Ortalama için tasarlama** (2. kural) | Ortalama kullanıcı yoktur; uç ihtiyaçlar için tasarla |
| **Tersini de dene** (1. kural) | "Daha ucuz" işe yaramıyorsa "daha pahalı"yı test et |

---

## Sutherland'ın Kendi Kilit Sorusu

> **"Ürünümüz iyi satmıyor" diyen bir şirketin yönetim kurulunda hangisini önermek daha kolaydır?**
> **a) "Fiyatı düşürmeliyiz"**
> **b) "Reklamlarımızda daha çok ördek göstermeliyiz"**
>
> **Tabii ki birincisi — ama ikincisi aslında çok daha kârlı olabilir.**

Bu soru, becerinin pratik özüdür. Bir sonraki toplantıda "b" seçeneğini yazılı hâle getir ve test listesine ekle.
