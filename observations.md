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

6. 
Data type information
beer/name               object
beer/beerId             object
beer/brewerId            int64
beer/ABV               float64
beer/style              object
review/appearance       object
review/aroma            object
review/palate           object
review/taste            object
review/overall         float64
review/time              int64
review/profileName      object
review/text             object
beer/ABV_normalized    float64
adjusted_rating        float64
dtype: object

7. No duplicate records found

8. Flagged reviews: more than 3 exactly matching review texts
Profile names with flagged reviews:
brewersspot
Quake1028
DasBierChef
drowland
bchlala
SuperDave
JediMindTricks
Brandman
camilla
kdheckle
dobrisa
iamsancho16

9. Wordcloud in the .ipynb file

10. Prolific reviewer defn = greater than 10 reviews. Graph included for prolific reviewer average rating vs overall

11. Scatter plot included for average rating / number of reviews.

12. Scatter plot -> text length vs rating

