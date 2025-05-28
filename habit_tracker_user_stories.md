# Habit Tracker User Story

## 1. Login/Registration Screen

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

**Story Points:** 5/10

**Notes:**
- The user is able to register; however, due to security constraints, the credentials are not saved in the browser cache but are removed once the user logs out. Therefore, the user is unable to log in with their own credentials. The only way to log in is with the default username and password.

## 2. Home Screen

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

**Story Points:** 8/10

**Notes:**
- The user is shown completed tasks only if they were previously completed by the user.

## 3. Settings Menu

1. **Access menu options:**
_As a user, I want to access a menu with options for configuring my habits, viewing reports, editing my profile, and signing out, so that I can easily navigate to different parts of the app._

2. **Navigate to profile:**
_As a user, I want to access a menu with options to view and edit my profile._

3. **Navigate to habits page:**
_As a user, I want to access the habits page from the menu, so that I can configure and manage my habits._

4. **Sign out from menu:**
_As a user, I want to sign out of my account using an option in the menu, so that I can securely log out when I'm finished using the app._

**Acceptance Criteria:**

1. The user is shown a menu with the option to configure habits, view reports.
2. The user is able to view and edit their profile.
3. The user is able to access the habits page from the menu.
4. The user is able to sign out of the account from the menu.
   

**Priority:** Medium

**Story Points:** 6/10


  ## 4. Profile Page

1. **View personal information:**
_As a user, I want to view my saved name, username, age, and country on my profile page, so that I can see the details I provided during registration._

2. **Edit personal information:**
_As a user, I want to update my name, username, age, and country on my profile page, so that I can keep my information up to date._

3. **Save updated information:**
_As a user, I want the changes I make to my profile to be saved, so that my updated details are stored and reflected throughout the app._

4. **Update name in header:**
_As a user, I want my updated name to be displayed in the app's header after I change it in the profile, so that my changes are immediately visible._

**Acceptance Criteria:**

1. The user is able to view saved profile information which includes name, username, age and country.
2. The user is able to update the saved profile information which includes name, username, age and country.
3. The user is able to save the updated information.
4. The user is able to update the name shown in the app header.
   

**Priority:** Medium

**Story Points:** 4/10

  ## 5. Details Screen

1. **Add a new habit:**
_As a user, I want to add new habits on the details configuration page so that I can manage and update my habits as needed._

2. **Delete a habit:**
_As a user, I want to delete existing habits so that I can keep my habits up to date._

3. **Personalize a habit with color:**
_As a user, I want to assign a specific color to each habit to make it personal to me._


**Acceptance Criteria:**

1. The user is able to add a new habit.
2. The user is able to delete an entered habit.
3. The user is able to personalise a habit with a color.
   

**Priority:** Medium

**Story Points:** 7/10

  ## 6. Reports Page

1. **View weekly reports:**
_As a user, I want to see a report of my weekly habit progress so that I can understand how well I am maintaining my habits._

2. **Visualize completed habits:**
_As a user, I want to see a chart of my completed habits for each day of the week so that I can quickly identify trends in my progress._

3. **View all habits:**
_As a user, I want to see both completed and incomplete habits in my report so that I have a comprehensive view of my habit tracking performance._


**Acceptance Criteria:**

1. The user is able to view weekly habit progress.
2. The user is able to view completed habits.
3. The user is able to view all habits including completed and incompleted ones.
   

**Priority:** Low

**Story Points:** 5/10

  ## 7. Notifications Screen

1. **Enable/disable notifications:**
_As a user, I want to be able to enable or disable notifications for the app, so that I can choose whether or not to receive reminders for my habits._

2. **Add habits for notifications:**
_As a user, I want to select specific habits to receive notifications for, so that I only get reminders for the habits I am actively working on._

3. **Set notification times:**
_As a user, I want to have the option to receive notifications three times a day (morning, afternoon, evening) for all selected habits, so that I get timely reminders throughout the day to complete my habits._


**Acceptance Criteria:**

1. The user is able to enable and disable notifications.
2. The user is able to add notifications to the habit of their choice.
3. The user is able to set the time when notifications are received to morning, afternoon, evening.
   

**Priority:** Low

**Story Points:** 3/10

## 8. Persistant Data

1. **Save Habits to Storage:**
_As a user, I want to be able to save habits to local storage so that the habit is available when I login again._

2. **Save Login Information:**
_As a user, I want to save login information to storage so that the next time I do not require to sign up again._

3. **Save settings preferences:**
_As a user, I want to save my settings preferences so that it stays as confiured with each use._


**Acceptance Criteria:**

1. The user is able to save habits information to storage.
2. The user is able to save login infornation to storage.
3. The user is able to settings intormation to storage.
   

**Priority:** Low

**Story Points:** 4/10

## 9. Integrate External API

1. **Store Habit information to External Storage using APIs:**
_As a user, I want to be able to save habits to external storage so that the habit is available across multiple devices._

2. **Save Login Information to External Storage using APIs:**
_As a user, I want to save login information to storage so that I can login to different device with same credentials._

3. **Save settings preferences to External Storage using APIs:**
_As a user, I want to save my settings preferences so that it stays as confiured across all devices I login to._


**Acceptance Criteria:**

1. The user is able to save habits information to external storage using API.
2. The user is able to save login infornation to external storage using API.
3. The user is able to settings intormation to external storage using API.
   

**Priority:** Low

**Story Points:** 4/10


