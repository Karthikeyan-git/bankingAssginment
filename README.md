# bankingAssginment
simple console application replication banking system


creata a Java application to replicate typical banking operations
Below are the entities of the application
1.Account
2.AccountHolder
3.BankManager
4.Transaction

Properties of Account:
  1.Account Number
  2.Account Balance
  3.Minimum Balance
  4.AccountHolderID
  
Properties of AccountHolder:
  1.AccountHolderID
  2.AccountHolderName
  3.AccountHolderPhoneNumber
  
Properties of Transaction:
  1.AccountNumber
  2.Transaction Type -> possible values - credit, debit
  3.Transction Status
  4.Transaction Amount
  5.Transaction Date
  
Use cases:
1. Create Account
2. Delete Account
3. Deposit amount to an account (credit)
4. Withdraw amount from an account (debit), a warning message to be displayed when the balance is less than minimum balance after withdrawal
