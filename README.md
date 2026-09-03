# Agrifood Supply Chain Analytics

## Power BI Analytics Portfolio Project

This project demonstrates how I connect my academic background in **Agriculture** and **Business Administration** with practical experience in **Operational Logistics and Supply Chain**, using **Data Analytics and Power BI** to turn domain and operational questions into measurable insights.

The project explores nature-inclusive agrifood transitions through a **120-observation project dataset**, interactive Power BI dashboards, KPI development, DAX measures, segmentation, data visualisation, and research synthesis.

## Professional Bridge

**Agriculture → Business Administration → Operational Logistics & Supply Chain → Data Analytics**

- **Agriculture:** farming systems, sustainability, biodiversity, soil health, agrifood context
- **Business Administration:** business viability, stakeholder thinking, incentives, strategy, decision-making
- **Operational Logistics:** coordination, process execution, operational efficiency, constraints
- **Supply Chain:** value chains, market access, stakeholder dependencies, material and information flows
- **Data Analytics:** KPI design, DAX, segmentation, visualisation, interactive analysis, insight generation

## Power BI Dashboard

The dashboard includes analytical views for:

- Total farmers
- Adopted farmers
- Adoption rate
- Adoption rate by training access
- Adoption rate by subsidy access
- Adoption rate by market-premium access
- Perceived risk vs. adoption intention
- Financial pressure by adoption status
- Soil health by adoption status
- Biodiversity index by adoption status
- Value-chain coordination by adoption status
- Policy support by adoption status
- Region filtering
- Farm-type filtering

### Core DAX Measures

```DAX
Total Farmers =
DISTINCTCOUNT(Farmer_Data[Farmer_ID])
```

```DAX
Adopted Farmers =
COUNTROWS(
    FILTER(
        Farmer_Data,
        Farmer_Data[Nature_Inclusive_Adoption] = "Yes"
    )
)
```

```DAX
Adoption Rate =
DIVIDE(
    [Adopted Farmers],
    [Total Farmers],
    0
)
```

## Dashboard Highlights

| Analytical View | Result |
|---|---:|
| Total farmers | 120 |
| Adopted farmers | 26 |
| Overall adoption rate | 21.7% |
| Training access | ~34% vs. ~12% |
| Subsidy access | ~26% vs. ~18% |
| Market-premium access | ~22–23% vs. ~21% |
| Perceived risk | Downward association with adoption intention |
| Financial pressure | Higher among non-adopters |
| Soil health | Higher average among adopters |
| Biodiversity index | ~77 vs. ~44 |
| Policy support | Very small difference between groups |

## Analytics Skills Demonstrated

- Power BI
- DAX
- KPI development
- Data modelling
- Data visualisation
- Interactive slicers
- Cross-filtering
- Segmentation
- Descriptive analytics
- Comparative analysis
- Business insight generation
- Supply-chain analytics
- Operations analytics
- Sustainability analytics
- Research synthesis
- Systems thinking

## Dataset Structure

The project dataset includes variables related to:

- Region
- Farm type
- Farm size
- Years farming
- Nature-inclusive adoption
- Adoption level
- Subsidy access
- Market-premium access
- Training access
- Perceived risk
- Peer influence
- Buyer pressure
- Biodiversity awareness
- Expected profitability
- Financial pressure
- Digital literacy
- Soil health
- Biodiversity index
- Annual farm income
- Nature-inclusive investment
- Value-chain coordination
- Policy support
- Adoption intention

## Research Layer

The project also includes a structured evidence base of **100 DOI-linked academic studies** covering themes such as:

- Nature-inclusive agriculture
- Farmer adoption and decision-making
- Economic incentives
- Agricultural policy
- Behavioural factors
- Farmer identity and social norms
- Value-chain coordination
- Biodiversity
- Soil health
- Agroecology
- Regenerative agriculture
- Sustainability transitions
- Systems thinking
- System dynamics
- Participatory modelling

The website contains the full DOI-linked reference library and maps the studies to major research themes.

## Systems-Thinking Extension

The project also explores how dashboard variables may connect in broader analytical relationships, for example:

```text
Training
  ↓
Knowledge and confidence
  ↓
Lower perceived risk
  ↓
Adoption intention
  ↓
Adoption
```

and:

```text
Financial pressure
  ↓
Transition risk
  ↓
Adoption intention
  ↓
Adoption
```

This extension helps connect descriptive analytics with systems-oriented thinking for future research and modelling.

## Repository Structure

```text
.
├── index.html
├── README.md
├── research.pbix
├── Nature_Inclusive_Agrifood_PowerBI_Research_Data.xlsx
└── Nature_Inclusive_Agrifood_100_Articles_DOI_Library.xlsx
```

## Website

The public project page presents:

- Portfolio positioning
- Power BI dashboard views
- KPI results
- Analytics capabilities
- Agrifood and supply-chain context
- Research synthesis
- Systems-thinking interpretation
- Methodology
- 100-paper DOI reference library

## Tools

**Analytics:** Power BI, DAX, Excel  
**Additional tools:** SQL, Python, Tableau  
**Domain:** Agriculture, Agribusiness, Supply Chain, Operational Logistics  
**Research:** Literature synthesis, sustainability transitions, systems thinking

## Author

**Vennela Sirusala**

LinkedIn: https://www.linkedin.com/in/vennela-sirusala-8001bb216/  
GitHub: https://github.com/vennelasirusala15-source

## Live Project

https://vennelasirusala15-source.github.io/Agrifood-Supplychain-Analytics-/

## Keywords

`Power BI` `Data Analytics` `Business Analytics` `Supply Chain Analytics` `Operations Analytics` `Agribusiness` `Agriculture` `DAX` `Data Visualization` `KPI Development` `Business Intelligence` `Systems Thinking`
