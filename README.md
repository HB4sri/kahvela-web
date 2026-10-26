# kahvela-web

Kahvela'nın halka açık belgelerini yayınlayan küçük site.

**Canlı adres:** <https://hb4sri.github.io/kahvela-web/>
**Gizlilik politikası:** <https://hb4sri.github.io/kahvela-web/gizlilik/>

Kahvela, evde kahve demleyenler için bir Android uygulamasıdır. Hesap istemez,
reklam göstermez ve internet izni yoktur.

---

The small site that publishes Kahvela's public documents. Kahvela is an
Android app for brewing coffee at home: no account, no ads, no internet
permission.

## Deponun düzeni

| Dosya | Ne işe yarar |
| --- | --- |
| `gizlilik.md` | Gizlilik politikası (TR + EN). |
| `index.md` | Giriş sayfası. |
| `_layouts/default.html` | Sayfa düzeni: stil, dil anahtarı, tema seçici, içindekiler. |
| `_config.yml` | Jekyll ayarları ve sitenin **tek dil kaynağı**. |
| `.gitattributes` | `gizlilik.md` satır sonunu LF'e çiviler. |
| `yazitipi/` | Yazı tipi (Bricolage Grotesque) ve lisansı (OFL). |

Düzen `minamo-web` ve `aruna-web` ile ortaktır; marka rengi Kahvela'nın amberidir.

| Yer | Değer |
| --- | --- |
| Simge zemini | `#0B0A09` |
| Açık temada metin ve bağ | `#9A5418` (zeminde 5.27) |
| Koyu temada metin ve bağ | `#F0A35E` (yüzeyde 8.87) |
