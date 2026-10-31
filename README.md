
# Bayesian Data Analysis for Agriculture Science: What, Why, and How

## Workshop details

<details open>
	<summary>...</summary>

**Where:** CANVAS 2026 in Portland, Oregon. 

**When:** October 31st, 3-5pm and November 1st, 9-5pm. 

**Facilitators:** Katherine Muller, Frederi Viens, Kate White, Quadri Popoola, Jeff Strock, Deirdre Griffin LaHue, Long-Term Agronomic Research and Soil Science communities. 

**Description:** Bayesian data analysis addresses common limitations in agricultural datasets such as small/uneven sample sizes and missing data but is underused in agricultural research. This workshop will introduce Bayesian data analysis, why it is useful, and how to implement it in R using the ‘brms’ package. You will hear researchers share real-world examples illustrating the use of Bayesian methods in agricultural research and you will implement your own Bayesian data analysis project, with the option of bringing your own analysis-ready dataset.

</details>

## Workshop materials

<details open>
	<summary>...</summary>
  
- [Syllabus](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/Syllabus.pdf)
- [Slides](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/WorkshopSlides.pdf)
- [Mini Bayesian analysis project](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/miniProject)

</details>

## Case studies

<details>
	<summary>...</summary>
	
Bayesian Correlation - PCA Approach for Soil Quality Assessment, Quadri Popoola

- [Slides](Link TBA)

Integrating long-term crop rotation experiments with the DRIVES Network, Katherine Muller

-  [DRIVES project website](https://www.drives-network.org/)
- [Slides](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/DRIVEScaseStudy.pdf)
- Bayesian analysis example: [Bybee-Finley et al. 2024, Rotational complexity increases cropping system output under poorer growing conditions](https://doi.org/10.1016/j.oneear.2024.07.008)
- [Bayesian analysis code](https://doi.org/10.15482/USDA.ADC/25943899)

Agronomic research in Malawi, Frederi Viens

- [Han et al. 2019, A Bayesian analysis of longitudinal farm surveys in Central Malawi reveals yield determinants and site-specific management strategies](https://doi.org/10.1371/journal.pone.0219296)
- [Tu et al. 2022, A Bayesian approach to understand controls on total and labile soil carbon in cultivated soils of Central and Southern Malawi](https://doi.org/10.1016/j.geoderma.2022.115746)

</details>

## Supplementary materials

<details open>
	<summary>...</summary>
These materials were developed for a January 2026 workshop, [*Bayesian statistics in Sustainability Science with a focus on Agrarian Societies and Ecosystem Services in the Lake Chad Basin*](https://github.com/lakechadproject/BayesWorkshop2026) developed for the [Sustainability Lake Chad Project](https://www.sustainabilitylakechad.com/).
  
</details>

### Computational tools and setup
<details>
	<summary>...</summary>

#### *Written setup instructions*:

- [Install software](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/setupinstructions/SetupPart1_installSoftware.md)
- [Set up Bayesian packages in R](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/setupinstructions/SetupPart2_BayesianPackages.md)
- [Computational workflow](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/setupinstructions/SetupPart3_ComputationalWorkflow.md)

#### *Videos*:

- [Why R and R studio?](https://youtu.be/nlBJbyaClpI?si=TKxwwMC066XgpOzD)
- [Why Git and Github?](https://youtu.be/m8XTHLjRJYg?si=DEbGYji42h1c33q1)
- [Installing R and R studio](https://youtu.be/bECWYQgqCqs?si=3FQc2SKaUe112kO6) (For new R users)
- [Updating old versions of R and R studio](https://youtu.be/Hlv14tEY6gQ?si=L0g0IaPzrM3RVVb9) (*For those who haven't used R in a while*)
- [Making a custom package library for R](https://youtu.be/ynfiEe9T5bc?si=y6_QX4SpKccw8Ly0) (*An optional step that makes it easier to manage packages across computers and software updates*) 
- [Setup Git and Github with R studio](https://youtu.be/Yi1pWV3f3RI?si=dL2NUctNCjHwTcyF) (*An optional step if you want to use Git and Github for version control*)
- [RStudio basics](https://youtu.be/_rieqQ4rcgg?si=GPb3hHJ5jOQUTv0y) 
- [Why and how to use RStudio Projects](https://youtu.be/6BBTi6dOSUc?si=gUGU8db6PnvexYZo)
- [Setting up an RStudio Project with Git/Github](https://youtu.be/2JAZB7geTUM?si=R8n95QnMs8MEc76C)
- [Using Git/Github for version control in R studio](https://youtu.be/UGp4yaAa3fg?si=kgqJ4wR2Uc38MwZZ)


</details>

### Building models from research questions

<details>
	<summary>...</summary>

1. Telling a data story. [Video](https://youtu.be/VA8hZXEoSxU?si=7F3rVlzSTEAao4YJ), [Exercises](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/exercises/TellingADataStoryExercises), [Slides](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/TellingADataStorySlides.pdf)
2. Using causal diagrams to build models [Video](https://youtu.be/3wbwSOsG3N0?si=QHDwYGyT-lYK1Z8u), [Exercises](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/exercises/CausalDiagramExercises), [Slides](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/CausalDiagramSlides.pdf)

</details>

### Theory fundamentals

<details>
	<summary>...</summary>
  
1. What/Why Bayes?: [Video](https://youtu.be/r7a_ju_l08I?si=rfazG5zN0FvqINMX)
2. Basics of Bayesian inference: [Video](https://youtu.be/7ZWfpiweRIA?si=EBXpC2taAAD2tV01), [Slides](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/BasicsOfBayesianInferenceSlides.pdf)
3. Bayesian estimation for linear models: [Video](https://youtu.be/r4sldw4kLy0?si=03sv6u65gjO2mh_8), [Notes](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/EstimatingLinearModelsWithBayes.pdf)
4. Basics of Bayesian computation: [Video](https://youtu.be/8Rcxv3AX0lg?si=NfDYzxmNhvdTzCpA), [Slides](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/slides/BasicsOfBayesianComputationSlides.pdf), [Gibbs sampler code and exercises](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/exercises/GibbsSamplerExercises)

</details>


### R coding basics

<details>
	<summary>...</summary>
	
### *You Can Learn R*

This module was developed by Dr. Sam Manski for a 2023 workshop in Ethiopa, moderated by Dr. Frederi Viens. Dr. Manski developed and tested this material as a component of his PhD dissertation at Rice University. 

Rice students and 2023 workshop participants gave glowing reviews about how this module helped make learning R accessible and fun. 

You can find Dr. Manski's original workshop materials on Posit Cloud: https://posit.cloud/content/5486172. This folder contains a PDF copy of his original book chapter and R exercises with minor revisions for an asynchronous format.  
- [Book](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/blob/main/RcodingBasics/YouCanLearnR/You_Can_Learn_R.pdf)
- [Exercises](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/RcodingBasics/YouCanLearnR/Exercises)
- [Exercise solutions](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/RcodingBasics/YouCanLearnR/Exercise_Solutions) 

### *Additional practice *
[Exercises](https://github.com/DRIVES-Project/CANVAS2026_BayesWorkshop/tree/main/RcodingBasics/AdditionalRpractice)


</details>