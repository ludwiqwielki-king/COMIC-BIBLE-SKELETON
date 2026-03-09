# AI PROTOCOL – Standard komunikacji z modelami

> To jest protokół który KAŻDY model AI musi przestrzegać pracując z tym projektem.

## 📋 STANDARD OPERATING PROCEDURE

Każdy model AI przed rozpoczęciem pracy MUSI:

### 1. LOAD PROJECT_BIBLE
Read: 01_METODA/style_locks.md
Read: 02_CHARACTERS/char_*.md (all characters)
Read: 03_WORLD/world_bible_v1.0.md
Read: 01_METODA/narrative_visual_rules.md

### 2. CONFIRM ROLE
You are: [Narrative Architect / Comic Panel Designer / Consistency Checker]
Task: [Generate scene / Verify consistency / Assemble prompt]

### 3. READ LATEST STATE
Check: 01_METODA/consistency_log.md
Find: Last scene generated
Note: Any deviations or corrections made

### 4. EXECUTE ASSIGNED TASK
Check: 01_METODA/consistency_log.md
Find: Last scene generated
Note: Any deviations or corrections made

### 4. EXECUTE ASSIGNED TASK
Follow: prompt_assembly_recipe.md
Use: Appropriate template from 04_PROMPTY/templates/
Apply: Visual anchors from style_locks.md
Verify: Against consistency_check.md

### 5. UPDATE STATE_REPORT
Log: What was generated
Note: Any deviations from Bible
Suggest: Corrections if needed

### 6. DO NOT MODIFY CORE DOCUMENTS
Never change: Character Bibles without permission
Never change: Style Locks without permission
Only suggest: Updates via consistency_log.md

## 🚫 FORBIDDEN ACTIONS

- ❌ Improvising visual details not in Bible
- ❌ Changing character appearance without logging
- ❌ Ignoring visual anchors (clock, crown, scar, crystals)
- ❌ Adding text/titles to scenes (unless cover)
- ❌ Making diorama dominant (>10% of frame)

## ✅ REQUIRED ACTIONS

- ✅ Always check cref_link before generating
- ✅ Always include STYLE CORE in prompt
- ✅ Always verify against consistency_check.md
- ✅ Always log deviations in consistency_log.md
- ✅ Always use visual_keywords from Character Bible

## 🔄 MODEL HANDOFF

Gdy jeden model kończy pracę, musi zostawić:
STATE_REPORT:
Last scene: scene_XXX
Status: approved/needs_rework
Issues: [list any deviations]
Next action: [what to do next]

To pozwala następnemu modelowi kontynuować bez utraty kontekstu.

[1/6] LOAD PROJECT_BIBLE ✅
- style_locks.md: loaded
- char_01_TOKE-ULF.md: loaded (beard accepted, scar left eyebrow)
- char_02_INN_SPAKI.md: loaded (blue glasses, meta-orb, white beard)
- char_03_GIRAFFE_TIME_GUARDIAN.md: loaded
- world_bible_v1.0.md: loaded
- narrative_visual_rules.md: loaded

[2/6] CONFIRM ROLE ✅
Role: COMIC PANEL DESIGNER
Task: Generate prompt for Scene 004 – "Inn Spaki gives meta-orb"

[3/6] READ LATEST STATE ✅
From consistency_log.md:
- Scene 003: Approved, 97% consistency
- Toke-Ulf: Full beard locked as evolution
- Visual anchors: All maintained (scar, crystals, clock)
- Diorama: Subtle frame (5%) working

[4/6] EXECUTE ASSIGNED TASK ✅
