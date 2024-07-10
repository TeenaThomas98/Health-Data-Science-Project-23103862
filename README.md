# Health-Data-Science-Project-23103862
"Estimating and Visualizing Prevalence of Small Vulnerable Babies in India Using Data from a Complex Survey Design: A Secondary Data Analysis of NFHS-5 Data"

# AIM
The aim of this study is to estimate and visualize the prevalence of small vulnerable babies for all 707 districts in India utilizing design based and model-based approaches 

# BACKGROUND 

## 1. Low Birth Weight

### 1.1 Statistics and public health importance 

According to World Health Organization (WHO) Low Birth Weight (LBW) is defined as a birth weight of less than 2500 grams (up to and including 2499 grams).[1] The LBW is a global public health issue because it’s a significant obstacle related to maternal and child healthcare. Low Birth Weight is an important public health indicator related to antenatal care (ANC), maternal health, nutrition health, economic vulnerability, infant and child mortality, especially in the Low and Middle-income countries (LMICs). The global burden of LBW is 14.6%, which accounts for 25 million LBW birth annually, where 95% of these are occurring in LMICs with South Asia accounting for nearly 52% of global burden.[2] The prevalence of LBW in India estimated in the nationally representative survey data reported a reduction of LBW as time progresses, the prevalence have reduced from 22% in National Family Health Survey 3 (NFHS 3) to 17.4% in NFHS – 5.[3] Even though the prevalence of LBW is declining, India is not on track towards achieving the target of 30% reduction in LBW burden by 2025 proposed by WHO in low birth weight policy brief.[4] The LBW has become a new public health threat globally as it is one of the strongest risk factors associated with neonatal mortality and morbidity, LBW has contributed to 60 – 80% of neonatal deaths across the world. Even though India is making some improvement in the numbers LBW is still a social issue of importance, the difference within the country also varies very much, and some states come up with statistics that can be compared to developed countries. In India the LBW prevalence ranges from 21.36% to the lowest 3.36%, the variation may be due to the difference in socioeconomic factors.[5] The sustainable development Goals (SDGs) aims at improving health, nutritional, and social wellness. One of the main objectives of the SDGs is to “ensure healthy lives and promote well-being for all at all ages”, through social and economic interventions.[6]  

### 1.2 Causes and effect of LBW 

The LBW is a multifactorial phenomenon with several known maternal and fetal risk factors. The maternal factors associated with LBW are maternal age (age below 16 years and above 46 years), multiple pregnancies, obstetric complications, trauma, pre-eclampsia or eclampsia, certain infections, chronic maternal conditions (hypertension, diabetes), nutritional status, and substance abuse (smoking, alcohol).[7–9] The fetal factors of associated with the LBW are intrauterine growth retardation, fetal infection and anomalies, and some conditions related to placenta.[10] The reports from various studies report that being lower socioeconomic backgrounds, women with their pregnancies at their teenage years and lower education of women are contributing to the LBW.  

The effect of LBW varies from immediate issues to problems in their later life, the immediate effects may be breathing problems, bleeding in brain, patent ductus arteriosus, retinopathy, jaundice, and other infections. Whereas some of effect in later stage of life are diabetes, heart disease, high blood pressure, intellectual and developmental disabilities, metabolic syndrome and obesity. 

## 2. Demographic and Health surveys (DHS) 

Demographic and Health surveys (DHS) are a series of nationally- representative household surveys that aim to collect information on various demographic and health indicators over 90 countries which includes more than 400 surveys. These are the surveys conducted periodically every five years, which allow the comparison of the collected data within the countries as well as between the countries over time. The data collected through the surveys are used by governments, policymakers, researchers, and various organizations to make evidence-based policies and programs that aim at the well-being of people. As the data collected in the surveys are comparable performance of the countries can be assessed.[11] 

The DHS program is funded and supported by the United States Agency for International Development (USAID) and implemented by ICF International, a global consulting and technology services company. The surveys collect data on a wide range of indicators including anemia, child health, gender/domestic violence, education, environment health, family planning, HIV/AIDS knowledge attitude and behavior, infant and child mortality, malaria, nutrition, tobacco use etc. The surveys are of two types of standard and interim DHS surveys; standard DHS surveys are conducted using a larger sample size and are typically conducted every five years, which allows comparison over time. Whereas the interim DHS surveys are focused on the collection of information on key performance indicators, these surveys are conducted between the usual rounds of DHS with a comparatively smaller sample size.[11] 

