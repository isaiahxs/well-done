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
         content: "
                    In the small town of Meadowville, there lived an ordinary
                    young man named John Doe, whose unwavering determination and
                    belief in himself fueled his journey towards success. Despite
                    financial hardships, he embraced his passion for writing,
                    honed his talent through hard work, and caught the attention
                    of a renowned author who became his mentor. With resilience
                    and a gift for storytelling, John's words captivated the
                    world, inspiring countless individuals to overcome their own
                    obstacles and chase their dreams. Today, he stands not just as
                    a celebrated author but as a symbol of triumph against all
                    odds, reminding us that extraordinary stories can emerge from
                    the most ordinary beginnings.",
         author_id: 1,
         created_at: "2023-05-20T11:00:00Z",
         updated_at: "2023-05-20T12:30:00Z"
      }
        2: {
         story_id: 2,
         title: "Her Story",
         content: "In the depths of the old, abandoned mansion, a chilling
                        presence lingered, feeding off the fears of unsuspecting
                        souls who dared to step inside. Whispers echoed through
                        the hallways, carrying tales of unspeakable horrors and
                        the tortured spirits trapped within its walls. Each
                        creaking floorboard sent shivers down the spines of those
                        who entered, their hearts pounding with an unrelenting
                        sense of dread. Shadows danced menacingly, as if alive,
                        while eerie whispers grew louder, suffocating the air with
                        a malevolent force. No one could escape the clutches of
                        this house of nightmares, as it hungered for souls to add
                        to its twisted collection, forever bound to a realm of
                        eternal darkness.",
         author_id: 2,
         created_at: "2023-06-20T11:00:00Z",
         updated_at: "2023-06-20T12:30:00Z"
      }
        3: {
         story_id: 3,
         title: "His Story",
         content: "
                        In the bustling city of Serendipity, fate brought together two
                        souls, Lucy and James, who found themselves in a
                        delightful whirlwind of a romantic comedy. With a
                        significant age gap between them, their initial encounters
                        were marked by amusing miscommunications and charming
                        moments of awkwardness. With their hearts entwined, Lucy
                        and James discovered that age was merely a number, and
                        that true love could be found in the most unexpected
                        places.
                        ",
         author_id: 3,
         created_at: "2023-07-20T11:00:00Z",
         updated_at: "2023-07-20T12:30:00Z"
      }
   },
   comments: {
      1: {
         comment_id: 1,
         content: "Great story!",
         user_id: 2,
         story_id: 1,
         created_at: "2023-05-20T11:30:00Z",
         updated_at: "2023-05-20T11:30:00Z"
      }
   },
   claps: {
      1: {
         clap_id: 1,
         user_id: 1,
         story_id: 2,
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
         story_id: 2,
         created_at: "2023-05-22T15:00:00Z",
         updated_at: "2023-05-22T15:00:00Z"
      },
         4: {
         clap_id: 3,
         user_id: 3,
         story_id: 2,
         created_at: "2023-05-22T15:00:00Z",
         updated_at: "2023-05-22T15:00:00Z"
      }
   },
   followers: {
      1: {
         follower_id: 1,
         author_id: 2
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
