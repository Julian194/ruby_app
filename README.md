# Twitter clone in Ruby on Rails 

 - Built following the tutorial by **Michael Hartl**
 - Learnings included project setup for a RoR application
 - Database migrations  
 - Image upload to AWS S3 storage 
 - Domain modelling including relationships  
 - Including smooth page transitions 
 - Authentication system 
 - Creating micro-posts and following other users 
 - Email handling 
 - Live demo at [https://infinite-taiga-93800.herokuapp.com](https://infinite-taiga-93800.herokuapp.com/)

## Getting started

To get started with the app, clone the repo and then install the needed gems:
```
$ bundle install --without production
```
Next, migrate the database:
```
$ rails db:migrate
```
Finally, run the test suite to verify that everything is working correctly:
```
$ rails test
```
If the test suite passes, you'll be ready to run the app in a local server:
```
$ rails server
```

