# AmortizationSchedule

This is a simple script for providing the amortization schedule of any loan. It is important to note that the code assumes monthly coupon payments until expiration of the contract
The code simply takes as Python Input from the users 4 inputs:
- Principal: the principal value (face value) of the loan
- Interest rate: the interest rate applied on the principal until maturity (i.e. if 8.02% insert 8.02)
- Expected payment: the monthly payment required by the creditor
- Extra payment: any extra payment the debtor is willing to add to its monthly expected payment (if 0 insert 0)

The code will return a schedule, in the form of a table, for both interest payments and principal repayment.
