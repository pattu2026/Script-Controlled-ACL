# Project Design

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Table Design
Table: Institution Details
Table Name: u_institution_details

## Fields
- Student Roll Number – Auto Number
- Student Name – Reference: User
- Faculty Name – Reference: User
- Branch – Choice: ECE, EEE, CSE
- Email – String
- Phone Number – String
- Description – Multi String

## ACL Design
The project uses four record-level ACL operations:

1. READ – bb1 role
2. CREATE – bb2 role
3. WRITE – bb3 role
4. DELETE – bb4 role

## Access Logic
- Admin users have full access.
- EEE users with the required role can access EEE records.
- Other users are restricted according to the ACL rules.
