# Habit Tracker User Story

## 1. Login/Registration page

1. **Account registration:**
_As a new user, I want to register with my name, username, age, and country so that I can create an account and access the habit tracking features._

2. **Account login:**
_As an existing user, I want to log in using my username and password so that I can access my account and track my habits._

3. **Error feedback on login:**
_As an exisitng user, I want to receive a message if I enter the wrong username or password so that I know my login attempt was unsuccessful._

**Acceptance Criteria:**

1. A new user is able to enter name, username, password, age and country.
2. An existing user is able to enter their username and password.
3. An exisitng user if provided the incorrect user name and password is shown the appropriate error message.
   

**Priority:** High

**Story Points:** 3

**Notes:**
- The user is able to register; however, due to security constraints, the credentials are not saved in the browser cache but are removed once the user logs out. Therefore, the user is unable to log in with their own credentials. The only way to log in is with the default username and password.
