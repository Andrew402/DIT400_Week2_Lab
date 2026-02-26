___________Part 1____________________
#Question 1
-1st accountnumber with String datatype
-2nd ownername with String datatype
-3rd Balance with double datatype

#Question 2
-double getbalance(){return balance}
-its returns the Balance avaibale and the type is double


#Question 3
-void deposit() adds money to the account and does return anything while double getBalance does do anything it just returns the current balance

____________Part 2___________________
#Question 4
-K1500 stays the same
-Each account has its own money. Putting money in acc1 doesn't affect acc2's money. They are separate.

#Question 5
-new creates the actual object in the computer's memory

#Question 6
-The dot connects an object to its method

____________Part 3___________________________
#Question 7
- @Test is an annotation that tells JUnit "this method is a test case" - it's how JUnit knows which methods to run as tests.

#Quesion 8
- assertEquals(1500.00, account.getBalance()) checks if the actual balance returned by getBalance() matches the expected value of 1500.00. If they're equal, the test passes.

#Question 9
- If test 1 fails with that message, it means after depositing 500 into an account with 1000, the balance is still 1000 - so deposit() isn't actually adding money to the balance