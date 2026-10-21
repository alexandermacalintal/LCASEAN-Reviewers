# Sequential batch 1 — founding documents, lecture decks and institutions

Audit date: 2026-10-21. References are physical PDF pages and original slide numbers. Original files were not edited. Text reading and visual inspection are recorded separately.

## Reading completed

| ID | Original file | Actual reading / inspection | Remaining limits |
|---|---|---|---|
| S03 | ASEAN Bali Concord II.pdf | All extracted text, pp. 1–13; p. 14 flowchart visually read | Not a line-by-line image comparison of pp. 1–13 |
| S04 | ASEAN Bangkok Declaration 1967.pdf | All extracted text, pp. 1–5 | OCR-like spelling corruption in copy; signature images not separately inspected |
| S05 | ASEAN Charter.pdf | All extracted text, pp. 1–59, including all 55 articles and annex text | Cover/blank candidates pp. 1–3, 58–59 not visually classified; flag/emblem images not separately inspected |
| S06 | ASEAN Community Vision 2025.pdf | All extracted text, pp. 1–8; substantive text pp. 3–7 | Some font-encoding corruption; low-text pages 1–2, 8 not visually classified; no invented quotations from corrupted text |
| S09 | ASEAN Map.png | Original image visually read | Stylized flag map with no legend/date; not an authoritative boundary or membership map |
| S10 | ASEAN Organizational Structure.pdf | Entire p. 1 visually read, major hierarchy and departments legible | Smallest division labels not transcribed exhaustively |
| S11 | ASEAN Overview 2012.pdf | All extracted text, pp. 1–25; diagrams pp. 12 and 20 visually read | Other pictures and p. 25 closing slide not separately inspected; title-page version is 16 February 2010, not 2012 |
| S16 | ASEAN Vision 2020.pdf | All four pages' extracted text read | No outstanding substantive text gap identified |
| S31 | LCASEAN Module 1 Structures and Mechanisms.pptx | All 59 slides' extracted text read in preceding context; embedded diagrams slides 29 and 49 visually read in this batch; slide 58 text rechecked | Slide 58 native-shape layout not rendered; other photographs/backgrounds not audited; no substantive speaker notes found |
| S32 | LCASEAN Module 1 The Making of ASEAN.pptx | All 21 slides' text read; every image-only slide 6–16 visually read from mapped embedded image | No substantive speaker notes; visual reading is not instructor narration |

## Visual findings

S32 mapping is saved in `extracted/S32/visual_map.json`. Slides 6–16 correspond in order to `media/image1.jpg` through image11 (extensions vary in mapping).

- Slide 6: Political map of Southeast Asia (2003). Identifies mainland and archipelagic spaces, capitals, seas, straits, Borneo and East Timor. Map warns boundary representation is not necessarily authoritative.
- Slide 7: Brunei (2008): two separated territories on north Borneo; Bandar Seri Begawan; Malaysia surrounds land borders; South China Sea coast.
- Slide 8: Cambodia (2008): Phnom Penh, Tonle Sap, Mekong, Thailand/Laos/Vietnam neighbors; Gulf of Thailand coastline.
- Slide 9: Indonesia (2008): Sumatra, Java, Kalimantan, Sulawesi, Maluku, western New Guinea; Jakarta as mapped capital; Timor-Leste separately labeled. Do not turn a historical map into a claim about present capital policy.
- Slide 10: Laos (2008): landlocked, Vientiane, Mekong, neighbors China/Myanmar/Thailand/Cambodia/Vietnam.
- Slide 11: Malaysia (2008): peninsula and Sabah/Sarawak separated by the South China Sea; Kuala Lumpur; Borneo shared with Indonesia and Brunei.
- Slide 12: Myanmar (2008): Bay of Bengal/Andaman Sea, Irrawaddy; Nay Pyi Taw explicitly marked administrative capital although Rangoon is prominently starred. Do not infer current capital from the largest label.
- Slide 13: Philippines (2008): Manila, Luzon, Visayan islands and Mindanao; South China, Philippine, Sulu and Celebes seas.
- Slide 14: Singapore (2008): island at the southern end of the Malay Peninsula, Johore Strait/Malaysia north, Singapore Strait/Indonesian islands south.
- Slide 15: Thailand (2008): Bangkok, central plain and southern peninsula; Gulf of Thailand and Andaman coastlines; Mekong along part of northeastern border.
- Slide 16: Vietnam (2008): Hanoi, Ho Chi Minh City, long coastline, China/Laos/Cambodia neighbors, Mekong delta.
- S09: stylized geographic flag map includes non-ASEAN neighbors such as China and Papua New Guinea. Presence in image does not establish ASEAN membership. Tiny states and disputed boundaries are unsuitable for testing from this image alone.
- S10: title is **ASEAN Secretariat Organisational Structure**, not the whole ASEAN political system. Dated 21 June 2012 in footer; marked internal use/strictly confidential in supplied document. Secretary-General oversees support divisions plus APSC, AEC, ASCC, and Community & Corporate Affairs departments. Administrative divisions are not sovereign decision-making councils.
- S31 slide 29: Secretariat chart dated 15 April 2009. Same broad four-department pattern; historical organization, not current roster.
- S31 slide 49: ASEAN Community (Vision 2015) links three mutually reinforcing pillars; AEC has four older characteristics; ASCC graphic lists five areas, so it must not replace the complete blueprint's categories.
- S11 p. 12: Summit above ACC and three Community Councils; sectoral ministers/senior officials below Community Councils, CPR under ACC in schematic. Legal mandates must still be read from Charter.
- S11 p. 20: Secretariat chart dated 15 December 2008; not interchangeable with 2009/2012 charts.
- S03 p. 14: proposed dispute-settlement sequence advisory (Legal Unit/ACT), consultative (Compliance Board), adjudication (enhanced DSM). Notes explicitly say stages are not mandatory sequential steps; mediation/conciliation may occur concurrently by agreement. This is a 2003 recommendation, not proof all proposed bodies subsequently existed.

## Corrections and interpretation controls

1. S31 slide 7 says TAC February 1967. **1976** verified by S03 p. 1 (primary declaration) and S11 p. 14. Do not repeat erroneous year.
2. S11 filename says 2012 but internal version p. 1 says **16 February 2010**, and p. 5 statistics are **2008 data**. External partner listings and officeholders are historical snapshots.
3. S31 is explicitly Yuyun Wahyuningrum/Oxfam, December 2009. Criticisms are an attributed civil-society perspective. Charter Articles 22–28 actually contain dispute-settlement provisions; 'no dispute mechanisms' is too absolute.
4. Charter legal personality is explicitly **intergovernmental**, Article 3, p. 12; not automatic EU-style supranational government.
5. Consensus has qualifications: Article 20(2) allows Summit decision on how to make a specific decision; Article 20(3) preserves instrument-specific modes; economic Minus X requires consensus, Article 21(2).
6. Human-rights body mandate comes from Article 14 and its terms of reference; do not call it a regional human-rights court.
7. Ten-state membership lists are dated to supplied resources, not represented as a verified 2026 roster.
8. Making slide 4's Cambodia invasion chronology remains simplified; exact 1978–1979 sequence awaits country-history source reading.

## Outputs

`modules/03_MAKING_OF_ASEAN.md` and `modules/04_STRUCTURES_AND_MECHANISMS.md` teach this batch. Module numbering is an inferred reviewer sequence; both supplied decks are explicitly Module 1.
