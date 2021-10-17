# AssociateRuleLearningForPredictingCustomerBehaviour

 Predicting that if a customer buy a particular product then there is a high chance that they will buy the other product.
 
 # Apriori algorithm
People who bought also bought ... That is what Association Rule Learning will help us figure out!

Apriori has 3 parts 1)Support 2)Confidence 3)Lift

1) Support
For Movie Recommendation : Support(M) = ((No of users whose watchlists containing M)/(Total number of users)
For Market basket optimisation : Support(I) = ((Number of transactions containing I)/(Total number of transactions))
for example let say out of 100 people , 10 people have watched movie american psycho so the support for the movie is 10%

2) Confidence
For Movie Recommendation : confidence(M1 -> M2) = ((No of users who watched M1 and M2)/(No of users who watched M1))
For Market basket optimisation : confidence(I1 -> I2) = ((No of transactions containing I1 and I2)/(No of transactions containing I1))
For example 20 people have seen movie A and B whereas 40 people have just seen movie A, so the confidence is (20)/40 = 50%

3) Lift
For Movie Recommendation : lift(M1->M2) = ((confidence(M1->M2))/(Support(M2)))


![Screenshot (243)](https://user-images.githubusercontent.com/20074508/137640725-f7c6145c-0e6f-4c0e-9a41-37154dd7bbb6.png)

![Screenshot (242)](https://user-images.githubusercontent.com/20074508/137640734-29c4a08e-e55b-4ffb-a311-7b608180d48b.png)

# Eclat method

intiuition
We only have support here
for movie recommendation support(M) = (No of users who has watched movie M)/(Total number of users)

![Screenshot (244)](https://user-images.githubusercontent.com/20074508/137640832-3907b5c1-01ec-43aa-aa2b-e0734ef3c56d.png)
