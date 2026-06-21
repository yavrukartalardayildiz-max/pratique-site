# Pratique — Web Sitesi İçerik Paketi (tasarımcıya teslim)

> **Bu doküman nedir?** Siteyi sıfırdan tasarlayacak ekip için **eksiksiz içerik
> kaynağı**: marka, mesaj, bölüm bölüm hazır Türkçe metin, ROI hesaplayıcı mantığı,
> fiyat, SSS, görseller, iletişim ve SEO. Tasarım serbest; **metin ve yapı budur.**
> Çalışan referans (içeriğin canlı hali): https://yavrukartalardayildiz-max.github.io/pratique-site/

---

## 0) Marka & konumlandırma (önce bunu oku)

- **Ürün/şirket adı:** **Pratique** *(denizcilik terimi: "free pratique" = bir geminin limana girmesi için aldığı ilk sağlık/serbest giriş izni — bizim de yaptığımız iş: acentenin evrak iznini saniyeler içinde "serbest" bırakmak).*
- **Biz kimiz:** Pratique, **gemi acentelerine yazılım + destek sağlayan yapımcı/teknoloji şirketidir.** Acentelerin yerine geçmiyoruz; onları hızlandırıyoruz.
- **MSA Horizon kimdir:** **Geliştirme ortağımız ve ilk referansımız** (Tuzla/İstanbul gemi acentesi). Sistem onun gerçek belgeleriyle geliştirildi; **henüz günlük operasyonunda canlı kullanmıyor.** Sitede "geliştirme ortağı / vaka çalışması" olarak geçer — **biz (yapımcı) değiliz, müşterimiz de değil.**
- **Tek cümlelik vaat:** *WhatsApp'tan gelen pasaport ve uçuş PDF'leri → 60 saniyede OK-TO-BOARD mektubu + EK-1 formları, acentenin kendi antetli kağıdıyla, tamamen yerel.*
- **Kime satıyoruz:** Türkiye'deki küçük ve orta ölçekli gemi acenteleri (KOBİ). Karar verici = acente sahibi / operasyon sorumlusu. Hâlâ Excel + e-posta + WhatsApp ile çalışan, büyük platformlara (DA-Desk vb.) bütçesi yetmeyen taraf.
- **Ton:** Güven veren, somut, az-laf-çok-iş. Abartı yok; rakamla ve gerçek örnekle konuş. Operatörün dilinden (denizci/acente jargonu doğru kullanılmış). Türkçe-öncelikli.

---

## 1) Sitenin amacı & dönüşüm hedefi

**Tek birincil aksiyon (CTA):** *"Bir sonraki geminizin crew PDF'lerini WhatsApp'tan gönderin — ilk OK-TO-BOARD + EK-1'i kendi antetinizde 60 saniyede ücretsiz alın."* (kart yok, kurulum yok, taahhüt yok).

**İkincil aksiyonlar:** canlı demo videosunu izle · ROI hesapla · sunumu aç.

**Dönüşüm omurgası (bölüm sırası):** Hero → Demo (video) → Sorun → Çözüm → Nasıl çalışır → ROI → Moduller → Neden biz → Güven → Vaka çalışması → Fiyat → SSS → Son CTA → Footer.

---

## 2) İletişim & yasal (her sayfada erişilebilir olmalı)

- **WhatsApp Business (BİRİNCİL):** +90 536 792 01 58
  - Tıklanabilir link: `https://wa.me/905367920158?text=Bir%20sonraki%20gemimizin%20crew%20PDF'lerini%20g%C3%B6ndermek%20istiyoruz%20(Pratique%20%C3%BCcretsiz%20ilk%20mektup).`
- **E-posta:** yavrukartalardayildiz@gmail.com *(markalı e-posta hazır olunca değişir, ör. info@pratique...)*
- **KVKK / gizlilik notu (footer + SSS):** "Mürettebat verisi ve üretilen belgeler yerelde, acentenin makinesinde kalır. Pasaport görüntüsü yalnızca okunması için seçilen vision servisine gider; istenirse tamamen yerel OCR kullanılır. Hiçbir belge otomatik gönderilmez."
- **Footer künyesi:** "Pratique — gemi acenteleri için operasyon yazılımı. Geliştirme ortağı / ilk referans: MSA Horizon (Tuzla/İstanbul)."

---

## 3) SEO / meta

