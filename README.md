<!-- STATS_START -->

# Awesome Food Allergy Datasets

![Datasets](https://img.shields.io/badge/datasets-72-blue)
![Open Source](https://img.shields.io/badge/open%20source-87%25-brightgreen)
![License](https://img.shields.io/badge/license-CC0-green)
![Maintained](https://img.shields.io/badge/maintained-yes-brightgreen)

> A curated collection of datasets, databases, and computational resources for food allergy research, allergen identification, drug development, and clinical applications.

## 🎯 Mission

Food allergy affects **over 220 million people worldwide**. This repository serves as the **first comprehensive, open collection** of AI-ready datasets for food allergy research — spanning clinical trials, immunotherapy, genomics, proteomics, microbiome, and molecular data.

Our goal: Enable researchers, ML practitioners, and the scientific community to advance AI applications in:
- 🏥 **Early Detection & Risk Stratification**
- 💊 **Drug Design & Immunotherapy Development**
- 🌿 **Food Engineering & Hypoallergenic Product Development**

## 📊 Quick Stats

| Metric | Count |
|--------|-------|
| **Total Datasets** | 72 |
| **Open Source** | 63 (87%) |
| **Gated** | 9 |
| **Categories** | 6 |

### By Category
- 💊 **Drug & Immunotherapy Development**: 34 datasets
- 🏥 **Patient Management & Clinical Decision Support**: 9 datasets
- 🍽️ **Food Product Development & Safety**: 9 datasets
- 🔬 **Computational Method Development**: 7 datasets
- 🔍 **Allergen Identification & Prediction**: 7 datasets
- 🔄 **Cross-Reactivity Analysis**: 6 datasets


## 📑 Table of Contents

- [💊 Drug & Immunotherapy Development](#drug--immunotherapy-development)
- [🏥 Patient Management & Clinical Decision Support](#patient-management--clinical-decision-support)
- [🍽️ Food Product Development & Safety](#food-product-development--safety)
- [🔬 Computational Method Development](#computational-method-development)
- [🔍 Allergen Identification & Prediction](#allergen-identification--prediction)
- [🔄 Cross-Reactivity Analysis](#cross-reactivity-analysis)

---

<!-- STATS_END -->


<!-- CATEGORY_Drug & Immunotherapy Development_START -->

<a id="drug--immunotherapy-development"></a>

# 💊 Drug & Immunotherapy Development

## SDAP 2.0

SDAP is a Web server that integrates a database of allergenic proteins with various computational tools that can assist structural biology studies related to allergens. SDAP is an important tool in the investigation of the cross-reactivity between known allergens, in testing the FAO/WHO allergenicity rules for new proteins, and in predicting the IgE-binding potential of genetically modified food proteins.

**Task:** Drug Design, Structural Analysis, Epitope Mapping, Cross-Reactivity Modeling | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC10509899/)

**Source:** https://fermi.utmb.edu/

---

## QSAR Database

QsarDB is a smart repository for (Q)SAR/QSPR models and datasets, providing access to peer-reviewed quantitative structure-activity relationship models

**Task:** Property Prediction, Drug Design | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://qsardb.org/)

**Source:** https://qsardb.org/

---

## e-Drug3D Database

Three-dimensional database of drug-like compounds and their molecular conformations for structure-based drug design applications

**Task:** Drug Design, Target Interaction | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC5846051/)

**Source:** https://zenodo.org/records/17063565

---

## Stanford Drug Data (Effects & Interactions)

Comprehensive dataset of drug effects and drug-drug interactions compiled from clinical data and pharmacological studies

**Task:** Drug Design | **Data Type:** Clinical | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC3382018/)

**Source:** https://purl.stanford.edu/zq918jm7358/version/1

---

## DrugCentral

Open-access online drug information repository covering over 4950 drugs with structural, physicochemical, and pharmacological details to support drug discovery and repositioning

**Task:** Drug Design, Target Interaction | **Data Type:** Chemical | **Availability:** 🟢 Open source

**Source:** https://drugcentral.org/download

---

## MedKG

Comprehensive medical knowledge graph integrating data from 35 authoritative sources with 34 node types and 79 relationships for precision medicine and drug discovery

**Task:** Drug Design, Target Interaction, Treatment Planning | **Data Type:** Chemical | **Availability:** 🟢 Open source | **Paper:** [Link](https://link.springer.com/article/10.1007/s11030-025-11164-z)

**Source:** https://github.com/chemplusx/MedKG

---

## PDBBind+

Enhanced version of PDBBind database providing protein-ligand binding affinity data with refined experimental measurements and structural information

**Task:** Target Interaction, Drug Design | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://arxiv.org/html/2308.09639v2)

**Source:** https://www.pdbbind-plus.org.cn/download

---

## Human Metabolome Database (HMDB)

Freely available electronic database containing detailed information about 220,945 small molecule metabolites found in the human body for metabolomics and biomarker discovery

**Task:** Drug Design, Target Interaction | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC1899095/)

**Source:** https://www.hmdb.ca/downloads

---

## Therapeutic Target Database (TTD)

Database providing information about known therapeutic protein and nucleic acid targets, targeted diseases, pathway information, and corresponding drugs

**Task:** Drug Design, Treatment Planning, Target Interaction | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://academic.oup.com/nar/article/52/D1/D1465/7275004)

**Source:** https://db.idrblab.net/ttd/full-data-download

---

## QCML Dataset

Quantum chemistry reference dataset with 33.5 m. DFT calculations and 14.7 billion semi empirical entries. It covers small molecules (up to 8 heavy atoms) and provide a wide variety of computed molecular properties

**Task:** Drug Design, Target Interaction | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.nature.com/articles/s41597-025-04720-7)

**Source:** https://zenodo.org/records/14859804

---

## M3-20M: Multi-Modal Molecular Dataset

M3-20M is an extensive multi-modal molecular dataset containing over 20 million molecules with 1D, 2D, and 3D molecular representations, physicochemical properties, and text descriptions. It supports AI-driven drug discovery, molecular property prediction, lead optimization, and drug-target interaction modeling across various applications, including allergy-related therapeutic design.

**Task:** Target Interaction, Property Prediction, Drug Design | **Data Type:** Chemical | **Availability:** 🟢 Open source | **Paper:** [Link](https://arxiv.org/html/2412.06847v2)

**Source:** https://huggingface.co/datasets/Alex99Gsy/M-3_Multi-Modal-Molecule | **Contact:** gsy9901224@tongji.edu.cn

---

## SAIR Dataset

The SAIR dataset is a massive repository containing over one million protein-ligand 3D cofolded structures paired with experimental binding affinity measurements (e.g., IC50). It supports AI-driven drug discovery by enabling prediction of molecular binding potency and facilitating the design and optimization of new therapeutic compounds targeting allergenic proteins and other disease-related targets.

**Task:** Target Interaction, Structural Analysis, Property Prediction, Drug Design | **Data Type:** Molecular | **Availability:** 🟡 Gated | **Paper:** [Link](https://go.sandboxaq.com/rs/175-UKR-711/images/sair_paper.pdf)

**Source:** https://huggingface.co/datasets/SandboxAQ/SAIR | **Contact:** SAIR@sandboxaq.com

---

## TDC

Curated collection of AI (ready) datasets and tasks in the therapeutic pipeline, with consistent splits and evals

**Task:** Drug Design, Target Interaction | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://tdcommons.ai/

---

## RxRx3

Cell imaging phenomics dataset, that provides a map for biology for ML methods, including knockouts small molecule perturbations and embeddings

**Task:** Drug Design, Target Interaction | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://arxiv.org/abs/2503.20158)

**Source:** https://www.recursion.com/news/accelerating-ai-drug-discovery-with-open-source-datasets

---

## Dorothea

Gene regulatory network of signed TF-> target interactions (human/mouse) with confidence levels

**Task:** Drug Design, Target Interaction | **Data Type:** Omics | **Availability:** 🟢 Open source

**Source:** https://archive.ics.uci.edu/ml/datasets/dorothea

---

## Simulated Allergen Immunotherapy Trials Dataset

Simulated datasets implementing an enchanced three stage trial design for allergen immunotherapy (AIT). It captures realistic features like corssover, discontinuation and staged enrollment

**Task:** Drug Design, Target Interaction | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://figshare.com/articles/dataset/Simulated_datasets_for_enhanced_three-stage_design_for_allergen_immunotherapy_trials/23638965

---

## IUPHAR Pharmacology Datasets

Pharmacology data curated from experts that links drug/ligand information to molecular targets

**Task:** Drug Design, Target Interaction | **Data Type:** Chemical | **Availability:** 🟢 Open source

**Source:** https://www.guidetopharmacology.org/download.jsp

---

## Enamine REAL Database

Massive virtual libary of synthesizable compunds and enumerated subsets for large scale virtual screening and hit expansion

**Task:** Drug Design, Target Interaction | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://gist.github.com/matteoferla/b1eee8656079d006835f2d8dc159fbb5

---

## Quantum Chemistry Database with Ground- and Excited-State (QCDGE) Dataset

more than 400k small organic molecules (<=10 heavy atoms) for which both ground state and excited state quantum chemical properties have already been computed

**Task:** Drug Design, Target Interaction | **Data Type:** Chemical | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.nature.com/articles/s41597-024-03788-x)

**Source:** https://springernature.figshare.com/collections/QCDGE_database_Quantum_Chemistry_Database_with_Ground-_and_Excited-State_Properties/7259125/1

---

## Probes & Drugs Datasets

The Probes & Drugs (P&D) portal is a comprehensive resource integrating high-quality bioactive compound sets for analysis and comparison, focusing on chemical probes and drugs. It includes compound data from multiple sources, provides expert scoring based on potency and selectivity, and offers standardized compound forms to unify data. The portal supports research by tagging probes, scoring probe-likeness, and highlighting structural alerts for compound reliability

**Task:** Target Interaction | **Data Type:** Chemical | **Availability:** 🟢 Open source

**Source:** https://www.probes-drugs.org/download

---

## AllerBase

Comprehensive allergen knowledgebase integrating data from multiple sources with extensive experimental validation and IgE epitope data

**Task:** Cross-Reactivity Modeling, Allergenicity Assessment, Drug Design | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://academic.oup.com/database/article/doi/10.1093/database/bax066/4157991)

**Source:** http://algpred.tu-bs.de/allerbase/

---

## Simulated AIT Trials Dataset

Simulated datasets with enhanced three-stage trial design for allergen immunotherapy capturing realistic features like crossover and discontinuation

**Task:** Treatment Planning, Drug Design | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://figshare.com/articles/dataset/Simulated_datasets_for_enhanced_three-stage_design_for_allergen_immunotherapy_trials/23638965

---

## Food Anaphylaxis ML Dataset (TIP)

Dataset from Tolerance Induction Program with 530 juvenile patients featuring 241 allergy assays per patient achieving 95.2% recall for peanut anaphylaxis prediction

**Task:** Drug Design, Treatment Planning | **Data Type:** Clinical | **Availability:** 🟡 Gated | **Paper:** [Link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0283141)

**Source:** Contact authors

---

## Food Allergy Risk Stratification Dataset

EMR-based dataset with 4077 children with food allergies and 95686 controls for predicting FA development with AUC 0.80

**Task:** Treatment Planning | **Data Type:** Food | **Availability:** 🟡 Gated | **Paper:** [Link](https://onlinelibrary.wiley.com/doi/10.1111/all.15839)

**Source:** Contact authors

---

## Enamine REAL Database

Massive virtual library of synthesizable compounds and enumerated subsets for large-scale virtual screening and hit expansion

**Task:** Drug Design, Target Interaction | **Data Type:** Chemical | **Availability:** 🟢 Open source

**Source:** https://gist.github.com/matteoferla/b1eee8656079d006835f2d8dc159fbb5

---

## AllerCatPro 2.0

Tool predicting allergenicity using amino acid sequence and 3D structure similarity with database of 4979 allergens 162 mild allergenic proteins and 165 autoimmune allergens

**Task:** Allergenicity Assessment, Drug Design | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/35157755/)

**Source:** https://allercatpro.bii.a-star.edu.sg/

---

## AllerTOP v1.1

First alignment-free server for in silico prediction of allergens based on physicochemical properties of proteins, achieving 94% sensitivity in allergen prediction

**Task:** Structural Analysis, Drug Design, Allergenicity Assessment, Allergen Identification | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/1471-2105-14-S6-S4)

**Source:** https://ddg-pharmfac.net/allertop/cite/

---

## FARE Food Allergy Research

The Data Coordinating Center will support critical FARE Clinical Network activities for the design, development, execution, monitoring, and analysis of translational research.

**Task:** Risk Stratification, Severity Assessment, Symptom Analysis, Treatment Planning | **Data Type:** Clinical | **Availability:** 🟡 Gated

**Source:** https://research.foodallergy.org/#_ga=2.222605656.279038653.1759159933-230927819.1759159933 | **Contact:** Email to FAREDCC@westat.com

---

## Allergy dataset

Dataset supporting the conclusions for article: "The epidemiologic characteristics of healthcare provider-diagnosed eczema, asthma, allergic rhinitis, and food allergy in children: a retrospective cohort study" by Hill et al.

**Task:** Risk Stratification, Ingredient Analysis, Treatment Planning, Product Development, Genetic Analysis | **Data Type:** Food | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/27542726/)

**Source:** https://zenodo.org/records/44529

---

## Allergome

A comprehensive, curated platform documenting allergenic molecules and their sources across all taxa and exposure routes, with monographs, literature integration, and tools tailored for clinicians and researchers in allergy and immunology.

**Task:** Allergenicity Assessment, Drug Design, Allergen Identification | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.jacionline.org/article/S0091-6749(04)03615-2/fulltext)

**Source:** https://www.allergome.org/

---

## GWAS Database

The NHGRI-EBI GWAS Catalog is a curated, standardized repository of human genome-wide association study results, offering hundreds of thousands of variant–trait associations and tens of thousands of full summary-statistics datasets suitable for downstream analyses like meta-analysis and fine-mapping. Because it indexes GWAS signals across many immune and barrier-function traits and includes loci implicated in food allergy (e.g., HLA, FLG, SERPINB cluster), it is directly usable to query, aggregate, and reanalyze genetic associations relevant to food allergies and specific allergens such as peanut

**Task:** Ingredient Analysis, Product Development | **Data Type:** Food | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC2639349/)

**Source:** https://www.ebi.ac.uk/gwas/

---

## COMPARE

The COMPARE database provides an annually updated, peer-reviewed collection of clinically relevant protein sequences of allergens, along with tools for aligning and assessing the allergenic potential of novel proteins based on established regulatory guidelines

**Task:** Allergen Identification, Cross-Reactivity Modeling, Allergenicity Assessment, Epitope Mapping, Risk Stratification, Ingredient Analysis, Target Interaction, Severity Assessment | **Data Type:** Molecular | **Availability:** 🟢 Open source

**Source:** https://comparefasta.comparedatabase.org/

---

## Open Food Facts

The Open Food Facts database is a large, publicly accessible collection of detailed product information including ingredients, nutrition, and labeling, available in multiple data formats with open licenses for broad reuse in food transparency and research.This dataset mainly supports food-related analyses including allergen detection, labeling validation, chemical and nutritional content analysis, and research into hypoallergenic or alternative food products

**Task:** Ingredient Analysis, Labeling Compliance, Property Prediction, Treatment Planning, Product Development, Alternative Ingredients | **Data Type:** Chemical | **Availability:** 🟢 Open source

**Source:** https://world.openfoodfacts.org/data

---

## IEDB (Immune Epitope Database)

Comprehensive database containing over 1.6 million immune epitopes including antibody and T cell epitopes for allergens, with analysis and prediction tools

**Task:** Epitope Mapping, Target Interaction, Drug Design, Product Development | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC3042621)

**Source:** https://www.iedb.org/

---

<!-- TSV_END -->
<!-- CATEGORY_Drug & Immunotherapy Development_END -->


<!-- CATEGORY_Patient Management & Clinical Decision Support_START -->

<a id="patient-management--clinical-decision-support"></a>

# 🏥 Patient Management & Clinical Decision Support

## Food Allergy & Intolerance Dataset

This dataset contains data related to food allergies and intolerances. It includes key features such as age, gender, symptoms, food type consumed, IgE levels, and allergy history, helping in predictive modeling for food allergy detection and reaction severity assessment.

**Task:** Severity Assessment, Risk Stratification | **Data Type:** Food | **Availability:** 🟢 Open source

**Source:** https://datahub.io/@RuthvikUppala30/US-food-allergy-dataset

---

## DIABIMMUNE

The DIABIMMUNE three-country cohort dataset tracks infants from Finland, Estonia, and Russia with similar HLA genetic risk for type 1 diabetes, collecting comprehensive longitudinal data including monthly stool microbiome sequencing (16S rRNA and whole-genome shotgun), clinical records, and lifestyle factors. It investigates the role of gut microbiome variations and early immune education in allergy and autoimmune disease development, providing valuable data to explore microbial and genetic influences on immune-related conditions

**Task:** Microbiome Analysis, Genetic Analysis | **Data Type:** Clinical | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC6361419/)

**Source:** https://diabimmune.broadinstitute.org/diabimmune/three-country-cohort

---

## CFSAN Adverse Event Reporting System (CAERS)

The CFSAN Adverse Event Reporting System (CAERS) dataset contains approximately 90,000 reports of adverse events related to foods, dietary supplements, and cosmetics submitted to the FDA from 2004 to 2017. It includes detailed data on food products suspected in adverse reactions and associated symptoms, supporting analysis of patient risk factors, symptoms classification, and identification of allergenic ingredients in food products

**Task:** Risk Stratification, Symptom Analysis, Ingredient Analysis | **Data Type:** Clinical | **Availability:** 🟢 Open source

**Source:** https://www.kaggle.com/datasets/fda/adverse-food-events

---

## DNA Methilation GSE59999

Genome wide DNA methylation profiling study of PBMC from 71 unique primary patient blood samples. The Illumina Human Methylation 450k array was used. 29 challenge proven food allergy, 29 sensitized but oral tolerant, 13 non food allergics Mixture of food allergy phenotypes (egg allergic (15), peanut allergic (14)), food sensitization phenotypes (egg sensitized (14), peanut sensitized (15)). 4 samples had technical replicate hybridzations. From "Blood DNA methylation biomarkers predict clinical reactivity in food-sensitized infants"

**Task:** Risk Stratification | **Data Type:** Clinical | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/25678091/)

