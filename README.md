# SFG_Practice_SecureLoanRequest
This is a practice app for an SAAS to get a bank loan approval
The layout of this app is as follows:
1. An SAAS application to UI into for Loan Requests and usual User setup of accounts. This will be a Spring Boot
application using Apache embedded website.
2. A database using Hibernate/JPA and MySql to hold user info. Preferrable, this should me a microservice with a bounded context for User only. More context to follow.
3. Encryption/Decription will be used to pass JSON encoded information to several external banks that will process the loan requests.
4. External banks (In this case three) that will decrypt the info and determine if the loan is approved. Return decision will also be encrypted back in JSON to the SAAS.
