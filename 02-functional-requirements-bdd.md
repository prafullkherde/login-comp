# Functional Requirements (BDD)

## R1 Registration
Given a new user
When valid credentials are provided
Then a user is created securely

## R2 Login
Given an existing user
When correct credentials are provided
Then authentication succeeds and token is issued

## R3 Token
Given successful login
Then token is verifiable and expires

## R4 Protected Access
Given valid token
When accessing protected resource
Then access is allowed

## R5 Logout
Given authenticated user
When logout is called
Then token becomes invalid

## R6 Invalid Access
Given invalid or missing credentials
Then access is rejected safely
