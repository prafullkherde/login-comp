# API Contracts

## POST /auth/register
Request: { identity, secret }
Responses: success | 400 | 409

## POST /auth/login
Request: { identity, secret }
Response: { token, expiresAt }
Errors: 401

## POST /auth/logout
Headers: Authorization
Response: logged_out

## /protected/*
Headers: Authorization
Errors: 401 | 403
