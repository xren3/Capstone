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
- After performing permutation importance on the features, we find that 'fertilizer type' seemed to be the only variable that impacted whether or not a plant met its growth milestone
- By training our best Decision Tree Classifier on only the 'fertilizer type' variable, we found a further increase in accuracy, precision, and recall
- The best classifier model was determined to be DecisionTreeClassifier with max depth of 20 and a minimum samples leaf of 3
- The best model yielded an accuracy score of 0.692308, a precision score of 0.678571, and a recall score of 0.863636
- Fertilizer type is crucial for determining if a plant meets its growth milestone, as a plant fed with chemical fertilizer was 1.5x more likely succeed compared to plants fed with organic fertilizer and no fertilizer
