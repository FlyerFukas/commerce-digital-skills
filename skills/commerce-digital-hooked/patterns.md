# Hooked — Uygulanabilir Ürün Desenleri

Her desen: ne zaman kullanılır · nasıl uygulanır · ödünleşimler.

---

## Tetikleyici Desenleri

### Sahipli Tetikleyici Merdiveni
**Ne zaman**: Alışkanlık henüz kurulmamışken tekrar etkileşim gerektiğinde.
**Nasıl**: Kademeli, agresifleşmeyen bir zincir kur — (1) uygulama ikonu üzerinde rozet → (2) push bildirimi → (3) gün kaçırılırsa "daha kolay bir plan dene" mesajı → (4) birkaç gün kaçırılırsa e-posta ile geri çağırma. (YouVersion'ın kullandığı tam merdiven.)
**Ödünleşim**: Her basamak izin (opt-in) gerektirir. Yoğunluk artınca bildirim kapatma/uninstall riski. Sıklığı kohort verisiyle kalibre et, varsayımla değil.

### Bağlamsal Zamanlama (Context Triggering)
**Ne zaman**: Dahili tetikleyicinin ne zaman ateşleneceğini öngörebiliyorsan.
**Nasıl**: Harici tetikleyiciyi o ana zamansal olarak kilitle. Any.do takvime bağlanır ve **toplantı biter bitmez** bildirim gönderir — "görevi unutma endişesi"nin doğduğu an.
**Ödünleşim**: Veri erişimi izni gerekir (KVKK açık rıza). Tahmin yanlışsa alaka düşer ve bildirim gürültüye dönüşür.

### 5 Neden ile Dahili Tetikleyici Kazısı
**Ne zaman**: Ürün konumlandırması duygusal değil işlevsel dille yazıldıysa.
**Nasıl**: Persona için "neden?" zincirini duyguya ulaşana kadar sür (genelde 5. adım). Sonucu tek cümleye indir: *"Kullanıcı her ___ hissettiğinde, ___ yapar."*
**Ödünleşim**: Zincirdeki varsayımlar sonucu değiştirir. Gerçek kullanıcı gözlemiyle doğrula; anketle değil.

---

## Eylem (Yetenek) Desenleri

### Tek CTA Kuralı
**Ne zaman**: Her harici tetikleyicide (e-posta, push, açılış ekranı).
**Nasıl**: Tek net eylem çağrısı bırak, rakip çağrıları sil. Mint hesap uyarısı e-postasında sadece "Oturum aç" var — bakiye, kredi kartı teklifi, hedef belirleme kasten çıkarılmış.
**Ödünleşim**: Diğer özelliklerin keşfi düşer. Onları ayrı bir döngüye taşı.

### Adım Silme (Hauptly)
**Ne zaman**: Dönüşüm hunisinde düşüş varsa.
**Nasıl**: (1) Kullanma nedenini anla. (2) Niyetten sonuca giden **tüm adımları listele**. (3) En basit sürece kadar sil. Dahili tetikleyiciden ödüle kadar adım say; rakiplerle kıyasla.
**Ödünleşim**: Silinen her adım bir veri noktası veya kontrol de siliyor olabilir. Önce sil, sonra gerekliyse geri ekle.

### Parçalama (Chunking)
**Ne zaman**: Görev korkutucu veya uzunsa (uzun içerik, karmaşık kurulum, öğrenme eğrisi).
**Nasıl**: Isırık büyüklüğünde günlük birimlere böl. Yeni başlayana en küçük birimi ver (YouVersion: bir ilham cümlesi + birkaç kısa ayet).
**Ödünleşim**: İleri kullanıcı yavaş bulabilir — hızlı yol (skip) sun.

### İlginç Olanı Öne Yükleme
**Ne zaman**: İçerik sırası kanonik ama tamamlama oranı düşükse.
**Nasıl**: Veriye göre ilginç bölümleri öne, sıkıcı kısımları sonraya al. (YouVersion tam bunu yaptı.)
**Ödünleşim**: İçeriğin doğal mantığı bozulabilir; sıralı bağımlılık varsa uygulanamaz.

### Modalite Alternatifi
**Ne zaman**: Kullanıcıların en kıt kaynağı farklılaşıyorsa (zaman, dikkat, bağlam).
**Nasıl**: Aynı değeri ikinci bir kanaldan sun — okuma yerine dinleme, yazma yerine sesli not.
**Ödünleşim**: Üretim ve bakım maliyeti iki katına çıkar.

### Sürtünmesiz Kimlik (Sosyal Giriş)
**Ne zaman**: Kayıt hunisinde mobilde yüksek terk varsa.
**Nasıl**: E-posta + şifre + isim + telefon yerine mevcut kimlik sağlayıcı.
**Ödünleşim**: Gizlilik endişesi olan kullanıcıda **beyin döngüsü ekler** — sürtünmeyi azaltmaz artırır. Her zaman klasik seçeneği yanında bırak.

### Sonsuz Kaydırma
**Ne zaman**: Keşif odaklı, av ödülü veren feed'lerde.
**Nasıl**: Sayfa sonuna yaklaşınca otomatik yükle; kesik görsellerle bir sonrakine dair ipucu bırak (Pinterest).
**Ödünleşim**: Kullanıcıya doğal durma noktası bırakmaz — **bu tam olarak DSA m.25'in hedefindeki desendir**. Bitiş noktası, "bugünkü özet bitti" ekranı veya kullanım sınırı ayarı ekle.

---

## Değişken Ödül Desenleri

### Üç Ödül Haritası
**Ne zaman**: Ürünün ödül katmanını tasarlarken veya boşluğu teşhis ederken.
**Nasıl**: Üç sütun çiz — Kabile (başkalarından alınan haz) / Av (eşya, para, bilgi) / Benlik (ustalık, tamamlama, yetkinlik). Ürününde her sütunda ne var? Boş sütun fırsattır.
**Ödünleşim**: Hepsini doldurmak zorunda değilsin; **eşleşmeyen ödül eklemek zarar verir** (Mahalo).

### Zincir / Seri (Streak)
**Ne zaman**: Günlük sıklık hedefliyorsan.
**Nasıl**: Tamamlanan günleri görsel olarak biriktir. Bahşedilmiş ilerlemeyle birleştir: kullanıcıyı sıfırdan değil, birkaç işaretle başlat.
**Ödünleşim**: Zincir kırılınca terk riski yükselir — **"zincir kurtarma" (streak freeze)** mekaniği koy. Aşırı baskı MyFitnessPal etkisi yaratır.

### Bahşedilmiş İlerleme
**Ne zaman**: Onboarding veya profil tamamlama gibi çok adımlı görevlerde.
**Nasıl**: Kullanıcıyı %0'dan değil, hediye edilmiş ilerlemeyle başlat. Araba yıkama deneyi: 8 boş kare yerine 10 kare + 2 hediye delik → tamamlama **%82 daha yüksek**. LinkedIn "Profil Gücü" çubuğu **sayısal ölçek içermez** — ilerleme algısını hızlandırır.
**Ödünleşim**: İlerleme sahteyse ve kullanıcı fark ederse güven kaybı. Hediye gerçek bir adımı karşılamalı.

### Özerklik Koruyucu Dil
**Ne zaman**: Her davranış talebinde, özellikle davranış değişikliği isteyen ürünlerde.
**Nasıl**: Talebin sonuna seçme özgürlüğünü teyit eden ifade ekle ("ama kabul etmekte ya da reddetmekte özgürsünüz"). 22.000+ katılımcılı 42 çalışmalık meta-analiz: "evet" olasılığını **ikiye katlıyor**.
**Ödünleşim**: Samimiyetsiz olursa ters teper — gerçekten kolay bir "hayır" yolu bırakman gerekir.

### Opt-in Değişiklik Duyurusu
**Ne zaman**: Gizlilik veya görünürlük etkileyen yeni özellik çıkarırken.
**Nasıl**: **Asla otomatik dahil etme.** Önce duyur, sonra opt-in yap. (Quora "views" tam bunu yapmadı ve isyan çıktı; birkaç hafta sonra geri aldı.)
**Ödünleşim**: Benimseme oranı düşer — ama güven kaybı çok daha pahalıdır, ve KVKK/GDPR açısından zorunludur.

### Sonsuz Değişkenliğe Geçiş
**Ne zaman**: Etkileşim zamanla düşüyorsa ve içerik senin ürettiğin, sonlu bir havuzdan geliyorsa.
**Nasıl**: Değişkenlik kaynağını **kullanıcılara veya kullanıcılar arası etkileşime** taşı. İçerik tüketimi → içerik üretimi. Tek oyunculu → çok oyunculu.
**Ödünleşim**: Moderasyon, kalite kontrolü ve topluluk yönetimi maliyeti doğar. Aksi hâlde stüdyo modeline geç: sürekli yeni içerik boru hattı finanse et.

---

## Yatırım Desenleri

### Ödülden Sonra İste (Post-Reward Ask)
**Ne zaman**: Her yatırım talebinde.
**Nasıl**: Akışı denetle — kullanıcı değişken ödülü aldı mı, sonra mı istiyorsun? Stanford deneyi: yardımsever bilgisayar verilen grup makinesi için **neredeyse iki kat** iş yaptı.
**Ödünleşim**: Yok — bu sıralama kuralıdır. Tersi basitçe çalışmaz.

### Aşamalı İş Parçaları (Progressive Bits of Work)
**Ne zaman**: İlk döngüde yatırım alınamıyorsa.
**Nasıl**: En küçük yatırımla başla (bir tercih işaretle, bir kişi takip et), ardışık döngülerde zorluğu artır.
**Ödünleşim**: Depolanan değer yavaş birikir; erken terk riski ilk döngülerde yüksek kalır.

### Depolanan Değer Katmanı
**Ne zaman**: Geçiş maliyeti düşük ve rakip kolayca klonlayabiliyorsa.
**Nasıl**: Beş biçimden en az birini kur — İçerik · Veri · Takipçi · İtibar · Beceri. Her biri **aktarılamaz** olmalı.
**Ödünleşim**: Kilit etkisi yarattığı için ürünü geliştirmeyi bırakma cazibesi doğar; bu uzun vadede itibar riskidir. Ayrıca veri taşınabilirliği (GDPR m.20) yasal bir hak.

### Sonraki Tetikleyiciyi Yükleme
**Ne zaman**: Her Kanca döngüsünün sonunda.
**Nasıl**: Yatırımın kendisi bir sonraki harici tetikleyiciyi kursun (takvim izni → toplantı sonrası bildirim; takip → yeni gönderi bildirimi; kaydetme → hatırlatma).
**Ödünleşim**: Yükleme kullanıcıya açıkça anlatılmalı; gizli kurulan tetikleyici karanlık desendir.

---

## Büyüme Desenleri

### İlişki Tetikleyicisi (temiz sürüm)
**Ne zaman**: Ürün başkalarıyla birlikte daha değerliyse (PayPal deseni: birinin sana para göndermesi hesap açmak için güçlü teşvik).
**Nasıl**: Paylaşımı kullanıcının **kimlik ifadesine** bağla — insanlar ürününü değil kendilerini paylaşır. YouVersion "Günün Ayetini Paylaş": tek tık, 24 saatte 200.000 paylaşım.
**Ödünleşim**: Kandırarak davet ettirmek (**karanlık desen**) kısa vadeli büyüme, uzun vadeli güven yıkımı getirir.

### Süper Düğüm Araçlandırma
**Ne zaman**: Kullanıcıların doğal olarak kümelendiği gruplar ve lider figürler varsa.
**Nasıl**: Lidere kendi araçlarını ver (YouVersion vaizlere vaazlarını uygulamaya girme imkânı verdi; cemaat gerçek zamanlı takip etti). Lider bağlandığında ağ takip eder.
**Ödünleşim**: Liderin kaybı topluca kayıp demektir; tek noktaya bağımlılık riski.

### Viral Döngü Süresini Kısaltma
**Ne zaman**: Büyüme yavaşsa ve ürün paylaşılabilirse.
**Nasıl**: Bir kullanıcının başkasını davet etmesi için geçen süreyi ölç ve **kısalt**. Skok: 2 günden 1 güne inince 20 günde 20.470 → 20.000.000 kullanıcı.
**Ödünleşim**: Aciliyeti yapay olarak artırma baskısı karanlık desene kayar.
