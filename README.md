# Capstone Pt 1
### Plant Growth Prediction and Classification

by Xinyi Ren

### Executive summary

#### Background
Providing plants with proper growth conditions greatly impacts crop yields and the agriculture sector. By understanding the different factors and how they affect plant growth, we can make farming more efficient, increasing the global food supply while minimizing waste. We can also learn how to better protect plant species from extreme weather conditions to ensure their health and longevity.

#### Research Question
Can we accurately predict if a plant can reach its growth milestone by analyzing its growth factors and determine the most optimal growth conditions?

#### Data Sources
The dataset Plant Growth Data Classification is sourced from Kaggle

#### Methodology
We will be focusing mainly on the classification techniques: KNN, Decision Tree, Logistic Regression and SVM to predict the optimal growth condition for plants. We can also use permutation importance to determine which factors have the most influence on plant growth.

#### Results
- Decision Tree Classifier scored the highest on accuracy, precision, and recall
- After performing permutation importance on the features, we find that 'fertilizer type' seemed to be the most important variable that impacted whether or not a plant met its growth milestone
- The best classifier model was determined to be DecisionTreeClassifier with max depth of 30 and a minimum samples split of 10
- Fertilizer type is crucial for determining if a plant meets its growth milestone, as a plant fed with chemical fertilizer was 1.5x more likely succeed compared to plants fed with organic fertilizer and no fertilizer

#### Next Steps
- More data would likely improve the classification models. A bigger dataset would minimize fluctuation in performance due to the train/test split.
- The Decision Tree model can be further tuned to detect for any overfitting
- The assumption is that all plants in this dataset are of the same specie, however the provider of this dataset did not confirm if this is true. If our assumption was false we would have to further divide up the dataset since different plants respond differently to environmental factors.
