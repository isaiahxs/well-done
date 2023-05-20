## User-facing routes for Medium

### "/login"

Log in page

This page displays a log in form.

- **GET /login**
- **POST /login**

### "/signup"

Sign up page

This page displays a signup form.

- **GET /signup**
- **POST /signup**

### "/"

Home page

This page displays the ten most recent stories on Medium and their claps (likes), as well as a navigation bar with login/signup or logout buttons. Each story has an "edit" and "delete" button if it belongs to the currently logged-in user. Logged-in users can clap stories on this page.

- **GET /**
- **POST /stories/:id/claps**
- **DELETE /stories/:id/claps**

### "/stories"

Story creation page

This page displays a form with which a logged-in user can create a new story, as well as a navigation bar with login/signup or logout buttons.

- **POST /stories**

### "/stories/:id"

Story page

This page displays an individual story with associated comments and claps, as well as a navigation bar with login/signup or logout buttons. If the logged-in user is the author of the story, this page also displays an "edit" and "delete" button. Logged-in users can clap the story and its comments, as well as post comments. The author of those comments can update or delete them.

- **GET /stories/:id**
- **POST /stories/:id/claps** (IF USER IS NOT AUTHOR)
- **PUT /stories/:id** (IF USER IS AUTHOR)
- **DELETE /stories/:id** (IF USER IS AUTHOR)
- **DELETE /stories/:id/claps** (IF USER IS NOT AUTHOR)
- **POST /stories/:id/comments** (IF USER IS NOT AUTHOR)
- **DELETE /stories/:id/comments** (IF USER IS NOT AUTHOR)
