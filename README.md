# RestAPI
RestAPI

A Rest Application for serving data from store.json.

## How it works
#### Locally
To run locally please download the project and install json server from https://github.com/typicode/json-server.<br>
After successful setup,please open Postman and test all the supported method through it.

#### Cloud
This application is already hosted on heroku <br>
https://restapi-abhinay.herokuapp.com

Any change in this project will automatically trigger its deployment on heroku.
Upon successful build, you can access the application using the above link.

### Supported Method

    GET /posts
    GET /posts/0
    POST /posts
    PUT authors/1
    PATCH /posts/1
    DELETE /posts/1
    
• Filtering :

    GET /posts?title=title1&author=CIQ 
    
• Sorting :

    GET /posts?_sort=views&_order=asc
    
• Search:

    GET /posts?q=100

Note: To test above methods like post,put,delete and patch, you need a client like postman
