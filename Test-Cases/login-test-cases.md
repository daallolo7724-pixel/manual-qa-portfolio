
# Login Functionality - Test Cases

## TC-001: Login with valid credentials

**Objective:** Verify that a registered user can log in successfully.

**Preconditions:**
- User has an active account.
- Login page is accessible.

**Test Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter a valid password.
4. Click Login.

**Expected Result:**
The user successfully logs in and is redirected to the homepage.

**Priority:** High

---

## TC-002: Login with incorrect password

**Objective:** Verify that the system rejects incorrect passwords.

**Preconditions:**
- User has an active account.

**Test Steps:**
1. Open the login page.
2. Enter a valid email.
3. Enter an incorrect password.
4. Click Login.

**Expected Result:**
The system displays an appropriate error message and denies access.

**Priority:** High

---

## TC-003: Login with empty fields

**Objective:** Verify that the system validates required fields.

**Test Steps:**
1. Open the login page.
2. Leave email and password empty.
3. Click Login.

**Expected Result:**
The system displays validation messages and does not allow login.

**Priority:** Medium

---

## TC-004: Login with invalid email format

**Objective:** Verify email format validation.

**Test Steps:**
1. Open the login page.
2. Enter an invalid email format.
3. Enter a password.
4. Click Login.

**Expected Result:**
The system displays an email validation message.

**Priority:** Medium
