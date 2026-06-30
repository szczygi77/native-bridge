# native-bridge.pl — Pełna analiza strony

> **URL:** https://native-bridge.pl/
> **CMS:** WordPress z Elementor 3.32.3
> **Język:** Polski
> **Branża:** Szkoła językowa (angielski i hiszpański)

---

## 1. TYPOGRAFIA

Strona korzysta z Google Fonts (włączone przez Elementor z ustawieniem `font_display: swap`).

### Kroje pisma

| Rola | Krój | Styl |
|---|---|---|
| Nagłówki (H1, H2) | Montserrat lub Poppins (Google Fonts, typowe dla Elementora) | Bold / Semi-Bold |
| Treść / Body | Sans-serif systemowy lub Roboto | Regular 400 |
| Przyciski CTA | Ten sam co nagłówki | Bold / Medium |
| Etykiety sekcji (np. „O NAS", „OPINIE") | Uppercase, letter-spacing zwiększony | Medium |

### Hierarchia nagłówków

```
H1 — Największy (hero): "Twój język. Twój czas. Twój lektor."
H2 — Nagłówki sekcji: "Poznaj naszą misję", "Co nas wyróżnia?", "Nasze kursy językowe"
H3 — Podsekcje: "Lekcje z native speakerami", "Nauka z pasją"
Tekst body — akapity opisowe, recenzje
```

### Rozmiary (szacunkowe na podstawie Elementor defaults)

| Element | Rozmiar |
|---|---|
| H1 (hero) | 48–64px (desktop) / 32–40px (mobile) |
| H2 (sekcje) | 32–42px |
| H3 | 22–26px |
| Body / paragraf | 16–18px |
| Etykiety sekcji (uppercase) | 12–14px, letter-spacing: 2–4px |
| Ceny | 36–48px bold |

---

## 2. KOLORY

> **Uwaga:** Kolory wyekstrahowane na podstawie treści i struktury strony. Dla 100% dokładności zalecane jest sprawdzenie przez DevTools → Inspect → Computed Styles.

### Paleta główna (szacunkowa)

| Nazwa | Hex | Zastosowanie |
|---|---|---|
| Tło główne (białe) | `#FFFFFF` | Tło body, karty, sekcje |
| Akcent główny (CTA, linki) | `#F59E0B` lub `#FF6B35` | Przyciski, podkreślenia, accenty |
| Tekst podstawowy | `#1A1A2E` lub `#111111` | Nagłówki, treść główna |
| Tekst drugorzędny | `#555555` lub `#6B7280` | Akapity, opisy |
| Tło sekcji ciemnej | `#1A1A2E` lub `#0F172A` | Sekcje kontrastowe (cennik, booking) |
| Tekst na ciemnym tle | `#FFFFFF` | Napisy w ciemnych sekcjach |
| Akcent pomocniczy | `#3B82F6` lub `#2563EB` | Ikony, detale |
| Tło szare (sekcje przerywające) | `#F3F4F6` lub `#F9FAFB` | Naprzemienne sekcje |
| Gwiazdki (opinie) | `#FBBF24` | Oceny 5/5 |
| Zielony (checkmarki) | `#10B981` lub `#22C55E` | Punkty w cenniku |

### Kolory elementów UI

| Element | Kolor |
|---|---|
| Przycisk CTA główny (fill) | `#F59E0B` / `#FF6B35` (jasny akcent) |
| Przycisk CTA — tekst | `#FFFFFF` |
| Przycisk outline/ghost | border: kolor akcentu, tekst: kolor akcentu |
| Nawigacja — tło | `#FFFFFF` (sticky) |
| Nawigacja — linki | `#1A1A2E` |
| Nawigacja — aktywny link | kolor akcentu |
| Footer — tło | `#0F172A` lub `#1A1A2E` |
| Footer — tekst | `#9CA3AF` lub `#D1D5DB` |
| Footer — ikony social media | `#FFFFFF` |

---

## 3. STRUKTURA STRONY (sekcja po sekcji)

---

### 🔝 HEADER / NAWIGACJA

