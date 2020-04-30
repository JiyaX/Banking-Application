# Banking-Application


1. We need an application to handle New Bank Account requests.

 We will have a application that will read a CXXVI file that will include names, Social Security numbers,the account type and initial deposit.

There's our social security number in column number 2.

Then we have in the third column either a savings account or a checking account.

And then our last parameter the last field is the initial deposit.

2. We should be able to deposit, transfer, withdraw and showinfo in both the types of accounts.

  Both will have an 11 digit account number generated. It will start with the one or two depending on whether it's a savings account a checking account. Then we're going to have the last two digits of the Social Security number, a unique five digit number and a random three digit number.

3. Savings account holders are given a safety deposit box and that's identified by a 3 digit number and access with the four digit code.

4. Checking account holders are assigned a debit card with a 12 digit number and a four digit PIN.

5. Both accounts will use an interface that determines the base interest rate. So we're going to gather this information from some API.
Now we will be the ones that will write the API. In our case our bank says that our savings account will use point to five points less than the base rate and our checking accounts will use 15 percent of the base rate.

6. Lastly the show info method should reveal relevant information as well as information specific to the checking account or savings account.
