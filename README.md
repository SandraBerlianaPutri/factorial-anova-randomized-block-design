# Factorial ANOVA with Randomized Complete Block Design

## About
This project applies factorial analysis of variance (ANOVA) within a Randomized Complete Block Design (RCBD) to two experimental case studies. The analyses examine the effects of treatment factors, their interactions, and blocking effects using R.

## Project Analysis
- [View Full Analysis on RPubs](https://rpubs.com/sandraberlianaputri/factorial-anova-randomized-block)

## Dataset
The project uses two experimental datasets from an experimental design coursework assignment.

**Case Study 1: Plant Height**
- **Response variable:** `Tinggi` — plant height
- **Factors:** `Varietas` (plant variety) and `Pupuk` (fertilizer)
- **Blocking variable:** `Kelompok`
- **Observations:** 8 experimental observations

**Case Study 2: Orange Syrup pH**
- **Response variable:** `pH` — syrup pH
- **Factors:** `Sitrat` (citric acid concentration) and `Gula` (sugar concentration)
- **Blocking variable:** `Kelompok`
- **Observations:** 8 experimental observations

Each case study contains two factor levels and two blocks, with one observation per treatment combination within each block.

## Methods
- **Factorial ANOVA:** Evaluated the main effects of each factor and their interaction.
- **Randomized Complete Block Design:** Included block effects to account for potential variation between groups.
- **Interaction Analysis:** Used interaction plots to examine how the effects of one factor varied across levels of another.
- **Hypothesis Testing:** Assessed statistical significance at the 5% level.

## Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University.