**Logo:**
- Plik: `3496f6c9-41a7-4c29-ba5c-13f080934fa7-1024x493.png`
- Umieszczone po lewej stronie navbaru
- Link do strony głównej

**Menu nawigacyjne (poziome):**
- Główna
- O Nas → `/o-nas/`
- Kursy językowe → `/nasze-kursy/`
- Lektorzy → `/nasi-lektorzy/`
- Cennik → `/cennik/`
- Lekcja próbna → `/lekcja-probna/`
- Kontakt → `/kontakt/`

**CTA w headerze:**
- Przycisk „Zarezerwuj online" → `/rezerwacje/`

---

### 🦸 SEKCJA HERO

**Nadtytuł (eyebrow label):**
> See How our Teacher Learn

**Nagłówek główny H1:**
> Twój język. Twój czas. Twój lektor.

**Opis:**
> NativeBridge to miejsce, w którym nauka języka staje się prawdziwą przygodą. Nasza szkoła językowa powstała z pasji i miłości do komunikacji.

**CTA:**
- Link „Dowiedz się więcej →" (przewija do sekcji #wiecej)

**Obraz:**
- `Hero-Images-1.png` (grafika prezentująca lektora/naukę online)

**Układ:** Tekst po lewej, obraz po prawej (split layout)

---

### 📖 SEKCJA „O NAS"

**Etykieta sekcji:** O NAS

**Nagłówek H2:**
> Poznaj naszą misję

**Treść:**
> Naszą misją jest otwieranie drzwi do nowych kultur i doświadczeń poprzez autentyczne, angażujące lekcje prowadzone przez doświadczonych native speakerów z krajów anglojęzycznych i hiszpańskojęzycznych. **Nauka w NativeBridge – to spotkania z ludźmi, emocjami i prawdziwym życiem języka, który już dziś może stać się Twoją drugą naturą.**
>
> Dołącz do nas i przekonaj się, jak prosta, angażująca i pełna radości może być nauka języków obcych!

**CTA:**
- „Dowiedz się więcej →" → `/o-nas/`

**Galeria zdjęć (4 obrazy):**
1. `laptop-flag-up-desk-scaled` — laptop z flagą na biurku
2. `english-book-resting-table-working-space-scaled` — książka do angielskiego na biurku
3. `virtual-classroom-study-space-1024x681` — wirtualna klasa
4. `portrait-happy-young-woman-redhead-girl-with-laptop` — kobieta na lekcji wideo

---

### ⭐ SEKCJA „CO NAS WYRÓŻNIA?"

**Nagłówek H2:**
> Co nas wyróżnia?

**Zdjęcie:** `portrait-female-work-having-video-call-1024x748.jpg`

**6 wyróżników (karty/punkty z ikonami):**

| # | Tytuł | Opis |
|---|---|---|
| 1 | Lekcje z native speakerami | Poznaj nauczycieli z całego świata i odkrywaj język oraz kulturę w ich głosach. |
| 2 | Nauka z pasją | Wierzymy, że najlepsze efekty można osiągnąć w atmosferze pozytywnej energii i pełnej inspiracji. Każda lekcja to nie tylko podróż językowa, ale też spotkanie z pasją, kulturą i nową perspektywą. |
| 3 | Program skrojony na Twoje potrzeby | Realizuj cele z lektorem – konwersacje, gramatyka, przygotowanie do egzaminu lub język biznesu. |
| 4 | Pakiety rodzinne, firmowe i grupowe | Prosimy o kontakt z biurem w celu uzyskania szczegółowych informacji. |
| 5 | Wydarzenia online dla uczestników kursu | Bezpłatne webinary i kluby konwersacyjne z native speakerami. |
| 6 | Pełne wsparcie i motywacja | Możliwość konsultacji z polskojęzycznym nauczycielem. |

---

### 📚 SEKCJA „NASZE KURSY JĘZYKOWE"

**Nagłówek H2:**
> Nasze kursy językowe

**Kurs 1 — Język angielski**

Obraz: `7498496-1024x683.jpg`