**Source:** https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE59999

---

## HealthNuts Study

Mass citometry data from 36 participants encompassing non-allergic, peanut sensitized with tolerance, and clinically peanut allergic infants

**Task:** Risk Stratification | **Data Type:** Clinical | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.nature.com/articles/s41597-022-01861-x#Sec6)

**Source:** https://www.immport.org/shared/search?text=SDY2015

---

## Dysfunctional Gut Microbiome Networks in Childhood IgE-Mediated Food Allergy

To identify potential target microbes, which may play a key role in regulating/ influencing the microbe-microbe interactions, leading to the onset of food allergy. 16S rRNA, 33 allergic vs 27 controls

**Task:** Risk Stratification | **Data Type:** Food | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC7923212/#notes5)

**Source:** https://www.ncbi.nlm.nih.gov/bioproject/?term=PRJNA699997

---

## PEAR – Partners’ Enterprise-wide Allergy Repository (Food entries subset)

Allergy entries from EHRs across a health system, with food terms extracted and normalized (approx. 158,552 food allergen records).

**Task:** Risk Stratification | **Data Type:** Food | **Availability:** 🟡 Gated | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC4954633/)

**Contact:** Partners Healthcare / investigator team

---

## FSA Allergen Database Service (UK Nut allergy Registry)

