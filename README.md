# My Research
Reverse chronological summary of my 2.5 years of research as a data scientist / machine learning engineer:

## Table of Contents:
| Project | Folder | Core Tech (some release-restricted) |
|---------|-------------------|------------------|
| **1. ORNL GDM – Power-Outage Prediction** | [`Graduate/Power_Outage_Prediction/`](Graduate/Power_Outage_Prediction/) | PyTorch, TensorFlow, Python, PostgreSQL |
| **2. ORNL GeoAI – Land-Use Segmentation** | [`Graduate/Land_Use_Classification/`](Graduate/Land_Use_Classification/) | PyTorch, Python, QGIS |
| **3. UTK – Land-Use Dynamics** | [`Undergraduate/Land_Cover/`](Undergraduate/Land_Cover/) | Python, Alteryx, Tableau |
| **4. UTK - TN Ag Dashboard** | [`Undergraduate/Dashboard/`](Undergraduate/Dashboard/) | Tableau, Python |
| **5. UTK - Farmland Cost** | [`Undergraduate/Farmland_Pricing/`](Undergraduate/Farmland_Pricing/) | Python |

## Oak Ridge National Laboratory - Geospatial Data Modeling Group

### Improving US power outage prediction and response (May 2025 - Aug 2025).
- Developed a method for categorizing extreme energy outage events to improve grid resilience using unsupervised learning (accepted to ACM SIGSPATIAL 2025; invention disclosure filed).
- Developed an integrated pipeline using outage clusters and deep learning-based prediction methods for improved Department of Energy forecasting, risk assessment, and response.
  
## Oak Ridge National Laboratory - GeoAI Group

### Improved ORNL's land-use classification capabilities (September 2024 - May 2025).
- Curated a satellite imagery dataset then developed several land-use/land cover segmentation models, differing by deep learning architecture, channels, and pre-training.
- Overall, improved inference speed by ~1,000x and granularity by >4,000x while maintaining high performance (0.86 accuracy, 0.58 mIoU).
- Tested the efficacy of few-shot learning for teaching new classes to our models for fast, critical adaptation tasks.
- A summary poster follows: ![Segmentation Results Poster](Graduate/Land_Use_Classification/Poster.png)

## University of Tennessee, Knoxville - Agricultural & Resource Economics Department

### Led research on US land-use dynamics (April 2023 - August 2024).
- Sourced, cleaned, analyzed, visualized, and modeled data to investigate the trends of US land-use, and its effects, including the novel implementation of a SUR model to investigate the interaction of land-use types (including exogenous factors). Culminated in a first author paper (under review).
- One major finding follows:
> We found that the acreage of each given land cover type (of cropland, pasture, forest, hay, developed open land, and developed non-open land) can predict with statistical significance the acreage of most other land cover types. Most notably from the interactions of different land cover types, the equations for cropland and forest suggest a major difference between the presence of open (very low density) and non-open developed land, with the presence of open developed land predicting a large increase in cropland and forest acreage within a given county, and with non-open development predicting a large decrease of the same, all else equal. We also find significant predictability from median income, the number of households within a county, and year fixed effects (all as controls), but most interestingly from Tennessee Agricultural Enhancement Program investment, a cost-share initiative. For each additional $1,000 USD in TAEP investment, a given county is expected to have 86 more acres of cropland, 127 more acres of pasture, and 27 more acres of hay, with 60 less acres of forest, seven less acres of open development, and four less acres of non-open development, all else equal.

### Developed a farmer-facing dashboard to democratize informational resources (June 2024 - August 2024).
- Built for TN state agencies to make production trends, trial results, and checkoff and trial center locations accessible to corn, soy, and livestock producers.
- Some of these farmer-facing visualizations are on [Tableau](https://public.tableau.com/app/profile/benjamin.koob/vizzes), accruing 25k+ views.

### Started research on farmland pricing behavior (September 2023 - February 2024).
- Created automations for data extraction, developed regression models, and investigated theorized pricing interactions for high-acreage parcels.

