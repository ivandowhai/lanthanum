### Back to [Log in and sign up to the portal](../../) feature

# Allow users to sign up using a third-party authentication provider

- [Description](#description)
- [Acceptance criteria](#acceptance-criteria)
- [Mockups](#mockups)
- [Test cases](#test-cases)

## Description

    As a new user
    I want to be able to sign up using a third-party authentication provider

## Acceptance criteria

<pre>
<b><i>Scenario: A new user creates or has an already created personal account on Facebook or Google+</i></b>

Given I have a Facebook or Google+ account

When I visit the <b>Create Account</b> or <b>Log in</b> page
Then I see <b>Google+</b> and <b>Facebook</b> icons above the form

When I select the <b>Google+</b> or <b>Facebook</b> icon
Then I see access confirmation dialog with a confirmation button

When I click <b>Confirm</b>
Then the dialog is closed
  And I see my name provided by selected third-party authentication provider instead of <b>Log in</b> and <b>Log out</b> buttons in the drop-down menu next to my name

When I click the drop-down menu next to my name
Then I see information about the social network I used to sign up
  And I see <b>My surveys</b>, <b>Team hub</b>, and <b>Log out</b>

When I click <b>My surveys</b>
Then I am taken to my <b>My surveys</b> page
  And I see 2 tabs:
    - My surveys
    - Team hub
  And the <b>My surveys</b> tab is active
</pre>

## Mockups

1. Users see the <b>Create Account</b> page
2. Users see the log-in form
3. Registered via third party users see a profile menu
4. Registered via third party users see a profile page

<details>
  <summary>Click here to see mockups details</summary>

**1. Users see the Create Account page:**

![Users see the Create Account page](/products/sport_news_portal/web_application_features/log_in_and_sign_up/images/sing_up_empty_form.png)

**2. Users see the log-in form:**

![Users see the log-in form](/products/sport_news_portal/web_application_features/log_in_and_sign_up/images/log_in_empty_form.png)

**3. Registered via third party users see a profile menu:**

![Registered via third party users see a profile menu](/products/sport_news_portal/web_application_features/log_in_and_sign_up/images/user_profile_menu_for_third_party.png)

**4. Registered via third party users see a profile page:**

![Registered via third party users see a profile page](/products/sport_news_portal/web_application_features/log_in_and_sign_up/images/user_profile_third_party_login.png)

</details>

## Test cases

1. Verify that the user is signed up using Google+ profile
2. Verify that the user is signed up using Facebook profile

<details>
  <summary>Click here to see test cases details</summary>

### **#1. Verify that the user is signed up using Google+ profile**

|Preconditions|Steps|Expected result
------|-------|----------
|- Go to the Sports Hub home page</br>- The user is not logged in to the account</br>- Google+ profile is created|1) Click **Log in**</br>2) Select the **Google+** icon above sign up form</br>3) On the confirmation dialog box, click **Confirm**|3) The dialog box is closed and I see my name provided by Google+ profile|

### **#2. Verify that the user is signed up using Facebook profile**

|Preconditions|Steps|Expected result
------|-------|----------
|- Go to the Sports Hub home page</br>- The user is not logged in to the account</br>- Facebook profile is created|1) Click **Log in**</br>2) Select the **Facebook** icon above sign up form</br>3) On the confirmation dialog box, click **Confirm**|3) The dialog box is closed and I see my name provided by Facebook profile|

</details>