Clinical and laboratory data from patients attending a UK allergy clinic for suspected nut allergy, including reaction history, severity, and lab tests.

**Task:** Risk Stratification | **Data Type:** Clinical | **Availability:** 🟡 Gated

**Source:** https://www.nal.usda.gov/research-tools/food-safety-research-projects/allergen-database-service | **Contact:** FSA / database administrators

---

## Swiss legislation on food allergens data

This dataset is a German-language, hand-curated list of common food allergens based on Swiss legislation, compiled to support allergen identification and text matching for developers and researchers, with a focus on enabling structured, multilingual allergen data relevant to Switzerland

**Task:** Allergen Identification, Ingredient Analysis, Labeling Compliance, Text Mining, Risk Stratification | **Data Type:** Molecular | **Availability:** 🟢 Open source

**Source:** https://github.com/foodopendata/food-allergens-ch

---

<!-- TSV_END -->
<!-- CATEGORY_Patient Management & Clinical Decision Support_END -->


<!-- CATEGORY_Food Product Development & Safety_START -->

<a id="food-product-development--safety"></a>

# 🍽️ Food Product Development & Safety

## Allergen30

More than 6,000 images of 30 commonly used food items which can cause an adverse reaction within a human body. The goal is building a robust detection model that can assist people in avoiding possible allergic reactions.

