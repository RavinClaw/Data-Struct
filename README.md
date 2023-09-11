# Data Struct
### A Development Operating System with all features
[Root Account](#root-account)\
[Other User Accounts](#other-users)\
[Common Questions](#common-questions)

## Root Account
#### The Root Account is the back bone for the whole system

##### The default root account is responsible for everything, it controls everything. this account cannot be accessed for privacy reasons

- Ways around the no password rule for root,\
the directory: `./storage/auth/auth.json` can be modified: `"password": null` --to-> `"password": "your-password"`.

- Root account permission,\
the root account permission looks like this: `root`, for example: `"owners": ["root"]`, by default root will always be on the `"owners"` section.

## Other Users
#### The Other users are the users of the pc

##### The creation of accounts will cause the file to update, these accounts can only be accessed after the pc restarts, due to the system only checking the file once per session



## Common Questions
#### The questions asked the most

- [Q] How to change password?\
[A] their are two ways to do this using the command `$user --change-password {password}` or it can be changed through the file `./storage/auth/auth.json`, through the `"password"`

- [Q] How to update?\
[A] updating is simple just use the command `!update&latest` or go to [Click Here](https://github.com/RavinClaw/Data-Struct)
