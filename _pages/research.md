---
title: ""
permalink: /research/
author_profile: true
---



Policies to Address U.S. Racial-Ethnic Inequality in Exposure to PM<sub>2.5</sub>
=====

The Clean Air Act has dramatically reduced outdoor air pollution levels in the US over the past decades, yet national racial-ethnic exposure disparities persist. People of color, and low-income populations are exposed to higher PM<sub>2.5</sub> concentrations. It is unknown whether the current government policies for improving air quality and adressing environmental injustice will adress or eliminate those exposure disparities.


I have published two reseach papers on this topic. [Wang et al. PNAS. 2022](https://www.pnas.org/doi/10.1073/pnas.2205548119) investigates three general emission-reduction approaches, and compare their optimal ability to address the disparity. [Wang et al. Science. 2023](https://www.science.org/doi/10.1126/science.adg9931) quantifies the effects of  Climate and Economic Justice Screening Tool (CEJST), which is a signiture component of Biden Administration’s Justice40 Initiative, and is the current method to define disadvantaged communities. In both research projects, we employ [InMAP](http://spatialmodel.com/inmap/) (Intervention Model for Air Pollution) source-receptor matrix ([ISRM](https://zenodo.org/record/2589760#.Y2g76ezMJK8)) to predict how changes in emissions impact annual-average PM<sub>2.5</sub> concentrations and exposure inequalities.

<figure>
<p align="center">
  <img align="middle" src="/images/compare_three_approaches.png" width="400px" style="width:50%"/>
<figcaption align="left"><b>PM<sub>2.5</sub> exposure disparity reduction curves.</b> Current conditions are the left side (i.e., "do nothing" at x=0) and a complete (100%) emission-reduction is the right side (i.e., achieving zero emissions: lower-right, at x=30.4 MT/y). The plot compares three approaches to emission-reduction: "location" (green line), "sector" (blue line), and "NAAQS-like" ( i.e., employing a concentration standard, here 6 $\mathrm{\mu g/m^{3}}$; orange line). An "equal reduction" approach, where all emissions are reduced proportionately, would be a straight line (black dotted line). The "location" approach (green line) can eliminate national disparities with modest total emission reductions, whereas with the other two approaches, national disparities remain even after substantial emission reductions)</figcaption>
</p>
</figure>

We compare three three broad approaches of emission reductions: 1) "location"-specific approach; 2) "sector"-specific approach; and 3) "NAAQS-like" approach. "Sector" and "NAAQS-like"  mirror aspects of current air quality regulations, "location" would be a new regulatory approach. Our results suggest that two main current regulatory strategies are ineffective at addressing national average racial-ethnic inequalities. In contrast, those inequalities can be eliminated with modest emission-reduction (optimal: ~1% of total emissions) using a location-specific approach. That approach is not included in current national regulatory frameworks (but it is being discussed, and some states have implemented it); also, that approach does as well as or better than the two other approaches, at the goal of reducing overall population average. This research informs the active national conversation about addressing environmental injustice, by providing a scientifically grounded approach for eliminating disparities.

<figure>
<p align="center">
  <img align="middle" src="/images/Science_figure2.png" width="400px" style="width:90%"/>
<figcaption align="left"><b>Disparities in PM<sub>2.5</sub> exposure and deaths for the three future scenarios. </b> Disparities in PM2.5 exposure and deaths for the three future scenariosDisparities relative to the population-average, for “business as usual” (BAU) scenario and when emission-reductions in disadvantaged communities (DAC) are double or quadruple the BAU rate. Top row, absolute disparities; bottom row, relative disparities. </figcaption>
</p>
</figure>

We find that air pollution exposure disparities will persist if the past trends of emission-reductions are to continue into the future. We also reveal that Biden administration’s current method for identifying disadvantaged communities (CEJST), if used to identify where to prioritize emissions reductions, will only eliminate disparities by income, but will not meaningfully reduce racial-ethnic air pollution disparities, even if the emissions reductions are aggressive or very aggressive. This is because CEJST is blind to racial/ethnic composition, and is also because the policy effects on disparities are not quantified prior to implementation. The largest exposure disparities are by race-ethnicity; disparities by race are larger than, and statistically distinct from, those by income. So policies cannot ignore race if they wish to eliminate air pollution disparities. New tools now make it possible to investigate whether proposed actions will eliminate the exposure disparities we see.


