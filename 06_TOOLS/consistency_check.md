# CHECKLISTA SPÓJNOŚCI – consistency_check.md

> Używaj przed zatwierdzeniem każdej wygenerowanej sceny. Drukuj, odhaczaj, nie ufaj pamięci.

## 🔍 Dla postaci
- [ ] Twarz: kształt, oczy, włosy, znamiona – 1:1 z Character Bible?
- [ ] Ubiór: wersja stroju zgodna z kontekstem sceny?
- [ ] Akcesoria: obecne i na właściwym miejscu?
- [ ] Proporcje ciała: nie zostały "wyglądzone" przez AI?

## 🌍 Dla świata
- [ ] Lokacja: architektura / materiały zgodne z World Bible?
- [ ] Pogoda / oświetlenie: zgodne z definicją?
- [ ] Paleta kolorów: HEX-e się zgadzają?
- [ ] Motywy wizualne: symbole powtarzające się są obecne?

## 🎨 Dla stylu
- [ ] Lineart: typ zgodny z style_locks.md?
- [ ] Shading / tekstury: bez "style drift"?
- [ ] Kompozycja: shot size / kąt kamery zgodny z intencją?

## ⚙️ Techniczne
- [ ] Parametry `--ar`, `--sref`, `--cref` obecne i poprawne?
- [ ] Negatywy zadziałały (brak deformacji, anime eyes itp.)?

## 📝 Decyzja
- [ ] ✅ Zatwierdź scenę (status: approved)
- [ ] ⚠️ Wymaga korekty (zapisz w consistency_log.md)
- [ ] ❌ Odrzuć i wygeneruj od nowa (zaktualizuj Biblię przed kolejną próbą)

*Checklista v1.0 – dodawaj punkty, gdy odkryjesz nowe źródła niespójności.*