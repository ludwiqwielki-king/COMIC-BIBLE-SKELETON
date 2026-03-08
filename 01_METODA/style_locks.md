# MASTER STYLE BIBLE – Globalny Stylesheet

> Ten plik definiuje styl, który musi pojawić się w KAŻDYM prompcie. Kopiuj blok "STYLE CORE" do każdego promptu.

**Lokalizacja referencji:** Wszystkie obrazy w `02_CHARACTERS/refs/`

---

## 🎨 Docelowy styl komiksu
"Dark fantasy surrealism with steampunk elements, Norse mythology meets AI meta-narrative, cork board diorama aesthetic, cinematic lighting, detailed yet stylized"

## 👨‍🎨 Referencje artystyczne (max 3)
1. Grzegorz Rosiński (Thorgal) – nordic fantasy, dynamic composition
2. Moebius – surrealism, otherworldly landscapes
3. Steampunk aesthetic – brass machinery, gears, Victorian-futurist fusion

---

## ✍️ Technika rysunku
| Element | Specyfikacja |
|---------|-------------|
| **Lineart** | Clean to semi-sketchy, medium-heavy weight, expressive contours |
| **Shading** | Cinematic chiaroscuro + soft cel shading, volumetric lighting |
| **Detaliczność** | High detail for: mechanisms, runes, crystals, textures |
| **Tekstury** | Cork board background, brass/bronze metallic, weathered wood, glowing crystals, parchment |

---

## 🎨 GLOBAL PALETTE (HEX + role)

| Nazwa | HEX | Rola w komiksie |
|-------|-----|----------------|
| Deep Teal | `#0d3b3b` | Background shadows, deep water, night sky |
| Turquoise Water | `#1a5f5a` | Rivers, atmosphere, mystical fog |
| Crystal Blue | `#2dd4bf` | Magic light, glowing crystals, ethereal effects |
| Portal Blue | `#00d2ff` | Time portals, energy beams, holograms, runic glow |
| Giraffe Gold | `#f4d03f` | Crowns, giraffe spots, magical flower, divine elements |
| Leather Brown | `#8b4513` | Clothing, wood, brass accents, cave walls |
| Parchment | `#e8e0d0` | Cork board, scrolls, paper elements, bone |
| Storm Gray | `#4a5568` | Clouds, metal, weathered stone |

### Paleta emocjonalna (dodawaj w zależności od sceny)

Calm: #1a5f5a + #e8e0d0 + soft #2dd4bf glow
Tension: #0d3b3b + #00d2ff accents + hard shadows
Mystery: #4a5568 + #2dd4bf volumetric fog + single spotlight
Magic: #00d2ff + #f4d03f + crystal bloom effects


---

## 💡 LIGHTING SYSTEM

### Primary Lighting
- **Chiaroscuro**: Hard contrast between light/shadow (dramatic comic style)
- **God Rays**: Light beams from above (moonlight, divine presence)
- **Perpetual Dusk**: Never full daylight – always twilight/moonlight atmosphere

