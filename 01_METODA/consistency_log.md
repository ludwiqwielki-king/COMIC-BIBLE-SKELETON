# DZIENNIK SPÓJNOŚCI – consistency_log.md

> Tu zapisujesz wszystkie odchylenia od Biblii i decyzje korekcyjne. To jest Twoja "patch notes" dla projektu.

## Szablon wpisu
```markdown
### Scene [NUMER] – [KRÓTKI OPIS]
- Data: [RRRR-MM-DD]
- Generator: [Grok/Midjourney/SDXL]

#### ✅ Co się udało (spójne z Biblią)
- [ ] Postać [IMIĘ]: [cecha 1], [cecha 2]
- [ ] Lokacja: [element świata]
- [ ] Styl: [element artystyczny]

#### ⚠️ Co się rozjechało (do poprawy)
- [ ] Postać [IMIĘ]: [np. kolor oczu inny niż w Biblii]
- [ ] Lokacja: [np. brak mgły, której wymaga World Bible]
- [ ] Styl: [np. AI dodało anime eyes]

#### 🔧 Podjęta korekta
- [ ] Dodano "[konkretna fraza]" do prompt_lock dla [CHAR_ID]
- [ ] Zaktualizowano `style_locks.md` o "[nowy parametr]"
- [ ] Wygenerowano nową referencję `cref` dla [IMIĘ]

#### 📎 Linki
- Prompt: `05_SCENES/scene_XXX_prompt.txt`
- Output: [link do wygenerowanego obrazu]
- Poprawka: [link do wersji po korekcie]

Pusty log = brak testów. Wypełniaj po każdej sesji generowania.

---

## 📄 `02_CHARACTERS/char_TEMPLATE.md`

```markdown
# CHARACTER BIBLE – [IMIĘ POSTACI]

> Szablon karty postaci. Duplikuj dla każdej ważnej postaci. Wypełniaj SZCZEGÓŁOWO – AI nie domyśli się niczego.

## 🔖 META
char_id: "CHAR_[XX]_[NAZWA]"
version: "v1.0"
last_updated: "[RRRR-MM-DD]"
status: "draft" / "locked"


## 🪪 Podstawowe dane
- **Pełna nazwa:** [Imię + pseudonim / kryptonim]
- **Rola w historii:** [główny bohater / antagonista / sidekick / recurring / cameo]
- **Wiek:** [biologiczny] / [wyglądający na]
- **Płeć / tożsamość:** [opis]
- **Proporcje ciała:** [wzrost, waga, sylwetka, np. "178 cm, 68 kg, smukła, długie nogi"]

## 👁️ Wygląd stały – MUST-HAVE (bardzo szczegółowo!)
### Twarz
- Kształt: [owalna / kwadratowa / trójkątna itp.]
- Oczy: [kolor, kształt, rozstaw, rzęsy]
- Włosy: [kolor, długość, fryzura, przedziałek, grzywka, tekstura]
- Skóra: [kolor, odcień, znamiona – piegi/blizny/tatuaże z LOKALIZACJĄ]
- Najbardziej rozpoznawalny element: [np. "blizna biegnąca od lewego oka do żuchwy"]
- Typowe wyrazy twarzy: [neutral / zły / uśmiech – słowa kluczowe]

## 👕 Ubiór – wersja podstawowa (najczęściej noszona)
- Góra: [opis]
- Dół: [opis]
- Buty: [opis]
- Akcesoria stałe: [okulary, naszyjnik, broń, torba – z detalem]
- Paleta kolorów stroju: [HEX lub nazwy, np. "#2c3e50, #95a5a6"]

## 🔄 Alternatywne wersje stroju (numeruj)
### Wersja 1: [casual / domowa]
- [opis]

### Wersja 2: [bojowa / kostium]
- [opis]

### Wersja 3: [historyczna / flashback]
- [opis]

## 🧠 Osobowość – 4-6 najsilniejszych cech (w kolejności ważności)
1. [cecha]
2. [cecha]
3. [cecha]
...

### Wartości – granice postaci
- **Nigdy nie:** [np. "nie zostawi sojusznika w niebezpieczeństwie"]
- **Zawsze:** [np. "zawsze sprawdza tyły przed wejściem"]

## 💔 Traumy / motywacje / cel nadrzędny
- [opis]

## 🎨 Kolorystyka emocjonalna postaci
| Stan | Kolory / oświetlenie |
|------|---------------------|
| Spokój / neutral | [np. "soft blue ambient, low contrast"] |
| Złość / walka | [np. "red rim light, hard shadows"] |
| Smutek / introspekcja | [np. "desaturated, single spotlight"] |
| Radość / ulga | [np. "warm gold backlight, lens flare"] |

---

## 🔗 AI REFERENCE TOKENS (NAJWAŻNIEJSZE – nie pomijaj!)
visual_keywords: "[imię], [wiek], [dokładny opis wyglądu], [strój], same face as reference, exact same freckles pattern, identical hairstyle, consistent character design"
cref_link: "[wklej link do portretu referencyjnego – wygeneruj go wcześniej!]"
sref_link: "[opcjonalnie: link do stylu]"
seed_value: "[opcjonalnie]"


## 📎 Referencje wizualne

### Scene 002 – Jaskinia, pierwsze spotkanie z żyrafą-malowidłem
- Data: 2026-03-09
- Generator: Grok

