# COMIC BIBLE SKELETON v1.0

> "Spójność to nie przypadek. To dyscyplina."

System do generowania spójnych wizualnie komiksów przy użyciu AI (Grok/Midjourney/SDXL). 
Inspirowany projektem [Typografia Mimetyczna](https://github.com/ludwiqwielki-king/typografia-mimetyczna).

## 🔥 Zasada działania
1. **Wypełnij Biblię** (`02_CHARACTERS/`, `03_WORLD/`, `01_METODA/style_locks.md`)
2. **Użyj recepty** (`01_METODA/prompt_assembly_recipe.md`) żeby złożyć prompt
3. **Wygeneruj** w Grok/Midjourney, zapisz wynik w `05_SCENES/`
4. **Weryfikuj spójność** przez `06_TOOLS/consistency_check.md`

## 📁 Struktura

01_METODA/ # Manifest, style locks, recepta na prompty
02_CHARACTERS/ # Szablony postaci – każda postać = jeden plik .md
03_WORLD/ # Świat, lokacje, reguły uniwersum
04_PROMPTY/ # Gotowe szablony promptów + parametry blokujące
05_SCENES/ # Wygenerowane prompty + notatki z sesji
06_TOOLS/ # Narzędzia weryfikacji spójności


## 🚀 Quick Start
1. Sklonuj repo / stwórz foldery jak wyżej
2. Skopiuj `char_TEMPLATE.md` → `char_01_TWOJA_POSTAC.md`
3. Wypełnij szablon (nie pomijaj sekcji 🔗 AI REFERENCE TOKENS)
4. Otwórz `prompt_assembly_recipe.md` i złóż swój pierwszy prompt
5. Testuj, zapisuj błędy, iteruj.

## ⚠️ Zasada Unikania Blokad (Safety Bypass)
Jeśli prompt zostanie zablokowany przez filtry AI:
- Nie usuwaj emocji / dramaturgii
- Zamień dosłowność na symbolikę: 
  - krew → wino / płatki róż / czerń tuszu
  - nagość → mgła / alabaster / cień
  - przemoc → metafora wizualna (pęknięte szkło, zgaszone światło)
- Zapisz zmianę w `consistency_log.md`

---
*Projekt w fazie alpha. Testuj, łam, poprawiaj. Metoda rodzi się w działaniu.*
