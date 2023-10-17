# SBML-Microbiome-Pipeline
Code for an integrated study conducted on vaginal 16S rRNA microbiome samples using Systems Biology and Machine Learning approaches for the prediction of Preterm Birth

**Microbiome Analysis was performed on Ubuntu using Parallel-META 3:**
Parallel-Meta Suite is a comprehensive and full-automatic computational toolkit for rapid data mining among metagenomic datasets. Both metagenomic shotgun sequences and 16S/18S/ITS rRNA amplicon sequences are accepted. For system requirements and further information, check out the Microbiome-Analysis repository.
Install Parallel-META 3 from http://bioinfo.single-cell.cn/parallel-meta.html, extract and install software.
Taxonomic classification and functional profiling command: PM-parallel-meta [parameters]
Multi-sample feature selection based on the taxonomical profiling results command: PM-select-taxa [parameters]
Multi-sample feature selection based on the taxonomical profiling results command: PM-select-func [parameters]

**Systems Biology approach: Correlational Analysis using Python 3.9.0:**
Spearman's correlational scores calculations: pandas, numpy, matplotlib.pyplot, seaborn, spearmanr libraries.

Machine Learning approach: Predictive Analysis using Python 3.9.0:
Importing and manipulating dataframes: pandas, NumPy libraries.
Label Encoding: scikit-learn library.
Normalization of absolute count data: StandardScaler(), RobustScaler(), and Logarithmic Normalisation algorithm from NumPy library.
Imbalance determination and handling: Collections, and Imblearn libraries.
Data Splitting: scikit-learn library.
Model algorithms: scikit-learn and XGBoost libraries.

**Visualizations and Statistical Analysis using R:**
Bar plots: ggplot2, tidyr, ggpubr libraries.
Alpha-Diversity: vegan, ggplot2, ggpubr libraries.
Beta-Diversity and PCoA plot: Custom function based on vegan, ape, and ggplot2 libraries.
T.Test and Effect-Size Calculations: dplyr, rstatix, ggplot2, and ggpubr libraries.
