# Kahvela

[Türkçe](#gizlilik-politikası) · [English](#privacy-policy)

---

## Gizlilik Politikası

**Sürüm:** 1.1 · **Yürürlük:** 12 Kasım 2026
**İletişim:** support@hb4.aleeas.com

### Özet

Kahvela'nın sunucusu yok, hesap istemiyor ve internet izni bile yok. Kayıtların telefonunda
saklanır. Telefondan çıkmasının yalnızca üç yolu vardır: senin aldığın yedek dosyası, telefonunun
Google yedeği ve telefon değiştirme.

Bu politika, Kahvela (paket adı `com.hb4sri.coffee`) Android uygulaması için geçerlidir.

### Sorumlu

Kahvela'yı bağımsız bir geliştirici olarak tek başıma yapıyorum; arkasında bir şirket yok.
Soruların ve taleplerin için bana yazabilirsin: **support@hb4.aleeas.com**

### Telefonunda ne saklanıyor

Uygulamanın sakladığı her şey telefonunun kendi uygulama alanındadır.

**Çekirdekler ve aday listesi:** girdiğin bilgiler (ad, kavurucu, menşe, işlem, kavurma, kavurma
tarihi, fiyat, paket ağırlığı, kalan miktar, notlar), eklediysen paketin fotoğrafı ve bir
tarayıcıdan paylaştığın mağaza sayfasının adresi.

**Demlemeler:** tarih ve saat, yöntem, kullandığın ekipman, öğütüm, kahve ve su miktarları,
tarif, süre, maliyet, tadım puanları, tatlar ve notlar.

**Ekipman:** değirmen, makine, filtre ve demleyicilerinin adları, ayarları ve eklediysen
fotoğrafları.

**Ayarlar:** dil, para birimi, demleme tercihleri, bildirim ve hatırlatma tercihleri, otomatik
yedek için seçtiğin klasör.

**Saklanmayanlar:** adın, e-posta adresin, telefon numaran, konumun, cihaz kimliğin ve
reklam kimliğin. Bunların hiçbiri istenmez ve saklanmaz.

### Fotoğraflar ve bağlantılar

Fotoğrafı telefonunun kamera uygulaması çeker ya da Android'in fotoğraf seçicisinden sen
seçersin; uygulama yalnızca seçtiğin fotoğrafı alır, küçültülmüş bir kopyasını kendi alanında
saklar. Uygulamanın kamera ya da galeri izni yoktur.

Bir tarayıcıdan paylaştığın mağaza sayfasının yalnızca adresi saklanır. Rehber'deki kaynaklara ve
mağaza bağlantılarına dokunduğunda sayfa tarayıcında açılır; o andan sonrası tarayıcının ve o
sitenin kendi gizlilik kurallarına bağlıdır. Uygulama kendisi hiçbir siteye bağlanmaz.

### Reklam, analitik ve izleme

Yoktur. Kahvela'da reklam ağı, analitik, çökme telemetrisi ve çapraz uygulama izleme bulunmaz.
Reklam kimliğin okunmaz. Uygulamada üçüncü taraf bir veri toplama kütüphanesi paketlenmemiştir.

### İzinler

Uygulama `INTERNET` izni **istemez.** Bu izin olmadan uygulama kendi başına ağ üzerinden hiçbir
veri gönderemez.

İstenen izinler: demleme sayacının kilit ekranındaki bildirimi, süre dolunca uyarısı ve "tekrar
tat" hatırlatması için `POST_NOTIFICATIONS`; uyarının tam zamanında gelmesi için
`SCHEDULE_EXACT_ALARM` (Android ayarlarından sen açarsın); Android 16'da sayacın canlı bildirim
olarak görünmesi için `POST_PROMOTED_NOTIFICATIONS`; titreşim için `VIBRATE`; bekleyen soğuk
demlemenin "hazır" uyarısını telefon yeniden açılınca kurmak için `RECEIVE_BOOT_COMPLETED`. Ayrıca
uygulamanın kendi adıyla başlayan `DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION` vardır; bunu Android
destek kütüphanesi kendi bileşenini başka uygulamalardan korumak için ekler. Bunların hiçbiri ağ
erişimi vermez.

### Verinin telefondan çıkabileceği durumlar

**1. Yedek dosyası.** Ayarlar'daki Yedek sayfasından kayıtlarını, ayarlarını ve fotoğraflarını
tek bir dosyaya yazarsın. Dosyanın nereye gideceğini sen seçersin: telefondaki bir klasör,
Google Drive gibi bir hizmet ya da paylaşım ekranından seçtiğin bir uygulama (WhatsApp, e-posta).
Otomatik yedeği açarsan uygulama günde en çok bir kez, seçtiğin klasöre bir yedek yazar ve
oradaki en yeni beş otomatik yedeği tutar; yalnızca kendi eski otomatik yedeklerini siler, klasördeki
başka hiçbir dosyaya dokunmaz. **Yedek dosyası şifrelenmez;** kaydettiğin ya da gönderdiğin yer
dosyayı okuyabilir.

**2. Telefonunun Google yedeği.** Telefonunda Android'in yedeği açıksa Android, uygulamanın
kayıtlarını ve ayarlarını Google hesabına yedekleyebilir. Paket ve ekipman fotoğrafları bu yedeğe
girmez. Bu yedeği Android ve Google yönetir; uygulama ona ayrıca bir şey göndermez. Telefonunun
yedek ayarlarından kapatabilirsin.

**3. Telefon değiştirme.** Yeni bir telefona geçerken Android'in aktarımı uygulamanın kayıtlarını,
ayarlarını ve fotoğraflarını taşıyabilir. Aktarımı sen başlatırsın, Android yürütür.

**Hata kaydı.** Uygulamada bir hata olursa hatanın türü, zamanı ve uygulamanın sürümü telefonunda
küçük bir kayda yazılır. Yazdıkların bu kayda girmez. Kayıt telefonundan kendiliğinden çıkmaz;
yalnızca sen paylaşırsan ya da geri bildirim e-postasına eklersen gider. Ayarlar'dan görebilir ve
silebilirsin.

### Saklama süresi ve silme

Kayıtların sen silene ya da uygulamayı kaldırana kadar saklanır; süre sınırı yoktur. Çekirdekleri,
adayları, demlemeleri ve ekipmanı uygulamanın içinden silebilirsin. Her şeyi birden silmek için
telefonun ayarlarından uygulamanın verisini temizleyebilir ya da uygulamayı kaldırabilirsin;
uygulamayı kaldırmak telefondaki bütün Kahvela verisini siler. Google hesabındaki yedek Google'ın
kurallarına göre bir süre durabilir; onu Google hesabının ayarlarından silebilirsin. Aldığın
yedek dosyaları senin dosyalarındır; onları bulundukları yerden sen silersin.

### Çocuklar

Uygulama çocuklara yönelik değildir ve yaş bilgisi istemez.

### Bu politikadaki değişiklikler

Politika değişirse bu sayfadaki sürüm numarası ve yürürlük tarihi güncellenir. Uygulamanın veri
davranışını değiştiren bir güncelleme yayımlanırsa politika aynı sürümde güncellenir.

### İletişim

**support@hb4.aleeas.com**

---

## Privacy Policy

**Version:** 1.1 · **Effective:** 12 November 2026
**Contact:** support@hb4.aleeas.com

### Summary

Kahvela has no server, no accounts, not even the internet permission. Your records are stored on your
phone. There are only three ways they can leave it: a backup file you make, your phone's Google
backup, and switching phones.

This policy applies to the Kahvela Android app (package `com.hb4sri.coffee`).

### Who is responsible

I make Kahvela on my own, as an independent developer; there is no company behind it. For
questions and requests, you can write to me: **support@hb4.aleeas.com**

### What is stored on your phone

Everything the app stores lives in your phone's own app storage.

**Beans and the wishlist:** what you enter (name, roaster, origin, process, roast, roast date,
price, pack weight, amount left, notes), a photo of the pack if you add one, and the address of a
shop page you share from a browser.

**Brews:** date and time, method, the equipment you used, grind, amounts of coffee and water,
recipe, time, cost, taste ratings, flavors and notes.

**Equipment:** the names and settings of your grinders, machines, filters and brewers, and photos
if you add them.

**Settings:** language, currency, brewing preferences, notification and reminder preferences, the
folder you chose for automatic backups.

**Not stored:** your name, email address, phone number, location, device ID or advertising ID.
None of these are requested or kept.

### Photos and links

Your phone's camera app takes a photo, or you pick one in Android's photo picker; the app receives
only the photo you chose and keeps a smaller copy in its own storage. The app has no camera or
gallery permission.

Only the address of a shop page you share from a browser is kept. When you tap a source in the
Guide or a shop link, the page opens in your browser; from then on the browser's and that site's
own privacy rules apply. The app itself never connects to any site.

### Ads, analytics and tracking

There are none. Kahvela contains no ad network, no analytics, no crash telemetry and no cross-app
tracking. Your advertising ID is not read. No third-party data collection library is bundled in
the app.

### Permissions

The app does **not** request the `INTERNET` permission. Without it, the app cannot send any data
over the network on its own.

Requested permissions: `POST_NOTIFICATIONS` for the brew timer on the lock screen, its time's up
alert and the "taste again" reminder; `SCHEDULE_EXACT_ALARM` so the alert comes right on time (you
turn it on in Android's settings); `POST_PROMOTED_NOTIFICATIONS` to show the timer as a live
notification on Android 16; `VIBRATE` for vibration; `RECEIVE_BOOT_COMPLETED` to set a waiting cold
brew's "ready" alert again after the phone restarts. There is also
`DYNAMIC_RECEIVER_NOT_EXPORTED_PERMISSION`, prefixed with the app's own id, which the Android
support library adds to keep its own component private to the app. None of these grant network
access.

### When data can leave your phone

**1. Backup file.** From the Backup page in Settings you write your records, settings and photos to
a single file. You choose where it goes: a folder on the phone, a service such as Google Drive, or
an app you pick in the share sheet (WhatsApp, email). If you turn on automatic backups, the app
writes a backup to the folder you chose at most once a day and keeps the newest five automatic
backups there; it deletes only its own older automatic backups and never touches any other file in
the folder. **The backup file is not encrypted;** wherever you save or send it can read it.

**2. Your phone's Google backup.** If Android's backup is on for your phone, Android can back up the
app's records and settings to your Google account. Photos of packs and equipment are left out of
it. Android and Google run this backup; the app sends nothing to it on its own. You can turn it off
in your phone's backup settings.

**3. Switching phones.** When you move to a new phone, Android's transfer can carry the app's
records, settings and photos. You and the operating system start this.

**Error log.** If the app runs into an error, the error's type, time and the app's version are
written to a small log on your phone. Nothing you wrote goes into it. The log does not leave your
phone on its own; it goes only if you share it or add it to a feedback email. You can see and delete
it in Settings.

### Retention and deletion

Your records are kept until you delete them or uninstall the app. There is no time limit. You can
delete beans, wishlist entries, brews and equipment inside the app. To delete everything at once,
clear the app's data in your phone's settings or uninstall the app; uninstalling removes all Kahvela
data from the phone. The backup in your Google account may stay for a while under Google's rules;
you can delete it in your Google account settings. Backup files you made are your own files; you
delete those from wherever you saved them.

### Children

The app is not directed at children and does not ask for anyone's age.

### Changes to this policy

If this policy changes, the version number and effective date on this page are updated. If an app
update changes data behaviour, the policy is updated in the same release.

### Contact

**support@hb4.aleeas.com**
