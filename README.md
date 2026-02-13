# COMPLIANT.EU

**EU Food Information Compliance Tool v2.0**

A browser-based regulatory screening tool that validates food product labels against EU food information law. Built for food business operators, quality managers, regulatory professionals, and food law researchers.

**[Launch the tool →](https://daniilsmetanca-collab.github.io/compliant-eu/)**

---

## What it does

Enter product details — name, ingredients, allergens, nutrition data, claims — and receive an instant compliance report with specific legal references, risk scoring, and actionable recommendations.

The tool runs **18 automated checks** covering:

- **Mandatory particulars** — product name, net quantity, FBO identification, date marking, lot identification (Art. 9, Reg. 1169/2011)
- **Ingredient list** — presence, descending weight order, compound ingredient rules (Art. 18–20)
- **Allergen declaration** — automated scan against all 14 Annex II allergens with cross-reference to declared allergens (Art. 21)
- **Nutrition declaration** — Big 7 completeness and logical consistency checks (Art. 29–35)
- **ABV & spirit category** — minimum ABV thresholds per spirit category (Reg. 2019/787, Annex I)
- **Nutrition & health claims** — condition verification, alcohol restrictions (Reg. 1924/2006)
- **Country of origin** — mandatory origin categories, primary ingredient origin rules (Art. 26; Reg. 2018/775)
- **QUID** — quantitative ingredient declaration applicability (Art. 22)
- **Font size & legibility** — minimum x-height based on package surface area (Art. 13)
- **Organic, novel food, GMO** — certification and authorisation requirements (Reg. 2018/848; Reg. 2015/2283; Reg. 1829/2003)
- **Geographic indications** — PDO/PGI/TSG verification (Reg. 1151/2012)

## Regulatory basis

Every check references specific articles from source legislation. All regulations are linked to their official texts on [EUR-Lex](https://eur-lex.europa.eu/).

| Legislation | Scope | EUR-Lex |
|---|---|---|
| Reg. (EU) 1169/2011 | Food Information to Consumers (FIC) | [Link](https://eur-lex.europa.eu/eli/reg/2011/1169/oj/eng) |
| Reg. (EC) 1924/2006 | Nutrition & Health Claims | [Link](https://eur-lex.europa.eu/eli/reg/2006/1924/oj/eng) |
| Reg. (EU) 2019/787 | Spirit Drinks | [Link](https://eur-lex.europa.eu/eli/reg/2019/787/oj/eng) |
| Dir. 2011/91/EU | Lot Identification | [Link](https://eur-lex.europa.eu/eli/dir/2011/91/oj/eng) |
| Reg. (EU) 1151/2012 | Quality Schemes (GI) | [Link](https://eur-lex.europa.eu/eli/reg/2012/1151/oj/eng) |
| Reg. (EU) 2015/2283 | Novel Foods | [Link](https://eur-lex.europa.eu/eli/reg/2015/2283/oj/eng) |
| Reg. (EU) 2018/848 | Organic Production | [Link](https://eur-lex.europa.eu/eli/reg/2018/848/oj/eng) |
| Reg. (EU) 2018/775 | Primary Ingredient Origin | [Link](https://eur-lex.europa.eu/eli/reg_impl/2018/775/oj/eng) |
| Reg. (EC) 1829/2003 | GMO Food & Feed | [Link](https://eur-lex.europa.eu/eli/reg/2003/1829/oj/eng) |
| Dir. 2005/29/EC | Unfair Commercial Practices | [Link](https://eur-lex.europa.eu/eli/dir/2005/29/oj/eng) |

## Technical design

- **Single HTML file** — no dependencies, no frameworks, no build step
- **Fully client-side** — all processing happens in the browser; no data is sent to any server
- **Zero installation** — open the URL and use it
- **Offline-capable** — download the file, open it locally, works without internet
- **Print/PDF export** — generate reports directly from the browser
- **Responsive** — works on desktop, tablet, and mobile

## Privacy

No data collection. No cookies. No analytics. No tracking. No account required. Product information entered into the tool never leaves the user's device.

## Limitations

This tool provides compliance screening guidance, not legal advice. It cannot verify:

- Accuracy of nutritional analysis values
- Actual composition of the product
- National implementing measures in individual Member States
- Label design, font measurements, or visual compliance
- Full GI technical file conformity

Final regulatory responsibility rests with the food business operator (Art. 8, Reg. 1169/2011).

## Author

**Daniil Smetanca**
MSc Food Safety — Wageningen University & Research
[COMPLIANT.EU](https://daniilsmetanca-collab.github.io/compliant-eu/)

## License

© 2026 Daniil Smetanca. All rights reserved.
