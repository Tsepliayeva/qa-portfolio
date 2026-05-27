# Login Test Cases

## Test Case 001

### Title
Login with valid credentials

### Preconditions
User account is registered

### Steps
1. Open login page
2. Enter valid email
3. Enter valid password
4. Click Login button

### Expected Result
User successfully logs into account

---

## Test Case 002

### Title
Login with invalid password

### Preconditions
User account is registered

### Steps
1. Open login page
2. Enter valid email
3. Enter invalid password
4. Click Login button

### Expected Result
Error message is displayed

---

## Test Case 003

### Title
Login with empty fields

### Steps
1. Open login page
2. Leave email field empty
3. Leave password field empty
4. Click Login button

### Expected Result
Validation messages are displayed

---

## Test Case 004

### Title
Login with invalid email format

### Steps
1. Open login page
2. Enter invalid email format
3. Enter password
4. Click Login button

### Expected Result
System displays invalid email format message

---

## Test Case 005

### Title
Password field hides entered characters

### Steps
1. Open login page
2. Enter password into password field

### Expected Result
Password characters are hidden
