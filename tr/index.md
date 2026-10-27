---
title: Bilexis - Gizlilik Politikası
permalink: /tr/
---

<div style="position: fixed; top: 16px; right: 16px; z-index: 100;">
  <a href="{{ '/en/' | relative_url }}" style="text-decoration: none; padding: 6px 14px; border: 1px solid #ccc; border-radius: 6px; font-size: 14px; color: #333; background: #fff;">🇬🇧 English</a>
</div>

# Gizlilik Politikası

Yürürlük Tarihi: 2026-03-02
Son Güncelleme: 2026-10-27

Bu Gizlilik Politikası, **Bilexis: İngilizce Öğren** uygulamasının ("Uygulama") kullanıcı gizliliğine yaklaşımını açıklar.

## Kısa Özet
- Uygulama, kullanıcıların hesap oluşturmasına (veya misafir olarak devam etmesine) izin verir ve **ilerlemenizi ve tercihlerinizi** güvenli sunucularımıza senkronize eder.
- Hesap oluşturma, giriş ve şifre sıfırlama için temel **kimlik bilgileri** (e-posta gibi) toplarız.
- İlerleme ve tercih bilgileri (ör. seçilen dil, tamamlanan dersler) cihazlar arasında kesintisiz bir deneyim sağlamak için **sunucularımızda saklanır**.
- Konuşma alıştırmalarında, ne söylediğinizi anlamak için **sesiniz işlenir**. İnternete bağlıyken ses, konuşma tanıma sağlayıcımıza (ElevenLabs) aktarılır; çevrimdışıyken tanıma cihazınızda yapılır. Ses kayıtlarınızı saklamayız.
- Uygulama; kimlik doğrulama (Google, Apple), içerik sunumu (gömülü YouTube videoları), **konuşma tanıma (ElevenLabs)**, **abonelik ve uygulama içi satın alımlar (Adapty)**, **ürün analitiği (Firebase Analytics)**, **çökme raporlama (Firebase Crashlytics)**, **anlık bildirimler (Firebase Cloud Messaging)** ve **reklam (Google AdMob)** için **üçüncü taraf hizmetler** kullanır.
- Uygulama, reklam kimliğinize (IDFA/GAID) dayalı kişiselleştirilmiş reklamlar da dahil olmak üzere **reklamlar gösterir**; bu, onay tercihinize tabidir (aşağıdaki "Reklam ve Takip" bölümüne bakın).
- Kişisel verilerinizi üçüncü taraflara **satmayız**.

## Kapsam
Bu politika, Uygulamanın çalışma şeklinden kaynaklanabilecek gizlilik etkilerini kapsar.
Uygulama içindeki bir bağlantı veya gömülü içerik üçüncü taraf bir hizmete yönlendiriyorsa (ör. YouTube), ilgili hizmetin kendi gizlilik politikası geçerlidir.

