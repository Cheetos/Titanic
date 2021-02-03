# Titanic
Getting Started to Kaggle

https://www.kaggle.com/c/titanic

## What do we need to learn?

* R/Python
* Basic theory for linear regression and classification (Introduction Machine Learning)

## Goal

* Build a classification algorithm, not matter if it is good or bad, but be able to see it working with R/Python. 
* Get our hands dirty with R/Python and machine learning
* Get knowledge

## References

* https://www.youtube.com/watch?v=8yZMXCaFshs&feature=youtu.be
* https://www.kaggle.com/alexisbcook/titanic-tutorial

## Results

The results are published in the following kernel:

https://www.kaggle.com/desparzaalba/titanic-with-transformers

This work was based on this other kernel:

https://www.kaggle.com/gunesevitan/titanic-advanced-feature-engineering-tutorial

I took the parts of feature engineering and data visialization from the kernel from "gunesevitan", since they are quite educational. The main change that I made was to integrate the pre-processing step into transformers, that way I can easily use it in a pipeline for the training and test sets.\\

There is work that can be done to improve the results, specially in the part of the model used. I didn't explore too many options to be honest. The accuracy of this kernel was 0.83 with the validation set and 0.78 in the test set, which is around the top 10%. 

## Conclusions

The main objective was accomplished, which was learning and getting familiar with Kaggle, I learnt to create new features from the existing ones, vsualization techniques and I was able to integrate customized transformers in order to have reusable pipelines. 

## Future work

Try other parameters for the Random Forest model used, and also try to use other models and compare the results obtained.
