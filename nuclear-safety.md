# Video 8: Which energy source is deadliest?

Sources for the *Actually, No* Short on deaths per unit of energy. Each claim in the script is listed with its primary source, the quoted wording, and the short credit shown on screen. Checked 2026-10-27.

## 1. The numbers (deaths per terawatt-hour)
- **Source:** Our World in Data, chart "Death rates per unit of electricity production". Values were downloaded as CSV from <https://ourworldindata.org/grapher/death-rates-from-energy-production-per-twh>:

  | Source | Deaths per TWh |
  |---|---|
  | Brown coal | 32.72 |
  | Coal | 24.62 |
  | Oil | 18.43 |
  | Biomass | 4.63 |
  | Gas | 2.821 |
  | Hydropower | 1.3 |
  | Wind | 0.035 |
  | Nuclear | 0.03 |
  | Solar | 0.019 |

- **Chart subtitle:** "Death rates are measured based on deaths from accidents and air pollution per terawatt-hour of electricity."
- **Data sources:** "Markandya and Wilkinson, and Sovacool et al. (2016) – processed by Our World in Data".
- **Article:** Hannah Ritchie, "What are the safest and cleanest sources of energy?", Our World in Data (first published 2017, updated July 2022). <https://ourworldindata.org/safest-sources-of-energy>
  - What it counts: "This includes deaths from air pollution and accidents in the supply chain."
  - Scale: "One terawatt-hour is about the same as the annual electricity consumption of 150,000 citizens in the European Union."

## 2. Checks on the draft script
- **"count every death"** goes too far. The figures count deaths from accidents and air pollution in the supply chain, and the article lists what is left out. Narration: "count deaths from accidents and air pollution".
- **"Coal: about twenty-five deaths"** needs its unit. It is 24.62 deaths **per terawatt-hour**.
- **The fossil-fuel rates are European.** "These rates are based on electricity production in Europe." The author thinks they undercount: "The estimates we get from Markandya and Wilkinson (2007) death rates undercount by a factor of 4 to 9", giving "a global average death rate from coal of 93 to 224 deaths per TWh". Narration: "One estimate puts coal worldwide four to nine times higher." Coal's real global gap is likely wider, not narrower. On screen: "European plants · global coal likely higher".
- **Wind, solar and nuclear "close to zero":** true (0.035, 0.019 and 0.03). The article warns against ranking them: "The uncertainties around these values mean they are likely to overlap." The film does not rank these three.
- **"Coal kills quietly"** breaks the channel's health wording. Narration: "air pollution linked to early deaths".

## 3. Chernobyl and Fukushima are included, and estimates vary
- **OWID assumption:** "I assume a death toll of 433 from Chernobyl, and 2,314 from Fukushima" (based on UNSCEAR and the Government of Japan).
- **Other estimates are far higher:**
  - WHO press release, 5 September 2005: "up to 4,000" eventual deaths among the most exposed groups. <https://www.who.int/mediacentre/news/releases/2005/pr38/en/>
  - Cardis et al. (2006) project about 16,000 cancer deaths in Europe by 2065.
  - Other model estimates reach tens of thousands. One review cited in coverage gives a range of 9,000 to 93,000.
- **Our check, computed:** nuclear's 2,747 counted deaths over 96,876 TWh give about 0.03 per TWh. Replacing the 433 for Chernobyl with 4,000, 16,000 or 93,000 gives about 0.07, 0.19 or 0.98 per TWh. Even the highest estimate stays below gas (2.8), oil (18.4) and coal (24.6). This is our arithmetic on OWID's inputs, not an OWID figure.
- **On screen:** `Chernobyl: estimates vary`

## 4. On-screen credits
- `Our World in Data · Markandya & Wilkinson 2007 · Sovacool et al. 2016`
- `deaths from accidents + air pollution, per TWh`

## 5. Hook and script claims (checked against the sections above)
- **Hook (chosen):** "You fear nuclear because of Chernobyl. But for the same power, coal is linked to far more dead."
  - Coal 24.62 vs nuclear 0.03 per TWh.
  - Even the highest Chernobyl estimate gives nuclear about 0.98, still far below coal (section 3).
- **"Wind, solar and nuclear: all under 0.05"**: 0.035, 0.019 and 0.03.
- **"about a year of electricity for 150,000 Europeans"**: the article's own scale for 1 TWh.
- **"Maybe that's why Chernobyl is the one we remember"**: our opinion, hedged with "maybe". No source claims it.

## Thumbnails and title (checked 2026-10-27)
- **Title:** "Nuclear 0.03, Coal 24.6: Deaths per Unit of Power". Both numbers are in section 1. It was linted with yt-package/title.py and scored 98 with each thumbnail; the only note was the mobile cut, and the subject survives it.
- **v1 "LOUD vs SILENT"**, subline "nuclear 0.03 · coal 24.6 deaths/TWh". Section 1, and the film's verdict line.
- **v2 "FEAR THE WRONG ONE?"**, subline "Our World in Data · deaths per TWh". A question, not a claim.
- **v3 "CHERNOBYL INCLUDED."**: coal 24.6 vs nuclear 0.03, subline "estimates vary". Section 3.
