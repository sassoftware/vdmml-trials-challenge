Champion model based on misclassification rate was a **Gradient Boosting** model with Variable Clustering
* KS: 0.5797
* Misclassification Rate: 0.1275

Love the variable clustering node. It grouped my variables according to the clusters before it performed the modelling. I did change the
subsample rate to 1 for both the gradient boosting model without variable clustering and the one with clustering so that I didn't have any
of the variation that can happen with subsampling.  

Pipeline: 

![Pipeline](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/melcar/Variable-Clustering/pipeline.png "Pipeline")


Variable Clustering Results: 

![VariableClusteringResults](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/melcar/Variable-Clustering/VariableClusteringResults.png "Variable Clustering Results")

Model Comparison Results: 

![ModelComparisonResults](https://github.com/sassoftware/vdmml-trials-challenge/blob/master/Speed-Dating-Challenge/melcar/Variable-Clustering/ModelComparison.png "Model Comparison Results")

