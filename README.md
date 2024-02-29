This case study aims to identify patterns which indicate if a client has difficulty paying their installments which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. This will ensure that the consumers capable of repaying the loan are not rejected. Identification of such applicants using EDA is the aim of this case study. In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default. The company can utilise this knowledge for its portfolio and risk assessment. To develop your understanding of the domain, it is advised to independently research a little about risk analytics - for understanding the types of variables and their significance should be enough).The 2 datasets used are 'application_data.csv' contains all the information of the client at the time of application. The data is about whether a client has payment difficulties.'previous_application.csv' contains information about the client’s previous loan data. It contains the data whether the previous application had been Approved, Cancelled, Refused or Unused offer.

The data given below contains the information about the loan application at the time of applying for the loan.

-->It contains two types of scenarios:

1.The client with payment difficulties: he/she had late payment more than X days on at least one of the first Y installments of the loan in our sample,

2.All other cases: All other cases when the payment is paid on time.When a client applies for a loan,

-->There are four types of decisions that could be taken by the client/company):

1.Approved: The Company has approved loan Application.

2.Cancelled: The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.

3.Refused: The company had rejected the loan (because the client does not meet their requirements etc.).

4.Unused offer: Loan has been cancelled by the client but on different stages of the process. 

In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
