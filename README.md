# 102017184_sampling_Assignment
In this python code, I have used sampling techniques on a credit card fraud detection dataset and then applied various ML models on each samples to determine which sampling technique gives higher accuracy on which model.

Following 5 sampling Techniques were used:

1) Simple Random Sampling (Sampling1)
2) Systematic Sampling (Sampling2)
3) Stratified Sampling (Sampling3)
4) Cluster Sampling (Sampling4)
5) Convenience Sampling(Sampling5)

The Sample size was calculates using the following formula: n = Z^2(p(1 – p)/m^2) where: n = sample size Z = z-value (for 95% confidence interval, Z = 1.96) p = proportion of the minority class (taken as 0.5 for a balanced dataset) m = margin of error (taken as 0.05).

Following 5 models were applied on the sampled dataset:

1) Logistic Regression (Model1)
2) Decision Tree Classifier (Model2)
3) Random Forest Classifier (Model3)
4) Support Vector Classifier (SVC) (Model4)
5) Extra Tree Classifier (Model5)

On execution of the code, following results were obtained: The cells of the table represent accuracy of the applied model using the respective sampling technique.


<img width="458" alt="image" src="https://user-images.githubusercontent.com/79622989/219969898-1c2f33a9-0c41-4424-93db-b481d15211a5.png">

As we can see the following accuracy was obtained for the different samples used:

1) For Sampling1, Model4 has the highest accuracy i.e. 68.39%.
2) For Sampling2, Model2 has the highest accuracy i.e. 85.16%.
3) For Sampling3, Model2 has the highest accuracy i.e. 68.39%.
4) For Sampling4, Model3 has the highest accuracy i.e. 70.97%.
5) For Sampling5, Model5 has the highest accuracy i.e. 74.84%.

