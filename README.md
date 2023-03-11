# router-level-middleware
To do so, you will be building a middleware function and placing it in the right place in the pipeline.

Create middleware
The validateNameLength() function should assess the length of the name route parameter. Then:

If the name is three characters or longer, move on to the next step of the middleware pipeline.

If the name is less than three characters long, trigger the error-handling middleware function with the following message:

"Name length is too short."
