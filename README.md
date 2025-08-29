# Timeweight: Forest Composition vs. Harvest History

This repository contains the **Timeweight code, molecular analysis scripts, watershed delineation, fluorescence correlations, manuscript, and supporting information** for the study:

> Freeman EC, Emilson EJS, Dittmar T, Tanentzap AJ.  
> *Forest composition outweighs harvest history in shaping aquatic headwater dissolved organic matter quality.*  
> Submitted to **JGR Biogeosciences** (2025).


## 📂 Repository Contents

### 🔹 Analysis Notebooks
- `TimeWeightWithAll4.ipynb` → Implements the Timeweight analysis and temporal weighting functions for harvest impacts.  
- `MoleculeClassifyCode.ipynb` → Classifies molecular formulae from FT-ICR-MS data into compound groups (e.g., polyphenols, aliphatics, CRAM).  
- `FT_UnqiueHarvestMolecules_Filter.ipynb` → Identifies and filters molecules uniquely associated with harvest effects.  
- `WatershedCode.ipynb` → Delineates headwater catchments and extracts watershed features from DEM and forest data.  
- `FluorescenceCorrelationCode_17112022.ipynb` → Correlates fluorescence PARAFAC components with FT-ICR-MS molecules.  

### 🔹 Data
- `OpenFluorSearch___20221213.xlsx` → Component matches against the OpenFluor fluorescence database.  


## 📖 Background

Forests release dissolved organic matter (DOM) into streams, shaping water quality and ecosystem processes. While logging is often assumed to strongly affect DOM, this study shows that forest composition is the strongest driver of DOM quality at landscape scales.

The Timeweight method tests different temporal decay functions to model harvest impacts through time, providing a framework for cumulative impact assessment.

## Key findings:

Forest composition and soil moisture dominate DOM patterns.

Logging effects are weaker, only detectable in wet or recently harvested forests.

Harvest during wet conditions amplifies DOM changes and should be avoided.

## 📜 Citation
If you use this code, manuscript, or supplementary information, please cite:
Freeman EC, Emilson EJS, Dittmar T, Tanentzap AJ. 
Forest composition outweighs harvest history in shaping aquatic headwater dissolved organic matter quality. 
JGR Biogeosciences (in review).

##📄 License
Code: MIT License
Manuscript, Supplementary Information, and Figures: CC-BY 4.0

## 📬 Contact
Erika C. Freeman
Eawag & University of Cambridge
📧 erika.freem@gmail.com
