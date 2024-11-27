# Observations

1. It does not make sense to use beer/name as a factor when designing a model due to the fact that the dataset provided seems to be grouped by beer name. So, in theory, it is highly plausible that an unseen portion could contain a beer/name that has never been seen before. Therefore, it seems rather irrelevant to include it as a factor when designing a model.

2. A lot of the reviews have common phrases such as "on tap", and "handbottled". It makes sense to study the influence of these words on user-ratings.

3. None of the 180k entries in the train data seem to have invalid/null entries. 196 entries do not have text-reviews, but are still considered as 'acceptable'

4. Data is 18000x13(18000 rows, 13 cols)

5. Other useful data:
No. of unique beers in train data: 7694
Average no. of reviews per beer: 23.394853132310892
No. of unique users: 9224
Average no. of reviews per user: 19.514310494362533
No. of unique breweries: 545
Average no. of reviews per brewer: 330.27522935779814
No. of rows: 180000
No. of cols: 13

## To-do:

1. Data Types: Check the data types of each column to confirm they match expected formats
2. Duplicate Records
3. Scam Reviews - More than three exact matching text reviews of differnet beers
4. Correlation between ABV and Taste, Aroma, Palate, Taste, Overall
5. Do prolific reviewers give higher or lower average ratings compared to occasional reviewers?
6. Any beer style correlation
7. Word cloud