**Task:** Ingredient Analysis | **Data Type:** Food | **Availability:** 🟢 Open source | **Paper:** [Link](https://link.springer.com/article/10.1007/s12161-022-02353-9)

**Source:** https://universe.roboflow.com/allergen30/food_new-uuulf

---

## Food: allergen and allergy

A comprehensive list of food items with their corresponding allergies.

**Task:** Ingredient Analysis | **Data Type:** Food | **Availability:** 🟢 Open source

**Source:** https://www.kaggle.com/datasets/boltcutters/food-allergens-and-allergies

---

## Food Ingredients and Allergens

The Food Allergens Dataset is a collection of information regarding allergens present in various food items. The dataset contains allergen information for a range of food ingredients, enabling the identification and analysis of potential allergens in different dishes and products. It serves as a valuable resource for researchers, food manufacturers, healthcare professionals, and individuals with food allergies.

**Task:** Ingredient Analysis | **Data Type:** Food | **Availability:** 🟢 Open source

**Source:** https://www.kaggle.com/datasets/uom190346a/food-ingredients-and-allergens/

---

## AllergyMap

A corpus that maps free-text allergy mentions (medications, foods, etc.) in EHRs to standard terminologies (SNOMED, etc.)

**Task:** Text Mining | **Data Type:** Food | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC8075505/)

