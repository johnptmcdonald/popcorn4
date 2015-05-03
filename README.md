## Popcorn App

An angular on rails app that consumes the youtube API.

Rails version 4.2.0
Ruby version 2.1.2


-------------------

## Chapter 1
* Add `gem angularjs-rails` 
For this gem to work properly, we need to remove `gem turbolinks` and also remove the turbolinks references in the view. Add `//= require angular` to the application.js file.

* Add `gem bootstrap-sass`
Add `//= require bootstrap` to the application.js file, and `@import "bootstrap";` to application.scss

