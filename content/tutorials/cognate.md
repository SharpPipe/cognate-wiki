---
title: Cognate tutorials
---

> How to use Cognate. Replace with ambitious quote when appropriate.

# List of tutorials regarding how to accomplish specific tasks

## Add new teacher to a project
The following task has several subtasks.
### Add new user to project group.
- Enter group config view
- There should be
  - List of pending invitations (get all group invitations)
  - Textbox that needs an identifier and a button (invite user to group)
  - User needs to give his or her identifier willingly
### Check identifier for user
User needs to:
- Enter profile view (get profile)
- An identifier should be displayed there
### Accept invitation for user
User needs to:
- Enter profile view (get profile)
- There should be displayed a list of pending invitations (get user invitations)
- For each invitation user should have a button to either accept or refuse (accept request & decline request)

When a user declines an invitation, it will still be displayed under group invitations because if a user does not consent to it, then the owner of the project group should not have access to any information about the user (including whether or not he or she has declined the invitation)
### Manage roles for users in project group
Once a user accepts an invitation, he or she will be given a "Blank" role. Then the account will show up under group config view.
- There should be list of users with their associated roles in that group (get users in group)
- It should then be possible to give new roles to users or remove existing ones (add new role to user & remove role from user)
### Manage roles for users in project
- There should be a similar view in project manage view.
- There should be a list of users and their roles in the specific project (get users in project)
- As well as a list of possible new users, who currently have roles in the project group, where that project belongs to (get users in group)
- It should then be possible to give and remove roles from users (add user to project & remove user from project)
