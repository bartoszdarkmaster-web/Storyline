# Storyline

Strona studia reklamy w social mediach i copywritingu.

Statyczny HTML/CSS/JS — bez builda. Wystarczy otworzyć `index.html` lub wrzucić pliki na dowolny hosting (np. GitHub Pages).

- `index.html` — strona główna: oferta, podejście, platformy, proces, zasady, FAQ, kontakt
- `404.html` — strona błędu
- `fonts/` — Fraunces i Manrope hostowane lokalnie (licencja OFL), bez Google Fonts
- `og.jpg`, `apple-touch-icon.png` — obraz do udostępniania w social mediach i ikona
- `robots.txt`, `sitemap.xml`

Formularz kontaktowy nie wymaga backendu: składa wiadomość i otwiera program pocztowy (`studio@storyline.pl`) albo WhatsApp (+48 515 152 580) z gotową treścią.

Biblioteki z CDN: GSAP 3.12 + ScrollTrigger, Lenis 1.1. Bez nich strona działa w trybie podstawowym (treść widoczna, menu i formularz działają).

Adres w `canonical`, `og:url`, `sitemap.xml` i `robots.txt` wskazuje na GitHub Pages — po podpięciu własnej domeny podmień go w tych czterech miejscach.