> Odkryj kursy, które naprawdę działają. Z nami nauczysz się mówić naturalnie, zrozumieć różnorodne akcenty i zbudować pewność siebie w codziennej komunikacji. Lekcje prowadzone przez doświadczonych native speakerów sprawiają, że język angielski przestaje być barierą, a staje się sposobem na świat. Elastyczny grafik, indywidualnie dopasowane materiały i pełne wsparcie – wszystko po to, byś mówił/a z pewnością i swobodą.

**Kurs 2 — Język hiszpański**

Obraz: `ODAzOTYxNzkw-e1756917682678-1024x683.jpg`

> Wejdź w świat hiszpańskiego z entuzjazmem i energią. Nasze kursy to lekcje, które odkrywają nie tylko język, ale również kulturę krajów hiszpańskojęzycznych. Zajęcia prowadzone przez rodzimych użytkowników języka dostarczają autentycznych doświadczeń. Elastyczne warunki, dopasowane cele i przyjazna atmosfera sprawiają, że nauka hiszpańskiego staje się prawdziwą przygodą — pełną pasji i realnych efektów.

**CTA:**
- „Zapisz się online →" → `/rezerwacje/`

---

### 👥 SEKCJA „DLA KOGO?"

**Etykieta sekcji:** NATIVE BRIDGE

**Nagłówek H2:**
> Dla kogo?

**Opis:**
> Dołącz do grona naszych kursantów i przekonaj się, jak fascynująca i skuteczna może być nauka języków! W NativeBridge to nie tylko lekcje — to most do świata, o którym marzysz.

**CTA:**
- „Poznaj pełną ofertę →" → `/nasze-kursy/`

**Obraz dekoracyjny:** Nastolatka skacząca z teczką (`pretty-teen-girl-going-to-school-jumping`)

**3 grupy docelowe (ikony + opisy):**

| # | Ikona | Tytuł | Opis |
|---|---|---|---|
| 1 | `Icon-3.png` | Uczysz się tam, gdzie Ci wygodnie | Z domu, pracy i każdego miejsca na świecie. |
| 2 | `Icon.png` | Dla dzieci, młodzieży i dorosłych | Dla wszystkich grup wiekowych — z materiałami i metodami dopasowanymi do potrzeb. |
| 3 | `Icon-1.png` | Dla początkujących i zaawansowanych | Od zera aż po biegłość — kursy odpowiadają każdemu poziomowi znajomości. |
| 4 | `Icon-2.png` | Dla tych, którzy chcą mówić płynnie, pewnie i naturalnie | Skoncentrowane na komunikacji i codziennym użyciu języka. |

**Każda pozycja zawiera CTA:** „Zobacz nasze kursy" → `/nasze-kursy/`

---

### 🎓 SEKCJA „JAK UCZYMY?"

**Nagłówek H2:**
> Jak uczymy?

**4 filary metodologii (ikony + teksty):**

| # | Ikona | Tytuł | Opis |
|---|---|---|---|
| 1 | `WhyChooseUs-Icon1.png` | 1:1 z lektorem | Indywidualne lekcje dopasowane do Twojego poziomu i celów, dzięki którym szybciej osiągniesz postępy. |
| 2 | `WhyChooseUs-Icon3.png` | Elastyczny grafik | Uczysz się w dogodnych godzinach i sam decydujesz, kiedy odbywają się zajęcia. |
| 3 | `WhyChooseUs-Icon2.png` | Wygodna rezerwacja online | Wybierasz terminy lekcji i rezerwujesz je w prostym systemie online w kilka chwil. |
| 4 | `WhyChooseUs-Icon4.png` | Atrakcyjne pakiety | Oszczędzaj wybierając nasze pakiety. Wybierz 8 lub 16 lekcji, w zależności od potrzeb. |

---

### 💰 SEKCJA „CENNIK"

**Etykieta sekcji:** cennik

**Nagłówek H2:**
> Poznaj nasze pakiety

**CTA pomocniczy:** „Zapytaj o plan indywidualny →" → `/kontakt/`

**3 pakiety cenowe (karty):**

#### Karta 1 — Lekcja próbna
- **Cena:** 0 zł
- **Opis:** Bezpłatna 25-minutowa lekcja próbna
- **CTA:** „Umów się za darmo" → `/lekcja-probna/`
- **Punkty:**
  - Sprawdzasz szkołę i nauczyciela bez zobowiązań
  - Poznajesz metodę pracy i tempo zajęć
  - Dostajesz rekomendacje, jak uczyć się dalej

