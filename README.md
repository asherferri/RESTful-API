# Resful API on plain Node.js
### What is your project?

I'm building an RESTful API for an uptime monitoring application, without using NPM modules, dependencies.
Only using Node modules.

UPTIME MONITOR: allows users to enter URLs they want monitored, and receive alerts when those resorces GO Down o COME BACK UP.

I'm gonna use plain NODE API, but for the SMS will use NODE to connect to TWILIO API, without using a 3rd party library.
I'm gonna craft an HTTP request, so i can interact with API's on plain node.

I will be writing to the filesystem instead of a DB.

In production should be good to click on a DB, now im jst gonna writ JSON to the filesystem.


## Requirements:

1. The API listens on a PORT and accepts incoming HTTP requests for POST, GET, PUT, DELETE, and HEAD.
2. The app allows to sign up, sign in, out, ediut settings
3. Alerts on SMS besides email.

4. The API listens on a PORT and accepts incoming HTTP requests for POST, GET, PUT, DELETE, and HEAD.
5. The API allows a client to connect, create, edit and delete that user.
6. The API allows user to sign in, gets a token for subsequent auth requests.
7. The API allows the user to sign out which invalidates their token.
8. The API allows a signed in user to use their token to create a new "check" a task for the system to check an URL if it's up or down. the user defines what UP or DOWN is (some websites up is 200 othe is anything not 500).
9. The API allows a signed in user to edit or delete checks. We want to limit their checks to 5.
10. In the background we want workers perform all the checks at thge right times, and send alerts to the users whjen a check changes its state,
from up to down or viceversa. 
    - we want checks to run 1 per minute. all the checks created by all users to run, see if they are up or down based on definition given by user, 
    and update the user based on state change up to down or down to up.



## Our App

### Wireframes!

![Wireframe](./resources/final_wireframe.png)

### User Stories

1. The API listens on a PORT and accepts incoming HTTP requests for POST, GET, PUT, DELETE, and HEAD.
  
### Database Schema

![DB_SCHMA](./resources/database_schema.png)

### 3rd Party Technologies

### Initial thoughts on app structure

### Phases of Completion

### Links and Resources
