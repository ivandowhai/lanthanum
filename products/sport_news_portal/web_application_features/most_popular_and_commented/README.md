# The most popular and commented articles on the portal

- [Description](#description)
- [Check list](#check-list)
- [Prototype of the feature](#prototype-of-the-feature)
- [User stories](#user-stories)

## Description

When users are viewing pages that contain the <b>Most popular</b> and <b>Most commented</b> sections, they should be able to see articles that have the highest number of views (<b>Most popular</b>) or the highest number of comments (<b>Most commented</b>) during the period configured by admin. The <b>Most popular</b> and <b>Most commented</b> sections should be context-sensitive:
  - Home page contains the most popular and most commented articles from the whole articles list
  - Any other page contains the most popular and the most commented articles that belong to the same category, conference, or team as the current page

Admin user can show or hide the <b>Most popular</b> and <b>Most commented</b> sections on the <b>Home</b> configuration page.
Admin user can configure the time period for the <b>Most popular</b> and <b>Most commented</b> sections

## Check list:

  - Verify if UI corresponds to the prototype
  - Admin user should be able to show and hide the <b>Most popular</b> section for the whole site
  - Admin user should be able to configure the time period (Day, Weak, Month, Year) for the <b>Most popular</b> section
  - Admin user should be able to show and hide the <b>Most commented</b> section
  - Admin user should be able to configure the time period (day, weak, month, year) for the <b>Most commented</b> section
  - User should be able to see articles with the highest number of visits during the period configured by admin in the <b>Most popular</b> section
  - User should be able to see articles with the highest number of comments during the period configured by admin in the <b>Most commented</b> section

## Prototype of the feature

Please click [here](https://www.figma.com/proto/BpGy9tY0mE6hfw0hUN2Qeb/Home-Page?node-id=0%3A1074&viewport=-659%2C447%2C0.10292607545852661&scaling=min-zoom) to see a clickable prototype.

Please click [here](https://www.figma.com/file/BpGy9tY0mE6hfw0hUN2Qeb/Home-Page?node-id=0%3A1073) to see mockups that were included in the prototype and additional style guides.

## User stories

No           |      Name     |   Details
------------ | ------------- | -------------
1 |[**Allow admin user to configure the Most popular section**](/products/sport_news_portal/web_application_features/most_popular_and_commented/user_stories/most_popular_configuration)|<pre>As an admin user<br>I want to configure the <b>Most popular</b> section</pre>
2 |[**Allow admin user to configure the Most commented section**](/products/sport_news_portal/web_application_features/most_popular_and_commented/user_stories/most_commented_configuration)|<pre>As an admin user<br>I want to configure the <b>Most commented</b> section</pre>
3 |[**Allow site users to view the most popular articles**](/products/sport_news_portal/web_application_features/most_popular_and_commented/user_stories/most_popular)|<pre>As a site user<br>I want to view the <b>Most popular</b> section<br>So that I can read articles that have the highest number of views in the period configured by admin (day, week, month, year)</pre>
4 |[**Allow site users to view the most commented articles**](/products/sport_news_portal/web_application_features/most_popular_and_commented/user_stories/most_commented)|<pre>As a site user<br>I want to view the <b>Most commented</b> section<br>So that I can read articles that have the highest number of comments in the period configured by admin (day, week, month, year)</pre>