**Source:** https://github.com/amywangmd/AllergyMap

---

## Allergen Status of Food Products

This dataset contains allergen status information for 400 food products, detailing ingredients, allergens present, pricing, and customer ratings, enabling allergen detection and analysis for researchers, manufacturers, and consumers

**Task:** Allergen Identification, Ingredient Analysis, Labeling Compliance, Allergenicity Assessment | **Data Type:** Food | **Availability:** 🟢 Open source

**Source:** https://www.kaggle.com/datasets/nandhanasuresh/allergen-status-of-food-products

---

## Ingredients with 16 Allergen Tags

This dataset lists 10,000 USDA ingredients, each tagged with 16 common allergen labels such as dairy, eggs, peanuts, gluten, and shellfish, with annotations indicating certainty or uncertainty of allergen presence.

**Task:** Allergen Identification, Ingredient Analysis, Allergenicity Assessment | **Data Type:** Food | **Availability:** 🟢 Open source

**Source:** https://www.kaggle.com/datasets/khochawongwat/ingredients-with-17-allergen-tags

---

## Food Ingredients and Allergens

This Food Allergens dataset contains 400 records detailing food products, their ingredients, associated allergens, and allergen presence prediction, supporting allergen detection and analysis for diverse applications.

**Task:** Allergen Identification, Ingredient Analysis, Allergenicity Assessment, Text Mining | **Data Type:** Food | **Availability:** 🟢 Open source

