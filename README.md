# Tribehired - Adib Omar
---
## REST API 
This repository is used for Technical Assessment.
**Cache implemented on this project.**

### First Task
Return a list of Top Posts ordered by their number of comments.
**@route** *baseUrl*==/api/getTopPosts==
**@method** ==GET==

API used in this task:
> https://jsonplaceholder.typicode.com/comments
> https://jsonplaceholder.typicode.com/posts

**NOTE:**
One variable created to used as a flag to add a random number instead of 1 for total number of comments to make sure the sort is working. Any value can be passed in the *random* query parameter.
**URL Example:** http://tribehired.local/getTopPosts?random=1

### Second Task
Return a list of posts and comments based on filters.
You can pass **one or more filter** in one request.
**@route** *baseUrl*==/api/searchPost==
**@method** ==POST==

API used in this task:
> https://jsonplaceholder.typicode.com/comments
> https://jsonplaceholder.typicode.com/posts

**Available filters:**
| Post Name | Description | Example Value |
| ----------- | ----------- | ----------- | 
| post_id | This will filter based on post id that the comment have been attached to post id | 1 |
| id | This will filter based comment id | 1 |
| name | This will filter if character passed in the filter contains in the comment name | voluptas |
| email | This will filter based on email | Emmet@guy.biz |
| body | This will filter if character passed in the filter contains in the comment body | consequatur |
| post_title | This will filter if character passed in the filter contains in the post title | quasi |
| post_body | This will filter if character passed in the filter contains in the post body | sint |
