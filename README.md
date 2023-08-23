# **Training an NLP on Habitual Be**
## A First Step Towards an AAVE-literate Language Learning Model
Flatiron School Data Science Capstone 
Created August 2023

## Overview & Methodology
African American Vernacular English (AAVE), like other forms of English, has its own unique grammatical structures, vocabulary, and usage patterns. Despite being a defining part of American culture, language learning models have yet to incorporate an understanding and usage of AAVE.Furthermore, as AI becomes more a part of our daily lives, it behooves us to do whatever we can to prevent already intrinsic biases from expanding in reach and power. 

Timnit Gebru and others have alerted the public on the dangers of reproducing hegemonic power structures and harming already marginalized populations through use of large datasets culled from the Internet. In "[On the Dangers of Stochastic Parrots: Can Language Models Be Too Big?](https://dl.acm.org/doi/pdf/10.1145/3442188.3445922) the authors **"recommend mitigating these risks by budgeting for curation and documentation at the start of a project and only creating datasets as large as can be sufficiently documented."**

I have attempted to do just that through creating my own corpus wherein each sentence has been carefully selected, (in some cases) edited, and tagged by me. When compiling the corpus, I chose to pull from text written by Black people who are native speakers of African American Vernacular English (AAVE) for the text tagged as habitual be. The text tagged as present be contains sentences mostly composed by Black people who are native speakers of AAVE as well as text composed by people of various racial and ethnic backgrounds who only or primarily communicate using Standard American English (SAE).

This project aims to classify the usage of the word "be" in African American Vernacular English (AAVE) using various machine learning models. The goal is to distinguish between different usages with a high degree of accuracy. Given the small dataset of 2,000 rows, the project focuses on creating effective models that fit the data well without overfitting.

### Content Notice
As Bender, Gebru et al. have also noted, the decision to filter out "slurs" or "obscenities" can result in screening out marginalized voices who have reclaimed these words. Just as I have decided to retain 'stop words', curse words are present in my corpus and therefore represented in the word clouds under the exploratory data analysis section of my Jupyter Notebook.

## Models
The following models were used and evaluated:

1. Multinomial Naive Bayes (Final Model): Achieved the highest performance among the models tested.
2. Random Forest: Tested to increase accuracy and avoid overfitting but underperformed compared to the Multinomial Naive Bayes models.
3. Logistic Regression (Baseline Model)

## Final Model Performance
**Training Set Results:**
* Accuracy: 0.926875
* Recall: 0.94875
* Precision: 0.9089820359281438
* F1 Score: 0.928440366972477

**Test Set Results:**
* Accuracy: 0.9
* Recall: 0.91
* Precision: 0.8921568627450981
* F1 Score: 0.9009900

Confusion matrices for both training and testing data are also available in the Jupyter Notebook.

## Conclusion and Next Steps
Despite the inherent limitations of a small dataset created by a team of one, the final model was able to distinguish between usages of the word be with a high degree of accuracy.

As I look to grow this project, I would like to:

* Expand the corpus in collaboration with other native speakers of AAVE and linguistic experts*
* Experiment with other modeling methods (e.g. support vector machines, neural networks, etc.)
* Train models on other aspects of AAVE


  **Please inbox me if this is you and you are interested in collaborating!*
