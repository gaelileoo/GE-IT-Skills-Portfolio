### Data Analytics & Visual Report

---

#### Dataset Focus: Mindanao Agricultural Production & Climate Resilience (Mock CSV Analysis)

---

#### 1. Data Cleaning Protocol Log

- **Raw Input Problem:** The CSV dataset contained incomplete crop yield records for 2023–2024, inconsistent numerical formatting (metric tons vs. kilograms), duplicate municipality entries, and missing values across multiple agricultural indicators.

- **AI Cleaning Instruction:** *"Scan the uploaded dataset. Detect duplicate municipality records, standardize all production values to metric tons, replace missing crop yield values using the median of the corresponding crop category, normalize date formatting to YYYY, and remove invalid characters without modifying verified observations."*

- **Structural Adjustments Summary:**
  - Standardized all production measurements to **metric tons**
  - Removed duplicate municipality records
  - Corrected inconsistent year formatting
  - Filled missing crop yield values using median imputation
  - Normalized categorical labels across provincial clusters
  - Successfully cleaned **156 records** covering agricultural production across Mindanao

---

#### 2. Visualizations Generated

##### Chart 1
*(Embedded High-Contrast Bar Chart: Annual Cacao Production in Mindanao, 2020–2025)*

```text
[Interactive Chart: 2020–2025 Mindanao Cacao Production Trend]
```

##### Chart 2
*(Embedded Line Chart: Rainfall Variability vs. Crop Yield Index, 2020–2025)*

```text
[Interactive Chart: Climate Variability and Agricultural Yield Correlation]
```

---

#### 3. Human Analytical Narrative (The "Why" Factor)

The cleaned dataset reveals a noticeable decline in cacao production during 2023, coinciding with periods of irregular rainfall and transport disruptions affecting agricultural communities throughout Mindanao. Although the automated analysis initially associated the decrease solely with weather variability, manual review of regional development reports indicates that logistical constraints, farm-to-market road conditions, and post-harvest handling also contributed to reduced production efficiency. The combined visualizations demonstrate that climate resilience cannot be addressed independently from investments in agricultural infrastructure and supply chain modernization. These findings support prioritizing budget allocations for climate-adaptive farming practices, improved road connectivity, and expanded post-harvest facilities to strengthen food security and economic resilience across the region.

---

#### 4. Policy Insights

| Indicator | Key Observation | Recommended LGU Action |
| :--- | :--- | :--- |
| Crop Yield | Declining production in climate-sensitive years | Expand climate-resilient farming programs and extension services |
| Rainfall Variability | Greater fluctuations correspond with lower yields | Invest in irrigation systems and water resource management |
| Farm Logistics | Transport bottlenecks increase post-harvest losses | Upgrade farm-to-market roads and establish additional consolidation centers |
| Agricultural Planning | Production trends vary across provinces | Adopt data-driven resource allocation using annual monitoring dashboards |

---

#### 5. Output Files
- ✅ Cleaned CSV Dataset
- ✅ Interactive Agricultural Production Dashboard
- ✅ Annual Crop Yield Trend Chart
- ✅ Climate vs. Crop Yield Correlation Chart
- ✅ Executive Summary for Regional Policymakers