#### Karta 2 — 1 lekcja
- **Cena:** 29 zł
- **Termin ważności:** Wykorzystaj w ciągu dwóch miesięcy
- **CTA:** „Kup teraz!" → `/rezerwacje/`
- **Punkty:**
  - Dostajesz rekomendacje, jak uczyć się dalej
  - Szybkie efekty – powtórzysz i utrwalisz podstawowe tematy
  - Pierwsze zauważalne postępy w swobodnej komunikacji
  - Elastyczny plan – idealny na start
- **Etykieta wyróżniająca:** „To się opłaca!"

#### Karta 3 — 10 lekcji (BESTSELLER / WYRÓŻNIONY)
- **Cena:** 290 zł
- **Termin ważności:** Wykorzystaj w ciągu trzech miesięcy
- **CTA:** „Kup teraz!" → `/rezerwacje/`
- **Obraz:** `emotional-black-guy-shouting-gesturing-yes` (postać wyróżniająca pakiet)
- **Punkty:**
  - Nauka przez 2–3 miesiące w stałym rytmie
  - Wyraźna poprawa płynności w mówieniu i rozumieniu
  - Regularność budująca trwały nawyk nauki
  - Duża szansa na przełamanie bariery językowej

---

### 📅 SEKCJA REZERWACJI ONLINE

**Etykieta sekcji:** SKORZYSTAJ Z NASZEJ PLATFORMY

**Nagłówek H2:**
> Umów się online!

**Opis:**
> Bez maili, bez telefonów, bez czekania – teraz możesz zarezerwować lekcję angielskiego w kilka kliknięć. Wybierz dogodny termin, wypełnij krótki formularz i gotowe! Nasz system rezerwacji online działa 24/7, więc umówienie się na zajęcia jest szybkie, wygodne i dostępne dokładnie wtedy, kiedy masz na to czas.

**Punkty:**
- Możliwość wyboru lektora
- Intuicyjny i przejrzysty panel
- Bezpieczne płatności online

**CTA:** „Kliknij, by się zapisać" → `/rezerwacje/`

**Obraz:** `Mobile-App-Image.png` (mockup platformy/aplikacji)

**3 badge'e / wyróżniki:**
- Płatność w złotówkach, polska obsługa
- Platforma rezerwacyjna 24/7
- Poczucie bezpieczeństwa i jasnych zasad

---

### ⭐ SEKCJA OPINII (TESTIMONIALS)

**Etykieta sekcji:** OPINIE

**Nagłówek H2:**
> Zobacz co mówią o nas Kursanci

**6 recenzji (slider / karuzela):**

| # | Autor | Kurs | Ocena | Treść |
|---|---|---|---|---|
| 1 | *(anonim — mama Kuby)* | Angielski | ⭐⭐⭐⭐⭐ 5/5 | Syn (8 lat) zachwycony, przełamał nieśmiałość i używa zwrotów w domu. Lektorzy mają świetne podejście do dzieci. |
| 2 | Anna | Angielski | ⭐⭐⭐⭐⭐ 5/5 | Kurs przed urlopem w Hiszpanii, poznała nie tylko język ale kulturę. Podziękowała: ¡Muchas gracias! |
| 3 | Marcin | Hiszpański | ⭐⭐⭐⭐⭐ 5/5 | Potrzebował języka do pracy z zagranicznym klientem. Po pół roku swobodnie prowadzi rozmowy po angielsku. |
| 4 | Tomasz | Angielski | ⭐⭐⭐⭐⭐ 5/5 | Całe życie stresował się zagranicznymi wyjazdami. Po kursie dogadał się we Włoszech bez problemu. |
| 5 | Kasia | Angielski | ⭐⭐⭐⭐⭐ 5/5 | Miał blokadę przed mówieniem mimo lat nauki. Lektorzy sprawili, że przestał analizować gramatykę i po prostu zaczął rozmawiać. |
| 6 | Michał | Angielski | ⭐⭐⭐⭐⭐ 5/5 | Zawsze chciał mówić po hiszpańsku, tempo dopasowane do pracujących. Szybko zaczęli budować pełne zdania. |
| 7 | Piotr | Hiszpański | ⭐⭐⭐⭐⭐ 5/5 | *(treść nie pojawia się w markdown — prawdopodobnie komentarz o kursie hispanskiego)* |

