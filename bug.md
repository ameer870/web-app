# Bug Report

## Bug ID:
BUG-001

## Title:
Login succeeds with wrong password

## Description:
Login function allows access even with incorrect password.

## Steps to Reproduce:
1. Run login.js
2. Enter username: admin
3. Enter wrong password

## Expected Result:
System should display "Login Failed"

## Actual Result:
System displays "Login Success"

## What User Was Doing:
Trying to login with incorrect password

## Impact:
Security issue – unauthorized access possible
