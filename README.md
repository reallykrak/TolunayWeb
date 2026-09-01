# Tolunay — Portfolio

Kişisel portföy sitem. Vanilla JS ile, framework kullanmadan sıfırdan yazıldı.

🔗 **Live:** [reallykrak.dev](#) <!-- kendi domainini bağlayınca linki güncelle -->

![preview](image/hello.png)

## Özellikler

- **GitHub entegrasyonu** — repoları, yıldız ve dil istatistiklerini GitHub REST API'sinden canlı çeker (`js/github.js`)
- **Custom mini müzik player** — play/pause, sonraki/önceki, ilerleme çubuğu, klavye kısayolları (`Space`, `←`/`→`)
- **Typewriter efekti** — hero alanındaki yazı animasyonu (`js/typewriter.js`)
- **Tek sayfa (SPA) navigasyon** — sayfa yenilemeden section geçişleri, scroll progress bar
- **Cursor glow + particle trail** — mouse hareketine tepki veren özel imleç efektleri
- **Konami code easter egg** — çünkü neden olmasın

## Kullanılan teknolojiler

| Katman | Teknoloji |
|---|---|
| Yapı | HTML5 |
| Stil | CSS3 (custom properties, hiçbir framework yok) |
| Mantık | Vanilla JavaScript (ES6+) |
| İkonlar | Font Awesome 6, Devicon |
| Font | Poppins, Inter, JetBrains Mono |
| Veri | GitHub REST API |

Bilinçli olarak Bootstrap/Tailwind gibi bir framework kullanılmadı — layout, animasyonlar ve state yönetimi sıfırdan yazıldı.

## Yerelde çalıştırma

Bağımlılık yok, build adımı yok. Sadece bir static server yeterli:

```bash
git clone https://github.com/reallykrak/TolunayWeb.git
cd TolunayWeb
python3 -m http.server 8000
# veya
npx serve .
