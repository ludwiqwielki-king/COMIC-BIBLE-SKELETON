# SYSTEM OVERVIEW – Comic Bible Skeleton

> Diagram całego systemu. Jedno miejsce które pokazuje jak wszystko działa razem.

## 📊 ARCHITECTURE DIAGRAM
SOURCE TEXT (story idea)
↓
SCENE EXTRACTION (what function? decision/consequence/state)
↓
PANEL STRUCTURE (wide/medium/close-up/surreal)
↓
PROMPT GENERATION (using templates + Bible)
↓
IMAGE MODEL (Grok/Midjourney/SDXL)
↓
CONSISTENCY CHECK (verify against Bible)
↓
DIALOGUE PASS (add text if needed)
↓
FINAL PANEL (saved to 05_SCENES/)

## 📁 FOLDER STRUCTURE
01_METODA/
├── 00_MANIFEST.md # Zasady gry
├── style_locks.md # Globalny styl (paleta, lighting, diorama)
├── prompt_assembly_recipe.md # Jak składać prompty
├── consistency_log.md # Dziennik zmian
└── narrative_visual_rules.md # Filozofia narracji wizualnej
02_CHARACTERS/
├── char_01_TOKE-ULF.md
├── char_02_INN_SPAKI.md
├── char_03_GIRAFFE_TIME_GUARDIAN.md
└── refs/ # Wszystkie obrazy referencyjne
03_WORLD/
└── world_bible_v1.0.md # Świat, lokacje, reguły
04_PROMPTY/
├── prompt_lock.txt # Globalne blokady
├── passive_mode.txt # Instrukcja dla AI
└── templates/
├── portrait.md
├── wide_cinematic.md
├── surreal_closeup.md
└── action_panel.md
05_SCENES/
└── scene_XXX_*.md # Wygenerowane sceny
06_TOOLS/
└── consistency_check.md # Checklista weryfikacji

## 🔄 WORKFLOW (krok po kroku)

1. **Load Bible:** Otwórz Character Bible + World Bible + Style Locks
2. **Define Scene Function:** Co jest celem sceny? (decyzja/konsekwencja/odkrycie)
3. **Choose Template:** portrait/wide/surreal/action
4. **Assemble Prompt:** STYLE CORE + character keywords + scene + location + diorama
5. **Generate:** Wklej w Grok z --cref i --sref
6. **Verify:** consistency_check.md – czy kotwice wizualne są obecne?
7. **Log:** consistency_log.md – zapisz odchylenia i korekty
8. **Save:** 05_SCENES/scene_XXX.md z metadanymi

## 🎯 KEY PRINCIPLES

- **Function > Action:** Obraz funkcji sceny, nie akcji w trakcie
- **One Subject:** Max 1 postać w kadrze (lub detal, lub pusta przestrzeń)
- **Visual Anchors:** Zegar, korona, blizna, kryształy – zawsze identyczne
- **Subtle Diorama:** Cork board = 5-10% ramki, nie dominujący element
- **No Text:** Brak napisów w scenach (tylko na okładce)

## 🤖 AI PROTOCOL

1. Load PROJECT_BIBLE (style_locks + character bibles)
2. Confirm role (Narrative Architect / Comic Panel Designer)
3. Read latest STATE from consistency_log.md
4. Execute task (generate scene / verify consistency)
5. Do not modify core documents without explicit permission

