# Mir's Falafel — Design Concept (Fas 1)

## A. Aesthetic Direction: **Maximalist Warm + Middle Eastern Soul**

**Val:** Maximalist Warm med starka mellanöstern influenser

**Motivering:** Mir's Falafel är en familjeägd kiosk i Norsborg — inte en kedja, inte corporate. Det är äkta, generöst, varmt. En falafel från Mir's är överfylld, färgglad, doftande. Designen ska spegla DET — inte minimalism. Vi går på rikedom, lager på lager, mustiga färger som påminner om kryddor, tegel, marknader i Damaskus och Beirut. Detta är mat med själ, och designen ska ha lika mycket själ.

**Känsla:** Som att kliva in i en familjeägd restaurang där väggarna är fulla av foton, där dofterna slår emot dig, där du känner dig välkommen direkt. Överflödigt? Ja. Generöst? Absolut.

---

## B. Typography System

### Headline Font: **Bebas Neue**
- **Varför:** Kondenserad, stark, karaktäristisk. Har en nästan affisch-lik kvalitet som påminner om gamla marknads-skyltar i Mellanöstern. Skriker "äkta" utan att vara dekorativ.
- **Användning:** H1, sektionsrubriker, priser

### Body Font: **Crimson Text**
- **Varför:** En elegant serif som kontrasterar vackert mot Bebas Neue. Har värme och läsbarhet samtidigt som den känns "analog" och mänsklig — perfekt för en familjeägd verksamhet.
- **Användning:** Brödtext, öppettider, adress, menybeskrivningar

### Accent Font (Alternativ): **Amiri**
- **Varför:** En arabisk-inspirerad serif som kan användas sparsamt för att smycka vissa element — t.ex. dekorativa ord som "äkta", "familj", "sedan 2010".
- **Användning:** Dekorativa accent-element, vissa headers i sekundär hierarki

---

## C. Color Palette

| Roll | Färg | HEX | Användning |
|------|------|-----|------------|
| **Dominant** | Tegelröd / Burnt Sienna | `#C75B39` | Huvudsakliga bakgrunder, stora sektioner, känslan av varm sten och tegel |
| **Secondary** | Mörk Oliv / Olive Drab | `#4A4A2A` | Sekundära sektioner, footer, kontrast mot tegel |
| **Accent** | Saffran / Goldenrod | `#F4B942` | CTA-knappar, highlights, priser, "ÖPPET"-indikatorer |
| **Text Primary** | Kol / Near Black | `#1A1A1A` | Rubriker, brödtext på ljusa ytor |
| **Text Secondary** | Varm Vit / Cream | `#FAF3E8` | Text på mörka/tegel-bakgrunder |
| **Background Alt** | Kornmjöl / Warm Beige | `#F5E6D3` | Kort, menyelement, kontrastsektioner |

**Palett-inspiration:** Torkad paprika, saffran, olivolja, tegel från gamla hus — färger som existerar i en riktig falafel-restaurang.

---

## D. Layout Approach

### Grid-System: **Asymmetrisk + Lager på Lager**
- Ingen centrerad hero — texten sitter till vänster, bilder överlappar
- Sektioner bryter mot varandra — en rak kant mot en diagonal, olika bakgrundsfärger som möts
- Generös padding — luft MEN fylld med färg och textur

### Sektions-ordning:
1. **Hero** — Stor typografi "MIR'S FALAFEL", familjefoto bakom, öppettider i ett hörn, adress i ett annat
2. **Meny Preview** — Tre stora kort (Falafel / Kebab / Sallad) med överlappande bilder och priser
3. **Om Oss** — Storyn om familjen, bilder från köket, personligt
4. **Meny Full** — Komplett meny med priser, asynkron layout
5. **Hitta Hit** — Karta + adress + öppettider i ett stort, färgstarkt block
6. **Footer** — Kontakt, sociala medier-länkar

### Animation/Motion Plan:
- **Page load:** Staggered reveal — först loggan, sedan rubriken, sedan resten (CSS animation-delay)
- **Scroll:** Bilder som parallaxar lätt, text som fade:ar in
- **Hover:** Knappar får en "fill"-effekt (färgen fylls uppåt), menykort skjuter upp lite
- **Micro-interactions:** Priser som "poppar" när man hoverar över menyalternativ

---

## E. Bildstrategi

### Befintliga Bilder (13 st):
- Behålla alla som visar mat — falafel, kebab, sallader
- Behålla bilder som visar köket/personal (om de finns) för autenticitet
- Utgå från att använda 6-8 av de 13 bilderna

### Genererar Nya Bilder:
- **Hero-bild:** Överhead-shot av en överfylld falafel-tallrik — gyllene falafelbollar, sallad, hummus, pickles, bröd. Varm belysning.
- **Bakgrunds-textur:** Subtil kornig textur (noise overlay) för alla sektioner — ska kännas som gammalt papper/tegel
- **Familjebild:** Om ingen bra familjebild finns bland de 13 — generera en varm bild av en äldre man (Mir) vid grillen, bakifrån, rök, varma färger

### Bildstil:
- Varm, mättad färgpalett
- Hög kontrast
- Lite "gritty" — inte perfekt studio-fotografi, utan äkta känsla
- Matbilder ska se APTITLIGA ut — närbilder, detaljer, texturer

---

## F. What Makes It Unique

**"En falafel-kiosk som ser ut som den smakar — generös, färgglad, och full av karaktär, inte ett enda slätt vitt yta i sikte."**

---

## Sammanfattning för Godkännande

| Element | Val |
|---------|-----|
| **Aesthetic** | Maximalist Warm + Middle Eastern |
| **Headline Font** | Bebas Neue |
| **Body Font** | Crimson Text |
| **Dominant Color** | `#C75B39` (Tegelröd) |
| **Accent Color** | `#F4B942` (Saffran) |
| **Layout** | Asymmetrisk, överlappande, inga centrerade heroes |
| **Vibe** | Generös, varm, familjär, äkta |

**Redo för Fas 2 (Bygg) efter godkännande.**
