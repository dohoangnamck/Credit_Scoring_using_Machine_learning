# Credit Risk Assessment Using Machine Learning Techniques
Ensemble CREDIT SCORING method using LOGISTIC REGRESSION, SVM, DECISION TREE and XGBOOST algorithm 

Credit is a must in financial systems. For all financial institutions, whose role is to allocate credit, it is necessary to fully understand the risk behind it and to correctly decide who to give credit and who not. To do so, they make use of credit scoring, which is one of the most successful application of statistical and operational research modelling in finance.

The aim of this thesis is to combine supervised and unsupervised machine learning models to predict the probability of default of a set of individuals who asked a loan to a bank, and to correctly classify them according to their individual propensity to default.

## Data Set Description
A significant problem for credit scoring models which must be pointed out is the unavailability of real-world credit data. The reason is that customer’s credit data is confidential in most of the financial institutions. For these reasons we will use a public data set from Kaggle.

Kaggle is an online community of data scientists and machine learning pratictioners that offers machine learning competitions and a public data platform.

The data set contains information on clients who have taken out a loan with
an unspecified financial institution. The aims of the analysis is to search for
statistical relationships that could give us some insights about the the risk
of credit and to develop some algorithms to predict credit default. Given
that the context of the data set is not fully explained, we are not going to
take into account external macroeconomic events, which could completely
change the results of the analysis. For instance, different countries could
have different loan’s requirement, or different phases of the economic cycle
could end up in a very different scenario.

Another important fact to which one must draw attention is that we will
assume the data set to be not distorted by a credit score system. This
means that no systematic screening of the costumers’ credit standing had
been implemented until the date of data retrieval.

The data set contains 12 attributes and 32581 observations, and its structure is resumed in Table below.
The potential covariates describe both customers and loans characteristics. As we can see there are both numerical and categorical variables. Let us see a little more in details which are the levels of the categorical ones.
![](https://i.imgur.com/JPlfCww.jpg)
* person_home_hownership has four levels: Mortage, Own, Rent and
Others
* loan_intent has six different levels: Debt consolidation, Education,
Home improvement, Medical, Personal, Venture
* loan_grade has seven levels: A, B, C, D, E, F, G. Th grade takes
into account a combination of several indicators of credit risk from the
credit report and loan application. These factors may include the level
of guarantor support, repayment history, cash flow, projected yearly expenses, etc.
* cb_person_default_on_file has only two level: Y if the client has
already had a default, N otherwise
* loan_status is the response variable and has two levels: 0 represent
non default, 1 represent default.

