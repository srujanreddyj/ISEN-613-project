# ENGINEERING-DATA-ANALYSIS-ISEN-613--ACADEMIC-PROJECT
#### This is an academic project done as a part of ENGINEERING-DATA-ANALYSIS course at TEXAS A&M UNIVERSITY. ####

Project Goal
----
"Image classification" using various machine learning concepts that are taught in the classroom. 
  * Apply various methods learned in the classroom and come with up detailed explanation for choosen specific three methods.
  * Learn and apply various pre-processing techniques (allowed to go beyond the classroom teaching)
  * Provide an Executive summary and comprehensive conclusion.


Data Source
----
CIFAR 10 (provided by the professor)

Results
-----

| Method        | Pre-processing Method | Time for pre-processing 50,000 datapoints | Pre-processing on test data | Training Time | Accuracy (testing) | Cross-Validation Error Rate |
|---------------|-----------------------|-------------------------------------------|-----------------------------|---------------|----------|-----------------------------|
| QDA           | PCA                   | 13s                                       | Required                    | 13s           |  43%        | 55.32%                      |
| Random Forest | PCA                   | ~5 Minuttes                               | Required                    | 15.5          |     47%     | 57.80%                      |
| CNN           | Not Required          |                                           | Not Required                | 7 Hours       |  84%        | 17%                         |

Conclusion
-----

  * Different classification algorithms (Logistic Regression, QDA, SVM, Random Forest with Boosting) were tested and we got best prediction performance using Random Forest among those classification methodologies.
  * But the best prediction performace was achieved with Deep learning methods [CNN model using keras and tensorflow] with a cross-validation error of 17% and a testing accuracy of 84%.
