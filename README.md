# Predicting-the-effectiveness-of-bank-marketing-campaigns

![image](https://user-images.githubusercontent.com/102027932/188068220-2b739b6a-d889-4958-879a-2d4df4609e3a.png)



Data Set Information:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed.

The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

data
1. age (numeric)

2. job : type of job (categorical: ‘admin.’,’blue-collar’,’entrepreneur’,’housemaid’,’management’,’retired’,’self-employed’,’services’,’student’,’technician’,’unemployed’,’unknown’)

3. marital : marital status (categorical: ‘divorced’,’married’,’single’,’unknown’; note: ‘divorced’ means divorced or widowed)

4. education (categorical: ‘basic.4y’,’basic.6y’,’basic.9y’,’high.school’,’illiterate’,’professional.course’,’university.degree’,’unknown’)

5. default: has credit in default? (categorical: ‘no’,’yes’,’unknown’)

6. housing: has housing loan? (categorical: ‘no’,’yes’,’unknown’)

7. loan: has personal loan? (categorical: ‘no’,’yes’,’unknown’)

8. contact: contact communication type (categorical: ‘cellular’,’telephone’)

9. month: last contact month of year (categorical: ‘jan’, ‘feb’, ‘mar’, …, ‘nov’, ‘dec’)

10. day_of_week: last contact day of the week (categorical: ‘mon’,’tue’,’wed’,’thu’,’fri’)

11. duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y=’no’). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

12. campaign: number of contacts performed during this campaign and for this client (numeric, includes last contact)

13. pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

14. previous: number of contacts performed before this campaign and for this client (numeric)

15. poutcome: outcome of the previous marketing campaign (categorical: ‘failure’,’nonexistent’,’success’)



---> Analyzed the prior marketing campaigns of a Portuguese Bank using various ML techniques like Logistic Regression, Random Forests, Decision Trees, Gradient Boosting and AdaBoost and predicted if the user will buy the Bank’s term deposit or not

---> Recommended, the marketing team, ways to better target customers using feature importance maps and business intuition

---> Instructions to run the code:

Make sure the data file ("bank-additional-full.csv") is in the same directory as the ipython notebook or edit the ipython notebook accordingly.
Make sure to run the notebook in python 3 environment. Make sure all the dependencies used in the notebook are installed in the local machine.
Run the code sequentially as given in the notebook.
Notebook is commented adequately to give the rational, inferences of the executed code.

CON  

