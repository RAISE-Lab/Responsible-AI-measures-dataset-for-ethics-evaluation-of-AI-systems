# Responsible Artificial Intelligence (RAI) Measures Dataset

Meaningful governance of any system requires the system to be assessed and monitored effectively. In the domain of Artificial Intelligence (AI), global efforts have established a set of ethical principles like fairness, transparency, and privacy upon which AI governance expectations are being built. The computing research community has proposed numerous means of measuring an AI system’s normative qualities along these principles. Current reporting of these measures is principle-specific, limited in scope, or otherwise dispersed across publication platforms, hindering the domain’s ability to critique its practices. To address this, we introduce the Responsible AI Measures Dataset, consolidating 11,865 data points across 791 evaluation measures covering 11 ethical principles. It is extracted from a corpus of computing literature (n=257) published between 2011 and 2023. The dataset includes detailed descriptions of each measure, AI system characteristics, and publication metadata. An accompanying, interactive Sunburst visualization tool supports usability and interpretation. The Responsible AI Measures Dataset enables practitioners to explore existing assessment approaches and critically analyze how the computing domain measures normative concepts.

# Using the Interactive Visualization
This dataset has a corresponding visualization that can be dynamically interacted with. It can be found as the "Sunburst_Visualization_Link.md" file in this repository.

## Demo Link: https://bit.ly/RAI_Measures_Dataset_demo

To use the visualization:

1. Select a principle, followed by the component of the ML system that you are interested in exploring. Note: Hovering will display three pieces of metadata: the tier you are currently at in the visual, the parent (e.g., the tier prior), and the principle you are currently hovering above.
2. Click on a measure to see the corresponding measurement process.
3. Learn more about the measure, its formulaic variables (if quantitative), and relative context of use, please click the link on each measurement process to access the authors’ publication.

Some measurement processes will include paper-specific references, terms, or formulas that may require further context to understand. Please use the paper title and lead author name(s) to further investigate the measure(s).

# Current Version 

Currently, this work is on Version 1.0 of the publicly shared dataset and corresponding visualization. The dataset is in a Microsoft Excel (.xslx) format. Note that it is not recommended to open the file in a .csv format due to the increased likelihood of corrupted characters and file formatting. Please read the below sections for more information on the dataset.

## Using the Dataset
The spreadsheet includes user guidance stages grouping fifteen columns. These user guidance stages intentionally divide and describe the data columns among similarities that they share. The interactive Sunburst visualization can be found here: **https://rai-measures-dataset.onrender.com**. 

**Target Output (Columns A and B in Blue)**: The resulting measures collected in this dataset.
  1. Measure
  2. Measurement Process
     
**Entry Points (Columns C and D in Orange)**: The primary features in narrowing down potential measures for an algorithmic system.

  4. Principle
  5. Part of the ML System

**Measurement Properties (Columns E - G in Green)**: The standard(s) per which each measure uses in its evaluation.

  7. Criterion Name 
  8. Criterion Description 
  9. Type of Assessment

**Algorithmic System Characteristics (Columns H - K in Purple)**: Additional features that a user can consider when narrowing down measures to use.

  10. Application Area
  11. Purpose of ML System 
  12. Type of Data
  13. Algorithm Type

**Metadata (Columns L - O in Light Blue)**: Details further documentation into each source that was extracted to collect each feature and measure.

  14. Title
  15. Lead Author(s)
  16. Publication Year
  17. Key Contributions 