#### ✅ Co się udało
- [x] Kompozycja: cork board subtelna ramka (5%)
- [x] Glitch elements: wózek sklepowy, holograficzny zegar 26.01.2026
- [x] Żyrafa: malowidło z koroną, hand prints na ścianie
- [x] Kryształy: turkusowe, świecące
- [x] Oświetlenie: ognisko + god rays z otworu jaskini

#### ⚠️ Co się rozjechało
- [ ] Toke-Ulf: pojawiła się pełna broda (w Biblii: light stubble)
- [ ] Twarz: nieco inna struktura niż w cref (ale nadal rozpoznawalny)

#### 🔧 Podjęta korekta
- [x] **Zaakceptowano ewolucję** – Toke-Ulf od teraz ma brodę (podróż, czas)
- [ ] Zaktualizować `char_01_TOKE-ULF.md` → dodać "full beard" do VISUAL CORE
- [ ] Od tej sceny wszystkie kolejne = Toke-Ulf z brodą (spójność w przód)

#### 📎 Linki
- Prompt: `04_PROMPTY/templates/wide_cinematic.md` (zmodyfikowany)
- Output: `05_SCENES/scene_002_cave_meeting.md`
- [Link do obrazu / opis numeru sref / cref który najlepiej działa]
- [Dodatkowe notatki: co AI dobrze interpretuje, co przekręca]

### Scene 003 – Zatruta Rzeka Pamięci (Discovery)
- Date: 2026-03-09
- Generator: Grok
- Template: wide_cinematic.md

#### ✅ Co się udało
- [x] Kompozycja: epic wide shot, Toke-Ulf w profilu (small in frame)
- [x] Funkcja sceny: discovery/contemplation (nie akcja w trakcie)
- [x] Visual anchors: scar, beard, crystals #2dd4bf, clock tower, portal
- [x] Diorama: subtle frame (5%) – gears in corners only
- [x] Spójność z Scene 002: beard maintained

#### 🔧 Decyzje
- [x] Beard accepted as permanent evolution (update char_01_TOKE-ULF.md)
- [x] Profile shot works better than front view for this character

#### 📎 Linki
- Prompt: Used AI_PROTOCOL.md + wide_cinematic.md template
- Output: 05_SCENES/scene_003_river_memory.md
- Status: APPROVED

### Consistency Grid – Scene 001-003
- Date: 2026-03-09
- Verdict: 97% consistency
- Major decision: Beard accepted as permanent evolution
- Visual anchors: All maintained (scar, face structure)
- --cref system: WORKING EFFECTIVELY

STATE_REPORT – Scene 004
- Scene ID: 004
- Function: Transfer (Inn Spaki gives meta-orb to Toke-Ulf)
- Panel type: Medium shot (2 characters)
- Status: ✅ APPROVED
- Visual anchors verified: 
  - Toke-Ulf: scar (left brow), beard, face structure
  - Inn Spaki: blue glasses, white beard, meta-orb #00d2ff
  - World: crystals #2dd4bf, brass pipes, runic symbols
- Deviations: NONE
- Next action: Scene 005 (Toke-Ulf activates orb / first time travel)
- Notes: FIRST successful 2-character scene! --cref system WORKING!

STATE_REPORT – Scene 005
- Scene ID: 005
- Function: Transformation (Toke-Ulf activates meta-orb)
- Panel type: Surreal close-up
- Status: ✅ APPROVED (Image 1)
- Visual anchors verified: 
  - Toke-Ulf: scar (left brow) ✅, beard ✅, expression ✅
  - Meta-orb: blue energy #00d2ff ✅, lightning ✅
  - Runes: floating glowing symbols ✅
  - Crystals: turquoise #2dd4bf ✅
- Deviations: 
  - Image 2: Unwanted text "META-ORB ACTIVATION"
  - Image 3: Double scar (both brows) - rejected
- Next action: Scene 006 (first time travel / arrival in new time)
- Notes: Orb activation SUCCESSFUL! Energy effects working!

STATE_REPORT – Scene 006
- Scene ID: 006
- Function: Arrival (Toke-Ulf arrives in new time period, disoriented)
- Panel type: Wide cinematic
- Status: ✅ APPROVED
- Visual anchors verified: 
  - Toke-Ulf: beard ✅, kneeling posture ✅
  - Meta-orb: present but dimly glowing ✅
  - Portal: blue energy dissipating #00d2ff ✅
  - Anachronism glitch: SHOPPING CART visible ✅
  - Runes: floating blue symbols ✅
- Deviations: NONE
- Next action: Scene 007 (exploring new time / first encounter with new era)
- Notes: ANACHRONISM TEST PASSED! Shopping cart perfectly subtle but visible. Time travel mechanics WORKING!WORKING!

STATE_REPORT – Scene 008
- Scene ID: 008
- Function: Establishing (Toke-Ulf sees San Francisco for first time)
- Panel type: Wide cinematic (16:9)
- Status: ✅ APPROVED (Image 2)
- Visual anchors verified: 
  - Toke-Ulf: scar (left brow) ✅, beard ✅, orb ✅
  - World: Golden Gate ✅, SF skyline ✅, fog Karl ✅
  - Anachronism: shopping cart ✅
  - Magic: turquoise crystals with runes ✅
  - Diorama: cork board + gears + push pins ✅
- Deviations: NONE
- Next action: Scene 009 (encounter with drunk man)
- Notes: DIORAMA + 16:9 WORKS! Character consistency maintained!

*Status: [draft / locked] – po zablokowaniu nie zmieniaj bez aktualizacji version!*
