# Transaction Analysis Challenge

This repository contains the solution to the transaction analysis challenge. The challenge involved analyzing customer transaction data to extract meaningful insights.

## Technologies Used
- **Python 3.12.17**
- **Pandas** for data manipulation
- **Matplotlib** for data visualization

## Challenge Overview
The dataset consists of two tables:

### Customers Table (TbCliente)
| CD_CLIENTE | NM_CLIENTE |
|------------|------------|
| 1          | João       |
| 2          | Maria      |
| 3          | José       |
| 4          | Adilson    |
| 5          | Cleber     |

### Transactions Table (TbTransacoes)
| CD_CLIENTE | DT_TRANSACAO | CD_TRANSACAO | VR_TRANSACAO |
|------------|--------------|--------------|--------------|
| 1          | 2021-08-28   | 000 (CashBack) | 020.00       |
| 1          | 2021-09-09   | 110 (CashIn)   | 078.90       |
| 1          | 2021-09-17   | 220 (CashOut)  | 058.00       |
| ...        | ...          | ...            | ...          |

## Analysis Performed
- Identified the customer with the highest average balance in November.
- Calculated the balance for each customer.
- Computed the average balance of customers who received cashback.
- Determined the average ticket size of the last four transactions per user.
- Analyzed the proportion between Cash In and Cash Out per month.
- Retrieved the last transaction of each type for each user.
- Counted the number of users who made transactions.
- Assessed the financial balance at the end of 2021.
- Investigated user engagement after receiving cashback.
- Identified the first and last transaction for users with a balance greater than R$100.
- Evaluated the balance of the last four transactions per user.
- Visualized key insights using three graphs.

## Results
The analysis was successfully completed, and the results were visualized using **Matplotlib**. The findings provide insights into customer transactions and financial behaviors.