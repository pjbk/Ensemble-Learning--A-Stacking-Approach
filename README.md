Notebook Outlines:

0. Stacking Ensemble: Overview
1. Dataset Description
2. Load libraries and read the data [EDA]
3. List of Individual Algorithms
4. Implement Stacking Ensemble Model
5. Performance Comparison



Dataset Description:

The Breast Cancer datasets is available UCI machine learning repository maintained by the University of California, Irvine. The dataset contains 569 samples of malignant and benign tumor cells.
The dataset can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Here, we choose four tree-based algorithms for this notebook.

* RandomForestClassifier
* DecisionTreeClassifier
* ExtraTreesClassifier and
* XGBoost Classifier

And, implement a Stacking Ensemble Model to probe if it can surpass the individual models accuracy.


Conclusion:

Although the individual classifier models showed reasonable outcomes, the Stacking ensemble learning approach has boosted the performance of the final model. The Stacked ensemble model outweighed the individual models.

Eventually, this notebook concludes that the Stacking ensemble learning approach can be a substantial paradigm in machine learning studies to improve models accuracy and reduce the error rate.


Reference

[1] Pankaj Bhowmik et al. "Cardiotocography Data Analysis to Predict Fetal Health Risks with Tree-Based Ensemble Learning", International Journal of Information Technology and Computer Science(IJITCS), Vol.13, No.5, pp.30-40, 2021. DOI: 10.5815/ijitcs.2021.05.03 link: http://www.mecs-press.org/ijitcs/ijitcs-v13-n5/v13n5-3.html

[2] Susan Yuhou Xia, “Using a Stacking Model Ensemble Approach to Predict Rare Events,” Conference Talks, SciPy 2019, 18th annual Scientific Computing with Python Conference, in Austin, Texas, USA. [Online]. Available: youtube.com/watch?v=6oD5K0x1k7c&t=551s

[3] ML From Scratch, "Stack Machine Learning Models - Get Better Results".  Access: https://mlfromscratch.com/model-stacking-explained/#/
