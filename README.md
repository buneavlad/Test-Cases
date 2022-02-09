# Test-Cases

**Title:**
Head title

**Description:**
Check if the website have the correct head title

**Steps to Reproduce:**
1. Go to www.fashiondays.ro

**Expected Results:**
The website should have the correct title "Colectii de moda pentru femei";

----------------------------------------------------------------------------


**Title:**
Recover password

**Description:**
Check if you can recover your password with an invalid email

**Steps to Reproduce:**
1. Go to www.fashiondays.ro
2. Go to Login Page
3. Press "Ai uitat parola ?" button
4. Add an invalid email

**Expected Results:**
The website should display a error message

**Test Data:**
email : vladovidiubunea@test.ro

-----------------------------------------------------------------------------

**Title:**
Login with invalid password

**Description:**
Check if you can login with an invalid password

**Steps to Reproduce:**
1. Go to www.fashiondays.ro
2. Go to Login Page
3. Add a correct email and a invalid password

**Expected Results:**
The website should display a error message

**Test Data:**
email : vladovidiubunea@gmail.com, password :12345