## Topladığımız Veriler
Uygulama, temel işlevselliğini sağlamak için aşağıdaki veri kategorilerini toplar:
- **Kimlik Bilgileri:** E-posta adresi ve şifre (doğrudan kayıt olunuyorsa) veya üçüncü taraf kimlik doğrulama hizmetleri (Google ile Giriş, Apple ile Giriş) tarafından sağlanan temel profil bilgileri (ad, e-posta). Misafir kullanıcılar kimlik bilgisi vermeden Uygulamayı kullanabilir.
- **Kullanıcı Kimliği:** İlerlemenizi, tercihlerinizi ve abonelik durumunuzu hesabınızla ilişkilendirmek için kullanılan dahili bir hesap tanımlayıcısı.
- **Uygulama Kullanımı ve İlerleme Verisi:** Uygulama içi ilerleme durumu (ör. tamamlanan dersler, alıştırma cevapları ve sonuçları, çalışma süresi, seriler) ve uygulama tercihleri (ör. seçilen dil, seçilen seviye). Uygulamayı geliştirmek amacıyla özellik kullanımı Firebase Analytics ile de ölçülür.
- **Ses Verisi (Konuşma Alıştırmaları):** Bir konuşma alıştırmasında mikrofonu kullandığınızda sesiniz metne dönüştürülür. İnternete bağlıysanız ses, cihazınızdan doğrudan konuşma tanıma sağlayıcımıza (ElevenLabs) aktarılır ve sunucularımızda saklanmaz; çevrimdışıysanız cihazınızın yerleşik konuşma tanıma özelliği kullanılır. Tanınan metin, alıştırma cevabınız olarak kaydedilir.
- **Konuşma Tanıma Teşhis Verileri:** Tanıma sorunlarını tespit edip düzeltmek için her dinleme oturumuna ait teknik bilgiler (ör. kullanılan tanıma motoru, ses sinyal seviyesi, bağlantı süreleri, oturumun nasıl sona erdiği, cihaz modeli, işletim sistemi sürümü ve uygulama sürümü). Bu veriler ses kaydı içermez.
- **Çökme ve Teşhis Verileri:** Uygulama çöker veya bir hatayla karşılaşırsa, sorunu düzeltebilmemiz için Firebase Crashlytics bir çökme raporu (ör. hata izi, cihaz modeli, işletim sistemi sürümü, uygulama sürümü) toplar.
- **Reklam Kimliği:** Cihazınızın reklam kimliği (iOS'ta IDFA, Android'de reklam kimliği), onay verirseniz kişiselleştirilmiş reklamlar dahil reklamları göstermek ve ölçmek için Google AdMob tarafından kullanılır.
- **Cihaz Tanımlayıcısı:** Platformun sağladığı bir cihaz tanımlayıcısı (Android'de Android ID, iOS'ta identifierForVendor), uygulama içi davet/referans sisteminin kötüye kullanımını önlemek (ör. aynı cihazın birden fazla davet ödülü talep etmesini tespit etmek) için kullanılır. Sunucularımız bu değerin yalnızca geri döndürülemez (hash'lenmiş) bir biçimini saklar.
- **Anlık Bildirim Belirteci:** Cihazınıza bildirim gönderebilmemizi sağlayan bir Firebase Cloud Messaging belirteci (token).
- **Satın Alma Geçmişi:** Premium özellikleri açmak ve satın alımları cihazlarınız arasında geri yüklemek için abonelik sağlayıcımız (Adapty) aracılığıyla yönetilen abonelik ve satın alma durumu.
- **Cihaz Bilgileri:** Kimlik doğrulama ve oturum yönetimi için kullanılan güvenli belirteçler (token) ve saat diliminiz (günlük çalışma sınırlarını ve hatırlatma saatlerini hesaplamak için).

Uygulama aşağıdakileri **toplamaz**:
- Hassas veya yaklaşık konum verisi
- Kart numarası gibi finansal bilgiler (ödemeler Apple/Google ve abonelik sağlayıcımız tarafından işlenir; kart bilgilerinizi almayız veya saklamayız)
- Sağlık/hassas kişisel veri
- Kişiler, fotoğraflar/medya veya dosyalar
- Ses kayıtları (sesiniz yalnızca tanıma için işlenir, saklanmaz)

## Verileri Nasıl Kullanıyoruz
Topladığımız veriler yalnızca aşağıdaki amaçlarla kullanılır:
- Kullanıcı hesabınızı oluşturmak ve yönetmek (kimlik doğrulama ve şifre sıfırlama dahil).
- Öğrenme ilerlemenizi ve tercihlerinizi cihazlarınız arasında senkronize tutmak.
- Uygulama özelliklerinin doğru çalışmasını sağlamak ve öğrenme deneyiminizi kişiselleştirmek.
- Konuşma alıştırmalarındaki cevaplarınızı değerlendirmek ve konuşma tanıma kalitesini iyileştirmek.
- Hesabınızla ilgili sizinle iletişim kurmak (ör. şifre sıfırlama e-postaları) ve ders hatırlatmaları göndermek.
- Uygulama kullanımını ölçmek, çökmeleri teşhis etmek ve toplu analitiklerle Uygulamayı geliştirmek.
- Abonelikleri ve uygulama içi satın alımları satmak, yönetmek ve geri yüklemek.
- Uygulamanın ücretsiz sürümünü desteklemek için reklam göstermek ve davet/referans sistemindeki dolandırıcılığı önlemek.

## Reklam ve Takip
Uygulama, ücretsiz erişimi desteklemek için **Google AdMob** aracılığıyla reklam gösterir. Bazı reklamlar reklam kimliğinize (iOS'ta IDFA, Android'de reklam kimliği) dayalı olarak kişiselleştirilmiş olabilir.

- iOS'ta Uygulama, kişiselleştirilmiş reklam için IDFA'yı kullanmadan önce Apple'ın Uygulama Takip Şeffaflığı (ATT) çerçevesi üzerinden izninizi ister. Reddederseniz yine de reklam görürsünüz, ancak bu reklamlar cihazınızın reklam kimliğine göre kişiselleştirilmez.
- Yasaların gerektirdiği yerlerde (ör. Avrupa Ekonomik Alanı ve Birleşik Krallık), Uygulama kişiselleştirilmiş reklam göstermeden önce Google'ın onay mesajı aracılığıyla onayınızı ister.
- Reklam takibi tercihinizi cihaz ayarlarınızdan istediğiniz zaman gözden geçirebilir veya değiştirebilirsiniz (iOS: Ayarlar → Gizlilik ve Güvenlik → Takip; Android: Ayarlar → Gizlilik → Reklamlar).
- Ödüllü reklam formatı, ek çalışma süresi karşılığında isteğe bağlı olarak reklam izlemenize olanak tanır; bu tamamen isteğe bağlıdır ve sizin tarafınızdan başlatılır.
- Premium aboneler reklam görmez.

## Abonelikler ve Satın Alımlar
Premium özellikler, Apple App Store / Google Play tarafından işlenen ve bizim adımıza **Adapty** tarafından yönetilen **otomatik yenilenen abonelikler** (Bilexis Premium: aylık, 3 aylık ve yıllık planlar) aracılığıyla sunulur.

- Her aboneliğin adı, süresi ve fiyatı satın almadan önce Uygulamada gösterilir.
- Ödeme, satın alımı onayladığınızda Apple Kimliğinizden / Google Play hesabınızdan tahsil edilir.
- Abonelik, mevcut dönemin bitiminden en az 24 saat önce iptal edilmediği sürece her dönemin sonunda otomatik olarak yenilenir. Yenileme ücreti, mevcut dönemin bitiminden önceki 24 saat içinde hesabınızdan tahsil edilir.
- Ücretsiz deneme sunuluyorsa, abonelik satın aldığınızda denemenin kullanılmayan kısmı geçersiz olur.
- Aboneliğinizi App Store veya Google Play hesap ayarlarınızdan yönetebilir veya iptal edebilirsiniz. Uygulamayı silmek aboneliğinizi iptal etmez.
- Kullanım Koşulları: iOS'ta [Apple Standart Son Kullanıcı Lisans Sözleşmesi (EULA)](https://www.apple.com/legal/internet-services/itunes/dev/stdeula/), Android'de [Google Play Hizmet Şartları](https://play.google.com/about/play-terms/) geçerlidir.

Ödeme kartı bilgilerinizi doğrudan işlemeyiz veya saklamayız. Adapty, premium özellikleri açmak ve cihazlarınız arasında senkronize tutmak için satın alma/abonelik durumunuzu alır.

## Veri Paylaşımı / Aktarımı
- Uygulama, kişisel verileri üçüncü taraflara **satmaz**.
- İlerleme ve profil verileriniz, Uygulamanın temel hizmetlerini sağlamak amacıyla bulut sunucularımıza gönderilir ve güvenli şekilde saklanır.
- Sınırlı veriler, yalnızca ilgili işlevlerini (konuşma tanıma, analitik, çökme raporlama, bildirim, reklam, abonelik, kimlik doğrulama) sağlamak amacıyla aşağıdaki "Üçüncü Taraf Hizmetler ve SDK'lar" bölümünde listelenen hizmet sağlayıcılarla paylaşılır.

## Üçüncü Taraf Hizmetler ve SDK'lar
Uygulama aşağıdaki üçüncü taraf hizmetleri kullanır:
- **Kimlik Doğrulama Sağlayıcıları:** Google ile Giriş ve Apple ile Giriş (alternatif giriş yöntemleri için).
- **İçerik Sağlayıcıları:** YouTube (derslerdeki gömülü eğitim videoları için). Gömülü videoları izlerken YouTube, kendi Gizlilik Politikasına göre veri toplayabilir.
- **Konuşma Tanıma:** ElevenLabs; internete bağlıyken konuşma alıştırmalarında sesinizi metne dönüştürmek için.
- **Reklam:** Google AdMob; banner, geçiş (interstitial), ödüllü ve uygulama açılış reklamlarını göstermek için, onay verildiğinde kişiselleştirilmiş reklamlar dahil.
- **Analitik:** Firebase Analytics; özellik kullanımını anlamak ve Uygulamayı geliştirmek için.
- **Çökme Raporlama:** Firebase Crashlytics; çökme raporlarını toplamak için.
- **Anlık Bildirimler:** Firebase Cloud Messaging; bildirimleri iletmek için.
- **Abonelikler:** Adapty; platformlar arasında otomatik yenilenen abonelikleri ve uygulama içi satın alımları yönetmek için.

Bu sağlayıcıların her biri, kendi gizlilik politikalarına göre veri işleyebilir:
- Google AdMob / Firebase: [https://policies.google.com/privacy](https://policies.google.com/privacy)
- ElevenLabs: [https://elevenlabs.io/privacy-policy](https://elevenlabs.io/privacy-policy)
- Adapty: [https://adapty.io/privacy](https://adapty.io/privacy)

## İzinler
Uygulama; sunucularımıza bağlanmak, öğrenme materyallerini almak, ilerlemenizi senkronize etmek ve reklam sunmak için **İnternet erişimi** gerektirir. Uygulama ayrıca şunları isteyebilir:
- **Mikrofon ve Konuşma Tanıma** erişimi, yalnızca konuşma alıştırmaları için kullanılır; reddedilirse Uygulamanın geri kalanı normal şekilde çalışmaya devam eder.
- **Bildirim** erişimi, ders hatırlatmaları ve hesapla ilgili güncellemeler için kullanılır.
- **Uygulama Takip Şeffaflığı (iOS)**, kişiselleştirilmiş reklamlar için reklam kimliğini kullanmadan önce izninizi istemek amacıyla kullanılır.

Uygulama, kişisel veri toplamak için fotoğraflarınıza, kişilerinize veya harici depolamanıza erişmek amacıyla izin kullanmaz.

## Veri Saklama Süresi
- Hesap bilgileriniz, ilerlemeniz ve tercihleriniz, hesabınız aktif olduğu sürece sunucularımızda güvenli şekilde saklanır.
- Hesabınızı silme talebinde bulunursanız, kişisel verileriniz ve ilerlemeniz saklama politikalarımıza uygun olarak sunucularımızdan kalıcı olarak kaldırılır.
- Apple ile giriş yaptıysanız, hesabınızı silmek hesabınızla ilişkili "Apple ile Giriş" bağlantısını da iptal eder.
- Uygulamayı kaldırırsanız veya uygulama verilerini temizlerseniz, cihazınızda yerel olarak önbelleğe alınan veriler kaldırılır.

## Veri Güvenliği
Verilerinizi korumak için uygun güvenlik önlemleri alıyoruz. Kimlik doğrulama belirteçleri cihazın güvenli depolama alanında saklanır. Uygulama, sunucularımız ve hizmet sağlayıcılarımız arasındaki iletişim şifrelenir. Ancak internet üzerinden hiçbir sistem veya iletimin %100 güvenli olduğu garanti edilemez.

## Çocukların Gizliliği
- Uygulama **13 yaşın altındaki çocuklar için tasarlanmamıştır**.
- 13 yaşın altındaki kişilerden bilerek kişisel veri toplamayız.

13 yaşın altındaki bir çocuğun bize kişisel bilgi verdiğini düşünüyorsanız, bu bilgileri silmek için gerekli adımları atabilmemiz adına lütfen aşağıdaki adresten bizimle iletişime geçin.

## Haklarınız ve Seçenekleriniz
Uygulama, hesap ve ilerleme verilerinizi sunucularımızda sakladığından, aşağıdaki haklara sahipsiniz:
- **Erişim ve Düzeltme:** Profil bilgilerinizi ve tercihlerinizi (dil ve seviye gibi) uygulama içinden görüntüleyebilir ve güncelleyebilirsiniz.
- **Hesap Silme:** Bizimle iletişime geçerek veya uygulama içi silme özelliğini kullanarak (Ayarlar → Hesabı Sil) hesabınızın ve ilişkili tüm verilerin silinmesini talep edebilirsiniz.
- **Reklam Takibi Tercihi:** Cihazınızın gizlilik ayarları üzerinden istediğiniz zaman kişiselleştirilmiş reklamlardan çıkabilirsiniz.
- **Mikrofon ve Bildirimler:** Mikrofon veya bildirim erişimini cihaz ayarlarınızdan istediğiniz zaman geri alabilirsiniz.
- **Yerel Veri:** Uygulamayı kaldırarak cihazınızda yerel olarak önbelleğe alınan verileri kaldırabilirsiniz.

## Bu Politikadaki Değişiklikler
Bu politika gerektiğinde güncellenebilir. Güncel sürüm bu sayfada ve uygulama içinde yayınlanır.
Kişisel verilerinizi işleme şeklimizde önemli değişiklikler olursa, sizi uygulama veya e-posta yoluyla bilgilendirmeyi hedefleriz.

## İletişim
Gizlilikle ilgili sorularınız veya hesap silme talepleriniz için: info@bilexis.com