**Publication**: [Wang et al. PNAS. 2022](https://www.pnas.org/doi/10.1073/pnas.2205548119), [Wang et al. Science. 2023](https://www.science.org/doi/10.1126/science.adg9931) <br/>


<br/>

Environmental Inequality in China
======
<figure>
<p align="center">
  <img align="middle" src="/images/EJchina_wide.png" width="400px" style="width:90%"/>
<figcaption align="left"><b>Ambient pollution concentration by individual's socioeconomic status.</b> Estimated ambient (A) NO<sub>2</sub> and (B) PM<sub>2.5</sub> concentration by individual’s rural-to-urban migration status, education, occupation, and income quintile. Box and whiskers indicate the 10th, 25th, 50th, 75th, and 90th percentiles and the mean (red circle). Income levels are displayed in the lower right of (B). The percentage numbers of individuals in each subgroup are annotated at the bottom of (A). </figcaption>
</p>
</figure>

Air pollution disparities by socioeconomic status (SES) display an inverse relationship (i.e., higher concentrations for lower-SES populations) in US and many high-income countries. However, my study indicate a reverse pattern in China (a country accounting for 26% of global premature deaths from ambient air pollution). Combing air pollution data from a national empirical model and demographic data from (1) national gridded GDP per capita, and (2) a national representative sample of 21,095 individuals from the China Health and Retirement Longitudinal Study ([CHARLS](https://charls.pku.edu.cn/en/)), we quantify air pollution disparities among individual’s rural-to-urban migration status; SES factors (education, occupation, and income); and minority status. Results indicate that in China, ambient NO<sub>2</sub> and PM<sub>2.5</sub> concentrations are higher for high-SES than for low-SES individuals; these results are robust to multiple sensitivity analyses. The findings imply that in China’s current industrialization and urbanization stage, economic development is correlated with both SES and air pollution. 

**Publication**: [Wang et al. EHP. 2022](https://ehp.niehs.nih.gov/doi/full/10.1289/EHP9872)<br/>


<br/>

Spatial Decomposition of Air Pollution
======

<figure>
<p align="center">
  <img align="middle" src="/images/spatial_decomposition.jpg" width="400px" style="width:50%"/>
<figcaption align="left"><b>Spatial decomposition of air pollution into four spatial components: long-range, mid-range, neighborhood, and near-source.</b> The plot is a schematic diagram of decomposed air pollution concentrations along a transect line across the urban center. </figcaption>
</p>
</figure>
Length scales for spatial variability of air pollution concentrations depend on the pollutant and the location. We develop a readily scalable algorithm based on “spatial-increment”, to decompose the air pollution concentration into four spatial components: long-range, mid-range, neighborhood, and near-source. We apply the algorithm to annual-average concentrations of outdoor NO<sub>2</sub> and PM<sub>2.5</sub> for all census blocks in the contiguous US. We show that for NO<sub>2</sub>, “neighborhood” and “mid-range” components dominate both within-city and between-city concentration differences, yet for PM<sub>2.5</sub>, the “long-range” component at regional level dominates. Our results can be used to estimate the contribution of sources at different distances from the receptor to the annual average pollution in a location of interest. The datasets have already been applied in environmental health and environmental justice analyses.

**Publication**: [Wang et al. AE. 2020](https://www.sciencedirect.com/science/article/pii/S1352231020302077); [Lefler et al. EH. 2019](https://link.springer.com/article/10.1186/s12940-019-0544-9)<br/>
**Dataset**: [Wang. Mendeley Data. 2020](https://data.mendeley.com/datasets/ckdvx3d3zc/1); [Wang. Mendeley Data. 2021](https://data.mendeley.com/datasets/bz8pdbcvf2/2)
