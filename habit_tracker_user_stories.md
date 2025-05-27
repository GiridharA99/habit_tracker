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
   

**Priority:** Medium

**Story Points:** 3

**Notes:**
- The user is able to register; however, due to security constraints, the credentials are not saved in the browser cache but are removed once the user logs out. Therefore, the user is unable to log in with their own credentials. The only way to log in is with the default username and password.

## 2. Homepage

1. **View welcome message:**
_As a user, I want to see a personalized welcome message with my name on the homepage, so that I feel recognized and can confirm I am logged into the correct account._

2. **Display weekly progress:**
_As a user, I want to see my daily progress for each habit on the homepage, so that I can easily monitor my progress._

3. **View completed habits:**
_As a user, I want to see a section for completed habits on the homepage, so that I can track what I have already achieved._

**Acceptance Criteria:**

1. The user is shown a personalized welcome message with their name on the homepage.
2. The user is able to see their daily progress for each habit on the homepage.
3. The user is able to see a section that shows the completed habits on the homepage.
   

**Priority:** High

**Story Points:** 8

**Notes:**
- The user is shown completed tasks only if they were previously completed by the user.
