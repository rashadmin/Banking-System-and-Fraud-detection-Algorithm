# Banking-System-and-Fraud-detection-Algorithm

## Problem
Build a banking system that:
i. Creates user accounts
ii. Receives Deposits
iii. Withdrawals
iv. Fraudulent Detection

## Project Descripton
This project was part of the CSA Africa bootcamp requirement for the fulfilment of the successful completion of the workshop.. A group of 4 colloborated together to create this. 
We used the divide and conquer rule by dividing the problem into two; first part being creating bank classes. These bank classes were used to create bank user objects 
where we stored information like personal details then generated 10 digit random account number addded deposits and withdrawals as methods.
The second part was creating a check_for_fraud function which uses the count sorting algorithm (was tweaked to our taste), the function sorts previous transactions in
ascending order, then compare their median with the next transaction. If the next transaction is greater than the median of previous transactions then the bank owner
gets an alert that this could be a possible fraudulent transaction and list out the transactions that were flagged.
