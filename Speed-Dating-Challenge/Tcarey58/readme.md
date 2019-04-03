Champion model based on KS and misclassification rate was a **Python Gradient Boosting** model with some variable selection, imputations, and sas code to 
convert some of the data to get it ready for the python model.

* KS: 0.5935
* Misclassification Rate: 0.1291

The Python Gradient Boosting model outperforms the SAS Gradient Boosting model but when I applied autotuning to the Gradient Boosting model the autotuned GB model outpermed the pythone one.  

Pipeline: 

![Pipeline](https://github.com/melcar1054/vdmml-trials-challenge/blob/master/melcar/Variable-Clustering/pipeline.png "Pipeline")


Variable Clustering Results: 

![VariableClusteringResults](https://github.com/melcar1054/vdmml-trials-challenge/blob/master/melcar/Variable-Clustering/VariableClusteringResults.png "Variable Clustering Results")

Model Comparison Results: 

![ModelComparisonResults](https://github.com/melcar1054/vdmml-trials-challenge/blob/master/melcar/Variable-Clustering/ModelComparison.png "Model Comparison Results")

