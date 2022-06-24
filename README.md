# LAB - Class 07

## Project: Bearer Authorization (Take Two)

### Author: Katharine Swilley

### Problem Domain

Authentication Server Phase 2: Token (Bearer) Authentication

At this point, our auth-server is able to allow a user to create an account as well as to handle Basic Authentication (user provides a username + password). When a “good” login happens, the user is considered to be “authenticated” and our auth-server generates a JWT signed “Token” which is returned to the application

We will now be using that Token to re-authenticate users to shield access to any route that requires a valid login to access.

### Links and Resources

- [ci/cd (GitHub Actions)](https://github.com/kath-a-rine/bearer-auth-take-two/actions)

### Setup

#### `.env` requirements (where applicable)

`PORT` - 3001
SECRET = 'TEST_SECRET'


#### How to initialize/run your application (where applicable)

- nodemon

#### How to use your library (where applicable)

#### Features / Routes

- `/signup`
- `/signin`
- `/routes`
-`/secret`

#### Tests

- Run tests using `npm test`
