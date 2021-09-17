# Robust-causal-inference-for-long-term-policy-decisions
Repository for the paper entitled: Robust causal inference for long-term policy decisions: cost effectiveness of interventions for obesity using Mendelian randomization

This repository contains the original manuscript, tables, figures, supplementary information and complete analysis code (top level), and the accepted paper and all additional files (in the folder).

Abstract for the study:

Background: The prevalence of obesity has increased in the United Kingdom, and reliably measuring the impact on quality of life and the total healthcare cost from obesity is key to informing the cost-effectiveness of interventions that target obesity, and determining healthcare funding. Current methods for estimating cost-effectiveness of interventions for obesity may be subject to confounding and reverse causation. The aim of this study is to apply a new approach using mendelian randomisation for estimating the cost-effectiveness of interventions that target body mass index (BMI), which may be less affected by confounding and reverse causation than previous approaches.

Methods and findings: We estimated health-related quality-adjusted life years (QALYs) and both primary and secondary healthcare costs for 310,913 men and women of white British ancestry aged between 39 and 72 years in UK Biobank between recruitment (2006 to 2010) and 31 March 2017. We then estimated the causal effect of differences in BMI on QALYs and total healthcare costs using mendelian randomisation. For this, we used instrumental variable regression with a polygenic risk score (PRS) for BMI, derived using a genome-wide association study (GWAS) of BMI, with age, sex, recruitment centre, and 40 genetic principal components as covariables to estimate the effect of a unit increase in BMI on QALYs and total healthcare costs. Finally, we used simulations to estimate the likely effect on BMI of policy relevant interventions for BMI, then used the mendelian randomisation estimates to estimate the cost-effectiveness of these interventions.

A unit increase in BMI decreased QALYs by 0.65% of a QALY (95% confidence interval [CI]: 0.49% to 0.81%) per year and increased annual total healthcare costs by £42.23 (95% CI: £32.95 to £51.51) per person. When considering only health conditions usually considered in previous cost-effectiveness modelling studies (cancer, cardiovascular disease, cerebrovascular disease, and type 2 diabetes), we estimated that a unit increase in BMI decreased QALYs by only 0.16% of a QALY (95% CI: 0.10% to 0.22%) per year.

We estimated that both laparoscopic bariatric surgery among individuals with BMI greater than 35 kg/m2, and restricting volume promotions for high fat, salt, and sugar products, would increase QALYs and decrease total healthcare costs, with net monetary benefits (at £20,000 per QALY) of £13,936 (95% CI: £8,112 to £20,658) per person over 20 years, and £546 million (95% CI: £435 million to £671 million) in total per year, respectively.

The main limitations of this approach are that mendelian randomisation relies on assumptions that cannot be proven, including the absence of directional pleiotropy, and that genotypes are independent of confounders.

Conclusions: Mendelian randomisation can be used to estimate the impact of interventions on quality of life and healthcare costs. We observed that the effect of increasing BMI on health-related quality of life is much larger when accounting for 240 chronic health conditions, compared with only a limited selection. This means that previous cost-effectiveness studies have likely underestimated the effect of BMI on quality of life and, therefore, the potential cost-effectiveness of interventions to reduce BMI.

Funding: Health Foundation.

Authors: Sean Harrison*, PhD [1,2], Padraig Dixon, DPhil [1,2], Hayley E Jones, PhD [2], Alisha R Davies, PhD [3], Laura D Howe^, PhD [1,2], Neil M Davies^, PhD [1,2,4]

* Corresponding author (email: sean.harrison@bristol.ac.uk)

^ denotes equal contribution

1.	MRC Integrative Epidemiology Unit (IEU), Population Health Sciences, Bristol Medical School, University of Bristol, Bristol
2.	Population Health Sciences, Bristol Medical School, University of Bristol, Canynge Hall, 39 Whatley Road, Bristol
3.	Research and Evaluation Division, Public Health Wales NHS Trust, Capital Quarter No.2, Tyndall Street, Cardiff
4.	K.G. Jebsen Center for Genetic Epidemiology, Department of Public Health and Nursing, NTNU, Norwegian University of Science and Technology, Norway.