The data collected are freely available to the public and can be accessed through the official website of DHS, where the public can download the datasets, reports, and other resources for analysis and research purposes. Various research conducted in different parts of the world has already used the DHS data, which helped create effective public health policies. 

Many countries have conducted multiple surveys to understand the trend and to create evidence-based policies. Countries participating in the DHS program are primarily countries that receive USAID assistance, several non-USAID-supported countries are also participating with the funding and support from various other organizations. 

The main objectives of DHS are collecting demographic data, assessing health status and health behavior, monitoring health trends, informing policy and program development, supporting research and analysis, and strengthening the health information system.[11] Overall, the DHS survey provides comprehensive data on the demographics and health of the population. 

### 2.1 Questionnaire 

The data collection of the DHS surveys is conducted using a standard model questionnaire developed with written descriptions for certain questions. Administration of the model questionnaire provides data that is comparable across the countries. The model questionnaire is reviewed and modified in each phase of DHS, typically a country is asked to adopt the model questionnaire completely, however, changes can be made to the questionnaire based on the country. The DHS surveys consist of three core questionnaires: A household questionnaire, a Women’s questionnaire, and a Men’s questionnaire. In the household questionnaire biomarker questionnaire is also included, which collects data on the biomarkers of the eligible participants. In 2015, the DHS program introduced the fieldworker questionnaire, which collects the characteristics of the field investigator or interviewer. In 2019, for the eighth phase of DHS, the core questionnaires were revised.[12] 

### 2.2 Sampling and sample weightage 

The sampling design is usually a two-stage probability sampling obtained from the most recent census frame. In the DHS surveys, to reduce the sampling errors stratification is done. In the DHS surveys the stratification of samples is done based on geographic region and by urban/rural setting. In the first stage of sampling, primary sampling units (PSUs) which are typically census enumeration areas (EAS) are selected with probability proportional to size (PPS) within each stratum. In the second stage, a complete list of households from the survey cluster i.e., PSUs is obtained; once the listing is done fixed number of households are selected by equal probability systematic sampling from the survey clusters.[11][13] 

The overall probability of selection of a household will differ from cluster to cluster because the probability of selection of each household within the sample is the multiple of the probability of selecting the cluster with the probability of electing the household within the cluster. 

Even though the sampling is done systematically, the data must be weighted because the overall probability of selection of each household is not constant. The sampling weights are adjustment factors applied in each case of tabulations to adjust for the differences in probability of selection and interview between cases, due to design or happenstance. In the DHS surveys, the sample is selected with unequal probability to increase the number of available cases in certain areas or subgroups. In this scenario, weights are calculated because of sample design and corrections for different response rates, the weights are applied to the tabulations obtained from the statistics; which in turn helps proper representation of data. 

In the DHS surveys, there are four sampling weights are used: household weights, household weights for men’s sample, individual weights for women, and individual weights for men. The household weight is calculated as the inverse of its household selection probability which is multiplied by the inverse of the household response rate in the stratum. Whereas the weight for the household for men’s sample is calculated as the inverse of its household selection probability for the subsample multiplied by the inverse of the household response rate for the subsample in the stratum. In the case of individual weight for women is the household weight multiplied by the inverse of the individual response rate for women in the stratum, whereas in the case of the individual weight for men in the household weight for men’s subsample is multiplied by the inverse of the individual response rate for men in the stratum.[11]  

In addition to the four main weights, there may be additional sampling weights for sample subsets, such as anthropometry, biomarkers, HIV testing, etc. The additional sample weight will be used only if there is a differential probability in selecting the subsamples.[14]  

Normalization of weight is done by dividing each weight by the average of the initial weights; hence the sum of the normalized weights equals the sum of the cases over the entire sample. For each weight normalization is done separately. 

### 2.3 Data collection 

The data collection of the DHS program is done in paper format, which is later converted to an electronic format. The data are updated in the Census and Processing System (CSPro), which is freely available from the US Census Bureau’s website. Once the electronic data is obtained, editing and imputation are performed to deal with the incomplete data set, which helps in providing high-quality data. Once the ‘raw data’ is ready to use data tabulation is done using CSPro, as a final stage the data set is made freely available to the public.[14] 

## 3. National Family Health Survey (NFHS) 

