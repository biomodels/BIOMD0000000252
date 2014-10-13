

This a model from the article:  
** Stress-specific response of the p53-Mdm2 feedback loop **   
Alexander Hunziker, Mogens H Jensen and Sandeep Krishna _BMC Systems Biology _
2010, Jul 12;4(1):94 [20624280](http://www.ncbi.nlm.nih.gov/pubmed/20624280),  
**Abstract:**   
ABSTRACT: BACKGROUND: The p53 signalling pathway has hundreds of inputs and
outputs. It can trigger cellular senescence, cell-cycle arrest and apoptosis
in response to diverse stress conditions, including DNA damage, hypoxia and
nutrient deprivation. Signals from all these inputs are channeled through a
single node, the transcription factor p53. Yet, the pathway is flexible enough
to produce different downstream gene expression patterns in response to
different stresses. RESULTS: We construct a mathematical model of the negative
feedback loop involving p53 and its inhibitor, Mdm2, at the core of this
pathway, and use it to examine the effect of different stresses that trigger
p53. In response to DNA damage, hypoxia, etc., the model exhibits a wide
variety of specific output behaviour -- steady states with low or high levels
of p53 and Mdm2, as well as spiky oscillations with low or high average p53
levels. CONCLUSIONS: We show that even a simple negative feedback loop is
capable of exhibiting the kind of flexible stress-specific response observed
in the p53 system. Further, our model provides a framework for predicting the
differences in p53 response to different stresses and single nucleotide
polymorphisms.

The parameters of the model corresponds to the resting state, with delta =
11hr-1, gamma = 0.2hr-1, kt = 0.03nM-1hr-1 and kf = 5000nM-1hr-1.

To simulate different stress conditions as in figure 2A (also look at the
curation figure of this model) of the reference publication, the above
parameter should be changed. The parameter values corresponding to different
stress conditions are shown in the following table.

  
Stress Condition/Parameter | delta | gamma  | kt | kf  
---|---|---|---|---  
Nutlin | 11hr-1 | 0.2hr-1 | 0.03nM-1hr-1 | 500nM-1hr-1  
Oncogene | 2hr-1 | 0.2hr-1 | 0.03nM-1hr-1 | 5000nM-1hr-1  
DNA damage | 2hr-1 | 0.5hr-1 | 0.03nM-1hr-1 | 2500nM-1hr-1  
Hypoxia | 2hr-1 | 0.2hr-1 | 0.01nM-1hr-1 | 5000nM-1hr-1  
  
This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2011 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)

