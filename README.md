# README
# Database (DB)
## ERD (Entity Relationship Diagram)
![erd database](/docs/images/erd.png)

# DB Tables
I made 3 tables for my app, User, Tweet and Porifle. User stores the user information like password etc. Tweet stores the information message that a user tweets ad the Profile table stores information about the user. Each user has one profile and many Tweets.

## User
- email 
- password 

## Profile
- avatar 
- first_name 
- last_name 
- country 
- user_id (belongs_to)

## Tweet
- message
- user_id (belongs_to)  


## Pages
# Homepage
- show tweets on page
- log in/log out

# Tweet show page
- see tweet
- edit tweet (if logged in)


# Profile page
- first_name, last_name
- tweet count
- avatar
- edit ability
- About me
- Country