# Readme

This artifact contains the dataset and source code of the Heuristic Linguistic Patterns approach published in Paper #75. 

The artifact is freely available at a permanent link:
 [here](https://doi.org/10.5281/zenodo.3875803) 

The raw dataset can be also found by Google Site as link: https://sites.google.com/view/fse-2020-hlp

# Heuristic Linguistic Pattern
This paper presents an approach to automatically tag performance issues, based on linguistic analysis of the issue description. Our approach stems from the observation that performance-related issues often contain similar linguistic characteristics at the sentence level, agnostic of specifc software product. 

# Experiment

Step 1: Download the raw data and executable jar file from the DOI link [Zenodo] # Heuristic Linguistic Pattern
This paper presents an approach to automatically tag performance issues, based on linguistic analysis of the issue description. Our approach stems from the observation that performance-related issues often contain similar linguistic characteristics at the sentence level, agnostic of specifc software product. 

# Experiment

Step 1: Download the raw data and executable jar file from the DOI link [Zenodo] https://doi.org/10.5281/zenodo.3875803

Step 2: Unzip the raw data.zip. There are csv files that contains the manually labelled sentences and issues from dataset-1, dataset-2, and dataset-3. 

Step 3: Split the issue description test into sentences by using the SentenceSplitter.jar file.
For example: 
```bash
java -jar SentenceSplitter.jar ./dataset-2-issue.csv ./dataset-2-sentence.csv
```

Step 4: Use NLPAnalysis.jar to generate the meta-data of sentences for fitting the linguistic pattern approach. 
For example:
```bash
java -jar SentenceSplitter.jar ./dataset-2-sentence.csv ./dataset-2-meta-sentences.csv
```

Step 5: Use HLPMatcher.jar to match the heuristic linguistic patterns to each sentence.
For example:
```bash
java -jar HLPMatcher.jar ./dataset-2-meta-sentences.csv ./dataset-2-vector.csv
```

Step 6: Use Text Classification.ipynb and Vector Binary Classification.ipynb to use machine learning/deep learning models to predict if and issue or sentence is performance related. 

Step 2: Unzip the raw data.zip. There are csv files that contains the manually labelled sentences and issues from dataset-1, dataset-2, and dataset-3. 

Step 3: Split the issue description test into sentences by using the SentenceSplitter.jar file.
For example: 
```bash
java -jar SentenceSplitter.jar ./dataset-2-issue.csv ./dataset-2-sentence.csv
```

Step 4: Use NLPAnalysis.jar to generate the meta-data of sentences for fitting the linguistic pattern approach. 
For example:
```bash
java -jar SentenceSplitter.jar ./dataset-2-sentence.csv ./dataset-2-meta-sentences.csv
```

Step 5: Use HLPMatcher.jar to match the heuristic linguistic patterns to each sentence.
For example:
```bash
java -jar HLPMatcher.jar ./dataset-2-meta-sentences.csv ./dataset-2-vector.csv
```

Step 6: Use Text Classification.ipynb and Vector Binary Classification.ipynb to use machine learning/deep learning models to predict if and issue or sentence is performance related. 