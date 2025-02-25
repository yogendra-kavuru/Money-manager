A React-based Money Manager application that helps users track their income, expenses, and overall balance.

Features

Initially, the Balance Amount, Income Amount, and Expenses Amount are set to 0.

The Balance Amount is calculated as:

totalBalance = totalIncome - totalExpenses

The Income Amount is updated based on the sum of income transactions.

The Expenses Amount is updated based on the sum of expense transactions.

Users can add transactions by providing a title, amount, and selecting a transaction type (Income or Expense).

The transaction history updates dynamically as transactions are added or removed.

Users can delete transactions, and the balance updates accordingly.

The MoneyManager component is provided with transactionTypeOptions, consisting of objects with the following properties:

optionId (String)

displayText (String)

Initially:

The titleInput and amountInput are empty.

The first option in transactionTypeOptions is selected.

After adding a transaction:

The transaction is added to the history.

Total Balance, Total Income, and Total Expenses are updated.

The input fields reset to their initial values.

Deleting a transaction updates the balance accordingly.
