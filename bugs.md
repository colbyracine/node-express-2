1.) app.js general error handler - added procedure to check if environment was in test and if so console.log

2.) function authUser in auth.js in middleware decodes the jwt token to verify instead of utilizing jwt.verify

3.)delet doesn't confirm if admin - allows anyone to delet a user 

4.)
