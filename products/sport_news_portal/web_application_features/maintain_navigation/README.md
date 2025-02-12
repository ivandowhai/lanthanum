# Maintain navigation on the portal

- [Description](#description)
- [Check list](#check-list)
- [Prototype of the feature](#prototype-of-the-feature)
- [User stories](#user-stories)

## Description

A navigation menu should be visible on every page of the Sports Hub site on the left side. The navigation menu consists of the following menu items:
  - Home
  - News pages configured by admin (e.g. NFL, NBA, Golf, Soccer, etc.)
  - Lifestyle
  - Dealbook
  - Video
  - Team hub

The Home, Lifestyle, Dealbook, Video, and Team hub menu items are static categories.
Site admins can add as many sports categories as they prefer. If there are lots of the sports categories configured, then there should be a scroll bar added to the menu section.

Some of the sports categories have subcategories. Subcategories contain a list of the teams related to them. For example, the NFL sports category consists of the following subcategories: AFC East, AFC North, AFC South. The AFC South contains the following teams: Houston, Indianapolis, Jacksonville, Tennessee.

When users hover over a category in the main navigation menu that consists of the subcategories, this category is highlighted and a drop-down menu with links to the subcategories appears on the UI. When users select the subcategory, they are redirected to the subcategory news page.
When users hover over the subcategory in the secondary navigation menu that consists of the teams, this subcategory is highlighted and a drop-down menu with the list of teams appears on the UI. When users select the team, they are redirected to a team news page.

The Lifestyle, Dealbook, Video, and Team hub menu categories do not have subcategories, so when users hover over one of these categories, only this category is highlighted. When users select one of these categories, they are redirected to the appropriate category news page.
Admin user configures a list of categories, subcategories, and teams visible in the navigation menu.

## Check list:

  - Verify if UI corresponds to the prototype
  - The navigation menu should be present on every page of the Sports Hub site
  - Admin user should be able to configure the navigation menu categories, subcategories, and teams
  - Users should be able to go to the sports subcategory page of the Sports Hub site by using the navigation menu
  - Users should be able to navigate to the team page of the Sports Hub site by using the navigation menu

## Prototype of the feature

_Admin side_

Please click [here](https://www.figma.com/proto/MejavVSuDAMfSDu27O108g/Maintain-Navigation?node-id=0%3A1075&viewport=-177%2C284%2C0.04348461702466011&scaling=min-zoom) to see a clickable prototype.

Please click [here](https://www.figma.com/file/MejavVSuDAMfSDu27O108g/Maintain-Navigation?node-id=0%3A1073) to see mockups that were included in the prototype and additional style guides.

_User side_

Please click [here](https://www.figma.com/proto/MejavVSuDAMfSDu27O108g/Maintain-Navigation?node-id=0%3A2&viewport=210%2C442%2C0.08585662394762039&scaling=min-zoom) to see a clickable prototype.

Please click [here](https://www.figma.com/file/MejavVSuDAMfSDu27O108g/Maintain-Navigation?node-id=0%3A1) to see mockups that were included in the prototype and additional style guides.

## User stories

No           |      Name     |   Details
------------ | ------------- | -------------
1 |[**Allow admin user to create navigation menu items on the portal**](/products/sport_news_portal/web_application_features/maintain_navigation/user_stories/manage_navigation_items)|<pre>As an admin user<br>I want to create the navigation menu categories, subcategories, and teams visible to the site users</pre>
2 |[**Allow admin user to show and hide navigation menu items on the portal**](/products/sport_news_portal/web_application_features/maintain_navigation/user_stories/hide_show_navigation_items)|<pre>As an admin user<br>I want to show and hide the navigation menu categories, subcategories, and teams on the portal</pre>
3 |[**Allow admin user to change order of the navigation menu items and move them between the categories and subcategories**](/products/sport_news_portal/web_application_features/maintain_navigation/user_stories/move_and_order_navigation_items)|<pre>As an admin user<br>I want to change order of the navigation menu items and move them between the categories and subcategories</pre>
4 |[**Allow site users to navigate to the sports categories, subcategories, and teams page on the portal**](/products/sport_news_portal/web_application_features/maintain_navigation/user_stories/navigation_user_side)|<pre>As a site user<br>I want to view the navigation menu on every page of the Sports Hub site<br>So that I can navigate between sports categories, subcategories, and teams news pages</pre>
