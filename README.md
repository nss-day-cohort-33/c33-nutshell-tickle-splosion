# Nutshell: The Information Dashboard

## Intro
Nutshell is a vanilla js dashboard displaying users with events, articles, tasks, messages and friends they are interested in. This app uses Webpack bundler to run http and json servers with npm.

## Install
1. Clone this repository
1. Make a branch
1. npm install
1. npm start

In your browser, visit 'localhost:8080'

## Register / Login
Once in at the welcome screen, create a new user or login as an existing user





<!-- Nutshell is a new product offering that you have been tasked with building. It's a dashboard for people to use to organize their daily tasks, events, news article, friends, and chat messages.

You will be utilizing all of the skills and concepts that you've learned up to this point in the course.

1. Functions
2. Databases/API
3. Github
4. Objects
5. CSS
6. Handling user events
7. Factory functions
8. Data entry/editing
9. Modular code with Browserify
10. Relational data

To start you off, here's an example of what the resources in your API should look like once it's populated with some data from your application.

### Users

```json
{ "id": 1, "username": "Steve", "email": "me@me.com" }
```

### Messages

```json
{ "id": 1, "userId": 1, "message": "What's up?" }
```

### News

```json
{
    "id": 1,
    "userId": 2,
    "url": "https://www.quantamagazine.org/newfound-wormhole-allows-information-to-escape-black-holes-20171023/",
    "title": "Wormholes Allow Information to Escape Black Holes",
    "synopsis": "Check out this recent discovery about workholes"
}
```

### Friends

```json
{ "connectionId": 1, "userId": 1, "otherFriendId": 3 }
```

### Tasks

```json
{ "id": 1, "userId": 3, "task": "Take out garbage" }
```

## Professional Requirements

1. All teammates must be using Grunt to run ESLint and Browserify during development
1. Each module should have a comment at the top with the following info: author(s) and purpose of module
1. The README for your project should include instructions on how another person can download and run the application

## How to Handle Authentication

You will be using session storage to keep track of which user has logged into Nutshell. When the user fills out the registration form, you will POST their username and password to the `users` collection in your API. You will then immediately take the `id` of the object in the response and save it to session storage.

```js
sessionStorage.setItem("activeUser", user.id)
```

If you want to add a Logout feature, all you need to do it remove the session storage item.

```js
sessionStorage.removeItem("activeUser")
```

## Visual Feature List

To help you along, here is a visualization of the features, and behaviors of the application to get you started.

![nutshell features](./Nutshell.png) -->
