# crc-bioai-transition
Computational analysis of colorectal adenoma-to-carcinoma progression using single-cell transcriptomics and BioAI approaches.
## Current stage
Project setup and computational training
## Current progress
- Python fundamentals: variables, lists, dictionaries, loops, conditionals, and functions.
- Data analysis: CSV handling, pandas, group-level descriptive statistics, and basic visualization.
- Research focus: colorectal adenoma-to-carcinoma progression.
- Next step: exploratory analysis of a public colorectal single-cell dataset.

## CRC single-nucleus RNA-seq project

### Dataset
- GEO accession: GSE201348
- Data type: Human single-nucleus RNA sequencing
- Initial sample: GSM6061645

### Completed
- Reviewed the dataset and sample metadata.
- Downloaded one sample in 10x Matrix Market format.
- Successfully loaded the sample using Scanpy.
- Created an AnnData object containing 1,651 nuclei
  and 33,538 features.
- Inspected the basic AnnData structure.

### Next steps
- Verify sample and donor metadata.
- Perform initial quality control.
- Examine sample-level and cell-level information.
- Expand the analysis to additional samples.