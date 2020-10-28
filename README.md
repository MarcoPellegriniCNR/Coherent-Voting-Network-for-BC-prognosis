# Coherent-Voting-Network-for-BC-prognosis
Support Web Site for the paper "Accurate Prediction of Breast Cancer Survival through Coherent Voting Networks with Gene Expression Profiling"

Directory InputDatFiles contains the train-validate-test data sets for 8 therapy classes.
Each file is a tab-separated csv text file.
The first line holds Metabric patient ID
The second line holds the survial class (below 60 months, above 72 months)
Subsequent lines hold the mRNA expression levels

Train data are marked as 'train' in the file name,
Validate data is marked as 'tests-part1' in the file name.
Testa data is marked as 'test-part2' in the filename.
The filename reports as 'equal' data sets in which the two classes have been equalized by subsampling the largest class.
