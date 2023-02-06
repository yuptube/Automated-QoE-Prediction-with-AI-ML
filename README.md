# Histogram-Based Feature Selection Method
The algorithm for solving the problem stetement [ML5G-PS-012: Classification of Home Network Users to Improve User Experience](https://challenge.aiforgood.itu.int/match/matchitem/73/) provided by the ITU AI/ML in 5G Challenge 2022 in collaboration with ZTE.\
We pre-process and extract features based on insights from data networking protocols as well as an accurate histogram analysis.\
The performance evaluations show a prediction accuracy of 78 %. The feature importance studies show that the LAN RTT (Local Area Network Round Trip Time) value during daytime and midweek plays the most crucial role affecting the user QoE.

# Repository Overview
`model.pkl`: Random Forest classifier trained.

`DataSet`: Directory storing the raw data set, which you can also download from [ML5G-PS-012](https://challenge.aiforgood.itu.int/match/matchitem/73/)

`model_code.ipynb`: A notebook for running Histogram-Based Feature Selection Method. This code consists of the sections below
1. Read csv files
2. Feature extraction
3. Classifier model training
4. Classifier model save & load (if needed)
5. Classifier model test
6. Grouped permutation importance study

`README.md`: You are here!

# Required python packages
Please install packages below before running `model_code.ipynb`
- pandas
- natsort
- chinese_holiday
- sklearn
- numpy
- pickle
- matplotlib
- grouped_permutation_importance

# References
- [ML5G-PS-012](https://challenge.aiforgood.itu.int/match/matchitem/73/)
- [chinese_holiday](https://pypi.org/project/Chinese-holiday/)
- [Grouped permutation importance](https://github.com/lucasplagwitz/grouped_permutation_importance)