**Source:** https://www.kaggle.com/datasets/uom190346a/food-ingredients-and-allergens

---

## ProPepper

ProPepper is a database of cereal prolamin epitopes, peptides and proteins for expert users that are dealing with protein chemistry, proteomics and mass spectrometry, method developments and related applications in food science, agricultural breeding or medical studies.

**Task:** Ingredient Analysis, Product Development | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/26450949/)

**Source:** https://ngdc.cncb.ac.cn/databasecommons/database/id/1686

---

## Allergen Peptide Browser

Allergen Detection using Mass Spectrometry (MS)

**Task:** Ingredient Analysis, Product Development | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://www.allergenpeptidebrowser.org/

---

<!-- TSV_END -->
<!-- CATEGORY_Food Product Development & Safety_END -->


<!-- CATEGORY_Computational Method Development_START -->

<a id="computational-method-development"></a>

# 🔬 Computational Method Development

## DAVIS (DrugTarget)

Drug-target affinity dataset containing Kd values for 68 drugs and 379 protein targets, widely used for benchmarking drug-target interaction prediction models

**Task:** Drug Design, Target Interaction | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/24723570/)

**Source:** https://staff.cs.utu.fi/~aatapa/data/DrugTarget/

---

## nabla²DFT

nabla²DFT is a large-scale dataset and benchmark in computational quantum chemistry that is designed to support machine learning models for predicting molecular electronic structure properties. Per molecule, it contains quantum-level properties like total electronic energy, DFT Hamilton matrices, forces, overlap matrices, etcetera. In addition to the data, it also contains benchmark tasks. Can be used to train neural network potentials.

**Task:** Structural Analysis, Drug Design | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubs.rsc.org/en/content/articlelanding/2022/CP/D2CP03966D)

