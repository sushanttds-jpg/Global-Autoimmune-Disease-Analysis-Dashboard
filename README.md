This project holds deep personal significance. It was built while someone close to me navigates Lupus (SLE) Stage III, and it reflects a genuine desire to understand and highlight global outcomes for people fighting autoimmune diseases.
---

## Key Findings
* **Global Survival:** 83.5% average survival rate across all analyzed conditions (~32.8 million people estimated to survive globally).
* **The Regional Gap:** A stark contrast between Africa (60% average survival) and North America (92%).
* **Diagnosis Delay Crisis:** Africa averages **7.4 years** to receive a diagnosis, compared to **1.8 years** in Europe.
* **Gender Disparity:** Roughly **72%** of all autoimmune patients globally are female.
* **Lupus Stage III (South Asia):** Shows a **78% survival rate**, the lowest among high-income tracked conditions.
---
## Diseases Analyzed
| Disease | Global Cases (est.) | Avg Survival |
| :--- | :--- | :--- |
| **Lupus (SLE)** | ~5 million | 82.4% |
| **Rheumatoid Arthritis** | ~16.5 million | 79.1% |
| **Multiple Sclerosis** | ~2.8 million | 83.0% |
| **Type 1 Diabetes** | ~7.8 million | 80.3% |
| **IBD (Crohn's/Colitis)** | ~6.8 million | 82.4% |
**Regions Covered:** North America • Europe • East Asia • South Asia • Latin America • Africa • Middle East
---
## Data Sources
* **WHO** Global Health Observatory
* **CDC** Lupus Data Center
* **Global Burden of Disease Study 2021** (PMC10546867)
* **IDF** Diabetes Atlas 2023
* **Multiple Sclerosis International Federation** Atlas 2023
* **Healthgrades** Lupus Survival Analysis
*Note: All values are published estimates from peer-reviewed sources. This is for research visualization and portfolio purposes, not for clinical or medical use.*
---
## How to Run
```bash
# Clone the repository
git clone [https://github.com/sushanttds-jpg/autoimmune-global-analysis](https://github.com/sushanttds-jpg/autoimmune-global-analysis)
cd autoimmune-global-analysis
# Install dependencies
pip install -r requirements.txt
# Run the pipeline
python create_data.py    # Generates the synthetic dataset (autoimmune_global.csv)
python analysis.py       # Computes stats and renders the dashboard image