### Secondary Lighting
- **Volumetric Fog**: Cyan/turquoise mist that catches light
- **Crystal Glow**: Turquoise (#2dd4bf) and blue (#00d2ff) emanating from magical elements
- **Campfire/Practical**: Warm orange accents for intimate scenes

### Magic/Energy Lighting
- **Portal Energy**: Swirling blue (#00d2ff) with particle effects
- **Runic Glow**: Blue symbols that pulse/brighten when active
- **Meta-Orb**: Electric blue lightning inside glowing sphere

### Direction Rules
- Heroes: Rim light from behind + frontal fill (separation from background)
- Villains/Mystery: Single harsh light source, deep shadows on face
- Surreal elements: Multiple light sources, impossible physics OK

---

## 🖼️ ESTETYKA DIORAMY (CRITICAL – zawsze obecna)

### Cork Board Frame
Composition: Main image centered, framed by cork board texture
Border: Deep 3D shadow box effect (not flat)
Push pins: Visible metal pins holding elements to board

### Decorative Elements (mieszaj w zależności od sceny)
Top corners: Brass steampunk flying drones / mechanical birds
Left side: Miniature scrolls with runic inscriptions, handwritten parchment letters
Right side: Turquoise glowing crystals, small hourglasses, brass gears
Bottom: Candles with flames, mechanical clockwork, metal runic symbols
Edges: Weathered wood frame, metal clips, aged paper notes

### Mix Principle
Ancient Norse (runes, longship, fur) + Steampunk (brass, gears, drones) + Surreal Time (clocks, portals, crystals)
= Unique diorama aesthetic

### Prompt Keywords for Diorama
cork board diorama frame, deep shadow box, push pins visible, brass steampunk elements, scrolls with runes, glowing crystals, candles, mechanical gears, weathered wood frame, 3D museum display aesthetic


---

## 📐 Kompozycja i kadrowanie

### Shot Types
| Typ | % użycia | Opis |
|-----|----------|------|
| **Wide Epic** | 40% | Full scene, landscape, multiple elements, cork frame prominent |
| **Medium Action** | 35% | Character + context, dynamic pose, diorama elements visible |
| **Close-Up Portrait** | 20% | Face/emotion focus, minimal background, cork edge visible |
| **Surreal Detail** | 5% | Symbol close-up (clock, rune, crystal), abstract composition |

### Camera Angles
- **Low Angle**: Heroes, epic moments, power dynamics
- **Eye-Level**: Dialogue, discovery, neutral scenes
- **Dutch Tilt**: Tension, surreal moments, timeline instability
- **Top-Down**: Maps, diorama overview, "collector's view"

### Space Rules
- Leave negative space for cork board elements
- Don't crowd edges – diorama decorations need room
- Main subject centered or rule-of-thirds, never edge-cropped

---

## 🔥 STYLE CORE – Gotowy blok do kopiowania w każdy prompt
dark fantasy surrealism with steampunk elements, Norse mythology meets AI meta-narrative, cork board diorama aesthetic with push pins and brass machinery, cinematic chiaroscuro lighting with god rays and volumetric fog, perpetual dusk atmosphere, color palette #0d3b3b #1a5f5a #2dd4bf #00d2ff #f4d03f #8b4513 #e8e0d0, detailed yet stylized, consistent art style throughout comic, no style drift, glowing turquoise crystals, runic inscriptions, weathered wood frame


> 💡 **Uwaga:** Wklej ten blok na POCZĄTKU każdego promptu, potem dodaj opis sceny/postaci.

---

## 🚫 NEGATIVES – czego unikać (dodawaj na końcu promptu)
style shift, different artist, blurry face, deformed hands, extra limbs, realistic photo, 3d render (unless specified for diorama effect), chibi, anime eyes, modern technology (except intentional anachronisms like shopping cart), clean minimalism, flat lighting, cartoon style, watercolor unless specified, bright daylight, cheerful atmosphere (unless scene requires)

### Specyficzne zakazy dla projektu
never remove cork board frame, never remove golden crown from giraffe, never change Toke-Ulf scar position, never make characters smile broadly (stoic/melancholic only), never use full daylight lighting


---

## 🔗 Globalne parametry techniczne
--ar 3:4 (portrait/cover) or 16:9 (epic wide scenes)
--style raw
--cw 100 (character weight – trzymaj wysokie dla spójności)
--stylize 300-400 (wyższe dla surrealizmu, niższe dla portretów)


### Sref link (globalny styl)
```markdown
sref_link: 
![Cover Style](https://github.com/ludwiqwielki-king/COMIC-BIBLE-SKELETON/blob/main/02_CHARACTERS/refs/cover_v1.jpg?raw=true)
💡 Używaj --sref [link] w promptach aby utrzymać spójność stylu z okładką.

🧩 PROMPT ASSEMBLY – Jak składać prompt (szybka ściągawka)
1. STYLE CORE (kopiuj z sekcji powyżej)
2. POSTAĆ/E (visual_keywords z Character Bible + --cref link)
3. AKCJA/SCENA (krótki opis: co się dzieje, gdzie, emocje)
4. LOKACJA (keywords z World Bible: atmosfera, elementy świata)
5. KOMPOZYCJA (shot type, camera angle, lighting mood)
6. DIORAMA ELEMENTS (cork board, brass drones, crystals – jeśli scena tego wymaga)
7. TECH PARAMS (--ar, --stylize, --cw, --sref)
8. NEGATIVES (kopiuj z sekcji 🚫)

Przykład struktury
[STYLE CORE] + [Toke-Ulf visual_keywords + --cref] + "standing in cave, campfire, storm outside" + [cave keywords: stone walls, hand prints, crystals] + "medium shot, low angle, dramatic lighting" + [cork board diorama frame keywords] + --ar 3:4 --stylize 300 --cw 100 --sref [link] + [negatives]

🔄 WERSJONOWANIE I AKTUALIZACJE
Version: v1.0
Last Updated: 2026-03-09
Updated By: [Ilon] created by Qwen 3.5

Change Log:
- v1.0: Initial release with palette, lighting, diorama specs

