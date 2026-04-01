# References: Economic & Political Indicators Dataset

**Project:** Economic Development & Political Indicators Analysis
**Dataset:** Master_EconDev_PoliticalIndicators.csv
**Coverage:** 324 countries/territories · 1996–2024 · 8,703 observations
**Last Updated:** 2026-03-26

---

## Data Sources

### 1. World Bank — Worldwide Governance Indicators (WGI)

> Kaufmann, D., Kraay, A., & Mastruzzi, M. (2010). *The Worldwide Governance Indicators: Methodology and Analytical Issues*. World Bank Policy Research Working Paper No. 5430. World Bank.

**URL:** https://www.worldbank.org/en/publication/worldwide-governance-indicators
**Indicators used:**
- Voice & Accountability (`WGI_Voice_Accountability.csv`)
- Political Stability & Absence of Violence (`WGI_Political_Stability.csv`)
- Government Effectiveness (`WGI_Government_Effectiveness.csv`)
- Regulatory Quality (`WGI_Regulatory_Quality.csv`)
- Rule of Law (`WGI_Rule_of_Law.csv`)
- Control of Corruption (`WGI_Control_of_Corruption.csv`)

**Notes:** Scores are standardized (mean ≈ 0, SD ≈ 1); comparisons are relative, not absolute.

---

### 2. International Monetary Fund — World Economic Outlook (WEO)

> International Monetary Fund. (2024). *World Economic Outlook Database, October 2024*. IMF.

**URL:** https://www.imf.org/en/Publications/WEO
**File:** `IMF_WEO_2024.csv`
**Indicators used:**
- GDP Growth Rate (%)
- Inflation Rate (CPI, %)
- Unemployment Rate (%)
- Current Account Balance (% of GDP)
- General Government Gross Debt (% of GDP)
- GDP (current USD, billions)

**Notes:** Dataset includes hyperinflationary episodes (max = 65,374%); median is more reliable than mean for inflation.

---

### 3. Varieties of Democracy (V-Dem) — Core Indices

> Coppedge, M., Gerring, J., Knutsen, C. H., Lindberg, S. I., Teorell, J., Altman, D., … Ziblatt, D. (2024). *V-Dem [Country-Year/Country-Date] Dataset v14*. Varieties of Democracy (V-Dem) Project. https://doi.org/10.23696/vdemds24

**URL:** https://www.v-dem.net/data/the-v-dem-dataset/
**File:** `VDem_Core_Indices.csv`
**Indicators used:**
- Electoral Democracy Index (v2x_polyarchy)
- Liberal Democracy Index (v2x_libdem)
- Participatory Democracy Index (v2x_partipdem)

---

### 4. Freedom House — Freedom in the World (FIW)

> Freedom House. (2025). *Freedom in the World 2025: The Struggle for Democratic Revival*. Freedom House.

**URL:** https://freedomhouse.org/report/freedom-world
**Files:** `Freedom_House_FIW_2013-2025.csv` · `Freedom_House_FIW_2013-2024.xlsx`
**Coverage:** 2013–2025
**Indicators used:**
- Political Rights Score (0–40)
- Civil Liberties Score (0–60)
- Freedom Status (Free / Partly Free / Not Free)

---

### 5. Polity5 Project — Political Regime Characteristics and Transitions

> Marshall, M. G., & Gurr, T. R. (2020). *Polity5: Political Regime Characteristics and Transitions, 1800–2018. Dataset Users' Manual*. Center for Systemic Peace.

**URL:** https://www.systemicpeace.org/polityproject.html
**Files:** `Polity5.csv` · `Polity5.xls`
**Indicators used:**
- Polity2 Score (−10 autocracy to +10 democracy)
- Democracy Score (democ)
- Autocracy Score (autoc)
- Executive Constraints (xconst)

**Notes:** Excludes micro-states and some territories (~3,748 observations).

---

### 6. United Nations Development Programme — Human Development Index (HDI)

> United Nations Development Programme. (2024). *Human Development Report 2023/24: Breaking the Gridlock — Reimagining Cooperation in a Polarized World*. UNDP.

**URL:** https://hdr.undp.org/data-center/human-development-index
**Files:** `UNDP_HDI_2023-24.csv` · `HDI_2023-24.xlsx`
**Indicators used:**
- Human Development Index (HDI, 0–1)
- Life Expectancy at Birth (years)
- Mean & Expected Years of Schooling
- Gross National Income (GNI) per capita (2017 PPP $)

**Notes:** Limited to cross-sectional observations (~185 countries in the merged dataset); longitudinal HDI trends require the UNDP panel directly.

---

## Citation Format

When citing the merged master dataset in academic work, acknowledge all underlying sources:

> Economic and Political Indicators Dataset (2026). Compiled from: World Bank WGI (Kaufmann et al., 2010); IMF World Economic Outlook (IMF, 2024); V-Dem Core Indices (Coppedge et al., 2024); Freedom House FIW (Freedom House, 2025); Polity5 (Marshall & Gurr, 2020); UNDP HDI (UNDP, 2024). Coverage: 324 countries/territories, 1996–2024.

---

## License Notes

| Source | License / Terms of Use |
|--------|------------------------|
| World Bank WGI | Creative Commons Attribution 4.0 (CC BY 4.0) |
| IMF WEO | IMF Terms & Conditions — free for non-commercial research with attribution |
| V-Dem | Creative Commons Attribution 4.0 (CC BY 4.0) |
| Freedom House | Public use with attribution; commercial use requires permission |
| Polity5 | Public domain — free for academic and policy use |
| UNDP HDI | Creative Commons Attribution 3.0 IGO (CC BY 3.0 IGO) |