**Source:** https://github.com/AIRI-Institute/nablaDFT/tree/1.0

---

## QM Datasets

Benchmarks quantum chemistry datasets of small organic molecules (<=9 heavy atoms) where molecular properties have been computed via quantum chemistry. WIDELY USED for molecular property prediction

**Task:** Property Prediction, Text Mining | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://quantum-machine.org/datasets/

---

## QDπ Dataset

The QDπ dataset enables creation of flexible target loss functions for neural network training relevant to drug discovery, including information-dense data sets of relative conformational energies and barriers, intermolecular interactions, tautomers and relative protonation energies of drug-like compounds and biomolecular fragments. Useful for training universal machine learning potentials (MLPs).

**Task:** Property Prediction, Text Mining | **Data Type:** Chemical | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.nature.com/articles/s41597-025-04972-3)

**Source:** https://zenodo.org/records/14970869

---

## AlgPred 2.0 Dataset

Large-scale dataset with 10075 allergens and 10075 non-allergens plus 10451 validated IgE epitopes for machine learning

**Task:** Allergenicity Assessment, Cross-Reactivity Modeling, Drug Design | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/33201237/)

**Source:** https://webs.iiitd.edu.in/raghava/algpred2/

---

## Allergen Chip data challenge

The goal of the competition was to develop Machine Learning models that can predict the presence and severity of an allergic disease based on this personalized profile. The dataset has been constructed from data of more than 4,000 patients includes tabular data associated with image files.

**Task:** Risk Stratification, Severity Assessment | **Data Type:** Clinical | **Availability:** 🟡 Gated

**Source:** https://github.com/Trustii-team/AllergenChip | **Contact:** contact@trustii.io

---

## TIP Dataset

Tolerance Induction Program dataset containing data from 530 pedriatic patients. From "Food anaphylaxis diagnostic marker compilation in machine learning design and validation"

**Task:** Risk Stratification, Severity Assessment | **Data Type:** Clinical | **Availability:** 🟢 Open source | **Paper:** [Link](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0283141)

**Source:** https://github.com/TPIRC/ai_paper_2022

---

<!-- TSV_END -->
<!-- CATEGORY_Computational Method Development_END -->


<!-- CATEGORY_Allergen Identification & Prediction_START -->

<a id="allergen-identification--prediction"></a>

# 🔍 Allergen Identification & Prediction

## STITCH

A database that itegrates known and predicted interactions between chemicals and proteins, combining evidence from experiments, databases, text mining and prediction algorithms

**Task:** Allergen Identification, Allergenicity Assessment | **Data Type:** Molecular | **Availability:** 🟢 Open source

**Source:** http://stitch.embl.de/cgi/download.pl?UserId=o7OnPFVV3JJ4&sessionId=e44tciEEXzEc

---

## Allermatch

Webtool for standardized allergenicity prediction according to FAO/WHO Codex alimentarius guidelines using sliding window approach

**Task:** Allergenicity Assessment | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC522748/)

**Source:** http://allermatch.org

---

## AllerHunter

Computational tool for allergen prediction with internal and external validation achieving MCC 0.738 on external dataset

**Task:** Allergenicity Assessment | **Data Type:** Mixed | **Availability:** 🟡 Gated

**Source:** Contact authors

---

## NetAllergen

A curated database of IgE-inducing allergens based on AllergenOnline, carefully removed allergen redundancy with a novel protein partitioning pipeline, and developed a new allergen prediction method, introducing MHC presentation propensity as a novel feature.

**Task:** Allergen Identification, Allergenicity Assessment | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://academic.oup.com/bioinformaticsadvances/article/3/1/vbad151/7319372?login=false)

**Source:** https://services.healthtech.dtu.dk/services/NetAllergen-1.0/

---

## Akkermansia muciniphila exacerbates food allergy in fibre-deprived mice

Study on alteration of mice gut microbioma, focusing on Akkermansia muciniphila.

**Task:** Allergen Identification, Allergenicity Assessment | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://www.nature.com/articles/s41564-023-01464-1)

**Source:** https://www.ebi.ac.uk/ena/browser/view/PRJEB53451

---

## CHILD cohort

Multi-omics; microbiome maturation predicts allergic disease

