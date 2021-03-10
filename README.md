# SVD_recommender
MSc module project: build a recommender system, train with a dataset of c.26m user-movie records.

I used the Singular Value Decomposition implemenation in the Surprise Library. 
Parameter tuning with GridSearch CV was attempted, but the computational expense with such a large data set was prohibitive and limited what could be done. 
Nonetheless a reasonable RMSE of c0.82 was achieved. 
