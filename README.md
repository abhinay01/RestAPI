# RestAPI
RestAPI

A Rest Application for serving data from store.json.

#### How it works
This application is hosted on heroku <br>
https://restapi-abhinay.herokuapp.com

Any change in the this project will autometically trigger it's deployment on heroku.
Upon succesful build, you can access the application using the above link.

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
