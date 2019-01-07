# Applied-AI-Decision-Network

Loan Repayment Decision system is a combination of Bayesian Network and influence Diagram designed using NETICA wherein information of different type of loan applicants and types of loan is asserted by the user of the Bank, and finally concludes whether applicant will be to repay loan or not.Accurately predicting whether a loan will be repaid (credit" scoring) is an important task for any bank.Furthermore, the decision regarding the deadline if it needs to be extended or not is made using the utility and decision node in influence diagram. High accuracy benefits both the banks and the loan applicants.

# FEATURES:

1.	The created is designed for a generic credit scoring scenario using 20 nodes.

2.	Nodes within the net are based upon the intuition.

3.	The resultant network had 12 evidence variables which do not depend on any   external nodes and have their prior probabilities feed, feeding into 6 inner nodes,   which, in turn, feed into the outcome node, LoanRepaid.

4.	The inner nodes serve two purposes: they group data into qualitative conceptual   categories, making interpretation of the BayesianNetwork easier, and they reduce the size of the CPTs in the network (via “divorcing”). However, even when using these inner nodes, the CPT was still too large to fill in manually.

5.	CPT i.e conditional probability table for each independent variable were used by Netica to generate the CPTs for dependent variables.

6.	The node, IndividualCreditworthiness, used a weighted average of its parents.

7.	Note: While some of the probabilities are as close to reality as possible, many have been formulated with hypothesizing and following the general trend defined by   banks.

8.	Most important variables like IndividualCreditWorthiness and FinancialStability   decides the posterior probabilities of every other factors.

9.	The decision node “Deadline_Extension” is a parameter used to define if the extension is to be given after deadline for the loan repayment.

10.	The utility node “Existing_Credit_WithBank” is used to model the change in the utility value for the deadline_extension node. It depends on the factors like “loan_duration” and “loan_purpose”.
 
