## Cooking data science project. 
# Given a list of ingredients, what are different recipes we can make?

Given a list of ingredients, what are different recipes I can make? That is, what recipes can I make with the food I have in my apartment?
 
I have three blogs on this project also and they can be found here:

[Data gatherting](https://medium.com/r?url=https%3A%2F%2Fjackmleitch.medium.com%2Fusing-beautifulsoup-to-help-make-beautiful-soups-d2670a1d1d52)

[Initital Model](https://towardsdatascience.com/building-a-recipe-recommendation-api-using-scikit-learn-nltk-docker-flask-and-heroku-bfc6c4bdd2d4)

[Updated Model](https://towardsdatascience.com/building-a-recipe-recommendation-system-297c229dda7b)


You can run this model yourself using my API:
```
docker pull jackmleitch/whatscooking:API

docker run -p 5000:5000 -d whatscooking:api

```

