# Example Redux State

```javascript
{
   users: {
      1: {
         user_id: 1,
         first_name: "John",
         last_name: "Doe",
         username: "johndoe",
         email: "johndoe@example.com",
         hashword: "********",
         created_at: "2023-05-20T10:00:00Z",
         updated_at: "2023-05-20T15:30:00Z"
      },
      2: {
         user_id: 2,
         first_name: "Jane",
         last_name: "Smith",
         username: "janesmith",
         email: "janesmith@example.com",
         hashword: "********",
         created_at: "2023-05-21T09:30:00Z",
         updated_at: "2023-05-21T11:45:00Z"
      },
      3: {
         user_id: 3,
         first_name: "Mike",
         last_name: "Johnson",
         username: "mikejohnson",
         email: "mikejohnson@example.com",
         hashword: "********",
         created_at: "2023-05-22T14:20:00Z",
         updated_at: "2023-05-22T16:10:00Z"
      }
   },
   stories: {
      1: {
         story_id: 1,
         title: "My Story",
         content: "Lorem ipsum dolor sit amet, consectetur adipiscing elit.",
         author_id: 1,
         created_at: "2023-05-20T11:00:00Z",
         updated_at: "2023-05-20T12:30:00Z"
      }
   },
   comments: {
      1: {
         comment_id: 1,
         content: "Great story!",
         user_id: 1,
         story_id: 1,
         created_at: "2023-05-20T11:30:00Z",
         updated_at: "2023-05-20T11:30:00Z"
      }
   },
   claps: {
      1: {
         clap_id: 1,
         user_id: 1,
         story_id: 1,
         created_at: "2023-05-20T12:00:00Z",
         updated_at: "2023-05-20T12:00:00Z"
      },
      2: {
         clap_id: 2,
         user_id: 2,
         story_id: 1,
         created_at: "2023-05-21T10:30:00Z",
         updated_at: "2023-05-21T10:30:00Z"
      },
      3: {
         clap_id: 3,
         user_id: 3,
         story_id: 1,
         created_at: "2023-05-22T15:00:00Z",
         updated_at: "2023-05-22T15:00:00Z"
      }
   },
   followers: {
      1: {
         follower_id: 1,
         author_id: 1
      },
      2: {
         follower_id: 2,
         author_id: 1
      },
      3: {
         follower_id: 3,
         author_id: 2
      }
   }
}

```
