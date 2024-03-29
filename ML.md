#### Evaluation Metrics

1. [Macro VS Micro VS Weighted VS Samples F1 Score](https://stackoverflow.com/questions/55740220/macro-vs-micro-vs-weighted-vs-samples-f1-score#:~:text=Trying%20to%20put%20it%20in,includes%20the%20individual%20sample%20sizes.) | [Video](https://youtu.be/DF-rJA-eOUQ)
2. [Sklearn Metrics](https://neptune.ai/blog/balanced-accuracy)
3. [Balanced accuracy: what and why?](http://mvpa.blogspot.com/2015/12/balanced-accuracy-what-and-why.html)
> A **macro-average** will compute the metric independently for each class and then take the average (hence treating all classes equally), whereas a **micro-average** will aggregate the contributions of all classes to compute the average metric. In a multi-class classification setup, micro-average is preferable if you suspect there might be class imbalance. [Good Example](https://datascience.stackexchange.com/questions/15989/micro-average-vs-macro-average-performance-in-a-multiclass-classification-settin)

---
#### Hidden Arguments

> Functions are easier to understand if the results depend only on the values of the inputs. If a function returns surprisingly different results with the same inputs, then we say it has hidden arguments. [Hidden arguments](https://design.tidyverse.org/args-hidden.html#:~:text=If%20a%20function%20returns%20surprisingly,to%20know%20some%20other%20state) make code harder to reason about, because to correctly predict the output you also need to know some other state.
