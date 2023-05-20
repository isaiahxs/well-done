## Users

### Sign Up

As an unregistered and unauthorized user, I want to be able to sign up for the website via a sign-up form.

**Scenario:**

- When I'm on the `/signup` page:
  - I would like to enter my email, username, and password on a clearly laid out form.
  - I expect the website to log me in upon successful completion of the sign-up form so that I can seamlessly access the site's functionality.

**Error Handling:**

- When I enter invalid data on the sign-up form:
  - I would like the website to inform me of the specific validations I failed to pass and repopulate the form with my valid entries (except my password).
  - I should be able to try again without needing to refill forms I entered valid data into.

### Log In

As a registered and unauthorized user, I want to be able to log in to the website via a log-in form.

**Scenario:**

- When I'm on the `/login` page:
  - I would like to enter my email and password on a clearly laid out form.
  - I expect the website to log me in upon successful completion of the log-in form.
- So that I can seamlessly access the site's functionality.

**Error Handling:**

- When I enter invalid data on the log-in form:
  - I would like the website to inform me of the validations I failed to pass and repopulate the form with my valid entries (except my password).
  - I should be able to try again without needing to refill forms I entered valid data into.

## Demo User

As an unregistered and unauthorized user, I would like an easy-to-find and clear button on both the /signup and /login pages to allow me to visit the site as a guest without signing up or logging in.

**Scenario:**

- When I'm on either the /signup or /login pages:
  - I can click on a Demo User button to log me in and grant me access as a normal user.
- So that I can test the site's features and functionality without needing to stop and enter credentials.

## Log Out

As a logged-in user, I want to log out via an easy-to-find log out button on the navigation bar.

**Scenario:**

- While on any page of the site:
  - I can log out of my account and be redirected to a page displaying recent stories.
- So that I can easily log out to keep my information secure.

## Stories

### Create Story

As a logged-in user, I want to be able to create and publish a new story.

**Scenario:**

- When I'm on the create story page:
  - I would like to enter the title and content of my story in clearly labeled input fields.
  - I expect to be able to publish my story by clicking a "Publish" button.
- So that I can share my thoughts and ideas with others.

### Edit Story

As a logged-in user, I want to be able to edit and update my own stories.

**Scenario:**

- When I'm viewing one of my stories:
  - I would like to see an "Edit" button that allows me to modify the title and content of the story.
  - I expect to be able to save my changes by clicking an "Update" button.
- So that I can refine and improve my story over time.

### Delete Story

As a logged-in user, I want to be able to delete my own stories.

**Scenario:**

- When I'm viewing one of my stories:
  - I would like to see a "Delete" button that allows me to remove the story from the platform.
  - I expect to be prompted for confirmation before permanently deleting the story.
- So that I can remove any content that I no longer want to be available.

## Commenting on Stories

### Post Comment

As a logged-in user, I want to be able to post comments on stories.

**Scenario:**

- When I'm viewing a story:
  - I would like to see an input field where I can enter my comment.
  - I expect to be able to submit my comment by clicking a "Post" button.
- So that I can engage in discussions and share my thoughts on the story.

### Edit Comment

As a logged-in user, I want to be able to edit my own comments on stories.

**Scenario:**

- When I'm viewing a story and see one of my comments:
  - I would like to see an "Edit" button that allows me to modify the content of my comment.
  - I expect to be able to save my changes by clicking an "Update" button.
- So that I can correct any mistakes or clarify my comment.

### Delete Comment

As a logged-in user, I want to be able to delete my own comments on stories.

**Scenario:**

- When I'm viewing a story and see one of my comments:
  - I would like to see a "Delete" button that allows me to remove the comment.
  - I expect to be prompted for confirmation before permanently deleting the comment.
- So that I can remove any comments that I no longer want to be associated with the story.

## Leaving Claps on Stories

### Clap Story

As a logged-in user, I want to be able to give a clap to stories that I appreciate or enjoy.

**Scenario:**

- When I'm viewing a story:
  - I would like to see a "Clap" button that allows me to indicate my appreciation for the content.
  - I expect the number of claps to be updated accordingly.
- So that I can show support and acknowledgement to the author.

### Unclap Story

As a logged-in user, I want to be able to remove my clap from a story.

**Scenario:**

- When I'm viewing a story that I have previously clapped:
  - I would like to see an "Unclap" button that allows me to remove my clap.
  - I expect the number of claps to be updated accordingly.
- So that I can adjust my engagement with the story.

## Follows and Feed

### Follow User

As a logged-in user, I want to be able to follow other users.

**Scenario:**

- When I'm viewing a user's profile:
  - I would like to see a "Follow" button that allows me to follow the user.
  - I expect to receive updates from the user's stories in my feed.
- So that I can stay connected with and receive updates from authors I'm interested in.

### View Feed

As a logged-in user, I want to be able to see a feed of stories from the authors I follow.

**Scenario:**

- When I'm on my dashboard or feed page:
  - I would like to see a personalized feed displaying the latest stories from the authors I follow.
  - I expect to have an option to filter or sort the feed based on different criteria.
- So that I can easily access and read stories from the authors I'm interested in.
