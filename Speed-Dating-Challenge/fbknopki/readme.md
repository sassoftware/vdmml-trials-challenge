Champion Model based on KS and misclassification rate was a **Gradient Boosting** model with node Variable Clustering selected.
* KS: 0.6533
* Misclassification Rate: 0.1100

This pipeline is quite interesting, I've experimented different machine learning techniques and I really could see the power of SAS Visual Data Mining and Machine Learning.
First, I prepared the data and analyzed the descriptive statistics (profiling the data) to understand missing values, outliers, similarities, possibilities to create clusters and others. Then, I explored the dataset with great objects like Automated Analysis, Parallel Coordenates Plot, Decision Tree and Correlation Matrix. After that, I built the model, created a project, my pipeline very fastly using incredible and performatics nodes. Below you can see features that I've used:
- For Data Mining:
   - Data Exploration (in miscellaneous menu)
   - Variable Selection
   - Variable Clustering
   - Transformations
   - Imputation for missing values
- For Supervised Learning:
   - Various Gradient Boosting with different parameters and also autotuning and LIME
   - Forest Model
   - Logistic Regression Model
   - And I've also included Open Source Model with R and Python codes
- In the end, I compared all models easily and discover the Champion.

The Speed Dating database brougth interesting points how people think to find the partner, the great and perfect relationship.
What really calls the attention is that in first moment when people register to the event, people thinks more how to evaluate the six main attributes: Attractiveness, Sincerity, Intelligence, Fun, Ambitious and Shared Interests. They're not under pressure, then they can idealize what they want. The second moment, in the event, the time runs fast and the decisions are taken without think too much as well without know better the partner.
In the end what we see is:
- Be attractive is relevant. But no lose your hope, if you are fun, you can gain many points with the other.
- Shared interests is something relevant as well. It can be comproved in first moment and during the event.
- Field of Study is an important variable where you see group differences that cause great impact on match. Never add "other" as option (you see no matches to it).
- Women are more confident regarding the probability they will be choosen by men.
- Match estimation is a good variable since people say a number and seems to act to achieve that number as a goal.
- The expectation of happiness is not important in this game. Is really true? And, is more important to men than women.
- Race is an interesting variable since we can see a cultural difference where, for example, Asians looking for Asians.
- Importance on religion appears more relevant to men. Even low or high values cause impacts on match.
- Ambition is more relevant for women chose, for men it appears, but for them the grade seems to women be less ambition than them.

There are much more to explore and be surprised, but I'll leave to you contribute :)
   
Below some details:

**Pipeline:** 

![Pipeline](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic01.png "Pipeline")

**Variable Clustering Results:**

![ClusteredVariablesNetwork](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic08.png "Clustered Variables Network")

![ClusteredVariablesTables](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic07.png "Clustered Variables Table")

![DendrogramClusteredVariables](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic09.png "Dendrogram Clustered Variables")

**Model Comparison Results:**

![ModelComparisonResults](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic02.png "Model Comparison Results")

**Results of my Champion Model:**

![ErrorPlotMisclassificationRate](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic03.png "Error Plot Misclassification Rate")

![VariableImportance](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic04.png "Variable Importance")
 
**Match Prediction of my Champion Model:**

![MatchPrediction](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/fbknopki/pic05.png "Match Prediction")
