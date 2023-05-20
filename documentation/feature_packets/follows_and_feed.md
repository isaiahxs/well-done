## Follows and Feed

### Models needed:
- Users
- Stories
- Follows

### Endpoints needed:

**Follow another user**
- Method: POST
- URL: /api/users/:userId/follow
- Body: [Provide the necessary parameters here]

**Unfollow another user**
- Method: DELETE
- URL: /api/users/:userId/follow
- Body: none

**Get feed**
- Method: GET
- URL: /api/feed
- Body: none

### Components needed:

**FollowButton:**
- A component that allows the user to follow or unfollow another user. This component would display the follow status and provide interactivity to follow or unfollow.

**Feed:**
- A component that displays the feed of stories from the authors the logged-in user follows. This component would render the list of stories in the feed.

### Wireframes or sketches:

[Include any wireframes or sketches relevant to the Follows and Feed feature]
