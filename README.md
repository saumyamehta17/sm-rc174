Railscast sm-rc174
===================

Pagination with ajax
```
page is not loading as ajax is used for pagination
```
Clone
```
git clone
```
pagination.js
```
javascript file named pagination.js is included in index.html.erb, so that we can perform ajaxify
```
use $.get()
```
To load data from server
parameters are url to which send request, data to pass ,function to run if success,dataType in which to get response
For this time script dataType is used so that response to run in javascript
```
Use live() or on()
```
To run one or  more event handler for select element. live() is depricted so use on
```
Index.js.erb
```
To respond ajax
```
Rails server
```
rails s
```
