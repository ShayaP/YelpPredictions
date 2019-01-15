# YelpPredictions
<h3>Description:</h3>
This model can predict the star rating that users would give to a restaurant based on their review.

Note: refer to the jupyter ntoebook for more analysis done on the yelp dateset. This dataset can be found <a href="https://www.yelp.com/dataset/challenge">here</a>

<h3>Model details</h3> For this model we used the tf-idf values of the words in the review as the features we also added some other features that were given to us about the business itself such as previous reviews and some other features about the user, like the the number of "funny" or "cool" ratings that were given to this user. 

<h3>Scores:</h3>
We trained many models and compared their accuracies on the test set. This is the result that we got:</br>
<ul>
<li>Multi-Class SVM: 0.62064 on the test set.</li>
<li>Random Forest Classfier: 0.52488 on the test set.</li>
<li>Neural Net: 0.4348 on the test set.</li>
</ul>

