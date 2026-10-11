# MLP – projekt poglądowy v2A „Premium / editorial” (10.10.2026)

Statyczny projekt poglądowy nowej strony głównej mlp.opole.pl. Nie jest to strona produkcyjna: `noindex, nofollow`, etykieta „Projekt poglądowy”, formularz nieaktywny.

## Treści
Wszystkie teksty, liczby i opinie pochodzą z obecnej strony mlp.opole.pl (publiczne GET, kopie w ../mockup/ref/): home, /kursy-korepetycje-jezykowe/ (+ angielski, hiszpański, francuski), /o-firmie/, /kontakt/, /tlumaczenia/.
Liczniki (tylko fakty): 92 opinie Google („Doskonała”), Parlament Europejski od X 2017, 500+ uczestników szkoleń EFS 2010–2015, 16 kursów angielskiego specjalistycznego (lista na stronie).
Opinie: dosłowne cytaty z widżetu opinii Google na stronie (MydłoWKostce, Jan Wyciślik).
Do uzupełnienia: godziny otwarcia (placeholder), docelowo żywy widżet opinii Google.

## Zdjęcia
- Hero / sala: `sala1_panorama4_2.jpg` z biblioteki mediów MLP (kopia wp-content/uploads) – sala z tablicą interaktywną; obróbka duotone. **Do potwierdzenia przez MLP, że to ich sala.**
- Budynek (Ozimska 63A), logo, odznaki Orły Kształcenia 2019 i Oferteo Najlepsi 2023 – z biblioteki mediów MLP.
- Zdjęcia ilustracyjne (Unsplash License, bez podpisów sugerujących uczniów/kadrę MLP):
  - kids-*.webp – Vitaly Gariev – https://unsplash.com/photos/_z2Ii760I38
  - workshop-*.webp – Centre for Ageing Better – https://unsplash.com/photos/XH8chLuj02g
  - biz-*.webp – Vitaly Gariev – https://unsplash.com/photos/-Lzdk59aldE

## Fonty (SIL Open Font License, self-hosted, subset Latin + polskie znaki)
Fraunces (variable, opsz 144, wght 300–800) + Fraunces Italic; Inter (variable).

## Technika
HTML/CSS + ~1 KB JS (scroll-reveal przez IntersectionObserver, liczniki; wyłączone przy prefers-reduced-motion). `<picture>` z art direction, WebP + srcset, preload hero per media query.
shots/ – desktop 1440×900 i mobile 390×844 (@2x): first_screen + full_page. lighthouse/ – 3× mobile + 3× desktop (LH 12.8.2), summary.json.
