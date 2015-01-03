# ionicNgMessagesExample

Simple example of how to use ngMessages directive with Ionic framework v1.0.0-beta.14 which uses Angular 1.3.6


These were the steps I took to create this example

1. `ionic start ionicNgMessagesExample sidemenu`

2. `cd ionicNgMessagesExample`

3. `bower install angular-messages#1.3.6 --save`

4. Add `<script src="lib/angular-messages/angular-messages.min.js"></script>` to www/index.html

5. Inject ngMessages into www/js/app.js `angular.module('starter', ['ionic', 'starter.controllers','ngMessages'])`

6. Create www/templates/error-messages.html with default messages that can be included from across the app.
You can override any one of these at the field level if you needed to.

7. Modify www/templates/login.html to include ng-messages and name attributes for the HTML <form> and <input> tags.


## References
* I followed the blog post at [http://www.yearofmoo.com/2014/05/how-to-use-ngmessages-in-angularjs.html](http://www.yearofmoo.com/2014/05/how-to-use-ngmessages-in-angularjs.html).

* You should also watch [https://egghead.io/lessons/angularjs-introduction-to-ng-messages-for-angularjs](https://egghead.io/lessons/angularjs-introduction-to-ng-messages-for-angularjs)

* You can also read this example [http://calendee.com/2014/12/26/validation-in-ionic-framework-apps-with-ngmessages/](http://calendee.com/2014/12/26/validation-in-ionic-framework-apps-with-ngmessages/)
