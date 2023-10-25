# Tuiter App

#### Group members:
Abdulrahman Isegen, Ernest Gurish, Meet Vora, Prinjal Dave


## Summary
                                 
We would like to implement the Bookmark feature and administration tools. Users can bookmark or unbookmark a tuit, view all Tuits they have bookmarked, and create, update, and delete their account. Administrators can view, create, update, and delete user accounts. Therefore, we will implement different User roles which are general users and administrators. Both types of users need to create their accounts by selecting different roles. Different types of users will have different views and access when logged in. Users can only view their own profile page, but administrators have access to all user’s profile pages and would be able to modify user accounts.

## User stories

Story 1: As a User, I would like to create, update, and delete my account, so that I can manage
and update my account information.
- The user must be able to log in and set a session
- The User must be able to navigate to their settings page to update or delete their account
- The User must be able to select if they are a general user (default) or an administrator when
creating their account

Story 2: As an administrator, I would like to create a User and view all existing Users in the application, so that I can help users create accounts and view users' information for customer services.
- The user must be able to log in and set a session
- The administrator must be able to navigate to an administrator page that shows all users
- Administrator must be able to search for another user based on their username or email
  
Story 3: As an administrator, I would like to be able to update or delete user accounts, and delete Tuits, so that I can help users manage their accounts for customer services.
- The user must be able to log in and set a session
- The administrator must be able to navigate to the general User’s profile page and update the user’s information or delete the user's account
  
Story 4: As a User, I would like to bookmark/unbookmark the Tuits, and view all the Tuits that I have bookmarked, so that I can save these tuits later for writing a clever response.
- The user must be able to log in and set a session
- User must be able to bookmark and un-bookmark Tuits
- Navigate to the Bookmark screen to see bookmarked Tuits

## High-Level Architecture

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/architecture.png?raw=true)

## Demo

This would be the version1 that focuses more on making sure the backend implementation runs smoothly then I'll release another version with the frontend looking better :)
Also shows the MongoDB database as well

#### Initial tuits

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/initial%20tuits.png?raw=true)

#### Login

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/login.png?raw=true)

#### Profile

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/profile.png?raw=true)

#### New Tuits

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/newTuits.png?raw=true)

#### New Tuits MongoDB

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/newTuitsBackend.png?raw=true)

#### Admin Vs Normal User

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/adminVSnormal.png?raw=true)

#### Admin User Screen

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/AdminUserScreen.png?raw=true)

#### Admin Tuit screen

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/AdminTuitScreen.png?raw=true)

#### Future UI 

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/futureUI.png?raw=true)

#### Future UI..

![alt text](https://github.com/Abdulzy/TwitterClone/blob/main/Images/futureUI2.png?raw=true)





## Code Repository

[Frontend](https://github.com/Abdulzy/Team-2-Frontend)

[Backend](https://github.com/Abdulzy/Team-2-Backend)






