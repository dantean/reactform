# reactform 

## concept
An interactive form that submits data to a repository, which can then be viewed in a separate dynamic page

## potential features
 - separate frontend UI and backend UI
 - self-service user account creation and login
    - self-service account deletion
    - editable profile details
    - polyjuice feature
    - Frontend UI: Users can only create an account with an invitation code or a link that contains an invitation code in the URL
    - users can request an account, which will send an approval notification to a designated administrator
    - if admin approves account, an account is created in the database for the user, and a temporary password is generted and sent to the user along with a link to access their account profile and set a new password. if admin declines, an email is generated and sent that informs the user that their account request has been denied
 - backend UI: user management features
 - backend UI: admin approves submission: submission is added to a dynamic list on a public page, formatted in markdown
 - backend UI: admin declines submission: submission is categorized in a separate list only viewable to Admins, but is not deleted
 - pages: SIMPLE SUBMISSION FORM, LOGIN/ACCOUNT REQUEST PAGE, ACCOUNT CREATION PAGE, USER PROFILE, APPROVED LIST, 

## MVP Requirements
 - interactive web form that submits text to an external database

