#  DeepMediChecker: NLP & Deep Learning-Driven Drug Interaction and Article Explorer

# Objectives

1. To develop an automated system to efficiently assist healthcare professionals and research scholars in extracting crucial DDI information from the extensive biomedical literature.
   
2. Integrating advanced NLP techniques and utilizing the BioBERT deep learning model, our system is dedicated to the automated identification, classification, and summarization of DDIs within specific medical conditions.

3. Offer a unique feature in the form of an article explorer. This article explorer empowers healthcare professionals and research scholars to explore a centralized repository of recommended articles, facilitating a comprehensive understanding of DDIs.

# Dataset Description

1) SemEval 2013 DDI Extraction The models under consideration were trained and
assessed using the DDIExtraction2013 corpus, accessible for download at the following link: https://github.com/yardstick17/DDIExtraction.

The DDIExtraction2013 challenge includes the DDI Corpus, a set of texts that have been manually annotated. This corpus is a valuable benchmark for training and evaluating supervised machine-learning algorithms to extract DDIs from biomedical literature. This corpus
holds significant importance as it is a pivotal dataset for assessing and contrasting the effectiveness of different
DDI extraction techniques. 

This corpus comprises 730 documents depicting DDIs sourced from the DrugBank database and 175 abstracts related to DDIs from the
MedLine database.


The DDI 2013 corpus contains five DDI types: Advice, Effect, Mechanism, and Int.

Mechanism: When the text describes the process of the interaction.

Effect: When the text describes the outcome of drug interactions.

Advice: When the text describes recommendations or advice.

Int: When a DDI is provided without any information.

# Conclusion

This study primarily focused on predicting the DDI type in the context of two drugs and generating summaries
within specific medical conditions, with the additional capability of article exploration. 
