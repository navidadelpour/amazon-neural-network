Context

This dataset consists of reviews of fine foods from amazon. The data span a period of more than 10 years, including all ~500,000 reviews up to October 2012. Reviews include product and user information, ratings, and a plain text review. It also includes reviews from all other Amazon categories.
Data includes:
- Reviews from Oct 1999 - Oct 2012
- 568,454 reviews
- 256,059 users
- 74,258 products
- 260 users with > 50 reviews


This Dataset contains 10 features/independent variables/predictors etc. We will look at the reviews of each and every customers and will analyze them using k-nearest neighbors algorithm for now and in next part we will apply algorithms like naive bayes, logistic regression, svm, decision tree etc.

**Id** Row Id

**ProductId** Unique identifier for the product

**UserId** Unqiue identifier for the user

**ProfileName** Profile name of the user

**HelpfulnessNumerator** Number of users who found the review helpful

**HelpfulnessDenominator** Number of users who indicated whether they found the review helpful

**Score** Rating between 1 and 5

**Time** Timestamp for the review

**Summary** Brief summary of the review

**Polarity** determines if review is positive or negative

**Text** Text of the review

**Cleaned_Text** Cleaned version of text of the review