**Task:** Allergen Identification, Allergenicity Assessment | **Data Type:** Omics | **Availability:** 🟡 Gated | **Paper:** [Link](https://www.nature.com/articles/s41467-023-40336-4#data-availability)

**Contact:** Contact Stuart E. Turvey (sturvey@bcchr.ca)

---

## WHO/IUIS Allergen Nomenclature Database

The WHO/IUIS Allergen Nomenclature is the authoritative system for naming allergenic proteins, approved by the World Health Organization and International Union of Immunological Societies. Established in 1984, this sub-committee maintains a unique, systematic nomenclature based on the Linnaean taxonomy for proteins causing IgE-mediated allergic reactions, supporting global consistency in allergen research and publication

**Task:** Text Mining | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/29625844/)

**Source:** https://allergen.org/

---

<!-- TSV_END -->
<!-- CATEGORY_Allergen Identification & Prediction_END -->


<!-- CATEGORY_Cross-Reactivity Analysis_START -->

<a id="cross-reactivity-analysis"></a>

# 🔄 Cross-Reactivity Analysis

## Allergen30

Dataset containing structural and sequence information for 30 major allergen families to support allergenicity prediction and cross-reactivity analysis

**Task:** Allergenicity Assessment, Allergen Identification, Structural Analysis | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://link.springer.com/article/10.1007/s12161-022-02353-9)

**Source:** https://data.mendeley.com/datasets/9ygs9vhnpw/1

---

## AllFam

Database classifying allergens into 134 protein families based on WHO/IUIS and AllergenOnline data with Pfam definitions

**Task:** Structural Analysis, Cross-Reactivity Modeling | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pubmed.ncbi.nlm.nih.gov/18395549/)

**Source:** https://www.meduniwien.ac.at/allfam/

---

## IEDB Analysis Resource

Companion to IEDB providing computational tools for B and T cell epitope prediction including MHC binding predictions

**Task:** Epitope Mapping | **Data Type:** Mixed | **Availability:** 🟢 Open source | **Paper:** [Link](https://academic.oup.com/nar/article/47/W1/W502/5494780)

**Source:** http://tools.iedb.org/

---

## AllergenAI

Allergenicity prediction based on protein sequences. Processed data from SDAP 2.0, COMPARE, and AlgPred 2

**Task:** Allergen Identification, Allergenicity Assessment | **Data Type:** Molecular | **Availability:** 🟢 Open source | **Paper:** [Link](https://pmc.ncbi.nlm.nih.gov/articles/PMC11230160/)

**Source:** https://compbio.uth.edu/AllergenAI/

---

## Allergen Family Database

A curated database that classifies known allergens into protein families to support analysis of allergenicity and cross-reactivity across sources and exposure routes. It integrates entries from WHO/IUIS Allergen Nomenclature and AllergenOnline with Pfam domain annotations, providing family-level pages with biochemical descriptions, allergological significance, and links to primary records and references.

**Task:** Allergen Identification, Allergenicity Assessment, Drug Design, Target Interaction, Structural Analysis | **Data Type:** Molecular | **Availability:** 🟢 Open source

**Source:** https://www.meduniwien.ac.at/allfam/

---

## Alleropedia Database for Allergens

The Alleropedia database is a comprehensive metadatabase consolidating 13,146 allergen records from six freely accessible sources, including major allergen databases like COMPARE, AllergenOnline, WHO/IUIS, and Allergome. It offers a user-friendly web interface and additional features such as data integration with sources like NCBI, facilitating easy access, analysis, and navigation of allergen-related information for researchers and clinician

**Task:** Allergen Identification, Allergenicity Assessment, Cross-Reactivity Modeling, Epitope Mapping, Structural Analysis | **Data Type:** Mixed | **Availability:** 🟢 Open source

**Source:** https://github.com/maitreyeepaliwal/Alleropedia-Database-for-Allergens

---

<!-- TSV_END -->
<!-- CATEGORY_Cross-Reactivity Analysis_END -->


---

## 🤝 Contributing

We welcome contributions! Please see [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on:
- Adding new datasets
- Updating existing entries
- Reporting issues

## 📜 License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, all contributors have waived all copyright and related rights to this work.

## 🙏 Acknowledgments

Thanks to all our contributors and the research community for making these datasets available!

Built with ❤️ for the food allergy research community.

---

**Maintained by:** [AI for Food Allergies](https://github.com/ludocomito/ai-for-allergies)
