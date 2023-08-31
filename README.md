# ATM App
This app allows a user to deposit money in a fictional account and withdraw money from that same account. If the user attempts to withdraw more money than the account balance, the "Submit" button is disabled. 

### Changes made
I grew weary of hearing Dr. Williams say "ATM machine", which is, of course, redundant. I changed the heading of the app from this redundancy to simply "Automated Teller Machine." I created a formatted account balance with a thousands separator using the following: `const formattedTotalState = totalState.toLocaleString();`. The variable `formattedTotalState` was then passed to the "<h2>" tag in the `return` function of the JSX file. 
