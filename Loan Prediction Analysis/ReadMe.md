# Dataset Information
Dream Housing Finance company deals in all home loans. They have a presence across all urban, semi-urban and rural areas. Customer-first applies for a home loan after that company validates the customer's eligibility for a loan. The company wants to automate the loan eligibility process (real-time) based on customer detail provided while filling out the online application form.

These details are Gender, Marital Status, Education, Number of Dependents, Income, Loan Amount, Credit History and others. To automate this process, they have given a problem to identify the customer's segments, those are eligible for loan amount so that they can specifically target these customers.

This is a standard supervised classification task. A classification problem where we have to predict whether a loan would be approved or not. 

## Libraries :

*   pandas - used to perform data manipulation and analysis

*   numpy - used to perform a wide variety of mathematical operations on arrays

*   matplotlib - used for data visualization and graphical plotting

*   seaborn - built on top of matplotlib with similar functionalities

*   %matplotlib - to enable the inline plotting.

## Algorithms:

* Logistic regression.
* Decision trees.
* Random forest

### Cross validation is also done to train the models.
   
    * Here, cross-validation will split the data set into multiple parts.

    * For example; cv=5 means, it will split the data into 5 parts.

    * For each iteration, the training will use 4 parts and testing will use 1 part.

    * You can change the cross-validation with the common term 3 or 5.

