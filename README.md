<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0b3d2e,100:1f7a5a&height=170&section=header&text=Aboubacar%20HEMA&fontSize=42&fontColor=ffffff&fontAlignY=38&desc=Research%20Analyst%20%26%20Data%20Scientist%20%7C%20IFPRI%20%2F%20CGIAR&descAlignY=60&descSize=16" width="100%" alt="Aboubacar HEMA banner"/>

**Food security · Climate and conflict shocks · Earth observation · Applied econometrics · Sahel and Sub-Saharan Africa**

<a href="https://abson-dev.github.io"><img src="https://img.shields.io/badge/Project%20portfolio-Open%20the%20website-1f7a5a?style=for-the-badge&logo=githubpages&logoColor=white" alt="Project portfolio website"/></a>

<a href="https://www.ifpri.org/profile/aboubacar-hema/"><img src="https://img.shields.io/badge/IFPRI-Profile-0b3d2e?style=flat-square" alt="IFPRI profile"/></a>
<a href="https://scholar.google.com/citations?user=owTdwCYAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-Publications-4285F4?style=flat-square&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>
<a href="https://orcid.org/0000-0001-9756-7270"><img src="https://img.shields.io/badge/ORCID-0000--0001--9756--7270-A6CE39?style=flat-square&logo=orcid&logoColor=white" alt="ORCID"/></a>
<a href="https://www.linkedin.com/in/aboubacar-hema-2768b7148/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:a.hema@cgiar.org"><img src="https://img.shields.io/badge/Email-a.hema%40cgiar.org-555555?style=flat-square&logo=maildotru&logoColor=white" alt="Email"/></a>

</div>

---

## About

I am a Research Analyst and Data Scientist at the **International Food Policy Research Institute (IFPRI / CGIAR)**, Development Strategies and Governance Unit, based in Dakar, Senegal. My work turns household surveys, routine surveillance data, satellite observations and conflict event records into reproducible evidence for food security and humanitarian decision making.

- **Research focus:** food security measurement, household shocks and coping strategies, political violence and conflict diffusion, climate variability, impact evaluation (including mental health and psychosocial outcomes).
- **Methods:** applied econometrics, spatial statistics, species distribution modelling, machine learning, AI agent development, survey harmonisation, cost-benefit analysis.
- **Current direction:** operational early warning systems that combine satellite data, climate reanalysis and sparse ground records into calibrated, interpretable risk signals.
- **Teaching:** visiting lecturer in statistics, spatial data science and Python at ENSAE Dakar and Université Numérique Cheikh Hamidou Kane.

---

## Featured projects

> Click any project title to open the repository. All pipelines are designed to be reproducible; where microdata belong to governments or partners, the code is public and the data are available from the data owners on request.

<table>
<tr>
<td width="50%" valign="top">

### [ENSA Chad harmonisation](https://github.com/Abson-dev/ensa-chad-harmonization)
**Food security · Survey harmonisation**

