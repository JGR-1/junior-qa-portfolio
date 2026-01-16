# Password recovery reveals whether an email adress is registered

Bug type:
- Security / Information Disclosure

Severity:
- Medium

Priority:
- Medium

Steps to reproduce:
- Navigate to login
- Click "Forgot your password?"
- Enter a registered email adress
- Submit the request
- Repeat the process using an unregistered email adress


Actual result:
- System displays different messages depending on wheter the email exists or not

Expected result:
- System should return a generic message to prevent account enumeration

Source: https://mega.nz/recovery
