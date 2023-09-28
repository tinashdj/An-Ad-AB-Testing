# An Ad AB Testing
## Introduction
The purpose of this project is to test whether the creative Ad strategy can brings significant user engagement comparing with the dummy Ad.

The dataset from [Kaggle](https://www.kaggle.com/datasets/osuolaleemmanuel/ad-ab-testing)

## Business Problem
An advertising company has created a new advertising strategy to increase the number of users of a platform. The company carries out an experimental method by giving creative advertisements to several customers and comparing them with the results of old or dummy advertisements that were also given to other customers. The company wants the data team to identify the most optimal advertising strategy by analyze the comparison of the results obtained. Does the creative ad increase the number of customer responses? Are there any significant differences? Can the creative advertising be used and give benefit to the company?

## Experiment Approach
Null Hypothesis Hₒ: p = pₒ

Alternative Hypothesis Hₐ: p ≠ pₒ

Confidence Level: 95% (α=0.05)

### Experiment Overview
1. What is the name of the experiment? An Ad A/B Testing
2. Define Hypothesis
- Hₒ : There is no significant difference between the ad success rate of both groups
- Hₐ : There is significant difference between the ad success rate of both groups
3. Who is the participant? The user that seeing the Ad
4. What variables will be tested? Dummy(old) Ad Design & Creative(new) Ad Design

### Experiment Time
- Experiment Design Date Started : 2020-07-03
- Experiment Design Date Finished : 2020-07-10
- The Number of Days Experiment Design Running : 8 (Friday to Friday)
- We will run this experiment for 8 days

## Statistical Conclusion
p-value = 0.2592 and alpha = 0.05

p-value > alpha

p-value higher than alpha, we can not reject the Null hypothesis and conclude that there is no statistically significant difference between the two groups of Ad A and Ad B

## Additional Conclusion
There were many unanswered observations that we removed from the dataset. The observations with no answers (both 'yes' and 'no' columns == 0) are removed with total 6834 or 84.61% observations from total 8077 observations. So we only left with 1243 observations. This significant loss of data causes a lack of observations to ensure that significant differences are detected.

## Business Conclusion
These findings indicate that the differences between the 'dummy ad' shown to the 'control' group, and the 'creative ad' shown to the 'exposed' group do not convert into better ad performance. These findings indicate that there is no solid business reason to push the implementation of the new ad design over the old one, as it will yield no extra benefit.
