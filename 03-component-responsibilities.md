# Component Responsibilities

## Auth API
- Input validation
- Error normalization
- Delegation only

## Authentication Engine
- Credential verification
- Password hash comparison

## Identity Store
- User persistence
- Password hash storage

## Token Manager
- Token issue, validation, invalidation

## Authorization Gate
- Enforce access control
- Block unauthorized requests