---

### 🔻 FOOTER

**Logo:** Ten sam co w headerze (`3496f6c9...png`) z linkiem do strony głównej

**Tagline:**
> NativeBridge to miejsce, w którym nauka języka staje się prawdziwą przygodą. Nasza szkoła językowa powstała z pasji i miłości do komunikacji.

**Social Media (ikony):**
- Facebook
- Twitter
- YouTube
- Instagram

**Kolumna 1 — Menu:**
- O Nas → `/o-nas/`
- Nasze Kursy → `/nasze-kursy/`
- Lektorzy → `/lektorzy/`
- Cennik → `/cennik/`
- Kontakt → `/kontakt/`

**Kolumna 2 — Ważne linki:**
- Regulamin strony → `/regulamin-strony/`
- Polityka prywatności → `/polityka-prywatnosci/`
- Polityka Cookies → `/polityka-cookies/`
- FAQ → `/faq/`

**Kolumna 3 — Kontakt:**
- E-mail: kontakt@native-bridge.pl
- Tel: +48 788 322 185

**Nota prawna:**
> Regulamin i Polityka Prywatności (RODO). Za odwołanie lub przełożenie zajęć odpowiada bezpośrednio prowadzący. W takich przypadkach student ma możliwość otrzymania zwrotu wpłaconej kwoty lub wyboru innego prowadzącego/terminu.

---

## 4. PEŁNA MAPA STRON (linki z footera i navbaru)

| Strona | URL |
|---|---|
| Strona główna | `/` |
| O nas | `/o-nas/` |
| Nasze kursy | `/nasze-kursy/` |
| Nasi lektorzy | `/nasi-lektorzy/` lub `/lektorzy/` |
| Cennik | `/cennik/` |
| Lekcja próbna | `/lekcja-probna/` |
| Kontakt | `/kontakt/` |
| Rezerwacje | `/rezerwacje/` |
| Regulamin strony | `/regulamin-strony/` |
| Polityka prywatności | `/polityka-prywatnosci/` |
| Polityka Cookies | `/polityka-cookies/` |
| FAQ | `/faq/` |

---

## 5. TECHNOLOGIE I META

| Parametr | Wartość |
|---|---|
| CMS | WordPress |
| Builder | Elementor 3.32.3 |
| Funkcje Elementor | `e_font_icon_svg`, `additional_custom_breakpoints` |
| CSS | External CSS (`css_print_method: external`) |
| Google Fonts | Enabled (`font_display: swap`) |
| Analytics | Google Tag Manager (`GTM-PTGMC4D6`) |
| Facebook Verification | `hj0x5a2q5hvj7rg44xukyb68tnquea` |
| Robots | `max-image-preview: large` |
| Canonical | `https://native-bridge.pl/` |
| Viewport | `width=device-width, initial-scale=1` |

---

## 6. UX / UKŁAD STRONY

- **Nawigacja:** Sticky header z menu poziomym i wyróżnionym przyciskiem CTA po prawej
- **Hero:** Full-width z podziałem tekst/obraz
- **Sekcje naprzemienne:** Jasne i ciemne tło dla kontrastu wizualnego
- **CTA:** Powtarzające się w każdej sekcji (Dowiedz się więcej, Zapisz się, Kup teraz)
- **Social proof:** Gwiazdkowe opinie z imieniem i kursem
- **Cennik:** 3 karty (Free / Basic / Popular) — klasyczny układ SaaS
- **Responsywność:** Breakpoints customowe przez Elementor
- **Ikony:** SVG (Elementor `e_font_icon_svg`)
- **Rezerwacje:** Zewnętrzna platforma pod `/rezerwacje/`

---

*Dokument wygenerowany na podstawie treści strony https://native-bridge.pl/ | Data analizy: czerwiec 2026*
