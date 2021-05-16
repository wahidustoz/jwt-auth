1. Make a simple WebAPI
2. Make a User model
3. Make a AuthorizationController
User() - POST - create a new user
User(id) - to get single user - Authorize(user)- GET
Users() - get all users - Authorize(superadmin) - GET
User() - edit user - PATCh - authorize

> IN JWT service class, the secret is just given as a string. BUt u have to change that, and find out a way to read that secret key from Configuration like we did in Startup.cs.
