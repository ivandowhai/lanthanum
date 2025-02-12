# User management on the portal

- [Description](#description)
- [Check list](#check-list)
- [Prototype of the feature](#prototype-of-the-feature)
- [User stories](#user-stories)

## Description

We allow users to register in our application. We need a place where we can review and manage a list of users if needed. This should be available on the admin side. In the list we can review users’:
  - Profile picture
  - First and last name
  - Status: active, blocked
  - Online/offline availability
  - Role: user and admin
  - Amount of users and admins

We want to do the following actions to the user accounts:
  - <i>Delete</i> ⁠– the user should be removed from the system and not have the ability to log in to the system.
  - <i>Block</i> ⁠– the user should be blocked which means the user will not be able to comment on any article or video. Users should be notified about this action.
  - <i>Activate</i> ⁠– only blocked users can be activated. Users should be notified about this action.
  - <i>Make as admin</i> ⁠– the user will receive admin permissions. Users should be notified about this action.
  - <i>Remove from admins</i> ⁠– removes admin permission from the user. Users should be notified about this action.

## Check list:

  - Admin should be able to delete users
  - Admin should be able to block users
  - Admin should be able to activate users that were blocked
  - Admin should be able to give admin permissions to users
  - Admin should be able to remove admin permission from users
  - Users should be able to receive emails that inform them about admin’s actions

## Prototype of the feature

Please click [here](https://www.figma.com/proto/8nNZGVmkZ2ukXV7NhmawgO/User-Management?node-id=0%3A1075&viewport=-111%2C560%2C0.05949114263057709&scaling=min-zoom) to see a clickable prototype.

Please click [here](https://www.figma.com/file/8nNZGVmkZ2ukXV7NhmawgO/User-Management?node-id=0%3A1073) to see mockups that were included in the prototype and additional style guides.

## User stories

No           |      Name     |   Details
------------ | ------------- | -------------
1 |[**Allow admin user to view user management page on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/create_user_management_page_on_the_admin_side)|<pre>As an admin user<br>I want to have a place with the list of users<br>So that I can review and manage them</pre>
2 |[**Allow admin user to delete users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/delete_user)|<pre>As an admin user<br>I want to be able to delete users<br>So that they do not have an account to log in to the system</pre>
3 |[**Allow admin user to block users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/block_user)|<pre>As an admin user<br>I want to be able to block users<br>So that they won’t have access to comments</pre>
4 |[**Allow admin user to activate users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/activate_user)|<pre>As an admin user<br>I want to be able to activate users<br>So that they will have access to comments</pre>
5 |[**Allow admin user to give user admin permissions on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/give_user_admin_permissions)|<pre>As an admin user<br>I want to be able to give active users admin permissions</pre>
6 |[**Allow admin user to remove admin permissions from users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/remove_admin_permissions_from_the_user)|<pre>As an admin user<br>I want to be able to remove admin permissions from users</pre>
7 |[**Allow admin user to view online/offline status of users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/view_online_offline_status_of_the_users)|<pre>As an admin user<br>I want to see if users are online/offline</pre>
8 |[**Allow admin user to filter users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/filter_users)|<pre>As an admin user<br>I want to be able to filter users based on criteria<br>So that I can perform the needed action</pre>
9 |[**Allow admin user to search users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/search_users)|<pre>As an admin user<br>I want to be able to search users by name</pre>
10 |[**Send notification emails to users on the portal**](/products/sport_news_portal/web_application_features/user_management/user_stories/send_notification_emails_to_the_user)|<pre>As a site user<br>I want to receive notification in my email<br>So that I know if I was blocked, activated, got/lost admin permissions</pre>