In India, demographic and health-related data are collected and provided through the National Family Health Survey (NFHS). The NFHS is a large-scale multi-round survey conducted among a representative sample of households throughout India. Five rounds of surveys are conducted in India and the background for the sixth phase has begun. The first round of surveys was conducted in 1992-1993, and the recently conducted survey was in the year 2019-2021. The Ministry of Health and Family Welfare (MOHFW), Government of India designated the Indian Institute for Population Studies (IIPS), Mumbai as the nodal agency, which is responsible for providing coordination and technical assistance for NFHS. Survey implementation is done by a number of Field Organizations (FO) with whom IIPS is collaborating, each FOs is responsible for conducting survey activities in one or more states.[15] 

### 3.1 Sampling strategy 

The sampling strategy of NFHS is similar to DHS, where the PSUs are selected using the census data. The PSUs are selected from each district which is divided into urban and rural areas, under urban areas Census Enumeration Blocks (CEBs) are the basic and in case of the rural the villages are acting as basic unit. Once the PSUs are selected, the final samples are chosen using PPS systematic sampling. The questionnaire of NFHSS have four schedules, that are household, woman, men, and biomarker.[3] 

### 3.2 Data collected with NFHS 

The NFHS data provides information at the national and state levels, the data includes fertility, infant and child mortality, family planning practice, maternal and child health, reproductive health, nutrition, anemia, utilization and quality of health and family planning services. The main objectives of each successive phase of NFHS are to provide essential data on health and family welfare utilized for program and policy purposes and to provide information on important emerging issues in health and family welfare. Revision of the questionnaire is done in each round of NFHS to add new variables.[3] 

  

## BIBILIOGRAPHY 

1. 	Brämer GR. International statistical classification of diseases and related health problems. Tenth revision. World Health Stat Q. 1988;41(1):32–6.  

2. 	Blencowe H, Krasevec J, de Onis M, Black RE, An X, Stevens GA, et al. National, regional, and worldwide estimates of low birthweight in 2015, with trends from 2000: a systematic analysis. Lancet Glob Heal. 2019 Jul;7(7):e849–60.  

3. 	National Family Health Survey [Internet]. [cited 2024 Mar 31]. Available from: https://rchiips.org/nfhs/nfhs5.shtml 

4. 	World Health Organization. Global nutrition targets 2025: low birth weight policy brief [Internet]. [cited 2024 Apr 15]. Available from: https://www.who.int/publications/i/item/WHO-NMH-NHD-14.5 

5. 	Girotra S, Mohan N, Malik M, Roy S, Basu S. Prevalence and Determinants of Low Birth Weight in India: Findings From a Nationally Representative Cross-Sectional Survey (2019-21). Cureus. 2023 Mar 26;15(3):e36717.  

6. 	THE 17 GOALS | Sustainable Development [Internet]. [cited 2024 Mar 31]. Available from: https://sdgs.un.org/goals 

7. 	Cutland CL, Lackritz EM, Mallett-Moore T, Bardají A, Chandrasekaran R, Lahariya C, et al. Low birth weight: Case definition & guidelines for data collection, analysis, and presentation of maternal immunization safety data. Vaccine. 2017 Dec 4;35(48 Pt A):6492–500.  

8. 	Kramer MS. Determinants of low birth weight: methodological assessment and meta-analysis. Bull World Health Organ. 1987;65(5):663–737.  

9. 	Demelash H, Motbainor A, Nigatu D, Gashaw K, Melese A. Risk factors for low birth weight in Bale zone hospitals, South-East Ethiopia : a case-control study. BMC Pregnancy Childbirth. 2015 Oct 13;15(1):264.  

10. 	Villar J, Papageorghiou AT, Knight HE, Gravett MG, Iams J, Waller SA, et al. The preterm birth syndrome: a prototype phenotypic classification. Am J Obstet Gynecol. 2012 Feb;206(2):119–23.  

11. 	Croft, Trevor N., Aileen M. J. Marshall, Courtney K. Allen, et al. Guide to DHS Statistics. Rockville, Maryland, USA ICF. 2018;7(2):22–51.  

12. 	USAID. The DHS Program - Getting Started [Internet]. [cited 2024 Apr 16]. Available from: https://www.dhsprogram.com/data/Getting-Started.cfm 

13. 	The DHS Program - Data Processing [Internet]. [cited 2024 Apr 16]. Available from: https://www.dhsprogram.com/data/Data-Processing.cfm 

14. 	The DHS Program - Data Collection [Internet]. [cited 2024 Apr 16]. Available from: https://www.dhsprogram.com/data/data-collection.cfm 

15. 	International Institute for Population Sciences. National Family Health Survey [Internet]. [cited 2024 Apr 16]. Available from: https://rchiips.org/nfhs/about.shtml 

  

 

 
