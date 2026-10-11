# Computational Research in Friedreich's Ataxia

Project: Accelerating Therapeutic Discovery in Friedreich's Ataxia Through Computational Drug Repurposing

Project Overview:

Friedreich’s ataxia (FA) is a rare inherited neurodegenerative disorder commonly associated with reduced frataxin expression, mitochondrial dysfunction, and progressive neurological and cardiac complications. Limited treatment options make the search for additional therapeutic strategies an important area of research.
Inspired by meeting two brothers living with FA and witnessing their determination despite significant hardships, I investigated how computational biology could contribute to therapeutic discovery. This project explores whether gene-expression patterns associated with frataxin deficiency can help identify existing compounds for further investigation as potential therapeutic candidates.
Rather than developing a new drug from scratch, this approach uses computational analysis to investigate whether existing compounds may reverse disease-associated molecular patterns. Such findings could help prioritize candidates for future laboratory studies.

Research Question:

Can gene-expression changes associated with frataxin deficiency be used to identify existing compounds with potential for further investigation as therapeutic candidates for Friedreich’s ataxia?

Dataset

Dataset: GSE244886 
Source: NCBI Gene Expression Omnibus (GEO)
Experimental model: Isogenic sensory neuron model
Data type: Gene expression data
Purpose: Investigate molecular differences associated with frataxin deficiency and develop a disease-associated transcriptional signature for computational drug repurposing analysis.
Publicly available gene-expression datasets provide an opportunity to investigate disease associated molecular patterns without requiring the collection of new patient samples.

Methods: 

1. Data Acquisition and Preprocessing
Gene-expression data were obtained from a public research repository for computational analysis. Data preparation is intended to support comparisons between relevant experimental conditions and ensure that the samples and expression measurements are interpreted appropriately.
2. Differential Gene-Expression Analysis
Gene expression differences between the relevant experimental conditions were investigated to identify genes associated with the disease model.
The project results currently report 1,903 differentially expressed genes. The final analysis should document the statistical method, significance threshold, multiple testing correction, sample groups, and direction of expression changes used to obtain this result.
3. Transcriptional Signature Interpretation
Differentially expressed genes were considered as a potential molecular signature of frataxin deficiency. Interpreting this signature may help identify biological patterns associated with the experimental disease model and provide an input for subsequent computational drug repurposing approaches.
4. Computational Drug Repurposing
The project investigated existing compounds that could potentially reverse disease-associated gene expression patterns.
Two candidate compounds identified in the current project results were:
Salermide: A compound reported to inhibit sirtuin activity.
SB 218078: A compound reported to inhibit checkpoint kinase 1 (CHK1).
These compounds are computationally prioritized candidates for further investigation, not established treatments for FA. Their relevance to the disease, predicted effects, safety, and therapeutic potential require additional evaluation.

Results:

The current project results report 1,903 differentially expressed genes in the analyzed comparison and identify Salermide and SB 218078 as candidate compounds for further investigation.
These findings illustrate how gene-expression analysis and computational drug repurposing can be combined to generate hypotheses about potential therapeutic avenues for a rare genetic disorder.
Interpretation: Differential gene expression can help characterize molecular changes in an experimental model, while computational drug repurposing approaches may help prioritize compounds for additional study. Neither differential expression nor computational prioritization alone establishes that a compound will improve disease outcomes.

Significance:

This project explores a computational approach to an important challenge in rare disease research: identifying promising therapeutic leads when treatment options are limited.
By investigating disease-associated gene-expression patterns and exploring existing compounds, the research aims to demonstrate how computational methods can support early stage therapeutic discovery. The approach may help narrow the range of candidates for future investigation, although experimental validation is necessary before drawing conclusions about therapeutic efficacy.
Limitations
Computational findings generate hypotheses rather than establish clinical efficacy. Results depend on the dataset, experimental model, preprocessing choices, and statistical methods. Any proposed therapeutic candidates require additional validation.

Limitations:

Experimental model: Findings from an isogenic sensory neuron model may not capture the full complexity of FA in humans, including its cardiac manifestations.
Statistical uncertainty: The reliability of differential-expression findings depends on sample size, data quality, statistical methods, and correction for multiple comparisons.
Computational predictions: A predicted ability to reverse a transcriptional signature does not establish that a compound corrects the underlying disease mechanism.
Biological relevance: Candidate compounds require further investigation to determine whether their known targets and effects are relevant to FA.
Clinical translation: Laboratory validation, safety assessment, and additional studies would be required before any candidate could be considered for clinical use.

Reproducibility:

The project is intended to document its computational workflow so that other researchers can understand and, where possible, reproduce the analysis.
Planned repository materials include:
notebooks/ — Jupyter notebooks containing the analysis actually performed.
figures/ — Figures generated from verified analysis results.
results/ — Exported results, including differential-expression tables and candidate-compound findings, where available.
README.md — Research overview, methods, data sources, findings, and limitations.

Research Outputs:
- [View Research Abstract (PDF)](FA_Research_Conference_Abstract.pdf)
- [View Research Award: Top 20 out of 250+ Entries (PDF)](FA_Research_Top_20_Award.pdf)




