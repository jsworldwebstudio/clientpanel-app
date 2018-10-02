# Clientpanel-App
This is an employee expense tracker app and can be tailored further for specific
client needs.

This app uses email/password authentication and also includes app level settings to:
Allow/Disallow Registration
Able/Disable Updating the Balance amount when adding a new employee
Able/Disable Updating the Balance amount when updating an employee's record

This app is written in React

## Application Features
This application uses:  
**Firebase:** For email authentication
**Firestore:** For storing client records
**React Router:** To access different pages of the app  
**Route Guards:** To block some pages from being seen if user not logged in.  
and block some pages from being viewed if flag is set for non-register (for a User)  
**Form Validation:** Not allow a form to be submitted unless all fields in correct format  
**Local Storage:** Add & retrieve an object of application level settings from local storage
**Bootstrap:** For App UI/Layout
