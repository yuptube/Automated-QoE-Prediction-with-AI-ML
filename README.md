# Automated-QoE-Prediction-with-AI-ML
The algorithm for solving the problem stetement [ML5G-PS-012: Classification of Home Network Users to Improve User Experience](https://challenge.aiforgood.itu.int/match/matchitem/73/) provided by the ITU AI/ML in 5G Challenge 2022 in collaboration with ZTE. The performance evaluations show a prediction accuracy of 78 %. 

# Repository Overview
`model.pkl`: Random Forest classifier trained.

`DataSet`: Directory storing the raw data set, which you can also download from [ML5G-PS-012](https://challenge.aiforgood.itu.int/match/matchitem/73/).

`model_code.ipynb`: A notebook for running Histogram-Based Feature Selection Method. This code consists of the sections below:
1. Read csv files
2. Feature extraction
3. Classifier model training
4. Classifier model save & load (if needed)
5. Classifier model test
6. Grouped permutation importance study
7. Classifier model benchmarking study

`README.md`: You are here!

# Questions?
Email to: m.boloursazmashhadi@surrey.ac.uk

# Dependency 
1. To run the repo , add poetry and general python environment for fixing package