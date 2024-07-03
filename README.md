# Antiviral_Prediction using Machine Learning
Seven Machine Learning algorithms Random Forest, XGBoost, Support Vector Machine, KNN, Decision Tree, MLP Classifier and Logistic Regression were benchmarked on a set of 2358 antiviral compounds compiled from the CAS COVID-19 antiviral SAR dataset. RF and XGBoost performed best in all the feature selection methods with maximum predictive accuracy.
A total 1157 two-dimensional molecular descriptors were computed among which, the most highly correlated descriptors were selected using Tree-based, Correlationbased and Mutual information-based feature selection methods.The best performance was achieved by the models developed using Random Forest and XGBoost algorithms in all the feature selection methods. The maximum predictive accuracy of both these models was 88% with internal validation. Whereas, with an external dataset, a maximum accuracy of 93.10% for XGBoost and 100% for Random Forest based model was achievable. Furthermore, the study demonstrated scaffold analysis of the molecules as a pragmatic approach to explore the importance of structurally diverse compounds in data driven studies.
# Dataset Collection and Curation
For this work, COVID-19 Antiviral Candidate SAR dataset
was obtained from CAS which is available at https://
www.cas.org/covid-19-sar-dataset. The dataset contained
290 K structure activity relation (SAR) data for antiviral
compounds which were directed at COVID-19 protein,
viruses and disease targets with their structure-bioactivity
details like IC50, EC50, MIC, potency, activity ratio etc. Out of
these 290 K antiviral compounds, 59872 were initially
selected whose activity was reported by their IC50 values.
These selected compounds were reported for 87 therapeutic
uses out of which 36 were discarded as they were not
significantly related to viral infections. For further analysis,
the compounds reported against these 51 therapeutic uses
were considered thus reducing the dataset size to 5572.
Thereafter, 3108 redundant compounds along with 106
other compounds which had inconclusive information i. e.
no definite values but some undefined references, against
their IC50 values were also discarded. Finally, 2358 antiviral
compounds were retained for further analysis as well as
dataset preparation for training and testing the ML models.
The data preparation process mainly included two activities
– first, to verify that all the 2358 antiviral compounds had a
definite IC50 value and second, to convert all these values
into same concentration unit i. e., μM. The conversion was
done due to diversity in the units of the IC50 values like nM,
μg/mol, ng/mol etc.
# Web server
The tool is available at https://acds.neist.res.in:8501/ and als in the Advanced Module of Molecular Property Diagnostic Suite - Covid 19 (https://mpds.neist.res.in:8085/)

# Cite the work
John, L., Soujanya, Y., Mahanta, H. J., & Narahari Sastry, G. (2022). Chemoinformatics and machine learning approaches for identifying antiviral compounds. Molecular Informatics, 41(4), 2100190.
