## This casestudy was analyzed using EDA with a gloal to understand how consumer attributes and loan attributes influence the tendency of default a loan.
 
# Business Understanding
The loan providing companies find it hard to give loans to people due to their insufficient or non-existent credit history.
When the company receives a loan application, the company has to decide for loan approval based on the applicant’s profile. 
Two types of risks are associated with the bank’s decision:

**If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company**

**If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company.**


When a client applies for a loan, there are four types of decisions that could be taken by the client/company):

**Approved:** The Company has approved loan Application

**Cancelled:** The client cancelled the application sometime during approval. Either the client changed her/his mind about the loan or in some cases due to a higher risk of the client he received worse pricing which he did not want.

**Refused:** The company had rejected the loan (because the client does not meet their requirements etc.).

**Unused offer:**  Loan has been cancelled by the client but on different stages of the process.

The analysis aims at finding the patterns that call for the above decission making.

##**You will find the follwing procedure in the analysis**
 1. Data cleaning
     >Looking for NaNs and missing values and treating them appropriately
     >Re-labeling variables for ease of access 
     >re-indexing as needed
     
 2. Obtaining derived variables
    >merging columns by using the aggregate
    >dropping variables with low R-squared value
    
 3. Vizualizations
    > boxplots were used to identify and then drop outliers
    > categorical data was analyzed using barplots
    > numerical data was analyzed using regression
    
 4. Summary
    > conclusions were drawn based on heat-map
