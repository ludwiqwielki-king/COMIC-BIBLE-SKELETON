# RECEPTA NA PROMPT SCENY – Algorytm składania

> Krok po kroku: jak złożyć gotowy prompt z kawałków Biblii. Działa dla Grok, Midjourney, SDXL.

## 🔄 KROKI

### 1. Weź opis sceny od użytkownika
[USER INPUT]: "Jan wchodzi do ciemnej alei, widzi cień na ścianie"


### 2. Doklej STYLE CORE z `style_locks.md`
[STYLE CORE]: "polish modern comic, clean lineart + soft cel shading, moody cinematic lighting..."


### 3. Dla każdej postaci w scenie:
- Otwórz jej kartę w `02_CHARACTERS/`
- Skopiuj sekcję `## 🔗 AI REFERENCE TOKENS` + `## Najlepsze słowa kluczowe do promptów AI`
- Wklej do promptu

Przykład:
"Jan, 30yo, man with scar on left cheek, short dark hair, worn leather jacket, white t-shirt, same face as reference, exact same freckles pattern, —cref [link] —cw 100"


### 4. Doklej kontekst świata z `03_WORLD/`
- Lokacja: atmosfera, pogoda, dominujące kolory
- Przykład: `"rain-slicked alley, neon reflections in puddles, fog, brutalist concrete walls"`

### 5. Dodaj kompozycję (opcjonalnie, ale zalecane)
- Shot size, kąt kamery, emocje
- Przykład: `"medium shot, low angle, tense atmosphere, chiaroscuro lighting"`

### 6. Na końcu doklej:
- `prompt_lock.txt` (globalne parametry techniczne)
- Negatywy z `style_locks.md`

### 7. CHECKLISTA przed wysłaniem do AI:
- [ ] Wszystkie postacie mają `cref` / `visual_keywords`?
- [ ] STYLE CORE jest w całości?
- [ ] Lokacja zgodna z World Bible?
- [ ] Parametry techniczne (`--ar`, `--sref`) są obecne?
- [ ] Negatywy dodane?

## 📦 Przykład gotowego promptu
Jan, 30yo, man with scar on left cheek, short dark hair, worn leather jacket, white t-shirt, same face as reference, exact same freckles pattern, walking into dark alley, sees shadow on wall, rain-slicked street, neon reflections, fog, brutalist concrete, medium shot, low angle, tense atmosphere, chiaroscuro lighting, polish modern comic book style, clean lineart + soft cel shading, moody cinematic lighting, color palette [#1a1a2e, #16213e, #e94560], detailed yet stylized, consistent art style, no style drift, —cref [link] —cw 100 —sref [link] —stylize 300 --ar 3:4 --style raw, no style shift, no blurry face, no deformed hands


*Zapisz gotowy prompt w `05_SCENES/scene_XXX_prompt.txt`*
