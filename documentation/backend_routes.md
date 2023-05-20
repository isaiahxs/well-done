# API-Routes
This web app uses the following API routes to dynamically update the page to create a single-page-app-like feel for the user for specific features.

## Account creation feature (sign up, log in, demo log in, sign out)

### Endpoints needed:

#### Get the Current User

- Method: GET
- URL: `/api/session`
- Body: none

#### Log In a User

- Method: POST
- URL: `/api/session`
- Body: [Provide the necessary parameters here]

#### Sign Up a User

- Method: POST
- URL: `/api/users`
- Body: [Provide the necessary parameters here]

## Stories (CRUD features, and viewing feed)

### Endpoints needed:

#### Get all Stories

- Method: GET
- URL: `/api/stories`
- Body: none

#### Get all Stories owned by the Current User

- Method: GET
- URL: `/api/stories/current`
- Body: none

## Commenting on Stories

### Endpoints needed:

#### Get all Comments of the Current User

- Method: GET
- URL: `/api/comments/current`
- Body: none

#### Get all Comments by a Story's ID

- Method: GET
- URL: `/api/story/:storyId`
- IMPORTANT TO NOTE: that URL doesn't change since the comments are a modal that come from the right side of the page
- Body: none

#### Create a comment for a Story based on the Story's ID

- Method: POST
- URL: `/api/story/:storyId/comments`
- Body: [Provide the necessary parameters here]

#### Edit a comment

- Method: PUT
- URL: `/api/comments/:commentId`
- Body: [Provide the necessary parameters here]

#### Delete a comment

- Method: DELETE
- URL: `/api/comment/:commentId`
- Body: none

## Clapping Stories

### Endpoints needed:

#### Post a clap

- Method: POST
- URL: `/api/stories/:storyId/claps`
- Body: [Provide the necessary parameters here]

#### Delete a clap

- Method: DELETE
- URL: `/api/stories/:storyId/claps/:clapId`
- Body: none

## Follows and Feed

### Endpoints needed:

#### Follow another user

- Method: POST
- URL: `/api/users/:userId/follow`
- Body: [Provide the necessary parameters here]

#### Unfollow another user

- Method: DELETE
- URL: `/api/users/:userId/follow`
- Body: none

#### Get feed

- Method: GET
- URL: `/api/feed`
- Body: none
