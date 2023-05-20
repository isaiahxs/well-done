## Commenting on Stories

### Models needed:
- Stories
- Comments
- Claps (users can clap a comment)

### Endpoints needed:

**Get all Comments of the Current User**
- Method: GET
- URL: /api/reviews/current
- Body: none

**Get all Comments by a Story's ID**
- Method: GET
- URL: /api/story/:storyId
- IMPORTANT TO NOTE: that URL doesn't change since the comments are a modal that come from the right side of the page
- Body: none

**Create a comment for a Story based on the Story's id**
- Method: POST
- URL: /api/story/:storyId/comments
- Body: [Provide the necessary parameters here]

**Edit a comment**
- Method: PUT
- URL: /api/comments/:commentId
- Body: [Provide the necessary parameters here]

**Delete a comment**
- Method: DELETE
- URL: /api/comment/:commentId
- Body: none

### Components needed:

**StoryDetailPage:**
- Renders the page that shows the details of a specific story, including the story content, comments, claps, and related stories.

**[Maybe a CommentsPage]**

### Wireframes or sketches:
[Include any wireframes or sketches relevant to the Commenting on Stories feature]