Config-driven, tested workflow harmonising **14 rounds** of Chad's national food security survey (ENSA, Oct 2018 to Oct 2025; **197,947 households**) into comparable thematic datasets: food consumption, coping strategies, expenditure and more. Indicators are recomputed and validated against the original analysts' scores, with provenance manifests.

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white) ![R Shiny](https://img.shields.io/badge/R-Shiny-276DC3?style=flat-square&logo=r&logoColor=white) ![Stata](https://img.shields.io/badge/Stata-checks-1A5F91?style=flat-square)

</td>
<td width="50%" valign="top">

### [sdmApp](https://github.com/Abson-dev/sdmApp)
**Earth observation · Species distribution modelling**

R package with a Shiny interface that makes species distribution modelling accessible to non-programmers: raster predictors and occurrence data in, spatially blocked cross-validation (blockCV), predictor screening (CENFA), MaxEnt and other models out, plus the generated R code for full reproducibility. Example data: agroforestry tree species in Niakhar, Senegal.

![R](https://img.shields.io/badge/R-package-276DC3?style=flat-square&logo=r&logoColor=white) ![Shiny](https://img.shields.io/badge/Shiny-app-276DC3?style=flat-square) ![License](https://img.shields.io/badge/license-GPL--3-blue?style=flat-square) ![Stars](https://img.shields.io/github/stars/Abson-dev/sdmApp?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Ituri epidemiological situation](https://github.com/Abson-dev/ituri-situation-epidemiologique)
**Public health surveillance · Impact evaluation**

R pipeline on the weekly IDSR surveillance database for Ituri province (DRC): automated weekly epidemiological bulletin in Word, a French-language dashboard (diseases, health zones, malaria, Ebola, data quality) and a **controlled interrupted time series** analysis of routine morbidity and Ebola burden across 36 health zones. Runs end to end on synthetic data with `Rscript run_all.R --demo`.

![R](https://img.shields.io/badge/R-4.5-276DC3?style=flat-square&logo=r&logoColor=white) ![renv](https://img.shields.io/badge/renv-locked-4c9a2a?style=flat-square) ![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

</td>
<td width="50%" valign="top">

### [Niger notifiable diseases (MDO) dashboard](https://github.com/Abson-dev/msf-mdo-niger)
**Public health surveillance · Forecasting**

Ten years (2015 to 2024) of Niger's weekly notifiable disease reports cleaned into tidy, source-validated tables and served in an R Shiny dashboard: disease trends, meningitis alert thresholds, reporting completeness, maternal deaths and a DHIS2 comparison. A modelling module fits negative binomial, hurdle and endemic-epidemic models with forecasts.

![R Shiny](https://img.shields.io/badge/R-Shiny-276DC3?style=flat-square&logo=r&logoColor=white) ![Python](https://img.shields.io/badge/Python-pipeline-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Productive agricultural land (IFPRI)](https://github.com/Abson-dev/-IFPRI--Calculate-Productive-Agriculture)
**Earth observation · Agricultural land**

Google Earth Engine workflow that maps **arable land at 30 m resolution** across African countries by combining cropland extent (NASA GFSAD 2015) and cleared forest, then masking steep slopes (>15%), permanent water and impervious surfaces. One script per country, from Burkina Faso to Uganda.

![Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-JS-4285F4?style=flat-square&logo=googleearth&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-notebooks-F37626?style=flat-square&logo=jupyter&logoColor=white) ![Stars](https://img.shields.io/github/stars/Abson-dev/-IFPRI--Calculate-Productive-Agriculture?style=flat-square)

</td>
<td width="50%" valign="top">

### [Exploratory spatial statistics course](https://github.com/Abson-dev/Statistique-Exploratoire-Spatiale)
**Teaching · Spatial data science** · [Course website](https://statistique-exploratoire-spatiale.vercel.app)

Eleven practical sessions taught at ENSAE Dakar: vector and raster data, zonal statistics, risk mapping, combining health, WorldPop and ACLED conflict data into composite indicators, spatial autocorrelation, species distribution modelling and Sentinel-2 spectral indices (NDVI, NDWI, NDBI). In French, CC BY 4.0.

![Python](https://img.shields.io/badge/Python-geopandas-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-sf%20%7C%20terra-276DC3?style=flat-square&logo=r&logoColor=white) ![GEE](https://img.shields.io/badge/GEE-Sentinel--2-4285F4?style=flat-square) ![Forks](https://img.shields.io/github/forks/Abson-dev/Statistique-Exploratoire-Spatiale?style=flat-square)

</td>
</tr>
</table>

## AI agents for humanitarian data

> Tool-using LLM assistants built on top of my data pipelines. The model answers questions in English or French only through **read-only, tested tools**; the server validates every published table and chart, attaches the analytical cautions, and lists the tool calls behind each answer. Each runs on synthetic data out of the box, with no API key needed to try the tools.

<table>
<tr>
<td width="50%" valign="top">

### [ENSA data assistant](https://github.com/Abson-dev/ensa-chad-data-assistant)
**AI agent · Food security surveys, Chad**

Ask how the 14 ENSA rounds were harmonised and what they show. **15 read-only tools** trace any variable across rounds, explain recodes and quality checks, compare **58 indicators** by round, region and sex of the household head, and draft crosswalk mappings for a new round. No household record ever reaches the model; regional cells under 30 households are suppressed.

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-tool%20use-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Web app](https://img.shields.io/badge/web%20app-CLI-555555?style=flat-square) [![Tests](https://github.com/Abson-dev/ensa-chad-data-assistant/actions/workflows/tests.yml/badge.svg)](https://github.com/Abson-dev/ensa-chad-data-assistant/actions/workflows/tests.yml)

</td>
<td width="50%" valign="top">

### [MDO Niger assistant](https://github.com/Abson-dev/mdo-niger-assistant)
**AI agent · Disease surveillance, Niger**

Ask what Niger's weekly notifiable disease surveillance shows: trends, seasonality, like-for-like year comparisons, meningitis epidemic thresholds, reporting completeness and model estimates with confidence intervals. **19 read-only tools** enforce the rules an epidemiologist would: partial years are never compared with full years, missing reports are never read as zero, and case-definition changes are always flagged.

![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=flat-square&logo=python&logoColor=white) ![Claude](https://img.shields.io/badge/Claude-tool%20use-D97757?style=flat-square&logo=anthropic&logoColor=white) ![Maps](https://img.shields.io/badge/charts-maps-1f7a5a?style=flat-square) ![Skill](https://img.shields.io/badge/Claude%20Code-skill-555555?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Ituri assistant](https://github.com/Abson-dev/ituri-assistant)
**AI agent · Epidemiological surveillance, DRC** · *work in progress*

Question-and-answer agent on Ituri's IDSR surveillance data, packaged as a Claude Code skill. Indicators are computed by the R pipeline, never by the model, and a parity test checks the tools against the pipeline across diseases, zones and weeks. Evaluated on **30 questions** against answers computed independently in R. Real data stay locked until a written data-sharing agreement is in place.

![Python](https://img.shields.io/badge/Python-stdlib%20only-3776AB?style=flat-square&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-export%20%26%20evals-276DC3?style=flat-square&logo=r&logoColor=white) ![Skill](https://img.shields.io/badge/Claude%20Code-skill-D97757?style=flat-square&logo=anthropic&logoColor=white)

</td>
<td width="50%" valign="top">

### [FAYAMA.AI](https://fayama-ai.netlify.app/)
**AI venture · Food security and agricultural transformation**

AI startup I founded to build decision tools for food security, poverty targeting and agricultural transformation in Africa, drawing on satellite data, household surveys and machine learning. Multilingual website in 19 languages.

![AI](https://img.shields.io/badge/AI-food%20security-1f7a5a?style=flat-square) ![Earth observation](https://img.shields.io/badge/Earth%20observation-satellite-4285F4?style=flat-square) ![Website](https://img.shields.io/badge/website-live-success?style=flat-square)

</td>
</tr>
</table>

## Research code

> Analysis code behind IFPRI working papers, policy briefs and technical notes. Survey microdata are not redistributed; scripts document every step from raw data to published estimates.

<table>
<tr>
<td width="50%" valign="top">

### [Household coping with covariate shocks, Burkina Faso](https://github.com/Abson-dev/ANALYZE-COPING-STRATEGY-BURKINA-FASO)
**Shocks · Coping strategies · 2019 to 2023**

How households respond to conflict, climate and price shocks, using eleven waves of cross-sectional household survey data linked to an extensive set of shock indicators compiled from external sources.

![Stata](https://img.shields.io/badge/Stata-1A5F91?style=flat-square) ![Data](https://img.shields.io/badge/11%20survey%20waves-shock%20linkage-1f7a5a?style=flat-square)

</td>
<td width="50%" valign="top">

### [Household coping with covariate shocks, Mali](https://github.com/Abson-dev/ANALYZE-COPING-STRATEGY-MALI)
**Shocks · Coping strategies · 2018 to 2023**

Companion analysis for Mali using association rule mining to identify which coping strategies households combine when facing different kinds of shocks and stressors.

![R](https://img.shields.io/badge/R-arules-276DC3?style=flat-square&logo=r&logoColor=white) ![Method](https://img.shields.io/badge/association%20rules-mining-1f7a5a?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Political violence in the G5 Sahel countries](https://github.com/Abson-dev/Political-Violence-in-the-G5-Sahel-Countries)
**Conflict · Spatial indicators**

Implementation in Google Earth Engine of ACLED's conflict diffusion indicator: share of populated 10 km grid cells with high levels of violence, built from WorldPop and ACLED and aggregated to admin 2, with sensitivity analysis on the population and event thresholds. Prepared for WFP.

![Earth Engine](https://img.shields.io/badge/Google%20Earth%20Engine-4285F4?style=flat-square&logo=googleearth&logoColor=white) ![ACLED](https://img.shields.io/badge/ACLED-WorldPop-8b1e1e?style=flat-square)

</td>
<td width="50%" valign="top">

### [Small area poverty estimation, Burkina Faso](https://github.com/Abson-dev/Application-of-Fay-Herriot-Model-for-Burkina-Faso)
**Poverty mapping · Small area estimation**

Poverty headcount (FGT0) below the levels where the EHCVM 2021 survey is representative (provinces and communes), comparing direct, Fay-Herriot and machine learning estimates with conflict and climate covariates. Part of a series also covering [Senegal](https://github.com/Abson-dev/Application-of-Fay-Herriot-Model-for-Senegal), [Mali](https://github.com/Abson-dev/Application-of-Fay-Herriot-Model-for-Mali), [Niger](https://github.com/Abson-dev/Application-of-Fay-Herriot-Model-for-Niger), [Benin](https://github.com/Abson-dev/Application-of-Fay-Herriot-Model-for-Benin) and [Côte d'Ivoire](https://github.com/Abson-dev/Application-of-Fay-Herriot-Model-for-RCI).

![R](https://img.shields.io/badge/R-SAE-276DC3?style=flat-square&logo=r&logoColor=white) ![XGBoost](https://img.shields.io/badge/XGBoost-ML-555555?style=flat-square) ![Survey](https://img.shields.io/badge/EHCVM%202021-3%2C227%20households-1f7a5a?style=flat-square)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Kenya soil, food, nutrition and policy database](https://github.com/Abson-dev/kenya-fnp-db)
**Food systems · Data engineering**

Configuration-driven, provenance-tracked pipeline assembling 30 sources across five layers (geography, soil, food, health, policy) into one database keyed on a county and sub-county crosswalk, built for soil-to-nutrition pathway analysis. Every object carries publisher, licence, checksum and extraction date.

![Python](https://img.shields.io/badge/Python-package-3776AB?style=flat-square&logo=python&logoColor=white) ![Sources](https://img.shields.io/badge/30%20sources-5%20layers-1f7a5a?style=flat-square)

</td>
<td width="50%" valign="top">

### [Field boundaries for Burkina Faso](https://github.com/Abson-dev/ftw-burkina-faso)
**Earth observation · Agriculture** · *replication guide*

Guide to replicating the Fields of The World global field boundary map at 10 m for Burkina Faso: cloud-free Sentinel-2 mosaics, inference with the PRUE U-Net model, polygon extraction and confidence filtering, for seasonal updates or local fine-tuning.

![Sentinel-2](https://img.shields.io/badge/Sentinel--2-10%20m-4285F4?style=flat-square) ![Deep learning](https://img.shields.io/badge/U--Net-segmentation-555555?style=flat-square)

</td>
</tr>
</table>

<div align="center">

**[Browse all repositories →](https://github.com/Abson-dev?tab=repositories&type=source)**

</div>

---

## Toolbox

<div align="center">

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Stata](https://img.shields.io/badge/Stata-1A5F91?style=for-the-badge)
![Shiny](https://img.shields.io/badge/Shiny-276DC3?style=for-the-badge&logo=rstudioide&logoColor=white)
![Google Earth Engine](https://img.shields.io/badge/Earth%20Engine-4285F4?style=for-the-badge&logo=googleearth&logoColor=white)
![QGIS](https://img.shields.io/badge/QGIS-589632?style=for-the-badge&logo=qgis&logoColor=white)
![ArcGIS](https://img.shields.io/badge/ArcGIS-2C7AC3?style=for-the-badge&logo=arcgis&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

</div>

---

## Background

| | |
|---|---|
| **Experience** | Research Analyst, IFPRI (2022 to present) · Data Analyst, IOM (2022 to 2023): impact evaluations and MHPSS survey analysis in West Africa · Remote Sensing and ML Engineer, CIRAD (2020 to 2021): tree species distribution in agroforestry parklands |
| **Education** | MITx MicroMasters, Data, Economics, and Design of Policy (2024) · MITx MicroMasters, Statistics and Data Science (2023) · Statistician Engineer with distinction, ENSAE Dakar (2020) · BSc Computer Science with distinction, University of Ouagadougou (2016) |
| **Languages** | French, Bambara, Senoufo (native) · English (professional) |

---

## GitHub activity

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=Abson-dev&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&theme=transparent&title_color=1f7a5a&icon_color=1f7a5a" alt="GitHub stats"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Abson-dev&layout=compact&langs_count=8&hide_border=true&theme=transparent&title_color=1f7a5a" alt="Top languages"/>

<img src="https://streak-stats.demolab.com/?user=Abson-dev&hide_border=true&theme=transparent&ring=1f7a5a&fire=1f7a5a&currStreakLabel=1f7a5a" alt="GitHub streak"/>

![Profile views](https://komarev.com/ghpvc/?username=Abson-dev&color=1f7a5a&style=flat-square&label=Profile+views)

</div>
