## PREREQUISITES
- Requirements: I want a journal.
- User Stories:
  * So that I can keep a personal record, I need to be able to sign in
  * So that I can sign in, I need to be able to register my information
  * So that I can record my data I need to be able to write somewhere.
  * I need to be able to review my records in chronological order
  * need to be able to see the date, and the date needs to be recorded for each of my records
  * I need to be able to edit records
  * I need to be able to add a title to my records
  * I need to be able to delete my record

## MV1
- Landing Page where users can visit, which contains a register/sign in
- Login page or modal where the user can input their information, and it can be verified
- Signup page or modal where the new user could input their information, and create a new account
- Landing page for registered users, where they can see all their records, and edit them from within the same page.
- Failure mechanism for when wrong data is put in (Probably just have it display red letters at the bottom)
- Modal or page for creating a new records
- Modal or page for updating a record
- button within the registered user landing page to be able to delete records.
- Database to be able to maintain all the records as well as user information


## DESIGN
- Technology Selection: HTML, CSS, VANILLA JS, NON-RELATIONAL DB (MONGO DB)
- Specifications:
  * Where do users go when they complete a record?: They'll be taken to the user dashboard
  * What will happen when users input the wrong data for login/signup?: They'll get a sign at the bottom or top (depending where it makes the most sense) that tells them what they did wrong
