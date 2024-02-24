# QL4POMR Readme: Jan-April Term

## Models Used
- **BioBert**: [View on GitHub](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April/BootStrapped-Level-1-filter-Bert)
- **BioLinkBert**: [View on GitHub](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April/BootStrapped-Level-1-filter-Bio-Link-Bert)
- **BioGpt**: [View on GitHub](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April/BootStrapped-Level-1-filter-Gpt)

## Observations
### Boot Strapped Level-1
- Initial bootstrapping shows promising classification for "No" and "Maybe", with a higher count of "Yes" due to context capture limitations.
![All Patients Graph for Boot Strapped Level-1](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/Patient_Graphs_Bootstrapping_level-1_vs_Manual_verification/All_patients_count.png)
### Bootstrapping Level-2
- Attention + Diagnosis words
- Upon bootstrapping level-2 we find that the ‘Yes’ are now classified properly when compared to Bootstrapping level-1 but still the BioGPT model has miss classified many ‘Yes’ to no that is why it has many no counts.
![All Patients Graph for Boot Strapped Level-2](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/Patient_Graphs_Bootstrapping_level-2_vs_Manual_verification/All_Patients-Counts.png)
### Enhanced Bootstrapping Level-2
- Attention + Definition of the diagnosis words
- Upon closer look we can see that definition of diagnosis worked slightly better when compared to bootstrapping-2. The main change is when we check for the patient individually we can see a better classification than bootstrapping 2.
![All Patients Graph for Boot Strapped Level-2 Enhanced](https://github.com/lukecage0/QL4POMR/blob/main/Jan-April/Patient_Graphs_Bootstrapping_level-2-Enhanced_definitions_vs_Manual_verification/All_Patient_Counts_by_Model.png)

## Data and Images
All related data and graphical visualizations are available at the following path: [View Data and Images](https://github.com/lukecage0/QL4POMR/tree/main/Jan-April)

