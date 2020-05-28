# YelpCamp

> A Node.js web application project that I've done while on Udemy's Web Development course - [The Web Developer Bootcamp](https://www.udemy.com/the-web-developer-bootcamp/)

## Demo

To see the app in action, go to [Ivan's YelpCamp Demo](https://shielded-mesa-04544.herokuapp.com/)

## Features

* Implemented Authentication:
  
  - User login with username and password

* Authorization:

  - Unable to create campgrounds without being logged in

  - Unable to edit campground posts or comments that do not belong to you

* Managing of campground posts

  - Create, edit and delete campgrounds and its associated comments

* Flash messages responding to users' interaction with the app

  - (e.g.) Success messages after logging in, error when accessing invalid campgrounds

## Built with

### Front-end

* [ejs](http://ejs.co/)
* [Bootstrap](https://getbootstrap.com)

### Back-end

* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [passport](http://www.passportjs.org/)
* [passport-local](https://github.com/jaredhanson/passport-local#passport-local)
* [express-session](https://github.com/expressjs/session#express-session)
* [method-override](https://github.com/expressjs/method-override#method-override)
* [connect-flash](https://github.com/jaredhanson/connect-flash#connect-flash)

### Platforms

* [Heroku](https://www.heroku.com/)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
