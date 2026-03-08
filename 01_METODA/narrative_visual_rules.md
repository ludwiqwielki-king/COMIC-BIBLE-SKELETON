# NARRATIVE & VISUAL RULES – Jak generować obrazy, żeby nie zabić historii

> Te zasady są WAŻNIEJSZE niż techniczne prompty. To jest filozofia narracji wizualnej.

---

## 1️⃣ NIE ILUSTRACJA SCEN – TYLKO FUNKCJA SCENY

### ❌ ŹLE (illustrating action)
"Toke-Ulf wchodzi do sali, patrzy na żyrafę, mówi coś"

**Dlaczego nie:** AI nie umie generować "akcji w trakcie" – wychodzi sztywno, nienaturalnie.

### ✅ DOBRZE (function of scene)
Generuj JEDNO z:
- **Moment decyzji:** "Toke-Ulf z ręką na mieczu, patrzy na żyrafę – wybór: zaufać czy walczyć"
- **Konsekwencja:** "Toke-Ulf klęczy po walce, miecz złamany, żyrafa patrzy z góry"
- **Stan świata po:** "Pusta sala po spotkaniu, tylko ślady walki i świecące kryształy"

**Zasada:** Obraz PO scenie lub PRZED sceną – nie W TRAKCIE.

---

## 2️⃣ OGRANICZ BOHATERÓW W KADRZE

### Paradoks: Im bogatszy tekst, tym uboższy kadr.

| Typ kadru | Co pokazać | Kiedy użyć |
|-----------|------------|------------|
| **Single Character** | Jeden bohater + emocja | Dialog, decyzja, odkrycie |
| **Detail Shot** | Detal (ręka, zegar, spojrzenie żyrafy) | Napięcie, symbolika, transition |
| **Empty Space** | Pusta przestrzeń PO akcji | Konsekwencja, cisza, refleksja |

**Dlaczego:** Mniej elementów = mniej dryftu AI = lepsza spójność.

---

## 3️⃣ KOTWICE WIZUALNE (Visual Anchors)

### Elementy które MUSZĄ się powtarzać IDENTYCZNIE:

| Kotwica | Specyfikacja | Gdzie zdefiniowane |
|---------|--------------|---------------------|
| **Zegar** | Jeden typ: brązowy z rzymskimi cyframi, niebieski portal | `style_locks.md` |
| **Kolor resetu** | #00d2ff (Portal Blue) – zawsze ten sam odcień | `style_locks.md` palette |
| **Korona żyrafy** | Złota, ozdobna, zawsze ten sam wzór | `char_03_GIRAFFE.md` |
| **Blizna Toke-Ulfa** | Pozioma przez LEWĄ brew | `char_01_TOKE-ULF.md` |
| **Kryształy** | Turkus #2dd4bf, sześcienne, świecące od wewnątrz | `style_locks.md` |

### Zasada:
> Jeśli coś jest KOTWICĄ – nie zmieniaj tego NIGDY. Jeśli musisz zmienić – zaktualizuj Biblię i zapisz w `consistency_log.md`.

---

## 🧩 PROMPT ASSEMBLY – Zastosowanie w praktyce

### Przykład: Scena odkrycia w jaskini

**❌ ŹLE:**
"Toke-Ulf wchodzi do jaskini, widzi malowidło żyrafy, podchodzi bliżej, dotyka ściany"


**✅ DOBRZE:**
"Toke-Ulf klęczy przy ognisku, patrzy na malowidło żyrafy na ścianie – moment zrozumienia, ręka wyciągnięta w stronę hologramu"


**Różnica:** Pierwszy to "ilustracja akcji" (AI się pogubi). Drugi to "funkcja sceny" (moment odkrycia = emocja).

---

## 📊 CHECKLIST przed generowaniem sceny

- [ ] Czy prompt opisuje FUNKCJĘ sceny (decyzja/konsekwencja/stan), nie akcję w trakcie?
- [ ] Czy w kadrze jest MAX 1 postać (lub detal, lub pusta przestrzeń)?
- [ ] Czy wszystkie KOTWICE WIZUALNE są obecne i zgodne z Biblią?
- [ ] Czy diorama jest SUBTELNA (5-10%), nie dominująca?
- [ ] Czy brak zbędnych napisów/tekstu w scenie?

---

*Te zasady są częścią systemu Comic Bible Skeleton. Nie łam ich bez świadomej decyzji.*
