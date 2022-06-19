---
title: "Immunotyping of whole blood with flow"
author: "nanaliu"
date: '2022-06-19'
slug: []
categories: Flow
tags:
- Flow
- Immunophenotype
- Whole blood
draft: yes
description: null
featured_image: null
---
# Abstract

I have whole blood samples from mouse, and want to assess the immune landscape in vivo, including the **subtype of immune cells, phenotype of immune cells, and their ability to immune stimulus, or potential to immune response**. The questions need to design staining and panels for immune cells.

The monitoring of immune cells gained great significance in prognosis and prediction of therapy response, especially for transplanation, cancer and autoimmune diseases, and peripheral whole blood is the easiest and flexible to test in the clinical. Many detailed tutorials aimed at enumeration and characterization of immunophenotyping of immune cell population in healthy and abnormal conditions for the clinical have been developed, like the [One study](https://pubmed.ncbi.nlm.nih.gov/24160259/) and [the Milieu Interieur Consortum](https://pubmed.ncbi.nlm.nih.gov/25572534/), while most research are focused on the human, it still needs clear and complete guidance of immunophenotypes for mice experiments. 

### Prepare for the whole blood for flow



### Expression level of markers identified in each immune population

Firstly we should know the expression of membrane antigens identified in different immune population of whole blood (leukocytes), [Simone et al](https://pubmed.ncbi.nlm.nih.gov/34709744/) summarised the immune landscapes and differentiated immune population based on their expression. 
![Defination of monitored immune cells](https://raw.githubusercontent.com/liunanaliu/NaLiu_blog/main/content/posts/2022-06-17-immunophenotyping-of-whole-blood-with-flow/figures/defination_monitored_immune_cells.png?token=GHSAT0AAAAAABU7LFPPOCS7ZMP6W4FUSTJYYVOZP4A)

After knowing hte expression patterns for immune cells, we could like to design panels of flow cytometry for staining, there are several approaches. 

[Kelly Menees et al](https://pubmed.ncbi.nlm.nih.gov/33419446/) and [Rachael Earls et al](https://pubmed.ncbi.nlm.nih.gov/31796095/) shared the same strategy (from the same group) for immune cells profiling. While I am confused that they considered **CD11b+ as monocytes, which is also possible for Ly6G+ neutrophils**. Actually, I often use CD11b and Ly6G double positive as biomarkers for neutrophils, I wrote an email to ask the corresponding author, but no reply. (considering to ask again)

![Gating strategy_1 for flow cytometry](https://raw.githubusercontent.com/liunanaliu/NaLiu_blog/main/content/posts/2022-06-17-immunophenotyping-of-whole-blood-with-flow/figures/gating_strategy_for_flow1.png?token=GHSAT0AAAAAABU7LFPOAZT5DEYLBE36I7VYYVOZQZA)
[Yen-Rei Yu et al](https://pubmed.ncbi.nlm.nih.gov/26938654/) performed a similar simplized method with the previous, while with difference order for lymphoid cells and myeloids, they setted myeloid first, including neutrophils and monocytes, then for lymphoid cells, including T cells and B cells.

![Gating strategy_2 for flow cytometry](https://raw.githubusercontent.com/liunanaliu/NaLiu_blog/main/content/posts/2022-06-17-immunophenotyping-of-whole-blood-with-flow/figures/gating_strategy_for_flow2.png?token=GHSAT0AAAAAABU7LFPPXKXRCV427KTCCAZSYVOZRYQ)
[Peter Carlsn et al](https://pubmed.ncbi.nlm.nih.gov/34261667/) adapted separative panels for lymphoid and myeloid, they also tested the difference on fresh, fixed and cryopreservation. 

![Staining protocol for gating](https://raw.githubusercontent.com/liunanaliu/NaLiu_blog/main/content/posts/2022-06-17-immunophenotyping-of-whole-blood-with-flow/figures/table_gating_immunophenotype.png?token=GHSAT0AAAAAABU7LFPPEJGVBSVVDJ7WXERAYVOZX4A)

Bsed on the expressed biomarkers for subpopulations of immune cells, here is the practical gating strategy for flow.
![Gating strategy_3 for flow cytometry](https://raw.githubusercontent.com/liunanaliu/NaLiu_blog/main/content/posts/2022-06-17-immunophenotyping-of-whole-blood-with-flow/figures/gating_strategy_for_flow3.jpeg?token=GHSAT0AAAAAABU7LFPOEFE7BFPFHDG2J6AIYVOZSPQ)

### Immunoassays [Reference](https://www.uclahealth.org/pathology/services-flow-cytometry)
As for immune cells secreted with cytokine, a consequence of immune cell activation is cytokine production, the amounts of responsive cells and types of released cytokines could be useful biomarkers to monitor immune response to stimulus. Flow cytometry could be used to evaluate cell degranulation and cytokine production by T cells and NK cells stimulated with antigen or chemicals.

[**Cytokine inducion assay**](https://pubmed.ncbi.nlm.nih.gov/24096457/)

**PMA plus ionomycin** (surface TNFa expression on the majority of CD3+ T cells and secretion of Th1-associated cytokines: IFN-y, IL2 and to a lesser extent, IL4) 
(PMA is a protein kinase C activator that bypass the T cell receptor and promote T cell and monocyte terminal differentiation and activation) for 3 hours  
**LPS** (the majority of CD14+ monocytes show surface TNFa expression, in parallel, high amounts of solble IL1b, IL6 and IL8 become detectable) 
(which is used to assess innate immune response to bacterial infection, via activating toll-like receptor 4 and nuclear factor-kappa B signaling pathway that leads to cytokine production and release in monocytes ) for 6 hours  
[**Simultaneous identification of activated cells and quantitative evaluation of cytokines released during activation via TNF-a inhibitor**](https://pubmed.ncbi.nlm.nih.gov/15311213/)
for TNF-a + immune cells with TACE inhibitor BB3103, which does not affect the release of cytokine other than TNFa and make it possible to assess the phenotype of TNF-a secreting cells.

[**Immune Cell Induced Cytokine Production**](https://biosci.mcdb.ucsb.edu/immunology/Methods/Concept-cytokine-production.htm)

**Monocytes/macrophages in whole blood cultures.**

•	LPS primarily stimulates IL-1β, IL-1ra, IL-6, IL-10, IL-12, and TNF-α production.

•	LPS plus PHA stimulates greater production of IL-6 and TNF-α and reduced production of IL-1β as compared to LPS alone.

**T cells in whole blood cultures**

•	PHA primarily stimulates IL-2, IL-4, IFN-γ, IL-17, and GM-CSF.

•	PHA plus LPS stimulates greater production of IFN-γ but only slightly greater production of IL-2 and GM-CSF, as compared to PHA alone.

•	LPS alone does not stimulate production of IL-2, IFN-γ or GM-CSF from whole blood cultures.
NK cells in PBL cultures.

•	Anti-CD2 (as opposed to anti-CD3; ) primarily stimulates TGF-β production.

**Lymphocyte proliferation assay (LPA)**

This test is useful for assessing T-cell function, particularly in the context of impairment of cellular immunity, immunosuppressive therapies, primary and secondary immunodeficiency.

**Natural killer cell cytotoxicity assay (NKCC)**

This test allows for the quantitative determination of NK cell cytotoxicity activity, which is useful for the assessment of patients with recurrent, severe herpes viral infections.

**Granulocyte / monocyte oxidative burst assay**

This assay determines the oxidative burst of granulocytes and monocytes in heparinized whole blood upon stimulation with PHA or opsonized E.coli by flow, which is useful for assessing granulocyte immune competency to aid in assessing a patient relative risk for infections.

See the assay with [a commercial product](https://www.abcam.com/respiratory-burst-assay-kit-neutrophilmonocyte-ab236210.html) from Abcam, [Yonggang Ma et al](https://pubmed.ncbi.nlm.nih.gov/33042165/) use it for neutrophil respiratory burst assay for flow.



### output for the flow

* Compare the percentage of subpopulation of immune subtypes. like [Maximilian Korn et al](https://pubmed.ncbi.nlm.nih.gov/32957521/) did

![Flow cytometry of leukocyte populations present in the synovial fluid of non-infected and infected patients](https://raw.githubusercontent.com/liunanaliu/NaLiu_blog/main/content/posts/2022-06-17-immunophenotyping-of-whole-blood-with-flow/figures/flow_leukocyte_population_compare_infection.jpeg?token=GHSAT0AAAAAABU7LFPOVJR27CGGPYBHW42MYVOZU7A)