# QL4POMR Readme: Jan-April Term

## Models Used
- **BioBert**: [View on GitHub](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April/BootStrapped-Level-1-filter-Bert)
- **BioLinkBert**: [View on GitHub](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April/BootStrapped-Level-1-filter-Bio-Link-Bert)
- **BioGpt**: [View on GitHub](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April/BootStrapped-Level-1-filter-Gpt)

## Observations
### Bar Graph Boot Strapped Level-1
- Initial bootstrapping shows promising classification for "No" and "Maybe", with a higher count of "Yes" due to context capture limitations.
![All Patients Graph for Boot Strapped Level-1](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/Patient_Graphs_Bootstrapping_level-1_vs_Manual_verification/All_patients_count.png)
### Bar Graph Bootstrapping Level-2
- Attention + Diagnosis words
- Upon bootstrapping level-2 we find that the ‘Yes’ are now classified properly when compared to Bootstrapping level-1 but still the BioGPT model has miss classified many ‘Yes’ to no that is why it has many no counts.
![All Patients Graph for Boot Strapped Level-2](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/Patient_Graphs_Bootstrapping_level-2_vs_Manual_verification/All_Patients-Counts.png)
### Bar Graph Enhanced Bootstrapping Level-2
- Attention + Definition of the diagnosis words
- Upon closer look we can see that definition of diagnosis worked slightly better when compared to bootstrapping-2. The main change is when we check for the patient individually we can see a better classification than bootstrapping 2.
![All Patients Graph for Boot Strapped Level-2 Enhanced](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/Patient_Graphs_Bootstrapping_level-2-Enhanced_definitions_vs_Manual_verification/All_Patient_Counts_by_Model.png)
### HeatMap Boot Strapped Level-1
- Attention + Definition of the diagnosis words
- Shows a perfect self-correlation, as expected.
- Has a strong positive correlation (0.81) with Bootstrapping with Diagnosis, indicating similar performance between these two methods.
- Displays a moderate positive correlation (0.46) with Bootstrapping with Definitions, suggesting some level of shared tendencies but also notable differences in outcomes.
![All Patients Graph for Boot Strapped Level-2 Enhanced](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/heatmaps/All_Patients_Heatmap.png)
### HeatMap Bootstrapping Level-2
- Attention + Definition of the diagnosis words
- The moderate positive correlation (0.51) with Bootstrapping with Definitions indicates these methods may complement each other but also have distinct aspects.
![All Patients Graph for Boot Strapped Level-2 Enhanced](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/heatmaps/All_Patients_Heatmap.png)
### HeatMap Enhanced Bootstrapping Level-2
- Attention + Definition of the diagnosis words
- The correlations with both Level-1 and Diagnosis methods are moderate (0.46 and 0.51 respectively), which could imply that definitions bring a unique approach to the analysis, diverging from the other two methods to some extent.
![All Patients Graph for Boot Strapped Level-2 Enhanced](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/heatmaps/All_Patients_Heatmap.png)

## Data and Images
All related data and graphical visualizations are available at the following path: [View Data and Images](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April)

