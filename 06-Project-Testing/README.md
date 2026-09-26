# Project Testing

## Project Title
Script-Controlled ACL – Restrict Record Access Based on Field Value

## Test Cases

### Test Case 1 – Read Access
- User with bb1 role can view EEE branch records.
- User without the required role cannot view the records.
- Admin can view all records.

### Test Case 2 – Create Access
- User with bb1 and bb2 roles can create records.

### Test Case 3 – Write Access
- User with bb1, bb2 and bb3 roles can edit EEE records.

### Test Case 4 – Delete Access
- User with bb1, bb2, bb3 and bb4 roles can delete EEE records.

## Expected Result
Access is controlled according to the configured ACL roles and Branch field conditions.
