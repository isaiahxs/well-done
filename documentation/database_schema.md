 # **Database Schema**

![db schema medium clone](https://github.com/isaiahxs/well-done/assets/106289871/759a11d7-a2b1-4eca-b81f-0038f84d67f8)

## `users`

| column name | data type | details                   |
|-------------|-----------|---------------------------|
| userId     | integer   | not null, primary key     |
| first_name  | string    | not null                 |
| last_name   | string    | not null                 |
| username    | string    | not null, unique                |
| email       | string    | not null, unique |
| created_at  | datetime  | not null                  |
| updated-at  | datetime  | not null                  |

## `stories`

| column name | data type | details               |
|-------------|-----------|-----------------------|
| storyId     | integer   | not null, primary key |
| content     | string    | not null              |
| authorId    | integer   | not null, foreign key |
| created_at  | datetime  | not null              |
| updated-at  | datetime  | not null              |

* `authorId` references `users` table

## `comments`

| column name   | data type | details               |
|---------------|-----------|-----------------------|
| commentId     | integer   | not null, primary key |
| content       | string    | not null              |
| userId        | integer   | not null, foreign key |
| storyId       | integer   | not null, foreign key |
| created_at    | datetime  | not null              |
| updated-at    | datetime  | not null              |

* `userId` references `users` table
* `storyId` references `story` table

## `fauxlikes`

| column name   | data type | details                        |
|---------------|-----------|--------------------------------|
| clapId        | integer   | not null, primary key          |
| userId        | integer   | not null,  foreign key         |
| storyId       | integer   | not null, foreign key          |
| fauxTweetId   | integer   | indexed, foreign key           |
| fauxCommentId | integer   | indexed, foreign key           |

* `userId` references `users` table
* `storyId` references `stories` table
* `commentId` references `comments` table