- **Title:** `Pratique — Gemi acentesi evrak yükünü 60 saniyeye indirir`
- **Meta description:** `WhatsApp'tan gelen pasaport ve uçuş PDF'leri → 60 saniyede OK-TO-BOARD + EK-1, kendi antetinizde. Gemi acenteleri için Türkiye-öncelikli operasyon yazılımı. Sabit aylık fiyat.`
- **Anahtar kelimeler:** gemi acentesi yazılımı, OK to board, EK-1 vize formu, crew change, disbursement account PDA FDA, denizci evrak otomasyonu, port agency software Türkiye.
- **OG görsel:** demo videosunun bir karesi ya da hero görseli (lacivert + altın).
- **Dil:** `lang="tr"`. Türkçe karakterler (İ/ı/Ş/ş/Ğ/ğ/Ç/Ü/Ö) her fontta düzgün görünmeli.

---

## 4) BÖLÜM BÖLÜM METİN (hazır, kopyala-kullan)

### 4.1 Üst menü (nav)
Logo: ⚓ **Pratique** · Linkler: Demo · ROI · Moduller · Fiyat · Sunum · **[CTA buton: WhatsApp'tan yaz]**

### 4.2 Hero
- **Üst rozet (eyebrow):** `⚓ Gemi acenteleri için operasyon OS · Türkiye-öncelikli`
- **Başlık (H1):** **WhatsApp'tan gelen pasaportlar, 60 saniyede OK-TO-BOARD mektubuna dönüşsün.** *("60 saniyede" vurgulu/altın.)*
- **Alt başlık:** Pratique pasaport + denizci cüzdanı + uçuş PDF'lerini okur; OK-TO-BOARD mektubunuzu ve her denizci için EK-1 formunu **kendi antetli kağıdınız, logonuz ve kaşenizle** dakikada hazırlar. Tamamen yerel, tamamen Türkçe.
- **Mikro-güven satırı:** Maritime Single Window 2024'ten beri zorunlu: *bir kez gir, her yere doldur.*
- **CTA:** Birincil → "Canlı demoyu izle" · İkincil → "Sunumu aç"

### 4.3 Demo (sayfanın kalbi)
- **Başlık:** PDF'i bırak, mektubu al. Sayfada, gerçekten, 60 saniyede.
- **Metin:** İddiayı satın almadan önce kanıtlayalım. Üstte gerçek uygulama kaydı (video); altında bugünkü yöntem (sol) vs Pratique (sağ). Sistem hiçbir alanı sessizce düzeltmez — çelişkiyi kırmızı gösterir, onay sizde.
- **Bileşen:** `demo.mp4` videosu (19 sn, repoda mevcut) + "Önce/Sonra" iki kolon: ÖNCE = Excel/WhatsApp ~1 saat; SONRA = sürükle-bırak → 60 sn.

### 4.4 Sorun
- **Başlık:** Aynı denizciyi günde beş kez yazıyorsunuz. Bir hatada da gemi kalkmıyor.
- **Metin:** Crew change acentenin en pahalı, en gergin işi: denizci başına 10-14 gün, $2.000-4.000'lık hareketli parça. Tek bir hane şaştığında (S00044582 yerine S00048582) denizci uçağa binemez, gemi limanda bekler.
- **4 acı maddesi (kırmızı ✕):**
  1. **"Bir bilgi, beş araç" parçalanması** — Aynı isim/numara: WhatsApp → Excel → antetli mektup → devlet portalı → muhasebe. Beş kez elle.
  2. **Kaçan süreler sessiz bir yük** — Pasaport/cüzdan/vize; biri fark edilmeden dolunca uçuş iptal, gemi gecikir.
  3. **PDA/FDA disbursement hataları** — ±%2-3 tutturmak zorundasınız; tek satır hata principal güvenini yer.
  4. **Crew change = en yüksek yük** — Denizci başına $2-4k, 10-14 gün, çok taraflı koordinasyon maratonu.

### 4.5 Çözüm
- **Başlık:** Bir kez tara. Her yere doldur.
- **Metin:** Pratique pasaport ve cüzdanın fotoğrafını vision ile okur, MRZ'yi ICAO çek-digit'leriyle doğrular, uçuştan tarih/sefer çeker. Tek bir Port-Call kaydı oluşur ve OKTB'ye, her EK-1'e, mürettebat veritabanına aynı anda akar — çıktı sizin gerçek antetinizde.
- **4'lü rakam bandı:** `~60 sn` (OKTB+EK-1 üretimi) · `~%90` (örnek taramalarda alan doğruluğu — 3 belge, küçük örneklem) · `%100` (yerel — pasaportlar makinenizde) · `±1 hane` (MRZ çek-digit yakalama).

### 4.6 Nasıl çalışır (3 adım)
1. **Bırak** — WhatsApp'tan gelen pasaport, cüzdan ve uçuş PDF'lerini tek alana sürükleyin.
2. **İncele** — Sistem alanları doldurur, MRZ'yi doğrular, şüpheliyi kırmızı işaretler; düzenlenebilir tabloda tek tıkla onaylarsınız.
3. **Üret** — OKTB (tek dosya, tüm mürettebat) + her denizci için EK-1 kendi antetinizde Word olarak iner. *Eğitim yok, kurulum yok.*

### 4.7 ROI hesaplayıcı (interaktif — bkz. §5)
- **Başlık:** Acenteniz ayda ne kazanır? Kendi rakamlarınızla hesaplayın.
- **Metin:** Asıl kazanç hata maliyetinde: tek bir kaçan süre ya da yanlış cüzdan numarası, çoğu zaman aylık ücretinizin kat kat üstünde.

### 4.8 Moduller (dürüst durum rozetleriyle)
- **Başlık:** Bugün çalışan çekirdek. Vaporware değil — dürüst yol haritası.
- **VAR (yeşil):** OKTB + EK-1 · Vision + MRZ · Mürettebat DB · Süre Takvimi (90/60/30/7) · Yedek Parça (3-sayfa Excel) · **Disbursement (PDA/FDA)**.
- **SIRADA (cyan):** WhatsApp intake · Principal canlı link.
- **YOL HARİTASI (gri):** MSW/FAL tek pencere · Dijital SOF/NOR · AIS ETA radar.

### 4.9 Neden biz
- **Başlık:** DA-Desk değiliz. Sizi fiyatla dışlamayan, Türkçe konuşan taraf biziz.
- **3 kart:** 🇹🇷 **Türkiye-öncelikli** (EK-1, GABS, MSW-TR, sizin ev şablonunuz) · 🔒 **Yerel & gizli** (pasaportlar makinenizde) · 💸 **Dürüst sabit fiyat** (port-call sayacı yok).
- **Karşılaştırma tablosu:**

  | | Büyük platform | **Pratique** |
  |---|---|---|
  | Fiyat | Custom / port-call başı | **Sabit $149–$390/ay** |
  | Türkiye-yerel (EK-1/GABS/MSW) | Çeviri / yok | **Yerleşik** |
  | Kurulum | Haftalar / IT projesi | **Çift tıkla, dakikalar** |
  | Hedef | Büyük acente / principal | **KOBİ acente** |

### 4.10 Güven
- **Başlık:** Sistem "düzeltmez" — size gösterir. Onay sizde, risk sıfır.
- **Metin:** MRZ ile basılı zon çeliştiğinde alan kırmızı işaretlenir; siz onaylamadan mektup üretilmez. Gerçek sahada cüzdan no farkını (S00044582 ↔ S00048582) böyle yakaladı — elle yazsanız gözden kaçardı.
- **Vurgu cümlesi:** **Hız makineden, karar sizden.**

### 4.11 Vaka çalışması (DÜRÜSTLÜK KRİTİK — bu çerçeveye sadık kal)
- **Başlık:** Laboratuvar prototipi değil: gerçek bir acentenin belgeleriyle, sahadaki ihtiyaca göre geliştirildi.
- **Geliştirme ortağı kartı (rozet: "GELİŞTİRME ORTAĞI / İLK REFERANS"):** **MSA Horizon** (gemi acentesi · Tuzla/İstanbul). MSA Horizon ile birlikte geliştirildi. Sistem, MSA Horizon'un kendi gerçek belgeleri (antetli OKTB ve EK-1 şablonları, bir Lausanne crew-change işi ve gerçek belge taramaları) temel alınarak kuruldu. Üretilen mektuplar, elle hazırlanan çıktılarla **birebir** eşleşecek biçimde tasarlandı ve golden test ile doğrulandı. WhatsApp'tan gelen PDF'ler, acentenin kendi antetli kağıdı, logosu ve kaşesiyle yaklaşık 60 saniyede OKTB ve EK-1 olarak üretilir. **MSA Horizon, sistemi henüz günlük operasyonuna almamıştır; bu işbirliği bir pilot/geliştirme ortaklığıdır.** (ASLA "müşterimiz kullanıyor / sahada çalışıyor / canlı pilot" deme.)
  - Rakamlar: **~1 sa → ~60 sn** (örnek bir işteki crew-change evrak süresi) · **±1 hane** (MRZ ile yakalanan gerçek hata).
  - **Net çizgi:** *Pratique, gemi acentelerine yazılım ve destek sağlayan yapımcı/teknoloji şirketidir; MSA Horizon ise geliştirme ortağımız ve ilk referansımızdır. Saha ölçümleri küçük bir örneklem üzerinden alınmıştır.*
- **Pazar fırsatı kartı:** `150+` VDA üyesi acente (TR) · `~63k` yıllık port call (TR) · `$7.2B` küresel port-agency pazarı · `%4.7` yıllık büyüme.

### 4.12 Fiyat
- **Başlık:** Sabit aylık fiyat. Port-call sayacı yok, sürpriz fatura yok.
- **Starter — $149/ay** (Başlangıç): Tek acente, 1-3 koltuk · OKTB + EK-1 (kendi antetinizde) · Vision + MRZ · Mürettebat DB · Süre Takvimi.
- **Pro — $390/ay** (⭐ En çok tercih edilen, vurgulu kart): Starter'daki her şey + çoklu gemi · Yedek Parça + Disbursement (PDA/FDA) · Excel in/out · WhatsApp intake · Öncelikli destek.
- **Filo / Kurumsal — Özel:** Pro'daki her şey + çok ofis · Principal canlı portalı · MSW/FAL entegrasyonu · SLA + özel onboarding.
- **Alt not:** Geri ödeme ayda 1 crew change. Yıllık ~$9-14k iş gücü tasarrufunun çok altında.

### 4.13 SSS (akordeon)
1. **Pasaport verilerimiz buluta mı gidiyor? KVKK?** → Mürettebat veritabanı ve üretilen belgeler makinenizde, yerelde kalır — buluta yüklenmez. Yalnızca pasaport görüntüsü, okunması için seçtiğiniz vision API'ye gider; yerel OCR'a da düşülebilir. Hiçbir belge otomatik gönderilmez.
2. **Mektup gerçekten bizim antetimizde mi çıkıyor?** → Evet, gerçek antetli kağıdınızda. Logonuz, kaşeniz, dipnotunuz ve ev kullandığınız crew tablonuz birebir korunur. EK-1 de resmi vize formuna birebir.
3. **Vision yanlış okursa? Hatalı mektup göndermekten korkuyorum.** → Sistem hiçbir alanı sessizce düzeltmez. MRZ ICAO çek-digit'leriyle doğrulanır; iki kaynak çeliştiğinde alan kırmızıyla işaretlenir, siz onaylamadan mektup üretilmez.
4. **Mevcut Excel dosyalarımı baştan mı kurmam gerekecek?** → Hayır. Yedek parça modülü zaten kullandığınız 3 sayfalık Excel formatına (VARIS/ZEYPORT/TESLIM) aynen yazar ve ondan okur.
5. **Fiyat port-call başına mı? Yoğun aylarda fatura patlar mı?** → Hayır, düz aylık tarife: Starter ~$149, Pro ~$390, Filo özel. Port-call sayacı yok; faturanız sabit.
6. **Çalıştırması karmaşık mı?** → Çift tıkla açılır (start.command), terminal gerekmez; uygulama makinenizde yerel çalışır.
7. **EK-1, GABS, MSW gibi TR süreçlerini biliyor mu?** → Evet, Pratique Türkiye-öncelikli kuruldu. EK-1, GABS ve Maritime Single Window mantığı sisteme yerleşik — yabancı bir platformu çevirmiyoruz.
8. **Denemesi gerçekten ücretsiz mi?** → Evet. Bir sonraki geminizin mürettebat PDF'lerini gönderin; ilk OK-TO-BOARD + EK-1'inizi kendi antetinizde 60 saniyede ücretsiz üretelim. Kart yok, sözleşme yok, kurulum yok.

### 4.14 Son CTA
- **Başlık:** Bir sonraki geminizin crew PDF'lerini gönderin. 60 saniyede görün.
- **Metin:** Risk yok: PDF'leri WhatsApp'tan gönderin, ilk OKTB + EK-1'i antetinizle üretelim. Beğenirseniz Starter'la başlarsınız; beğenmezseniz elinizde çalışan bir mektup kalır.
- **CTA:** **[WhatsApp'tan gönder → +90 536 792 01 58]** · İkincil: Sunumu aç.

### 4.15 Footer
⚓ Pratique · Gemi acenteleri için operasyon yazılımı · Geliştirme ortağı / ilk referans: MSA Horizon (Tuzla/İstanbul) · WhatsApp: +90 536 792 01 58 · KVKK-uyumlu, yerel veri · Sunum linki.

---

## 5) ROI hesaplayıcı — mantık (geliştiriciye)

**Girişler (kaydırıcı):** `pc` = aylık crew change/port-call (varsayılan 8) · `cr` = işlem başına denizci (4) · `hr` = operasyon saatlik maliyet USD (14).

**Formül:**
```
saat   = pc × (2.5 + 0.25 × max(0, cr − 3))      // aylık kazanılan saat
direkt = saat × hr                                // doğrudan iş gücü ($/ay)
efektif= direkt × 2.5                             // kaçan süre + yeniden iş + önlenen hata çarpanı
payback= efektif ÷ 390                            // Pro aylık ücretinin kaç katı
TL     ≈ efektif × 34                             // yaklaşık (kur değişir; "≈" göster)
```
**Çıktı kartı:** büyük "Aylık efektif değer = $efektif" + satırlar (kazanılan saat, doğrudan iş gücü, ≈TL) + yeşil rozet "Örnek hesaba göre Pro ücretinin ~{payback} katı — birkaç crew change'de geri ödeyebilir." + **zorunlu uyarı (küçük punto):** "Bu, girdiğiniz değerlere dayalı illüstratif bir projeksiyondur; bağlayıcı taahhüt değildir. Gerçek kazanç acentenizin hacmine ve önlenen hatalara göre değişir. Önlenen tek bir hata, crew change başına 2.000-4.000 USD'lik bir riski ortadan kaldırabilir."

---

## 6) Görsel varlıklar (repoda mevcut / üretilecek)

- **`demo.mp4`** — 19 sn gerçek uygulama kaydı (sentetik mürettebat, PII yok). Demo bölümüne göm.
- **Logo:** ⚓ çapa, altın yuvarlatılmış kare içinde, "Pratique" Sora yazı tipi. *(İsteğe göre profesyonel logo yapılabilir.)*
- **Ekran görüntüleri:** Genel Bakış, Yeni İşlem (incele), Süre Takvimi, Disbursement (PDA/FDA) — uygulamadan alınabilir.
- **OG/sosyal kart:** lacivert zemin + altın "60 saniyede" + ⚓.

## 7) Tasarım yön notu (tasarımcı serbest — sadece referans)
Cinematik "premium B2B": koyu lacivert zemin (#08111f) + **az ve değerli altın** (#f2c14e — sadece CTA, tek vurgu kelime, marka, kanıt rakamı), kicker'larda cyan (#59c7f2). Başlık/rakam fontu **Sora**, gövde **Inter**. Glass kartlar, yumuşak gölge, tek "deniz feneri" altın ışıma. Durum rozetleri (VAR/SIRADA/YOL HARİTASI) her modül kartında = dürüstlük sinyali. Kırmızı sadece hata/uyarı. Beyaz-on-altın YOK.

---

## 8) Pitch / sunum içeriği (12 slayt — ayrı dosya: pitch.html)
1. **Sorun** — Crew change en maliyetli ve en hata riskli süreç: aynı bilgi beş ayrı yere elle giriliyor, tek hane hatası gemiyi geciktiriyor.
2. **Maliyet** — Aynı veriyi 5 yere giriyorsunuz; bir tarih kaçarsa $2.000-4.000.
3. **Kama** — 1 saat → 60 saniye, önce/sonra.
4. **3 adım** — Bırak/Doğrula/Üret; eğitim yok.
5. **Güven** — Sizin antetiniz, sizin kaşeniz, pasaportlar makinenizde.
6. **Risk sıfır** — Sistem düzeltmez, gösterir; onay sizde.
7. **Vizyon** — Bir kez gir, her yere doldur; bugünkü mektup → yarının OS'i.
8. **Konum** — DA-Desk değiliz; Türkçe konuşan, KOBİ'yi dışlamayan taraf.
9. **Fiyat** — Sabit aylık; Starter/Pro/Filo.
10. **Kanıt + pazar** — MSA Horizon ile geliştirildi (geliştirme ortağı, henüz canlı değil); golden test ile doğrulandı. Sektör: 150+ acente, ~63k port call, $7.2B (müşterimiz değil, pazar verisi).
11. **Risksiz aksiyon** — Bir sonraki geminizin PDF'lerini gönderin; ilk mektup bizden.
12. **Kapanış** — Pratique marka + iletişim (WhatsApp +90 536 792 01 58).
