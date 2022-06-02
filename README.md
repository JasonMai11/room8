# Room8 [iOS app]
An iOS app that resolves issues of dividing the debt between roomates.

The following **required** functionality is completed:

- [] App Design
- [] Login Page
- [] Ability to Logout
- [] DataBase that holds account information
- [] 
- [] 
- [] 

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![] TBD

## User Stories (Part 1)

The following **required** functionality is completed:

- [] Users can sign in and sign out for the app.
- [] Added some more functionality for posting.

## Video Walkthrough

Here's a walkthrough of implemented user stories:


## User Stories (Part 2)

The following **required** functionality is completed:

- [X] Users can logout for the app.
- [X] Post creation screen is made.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![] TBD


## User Stories (Part 3)

The following **required** functionality is completed:

- [] Users can sign up for the app.
- [] Parse server configured for sign ups.

## Video Walkthrough
Here's a walkthrough of implemented user stories:
![]


Original App Design Project - README Template
===

# Room8 (Placeholder)

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Room8 is an app that allows ...

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** ...
- **Mobile:** ...
- **Story:** ...
- **Market:** ...
- **Habit:** ...
- **Scope:** ...

## Product Spec

### 1. Business Problem and User Base
What problem are you solving and who will use the solution?


### 2. Description
What will the app do?

### 3. User Stories

**Required User Stories**

* Users can create accounts
* Users can login
* Users can upload photos
* Users can search for notes?
* Users can like notes
* Users can follow/unfollow courses they're in
* Users can view a feed of notes

**Optional User Stories**

* Users can leave comments under notes
* Users can tap photos to see more details about notes
* Users can search up notes
* User can be notified for when their notes are liked
* Users can upload due dates for current semester on the side

### 2. Screen Archetypes

What screens will the user see?


### 3. Navigation

**Flow Navigation** (Screen to Screen)

* (Examples) 
    * Launch Screen
        * Login/Register
            * Navigation/Main Screen
            * Can look at notes on here, post notes or look up courses
               * Creation Screen
               * Post Notes Here

## Wireframes
![Screen Shot 2021-11-01 at 10 24 31 PM](https://user-images.githubusercontent.com/70527398/139776584-7c549243-19ea-49ea-852d-0391ecf926e0.png)


## Schema 
[This section will be completed in Unit 9]
### Models
| Property      | Type     | Description |
   | ------------- | -------- | ------------|
   | User          | String   | unique id for the user (default field) |

   
### Networking
- [Add list of network requests by screen ]
- #### List of network requests by screen
   - Home Feed Screen
      - (Read/GET) Query all posts of users/courses that user follows  
      - (Create/POST) Create a new like on a post
      - (Delete) Delete existing like
   - Create Post Screen
      - (Create/POST) Create a new post object
   - Profile Screen
      - (Read/GET) Query logged in user object
      - (Update/PUT) Update user profile image [Create basic snippets for each Parse network request]
      - (Read/GET) Query all posts where user is author
   - Navigation Screen
      - (Read/GET) Query all posts of topic/course/content user searched for
      -  
