# Customer-Attrition-Modeling
Improving the performance of the classification task on imbalanced data sets, where instances of one class occur more frequently than the other, poses a challenge on standard machine learning algorithms. This is especially important when misclassifying the minority class incurs more cost. In this paper, I apply random sampling and cost-sensitive learning techniques to bagging and boosting classifiers to improve the performance of the imbalanced customer attrition classification task using recent data from a telecommunications service provider. I find that combining random up-sampling at an 80:20 ratio with a boosting classifier, in the form of AdaBoost, produces the best results. A 96% improvement over a Gaussian naive Bayes baseline classifier, as measured on the Matthews correlation coefficient (MCC), is observed.

---
File description:
- **01 Data_Exploration_and_Cleaning.ipynb:** Training data exploration, cleaning, preprocessing, and encoding
- **01 Test_Data_Prep.ipynb:** Test data preperation, preprocessing, and encoding
- **02 Initial_Hypothesis_Set_Evaluation.ipynb:** Evaluation of base classifiers on original data set
- **03 Random_Downsampling_50_50.ipynb:** Evaluation of base classifiers on original majority class down-sampled data set (50:50 ratio)
- **03 Random_Downsampling_60_40.ipynb:** Evaluation of base classifiers on original majority class down-sampled data set (60:40 ratio)
- **03 Random_Downsampling_70_30 .ipynb:** Evaluation of base classifiers on original majority class down-sampled data set (70:30 ratio)
- **03 Random_Downsampling_80_20.ipynb:** Evaluation of base classifiers on original majority class down-sampled data set (80:20 ratio)
- **03 Random_Downsampling_90_10.ipynb:** Evaluation of base classifiers on original majority class down-sampled data set (90:10 ratio)
- **04 Random_Upsampling_50_50.ipynb:** Evaluation of base classifiers on original minority class up-sampled data set (50:50 ratio)
- **04 Random_Upsampling_60_40.ipynb:** Evaluation of base classifiers on original minority class up-sampled data set (60:40 ratio)
- **04 Random_Upsampling_70_30.ipynb:** Evaluation of base classifiers on original minority class up-sampled data set (70:30 ratio)
- **04 Random_Upsampling_80_20.ipynb:** Evaluation of base classifiers on original minority class up-sampled data set (80:20 ratio)
- **04 Random_Upsampling_90_10.ipynb:** Evaluation of base classifiers on original minority class up-sampled data set (90:10 ratio)
- **05 Finetuning_RUS_80_20.ipynb:** Finetuning base classifiers using the 80:20 up-sampled data set
- **06 Finetuning_RUS_80_20.ipynb:** Further finetuning of base classifiers using the 80:20 up-sampled data set
- **07 Finetuning_Ada.ipynb:** Finetuning the AdaBoost classifier using the 80:20 up-sampled data set
- **08 Final_Test.ipynb:** Final evaluation of models on test set
