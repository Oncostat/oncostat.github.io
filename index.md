
<img src="https://www.gustaveroussy.fr/sites/all/themes/gustave_roussy/logo.png" alt="logo GR">
<img src="https://upload.wikimedia.org/wikipedia/commons/c/cd/Inserm.svg" alt="logo INSERM" width="200px">
<img src="https://www.ligue-cancer.net/sites/all/themes/ligue/logo.png" alt="logo LCC">
<img src="https://hal.archives-ouvertes.fr/UNIV-PARIS-SACLAY/public/logo_UP_saclay_final.png" alt="logo UPSC" width="150px">
Oncostat is a research team of the Centre for Epidemiology and Population Health (CESP). More information on <https://cesp.inserm.fr/en/equipe/oncostat>.

## Teaching

-   Book: Textbook of Clinical Trials in Oncology: A Statistical Perspective, 2019, CRC Press, edited by Susan Halabi & Stefan Michiels [[link](https://www.routledge.com/Textbook-of-Clinical-Trials-in-Oncology-A-Statistical-Perspective/Halabi-Michiels/p/book/9781138083776) and [supplemental material](https://www.routledge.com/downloads/K34556/stat%20code%20book%20halabi%20michiels.zip)]
-   [R Notebooks](https://github.com/Oncostat/R_notebooks)
-   INSERM workshop 2017: predictionPenalized [[link](https://github.com/Oncostat/predictionPenalized)]

## Software

### R packages

-   Biomarker selection in penalized regression models, package `biospear` [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/biospear)](https://cran.r-project.org/package=biospear) [[code](https://github.com/Oncostat/biospear)]

    *Described in*: Nils Ternès, Federico Rotolo, Stefan Michiels, biospear: an R package for biomarker selection in penalized Cox regression, Bioinformatics, Volume 34, Issue 1, 01 January 2018, Pages 112--113. [[DOI](https://doi.org/10.1093/bioinformatics/btx560)].

-   Evaluation of Failure Time Surrogate Endpoints in Individual Patient Data Meta-Analyses, package `surrosurv` [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/surrosurv)](https://cran.r-project.org/package=surrosurv) [[code](https://github.com/Oncostat/surrosurv)]

    *Described in*: Federico Rotolo, Xavier Paoletti, Stefan Michiels, surrosurv: an R package for the evaluation of failure time surrogate endpoints in individual patient data meta-analyses of randomized clinical trials. Comput Methods Programs Biomed. 2018 Mar;155:189-198. [[DOI](https://doi.org/10.1016/j.cmpb.2017.12.005)].

-   Parametric Frailty Models, package `parfm` [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/parfm)](https://cran.r-project.org/package=parfm) [[code](https://github.com/Oncostat/parfm)]

-   Import tool to work with TrialMaster, package `EDCImport` [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/EDCimport)](https://cran.r-project.org/package=EDCimport) [[code](https://github.com/Oncostat/EDCImport)]

-   Description tool to build tables and reports, package `crosstable` [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/crosstable)](https://cran.r-project.org/package=crosstable) [[code](https://github.com/Oncostat/crosstable)]

-   R interface for NIH's joinpoint regression software ([link](https://surveillance.cancer.gov/joinpoint/callable/)) to build tables and reports, package `nih.joinpoint` [![CRAN_Status_Badge](https://www.r-pkg.org/badges/version/nih.joinpoint)](https://cran.r-project.org/package=crosstable) [[code](https://github.com/Oncostat/nih.joinpoint)]

### R code

-  Favouring the hierarchy constraint when penalising (many) biomarker by treatment interactions in a Cox regression model [[code](https://github.com/ShaimaBelhechmi/Adaptive-lasso-for-favoring-the-hierarchical-constraint-/tree/main)].

    *Described in*: Belhechmi S, Le Teuff G, De Bin R, Rotolo F, Michiels S. Favoring the hierarchical constraint in penalized survival models for randomized trials in precision medicine. BMC Bioinformatics. 2023 Mar 16;24(1):96. doi: .  [[DOI](https://doi.org/10.1186/s12859-023-05162-x)]

-   Survival infinite sparse graphical independent component analysis (Variational Inference) [[code](https://github.com/Oncostat/SisgICA)].

    *Described in*: Rincourt SL, Michiels S, Drubay D. A non-parametric Bayesian joint model for latent individual molecular profils and survival in oncology. Journal of Bioinformatics and Computational Biology. 2022 Aug 24; doi: 10.1142/S0219720022500226. [[DOI](https://doi.org/10.1142/S0219720022500226)]

-   Frequest individual patient data network meta-analysis for time-to-event data using penalized Poisson regression [[code](https://github.com/EdOllier/PenalizedPoissonNMA)].

    *Described in*: Ollier E, Blanchard P, Le Teuff G, Michiels S. Penalized Poisson model for network meta-analysis of individual patient time-to-event data. Stat Med. 2021 Oct 28. doi: 10.1002/sim.9240. [[DOI](https://doi.org/10.1002/sim.9240)].

-   SImulation study comparing individual patient vs. agregate 3-node time-to-event network meta-analysis with an effect modifier, using a unpenaliszed Poisson regression model. [[code](https://github.com/Oncostat/One_step_frequentitst_IPD_NMA)].

    *Described in*: Faron M, Blanchard P, Ribassin-Majed L, Pignon JP, Michiels S, Le Teuff G. A frequentist one-step model for a simple network meta-analysis of time-to-event data in presence of an effect modifier. PLoS One. 2021 Nov 1;16(11):e0259121. [[DOI](https://doi.org/10.1371/journal.pone.0259121)].

-   Drop the losers with historical control group with time-to-event outcomes [[code](https://github.com/Oncostat/DTLHC)]

    *Described in*: Abbas R, Wason J, Michiels S, Le Teuff G. A two-stage drop-the-losers design for time-to-event outcome using a historical control arm. Pharm Stat. 2021 Sep 8. doi: 10.1002/pst.2168. [[DOI](https://doi.org/10.1002/pst.2168)].

-   Neural network implementations for time-to-event outcomes, including the use of pseudo-observations [[code](https://github.com/eroblin/NN_Pseudobs)]

    *Described in*: Elvire Roblin, PH Paul-Henri Cournede, Stefan Michiels (2020) On the Use of Neural Networks with Censored Time-to-Event Data In: Mathematical and Computational Oncology. ISMCO 2020. Lecture Notes in Computer Science, vol 12508. [[DOI](https://doi.org/10.1007/978-3-030-64511-3_6)].

-   Group Sequential Adaptive Designs in Series of Time-To-Event Randomised Trials in Rare Diseases: A Simulation Study [[code](https://github.com/Oncostat/Group-sequential-adaptive-designs-in-series-of-time-to-event-randomized-trials-in-rare-diseases)]

    *Described in*: Bayar MA, Le Teuff G, Koenig F, Le Deley MC, Michiels S. Stat Methods Med Res. 2020 Jun;29(6):1483-1498. [[DOI](https://doi.org/10.1177/0962280219862313)].

-   Mixed Effect Multivariate Continuation Ratio model [[code](https://github.com/Oncostat/POP1)]

    *Described in*: Drubay D, Collette L, Paoletti X. Proportional odds assumption for modeling longitudinal ordinal multiple toxicity outcomes in dose finding studies of targeted agents: A pooled analysis of 54 studies. Contemp Clin Trials Commun. 2020 Jan 25;17:100529. [[DOI](https://doi.org/10.1016/j.conctc.2020.100529)].

-   Estimation of the probability of patients having a time to progression ratio superior to a given threshold [[code](https://github.com/Oncostat/TTPratio)]

    *Described in*: Texier M, Rotolo F, Ducreux M, Bouché O, Pignon JP, Michiels S. Evaluation of Treatment Effect with Paired Failure Times in a Single-Arm Phase II Trial in Oncology. Comput Math Methods Med. 2018 Jan 11;2018:1672176. [[DOI](https://doi.org/10.1155/2018/1672176)].

-   Competing risk model for meta-analysis of survival data [[code](https://github.com/AMeddis/Meta-analysis-for-competing-risk)] (collaboration with Inserm U900)

    *Described in*: Meddis A, Latouche A, Zhou B, Michiels S, Fine J. Meta-analysis of clinical trials with competing time-to-event endpoints. Biom J. 2020 May;62(3):712-723. [[DOI](https://doi.org/10.1002/bimj.201900103)].

### Python code

-   CustOmics: A versatile deep-learning based strategy for multi-omics integration [[code](https://github.com/Oncostat/CustOmics)]

    *Described in*: Benkirane H, Pradat Y, Michiels S, Cournède P-H (2023) CustOmics: A versatile deep-learning based strategy for multi-omics integration. PLoS Comput Biol 19(3): e1010921. [[DOI](https://doi.org/10.1371/journal.pcbi.1010921)].

-   Hyper-AdaC: Adaptive clustering-based hypergraph representation of whole slide images for survival analysis [[code](https://proceedings.mlr.press/v193/benkirane22a.html)]

    *Described in*: Benkirane, H., Vakalopoulou, M., Christodoulidis, S., Garberis, I., Michiels, S., Cournède, P. (2022) Hyper-AdaC: Adaptive clustering-based hypergraph representation of whole slide images for survival analysis. Proceedings of Machine Learning Research 193:405-418 [[link](https://proceedings.mlr.press/v193/benkirane22a.html)].

### SAS macros

-   Dual-Agent Bayesian Continual Reassessment Method [[code](https://github.com/Oncostat/CRM2dim)]

    *Described in*: Bayar MA, Ivanova A, Le Teuff G. CRM2DIM: A SAS macro for implementing the dual-agent Bayesian continual reassessment method. Comput Methods Programs Biomed. 2019 Jul;176:211-223. [[DOI](https://doi.org/10.1016/j.cmpb.2019.04.025)].

### Online prediction models

-   Prognostic model for triple-negative breast cancer patients treated with anthracycline-based chemotherapy based on clinicopathological factors and tumour infiltrating lymphocytes [[code](https://github.com/Oncostat/PrognosTILs)]

    *Described in*: Loi S, Drubay D, Adams S, Pruneri G, Francis PA, Lacroix-Triki M, Joensuu H, Dieci MV, Badve S, Demaria S, Gray R, Munzone E, Lemonnier J, Sotiriou C, Piccart MJ, Kellokumpu-Lehtinen PL, Vingiani A, Gray K, Andre F, Denkert C, Salgado R, Michiels S.Tumor-Infiltrating Lymphocytes and Prognosis: A Pooled Individual Patient Analysis of Early-Stage Triple-Negative Breast Cancers. J Clin Oncol. 2019 Mar 1;37(7):559-569. [[DOI](https://doi.org/10.1200/JCO.18.01010)].

### Others

-   BenchmarkNCVTools [[code](https://github.com/Oncostat/BenchmarkNCVTools)]

    *Described in*: Drubay D, Gautheret D, Michiels S. A benchmark study of scoring methods for non-coding mutations. Bioinformatics. 2018 May 15;34(10):1635-1641. [[DOI](https://doi.org/10.1093/bioinformatics/bty008)].

## Supplementary Material of Publication

-   Brard C, Le Teuff G, Le Deley MC, Hampson LV. Bayesian survival analysis in clinical trials: What methods are used in practice? Clinical Trials. 2017; 14(1):78-87 [Supplementary material (Excel table)](https://www.gustaveroussy.fr/sites/default/files/article_ct-16-0032-r1_supplementary_material.xlsx)

## Under development

-   


<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-4ZHTSJHT5F"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-4ZHTSJHT5F');
</script>
