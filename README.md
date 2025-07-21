## MULLA-LITE
- This is a mini app simulating a mobile money service that puts into practice and tests out system design concepts.

### FEATURES
Users can be able to
- Register for the service
- Deposit money
- Check balance
- Send money
- Receive money
- Pay for service

### APIs
- register account (ID, FirstName, LastName, Email, YOB, Mobile)
- deposit money (ID, mobile, amount)
- check balance (mobile, amount)
- send money (mobile, amount to send)
- receive money (amount received, old balance, new balance)
- pay for service (amount to pay, service number, old number, new number)

### DATA MODELS
- USERS
- TRANSACTIONS

### EDGE CASES TO HANDLE
1. Valid data when registering
2. Limit on send receive and deposit amounts
3. Can't send more than balance
4. Can't receive more than balance
5. Valid recipients and services

### STACK
- Go for APIs
- DB to be decided.