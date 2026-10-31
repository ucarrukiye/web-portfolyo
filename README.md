# Web Portfolyo

Kendi tanıtım sitem ve müşterilere gösterilecek örnek siteler. **Henüz canlıda değil.**

## İçerik

| Dosya | Ne? |
|---|---|
| `index.html` | Kendi tanıtım sitem (işler, paketler, süreç, iletişim) |
| `kafe.html` | Fincan & Fırın — kafe örneği (menü sekmeleri, masa ayırtma) |
| `kuafor.html` | Atölye Makas — kuaför örneği (fiyat listesi, saat seçmeli randevu) |
| `dis-klinigi.html` | Lale Diş — diş kliniği örneği (tedaviler, hekimler, SSS, KVKK onaylı form) |
| `*.jpg` | Portfolyo kartlarındaki ekran görüntüleri |

Gerçek proje: **G.O Yapı** — https://www.goyapi.com.tr

## Ayarlar (tanıtım sitesi)

`index.html` dosyasının en altındaki `AYAR` bloğunu değiştir:

```js
const AYAR = {
  marka: "GO Yapı",           // marka adın
  whatsapp: "",               // 90 ile başlayan, boşluksuz numara (boşsa WhatsApp butonları gizlenir)
  fiyatlar: { tanitim: "", kurumsal: "", bakim: "" } // ör. "₺4.000"
};
```

## Görüntüleme

Dosyayı tarayıcıda açman yeterli (`index.html`). Kurulum gerekmez; tüm siteler tek HTML dosyası.

## Notlar

- Örnek sitelerdeki işletme adları, kişiler, fiyatlar ve yorumlar temsilidir; her sayfanın altında "örnek tasarım" notu var.
- Bir müşteri için uyarlarken: ad, renkler, metinler, WhatsApp numarası (`wa.me/...`) ve form gönderim adresi değiştirilir.
- Diş kliniği örneğinde sağlık reklam kurallarına uygun olsun diye fiyat, hasta yorumu ve "en iyi" gibi iddialar yok.
